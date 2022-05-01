Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 7786

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6710b89c52](https://linux-hardware.org/?probe=6710b89c52) | Apr 30, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6b213d6f7e](https://linux-hardware.org/?probe=6b213d6f7e) | Apr 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [133b6e19a9](https://linux-hardware.org/?probe=133b6e19a9) | Apr 30, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ce42a9f877](https://linux-hardware.org/?probe=ce42a9f877) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | Desktop     | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [4af637024a](https://linux-hardware.org/?probe=4af637024a) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [3b8440b69f](https://linux-hardware.org/?probe=3b8440b69f) | Apr 29, 2022 |
| MSI           | MEG Z590 GODLIKE            | Desktop     | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | Desktop     | [ec7e5a0314](https://linux-hardware.org/?probe=ec7e5a0314) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | Desktop     | [db3540f085](https://linux-hardware.org/?probe=db3540f085) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | Desktop     | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [b8854e91ae](https://linux-hardware.org/?probe=b8854e91ae) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [1715307c13](https://linux-hardware.org/?probe=1715307c13) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| Sony          | VPCF120FL                   | Notebook    | [1636c68c92](https://linux-hardware.org/?probe=1636c68c92) | Apr 27, 2022 |
| Timi          | A35S                        | Notebook    | [8a3195e10c](https://linux-hardware.org/?probe=8a3195e10c) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4a7baada7f](https://linux-hardware.org/?probe=4a7baada7f) | Apr 27, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1a773927c4](https://linux-hardware.org/?probe=1a773927c4) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1243ca01bb](https://linux-hardware.org/?probe=1243ca01bb) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| ASUSTek       | Acacia                      | Desktop     | [d43c62d4ab](https://linux-hardware.org/?probe=d43c62d4ab) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [d23e7110f6](https://linux-hardware.org/?probe=d23e7110f6) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [3390e01a9c](https://linux-hardware.org/?probe=3390e01a9c) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [d060ed71c3](https://linux-hardware.org/?probe=d060ed71c3) | Apr 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| AZW           | U59                         | Desktop     | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | Desktop     | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | Desktop     | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| Lenovo        | IdeaPadFlex 5-1470 81C9     | Convertible | [038b7bda71](https://linux-hardware.org/?probe=038b7bda71) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [009a9c8ce0](https://linux-hardware.org/?probe=009a9c8ce0) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Dell          | 0KP561                      | Desktop     | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8104edaf22](https://linux-hardware.org/?probe=8104edaf22) | Apr 24, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [2e5a3b2158](https://linux-hardware.org/?probe=2e5a3b2158) | Apr 24, 2022 |
| Dell          | XPS 12-9Q33                 | Notebook    | [5cbe457f54](https://linux-hardware.org/?probe=5cbe457f54) | Apr 24, 2022 |
| ZOTAC         | ZBOXSD-ID12/ID13            | Mini pc     | [730b034ed7](https://linux-hardware.org/?probe=730b034ed7) | Apr 24, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [33a9b533e8](https://linux-hardware.org/?probe=33a9b533e8) | Apr 23, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [ffb0508bd2](https://linux-hardware.org/?probe=ffb0508bd2) | Apr 23, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | Desktop     | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4a76d57188](https://linux-hardware.org/?probe=4a76d57188) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ee546b53aa](https://linux-hardware.org/?probe=ee546b53aa) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [0ca0b999d6](https://linux-hardware.org/?probe=0ca0b999d6) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [2147b931e3](https://linux-hardware.org/?probe=2147b931e3) | Apr 22, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [891c8720c2](https://linux-hardware.org/?probe=891c8720c2) | Apr 22, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ceab75e03](https://linux-hardware.org/?probe=2ceab75e03) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [a1e3d6d19a](https://linux-hardware.org/?probe=a1e3d6d19a) | Apr 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| Dell          | 0KP561                      | Desktop     | [87398af452](https://linux-hardware.org/?probe=87398af452) | Apr 22, 2022 |
| Acer          | Predator G3610              | Desktop     | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [4c6e3f36dd](https://linux-hardware.org/?probe=4c6e3f36dd) | Apr 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [aa08ee444f](https://linux-hardware.org/?probe=aa08ee444f) | Apr 21, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [878d9753ef](https://linux-hardware.org/?probe=878d9753ef) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [676db10abf](https://linux-hardware.org/?probe=676db10abf) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bf030ccfa0](https://linux-hardware.org/?probe=bf030ccfa0) | Apr 21, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [9fc8be1cac](https://linux-hardware.org/?probe=9fc8be1cac) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [3b23a0c003](https://linux-hardware.org/?probe=3b23a0c003) | Apr 20, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [e3fcba68df](https://linux-hardware.org/?probe=e3fcba68df) | Apr 20, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [0ebad8c6f7](https://linux-hardware.org/?probe=0ebad8c6f7) | Apr 20, 2022 |
| Dell          | Latitude 5480               | Notebook    | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [790b162fa0](https://linux-hardware.org/?probe=790b162fa0) | Apr 20, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [9e2b287533](https://linux-hardware.org/?probe=9e2b287533) | Apr 20, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [2851261ddb](https://linux-hardware.org/?probe=2851261ddb) | Apr 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | GS60 2PE Ghost Pro          | Notebook    | [89a2ef83fd](https://linux-hardware.org/?probe=89a2ef83fd) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 6474WBN       | Notebook    | [8bac0a70d6](https://linux-hardware.org/?probe=8bac0a70d6) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 6474WBN       | Notebook    | [b7f4f882f3](https://linux-hardware.org/?probe=b7f4f882f3) | Apr 19, 2022 |
| Lenovo        | 3000 N100 076835U           | Notebook    | [31a5dc6cf6](https://linux-hardware.org/?probe=31a5dc6cf6) | Apr 19, 2022 |
| Lenovo        | ThinkPad T440p 20AWS03H0... | Notebook    | [0458ae6c71](https://linux-hardware.org/?probe=0458ae6c71) | Apr 19, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Timi          | A35S                        | Notebook    | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [a010271a3d](https://linux-hardware.org/?probe=a010271a3d) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [d6203110b3](https://linux-hardware.org/?probe=d6203110b3) | Apr 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [51a3d5d920](https://linux-hardware.org/?probe=51a3d5d920) | Apr 19, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [3ad8717f9a](https://linux-hardware.org/?probe=3ad8717f9a) | Apr 18, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [2cca37f312](https://linux-hardware.org/?probe=2cca37f312) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e9f6594677](https://linux-hardware.org/?probe=e9f6594677) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [d6b72a0160](https://linux-hardware.org/?probe=d6b72a0160) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| HP            | ProBook 4535s               | Notebook    | [23ab986b5e](https://linux-hardware.org/?probe=23ab986b5e) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [c9e6f401ab](https://linux-hardware.org/?probe=c9e6f401ab) | Apr 18, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [c7f2c2e71c](https://linux-hardware.org/?probe=c7f2c2e71c) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [c661d7a105](https://linux-hardware.org/?probe=c661d7a105) | Apr 18, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [b1ea72b76e](https://linux-hardware.org/?probe=b1ea72b76e) | Apr 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [bd010335eb](https://linux-hardware.org/?probe=bd010335eb) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Lenovo        | 3714 NOK                    | Desktop     | [80ed454cc3](https://linux-hardware.org/?probe=80ed454cc3) | Apr 17, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [abdd8db787](https://linux-hardware.org/?probe=abdd8db787) | Apr 17, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [278ccbaf44](https://linux-hardware.org/?probe=278ccbaf44) | Apr 17, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [49f90b075b](https://linux-hardware.org/?probe=49f90b075b) | Apr 17, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [1fef674c68](https://linux-hardware.org/?probe=1fef674c68) | Apr 17, 2022 |
| MSI           | MS-7438 100                 | Desktop     | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a37c8a7b48](https://linux-hardware.org/?probe=a37c8a7b48) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0d918922ac](https://linux-hardware.org/?probe=0d918922ac) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | Notebook    | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | Notebook    | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Lenovo        | ThinkPad X230 2325YGM       | Notebook    | [3606442649](https://linux-hardware.org/?probe=3606442649) | Apr 16, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [b39b237ff0](https://linux-hardware.org/?probe=b39b237ff0) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| Lenovo        | ThinkPad L440 20ASA02800    | Notebook    | [697a90ffa2](https://linux-hardware.org/?probe=697a90ffa2) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [144971e364](https://linux-hardware.org/?probe=144971e364) | Apr 16, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e29970db9c](https://linux-hardware.org/?probe=e29970db9c) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS03H0... | Notebook    | [64fb4146d0](https://linux-hardware.org/?probe=64fb4146d0) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [48e04dd798](https://linux-hardware.org/?probe=48e04dd798) | Apr 15, 2022 |
| Samsung       | 930QDB                      | Convertible | [e04b517cae](https://linux-hardware.org/?probe=e04b517cae) | Apr 15, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [1488e2a91f](https://linux-hardware.org/?probe=1488e2a91f) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [0d1712dd76](https://linux-hardware.org/?probe=0d1712dd76) | Apr 14, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [13bfd82a49](https://linux-hardware.org/?probe=13bfd82a49) | Apr 14, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [c8afb3fce8](https://linux-hardware.org/?probe=c8afb3fce8) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8b693a6221](https://linux-hardware.org/?probe=8b693a6221) | Apr 14, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [819cf0afbc](https://linux-hardware.org/?probe=819cf0afbc) | Apr 14, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [893e3f4940](https://linux-hardware.org/?probe=893e3f4940) | Apr 14, 2022 |
| TUXEDO        | PA70ES                      | Notebook    | [aa3ae14c59](https://linux-hardware.org/?probe=aa3ae14c59) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [154eb4b040](https://linux-hardware.org/?probe=154eb4b040) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [2550bb5cd7](https://linux-hardware.org/?probe=2550bb5cd7) | Apr 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [41b0487e91](https://linux-hardware.org/?probe=41b0487e91) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASRock        | AB350M                      | Desktop     | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | Notebook    | [4035ec75ce](https://linux-hardware.org/?probe=4035ec75ce) | Apr 14, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [aada4d4d5e](https://linux-hardware.org/?probe=aada4d4d5e) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | Notebook    | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | Desktop     | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [fa4a611c3a](https://linux-hardware.org/?probe=fa4a611c3a) | Apr 13, 2022 |
| HP            | 18E4                        | Desktop     | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | Desktop     | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| Avell High... | B.ON                        | Notebook    | [0e81f76e2b](https://linux-hardware.org/?probe=0e81f76e2b) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [1aa29ed37f](https://linux-hardware.org/?probe=1aa29ed37f) | Apr 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5029c3c4a2](https://linux-hardware.org/?probe=5029c3c4a2) | Apr 13, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [be27a452e2](https://linux-hardware.org/?probe=be27a452e2) | Apr 13, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [19bfd91984](https://linux-hardware.org/?probe=19bfd91984) | Apr 13, 2022 |
| ASUSTek       | G752VL                      | Notebook    | [910e126de2](https://linux-hardware.org/?probe=910e126de2) | Apr 13, 2022 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [c8abf66820](https://linux-hardware.org/?probe=c8abf66820) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [801d12367e](https://linux-hardware.org/?probe=801d12367e) | Apr 11, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| ASRock        | B250M Performance           | Desktop     | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| HP            | ZBook 15                    | Notebook    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [17f7c92cc6](https://linux-hardware.org/?probe=17f7c92cc6) | Apr 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1a475ba1e6](https://linux-hardware.org/?probe=1a475ba1e6) | Apr 11, 2022 |
| ASUSTek       | G752VL                      | Notebook    | [ee065014a8](https://linux-hardware.org/?probe=ee065014a8) | Apr 11, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f986565b6b](https://linux-hardware.org/?probe=f986565b6b) | Apr 10, 2022 |
| HP            | 1998                        | Desktop     | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [7bc4dfd917](https://linux-hardware.org/?probe=7bc4dfd917) | Apr 10, 2022 |
| HP            | Notebook                    | Notebook    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2fa2ca8320](https://linux-hardware.org/?probe=2fa2ca8320) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| Monster       | ABRA A5 V12.1               | Notebook    | [4b45daf3b2](https://linux-hardware.org/?probe=4b45daf3b2) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [1a7b7179f7](https://linux-hardware.org/?probe=1a7b7179f7) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Lenovo        | B560                        | Notebook    | [276b375e4a](https://linux-hardware.org/?probe=276b375e4a) | Apr 09, 2022 |
| ASUSTek       | UX310UA                     | Notebook    | [732364c253](https://linux-hardware.org/?probe=732364c253) | Apr 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| Intel         | NUC5i3MYBE H47781-203       | Mini pc     | [0f2cd9d89c](https://linux-hardware.org/?probe=0f2cd9d89c) | Apr 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| Timi          | A35                         | Notebook    | [d7e8ca818b](https://linux-hardware.org/?probe=d7e8ca818b) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa7db96c10](https://linux-hardware.org/?probe=aa7db96c10) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [28b5efd5f1](https://linux-hardware.org/?probe=28b5efd5f1) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [a0b889a753](https://linux-hardware.org/?probe=a0b889a753) | Apr 09, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| HP            | ZBook 15                    | Notebook    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [163d8c26a5](https://linux-hardware.org/?probe=163d8c26a5) | Apr 09, 2022 |
| MSI           | GS70 6QE                    | Notebook    | [8e387655c0](https://linux-hardware.org/?probe=8e387655c0) | Apr 08, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [d97d3f2838](https://linux-hardware.org/?probe=d97d3f2838) | Apr 08, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [dc1db2125f](https://linux-hardware.org/?probe=dc1db2125f) | Apr 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [414464db43](https://linux-hardware.org/?probe=414464db43) | Apr 08, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [d9c54563b1](https://linux-hardware.org/?probe=d9c54563b1) | Apr 08, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | Notebook    | [ca8d7c1137](https://linux-hardware.org/?probe=ca8d7c1137) | Apr 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [98688480ec](https://linux-hardware.org/?probe=98688480ec) | Apr 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [82b5d0a46e](https://linux-hardware.org/?probe=82b5d0a46e) | Apr 07, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [8dae5ce312](https://linux-hardware.org/?probe=8dae5ce312) | Apr 07, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [ce5b95cf78](https://linux-hardware.org/?probe=ce5b95cf78) | Apr 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [2f09a13f44](https://linux-hardware.org/?probe=2f09a13f44) | Apr 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [bb750c0f56](https://linux-hardware.org/?probe=bb750c0f56) | Apr 06, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a39d4e32a0](https://linux-hardware.org/?probe=a39d4e32a0) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [73a02fadb2](https://linux-hardware.org/?probe=73a02fadb2) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [9b7950cd38](https://linux-hardware.org/?probe=9b7950cd38) | Apr 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [943191da55](https://linux-hardware.org/?probe=943191da55) | Apr 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [9a0f2c7fe7](https://linux-hardware.org/?probe=9a0f2c7fe7) | Apr 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [81165aa277](https://linux-hardware.org/?probe=81165aa277) | Apr 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [bac9bb4c7e](https://linux-hardware.org/?probe=bac9bb4c7e) | Apr 05, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [55de739c49](https://linux-hardware.org/?probe=55de739c49) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| HP            | Victus by Laptop 16         | Notebook    | [62650f5d20](https://linux-hardware.org/?probe=62650f5d20) | Apr 04, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [9c1fd6c304](https://linux-hardware.org/?probe=9c1fd6c304) | Apr 04, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [44a524bb2f](https://linux-hardware.org/?probe=44a524bb2f) | Apr 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| HP            | Unknown                     | Notebook    | [e33741c278](https://linux-hardware.org/?probe=e33741c278) | Apr 03, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [eebc95dcb6](https://linux-hardware.org/?probe=eebc95dcb6) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ba24b37041](https://linux-hardware.org/?probe=ba24b37041) | Apr 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [25cb5de968](https://linux-hardware.org/?probe=25cb5de968) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [57a0d73ab9](https://linux-hardware.org/?probe=57a0d73ab9) | Apr 02, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [736e44b59d](https://linux-hardware.org/?probe=736e44b59d) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| HP            | Unknown                     | Notebook    | [761f0c08b2](https://linux-hardware.org/?probe=761f0c08b2) | Apr 02, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [376ed7f486](https://linux-hardware.org/?probe=376ed7f486) | Apr 02, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [e2586a5bf3](https://linux-hardware.org/?probe=e2586a5bf3) | Apr 02, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| MSI           | MS-7816                     | Notebook    | [5641d3418b](https://linux-hardware.org/?probe=5641d3418b) | Apr 01, 2022 |
| Dell          | 0N867P A02                  | Desktop     | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4fb10b4b1b](https://linux-hardware.org/?probe=4fb10b4b1b) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | Notebook    | [00630dc1b2](https://linux-hardware.org/?probe=00630dc1b2) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | Notebook    | [373ac41605](https://linux-hardware.org/?probe=373ac41605) | Apr 01, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [224f954e8f](https://linux-hardware.org/?probe=224f954e8f) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Lenovo        | ThinkPad L512 2598AM7       | Notebook    | [92d91f4fb8](https://linux-hardware.org/?probe=92d91f4fb8) | Mar 31, 2022 |
| Gateway       | NV57H                       | Notebook    | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | Desktop     | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | Desktop     | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [a18aa9fa7e](https://linux-hardware.org/?probe=a18aa9fa7e) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [f4ca737c25](https://linux-hardware.org/?probe=f4ca737c25) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a9a0826520](https://linux-hardware.org/?probe=a9a0826520) | Mar 31, 2022 |
| Lenovo        | ThinkPad L512 2598AM7       | Notebook    | [661c16a667](https://linux-hardware.org/?probe=661c16a667) | Mar 31, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eeb03a5d88](https://linux-hardware.org/?probe=eeb03a5d88) | Mar 31, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [10fe068865](https://linux-hardware.org/?probe=10fe068865) | Mar 30, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [1bb27cf702](https://linux-hardware.org/?probe=1bb27cf702) | Mar 30, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [caa021af45](https://linux-hardware.org/?probe=caa021af45) | Mar 30, 2022 |
| Dell          | 0XGMD0 A00                  | All in one  | [4ea1550be2](https://linux-hardware.org/?probe=4ea1550be2) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | Notebook    | [85f1411d0e](https://linux-hardware.org/?probe=85f1411d0e) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | Notebook    | [f8edce28d5](https://linux-hardware.org/?probe=f8edce28d5) | Mar 30, 2022 |
| Samsung       | 530XBB                      | Notebook    | [cf7f06b3fe](https://linux-hardware.org/?probe=cf7f06b3fe) | Mar 30, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | Notebook    | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [9fde02b49a](https://linux-hardware.org/?probe=9fde02b49a) | Mar 30, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [c247b0bad3](https://linux-hardware.org/?probe=c247b0bad3) | Mar 30, 2022 |
| AMI           | Intel                       | Convertible | [b349c1e550](https://linux-hardware.org/?probe=b349c1e550) | Mar 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [8cf6c58236](https://linux-hardware.org/?probe=8cf6c58236) | Mar 29, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [81fe04322e](https://linux-hardware.org/?probe=81fe04322e) | Mar 29, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ab2bed88a7](https://linux-hardware.org/?probe=ab2bed88a7) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [192125a71f](https://linux-hardware.org/?probe=192125a71f) | Mar 29, 2022 |
| HP            | 1998                        | Desktop     | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| MSI           | H81M-E34                    | Desktop     | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [d59a8be353](https://linux-hardware.org/?probe=d59a8be353) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [b431dc3d73](https://linux-hardware.org/?probe=b431dc3d73) | Mar 28, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [6c3b8c6e6c](https://linux-hardware.org/?probe=6c3b8c6e6c) | Mar 28, 2022 |
| HP            | ProBook 4340s               | Notebook    | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [26c61ab42f](https://linux-hardware.org/?probe=26c61ab42f) | Mar 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [6e19fc670b](https://linux-hardware.org/?probe=6e19fc670b) | Mar 27, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [c4ce562b21](https://linux-hardware.org/?probe=c4ce562b21) | Mar 27, 2022 |
| AMD           | 970A-D3                     | Desktop     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [d6a6546ccd](https://linux-hardware.org/?probe=d6a6546ccd) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| Alienware     | 0R3FWM A00                  | Desktop     | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Dell          | Vostro 7590                 | Notebook    | [1a15d49b97](https://linux-hardware.org/?probe=1a15d49b97) | Mar 25, 2022 |
| Dell          | Latitude E7240              | Notebook    | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f453ee2c77](https://linux-hardware.org/?probe=f453ee2c77) | Mar 25, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [4f862c8b5e](https://linux-hardware.org/?probe=4f862c8b5e) | Mar 25, 2022 |
| Acer          | Veriton M6660G V:1.0        | Desktop     | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |
| MSI           | GS60 2PE Ghost Pro          | Notebook    | [7700fa2b69](https://linux-hardware.org/?probe=7700fa2b69) | Mar 24, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [b3f93f17bb](https://linux-hardware.org/?probe=b3f93f17bb) | Mar 24, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [80a259fdac](https://linux-hardware.org/?probe=80a259fdac) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bb1d6b4aae](https://linux-hardware.org/?probe=bb1d6b4aae) | Mar 24, 2022 |
| AZW           | SER V01                     | Mini pc     | [57ee00cdcc](https://linux-hardware.org/?probe=57ee00cdcc) | Mar 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8533e3cf0d](https://linux-hardware.org/?probe=8533e3cf0d) | Mar 23, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [d081c85de2](https://linux-hardware.org/?probe=d081c85de2) | Mar 23, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| Intel         | Unknown                     | Desktop     | [169b017d29](https://linux-hardware.org/?probe=169b017d29) | Mar 23, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [82934a5fbf](https://linux-hardware.org/?probe=82934a5fbf) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c5a0300da9](https://linux-hardware.org/?probe=c5a0300da9) | Mar 23, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e02916c256](https://linux-hardware.org/?probe=e02916c256) | Mar 22, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | Desktop     | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| MSI           | GE62 6QF                    | Notebook    | [4596b4e280](https://linux-hardware.org/?probe=4596b4e280) | Mar 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d24fcefe24](https://linux-hardware.org/?probe=d24fcefe24) | Mar 22, 2022 |
| Acer          | Veriton M6660G V:1.0        | Desktop     | [228974c486](https://linux-hardware.org/?probe=228974c486) | Mar 22, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [8f5ec6c004](https://linux-hardware.org/?probe=8f5ec6c004) | Mar 22, 2022 |
| Apple         | Mac-27AD2F918AE68F61        | Desktop     | [03e06a3a70](https://linux-hardware.org/?probe=03e06a3a70) | Mar 22, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| HP            | Victus by Laptop 16         | Notebook    | [8eb2f12374](https://linux-hardware.org/?probe=8eb2f12374) | Mar 22, 2022 |
| HP            | Pavilion g7                 | Notebook    | [9d4d9b0c34](https://linux-hardware.org/?probe=9d4d9b0c34) | Mar 22, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1462cd20b7](https://linux-hardware.org/?probe=1462cd20b7) | Mar 22, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d9f1365e01](https://linux-hardware.org/?probe=d9f1365e01) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [747e4d92cf](https://linux-hardware.org/?probe=747e4d92cf) | Mar 21, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [ce0d6584b2](https://linux-hardware.org/?probe=ce0d6584b2) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [0d8a2d4ea4](https://linux-hardware.org/?probe=0d8a2d4ea4) | Mar 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [9c194b83e5](https://linux-hardware.org/?probe=9c194b83e5) | Mar 21, 2022 |
| Casper        | EXCALIBUR G900              | Notebook    | [d4902562f0](https://linux-hardware.org/?probe=d4902562f0) | Mar 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [490b0d88b3](https://linux-hardware.org/?probe=490b0d88b3) | Mar 20, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [daa5dd8024](https://linux-hardware.org/?probe=daa5dd8024) | Mar 20, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [48816e7394](https://linux-hardware.org/?probe=48816e7394) | Mar 20, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [8ce1eed900](https://linux-hardware.org/?probe=8ce1eed900) | Mar 20, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [8e148f567b](https://linux-hardware.org/?probe=8e148f567b) | Mar 19, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [52558a7cc2](https://linux-hardware.org/?probe=52558a7cc2) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [ee813d0051](https://linux-hardware.org/?probe=ee813d0051) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [6adea9d280](https://linux-hardware.org/?probe=6adea9d280) | Mar 19, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [1897912bfc](https://linux-hardware.org/?probe=1897912bfc) | Mar 19, 2022 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Dell          | Latitude 5285               | Notebook    | [662d409a76](https://linux-hardware.org/?probe=662d409a76) | Mar 18, 2022 |
| Dell          | Latitude 5285               | Notebook    | [fb9225d49b](https://linux-hardware.org/?probe=fb9225d49b) | Mar 18, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [962a1f764e](https://linux-hardware.org/?probe=962a1f764e) | Mar 18, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [0cd9c29dd0](https://linux-hardware.org/?probe=0cd9c29dd0) | Mar 18, 2022 |
| Intel         | NUC7i3BNB J22859-308        | Mini pc     | [418f0a8f9a](https://linux-hardware.org/?probe=418f0a8f9a) | Mar 18, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [4cf633a014](https://linux-hardware.org/?probe=4cf633a014) | Mar 18, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d2378fc2ac](https://linux-hardware.org/?probe=d2378fc2ac) | Mar 18, 2022 |
| HP            | Victus by Laptop 16         | Notebook    | [cbf47a2c89](https://linux-hardware.org/?probe=cbf47a2c89) | Mar 18, 2022 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [af8d9c8c06](https://linux-hardware.org/?probe=af8d9c8c06) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [7451bcb3ef](https://linux-hardware.org/?probe=7451bcb3ef) | Mar 17, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [b8fa124867](https://linux-hardware.org/?probe=b8fa124867) | Mar 17, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [75909ee2fc](https://linux-hardware.org/?probe=75909ee2fc) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [9ebb2a429f](https://linux-hardware.org/?probe=9ebb2a429f) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b844e23ce9](https://linux-hardware.org/?probe=b844e23ce9) | Mar 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [b289d3d5b9](https://linux-hardware.org/?probe=b289d3d5b9) | Mar 17, 2022 |
| Google        | Nightfury                   | Notebook    | [33c6929b2c](https://linux-hardware.org/?probe=33c6929b2c) | Mar 16, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [d49f3c26e1](https://linux-hardware.org/?probe=d49f3c26e1) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [bff9275f72](https://linux-hardware.org/?probe=bff9275f72) | Mar 16, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f617b8e30b](https://linux-hardware.org/?probe=f617b8e30b) | Mar 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [c6a31b3447](https://linux-hardware.org/?probe=c6a31b3447) | Mar 16, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [ac96c74ffa](https://linux-hardware.org/?probe=ac96c74ffa) | Mar 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ca405b99d5](https://linux-hardware.org/?probe=ca405b99d5) | Mar 16, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [f4c72eaa35](https://linux-hardware.org/?probe=f4c72eaa35) | Mar 15, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [25c3d1bf8e](https://linux-hardware.org/?probe=25c3d1bf8e) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0927f69114](https://linux-hardware.org/?probe=0927f69114) | Mar 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2aa5fb5b66](https://linux-hardware.org/?probe=2aa5fb5b66) | Mar 15, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [1b6764fd97](https://linux-hardware.org/?probe=1b6764fd97) | Mar 15, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [de6a7f79dc](https://linux-hardware.org/?probe=de6a7f79dc) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a4cc8c4dda](https://linux-hardware.org/?probe=a4cc8c4dda) | Mar 15, 2022 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [fcb0dd110e](https://linux-hardware.org/?probe=fcb0dd110e) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [a4dd59149a](https://linux-hardware.org/?probe=a4dd59149a) | Mar 15, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [8116dd6dc0](https://linux-hardware.org/?probe=8116dd6dc0) | Mar 14, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [ebeea29eda](https://linux-hardware.org/?probe=ebeea29eda) | Mar 14, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [b7cee19d72](https://linux-hardware.org/?probe=b7cee19d72) | Mar 14, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [461f90d3a5](https://linux-hardware.org/?probe=461f90d3a5) | Mar 14, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [e0efdaa76a](https://linux-hardware.org/?probe=e0efdaa76a) | Mar 13, 2022 |
| Dell          | Latitude 5400               | Notebook    | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0a16c273a4](https://linux-hardware.org/?probe=0a16c273a4) | Mar 13, 2022 |
| Acer          | Swift SF514-54GT            | Notebook    | [a170593a67](https://linux-hardware.org/?probe=a170593a67) | Mar 13, 2022 |
| ASRock        | H61 Pro BTC                 | Desktop     | [43528c8a20](https://linux-hardware.org/?probe=43528c8a20) | Mar 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [75561646a7](https://linux-hardware.org/?probe=75561646a7) | Mar 13, 2022 |
| HP            | ProBook 4340s               | Notebook    | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [8859888f0c](https://linux-hardware.org/?probe=8859888f0c) | Mar 12, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [693ec12319](https://linux-hardware.org/?probe=693ec12319) | Mar 12, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1eeedb6d3e](https://linux-hardware.org/?probe=1eeedb6d3e) | Mar 12, 2022 |
| HP            | Pavilion dm1                | Notebook    | [d65e1a184d](https://linux-hardware.org/?probe=d65e1a184d) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [138594b67f](https://linux-hardware.org/?probe=138594b67f) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | Desktop     | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [cef0b5d08f](https://linux-hardware.org/?probe=cef0b5d08f) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4Q20... | Notebook    | [4d9c3fdcc5](https://linux-hardware.org/?probe=4d9c3fdcc5) | Mar 12, 2022 |
| MSI           | H81M-E34                    | Desktop     | [8d5b326668](https://linux-hardware.org/?probe=8d5b326668) | Mar 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| HP            | 1850                        | Desktop     | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [30df05cc2f](https://linux-hardware.org/?probe=30df05cc2f) | Mar 11, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [8248b17f01](https://linux-hardware.org/?probe=8248b17f01) | Mar 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5be1842448](https://linux-hardware.org/?probe=5be1842448) | Mar 11, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [4f1cae64b4](https://linux-hardware.org/?probe=4f1cae64b4) | Mar 11, 2022 |
| HP            | 3396                        | Desktop     | [7bd27c71ed](https://linux-hardware.org/?probe=7bd27c71ed) | Mar 11, 2022 |
| HP            | 3396                        | Desktop     | [adeef3162a](https://linux-hardware.org/?probe=adeef3162a) | Mar 11, 2022 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [14747d7263](https://linux-hardware.org/?probe=14747d7263) | Mar 11, 2022 |
| Dell          | Latitude 5480               | Notebook    | [817e973e9d](https://linux-hardware.org/?probe=817e973e9d) | Mar 11, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [566eee23f5](https://linux-hardware.org/?probe=566eee23f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [0046299935](https://linux-hardware.org/?probe=0046299935) | Mar 10, 2022 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [2d72940994](https://linux-hardware.org/?probe=2d72940994) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [92f34786b4](https://linux-hardware.org/?probe=92f34786b4) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [160a8dd021](https://linux-hardware.org/?probe=160a8dd021) | Mar 10, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e323bc4a41](https://linux-hardware.org/?probe=e323bc4a41) | Mar 09, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [fab21c122b](https://linux-hardware.org/?probe=fab21c122b) | Mar 09, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [6e46455791](https://linux-hardware.org/?probe=6e46455791) | Mar 09, 2022 |
| Dell          | G7 7588                     | Notebook    | [6a2247e8e1](https://linux-hardware.org/?probe=6a2247e8e1) | Mar 09, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [4425801f5c](https://linux-hardware.org/?probe=4425801f5c) | Mar 09, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8bd86981d1](https://linux-hardware.org/?probe=8bd86981d1) | Mar 09, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [9bd4914d8e](https://linux-hardware.org/?probe=9bd4914d8e) | Mar 08, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [321af0eb17](https://linux-hardware.org/?probe=321af0eb17) | Mar 08, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [b2aeea55e5](https://linux-hardware.org/?probe=b2aeea55e5) | Mar 07, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [fb183bfd9b](https://linux-hardware.org/?probe=fb183bfd9b) | Mar 07, 2022 |
| HP            | 1497                        | Desktop     | [f67b96c14e](https://linux-hardware.org/?probe=f67b96c14e) | Mar 07, 2022 |
| HP            | Laptop 14 14s-dq1008ni      | Notebook    | [8184627283](https://linux-hardware.org/?probe=8184627283) | Mar 07, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [ea52efd6b6](https://linux-hardware.org/?probe=ea52efd6b6) | Mar 07, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7901968d67](https://linux-hardware.org/?probe=7901968d67) | Mar 07, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [acdeb0a436](https://linux-hardware.org/?probe=acdeb0a436) | Mar 07, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [50420d6d58](https://linux-hardware.org/?probe=50420d6d58) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CLS06L00    | Notebook    | [e6d00b85ed](https://linux-hardware.org/?probe=e6d00b85ed) | Mar 06, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [0bb1088899](https://linux-hardware.org/?probe=0bb1088899) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [783c8d9097](https://linux-hardware.org/?probe=783c8d9097) | Mar 06, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [141a11bf15](https://linux-hardware.org/?probe=141a11bf15) | Mar 06, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [a75c798641](https://linux-hardware.org/?probe=a75c798641) | Mar 06, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [68250a6d74](https://linux-hardware.org/?probe=68250a6d74) | Mar 06, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [715dec819e](https://linux-hardware.org/?probe=715dec819e) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [31f37e7748](https://linux-hardware.org/?probe=31f37e7748) | Mar 05, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [77ffb9a5a6](https://linux-hardware.org/?probe=77ffb9a5a6) | Mar 05, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [7e97d74a65](https://linux-hardware.org/?probe=7e97d74a65) | Mar 05, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [b949238632](https://linux-hardware.org/?probe=b949238632) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [167b8de1e1](https://linux-hardware.org/?probe=167b8de1e1) | Mar 05, 2022 |
| Dell          | Inspiron 5735               | Notebook    | [cc6ad48a04](https://linux-hardware.org/?probe=cc6ad48a04) | Mar 05, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [b56033aa1d](https://linux-hardware.org/?probe=b56033aa1d) | Mar 05, 2022 |
| Gigabyte      | 2AC8                        | Desktop     | [af655fd169](https://linux-hardware.org/?probe=af655fd169) | Mar 04, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [61191e0c42](https://linux-hardware.org/?probe=61191e0c42) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8e27cc62b4](https://linux-hardware.org/?probe=8e27cc62b4) | Mar 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [3a12accc7d](https://linux-hardware.org/?probe=3a12accc7d) | Mar 03, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6ea2fbdb95](https://linux-hardware.org/?probe=6ea2fbdb95) | Mar 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [89e8399104](https://linux-hardware.org/?probe=89e8399104) | Mar 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ee8029d2c8](https://linux-hardware.org/?probe=ee8029d2c8) | Mar 03, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [29053388a7](https://linux-hardware.org/?probe=29053388a7) | Mar 03, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [cff135fa1e](https://linux-hardware.org/?probe=cff135fa1e) | Mar 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [eb3d721453](https://linux-hardware.org/?probe=eb3d721453) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5f0757c539](https://linux-hardware.org/?probe=5f0757c539) | Mar 02, 2022 |
| Clevo         | E512xQ/E4129                | Notebook    | [7aff97f14f](https://linux-hardware.org/?probe=7aff97f14f) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f7989573c3](https://linux-hardware.org/?probe=f7989573c3) | Mar 02, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [ae5611419f](https://linux-hardware.org/?probe=ae5611419f) | Mar 02, 2022 |
| UNOWHY        | Y14G101S2E                  | Notebook    | [1c7bb4416a](https://linux-hardware.org/?probe=1c7bb4416a) | Mar 02, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c697a91a8e](https://linux-hardware.org/?probe=c697a91a8e) | Mar 02, 2022 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [07f8fcde55](https://linux-hardware.org/?probe=07f8fcde55) | Mar 02, 2022 |
| UNOWHY        | Y14G101S2E                  | Notebook    | [1b4f96aec6](https://linux-hardware.org/?probe=1b4f96aec6) | Mar 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [93ec468fa7](https://linux-hardware.org/?probe=93ec468fa7) | Mar 02, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0c6f411b98](https://linux-hardware.org/?probe=0c6f411b98) | Mar 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [14b646834e](https://linux-hardware.org/?probe=14b646834e) | Mar 01, 2022 |
| Acer          | Spin SP314-21               | Convertible | [81f3df3204](https://linux-hardware.org/?probe=81f3df3204) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60d1c44981](https://linux-hardware.org/?probe=60d1c44981) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | Notebook    | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [435548337a](https://linux-hardware.org/?probe=435548337a) | Feb 28, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [58d47eab9c](https://linux-hardware.org/?probe=58d47eab9c) | Feb 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [c9fa0137bd](https://linux-hardware.org/?probe=c9fa0137bd) | Feb 27, 2022 |
| Dell          | Latitude 5420               | Notebook    | [8f9eabc64b](https://linux-hardware.org/?probe=8f9eabc64b) | Feb 27, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [1163e289a9](https://linux-hardware.org/?probe=1163e289a9) | Feb 27, 2022 |
| HP            | 18E4                        | Desktop     | [192b302f41](https://linux-hardware.org/?probe=192b302f41) | Feb 27, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fa88748b6b](https://linux-hardware.org/?probe=fa88748b6b) | Feb 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c1bee41eec](https://linux-hardware.org/?probe=c1bee41eec) | Feb 27, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [97ab51b64a](https://linux-hardware.org/?probe=97ab51b64a) | Feb 26, 2022 |
| HP            | Notebook                    | Notebook    | [51dbbe9d8d](https://linux-hardware.org/?probe=51dbbe9d8d) | Feb 26, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [081ea4e585](https://linux-hardware.org/?probe=081ea4e585) | Feb 26, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [42cbfe4ee6](https://linux-hardware.org/?probe=42cbfe4ee6) | Feb 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [97ebb25b17](https://linux-hardware.org/?probe=97ebb25b17) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [16281a52e8](https://linux-hardware.org/?probe=16281a52e8) | Feb 26, 2022 |
| HP            | Pavilion g7                 | Notebook    | [66d6050018](https://linux-hardware.org/?probe=66d6050018) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | Notebook    | [a74bea030c](https://linux-hardware.org/?probe=a74bea030c) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | Notebook    | [318a4d1d35](https://linux-hardware.org/?probe=318a4d1d35) | Feb 25, 2022 |
| AIO           | H61H-G11                    | All in one  | [137ec871e7](https://linux-hardware.org/?probe=137ec871e7) | Feb 25, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [42117b7c9e](https://linux-hardware.org/?probe=42117b7c9e) | Feb 25, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6f1958559b](https://linux-hardware.org/?probe=6f1958559b) | Feb 24, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [b6891f77df](https://linux-hardware.org/?probe=b6891f77df) | Feb 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [f2a6491fc3](https://linux-hardware.org/?probe=f2a6491fc3) | Feb 24, 2022 |
| Samsung       | 950QCG                      | Convertible | [5b950e3462](https://linux-hardware.org/?probe=5b950e3462) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| MSI           | P65 Creator 9SD             | Notebook    | [093c9b9f41](https://linux-hardware.org/?probe=093c9b9f41) | Feb 24, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| MSI           | P65 Creator 9SD             | Notebook    | [3c55366478](https://linux-hardware.org/?probe=3c55366478) | Feb 24, 2022 |
| MSI           | GS60 2PE Ghost Pro          | Notebook    | [2a0cbe38d7](https://linux-hardware.org/?probe=2a0cbe38d7) | Feb 24, 2022 |
| Supermicro    | A1SAM-2550F                 | Server      | [a9e1a5906c](https://linux-hardware.org/?probe=a9e1a5906c) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [9f42d69f9f](https://linux-hardware.org/?probe=9f42d69f9f) | Feb 24, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [e6564282e5](https://linux-hardware.org/?probe=e6564282e5) | Feb 23, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [9a94ad6810](https://linux-hardware.org/?probe=9a94ad6810) | Feb 23, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [2f53cef399](https://linux-hardware.org/?probe=2f53cef399) | Feb 23, 2022 |
| MSI           | GT72 6QD                    | Notebook    | [7f4b5361a7](https://linux-hardware.org/?probe=7f4b5361a7) | Feb 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [6d2bec51f3](https://linux-hardware.org/?probe=6d2bec51f3) | Feb 23, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | Desktop     | [17aa7b3d5b](https://linux-hardware.org/?probe=17aa7b3d5b) | Feb 23, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c2ed3df75c](https://linux-hardware.org/?probe=c2ed3df75c) | Feb 23, 2022 |
| MSI           | P65 Creator 9SD             | Notebook    | [2782f833c9](https://linux-hardware.org/?probe=2782f833c9) | Feb 23, 2022 |
| Supermicro    | A1SAM-2550F                 | Server      | [b7df6b0231](https://linux-hardware.org/?probe=b7df6b0231) | Feb 23, 2022 |
| MSI           | 880G-E45                    | Desktop     | [e6f9c8c9f6](https://linux-hardware.org/?probe=e6f9c8c9f6) | Feb 23, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [742af9249b](https://linux-hardware.org/?probe=742af9249b) | Feb 23, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [0a9140ff8f](https://linux-hardware.org/?probe=0a9140ff8f) | Feb 22, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [63fe1b47e9](https://linux-hardware.org/?probe=63fe1b47e9) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [3886078240](https://linux-hardware.org/?probe=3886078240) | Feb 22, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [78e355e895](https://linux-hardware.org/?probe=78e355e895) | Feb 21, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [1adb30dfb2](https://linux-hardware.org/?probe=1adb30dfb2) | Feb 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [db907dad62](https://linux-hardware.org/?probe=db907dad62) | Feb 21, 2022 |
| Gigabyte      | 2AC8                        | Desktop     | [90d30ccc29](https://linux-hardware.org/?probe=90d30ccc29) | Feb 21, 2022 |
| HP            | Notebook                    | Notebook    | [d734cd43d3](https://linux-hardware.org/?probe=d734cd43d3) | Feb 21, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [03491eae09](https://linux-hardware.org/?probe=03491eae09) | Feb 21, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e1943c32e9](https://linux-hardware.org/?probe=e1943c32e9) | Feb 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b4979c164c](https://linux-hardware.org/?probe=b4979c164c) | Feb 20, 2022 |
| Lenovo        | ThinkPad ThinkPad L14 20... | Notebook    | [369c625e43](https://linux-hardware.org/?probe=369c625e43) | Feb 20, 2022 |
| HP            | 1998                        | Desktop     | [1cd99a92d0](https://linux-hardware.org/?probe=1cd99a92d0) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [90154b9001](https://linux-hardware.org/?probe=90154b9001) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [b42d2ce48e](https://linux-hardware.org/?probe=b42d2ce48e) | Feb 20, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [a182c90da3](https://linux-hardware.org/?probe=a182c90da3) | Feb 20, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [420ec4b69b](https://linux-hardware.org/?probe=420ec4b69b) | Feb 20, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [95b177e121](https://linux-hardware.org/?probe=95b177e121) | Feb 19, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [215889b22b](https://linux-hardware.org/?probe=215889b22b) | Feb 19, 2022 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [e849c7b27b](https://linux-hardware.org/?probe=e849c7b27b) | Feb 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [b91f497b74](https://linux-hardware.org/?probe=b91f497b74) | Feb 19, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bc582ad91](https://linux-hardware.org/?probe=3bc582ad91) | Feb 19, 2022 |
| HP            | Notebook                    | Notebook    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | Notebook    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [2542eb898d](https://linux-hardware.org/?probe=2542eb898d) | Feb 19, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [7ecf132718](https://linux-hardware.org/?probe=7ecf132718) | Feb 19, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f7adb86dce](https://linux-hardware.org/?probe=f7adb86dce) | Feb 18, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [862a31fa80](https://linux-hardware.org/?probe=862a31fa80) | Feb 18, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [d08ed1959b](https://linux-hardware.org/?probe=d08ed1959b) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [3c30a8c6a1](https://linux-hardware.org/?probe=3c30a8c6a1) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4fba279b51](https://linux-hardware.org/?probe=4fba279b51) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [42cf76ea1b](https://linux-hardware.org/?probe=42cf76ea1b) | Feb 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [91540e8aa6](https://linux-hardware.org/?probe=91540e8aa6) | Feb 18, 2022 |
| HP            | 1497                        | Desktop     | [8693cfc8c8](https://linux-hardware.org/?probe=8693cfc8c8) | Feb 17, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3bb86aa608](https://linux-hardware.org/?probe=3bb86aa608) | Feb 17, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [ac3f9fa03e](https://linux-hardware.org/?probe=ac3f9fa03e) | Feb 17, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [304e498f77](https://linux-hardware.org/?probe=304e498f77) | Feb 17, 2022 |
| HP            | 2820h                       | Desktop     | [f45476e17a](https://linux-hardware.org/?probe=f45476e17a) | Feb 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [3dc3e4c8c8](https://linux-hardware.org/?probe=3dc3e4c8c8) | Feb 17, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [2dece71caa](https://linux-hardware.org/?probe=2dece71caa) | Feb 17, 2022 |
| Apple         | MacBookAir3,2               | Notebook    | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [00fa8d31f3](https://linux-hardware.org/?probe=00fa8d31f3) | Feb 17, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [4d1c34fef7](https://linux-hardware.org/?probe=4d1c34fef7) | Feb 17, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [c9d8bb9bd9](https://linux-hardware.org/?probe=c9d8bb9bd9) | Feb 16, 2022 |
| HP            | 0AA8h                       | Desktop     | [cb11b8e6fb](https://linux-hardware.org/?probe=cb11b8e6fb) | Feb 16, 2022 |
| ASUSTek       | X55A                        | Notebook    | [1ed422d0e2](https://linux-hardware.org/?probe=1ed422d0e2) | Feb 16, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | Desktop     | [922f3559c8](https://linux-hardware.org/?probe=922f3559c8) | Feb 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [913928e6e9](https://linux-hardware.org/?probe=913928e6e9) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | Desktop     | [c80545d294](https://linux-hardware.org/?probe=c80545d294) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | Desktop     | [98e8879090](https://linux-hardware.org/?probe=98e8879090) | Feb 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [4b52b51003](https://linux-hardware.org/?probe=4b52b51003) | Feb 15, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| Google        | Chell                       | Notebook    | [a7795e2fb9](https://linux-hardware.org/?probe=a7795e2fb9) | Feb 15, 2022 |
| Google        | Chell                       | Notebook    | [9ec35bc2d1](https://linux-hardware.org/?probe=9ec35bc2d1) | Feb 15, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [ef498b262a](https://linux-hardware.org/?probe=ef498b262a) | Feb 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS06K0... | Notebook    | [60cf03acd8](https://linux-hardware.org/?probe=60cf03acd8) | Feb 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS06K0... | Notebook    | [8305aa0d2e](https://linux-hardware.org/?probe=8305aa0d2e) | Feb 15, 2022 |
| Toshiba       | Satellite C870D-11F         | Notebook    | [eaac3ab809](https://linux-hardware.org/?probe=eaac3ab809) | Feb 14, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [92d9e3e1eb](https://linux-hardware.org/?probe=92d9e3e1eb) | Feb 14, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [031e61417a](https://linux-hardware.org/?probe=031e61417a) | Feb 14, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [6f8f7c786e](https://linux-hardware.org/?probe=6f8f7c786e) | Feb 14, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [b4c976a541](https://linux-hardware.org/?probe=b4c976a541) | Feb 14, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [bf684bced7](https://linux-hardware.org/?probe=bf684bced7) | Feb 14, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [2a5bcaeec9](https://linux-hardware.org/?probe=2a5bcaeec9) | Feb 14, 2022 |
| Google        | Celes                       | Notebook    | [93a2853671](https://linux-hardware.org/?probe=93a2853671) | Feb 13, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3bbcbc62f5](https://linux-hardware.org/?probe=3bbcbc62f5) | Feb 13, 2022 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | Notebook    | [98d7355c52](https://linux-hardware.org/?probe=98d7355c52) | Feb 13, 2022 |
| Acer          | Swift SF315-51G             | Notebook    | [5e25ecab1f](https://linux-hardware.org/?probe=5e25ecab1f) | Feb 13, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [25027ae3f1](https://linux-hardware.org/?probe=25027ae3f1) | Feb 13, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [2e9d58f492](https://linux-hardware.org/?probe=2e9d58f492) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [a84f254fbc](https://linux-hardware.org/?probe=a84f254fbc) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [26ed6eddae](https://linux-hardware.org/?probe=26ed6eddae) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [eb0e21d784](https://linux-hardware.org/?probe=eb0e21d784) | Feb 11, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0eb31742e7](https://linux-hardware.org/?probe=0eb31742e7) | Feb 11, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [981b697116](https://linux-hardware.org/?probe=981b697116) | Feb 11, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| Intel         | DH67GD AAG10206-202         | Desktop     | [56c802164a](https://linux-hardware.org/?probe=56c802164a) | Feb 11, 2022 |
| Microsoft     | Surface Book                | Tablet      | [2f68670c69](https://linux-hardware.org/?probe=2f68670c69) | Feb 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [da04806287](https://linux-hardware.org/?probe=da04806287) | Feb 11, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [ecd6593b16](https://linux-hardware.org/?probe=ecd6593b16) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [36b4f54213](https://linux-hardware.org/?probe=36b4f54213) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [8abd201999](https://linux-hardware.org/?probe=8abd201999) | Feb 11, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [112bf24036](https://linux-hardware.org/?probe=112bf24036) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [a84b20f4fd](https://linux-hardware.org/?probe=a84b20f4fd) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6df20f0f72](https://linux-hardware.org/?probe=6df20f0f72) | Feb 11, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [3ac8f883ab](https://linux-hardware.org/?probe=3ac8f883ab) | Feb 11, 2022 |
| Acer          | Predator PO3-630            | Desktop     | [96dccc1214](https://linux-hardware.org/?probe=96dccc1214) | Feb 11, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [c38ad73c09](https://linux-hardware.org/?probe=c38ad73c09) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [0f65488b54](https://linux-hardware.org/?probe=0f65488b54) | Feb 11, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b380982ba5](https://linux-hardware.org/?probe=b380982ba5) | Feb 11, 2022 |
| AZW           | GTR V01                     | Mini pc     | [1b95862ca6](https://linux-hardware.org/?probe=1b95862ca6) | Feb 10, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [21d3c81852](https://linux-hardware.org/?probe=21d3c81852) | Feb 10, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [afc31097cd](https://linux-hardware.org/?probe=afc31097cd) | Feb 09, 2022 |
| Gateway       | NV57H                       | Notebook    | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a752207fe2](https://linux-hardware.org/?probe=a752207fe2) | Feb 09, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [ee510b7924](https://linux-hardware.org/?probe=ee510b7924) | Feb 09, 2022 |
| HP            | Notebook                    | Notebook    | [7900320935](https://linux-hardware.org/?probe=7900320935) | Feb 09, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [1308425490](https://linux-hardware.org/?probe=1308425490) | Feb 08, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [8545c3246e](https://linux-hardware.org/?probe=8545c3246e) | Feb 08, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6c60cbb4d6](https://linux-hardware.org/?probe=6c60cbb4d6) | Feb 08, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [7135f3c638](https://linux-hardware.org/?probe=7135f3c638) | Feb 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [d6aefe2df6](https://linux-hardware.org/?probe=d6aefe2df6) | Feb 07, 2022 |
| Toshiba       | Satellite U900              | Notebook    | [de937d0299](https://linux-hardware.org/?probe=de937d0299) | Feb 07, 2022 |
| ASUSTek       | TUF GAMING Z490-PLUS        | Desktop     | [9dd525ae45](https://linux-hardware.org/?probe=9dd525ae45) | Feb 07, 2022 |
| Toshiba       | Satellite U900              | Notebook    | [2c06fc7359](https://linux-hardware.org/?probe=2c06fc7359) | Feb 07, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [b2bc043c0b](https://linux-hardware.org/?probe=b2bc043c0b) | Feb 07, 2022 |
| Lenovo        | ThinkPad E495 20NES01600    | Notebook    | [c40a0c5222](https://linux-hardware.org/?probe=c40a0c5222) | Feb 07, 2022 |
| HP            | 2820h                       | Desktop     | [347b6a83de](https://linux-hardware.org/?probe=347b6a83de) | Feb 07, 2022 |
| HP            | 2820h                       | Desktop     | [7c5fb9c18f](https://linux-hardware.org/?probe=7c5fb9c18f) | Feb 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9efa6de9c0](https://linux-hardware.org/?probe=9efa6de9c0) | Feb 07, 2022 |
| MSI           | GE76 Raider 11UH            | Notebook    | [092c3d1877](https://linux-hardware.org/?probe=092c3d1877) | Feb 07, 2022 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [11b7d331bc](https://linux-hardware.org/?probe=11b7d331bc) | Feb 06, 2022 |
| Intel         | H61 V124                    | Desktop     | [258b472104](https://linux-hardware.org/?probe=258b472104) | Feb 06, 2022 |
| Samsung       | 550XDA                      | Notebook    | [9c9b8d6672](https://linux-hardware.org/?probe=9c9b8d6672) | Feb 06, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [5b4fcb642e](https://linux-hardware.org/?probe=5b4fcb642e) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c1fe9c81a0](https://linux-hardware.org/?probe=c1fe9c81a0) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f92b5e4b44](https://linux-hardware.org/?probe=f92b5e4b44) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [497f20602c](https://linux-hardware.org/?probe=497f20602c) | Feb 05, 2022 |
| Acer          | Predator PO3-630            | Desktop     | [7d12bf5399](https://linux-hardware.org/?probe=7d12bf5399) | Feb 05, 2022 |
| Lenovo        | ThinkPad E490 20N80029GE    | Notebook    | [463f54f91a](https://linux-hardware.org/?probe=463f54f91a) | Feb 05, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [dc86c1f5d5](https://linux-hardware.org/?probe=dc86c1f5d5) | Feb 05, 2022 |
| MSI           | Z270I GAMING PRO CARBON ... | Desktop     | [424f798e37](https://linux-hardware.org/?probe=424f798e37) | Feb 05, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [4c27e1f600](https://linux-hardware.org/?probe=4c27e1f600) | Feb 05, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [24713a7953](https://linux-hardware.org/?probe=24713a7953) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [055aea6734](https://linux-hardware.org/?probe=055aea6734) | Feb 05, 2022 |
| Acer          | Aspire SW7-272              | Notebook    | [920f676336](https://linux-hardware.org/?probe=920f676336) | Feb 04, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [987feed95d](https://linux-hardware.org/?probe=987feed95d) | Feb 04, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [5828b467b9](https://linux-hardware.org/?probe=5828b467b9) | Feb 04, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [748e3fae6c](https://linux-hardware.org/?probe=748e3fae6c) | Feb 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [8ba5ead5e5](https://linux-hardware.org/?probe=8ba5ead5e5) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [436259c69f](https://linux-hardware.org/?probe=436259c69f) | Feb 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [32586355fe](https://linux-hardware.org/?probe=32586355fe) | Feb 02, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [76dff27038](https://linux-hardware.org/?probe=76dff27038) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [a4c71279a4](https://linux-hardware.org/?probe=a4c71279a4) | Feb 02, 2022 |
| Teclast       | X6 plus                     | Tablet      | [dca4d50a5c](https://linux-hardware.org/?probe=dca4d50a5c) | Feb 02, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [05d8bff376](https://linux-hardware.org/?probe=05d8bff376) | Feb 02, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8086fa496d](https://linux-hardware.org/?probe=8086fa496d) | Feb 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [a6bc5bb673](https://linux-hardware.org/?probe=a6bc5bb673) | Feb 01, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [01eb76fa65](https://linux-hardware.org/?probe=01eb76fa65) | Feb 01, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [9d172808c8](https://linux-hardware.org/?probe=9d172808c8) | Feb 01, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [196508f0aa](https://linux-hardware.org/?probe=196508f0aa) | Feb 01, 2022 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [8583114e36](https://linux-hardware.org/?probe=8583114e36) | Feb 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [e68105f8de](https://linux-hardware.org/?probe=e68105f8de) | Feb 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [8d0b4e7b64](https://linux-hardware.org/?probe=8d0b4e7b64) | Feb 01, 2022 |
| HP            | Grunt                       | Notebook    | [315d957271](https://linux-hardware.org/?probe=315d957271) | Feb 01, 2022 |
| HP            | Grunt                       | Notebook    | [e95882e549](https://linux-hardware.org/?probe=e95882e549) | Jan 31, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [bbe17ee442](https://linux-hardware.org/?probe=bbe17ee442) | Jan 31, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [dccef6f0ca](https://linux-hardware.org/?probe=dccef6f0ca) | Jan 30, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e41e701a15](https://linux-hardware.org/?probe=e41e701a15) | Jan 30, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [93f280e643](https://linux-hardware.org/?probe=93f280e643) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [2248ba47d2](https://linux-hardware.org/?probe=2248ba47d2) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [74eb47cb2f](https://linux-hardware.org/?probe=74eb47cb2f) | Jan 30, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [c342bd0bba](https://linux-hardware.org/?probe=c342bd0bba) | Jan 30, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [67f194f1e2](https://linux-hardware.org/?probe=67f194f1e2) | Jan 29, 2022 |
| Huanan        | X99-TF GAMING V2.0          | Desktop     | [aa1fb1fa56](https://linux-hardware.org/?probe=aa1fb1fa56) | Jan 29, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [7697915441](https://linux-hardware.org/?probe=7697915441) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ce7d1b347](https://linux-hardware.org/?probe=1ce7d1b347) | Jan 29, 2022 |
| HP            | ProBook 4720s               | Notebook    | [c17f5dcf26](https://linux-hardware.org/?probe=c17f5dcf26) | Jan 29, 2022 |
| GPD           | G1621-02                    | Notebook    | [7bc0adb6d3](https://linux-hardware.org/?probe=7bc0adb6d3) | Jan 28, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [c1e858090a](https://linux-hardware.org/?probe=c1e858090a) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f653016830](https://linux-hardware.org/?probe=f653016830) | Jan 28, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [bfc2cf603f](https://linux-hardware.org/?probe=bfc2cf603f) | Jan 27, 2022 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [3b632063e5](https://linux-hardware.org/?probe=3b632063e5) | Jan 27, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [12a1ab9ddb](https://linux-hardware.org/?probe=12a1ab9ddb) | Jan 27, 2022 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [bda3f36826](https://linux-hardware.org/?probe=bda3f36826) | Jan 27, 2022 |
| ASUSTek       | TUF GAMING A520M-PLUS II    | Desktop     | [ad887e6da9](https://linux-hardware.org/?probe=ad887e6da9) | Jan 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [1fbb598e3a](https://linux-hardware.org/?probe=1fbb598e3a) | Jan 27, 2022 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [ef86245dd3](https://linux-hardware.org/?probe=ef86245dd3) | Jan 26, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [1fdcf46e3b](https://linux-hardware.org/?probe=1fdcf46e3b) | Jan 26, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [bd83b31919](https://linux-hardware.org/?probe=bd83b31919) | Jan 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [56ce398ad8](https://linux-hardware.org/?probe=56ce398ad8) | Jan 25, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [1816cd81d3](https://linux-hardware.org/?probe=1816cd81d3) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [510e973c9d](https://linux-hardware.org/?probe=510e973c9d) | Jan 25, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [f4ad8a6220](https://linux-hardware.org/?probe=f4ad8a6220) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [40d8a83107](https://linux-hardware.org/?probe=40d8a83107) | Jan 25, 2022 |
| HP            | Split 13 x2 PC              | Notebook    | [386f52f504](https://linux-hardware.org/?probe=386f52f504) | Jan 25, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [7cffc1095f](https://linux-hardware.org/?probe=7cffc1095f) | Jan 25, 2022 |
| Gigabyte      | 2AC8                        | Desktop     | [1480b4a02f](https://linux-hardware.org/?probe=1480b4a02f) | Jan 25, 2022 |
| Dell          | Inspiron 7437               | Notebook    | [eb390d4f76](https://linux-hardware.org/?probe=eb390d4f76) | Jan 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [245774979e](https://linux-hardware.org/?probe=245774979e) | Jan 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [055decea61](https://linux-hardware.org/?probe=055decea61) | Jan 24, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [09346f1d27](https://linux-hardware.org/?probe=09346f1d27) | Jan 24, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d0dde4a553](https://linux-hardware.org/?probe=d0dde4a553) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| Gigabyte      | 965P-S3                     | Desktop     | [9e4aca104e](https://linux-hardware.org/?probe=9e4aca104e) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [c386ed263b](https://linux-hardware.org/?probe=c386ed263b) | Jan 24, 2022 |
| Lenovo        | ThinkPad E560 20EV002UIX    | Notebook    | [5df655624a](https://linux-hardware.org/?probe=5df655624a) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [36709c59ac](https://linux-hardware.org/?probe=36709c59ac) | Jan 24, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f48fe5a028](https://linux-hardware.org/?probe=f48fe5a028) | Jan 24, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [dd98b6fbca](https://linux-hardware.org/?probe=dd98b6fbca) | Jan 23, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [77e433fe30](https://linux-hardware.org/?probe=77e433fe30) | Jan 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [db3a3ddae1](https://linux-hardware.org/?probe=db3a3ddae1) | Jan 23, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASRock        | H510M-ITX/ac                | Desktop     | [606c183545](https://linux-hardware.org/?probe=606c183545) | Jan 23, 2022 |
| ASUSTek       | TUF GAMING A520M-PLUS II    | Desktop     | [f950d7e322](https://linux-hardware.org/?probe=f950d7e322) | Jan 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a934945d5](https://linux-hardware.org/?probe=7a934945d5) | Jan 23, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [05d9d96be4](https://linux-hardware.org/?probe=05d9d96be4) | Jan 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [92418aeb06](https://linux-hardware.org/?probe=92418aeb06) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fb18e68215](https://linux-hardware.org/?probe=fb18e68215) | Jan 22, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [1df9cf7c06](https://linux-hardware.org/?probe=1df9cf7c06) | Jan 22, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [e15086b2b6](https://linux-hardware.org/?probe=e15086b2b6) | Jan 22, 2022 |
| AZW           | SEi                         | Notebook    | [71b530bc33](https://linux-hardware.org/?probe=71b530bc33) | Jan 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1c15058d91](https://linux-hardware.org/?probe=1c15058d91) | Jan 22, 2022 |
| Google        | Candy                       | Notebook    | [f050105bbf](https://linux-hardware.org/?probe=f050105bbf) | Jan 21, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [664826a715](https://linux-hardware.org/?probe=664826a715) | Jan 21, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [11d1870f98](https://linux-hardware.org/?probe=11d1870f98) | Jan 21, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [e19ee364b0](https://linux-hardware.org/?probe=e19ee364b0) | Jan 21, 2022 |
| HP            | ZBook 14                    | Notebook    | [b64ef7e687](https://linux-hardware.org/?probe=b64ef7e687) | Jan 21, 2022 |
| Lenovo        | ThinkPad X220 4291B60       | Notebook    | [94a949025b](https://linux-hardware.org/?probe=94a949025b) | Jan 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6d6c1565b7](https://linux-hardware.org/?probe=6d6c1565b7) | Jan 21, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [e45ce2cdc0](https://linux-hardware.org/?probe=e45ce2cdc0) | Jan 21, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| Gigabyte      | Z590 VISION D               | Desktop     | [1d8fa44afd](https://linux-hardware.org/?probe=1d8fa44afd) | Jan 20, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [88150d957e](https://linux-hardware.org/?probe=88150d957e) | Jan 20, 2022 |
| Dell          | Latitude E5470              | Notebook    | [c97c4b19b1](https://linux-hardware.org/?probe=c97c4b19b1) | Jan 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [e97b90d14b](https://linux-hardware.org/?probe=e97b90d14b) | Jan 20, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [64a2a3257d](https://linux-hardware.org/?probe=64a2a3257d) | Jan 20, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [6eab6bd21a](https://linux-hardware.org/?probe=6eab6bd21a) | Jan 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cf4e41b312](https://linux-hardware.org/?probe=cf4e41b312) | Jan 19, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [9307ab1c57](https://linux-hardware.org/?probe=9307ab1c57) | Jan 19, 2022 |
| Gigabyte      | H61M-DS2                    | All in one  | [a965900724](https://linux-hardware.org/?probe=a965900724) | Jan 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [993543545b](https://linux-hardware.org/?probe=993543545b) | Jan 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ce0d7ad7f6](https://linux-hardware.org/?probe=ce0d7ad7f6) | Jan 18, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [7e0c6ebfc9](https://linux-hardware.org/?probe=7e0c6ebfc9) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [d531de56b2](https://linux-hardware.org/?probe=d531de56b2) | Jan 18, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [5cccda3e40](https://linux-hardware.org/?probe=5cccda3e40) | Jan 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [d6cba98531](https://linux-hardware.org/?probe=d6cba98531) | Jan 18, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [484bd19da3](https://linux-hardware.org/?probe=484bd19da3) | Jan 18, 2022 |
| HP            | Split 13 x2 PC              | Notebook    | [5bb3f2a066](https://linux-hardware.org/?probe=5bb3f2a066) | Jan 18, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [bc394cac32](https://linux-hardware.org/?probe=bc394cac32) | Jan 17, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [2f8e734236](https://linux-hardware.org/?probe=2f8e734236) | Jan 17, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [42d55a089f](https://linux-hardware.org/?probe=42d55a089f) | Jan 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5a609ef492](https://linux-hardware.org/?probe=5a609ef492) | Jan 16, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [8a9370c34f](https://linux-hardware.org/?probe=8a9370c34f) | Jan 16, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [7e44b8f1f8](https://linux-hardware.org/?probe=7e44b8f1f8) | Jan 16, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [9b7d66cb9d](https://linux-hardware.org/?probe=9b7d66cb9d) | Jan 16, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [5f93713b6d](https://linux-hardware.org/?probe=5f93713b6d) | Jan 16, 2022 |
| Dell          | Vostro 15 7510              | Notebook    | [8d4c65829a](https://linux-hardware.org/?probe=8d4c65829a) | Jan 15, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [67c671c04f](https://linux-hardware.org/?probe=67c671c04f) | Jan 15, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [eb68d3d4dd](https://linux-hardware.org/?probe=eb68d3d4dd) | Jan 15, 2022 |
| Google        | Falco                       | Notebook    | [f6669b14c1](https://linux-hardware.org/?probe=f6669b14c1) | Jan 15, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [0d267e1823](https://linux-hardware.org/?probe=0d267e1823) | Jan 15, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [eafa397038](https://linux-hardware.org/?probe=eafa397038) | Jan 14, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [ba7ea12461](https://linux-hardware.org/?probe=ba7ea12461) | Jan 14, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [8ec42ce5c6](https://linux-hardware.org/?probe=8ec42ce5c6) | Jan 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a9f451830b](https://linux-hardware.org/?probe=a9f451830b) | Jan 14, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [327b6c6601](https://linux-hardware.org/?probe=327b6c6601) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [43f8f76683](https://linux-hardware.org/?probe=43f8f76683) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [328af2e60a](https://linux-hardware.org/?probe=328af2e60a) | Jan 13, 2022 |
| Sony          | SVF13N2J4RS                 | Notebook    | [e0501f4bf8](https://linux-hardware.org/?probe=e0501f4bf8) | Jan 12, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [e01d513669](https://linux-hardware.org/?probe=e01d513669) | Jan 12, 2022 |
| HP            | ProBook 6470b               | Notebook    | [1d463f955b](https://linux-hardware.org/?probe=1d463f955b) | Jan 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d0ebb55aa3](https://linux-hardware.org/?probe=d0ebb55aa3) | Jan 12, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [8ae8b9f712](https://linux-hardware.org/?probe=8ae8b9f712) | Jan 12, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [b5437027b1](https://linux-hardware.org/?probe=b5437027b1) | Jan 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [729fd5a406](https://linux-hardware.org/?probe=729fd5a406) | Jan 12, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [acd1da8f35](https://linux-hardware.org/?probe=acd1da8f35) | Jan 12, 2022 |
| MSI           | X99S GAMING 7               | Desktop     | [66556a15be](https://linux-hardware.org/?probe=66556a15be) | Jan 11, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [9b830c06c5](https://linux-hardware.org/?probe=9b830c06c5) | Jan 11, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | Desktop     | [7a18fc5ecf](https://linux-hardware.org/?probe=7a18fc5ecf) | Jan 11, 2022 |
| Dell          | Precision M4700             | Notebook    | [8cb828d48a](https://linux-hardware.org/?probe=8cb828d48a) | Jan 11, 2022 |
| Star Labs     | LabTop                      | Notebook    | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4d0e193e1](https://linux-hardware.org/?probe=c4d0e193e1) | Jan 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [45e02e5604](https://linux-hardware.org/?probe=45e02e5604) | Jan 11, 2022 |
| Dell          | 0KP561                      | Desktop     | [91846f4dc8](https://linux-hardware.org/?probe=91846f4dc8) | Jan 10, 2022 |
| HP            | Notebook                    | Notebook    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [bb8e7fc409](https://linux-hardware.org/?probe=bb8e7fc409) | Jan 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d6a720b87c](https://linux-hardware.org/?probe=d6a720b87c) | Jan 10, 2022 |
| Google        | Falco                       | Notebook    | [94a0bc1e5f](https://linux-hardware.org/?probe=94a0bc1e5f) | Jan 10, 2022 |
| ASRock        | H81M-VG4                    | Desktop     | [8678202106](https://linux-hardware.org/?probe=8678202106) | Jan 10, 2022 |
| ASUSTek       | P5WDG2 WS PRO               | Desktop     | [c22b31be4e](https://linux-hardware.org/?probe=c22b31be4e) | Jan 10, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [936bd6bf44](https://linux-hardware.org/?probe=936bd6bf44) | Jan 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [8abb20fa3a](https://linux-hardware.org/?probe=8abb20fa3a) | Jan 09, 2022 |
| Chatreey      | AC1-DP                      | Desktop     | [fb4af3e7ac](https://linux-hardware.org/?probe=fb4af3e7ac) | Jan 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0127739070](https://linux-hardware.org/?probe=0127739070) | Jan 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [c8e28c5df0](https://linux-hardware.org/?probe=c8e28c5df0) | Jan 09, 2022 |
| Acer          | Aspire S7-391               | Notebook    | [1c31255215](https://linux-hardware.org/?probe=1c31255215) | Jan 08, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [5300368575](https://linux-hardware.org/?probe=5300368575) | Jan 08, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6cb48fa647](https://linux-hardware.org/?probe=6cb48fa647) | Jan 08, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [feff8775da](https://linux-hardware.org/?probe=feff8775da) | Jan 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [14e41b405a](https://linux-hardware.org/?probe=14e41b405a) | Jan 08, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [50adc5f773](https://linux-hardware.org/?probe=50adc5f773) | Jan 08, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b5fbd6f1c9](https://linux-hardware.org/?probe=b5fbd6f1c9) | Jan 08, 2022 |
| Schenker      | N24_25JU                    | Notebook    | [b847cd914a](https://linux-hardware.org/?probe=b847cd914a) | Jan 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ddd3544bcf](https://linux-hardware.org/?probe=ddd3544bcf) | Jan 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [4c8aea2ca5](https://linux-hardware.org/?probe=4c8aea2ca5) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [e6501cd7df](https://linux-hardware.org/?probe=e6501cd7df) | Jan 08, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a46f46da47](https://linux-hardware.org/?probe=a46f46da47) | Jan 08, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | Notebook    | [e3d4c84cce](https://linux-hardware.org/?probe=e3d4c84cce) | Jan 08, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [46878503d2](https://linux-hardware.org/?probe=46878503d2) | Jan 07, 2022 |
| Sony          | VPCEB2Z1E                   | Notebook    | [40bc339ad3](https://linux-hardware.org/?probe=40bc339ad3) | Jan 07, 2022 |
| Sony          | VPCEB2Z1E                   | Notebook    | [4e59f301b2](https://linux-hardware.org/?probe=4e59f301b2) | Jan 07, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [5b879a9c87](https://linux-hardware.org/?probe=5b879a9c87) | Jan 07, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8a3b6c72a9](https://linux-hardware.org/?probe=8a3b6c72a9) | Jan 06, 2022 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [96dd604fa9](https://linux-hardware.org/?probe=96dd604fa9) | Jan 06, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [8a1611ac33](https://linux-hardware.org/?probe=8a1611ac33) | Jan 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [8c59662d46](https://linux-hardware.org/?probe=8c59662d46) | Jan 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [6065957c5e](https://linux-hardware.org/?probe=6065957c5e) | Jan 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [14039ef983](https://linux-hardware.org/?probe=14039ef983) | Jan 05, 2022 |
| MSI           | B85M-E33 V2                 | Desktop     | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [6e5d25e99f](https://linux-hardware.org/?probe=6e5d25e99f) | Jan 05, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [d83cbe9961](https://linux-hardware.org/?probe=d83cbe9961) | Jan 05, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | Desktop     | [a1e2cab707](https://linux-hardware.org/?probe=a1e2cab707) | Jan 05, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [b70942532f](https://linux-hardware.org/?probe=b70942532f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| Acer          | TravelMate P253             | Notebook    | [90c92c4f35](https://linux-hardware.org/?probe=90c92c4f35) | Jan 04, 2022 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [217fe39d3f](https://linux-hardware.org/?probe=217fe39d3f) | Jan 04, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [513ea3a232](https://linux-hardware.org/?probe=513ea3a232) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [c1f08a0773](https://linux-hardware.org/?probe=c1f08a0773) | Jan 04, 2022 |
| ilife         | S806                        | Notebook    | [72d842b86c](https://linux-hardware.org/?probe=72d842b86c) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [c52ca0986f](https://linux-hardware.org/?probe=c52ca0986f) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [3c727538a0](https://linux-hardware.org/?probe=3c727538a0) | Jan 04, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [608b8edfd4](https://linux-hardware.org/?probe=608b8edfd4) | Jan 03, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [157c5615eb](https://linux-hardware.org/?probe=157c5615eb) | Jan 03, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [ce034fa823](https://linux-hardware.org/?probe=ce034fa823) | Jan 03, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [7c5499f8b4](https://linux-hardware.org/?probe=7c5499f8b4) | Jan 03, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [2631c46dd7](https://linux-hardware.org/?probe=2631c46dd7) | Jan 03, 2022 |
| AZW           | SEi                         | Notebook    | [99d54c937c](https://linux-hardware.org/?probe=99d54c937c) | Jan 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f6c8e7bdf4](https://linux-hardware.org/?probe=f6c8e7bdf4) | Jan 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [e99913f33f](https://linux-hardware.org/?probe=e99913f33f) | Jan 02, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ec461a0a66](https://linux-hardware.org/?probe=ec461a0a66) | Jan 02, 2022 |
| Google        | Rammus                      | Notebook    | [aa3b26a209](https://linux-hardware.org/?probe=aa3b26a209) | Jan 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0d6aab7930](https://linux-hardware.org/?probe=0d6aab7930) | Jan 01, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [8317742b36](https://linux-hardware.org/?probe=8317742b36) | Jan 01, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [255ef3cc1a](https://linux-hardware.org/?probe=255ef3cc1a) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [036e5ba88c](https://linux-hardware.org/?probe=036e5ba88c) | Jan 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [206e0d977a](https://linux-hardware.org/?probe=206e0d977a) | Dec 31, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [2ddd424f94](https://linux-hardware.org/?probe=2ddd424f94) | Dec 31, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [65aab50b2c](https://linux-hardware.org/?probe=65aab50b2c) | Dec 31, 2021 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0f92fab3db](https://linux-hardware.org/?probe=0f92fab3db) | Dec 31, 2021 |
| Toshiba       | Satellite P850              | Notebook    | [757fbcaab1](https://linux-hardware.org/?probe=757fbcaab1) | Dec 31, 2021 |
| Dell          | Inspiron 5557               | Notebook    | [53d769eaf7](https://linux-hardware.org/?probe=53d769eaf7) | Dec 31, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [bdf0263352](https://linux-hardware.org/?probe=bdf0263352) | Dec 31, 2021 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [c63ae72882](https://linux-hardware.org/?probe=c63ae72882) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | Desktop     | [5407438c6e](https://linux-hardware.org/?probe=5407438c6e) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | Desktop     | [0b80d9da29](https://linux-hardware.org/?probe=0b80d9da29) | Dec 30, 2021 |
| Gigabyte      | H61M-DS2                    | All in one  | [64741af4ef](https://linux-hardware.org/?probe=64741af4ef) | Dec 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [36a412db42](https://linux-hardware.org/?probe=36a412db42) | Dec 29, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [5c4181f9b7](https://linux-hardware.org/?probe=5c4181f9b7) | Dec 29, 2021 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [bd290bc56d](https://linux-hardware.org/?probe=bd290bc56d) | Dec 29, 2021 |
| Alienware     | M17xR3                      | Notebook    | [be8fd9059b](https://linux-hardware.org/?probe=be8fd9059b) | Dec 29, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [bda1b240c9](https://linux-hardware.org/?probe=bda1b240c9) | Dec 28, 2021 |
| Microsoft     | Surface Laptop 3            | Tablet      | [162da90cc6](https://linux-hardware.org/?probe=162da90cc6) | Dec 28, 2021 |
| Schenker      | XMG CORE (REN/E21)          | Notebook    | [850f9a55d7](https://linux-hardware.org/?probe=850f9a55d7) | Dec 28, 2021 |
| MSI           | B150M PRO-VDH               | Desktop     | [6af03f4abc](https://linux-hardware.org/?probe=6af03f4abc) | Dec 28, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [becfdd4806](https://linux-hardware.org/?probe=becfdd4806) | Dec 28, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [a210566e0d](https://linux-hardware.org/?probe=a210566e0d) | Dec 27, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [e3a30bf51f](https://linux-hardware.org/?probe=e3a30bf51f) | Dec 27, 2021 |
| Samsung       | 900X3G                      | Notebook    | [2fb7be579f](https://linux-hardware.org/?probe=2fb7be579f) | Dec 27, 2021 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [59a5f5e5c1](https://linux-hardware.org/?probe=59a5f5e5c1) | Dec 27, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [feb833c87a](https://linux-hardware.org/?probe=feb833c87a) | Dec 27, 2021 |
| HP            | ZBook 14                    | Notebook    | [456906dfff](https://linux-hardware.org/?probe=456906dfff) | Dec 27, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [ea1a58e848](https://linux-hardware.org/?probe=ea1a58e848) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [661d4c5b99](https://linux-hardware.org/?probe=661d4c5b99) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [9257b6fa8f](https://linux-hardware.org/?probe=9257b6fa8f) | Dec 26, 2021 |
| HP            | 1998                        | Desktop     | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [c7fcfb6f2a](https://linux-hardware.org/?probe=c7fcfb6f2a) | Dec 25, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | Notebook    | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| HP            | 3047h                       | Desktop     | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c3905a26bc](https://linux-hardware.org/?probe=c3905a26bc) | Dec 24, 2021 |
| Dell          | Precision M4700             | Notebook    | [82ba56cc90](https://linux-hardware.org/?probe=82ba56cc90) | Dec 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [b47d00c36a](https://linux-hardware.org/?probe=b47d00c36a) | Dec 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [35af56c083](https://linux-hardware.org/?probe=35af56c083) | Dec 24, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b690600862](https://linux-hardware.org/?probe=b690600862) | Dec 24, 2021 |
| HP            | ZBook 15                    | Notebook    | [57cb28cc81](https://linux-hardware.org/?probe=57cb28cc81) | Dec 24, 2021 |
| Acer          | Aspire 5740                 | Notebook    | [baf5d23f31](https://linux-hardware.org/?probe=baf5d23f31) | Dec 24, 2021 |
| Dell          | Latitude E7470              | Notebook    | [e712cd258c](https://linux-hardware.org/?probe=e712cd258c) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Microsoft     | Surface Go 3                | Tablet      | [6b6ac41923](https://linux-hardware.org/?probe=6b6ac41923) | Dec 23, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [f3b0f91998](https://linux-hardware.org/?probe=f3b0f91998) | Dec 23, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ec762046b0](https://linux-hardware.org/?probe=ec762046b0) | Dec 23, 2021 |
| Dell          | 0Y56T3 A00                  | Desktop     | [456cb4ebcc](https://linux-hardware.org/?probe=456cb4ebcc) | Dec 23, 2021 |
| Timi          | RedmiBook 16                | Notebook    | [c9cd395256](https://linux-hardware.org/?probe=c9cd395256) | Dec 23, 2021 |
| HP            | 1494                        | Desktop     | [690d2204ea](https://linux-hardware.org/?probe=690d2204ea) | Dec 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| Intel         | X79 V1.3                    | Desktop     | [fbd3ea5fee](https://linux-hardware.org/?probe=fbd3ea5fee) | Dec 23, 2021 |
| Schenker T... | VIA13                       | Notebook    | [30bd5ce366](https://linux-hardware.org/?probe=30bd5ce366) | Dec 22, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [99e4c4339b](https://linux-hardware.org/?probe=99e4c4339b) | Dec 22, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [4b20c43b53](https://linux-hardware.org/?probe=4b20c43b53) | Dec 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| ASUSTek       | TUF GAMING B560M-PLUS       | Desktop     | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| MSI           | GE76 Raider 10UE            | Notebook    | [84342785a9](https://linux-hardware.org/?probe=84342785a9) | Dec 22, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [352c2b8493](https://linux-hardware.org/?probe=352c2b8493) | Dec 22, 2021 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [a187b5a5da](https://linux-hardware.org/?probe=a187b5a5da) | Dec 21, 2021 |
| Dell          | Precision M4700             | Notebook    | [42db3d0b71](https://linux-hardware.org/?probe=42db3d0b71) | Dec 21, 2021 |
| Dell          | Precision M3800             | Notebook    | [3f67f81b54](https://linux-hardware.org/?probe=3f67f81b54) | Dec 21, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [2ebe7aff5f](https://linux-hardware.org/?probe=2ebe7aff5f) | Dec 21, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [28771b0751](https://linux-hardware.org/?probe=28771b0751) | Dec 21, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [73dda192d5](https://linux-hardware.org/?probe=73dda192d5) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [b6372cc6a4](https://linux-hardware.org/?probe=b6372cc6a4) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d5585257e](https://linux-hardware.org/?probe=3d5585257e) | Dec 20, 2021 |
| Google        | Edgar                       | Notebook    | [dc1b8b8c81](https://linux-hardware.org/?probe=dc1b8b8c81) | Dec 20, 2021 |
| Google        | Edgar                       | Notebook    | [96597eb5fd](https://linux-hardware.org/?probe=96597eb5fd) | Dec 20, 2021 |
| MSI           | GS70 6QE                    | Notebook    | [7b24bd01d3](https://linux-hardware.org/?probe=7b24bd01d3) | Dec 20, 2021 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [8b7026e04a](https://linux-hardware.org/?probe=8b7026e04a) | Dec 20, 2021 |
| UNIQCELL      | Q15.6                       | Notebook    | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| Dell          | Latitude XT3                | Notebook    | [8db51f70a2](https://linux-hardware.org/?probe=8db51f70a2) | Dec 19, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [f33ca54f97](https://linux-hardware.org/?probe=f33ca54f97) | Dec 19, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [190dd03fd5](https://linux-hardware.org/?probe=190dd03fd5) | Dec 19, 2021 |
| Dell          | Precision M4700             | Notebook    | [cb8274d390](https://linux-hardware.org/?probe=cb8274d390) | Dec 19, 2021 |
| Acer          | Unknown                     | Notebook    | [21b566f81d](https://linux-hardware.org/?probe=21b566f81d) | Dec 19, 2021 |
| MSI           | A78M-E45 V2                 | Desktop     | [abed6d2431](https://linux-hardware.org/?probe=abed6d2431) | Dec 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [69570e76ba](https://linux-hardware.org/?probe=69570e76ba) | Dec 19, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d38d7f8ea2](https://linux-hardware.org/?probe=d38d7f8ea2) | Dec 18, 2021 |
| HP            | 8169                        | Desktop     | [ed47c6784c](https://linux-hardware.org/?probe=ed47c6784c) | Dec 18, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bc76e4bc78](https://linux-hardware.org/?probe=bc76e4bc78) | Dec 18, 2021 |
| Dell          | Latitude D630               | Notebook    | [ef872c1744](https://linux-hardware.org/?probe=ef872c1744) | Dec 18, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [9a24ef697f](https://linux-hardware.org/?probe=9a24ef697f) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2268e18a25](https://linux-hardware.org/?probe=2268e18a25) | Dec 18, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [2f8a6719a1](https://linux-hardware.org/?probe=2f8a6719a1) | Dec 18, 2021 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [13bfd7bbd2](https://linux-hardware.org/?probe=13bfd7bbd2) | Dec 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [856134876d](https://linux-hardware.org/?probe=856134876d) | Dec 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [5d09272eb0](https://linux-hardware.org/?probe=5d09272eb0) | Dec 17, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01b4efe7c0](https://linux-hardware.org/?probe=01b4efe7c0) | Dec 17, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [66a87b529d](https://linux-hardware.org/?probe=66a87b529d) | Dec 17, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [bd3d222214](https://linux-hardware.org/?probe=bd3d222214) | Dec 17, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [bfe957f66c](https://linux-hardware.org/?probe=bfe957f66c) | Dec 17, 2021 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [952c6df001](https://linux-hardware.org/?probe=952c6df001) | Dec 16, 2021 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [376eb1624e](https://linux-hardware.org/?probe=376eb1624e) | Dec 16, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [83c339b963](https://linux-hardware.org/?probe=83c339b963) | Dec 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b7b779b709](https://linux-hardware.org/?probe=b7b779b709) | Dec 16, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [87041f9c2d](https://linux-hardware.org/?probe=87041f9c2d) | Dec 16, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [7331c7f2ee](https://linux-hardware.org/?probe=7331c7f2ee) | Dec 16, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [f3f7e374e1](https://linux-hardware.org/?probe=f3f7e374e1) | Dec 16, 2021 |
| Dell          | Latitude D830               | Notebook    | [5c79754a4d](https://linux-hardware.org/?probe=5c79754a4d) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| AMI           | Intel                       | Notebook    | [5d6b643426](https://linux-hardware.org/?probe=5d6b643426) | Dec 15, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [314899553a](https://linux-hardware.org/?probe=314899553a) | Dec 15, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [f5d1de8ec2](https://linux-hardware.org/?probe=f5d1de8ec2) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [e57dc7794c](https://linux-hardware.org/?probe=e57dc7794c) | Dec 15, 2021 |
| Schenker      | XMG CORE 15(M20, RTX 206... | Notebook    | [abe037b9c1](https://linux-hardware.org/?probe=abe037b9c1) | Dec 15, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9ea3459352](https://linux-hardware.org/?probe=9ea3459352) | Dec 15, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [3d9f848d7e](https://linux-hardware.org/?probe=3d9f848d7e) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0db7a32c32](https://linux-hardware.org/?probe=0db7a32c32) | Dec 15, 2021 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [bcdd9529a6](https://linux-hardware.org/?probe=bcdd9529a6) | Dec 15, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [349550727a](https://linux-hardware.org/?probe=349550727a) | Dec 14, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [e3c15cfedb](https://linux-hardware.org/?probe=e3c15cfedb) | Dec 14, 2021 |
| Sony          | SVS131290S                  | Notebook    | [9dffd4b7f9](https://linux-hardware.org/?probe=9dffd4b7f9) | Dec 14, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [5559a99303](https://linux-hardware.org/?probe=5559a99303) | Dec 14, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [8ba36ff904](https://linux-hardware.org/?probe=8ba36ff904) | Dec 14, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [d0889ec2eb](https://linux-hardware.org/?probe=d0889ec2eb) | Dec 14, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c029d9c42b](https://linux-hardware.org/?probe=c029d9c42b) | Dec 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [f7678361d9](https://linux-hardware.org/?probe=f7678361d9) | Dec 14, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [da23db2916](https://linux-hardware.org/?probe=da23db2916) | Dec 13, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [9e321117dd](https://linux-hardware.org/?probe=9e321117dd) | Dec 13, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [28e1968e2a](https://linux-hardware.org/?probe=28e1968e2a) | Dec 13, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [f87ff266d6](https://linux-hardware.org/?probe=f87ff266d6) | Dec 13, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [38f2bc6cc7](https://linux-hardware.org/?probe=38f2bc6cc7) | Dec 13, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [59932384de](https://linux-hardware.org/?probe=59932384de) | Dec 13, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [711aa97225](https://linux-hardware.org/?probe=711aa97225) | Dec 13, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [6df961216e](https://linux-hardware.org/?probe=6df961216e) | Dec 12, 2021 |
| MSI           | GE66 Raider 10SGS           | Notebook    | [f8dff3c5c7](https://linux-hardware.org/?probe=f8dff3c5c7) | Dec 12, 2021 |
| MSI           | GE66 Raider 10SGS           | Notebook    | [abbd7d0c07](https://linux-hardware.org/?probe=abbd7d0c07) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | Notebook    | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [e60b9ed6dd](https://linux-hardware.org/?probe=e60b9ed6dd) | Dec 12, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3b60828a9a](https://linux-hardware.org/?probe=3b60828a9a) | Dec 11, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [918008ea2a](https://linux-hardware.org/?probe=918008ea2a) | Dec 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP            | ZBook 15                    | Notebook    | [cb2487cb67](https://linux-hardware.org/?probe=cb2487cb67) | Dec 11, 2021 |
| Huanan        | X79                         | Desktop     | [86c899a9ae](https://linux-hardware.org/?probe=86c899a9ae) | Dec 11, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a50dca2bf2](https://linux-hardware.org/?probe=a50dca2bf2) | Dec 10, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [4afc969d1d](https://linux-hardware.org/?probe=4afc969d1d) | Dec 10, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [ed02327600](https://linux-hardware.org/?probe=ed02327600) | Dec 10, 2021 |
| ASRock        | QC6000M                     | Desktop     | [3475206cb1](https://linux-hardware.org/?probe=3475206cb1) | Dec 10, 2021 |
| HP            | ZBook 15                    | Notebook    | [c0d2e24505](https://linux-hardware.org/?probe=c0d2e24505) | Dec 10, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [89dd614f98](https://linux-hardware.org/?probe=89dd614f98) | Dec 09, 2021 |
| MSI           | B365M PLUS                  | Desktop     | [2b5c7216f7](https://linux-hardware.org/?probe=2b5c7216f7) | Dec 08, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [aef037d3c7](https://linux-hardware.org/?probe=aef037d3c7) | Dec 08, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ff3ed0ea84](https://linux-hardware.org/?probe=ff3ed0ea84) | Dec 08, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [e45d70e70f](https://linux-hardware.org/?probe=e45d70e70f) | Dec 08, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [738c57ae47](https://linux-hardware.org/?probe=738c57ae47) | Dec 08, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [3c204fb3ad](https://linux-hardware.org/?probe=3c204fb3ad) | Dec 08, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [9b11e98d14](https://linux-hardware.org/?probe=9b11e98d14) | Dec 08, 2021 |
| Acer          | Spin SP315-51               | Convertible | [b0024d427d](https://linux-hardware.org/?probe=b0024d427d) | Dec 08, 2021 |
| Toshiba       | Satellite C855D             | Notebook    | [1ee3f1b59d](https://linux-hardware.org/?probe=1ee3f1b59d) | Dec 08, 2021 |
| Acer          | Aspire E1-530               | Notebook    | [e3ece66b6e](https://linux-hardware.org/?probe=e3ece66b6e) | Dec 08, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [d580dc1bf8](https://linux-hardware.org/?probe=d580dc1bf8) | Dec 08, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Acer          | Nitro AN515-41              | Notebook    | [f23b6c43d7](https://linux-hardware.org/?probe=f23b6c43d7) | Dec 07, 2021 |
| ASUSTek       | G20AJ                       | Desktop     | [8f17fe0c1e](https://linux-hardware.org/?probe=8f17fe0c1e) | Dec 07, 2021 |
| Acer          | Nitro AN515-41              | Notebook    | [5e621815cc](https://linux-hardware.org/?probe=5e621815cc) | Dec 07, 2021 |
| Acer          | Nitro AN515-41              | Notebook    | [21c3c1ac8c](https://linux-hardware.org/?probe=21c3c1ac8c) | Dec 07, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [7378f60dce](https://linux-hardware.org/?probe=7378f60dce) | Dec 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [04fc6209b4](https://linux-hardware.org/?probe=04fc6209b4) | Dec 07, 2021 |
| Toshiba       | Satellite P850              | Notebook    | [e9d0c6b6fa](https://linux-hardware.org/?probe=e9d0c6b6fa) | Dec 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | Notebook    | [027f8c5de6](https://linux-hardware.org/?probe=027f8c5de6) | Dec 06, 2021 |
| Lenovo        | ThinkPad L390 20NR0013SP    | Notebook    | [493a0cc63e](https://linux-hardware.org/?probe=493a0cc63e) | Dec 06, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [1c81e561e7](https://linux-hardware.org/?probe=1c81e561e7) | Dec 06, 2021 |
| Dell          | Inspiron 5482               | Convertible | [03eafd14da](https://linux-hardware.org/?probe=03eafd14da) | Dec 05, 2021 |
| Dell          | Inspiron 5482               | Convertible | [c1bb3c51d7](https://linux-hardware.org/?probe=c1bb3c51d7) | Dec 05, 2021 |
| Jumper        | EZpad                       | Tablet      | [6599d3c782](https://linux-hardware.org/?probe=6599d3c782) | Dec 05, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [0d989a4f1f](https://linux-hardware.org/?probe=0d989a4f1f) | Dec 05, 2021 |
| HP            | 2B2C                        | Desktop     | [7a51474f1a](https://linux-hardware.org/?probe=7a51474f1a) | Dec 05, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [f9ceff4572](https://linux-hardware.org/?probe=f9ceff4572) | Dec 04, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [3e9bd01c9e](https://linux-hardware.org/?probe=3e9bd01c9e) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [a3209e0ed1](https://linux-hardware.org/?probe=a3209e0ed1) | Dec 04, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [b8813e5654](https://linux-hardware.org/?probe=b8813e5654) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [d38dac9942](https://linux-hardware.org/?probe=d38dac9942) | Dec 04, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [126b0a6c4c](https://linux-hardware.org/?probe=126b0a6c4c) | Dec 04, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [50d31f61ab](https://linux-hardware.org/?probe=50d31f61ab) | Dec 04, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [62fe653f0b](https://linux-hardware.org/?probe=62fe653f0b) | Dec 03, 2021 |
| Apple         | MacBook8,1                  | Notebook    | [8cc90173e7](https://linux-hardware.org/?probe=8cc90173e7) | Dec 03, 2021 |
| MSI           | GL65 Leopard 9SCXR          | Notebook    | [53bdcf665a](https://linux-hardware.org/?probe=53bdcf665a) | Dec 03, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [633a8b9f67](https://linux-hardware.org/?probe=633a8b9f67) | Dec 03, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [cbffb1c69a](https://linux-hardware.org/?probe=cbffb1c69a) | Dec 03, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [576a21c925](https://linux-hardware.org/?probe=576a21c925) | Dec 03, 2021 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [c9d1041224](https://linux-hardware.org/?probe=c9d1041224) | Dec 03, 2021 |
| Pegatron      | 2AD2A                       | Desktop     | [62775fc64d](https://linux-hardware.org/?probe=62775fc64d) | Dec 03, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [1302ff09b2](https://linux-hardware.org/?probe=1302ff09b2) | Dec 03, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [54f7f8dbfa](https://linux-hardware.org/?probe=54f7f8dbfa) | Dec 03, 2021 |
| HP            | Notebook                    | Notebook    | [0582d239e9](https://linux-hardware.org/?probe=0582d239e9) | Dec 03, 2021 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [ca0a1ff745](https://linux-hardware.org/?probe=ca0a1ff745) | Dec 02, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | Notebook    | [e85a481d36](https://linux-hardware.org/?probe=e85a481d36) | Dec 02, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [ffee0a8443](https://linux-hardware.org/?probe=ffee0a8443) | Dec 02, 2021 |
| Timi          | RedmiBook Pro 15            | Notebook    | [501235754e](https://linux-hardware.org/?probe=501235754e) | Dec 02, 2021 |
| Timi          | RedmiBook Pro 15            | Notebook    | [ce5fda447e](https://linux-hardware.org/?probe=ce5fda447e) | Dec 02, 2021 |
| Intel         | X99 V1.x                    | Desktop     | [727aef8ed6](https://linux-hardware.org/?probe=727aef8ed6) | Dec 02, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [51a3b8e589](https://linux-hardware.org/?probe=51a3b8e589) | Dec 02, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [cd99bbcc4d](https://linux-hardware.org/?probe=cd99bbcc4d) | Dec 02, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [069ca6ffe2](https://linux-hardware.org/?probe=069ca6ffe2) | Dec 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [55a4727c30](https://linux-hardware.org/?probe=55a4727c30) | Dec 01, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e2d4b12fef](https://linux-hardware.org/?probe=e2d4b12fef) | Dec 01, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [0a3e70b938](https://linux-hardware.org/?probe=0a3e70b938) | Dec 01, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [57587ffa8e](https://linux-hardware.org/?probe=57587ffa8e) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [6807edf501](https://linux-hardware.org/?probe=6807edf501) | Dec 01, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [6522739036](https://linux-hardware.org/?probe=6522739036) | Dec 01, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [3438f86ded](https://linux-hardware.org/?probe=3438f86ded) | Dec 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4855fe75cb](https://linux-hardware.org/?probe=4855fe75cb) | Dec 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [7fe28eead2](https://linux-hardware.org/?probe=7fe28eead2) | Nov 30, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [bf860936aa](https://linux-hardware.org/?probe=bf860936aa) | Nov 30, 2021 |
| Dell          | Latitude 5285               | Notebook    | [39706b5a48](https://linux-hardware.org/?probe=39706b5a48) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [fe3d4f5bc1](https://linux-hardware.org/?probe=fe3d4f5bc1) | Nov 30, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9feb65b15d](https://linux-hardware.org/?probe=9feb65b15d) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6762543fa8](https://linux-hardware.org/?probe=6762543fa8) | Nov 30, 2021 |
| HP            | 2000                        | Notebook    | [e9ba2ea37c](https://linux-hardware.org/?probe=e9ba2ea37c) | Nov 30, 2021 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [2dbb4db154](https://linux-hardware.org/?probe=2dbb4db154) | Nov 29, 2021 |
| Gigabyte      | Z490 AORUS XTREME           | Desktop     | [e964d05300](https://linux-hardware.org/?probe=e964d05300) | Nov 29, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [c81c74d820](https://linux-hardware.org/?probe=c81c74d820) | Nov 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [d41428d9f6](https://linux-hardware.org/?probe=d41428d9f6) | Nov 29, 2021 |
| Acer          | Predator PT315-51           | Notebook    | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| Toshiba       | Satellite C50-A             | Notebook    | [9b0318cb9b](https://linux-hardware.org/?probe=9b0318cb9b) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [ab1b265412](https://linux-hardware.org/?probe=ab1b265412) | Nov 29, 2021 |
| LG Electro... | R510                        | Notebook    | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [0e07acbea7](https://linux-hardware.org/?probe=0e07acbea7) | Nov 28, 2021 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [6c61c57e1d](https://linux-hardware.org/?probe=6c61c57e1d) | Nov 28, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [aa9b2c7788](https://linux-hardware.org/?probe=aa9b2c7788) | Nov 28, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6b4fb72d69](https://linux-hardware.org/?probe=6b4fb72d69) | Nov 28, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470s 20HF003QU... | Notebook    | [891d5afaba](https://linux-hardware.org/?probe=891d5afaba) | Nov 28, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [0d716e0681](https://linux-hardware.org/?probe=0d716e0681) | Nov 28, 2021 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [f51a3541c8](https://linux-hardware.org/?probe=f51a3541c8) | Nov 28, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [f34bca522a](https://linux-hardware.org/?probe=f34bca522a) | Nov 28, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [0cb5ca7e51](https://linux-hardware.org/?probe=0cb5ca7e51) | Nov 28, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [af5cb748c4](https://linux-hardware.org/?probe=af5cb748c4) | Nov 27, 2021 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [a754ed7b33](https://linux-hardware.org/?probe=a754ed7b33) | Nov 27, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [f6d9c481bd](https://linux-hardware.org/?probe=f6d9c481bd) | Nov 27, 2021 |
| Lenovo        | ThinkPad T460s 20F9S08Y0... | Notebook    | [c2437b4887](https://linux-hardware.org/?probe=c2437b4887) | Nov 27, 2021 |
| Lenovo        | ThinkPad T460s 20F9S08Y0... | Notebook    | [a339e0ba96](https://linux-hardware.org/?probe=a339e0ba96) | Nov 27, 2021 |
| Schenker      | XMG CORE 15(M20, RTX 206... | Notebook    | [390eb51b5f](https://linux-hardware.org/?probe=390eb51b5f) | Nov 27, 2021 |
| Schenker      | XMG CORE 15(M20, RTX 206... | Notebook    | [42e34578e5](https://linux-hardware.org/?probe=42e34578e5) | Nov 27, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4bbdbb4261](https://linux-hardware.org/?probe=4bbdbb4261) | Nov 27, 2021 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [7280b29922](https://linux-hardware.org/?probe=7280b29922) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5410966f9e](https://linux-hardware.org/?probe=5410966f9e) | Nov 27, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [942114b7ed](https://linux-hardware.org/?probe=942114b7ed) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [ab87a28736](https://linux-hardware.org/?probe=ab87a28736) | Nov 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9c3cc382a3](https://linux-hardware.org/?probe=9c3cc382a3) | Nov 26, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [e7cfc4b381](https://linux-hardware.org/?probe=e7cfc4b381) | Nov 25, 2021 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [abcb0a70cd](https://linux-hardware.org/?probe=abcb0a70cd) | Nov 25, 2021 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [6443905b94](https://linux-hardware.org/?probe=6443905b94) | Nov 25, 2021 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [0bf1567918](https://linux-hardware.org/?probe=0bf1567918) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [4d074b886e](https://linux-hardware.org/?probe=4d074b886e) | Nov 25, 2021 |
| ASRock        | Z370 Taichi                 | Desktop     | [f0deb8e1ab](https://linux-hardware.org/?probe=f0deb8e1ab) | Nov 25, 2021 |
| HP            | 1589                        | Desktop     | [51a24550cd](https://linux-hardware.org/?probe=51a24550cd) | Nov 25, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1fbb0d4bba](https://linux-hardware.org/?probe=1fbb0d4bba) | Nov 25, 2021 |
| MSI           | GE66 Raider 11UG            | Notebook    | [389f917041](https://linux-hardware.org/?probe=389f917041) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Acer          | Aspire X1430G               | Desktop     | [de61443dc4](https://linux-hardware.org/?probe=de61443dc4) | Nov 24, 2021 |
| Acer          | Aspire X1430G               | Desktop     | [80780aa6df](https://linux-hardware.org/?probe=80780aa6df) | Nov 24, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [3e75772394](https://linux-hardware.org/?probe=3e75772394) | Nov 24, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2ee3a41100](https://linux-hardware.org/?probe=2ee3a41100) | Nov 24, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [dbf2659c98](https://linux-hardware.org/?probe=dbf2659c98) | Nov 23, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [81a6212074](https://linux-hardware.org/?probe=81a6212074) | Nov 23, 2021 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [35534f78a5](https://linux-hardware.org/?probe=35534f78a5) | Nov 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f5cadf9b2e](https://linux-hardware.org/?probe=f5cadf9b2e) | Nov 23, 2021 |
| Lenovo        | ThinkPad T440s 20AQ004UR... | Notebook    | [06d4eedaae](https://linux-hardware.org/?probe=06d4eedaae) | Nov 23, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [7e3d18d75e](https://linux-hardware.org/?probe=7e3d18d75e) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [b8d8d8e85e](https://linux-hardware.org/?probe=b8d8d8e85e) | Nov 23, 2021 |
| ASUSTek       | TP300LJ                     | Notebook    | [f685935861](https://linux-hardware.org/?probe=f685935861) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [bc6d62f60a](https://linux-hardware.org/?probe=bc6d62f60a) | Nov 22, 2021 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [a108397b13](https://linux-hardware.org/?probe=a108397b13) | Nov 22, 2021 |
| Gigabyte      | B460M GAMING HD             | Desktop     | [b15ec9f086](https://linux-hardware.org/?probe=b15ec9f086) | Nov 21, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [9aee4c877d](https://linux-hardware.org/?probe=9aee4c877d) | Nov 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [2443700844](https://linux-hardware.org/?probe=2443700844) | Nov 21, 2021 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [de03a1c3ee](https://linux-hardware.org/?probe=de03a1c3ee) | Nov 21, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [549ab62c90](https://linux-hardware.org/?probe=549ab62c90) | Nov 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [c9ecfca27b](https://linux-hardware.org/?probe=c9ecfca27b) | Nov 21, 2021 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [cc3c046ba9](https://linux-hardware.org/?probe=cc3c046ba9) | Nov 21, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [8cd3929553](https://linux-hardware.org/?probe=8cd3929553) | Nov 21, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Lenovo        | IdeaPadFlex Pro-13IKB 81... | Convertible | [c4653262b0](https://linux-hardware.org/?probe=c4653262b0) | Nov 21, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [09569b7a42](https://linux-hardware.org/?probe=09569b7a42) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059be1d157](https://linux-hardware.org/?probe=059be1d157) | Nov 20, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [ccd0498c9b](https://linux-hardware.org/?probe=ccd0498c9b) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | Desktop     | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [15bcf4b84f](https://linux-hardware.org/?probe=15bcf4b84f) | Nov 20, 2021 |
| MSI           | H81M-P33                    | Desktop     | [cc4ed13747](https://linux-hardware.org/?probe=cc4ed13747) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [bd795eb1c2](https://linux-hardware.org/?probe=bd795eb1c2) | Nov 19, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [0a32a05b5c](https://linux-hardware.org/?probe=0a32a05b5c) | Nov 19, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [633630572c](https://linux-hardware.org/?probe=633630572c) | Nov 18, 2021 |
| HP            | 82F2                        | Desktop     | [864b1b1731](https://linux-hardware.org/?probe=864b1b1731) | Nov 18, 2021 |
| Sony          | VPCEB2Z1E                   | Notebook    | [95014a6fcd](https://linux-hardware.org/?probe=95014a6fcd) | Nov 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [dceb2debdb](https://linux-hardware.org/?probe=dceb2debdb) | Nov 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9690c12aa3](https://linux-hardware.org/?probe=9690c12aa3) | Nov 18, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [2dc50bf90a](https://linux-hardware.org/?probe=2dc50bf90a) | Nov 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [2b0946038d](https://linux-hardware.org/?probe=2b0946038d) | Nov 18, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [019ff66515](https://linux-hardware.org/?probe=019ff66515) | Nov 18, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [e19037ab0d](https://linux-hardware.org/?probe=e19037ab0d) | Nov 18, 2021 |
| ASUSTek       | X550LA                      | Notebook    | [678826613e](https://linux-hardware.org/?probe=678826613e) | Nov 18, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [c7712aabce](https://linux-hardware.org/?probe=c7712aabce) | Nov 18, 2021 |
| Dell          | Vostro 2520                 | Notebook    | [b4ab72ffc4](https://linux-hardware.org/?probe=b4ab72ffc4) | Nov 18, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2e5006f24c](https://linux-hardware.org/?probe=2e5006f24c) | Nov 18, 2021 |
| Sony          | VPCEB2Z1E                   | Notebook    | [634e6f2784](https://linux-hardware.org/?probe=634e6f2784) | Nov 17, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b5f15b725f](https://linux-hardware.org/?probe=b5f15b725f) | Nov 17, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b378b1b259](https://linux-hardware.org/?probe=b378b1b259) | Nov 17, 2021 |
| Lenovo        | ThinkPad X230 2324FV6       | Notebook    | [92c4db6150](https://linux-hardware.org/?probe=92c4db6150) | Nov 17, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [facd9bfb3a](https://linux-hardware.org/?probe=facd9bfb3a) | Nov 17, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [0631623e1e](https://linux-hardware.org/?probe=0631623e1e) | Nov 17, 2021 |
| MSI           | H310M PRO-VDH               | Desktop     | [645d9fd97e](https://linux-hardware.org/?probe=645d9fd97e) | Nov 17, 2021 |
| MSI           | H310M PRO-VDH               | Desktop     | [d4f2aa5324](https://linux-hardware.org/?probe=d4f2aa5324) | Nov 17, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [dfdeaca88b](https://linux-hardware.org/?probe=dfdeaca88b) | Nov 16, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [e1597401db](https://linux-hardware.org/?probe=e1597401db) | Nov 16, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [cb2fba28ed](https://linux-hardware.org/?probe=cb2fba28ed) | Nov 16, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [85c3572da6](https://linux-hardware.org/?probe=85c3572da6) | Nov 16, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [79eb5a8344](https://linux-hardware.org/?probe=79eb5a8344) | Nov 16, 2021 |
| HP            | 250 G3                      | Notebook    | [8d370cbb27](https://linux-hardware.org/?probe=8d370cbb27) | Nov 16, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [348b6bc909](https://linux-hardware.org/?probe=348b6bc909) | Nov 16, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e4375ff53a](https://linux-hardware.org/?probe=e4375ff53a) | Nov 16, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [99fc9a854f](https://linux-hardware.org/?probe=99fc9a854f) | Nov 16, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [8109914a61](https://linux-hardware.org/?probe=8109914a61) | Nov 16, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b8aa4af077](https://linux-hardware.org/?probe=b8aa4af077) | Nov 16, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [3ffb20130b](https://linux-hardware.org/?probe=3ffb20130b) | Nov 16, 2021 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [1ec9076975](https://linux-hardware.org/?probe=1ec9076975) | Nov 16, 2021 |
| Acer          | Nitro NP515-51              | Convertible | [8dc2269951](https://linux-hardware.org/?probe=8dc2269951) | Nov 16, 2021 |
| Acer          | Nitro NP515-51              | Convertible | [d43af77dd1](https://linux-hardware.org/?probe=d43af77dd1) | Nov 16, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9070f5cc5f](https://linux-hardware.org/?probe=9070f5cc5f) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| HP            | 250 G3                      | Notebook    | [fb9fe2f3fb](https://linux-hardware.org/?probe=fb9fe2f3fb) | Nov 16, 2021 |
| Dell          | Latitude D630               | Notebook    | [1494826be4](https://linux-hardware.org/?probe=1494826be4) | Nov 15, 2021 |
| Samsung       | Q430/Q530                   | Notebook    | [521c5d5ad1](https://linux-hardware.org/?probe=521c5d5ad1) | Nov 15, 2021 |
| Dell          | Inspiron 7586               | Convertible | [ee98ffad33](https://linux-hardware.org/?probe=ee98ffad33) | Nov 15, 2021 |
| Samsung       | Q430/Q530                   | Notebook    | [46694a7063](https://linux-hardware.org/?probe=46694a7063) | Nov 15, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [9d8a722c70](https://linux-hardware.org/?probe=9d8a722c70) | Nov 15, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e322467b68](https://linux-hardware.org/?probe=e322467b68) | Nov 15, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [960385cce0](https://linux-hardware.org/?probe=960385cce0) | Nov 15, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [11bbaa8e59](https://linux-hardware.org/?probe=11bbaa8e59) | Nov 15, 2021 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [81b679850b](https://linux-hardware.org/?probe=81b679850b) | Nov 15, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [89c5a1af70](https://linux-hardware.org/?probe=89c5a1af70) | Nov 15, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [20f3d82708](https://linux-hardware.org/?probe=20f3d82708) | Nov 15, 2021 |
| Acer          | Aspire A517-52              | Notebook    | [b384c8f995](https://linux-hardware.org/?probe=b384c8f995) | Nov 15, 2021 |
| Acer          | Aspire A517-52              | Notebook    | [92fe187f42](https://linux-hardware.org/?probe=92fe187f42) | Nov 15, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [41db42ad22](https://linux-hardware.org/?probe=41db42ad22) | Nov 15, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3346838ebf](https://linux-hardware.org/?probe=3346838ebf) | Nov 14, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [3c66d8c5e4](https://linux-hardware.org/?probe=3c66d8c5e4) | Nov 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [25ce89b0fe](https://linux-hardware.org/?probe=25ce89b0fe) | Nov 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9a7d3c310f](https://linux-hardware.org/?probe=9a7d3c310f) | Nov 14, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [4a568a9bdf](https://linux-hardware.org/?probe=4a568a9bdf) | Nov 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9417ebb46d](https://linux-hardware.org/?probe=9417ebb46d) | Nov 13, 2021 |
| Acer          | Aspire VN7-593G             | Notebook    | [9d5442fe37](https://linux-hardware.org/?probe=9d5442fe37) | Nov 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25fd06c06b](https://linux-hardware.org/?probe=25fd06c06b) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | Notebook    | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| MSI           | 970A-G43                    | Desktop     | [da61ca8b52](https://linux-hardware.org/?probe=da61ca8b52) | Nov 13, 2021 |
| MSI           | 970A-G43                    | Desktop     | [d27f131cce](https://linux-hardware.org/?probe=d27f131cce) | Nov 13, 2021 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [a031da091f](https://linux-hardware.org/?probe=a031da091f) | Nov 13, 2021 |
| Samsung       | 950QDA                      | Convertible | [45d49f2001](https://linux-hardware.org/?probe=45d49f2001) | Nov 13, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [7d4b51e485](https://linux-hardware.org/?probe=7d4b51e485) | Nov 12, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [933234f294](https://linux-hardware.org/?probe=933234f294) | Nov 12, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [655b92ca25](https://linux-hardware.org/?probe=655b92ca25) | Nov 12, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [5a9d6ba46e](https://linux-hardware.org/?probe=5a9d6ba46e) | Nov 12, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [6c0ee3ae74](https://linux-hardware.org/?probe=6c0ee3ae74) | Nov 12, 2021 |
| Pegatron      | 2AD2A                       | Desktop     | [5e251eb093](https://linux-hardware.org/?probe=5e251eb093) | Nov 12, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [f806b413c5](https://linux-hardware.org/?probe=f806b413c5) | Nov 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a42a22a526](https://linux-hardware.org/?probe=a42a22a526) | Nov 11, 2021 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [33c3ae53dc](https://linux-hardware.org/?probe=33c3ae53dc) | Nov 11, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [51777be647](https://linux-hardware.org/?probe=51777be647) | Nov 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [99637e8ed3](https://linux-hardware.org/?probe=99637e8ed3) | Nov 11, 2021 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7b125e4ba6](https://linux-hardware.org/?probe=7b125e4ba6) | Nov 11, 2021 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [b11f112034](https://linux-hardware.org/?probe=b11f112034) | Nov 11, 2021 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [1e07fc1b9d](https://linux-hardware.org/?probe=1e07fc1b9d) | Nov 10, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d0f30ab5d2](https://linux-hardware.org/?probe=d0f30ab5d2) | Nov 10, 2021 |
| Intel         | D945GCL AAD75361-301        | Desktop     | [378e32942d](https://linux-hardware.org/?probe=378e32942d) | Nov 10, 2021 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [6219a911b9](https://linux-hardware.org/?probe=6219a911b9) | Nov 10, 2021 |
| Kanji         | Tamura MAX DUO              | Convertible | [0cff4ea4dd](https://linux-hardware.org/?probe=0cff4ea4dd) | Nov 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [cd42c62b14](https://linux-hardware.org/?probe=cd42c62b14) | Nov 09, 2021 |
| ASUSTek       | X99-A                       | Desktop     | [99d97fbc79](https://linux-hardware.org/?probe=99d97fbc79) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [86ba55d67a](https://linux-hardware.org/?probe=86ba55d67a) | Nov 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a6a6f59d46](https://linux-hardware.org/?probe=a6a6f59d46) | Nov 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3d661ce2df](https://linux-hardware.org/?probe=3d661ce2df) | Nov 09, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a1a9bf0a7a](https://linux-hardware.org/?probe=a1a9bf0a7a) | Nov 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS7R400    | Notebook    | [55f197a179](https://linux-hardware.org/?probe=55f197a179) | Nov 09, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [9ebb713a28](https://linux-hardware.org/?probe=9ebb713a28) | Nov 09, 2021 |
| Lenovo        | IdeaPadFlex Pro-13IKB 81... | Convertible | [55cb0c1190](https://linux-hardware.org/?probe=55cb0c1190) | Nov 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [90ae0f9fe2](https://linux-hardware.org/?probe=90ae0f9fe2) | Nov 09, 2021 |
| Acer          | Aspire XC-230               | Desktop     | [6ccebdc02f](https://linux-hardware.org/?probe=6ccebdc02f) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c0671f26c9](https://linux-hardware.org/?probe=c0671f26c9) | Nov 08, 2021 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [9f4639af3b](https://linux-hardware.org/?probe=9f4639af3b) | Nov 08, 2021 |
| Intel         | D945GCL AAD75361-301        | Desktop     | [510547811c](https://linux-hardware.org/?probe=510547811c) | Nov 08, 2021 |
| Lenovo        | ThinkPad T430 2349Y3D       | Notebook    | [6ce1ddef22](https://linux-hardware.org/?probe=6ce1ddef22) | Nov 08, 2021 |
| Dell          | Latitude E6400              | Notebook    | [8256fe7e99](https://linux-hardware.org/?probe=8256fe7e99) | Nov 08, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [67a720ad20](https://linux-hardware.org/?probe=67a720ad20) | Nov 07, 2021 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [80c808336f](https://linux-hardware.org/?probe=80c808336f) | Nov 07, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [304acea090](https://linux-hardware.org/?probe=304acea090) | Nov 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f7d56c8c6](https://linux-hardware.org/?probe=3f7d56c8c6) | Nov 07, 2021 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [10a403bc34](https://linux-hardware.org/?probe=10a403bc34) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| Dell          | Latitude 5490               | Notebook    | [f74abc0174](https://linux-hardware.org/?probe=f74abc0174) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f4273d4dc1](https://linux-hardware.org/?probe=f4273d4dc1) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [86f7bd9873](https://linux-hardware.org/?probe=86f7bd9873) | Nov 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [9245f5eda7](https://linux-hardware.org/?probe=9245f5eda7) | Nov 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [d0d01dbadf](https://linux-hardware.org/?probe=d0d01dbadf) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8cb9402546](https://linux-hardware.org/?probe=8cb9402546) | Nov 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1ce772933a](https://linux-hardware.org/?probe=1ce772933a) | Nov 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [06c80b3339](https://linux-hardware.org/?probe=06c80b3339) | Nov 05, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [e30e1a1247](https://linux-hardware.org/?probe=e30e1a1247) | Nov 05, 2021 |
| Acer          | Aspire XC-230               | Desktop     | [5ec278c995](https://linux-hardware.org/?probe=5ec278c995) | Nov 05, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [357d456473](https://linux-hardware.org/?probe=357d456473) | Nov 04, 2021 |
| Acer          | Spin SP313-51N              | Convertible | [bb22feca61](https://linux-hardware.org/?probe=bb22feca61) | Nov 04, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [b4285afb59](https://linux-hardware.org/?probe=b4285afb59) | Nov 04, 2021 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [aea87680f8](https://linux-hardware.org/?probe=aea87680f8) | Nov 04, 2021 |
| Google        | Nami                        | Notebook    | [236ff0e1dc](https://linux-hardware.org/?probe=236ff0e1dc) | Nov 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c289308c14](https://linux-hardware.org/?probe=c289308c14) | Nov 04, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [470204d924](https://linux-hardware.org/?probe=470204d924) | Nov 03, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [8686d92d45](https://linux-hardware.org/?probe=8686d92d45) | Nov 03, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [e8ef49b867](https://linux-hardware.org/?probe=e8ef49b867) | Nov 03, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [05eee3d7f5](https://linux-hardware.org/?probe=05eee3d7f5) | Nov 03, 2021 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [8fb2fb886c](https://linux-hardware.org/?probe=8fb2fb886c) | Nov 03, 2021 |
| Timi          | TM1701                      | Notebook    | [350200ef11](https://linux-hardware.org/?probe=350200ef11) | Nov 03, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [7293ff9be8](https://linux-hardware.org/?probe=7293ff9be8) | Nov 02, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [f63e8beb3b](https://linux-hardware.org/?probe=f63e8beb3b) | Nov 02, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [dd56ae94d2](https://linux-hardware.org/?probe=dd56ae94d2) | Nov 02, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [731013ba31](https://linux-hardware.org/?probe=731013ba31) | Nov 02, 2021 |
| Positivo      | C464C                       | Convertible | [9e96f56fdb](https://linux-hardware.org/?probe=9e96f56fdb) | Nov 02, 2021 |
| Sony          | VPCEB2Z1E                   | Notebook    | [b843bc7dd7](https://linux-hardware.org/?probe=b843bc7dd7) | Nov 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c911492ba6](https://linux-hardware.org/?probe=c911492ba6) | Nov 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [d35b1ab829](https://linux-hardware.org/?probe=d35b1ab829) | Nov 01, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [f8a7da7b89](https://linux-hardware.org/?probe=f8a7da7b89) | Nov 01, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [0f08b62632](https://linux-hardware.org/?probe=0f08b62632) | Nov 01, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [f96e0bb7fc](https://linux-hardware.org/?probe=f96e0bb7fc) | Nov 01, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4ecaef699b](https://linux-hardware.org/?probe=4ecaef699b) | Nov 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [b75ca3ba11](https://linux-hardware.org/?probe=b75ca3ba11) | Nov 01, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8506f2e02d](https://linux-hardware.org/?probe=8506f2e02d) | Nov 01, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [da5e2f59cc](https://linux-hardware.org/?probe=da5e2f59cc) | Nov 01, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [44acfe85a5](https://linux-hardware.org/?probe=44acfe85a5) | Oct 31, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [491d1a96cc](https://linux-hardware.org/?probe=491d1a96cc) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [4eb6b00cac](https://linux-hardware.org/?probe=4eb6b00cac) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c9153e029e](https://linux-hardware.org/?probe=c9153e029e) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2bf6813ad9](https://linux-hardware.org/?probe=2bf6813ad9) | Oct 31, 2021 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f3b1068713](https://linux-hardware.org/?probe=f3b1068713) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [3f7a2585fe](https://linux-hardware.org/?probe=3f7a2585fe) | Oct 31, 2021 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [2fca11cf26](https://linux-hardware.org/?probe=2fca11cf26) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [e6958a71d6](https://linux-hardware.org/?probe=e6958a71d6) | Oct 31, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [8d45d9544e](https://linux-hardware.org/?probe=8d45d9544e) | Oct 31, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b9c2fec8aa](https://linux-hardware.org/?probe=b9c2fec8aa) | Oct 30, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| MSI           | Z170A SLI PLUS              | Desktop     | [2d4144d0b9](https://linux-hardware.org/?probe=2d4144d0b9) | Oct 30, 2021 |
| Dell          | Inspiron 5421               | Notebook    | [d70e2b74d0](https://linux-hardware.org/?probe=d70e2b74d0) | Oct 30, 2021 |
| Dell          | Inspiron 5421               | Notebook    | [d4d3ebf711](https://linux-hardware.org/?probe=d4d3ebf711) | Oct 30, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | Notebook    | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [aa4e0fdcd6](https://linux-hardware.org/?probe=aa4e0fdcd6) | Oct 30, 2021 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [5630d736dd](https://linux-hardware.org/?probe=5630d736dd) | Oct 30, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [973ddbdc04](https://linux-hardware.org/?probe=973ddbdc04) | Oct 30, 2021 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [179bbb4416](https://linux-hardware.org/?probe=179bbb4416) | Oct 29, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [42098ee0e7](https://linux-hardware.org/?probe=42098ee0e7) | Oct 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f1941a09e5](https://linux-hardware.org/?probe=f1941a09e5) | Oct 28, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [f6317b60dd](https://linux-hardware.org/?probe=f6317b60dd) | Oct 28, 2021 |
| Sony          | VPCEB2Z1E                   | Notebook    | [a18fb33a6f](https://linux-hardware.org/?probe=a18fb33a6f) | Oct 28, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [6cb570a67e](https://linux-hardware.org/?probe=6cb570a67e) | Oct 28, 2021 |
| Dell          | Inspiron 7586               | Convertible | [5a60912d9f](https://linux-hardware.org/?probe=5a60912d9f) | Oct 28, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [2b361b1035](https://linux-hardware.org/?probe=2b361b1035) | Oct 28, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [8a5f05e4c1](https://linux-hardware.org/?probe=8a5f05e4c1) | Oct 28, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [dea3395c5a](https://linux-hardware.org/?probe=dea3395c5a) | Oct 28, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [20f75f2d4c](https://linux-hardware.org/?probe=20f75f2d4c) | Oct 28, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [85a8dff4da](https://linux-hardware.org/?probe=85a8dff4da) | Oct 28, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [3432e77d5e](https://linux-hardware.org/?probe=3432e77d5e) | Oct 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [3b46a4881d](https://linux-hardware.org/?probe=3b46a4881d) | Oct 27, 2021 |
| Sony          | VPCEB2Z1E                   | Notebook    | [7c20abcead](https://linux-hardware.org/?probe=7c20abcead) | Oct 27, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| MSI           | GV72 7RD                    | Notebook    | [cf85648f3a](https://linux-hardware.org/?probe=cf85648f3a) | Oct 27, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [17b2218dab](https://linux-hardware.org/?probe=17b2218dab) | Oct 27, 2021 |
| Acer          | TravelMate 5320             | Notebook    | [8592f1650f](https://linux-hardware.org/?probe=8592f1650f) | Oct 27, 2021 |
| Acer          | TravelMate 5320             | Notebook    | [a9113c440d](https://linux-hardware.org/?probe=a9113c440d) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [325f630dff](https://linux-hardware.org/?probe=325f630dff) | Oct 26, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [e94404d654](https://linux-hardware.org/?probe=e94404d654) | Oct 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [10373a3fda](https://linux-hardware.org/?probe=10373a3fda) | Oct 26, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3adcb9ecf9](https://linux-hardware.org/?probe=3adcb9ecf9) | Oct 26, 2021 |
| Acer          | AS1830                      | Notebook    | [bcef8c44a6](https://linux-hardware.org/?probe=bcef8c44a6) | Oct 26, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c5a4238477](https://linux-hardware.org/?probe=c5a4238477) | Oct 25, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [a391445664](https://linux-hardware.org/?probe=a391445664) | Oct 25, 2021 |
| Dell          | G5 5500                     | Notebook    | [cf10cd5b99](https://linux-hardware.org/?probe=cf10cd5b99) | Oct 25, 2021 |
| HP            | Convertible x360 11-ab0X... | Convertible | [ab13e942f9](https://linux-hardware.org/?probe=ab13e942f9) | Oct 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS7R400    | Notebook    | [22a87cb141](https://linux-hardware.org/?probe=22a87cb141) | Oct 25, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [b6338a1294](https://linux-hardware.org/?probe=b6338a1294) | Oct 25, 2021 |
| ASUSTek       | X540LJ                      | Notebook    | [a5f750922a](https://linux-hardware.org/?probe=a5f750922a) | Oct 25, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [567f0f4a13](https://linux-hardware.org/?probe=567f0f4a13) | Oct 25, 2021 |
| Lenovo        | ThinkPad X230 2325SWF       | Notebook    | [64f9882936](https://linux-hardware.org/?probe=64f9882936) | Oct 25, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [e4cb18707b](https://linux-hardware.org/?probe=e4cb18707b) | Oct 25, 2021 |
| Dell          | Latitude E5400              | Notebook    | [7049bbe182](https://linux-hardware.org/?probe=7049bbe182) | Oct 24, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [702bdda3bf](https://linux-hardware.org/?probe=702bdda3bf) | Oct 24, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d7ee1e117f](https://linux-hardware.org/?probe=d7ee1e117f) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [4e5da9e4d3](https://linux-hardware.org/?probe=4e5da9e4d3) | Oct 24, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [5bd168595f](https://linux-hardware.org/?probe=5bd168595f) | Oct 24, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [46971ff562](https://linux-hardware.org/?probe=46971ff562) | Oct 23, 2021 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [66630328b1](https://linux-hardware.org/?probe=66630328b1) | Oct 23, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a32abedb3](https://linux-hardware.org/?probe=4a32abedb3) | Oct 23, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| Alienware     | 0H869M A00                  | Desktop     | [0c3463c65c](https://linux-hardware.org/?probe=0c3463c65c) | Oct 22, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [05d8adc377](https://linux-hardware.org/?probe=05d8adc377) | Oct 22, 2021 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [199b9bc400](https://linux-hardware.org/?probe=199b9bc400) | Oct 22, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [c7bf3fea46](https://linux-hardware.org/?probe=c7bf3fea46) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [4a5f986165](https://linux-hardware.org/?probe=4a5f986165) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [ba47e47b91](https://linux-hardware.org/?probe=ba47e47b91) | Oct 22, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [349c41d927](https://linux-hardware.org/?probe=349c41d927) | Oct 21, 2021 |
| MSI           | X299 PRO                    | Desktop     | [30591f341d](https://linux-hardware.org/?probe=30591f341d) | Oct 21, 2021 |
| MSI           | Z170A GAMING M7             | Desktop     | [532a08b7c5](https://linux-hardware.org/?probe=532a08b7c5) | Oct 21, 2021 |
| Dell          | 0YC9KY A01                  | Desktop     | [983c46dbbe](https://linux-hardware.org/?probe=983c46dbbe) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [b4c9d0ec61](https://linux-hardware.org/?probe=b4c9d0ec61) | Oct 21, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [0a44b96544](https://linux-hardware.org/?probe=0a44b96544) | Oct 20, 2021 |
| HP            | Dratini                     | Notebook    | [fe5d417b15](https://linux-hardware.org/?probe=fe5d417b15) | Oct 20, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [dc6378e76b](https://linux-hardware.org/?probe=dc6378e76b) | Oct 20, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1ee663a97d](https://linux-hardware.org/?probe=1ee663a97d) | Oct 20, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| HP            | Dratini                     | Notebook    | [059b121b4a](https://linux-hardware.org/?probe=059b121b4a) | Oct 20, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [9f2d69e4c4](https://linux-hardware.org/?probe=9f2d69e4c4) | Oct 20, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [8a587aa0a7](https://linux-hardware.org/?probe=8a587aa0a7) | Oct 20, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [3d61b5412d](https://linux-hardware.org/?probe=3d61b5412d) | Oct 19, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [43a0eecb3a](https://linux-hardware.org/?probe=43a0eecb3a) | Oct 19, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [0eefebb1a4](https://linux-hardware.org/?probe=0eefebb1a4) | Oct 19, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [701ee8ce26](https://linux-hardware.org/?probe=701ee8ce26) | Oct 19, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [d8302cc197](https://linux-hardware.org/?probe=d8302cc197) | Oct 19, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [310f5898f3](https://linux-hardware.org/?probe=310f5898f3) | Oct 18, 2021 |
| ASUSTek       | X556UJ                      | Notebook    | [a68861943e](https://linux-hardware.org/?probe=a68861943e) | Oct 18, 2021 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [3203cd6474](https://linux-hardware.org/?probe=3203cd6474) | Oct 18, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [a4bb8bffd7](https://linux-hardware.org/?probe=a4bb8bffd7) | Oct 18, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [1a4aebd85f](https://linux-hardware.org/?probe=1a4aebd85f) | Oct 18, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90aa462368](https://linux-hardware.org/?probe=90aa462368) | Oct 18, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [90fe8a952c](https://linux-hardware.org/?probe=90fe8a952c) | Oct 18, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [57260c1999](https://linux-hardware.org/?probe=57260c1999) | Oct 18, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [b731701c16](https://linux-hardware.org/?probe=b731701c16) | Oct 18, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [8f4a8b3789](https://linux-hardware.org/?probe=8f4a8b3789) | Oct 18, 2021 |
| HP            | 86C7                        | All in one  | [5d87deb347](https://linux-hardware.org/?probe=5d87deb347) | Oct 18, 2021 |
| Dell          | 0RF705                      | Desktop     | [07965413db](https://linux-hardware.org/?probe=07965413db) | Oct 18, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b41d10be8d](https://linux-hardware.org/?probe=b41d10be8d) | Oct 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [dda062734d](https://linux-hardware.org/?probe=dda062734d) | Oct 17, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2e7ac4731f](https://linux-hardware.org/?probe=2e7ac4731f) | Oct 16, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [4ea9ae9f30](https://linux-hardware.org/?probe=4ea9ae9f30) | Oct 16, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [6010354fe1](https://linux-hardware.org/?probe=6010354fe1) | Oct 16, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [bcb9322f96](https://linux-hardware.org/?probe=bcb9322f96) | Oct 16, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [53c7eee326](https://linux-hardware.org/?probe=53c7eee326) | Oct 16, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [fe5a6d9ad6](https://linux-hardware.org/?probe=fe5a6d9ad6) | Oct 15, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [df9b8ce795](https://linux-hardware.org/?probe=df9b8ce795) | Oct 15, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [2b2014250f](https://linux-hardware.org/?probe=2b2014250f) | Oct 15, 2021 |
| HP            | 86C7                        | All in one  | [57c1da4955](https://linux-hardware.org/?probe=57c1da4955) | Oct 15, 2021 |
| Alienware     | M17xR4                      | Notebook    | [98464fe67b](https://linux-hardware.org/?probe=98464fe67b) | Oct 15, 2021 |
| Alienware     | M17xR4                      | Notebook    | [ea79d2496d](https://linux-hardware.org/?probe=ea79d2496d) | Oct 15, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [99909129fd](https://linux-hardware.org/?probe=99909129fd) | Oct 15, 2021 |
| Lenovo        | ThinkPad P51 20HH000TUS     | Notebook    | [ae9be8f492](https://linux-hardware.org/?probe=ae9be8f492) | Oct 15, 2021 |
| Lenovo        | ThinkPad P51 20HH000TUS     | Notebook    | [87be37cfa1](https://linux-hardware.org/?probe=87be37cfa1) | Oct 15, 2021 |
| Dell          | G5 5590                     | Notebook    | [556c4afa17](https://linux-hardware.org/?probe=556c4afa17) | Oct 14, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [db073988d6](https://linux-hardware.org/?probe=db073988d6) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [77dff3a32a](https://linux-hardware.org/?probe=77dff3a32a) | Oct 14, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [bd90c00536](https://linux-hardware.org/?probe=bd90c00536) | Oct 14, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [2bf61f2ec6](https://linux-hardware.org/?probe=2bf61f2ec6) | Oct 14, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [7292852d90](https://linux-hardware.org/?probe=7292852d90) | Oct 14, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [d48e266fc2](https://linux-hardware.org/?probe=d48e266fc2) | Oct 14, 2021 |
| AZW           | U55                         | Mini pc     | [0a76ac3fb8](https://linux-hardware.org/?probe=0a76ac3fb8) | Oct 13, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [cf5752bb45](https://linux-hardware.org/?probe=cf5752bb45) | Oct 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| Acer          | Predator G9-793             | Notebook    | [427117b3e7](https://linux-hardware.org/?probe=427117b3e7) | Oct 13, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [6096718e44](https://linux-hardware.org/?probe=6096718e44) | Oct 13, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [b935797d2e](https://linux-hardware.org/?probe=b935797d2e) | Oct 13, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [a08da25590](https://linux-hardware.org/?probe=a08da25590) | Oct 13, 2021 |
| Teclast       | F5                          | Convertible | [e4fb415516](https://linux-hardware.org/?probe=e4fb415516) | Oct 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [139f682d03](https://linux-hardware.org/?probe=139f682d03) | Oct 12, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [ab28d0c9d9](https://linux-hardware.org/?probe=ab28d0c9d9) | Oct 12, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [023195c0f7](https://linux-hardware.org/?probe=023195c0f7) | Oct 12, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [e751114673](https://linux-hardware.org/?probe=e751114673) | Oct 12, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [cf61a35aa1](https://linux-hardware.org/?probe=cf61a35aa1) | Oct 12, 2021 |
| Unknown       | GSUO H61V10C                | Desktop     | [c3a23ae9fb](https://linux-hardware.org/?probe=c3a23ae9fb) | Oct 12, 2021 |
| Unknown       | GSUO H61V10C                | Desktop     | [55fe5f3dd1](https://linux-hardware.org/?probe=55fe5f3dd1) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [f4cfafc886](https://linux-hardware.org/?probe=f4cfafc886) | Oct 11, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [530994c225](https://linux-hardware.org/?probe=530994c225) | Oct 11, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [2ae74a35c9](https://linux-hardware.org/?probe=2ae74a35c9) | Oct 11, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [c780997373](https://linux-hardware.org/?probe=c780997373) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| Intel         | H61                         | Desktop     | [38f7084dac](https://linux-hardware.org/?probe=38f7084dac) | Oct 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aabedcd74f](https://linux-hardware.org/?probe=aabedcd74f) | Oct 10, 2021 |
| MSI           | A320M PRO-E                 | Desktop     | [1fd41edb49](https://linux-hardware.org/?probe=1fd41edb49) | Oct 10, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [d065c7d528](https://linux-hardware.org/?probe=d065c7d528) | Oct 10, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [cdc33ce722](https://linux-hardware.org/?probe=cdc33ce722) | Oct 10, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5456e75bff](https://linux-hardware.org/?probe=5456e75bff) | Oct 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [d36b70e744](https://linux-hardware.org/?probe=d36b70e744) | Oct 09, 2021 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [5629f05c6b](https://linux-hardware.org/?probe=5629f05c6b) | Oct 09, 2021 |
| Emaxx Tech... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| Emaxx Tech... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [ab4e6ed1fb](https://linux-hardware.org/?probe=ab4e6ed1fb) | Oct 09, 2021 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [b2d192f2f2](https://linux-hardware.org/?probe=b2d192f2f2) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cb7bf65b6c](https://linux-hardware.org/?probe=cb7bf65b6c) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d6d744895a](https://linux-hardware.org/?probe=d6d744895a) | Oct 08, 2021 |
| MSI           | H81M-E34                    | Desktop     | [bb7dad2b62](https://linux-hardware.org/?probe=bb7dad2b62) | Oct 08, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [5678c0e0be](https://linux-hardware.org/?probe=5678c0e0be) | Oct 08, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [38623b5e33](https://linux-hardware.org/?probe=38623b5e33) | Oct 08, 2021 |
| HP            | 84EE 1100                   | All in one  | [d26755f36d](https://linux-hardware.org/?probe=d26755f36d) | Oct 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [b9aad755ee](https://linux-hardware.org/?probe=b9aad755ee) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b77373d120](https://linux-hardware.org/?probe=b77373d120) | Oct 08, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [330659159b](https://linux-hardware.org/?probe=330659159b) | Oct 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [14d286f67e](https://linux-hardware.org/?probe=14d286f67e) | Oct 07, 2021 |
| Lenovo        | B320-14IKB 81CC             | Notebook    | [d2b36ea612](https://linux-hardware.org/?probe=d2b36ea612) | Oct 07, 2021 |
| MSI           | Z170A SLI PLUS              | Desktop     | [ca217e43ff](https://linux-hardware.org/?probe=ca217e43ff) | Oct 07, 2021 |
| Dell          | Latitude E6430              | Notebook    | [c9b6be5ccb](https://linux-hardware.org/?probe=c9b6be5ccb) | Oct 07, 2021 |
| HP            | ProBook 455R G6             | Notebook    | [9cfde72e18](https://linux-hardware.org/?probe=9cfde72e18) | Oct 07, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [b4488791d9](https://linux-hardware.org/?probe=b4488791d9) | Oct 07, 2021 |
| Dell          | Latitude E5440              | Notebook    | [30a45fe2ee](https://linux-hardware.org/?probe=30a45fe2ee) | Oct 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [f2ab7926e3](https://linux-hardware.org/?probe=f2ab7926e3) | Oct 07, 2021 |
| HP            | 212B                        | Desktop     | [a4318b7064](https://linux-hardware.org/?probe=a4318b7064) | Oct 06, 2021 |
| Lenovo        | ThinkPad P51 20HH000TUS     | Notebook    | [c6b9f35202](https://linux-hardware.org/?probe=c6b9f35202) | Oct 06, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [1f6982c7e0](https://linux-hardware.org/?probe=1f6982c7e0) | Oct 06, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [478bb5a390](https://linux-hardware.org/?probe=478bb5a390) | Oct 06, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [e114537b7c](https://linux-hardware.org/?probe=e114537b7c) | Oct 06, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [744382b8bf](https://linux-hardware.org/?probe=744382b8bf) | Oct 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [c111f21064](https://linux-hardware.org/?probe=c111f21064) | Oct 05, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | Notebook    | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| Dell          | 0YC9KY A01                  | Desktop     | [b8552bd421](https://linux-hardware.org/?probe=b8552bd421) | Oct 05, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [0702bea744](https://linux-hardware.org/?probe=0702bea744) | Oct 04, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [999feee9dc](https://linux-hardware.org/?probe=999feee9dc) | Oct 04, 2021 |
| HP            | ProBook 5320m               | Notebook    | [8ca90ebadb](https://linux-hardware.org/?probe=8ca90ebadb) | Oct 04, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [5d1fb1f342](https://linux-hardware.org/?probe=5d1fb1f342) | Oct 04, 2021 |
| Dell          | Inspiron 7558               | Notebook    | [f81bc6aa70](https://linux-hardware.org/?probe=f81bc6aa70) | Oct 04, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b18b29eed7](https://linux-hardware.org/?probe=b18b29eed7) | Oct 04, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [b89f59ad24](https://linux-hardware.org/?probe=b89f59ad24) | Oct 04, 2021 |
| Dell          | 0YC9KY A01                  | Desktop     | [a7fdac613d](https://linux-hardware.org/?probe=a7fdac613d) | Oct 04, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [0c3a459a0e](https://linux-hardware.org/?probe=0c3a459a0e) | Oct 03, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [b1f376b75a](https://linux-hardware.org/?probe=b1f376b75a) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c9022127a9](https://linux-hardware.org/?probe=c9022127a9) | Oct 03, 2021 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [9d8a13ff43](https://linux-hardware.org/?probe=9d8a13ff43) | Oct 03, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [e226210c1b](https://linux-hardware.org/?probe=e226210c1b) | Oct 03, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [c40c540510](https://linux-hardware.org/?probe=c40c540510) | Oct 03, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [5a9aedea87](https://linux-hardware.org/?probe=5a9aedea87) | Oct 03, 2021 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [7a7dd8eed3](https://linux-hardware.org/?probe=7a7dd8eed3) | Oct 02, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [8a0438f443](https://linux-hardware.org/?probe=8a0438f443) | Oct 02, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [270938ccab](https://linux-hardware.org/?probe=270938ccab) | Oct 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [a1ffad5b6d](https://linux-hardware.org/?probe=a1ffad5b6d) | Oct 02, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [401bfdffc0](https://linux-hardware.org/?probe=401bfdffc0) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1b8efceaa3](https://linux-hardware.org/?probe=1b8efceaa3) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| TrekStor      | Primebook C11               | Convertible | [4bf1eebde1](https://linux-hardware.org/?probe=4bf1eebde1) | Oct 02, 2021 |
| Alienware     | m17 R4                      | Notebook    | [0665c5359b](https://linux-hardware.org/?probe=0665c5359b) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | Notebook    | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [b421c07e30](https://linux-hardware.org/?probe=b421c07e30) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [5dee3aa26b](https://linux-hardware.org/?probe=5dee3aa26b) | Oct 01, 2021 |
| HP            | ENVY dv6                    | Notebook    | [fb70536639](https://linux-hardware.org/?probe=fb70536639) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [877b2c8628](https://linux-hardware.org/?probe=877b2c8628) | Sep 30, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [e3263a11a6](https://linux-hardware.org/?probe=e3263a11a6) | Sep 30, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [95630064bf](https://linux-hardware.org/?probe=95630064bf) | Sep 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [bb6272e86b](https://linux-hardware.org/?probe=bb6272e86b) | Sep 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [27e698d0d3](https://linux-hardware.org/?probe=27e698d0d3) | Sep 29, 2021 |
| Alienware     | m17 R4                      | Notebook    | [42b7c51236](https://linux-hardware.org/?probe=42b7c51236) | Sep 29, 2021 |
| MSI           | MS-168A                     | Notebook    | [8f867d43d5](https://linux-hardware.org/?probe=8f867d43d5) | Sep 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [7bd5717e4d](https://linux-hardware.org/?probe=7bd5717e4d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [37106dbfa3](https://linux-hardware.org/?probe=37106dbfa3) | Sep 28, 2021 |
| Acer          | Aspire A515-52G             | Notebook    | [5627f9a45d](https://linux-hardware.org/?probe=5627f9a45d) | Sep 28, 2021 |
| JGINYUE       | H97I PLUS V2.0              | Desktop     | [2e66de23a2](https://linux-hardware.org/?probe=2e66de23a2) | Sep 28, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [03981fc11c](https://linux-hardware.org/?probe=03981fc11c) | Sep 28, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [ca2d8e0470](https://linux-hardware.org/?probe=ca2d8e0470) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ec7578e1e4](https://linux-hardware.org/?probe=ec7578e1e4) | Sep 27, 2021 |
| Gigabyte      | H61M-DS2                    | All in one  | [a3482755c1](https://linux-hardware.org/?probe=a3482755c1) | Sep 27, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [7bef052f59](https://linux-hardware.org/?probe=7bef052f59) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [32ddd5fb97](https://linux-hardware.org/?probe=32ddd5fb97) | Sep 26, 2021 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [23dbed3ab1](https://linux-hardware.org/?probe=23dbed3ab1) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [a620803ef3](https://linux-hardware.org/?probe=a620803ef3) | Sep 26, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [621a61e24a](https://linux-hardware.org/?probe=621a61e24a) | Sep 26, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5fbac554c3](https://linux-hardware.org/?probe=5fbac554c3) | Sep 25, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [0b4dcc064a](https://linux-hardware.org/?probe=0b4dcc064a) | Sep 25, 2021 |
| HP            | Notebook                    | Notebook    | [ce31fe9ce5](https://linux-hardware.org/?probe=ce31fe9ce5) | Sep 25, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2ebf1f2bec](https://linux-hardware.org/?probe=2ebf1f2bec) | Sep 25, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [a358e3d4b7](https://linux-hardware.org/?probe=a358e3d4b7) | Sep 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [cc28e09d3f](https://linux-hardware.org/?probe=cc28e09d3f) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [60ee9cd152](https://linux-hardware.org/?probe=60ee9cd152) | Sep 25, 2021 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [fb0850ebcd](https://linux-hardware.org/?probe=fb0850ebcd) | Sep 25, 2021 |
| ASRock        | B360M Xtreme                | Desktop     | [4a7f7f8cd0](https://linux-hardware.org/?probe=4a7f7f8cd0) | Sep 24, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [4ec1d30e28](https://linux-hardware.org/?probe=4ec1d30e28) | Sep 24, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7b0d9ff7a8](https://linux-hardware.org/?probe=7b0d9ff7a8) | Sep 24, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e0c086ecef](https://linux-hardware.org/?probe=e0c086ecef) | Sep 24, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [9973a9c2a2](https://linux-hardware.org/?probe=9973a9c2a2) | Sep 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [04d40a1180](https://linux-hardware.org/?probe=04d40a1180) | Sep 24, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [72114a075d](https://linux-hardware.org/?probe=72114a075d) | Sep 24, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [61079f0319](https://linux-hardware.org/?probe=61079f0319) | Sep 23, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [d71a8b92c0](https://linux-hardware.org/?probe=d71a8b92c0) | Sep 23, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [d5b698161c](https://linux-hardware.org/?probe=d5b698161c) | Sep 23, 2021 |
| HP            | G72                         | Notebook    | [5e97b4aba2](https://linux-hardware.org/?probe=5e97b4aba2) | Sep 23, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [948ac814e8](https://linux-hardware.org/?probe=948ac814e8) | Sep 23, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c2bc4c2716](https://linux-hardware.org/?probe=c2bc4c2716) | Sep 22, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [c79b739932](https://linux-hardware.org/?probe=c79b739932) | Sep 22, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [6a1f29d17c](https://linux-hardware.org/?probe=6a1f29d17c) | Sep 22, 2021 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [7cbe8bb003](https://linux-hardware.org/?probe=7cbe8bb003) | Sep 22, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [a0cbc39688](https://linux-hardware.org/?probe=a0cbc39688) | Sep 22, 2021 |
| Lenovo        | IdeaPad S740-15IRH 81NY     | Convertible | [4eee4b94cb](https://linux-hardware.org/?probe=4eee4b94cb) | Sep 22, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [b3c691aae1](https://linux-hardware.org/?probe=b3c691aae1) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [2b8efc01ba](https://linux-hardware.org/?probe=2b8efc01ba) | Sep 22, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [0f2ad22f4c](https://linux-hardware.org/?probe=0f2ad22f4c) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [18b064d0d6](https://linux-hardware.org/?probe=18b064d0d6) | Sep 22, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f28906612f](https://linux-hardware.org/?probe=f28906612f) | Sep 21, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [b504ad8727](https://linux-hardware.org/?probe=b504ad8727) | Sep 21, 2021 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [90513bcdea](https://linux-hardware.org/?probe=90513bcdea) | Sep 21, 2021 |
| Dell          | Latitude E5450              | Notebook    | [88b334f9f9](https://linux-hardware.org/?probe=88b334f9f9) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [17ad477c6f](https://linux-hardware.org/?probe=17ad477c6f) | Sep 21, 2021 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [54cd6887df](https://linux-hardware.org/?probe=54cd6887df) | Sep 21, 2021 |
| HP            | 255 G4                      | Notebook    | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [7f0754075c](https://linux-hardware.org/?probe=7f0754075c) | Sep 20, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0beca82e69](https://linux-hardware.org/?probe=0beca82e69) | Sep 20, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [aa80372d13](https://linux-hardware.org/?probe=aa80372d13) | Sep 20, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [74fd2912fb](https://linux-hardware.org/?probe=74fd2912fb) | Sep 20, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [68c27a546a](https://linux-hardware.org/?probe=68c27a546a) | Sep 20, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [ac834bec82](https://linux-hardware.org/?probe=ac834bec82) | Sep 20, 2021 |
| MSI           | Z270 XPOWER GAMING TITAN... | Desktop     | [d6ad7eca73](https://linux-hardware.org/?probe=d6ad7eca73) | Sep 20, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [3a0a2208fb](https://linux-hardware.org/?probe=3a0a2208fb) | Sep 20, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [961e347941](https://linux-hardware.org/?probe=961e347941) | Sep 19, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a122cb5006](https://linux-hardware.org/?probe=a122cb5006) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [300f6df2c4](https://linux-hardware.org/?probe=300f6df2c4) | Sep 19, 2021 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [464949f239](https://linux-hardware.org/?probe=464949f239) | Sep 19, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [6e80efd4f4](https://linux-hardware.org/?probe=6e80efd4f4) | Sep 19, 2021 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [5182b3bdc4](https://linux-hardware.org/?probe=5182b3bdc4) | Sep 18, 2021 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [a26998d493](https://linux-hardware.org/?probe=a26998d493) | Sep 18, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | Notebook    | [c3f2419a83](https://linux-hardware.org/?probe=c3f2419a83) | Sep 18, 2021 |
| ASUSTek       | UX303UB                     | Notebook    | [8cfb61f7ff](https://linux-hardware.org/?probe=8cfb61f7ff) | Sep 18, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | Notebook    | [63dde78ef0](https://linux-hardware.org/?probe=63dde78ef0) | Sep 18, 2021 |
| ASUSTek       | UX303UB                     | Notebook    | [bcfcb824b7](https://linux-hardware.org/?probe=bcfcb824b7) | Sep 18, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [89c9c70286](https://linux-hardware.org/?probe=89c9c70286) | Sep 18, 2021 |
| MSI           | GS76 Stealth 11UH           | Notebook    | [0589c1c238](https://linux-hardware.org/?probe=0589c1c238) | Sep 18, 2021 |
| Lenovo        | ThinkPad X230 2324CD1       | Notebook    | [348eb8e841](https://linux-hardware.org/?probe=348eb8e841) | Sep 18, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [66acff21b7](https://linux-hardware.org/?probe=66acff21b7) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [18cbc8a35f](https://linux-hardware.org/?probe=18cbc8a35f) | Sep 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [318f8d1653](https://linux-hardware.org/?probe=318f8d1653) | Sep 18, 2021 |
| Dell          | 0YC9KY A01                  | Desktop     | [bb623e3490](https://linux-hardware.org/?probe=bb623e3490) | Sep 18, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [81c906621e](https://linux-hardware.org/?probe=81c906621e) | Sep 17, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7ab07746a7](https://linux-hardware.org/?probe=7ab07746a7) | Sep 17, 2021 |
| HP            | Pro Tablet 608 G1           | Notebook    | [0e503aaa16](https://linux-hardware.org/?probe=0e503aaa16) | Sep 17, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [82058974d9](https://linux-hardware.org/?probe=82058974d9) | Sep 17, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [252914c6d3](https://linux-hardware.org/?probe=252914c6d3) | Sep 16, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [220acb8f8f](https://linux-hardware.org/?probe=220acb8f8f) | Sep 16, 2021 |
| Dell          | Inspiron 5482               | Convertible | [c52711ab47](https://linux-hardware.org/?probe=c52711ab47) | Sep 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0d59451bad](https://linux-hardware.org/?probe=0d59451bad) | Sep 16, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [6bc981dced](https://linux-hardware.org/?probe=6bc981dced) | Sep 16, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [acbb9cba5f](https://linux-hardware.org/?probe=acbb9cba5f) | Sep 16, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [2281c359fc](https://linux-hardware.org/?probe=2281c359fc) | Sep 16, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [dbebd11a10](https://linux-hardware.org/?probe=dbebd11a10) | Sep 16, 2021 |
| Google        | Delbin                      | Notebook    | [aba9776f35](https://linux-hardware.org/?probe=aba9776f35) | Sep 16, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [d2d796ebc7](https://linux-hardware.org/?probe=d2d796ebc7) | Sep 15, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [33d9922ddc](https://linux-hardware.org/?probe=33d9922ddc) | Sep 15, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6f6cb6043b](https://linux-hardware.org/?probe=6f6cb6043b) | Sep 15, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ae684abd8c](https://linux-hardware.org/?probe=ae684abd8c) | Sep 14, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f55a8d5ce5](https://linux-hardware.org/?probe=f55a8d5ce5) | Sep 14, 2021 |
| Pegatron      | IPMSB-H61A                  | Desktop     | [a9ed94aa19](https://linux-hardware.org/?probe=a9ed94aa19) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | Notebook    | [b4ff244fa1](https://linux-hardware.org/?probe=b4ff244fa1) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | Notebook    | [ca370567d0](https://linux-hardware.org/?probe=ca370567d0) | Sep 14, 2021 |
| ASUSTek       | F5VL                        | Notebook    | [cd0276a1e8](https://linux-hardware.org/?probe=cd0276a1e8) | Sep 14, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [30634e3721](https://linux-hardware.org/?probe=30634e3721) | Sep 14, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6aeae42410](https://linux-hardware.org/?probe=6aeae42410) | Sep 14, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [320f66acb3](https://linux-hardware.org/?probe=320f66acb3) | Sep 14, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c8e465fcb0](https://linux-hardware.org/?probe=c8e465fcb0) | Sep 14, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [4fece13da7](https://linux-hardware.org/?probe=4fece13da7) | Sep 14, 2021 |
| Dell          | XPS L502X                   | Notebook    | [78c56851dc](https://linux-hardware.org/?probe=78c56851dc) | Sep 14, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [eee9e1661b](https://linux-hardware.org/?probe=eee9e1661b) | Sep 13, 2021 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [61e703a3e0](https://linux-hardware.org/?probe=61e703a3e0) | Sep 13, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [789f34e59b](https://linux-hardware.org/?probe=789f34e59b) | Sep 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [db46242eec](https://linux-hardware.org/?probe=db46242eec) | Sep 13, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [19db16c9df](https://linux-hardware.org/?probe=19db16c9df) | Sep 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [63b6ade950](https://linux-hardware.org/?probe=63b6ade950) | Sep 13, 2021 |
| Acer          | Swift SF514-55TA            | Notebook    | [c3a4ff2798](https://linux-hardware.org/?probe=c3a4ff2798) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [69338ada32](https://linux-hardware.org/?probe=69338ada32) | Sep 12, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [57f772fc9f](https://linux-hardware.org/?probe=57f772fc9f) | Sep 12, 2021 |
| ASUSTek       | G73Jh                       | Notebook    | [2fa5cc10d9](https://linux-hardware.org/?probe=2fa5cc10d9) | Sep 12, 2021 |
| ASUSTek       | G73Jh                       | Notebook    | [480926c7be](https://linux-hardware.org/?probe=480926c7be) | Sep 12, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [34c7038f6f](https://linux-hardware.org/?probe=34c7038f6f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| Dell          | Latitude 5420               | Notebook    | [fe7a0defea](https://linux-hardware.org/?probe=fe7a0defea) | Sep 12, 2021 |
| Dell          | Latitude 5420               | Notebook    | [e0b391ba90](https://linux-hardware.org/?probe=e0b391ba90) | Sep 12, 2021 |
| Gigabyte      | H110M-S2HP-CF               | Desktop     | [88b4dd396f](https://linux-hardware.org/?probe=88b4dd396f) | Sep 12, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a23af43cbf](https://linux-hardware.org/?probe=a23af43cbf) | Sep 12, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1fbb778cec](https://linux-hardware.org/?probe=1fbb778cec) | Sep 12, 2021 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [801b6de138](https://linux-hardware.org/?probe=801b6de138) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Monster       | TULPAR T7 V24.1             | Notebook    | [7489a1a6c9](https://linux-hardware.org/?probe=7489a1a6c9) | Sep 12, 2021 |
| Monster       | TULPAR T7 V24.1             | Notebook    | [5eef50e997](https://linux-hardware.org/?probe=5eef50e997) | Sep 11, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [d8a1bf8786](https://linux-hardware.org/?probe=d8a1bf8786) | Sep 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [02a95fadba](https://linux-hardware.org/?probe=02a95fadba) | Sep 11, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [0385e56112](https://linux-hardware.org/?probe=0385e56112) | Sep 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddde472ce9](https://linux-hardware.org/?probe=ddde472ce9) | Sep 11, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1698c9e06f](https://linux-hardware.org/?probe=1698c9e06f) | Sep 11, 2021 |
| HP            | 240 G7 Notebook PC          | Notebook    | [ed4c6315e5](https://linux-hardware.org/?probe=ed4c6315e5) | Sep 10, 2021 |
| ASUSTek       | X45U                        | Notebook    | [ebb2079624](https://linux-hardware.org/?probe=ebb2079624) | Sep 10, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [ea7cb94a03](https://linux-hardware.org/?probe=ea7cb94a03) | Sep 10, 2021 |
| Gigabyte      | Sabre 17KV8                 | Notebook    | [c6c64577d9](https://linux-hardware.org/?probe=c6c64577d9) | Sep 10, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [0c8b9d0704](https://linux-hardware.org/?probe=0c8b9d0704) | Sep 10, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [8c33c033c0](https://linux-hardware.org/?probe=8c33c033c0) | Sep 10, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [b8fecfa6b6](https://linux-hardware.org/?probe=b8fecfa6b6) | Sep 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [258d846b85](https://linux-hardware.org/?probe=258d846b85) | Sep 09, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [df5ddcca8a](https://linux-hardware.org/?probe=df5ddcca8a) | Sep 09, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [82826e5cce](https://linux-hardware.org/?probe=82826e5cce) | Sep 09, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5ccce57d3f](https://linux-hardware.org/?probe=5ccce57d3f) | Sep 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [581b818f1f](https://linux-hardware.org/?probe=581b818f1f) | Sep 08, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [5f255ee421](https://linux-hardware.org/?probe=5f255ee421) | Sep 08, 2021 |
| Lenovo        | ThinkPad E460 20ET0014LM    | Notebook    | [e8fd1e538b](https://linux-hardware.org/?probe=e8fd1e538b) | Sep 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4b7b87adc3](https://linux-hardware.org/?probe=4b7b87adc3) | Sep 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [1ee958abc3](https://linux-hardware.org/?probe=1ee958abc3) | Sep 08, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [5c44d97d66](https://linux-hardware.org/?probe=5c44d97d66) | Sep 08, 2021 |
| ASUSTek       | X99-A                       | Desktop     | [f578a42272](https://linux-hardware.org/?probe=f578a42272) | Sep 08, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [0417817492](https://linux-hardware.org/?probe=0417817492) | Sep 08, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2327ab2724](https://linux-hardware.org/?probe=2327ab2724) | Sep 07, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [52b780559c](https://linux-hardware.org/?probe=52b780559c) | Sep 07, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [6eb800a8c2](https://linux-hardware.org/?probe=6eb800a8c2) | Sep 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [8e5bd209fa](https://linux-hardware.org/?probe=8e5bd209fa) | Sep 07, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [f6272b3785](https://linux-hardware.org/?probe=f6272b3785) | Sep 07, 2021 |
| Teclast       | F5                          | Convertible | [bac577cc32](https://linux-hardware.org/?probe=bac577cc32) | Sep 06, 2021 |
| Dell          | Precision 5540              | Notebook    | [b3e3027549](https://linux-hardware.org/?probe=b3e3027549) | Sep 06, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [7e44f2ff81](https://linux-hardware.org/?probe=7e44f2ff81) | Sep 06, 2021 |
| Dell          | Precision 7550              | Notebook    | [d5d4d4b217](https://linux-hardware.org/?probe=d5d4d4b217) | Sep 06, 2021 |
| Google        | Akemi                       | Notebook    | [b6b750e871](https://linux-hardware.org/?probe=b6b750e871) | Sep 06, 2021 |
| Google        | Akemi                       | Notebook    | [9e44fff6da](https://linux-hardware.org/?probe=9e44fff6da) | Sep 06, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [938b16305c](https://linux-hardware.org/?probe=938b16305c) | Sep 06, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [67630c1611](https://linux-hardware.org/?probe=67630c1611) | Sep 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [18ac8d8acd](https://linux-hardware.org/?probe=18ac8d8acd) | Sep 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8647bf375d](https://linux-hardware.org/?probe=8647bf375d) | Sep 06, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Google        | Akemi                       | Notebook    | [6616d48ea1](https://linux-hardware.org/?probe=6616d48ea1) | Sep 06, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [694b8d27de](https://linux-hardware.org/?probe=694b8d27de) | Sep 06, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [486c5704ac](https://linux-hardware.org/?probe=486c5704ac) | Sep 05, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [6380b270a4](https://linux-hardware.org/?probe=6380b270a4) | Sep 05, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [57ed7dc3c0](https://linux-hardware.org/?probe=57ed7dc3c0) | Sep 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6ce77afdbf](https://linux-hardware.org/?probe=6ce77afdbf) | Sep 05, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e61af3ac08](https://linux-hardware.org/?probe=e61af3ac08) | Sep 05, 2021 |
| HP            | Notebook                    | Notebook    | [ee056678db](https://linux-hardware.org/?probe=ee056678db) | Sep 05, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [f941092135](https://linux-hardware.org/?probe=f941092135) | Sep 05, 2021 |
| eii           | WSA116                      | Notebook    | [c3a328b794](https://linux-hardware.org/?probe=c3a328b794) | Sep 04, 2021 |
| Dell          | 0YC9KY A01                  | Desktop     | [09c35f97f8](https://linux-hardware.org/?probe=09c35f97f8) | Sep 04, 2021 |
| eii           | WSA116                      | Notebook    | [bad23ad0a0](https://linux-hardware.org/?probe=bad23ad0a0) | Sep 04, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [c26ea54abd](https://linux-hardware.org/?probe=c26ea54abd) | Sep 04, 2021 |
| Dell          | Latitude E6520              | Notebook    | [49385b6000](https://linux-hardware.org/?probe=49385b6000) | Sep 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [2bcaee9bfb](https://linux-hardware.org/?probe=2bcaee9bfb) | Sep 04, 2021 |
| Dell          | Latitude E5400              | Notebook    | [3840dd9a96](https://linux-hardware.org/?probe=3840dd9a96) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [a2b6653813](https://linux-hardware.org/?probe=a2b6653813) | Sep 04, 2021 |
| Dell          | Latitude E5400              | Notebook    | [d568753381](https://linux-hardware.org/?probe=d568753381) | Sep 04, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [40be76674a](https://linux-hardware.org/?probe=40be76674a) | Sep 04, 2021 |
| HP            | Pavilion 15                 | Notebook    | [bef47b45ee](https://linux-hardware.org/?probe=bef47b45ee) | Sep 03, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [d606dd2010](https://linux-hardware.org/?probe=d606dd2010) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2249c5110d](https://linux-hardware.org/?probe=2249c5110d) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [10053be0c4](https://linux-hardware.org/?probe=10053be0c4) | Sep 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0e08e4b191](https://linux-hardware.org/?probe=0e08e4b191) | Sep 03, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [b548c2ffad](https://linux-hardware.org/?probe=b548c2ffad) | Sep 03, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [dc3749d5f0](https://linux-hardware.org/?probe=dc3749d5f0) | Sep 02, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [52f22a89b7](https://linux-hardware.org/?probe=52f22a89b7) | Sep 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5b03ee6ff2](https://linux-hardware.org/?probe=5b03ee6ff2) | Sep 02, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [059a88a1cb](https://linux-hardware.org/?probe=059a88a1cb) | Sep 02, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [557a0d5396](https://linux-hardware.org/?probe=557a0d5396) | Sep 02, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [49170bd478](https://linux-hardware.org/?probe=49170bd478) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [bf06fd5933](https://linux-hardware.org/?probe=bf06fd5933) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [740118101a](https://linux-hardware.org/?probe=740118101a) | Sep 02, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [ae90a1e459](https://linux-hardware.org/?probe=ae90a1e459) | Sep 02, 2021 |
| Dell          | 0YC9KY A01                  | Desktop     | [ec53516abc](https://linux-hardware.org/?probe=ec53516abc) | Sep 02, 2021 |
| Huanan        | X99-F8                      | Desktop     | [67f35844cd](https://linux-hardware.org/?probe=67f35844cd) | Sep 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [42c8988de1](https://linux-hardware.org/?probe=42c8988de1) | Sep 01, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [286d6314d1](https://linux-hardware.org/?probe=286d6314d1) | Sep 01, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Fusion5       | FWIN232 PLUS                | Tablet      | [e6a99aea30](https://linux-hardware.org/?probe=e6a99aea30) | Sep 01, 2021 |
| Dell          | Inspiron 5370               | Notebook    | [b92f2ddb11](https://linux-hardware.org/?probe=b92f2ddb11) | Sep 01, 2021 |
| Acer          | Predator G9-793             | Notebook    | [43e3d39bf8](https://linux-hardware.org/?probe=43e3d39bf8) | Sep 01, 2021 |
| ASUSTek       | X99-A                       | Desktop     | [7bd93377b5](https://linux-hardware.org/?probe=7bd93377b5) | Sep 01, 2021 |
| Huanan        | X99-F8                      | Desktop     | [33e8040986](https://linux-hardware.org/?probe=33e8040986) | Aug 31, 2021 |
| Huanan        | X99-F8                      | Desktop     | [adc113ad6f](https://linux-hardware.org/?probe=adc113ad6f) | Aug 31, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [2bd5adb706](https://linux-hardware.org/?probe=2bd5adb706) | Aug 31, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [425d116724](https://linux-hardware.org/?probe=425d116724) | Aug 31, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [9d7de5d91d](https://linux-hardware.org/?probe=9d7de5d91d) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7f11ebf1f0](https://linux-hardware.org/?probe=7f11ebf1f0) | Aug 31, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [858de30180](https://linux-hardware.org/?probe=858de30180) | Aug 31, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [0b8018e28d](https://linux-hardware.org/?probe=0b8018e28d) | Aug 30, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [44ec15b4b9](https://linux-hardware.org/?probe=44ec15b4b9) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [497eefad0b](https://linux-hardware.org/?probe=497eefad0b) | Aug 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbe1424130](https://linux-hardware.org/?probe=bbe1424130) | Aug 30, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [038868057d](https://linux-hardware.org/?probe=038868057d) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [b7c59b9453](https://linux-hardware.org/?probe=b7c59b9453) | Aug 30, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [875e21217a](https://linux-hardware.org/?probe=875e21217a) | Aug 30, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [93d5d9545d](https://linux-hardware.org/?probe=93d5d9545d) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a21f02142b](https://linux-hardware.org/?probe=a21f02142b) | Aug 30, 2021 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [e188b2bd24](https://linux-hardware.org/?probe=e188b2bd24) | Aug 30, 2021 |
| Acer          | Predator G9-793             | Notebook    | [7cf631ac92](https://linux-hardware.org/?probe=7cf631ac92) | Aug 30, 2021 |
| Acer          | Predator G9-793             | Notebook    | [3f04db011d](https://linux-hardware.org/?probe=3f04db011d) | Aug 29, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [b5d8eb81a4](https://linux-hardware.org/?probe=b5d8eb81a4) | Aug 29, 2021 |
| Gigabyte      | H97-HD3                     | Desktop     | [c72a8f9c61](https://linux-hardware.org/?probe=c72a8f9c61) | Aug 29, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [229e89f193](https://linux-hardware.org/?probe=229e89f193) | Aug 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [88e33a1120](https://linux-hardware.org/?probe=88e33a1120) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [445afafc69](https://linux-hardware.org/?probe=445afafc69) | Aug 29, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6df437488d](https://linux-hardware.org/?probe=6df437488d) | Aug 29, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a27ab262e2](https://linux-hardware.org/?probe=a27ab262e2) | Aug 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d9d4f6bc02](https://linux-hardware.org/?probe=d9d4f6bc02) | Aug 28, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [72466f351b](https://linux-hardware.org/?probe=72466f351b) | Aug 28, 2021 |
| ZOTAC         | Board                       | Mini pc     | [94025849e2](https://linux-hardware.org/?probe=94025849e2) | Aug 28, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [30d745e8d3](https://linux-hardware.org/?probe=30d745e8d3) | Aug 28, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [c431035e14](https://linux-hardware.org/?probe=c431035e14) | Aug 28, 2021 |
| Lenovo        | ThinkPad T590 20N4002WGE    | Notebook    | [8eac55bc7a](https://linux-hardware.org/?probe=8eac55bc7a) | Aug 28, 2021 |
| Lenovo        | ThinkPad T480 20L6S69B00    | Notebook    | [af0a8038bf](https://linux-hardware.org/?probe=af0a8038bf) | Aug 28, 2021 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [456241c002](https://linux-hardware.org/?probe=456241c002) | Aug 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [7ca800480b](https://linux-hardware.org/?probe=7ca800480b) | Aug 28, 2021 |
| Lenovo        | ThinkPad P51 20HH000TUS     | Notebook    | [b632928916](https://linux-hardware.org/?probe=b632928916) | Aug 28, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [96188348ae](https://linux-hardware.org/?probe=96188348ae) | Aug 27, 2021 |
| Lenovo        | ThinkPad T480 20L6S69B00    | Notebook    | [740276670a](https://linux-hardware.org/?probe=740276670a) | Aug 27, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5cee16a454](https://linux-hardware.org/?probe=5cee16a454) | Aug 27, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [08b5160307](https://linux-hardware.org/?probe=08b5160307) | Aug 27, 2021 |
| Gigabyte      | H310M S2V x.x               | Desktop     | [5df25320dd](https://linux-hardware.org/?probe=5df25320dd) | Aug 27, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b6bd53772](https://linux-hardware.org/?probe=1b6bd53772) | Aug 26, 2021 |
| Gigabyte      | H97-HD3                     | Desktop     | [43d70d4502](https://linux-hardware.org/?probe=43d70d4502) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [49f141b749](https://linux-hardware.org/?probe=49f141b749) | Aug 26, 2021 |
| ASRock        | H61M-ITX                    | Desktop     | [4f191c568f](https://linux-hardware.org/?probe=4f191c568f) | Aug 26, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [608a529334](https://linux-hardware.org/?probe=608a529334) | Aug 26, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [664681220c](https://linux-hardware.org/?probe=664681220c) | Aug 26, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [e9fbc2c540](https://linux-hardware.org/?probe=e9fbc2c540) | Aug 25, 2021 |
| HP            | Presario CQ57               | Notebook    | [4b863ffc87](https://linux-hardware.org/?probe=4b863ffc87) | Aug 25, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [c6bb5b219f](https://linux-hardware.org/?probe=c6bb5b219f) | Aug 25, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [806404c773](https://linux-hardware.org/?probe=806404c773) | Aug 25, 2021 |
| Gigabyte      | P55-USB3                    | Desktop     | [6c827139ab](https://linux-hardware.org/?probe=6c827139ab) | Aug 24, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a05b926d33](https://linux-hardware.org/?probe=a05b926d33) | Aug 24, 2021 |
| Lenovo        | ThinkPad T410 2537NP8       | Notebook    | [e17d2f91ab](https://linux-hardware.org/?probe=e17d2f91ab) | Aug 24, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [517d599afa](https://linux-hardware.org/?probe=517d599afa) | Aug 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e5f2d0e3db](https://linux-hardware.org/?probe=e5f2d0e3db) | Aug 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13c65ae775](https://linux-hardware.org/?probe=13c65ae775) | Aug 24, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | Desktop     | [5141221da1](https://linux-hardware.org/?probe=5141221da1) | Aug 24, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | Notebook    | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [be114a1393](https://linux-hardware.org/?probe=be114a1393) | Aug 23, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [742490d4ea](https://linux-hardware.org/?probe=742490d4ea) | Aug 23, 2021 |
| Acer          | Aspire V3-551               | Notebook    | [9fd29f4a13](https://linux-hardware.org/?probe=9fd29f4a13) | Aug 23, 2021 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [3efdd11521](https://linux-hardware.org/?probe=3efdd11521) | Aug 23, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [4e6b4d3b69](https://linux-hardware.org/?probe=4e6b4d3b69) | Aug 23, 2021 |
| Acer          | Aspire V3-551               | Notebook    | [7952925c50](https://linux-hardware.org/?probe=7952925c50) | Aug 23, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1674818018](https://linux-hardware.org/?probe=1674818018) | Aug 23, 2021 |
| Dell          | G3 3579                     | Notebook    | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | Notebook    | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [0ce1387ee5](https://linux-hardware.org/?probe=0ce1387ee5) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| MSI           | X299 PRO                    | Desktop     | [0277a177a4](https://linux-hardware.org/?probe=0277a177a4) | Aug 22, 2021 |
| MSI           | X299 PRO                    | Desktop     | [795630b041](https://linux-hardware.org/?probe=795630b041) | Aug 22, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [26c3a03bb6](https://linux-hardware.org/?probe=26c3a03bb6) | Aug 22, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [43612f16b2](https://linux-hardware.org/?probe=43612f16b2) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ff1e83e570](https://linux-hardware.org/?probe=ff1e83e570) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [4128c360ba](https://linux-hardware.org/?probe=4128c360ba) | Aug 22, 2021 |
| HP            | Presario CQ57               | Notebook    | [a45389ec74](https://linux-hardware.org/?probe=a45389ec74) | Aug 21, 2021 |
| Dell          | Studio 1537                 | Notebook    | [b3d049b276](https://linux-hardware.org/?probe=b3d049b276) | Aug 21, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22899c080b](https://linux-hardware.org/?probe=22899c080b) | Aug 21, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [34bd5251b6](https://linux-hardware.org/?probe=34bd5251b6) | Aug 21, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [9eb1fd9b8f](https://linux-hardware.org/?probe=9eb1fd9b8f) | Aug 21, 2021 |
| ASUSTek       | VM62                        | Desktop     | [9452e7da05](https://linux-hardware.org/?probe=9452e7da05) | Aug 21, 2021 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [df9d84a892](https://linux-hardware.org/?probe=df9d84a892) | Aug 21, 2021 |
| Lenovo        | ThinkPad P52s 20LB0009FR    | Notebook    | [d2c417c68b](https://linux-hardware.org/?probe=d2c417c68b) | Aug 21, 2021 |
| Acer          | RS780HVF                    | Desktop     | [f051228785](https://linux-hardware.org/?probe=f051228785) | Aug 21, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [92137cbbc7](https://linux-hardware.org/?probe=92137cbbc7) | Aug 21, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [a33b940821](https://linux-hardware.org/?probe=a33b940821) | Aug 21, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2187d44ef1](https://linux-hardware.org/?probe=2187d44ef1) | Aug 21, 2021 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [bc2c7ba0ca](https://linux-hardware.org/?probe=bc2c7ba0ca) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4cdb976c2](https://linux-hardware.org/?probe=d4cdb976c2) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [633e5a9649](https://linux-hardware.org/?probe=633e5a9649) | Aug 20, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [447b6e0cd4](https://linux-hardware.org/?probe=447b6e0cd4) | Aug 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [b5ff89deed](https://linux-hardware.org/?probe=b5ff89deed) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [2d342c6a1a](https://linux-hardware.org/?probe=2d342c6a1a) | Aug 19, 2021 |
| Dell          | Latitude 7285               | Notebook    | [67c03244dc](https://linux-hardware.org/?probe=67c03244dc) | Aug 19, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [fb76d1eaf9](https://linux-hardware.org/?probe=fb76d1eaf9) | Aug 19, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [1a23a6605b](https://linux-hardware.org/?probe=1a23a6605b) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S69B00    | Notebook    | [b7f2d9b7f5](https://linux-hardware.org/?probe=b7f2d9b7f5) | Aug 19, 2021 |
| ECS           | Livermore8                  | Desktop     | [a86f5a7745](https://linux-hardware.org/?probe=a86f5a7745) | Aug 18, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [0467d0f4e8](https://linux-hardware.org/?probe=0467d0f4e8) | Aug 18, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [4b4e9791f0](https://linux-hardware.org/?probe=4b4e9791f0) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [0108787fbb](https://linux-hardware.org/?probe=0108787fbb) | Aug 18, 2021 |
| Notebook      | N85_N870HL                  | Notebook    | [76e346d6a9](https://linux-hardware.org/?probe=76e346d6a9) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [c33f348fa9](https://linux-hardware.org/?probe=c33f348fa9) | Aug 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [bb476838d6](https://linux-hardware.org/?probe=bb476838d6) | Aug 17, 2021 |
| ASRock        | B550 Taichi                 | Desktop     | [2d5673f15b](https://linux-hardware.org/?probe=2d5673f15b) | Aug 17, 2021 |
| Lenovo        | ThinkPad T430 2349Y3D       | Notebook    | [f44d1fb51f](https://linux-hardware.org/?probe=f44d1fb51f) | Aug 17, 2021 |
| Lenovo        | ThinkPad T430 2349Y3D       | Notebook    | [11a610ae94](https://linux-hardware.org/?probe=11a610ae94) | Aug 17, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [9398b33192](https://linux-hardware.org/?probe=9398b33192) | Aug 17, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [0a023d2778](https://linux-hardware.org/?probe=0a023d2778) | Aug 17, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [a21a597e6e](https://linux-hardware.org/?probe=a21a597e6e) | Aug 17, 2021 |
| Timi          | A35S                        | Notebook    | [1f0e95ee1d](https://linux-hardware.org/?probe=1f0e95ee1d) | Aug 17, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [3a87b575a4](https://linux-hardware.org/?probe=3a87b575a4) | Aug 17, 2021 |
| Acer          | TravelMate P633-M           | Notebook    | [0eabc60188](https://linux-hardware.org/?probe=0eabc60188) | Aug 17, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [9eb8d9150f](https://linux-hardware.org/?probe=9eb8d9150f) | Aug 17, 2021 |
| Acer          | TravelMate P633-M           | Notebook    | [46ece2a35a](https://linux-hardware.org/?probe=46ece2a35a) | Aug 17, 2021 |
| Jumper        | EZpad                       | Tablet      | [e97e240440](https://linux-hardware.org/?probe=e97e240440) | Aug 16, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [9b7ea1199f](https://linux-hardware.org/?probe=9b7ea1199f) | Aug 16, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [8c94839928](https://linux-hardware.org/?probe=8c94839928) | Aug 16, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [d2470cae4e](https://linux-hardware.org/?probe=d2470cae4e) | Aug 16, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2e73a852fb](https://linux-hardware.org/?probe=2e73a852fb) | Aug 16, 2021 |
| MSI           | GF75 Thin 10SC              | Notebook    | [3d501c56aa](https://linux-hardware.org/?probe=3d501c56aa) | Aug 16, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [d94f741f99](https://linux-hardware.org/?probe=d94f741f99) | Aug 16, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [d628c6c320](https://linux-hardware.org/?probe=d628c6c320) | Aug 16, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [443958ef25](https://linux-hardware.org/?probe=443958ef25) | Aug 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7b753e19c5](https://linux-hardware.org/?probe=7b753e19c5) | Aug 16, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| HP            | 2B2C                        | Desktop     | [001437ec4a](https://linux-hardware.org/?probe=001437ec4a) | Aug 16, 2021 |
| MSI           | GF75 Thin 10SC              | Notebook    | [4f22ea9d70](https://linux-hardware.org/?probe=4f22ea9d70) | Aug 16, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6c75d75ebf](https://linux-hardware.org/?probe=6c75d75ebf) | Aug 15, 2021 |
| AYADEVICE     | AYA NEO FOUNDER             | Tablet      | [ba4d2b512a](https://linux-hardware.org/?probe=ba4d2b512a) | Aug 15, 2021 |
| HP            | ProBook 6470b               | Notebook    | [4d338e7f16](https://linux-hardware.org/?probe=4d338e7f16) | Aug 15, 2021 |
| Dell          | System XPS L321X            | Notebook    | [f3a39bfac9](https://linux-hardware.org/?probe=f3a39bfac9) | Aug 15, 2021 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [da306f5d5b](https://linux-hardware.org/?probe=da306f5d5b) | Aug 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e8465fe6ef](https://linux-hardware.org/?probe=e8465fe6ef) | Aug 15, 2021 |
| Acer          | RS780HVF                    | Desktop     | [32c3b00b51](https://linux-hardware.org/?probe=32c3b00b51) | Aug 14, 2021 |
| Acer          | RS780HVF                    | Desktop     | [858844ae39](https://linux-hardware.org/?probe=858844ae39) | Aug 14, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [a0310af3b9](https://linux-hardware.org/?probe=a0310af3b9) | Aug 14, 2021 |
| HP            | 0A5Ch                       | Desktop     | [7fba04422d](https://linux-hardware.org/?probe=7fba04422d) | Aug 14, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [6ea89661ff](https://linux-hardware.org/?probe=6ea89661ff) | Aug 14, 2021 |
| LG Electro... | 17Z90P-K.AAC8U1             | Notebook    | [cb96359874](https://linux-hardware.org/?probe=cb96359874) | Aug 14, 2021 |
| MSI           | X299 PRO                    | Desktop     | [a95d7ebf1a](https://linux-hardware.org/?probe=a95d7ebf1a) | Aug 14, 2021 |
| MSI           | X299 PRO                    | Desktop     | [7c93d91421](https://linux-hardware.org/?probe=7c93d91421) | Aug 14, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [7645f25b97](https://linux-hardware.org/?probe=7645f25b97) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8d3fc7fc33](https://linux-hardware.org/?probe=8d3fc7fc33) | Aug 13, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [4b51090679](https://linux-hardware.org/?probe=4b51090679) | Aug 13, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [cf27f0337d](https://linux-hardware.org/?probe=cf27f0337d) | Aug 13, 2021 |
| Jumper        | EZpad                       | Tablet      | [67934ebe7d](https://linux-hardware.org/?probe=67934ebe7d) | Aug 13, 2021 |
| MSI           | GF75 Thin 10SC              | Notebook    | [4061dae27f](https://linux-hardware.org/?probe=4061dae27f) | Aug 13, 2021 |
| MSI           | GF75 Thin 10SC              | Notebook    | [b8041fbc03](https://linux-hardware.org/?probe=b8041fbc03) | Aug 13, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | Notebook    | [9453b06bd3](https://linux-hardware.org/?probe=9453b06bd3) | Aug 13, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [13fb44b235](https://linux-hardware.org/?probe=13fb44b235) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [3fddac7986](https://linux-hardware.org/?probe=3fddac7986) | Aug 12, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [4cf8cbc0f0](https://linux-hardware.org/?probe=4cf8cbc0f0) | Aug 12, 2021 |
| Apple         | MacBookPro6,1               | Notebook    | [00c2cb427f](https://linux-hardware.org/?probe=00c2cb427f) | Aug 12, 2021 |
| Apple         | MacBookPro6,1               | Notebook    | [f24034c81e](https://linux-hardware.org/?probe=f24034c81e) | Aug 12, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c199b0c50](https://linux-hardware.org/?probe=2c199b0c50) | Aug 12, 2021 |
| ASUSTek       | X541UV                      | Notebook    | [3f45acb762](https://linux-hardware.org/?probe=3f45acb762) | Aug 11, 2021 |
| HP            | ProBook 6460b               | Notebook    | [83029580f3](https://linux-hardware.org/?probe=83029580f3) | Aug 11, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [acf20e4675](https://linux-hardware.org/?probe=acf20e4675) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [1be38e6e19](https://linux-hardware.org/?probe=1be38e6e19) | Aug 11, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [1536f481a9](https://linux-hardware.org/?probe=1536f481a9) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [8ec2e186a0](https://linux-hardware.org/?probe=8ec2e186a0) | Aug 11, 2021 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [d36f5a6f5e](https://linux-hardware.org/?probe=d36f5a6f5e) | Aug 10, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [ed626be34e](https://linux-hardware.org/?probe=ed626be34e) | Aug 10, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [61781b1ca9](https://linux-hardware.org/?probe=61781b1ca9) | Aug 10, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [bb91bab85b](https://linux-hardware.org/?probe=bb91bab85b) | Aug 09, 2021 |
| HP            | ProBook 6550b               | Notebook    | [748ed5112b](https://linux-hardware.org/?probe=748ed5112b) | Aug 09, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [457acf4b11](https://linux-hardware.org/?probe=457acf4b11) | Aug 09, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [66f8907e13](https://linux-hardware.org/?probe=66f8907e13) | Aug 09, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [77619b573f](https://linux-hardware.org/?probe=77619b573f) | Aug 09, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1a27b7d75c](https://linux-hardware.org/?probe=1a27b7d75c) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | Notebook    | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [6a56825e93](https://linux-hardware.org/?probe=6a56825e93) | Aug 09, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [2155467a9b](https://linux-hardware.org/?probe=2155467a9b) | Aug 09, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [e658937af2](https://linux-hardware.org/?probe=e658937af2) | Aug 09, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [3f30f452cf](https://linux-hardware.org/?probe=3f30f452cf) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [bc4528fae5](https://linux-hardware.org/?probe=bc4528fae5) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [d507058bbf](https://linux-hardware.org/?probe=d507058bbf) | Aug 09, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [0db2fd9f89](https://linux-hardware.org/?probe=0db2fd9f89) | Aug 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [2c47def4c0](https://linux-hardware.org/?probe=2c47def4c0) | Aug 08, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [aa49e75b2a](https://linux-hardware.org/?probe=aa49e75b2a) | Aug 08, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6f30dc0462](https://linux-hardware.org/?probe=6f30dc0462) | Aug 08, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [08589f5190](https://linux-hardware.org/?probe=08589f5190) | Aug 08, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [abd20255c2](https://linux-hardware.org/?probe=abd20255c2) | Aug 08, 2021 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [bd2f6222e5](https://linux-hardware.org/?probe=bd2f6222e5) | Aug 08, 2021 |
| Dell          | Latitude E6530              | Notebook    | [52a24657c0](https://linux-hardware.org/?probe=52a24657c0) | Aug 08, 2021 |
| Dell          | Latitude E6530              | Notebook    | [8dd6d1b3f0](https://linux-hardware.org/?probe=8dd6d1b3f0) | Aug 08, 2021 |
| Acer          | Switch SA5-271              | Tablet      | [6c11ddaf17](https://linux-hardware.org/?probe=6c11ddaf17) | Aug 08, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [15b26f4936](https://linux-hardware.org/?probe=15b26f4936) | Aug 07, 2021 |
| Gigabyte      | 970A-UD3                    | Desktop     | [9a660e5baf](https://linux-hardware.org/?probe=9a660e5baf) | Aug 07, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [30f57a6cdf](https://linux-hardware.org/?probe=30f57a6cdf) | Aug 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [d35224de9f](https://linux-hardware.org/?probe=d35224de9f) | Aug 07, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b6e23e4857](https://linux-hardware.org/?probe=b6e23e4857) | Aug 07, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | Desktop     | [e485c3c778](https://linux-hardware.org/?probe=e485c3c778) | Aug 07, 2021 |
| HP            | 8767 A                      | Desktop     | [70ecb0dd03](https://linux-hardware.org/?probe=70ecb0dd03) | Aug 06, 2021 |
| Lenovo        | ThinkPad T470s 20HGS2PL0... | Notebook    | [dd4f65c66d](https://linux-hardware.org/?probe=dd4f65c66d) | Aug 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7a8625559f](https://linux-hardware.org/?probe=7a8625559f) | Aug 06, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [d0439be169](https://linux-hardware.org/?probe=d0439be169) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [cc7e14cb7d](https://linux-hardware.org/?probe=cc7e14cb7d) | Aug 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [9436e8a2ea](https://linux-hardware.org/?probe=9436e8a2ea) | Aug 06, 2021 |
| Acer          | Spin SP111-34N              | Convertible | [966360458f](https://linux-hardware.org/?probe=966360458f) | Aug 05, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [21df8e00b3](https://linux-hardware.org/?probe=21df8e00b3) | Aug 05, 2021 |
| Acer          | Spin SP111-34N              | Convertible | [7315375911](https://linux-hardware.org/?probe=7315375911) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [983611f01f](https://linux-hardware.org/?probe=983611f01f) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [5e399cedc5](https://linux-hardware.org/?probe=5e399cedc5) | Aug 05, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [ad0495c9d1](https://linux-hardware.org/?probe=ad0495c9d1) | Aug 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0db1faaeaf](https://linux-hardware.org/?probe=0db1faaeaf) | Aug 05, 2021 |
| Dell          | 097YXY A00                  | Desktop     | [39ce9f3df5](https://linux-hardware.org/?probe=39ce9f3df5) | Aug 04, 2021 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [42728265a9](https://linux-hardware.org/?probe=42728265a9) | Aug 04, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [ebe1293bff](https://linux-hardware.org/?probe=ebe1293bff) | Aug 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [eb9b4845c3](https://linux-hardware.org/?probe=eb9b4845c3) | Aug 04, 2021 |
| Timi          | TM1612                      | Notebook    | [9c80791f81](https://linux-hardware.org/?probe=9c80791f81) | Aug 04, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [854fc93a51](https://linux-hardware.org/?probe=854fc93a51) | Aug 04, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [14bb5ae34e](https://linux-hardware.org/?probe=14bb5ae34e) | Aug 03, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [26c16d2362](https://linux-hardware.org/?probe=26c16d2362) | Aug 03, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | Notebook    | [b83cac3113](https://linux-hardware.org/?probe=b83cac3113) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440s 20ARS2V90... | Notebook    | [aa03bf0e42](https://linux-hardware.org/?probe=aa03bf0e42) | Aug 03, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | Desktop     | [65e0d03193](https://linux-hardware.org/?probe=65e0d03193) | Aug 03, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0030... | Notebook    | [c4db4594bf](https://linux-hardware.org/?probe=c4db4594bf) | Aug 03, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f847512f79](https://linux-hardware.org/?probe=f847512f79) | Aug 03, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [70e98e9b9e](https://linux-hardware.org/?probe=70e98e9b9e) | Aug 02, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [b35c2e1e83](https://linux-hardware.org/?probe=b35c2e1e83) | Aug 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [67a5dfd8d6](https://linux-hardware.org/?probe=67a5dfd8d6) | Aug 02, 2021 |
| HP            | 8767 A                      | Desktop     | [08e746a681](https://linux-hardware.org/?probe=08e746a681) | Aug 02, 2021 |
| HP            | Presario CQ57               | Notebook    | [e0ccead71b](https://linux-hardware.org/?probe=e0ccead71b) | Aug 02, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [6177f24834](https://linux-hardware.org/?probe=6177f24834) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [58fb87de66](https://linux-hardware.org/?probe=58fb87de66) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8d891b7431](https://linux-hardware.org/?probe=8d891b7431) | Aug 02, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [7fa66f2f95](https://linux-hardware.org/?probe=7fa66f2f95) | Aug 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20eabf2484](https://linux-hardware.org/?probe=20eabf2484) | Aug 02, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [7c2abb5f03](https://linux-hardware.org/?probe=7c2abb5f03) | Aug 02, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [fbd8d927e6](https://linux-hardware.org/?probe=fbd8d927e6) | Aug 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [37e5e76ea0](https://linux-hardware.org/?probe=37e5e76ea0) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [490fa4535e](https://linux-hardware.org/?probe=490fa4535e) | Aug 01, 2021 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [41bc897e5b](https://linux-hardware.org/?probe=41bc897e5b) | Aug 01, 2021 |
| MSI           | 2AE0                        | Desktop     | [4c2c38d8a4](https://linux-hardware.org/?probe=4c2c38d8a4) | Aug 01, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [f1e1a28585](https://linux-hardware.org/?probe=f1e1a28585) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b877e6ca87](https://linux-hardware.org/?probe=b877e6ca87) | Jul 31, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [0580c6e530](https://linux-hardware.org/?probe=0580c6e530) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7c60081cf9](https://linux-hardware.org/?probe=7c60081cf9) | Jul 30, 2021 |
| Lenovo        | ThinkPad T420 423663G       | Notebook    | [5432482018](https://linux-hardware.org/?probe=5432482018) | Jul 30, 2021 |
| Acer          | Aspire F5-573               | Notebook    | [8ca138437d](https://linux-hardware.org/?probe=8ca138437d) | Jul 30, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [fb4032692a](https://linux-hardware.org/?probe=fb4032692a) | Jul 30, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f29d9ce9e4](https://linux-hardware.org/?probe=f29d9ce9e4) | Jul 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [e07e2a7ec0](https://linux-hardware.org/?probe=e07e2a7ec0) | Jul 30, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| Lenovo        | G770 1037                   | Notebook    | [dcc0bc28c6](https://linux-hardware.org/?probe=dcc0bc28c6) | Jul 30, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [9dd43d1e7a](https://linux-hardware.org/?probe=9dd43d1e7a) | Jul 30, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [20f550f120](https://linux-hardware.org/?probe=20f550f120) | Jul 29, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [ba1ddda65a](https://linux-hardware.org/?probe=ba1ddda65a) | Jul 29, 2021 |
| Acer          | Aspire F5-573               | Notebook    | [b9659974d6](https://linux-hardware.org/?probe=b9659974d6) | Jul 29, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [323bd4a7d0](https://linux-hardware.org/?probe=323bd4a7d0) | Jul 29, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [88a300abb6](https://linux-hardware.org/?probe=88a300abb6) | Jul 29, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [20c7598430](https://linux-hardware.org/?probe=20c7598430) | Jul 29, 2021 |
| HP            | 3398                        | Desktop     | [5e7de7b4b8](https://linux-hardware.org/?probe=5e7de7b4b8) | Jul 29, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [c41a93deb8](https://linux-hardware.org/?probe=c41a93deb8) | Jul 29, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [b4a1e99fc0](https://linux-hardware.org/?probe=b4a1e99fc0) | Jul 28, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [cc1c71078c](https://linux-hardware.org/?probe=cc1c71078c) | Jul 28, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b90f06f2eb](https://linux-hardware.org/?probe=b90f06f2eb) | Jul 28, 2021 |
| HP            | 843C                        | Desktop     | [9b7de9f08a](https://linux-hardware.org/?probe=9b7de9f08a) | Jul 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b00a4be291](https://linux-hardware.org/?probe=b00a4be291) | Jul 27, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [265ab10b75](https://linux-hardware.org/?probe=265ab10b75) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [80a7298343](https://linux-hardware.org/?probe=80a7298343) | Jul 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d27d622754](https://linux-hardware.org/?probe=d27d622754) | Jul 27, 2021 |
| Lenovo        | Board                       | Desktop     | [aa42758551](https://linux-hardware.org/?probe=aa42758551) | Jul 27, 2021 |
| Acer          | Aspire V3-551               | Notebook    | [3d4f4e38ce](https://linux-hardware.org/?probe=3d4f4e38ce) | Jul 27, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [4cc3e84ee3](https://linux-hardware.org/?probe=4cc3e84ee3) | Jul 27, 2021 |
| Acer          | Aspire V3-551               | Notebook    | [a86f57cf53](https://linux-hardware.org/?probe=a86f57cf53) | Jul 27, 2021 |
| HP            | 8437                        | Desktop     | [06f61b9a3f](https://linux-hardware.org/?probe=06f61b9a3f) | Jul 27, 2021 |
| HP            | 8437                        | Desktop     | [3e06775292](https://linux-hardware.org/?probe=3e06775292) | Jul 27, 2021 |
| Lenovo        | Board                       | Desktop     | [ea9486d3cb](https://linux-hardware.org/?probe=ea9486d3cb) | Jul 27, 2021 |
| Intel         | H61                         | Desktop     | [0c722a183c](https://linux-hardware.org/?probe=0c722a183c) | Jul 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0d0411116a](https://linux-hardware.org/?probe=0d0411116a) | Jul 26, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [45f00bac70](https://linux-hardware.org/?probe=45f00bac70) | Jul 26, 2021 |
| Packard Be... | EasyNote TV11HC             | Notebook    | [6e255437ad](https://linux-hardware.org/?probe=6e255437ad) | Jul 26, 2021 |
| ASUSTek       | K73BY                       | Notebook    | [b884d58259](https://linux-hardware.org/?probe=b884d58259) | Jul 26, 2021 |
| HP            | 255 G3                      | Notebook    | [cd8de84d34](https://linux-hardware.org/?probe=cd8de84d34) | Jul 26, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [19835b0c7f](https://linux-hardware.org/?probe=19835b0c7f) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d9f533bc60](https://linux-hardware.org/?probe=d9f533bc60) | Jul 25, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | Desktop     | [55e20e7b26](https://linux-hardware.org/?probe=55e20e7b26) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | Notebook    | [d1e3a988b1](https://linux-hardware.org/?probe=d1e3a988b1) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | Desktop     | [71e8ceac80](https://linux-hardware.org/?probe=71e8ceac80) | Jul 25, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [5b80d3040f](https://linux-hardware.org/?probe=5b80d3040f) | Jul 25, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [771ef872d9](https://linux-hardware.org/?probe=771ef872d9) | Jul 25, 2021 |
| Acer          | Aspire 4830TG               | Notebook    | [f3c5c8d207](https://linux-hardware.org/?probe=f3c5c8d207) | Jul 25, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [94bac3c66f](https://linux-hardware.org/?probe=94bac3c66f) | Jul 24, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [2b30561690](https://linux-hardware.org/?probe=2b30561690) | Jul 24, 2021 |
| Gigabyte      | Z490 AORUS XTREME           | Desktop     | [f4e7c92416](https://linux-hardware.org/?probe=f4e7c92416) | Jul 24, 2021 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [44ac8f3913](https://linux-hardware.org/?probe=44ac8f3913) | Jul 24, 2021 |
| Lenovo        | ThinkPad P53 20QQS0LW00     | Notebook    | [5a3284cdb5](https://linux-hardware.org/?probe=5a3284cdb5) | Jul 24, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | Desktop     | [f0937920ce](https://linux-hardware.org/?probe=f0937920ce) | Jul 24, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [d43ac798f5](https://linux-hardware.org/?probe=d43ac798f5) | Jul 24, 2021 |
| ASUSTek       | H81M-R                      | Desktop     | [4b99423aa2](https://linux-hardware.org/?probe=4b99423aa2) | Jul 24, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [5ee684a582](https://linux-hardware.org/?probe=5ee684a582) | Jul 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [bd29e505b9](https://linux-hardware.org/?probe=bd29e505b9) | Jul 24, 2021 |
| HP            | 18E7                        | Desktop     | [c0cddf4243](https://linux-hardware.org/?probe=c0cddf4243) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| HP            | Notebook                    | Notebook    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [2c81844355](https://linux-hardware.org/?probe=2c81844355) | Jul 23, 2021 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [b2680c0803](https://linux-hardware.org/?probe=b2680c0803) | Jul 23, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [96cd9229f0](https://linux-hardware.org/?probe=96cd9229f0) | Jul 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [c627d4fe6d](https://linux-hardware.org/?probe=c627d4fe6d) | Jul 23, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [93a813bbba](https://linux-hardware.org/?probe=93a813bbba) | Jul 22, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [ddeb632fba](https://linux-hardware.org/?probe=ddeb632fba) | Jul 22, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [f1e03c6033](https://linux-hardware.org/?probe=f1e03c6033) | Jul 21, 2021 |
| Timi          | A35S                        | Notebook    | [203b3229da](https://linux-hardware.org/?probe=203b3229da) | Jul 20, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [af87c52a43](https://linux-hardware.org/?probe=af87c52a43) | Jul 20, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| ASRock        | Z75 Pro3                    | Desktop     | [49f8efd16b](https://linux-hardware.org/?probe=49f8efd16b) | Jul 19, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6dea4c88d](https://linux-hardware.org/?probe=c6dea4c88d) | Jul 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8e540a6dfa](https://linux-hardware.org/?probe=8e540a6dfa) | Jul 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4b557e80dc](https://linux-hardware.org/?probe=4b557e80dc) | Jul 19, 2021 |
| ASRock        | H310M-HG4                   | Desktop     | [08454bc13f](https://linux-hardware.org/?probe=08454bc13f) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8fc400a46a](https://linux-hardware.org/?probe=8fc400a46a) | Jul 18, 2021 |
| HONOR         | NBD-WXX9                    | Notebook    | [1becd520d5](https://linux-hardware.org/?probe=1becd520d5) | Jul 18, 2021 |
| Google        | Kindred                     | Notebook    | [b05d56c825](https://linux-hardware.org/?probe=b05d56c825) | Jul 18, 2021 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [a5c0c36d23](https://linux-hardware.org/?probe=a5c0c36d23) | Jul 18, 2021 |
| Dell          | Inspiron 3780               | Notebook    | [b3bd1dbe25](https://linux-hardware.org/?probe=b3bd1dbe25) | Jul 18, 2021 |
| Dell          | Inspiron 3780               | Notebook    | [fba70c883f](https://linux-hardware.org/?probe=fba70c883f) | Jul 18, 2021 |
| HP            | 212A                        | Desktop     | [56cd9e7eaa](https://linux-hardware.org/?probe=56cd9e7eaa) | Jul 18, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [69f4400ea6](https://linux-hardware.org/?probe=69f4400ea6) | Jul 18, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [e5d91fa975](https://linux-hardware.org/?probe=e5d91fa975) | Jul 17, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [7f39dd8a29](https://linux-hardware.org/?probe=7f39dd8a29) | Jul 16, 2021 |
| Acer          | TravelMate P2410-G2-M       | Notebook    | [7088129430](https://linux-hardware.org/?probe=7088129430) | Jul 16, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [288b6b0769](https://linux-hardware.org/?probe=288b6b0769) | Jul 16, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9ceb18858a](https://linux-hardware.org/?probe=9ceb18858a) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [47397fcb5b](https://linux-hardware.org/?probe=47397fcb5b) | Jul 16, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [afa612eab2](https://linux-hardware.org/?probe=afa612eab2) | Jul 16, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [e0c6e30dd3](https://linux-hardware.org/?probe=e0c6e30dd3) | Jul 16, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [84c1debfb0](https://linux-hardware.org/?probe=84c1debfb0) | Jul 16, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1c12640b47](https://linux-hardware.org/?probe=1c12640b47) | Jul 15, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [3e04f9763c](https://linux-hardware.org/?probe=3e04f9763c) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [0c938c67c6](https://linux-hardware.org/?probe=0c938c67c6) | Jul 15, 2021 |
| HP            | Notebook                    | Notebook    | [2dc686eca0](https://linux-hardware.org/?probe=2dc686eca0) | Jul 15, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [7b8716662b](https://linux-hardware.org/?probe=7b8716662b) | Jul 14, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [610bb918de](https://linux-hardware.org/?probe=610bb918de) | Jul 14, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [402385e552](https://linux-hardware.org/?probe=402385e552) | Jul 14, 2021 |
| Acer          | Aspire E5-532               | Notebook    | [eecd3e1764](https://linux-hardware.org/?probe=eecd3e1764) | Jul 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [aae2aab87d](https://linux-hardware.org/?probe=aae2aab87d) | Jul 14, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0cc68536b5](https://linux-hardware.org/?probe=0cc68536b5) | Jul 14, 2021 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8d1152ff75](https://linux-hardware.org/?probe=8d1152ff75) | Jul 14, 2021 |
| HP            | 872E                        | Mini pc     | [dfca28cc5f](https://linux-hardware.org/?probe=dfca28cc5f) | Jul 14, 2021 |
| Lenovo        | ThinkPad T470 20HES0FX00    | Notebook    | [be6eee6fb4](https://linux-hardware.org/?probe=be6eee6fb4) | Jul 14, 2021 |
| Lenovo        | ThinkPad T470 20HES0FX00    | Notebook    | [dc49775174](https://linux-hardware.org/?probe=dc49775174) | Jul 14, 2021 |
| Teclast       | TbooK 10 S                  | Notebook    | [096daaa093](https://linux-hardware.org/?probe=096daaa093) | Jul 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [532e266dcb](https://linux-hardware.org/?probe=532e266dcb) | Jul 13, 2021 |
| HONOR         | NBD-WXX9                    | Notebook    | [038b75ac47](https://linux-hardware.org/?probe=038b75ac47) | Jul 13, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [2e706cd74a](https://linux-hardware.org/?probe=2e706cd74a) | Jul 13, 2021 |
| Dell          | 097YXY A00                  | Desktop     | [300a6a5871](https://linux-hardware.org/?probe=300a6a5871) | Jul 13, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [1c971f47d9](https://linux-hardware.org/?probe=1c971f47d9) | Jul 13, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [176c1d695d](https://linux-hardware.org/?probe=176c1d695d) | Jul 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [300cd4ff38](https://linux-hardware.org/?probe=300cd4ff38) | Jul 13, 2021 |
| HP            | 18E7                        | Desktop     | [03d84525e8](https://linux-hardware.org/?probe=03d84525e8) | Jul 13, 2021 |
| Apple         | MacBookAir5,2               | Notebook    | [282dc998b0](https://linux-hardware.org/?probe=282dc998b0) | Jul 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c6b9d9da5c](https://linux-hardware.org/?probe=c6b9d9da5c) | Jul 13, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [f60f031bde](https://linux-hardware.org/?probe=f60f031bde) | Jul 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [427828621f](https://linux-hardware.org/?probe=427828621f) | Jul 12, 2021 |
| MSI           | B250M GAMING PRO            | Desktop     | [93f476cea0](https://linux-hardware.org/?probe=93f476cea0) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50f500af5b](https://linux-hardware.org/?probe=50f500af5b) | Jul 12, 2021 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [422410f18b](https://linux-hardware.org/?probe=422410f18b) | Jul 12, 2021 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5301fe2213](https://linux-hardware.org/?probe=5301fe2213) | Jul 12, 2021 |
| Star Labs     | LabTop                      | Notebook    | [66b11f0101](https://linux-hardware.org/?probe=66b11f0101) | Jul 12, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a7a2abffd6](https://linux-hardware.org/?probe=a7a2abffd6) | Jul 12, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [abde1921e9](https://linux-hardware.org/?probe=abde1921e9) | Jul 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [88e83727c2](https://linux-hardware.org/?probe=88e83727c2) | Jul 12, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [04163e3fa8](https://linux-hardware.org/?probe=04163e3fa8) | Jul 12, 2021 |
| HP            | 3047h                       | Desktop     | [27e2083302](https://linux-hardware.org/?probe=27e2083302) | Jul 12, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [247cd4997f](https://linux-hardware.org/?probe=247cd4997f) | Jul 12, 2021 |
| HP            | 3047h                       | Desktop     | [dd341bf85a](https://linux-hardware.org/?probe=dd341bf85a) | Jul 12, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [35eef02824](https://linux-hardware.org/?probe=35eef02824) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [83b65f2c8e](https://linux-hardware.org/?probe=83b65f2c8e) | Jul 11, 2021 |
| Intel         | NUC11TNBi5 M11904-403       | Mini pc     | [7542ba6c47](https://linux-hardware.org/?probe=7542ba6c47) | Jul 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [6d44a79029](https://linux-hardware.org/?probe=6d44a79029) | Jul 11, 2021 |
| Sony          | VGN-SR11MR                  | Notebook    | [b2c0a09286](https://linux-hardware.org/?probe=b2c0a09286) | Jul 11, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bc36fb9437](https://linux-hardware.org/?probe=bc36fb9437) | Jul 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7a7638e735](https://linux-hardware.org/?probe=7a7638e735) | Jul 11, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [e6255c5a59](https://linux-hardware.org/?probe=e6255c5a59) | Jul 11, 2021 |
| Samsung       | R530/R730                   | Notebook    | [103edb36d2](https://linux-hardware.org/?probe=103edb36d2) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [ff5e8e2016](https://linux-hardware.org/?probe=ff5e8e2016) | Jul 10, 2021 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [60a9c6d0bd](https://linux-hardware.org/?probe=60a9c6d0bd) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [025340fa5f](https://linux-hardware.org/?probe=025340fa5f) | Jul 10, 2021 |
| Supermicro    | X8DTH                       | Server      | [2cd9beee8c](https://linux-hardware.org/?probe=2cd9beee8c) | Jul 10, 2021 |
| HP            | 8643 SMVB                   | Desktop     | [167dd357d0](https://linux-hardware.org/?probe=167dd357d0) | Jul 09, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a0d1904129](https://linux-hardware.org/?probe=a0d1904129) | Jul 09, 2021 |
| AMD           | 970A-D3                     | Desktop     | [95fa7132e5](https://linux-hardware.org/?probe=95fa7132e5) | Jul 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [e4a82a9774](https://linux-hardware.org/?probe=e4a82a9774) | Jul 09, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [b293f94839](https://linux-hardware.org/?probe=b293f94839) | Jul 09, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [23105ea565](https://linux-hardware.org/?probe=23105ea565) | Jul 09, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [e689bf94fe](https://linux-hardware.org/?probe=e689bf94fe) | Jul 09, 2021 |
| Samsung       | 520U4C/520U4X               | Notebook    | [356e4d7151](https://linux-hardware.org/?probe=356e4d7151) | Jul 09, 2021 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [f8be96c44a](https://linux-hardware.org/?probe=f8be96c44a) | Jul 09, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4e446a2f6a](https://linux-hardware.org/?probe=4e446a2f6a) | Jul 09, 2021 |
| Acer          | Spin SP111-34N              | Convertible | [c090bcd688](https://linux-hardware.org/?probe=c090bcd688) | Jul 09, 2021 |
| Acer          | Spin SP111-34N              | Convertible | [8f70dc10db](https://linux-hardware.org/?probe=8f70dc10db) | Jul 09, 2021 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [1d9cf03bf3](https://linux-hardware.org/?probe=1d9cf03bf3) | Jul 09, 2021 |
| Pegatron      | 2A99                        | Desktop     | [95093cac58](https://linux-hardware.org/?probe=95093cac58) | Jul 09, 2021 |
| Sony          | VGN-SR11MR                  | Notebook    | [51f4cf53d6](https://linux-hardware.org/?probe=51f4cf53d6) | Jul 08, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d52206ed3d](https://linux-hardware.org/?probe=d52206ed3d) | Jul 08, 2021 |
| Dell          | 0N867P A02                  | Desktop     | [da767a9476](https://linux-hardware.org/?probe=da767a9476) | Jul 08, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [6f6b7cbdf5](https://linux-hardware.org/?probe=6f6b7cbdf5) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [bcc1877c20](https://linux-hardware.org/?probe=bcc1877c20) | Jul 08, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [222c467b30](https://linux-hardware.org/?probe=222c467b30) | Jul 08, 2021 |
| Dell          | 0N867P A02                  | Desktop     | [33c3239e68](https://linux-hardware.org/?probe=33c3239e68) | Jul 08, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [95b6f836aa](https://linux-hardware.org/?probe=95b6f836aa) | Jul 08, 2021 |
| Dell          | 0KV62T A00                  | Desktop     | [1b054bb288](https://linux-hardware.org/?probe=1b054bb288) | Jul 08, 2021 |
| Dell          | 0KV62T A00                  | Desktop     | [57488ccc98](https://linux-hardware.org/?probe=57488ccc98) | Jul 08, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [dca13f88c7](https://linux-hardware.org/?probe=dca13f88c7) | Jul 08, 2021 |
| Dell          | 0DR845                      | Desktop     | [96c970127e](https://linux-hardware.org/?probe=96c970127e) | Jul 08, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [24f88bad7b](https://linux-hardware.org/?probe=24f88bad7b) | Jul 07, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [4d5cea91ad](https://linux-hardware.org/?probe=4d5cea91ad) | Jul 07, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [12ffb2db61](https://linux-hardware.org/?probe=12ffb2db61) | Jul 07, 2021 |
| MSI           | B150M ECO                   | Desktop     | [c97e6af0f2](https://linux-hardware.org/?probe=c97e6af0f2) | Jul 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5aa7505f65](https://linux-hardware.org/?probe=5aa7505f65) | Jul 07, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d0ad741532](https://linux-hardware.org/?probe=d0ad741532) | Jul 07, 2021 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [e661874cb2](https://linux-hardware.org/?probe=e661874cb2) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a88a1df2f5](https://linux-hardware.org/?probe=a88a1df2f5) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [77f6869d84](https://linux-hardware.org/?probe=77f6869d84) | Jul 07, 2021 |
| Unknown       | Unknown                     | Mini pc     | [62f62342c5](https://linux-hardware.org/?probe=62f62342c5) | Jul 07, 2021 |
| Dell          | Precision 5530              | Notebook    | [a2698d4e69](https://linux-hardware.org/?probe=a2698d4e69) | Jul 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [d230beaf72](https://linux-hardware.org/?probe=d230beaf72) | Jul 07, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [bf1d5b8d96](https://linux-hardware.org/?probe=bf1d5b8d96) | Jul 06, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [9b525f7832](https://linux-hardware.org/?probe=9b525f7832) | Jul 06, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [751acf1dac](https://linux-hardware.org/?probe=751acf1dac) | Jul 06, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [8c12c26efd](https://linux-hardware.org/?probe=8c12c26efd) | Jul 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [ec562cbbed](https://linux-hardware.org/?probe=ec562cbbed) | Jul 06, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e449104cb1](https://linux-hardware.org/?probe=e449104cb1) | Jul 06, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [914f5ee7dd](https://linux-hardware.org/?probe=914f5ee7dd) | Jul 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1bd2963aa0](https://linux-hardware.org/?probe=1bd2963aa0) | Jul 06, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [4e5088a32a](https://linux-hardware.org/?probe=4e5088a32a) | Jul 06, 2021 |
| Lenovo        | ThinkPad T410 2537KR6       | Notebook    | [8226c09c23](https://linux-hardware.org/?probe=8226c09c23) | Jul 05, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4d1b1ed48f](https://linux-hardware.org/?probe=4d1b1ed48f) | Jul 05, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0bdc8750c3](https://linux-hardware.org/?probe=0bdc8750c3) | Jul 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [21de58e8c0](https://linux-hardware.org/?probe=21de58e8c0) | Jul 05, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [73c9397098](https://linux-hardware.org/?probe=73c9397098) | Jul 05, 2021 |
| ASUSTek       | K401UQ                      | Notebook    | [9f9a853e03](https://linux-hardware.org/?probe=9f9a853e03) | Jul 05, 2021 |
| Google        | Ekko                        | Notebook    | [05351ac012](https://linux-hardware.org/?probe=05351ac012) | Jul 05, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [9078ad4c9f](https://linux-hardware.org/?probe=9078ad4c9f) | Jul 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [4b6753e3b4](https://linux-hardware.org/?probe=4b6753e3b4) | Jul 04, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [56c6bcf36b](https://linux-hardware.org/?probe=56c6bcf36b) | Jul 04, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [d90c6cbf04](https://linux-hardware.org/?probe=d90c6cbf04) | Jul 04, 2021 |
| ASUSTek       | P7P55-M                     | Desktop     | [f78850b2d2](https://linux-hardware.org/?probe=f78850b2d2) | Jul 04, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [7d718f3e0c](https://linux-hardware.org/?probe=7d718f3e0c) | Jul 04, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3fcdda6371](https://linux-hardware.org/?probe=3fcdda6371) | Jul 04, 2021 |
| HP            | 212B                        | Desktop     | [17ed8f7604](https://linux-hardware.org/?probe=17ed8f7604) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [e735a4421a](https://linux-hardware.org/?probe=e735a4421a) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [def9f42f6c](https://linux-hardware.org/?probe=def9f42f6c) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [f32b18c185](https://linux-hardware.org/?probe=f32b18c185) | Jul 02, 2021 |
| MSI           | PS42 8RB                    | Notebook    | [f14eb40c10](https://linux-hardware.org/?probe=f14eb40c10) | Jul 02, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [f17656a521](https://linux-hardware.org/?probe=f17656a521) | Jul 02, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8313d3ba2e](https://linux-hardware.org/?probe=8313d3ba2e) | Jul 02, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0812ba2f1d](https://linux-hardware.org/?probe=0812ba2f1d) | Jul 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [b30925c792](https://linux-hardware.org/?probe=b30925c792) | Jul 01, 2021 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [d1ccd9254a](https://linux-hardware.org/?probe=d1ccd9254a) | Jul 01, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [2400f68450](https://linux-hardware.org/?probe=2400f68450) | Jul 01, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [cbda299075](https://linux-hardware.org/?probe=cbda299075) | Jul 01, 2021 |
| Dell          | 0W0CHX A01                  | Desktop     | [e0a09aa1a5](https://linux-hardware.org/?probe=e0a09aa1a5) | Jul 01, 2021 |
| MSI           | GL63 8RD                    | Notebook    | [87b563bdd7](https://linux-hardware.org/?probe=87b563bdd7) | Jul 01, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a2e3a6298](https://linux-hardware.org/?probe=1a2e3a6298) | Jul 01, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [76131339cb](https://linux-hardware.org/?probe=76131339cb) | Jun 30, 2021 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [115ededeb2](https://linux-hardware.org/?probe=115ededeb2) | Jun 30, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [c9e2af3662](https://linux-hardware.org/?probe=c9e2af3662) | Jun 30, 2021 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [d7662e3ec4](https://linux-hardware.org/?probe=d7662e3ec4) | Jun 30, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2ffe8751ce](https://linux-hardware.org/?probe=2ffe8751ce) | Jun 30, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [a9d39196ef](https://linux-hardware.org/?probe=a9d39196ef) | Jun 30, 2021 |
| Timi          | RedmiBook 16                | Notebook    | [50b2bd63ee](https://linux-hardware.org/?probe=50b2bd63ee) | Jun 30, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [cb13ff6570](https://linux-hardware.org/?probe=cb13ff6570) | Jun 30, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [ef66765380](https://linux-hardware.org/?probe=ef66765380) | Jun 30, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [985f11d604](https://linux-hardware.org/?probe=985f11d604) | Jun 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e2743844ad](https://linux-hardware.org/?probe=e2743844ad) | Jun 29, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [ee9a33e3d6](https://linux-hardware.org/?probe=ee9a33e3d6) | Jun 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [9baddf5afd](https://linux-hardware.org/?probe=9baddf5afd) | Jun 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a7417bd833](https://linux-hardware.org/?probe=a7417bd833) | Jun 28, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [2edcde427c](https://linux-hardware.org/?probe=2edcde427c) | Jun 28, 2021 |
| Samsung       | RF712                       | Notebook    | [535f6d5c8b](https://linux-hardware.org/?probe=535f6d5c8b) | Jun 28, 2021 |
| Schenker      | SCHENKER_SLIM14_SSL14L19    | Notebook    | [f3011454f5](https://linux-hardware.org/?probe=f3011454f5) | Jun 28, 2021 |
| Schenker      | SCHENKER_SLIM14_SSL14L19    | Notebook    | [5d23cf78e1](https://linux-hardware.org/?probe=5d23cf78e1) | Jun 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [0cc4327df6](https://linux-hardware.org/?probe=0cc4327df6) | Jun 28, 2021 |
| Dell          | Latitude E7470              | Notebook    | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [a6a1935419](https://linux-hardware.org/?probe=a6a1935419) | Jun 27, 2021 |
| HP            | 339A                        | Desktop     | [f7045a85f1](https://linux-hardware.org/?probe=f7045a85f1) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [af518ffcbd](https://linux-hardware.org/?probe=af518ffcbd) | Jun 27, 2021 |
| HP            | 339A                        | Desktop     | [efc2a68df7](https://linux-hardware.org/?probe=efc2a68df7) | Jun 27, 2021 |
| Multilaser    | PC301                       | Notebook    | [55b685927b](https://linux-hardware.org/?probe=55b685927b) | Jun 27, 2021 |
| Sony          | VGN-SR11MR                  | Notebook    | [6e386e9a8f](https://linux-hardware.org/?probe=6e386e9a8f) | Jun 27, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [633004c28c](https://linux-hardware.org/?probe=633004c28c) | Jun 27, 2021 |
| Sony          | VGN-SR11MR                  | Notebook    | [11a3d84878](https://linux-hardware.org/?probe=11a3d84878) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [795eda0f4c](https://linux-hardware.org/?probe=795eda0f4c) | Jun 27, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [00c095bc61](https://linux-hardware.org/?probe=00c095bc61) | Jun 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75e20e29df](https://linux-hardware.org/?probe=75e20e29df) | Jun 26, 2021 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [6947fe0c62](https://linux-hardware.org/?probe=6947fe0c62) | Jun 26, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [016ae4ca5b](https://linux-hardware.org/?probe=016ae4ca5b) | Jun 26, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [21f95ca802](https://linux-hardware.org/?probe=21f95ca802) | Jun 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e64ce85717](https://linux-hardware.org/?probe=e64ce85717) | Jun 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [0f2110892b](https://linux-hardware.org/?probe=0f2110892b) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [254ec7747f](https://linux-hardware.org/?probe=254ec7747f) | Jun 25, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [b7ccbbbdac](https://linux-hardware.org/?probe=b7ccbbbdac) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e6a2788612](https://linux-hardware.org/?probe=e6a2788612) | Jun 25, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f1088ef024](https://linux-hardware.org/?probe=f1088ef024) | Jun 25, 2021 |
| HP            | Pavilion 15                 | Notebook    | [425cadcae4](https://linux-hardware.org/?probe=425cadcae4) | Jun 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [13b457a4c9](https://linux-hardware.org/?probe=13b457a4c9) | Jun 25, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [59f098366f](https://linux-hardware.org/?probe=59f098366f) | Jun 24, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2YL0... | Notebook    | [338c2a41b3](https://linux-hardware.org/?probe=338c2a41b3) | Jun 24, 2021 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [6995133402](https://linux-hardware.org/?probe=6995133402) | Jun 24, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3bdba9944](https://linux-hardware.org/?probe=e3bdba9944) | Jun 24, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [edbc0b05ab](https://linux-hardware.org/?probe=edbc0b05ab) | Jun 23, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7767a1cde7](https://linux-hardware.org/?probe=7767a1cde7) | Jun 23, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [54311d58e1](https://linux-hardware.org/?probe=54311d58e1) | Jun 23, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [1ffdf184c5](https://linux-hardware.org/?probe=1ffdf184c5) | Jun 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [0d10716049](https://linux-hardware.org/?probe=0d10716049) | Jun 22, 2021 |
| Acer          | Swift SF514-52T             | Notebook    | [9e0f7fa4a4](https://linux-hardware.org/?probe=9e0f7fa4a4) | Jun 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [c68f31590c](https://linux-hardware.org/?probe=c68f31590c) | Jun 22, 2021 |
| MSI           | Z170A SLI PLUS              | Desktop     | [d715625644](https://linux-hardware.org/?probe=d715625644) | Jun 22, 2021 |
| Dell          | XPS 15 9575                 | Convertible | [1f0047afe8](https://linux-hardware.org/?probe=1f0047afe8) | Jun 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6fc5273b4b](https://linux-hardware.org/?probe=6fc5273b4b) | Jun 22, 2021 |
| Multilaser    | PC301                       | Notebook    | [71d16b6679](https://linux-hardware.org/?probe=71d16b6679) | Jun 21, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [be0bf36f42](https://linux-hardware.org/?probe=be0bf36f42) | Jun 21, 2021 |
| Google        | Peppy                       | Notebook    | [2e7909a66d](https://linux-hardware.org/?probe=2e7909a66d) | Jun 21, 2021 |
| Google        | Peppy                       | Notebook    | [a97829b01e](https://linux-hardware.org/?probe=a97829b01e) | Jun 21, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [d04705eaef](https://linux-hardware.org/?probe=d04705eaef) | Jun 20, 2021 |
| Notebook      | W740SU                      | Notebook    | [874b5c706a](https://linux-hardware.org/?probe=874b5c706a) | Jun 20, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c76462e732](https://linux-hardware.org/?probe=c76462e732) | Jun 20, 2021 |
| MSI           | H81I                        | Desktop     | [9da600784e](https://linux-hardware.org/?probe=9da600784e) | Jun 20, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7fe08a233a](https://linux-hardware.org/?probe=7fe08a233a) | Jun 20, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [f099f238fd](https://linux-hardware.org/?probe=f099f238fd) | Jun 19, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| MSI           | H81I                        | Desktop     | [ae29e406d6](https://linux-hardware.org/?probe=ae29e406d6) | Jun 19, 2021 |
| ASRock        | B360M Xtreme                | Desktop     | [6f72c14952](https://linux-hardware.org/?probe=6f72c14952) | Jun 19, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [43ef80b625](https://linux-hardware.org/?probe=43ef80b625) | Jun 19, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [439593d28e](https://linux-hardware.org/?probe=439593d28e) | Jun 19, 2021 |
| Lenovo        | ThinkPad X240 20AMS26F00    | Notebook    | [f74e9b1255](https://linux-hardware.org/?probe=f74e9b1255) | Jun 19, 2021 |
| Lenovo        | ThinkPad X240 20AMS26F00    | Notebook    | [68fd6d65fe](https://linux-hardware.org/?probe=68fd6d65fe) | Jun 19, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [50a09c8dbd](https://linux-hardware.org/?probe=50a09c8dbd) | Jun 19, 2021 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1154063733](https://linux-hardware.org/?probe=1154063733) | Jun 19, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [8b9f25c98b](https://linux-hardware.org/?probe=8b9f25c98b) | Jun 19, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d3eff8785e](https://linux-hardware.org/?probe=d3eff8785e) | Jun 19, 2021 |
| Lenovo        | ThinkPad T450 20BV000DUS    | Notebook    | [04a4305735](https://linux-hardware.org/?probe=04a4305735) | Jun 19, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [4833388359](https://linux-hardware.org/?probe=4833388359) | Jun 18, 2021 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [7ae699d160](https://linux-hardware.org/?probe=7ae699d160) | Jun 18, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [6f461f3c1e](https://linux-hardware.org/?probe=6f461f3c1e) | Jun 18, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [f8c3eb2017](https://linux-hardware.org/?probe=f8c3eb2017) | Jun 18, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e8a5139869](https://linux-hardware.org/?probe=e8a5139869) | Jun 18, 2021 |
| Lenovo        | ThinkPad T450 20BV000DUS    | Notebook    | [fc1f25158e](https://linux-hardware.org/?probe=fc1f25158e) | Jun 18, 2021 |
| Notebook      | W65_W67RZ1                  | Notebook    | [2a40ac68da](https://linux-hardware.org/?probe=2a40ac68da) | Jun 18, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e9d94e06f1](https://linux-hardware.org/?probe=e9d94e06f1) | Jun 18, 2021 |
| Intel         | H55 INTEL                   | Desktop     | [6c8ddcd99b](https://linux-hardware.org/?probe=6c8ddcd99b) | Jun 17, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [6eb1b5cb5d](https://linux-hardware.org/?probe=6eb1b5cb5d) | Jun 17, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [5b93bcdc50](https://linux-hardware.org/?probe=5b93bcdc50) | Jun 17, 2021 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [4d09439ef7](https://linux-hardware.org/?probe=4d09439ef7) | Jun 17, 2021 |
| ASRock        | B360M Xtreme                | Desktop     | [9df3a36025](https://linux-hardware.org/?probe=9df3a36025) | Jun 17, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [0a8a0272de](https://linux-hardware.org/?probe=0a8a0272de) | Jun 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7563cf4f19](https://linux-hardware.org/?probe=7563cf4f19) | Jun 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a5b1129bb5](https://linux-hardware.org/?probe=a5b1129bb5) | Jun 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [22c9d6c7de](https://linux-hardware.org/?probe=22c9d6c7de) | Jun 16, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [8489c2150d](https://linux-hardware.org/?probe=8489c2150d) | Jun 16, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [cb71a2d937](https://linux-hardware.org/?probe=cb71a2d937) | Jun 16, 2021 |
| Dell          | Latitude E5450              | Notebook    | [81ae47e8e5](https://linux-hardware.org/?probe=81ae47e8e5) | Jun 16, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [55619bf1dc](https://linux-hardware.org/?probe=55619bf1dc) | Jun 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [fa35222ed7](https://linux-hardware.org/?probe=fa35222ed7) | Jun 16, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [d789e20cee](https://linux-hardware.org/?probe=d789e20cee) | Jun 15, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [e33843092a](https://linux-hardware.org/?probe=e33843092a) | Jun 15, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [51a5eb8469](https://linux-hardware.org/?probe=51a5eb8469) | Jun 15, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [f7b20c6d06](https://linux-hardware.org/?probe=f7b20c6d06) | Jun 15, 2021 |
| Lenovo        | Yoga S730-13IML 81U4        | Notebook    | [a357c549d3](https://linux-hardware.org/?probe=a357c549d3) | Jun 15, 2021 |
| Lenovo        | ThinkPad T470s 20HF0000R... | Notebook    | [67e31eddda](https://linux-hardware.org/?probe=67e31eddda) | Jun 15, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [5332747c68](https://linux-hardware.org/?probe=5332747c68) | Jun 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [dc4638687a](https://linux-hardware.org/?probe=dc4638687a) | Jun 15, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [9a8312032f](https://linux-hardware.org/?probe=9a8312032f) | Jun 15, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [f803b837d5](https://linux-hardware.org/?probe=f803b837d5) | Jun 15, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d4bdba3b19](https://linux-hardware.org/?probe=d4bdba3b19) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [2f73140174](https://linux-hardware.org/?probe=2f73140174) | Jun 14, 2021 |
| Sony          | VGN-SR11MR                  | Notebook    | [e950efc058](https://linux-hardware.org/?probe=e950efc058) | Jun 14, 2021 |
| MSI           | H81I                        | Desktop     | [5f8c385421](https://linux-hardware.org/?probe=5f8c385421) | Jun 14, 2021 |
| Dell          | Latitude 5590               | Notebook    | [7426bd2bfa](https://linux-hardware.org/?probe=7426bd2bfa) | Jun 14, 2021 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [36a736b616](https://linux-hardware.org/?probe=36a736b616) | Jun 14, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [40ad2c3f08](https://linux-hardware.org/?probe=40ad2c3f08) | Jun 14, 2021 |
| SANTECH       | PCX0DX                      | Notebook    | [d900b00344](https://linux-hardware.org/?probe=d900b00344) | Jun 13, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [e6bdb7d91e](https://linux-hardware.org/?probe=e6bdb7d91e) | Jun 13, 2021 |
| Lenovo        | G575 20081                  | Notebook    | [9ff42cacec](https://linux-hardware.org/?probe=9ff42cacec) | Jun 13, 2021 |
| Lenovo        | G575 20081                  | Notebook    | [7c640d46ae](https://linux-hardware.org/?probe=7c640d46ae) | Jun 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Dell          | Latitude E5550              | Notebook    | [d76e5c2a03](https://linux-hardware.org/?probe=d76e5c2a03) | Jun 12, 2021 |
| Lenovo        | H310                        | Desktop     | [309031a039](https://linux-hardware.org/?probe=309031a039) | Jun 12, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [026e5cffe4](https://linux-hardware.org/?probe=026e5cffe4) | Jun 11, 2021 |
| HP            | 212B                        | Desktop     | [cccf3ad9d7](https://linux-hardware.org/?probe=cccf3ad9d7) | Jun 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [77f9400e70](https://linux-hardware.org/?probe=77f9400e70) | Jun 11, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [d6db04ed89](https://linux-hardware.org/?probe=d6db04ed89) | Jun 11, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [6075f884f6](https://linux-hardware.org/?probe=6075f884f6) | Jun 11, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [816f7da8de](https://linux-hardware.org/?probe=816f7da8de) | Jun 10, 2021 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [4bbf266b53](https://linux-hardware.org/?probe=4bbf266b53) | Jun 10, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [d6ca3a26d9](https://linux-hardware.org/?probe=d6ca3a26d9) | Jun 10, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a0ddd8a58c](https://linux-hardware.org/?probe=a0ddd8a58c) | Jun 10, 2021 |
| Packard Be... | ipower G5800                | Desktop     | [6978d14549](https://linux-hardware.org/?probe=6978d14549) | Jun 10, 2021 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| HP            | 8436                        | Desktop     | [f8cefa0267](https://linux-hardware.org/?probe=f8cefa0267) | Jun 09, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [e0d6a428c2](https://linux-hardware.org/?probe=e0d6a428c2) | Jun 09, 2021 |
| ASUSTek       | TUF GAMING Z490-PLUS        | Desktop     | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [72168c7c5d](https://linux-hardware.org/?probe=72168c7c5d) | Jun 09, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [68ec58f92a](https://linux-hardware.org/?probe=68ec58f92a) | Jun 08, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [1d17ef91f5](https://linux-hardware.org/?probe=1d17ef91f5) | Jun 08, 2021 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [1858917700](https://linux-hardware.org/?probe=1858917700) | Jun 08, 2021 |
| ASUSTek       | K53U                        | Notebook    | [3acb45024a](https://linux-hardware.org/?probe=3acb45024a) | Jun 08, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [ce1e41c6b2](https://linux-hardware.org/?probe=ce1e41c6b2) | Jun 08, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [f081686c26](https://linux-hardware.org/?probe=f081686c26) | Jun 08, 2021 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [c23781809b](https://linux-hardware.org/?probe=c23781809b) | Jun 08, 2021 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [73ed42ce55](https://linux-hardware.org/?probe=73ed42ce55) | Jun 08, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | GP63 Leopard 8RF            | Notebook    | [d9f35040b9](https://linux-hardware.org/?probe=d9f35040b9) | Jun 08, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [72607c5291](https://linux-hardware.org/?probe=72607c5291) | Jun 07, 2021 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [9bf0fe4130](https://linux-hardware.org/?probe=9bf0fe4130) | Jun 07, 2021 |
| HP            | ENVY 15                     | Notebook    | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [dd1471e42c](https://linux-hardware.org/?probe=dd1471e42c) | Jun 07, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [9a300fec29](https://linux-hardware.org/?probe=9a300fec29) | Jun 07, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [ee3eb77530](https://linux-hardware.org/?probe=ee3eb77530) | Jun 07, 2021 |
| Lenovo        | ThinkPad T460 20FMS2D600    | Notebook    | [2150a97717](https://linux-hardware.org/?probe=2150a97717) | Jun 06, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [2324c596b3](https://linux-hardware.org/?probe=2324c596b3) | Jun 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [53b3f56f7e](https://linux-hardware.org/?probe=53b3f56f7e) | Jun 06, 2021 |
| Packard Be... | ipower G5800                | Desktop     | [22042b1727](https://linux-hardware.org/?probe=22042b1727) | Jun 06, 2021 |
| ASUSTek       | TUF GAMING Z490-PLUS        | Desktop     | [599b4af4cf](https://linux-hardware.org/?probe=599b4af4cf) | Jun 06, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [deb578adc9](https://linux-hardware.org/?probe=deb578adc9) | Jun 06, 2021 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [22f5d8b296](https://linux-hardware.org/?probe=22f5d8b296) | Jun 06, 2021 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [0592a0c693](https://linux-hardware.org/?probe=0592a0c693) | Jun 06, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0WL0... | Notebook    | [396c8bd5a4](https://linux-hardware.org/?probe=396c8bd5a4) | Jun 06, 2021 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [6f4295380b](https://linux-hardware.org/?probe=6f4295380b) | Jun 06, 2021 |
| Lenovo        | H310                        | Desktop     | [3fcd2a8ff0](https://linux-hardware.org/?probe=3fcd2a8ff0) | Jun 06, 2021 |
| Lenovo        | H310                        | Desktop     | [f36653c4fb](https://linux-hardware.org/?probe=f36653c4fb) | Jun 06, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [511d902317](https://linux-hardware.org/?probe=511d902317) | Jun 06, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [19f07435fc](https://linux-hardware.org/?probe=19f07435fc) | Jun 05, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [efb0b681f0](https://linux-hardware.org/?probe=efb0b681f0) | Jun 05, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [d69e4bf972](https://linux-hardware.org/?probe=d69e4bf972) | Jun 04, 2021 |
| Dell          | Precision M4600             | Notebook    | [b1bc313622](https://linux-hardware.org/?probe=b1bc313622) | Jun 04, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [c8f0fcf24b](https://linux-hardware.org/?probe=c8f0fcf24b) | Jun 04, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a5f9991c55](https://linux-hardware.org/?probe=a5f9991c55) | Jun 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [820516f627](https://linux-hardware.org/?probe=820516f627) | Jun 04, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [00d1d057e5](https://linux-hardware.org/?probe=00d1d057e5) | Jun 03, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [dcea776f2d](https://linux-hardware.org/?probe=dcea776f2d) | Jun 03, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [0d8f86bc6f](https://linux-hardware.org/?probe=0d8f86bc6f) | Jun 03, 2021 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [d0428398f6](https://linux-hardware.org/?probe=d0428398f6) | Jun 03, 2021 |
| MSI           | H81M-P33                    | Desktop     | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| Lenovo        | ThinkPad L490 20Q6S08600    | Notebook    | [43487c60b3](https://linux-hardware.org/?probe=43487c60b3) | Jun 02, 2021 |
| Lenovo        | ThinkPad L490 20Q6S08600    | Notebook    | [0264f97240](https://linux-hardware.org/?probe=0264f97240) | Jun 02, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [60d052c05d](https://linux-hardware.org/?probe=60d052c05d) | Jun 02, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [b21d98595a](https://linux-hardware.org/?probe=b21d98595a) | Jun 02, 2021 |
| HP            | 82F2                        | Desktop     | [6e39f485fa](https://linux-hardware.org/?probe=6e39f485fa) | Jun 02, 2021 |
| Lenovo        | ThinkPad E475 20H4CTO1WW    | Notebook    | [7d45268487](https://linux-hardware.org/?probe=7d45268487) | Jun 02, 2021 |
| HP            | 82F2                        | Desktop     | [6f6cb7bd60](https://linux-hardware.org/?probe=6f6cb7bd60) | Jun 02, 2021 |
| HP            | 85A2                        | All in one  | [f0691e6eda](https://linux-hardware.org/?probe=f0691e6eda) | Jun 02, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [0a074f7196](https://linux-hardware.org/?probe=0a074f7196) | Jun 02, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [ca13ed3341](https://linux-hardware.org/?probe=ca13ed3341) | Jun 02, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [2b0f0f0333](https://linux-hardware.org/?probe=2b0f0f0333) | Jun 02, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [ca5008ebaf](https://linux-hardware.org/?probe=ca5008ebaf) | Jun 02, 2021 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [a25665710e](https://linux-hardware.org/?probe=a25665710e) | Jun 01, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [72c6428c32](https://linux-hardware.org/?probe=72c6428c32) | Jun 01, 2021 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [5e809e3c9c](https://linux-hardware.org/?probe=5e809e3c9c) | Jun 01, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [15de6a42cc](https://linux-hardware.org/?probe=15de6a42cc) | Jun 01, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [c685658547](https://linux-hardware.org/?probe=c685658547) | Jun 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f504e72617](https://linux-hardware.org/?probe=f504e72617) | Jun 01, 2021 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [f544511e0a](https://linux-hardware.org/?probe=f544511e0a) | Jun 01, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [01c5e2e798](https://linux-hardware.org/?probe=01c5e2e798) | May 31, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [e1b676d2a4](https://linux-hardware.org/?probe=e1b676d2a4) | May 31, 2021 |
| Biostar       | G31D-M7                     | Desktop     | [960762905f](https://linux-hardware.org/?probe=960762905f) | May 31, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [acd068603b](https://linux-hardware.org/?probe=acd068603b) | May 31, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [f7e3cd3e35](https://linux-hardware.org/?probe=f7e3cd3e35) | May 31, 2021 |
| Dell          | 0R23KR A01                  | Desktop     | [862b2d2013](https://linux-hardware.org/?probe=862b2d2013) | May 31, 2021 |
| Dell          | XPS MXC062                  | Notebook    | [cde37c331e](https://linux-hardware.org/?probe=cde37c331e) | May 31, 2021 |
| Lenovo        | ThinkPad E490 20N8000YGE    | Notebook    | [62c94909c7](https://linux-hardware.org/?probe=62c94909c7) | May 31, 2021 |
| Lenovo        | Zhaoyang K29 20186          | Notebook    | [f02d15e805](https://linux-hardware.org/?probe=f02d15e805) | May 31, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [804cee7367](https://linux-hardware.org/?probe=804cee7367) | May 31, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [4957caa987](https://linux-hardware.org/?probe=4957caa987) | May 31, 2021 |
| HP            | Compaq 6530b (NB005EA#AK... | Notebook    | [65fbd3def4](https://linux-hardware.org/?probe=65fbd3def4) | May 30, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [eae7be56e8](https://linux-hardware.org/?probe=eae7be56e8) | May 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ea164260eb](https://linux-hardware.org/?probe=ea164260eb) | May 30, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [49a6d8dec1](https://linux-hardware.org/?probe=49a6d8dec1) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e57c2fb16d](https://linux-hardware.org/?probe=e57c2fb16d) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [976e39384a](https://linux-hardware.org/?probe=976e39384a) | May 30, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [3b1546b203](https://linux-hardware.org/?probe=3b1546b203) | May 30, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [e79f44c522](https://linux-hardware.org/?probe=e79f44c522) | May 30, 2021 |
| HP            | 8054                        | Desktop     | [b0662fd84b](https://linux-hardware.org/?probe=b0662fd84b) | May 30, 2021 |
| Samsung       | 750XDA                      | Notebook    | [63a21f6d55](https://linux-hardware.org/?probe=63a21f6d55) | May 30, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [ed22adfd9f](https://linux-hardware.org/?probe=ed22adfd9f) | May 29, 2021 |
| ASRock        | A520M-ITX/ac                | Desktop     | [cef790f685](https://linux-hardware.org/?probe=cef790f685) | May 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [1697ac5b27](https://linux-hardware.org/?probe=1697ac5b27) | May 29, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | Notebook    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9fd8771a18](https://linux-hardware.org/?probe=9fd8771a18) | May 29, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [7fd687d091](https://linux-hardware.org/?probe=7fd687d091) | May 29, 2021 |
| Samsung       | 550XBE/350XBE               | Notebook    | [6d896a2155](https://linux-hardware.org/?probe=6d896a2155) | May 29, 2021 |
| Lenovo        | ThinkPad T460 20FMS2D600    | Notebook    | [18933265e1](https://linux-hardware.org/?probe=18933265e1) | May 29, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2cb43ec28b](https://linux-hardware.org/?probe=2cb43ec28b) | May 29, 2021 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [707a991f9c](https://linux-hardware.org/?probe=707a991f9c) | May 29, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [07aa6c505d](https://linux-hardware.org/?probe=07aa6c505d) | May 29, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [86d09890e7](https://linux-hardware.org/?probe=86d09890e7) | May 29, 2021 |
| Dell          | System XPS L502X            | Notebook    | [2d234eb9fb](https://linux-hardware.org/?probe=2d234eb9fb) | May 29, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c45342870c](https://linux-hardware.org/?probe=c45342870c) | May 28, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [fc1870a101](https://linux-hardware.org/?probe=fc1870a101) | May 28, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [75f763a124](https://linux-hardware.org/?probe=75f763a124) | May 28, 2021 |
| Gigabyte      | 970-GAMING                  | Desktop     | [d721904b6e](https://linux-hardware.org/?probe=d721904b6e) | May 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1dbb8065d8](https://linux-hardware.org/?probe=1dbb8065d8) | May 28, 2021 |
| ASUSTek       | K501UQ                      | Notebook    | [ea9385ec68](https://linux-hardware.org/?probe=ea9385ec68) | May 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Gigabyte      | AX370-Gaming K3             | Desktop     | [3ca0951964](https://linux-hardware.org/?probe=3ca0951964) | May 27, 2021 |
| Lenovo        | ThinkPad L390 20NR0013SP    | Notebook    | [b45633d7f6](https://linux-hardware.org/?probe=b45633d7f6) | May 27, 2021 |
| ONE-NETBOO... | One-Mix3 Pro                | Notebook    | [02f641ea60](https://linux-hardware.org/?probe=02f641ea60) | May 27, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [9372d60118](https://linux-hardware.org/?probe=9372d60118) | May 27, 2021 |
| HP            | 8054                        | Desktop     | [37f65c4171](https://linux-hardware.org/?probe=37f65c4171) | May 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [9054d4ebeb](https://linux-hardware.org/?probe=9054d4ebeb) | May 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [1f12426f2f](https://linux-hardware.org/?probe=1f12426f2f) | May 26, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [af06884158](https://linux-hardware.org/?probe=af06884158) | May 26, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [e0982e1f66](https://linux-hardware.org/?probe=e0982e1f66) | May 26, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [b34a66fe8d](https://linux-hardware.org/?probe=b34a66fe8d) | May 26, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [1e28737c91](https://linux-hardware.org/?probe=1e28737c91) | May 26, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [e866dfbe2d](https://linux-hardware.org/?probe=e866dfbe2d) | May 26, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [dfc512f53c](https://linux-hardware.org/?probe=dfc512f53c) | May 26, 2021 |
| Multilaser    | PC301                       | Notebook    | [041c47a5f0](https://linux-hardware.org/?probe=041c47a5f0) | May 25, 2021 |
| Acer          | AOD255E                     | Notebook    | [ff209e1d5d](https://linux-hardware.org/?probe=ff209e1d5d) | May 25, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [466576f64f](https://linux-hardware.org/?probe=466576f64f) | May 25, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [821afb2d5f](https://linux-hardware.org/?probe=821afb2d5f) | May 25, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [59f94e4db6](https://linux-hardware.org/?probe=59f94e4db6) | May 25, 2021 |
| ASUSTek       | K53Z                        | Notebook    | [2dd5a159d0](https://linux-hardware.org/?probe=2dd5a159d0) | May 25, 2021 |
| Lenovo        | V310-14ISK 80UF0004BR       | Notebook    | [834dfabed8](https://linux-hardware.org/?probe=834dfabed8) | May 25, 2021 |
| Lenovo        | V310-14ISK 80UF0004BR       | Notebook    | [ce7b65f353](https://linux-hardware.org/?probe=ce7b65f353) | May 25, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [23fbf90204](https://linux-hardware.org/?probe=23fbf90204) | May 25, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [0e0a4691f5](https://linux-hardware.org/?probe=0e0a4691f5) | May 25, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [c5a9132daa](https://linux-hardware.org/?probe=c5a9132daa) | May 25, 2021 |
| Multilaser    | PC301                       | Notebook    | [84be1288f4](https://linux-hardware.org/?probe=84be1288f4) | May 25, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [9f332f4fec](https://linux-hardware.org/?probe=9f332f4fec) | May 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [b2b10d4380](https://linux-hardware.org/?probe=b2b10d4380) | May 25, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [ea8b53c3dc](https://linux-hardware.org/?probe=ea8b53c3dc) | May 24, 2021 |
| Dell          | Latitude E6400              | Notebook    | [128169dd93](https://linux-hardware.org/?probe=128169dd93) | May 24, 2021 |
| Dell          | Latitude E6400              | Notebook    | [2d31bca830](https://linux-hardware.org/?probe=2d31bca830) | May 24, 2021 |
| ASUSTek       | P8P67 WS REVOLUTION         | Desktop     | [910ce6a9d9](https://linux-hardware.org/?probe=910ce6a9d9) | May 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8c072ea1c4](https://linux-hardware.org/?probe=8c072ea1c4) | May 24, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3f2aa0eb97](https://linux-hardware.org/?probe=3f2aa0eb97) | May 24, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [7b080b315d](https://linux-hardware.org/?probe=7b080b315d) | May 24, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [66c4430cc9](https://linux-hardware.org/?probe=66c4430cc9) | May 24, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [007d661b1c](https://linux-hardware.org/?probe=007d661b1c) | May 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [c5ca0c36a0](https://linux-hardware.org/?probe=c5ca0c36a0) | May 24, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [43d63daff7](https://linux-hardware.org/?probe=43d63daff7) | May 24, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [6d8c26fb00](https://linux-hardware.org/?probe=6d8c26fb00) | May 23, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [cb2e47587e](https://linux-hardware.org/?probe=cb2e47587e) | May 23, 2021 |
| Dell          | Latitude 5480               | Notebook    | [c0b53e96ba](https://linux-hardware.org/?probe=c0b53e96ba) | May 22, 2021 |
| Dell          | Latitude 5480               | Notebook    | [d55095b7a4](https://linux-hardware.org/?probe=d55095b7a4) | May 22, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [b249a9a615](https://linux-hardware.org/?probe=b249a9a615) | May 22, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [710c08259c](https://linux-hardware.org/?probe=710c08259c) | May 22, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [f6fcdde3e1](https://linux-hardware.org/?probe=f6fcdde3e1) | May 22, 2021 |
| Lenovo        | ThinkPad T520 42406EG       | Notebook    | [c40baa791f](https://linux-hardware.org/?probe=c40baa791f) | May 22, 2021 |
| HP            | ENVY 15                     | Notebook    | [286d5773a8](https://linux-hardware.org/?probe=286d5773a8) | May 22, 2021 |
| HP            | ProBook 6550b               | Notebook    | [7dbe5cc999](https://linux-hardware.org/?probe=7dbe5cc999) | May 22, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [0d671acb94](https://linux-hardware.org/?probe=0d671acb94) | May 22, 2021 |
| Multilaser    | PC301                       | Notebook    | [c68bb3678d](https://linux-hardware.org/?probe=c68bb3678d) | May 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [5756ecab4b](https://linux-hardware.org/?probe=5756ecab4b) | May 22, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [95410aef6a](https://linux-hardware.org/?probe=95410aef6a) | May 21, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [5f7f61234f](https://linux-hardware.org/?probe=5f7f61234f) | May 21, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [83a315e28f](https://linux-hardware.org/?probe=83a315e28f) | May 21, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [c9e7ae41ba](https://linux-hardware.org/?probe=c9e7ae41ba) | May 21, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [15fa523874](https://linux-hardware.org/?probe=15fa523874) | May 21, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [92d97521bc](https://linux-hardware.org/?probe=92d97521bc) | May 21, 2021 |
| Lenovo        | ThinkPad T60 2007VW1        | Notebook    | [4918b498c1](https://linux-hardware.org/?probe=4918b498c1) | May 21, 2021 |
| Dell          | Latitude E6430              | Notebook    | [b489ee68c9](https://linux-hardware.org/?probe=b489ee68c9) | May 21, 2021 |
| HP            | 82F2                        | Desktop     | [4efc31781e](https://linux-hardware.org/?probe=4efc31781e) | May 21, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d6371109b2](https://linux-hardware.org/?probe=d6371109b2) | May 21, 2021 |
| ASUSTek       | K53SM                       | Notebook    | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| Toshiba       | Satellite C50D-B            | Notebook    | [7ae2644ef1](https://linux-hardware.org/?probe=7ae2644ef1) | May 20, 2021 |
| Toshiba       | Satellite C50D-B            | Notebook    | [599106595e](https://linux-hardware.org/?probe=599106595e) | May 20, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [7799e3d32a](https://linux-hardware.org/?probe=7799e3d32a) | May 20, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [76598a468f](https://linux-hardware.org/?probe=76598a468f) | May 20, 2021 |
| Unknown       | Board                       | Desktop     | [1713150242](https://linux-hardware.org/?probe=1713150242) | May 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [28e93c07f9](https://linux-hardware.org/?probe=28e93c07f9) | May 20, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e18d5bc827](https://linux-hardware.org/?probe=e18d5bc827) | May 20, 2021 |
| Colorful T... | BATTLE-AX B450M-HD V14      | Desktop     | [a9ea33d1f6](https://linux-hardware.org/?probe=a9ea33d1f6) | May 20, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [33883a2571](https://linux-hardware.org/?probe=33883a2571) | May 20, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [d98e02f5b1](https://linux-hardware.org/?probe=d98e02f5b1) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [895d614ba3](https://linux-hardware.org/?probe=895d614ba3) | May 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b47c4ef32e](https://linux-hardware.org/?probe=b47c4ef32e) | May 19, 2021 |
| MSI           | PS42 8RB                    | Notebook    | [453b4a46dc](https://linux-hardware.org/?probe=453b4a46dc) | May 19, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [ba8d4405be](https://linux-hardware.org/?probe=ba8d4405be) | May 19, 2021 |
| Multilaser    | PC301                       | Notebook    | [bfdfb54a4a](https://linux-hardware.org/?probe=bfdfb54a4a) | May 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0c53f18728](https://linux-hardware.org/?probe=0c53f18728) | May 19, 2021 |
| Lenovo        | ThinkPad X250 20CLS1V210    | Notebook    | [3731af09ec](https://linux-hardware.org/?probe=3731af09ec) | May 19, 2021 |
| HP            | 1589                        | Desktop     | [2f621a1ba2](https://linux-hardware.org/?probe=2f621a1ba2) | May 19, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cd11019de2](https://linux-hardware.org/?probe=cd11019de2) | May 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [e01e5a5f59](https://linux-hardware.org/?probe=e01e5a5f59) | May 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [5e30bc589e](https://linux-hardware.org/?probe=5e30bc589e) | May 19, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1fd1fbe647](https://linux-hardware.org/?probe=1fd1fbe647) | May 19, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [122ed0bba8](https://linux-hardware.org/?probe=122ed0bba8) | May 19, 2021 |
| Lenovo        | ThinkPad L390 20NR0013SP    | Notebook    | [8890f7793c](https://linux-hardware.org/?probe=8890f7793c) | May 19, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [9ec7a6436d](https://linux-hardware.org/?probe=9ec7a6436d) | May 19, 2021 |
| Lenovo        | ThinkPad T460 20FN003NUK    | Notebook    | [a07e4b12f8](https://linux-hardware.org/?probe=a07e4b12f8) | May 19, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [e2d82a3a62](https://linux-hardware.org/?probe=e2d82a3a62) | May 19, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | Desktop     | [236a9a94b1](https://linux-hardware.org/?probe=236a9a94b1) | May 19, 2021 |
| ASUSTek       | K54C                        | Notebook    | [4ebc51e5a7](https://linux-hardware.org/?probe=4ebc51e5a7) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [901f37d11b](https://linux-hardware.org/?probe=901f37d11b) | May 19, 2021 |
| ASUSTek       | X550VX                      | Notebook    | [6b634edf3a](https://linux-hardware.org/?probe=6b634edf3a) | May 19, 2021 |
| Gigabyte      | P55A-UD4                    | Desktop     | [e50e39f36f](https://linux-hardware.org/?probe=e50e39f36f) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [39f2002b6b](https://linux-hardware.org/?probe=39f2002b6b) | May 19, 2021 |
| Medion        | S15450                      | Notebook    | [4d709dc08c](https://linux-hardware.org/?probe=4d709dc08c) | May 19, 2021 |
| ASRock        | H61M-ITX                    | Desktop     | [e235be30d5](https://linux-hardware.org/?probe=e235be30d5) | May 19, 2021 |
| ASRock        | H61M-ITX                    | Desktop     | [216be38323](https://linux-hardware.org/?probe=216be38323) | May 19, 2021 |
| Sony          | VPCYB35AB                   | Notebook    | [2b76ee0822](https://linux-hardware.org/?probe=2b76ee0822) | May 18, 2021 |
| HP            | EliteBook x360 1040 G5      | Convertible | [ef7445eb15](https://linux-hardware.org/?probe=ef7445eb15) | May 18, 2021 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cd49abe808](https://linux-hardware.org/?probe=cd49abe808) | May 18, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [384729bee7](https://linux-hardware.org/?probe=384729bee7) | May 18, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d090eaf727](https://linux-hardware.org/?probe=d090eaf727) | May 18, 2021 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ebf7c07ab3](https://linux-hardware.org/?probe=ebf7c07ab3) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [332c7b4313](https://linux-hardware.org/?probe=332c7b4313) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [32546ecaa0](https://linux-hardware.org/?probe=32546ecaa0) | May 17, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [1b6ff89b42](https://linux-hardware.org/?probe=1b6ff89b42) | May 17, 2021 |
| Dell          | 0N867P A02                  | Desktop     | [8ef532d4ec](https://linux-hardware.org/?probe=8ef532d4ec) | May 17, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [bd63b276ce](https://linux-hardware.org/?probe=bd63b276ce) | May 17, 2021 |
| Multilaser    | PC301                       | Notebook    | [b7adb90c84](https://linux-hardware.org/?probe=b7adb90c84) | May 17, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [d0f7cef5fe](https://linux-hardware.org/?probe=d0f7cef5fe) | May 16, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [e1f7cfefe3](https://linux-hardware.org/?probe=e1f7cfefe3) | May 16, 2021 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [e44093c222](https://linux-hardware.org/?probe=e44093c222) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e74c6f6436](https://linux-hardware.org/?probe=e74c6f6436) | May 16, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [c9e0f74234](https://linux-hardware.org/?probe=c9e0f74234) | May 16, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [6f51becb58](https://linux-hardware.org/?probe=6f51becb58) | May 16, 2021 |
| HP            | 87C3                        | Desktop     | [6ef8441fda](https://linux-hardware.org/?probe=6ef8441fda) | May 16, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [86286fad9c](https://linux-hardware.org/?probe=86286fad9c) | May 16, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [157e1f057d](https://linux-hardware.org/?probe=157e1f057d) | May 16, 2021 |
| Medion        | S15450                      | Notebook    | [7973a20895](https://linux-hardware.org/?probe=7973a20895) | May 15, 2021 |
| Timi          | TM1703                      | Notebook    | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [aba051d387](https://linux-hardware.org/?probe=aba051d387) | May 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10dd12b38c](https://linux-hardware.org/?probe=10dd12b38c) | May 15, 2021 |
| MSI           | A68HM GRENADE               | Desktop     | [a2ab595336](https://linux-hardware.org/?probe=a2ab595336) | May 14, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2e19a058f9](https://linux-hardware.org/?probe=2e19a058f9) | May 14, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [54dd671b29](https://linux-hardware.org/?probe=54dd671b29) | May 14, 2021 |
| Multilaser    | PC301                       | Notebook    | [8a77e5f988](https://linux-hardware.org/?probe=8a77e5f988) | May 14, 2021 |
| Dell          | G3 3779                     | Notebook    | [b6bc261100](https://linux-hardware.org/?probe=b6bc261100) | May 14, 2021 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [0f6653a472](https://linux-hardware.org/?probe=0f6653a472) | May 14, 2021 |
| MSI           | H97 PC Mate                 | Desktop     | [14457815f8](https://linux-hardware.org/?probe=14457815f8) | May 13, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [4ad5bc744a](https://linux-hardware.org/?probe=4ad5bc744a) | May 13, 2021 |
| HP            | ProBook 6550b               | Notebook    | [47bcdf1bc3](https://linux-hardware.org/?probe=47bcdf1bc3) | May 13, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [7195f02080](https://linux-hardware.org/?probe=7195f02080) | May 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ccda5444d9](https://linux-hardware.org/?probe=ccda5444d9) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [36ade7dd15](https://linux-hardware.org/?probe=36ade7dd15) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [06c1bbc65e](https://linux-hardware.org/?probe=06c1bbc65e) | May 13, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1ed3419726](https://linux-hardware.org/?probe=1ed3419726) | May 13, 2021 |
| Multilaser    | PC301                       | Notebook    | [9d6cce1dd7](https://linux-hardware.org/?probe=9d6cce1dd7) | May 13, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [39f25072f9](https://linux-hardware.org/?probe=39f25072f9) | May 13, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [8530bb15d7](https://linux-hardware.org/?probe=8530bb15d7) | May 12, 2021 |
| Dell          | 02K9CR A02                  | Desktop     | [6b03c7e506](https://linux-hardware.org/?probe=6b03c7e506) | May 12, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [dceb3210ff](https://linux-hardware.org/?probe=dceb3210ff) | May 12, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3eefcf4b58](https://linux-hardware.org/?probe=3eefcf4b58) | May 11, 2021 |
| AZW           | GK mini                     | Mini pc     | [5250cd21ef](https://linux-hardware.org/?probe=5250cd21ef) | May 11, 2021 |
| Sony          | VPCEH2D0E                   | Notebook    | [3c201a9337](https://linux-hardware.org/?probe=3c201a9337) | May 11, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [58581a5843](https://linux-hardware.org/?probe=58581a5843) | May 11, 2021 |
| Dell          | Latitude E7450              | Notebook    | [5f0ce579ec](https://linux-hardware.org/?probe=5f0ce579ec) | May 11, 2021 |
| Dell          | 0200DY A00                  | Desktop     | [38f2da4073](https://linux-hardware.org/?probe=38f2da4073) | May 11, 2021 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [6b8b61937f](https://linux-hardware.org/?probe=6b8b61937f) | May 10, 2021 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [6724960cf9](https://linux-hardware.org/?probe=6724960cf9) | May 10, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [d30533fffe](https://linux-hardware.org/?probe=d30533fffe) | May 10, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [176f12e2f9](https://linux-hardware.org/?probe=176f12e2f9) | May 10, 2021 |
| ASUSTek       | X705UDR                     | Notebook    | [172dc45c89](https://linux-hardware.org/?probe=172dc45c89) | May 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [55971412c7](https://linux-hardware.org/?probe=55971412c7) | May 10, 2021 |
| HP            | Laptop 17z-ca100            | Notebook    | [7623ef5f0e](https://linux-hardware.org/?probe=7623ef5f0e) | May 10, 2021 |
| ASUSTek       | K52Jr                       | Notebook    | [5484537afd](https://linux-hardware.org/?probe=5484537afd) | May 09, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c88308fb06](https://linux-hardware.org/?probe=c88308fb06) | May 09, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [d03bdbf1da](https://linux-hardware.org/?probe=d03bdbf1da) | May 09, 2021 |
| Google        | Edgar                       | Notebook    | [5757463a4d](https://linux-hardware.org/?probe=5757463a4d) | May 09, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [45f902869d](https://linux-hardware.org/?probe=45f902869d) | May 09, 2021 |
| Medion        | S15450                      | Notebook    | [c63ba2a1c0](https://linux-hardware.org/?probe=c63ba2a1c0) | May 08, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [5372b6674e](https://linux-hardware.org/?probe=5372b6674e) | May 08, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| HP            | Pavilion dv7                | Notebook    | [727672085e](https://linux-hardware.org/?probe=727672085e) | May 08, 2021 |
| Dell          | Latitude E7240              | Notebook    | [f1b2530633](https://linux-hardware.org/?probe=f1b2530633) | May 08, 2021 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [b9c914324d](https://linux-hardware.org/?probe=b9c914324d) | May 07, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [d3b1df1e3a](https://linux-hardware.org/?probe=d3b1df1e3a) | May 07, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [ccaf1e5387](https://linux-hardware.org/?probe=ccaf1e5387) | May 07, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | Notebook    | [e2c28f7c2d](https://linux-hardware.org/?probe=e2c28f7c2d) | May 07, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [89628bc0a5](https://linux-hardware.org/?probe=89628bc0a5) | May 07, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Dell          | 0200DY A00                  | Desktop     | [fdf817c5f5](https://linux-hardware.org/?probe=fdf817c5f5) | May 07, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5927d6bfa2](https://linux-hardware.org/?probe=5927d6bfa2) | May 06, 2021 |
| Multilaser    | PC301                       | Notebook    | [2bbc116611](https://linux-hardware.org/?probe=2bbc116611) | May 06, 2021 |
| HP            | ENVY 15                     | Notebook    | [16d03ed296](https://linux-hardware.org/?probe=16d03ed296) | May 06, 2021 |
| Multilaser    | PC301                       | Notebook    | [e8c1f6996f](https://linux-hardware.org/?probe=e8c1f6996f) | May 06, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [31dd47cfcb](https://linux-hardware.org/?probe=31dd47cfcb) | May 06, 2021 |
| HP            | 82F2                        | Desktop     | [94c637deae](https://linux-hardware.org/?probe=94c637deae) | May 06, 2021 |
| Toshiba       | SATEGO P100                 | Notebook    | [5b05669f7f](https://linux-hardware.org/?probe=5b05669f7f) | May 06, 2021 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [53fe7a4a32](https://linux-hardware.org/?probe=53fe7a4a32) | May 06, 2021 |
| ASUSTek       | ZenBook UX393EA_UX393EA     | Notebook    | [da6991dcc3](https://linux-hardware.org/?probe=da6991dcc3) | May 06, 2021 |
| Dell          | Precision 5530              | Notebook    | [ec979f10db](https://linux-hardware.org/?probe=ec979f10db) | May 06, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c8f8650f7f](https://linux-hardware.org/?probe=c8f8650f7f) | May 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [ca992302b8](https://linux-hardware.org/?probe=ca992302b8) | May 06, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [c31eb4d212](https://linux-hardware.org/?probe=c31eb4d212) | May 05, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [bf89b64c2b](https://linux-hardware.org/?probe=bf89b64c2b) | May 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [47978d7f33](https://linux-hardware.org/?probe=47978d7f33) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | Desktop     | [2e99e6785b](https://linux-hardware.org/?probe=2e99e6785b) | May 05, 2021 |
| Lenovo        | ThinkPad T61 766512G        | Notebook    | [8f0e1224e3](https://linux-hardware.org/?probe=8f0e1224e3) | May 05, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| HP            | 15                          | Notebook    | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| Dell          | 0T0MHW A03                  | Desktop     | [d5a07eb379](https://linux-hardware.org/?probe=d5a07eb379) | May 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3c5ffb0a02](https://linux-hardware.org/?probe=3c5ffb0a02) | May 04, 2021 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [4aac1d085d](https://linux-hardware.org/?probe=4aac1d085d) | May 04, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [b11a2922f2](https://linux-hardware.org/?probe=b11a2922f2) | May 04, 2021 |
| HP            | Notebook                    | Notebook    | [342db0e97a](https://linux-hardware.org/?probe=342db0e97a) | May 03, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | Notebook                    | Notebook    | [419a488779](https://linux-hardware.org/?probe=419a488779) | May 03, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | Notebook    | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [2c20bea856](https://linux-hardware.org/?probe=2c20bea856) | May 03, 2021 |
| MSI           | GE76 Raider 10UE            | Notebook    | [3d5116ec46](https://linux-hardware.org/?probe=3d5116ec46) | May 02, 2021 |
| Toshiba       | Satellite L510              | Notebook    | [01753d1f93](https://linux-hardware.org/?probe=01753d1f93) | May 02, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [522b9403fb](https://linux-hardware.org/?probe=522b9403fb) | May 02, 2021 |
| MSI           | GE76 Raider 10UE            | Notebook    | [382904ecd6](https://linux-hardware.org/?probe=382904ecd6) | May 02, 2021 |
| ASUSTek       | N56VB                       | Notebook    | [aac6964149](https://linux-hardware.org/?probe=aac6964149) | May 02, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [b319f99046](https://linux-hardware.org/?probe=b319f99046) | May 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [f89317f54a](https://linux-hardware.org/?probe=f89317f54a) | May 02, 2021 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [30b02cf768](https://linux-hardware.org/?probe=30b02cf768) | May 02, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [573b65efbd](https://linux-hardware.org/?probe=573b65efbd) | May 02, 2021 |
| Medion        | P2211T                      | Tablet      | [bd366e047f](https://linux-hardware.org/?probe=bd366e047f) | May 02, 2021 |
| Dell          | Precision 5530              | Notebook    | [0fe92c8a70](https://linux-hardware.org/?probe=0fe92c8a70) | May 02, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [d1bde8c0f4](https://linux-hardware.org/?probe=d1bde8c0f4) | May 02, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [e6efc8f997](https://linux-hardware.org/?probe=e6efc8f997) | May 02, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [4f8f955faf](https://linux-hardware.org/?probe=4f8f955faf) | May 02, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [60ed580134](https://linux-hardware.org/?probe=60ed580134) | May 01, 2021 |
| HP            | 3048h                       | Desktop     | [74f738bae1](https://linux-hardware.org/?probe=74f738bae1) | May 01, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [09afa10520](https://linux-hardware.org/?probe=09afa10520) | May 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5896a72e6f](https://linux-hardware.org/?probe=5896a72e6f) | May 01, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [092736d168](https://linux-hardware.org/?probe=092736d168) | May 01, 2021 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [9021bab8e3](https://linux-hardware.org/?probe=9021bab8e3) | May 01, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [3d6450f98b](https://linux-hardware.org/?probe=3d6450f98b) | May 01, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [84496aeea1](https://linux-hardware.org/?probe=84496aeea1) | May 01, 2021 |
| Dell          | G7 7700                     | Notebook    | [05da8e61d2](https://linux-hardware.org/?probe=05da8e61d2) | May 01, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [6d514e1b5f](https://linux-hardware.org/?probe=6d514e1b5f) | May 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [e9ef8cb837](https://linux-hardware.org/?probe=e9ef8cb837) | May 01, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [c2441cb2d5](https://linux-hardware.org/?probe=c2441cb2d5) | Apr 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [85bfb2950b](https://linux-hardware.org/?probe=85bfb2950b) | Apr 30, 2021 |
| Gigabyte      | M2432                       | Notebook    | [354e017032](https://linux-hardware.org/?probe=354e017032) | Apr 30, 2021 |
| Gigabyte      | M2432                       | Notebook    | [59243622d0](https://linux-hardware.org/?probe=59243622d0) | Apr 30, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [cee847c753](https://linux-hardware.org/?probe=cee847c753) | Apr 30, 2021 |
| HP            | 844C                        | Desktop     | [913d5aff80](https://linux-hardware.org/?probe=913d5aff80) | Apr 30, 2021 |
| Dell          | 097YXY A00                  | Desktop     | [121ea94e76](https://linux-hardware.org/?probe=121ea94e76) | Apr 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [cc6bef7fe5](https://linux-hardware.org/?probe=cc6bef7fe5) | Apr 30, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [799ad15d8b](https://linux-hardware.org/?probe=799ad15d8b) | Apr 30, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [b2cc5a01b1](https://linux-hardware.org/?probe=b2cc5a01b1) | Apr 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [fcc7840d63](https://linux-hardware.org/?probe=fcc7840d63) | Apr 29, 2021 |
| ASUSTek       | P8P67 WS REVOLUTION         | Desktop     | [64d0eef5ff](https://linux-hardware.org/?probe=64d0eef5ff) | Apr 29, 2021 |
| Lenovo        | ThinkPad T540p 20BE003AU... | Notebook    | [5d86d2bd4a](https://linux-hardware.org/?probe=5d86d2bd4a) | Apr 29, 2021 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [61235db641](https://linux-hardware.org/?probe=61235db641) | Apr 29, 2021 |
| Maibenben     | S431                        | Notebook    | [a4db49a83f](https://linux-hardware.org/?probe=a4db49a83f) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [1abfb429b9](https://linux-hardware.org/?probe=1abfb429b9) | Apr 28, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [34b2d651e1](https://linux-hardware.org/?probe=34b2d651e1) | Apr 28, 2021 |
| Pegatron      | IPMSB-H61A                  | Desktop     | [393da2834d](https://linux-hardware.org/?probe=393da2834d) | Apr 28, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [2388eeb59b](https://linux-hardware.org/?probe=2388eeb59b) | Apr 28, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d4a67740c8](https://linux-hardware.org/?probe=d4a67740c8) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [cbbdd343bd](https://linux-hardware.org/?probe=cbbdd343bd) | Apr 28, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [79865c9dbb](https://linux-hardware.org/?probe=79865c9dbb) | Apr 28, 2021 |
| Lenovo        | ThinkPad T540p 20BE003AU... | Notebook    | [e45e5a44cb](https://linux-hardware.org/?probe=e45e5a44cb) | Apr 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [3aa335d3bb](https://linux-hardware.org/?probe=3aa335d3bb) | Apr 28, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [220e290fcb](https://linux-hardware.org/?probe=220e290fcb) | Apr 28, 2021 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [cbcd008426](https://linux-hardware.org/?probe=cbcd008426) | Apr 28, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [6d5f7aacc2](https://linux-hardware.org/?probe=6d5f7aacc2) | Apr 28, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2a863a4322](https://linux-hardware.org/?probe=2a863a4322) | Apr 27, 2021 |
| Multilaser    | PC132                       | Notebook    | [f3844ad90d](https://linux-hardware.org/?probe=f3844ad90d) | Apr 27, 2021 |
| Medion        | S15450                      | Notebook    | [a0dfd77d31](https://linux-hardware.org/?probe=a0dfd77d31) | Apr 27, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [489e368d37](https://linux-hardware.org/?probe=489e368d37) | Apr 27, 2021 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [3a4d940472](https://linux-hardware.org/?probe=3a4d940472) | Apr 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [92c9fc9c46](https://linux-hardware.org/?probe=92c9fc9c46) | Apr 27, 2021 |
| Sony          | VPCYB35AB                   | Notebook    | [cdaa0ecd8d](https://linux-hardware.org/?probe=cdaa0ecd8d) | Apr 27, 2021 |
| Sony          | VPCYB35AB                   | Notebook    | [727ae4ccc1](https://linux-hardware.org/?probe=727ae4ccc1) | Apr 27, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [38805fbcb8](https://linux-hardware.org/?probe=38805fbcb8) | Apr 26, 2021 |
| Standard      | SF20BA2                     | Notebook    | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [e471fd0bf4](https://linux-hardware.org/?probe=e471fd0bf4) | Apr 26, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [40e07b4dad](https://linux-hardware.org/?probe=40e07b4dad) | Apr 26, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [a3a8c3f6d6](https://linux-hardware.org/?probe=a3a8c3f6d6) | Apr 26, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [9b73c538df](https://linux-hardware.org/?probe=9b73c538df) | Apr 26, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e660235017](https://linux-hardware.org/?probe=e660235017) | Apr 26, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [36b99221bf](https://linux-hardware.org/?probe=36b99221bf) | Apr 26, 2021 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [7fc828532c](https://linux-hardware.org/?probe=7fc828532c) | Apr 26, 2021 |
| ASRock        | B560 Pro4                   | Desktop     | [ddd384c6cb](https://linux-hardware.org/?probe=ddd384c6cb) | Apr 26, 2021 |
| ASUSTek       | M4N78 PRO                   | Desktop     | [dbead6c4f6](https://linux-hardware.org/?probe=dbead6c4f6) | Apr 26, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [aa1913f348](https://linux-hardware.org/?probe=aa1913f348) | Apr 25, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [088ae8b87b](https://linux-hardware.org/?probe=088ae8b87b) | Apr 25, 2021 |
| Lenovo        | ThinkPad X230 232502S       | Notebook    | [0ee18bf1ae](https://linux-hardware.org/?probe=0ee18bf1ae) | Apr 25, 2021 |
| ASUSTek       | A88XM-E                     | Desktop     | [10eeeb8da1](https://linux-hardware.org/?probe=10eeeb8da1) | Apr 24, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [0059812cf8](https://linux-hardware.org/?probe=0059812cf8) | Apr 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [a18b247e3d](https://linux-hardware.org/?probe=a18b247e3d) | Apr 24, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [93eb4a6a39](https://linux-hardware.org/?probe=93eb4a6a39) | Apr 24, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [43bc2ef593](https://linux-hardware.org/?probe=43bc2ef593) | Apr 23, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [3b9a379994](https://linux-hardware.org/?probe=3b9a379994) | Apr 23, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [befb86f02f](https://linux-hardware.org/?probe=befb86f02f) | Apr 23, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [6db79f659d](https://linux-hardware.org/?probe=6db79f659d) | Apr 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS02000    | Notebook    | [c2afb61dd0](https://linux-hardware.org/?probe=c2afb61dd0) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | Notebook    | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [9d1694385f](https://linux-hardware.org/?probe=9d1694385f) | Apr 22, 2021 |
| Google        | Samus                       | Notebook    | [8962398d10](https://linux-hardware.org/?probe=8962398d10) | Apr 22, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [47a7c2b6f3](https://linux-hardware.org/?probe=47a7c2b6f3) | Apr 22, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [cf7ab2ca73](https://linux-hardware.org/?probe=cf7ab2ca73) | Apr 22, 2021 |
| MSI           | CX61 2PC                    | Notebook    | [5430109f6d](https://linux-hardware.org/?probe=5430109f6d) | Apr 22, 2021 |
| Lenovo        | ThinkPad T420s 4173A57      | Notebook    | [01060ed632](https://linux-hardware.org/?probe=01060ed632) | Apr 22, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [3d4e2aaf41](https://linux-hardware.org/?probe=3d4e2aaf41) | Apr 22, 2021 |
| HP            | ProBook 430 G2              | Notebook    | [03a0b4cf9d](https://linux-hardware.org/?probe=03a0b4cf9d) | Apr 22, 2021 |
| HP            | ProBook 430 G2              | Notebook    | [9f9065affa](https://linux-hardware.org/?probe=9f9065affa) | Apr 22, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [51fd34a847](https://linux-hardware.org/?probe=51fd34a847) | Apr 22, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f99e16bf71](https://linux-hardware.org/?probe=f99e16bf71) | Apr 22, 2021 |
| HP            | 3047h                       | Desktop     | [a99069fd7d](https://linux-hardware.org/?probe=a99069fd7d) | Apr 21, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [f4ffa2fa57](https://linux-hardware.org/?probe=f4ffa2fa57) | Apr 21, 2021 |
| Dell          | 0N867P A02                  | Desktop     | [cb4f6f1826](https://linux-hardware.org/?probe=cb4f6f1826) | Apr 21, 2021 |
| Dell          | 0N867P A02                  | Desktop     | [d5948761c4](https://linux-hardware.org/?probe=d5948761c4) | Apr 21, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [39b121f107](https://linux-hardware.org/?probe=39b121f107) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [ca62d8f11b](https://linux-hardware.org/?probe=ca62d8f11b) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f71c55764e](https://linux-hardware.org/?probe=f71c55764e) | Apr 21, 2021 |
| MSI           | CX61 2PC                    | Notebook    | [a109904ae8](https://linux-hardware.org/?probe=a109904ae8) | Apr 21, 2021 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [d8777edc9a](https://linux-hardware.org/?probe=d8777edc9a) | Apr 21, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [5d8af2080d](https://linux-hardware.org/?probe=5d8af2080d) | Apr 21, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [a8fe0bb3fe](https://linux-hardware.org/?probe=a8fe0bb3fe) | Apr 21, 2021 |
| MSI           | GL65 Leopard 9SCXR          | Notebook    | [795030a489](https://linux-hardware.org/?probe=795030a489) | Apr 21, 2021 |
| Intel Clie... | LAPQC71B                    | Notebook    | [0ddadcba51](https://linux-hardware.org/?probe=0ddadcba51) | Apr 20, 2021 |
| Lenovo        | Legion 5 82B5               | Notebook    | [da2135f7c0](https://linux-hardware.org/?probe=da2135f7c0) | Apr 20, 2021 |
| Jumper        | EZpad6                      | Notebook    | [fc951e523c](https://linux-hardware.org/?probe=fc951e523c) | Apr 20, 2021 |
| Gigabyte      | 990FXA-UD7                  | Desktop     | [f4365c697b](https://linux-hardware.org/?probe=f4365c697b) | Apr 20, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3feeb55814](https://linux-hardware.org/?probe=3feeb55814) | Apr 20, 2021 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [ae668f7b16](https://linux-hardware.org/?probe=ae668f7b16) | Apr 20, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [a9f5686a69](https://linux-hardware.org/?probe=a9f5686a69) | Apr 19, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7f599e2b8c](https://linux-hardware.org/?probe=7f599e2b8c) | Apr 19, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [8d867729f0](https://linux-hardware.org/?probe=8d867729f0) | Apr 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [2352caa9cf](https://linux-hardware.org/?probe=2352caa9cf) | Apr 19, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | Notebook    | [d7fed90840](https://linux-hardware.org/?probe=d7fed90840) | Apr 19, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [0ebfeb7dc6](https://linux-hardware.org/?probe=0ebfeb7dc6) | Apr 19, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [f0abad1174](https://linux-hardware.org/?probe=f0abad1174) | Apr 18, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [c5f58b3a82](https://linux-hardware.org/?probe=c5f58b3a82) | Apr 18, 2021 |
| Lenovo        | ThinkPad T540p 20BE003AU... | Notebook    | [cbc2a9d820](https://linux-hardware.org/?probe=cbc2a9d820) | Apr 18, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [16759fcbfa](https://linux-hardware.org/?probe=16759fcbfa) | Apr 18, 2021 |
| Biostar       | A58MD                       | Desktop     | [3effc9a4ed](https://linux-hardware.org/?probe=3effc9a4ed) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [00c8d54652](https://linux-hardware.org/?probe=00c8d54652) | Apr 18, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [4b3e231307](https://linux-hardware.org/?probe=4b3e231307) | Apr 18, 2021 |
| ASUSTek       | X550VX                      | Notebook    | [030fd49808](https://linux-hardware.org/?probe=030fd49808) | Apr 17, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| Lenovo        | ThinkPad T540p 20BE003AU... | Notebook    | [61b12483e7](https://linux-hardware.org/?probe=61b12483e7) | Apr 17, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d34b8dac02](https://linux-hardware.org/?probe=d34b8dac02) | Apr 17, 2021 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [1473c30db9](https://linux-hardware.org/?probe=1473c30db9) | Apr 17, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [47d0215e94](https://linux-hardware.org/?probe=47d0215e94) | Apr 17, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [9b49622881](https://linux-hardware.org/?probe=9b49622881) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [e1efa9fc86](https://linux-hardware.org/?probe=e1efa9fc86) | Apr 17, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0389c5caad](https://linux-hardware.org/?probe=0389c5caad) | Apr 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [74e927acae](https://linux-hardware.org/?probe=74e927acae) | Apr 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5ea126f6da](https://linux-hardware.org/?probe=5ea126f6da) | Apr 16, 2021 |
| Acer          | Predator G3-572             | Notebook    | [a1de054bbb](https://linux-hardware.org/?probe=a1de054bbb) | Apr 16, 2021 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [a96e1ef344](https://linux-hardware.org/?probe=a96e1ef344) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [868df33c64](https://linux-hardware.org/?probe=868df33c64) | Apr 16, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [248c5ed293](https://linux-hardware.org/?probe=248c5ed293) | Apr 16, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [1698adec47](https://linux-hardware.org/?probe=1698adec47) | Apr 16, 2021 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [63b5731a5e](https://linux-hardware.org/?probe=63b5731a5e) | Apr 16, 2021 |
| Lenovo        | IdeaPad S940-14IWL 81R0     | Notebook    | [3128e2e0b9](https://linux-hardware.org/?probe=3128e2e0b9) | Apr 16, 2021 |
| Lenovo        | IdeaPad S940-14IWL 81R0     | Notebook    | [ee18a65cf2](https://linux-hardware.org/?probe=ee18a65cf2) | Apr 15, 2021 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [44e586277c](https://linux-hardware.org/?probe=44e586277c) | Apr 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [5b14c882ea](https://linux-hardware.org/?probe=5b14c882ea) | Apr 15, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [7ca0cd3696](https://linux-hardware.org/?probe=7ca0cd3696) | Apr 15, 2021 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | Notebook    | [cade005acb](https://linux-hardware.org/?probe=cade005acb) | Apr 15, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b87e295470](https://linux-hardware.org/?probe=b87e295470) | Apr 15, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [35daf1f455](https://linux-hardware.org/?probe=35daf1f455) | Apr 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7d989ef8e0](https://linux-hardware.org/?probe=7d989ef8e0) | Apr 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29b3051b39](https://linux-hardware.org/?probe=29b3051b39) | Apr 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d5239cd417](https://linux-hardware.org/?probe=d5239cd417) | Apr 14, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [fb2b83a817](https://linux-hardware.org/?probe=fb2b83a817) | Apr 14, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [02903c0426](https://linux-hardware.org/?probe=02903c0426) | Apr 14, 2021 |
| Google        | Falco                       | Notebook    | [595d810b0c](https://linux-hardware.org/?probe=595d810b0c) | Apr 14, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [a0d23769ed](https://linux-hardware.org/?probe=a0d23769ed) | Apr 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8e6097fc59](https://linux-hardware.org/?probe=8e6097fc59) | Apr 14, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ab16e4844b](https://linux-hardware.org/?probe=ab16e4844b) | Apr 14, 2021 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | Desktop     | [177bf1f346](https://linux-hardware.org/?probe=177bf1f346) | Apr 13, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [e0583d0fa4](https://linux-hardware.org/?probe=e0583d0fa4) | Apr 13, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [10edf1ccc5](https://linux-hardware.org/?probe=10edf1ccc5) | Apr 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [513ef9e574](https://linux-hardware.org/?probe=513ef9e574) | Apr 13, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [8e1aa2c9ab](https://linux-hardware.org/?probe=8e1aa2c9ab) | Apr 13, 2021 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [136e5d26e2](https://linux-hardware.org/?probe=136e5d26e2) | Apr 13, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [3f67213f5a](https://linux-hardware.org/?probe=3f67213f5a) | Apr 13, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [d4872b050f](https://linux-hardware.org/?probe=d4872b050f) | Apr 13, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [dd6f0b870d](https://linux-hardware.org/?probe=dd6f0b870d) | Apr 13, 2021 |
| Jumper        | EZbook                      | Notebook    | [9fea6dbc67](https://linux-hardware.org/?probe=9fea6dbc67) | Apr 13, 2021 |
| Medion        | P6815                       | Notebook    | [684ff8cd10](https://linux-hardware.org/?probe=684ff8cd10) | Apr 13, 2021 |
| Acer          | Aspire M5-582PT             | Notebook    | [8abc23484b](https://linux-hardware.org/?probe=8abc23484b) | Apr 13, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [8eeff8c77c](https://linux-hardware.org/?probe=8eeff8c77c) | Apr 13, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Manjaro                   | 1955      | 36.63%  |
| Manjaro 20.1              | 291       | 5.45%   |
| Manjaro 20.2.1            | 283       | 5.3%    |
| Manjaro 20.2              | 243       | 4.55%   |
| Manjaro 20.0.3            | 223       | 4.18%   |
| Manjaro 21.1.0            | 149       | 2.79%   |
| Manjaro 18.1.5            | 143       | 2.68%   |
| Manjaro 21.2.0            | 126       | 2.36%   |
| Manjaro 21.2.5            | 125       | 2.34%   |
| Manjaro 21.1.6            | 114       | 2.14%   |
| Manjaro 21.0.7            | 112       | 2.1%    |
| Manjaro 20.0              | 101       | 1.89%   |
| Manjaro 19.0.2            | 97        | 1.82%   |
| Manjaro 18.0.4            | 96        | 1.8%    |
| Manjaro 21.0              | 87        | 1.63%   |
| Manjaro 21.0.5            | 80        | 1.5%    |
| Manjaro 20.1.2            | 80        | 1.5%    |
| Manjaro 21.2.3            | 74        | 1.39%   |
| Manjaro 21.2.1            | 73        | 1.37%   |
| Manjaro 20.1.1            | 71        | 1.33%   |
| Manjaro 20.0.1            | 69        | 1.29%   |
| Manjaro 21.0.4            | 50        | 0.94%   |
| Manjaro 21.2.2            | 45        | 0.84%   |
| Manjaro 21.2.4            | 43        | 0.81%   |
| Manjaro 21.2.6            | 41        | 0.77%   |
| Manjaro 21.1.2            | 41        | 0.77%   |
| Manjaro 21.1.4            | 37        | 0.69%   |
| Manjaro 21.0.1            | 36        | 0.67%   |
| Manjaro 21.0.2            | 34        | 0.64%   |
| Manjaro 21.0.3            | 31        | 0.58%   |
| Manjaro 21.1.1            | 30        | 0.56%   |
| Manjaro 21.1.3            | 29        | 0.54%   |
| Manjaro 21.2rc            | 28        | 0.52%   |
| Manjaro 18.1.4            | 27        | 0.51%   |
| Manjaro 18.1.3            | 25        | 0.47%   |
| Manjaro 18.1.0            | 25        | 0.47%   |
| Manjaro 21.1.5            | 24        | 0.45%   |
| Manjaro 21.0.6            | 19        | 0.36%   |
| Manjaro 18.0.0-rc         | 19        | 0.36%   |
| Manjaro 18.0.0            | 16        | 0.3%    |
| Manjaro 17.1.12           | 15        | 0.28%   |
| Manjaro 20.0.2            | 14        | 0.26%   |
| Manjaro 19.0.1            | 13        | 0.24%   |
| Manjaro 18.1.2            | 12        | 0.22%   |
| Manjaro 19.0              | 11        | 0.21%   |
| Manjaro 18.1.1            | 10        | 0.19%   |
| Manjaro 18.0.2            | 9         | 0.17%   |
| Manjaro 21.2pre1          | 8         | 0.15%   |
| Manjaro 19.0.0            | 8         | 0.15%   |
| Manjaro 21.2rc1           | 5         | 0.09%   |
| Manjaro 18.0.3            | 5         | 0.09%   |
| Manjaro 18.0              | 4         | 0.07%   |
| Manjaro 17.1.11           | 3         | 0.06%   |
| Manjaro 21.2rc2           | 2         | 0.04%   |
| Manjaro 20.1-rc2          | 2         | 0.04%   |
| Manjaro 20.1-rc1          | 2         | 0.04%   |
| Manjaro 18.0.1            | 2         | 0.04%   |
| Manjaro 21.07-development | 1         | 0.02%   |
| Manjaro 20.2-rc3          | 1         | 0.02%   |
| Manjaro 20.2-rc1          | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 4927      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 293       | 5.06%   |
| 5.13.19-2-MANJARO | 174       | 3%      |
| 5.8.6-1-MANJARO   | 144       | 2.49%   |
| 5.9.11-3-MANJARO  | 130       | 2.24%   |
| 5.8.11-1-MANJARO  | 123       | 2.12%   |
| 5.15.28-1-MANJARO | 117       | 2.02%   |
| 5.8.18-1-MANJARO  | 103       | 1.78%   |
| 5.10.42-1-MANJARO | 101       | 1.74%   |
| 5.15.12-1-MANJARO | 82        | 1.42%   |
| 5.8.16-2-MANJARO  | 75        | 1.29%   |
| 5.6.16-1-MANJARO  | 73        | 1.26%   |
| 5.10.2-2-MANJARO  | 66        | 1.14%   |
| 5.10.7-3-MANJARO  | 63        | 1.09%   |
| 5.10.36-2-MANJARO | 62        | 1.07%   |
| 5.7.9-1-MANJARO   | 61        | 1.05%   |
| 5.6.19-2-MANJARO  | 60        | 1.04%   |
| 5.8.3-2-MANJARO   | 59        | 1.02%   |
| 5.7.0-3-MANJARO   | 58        | 1%      |
| 5.6.15-1-MANJARO  | 58        | 1%      |
| 5.12.9-1-MANJARO  | 54        | 0.93%   |
| 5.7.17-2-MANJARO  | 52        | 0.9%    |
| 5.14.10-1-MANJARO | 51        | 0.88%   |
| 5.15.32-1-MANJARO | 50        | 0.86%   |
| 5.9.1-1-MANJARO   | 49        | 0.85%   |
| 5.15.7-1-MANJARO  | 48        | 0.83%   |
| 5.11.6-1-MANJARO  | 48        | 0.83%   |
| 5.10.23-1-MANJARO | 48        | 0.83%   |
| 5.16.14-1-MANJARO | 47        | 0.81%   |
| 5.10.34-1-MANJARO | 45        | 0.78%   |
| 5.6.12-1-MANJARO  | 44        | 0.76%   |
| 5.4.6-2-MANJARO   | 44        | 0.76%   |
| 5.6.7-1-MANJARO   | 43        | 0.74%   |
| 5.15.25-1-MANJARO | 43        | 0.74%   |
| 5.10.53-1-MANJARO | 43        | 0.74%   |
| 5.9.3-1-MANJARO   | 42        | 0.72%   |
| 5.4.15-2-MANJARO  | 42        | 0.72%   |
| 5.15.2-2-MANJARO  | 42        | 0.72%   |
| 5.10.70-1-MANJARO | 42        | 0.72%   |
| 5.10.15-1-MANJARO | 40        | 0.69%   |
| 5.12.2-1-MANJARO  | 37        | 0.64%   |
| 5.15.21-1-MANJARO | 36        | 0.62%   |
| 5.7.19-2-MANJARO  | 35        | 0.6%    |
| 5.13.13-1-MANJARO | 35        | 0.6%    |
| 5.13.12-1-MANJARO | 35        | 0.6%    |
| 5.10.56-1-MANJARO | 32        | 0.55%   |
| 5.6.11-1-MANJARO  | 30        | 0.52%   |
| 5.10.32-1-MANJARO | 30        | 0.52%   |
| 5.15.16-1-MANJARO | 29        | 0.5%    |
| 5.4.23-1-MANJARO  | 28        | 0.48%   |
| 5.16.11-2-MANJARO | 28        | 0.48%   |
| 5.15.6-2-MANJARO  | 28        | 0.48%   |
| 5.13.11-1-MANJARO | 28        | 0.48%   |
| 5.11.2-1-MANJARO  | 27        | 0.47%   |
| 5.10.79-1-MANJARO | 27        | 0.47%   |
| 5.4.80-2-MANJARO  | 26        | 0.45%   |
| 5.12.0-1-MANJARO  | 26        | 0.45%   |
| 5.10.30-1-MANJARO | 26        | 0.45%   |
| 5.15.19-1-MANJARO | 25        | 0.43%   |
| 5.4.64-1-MANJARO  | 24        | 0.41%   |
| 5.4.18-1-MANJARO  | 24        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 293       | 5.06%   |
| 5.13.19 | 175       | 3.02%   |
| 5.8.6   | 144       | 2.49%   |
| 5.9.11  | 136       | 2.35%   |
| 5.8.11  | 124       | 2.14%   |
| 5.15.28 | 117       | 2.02%   |
| 5.8.18  | 103       | 1.78%   |
| 5.10.42 | 101       | 1.74%   |
| 5.15.12 | 82        | 1.42%   |
| 5.8.16  | 76        | 1.31%   |
| 5.6.16  | 73        | 1.26%   |
| 5.7.0   | 72        | 1.24%   |
| 5.9.1   | 68        | 1.17%   |
| 5.6.19  | 66        | 1.14%   |
| 5.10.2  | 66        | 1.14%   |
| 5.10.7  | 65        | 1.12%   |
| 5.10.36 | 62        | 1.07%   |
| 5.7.9   | 61        | 1.05%   |
| 5.8.3   | 60        | 1.04%   |
| 5.6.15  | 58        | 1%      |
| 5.12.9  | 54        | 0.93%   |
| 5.7.17  | 53        | 0.92%   |
| 5.15.32 | 51        | 0.88%   |
| 5.14.10 | 51        | 0.88%   |
| 5.15.7  | 50        | 0.86%   |
| 5.11.6  | 49        | 0.85%   |
| 5.10.23 | 48        | 0.83%   |
| 5.16.14 | 47        | 0.81%   |
| 5.6.12  | 46        | 0.79%   |
| 5.15.2  | 46        | 0.79%   |
| 5.10.34 | 45        | 0.78%   |
| 5.9.3   | 44        | 0.76%   |
| 5.6.7   | 44        | 0.76%   |
| 5.4.6   | 44        | 0.76%   |
| 5.15.25 | 43        | 0.74%   |
| 5.10.53 | 43        | 0.74%   |
| 5.4.15  | 42        | 0.73%   |
| 5.10.70 | 42        | 0.73%   |
| 5.10.15 | 40        | 0.69%   |
| 5.15.21 | 37        | 0.64%   |
| 5.14.0  | 37        | 0.64%   |
| 5.12.2  | 37        | 0.64%   |
| 5.7.19  | 36        | 0.62%   |
| 5.13.13 | 35        | 0.6%    |
| 5.13.12 | 35        | 0.6%    |
| 5.8.0   | 32        | 0.55%   |
| 5.10.56 | 32        | 0.55%   |
| 5.6.11  | 30        | 0.52%   |
| 5.15.6  | 30        | 0.52%   |
| 5.10.32 | 30        | 0.52%   |
| 5.4.13  | 29        | 0.5%    |
| 5.17.1  | 29        | 0.5%    |
| 5.16.11 | 29        | 0.5%    |
| 5.15.16 | 29        | 0.5%    |
| 5.4.80  | 28        | 0.48%   |
| 5.4.33  | 28        | 0.48%   |
| 5.4.23  | 28        | 0.48%   |
| 5.13.11 | 28        | 0.48%   |
| 5.16.2  | 27        | 0.47%   |
| 5.11.2  | 27        | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 871       | 15.95%  |
| 5.4     | 622       | 11.39%  |
| 5.9     | 590       | 10.8%   |
| 5.8     | 557       | 10.2%   |
| 5.15    | 523       | 9.58%   |
| 5.6     | 393       | 7.2%    |
| 5.13    | 352       | 6.44%   |
| 5.7     | 263       | 4.82%   |
| 4.19    | 195       | 3.57%   |
| 5.11    | 185       | 3.39%   |
| 5.12    | 158       | 2.89%   |
| 5.16    | 155       | 2.84%   |
| 5.14    | 148       | 2.71%   |
| 5.5     | 111       | 2.03%   |
| 5.3     | 92        | 1.68%   |
| 4.14    | 59        | 1.08%   |
| 5.17    | 50        | 0.92%   |
| 5.2     | 41        | 0.75%   |
| 5.0     | 30        | 0.55%   |
| 5.1     | 26        | 0.48%   |
| 4.20    | 14        | 0.26%   |
| 4.18    | 12        | 0.22%   |
| 4.9     | 4         | 0.07%   |
| 4.16    | 4         | 0.07%   |
| 4.17    | 3         | 0.05%   |
| 4.7     | 2         | 0.04%   |
| 4.4     | 2         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4924      | 99.94%  |
| i686    | 2         | 0.04%   |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 1506      | 29.5%   |
| XFCE                     | 1216      | 23.82%  |
| GNOME                    | 1072      | 21%     |
| KDE                      | 547       | 10.71%  |
| Unknown                  | 273       | 5.35%   |
| X-Cinnamon               | 138       | 2.7%    |
| i3                       | 112       | 2.19%   |
| Cinnamon                 | 55        | 1.08%   |
| MATE                     | 51        | 1%      |
| Deepin                   | 48        | 0.94%   |
| Budgie                   | 22        | 0.43%   |
| LXQt                     | 14        | 0.27%   |
| Awesome                  | 14        | 0.27%   |
| LXDE                     | 7         | 0.14%   |
| Bspwm                    | 5         | 0.1%    |
| Sway                     | 4         | 0.08%   |
| i3-with-shmlog           | 3         | 0.06%   |
| dwm                      | 3         | 0.06%   |
| leftwm                   | 2         | 0.04%   |
| GNOME Flashback          | 2         | 0.04%   |
| GNOME Classic            | 2         | 0.04%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.02%   |
| qtile                    | 1         | 0.02%   |
| openbox                  | 1         | 0.02%   |
| ICEWM                    | 1         | 0.02%   |
| herbstluftwm             | 1         | 0.02%   |
| Enlightenment            | 1         | 0.02%   |
| /usr/bin/openbox-session | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4331      | 86.65%  |
| Wayland | 512       | 10.24%  |
| Unknown | 110       | 2.2%    |
| Tty     | 45        | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1934      | 38.24%  |
| SDDM    | 1286      | 25.43%  |
| LightDM | 928       | 18.35%  |
| GDM     | 673       | 13.31%  |
| TDM     | 220       | 4.35%   |
| LXDM    | 8         | 0.16%   |
| SLiM    | 3         | 0.06%   |
| XDM     | 2         | 0.04%   |
| Ly      | 2         | 0.04%   |
| GREETD  | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2050      | 40.97%  |
| Unknown | 397       | 7.93%   |
| de_DE   | 396       | 7.91%   |
| ru_RU   | 368       | 7.35%   |
| en_GB   | 312       | 6.24%   |
| pt_BR   | 198       | 3.96%   |
| fr_FR   | 127       | 2.54%   |
| es_ES   | 110       | 2.2%    |
| en_CA   | 109       | 2.18%   |
| pl_PL   | 91        | 1.82%   |
| it_IT   | 90        | 1.8%    |
| en_AU   | 64        | 1.28%   |
| en_IN   | 62        | 1.24%   |
| ru_UA   | 37        | 0.74%   |
| zh_CN   | 35        | 0.7%    |
| es_MX   | 33        | 0.66%   |
| de_AT   | 29        | 0.58%   |
| nl_NL   | 28        | 0.56%   |
| sv_SE   | 24        | 0.48%   |
| en_IE   | 24        | 0.48%   |
| fi_FI   | 18        | 0.36%   |
| en_NZ   | 18        | 0.36%   |
| hu_HU   | 17        | 0.34%   |
| es_AR   | 17        | 0.34%   |
| cs_CZ   | 17        | 0.34%   |
| pt_PT   | 16        | 0.32%   |
| en_ZA   | 16        | 0.32%   |
| es_CL   | 15        | 0.3%    |
| C       | 15        | 0.3%    |
| uk_UA   | 14        | 0.28%   |
| tr_TR   | 13        | 0.26%   |
| en_DK   | 13        | 0.26%   |
| de_CH   | 12        | 0.24%   |
| nl_BE   | 11        | 0.22%   |
| fr_CA   | 11        | 0.22%   |
| es_CO   | 11        | 0.22%   |
| da_DK   | 11        | 0.22%   |
| en_IL   | 10        | 0.2%    |
| en_PH   | 9         | 0.18%   |
| en_DE   | 9         | 0.18%   |
| el_GR   | 9         | 0.18%   |
| nb_NO   | 8         | 0.16%   |
| ja_JP   | 8         | 0.16%   |
| zh_TW   | 7         | 0.14%   |
| es_PE   | 7         | 0.14%   |
| sk_SK   | 6         | 0.12%   |
| fr_BE   | 6         | 0.12%   |
| en_SG   | 6         | 0.12%   |
| bg_BG   | 6         | 0.12%   |
| ro_RO   | 4         | 0.08%   |
| id_ID   | 4         | 0.08%   |
| fr_CH   | 4         | 0.08%   |
| es_EC   | 4         | 0.08%   |
| es_BO   | 4         | 0.08%   |
| en_HK   | 4         | 0.08%   |
| szl_PL  | 3         | 0.06%   |
| ko_KR   | 3         | 0.06%   |
| hr_HR   | 3         | 0.06%   |
| eu_ES   | 3         | 0.06%   |
| et_EE   | 3         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2696      | 53.81%  |
| EFI  | 2314      | 46.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4254      | 85.47%  |
| Btrfs    | 359       | 7.21%   |
| Unknown  | 128       | 2.57%   |
| Overlay  | 118       | 2.37%   |
| Xfs      | 59        | 1.19%   |
| F2fs     | 23        | 0.46%   |
| Tmpfs    | 17        | 0.34%   |
| Ext3     | 5         | 0.1%    |
| Zfs      | 4         | 0.08%   |
| Ext2     | 4         | 0.08%   |
| Reiserfs | 3         | 0.06%   |
| XXXX     | 1         | 0.02%   |
| XXXfs    | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2353      | 46.94%  |
| Unknown | 2142      | 42.73%  |
| MBR     | 518       | 10.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4365      | 87.42%  |
| Yes       | 628       | 12.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3270      | 65.37%  |
| Yes       | 1732      | 34.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 902       | 18.31%  |
| Lenovo                 | 795       | 16.14%  |
| Hewlett-Packard        | 636       | 12.91%  |
| Dell                   | 540       | 10.96%  |
| Gigabyte Technology    | 415       | 8.42%   |
| MSI                    | 379       | 7.69%   |
| Acer                   | 257       | 5.22%   |
| ASRock                 | 214       | 4.34%   |
| Apple                  | 96        | 1.95%   |
| Intel                  | 70        | 1.42%   |
| Toshiba                | 54        | 1.1%    |
| Samsung Electronics    | 53        | 1.08%   |
| HUAWEI                 | 40        | 0.81%   |
| Timi                   | 30        | 0.61%   |
| Unknown                | 27        | 0.55%   |
| Fujitsu                | 26        | 0.53%   |
| Notebook               | 25        | 0.51%   |
| Sony                   | 22        | 0.45%   |
| Google                 | 19        | 0.39%   |
| Microsoft              | 17        | 0.35%   |
| Biostar                | 17        | 0.35%   |
| Pegatron               | 14        | 0.28%   |
| Medion                 | 14        | 0.28%   |
| Alienware              | 14        | 0.28%   |
| Huanan                 | 10        | 0.2%    |
| TUXEDO                 | 9         | 0.18%   |
| Positivo               | 9         | 0.18%   |
| AZW                    | 9         | 0.18%   |
| Packard Bell           | 8         | 0.16%   |
| Foxconn                | 8         | 0.16%   |
| Schenker               | 7         | 0.14%   |
| Razer                  | 7         | 0.14%   |
| TrekStor               | 6         | 0.12%   |
| Panasonic              | 6         | 0.12%   |
| Monster                | 6         | 0.12%   |
| LG Electronics         | 6         | 0.12%   |
| HONOR                  | 6         | 0.12%   |
| ECS                    | 6         | 0.12%   |
| Clevo                  | 6         | 0.12%   |
| ZOTAC                  | 5         | 0.1%    |
| Teclast                | 5         | 0.1%    |
| System76               | 5         | 0.1%    |
| Supermicro             | 5         | 0.1%    |
| Multilaser             | 5         | 0.1%    |
| AMI                    | 5         | 0.1%    |
| PC Specialist          | 4         | 0.08%   |
| Gateway                | 4         | 0.08%   |
| Fujitsu Siemens        | 4         | 0.08%   |
| Chuwi                  | 4         | 0.08%   |
| BESSTAR Tech           | 4         | 0.08%   |
| Jumper                 | 3         | 0.06%   |
| Intel Client Systems   | 3         | 0.06%   |
| Wortmann AG            | 2         | 0.04%   |
| UNOWHY                 | 2         | 0.04%   |
| Star Labs              | 2         | 0.04%   |
| Shuttle                | 2         | 0.04%   |
| Semp Toshiba           | 2         | 0.04%   |
| PCWare                 | 2         | 0.04%   |
| ONE-NETBOOK TECHNOLOGY | 2         | 0.04%   |
| MECHREVO               | 2         | 0.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 60        | 1.22%   |
| Unknown                              | 37        | 0.75%   |
| Gigabyte B450M DS3H                  | 24        | 0.49%   |
| MSI MS-7C37                          | 19        | 0.39%   |
| MSI MS-7C02                          | 19        | 0.39%   |
| HP Notebook                          | 18        | 0.37%   |
| ASUS PRIME A320M-K                   | 15        | 0.3%    |
| MSI MS-7B79                          | 14        | 0.28%   |
| ASRock B450M Pro4                    | 14        | 0.28%   |
| Lenovo Legion 5 15ARH05 82B5         | 13        | 0.26%   |
| ASUS TUF GAMING X570-PLUS            | 13        | 0.26%   |
| ASUS ROG STRIX B450-F GAMING         | 13        | 0.26%   |
| MSI MS-7B86                          | 12        | 0.24%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 11        | 0.22%   |
| Dell XPS 13 9310                     | 11        | 0.22%   |
| ASUS PRIME B350-PLUS                 | 11        | 0.22%   |
| Lenovo IdeaPad Flex 5 14ARE05 81X2   | 10        | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 10        | 0.2%    |
| Gigabyte X470 AORUS ULTRA GAMING     | 10        | 0.2%    |
| Gigabyte 970A-DS3P                   | 10        | 0.2%    |
| Dell OptiPlex 9020                   | 10        | 0.2%    |
| ASUS PRIME B450M-A                   | 10        | 0.2%    |
| MSI MS-7C91                          | 9         | 0.18%   |
| MSI MS-7A38                          | 9         | 0.18%   |
| HP Pavilion Notebook                 | 9         | 0.18%   |
| HP Pavilion dv7                      | 9         | 0.18%   |
| HP Laptop 15-bs0xx                   | 9         | 0.18%   |
| Gigabyte X570 AORUS MASTER           | 9         | 0.18%   |
| Gigabyte X570 AORUS ELITE            | 9         | 0.18%   |
| Dell XPS 15 9560                     | 9         | 0.18%   |
| MSI MS-7B89                          | 8         | 0.16%   |
| HP Pavilion 15                       | 8         | 0.16%   |
| HP 15                                | 8         | 0.16%   |
| Gigabyte B450 AORUS M                | 8         | 0.16%   |
| Dell XPS 15 9500                     | 8         | 0.16%   |
| Dell OptiPlex 7010                   | 8         | 0.16%   |
| ASUS TUF GAMING B550M-PLUS           | 8         | 0.16%   |
| ASUS PRIME X470-PRO                  | 8         | 0.16%   |
| Timi TM1701                          | 7         | 0.14%   |
| MSI MS-7A34                          | 7         | 0.14%   |
| MSI MS-7817                          | 7         | 0.14%   |
| MSI MS-7693                          | 7         | 0.14%   |
| Lenovo Z50-70 20354                  | 7         | 0.14%   |
| Lenovo Y520-15IKBN 80WK              | 7         | 0.14%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 7         | 0.14%   |
| HP Pavilion g6                       | 7         | 0.14%   |
| HP Pavilion dv6                      | 7         | 0.14%   |
| Dell XPS 15 7590                     | 7         | 0.14%   |
| Dell XPS 13 7390                     | 7         | 0.14%   |
| Dell Inspiron 3542                   | 7         | 0.14%   |
| ASUS ROG STRIX X570-E GAMING         | 7         | 0.14%   |
| ASUS ROG CROSSHAIR VIII HERO         | 7         | 0.14%   |
| ASUS PRIME X370-PRO                  | 7         | 0.14%   |
| ASUS PRIME B350M-A                   | 7         | 0.14%   |
| ASRock B450 Pro4                     | 7         | 0.14%   |
| Apple MacBookPro9,2                  | 7         | 0.14%   |
| Acer Swift SF314-42                  | 7         | 0.14%   |
| Lenovo ThinkBook 15-IIL 20SM         | 6         | 0.12%   |
| Lenovo IdeaPad S540-14API 81NH       | 6         | 0.12%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 6         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 322       | 6.54%   |
| Lenovo IdeaPad     | 208       | 4.22%   |
| Dell Inspiron      | 163       | 3.31%   |
| Acer Aspire        | 160       | 3.25%   |
| HP Pavilion        | 133       | 2.7%    |
| ASUS ROG           | 119       | 2.42%   |
| ASUS PRIME         | 118       | 2.39%   |
| Dell Latitude      | 112       | 2.27%   |
| Dell XPS           | 87        | 1.77%   |
| ASUS TUF           | 76        | 1.54%   |
| HP ProBook         | 74        | 1.5%    |
| HP Laptop          | 68        | 1.38%   |
| HP EliteBook       | 67        | 1.36%   |
| Dell OptiPlex      | 61        | 1.24%   |
| ASUS All           | 60        | 1.22%   |
| HP ENVY            | 52        | 1.06%   |
| Lenovo Legion      | 49        | 0.99%   |
| Toshiba Satellite  | 48        | 0.97%   |
| Dell Precision     | 47        | 0.95%   |
| ASUS VivoBook      | 46        | 0.93%   |
| HP Compaq          | 42        | 0.85%   |
| Gigabyte X570      | 39        | 0.79%   |
| Lenovo Yoga        | 37        | 0.75%   |
| Gigabyte B450M     | 37        | 0.75%   |
| Unknown            | 37        | 0.75%   |
| Dell Vostro        | 33        | 0.67%   |
| Acer Swift         | 30        | 0.61%   |
| Gigabyte B450      | 25        | 0.51%   |
| ASUS ZenBook       | 25        | 0.51%   |
| HP OMEN            | 21        | 0.43%   |
| ASRock B450M       | 21        | 0.43%   |
| Acer Nitro         | 21        | 0.43%   |
| Lenovo ThinkCentre | 20        | 0.41%   |
| MSI MS-7C37        | 19        | 0.39%   |
| MSI MS-7C02        | 19        | 0.39%   |
| Lenovo ThinkBook   | 19        | 0.39%   |
| HP ZBook           | 18        | 0.37%   |
| HP Notebook        | 18        | 0.37%   |
| Microsoft Surface  | 17        | 0.35%   |
| Fujitsu LIFEBOOK   | 17        | 0.35%   |
| HP Spectre         | 16        | 0.32%   |
| ASRock B450        | 16        | 0.32%   |
| HP 250             | 15        | 0.3%    |
| ASUS P8Z77-V       | 15        | 0.3%    |
| MSI MS-7B79        | 14        | 0.28%   |
| Dell G3            | 14        | 0.28%   |
| ASRock X570        | 14        | 0.28%   |
| Timi RedmiBook     | 13        | 0.26%   |
| Gigabyte Z390      | 13        | 0.26%   |
| MSI MS-7B86        | 12        | 0.24%   |
| HP 15              | 12        | 0.24%   |
| Gigabyte X470      | 12        | 0.24%   |
| Acer Predator      | 12        | 0.24%   |
| HP EliteDesk       | 11        | 0.22%   |
| ASUS P8H61-M       | 11        | 0.22%   |
| ASUS Maximus       | 11        | 0.22%   |
| ASUS ASUS          | 11        | 0.22%   |
| Acer TravelMate    | 11        | 0.22%   |
| Gigabyte B550      | 10        | 0.2%    |
| Gigabyte 970A-DS3P | 10        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 707       | 14.35%  |
| 2018    | 685       | 13.9%   |
| 2020    | 602       | 12.22%  |
| 2017    | 449       | 9.11%   |
| 2012    | 390       | 7.92%   |
| 2014    | 303       | 6.15%   |
| 2013    | 299       | 6.07%   |
| 2011    | 270       | 5.48%   |
| 2016    | 267       | 5.42%   |
| 2015    | 267       | 5.42%   |
| 2021    | 215       | 4.36%   |
| 2010    | 172       | 3.49%   |
| 2009    | 110       | 2.23%   |
| 2008    | 102       | 2.07%   |
| 2007    | 60        | 1.22%   |
| 2006    | 18        | 0.37%   |
| 2005    | 4         | 0.08%   |
| Unknown | 4         | 0.08%   |
| 2022    | 3         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2716      | 55.12%  |
| Desktop     | 1918      | 38.93%  |
| Convertible | 167       | 3.39%   |
| Mini pc     | 51        | 1.04%   |
| All in one  | 35        | 0.71%   |
| Tablet      | 33        | 0.67%   |
| Server      | 6         | 0.12%   |
| Phone       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4924      | 99.92%  |
| Enabled  | 4         | 0.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4896      | 99.37%  |
| Yes  | 31        | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1389      | 27.81%  |
| 4.01-8.0        | 1119      | 22.41%  |
| 8.01-16.0       | 993       | 19.88%  |
| 3.01-4.0        | 620       | 12.41%  |
| 32.01-64.0      | 551       | 11.03%  |
| 64.01-256.0     | 109       | 2.18%   |
| 1.01-2.0        | 94        | 1.88%   |
| 24.01-32.0      | 88        | 1.76%   |
| 2.01-3.0        | 29        | 0.58%   |
| More than 256.0 | 1         | 0.02%   |
| 0.51-1.0        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1479      | 27.1%   |
| 2.01-3.0    | 1426      | 26.13%  |
| 4.01-8.0    | 1096      | 20.08%  |
| 3.01-4.0    | 874       | 16.01%  |
| 8.01-16.0   | 310       | 5.68%   |
| 0.51-1.0    | 196       | 3.59%   |
| 16.01-24.0  | 42        | 0.77%   |
| 0.01-0.5    | 19        | 0.35%   |
| 24.01-32.0  | 9         | 0.16%   |
| 32.01-64.0  | 6         | 0.11%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2547      | 50.31%  |
| 2      | 1445      | 28.54%  |
| 3      | 521       | 10.29%  |
| 4      | 274       | 5.41%   |
| 5      | 141       | 2.78%   |
| 6      | 60        | 1.19%   |
| 7      | 30        | 0.59%   |
| 0      | 25        | 0.49%   |
| 8      | 10        | 0.2%    |
| 9      | 5         | 0.1%    |
| 11     | 3         | 0.06%   |
| 12     | 1         | 0.02%   |
| 10     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3480      | 70.05%  |
| Yes       | 1488      | 29.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4162      | 84.32%  |
| No        | 774       | 15.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3829      | 77.32%  |
| No        | 1123      | 22.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3166      | 63.7%   |
| No        | 1804      | 36.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 806       | 16.29%  |
| Germany      | 580       | 11.72%  |
| Russia       | 464       | 9.38%   |
| Brazil       | 293       | 5.92%   |
| France       | 180       | 3.64%   |
| UK           | 174       | 3.52%   |
| Canada       | 170       | 3.44%   |
| Spain        | 148       | 2.99%   |
| Poland       | 147       | 2.97%   |
| Italy        | 140       | 2.83%   |
| Ukraine      | 132       | 2.67%   |
| Netherlands  | 105       | 2.12%   |
| India        | 90        | 1.82%   |
| Sweden       | 73        | 1.48%   |
| Australia    | 72        | 1.45%   |
| Austria      | 66        | 1.33%   |
| Mexico       | 64        | 1.29%   |
| China        | 51        | 1.03%   |
| Belgium      | 50        | 1.01%   |
| Romania      | 49        | 0.99%   |
| Finland      | 47        | 0.95%   |
| Switzerland  | 46        | 0.93%   |
| Turkey       | 45        | 0.91%   |
| Portugal     | 43        | 0.87%   |
| Czechia      | 40        | 0.81%   |
| Norway       | 39        | 0.79%   |
| Indonesia    | 39        | 0.79%   |
| Greece       | 37        | 0.75%   |
| Hungary      | 35        | 0.71%   |
| Belarus      | 35        | 0.71%   |
| Bulgaria     | 33        | 0.67%   |
| Denmark      | 29        | 0.59%   |
| Argentina    | 29        | 0.59%   |
| South Africa | 23        | 0.46%   |
| Taiwan       | 22        | 0.44%   |
| New Zealand  | 22        | 0.44%   |
| Colombia     | 22        | 0.44%   |
| Bangladesh   | 21        | 0.42%   |
| Lithuania    | 20        | 0.4%    |
| Ireland      | 20        | 0.4%    |
| Israel       | 19        | 0.38%   |
| Chile        | 18        | 0.36%   |
| Japan        | 17        | 0.34%   |
| Croatia      | 17        | 0.34%   |
| Iran         | 16        | 0.32%   |
| Serbia       | 15        | 0.3%    |
| Vietnam      | 14        | 0.28%   |
| Slovakia     | 14        | 0.28%   |
| Peru         | 13        | 0.26%   |
| Estonia      | 13        | 0.26%   |
| Egypt        | 13        | 0.26%   |
| Saudi Arabia | 12        | 0.24%   |
| Philippines  | 12        | 0.24%   |
| Slovenia     | 11        | 0.22%   |
| Kazakhstan   | 10        | 0.2%    |
| Hong Kong    | 10        | 0.2%    |
| Malaysia     | 9         | 0.18%   |
| South Korea  | 8         | 0.16%   |
| Costa Rica   | 8         | 0.16%   |
| Venezuela    | 7         | 0.14%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 107       | 2.07%   |
| St Petersburg     | 56        | 1.08%   |
| Berlin            | 42        | 0.81%   |
| Vienna            | 40        | 0.77%   |
| Kyiv              | 36        | 0.69%   |
| Paris             | 35        | 0.68%   |
| Warsaw            | 28        | 0.54%   |
| Sao Paulo         | 27        | 0.52%   |
| Madrid            | 27        | 0.52%   |
| Toronto           | 25        | 0.48%   |
| Athens            | 23        | 0.44%   |
| Amsterdam         | 22        | 0.42%   |
| Rome              | 21        | 0.41%   |
| Minsk             | 21        | 0.41%   |
| Helsinki          | 21        | 0.41%   |
| Hamburg           | 21        | 0.41%   |
| Barcelona         | 20        | 0.39%   |
| Frankfurt am Main | 19        | 0.37%   |
| Bengaluru         | 19        | 0.37%   |
| Stockholm         | 18        | 0.35%   |
| Novosibirsk       | 18        | 0.35%   |
| Munich            | 18        | 0.35%   |
| Montreal          | 18        | 0.35%   |
| Yekaterinburg     | 17        | 0.33%   |
| London            | 17        | 0.33%   |
| Sofia             | 16        | 0.31%   |
| Krakow            | 16        | 0.31%   |
| Bucharest         | 16        | 0.31%   |
| Sydney            | 15        | 0.29%   |
| Stuttgart         | 15        | 0.29%   |
| Rio de Janeiro    | 15        | 0.29%   |
| Portland          | 15        | 0.29%   |
| Milan             | 15        | 0.29%   |
| Istanbul          | 15        | 0.29%   |
| Belo Horizonte    | 15        | 0.29%   |
| Prague            | 14        | 0.27%   |
| Miami             | 14        | 0.27%   |
| Dhaka             | 14        | 0.27%   |
| Curitiba          | 14        | 0.27%   |
| Budapest          | 14        | 0.27%   |
| Rostov-on-Don     | 13        | 0.25%   |
| Oslo              | 13        | 0.25%   |
| Dublin            | 13        | 0.25%   |
| Chicago           | 13        | 0.25%   |
| Zurich            | 12        | 0.23%   |
| Vilnius           | 12        | 0.23%   |
| Nuremberg         | 12        | 0.23%   |
| Los Angeles       | 12        | 0.23%   |
| Copenhagen        | 12        | 0.23%   |
| Austin            | 12        | 0.23%   |
| Atlanta           | 12        | 0.23%   |
| Seattle           | 11        | 0.21%   |
| Perth             | 11        | 0.21%   |
| Brisbane          | 11        | 0.21%   |
| Vancouver         | 10        | 0.19%   |
| The Hague         | 10        | 0.19%   |
| Odessa            | 10        | 0.19%   |
| Mexico City       | 10        | 0.19%   |
| Melbourne         | 10        | 0.19%   |
| Karlsruhe         | 10        | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1401      | 2089   | 17.26%  |
| WDC                            | 1220      | 1815   | 15.03%  |
| Seagate                        | 1185      | 1777   | 14.6%   |
| Toshiba                        | 560       | 666    | 6.9%    |
| Kingston                       | 491       | 633    | 6.05%   |
| SanDisk                        | 417       | 527    | 5.14%   |
| Crucial                        | 352       | 494    | 4.34%   |
| Unknown                        | 245       | 321    | 3.02%   |
| Intel                          | 238       | 316    | 2.93%   |
| SK Hynix                       | 202       | 243    | 2.49%   |
| Hitachi                        | 189       | 249    | 2.33%   |
| HGST                           | 174       | 232    | 2.14%   |
| A-DATA Technology              | 109       | 143    | 1.34%   |
| Phison                         | 102       | 146    | 1.26%   |
| Micron Technology              | 92        | 113    | 1.13%   |
| China                          | 63        | 86     | 0.78%   |
| Apple                          | 56        | 65     | 0.69%   |
| Silicon Motion                 | 48        | 63     | 0.59%   |
| Transcend                      | 45        | 49     | 0.55%   |
| PNY                            | 43        | 61     | 0.53%   |
| XPG                            | 41        | 46     | 0.51%   |
| KIOXIA                         | 41        | 45     | 0.51%   |
| Patriot                        | 40        | 46     | 0.49%   |
| OCZ                            | 40        | 46     | 0.49%   |
| SPCC                           | 38        | 46     | 0.47%   |
| Intenso                        | 38        | 53     | 0.47%   |
| Corsair                        | 34        | 43     | 0.42%   |
| JMicron                        | 33        | 40     | 0.41%   |
| PLEXTOR                        | 31        | 42     | 0.38%   |
| LITEONIT                       | 31        | 35     | 0.38%   |
| Micron/Crucial Technology      | 30        | 36     | 0.37%   |
| LITEON                         | 29        | 32     | 0.36%   |
| GOODRAM                        | 29        | 42     | 0.36%   |
| Apacer                         | 18        | 19     | 0.22%   |
| Lexar                          | 15        | 17     | 0.18%   |
| Hewlett-Packard                | 15        | 21     | 0.18%   |
| Fujitsu                        | 15        | 15     | 0.18%   |
| Team                           | 14        | 18     | 0.17%   |
| Realtek Semiconductor          | 14        | 16     | 0.17%   |
| KingSpec                       | 14        | 15     | 0.17%   |
| MAXTOR                         | 12        | 15     | 0.15%   |
| Gigabyte Technology            | 12        | 18     | 0.15%   |
| SABRENT                        | 11        | 11     | 0.14%   |
| KingDian                       | 11        | 11     | 0.14%   |
| ASMT                           | 11        | 18     | 0.14%   |
| Union Memory (Shenzhen)        | 9         | 9      | 0.11%   |
| TO Exter                       | 8         | 9      | 0.1%    |
| ADATA Technology               | 8         | 9      | 0.1%    |
| Union Memory                   | 7         | 7      | 0.09%   |
| Leven                          | 7         | 8      | 0.09%   |
| Lenovo                         | 7         | 9      | 0.09%   |
| Unknown                        | 7         | 7      | 0.09%   |
| Mushkin                        | 6         | 7      | 0.07%   |
| FORESEE                        | 6         | 8      | 0.07%   |
| External                       | 6         | 8      | 0.07%   |
| Solid State Storage Technology | 5         | 8      | 0.06%   |
| Netac                          | 5         | 5      | 0.06%   |
| Lite-On                        | 5         | 5      | 0.06%   |
| USB3.0                         | 4         | 4      | 0.05%   |
| PIONEER                        | 4         | 6      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 105       | 1.16%   |
| Samsung SSD 860 EVO 500GB           | 87        | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB      | 86        | 0.95%   |
| Samsung NVMe SSD Drive 512GB        | 79        | 0.87%   |
| Samsung SSD 850 EVO 500GB           | 77        | 0.85%   |
| Samsung NVMe SSD Drive 500GB        | 74        | 0.81%   |
| Kingston SA400S37120G 120GB SSD     | 72        | 0.79%   |
| Samsung SSD 850 EVO 250GB           | 67        | 0.74%   |
| Samsung NVMe SSD Drive 1TB          | 64        | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB      | 59        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB      | 57        | 0.63%   |
| Crucial CT500MX500SSD1 500GB        | 56        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 55        | 0.61%   |
| Samsung SSD 860 EVO 1TB             | 55        | 0.61%   |
| Samsung NVMe SSD Drive 256GB        | 53        | 0.58%   |
| Toshiba MQ01ABD100 1TB              | 52        | 0.57%   |
| Sandisk NVMe SSD Drive 512GB        | 49        | 0.54%   |
| Crucial CT240BX500SSD1 240GB        | 48        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB         | 47        | 0.52%   |
| Toshiba DT01ACA100 1TB              | 46        | 0.51%   |
| Samsung SSD 860 EVO 250GB           | 46        | 0.51%   |
| HGST HTS721010A9E630 1TB            | 46        | 0.51%   |
| Seagate Expansion+ 2TB              | 45        | 0.5%    |
| SK Hynix NVMe SSD Drive 512GB       | 42        | 0.46%   |
| Toshiba MQ04ABF100 1TB              | 41        | 0.45%   |
| Kingston SA400S37480G 480GB SSD     | 41        | 0.45%   |
| Unknown SD/MMC/MS PRO 16GB          | 40        | 0.44%   |
| Toshiba MQ01ABF050 500GB            | 40        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB            | 39        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB     | 36        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB      | 35        | 0.39%   |
| Sandisk NVMe SSD Drive 500GB        | 35        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB      | 35        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD    | 35        | 0.39%   |
| Intel NVMe SSD Drive 512GB          | 35        | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB      | 33        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB            | 31        | 0.34%   |
| Samsung SSD 970 EVO 1TB             | 31        | 0.34%   |
| Unknown MMC Card  64GB              | 29        | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB      | 29        | 0.32%   |
| Samsung SSD 970 EVO 500GB           | 29        | 0.32%   |
| Samsung NVMe SSD Drive 250GB        | 29        | 0.32%   |
| Toshiba HDWD110 1TB                 | 28        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB      | 28        | 0.31%   |
| Sandisk NVMe SSD Drive 1TB          | 28        | 0.31%   |
| Seagate ST3500418AS 500GB           | 27        | 0.3%    |
| Sandisk NVMe SSD Drive 256GB        | 27        | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 26        | 0.29%   |
| Unknown MMC Card  32GB              | 26        | 0.29%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 26        | 0.29%   |
| Seagate ST500LT012-1DG142 500GB     | 26        | 0.29%   |
| HGST HTS545050A7E680 500GB          | 26        | 0.29%   |
| SK Hynix NVMe SSD Drive 256GB       | 25        | 0.28%   |
| Seagate Expansion Desk 4TB          | 25        | 0.28%   |
| Samsung SSD 860 QVO 1TB             | 25        | 0.28%   |
| Samsung SSD 840 EVO 250GB           | 24        | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 23        | 0.25%   |
| Toshiba DT01ACA200 2TB              | 23        | 0.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 23        | 0.25%   |
| Seagate ST2000DM001-1CH164 2TB      | 23        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1164      | 1737   | 36.77%  |
| WDC                 | 965       | 1425   | 30.48%  |
| Toshiba             | 406       | 482    | 12.82%  |
| Hitachi             | 189       | 249    | 5.97%   |
| HGST                | 173       | 231    | 5.46%   |
| Samsung Electronics | 135       | 195    | 4.26%   |
| Unknown             | 43        | 52     | 1.36%   |
| Apple               | 16        | 20     | 0.51%   |
| Fujitsu             | 15        | 15     | 0.47%   |
| SABRENT             | 11        | 11     | 0.35%   |
| MAXTOR              | 11        | 14     | 0.35%   |
| ASMT                | 8         | 10     | 0.25%   |
| Intenso             | 6         | 9      | 0.19%   |
| JMicron             | 4         | 7      | 0.13%   |
| Hewlett-Packard     | 3         | 3      | 0.09%   |
| Asmedia             | 3         | 5      | 0.09%   |
| USB3.0              | 2         | 2      | 0.06%   |
| HGST HTS            | 2         | 2      | 0.06%   |
| Apricorn            | 2         | 2      | 0.06%   |
| QNAP                | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 715       | 991    | 25.11%  |
| Kingston            | 410       | 523    | 14.4%   |
| Crucial             | 320       | 453    | 11.24%  |
| SanDisk             | 237       | 302    | 8.32%   |
| WDC                 | 172       | 225    | 6.04%   |
| Intel               | 85        | 107    | 2.98%   |
| A-DATA Technology   | 84        | 109    | 2.95%   |
| China               | 62        | 85     | 2.18%   |
| Micron Technology   | 53        | 62     | 1.86%   |
| Toshiba             | 46        | 57     | 1.62%   |
| SK Hynix            | 43        | 52     | 1.51%   |
| Transcend           | 41        | 44     | 1.44%   |
| OCZ                 | 40        | 46     | 1.4%    |
| PNY                 | 38        | 56     | 1.33%   |
| Patriot             | 37        | 43     | 1.3%    |
| LITEONIT            | 31        | 35     | 1.09%   |
| SPCC                | 30        | 38     | 1.05%   |
| Apple               | 30        | 33     | 1.05%   |
| PLEXTOR             | 28        | 39     | 0.98%   |
| Intenso             | 27        | 37     | 0.95%   |
| GOODRAM             | 27        | 40     | 0.95%   |
| LITEON              | 23        | 26     | 0.81%   |
| Corsair             | 23        | 30     | 0.81%   |
| Apacer              | 17        | 18     | 0.6%    |
| Lexar               | 14        | 16     | 0.49%   |
| Seagate             | 13        | 20     | 0.46%   |
| KingSpec            | 13        | 14     | 0.46%   |
| Team                | 12        | 16     | 0.42%   |
| JMicron             | 12        | 13     | 0.42%   |
| KingDian            | 11        | 11     | 0.39%   |
| Gigabyte Technology | 9         | 10     | 0.32%   |
| TO Exter            | 8         | 9      | 0.28%   |
| Leven               | 6         | 7      | 0.21%   |
| Hewlett-Packard     | 6         | 8      | 0.21%   |
| External            | 6         | 8      | 0.21%   |
| Netac               | 5         | 5      | 0.18%   |
| Mushkin             | 5         | 6      | 0.18%   |
| NGFF                | 4         | 4      | 0.14%   |
| Hoodisk             | 4         | 4      | 0.14%   |
| FORESEE             | 4         | 4      | 0.14%   |
| Vaseky              | 3         | 3      | 0.11%   |
| Unknown             | 3         | 6      | 0.11%   |
| Teclast             | 3         | 3      | 0.11%   |
| Pioneer             | 3         | 5      | 0.11%   |
| LONDISK             | 3         | 3      | 0.11%   |
| Kingmax             | 3         | 4      | 0.11%   |
| DREVO               | 3         | 4      | 0.11%   |
| ASMT                | 3         | 8      | 0.11%   |
| Unknown             | 3         | 3      | 0.11%   |
| Zheino              | 2         | 2      | 0.07%   |
| USB3.0              | 2         | 2      | 0.07%   |
| TwinMOS             | 2         | 2      | 0.07%   |
| TCSUNBOW            | 2         | 2      | 0.07%   |
| Smartbuy            | 2         | 2      | 0.07%   |
| OWC                 | 2         | 4      | 0.07%   |
| OCZ-VERTEX3         | 2         | 2      | 0.07%   |
| INNOVATION IT       | 2         | 2      | 0.07%   |
| GALAX               | 2         | 2      | 0.07%   |
| Emtec               | 2         | 2      | 0.07%   |
| Colorful            | 2         | 2      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2564      | 4479   | 35.96%  |
| SSD     | 2416      | 3729   | 33.88%  |
| NVMe    | 1854      | 2556   | 26%     |
| MMC     | 188       | 247    | 2.64%   |
| Unknown | 108       | 130    | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3755      | 7874   | 61.28%  |
| NVMe | 1854      | 2552   | 30.25%  |
| SAS  | 331       | 468    | 5.4%    |
| MMC  | 188       | 247    | 3.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2756      | 4453   | 51.92%  |
| 0.51-1.0   | 1690      | 2455   | 31.84%  |
| 1.01-2.0   | 513       | 740    | 9.66%   |
| 3.01-4.0   | 161       | 249    | 3.03%   |
| 2.01-3.0   | 106       | 170    | 2%      |
| 4.01-10.0  | 71        | 120    | 1.34%   |
| 10.01-20.0 | 11        | 21     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1263      | 24.54%  |
| 251-500        | 1120      | 21.76%  |
| 501-1000       | 803       | 15.6%   |
| 1001-2000      | 573       | 11.13%  |
| More than 3000 | 315       | 6.12%   |
| 51-100         | 284       | 5.52%   |
| Unknown        | 264       | 5.13%   |
| 2001-3000      | 222       | 4.31%   |
| 1-20           | 158       | 3.07%   |
| 21-50          | 145       | 2.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1153      | 21.55%  |
| 21-50          | 883       | 16.5%   |
| 101-250        | 862       | 16.11%  |
| 51-100         | 733       | 13.7%   |
| 251-500        | 548       | 10.24%  |
| 501-1000       | 431       | 8.06%   |
| Unknown        | 264       | 4.93%   |
| 1001-2000      | 252       | 4.71%   |
| More than 3000 | 128       | 2.39%   |
| 2001-3000      | 93        | 1.74%   |
| 0              | 3         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 2.12%   |
| HGST HTS545050A7E680 500GB                          | 8         | 8      | 1.7%    |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 7      | 1.49%   |
| HGST HTS721010A9E630 1TB                            | 7         | 7      | 1.49%   |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.49%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 1.27%   |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.27%   |
| WDC WD5000AAKX-001CA0 500GB                         | 5         | 7      | 1.06%   |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 1.06%   |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 1.06%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.85%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.85%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 5      | 0.85%   |
| Hitachi HDS721010CLA332 1TB                         | 4         | 4      | 0.85%   |
| Crucial CT525MX300SSD1 528GB                        | 4         | 4      | 0.85%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.64%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.64%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.64%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.64%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 3         | 3      | 0.64%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 3      | 0.64%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.64%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 0.64%   |
| Seagate ST9320325AS 320GB                           | 3         | 4      | 0.64%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 14     | 0.64%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.64%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 4      | 0.64%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.64%   |
| Seagate ST1000DX001-1CM162 1TB                      | 3         | 5      | 0.64%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.64%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 3      | 0.64%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 0.64%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.64%   |
| HGST HTS725050A7E630 500GB                          | 3         | 3      | 0.64%   |
| HGST HTS541010A9E680 1TB                            | 3         | 3      | 0.64%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2         | 2      | 0.42%   |
| WDC WD5000AAKX-003CA0 500GB                         | 2         | 2      | 0.42%   |
| WDC WD5000AACS-00G8B1 500GB                         | 2         | 2      | 0.42%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 2         | 3      | 0.42%   |
| WDC WD20EARX-00PASB0 2TB                            | 2         | 2      | 0.42%   |
| WDC WD20EARS-00MVWB0 2TB                            | 2         | 2      | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 0.42%   |
| WDC WD1001FALS-40K1B0 1TB                           | 2         | 2      | 0.42%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 0.42%   |
| Seagate ST3750630AS 752GB                           | 2         | 2      | 0.42%   |
| Seagate ST3250318AS 250GB                           | 2         | 2      | 0.42%   |
| Seagate ST3250310AS 250GB                           | 2         | 2      | 0.42%   |
| Seagate ST31000524AS 1TB                            | 2         | 4      | 0.42%   |
| Seagate ST31000340NS 1TB                            | 2         | 3      | 0.42%   |
| Seagate ST2000LM007-1R8174 2TB                      | 2         | 3      | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 2      | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                      | 2         | 7      | 0.42%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 4      | 0.42%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 0.42%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2         | 2      | 0.42%   |
| Seagate ST1000DX001-1NS162 1TB                      | 2         | 3      | 0.42%   |
| Seagate ST1000DM003-9YN162 1TB                      | 2         | 3      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 178    | 27.29%  |
| WDC                 | 111       | 127    | 24.24%  |
| Hitachi             | 35        | 38     | 7.64%   |
| HGST                | 34        | 34     | 7.42%   |
| Toshiba             | 32        | 35     | 6.99%   |
| Samsung Electronics | 32        | 37     | 6.99%   |
| Crucial             | 15        | 18     | 3.28%   |
| Kingston            | 13        | 13     | 2.84%   |
| Intel               | 12        | 14     | 2.62%   |
| SanDisk             | 10        | 13     | 2.18%   |
| SK Hynix            | 6         | 11     | 1.31%   |
| Micron Technology   | 5         | 7      | 1.09%   |
| A-DATA Technology   | 5         | 5      | 1.09%   |
| LITEON              | 3         | 3      | 0.66%   |
| Corsair             | 2         | 6      | 0.44%   |
| ASMT                | 2         | 6      | 0.44%   |
| Transcend           | 1         | 1      | 0.22%   |
| SPCC                | 1         | 1      | 0.22%   |
| Phison              | 1         | 2      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| OCZ                 | 1         | 1      | 0.22%   |
| MAXTOR              | 1         | 1      | 0.22%   |
| MaxDigital          | 1         | 1      | 0.22%   |
| LITEONIT            | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| Intenso             | 1         | 4      | 0.22%   |
| IM3D                | 1         | 1      | 0.22%   |
| Fujitsu             | 1         | 1      | 0.22%   |
| FASPEED             | 1         | 1      | 0.22%   |
| DREVO               | 1         | 1      | 0.22%   |
| Apple               | 1         | 1      | 0.22%   |
| Unknown             | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 124       | 175    | 35.13%  |
| WDC                 | 109       | 125    | 30.88%  |
| Hitachi             | 35        | 38     | 9.92%   |
| HGST                | 34        | 34     | 9.63%   |
| Toshiba             | 28        | 31     | 7.93%   |
| Samsung Electronics | 19        | 23     | 5.38%   |
| MAXTOR              | 1         | 1      | 0.28%   |
| MaxDigital          | 1         | 1      | 0.28%   |
| Fujitsu             | 1         | 1      | 0.28%   |
| ASMT                | 1         | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 334       | 430    | 76.61%  |
| SSD  | 88        | 119    | 20.18%  |
| NVMe | 14        | 16     | 3.21%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 7.14%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 7.14%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 7.14%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 7.14%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 7.14%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 7.14%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 7.14%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 7.14%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 7.14%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 7.14%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 7.14%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 7.14%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 28.57%  |
| Seagate             | 4         | 5      | 28.57%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| Kingston            | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3044      | 6631   | 55.47%  |
| Works    | 2010      | 3930   | 36.63%  |
| Malfunc  | 420       | 565    | 7.65%   |
| Failed   | 14        | 15     | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3051      | 46.66%  |
| AMD                              | 1304      | 19.94%  |
| Samsung Electronics              | 715       | 10.93%  |
| Sandisk                          | 299       | 4.57%   |
| SK Hynix                         | 157       | 2.4%    |
| Phison Electronics               | 126       | 1.93%   |
| ASMedia Technology               | 124       | 1.9%    |
| Toshiba America Info Systems     | 102       | 1.56%   |
| Kingston Technology Company      | 87        | 1.33%   |
| Micron/Crucial Technology        | 65        | 0.99%   |
| Marvell Technology Group         | 63        | 0.96%   |
| Silicon Motion                   | 60        | 0.92%   |
| ADATA Technology                 | 60        | 0.92%   |
| JMicron Technology               | 52        | 0.8%    |
| Nvidia                           | 51        | 0.78%   |
| KIOXIA                           | 51        | 0.78%   |
| Micron Technology                | 38        | 0.58%   |
| Realtek Semiconductor            | 26        | 0.4%    |
| Union Memory (Shenzhen)          | 22        | 0.34%   |
| Lite-On Technology               | 14        | 0.21%   |
| Solid State Storage Technology   | 11        | 0.17%   |
| Apple                            | 9         | 0.14%   |
| VIA Technologies                 | 6         | 0.09%   |
| Shenzhen Longsys Electronics     | 6         | 0.09%   |
| Seagate Technology               | 6         | 0.09%   |
| LSI Logic / Symbios Logic        | 6         | 0.09%   |
| Silicon Image                    | 5         | 0.08%   |
| Lenovo                           | 5         | 0.08%   |
| Adaptec                          | 4         | 0.06%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Broadcom / LSI                   | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| OCZ Technology Group             | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1002      | 13.42%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 436       | 5.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 303       | 4.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 279       | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 219       | 2.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 214       | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 189       | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 137       | 1.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 132       | 1.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 132       | 1.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 123       | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 118       | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 118       | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 112       | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 112       | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 109       | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 104       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 92        | 1.23%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 90        | 1.21%   |
| Intel SSD 660P Series                                                                   | 90        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 90        | 1.21%   |
| Samsung NVMe SSD Controller 980                                                         | 89        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 89        | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 82        | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                                  | 72        | 0.96%   |
| Intel SATA Controller [RAID mode]                                                       | 69        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 66        | 0.88%   |
| Phison E12 NVMe Controller                                                              | 65        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 63        | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 60        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 56        | 0.75%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 52        | 0.7%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 50        | 0.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 49        | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 48        | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 48        | 0.64%   |
| KIOXIA Non-Volatile memory controller                                                   | 47        | 0.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 46        | 0.62%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 45        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 45        | 0.6%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 43        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 41        | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 41        | 0.55%   |
| Kingston Company A2000 NVMe SSD                                                         | 40        | 0.54%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 40        | 0.54%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 40        | 0.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39        | 0.52%   |
| AMD FCH SATA Controller D                                                               | 39        | 0.52%   |
| SK Hynix BC511                                                                          | 38        | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 38        | 0.51%   |
| Micron Non-Volatile memory controller                                                   | 38        | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 36        | 0.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 36        | 0.48%   |
| AMD X370 Series Chipset SATA Controller                                                 | 36        | 0.48%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 35        | 0.47%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 34        | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 34        | 0.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 34        | 0.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 33        | 0.44%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 32        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3842      | 59.47%  |
| NVMe | 1863      | 28.84%  |
| IDE  | 409       | 6.33%   |
| RAID | 331       | 5.12%   |
| SAS  | 12        | 0.19%   |
| SCSI | 3         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3403      | 69.07%  |
| AMD    | 1523      | 30.91%  |
| ARM    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 99        | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 77        | 1.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 64        | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 63        | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 63        | 1.28%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 62        | 1.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 58        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 58        | 1.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 56        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 49        | 0.99%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 48        | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 46        | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 43        | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 38        | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 37        | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 37        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 36        | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 36        | 0.73%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 35        | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 35        | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 30        | 0.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 29        | 0.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 28        | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 27        | 0.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 26        | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 25        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.51%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 25        | 0.51%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 25        | 0.51%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 24        | 0.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 24        | 0.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 24        | 0.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 23        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 23        | 0.47%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 22        | 0.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 21        | 0.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.43%   |
| AMD FX-8350 Eight-Core Processor              | 21        | 0.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 20        | 0.41%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 20        | 0.41%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 20        | 0.41%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 19        | 0.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 19        | 0.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 19        | 0.38%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 19        | 0.38%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 19        | 0.38%   |
| AMD FX-6300 Six-Core Processor                | 19        | 0.38%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 18        | 0.36%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 18        | 0.36%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 18        | 0.36%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 18        | 0.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 17        | 0.34%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 17        | 0.34%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 17        | 0.34%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 17        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 1162      | 23.55%  |
| Intel Core i7                  | 1108      | 22.46%  |
| AMD Ryzen 5                    | 504       | 10.21%  |
| AMD Ryzen 7                    | 387       | 7.84%   |
| Intel Core i3                  | 329       | 6.67%   |
| Intel Celeron                  | 155       | 3.14%   |
| Other                          | 148       | 3%      |
| Intel Core 2 Duo               | 120       | 2.43%   |
| Intel Pentium                  | 105       | 2.13%   |
| Intel Xeon                     | 96        | 1.95%   |
| AMD FX                         | 90        | 1.82%   |
| AMD Ryzen 9                    | 89        | 1.8%    |
| AMD Ryzen 3                    | 75        | 1.52%   |
| Intel Atom                     | 39        | 0.79%   |
| Intel Pentium Dual-Core        | 38        | 0.77%   |
| Intel Core i9                  | 33        | 0.67%   |
| AMD A8                         | 33        | 0.67%   |
| AMD A10                        | 32        | 0.65%   |
| AMD A4                         | 31        | 0.63%   |
| AMD Ryzen 7 PRO                | 28        | 0.57%   |
| AMD Phenom II X4               | 25        | 0.51%   |
| AMD A6                         | 24        | 0.49%   |
| Intel Core 2 Quad              | 22        | 0.45%   |
| AMD Ryzen Threadripper         | 22        | 0.45%   |
| Intel Core 2                   | 18        | 0.36%   |
| AMD E1                         | 17        | 0.34%   |
| AMD E                          | 16        | 0.32%   |
| AMD Athlon II X2               | 16        | 0.32%   |
| AMD Athlon                     | 13        | 0.26%   |
| AMD Athlon 64 X2               | 12        | 0.24%   |
| AMD Phenom II X6               | 11        | 0.22%   |
| Intel Pentium Silver           | 10        | 0.2%    |
| Intel Genuine                  | 9         | 0.18%   |
| AMD Ryzen 5 PRO                | 9         | 0.18%   |
| Intel Pentium Gold             | 8         | 0.16%   |
| AMD E2                         | 8         | 0.16%   |
| AMD Athlon X4                  | 8         | 0.16%   |
| AMD Athlon II X4               | 8         | 0.16%   |
| Intel Core m3                  | 6         | 0.12%   |
| AMD Turion 64 X2 Mobile        | 6         | 0.12%   |
| AMD Phenom                     | 6         | 0.12%   |
| Intel Pentium Dual             | 5         | 0.1%    |
| AMD A12                        | 5         | 0.1%    |
| Intel Pentium D                | 4         | 0.08%   |
| AMD Athlon II X3               | 4         | 0.08%   |
| Intel Core m5                  | 3         | 0.06%   |
| AMD Sempron                    | 3         | 0.06%   |
| AMD Phenom II X2               | 3         | 0.06%   |
| AMD Athlon X2                  | 3         | 0.06%   |
| Intel Core m7                  | 2         | 0.04%   |
| Intel Core M                   | 2         | 0.04%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.04%   |
| AMD Turion II                  | 2         | 0.04%   |
| AMD Ryzen 3 PRO                | 2         | 0.04%   |
| AMD Phenom II                  | 2         | 0.04%   |
| AMD Athlon II Dual-Core        | 2         | 0.04%   |
| Intel Celeron Dual-Core        | 1         | 0.02%   |
| AMD V120                       | 1         | 0.02%   |
| AMD Turion 64 Mobile           | 1         | 0.02%   |
| AMD Ryzen Embedded             | 1         | 0.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1891      | 38.34%  |
| 2       | 1642      | 33.29%  |
| 6       | 717       | 14.54%  |
| 8       | 477       | 9.67%   |
| 12      | 70        | 1.42%   |
| 16      | 40        | 0.81%   |
| 3       | 37        | 0.75%   |
| 1       | 37        | 0.75%   |
| 10      | 9         | 0.18%   |
| 32      | 4         | 0.08%   |
| 24      | 3         | 0.06%   |
| Unknown | 3         | 0.06%   |
| 20      | 1         | 0.02%   |
| 14      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4910      | 99.65%  |
| 2      | 16        | 0.32%   |
| 4      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3659      | 74.17%  |
| 1       | 1271      | 25.77%  |
| Unknown | 3         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4831      | 97.91%  |
| Unknown        | 102       | 2.07%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2306      | 45.3%   |
| 0x306a9    | 180       | 3.54%   |
| 0x906ea    | 158       | 3.1%    |
| 0x306c3    | 140       | 2.75%   |
| 0x206a7    | 124       | 2.44%   |
| 0x806ea    | 108       | 2.12%   |
| 0x08701021 | 104       | 2.04%   |
| 0x806ec    | 102       | 2%      |
| 0x0800820d | 91        | 1.79%   |
| 0x806e9    | 84        | 1.65%   |
| 0x906e9    | 80        | 1.57%   |
| 0x506e3    | 75        | 1.47%   |
| 0x806c1    | 72        | 1.41%   |
| 0x406e3    | 72        | 1.41%   |
| 0x08701013 | 72        | 1.41%   |
| 0x40651    | 68        | 1.34%   |
| 0x08108102 | 62        | 1.22%   |
| 0x1067a    | 61        | 1.2%    |
| 0x306d4    | 55        | 1.08%   |
| 0x08108109 | 52        | 1.02%   |
| 0x08600106 | 49        | 0.96%   |
| 0x806eb    | 42        | 0.82%   |
| 0x08600103 | 42        | 0.82%   |
| 0x06000852 | 42        | 0.82%   |
| 0x706e5    | 41        | 0.81%   |
| 0x08600104 | 37        | 0.73%   |
| 0xa0652    | 35        | 0.69%   |
| 0x20655    | 28        | 0.55%   |
| 0x0a50000c | 27        | 0.53%   |
| 0x08001138 | 26        | 0.51%   |
| 0x010000c8 | 25        | 0.49%   |
| 0x0810100b | 24        | 0.47%   |
| 0x08600102 | 23        | 0.45%   |
| 0x06001119 | 22        | 0.43%   |
| 0x506c9    | 20        | 0.39%   |
| 0x406c4    | 19        | 0.37%   |
| 0x306f2    | 19        | 0.37%   |
| 0x30678    | 19        | 0.37%   |
| 0x08608103 | 19        | 0.37%   |
| 0x906ed    | 18        | 0.35%   |
| 0x706a1    | 18        | 0.35%   |
| 0x0a201009 | 18        | 0.35%   |
| 0x206d7    | 16        | 0.31%   |
| 0x106e5    | 16        | 0.31%   |
| 0x10676    | 16        | 0.31%   |
| 0x08001137 | 16        | 0.31%   |
| 0x06006705 | 15        | 0.29%   |
| 0x0a201016 | 13        | 0.26%   |
| 0x06003106 | 13        | 0.26%   |
| 0xa0655    | 12        | 0.24%   |
| 0x6fd      | 12        | 0.24%   |
| 0x0600611a | 12        | 0.24%   |
| 0x08101016 | 11        | 0.22%   |
| 0x806d1    | 9         | 0.18%   |
| 0x20652    | 9         | 0.18%   |
| 0x0a50000b | 9         | 0.18%   |
| 0x08001129 | 9         | 0.18%   |
| 0xa0660    | 8         | 0.16%   |
| 0x906eb    | 8         | 0.16%   |
| 0x6f6      | 8         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1025      | 20.79%  |
| Zen 2           | 467       | 9.47%   |
| Haswell         | 454       | 9.21%   |
| Zen+            | 345       | 7%      |
| IvyBridge       | 343       | 6.96%   |
| SandyBridge     | 307       | 6.23%   |
| Skylake         | 273       | 5.54%   |
| Zen             | 173       | 3.51%   |
| Penryn          | 163       | 3.31%   |
| Broadwell       | 128       | 2.6%    |
| Piledriver      | 120       | 2.43%   |
| Zen 3           | 115       | 2.33%   |
| CometLake       | 111       | 2.25%   |
| Westmere        | 103       | 2.09%   |
| TigerLake       | 103       | 2.09%   |
| Silvermont      | 96        | 1.95%   |
| K10             | 79        | 1.6%    |
| IceLake         | 75        | 1.52%   |
| Core            | 64        | 1.3%    |
| Excavator       | 54        | 1.1%    |
| Unknown         | 54        | 1.1%    |
| Goldmont plus   | 44        | 0.89%   |
| Nehalem         | 38        | 0.77%   |
| Goldmont        | 36        | 0.73%   |
| Bobcat          | 27        | 0.55%   |
| Steamroller     | 23        | 0.47%   |
| K8 Hammer       | 22        | 0.45%   |
| Jaguar          | 20        | 0.41%   |
| Puma            | 19        | 0.39%   |
| Bulldozer       | 15        | 0.3%    |
| K10 Llano       | 12        | 0.24%   |
| Bonnell         | 12        | 0.24%   |
| NetBurst        | 6         | 0.12%   |
| K8 & K10 hybrid | 5         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2569      | 42.53%  |
| Nvidia                     | 1980      | 32.78%  |
| AMD                        | 1485      | 24.58%  |
| ATI Technologies           | 3         | 0.05%   |
| ASPEED Technology          | 3         | 0.05%   |
| Matrox Electronics Systems | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 209       | 3.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 197       | 3.19%   |
| AMD Renoir                                                                               | 194       | 3.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 185       | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 174       | 2.82%   |
| Intel UHD Graphics 620                                                                   | 166       | 2.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 166       | 2.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 146       | 2.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 140       | 2.27%   |
| Intel HD Graphics 620                                                                    | 120       | 1.94%   |
| Intel HD Graphics 630                                                                    | 103       | 1.67%   |
| Intel HD Graphics 5500                                                                   | 102       | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 100       | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 89        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 78        | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 1.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 75        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 71        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 70        | 1.13%   |
| Intel HD Graphics 530                                                                    | 69        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 60        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 60        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 59        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 58        | 0.94%   |
| AMD Cezanne                                                                              | 57        | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 52        | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 50        | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 49        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 47        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 47        | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 46        | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 45        | 0.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 43        | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 41        | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 40        | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 37        | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 37        | 0.6%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 37        | 0.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 35        | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 35        | 0.57%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 35        | 0.57%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 34        | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 33        | 0.53%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.53%   |
| Nvidia TU117M                                                                            | 32        | 0.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 31        | 0.5%    |
| AMD Lucienne                                                                             | 31        | 0.5%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 30        | 0.49%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 29        | 0.47%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 29        | 0.47%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 0.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 29        | 0.47%   |
| Intel Iris Plus Graphics G7                                                              | 28        | 0.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 27        | 0.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 27        | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 26        | 0.42%   |
| Intel HD Graphics 500                                                                    | 26        | 0.42%   |
| Nvidia GM108M [GeForce MX130]                                                            | 25        | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1600      | 32.25%  |
| 1 x AMD            | 1185      | 23.89%  |
| 1 x Nvidia         | 1043      | 21.02%  |
| Intel + Nvidia     | 795       | 16.02%  |
| AMD + Nvidia       | 118       | 2.38%   |
| Intel + AMD        | 115       | 2.32%   |
| 2 x AMD            | 74        | 1.49%   |
| 2 x Nvidia         | 24        | 0.48%   |
| 1 x ASPEED         | 3         | 0.06%   |
| Other              | 1         | 0.02%   |
| 1 x Matrox         | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3616      | 72.65%  |
| Proprietary | 1349      | 27.1%   |
| Unknown     | 12        | 0.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3065      | 61.07%  |
| 1.01-2.0   | 470       | 9.36%   |
| 0.01-0.5   | 327       | 6.52%   |
| 7.01-8.0   | 325       | 6.48%   |
| 3.01-4.0   | 303       | 6.04%   |
| 0.51-1.0   | 223       | 4.44%   |
| 5.01-6.0   | 195       | 3.89%   |
| 8.01-16.0  | 57        | 1.14%   |
| 2.01-3.0   | 48        | 0.96%   |
| 16.01-24.0 | 4         | 0.08%   |
| 4.01-5.0   | 2         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 626       | 10.8%   |
| AU Optronics            | 611       | 10.54%  |
| LG Display              | 535       | 9.23%   |
| Chimei Innolux          | 501       | 8.65%   |
| BOE                     | 489       | 8.44%   |
| Goldstar                | 365       | 6.3%    |
| Dell                    | 316       | 5.45%   |
| Acer                    | 227       | 3.92%   |
| Ancor Communications    | 178       | 3.07%   |
| BenQ                    | 169       | 2.92%   |
| AOC                     | 164       | 2.83%   |
| Hewlett-Packard         | 152       | 2.62%   |
| Philips                 | 134       | 2.31%   |
| Sharp                   | 122       | 2.11%   |
| Lenovo                  | 98        | 1.69%   |
| Apple                   | 88        | 1.52%   |
| PANDA                   | 76        | 1.31%   |
| LG Electronics          | 71        | 1.23%   |
| Chi Mei Optoelectronics | 67        | 1.16%   |
| ViewSonic               | 66        | 1.14%   |
| ASUSTek Computer        | 54        | 0.93%   |
| Iiyama                  | 46        | 0.79%   |
| Unknown                 | 36        | 0.62%   |
| Sony                    | 33        | 0.57%   |
| InfoVision              | 30        | 0.52%   |
| Panasonic               | 20        | 0.35%   |
| Vizio                   | 19        | 0.33%   |
| Eizo                    | 18        | 0.31%   |
| LGD                     | 17        | 0.29%   |
| NEC Computers           | 16        | 0.28%   |
| Fujitsu Siemens         | 16        | 0.28%   |
| Sceptre Tech            | 15        | 0.26%   |
| AUS                     | 15        | 0.26%   |
| MSI                     | 14        | 0.24%   |
| CSO                     | 14        | 0.24%   |
| LG Philips              | 13        | 0.22%   |
| Toshiba                 | 12        | 0.21%   |
| Medion                  | 12        | 0.21%   |
| HannStar                | 12        | 0.21%   |
| Unknown                 | 11        | 0.19%   |
| Idek Iiyama             | 10        | 0.17%   |
| CPT                     | 10        | 0.17%   |
| Vestel Elektronik       | 9         | 0.16%   |
| TMX                     | 9         | 0.16%   |
| Pixio                   | 7         | 0.12%   |
| Microstep               | 7         | 0.12%   |
| Packard Bell            | 6         | 0.1%    |
| Insignia                | 6         | 0.1%    |
| Gigabyte Technology     | 6         | 0.1%    |
| Denver                  | 6         | 0.1%    |
| Belinea                 | 6         | 0.1%    |
| Vestel                  | 5         | 0.09%   |
| UGD                     | 5         | 0.09%   |
| RTK                     | 5         | 0.09%   |
| KTC                     | 5         | 0.09%   |
| IBM                     | 5         | 0.09%   |
| Gateway                 | 5         | 0.09%   |
| TCL                     | 4         | 0.07%   |
| Plain Tree Systems      | 4         | 0.07%   |
| Pioneer                 | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 36        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 34        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 30        | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 25        | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 24        | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 24        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 22        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.33%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch               | 18        | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 16        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 16        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 15        | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.23%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 13        | 0.22%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 12        | 0.2%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 12        | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 12        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.18%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 11        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 11        | 0.18%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                       | 11        | 0.18%   |
| Unknown                                                                  | 11        | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 10        | 0.17%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch              | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 10        | 0.17%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 10        | 0.17%   |
| AOC 24E1W1 AOC2401 1920x1080 527x296mm 23.8-inch                         | 10        | 0.17%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 9         | 0.15%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.15%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 9         | 0.15%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 9         | 0.15%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 9         | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 9         | 0.15%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 9         | 0.15%   |
| Goldstar Ultra HD GSM5B09 3780x2160 600x340mm 27.2-inch                  | 9         | 0.15%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 9         | 0.15%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 9         | 0.15%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 9         | 0.15%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 9         | 0.15%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 9         | 0.15%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 9         | 0.15%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 9         | 0.15%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                        | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO572D 1920x1080 293x165mm 13.2-inch           | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch           | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 9         | 0.15%   |
| AU Optronics LCD Monitor 1920x1080                                       | 9         | 0.15%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                         | 9         | 0.15%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                          | 9         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2647      | 48.13%  |
| 1366x768 (WXGA)    | 852       | 15.49%  |
| 3840x2160 (4K)     | 361       | 6.56%   |
| 2560x1440 (QHD)    | 289       | 5.25%   |
| 1600x900 (HD+)     | 179       | 3.25%   |
| 1680x1050 (WSXGA+) | 130       | 2.36%   |
| Unknown            | 121       | 2.2%    |
| 1920x1200 (WUXGA)  | 115       | 2.09%   |
| 1280x1024 (SXGA)   | 114       | 2.07%   |
| 1440x900 (WXGA+)   | 106       | 1.93%   |
| 2560x1080          | 77        | 1.4%    |
| 1280x800 (WXGA)    | 71        | 1.29%   |
| 3440x1440          | 58        | 1.05%   |
| 3840x1080          | 53        | 0.96%   |
| 1360x768           | 36        | 0.65%   |
| 2560x1600          | 31        | 0.56%   |
| 2880x1800          | 18        | 0.33%   |
| 2160x1440          | 17        | 0.31%   |
| 1920x540           | 15        | 0.27%   |
| 3840x2400          | 14        | 0.25%   |
| 3200x1800 (QHD+)   | 13        | 0.24%   |
| 1280x720 (HD)      | 9         | 0.16%   |
| 4480x1440          | 8         | 0.15%   |
| 3840x1600          | 8         | 0.15%   |
| 2736x1824          | 8         | 0.15%   |
| 1024x768 (XGA)     | 8         | 0.15%   |
| 3456x2160          | 7         | 0.13%   |
| 1600x1200          | 7         | 0.13%   |
| 5760x2160          | 6         | 0.11%   |
| 5760x1080          | 6         | 0.11%   |
| 3600x1080          | 5         | 0.09%   |
| 3286x1080          | 5         | 0.09%   |
| 3200x2000          | 5         | 0.09%   |
| 2256x1504          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 3200x1080          | 4         | 0.07%   |
| 3000x2000          | 4         | 0.07%   |
| 2880x1920          | 4         | 0.07%   |
| 6400x2160          | 3         | 0.05%   |
| 5120x1440          | 3         | 0.05%   |
| 3840x1200          | 3         | 0.05%   |
| 3360x1080          | 3         | 0.05%   |
| 2240x1400          | 3         | 0.05%   |
| 1400x1050          | 3         | 0.05%   |
| 1024x600           | 3         | 0.05%   |
| 7680x1080          | 2         | 0.04%   |
| 6400x1440          | 2         | 0.04%   |
| 4240x1440          | 2         | 0.04%   |
| 3520x1080          | 2         | 0.04%   |
| 3360x1050          | 2         | 0.04%   |
| 2880x900           | 2         | 0.04%   |
| 2720x1024          | 2         | 0.04%   |
| 2560x1700          | 2         | 0.04%   |
| 2160x1200          | 2         | 0.04%   |
| 2048x1152          | 2         | 0.04%   |
| 1280x768           | 2         | 0.04%   |
| 800x1280           | 1         | 0.02%   |
| 7680x2160          | 1         | 0.02%   |
| 7680x1440          | 1         | 0.02%   |
| 720x1280           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1460      | 25.58%  |
| 13      | 537       | 9.41%   |
| 24      | 451       | 7.9%    |
| 27      | 442       | 7.74%   |
| 14      | 439       | 7.69%   |
| Unknown | 420       | 7.36%   |
| 23      | 363       | 6.36%   |
| 21      | 312       | 5.47%   |
| 17      | 250       | 4.38%   |
| 19      | 127       | 2.23%   |
| 31      | 118       | 2.07%   |
| 34      | 109       | 1.91%   |
| 22      | 84        | 1.47%   |
| 12      | 84        | 1.47%   |
| 18      | 77        | 1.35%   |
| 20      | 71        | 1.24%   |
| 11      | 53        | 0.93%   |
| 84      | 45        | 0.79%   |
| 32      | 25        | 0.44%   |
| 25      | 24        | 0.42%   |
| 54      | 23        | 0.4%    |
| 16      | 19        | 0.33%   |
| 72      | 18        | 0.32%   |
| 40      | 13        | 0.23%   |
| 26      | 13        | 0.23%   |
| 49      | 12        | 0.21%   |
| 37      | 11        | 0.19%   |
| 48      | 9         | 0.16%   |
| 43      | 9         | 0.16%   |
| 28      | 9         | 0.16%   |
| 65      | 8         | 0.14%   |
| 33      | 8         | 0.14%   |
| 39      | 6         | 0.11%   |
| 10      | 6         | 0.11%   |
| 46      | 5         | 0.09%   |
| 42      | 5         | 0.09%   |
| 35      | 5         | 0.09%   |
| 74      | 4         | 0.07%   |
| 52      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |
| 64      | 3         | 0.05%   |
| 47      | 3         | 0.05%   |
| 38      | 3         | 0.05%   |
| 75      | 2         | 0.04%   |
| 60      | 2         | 0.04%   |
| 55      | 2         | 0.04%   |
| 41      | 2         | 0.04%   |
| 36      | 2         | 0.04%   |
| 8       | 2         | 0.04%   |
| 69      | 1         | 0.02%   |
| 59      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2192      | 39.37%  |
| 501-600     | 1136      | 20.41%  |
| 401-500     | 594       | 10.67%  |
| Unknown     | 420       | 7.54%   |
| 201-300     | 409       | 7.35%   |
| 351-400     | 309       | 5.55%   |
| 601-700     | 168       | 3.02%   |
| 701-800     | 142       | 2.55%   |
| 1501-2000   | 70        | 1.26%   |
| 1001-1500   | 70        | 1.26%   |
| 801-900     | 39        | 0.7%    |
| 901-1000    | 16        | 0.29%   |
| 101-200     | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3858      | 75.84%  |
| 16/10   | 489       | 9.61%   |
| Unknown | 379       | 7.45%   |
| 21/9    | 123       | 2.42%   |
| 5/4     | 107       | 2.1%    |
| 3/2     | 69        | 1.36%   |
| 4/3     | 34        | 0.67%   |
| 32/9    | 14        | 0.28%   |
| 6/5     | 6         | 0.12%   |
| 0.62    | 3         | 0.06%   |
| 3.40    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.80    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1463      | 25.87%  |
| 201-250        | 973       | 17.2%   |
| 81-90          | 747       | 13.21%  |
| 301-350        | 450       | 7.96%   |
| Unknown        | 420       | 7.43%   |
| 351-500        | 273       | 4.83%   |
| 151-200        | 269       | 4.76%   |
| 71-80          | 233       | 4.12%   |
| 121-130        | 176       | 3.11%   |
| 251-300        | 168       | 2.97%   |
| More than 1000 | 123       | 2.17%   |
| 141-150        | 102       | 1.8%    |
| 61-70          | 72        | 1.27%   |
| 501-1000       | 68        | 1.2%    |
| 51-60          | 54        | 0.95%   |
| 131-140        | 34        | 0.6%    |
| 91-100         | 13        | 0.23%   |
| 111-120        | 10        | 0.18%   |
| 41-50          | 6         | 0.11%   |
| 1-40           | 2         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1648      | 30.16%  |
| 121-160       | 1568      | 28.69%  |
| 101-120       | 1268      | 23.2%   |
| Unknown       | 420       | 7.69%   |
| 161-240       | 320       | 5.86%   |
| More than 240 | 146       | 2.67%   |
| 1-50          | 95        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3918      | 78.13%  |
| 2     | 928       | 18.5%   |
| 3     | 114       | 2.27%   |
| 0     | 47        | 0.94%   |
| 4     | 8         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2771      | 37.59%  |
| Intel                                  | 2528      | 34.29%  |
| Qualcomm Atheros                       | 802       | 10.88%  |
| Broadcom                               | 319       | 4.33%   |
| Ralink Technology                      | 105       | 1.42%   |
| TP-Link                                | 87        | 1.18%   |
| Broadcom Limited                       | 73        | 0.99%   |
| Ralink                                 | 60        | 0.81%   |
| Marvell Technology Group               | 50        | 0.68%   |
| Nvidia                                 | 38        | 0.52%   |
| Microsoft                              | 37        | 0.5%    |
| MEDIATEK                               | 37        | 0.5%    |
| Xiaomi                                 | 33        | 0.45%   |
| Samsung Electronics                    | 28        | 0.38%   |
| Qualcomm Atheros Communications        | 27        | 0.37%   |
| Aquantia                               | 23        | 0.31%   |
| Huawei Technologies                    | 21        | 0.28%   |
| Sierra Wireless                        | 20        | 0.27%   |
| ASUSTek Computer                       | 20        | 0.27%   |
| ASIX Electronics                       | 20        | 0.27%   |
| D-Link                                 | 19        | 0.26%   |
| Dell                                   | 18        | 0.24%   |
| NetGear                                | 16        | 0.22%   |
| Lenovo                                 | 15        | 0.2%    |
| Linksys                                | 14        | 0.19%   |
| DisplayLink                            | 14        | 0.19%   |
| JMicron Technology                     | 13        | 0.18%   |
| Qualcomm                               | 11        | 0.15%   |
| Edimax Technology                      | 11        | 0.15%   |
| Hewlett-Packard                        | 10        | 0.14%   |
| Ericsson Business Mobile Networks      | 10        | 0.14%   |
| D-Link System                          | 7         | 0.09%   |
| ZyXEL Communications                   | 6         | 0.08%   |
| Microchip Technology                   | 6         | 0.08%   |
| Google                                 | 6         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.07%   |
| Fibocom                                | 5         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.05%   |
| SEGGER                                 | 4         | 0.05%   |
| Motorola PCS                           | 4         | 0.05%   |
| Mellanox Technologies                  | 4         | 0.05%   |
| Apple                                  | 4         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 4         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.04%   |
| T & A Mobile Phones                    | 3         | 0.04%   |
| InterBiometrics                        | 3         | 0.04%   |
| IMC Networks                           | 3         | 0.04%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| OPPO Electronics                       | 2         | 0.03%   |
| OnePlus                                | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| Mercucys                               | 2         | 0.03%   |
| Input Club                             | 2         | 0.03%   |
| ICS Advent                             | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Foxconn / Hon Hai                      | 2         | 0.03%   |
| Belkin Components                      | 2         | 0.03%   |
| Attansic Technology                    | 2         | 0.03%   |
| Arduino SA                             | 2         | 0.03%   |
| ZyDAS                                  | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1997      | 23.16%  |
| Intel Wi-Fi 6 AX200                                               | 367       | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 298       | 3.46%   |
| Intel I211 Gigabit Network Connection                             | 223       | 2.59%   |
| Intel Wireless 8265 / 8275                                        | 183       | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 162       | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 147       | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 126       | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 122       | 1.41%   |
| Intel Wireless 7265                                               | 119       | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 114       | 1.32%   |
| Intel Wireless 7260                                               | 114       | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 111       | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 102       | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 100       | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 98        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 94        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 94        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 86        | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 85        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 84        | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 82        | 0.95%   |
| Intel Wireless 8260                                               | 80        | 0.93%   |
| Intel Wireless 3165                                               | 79        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 78        | 0.9%    |
| Intel Wireless-AC 9260                                            | 76        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 69        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 65        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 57        | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 56        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 52        | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 50        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 47        | 0.54%   |
| Intel Wireless 3160                                               | 44        | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 44        | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 43        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 39        | 0.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 38        | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 36        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 36        | 0.42%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 35        | 0.41%   |
| Intel Centrino Wireless-N 2230                                    | 35        | 0.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 34        | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 33        | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33        | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.38%   |
| Ralink MT7601U Wireless Adapter                                   | 32        | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 0.37%   |
| Broadcom BCM43142 802.11b/g/n                                     | 31        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 30        | 0.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 30        | 0.35%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 28        | 0.32%   |
| Realtek 802.11ac NIC                                              | 27        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.31%   |
| Qualcomm Atheros AR9271 802.11n                                   | 27        | 0.31%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 27        | 0.31%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 26        | 0.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1957      | 48.29%  |
| Realtek Semiconductor                 | 676       | 16.68%  |
| Qualcomm Atheros                      | 626       | 15.45%  |
| Broadcom                              | 233       | 5.75%   |
| Ralink Technology                     | 105       | 2.59%   |
| TP-Link                               | 81        | 2%      |
| Ralink                                | 60        | 1.48%   |
| Broadcom Limited                      | 54        | 1.33%   |
| Microsoft                             | 34        | 0.84%   |
| MEDIATEK                              | 31        | 0.76%   |
| Qualcomm Atheros Communications       | 27        | 0.67%   |
| Sierra Wireless                       | 20        | 0.49%   |
| ASUSTek Computer                      | 20        | 0.49%   |
| D-Link                                | 19        | 0.47%   |
| NetGear                               | 16        | 0.39%   |
| Marvell Technology Group              | 14        | 0.35%   |
| Dell                                  | 14        | 0.35%   |
| Linksys                               | 13        | 0.32%   |
| Edimax Technology                     | 11        | 0.27%   |
| ZyXEL Communications                  | 6         | 0.15%   |
| D-Link System                         | 5         | 0.12%   |
| Fibocom                               | 4         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.1%    |
| Qualcomm                              | 3         | 0.07%   |
| IMC Networks                          | 3         | 0.07%   |
| Hewlett-Packard                       | 3         | 0.07%   |
| Mercucys                              | 2         | 0.05%   |
| Belkin Components                     | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 367       | 8.98%   |
| Intel Wireless 8265 / 8275                                     | 183       | 4.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 147       | 3.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 126       | 3.08%   |
| Intel Wireless 7265                                            | 119       | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 114       | 2.79%   |
| Intel Wireless 7260                                            | 114       | 2.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 102       | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 100       | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 98        | 2.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 94        | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 94        | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 86        | 2.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 84        | 2.06%   |
| Intel Wi-Fi 6 AX201                                            | 82        | 2.01%   |
| Intel Wireless 8260                                            | 80        | 1.96%   |
| Intel Wireless 3165                                            | 79        | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 78        | 1.91%   |
| Intel Wireless-AC 9260                                         | 76        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 69        | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 65        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 57        | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 52        | 1.27%   |
| Intel Wireless 3160                                            | 44        | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 43        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 38        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 36        | 0.88%   |
| Intel Centrino Wireless-N 2230                                 | 35        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 34        | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 33        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 33        | 0.81%   |
| Ralink MT7601U Wireless Adapter                                | 32        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 31        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 30        | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 28        | 0.69%   |
| Realtek 802.11ac NIC                                           | 27        | 0.66%   |
| Qualcomm Atheros AR9271 802.11n                                | 27        | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 27        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 26        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 25        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 25        | 0.61%   |
| Intel Centrino Advanced-N 6235                                 | 24        | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                            | 23        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                 | 21        | 0.51%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 21        | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 20        | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 20        | 0.49%   |
| Ralink RT5370 Wireless Adapter                                 | 19        | 0.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 18        | 0.44%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 18        | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 17        | 0.42%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 0.42%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 17        | 0.42%   |
| Intel Centrino Advanced-N 6200                                 | 16        | 0.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 15        | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 14        | 0.34%   |
| Intel WiFi Link 5100                                           | 14        | 0.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 14        | 0.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 14        | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2516      | 57.42%  |
| Intel                                  | 1169      | 26.68%  |
| Qualcomm Atheros                       | 243       | 5.55%   |
| Broadcom                               | 127       | 2.9%    |
| Nvidia                                 | 38        | 0.87%   |
| Marvell Technology Group               | 36        | 0.82%   |
| Xiaomi                                 | 31        | 0.71%   |
| Samsung Electronics                    | 27        | 0.62%   |
| Aquantia                               | 23        | 0.52%   |
| Broadcom Limited                       | 22        | 0.5%    |
| ASIX Electronics                       | 20        | 0.46%   |
| Lenovo                                 | 15        | 0.34%   |
| DisplayLink                            | 14        | 0.32%   |
| JMicron Technology                     | 13        | 0.3%    |
| Huawei Technologies                    | 12        | 0.27%   |
| Qualcomm                               | 7         | 0.16%   |
| TP-Link                                | 6         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.11%   |
| MediaTek                               | 5         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.09%   |
| Mellanox Technologies                  | 4         | 0.09%   |
| Google                                 | 4         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.07%   |
| Microsoft                              | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| T & A Mobile Phones                    | 2         | 0.05%   |
| Spreadtrum Communications              | 2         | 0.05%   |
| OPPO Electronics                       | 2         | 0.05%   |
| National Semiconductor                 | 2         | 0.05%   |
| ICS Advent                             | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| Foxconn / Hon Hai                      | 2         | 0.05%   |
| D-Link System                          | 2         | 0.05%   |
| Attansic Technology                    | 2         | 0.05%   |
| VIA Technologies                       | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| MosChip Semiconductor                  | 1         | 0.02%   |
| Microchip Technology                   | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HTC (High Tech Computer)               | 1         | 0.02%   |
| Accton Technology                      | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1997      | 44.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 298       | 6.67%   |
| Intel I211 Gigabit Network Connection                             | 223       | 4.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 162       | 3.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 122       | 2.73%   |
| Intel Ethernet Connection (2) I219-V                              | 111       | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 85        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 56        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 50        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 47        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 44        | 0.98%   |
| Intel Ethernet Connection (2) I218-V                              | 39        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 36        | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 35        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 30        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 25        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 25        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 21        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 21        | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.47%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18        | 0.4%    |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17        | 0.38%   |
| Nvidia MCP61 Ethernet                                             | 16        | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 16        | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 15        | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 15        | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 14        | 0.31%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13        | 0.29%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.29%   |
| Intel 82567LM Gigabit Network Connection                          | 13        | 0.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.27%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 12        | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12        | 0.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11        | 0.25%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 11        | 0.25%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.25%   |
| Intel Ethernet Connection (11) I219-V                             | 11        | 0.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 9         | 0.2%    |
| Nvidia MCP79 Ethernet                                             | 9         | 0.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 8         | 0.18%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 7         | 0.16%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 7         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4150      | 51.58%  |
| WiFi     | 3828      | 47.58%  |
| Modem    | 55        | 0.68%   |
| Unknown  | 12        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3233      | 53.63%  |
| Ethernet | 2792      | 46.32%  |
| Modem    | 2         | 0.03%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2601      | 52.58%  |
| 1     | 2182      | 44.11%  |
| 3     | 102       | 2.06%   |
| 0     | 48        | 0.97%   |
| 4     | 7         | 0.14%   |
| 5     | 5         | 0.1%    |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4372      | 87.62%  |
| Yes  | 618       | 12.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1635      | 51.01%  |
| Realtek Semiconductor           | 328       | 10.23%  |
| Qualcomm Atheros Communications | 263       | 8.21%   |
| Cambridge Silicon Radio         | 252       | 7.86%   |
| IMC Networks                    | 119       | 3.71%   |
| Broadcom                        | 119       | 3.71%   |
| Lite-On Technology              | 106       | 3.31%   |
| Apple                           | 88        | 2.75%   |
| ASUSTek Computer                | 81        | 2.53%   |
| Foxconn / Hon Hai               | 48        | 1.5%    |
| Realtek                         | 29        | 0.9%    |
| Ralink                          | 20        | 0.62%   |
| Dell                            | 19        | 0.59%   |
| Hewlett-Packard                 | 13        | 0.41%   |
| Marvell Semiconductor           | 11        | 0.34%   |
| Toshiba                         | 10        | 0.31%   |
| Foxconn International           | 8         | 0.25%   |
| Ralink Technology               | 6         | 0.19%   |
| MediaTek                        | 6         | 0.19%   |
| Dynex                           | 5         | 0.16%   |
| Belkin Components               | 5         | 0.16%   |
| Opticis                         | 4         | 0.12%   |
| HTC (High Tech Computer)        | 4         | 0.12%   |
| Conwise Technology              | 4         | 0.12%   |
| Askey Computer                  | 4         | 0.12%   |
| Alps Electric                   | 4         | 0.12%   |
| TP-Link                         | 2         | 0.06%   |
| SINO WEALTH                     | 2         | 0.06%   |
| Integrated System Solution      | 2         | 0.06%   |
| Fujitsu                         | 2         | 0.06%   |
| Edimax Technology               | 2         | 0.06%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 574       | 17.88%  |
| Intel AX200 Bluetooth                                    | 345       | 10.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 271       | 8.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 252       | 7.85%   |
| Intel Bluetooth Device                                   | 195       | 6.07%   |
| Realtek Bluetooth Radio                                  | 192       | 5.98%   |
| Qualcomm Atheros  Bluetooth Device                       | 132       | 4.11%   |
| Realtek  Bluetooth 4.2 Adapter                           | 97        | 3.02%   |
| Intel Wireless-AC 3168 Bluetooth                         | 90        | 2.8%    |
| Lite-On Bluetooth Device                                 | 75        | 2.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 71        | 2.21%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 51        | 1.59%   |
| IMC Networks Bluetooth Radio                             | 51        | 1.59%   |
| Apple Bluetooth USB Host Controller                      | 45        | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 37        | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 33        | 1.03%   |
| IMC Networks Bluetooth Device                            | 33        | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 33        | 1.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 32        | 1%      |
| Realtek Bluetooth Radio                                  | 29        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                        | 29        | 0.9%    |
| Intel AX210 Bluetooth                                    | 26        | 0.81%   |
| Apple Bluetooth Host Controller                          | 26        | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                       | 25        | 0.78%   |
| Ralink RT3290 Bluetooth                                  | 20        | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 16        | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 16        | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 15        | 0.47%   |
| Realtek RTL8821A Bluetooth                               | 13        | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                         | 13        | 0.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 13        | 0.4%    |
| ASUS Bluetooth Radio                                     | 13        | 0.4%    |
| ASUS Bluetooth Adapter                                   | 11        | 0.34%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 11        | 0.34%   |
| Realtek RTL8723B Bluetooth                               | 10        | 0.31%   |
| IMC Networks Wireless_Device                             | 10        | 0.31%   |
| Broadcom BCM2045B (BDC-2.1)                              | 10        | 0.31%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 9         | 0.28%   |
| Broadcom HP Portable SoftSailing                         | 9         | 0.28%   |
| ASUS BCM20702A0                                          | 9         | 0.28%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 8         | 0.25%   |
| Foxconn International BCM43142A0 Bluetooth module        | 8         | 0.25%   |
| Dell BCM20702A0 Bluetooth Module                         | 8         | 0.25%   |
| Marvell Bluetooth and Wireless LAN Composite             | 7         | 0.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 7         | 0.22%   |
| Toshiba Bluetooth Device                                 | 6         | 0.19%   |
| Lite-On Qualcomm Atheros Bluetooth                       | 6         | 0.19%   |
| HP Broadcom 2070 Bluetooth Combo                         | 6         | 0.19%   |
| Foxconn / Hon Hai BCM20702A0                             | 6         | 0.19%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter             | 5         | 0.16%   |
| MediaTek Wireless_Device                                 | 5         | 0.16%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device             | 5         | 0.16%   |
| IMC Networks Bluetooth USB Host Controller               | 5         | 0.16%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 5         | 0.16%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 5         | 0.16%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                     | 5         | 0.16%   |
| ASUS Qualcomm Bluetooth 4.1                              | 5         | 0.16%   |
| ASUS ASUS USB-BT500                                      | 5         | 0.16%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                | 5         | 0.16%   |
| Qualcomm Atheros AR3012 Bluetooth                        | 4         | 0.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 3313      | 45.49%  |
| AMD                                             | 1754      | 24.08%  |
| Nvidia                                          | 1297      | 17.81%  |
| C-Media Electronics                             | 154       | 2.11%   |
| Logitech                                        | 68        | 0.93%   |
| Creative Labs                                   | 54        | 0.74%   |
| Kingston Technology                             | 42        | 0.58%   |
| JMTek                                           | 39        | 0.54%   |
| Texas Instruments                               | 36        | 0.49%   |
| Realtek Semiconductor                           | 32        | 0.44%   |
| SteelSeries ApS                                 | 28        | 0.38%   |
| Corsair                                         | 28        | 0.38%   |
| Generalplus Technology                          | 25        | 0.34%   |
| Focusrite-Novation                              | 25        | 0.34%   |
| Plantronics                                     | 24        | 0.33%   |
| Creative Technology                             | 23        | 0.32%   |
| Blue Microphones                                | 21        | 0.29%   |
| Razer USA                                       | 20        | 0.27%   |
| GN Netcom                                       | 18        | 0.25%   |
| Lenovo                                          | 16        | 0.22%   |
| BEHRINGER International                         | 13        | 0.18%   |
| ASUSTek Computer                                | 13        | 0.18%   |
| Sennheiser Communications                       | 11        | 0.15%   |
| Samson Technologies                             | 11        | 0.15%   |
| Sony                                            | 10        | 0.14%   |
| GYROCOM C&C                                     | 10        | 0.14%   |
| M-Audio                                         | 9         | 0.12%   |
| Apple                                           | 9         | 0.12%   |
| VIA Technologies                                | 7         | 0.1%    |
| Turtle Beach                                    | 7         | 0.1%    |
| SAVITECH                                        | 7         | 0.1%    |
| RODE Microphones                                | 7         | 0.1%    |
| Yamaha                                          | 6         | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 6         | 0.08%   |
| Astro Gaming                                    | 6         | 0.08%   |
| Dell                                            | 5         | 0.07%   |
| Cambridge Silicon Radio                         | 5         | 0.07%   |
| XMOS                                            | 4         | 0.05%   |
| Valve Software                                  | 4         | 0.05%   |
| Huawei Technologies                             | 4         | 0.05%   |
| Giga-Byte Technology                            | 4         | 0.05%   |
| Audio-Technica                                  | 4         | 0.05%   |
| Arturia                                         | 4         | 0.05%   |
| Tenx Technology                                 | 3         | 0.04%   |
| Microsoft                                       | 3         | 0.04%   |
| Micro Star International                        | 3         | 0.04%   |
| Licensed by Sony Computer Entertainment America | 3         | 0.04%   |
| FiiO Electronics Technology                     | 3         | 0.04%   |
| Elite Silicon                                   | 3         | 0.04%   |
| Bose                                            | 3         | 0.04%   |
| Barco Display Systems                           | 3         | 0.04%   |
| Audient                                         | 3         | 0.04%   |
| USB MICROPHONE                                  | 2         | 0.03%   |
| Trust                                           | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]                | 2         | 0.03%   |
| Roland                                          | 2         | 0.03%   |
| Pioneer DJ                                      | 2         | 0.03%   |
| OPPO Electronics                                | 2         | 0.03%   |
| Microchip Technology                            | 2         | 0.03%   |
| Hewlett-Packard                                 | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 548       | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 430       | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 341       | 3.89%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 308       | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 272       | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 257       | 2.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 254       | 2.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 238       | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 238       | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 219       | 2.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 197       | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 171       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 150       | 1.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 150       | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 150       | 1.71%   |
| Intel 8 Series HD Audio Controller                                                                | 144       | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 143       | 1.63%   |
| AMD FCH Azalia Controller                                                                         | 129       | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 123       | 1.4%    |
| Intel Broadwell-U Audio Controller                                                                | 121       | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 120       | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 120       | 1.37%   |
| Intel 200 Series PCH HD Audio                                                                     | 116       | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 115       | 1.31%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 110       | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 103       | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 99        | 1.13%   |
| AMD Navi 10 HDMI Audio                                                                            | 94        | 1.07%   |
| Intel CM238 HD Audio Controller                                                                   | 88        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 78        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 76        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 75        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 74        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 72        | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 68        | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 65        | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 64        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 64        | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 64        | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 63        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 62        | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 60        | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 58        | 0.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 52        | 0.59%   |
| Nvidia TU104 HD Audio Controller                                                                  | 51        | 0.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 44        | 0.5%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 44        | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 43        | 0.49%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 39        | 0.44%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 39        | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 38        | 0.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 38        | 0.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 38        | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 37        | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 35        | 0.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 35        | 0.4%    |
| AMD Trinity HDMI Audio Controller                                                                 | 35        | 0.4%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 34        | 0.39%   |
| Nvidia High Definition Audio Controller                                                           | 33        | 0.38%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 33        | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 834       | 22.84%  |
| SK Hynix                     | 557       | 15.26%  |
| Kingston                     | 446       | 12.22%  |
| Micron Technology            | 338       | 9.26%   |
| Corsair                      | 276       | 7.56%   |
| Unknown                      | 264       | 7.23%   |
| Crucial                      | 224       | 6.14%   |
| G.Skill                      | 210       | 5.75%   |
| A-DATA Technology            | 89        | 2.44%   |
| Ramaxel Technology           | 65        | 1.78%   |
| Elpida                       | 47        | 1.29%   |
| Patriot                      | 37        | 1.01%   |
| Team                         | 35        | 0.96%   |
| Nanya Technology             | 35        | 0.96%   |
| Unknown (ABCD)               | 22        | 0.6%    |
| Smart                        | 20        | 0.55%   |
| GOODRAM                      | 19        | 0.52%   |
| Transcend                    | 15        | 0.41%   |
| Apacer                       | 9         | 0.25%   |
| AMD                          | 8         | 0.22%   |
| ASint Technology             | 7         | 0.19%   |
| Kllisre                      | 6         | 0.16%   |
| Unknown                      | 6         | 0.16%   |
| Silicon Power                | 5         | 0.14%   |
| PNY                          | 4         | 0.11%   |
| Teikon                       | 3         | 0.08%   |
| SMART Brazil                 | 3         | 0.08%   |
| Qumo                         | 3         | 0.08%   |
| Neo Forza                    | 3         | 0.08%   |
| Kingmax                      | 3         | 0.08%   |
| GeIL                         | 3         | 0.08%   |
| CSX                          | 3         | 0.08%   |
| Avant                        | 3         | 0.08%   |
| Atermiter                    | 3         | 0.08%   |
| Qimonda                      | 2         | 0.05%   |
| Patriot Memory               | 2         | 0.05%   |
| Goldkey                      | 2         | 0.05%   |
| Wilk Elektronik              | 1         | 0.03%   |
| V-Color                      | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |
| Unknown (0xAD44594E45540000) | 1         | 0.03%   |
| Unknown (0x8551)             | 1         | 0.03%   |
| Unknown (0x0416)             | 1         | 0.03%   |
| Unknown (0x02BA)             | 1         | 0.03%   |
| Unknown (08C8)               | 1         | 0.03%   |
| Unknown (08B5)               | 1         | 0.03%   |
| Unknown (08AE)               | 1         | 0.03%   |
| Unifosa                      | 1         | 0.03%   |
| TwinMOS                      | 1         | 0.03%   |
| Thermaltake                  | 1         | 0.03%   |
| Super Talent                 | 1         | 0.03%   |
| Smart Modular                | 1         | 0.03%   |
| SHARETRONIC                  | 1         | 0.03%   |
| SemsoTai                     | 1         | 0.03%   |
| S                            | 1         | 0.03%   |
| RZX                          | 1         | 0.03%   |
| Ramsta                       | 1         | 0.03%   |
| Puskill                      | 1         | 0.03%   |
| PRINCETON                    | 1         | 0.03%   |
| Patriot Memory (PDP Systems) | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 54        | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 51        | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 35        | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 35        | 0.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 35        | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 33        | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 31        | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 30        | 0.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 30        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 24        | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 23        | 0.59%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.56%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 22        | 0.56%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s           | 19        | 0.48%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 18        | 0.46%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 18        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 18        | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 16        | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 16        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 15        | 0.38%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 15        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.38%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.36%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 14        | 0.36%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 14        | 0.36%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 14        | 0.36%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 14        | 0.36%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 14        | 0.36%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.33%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 13        | 0.33%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.31%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.31%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 12        | 0.31%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.28%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.28%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 11        | 0.28%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 11        | 0.28%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 11        | 0.28%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.25%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.25%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.25%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 10        | 0.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.25%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 10        | 0.25%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 9         | 0.23%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s               | 9         | 0.23%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 9         | 0.23%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 9         | 0.23%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 0.23%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 9         | 0.23%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 9         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1753      | 55.47%  |
| DDR3    | 964       | 30.51%  |
| LPDDR4  | 116       | 3.67%   |
| LPDDR3  | 102       | 3.23%   |
| Unknown | 76        | 2.41%   |
| DDR2    | 69        | 2.18%   |
| SDRAM   | 65        | 2.06%   |
| DDR     | 13        | 0.41%   |
| DRAM    | 2         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1704      | 54.2%   |
| DIMM         | 1167      | 37.12%  |
| Row Of Chips | 248       | 7.89%   |
| Chip         | 15        | 0.48%   |
| Unknown      | 7         | 0.22%   |
| FB-DIMM      | 3         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1493      | 43.49%  |
| 4096  | 1021      | 29.74%  |
| 16384 | 457       | 13.31%  |
| 2048  | 314       | 9.15%   |
| 32768 | 81        | 2.36%   |
| 1024  | 62        | 1.81%   |
| 512   | 5         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 665       | 19.24%  |
| 2667    | 635       | 18.37%  |
| 3200    | 506       | 14.64%  |
| 2400    | 296       | 8.56%   |
| 2133    | 200       | 5.79%   |
| 1333    | 181       | 5.24%   |
| 3600    | 122       | 3.53%   |
| 1334    | 89        | 2.57%   |
| 1867    | 84        | 2.43%   |
| 3466    | 71        | 2.05%   |
| 800     | 55        | 1.59%   |
| 4267    | 54        | 1.56%   |
| 3266    | 54        | 1.56%   |
| 667     | 45        | 1.3%    |
| 3000    | 40        | 1.16%   |
| 2933    | 30        | 0.87%   |
| 1866    | 29        | 0.84%   |
| Unknown | 29        | 0.84%   |
| 1067    | 27        | 0.78%   |
| 3733    | 24        | 0.69%   |
| 4199    | 23        | 0.67%   |
| 1066    | 19        | 0.55%   |
| 3400    | 18        | 0.52%   |
| 2666    | 13        | 0.38%   |
| 3800    | 12        | 0.35%   |
| 4266    | 10        | 0.29%   |
| 2048    | 10        | 0.29%   |
| 2800    | 9         | 0.26%   |
| 975     | 9         | 0.26%   |
| 3533    | 8         | 0.23%   |
| 1800    | 8         | 0.23%   |
| 333     | 7         | 0.2%    |
| 3067    | 6         | 0.17%   |
| 3866    | 5         | 0.14%   |
| 3500    | 4         | 0.12%   |
| 3100    | 4         | 0.12%   |
| 533     | 4         | 0.12%   |
| 400     | 4         | 0.12%   |
| 49926   | 3         | 0.09%   |
| 3666    | 3         | 0.09%   |
| 3334    | 3         | 0.09%   |
| 3066    | 3         | 0.09%   |
| 1639    | 3         | 0.09%   |
| 4000    | 2         | 0.06%   |
| 3333    | 2         | 0.06%   |
| 3151    | 2         | 0.06%   |
| 933     | 2         | 0.06%   |
| 65535   | 1         | 0.03%   |
| 57535   | 1         | 0.03%   |
| 5354    | 1         | 0.03%   |
| 4400    | 1         | 0.03%   |
| 4133    | 1         | 0.03%   |
| 3734    | 1         | 0.03%   |
| 3020    | 1         | 0.03%   |
| 3007    | 1         | 0.03%   |
| 2747    | 1         | 0.03%   |
| 2733    | 1         | 0.03%   |
| 2600    | 1         | 0.03%   |
| 2187    | 1         | 0.03%   |
| 2176    | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 45        | 41.28%  |
| Brother Industries    | 21        | 19.27%  |
| Seiko Epson           | 11        | 10.09%  |
| Canon                 | 9         | 8.26%   |
| Samsung Electronics   | 8         | 7.34%   |
| Xerox                 | 2         | 1.83%   |
| Prolific Technology   | 2         | 1.83%   |
| Pantum                | 2         | 1.83%   |
| Dymo-CoStar           | 2         | 1.83%   |
| Xiaomi                | 1         | 0.92%   |
| Sagem                 | 1         | 0.92%   |
| QinHeng Electronics   | 1         | 0.92%   |
| Oki Data              | 1         | 0.92%   |
| Lexmark International | 1         | 0.92%   |
| Kyocera               | 1         | 0.92%   |
| Apple                 | 1         | 0.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                               | 3         | 2.73%   |
| HP LaserJet 1300                                       | 3         | 2.73%   |
| HP ENVY 4520 series                                    | 3         | 2.73%   |
| Xerox Phaser 3020                                      | 2         | 1.82%   |
| Seiko Epson L120 Series                                | 2         | 1.82%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.82%   |
| HP Officejet 2620 series                               | 2         | 1.82%   |
| HP DeskJet 2130 series                                 | 2         | 1.82%   |
| HP Color LaserJet Pro M453-4                           | 2         | 1.82%   |
| Brother MFC-L2710DW series                             | 2         | 1.82%   |
| Brother HL-L2300D series                               | 2         | 1.82%   |
| Brother HL-5370DW series                               | 2         | 1.82%   |
| Xiaomi MiMouse 2                                       | 1         | 0.91%   |
| Seiko Epson Stylus NX230/SX235W Series                 | 1         | 0.91%   |
| Seiko Epson Printer                                    | 1         | 0.91%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.91%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]           | 1         | 0.91%   |
| Seiko Epson L805 Series                                | 1         | 0.91%   |
| Seiko Epson L365 Series                                | 1         | 0.91%   |
| Seiko Epson L355 Series                                | 1         | 0.91%   |
| Seiko Epson ET-4760 Series                             | 1         | 0.91%   |
| Seiko Epson ET-3850 Series                             | 1         | 0.91%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.91%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.91%   |
| Samsung ML-1865                                        | 1         | 0.91%   |
| Samsung ML-1660 Series                                 | 1         | 0.91%   |
| Samsung ML-1640 Series Laser Printer                   | 1         | 0.91%   |
| Samsung M2020 Series                                   | 1         | 0.91%   |
| Samsung CLX-3300 Series                                | 1         | 0.91%   |
| Samsung CLX-3180 Series                                | 1         | 0.91%   |
| Samsung CLP-310 Color Laser Printer                    | 1         | 0.91%   |
| Sagem Laser Pro LL                                     | 1         | 0.91%   |
| QinHeng CH340S                                         | 1         | 0.91%   |
| Pantum P2500W series                                   | 1         | 0.91%   |
| Pantum M6500 series                                    | 1         | 0.91%   |
| Oki Data USB Device                                    | 1         | 0.91%   |
| Lexmark International Lexmark MS312dn                  | 1         | 0.91%   |
| Kyocera FS-1030D printer                               | 1         | 0.91%   |
| HP OfficeJet Pro 8020 series                           | 1         | 0.91%   |
| HP Officejet 4500 G510g-m                              | 1         | 0.91%   |
| HP LaserJet P2015 series                               | 1         | 0.91%   |
| HP LaserJet P1102                                      | 1         | 0.91%   |
| HP LaserJet P1005                                      | 1         | 0.91%   |
| HP LaserJet 200 colorMFP M276nw                        | 1         | 0.91%   |
| HP LaserJet 1020                                       | 1         | 0.91%   |
| HP LaserJet 1012                                       | 1         | 0.91%   |
| HP LaserJet 1010                                       | 1         | 0.91%   |
| HP Ink Tank Wireless 410 series                        | 1         | 0.91%   |
| HP Ink Tank 310 series                                 | 1         | 0.91%   |
| HP Ink Tank 110 series                                 | 1         | 0.91%   |
| HP ENVY Photo 7100 series                              | 1         | 0.91%   |
| HP ENVY 6000 series                                    | 1         | 0.91%   |
| HP ENVY 5000 series                                    | 1         | 0.91%   |
| HP ENVY 4500 series                                    | 1         | 0.91%   |
| HP DeskJet Plus 4100 series                            | 1         | 0.91%   |
| HP Deskjet F4500 series                                | 1         | 0.91%   |
| HP DeskJet F4200 series                                | 1         | 0.91%   |
| HP DeskJet F4100 Printer series                        | 1         | 0.91%   |
| HP DeskJet F2492 All-in-One                            | 1         | 0.91%   |
| HP DeskJet F2100 Printer series                        | 1         | 0.91%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 17        | 62.96%  |
| Seiko Epson        | 5         | 18.52%  |
| Hewlett-Packard    | 2         | 7.41%   |
| Visioneer          | 1         | 3.7%    |
| Ultima Electronics | 1         | 3.7%    |
| AGFA-Gevaert NV    | 1         | 3.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 5         | 18.52%  |
| Canon CanoScan LiDE 220                                                               | 4         | 14.81%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 7.41%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 7.41%   |
| Canon CanoScan LIDE 25                                                                | 2         | 7.41%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.7%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.7%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.7%    |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.7%    |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.7%    |
| HP ScanJet 3500c                                                                      | 1         | 3.7%    |
| HP ScanJet 3400cse                                                                    | 1         | 3.7%    |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.7%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.7%    |
| Canon CanoScan LiDE 200                                                               | 1         | 3.7%    |
| Canon CanoScan LiDE 120                                                               | 1         | 3.7%    |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 641       | 20.51%  |
| IMC Networks                           | 356       | 11.39%  |
| Realtek Semiconductor                  | 237       | 7.58%   |
| Acer                                   | 235       | 7.52%   |
| Microdia                               | 231       | 7.39%   |
| Logitech                               | 216       | 6.91%   |
| Quanta                                 | 145       | 4.64%   |
| Sunplus Innovation Technology          | 144       | 4.61%   |
| Cheng Uei Precision Industry (Foxlink) | 121       | 3.87%   |
| Syntek                                 | 95        | 3.04%   |
| Lite-On Technology                     | 94        | 3.01%   |
| Suyin                                  | 81        | 2.59%   |
| Apple                                  | 78        | 2.5%    |
| Microsoft                              | 52        | 1.66%   |
| Silicon Motion                         | 50        | 1.6%    |
| Alcor Micro                            | 40        | 1.28%   |
| Samsung Electronics                    | 34        | 1.09%   |
| Luxvisions Innotech Limited            | 26        | 0.83%   |
| Z-Star Microelectronics                | 21        | 0.67%   |
| Ricoh                                  | 14        | 0.45%   |
| Lenovo                                 | 13        | 0.42%   |
| Creative Technology                    | 13        | 0.42%   |
| Importek                               | 11        | 0.35%   |
| MacroSilicon                           | 9         | 0.29%   |
| Primax Electronics                     | 8         | 0.26%   |
| LG Electronics                         | 8         | 0.26%   |
| Genesys Logic                          | 8         | 0.26%   |
| GEMBIRD                                | 8         | 0.26%   |
| Google                                 | 7         | 0.22%   |
| Unknown                                | 6         | 0.19%   |
| Generalplus Technology                 | 6         | 0.19%   |
| Cubeternet                             | 6         | 0.19%   |
| webcam                                 | 5         | 0.16%   |
| Sonix Technology                       | 5         | 0.16%   |
| KYE Systems (Mouse Systems)            | 5         | 0.16%   |
| DigiTech                               | 5         | 0.16%   |
| Denron                                 | 5         | 0.16%   |
| ARC International                      | 5         | 0.16%   |
| ALi                                    | 5         | 0.16%   |
| Valve Software                         | 4         | 0.13%   |
| OmniVision Technologies                | 4         | 0.13%   |
| Intel                                  | 4         | 0.13%   |
| Aveo Technology                        | 4         | 0.13%   |
| Arkmicro Technologies                  | 4         | 0.13%   |
| Xiongmai                               | 3         | 0.1%    |
| SHENZHEN EMEET TECHNOLOGY              | 3         | 0.1%    |
| Pixart Imaging                         | 3         | 0.1%    |
| Huawei Technologies                    | 3         | 0.1%    |
| WCM_USB                                | 2         | 0.06%   |
| SunplusIT                              | 2         | 0.06%   |
| Solid Year                             | 2         | 0.06%   |
| SJ-180517-N                            | 2         | 0.06%   |
| Razer USA                              | 2         | 0.06%   |
| Panasonic (Matsushita)                 | 2         | 0.06%   |
| Novatel Wireless                       | 2         | 0.06%   |
| Jieli Technology                       | 2         | 0.06%   |
| Holitech                               | 2         | 0.06%   |
| AVerMedia Technologies                 | 2         | 0.06%   |
| YGTek                                  | 1         | 0.03%   |
| Xiaomi                                 | 1         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 149       | 4.73%   |
| IMC Networks Integrated Camera                          | 119       | 3.77%   |
| Microdia Integrated_Webcam_HD                           | 101       | 3.2%    |
| Realtek Integrated_Webcam_HD                            | 83        | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 77        | 2.44%   |
| Acer Integrated Camera                                  | 74        | 2.35%   |
| Chicony HD WebCam                                       | 73        | 2.32%   |
| Syntek Integrated Camera                                | 66        | 2.09%   |
| Sunplus Integrated_Webcam_HD                            | 55        | 1.74%   |
| Logitech Webcam C270                                    | 55        | 1.74%   |
| Logitech HD Pro Webcam C920                             | 37        | 1.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 35        | 1.11%   |
| Samsung Galaxy A5 (MTP)                                 | 34        | 1.08%   |
| Lite-On Integrated Camera                               | 34        | 1.08%   |
| Chicony HP HD Camera                                    | 29        | 0.92%   |
| Acer HD Webcam                                          | 27        | 0.86%   |
| Apple iPhone 5/5C/5S/6/SE                               | 26        | 0.82%   |
| Acer Lenovo EasyCamera                                  | 25        | 0.79%   |
| Chicony HP Wide Vision HD Camera                        | 24        | 0.76%   |
| Quanta HP TrueVision HD Camera                          | 23        | 0.73%   |
| Microsoft LifeCam HD-3000                               | 23        | 0.73%   |
| Chicony USB2.0 Camera                                   | 23        | 0.73%   |
| Acer EasyCamera                                         | 22        | 0.7%    |
| Quanta HD WebCam                                        | 21        | 0.67%   |
| Quanta HD User Facing                                   | 21        | 0.67%   |
| Realtek USB2.0 HD UVC WebCam                            | 20        | 0.63%   |
| Lite-On HP HD Camera                                    | 20        | 0.63%   |
| IMC Networks HD Camera                                  | 20        | 0.63%   |
| Chicony EasyCamera                                      | 20        | 0.63%   |
| Acer SunplusIT Integrated Camera                        | 20        | 0.63%   |
| Acer BisonCam, NB Pro                                   | 20        | 0.63%   |
| Chicony Lenovo EasyCamera                               | 19        | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                            | 18        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 18        | 0.57%   |
| Syntek Lenovo EasyCamera                                | 17        | 0.54%   |
| Sunplus HD WebCam                                       | 17        | 0.54%   |
| Chicony Integrated Camera (1280x720@30)                 | 17        | 0.54%   |
| Chicony HP TrueVision HD                                | 17        | 0.54%   |
| Realtek Integrated Webcam                               | 16        | 0.51%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 16        | 0.51%   |
| Microdia Integrated Webcam                              | 16        | 0.51%   |
| Lite-On HP Wide Vision HD Camera                        | 16        | 0.51%   |
| Apple FaceTime HD Camera (Built-in)                     | 16        | 0.51%   |
| Realtek USB Camera                                      | 15        | 0.48%   |
| IMC Networks HP TrueVision HD Camera                    | 15        | 0.48%   |
| Chicony HD User Facing                                  | 15        | 0.48%   |
| Chicony FJ Camera                                       | 15        | 0.48%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 15        | 0.48%   |
| Apple FaceTime HD Camera                                | 15        | 0.48%   |
| Realtek HD WebCam                                       | 14        | 0.44%   |
| Microdia Webcam Vitade AF                               | 14        | 0.44%   |
| IMC Networks EasyCamera                                 | 14        | 0.44%   |
| Chicony TOSHIBA Web Camera - HD                         | 14        | 0.44%   |
| Chicony HP Webcam                                       | 14        | 0.44%   |
| Suyin HP TrueVision HD                                  | 13        | 0.41%   |
| Quanta HP Wide Vision HD Camera                         | 13        | 0.41%   |
| Chicony HP TrueVision HD Camera                         | 13        | 0.41%   |
| Chicony HP HD Webcam                                    | 13        | 0.41%   |
| Realtek Lenovo EasyCamera                               | 12        | 0.38%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 12        | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 200       | 30.63%  |
| Validity Sensors           | 185       | 28.33%  |
| Shenzhen Goodix Technology | 127       | 19.45%  |
| Elan Microelectronics      | 53        | 8.12%   |
| LighTuning Technology      | 30        | 4.59%   |
| Upek                       | 25        | 3.83%   |
| AuthenTec                  | 17        | 2.6%    |
| STMicroelectronics         | 6         | 0.92%   |
| Samsung Electronics        | 5         | 0.77%   |
| Focal-systems.Corp         | 2         | 0.31%   |
| HOLTEK                     | 1         | 0.15%   |
| Futronic Technology        | 1         | 0.15%   |
| DigitalPersona             | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 74        | 11.33%  |
| Shenzhen Goodix  Fingerprint Device                                        | 54        | 8.27%   |
| Shenzhen Goodix Fingerprint Reader                                         | 52        | 7.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 42        | 6.43%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 6.28%   |
| Elan ELAN:Fingerprint                                                      | 41        | 6.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 3.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 23        | 3.52%   |
| Synaptics  WBDI                                                            | 21        | 3.22%   |
| Shenzhen Goodix FingerPrint                                                | 21        | 3.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 20        | 3.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 19        | 2.91%   |
| Validity Sensors Synaptics WBDI                                            | 18        | 2.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 2.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 2.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 1.84%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 1.84%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.84%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.68%   |
| Validity Sensors VFS491                                                    | 9         | 1.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 1.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.07%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 0.92%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.92%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.61%   |
| Synaptics WBDI Device                                                      | 4         | 0.61%   |
| AuthenTec AES2810                                                          | 4         | 0.61%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.46%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.46%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.46%   |
| AuthenTec AES1600                                                          | 3         | 0.46%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.31%   |
| Samsung Fingerprint Device                                                 | 2         | 0.31%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.31%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.31%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.31%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.15%   |
| Futronic FS81 Fingerprint Scanner Module                                   | 1         | 0.15%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.15%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 64        | 32.82%  |
| Alcor Micro                       | 64        | 32.82%  |
| Lenovo                            | 15        | 7.69%   |
| O2 Micro                          | 14        | 7.18%   |
| Upek                              | 12        | 6.15%   |
| Yubico.com                        | 7         | 3.59%   |
| Gemalto (was Gemplus)             | 5         | 2.56%   |
| Realtek Semiconductor             | 3         | 1.54%   |
| VASCO Data Security International | 2         | 1.03%   |
| OmniKey                           | 2         | 1.03%   |
| SCM Microsystems                  | 1         | 0.51%   |
| Reiner SCT Kartensysteme          | 1         | 0.51%   |
| Hewlett-Packard                   | 1         | 0.51%   |
| Clay Logic                        | 1         | 0.51%   |
| Cherry                            | 1         | 0.51%   |
| C3PO                              | 1         | 0.51%   |
| BIT4ID                            | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 63        | 32.31%  |
| Broadcom BCM5880 Secure Applications Processor                               | 24        | 12.31%  |
| Broadcom 5880                                                                | 19        | 9.74%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 6.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.64%   |
| Broadcom 58200                                                               | 10        | 5.13%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 3.59%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.54%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.54%   |
| OmniKey 3x21 Smart Card Reader                                               | 2         | 1.03%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.51%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.51%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.51%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.51%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.51%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.51%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.51%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.51%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.51%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.51%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.51%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3520      | 70.26%  |
| 1     | 1224      | 24.43%  |
| 2     | 242       | 4.83%   |
| 3     | 23        | 0.46%   |
| 4     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 643       | 37.32%  |
| Graphics card            | 304       | 17.64%  |
| Net/wireless             | 227       | 13.17%  |
| Chipcard                 | 170       | 9.87%   |
| Multimedia controller    | 112       | 6.5%    |
| Camera                   | 58        | 3.37%   |
| Net/ethernet             | 46        | 2.67%   |
| Unassigned class         | 37        | 2.15%   |
| Bluetooth                | 35        | 2.03%   |
| Sound                    | 19        | 1.1%    |
| Communication controller | 17        | 0.99%   |
| Storage                  | 16        | 0.93%   |
| Card reader              | 10        | 0.58%   |
| Dvb card                 | 9         | 0.52%   |
| Network                  | 8         | 0.46%   |
| Storage/raid             | 4         | 0.23%   |
| Modem                    | 4         | 0.23%   |
| Storage/ide              | 2         | 0.12%   |
| Video                    | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |

