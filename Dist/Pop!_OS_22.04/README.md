Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 981

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5520               | Notebook    | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [4d0f459190](https://linux-hardware.org/?probe=4d0f459190) | Aug 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [d73365fe3e](https://linux-hardware.org/?probe=d73365fe3e) | Jul 31, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [98e8e717df](https://linux-hardware.org/?probe=98e8e717df) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [b2c0846cf5](https://linux-hardware.org/?probe=b2c0846cf5) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| EVGA          | 134-KS-E377                 | Desktop     | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Dell          | 0TP412                      | Desktop     | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [773e4afb47](https://linux-hardware.org/?probe=773e4afb47) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | Notebook    | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| HP            | 2215                        | Desktop     | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| PC Special... | NS50MU                      | Notebook    | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [a6c7b90642](https://linux-hardware.org/?probe=a6c7b90642) | Jul 29, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | Notebook    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | Notebook    | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | Desktop     | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | Desktop     | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [830913d1ab](https://linux-hardware.org/?probe=830913d1ab) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | Notebook    | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7c25b2c2c7](https://linux-hardware.org/?probe=7c25b2c2c7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [97bbabec13](https://linux-hardware.org/?probe=97bbabec13) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | Desktop     | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | Notebook    | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cfb18dd008](https://linux-hardware.org/?probe=cfb18dd008) | Jul 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [04ae47501b](https://linux-hardware.org/?probe=04ae47501b) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [023ff9a691](https://linux-hardware.org/?probe=023ff9a691) | Jul 25, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [447f8a06ea](https://linux-hardware.org/?probe=447f8a06ea) | Jul 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| System76      | Lemur Pro                   | Notebook    | [c6269208fe](https://linux-hardware.org/?probe=c6269208fe) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [8c5e11fe0e](https://linux-hardware.org/?probe=8c5e11fe0e) | Jul 25, 2022 |
| Dynabook      | Satellite Pro C50D-B        | Notebook    | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [ac0f2b51c0](https://linux-hardware.org/?probe=ac0f2b51c0) | Jul 25, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [03bb89eced](https://linux-hardware.org/?probe=03bb89eced) | Jul 24, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [970f226406](https://linux-hardware.org/?probe=970f226406) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d41e7515af](https://linux-hardware.org/?probe=d41e7515af) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fdada0c3a6](https://linux-hardware.org/?probe=fdada0c3a6) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [147556bf0a](https://linux-hardware.org/?probe=147556bf0a) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [752155f862](https://linux-hardware.org/?probe=752155f862) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [95c9916b84](https://linux-hardware.org/?probe=95c9916b84) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| ASUSTek       | K93SM                       | Notebook    | [add292129b](https://linux-hardware.org/?probe=add292129b) | Jul 22, 2022 |
| Samsung       | 760XDA                      | Notebook    | [c3e04193b8](https://linux-hardware.org/?probe=c3e04193b8) | Jul 22, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [4763ba77ba](https://linux-hardware.org/?probe=4763ba77ba) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [da25f9d9b4](https://linux-hardware.org/?probe=da25f9d9b4) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20d32236ad](https://linux-hardware.org/?probe=20d32236ad) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| Toshiba       | BLB                         | Notebook    | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [e73fa302e0](https://linux-hardware.org/?probe=e73fa302e0) | Jul 21, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [ed3f7b7f50](https://linux-hardware.org/?probe=ed3f7b7f50) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [c6dcb4ffa6](https://linux-hardware.org/?probe=c6dcb4ffa6) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Lenovo        | 3136 SDK0K17763 WIN 1801... | Mini pc     | [fd1c3f77f0](https://linux-hardware.org/?probe=fd1c3f77f0) | Jul 20, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [f5675c45dc](https://linux-hardware.org/?probe=f5675c45dc) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0cee82005e](https://linux-hardware.org/?probe=0cee82005e) | Jul 19, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| Dell          | Latitude D430               | Notebook    | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [df814add04](https://linux-hardware.org/?probe=df814add04) | Jul 18, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [2baa51bbc9](https://linux-hardware.org/?probe=2baa51bbc9) | Jul 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b903541b55](https://linux-hardware.org/?probe=b903541b55) | Jul 18, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [219d908f50](https://linux-hardware.org/?probe=219d908f50) | Jul 17, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e423ccf90d](https://linux-hardware.org/?probe=e423ccf90d) | Jul 17, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e02de9c624](https://linux-hardware.org/?probe=e02de9c624) | Jul 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [515f269efc](https://linux-hardware.org/?probe=515f269efc) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | Desktop     | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| Gigabyte      | Blade Pro                   | Notebook    | [3c2576e897](https://linux-hardware.org/?probe=3c2576e897) | Jul 16, 2022 |
| MSI           | GS75 Stealth 9SG            | Notebook    | [8707f3e800](https://linux-hardware.org/?probe=8707f3e800) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Alienware     | 15 R2                       | Notebook    | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [61b03607fa](https://linux-hardware.org/?probe=61b03607fa) | Jul 15, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| Dell          | Precision M4600             | Notebook    | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | Desktop     | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| HP            | Laptop 17z-ca200            | Notebook    | [1159e9b888](https://linux-hardware.org/?probe=1159e9b888) | Jul 15, 2022 |
| System76      | Pangolin                    | Notebook    | [690b7b5984](https://linux-hardware.org/?probe=690b7b5984) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| Lenovo        | ThinkPad X230 2325YHU       | Notebook    | [4720a42a7f](https://linux-hardware.org/?probe=4720a42a7f) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [285e41f0aa](https://linux-hardware.org/?probe=285e41f0aa) | Jul 14, 2022 |
| Samsung       | 950XED                      | Notebook    | [b7f59889a0](https://linux-hardware.org/?probe=b7f59889a0) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [be07af7e99](https://linux-hardware.org/?probe=be07af7e99) | Jul 13, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | Notebook    | [b70dfefc75](https://linux-hardware.org/?probe=b70dfefc75) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7107c7c2eb](https://linux-hardware.org/?probe=7107c7c2eb) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| Dell          | Latitude 3500               | Notebook    | [f42f32c17f](https://linux-hardware.org/?probe=f42f32c17f) | Jul 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [9cc1538196](https://linux-hardware.org/?probe=9cc1538196) | Jul 12, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [f3ead95b28](https://linux-hardware.org/?probe=f3ead95b28) | Jul 12, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [0ce04e7b03](https://linux-hardware.org/?probe=0ce04e7b03) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [821459e114](https://linux-hardware.org/?probe=821459e114) | Jul 12, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [aedb7a18da](https://linux-hardware.org/?probe=aedb7a18da) | Jul 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| Dell          | Latitude 9420               | Convertible | [afe463abbf](https://linux-hardware.org/?probe=afe463abbf) | Jul 11, 2022 |
| Dell          | Latitude 9420               | Convertible | [e1f5e84d11](https://linux-hardware.org/?probe=e1f5e84d11) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| Lenovo        | 14w 81MQ0013AU              | Notebook    | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [1a9d6df3b5](https://linux-hardware.org/?probe=1a9d6df3b5) | Jul 11, 2022 |
| MSI           | P67A-C43                    | Desktop     | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| Dell          | Latitude E5440              | Notebook    | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [c39e03e656](https://linux-hardware.org/?probe=c39e03e656) | Jul 10, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [8f152d3669](https://linux-hardware.org/?probe=8f152d3669) | Jul 10, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [a885fd8b41](https://linux-hardware.org/?probe=a885fd8b41) | Jul 10, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [b1749f4194](https://linux-hardware.org/?probe=b1749f4194) | Jul 10, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [9b65b57a57](https://linux-hardware.org/?probe=9b65b57a57) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [9dc5c32b9f](https://linux-hardware.org/?probe=9dc5c32b9f) | Jul 09, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | Desktop     | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | Notebook    | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Dell          | Latitude E7450              | Notebook    | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| MSI           | MS-16G4                     | Notebook    | [53f40f3420](https://linux-hardware.org/?probe=53f40f3420) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [38e90a5b4d](https://linux-hardware.org/?probe=38e90a5b4d) | Jul 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [92eb60a700](https://linux-hardware.org/?probe=92eb60a700) | Jul 08, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [d4426d8840](https://linux-hardware.org/?probe=d4426d8840) | Jul 08, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| Panasonic     | CF-C2AQAZXLM                | Notebook    | [be9cf3127a](https://linux-hardware.org/?probe=be9cf3127a) | Jul 08, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [f9d5ea94ec](https://linux-hardware.org/?probe=f9d5ea94ec) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [9e40e3f8ad](https://linux-hardware.org/?probe=9e40e3f8ad) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| HP            | 3398                        | Desktop     | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| System76      | Lemur Pro                   | Notebook    | [bdc2ddb608](https://linux-hardware.org/?probe=bdc2ddb608) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [861d7b3714](https://linux-hardware.org/?probe=861d7b3714) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Pegatron      | H36FF                       | Notebook    | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Acer          | Aspire E3-112M              | Notebook    | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | Desktop     | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASUSTek       | Q405UA                      | Convertible | [4ca30672dc](https://linux-hardware.org/?probe=4ca30672dc) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [a194cebb73](https://linux-hardware.org/?probe=a194cebb73) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [90ccec43bf](https://linux-hardware.org/?probe=90ccec43bf) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [21b712ca64](https://linux-hardware.org/?probe=21b712ca64) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [ece534d446](https://linux-hardware.org/?probe=ece534d446) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [1c52419886](https://linux-hardware.org/?probe=1c52419886) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Dell          | Latitude 7280               | Notebook    | [b7ed5b72a9](https://linux-hardware.org/?probe=b7ed5b72a9) | Jul 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [2f88b6162e](https://linux-hardware.org/?probe=2f88b6162e) | Jul 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [abbd7fd848](https://linux-hardware.org/?probe=abbd7fd848) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [23da2ae018](https://linux-hardware.org/?probe=23da2ae018) | Jul 04, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [6f24a453bf](https://linux-hardware.org/?probe=6f24a453bf) | Jul 04, 2022 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [67d4a66421](https://linux-hardware.org/?probe=67d4a66421) | Jul 04, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [ad84993245](https://linux-hardware.org/?probe=ad84993245) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [a21d756ee1](https://linux-hardware.org/?probe=a21d756ee1) | Jul 03, 2022 |
| Notebook      | P65xHP                      | Notebook    | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Notebook    | [80c5bb3483](https://linux-hardware.org/?probe=80c5bb3483) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Acer          | Aspire E5-473G              | Notebook    | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8999ce3eca](https://linux-hardware.org/?probe=8999ce3eca) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [6e6839a1d0](https://linux-hardware.org/?probe=6e6839a1d0) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [949457a05f](https://linux-hardware.org/?probe=949457a05f) | Jul 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1b85081b50](https://linux-hardware.org/?probe=1b85081b50) | Jul 03, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [f437b1ee99](https://linux-hardware.org/?probe=f437b1ee99) | Jul 03, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [848a8591de](https://linux-hardware.org/?probe=848a8591de) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [a8c5e48dc8](https://linux-hardware.org/?probe=a8c5e48dc8) | Jul 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | Notebook    | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [516b60430c](https://linux-hardware.org/?probe=516b60430c) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [c70a95cfc1](https://linux-hardware.org/?probe=c70a95cfc1) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| HP            | 18E7                        | Desktop     | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| Dell          | Precision 7510              | Notebook    | [4831b50f9a](https://linux-hardware.org/?probe=4831b50f9a) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [6b1e1133e4](https://linux-hardware.org/?probe=6b1e1133e4) | Jul 01, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Dell          | Precision M4600             | Notebook    | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | Notebook    | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Samsung       | 930XED                      | Notebook    | [56a04fa69d](https://linux-hardware.org/?probe=56a04fa69d) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| Dell          | Precision 5530              | Notebook    | [d6dc0ecd91](https://linux-hardware.org/?probe=d6dc0ecd91) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [63508059d3](https://linux-hardware.org/?probe=63508059d3) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b7aef43e9e](https://linux-hardware.org/?probe=b7aef43e9e) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| HP            | 18E7                        | Desktop     | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | Precision 7510              | Notebook    | [c82cc3cb0f](https://linux-hardware.org/?probe=c82cc3cb0f) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [ab31abf1d5](https://linux-hardware.org/?probe=ab31abf1d5) | Jun 30, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Dell          | Latitude E5470              | Notebook    | [2440e59a5a](https://linux-hardware.org/?probe=2440e59a5a) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d403c021c](https://linux-hardware.org/?probe=6d403c021c) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| Eluktronic... | MECH-15 G3                  | Notebook    | [d307b13800](https://linux-hardware.org/?probe=d307b13800) | Jun 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c14a32dd6b](https://linux-hardware.org/?probe=c14a32dd6b) | Jun 28, 2022 |
| HP            | 3647h                       | Desktop     | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [843cbccc63](https://linux-hardware.org/?probe=843cbccc63) | Jun 27, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8e17cfd388](https://linux-hardware.org/?probe=8e17cfd388) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [6580b51e30](https://linux-hardware.org/?probe=6580b51e30) | Jun 25, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | Notebook    | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | Notebook    | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | Notebook    | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [490c1074fe](https://linux-hardware.org/?probe=490c1074fe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [51d3a22bf6](https://linux-hardware.org/?probe=51d3a22bf6) | Jun 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0db95d58d4](https://linux-hardware.org/?probe=0db95d58d4) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | Desktop     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| System76      | Darter Pro                  | Notebook    | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [fe87d16f84](https://linux-hardware.org/?probe=fe87d16f84) | Jun 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [c2a22e5a3d](https://linux-hardware.org/?probe=c2a22e5a3d) | Jun 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [962571591a](https://linux-hardware.org/?probe=962571591a) | Jun 24, 2022 |
| Alienware     | 14                          | Notebook    | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | Notebook    | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ee06b837b0](https://linux-hardware.org/?probe=ee06b837b0) | Jun 23, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| Dell          | Precision 5520              | Notebook    | [2216faa750](https://linux-hardware.org/?probe=2216faa750) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5dc08ee2d7](https://linux-hardware.org/?probe=5dc08ee2d7) | Jun 22, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [c288025720](https://linux-hardware.org/?probe=c288025720) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [3086580cf5](https://linux-hardware.org/?probe=3086580cf5) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [0bc7456f92](https://linux-hardware.org/?probe=0bc7456f92) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| Quanta        | TWC                         | Notebook    | [6a466d7eac](https://linux-hardware.org/?probe=6a466d7eac) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [0350f8d8f7](https://linux-hardware.org/?probe=0350f8d8f7) | Jun 21, 2022 |
| Biostar       | N68S3+                      | Desktop     | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Iconia                      | Notebook    | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| Dell          | Inspiron 7590 2n1           | Convertible | [3c26fdb170](https://linux-hardware.org/?probe=3c26fdb170) | Jun 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0d3fa4ad21](https://linux-hardware.org/?probe=0d3fa4ad21) | Jun 19, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b3efe3d4b5](https://linux-hardware.org/?probe=b3efe3d4b5) | Jun 19, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [b04866cc36](https://linux-hardware.org/?probe=b04866cc36) | Jun 19, 2022 |
| HP            | 158B                        | Desktop     | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [1820538c80](https://linux-hardware.org/?probe=1820538c80) | Jun 18, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [e601e834f2](https://linux-hardware.org/?probe=e601e834f2) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [8121d73bc9](https://linux-hardware.org/?probe=8121d73bc9) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [41eb5a7de2](https://linux-hardware.org/?probe=41eb5a7de2) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ed83fdd673](https://linux-hardware.org/?probe=ed83fdd673) | Jun 18, 2022 |
| Lenovo        | ThinkPad T450 20BUS1110E    | Notebook    | [77dd393da8](https://linux-hardware.org/?probe=77dd393da8) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [d542c2f694](https://linux-hardware.org/?probe=d542c2f694) | Jun 18, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| HP            | Unknown                     | Notebook    | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [13d72fd6f0](https://linux-hardware.org/?probe=13d72fd6f0) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [1d1727713f](https://linux-hardware.org/?probe=1d1727713f) | Jun 17, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [ee03ec1eae](https://linux-hardware.org/?probe=ee03ec1eae) | Jun 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [617dc7c353](https://linux-hardware.org/?probe=617dc7c353) | Jun 17, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [8f60c0fb25](https://linux-hardware.org/?probe=8f60c0fb25) | Jun 17, 2022 |
| Dell          | Precision 5540              | Notebook    | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Acer          | Aspire E5-574G              | Notebook    | [23c2dd37fe](https://linux-hardware.org/?probe=23c2dd37fe) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Acer          | Aspire 4741                 | Notebook    | [9f25816784](https://linux-hardware.org/?probe=9f25816784) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| System76      | Oryx Pro                    | Notebook    | [4daa6c7d77](https://linux-hardware.org/?probe=4daa6c7d77) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Dell          | Latitude E6540              | Notebook    | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| System76      | Galago Pro                  | Notebook    | [440ba53ef9](https://linux-hardware.org/?probe=440ba53ef9) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [d6e4d7642d](https://linux-hardware.org/?probe=d6e4d7642d) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [6abbac5ca2](https://linux-hardware.org/?probe=6abbac5ca2) | Jun 15, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [aa390f3eaa](https://linux-hardware.org/?probe=aa390f3eaa) | Jun 15, 2022 |
| Sony          | SVF15A1M2ES                 | Notebook    | [bdcd4a90fc](https://linux-hardware.org/?probe=bdcd4a90fc) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | Desktop     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [03fb6fa23c](https://linux-hardware.org/?probe=03fb6fa23c) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| Dell          | Precision 5550              | Notebook    | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | Desktop     | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| HP            | 18E7                        | Desktop     | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Dell          | Precision 7720              | Notebook    | [8b4da2326e](https://linux-hardware.org/?probe=8b4da2326e) | Jun 14, 2022 |
| Dell          | Precision 7720              | Notebook    | [bf25929cec](https://linux-hardware.org/?probe=bf25929cec) | Jun 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [44b876534d](https://linux-hardware.org/?probe=44b876534d) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [f4ef35b902](https://linux-hardware.org/?probe=f4ef35b902) | Jun 14, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [6fa74e19b1](https://linux-hardware.org/?probe=6fa74e19b1) | Jun 13, 2022 |
| Alienware     | 0R3FWM A00                  | Desktop     | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Lenovo        | B40-80 80F6                 | Notebook    | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [2eb24f0195](https://linux-hardware.org/?probe=2eb24f0195) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [110ff08266](https://linux-hardware.org/?probe=110ff08266) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [7222fb776a](https://linux-hardware.org/?probe=7222fb776a) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| Dell          | Latitude E6540              | Notebook    | [91e07b8f2d](https://linux-hardware.org/?probe=91e07b8f2d) | Jun 12, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | UX430UQ                     | Notebook    | [9754c7394d](https://linux-hardware.org/?probe=9754c7394d) | Jun 12, 2022 |
| Dell          | System XPS L702X            | Notebook    | [b79115e065](https://linux-hardware.org/?probe=b79115e065) | Jun 12, 2022 |
| MSI           | Alpha 17 A4DEK              | Notebook    | [42171e02bb](https://linux-hardware.org/?probe=42171e02bb) | Jun 11, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [4916232f15](https://linux-hardware.org/?probe=4916232f15) | Jun 11, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [7c8c3427a9](https://linux-hardware.org/?probe=7c8c3427a9) | Jun 11, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | Desktop     | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| Dell          | Latitude E7270              | Notebook    | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [ad03ec2516](https://linux-hardware.org/?probe=ad03ec2516) | Jun 09, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [ebbea30b2b](https://linux-hardware.org/?probe=ebbea30b2b) | Jun 09, 2022 |
| Dell          | G7 7790                     | Notebook    | [58cfc35862](https://linux-hardware.org/?probe=58cfc35862) | Jun 09, 2022 |
| Dell          | G7 7790                     | Notebook    | [495cfbb6f3](https://linux-hardware.org/?probe=495cfbb6f3) | Jun 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| System76      | Oryx Pro                    | Notebook    | [bf9c9467d3](https://linux-hardware.org/?probe=bf9c9467d3) | Jun 08, 2022 |
| System76      | Oryx Pro                    | Notebook    | [2f96b6b08d](https://linux-hardware.org/?probe=2f96b6b08d) | Jun 08, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5c2fedfca8](https://linux-hardware.org/?probe=5c2fedfca8) | Jun 08, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [ebf8dce138](https://linux-hardware.org/?probe=ebf8dce138) | Jun 07, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [37e02e84a5](https://linux-hardware.org/?probe=37e02e84a5) | Jun 07, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [d4a2222ff7](https://linux-hardware.org/?probe=d4a2222ff7) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7ca8395543](https://linux-hardware.org/?probe=7ca8395543) | Jun 07, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [7bb51064db](https://linux-hardware.org/?probe=7bb51064db) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Dell          | 0JW6C6 A01                  | Desktop     | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [56c4428636](https://linux-hardware.org/?probe=56c4428636) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Framework     | Laptop                      | Notebook    | [ed8e682778](https://linux-hardware.org/?probe=ed8e682778) | Jun 06, 2022 |
| Samsung       | 760XDA                      | Notebook    | [46350b515c](https://linux-hardware.org/?probe=46350b515c) | Jun 06, 2022 |
| MSI           | GS75 Stealth 9SF            | Notebook    | [9d18e7094e](https://linux-hardware.org/?probe=9d18e7094e) | Jun 05, 2022 |
| ASUSTek       | X556URK                     | Notebook    | [d6da70c8bd](https://linux-hardware.org/?probe=d6da70c8bd) | Jun 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e817967c8](https://linux-hardware.org/?probe=0e817967c8) | Jun 05, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [1485986503](https://linux-hardware.org/?probe=1485986503) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [2f60fd04bf](https://linux-hardware.org/?probe=2f60fd04bf) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Dell          | 0YKWK2 A00                  | All in one  | [f373c43a01](https://linux-hardware.org/?probe=f373c43a01) | Jun 05, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| Dell          | Inspiron 3502               | Notebook    | [afa1c5cd74](https://linux-hardware.org/?probe=afa1c5cd74) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f729442cad](https://linux-hardware.org/?probe=f729442cad) | Jun 04, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [a8c04eea72](https://linux-hardware.org/?probe=a8c04eea72) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [562348dd07](https://linux-hardware.org/?probe=562348dd07) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | Notebook    | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [f1f4aec562](https://linux-hardware.org/?probe=f1f4aec562) | Jun 02, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [d793b451f6](https://linux-hardware.org/?probe=d793b451f6) | Jun 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9299688b01](https://linux-hardware.org/?probe=9299688b01) | Jun 02, 2022 |
| Dell          | Latitude E7470              | Notebook    | [f9a9090c54](https://linux-hardware.org/?probe=f9a9090c54) | Jun 02, 2022 |
| Dell          | Latitude 7390               | Notebook    | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | Desktop     | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [de2e1727bc](https://linux-hardware.org/?probe=de2e1727bc) | Jun 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [6f6e6c038a](https://linux-hardware.org/?probe=6f6e6c038a) | Jun 01, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | Notebook    | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [506d3fb361](https://linux-hardware.org/?probe=506d3fb361) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | G7 7700                     | Notebook    | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | Desktop     | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [4863034bc5](https://linux-hardware.org/?probe=4863034bc5) | May 31, 2022 |
| Dell          | Inspiron 7590 2n1           | Convertible | [30a0d0ec81](https://linux-hardware.org/?probe=30a0d0ec81) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | Desktop     | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [923158d12f](https://linux-hardware.org/?probe=923158d12f) | May 30, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6dd26d47b1](https://linux-hardware.org/?probe=6dd26d47b1) | May 30, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [14f581788f](https://linux-hardware.org/?probe=14f581788f) | May 30, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | Desktop     | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | Desktop     | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [72b7fc79d4](https://linux-hardware.org/?probe=72b7fc79d4) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | Vostro V130                 | Notebook    | [abefbba5b8](https://linux-hardware.org/?probe=abefbba5b8) | May 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [0d556408f3](https://linux-hardware.org/?probe=0d556408f3) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [35e3478a5d](https://linux-hardware.org/?probe=35e3478a5d) | May 28, 2022 |
| Medion        | X6816                       | Notebook    | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| Lenovo        | CRESCENTBAY 31900059 STD... | All in one  | [d222b1e86e](https://linux-hardware.org/?probe=d222b1e86e) | May 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [88c420d481](https://linux-hardware.org/?probe=88c420d481) | May 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [c7a5f5eef3](https://linux-hardware.org/?probe=c7a5f5eef3) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | Desktop     | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3980ea8269](https://linux-hardware.org/?probe=3980ea8269) | May 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e7b6eddea](https://linux-hardware.org/?probe=6e7b6eddea) | May 27, 2022 |
| Dell          | Precision 5530              | Notebook    | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [ca090207b8](https://linux-hardware.org/?probe=ca090207b8) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | Notebook    | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | Notebook    | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [3db2e28ef2](https://linux-hardware.org/?probe=3db2e28ef2) | May 24, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [a34eaa3e4a](https://linux-hardware.org/?probe=a34eaa3e4a) | May 24, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e6e080d6e0](https://linux-hardware.org/?probe=e6e080d6e0) | May 24, 2022 |
| HP            | 8703                        | Desktop     | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | Desktop     | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [a59234d081](https://linux-hardware.org/?probe=a59234d081) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [1d4f3a60c0](https://linux-hardware.org/?probe=1d4f3a60c0) | May 23, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [5ec2b88c83](https://linux-hardware.org/?probe=5ec2b88c83) | May 22, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [5a2f6291b5](https://linux-hardware.org/?probe=5a2f6291b5) | May 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | X505BA                      | Notebook    | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | Notebook    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | Notebook    | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [1993c161fd](https://linux-hardware.org/?probe=1993c161fd) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | Desktop     | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Google        | Lulu                        | Notebook    | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [77d5276ecc](https://linux-hardware.org/?probe=77d5276ecc) | May 20, 2022 |
| ASRock        | TRX40 Creator               | Desktop     | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | Desktop     | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d705be052a](https://linux-hardware.org/?probe=d705be052a) | May 20, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [35c2610913](https://linux-hardware.org/?probe=35c2610913) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | Desktop     | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [ba19473e18](https://linux-hardware.org/?probe=ba19473e18) | May 19, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [fba154be66](https://linux-hardware.org/?probe=fba154be66) | May 18, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| Supermicro    | X8SIL                       | Desktop     | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | Desktop     | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c9a82e1be0](https://linux-hardware.org/?probe=c9a82e1be0) | May 18, 2022 |
| HP            | 8054                        | Desktop     | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [8ef2235464](https://linux-hardware.org/?probe=8ef2235464) | May 17, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [5bc959890b](https://linux-hardware.org/?probe=5bc959890b) | May 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [e4bf8d23b8](https://linux-hardware.org/?probe=e4bf8d23b8) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [f5ade437dc](https://linux-hardware.org/?probe=f5ade437dc) | May 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [77a8cae8a0](https://linux-hardware.org/?probe=77a8cae8a0) | May 17, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [2d96e5ecba](https://linux-hardware.org/?probe=2d96e5ecba) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| Alienware     | 18                          | Notebook    | [7aa82b2786](https://linux-hardware.org/?probe=7aa82b2786) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| Acer          | Aspire 7560G                | Notebook    | [d3d9aa988f](https://linux-hardware.org/?probe=d3d9aa988f) | May 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [eb5345a5c6](https://linux-hardware.org/?probe=eb5345a5c6) | May 16, 2022 |
| Google        | Lulu                        | Notebook    | [c402204a03](https://linux-hardware.org/?probe=c402204a03) | May 16, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [aa531d1bf8](https://linux-hardware.org/?probe=aa531d1bf8) | May 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | Notebook    | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [30bb58501e](https://linux-hardware.org/?probe=30bb58501e) | May 13, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [95339de38e](https://linux-hardware.org/?probe=95339de38e) | May 13, 2022 |
| NZXT          | N7 B550                     | Desktop     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | Desktop     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [fe8e3837f4](https://linux-hardware.org/?probe=fe8e3837f4) | May 12, 2022 |
| System76      | Pangolin                    | Notebook    | [0f05fa93a8](https://linux-hardware.org/?probe=0f05fa93a8) | May 12, 2022 |
| AZW           | BT3 X                       | Desktop     | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [0b95d0a5d8](https://linux-hardware.org/?probe=0b95d0a5d8) | May 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [114ef2756f](https://linux-hardware.org/?probe=114ef2756f) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Google        | Cyan                        | Notebook    | [cec3bd0a88](https://linux-hardware.org/?probe=cec3bd0a88) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [78ee3350a8](https://linux-hardware.org/?probe=78ee3350a8) | May 11, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [4f25a82453](https://linux-hardware.org/?probe=4f25a82453) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | Desktop     | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0913ac4c8e](https://linux-hardware.org/?probe=0913ac4c8e) | May 11, 2022 |
| System76      | Pangolin                    | Notebook    | [da80a33b86](https://linux-hardware.org/?probe=da80a33b86) | May 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| NZXT          | N7 B550                     | Desktop     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [cae0934838](https://linux-hardware.org/?probe=cae0934838) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | Desktop     | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d88f833b65](https://linux-hardware.org/?probe=d88f833b65) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [fd022c446e](https://linux-hardware.org/?probe=fd022c446e) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [20f46751c2](https://linux-hardware.org/?probe=20f46751c2) | May 08, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [c1df33620d](https://linux-hardware.org/?probe=c1df33620d) | May 08, 2022 |
| MSI           | Modern 15 A10RAS            | Notebook    | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | Notebook    | [5eefaba8d3](https://linux-hardware.org/?probe=5eefaba8d3) | May 08, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | Desktop     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dcdc07525d](https://linux-hardware.org/?probe=dcdc07525d) | May 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [057ea02fdb](https://linux-hardware.org/?probe=057ea02fdb) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | Notebook    | [892d07e5cf](https://linux-hardware.org/?probe=892d07e5cf) | May 08, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| MSI           | GS63 7RD                    | Notebook    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| ECS           | Nettle3                     | Desktop     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Google        | Lulu                        | Notebook    | [18ecc4a6e7](https://linux-hardware.org/?probe=18ecc4a6e7) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5790e8a0cb](https://linux-hardware.org/?probe=5790e8a0cb) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [632a2af548](https://linux-hardware.org/?probe=632a2af548) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [4071a1a35e](https://linux-hardware.org/?probe=4071a1a35e) | May 06, 2022 |
| Google        | Peppy                       | Notebook    | [03dc670128](https://linux-hardware.org/?probe=03dc670128) | May 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [f99b5cee66](https://linux-hardware.org/?probe=f99b5cee66) | May 06, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | Notebook    | [710c086b29](https://linux-hardware.org/?probe=710c086b29) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | Notebook    | [76fb8bb966](https://linux-hardware.org/?probe=76fb8bb966) | May 06, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [080b4f2667](https://linux-hardware.org/?probe=080b4f2667) | May 06, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [66a01dfd2d](https://linux-hardware.org/?probe=66a01dfd2d) | May 05, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [af36cfb1a8](https://linux-hardware.org/?probe=af36cfb1a8) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [fa323515aa](https://linux-hardware.org/?probe=fa323515aa) | May 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [1c70ba9e33](https://linux-hardware.org/?probe=1c70ba9e33) | May 05, 2022 |
| Dell          | Latitude E5440              | Notebook    | [a505dc0b3c](https://linux-hardware.org/?probe=a505dc0b3c) | May 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [d153ef27fa](https://linux-hardware.org/?probe=d153ef27fa) | May 04, 2022 |
| Acer          | Spin SP315-51               | Convertible | [b96494c3bc](https://linux-hardware.org/?probe=b96494c3bc) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| ASUSTek       | GL552JX                     | Notebook    | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | Notebook    | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| Acer          | Spin SP315-51               | Convertible | [227f2d9f45](https://linux-hardware.org/?probe=227f2d9f45) | May 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [8daebf6110](https://linux-hardware.org/?probe=8daebf6110) | May 02, 2022 |
| Dell          | Latitude E6440              | Notebook    | [d2ab063048](https://linux-hardware.org/?probe=d2ab063048) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [58ff4a1984](https://linux-hardware.org/?probe=58ff4a1984) | May 02, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [6c38249bc4](https://linux-hardware.org/?probe=6c38249bc4) | May 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | Desktop     | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | Notebook    | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| System76      | Oryx Pro                    | Notebook    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| Acer          | Aspire V5-573P              | Notebook    | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Dell          | Latitude E5570              | Notebook    | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [abd7ed0c5c](https://linux-hardware.org/?probe=abd7ed0c5c) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | Notebook    | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [be68c0201a](https://linux-hardware.org/?probe=be68c0201a) | May 01, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [83a8bbb313](https://linux-hardware.org/?probe=83a8bbb313) | May 01, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [48afcac3f0](https://linux-hardware.org/?probe=48afcac3f0) | May 01, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [89a959efc4](https://linux-hardware.org/?probe=89a959efc4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| Samsung       | 950QCG                      | Convertible | [3010ee5185](https://linux-hardware.org/?probe=3010ee5185) | May 01, 2022 |
| Samsung       | 950QCG                      | Convertible | [257ee40584](https://linux-hardware.org/?probe=257ee40584) | May 01, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | Desktop     | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | G55VW                       | Notebook    | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [ea3b16fcfd](https://linux-hardware.org/?probe=ea3b16fcfd) | Apr 29, 2022 |
| Dell          | G5 5500                     | Notebook    | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| System76      | Oryx Pro                    | Notebook    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| Lenovo        | ThinkPad T431s 20ACS03P0... | Notebook    | [3c0878aee3](https://linux-hardware.org/?probe=3c0878aee3) | Apr 28, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ae46ece731](https://linux-hardware.org/?probe=ae46ece731) | Apr 28, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [1f26415f58](https://linux-hardware.org/?probe=1f26415f58) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [b7443972f3](https://linux-hardware.org/?probe=b7443972f3) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3e5933fe0d](https://linux-hardware.org/?probe=3e5933fe0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e51ff27a5a](https://linux-hardware.org/?probe=e51ff27a5a) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | Desktop     | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c9fb277b57](https://linux-hardware.org/?probe=c9fb277b57) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [25041b35de](https://linux-hardware.org/?probe=25041b35de) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [bbb524450f](https://linux-hardware.org/?probe=bbb524450f) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | Notebook    | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| Dell          | Latitude E7270              | Notebook    | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.17.5-76051705-generic   | 398       | 51.89%  |
| 5.17.15-76051715-generic  | 174       | 22.69%  |
| 5.16.19-76051619-generic  | 117       | 15.25%  |
| 5.18.10-76051810-generic  | 58        | 7.56%   |
| 5.16.15-76051615-generic  | 3         | 0.39%   |
| 5.17.7-051707-generic     | 2         | 0.26%   |
| 5.17.5-051705-generic     | 2         | 0.26%   |
| 5.19.0-rc1+               | 1         | 0.13%   |
| 5.18.6-xanmod1            | 1         | 0.13%   |
| 5.18.4-xanmod1            | 1         | 0.13%   |
| 5.18.11-051811-generic    | 1         | 0.13%   |
| 5.18.0-9.1-liquorix-amd64 | 1         | 0.13%   |
| 5.18.0-051800rc1-generic  | 1         | 0.13%   |
| 5.17.9-051709-generic     | 1         | 0.13%   |
| 5.17.6-051706-generic     | 1         | 0.13%   |
| 5.17.5-tkg-bmq            | 1         | 0.13%   |
| 5.17.4-051704-generic     | 1         | 0.13%   |
| 5.17.2-xanmod1            | 1         | 0.13%   |
| 5.17.0-051700-generic     | 1         | 0.13%   |
| 5.16.11-76051611-generic  | 1         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 401       | 52.28%  |
| 5.17.15 | 174       | 22.69%  |
| 5.16.19 | 117       | 15.25%  |
| 5.18.10 | 58        | 7.56%   |
| 5.16.15 | 3         | 0.39%   |
| 5.18.0  | 2         | 0.26%   |
| 5.17.7  | 2         | 0.26%   |
| 5.19.0  | 1         | 0.13%   |
| 5.18.6  | 1         | 0.13%   |
| 5.18.4  | 1         | 0.13%   |
| 5.18.11 | 1         | 0.13%   |
| 5.17.9  | 1         | 0.13%   |
| 5.17.6  | 1         | 0.13%   |
| 5.17.4  | 1         | 0.13%   |
| 5.17.2  | 1         | 0.13%   |
| 5.17.0  | 1         | 0.13%   |
| 5.16.11 | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 571       | 75.53%  |
| 5.16    | 121       | 16.01%  |
| 5.18    | 63        | 8.33%   |
| 5.19    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 743       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 724       | 97.31%  |
| KDE5            | 10        | 1.34%   |
| Unknown         | 4         | 0.54%   |
| X-Cinnamon      | 2         | 0.27%   |
| XFCE            | 1         | 0.13%   |
| LXQt            | 1         | 0.13%   |
| GNOME Flashback | 1         | 0.13%   |
| Cinnamon        | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 714       | 95.84%  |
| Wayland | 27        | 3.62%   |
| Unknown | 3         | 0.4%    |
| Tty     | 1         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 600       | 80.65%  |
| GDM3    | 140       | 18.82%  |
| SDDM    | 2         | 0.27%   |
| GDM     | 2         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 450       | 60.4%   |
| en_GB   | 43        | 5.77%   |
| pt_BR   | 41        | 5.5%    |
| de_DE   | 28        | 3.76%   |
| en_AU   | 23        | 3.09%   |
| C       | 20        | 2.68%   |
| fr_FR   | 18        | 2.42%   |
| en_CA   | 17        | 2.28%   |
| pl_PL   | 11        | 1.48%   |
| it_IT   | 11        | 1.48%   |
| sv_SE   | 9         | 1.21%   |
| es_ES   | 9         | 1.21%   |
| ru_RU   | 8         | 1.07%   |
| es_CL   | 4         | 0.54%   |
| nl_NL   | 3         | 0.4%    |
| nb_NO   | 3         | 0.4%    |
| fr_CA   | 3         | 0.4%    |
| en_NZ   | 3         | 0.4%    |
| en_IN   | 3         | 0.4%    |
| de_AT   | 3         | 0.4%    |
| Unknown | 3         | 0.4%    |
| ro_RO   | 2         | 0.27%   |
| pt_PT   | 2         | 0.27%   |
| ja_JP   | 2         | 0.27%   |
| fi_FI   | 2         | 0.27%   |
| es_UY   | 2         | 0.27%   |
| es_MX   | 2         | 0.27%   |
| es_CO   | 2         | 0.27%   |
| es_AR   | 2         | 0.27%   |
| en_ZA   | 2         | 0.27%   |
| en_DK   | 2         | 0.27%   |
| de_CH   | 2         | 0.27%   |
| nl_BE   | 1         | 0.13%   |
| hr_HR   | 1         | 0.13%   |
| fr_BE   | 1         | 0.13%   |
| es_GT   | 1         | 0.13%   |
| es_DO   | 1         | 0.13%   |
| en_SG   | 1         | 0.13%   |
| en_PH   | 1         | 0.13%   |
| en_IL   | 1         | 0.13%   |
| en_IE   | 1         | 0.13%   |
| cs_CZ   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 608       | 81.72%  |
| EFI  | 136       | 18.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 711       | 95.69%  |
| Btrfs   | 20        | 2.69%   |
| Overlay | 10        | 1.35%   |
| Xfs     | 2         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 597       | 80.13%  |
| GPT     | 140       | 18.79%  |
| MBR     | 8         | 1.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 725       | 97.58%  |
| Yes       | 18        | 2.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 681       | 91.53%  |
| Yes       | 63        | 8.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| ASUSTek Computer     | 138       | 18.57%  |
| Dell                 | 106       | 14.27%  |
| Lenovo               | 87        | 11.71%  |
| Hewlett-Packard      | 75        | 10.09%  |
| MSI                  | 59        | 7.94%   |
| Gigabyte Technology  | 59        | 7.94%   |
| Apple                | 39        | 5.25%   |
| Acer                 | 35        | 4.71%   |
| ASRock               | 20        | 2.69%   |
| System76             | 15        | 2.02%   |
| Toshiba              | 13        | 1.75%   |
| Samsung Electronics  | 9         | 1.21%   |
| Intel                | 9         | 1.21%   |
| Alienware            | 7         | 0.94%   |
| HUAWEI               | 6         | 0.81%   |
| Microsoft            | 5         | 0.67%   |
| Notebook             | 4         | 0.54%   |
| GPU Company          | 4         | 0.54%   |
| Google               | 4         | 0.54%   |
| Fujitsu              | 4         | 0.54%   |
| Unknown              | 4         | 0.54%   |
| Sony                 | 3         | 0.4%    |
| Medion               | 3         | 0.4%    |
| Timi                 | 2         | 0.27%   |
| PC Specialist        | 2         | 0.27%   |
| MACHINIST            | 2         | 0.27%   |
| Framework            | 2         | 0.27%   |
| Foxconn              | 2         | 0.27%   |
| EVGA                 | 2         | 0.27%   |
| TUXEDO               | 1         | 0.13%   |
| Supermicro           | 1         | 0.13%   |
| Soyo                 | 1         | 0.13%   |
| SIEMENS              | 1         | 0.13%   |
| Semp Toshiba         | 1         | 0.13%   |
| Schenker             | 1         | 0.13%   |
| Razer                | 1         | 0.13%   |
| Quanta               | 1         | 0.13%   |
| Purism               | 1         | 0.13%   |
| Positivo             | 1         | 0.13%   |
| Pegatron             | 1         | 0.13%   |
| Panasonic            | 1         | 0.13%   |
| NZXT                 | 1         | 0.13%   |
| Monster              | 1         | 0.13%   |
| LG Electronics       | 1         | 0.13%   |
| Intel Client Systems | 1         | 0.13%   |
| Eluktronics          | 1         | 0.13%   |
| ECS                  | 1         | 0.13%   |
| Dynabook             | 1         | 0.13%   |
| Biostar              | 1         | 0.13%   |
| BESSTAR Tech         | 1         | 0.13%   |
| AZW                  | 1         | 0.13%   |
| A-DATA Technology    | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 7         | 0.94%   |
| System76 Oryx Pro                    | 5         | 0.67%   |
| Gigabyte X570 AORUS ELITE            | 5         | 0.67%   |
| ASUS All Series                      | 5         | 0.67%   |
| Apple MacBookAir7,2                  | 5         | 0.67%   |
| Gigabyte B450 AORUS M                | 4         | 0.54%   |
| System76 Lemur Pro                   | 3         | 0.4%    |
| Lenovo IdeaPad S145-15API 81V7       | 3         | 0.4%    |
| HP Pavilion Notebook                 | 3         | 0.4%    |
| HP OMEN Laptop 15-en0xxx             | 3         | 0.4%    |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 3         | 0.4%    |
| Dell OptiPlex 3020                   | 3         | 0.4%    |
| Dell Latitude E7240                  | 3         | 0.4%    |
| ASUS ROG STRIX B450-F GAMING         | 3         | 0.4%    |
| ASUS ROG CROSSHAIR VIII DARK HERO    | 3         | 0.4%    |
| ASUS PRIME B450M-A                   | 3         | 0.4%    |
| Apple MacBookPro7,1                  | 3         | 0.4%    |
| System76 Thelio                      | 2         | 0.27%   |
| System76 Pangolin                    | 2         | 0.27%   |
| Samsung 760XDA                       | 2         | 0.27%   |
| MSI MS-7D32                          | 2         | 0.27%   |
| MSI MS-7C37                          | 2         | 0.27%   |
| MSI MS-7C35                          | 2         | 0.27%   |
| MSI MS-7C02                          | 2         | 0.27%   |
| MSI Katana GF76 11UD                 | 2         | 0.27%   |
| MSI GF63 Thin 11UD                   | 2         | 0.27%   |
| Lenovo V14-IIL 82C4                  | 2         | 0.27%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000 | 2         | 0.27%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 2         | 0.27%   |
| HP ProDesk 600 G1 SFF                | 2         | 0.27%   |
| HP Pavilion 15                       | 2         | 0.27%   |
| HP Pavilion 13 x360 PC               | 2         | 0.27%   |
| HP EliteBook 855 G8 Notebook PC      | 2         | 0.27%   |
| HP EliteBook 745 G2                  | 2         | 0.27%   |
| HP 15 Notebook PC                    | 2         | 0.27%   |
| GPU Company GWTN141-10               | 2         | 0.27%   |
| GPU Company GWTC116-2                | 2         | 0.27%   |
| Google Lulu                          | 2         | 0.27%   |
| Gigabyte Z170-HD3P                   | 2         | 0.27%   |
| Gigabyte Z170-Gaming K3              | 2         | 0.27%   |
| Gigabyte X570 I AORUS PRO WIFI       | 2         | 0.27%   |
| Gigabyte X570 AORUS MASTER           | 2         | 0.27%   |
| Gigabyte B450M DS3H                  | 2         | 0.27%   |
| Gigabyte AB350-Gaming 3              | 2         | 0.27%   |
| Framework Laptop                     | 2         | 0.27%   |
| Dell XPS 15 9570                     | 2         | 0.27%   |
| Dell XPS 15 9510                     | 2         | 0.27%   |
| Dell XPS 13 9310                     | 2         | 0.27%   |
| Dell Vostro 5470                     | 2         | 0.27%   |
| Dell Vostro 5402                     | 2         | 0.27%   |
| Dell Vostro 15 3515                  | 2         | 0.27%   |
| Dell Precision M4800                 | 2         | 0.27%   |
| Dell Latitude E7470                  | 2         | 0.27%   |
| Dell Latitude E7270                  | 2         | 0.27%   |
| Dell Latitude E6540                  | 2         | 0.27%   |
| Dell Inspiron 5566                   | 2         | 0.27%   |
| Dell Inspiron 5547                   | 2         | 0.27%   |
| Dell Inspiron 3542                   | 2         | 0.27%   |
| Dell Inspiron 3442                   | 2         | 0.27%   |
| Dell Inspiron 1750                   | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS ROG              | 35        | 4.71%   |
| Lenovo ThinkPad       | 32        | 4.31%   |
| Dell Inspiron         | 27        | 3.63%   |
| Dell Latitude         | 23        | 3.1%    |
| Acer Aspire           | 22        | 2.96%   |
| Dell Precision        | 16        | 2.15%   |
| ASUS PRIME            | 16        | 2.15%   |
| Lenovo IdeaPad        | 15        | 2.02%   |
| Dell XPS              | 15        | 2.02%   |
| HP Pavilion           | 13        | 1.75%   |
| Toshiba Satellite     | 10        | 1.35%   |
| Lenovo Legion         | 10        | 1.35%   |
| Gigabyte X570         | 10        | 1.35%   |
| Dell Vostro           | 10        | 1.35%   |
| HP ProBook            | 9         | 1.21%   |
| HP EliteBook          | 9         | 1.21%   |
| Dell OptiPlex         | 9         | 1.21%   |
| ASUS VivoBook         | 9         | 1.21%   |
| ASUS TUF              | 9         | 1.21%   |
| HP ENVY               | 8         | 1.08%   |
| HP Laptop             | 7         | 0.94%   |
| Unknown               | 7         | 0.94%   |
| Lenovo ThinkCentre    | 6         | 0.81%   |
| HP OMEN               | 6         | 0.81%   |
| System76 Oryx         | 5         | 0.67%   |
| Microsoft Surface     | 5         | 0.67%   |
| Lenovo Yoga           | 5         | 0.67%   |
| Gigabyte B450         | 5         | 0.67%   |
| ASUS All              | 5         | 0.67%   |
| Apple MacBookAir7     | 5         | 0.67%   |
| ASUS ZenBook          | 4         | 0.54%   |
| ASUS ASUS             | 4         | 0.54%   |
| ASRock B450           | 4         | 0.54%   |
| Apple MacBookPro11    | 4         | 0.54%   |
| Alienware Aurora      | 4         | 0.54%   |
| Acer Swift            | 4         | 0.54%   |
| Acer Nitro            | 4         | 0.54%   |
| System76 Thelio       | 3         | 0.4%    |
| System76 Lemur        | 3         | 0.4%    |
| MSI Modern            | 3         | 0.4%    |
| MSI Katana            | 3         | 0.4%    |
| MSI GF63              | 3         | 0.4%    |
| Lenovo ThinkBook      | 3         | 0.4%    |
| HP ZBook              | 3         | 0.4%    |
| HP Spectre            | 3         | 0.4%    |
| HP EliteDesk          | 3         | 0.4%    |
| HP Compaq             | 3         | 0.4%    |
| Gigabyte B550         | 3         | 0.4%    |
| Gigabyte B450M        | 3         | 0.4%    |
| Gigabyte AB350-Gaming | 3         | 0.4%    |
| Apple MacBookPro9     | 3         | 0.4%    |
| Apple MacBookPro7     | 3         | 0.4%    |
| System76 Pangolin     | 2         | 0.27%   |
| Samsung 760XDA        | 2         | 0.27%   |
| MSI MS-7D32           | 2         | 0.27%   |
| MSI MS-7C37           | 2         | 0.27%   |
| MSI MS-7C35           | 2         | 0.27%   |
| MSI MS-7C02           | 2         | 0.27%   |
| MSI GS75              | 2         | 0.27%   |
| Lenovo V14-IIL        | 2         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 110       | 14.8%   |
| 2020 | 90        | 12.11%  |
| 2018 | 82        | 11.04%  |
| 2019 | 80        | 10.77%  |
| 2016 | 49        | 6.59%   |
| 2013 | 46        | 6.19%   |
| 2015 | 45        | 6.06%   |
| 2017 | 40        | 5.38%   |
| 2014 | 39        | 5.25%   |
| 2011 | 36        | 4.85%   |
| 2012 | 33        | 4.44%   |
| 2022 | 32        | 4.31%   |
| 2010 | 25        | 3.36%   |
| 2009 | 23        | 3.1%    |
| 2008 | 8         | 1.08%   |
| 2007 | 4         | 0.54%   |
| 2006 | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 422       | 56.8%   |
| Desktop     | 268       | 36.07%  |
| Convertible | 26        | 3.5%    |
| Mini pc     | 11        | 1.48%   |
| All in one  | 9         | 1.21%   |
| Tablet      | 6         | 0.81%   |
| Server      | 1         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 742       | 99.87%  |
| Enabled  | 1         | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 730       | 98.25%  |
| Yes  | 13        | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 206       | 27.65%  |
| 4.01-8.0        | 160       | 21.48%  |
| 8.01-16.0       | 140       | 18.79%  |
| 32.01-64.0      | 114       | 15.3%   |
| 3.01-4.0        | 77        | 10.34%  |
| 64.01-256.0     | 38        | 5.1%    |
| 24.01-32.0      | 5         | 0.67%   |
| 1.01-2.0        | 3         | 0.4%    |
| More than 256.0 | 2         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 263       | 33.98%  |
| 3.01-4.0   | 177       | 22.87%  |
| 4.01-8.0   | 176       | 22.74%  |
| 1.01-2.0   | 112       | 14.47%  |
| 8.01-16.0  | 35        | 4.52%   |
| 16.01-24.0 | 7         | 0.9%    |
| 32.01-64.0 | 3         | 0.39%   |
| 24.01-32.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 412       | 55.15%  |
| 2      | 214       | 28.65%  |
| 3      | 71        | 9.5%    |
| 4      | 21        | 2.81%   |
| 5      | 11        | 1.47%   |
| 6      | 10        | 1.34%   |
| 7      | 4         | 0.54%   |
| 11     | 1         | 0.13%   |
| 10     | 1         | 0.13%   |
| 9      | 1         | 0.13%   |
| 0      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 548       | 73.76%  |
| Yes       | 195       | 26.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 624       | 83.65%  |
| No        | 122       | 16.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 624       | 83.98%  |
| No        | 119       | 16.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 523       | 70.2%   |
| No        | 222       | 29.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 251       | 33.65%  |
| Brazil                | 57        | 7.64%   |
| Germany               | 46        | 6.17%   |
| Canada                | 33        | 4.42%   |
| Australia             | 30        | 4.02%   |
| UK                    | 26        | 3.49%   |
| India                 | 24        | 3.22%   |
| France                | 22        | 2.95%   |
| Italy                 | 18        | 2.41%   |
| Netherlands           | 14        | 1.88%   |
| Sweden                | 13        | 1.74%   |
| Norway                | 13        | 1.74%   |
| Russia                | 12        | 1.61%   |
| Poland                | 10        | 1.34%   |
| Mexico                | 10        | 1.34%   |
| Switzerland           | 9         | 1.21%   |
| Austria               | 9         | 1.21%   |
| Spain                 | 7         | 0.94%   |
| Japan                 | 7         | 0.94%   |
| Turkey                | 6         | 0.8%    |
| New Zealand           | 6         | 0.8%    |
| Greece                | 6         | 0.8%    |
| Finland               | 6         | 0.8%    |
| Belgium               | 6         | 0.8%    |
| Argentina             | 6         | 0.8%    |
| Romania               | 5         | 0.67%   |
| Ireland               | 5         | 0.67%   |
| Colombia              | 5         | 0.67%   |
| Chile                 | 5         | 0.67%   |
| Thailand              | 4         | 0.54%   |
| South Africa          | 4         | 0.54%   |
| Philippines           | 4         | 0.54%   |
| Hong Kong             | 4         | 0.54%   |
| Uruguay               | 3         | 0.4%    |
| Saudi Arabia          | 3         | 0.4%    |
| Portugal              | 3         | 0.4%    |
| Morocco               | 3         | 0.4%    |
| Hungary               | 3         | 0.4%    |
| Czechia               | 3         | 0.4%    |
| Croatia               | 3         | 0.4%    |
| Venezuela             | 2         | 0.27%   |
| Tunisia               | 2         | 0.27%   |
| Singapore             | 2         | 0.27%   |
| Peru                  | 2         | 0.27%   |
| Panama                | 2         | 0.27%   |
| Malaysia              | 2         | 0.27%   |
| Georgia               | 2         | 0.27%   |
| Egypt                 | 2         | 0.27%   |
| Denmark               | 2         | 0.27%   |
| Bulgaria              | 2         | 0.27%   |
| Vietnam               | 1         | 0.13%   |
| Uzbekistan            | 1         | 0.13%   |
| South Korea           | 1         | 0.13%   |
| Slovenia              | 1         | 0.13%   |
| Slovakia              | 1         | 0.13%   |
| Republic of the Congo | 1         | 0.13%   |
| Pakistan              | 1         | 0.13%   |
| Nicaragua             | 1         | 0.13%   |
| Maldives              | 1         | 0.13%   |
| Lithuania             | 1         | 0.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Sydney           | 7         | 0.93%   |
| Oslo             | 7         | 0.93%   |
| Melbourne        | 7         | 0.93%   |
| Zurich           | 6         | 0.8%    |
| Vienna           | 6         | 0.8%    |
| Brisbane         | 6         | 0.8%    |
| Sao Paulo        | 5         | 0.66%   |
| Munich           | 5         | 0.66%   |
| Mannheim         | 5         | 0.66%   |
| Istanbul         | 5         | 0.66%   |
| Berlin           | 5         | 0.66%   |
| Toronto          | 4         | 0.53%   |
| Mumbai           | 4         | 0.53%   |
| Manaus           | 4         | 0.53%   |
| Auckland         | 4         | 0.53%   |
| Warsaw           | 3         | 0.4%    |
| Stockholm        | 3         | 0.4%    |
| Springfield      | 3         | 0.4%    |
| Seattle          | 3         | 0.4%    |
| San Jose         | 3         | 0.4%    |
| San Francisco    | 3         | 0.4%    |
| San Antonio      | 3         | 0.4%    |
| Rome             | 3         | 0.4%    |
| Rio de Janeiro   | 3         | 0.4%    |
| Paris            | 3         | 0.4%    |
| Ottawa           | 3         | 0.4%    |
| Moscow           | 3         | 0.4%    |
| Milan            | 3         | 0.4%    |
| Helsinki         | 3         | 0.4%    |
| Durham           | 3         | 0.4%    |
| Denver           | 3         | 0.4%    |
| Columbus         | 3         | 0.4%    |
| Colorado Springs | 3         | 0.4%    |
| Chicago          | 3         | 0.4%    |
| Boise            | 3         | 0.4%    |
| Birmingham       | 3         | 0.4%    |
| Bengaluru        | 3         | 0.4%    |
| Virginia Beach   | 2         | 0.27%   |
| Utrecht          | 2         | 0.27%   |
| Turin            | 2         | 0.27%   |
| Tunis            | 2         | 0.27%   |
| Tucson           | 2         | 0.27%   |
| Trondheim        | 2         | 0.27%   |
| Tallahassee      | 2         | 0.27%   |
| Stuttgart        | 2         | 0.27%   |
| Singapore        | 2         | 0.27%   |
| Sarasota         | 2         | 0.27%   |
| Sapporo          | 2         | 0.27%   |
| Sao Luís        | 2         | 0.27%   |
| Saint Paul       | 2         | 0.27%   |
| Riyadh           | 2         | 0.27%   |
| Riverview        | 2         | 0.27%   |
| Richmond         | 2         | 0.27%   |
| Recife           | 2         | 0.27%   |
| Quezon City      | 2         | 0.27%   |
| Prague           | 2         | 0.27%   |
| Portland         | 2         | 0.27%   |
| Panama City      | 2         | 0.27%   |
| Ogden            | 2         | 0.27%   |
| Nuremberg        | 2         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 219       | 281    | 19.11%  |
| Seagate                        | 142       | 188    | 12.39%  |
| WDC                            | 127       | 167    | 11.08%  |
| SanDisk                        | 85        | 102    | 7.42%   |
| Toshiba                        | 65        | 74     | 5.67%   |
| Kingston                       | 65        | 76     | 5.67%   |
| Crucial                        | 52        | 69     | 4.54%   |
| SK hynix                       | 37        | 38     | 3.23%   |
| Phison                         | 27        | 33     | 2.36%   |
| Intel                          | 27        | 31     | 2.36%   |
| Hitachi                        | 23        | 30     | 2.01%   |
| Apple                          | 22        | 25     | 1.92%   |
| Unknown                        | 21        | 24     | 1.83%   |
| Micron Technology              | 21        | 22     | 1.83%   |
| A-DATA Technology              | 21        | 23     | 1.83%   |
| HGST                           | 19        | 19     | 1.66%   |
| Silicon Motion                 | 11        | 14     | 0.96%   |
| PNY                            | 10        | 11     | 0.87%   |
| SPCC                           | 9         | 11     | 0.79%   |
| China                          | 9         | 10     | 0.79%   |
| Micron/Crucial Technology      | 8         | 10     | 0.7%    |
| KIOXIA                         | 7         | 8      | 0.61%   |
| Intenso                        | 7         | 7      | 0.61%   |
| LITEONIT                       | 5         | 5      | 0.44%   |
| LITEON                         | 5         | 5      | 0.44%   |
| Lexar                          | 5         | 5      | 0.44%   |
| Union Memory (Shenzhen)        | 4         | 5      | 0.35%   |
| Hewlett-Packard                | 4         | 4      | 0.35%   |
| ADATA Technology               | 4         | 4      | 0.35%   |
| Patriot                        | 3         | 3      | 0.26%   |
| OCZ                            | 3         | 3      | 0.26%   |
| MyDigitalSSD                   | 3         | 3      | 0.26%   |
| KingSpec                       | 3         | 3      | 0.26%   |
| Fujitsu                        | 3         | 4      | 0.26%   |
| XPG                            | 2         | 2      | 0.17%   |
| W800S                          | 2         | 3      | 0.17%   |
| Team                           | 2         | 2      | 0.17%   |
| T-FORCE                        | 2         | 3      | 0.17%   |
| SSSTC                          | 2         | 2      | 0.17%   |
| Solid State Storage Technology | 2         | 2      | 0.17%   |
| PNY USB                        | 2         | 2      | 0.17%   |
| Mushkin                        | 2         | 3      | 0.17%   |
| Maxtor                         | 2         | 2      | 0.17%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.17%   |
| KingFast                       | 2         | 3      | 0.17%   |
| JMicron Technology             | 2         | 2      | 0.17%   |
| Corsair                        | 2         | 3      | 0.17%   |
| ASMT                           | 2         | 3      | 0.17%   |
| Apacer                         | 2         | 4      | 0.17%   |
| Unknown                        | 2         | 2      | 0.17%   |
| YMTC                           | 1         | 1      | 0.09%   |
| WALRAM                         | 1         | 1      | 0.09%   |
| USB3.0                         | 1         | 1      | 0.09%   |
| TwinMOS                        | 1         | 1      | 0.09%   |
| TurXun                         | 1         | 1      | 0.09%   |
| Transcend                      | 1         | 2      | 0.09%   |
| TO Exter                       | 1         | 1      | 0.09%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.09%   |
| SATAFIRM                       | 1         | 1      | 0.09%   |
| SABRENT                        | 1         | 2      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB         | 23        | 1.81%   |
| Samsung NVMe SSD Drive 500GB       | 22        | 1.73%   |
| SanDisk NVMe SSD Drive 1TB         | 21        | 1.65%   |
| Kingston SA400S37240G 240GB SSD    | 18        | 1.42%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 1.26%   |
| Samsung NVMe SSD Drive 2TB         | 14        | 1.1%    |
| Samsung NVMe SSD Drive 512GB       | 13        | 1.02%   |
| SanDisk NVMe SSD Drive 512GB       | 11        | 0.86%   |
| SK hynix NVMe SSD Drive 512GB      | 10        | 0.79%   |
| Samsung SSD 850 EVO 500GB          | 10        | 0.79%   |
| Kingston SA400S37120G 120GB SSD    | 10        | 0.79%   |
| Crucial CT1000MX500SSD1 1TB        | 10        | 0.79%   |
| Samsung SSD 850 EVO 250GB          | 9         | 0.71%   |
| Samsung NVMe SSD Drive 1024GB      | 9         | 0.71%   |
| Phison NVMe SSD Drive 1TB          | 9         | 0.71%   |
| Samsung SSD 860 EVO 1TB            | 8         | 0.63%   |
| Kingston NVMe SSD Drive 512GB      | 8         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB           | 7         | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB     | 7         | 0.55%   |
| SanDisk NVMe SSD Drive 500GB       | 7         | 0.55%   |
| SanDisk NVMe SSD Drive 256GB       | 7         | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB       | 7         | 0.55%   |
| Samsung NVMe SSD Drive 256GB       | 7         | 0.55%   |
| Intel NVMe SSD Drive 512GB         | 7         | 0.55%   |
| HGST HTS721010A9E630 1TB           | 7         | 0.55%   |
| Crucial CT2000MX500SSD1 2TB        | 7         | 0.55%   |
| SK hynix NVMe SSD Drive 1024GB     | 6         | 0.47%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB     | 6         | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 0.47%   |
| Samsung SSD 860 EVO 500GB          | 6         | 0.47%   |
| Intel NVMe SSD Drive 1024GB        | 6         | 0.47%   |
| Toshiba MQ04ABF100 1TB             | 5         | 0.39%   |
| SK hynix NVMe SSD Drive 256GB      | 5         | 0.39%   |
| Seagate Expansion 1TB              | 5         | 0.39%   |
| Samsung NVMe SSD Drive 250GB       | 5         | 0.39%   |
| Phison NVMe SSD Drive 2TB          | 5         | 0.39%   |
| Kingston SA400S37480G 480GB SSD    | 5         | 0.39%   |
| Apple SSD SM0128G 121GB            | 5         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 4         | 0.31%   |
| WDC WD30EFRX-68EUZN0 3TB           | 4         | 0.31%   |
| Unknown MMC Card  64GB             | 4         | 0.31%   |
| Unknown MMC Card  128GB            | 4         | 0.31%   |
| Toshiba NVMe SSD Drive 512GB       | 4         | 0.31%   |
| Toshiba MQ01ACF050 500GB           | 4         | 0.31%   |
| Toshiba HDWD120 2TB                | 4         | 0.31%   |
| Toshiba DT01ACA200 2TB             | 4         | 0.31%   |
| Toshiba DT01ACA100 1TB             | 4         | 0.31%   |
| SPCC Solid State Disk 512GB        | 4         | 0.31%   |
| Seagate ST31000528AS 1TB           | 4         | 0.31%   |
| Seagate ST2000LM007-1R8174 2TB     | 4         | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB     | 4         | 0.31%   |
| Seagate ST1000LM049-2GH172 1TB     | 4         | 0.31%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 0.31%   |
| SanDisk SSD PLUS 240GB             | 4         | 0.31%   |
| Samsung SSD 980 1TB                | 4         | 0.31%   |
| Samsung SSD 970 EVO 500GB          | 4         | 0.31%   |
| Samsung SSD 860 EVO M.2 500GB      | 4         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 137       | 180    | 39.14%  |
| WDC                 | 93        | 121    | 26.57%  |
| Toshiba             | 50        | 57     | 14.29%  |
| Hitachi             | 23        | 30     | 6.57%   |
| HGST                | 19        | 19     | 5.43%   |
| Samsung Electronics | 12        | 15     | 3.43%   |
| Apple               | 7         | 7      | 2%      |
| Fujitsu             | 2         | 3      | 0.57%   |
| Unknown             | 1         | 1      | 0.29%   |
| SATAFIRM            | 1         | 1      | 0.29%   |
| SABRENT             | 1         | 2      | 0.29%   |
| Maxtor              | 1         | 1      | 0.29%   |
| Intenso             | 1         | 1      | 0.29%   |
| HGST HDN            | 1         | 1      | 0.29%   |
| ASMT                | 1         | 2      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 88        | 105    | 23.1%   |
| Kingston            | 50        | 56     | 13.12%  |
| Crucial             | 44        | 61     | 11.55%  |
| SanDisk             | 36        | 41     | 9.45%   |
| WDC                 | 22        | 26     | 5.77%   |
| A-DATA Technology   | 16        | 18     | 4.2%    |
| Apple               | 14        | 15     | 3.67%   |
| PNY                 | 10        | 11     | 2.62%   |
| China               | 9         | 10     | 2.36%   |
| SPCC                | 7         | 8      | 1.84%   |
| Intel               | 7         | 7      | 1.84%   |
| SK hynix            | 5         | 5      | 1.31%   |
| Micron Technology   | 5         | 5      | 1.31%   |
| LITEONIT            | 5         | 5      | 1.31%   |
| LITEON              | 4         | 4      | 1.05%   |
| Lexar               | 4         | 4      | 1.05%   |
| Toshiba             | 3         | 3      | 0.79%   |
| Patriot             | 3         | 3      | 0.79%   |
| OCZ                 | 3         | 3      | 0.79%   |
| MyDigitalSSD        | 3         | 3      | 0.79%   |
| KingSpec            | 3         | 3      | 0.79%   |
| Intenso             | 3         | 3      | 0.79%   |
| Hewlett-Packard     | 3         | 3      | 0.79%   |
| PNY USB             | 2         | 2      | 0.52%   |
| Mushkin             | 2         | 3      | 0.52%   |
| Apacer              | 2         | 4      | 0.52%   |
| W800S               | 1         | 1      | 0.26%   |
| USB3.0              | 1         | 1      | 0.26%   |
| TwinMOS             | 1         | 1      | 0.26%   |
| Transcend           | 1         | 2      | 0.26%   |
| TO Exter            | 1         | 1      | 0.26%   |
| Seagate             | 1         | 1      | 0.26%   |
| Ramaxel Technology  | 1         | 1      | 0.26%   |
| Radeon              | 1         | 1      | 0.26%   |
| PUSKILL             | 1         | 1      | 0.26%   |
| Phison              | 1         | 1      | 0.26%   |
| OWC                 | 1         | 1      | 0.26%   |
| Maxtor              | 1         | 1      | 0.26%   |
| Leven               | 1         | 1      | 0.26%   |
| KingFast            | 1         | 1      | 0.26%   |
| KingDian            | 1         | 1      | 0.26%   |
| KINGBANK            | 1         | 1      | 0.26%   |
| INTEL SS            | 1         | 1      | 0.26%   |
| Inland              | 1         | 1      | 0.26%   |
| HS-SSD-E100N        | 1         | 1      | 0.26%   |
| Gigabyte Technology | 1         | 1      | 0.26%   |
| Fujitsu             | 1         | 1      | 0.26%   |
| FORESEE             | 1         | 2      | 0.26%   |
| Corsair             | 1         | 2      | 0.26%   |
| BHT                 | 1         | 1      | 0.26%   |
| ASMT                | 1         | 1      | 0.26%   |
| AFOX                | 1         | 1      | 0.26%   |
| Aarvex              | 1         | 1      | 0.26%   |
| Unknown             | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 344       | 468    | 33.76%  |
| SSD     | 335       | 442    | 32.88%  |
| HDD     | 297       | 441    | 29.15%  |
| Unknown | 24        | 27     | 2.36%   |
| MMC     | 19        | 22     | 1.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 513       | 857    | 55.64%  |
| NVMe | 344       | 465    | 37.31%  |
| SAS  | 46        | 56     | 4.99%   |
| MMC  | 19        | 22     | 2.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 348       | 450    | 50.8%   |
| 0.51-1.0   | 198       | 265    | 28.91%  |
| 1.01-2.0   | 90        | 105    | 13.14%  |
| 3.01-4.0   | 22        | 27     | 3.21%   |
| 2.01-3.0   | 14        | 17     | 2.04%   |
| 4.01-10.0  | 12        | 16     | 1.75%   |
| 10.01-20.0 | 1         | 3      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 207       | 27.53%  |
| 251-500        | 191       | 25.4%   |
| 501-1000       | 150       | 19.95%  |
| 1001-2000      | 75        | 9.97%   |
| More than 3000 | 44        | 5.85%   |
| 2001-3000      | 23        | 3.06%   |
| 51-100         | 22        | 2.93%   |
| 21-50          | 18        | 2.39%   |
| 1-20           | 17        | 2.26%   |
| Unknown        | 5         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 232       | 30.37%  |
| 21-50          | 175       | 22.91%  |
| 101-250        | 113       | 14.79%  |
| 51-100         | 91        | 11.91%  |
| 251-500        | 66        | 8.64%   |
| 501-1000       | 36        | 4.71%   |
| 1001-2000      | 24        | 3.14%   |
| More than 3000 | 16        | 2.09%   |
| 2001-3000      | 6         | 0.79%   |
| Unknown        | 5         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5001AALS-00J7B1 500GB           | 1         | 1      | 4.17%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 4.17%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 4.17%   |
| WDC WD1001FALS-00E8B0 1TB             | 1         | 1      | 4.17%   |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 4.17%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 1         | 1      | 4.17%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 4.17%   |
| Seagate ST500LM030-2E717D 500GB       | 1         | 1      | 4.17%   |
| Seagate ST5000LM000-2AN170 5TB        | 1         | 1      | 4.17%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 4.17%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 850 PRO 256GB | 1         | 1      | 4.17%   |
| Lexar 1TB SSD                         | 1         | 1      | 4.17%   |
| Leven JAJS600M256C 256GB SSD          | 1         | 1      | 4.17%   |
| Kingston SV300S37A240G 240GB SSD      | 1         | 1      | 4.17%   |
| Intel SSDPEKNW010T8 1TB               | 1         | 1      | 4.17%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 2      | 4.17%   |
| Hitachi HDP725050GLA360 500GB         | 1         | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 4.17%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 4.17%   |
| A-DATA Technology SU800 512GB SSD     | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 25%     |
| WDC                 | 5         | 5      | 20.83%  |
| Hitachi             | 2         | 3      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| SK hynix            | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Lexar               | 1         | 1      | 4.17%   |
| Leven               | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 37.5%   |
| WDC     | 5         | 5      | 31.25%  |
| Hitachi | 2         | 3      | 12.5%   |
| HGST    | 2         | 2      | 12.5%   |
| Toshiba | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 66.67%  |
| SSD  | 5         | 5      | 20.83%  |
| NVMe | 3         | 3      | 12.5%   |

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
| Detected | 608       | 1134   | 77.16%  |
| Works    | 157       | 241    | 19.92%  |
| Malfunc  | 23        | 25     | 2.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 439       | 41.81%  |
| AMD                            | 188       | 17.9%   |
| Samsung Electronics            | 145       | 13.81%  |
| SanDisk                        | 61        | 5.81%   |
| SK hynix                       | 32        | 3.05%   |
| Phison Electronics             | 30        | 2.86%   |
| Micron Technology              | 16        | 1.52%   |
| Micron/Crucial Technology      | 15        | 1.43%   |
| Toshiba America Info Systems   | 14        | 1.33%   |
| Silicon Motion                 | 14        | 1.33%   |
| Kingston Technology Company    | 14        | 1.33%   |
| ASMedia Technology             | 13        | 1.24%   |
| Nvidia                         | 12        | 1.14%   |
| ADATA Technology               | 9         | 0.86%   |
| Marvell Technology Group       | 8         | 0.76%   |
| KIOXIA                         | 7         | 0.67%   |
| Union Memory (Shenzhen)        | 4         | 0.38%   |
| Solid State Storage Technology | 4         | 0.38%   |
| Shenzhen Longsys Electronics   | 3         | 0.29%   |
| Seagate Technology             | 3         | 0.29%   |
| Realtek Semiconductor          | 3         | 0.29%   |
| JMicron Technology             | 3         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.19%   |
| Lite-On Technology             | 2         | 0.19%   |
| Apple                          | 2         | 0.19%   |
| Yangtze Memory Technologies    | 1         | 0.1%    |
| VIA Technologies               | 1         | 0.1%    |
| Unknown                        | 1         | 0.1%    |
| Silicon Image                  | 1         | 0.1%    |
| LSI Logic / Symbios Logic      | 1         | 0.1%    |
| Hewlett-Packard                | 1         | 0.1%    |
| Broadcom / LSI                 | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 143       | 12.23%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 76        | 6.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 36        | 3.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 32        | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 28        | 2.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 27        | 2.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 27        | 2.31%   |
| Samsung NVMe SSD Controller 980                                                         | 25        | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23        | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 23        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 22        | 1.88%   |
| SK hynix Gold P31 SSD                                                                   | 21        | 1.8%    |
| AMD 500 Series Chipset SATA Controller                                                  | 21        | 1.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19        | 1.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 18        | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 17        | 1.45%   |
| Micron Non-Volatile memory controller                                                   | 16        | 1.37%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16        | 1.37%   |
| Phison E12 NVMe Controller                                                              | 15        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 15        | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 14        | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 13        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 13        | 1.11%   |
| Intel SSD 660P Series                                                                   | 12        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 12        | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12        | 1.03%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11        | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11        | 0.94%   |
| SanDisk Non-Volatile memory controller                                                  | 10        | 0.86%   |
| Samsung Electronics SATA controller                                                     | 10        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 9         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 0.77%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 8         | 0.68%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 8         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8         | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 7         | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                                 | 7         | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6         | 0.51%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 6         | 0.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 0.51%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 0.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 0.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 0.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6         | 0.51%   |
| SK hynix Non-Volatile memory controller                                                 | 5         | 0.43%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5         | 0.43%   |
| Phison PS5013 E13 NVMe Controller                                                       | 5         | 0.43%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5         | 0.43%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5         | 0.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 551       | 54.02%  |
| NVMe | 345       | 33.82%  |
| RAID | 67        | 6.57%   |
| IDE  | 55        | 5.39%   |
| SAS  | 2         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 509       | 68.51%  |
| AMD    | 234       | 31.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 16        | 2.15%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 15        | 2.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.35%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 10        | 1.35%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.94%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 0.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.81%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 6         | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.81%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 6         | 0.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 5         | 0.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.67%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 4         | 0.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.54%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.54%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 4         | 0.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.54%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 4         | 0.54%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 4         | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 4         | 0.54%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.54%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.54%   |
| AMD FX-8350 Eight-Core Processor              | 4         | 0.54%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 4         | 0.54%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.4%    |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3         | 0.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.4%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.4%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.4%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.4%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.4%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.4%    |
| Intel Core i5-9600K CPU @ 3.70GHz             | 3         | 0.4%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.4%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 0.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 176       | 23.69%  |
| Intel Core i5           | 145       | 19.52%  |
| AMD Ryzen 5             | 74        | 9.96%   |
| AMD Ryzen 7             | 64        | 8.61%   |
| Other                   | 63        | 8.48%   |
| Intel Core i3           | 42        | 5.65%   |
| AMD Ryzen 9             | 32        | 4.31%   |
| Intel Core 2 Duo        | 18        | 2.42%   |
| Intel Celeron           | 14        | 1.88%   |
| Intel Xeon              | 13        | 1.75%   |
| Intel Core i9           | 12        | 1.62%   |
| Intel Pentium           | 9         | 1.21%   |
| AMD Ryzen 3             | 8         | 1.08%   |
| AMD A8                  | 8         | 1.08%   |
| AMD FX                  | 7         | 0.94%   |
| AMD A6                  | 7         | 0.94%   |
| AMD A10                 | 6         | 0.81%   |
| Intel Core 2 Quad       | 5         | 0.67%   |
| AMD Ryzen 7 PRO         | 5         | 0.67%   |
| Intel Pentium Gold      | 3         | 0.4%    |
| Intel Pentium Dual-Core | 3         | 0.4%    |
| AMD Ryzen Threadripper  | 3         | 0.4%    |
| Intel Core 2            | 2         | 0.27%   |
| AMD Ryzen 5 PRO         | 2         | 0.27%   |
| AMD Phenom              | 2         | 0.27%   |
| AMD Athlon              | 2         | 0.27%   |
| Intel Pentium Silver    | 1         | 0.13%   |
| Intel Pentium Dual      | 1         | 0.13%   |
| Intel Pentium D         | 1         | 0.13%   |
| Intel Core m5           | 1         | 0.13%   |
| Intel Core m3           | 1         | 0.13%   |
| Intel Atom              | 1         | 0.13%   |
| AMD Turion 64 X2 Mobile | 1         | 0.13%   |
| AMD Sempron             | 1         | 0.13%   |
| AMD PRO A10             | 1         | 0.13%   |
| AMD Phenom II X6        | 1         | 0.13%   |
| AMD Phenom II X4        | 1         | 0.13%   |
| AMD Phenom II X3        | 1         | 0.13%   |
| AMD Phenom II           | 1         | 0.13%   |
| AMD E2                  | 1         | 0.13%   |
| AMD E                   | 1         | 0.13%   |
| AMD Athlon X2           | 1         | 0.13%   |
| AMD Athlon II X4        | 1         | 0.13%   |
| AMD Athlon II X2        | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 249       | 33.51%  |
| 2      | 217       | 29.21%  |
| 8      | 112       | 15.07%  |
| 6      | 111       | 14.94%  |
| 12     | 20        | 2.69%   |
| 16     | 14        | 1.88%   |
| 10     | 6         | 0.81%   |
| 14     | 4         | 0.54%   |
| 3      | 4         | 0.54%   |
| 1      | 3         | 0.4%    |
| 32     | 2         | 0.27%   |
| 24     | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 739       | 99.46%  |
| 2      | 4         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 599       | 80.62%  |
| 1      | 144       | 19.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 743       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 580       | 77.96%  |
| 0x0a50000c | 12        | 1.61%   |
| 0x806c1    | 10        | 1.34%   |
| 0x806d1    | 9         | 1.21%   |
| 0x806ec    | 8         | 1.08%   |
| 0x08701021 | 7         | 0.94%   |
| 0x906ea    | 6         | 0.81%   |
| 0x0800820d | 6         | 0.81%   |
| 0x506e3    | 5         | 0.67%   |
| 0x40651    | 5         | 0.67%   |
| 0x306c3    | 5         | 0.67%   |
| 0x306a9    | 5         | 0.67%   |
| 0x08608103 | 5         | 0.67%   |
| 0x08600106 | 5         | 0.67%   |
| 0x906e9    | 4         | 0.54%   |
| 0x806ea    | 4         | 0.54%   |
| 0x806e9    | 4         | 0.54%   |
| 0x706e5    | 4         | 0.54%   |
| 0x406e3    | 4         | 0.54%   |
| 0x08108109 | 4         | 0.54%   |
| 0xa0652    | 3         | 0.4%    |
| 0x906ec    | 3         | 0.4%    |
| 0x306d4    | 3         | 0.4%    |
| 0x206a7    | 3         | 0.4%    |
| 0x0a404101 | 3         | 0.4%    |
| 0x0810100b | 3         | 0.4%    |
| 0x906a3    | 2         | 0.27%   |
| 0x90672    | 2         | 0.27%   |
| 0x806eb    | 2         | 0.27%   |
| 0x806c2    | 2         | 0.27%   |
| 0x0a201016 | 2         | 0.27%   |
| 0x08600104 | 2         | 0.27%   |
| 0x08600103 | 2         | 0.27%   |
| 0x08001138 | 2         | 0.27%   |
| 0x08001137 | 2         | 0.27%   |
| 0xa0660    | 1         | 0.13%   |
| 0xa0655    | 1         | 0.13%   |
| 0xa0653    | 1         | 0.13%   |
| 0x50657    | 1         | 0.13%   |
| 0x30678    | 1         | 0.13%   |
| 0x1067a    | 1         | 0.13%   |
| 0x10676    | 1         | 0.13%   |
| 0x0a201006 | 1         | 0.13%   |
| 0x08701013 | 1         | 0.13%   |
| 0x08301039 | 1         | 0.13%   |
| 0x08101016 | 1         | 0.13%   |
| 0x07030105 | 1         | 0.13%   |
| 0x06006705 | 1         | 0.13%   |
| 0x0600611a | 1         | 0.13%   |
| 0x06003106 | 1         | 0.13%   |
| 0x06000852 | 1         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 120       | 16.15%  |
| Haswell          | 70        | 9.42%   |
| Zen 3            | 69        | 9.29%   |
| Zen 2            | 55        | 7.4%    |
| Unknown          | 49        | 6.59%   |
| Skylake          | 45        | 6.06%   |
| SandyBridge      | 43        | 5.79%   |
| IvyBridge        | 41        | 5.52%   |
| Zen+             | 30        | 4.04%   |
| CometLake        | 28        | 3.77%   |
| TigerLake        | 25        | 3.36%   |
| Penryn           | 25        | 3.36%   |
| Broadwell        | 25        | 3.36%   |
| Icelake          | 17        | 2.29%   |
| Zen              | 14        | 1.88%   |
| Westmere         | 13        | 1.75%   |
| Piledriver       | 11        | 1.48%   |
| Silvermont       | 8         | 1.08%   |
| Nehalem          | 8         | 1.08%   |
| K10              | 8         | 1.08%   |
| Excavator        | 8         | 1.08%   |
| Puma             | 7         | 0.94%   |
| Core             | 5         | 0.67%   |
| Steamroller      | 4         | 0.54%   |
| Goldmont plus    | 3         | 0.4%    |
| Alderlake Hybrid | 3         | 0.4%    |
| K8 Hammer        | 2         | 0.27%   |
| K10 Llano        | 2         | 0.27%   |
| Goldmont         | 2         | 0.27%   |
| NetBurst         | 1         | 0.13%   |
| Jaguar           | 1         | 0.13%   |
| Bobcat           | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 370       | 40.84%  |
| Nvidia                     | 307       | 33.89%  |
| AMD                        | 228       | 25.17%  |
| Matrox Electronics Systems | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 3.01%   |
| AMD Cezanne                                                                              | 27        | 2.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 2.58%   |
| AMD Renoir                                                                               | 18        | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 1.83%   |
| AMD Lucienne                                                                             | 17        | 1.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 16        | 1.72%   |
| Intel HD Graphics 620                                                                    | 16        | 1.72%   |
| Intel UHD Graphics 620                                                                   | 15        | 1.61%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.51%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 13        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 1.4%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.29%   |
| Intel HD Graphics 530                                                                    | 11        | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.18%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 10        | 1.08%   |
| Intel HD Graphics 630                                                                    | 10        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 9         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 7         | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.65%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.65%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 0.65%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 6         | 0.65%   |
| AMD Barcelo                                                                              | 6         | 0.65%   |
| Nvidia TU117M                                                                            | 5         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 5         | 0.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 5         | 0.54%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.54%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 5         | 0.54%   |
| Intel HD Graphics 6000                                                                   | 5         | 0.54%   |
| Intel AlderLake-S GT1                                                                    | 5         | 0.54%   |
| AMD Rembrandt [Radeon 680M]                                                              | 5         | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.54%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 5         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.43%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 4         | 0.43%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 4         | 0.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.43%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 236       | 31.51%  |
| 1 x AMD              | 174       | 23.23%  |
| 1 x Nvidia           | 166       | 22.16%  |
| Intel + Nvidia       | 110       | 14.69%  |
| AMD + Nvidia         | 25        | 3.34%   |
| 2 x AMD              | 14        | 1.87%   |
| Intel + AMD          | 14        | 1.87%   |
| 2 x Nvidia           | 6         | 0.8%    |
| Other                | 1         | 0.13%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.13%   |
| 1 x Matrox           | 1         | 0.13%   |
| AMD + 2 x Nvidia     | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 473       | 63.15%  |
| Proprietary | 259       | 34.58%  |
| Unknown     | 17        | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 541       | 72.04%  |
| 7.01-8.0   | 47        | 6.26%   |
| 3.01-4.0   | 37        | 4.93%   |
| 1.01-2.0   | 34        | 4.53%   |
| 5.01-6.0   | 29        | 3.86%   |
| 8.01-16.0  | 25        | 3.33%   |
| 0.01-0.5   | 21        | 2.8%    |
| 2.01-3.0   | 8         | 1.07%   |
| 0.51-1.0   | 6         | 0.8%    |
| 16.01-24.0 | 2         | 0.27%   |
| 32.01-64.0 | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 98        | 11.49%  |
| AU Optronics            | 96        | 11.25%  |
| BOE                     | 89        | 10.43%  |
| LG Display              | 82        | 9.61%   |
| Chimei Innolux          | 73        | 8.56%   |
| Dell                    | 65        | 7.62%   |
| Goldstar                | 51        | 5.98%   |
| Apple                   | 32        | 3.75%   |
| Hewlett-Packard         | 24        | 2.81%   |
| AOC                     | 23        | 2.7%    |
| Sharp                   | 21        | 2.46%   |
| Acer                    | 21        | 2.46%   |
| Ancor Communications    | 19        | 2.23%   |
| ASUSTek Computer        | 17        | 1.99%   |
| BenQ                    | 16        | 1.88%   |
| PANDA                   | 11        | 1.29%   |
| Lenovo                  | 10        | 1.17%   |
| Iiyama                  | 8         | 0.94%   |
| ViewSonic               | 5         | 0.59%   |
| Sceptre Tech            | 5         | 0.59%   |
| NEC Computers           | 5         | 0.59%   |
| MSI                     | 5         | 0.59%   |
| Gigabyte Technology     | 5         | 0.59%   |
| Unknown                 | 4         | 0.47%   |
| Philips                 | 4         | 0.47%   |
| InfoVision              | 3         | 0.35%   |
| CSO                     | 3         | 0.35%   |
| Chi Mei Optoelectronics | 3         | 0.35%   |
| Vizio                   | 2         | 0.23%   |
| Viotek                  | 2         | 0.23%   |
| Vestel Elektronik       | 2         | 0.23%   |
| Toshiba                 | 2         | 0.23%   |
| TMX                     | 2         | 0.23%   |
| Sony                    | 2         | 0.23%   |
| ONN                     | 2         | 0.23%   |
| LG Electronics          | 2         | 0.23%   |
| JDI                     | 2         | 0.23%   |
| ITE                     | 2         | 0.23%   |
| Hitachi                 | 2         | 0.23%   |
| Eizo                    | 2         | 0.23%   |
| ___                     | 1         | 0.12%   |
| VOXICON                 | 1         | 0.12%   |
| Valve                   | 1         | 0.12%   |
| Unknown (XXX)           | 1         | 0.12%   |
| TCL                     | 1         | 0.12%   |
| STD                     | 1         | 0.12%   |
| SKY                     | 1         | 0.12%   |
| SGT                     | 1         | 0.12%   |
| RTK                     | 1         | 0.12%   |
| Positivo                | 1         | 0.12%   |
| Plain Tree Systems      | 1         | 0.12%   |
| Pixio                   | 1         | 0.12%   |
| Pioneer                 | 1         | 0.12%   |
| Panasonic               | 1         | 0.12%   |
| Orion                   | 1         | 0.12%   |
| Onkyo                   | 1         | 0.12%   |
| OEM                     | 1         | 0.12%   |
| MiTAC                   | 1         | 0.12%   |
| Mi                      | 1         | 0.12%   |
| Medion Akoya            | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 6         | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.46%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 4         | 0.46%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.46%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 3         | 0.34%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 3         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.34%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3         | 0.34%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 3         | 0.34%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 3         | 0.34%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.34%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.34%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch          | 3         | 0.34%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3         | 0.34%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 2         | 0.23%   |
| Sharp LQ134N1JW55 SHP1558 1920x1200 288x180mm 13.4-inch               | 2         | 0.23%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.23%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.23%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 2         | 0.23%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch         | 2         | 0.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2         | 0.23%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch     | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch | 2         | 0.23%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 2         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.23%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 2         | 0.23%   |
| LG Display LCD Monitor LGD0627 1920x1080 294x165mm 13.3-inch          | 2         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.23%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 2         | 0.23%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 2         | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.23%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 2         | 0.23%   |
| Lenovo LBG AIO PC LEN8000 1920x1080 480x270mm 21.7-inch               | 2         | 0.23%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.23%   |
| Goldstar LG QHD GSM772A 2560x1440 700x390mm 31.5-inch                 | 2         | 0.23%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 2         | 0.23%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 0.23%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch      | 2         | 0.23%   |
| Dell U2212HM DELD048 1920x1080 475x267mm 21.5-inch                    | 2         | 0.23%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                   | 2         | 0.23%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 396       | 48.77%  |
| 1366x768 (WXGA)    | 121       | 14.9%   |
| 3840x2160 (4K)     | 62        | 7.64%   |
| 2560x1440 (QHD)    | 47        | 5.79%   |
| 1600x900 (HD+)     | 29        | 3.57%   |
| 1920x1200 (WUXGA)  | 20        | 2.46%   |
| 3440x1440          | 17        | 2.09%   |
| 1680x1050 (WSXGA+) | 15        | 1.85%   |
| 1440x900 (WXGA+)   | 14        | 1.72%   |
| 2560x1600          | 13        | 1.6%    |
| 2560x1080          | 13        | 1.6%    |
| 1280x800 (WXGA)    | 10        | 1.23%   |
| 1280x1024 (SXGA)   | 10        | 1.23%   |
| 2880x1800          | 6         | 0.74%   |
| 3840x1080          | 5         | 0.62%   |
| 1360x768           | 4         | 0.49%   |
| 3840x1600          | 3         | 0.37%   |
| 1920x540           | 3         | 0.37%   |
| Unknown            | 3         | 0.37%   |
| 3840x2400          | 2         | 0.25%   |
| 3000x2000          | 2         | 0.25%   |
| 2736x1824          | 2         | 0.25%   |
| 2256x1504          | 2         | 0.25%   |
| 2160x1440          | 2         | 0.25%   |
| 1024x768 (XGA)     | 2         | 0.25%   |
| 3840x1200          | 1         | 0.12%   |
| 3840x1100          | 1         | 0.12%   |
| 3456x2160          | 1         | 0.12%   |
| 3200x2000          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3040x900           | 1         | 0.12%   |
| 1920x1280          | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1280x1080          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 217       | 25.68%  |
| 13      | 98        | 11.6%   |
| 27      | 65        | 7.69%   |
| 24      | 60        | 7.1%    |
| 14      | 59        | 6.98%   |
| 23      | 53        | 6.27%   |
| 17      | 45        | 5.33%   |
| 21      | 39        | 4.62%   |
| 31      | 34        | 4.02%   |
| 34      | 27        | 3.2%    |
| 12      | 19        | 2.25%   |
| Unknown | 15        | 1.78%   |
| 22      | 11        | 1.3%    |
| 32      | 10        | 1.18%   |
| 84      | 9         | 1.07%   |
| 19      | 9         | 1.07%   |
| 16      | 8         | 0.95%   |
| 11      | 8         | 0.95%   |
| 20      | 7         | 0.83%   |
| 18      | 7         | 0.83%   |
| 72      | 6         | 0.71%   |
| 25      | 6         | 0.71%   |
| 48      | 5         | 0.59%   |
| 37      | 4         | 0.47%   |
| 26      | 4         | 0.47%   |
| 54      | 2         | 0.24%   |
| 49      | 2         | 0.24%   |
| 46      | 2         | 0.24%   |
| 35      | 2         | 0.24%   |
| 28      | 2         | 0.24%   |
| 69      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 55      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 47      | 1         | 0.12%   |
| 43      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 30      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 331       | 39.74%  |
| 501-600     | 170       | 20.41%  |
| 201-300     | 76        | 9.12%   |
| 401-500     | 67        | 8.04%   |
| 351-400     | 51        | 6.12%   |
| 601-700     | 46        | 5.52%   |
| 701-800     | 37        | 4.44%   |
| 1501-2000   | 16        | 1.92%   |
| 1001-1500   | 16        | 1.92%   |
| Unknown     | 15        | 1.8%    |
| 801-900     | 7         | 0.84%   |
| 901-1000    | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 608       | 79.17%  |
| 16/10   | 86        | 11.2%   |
| 21/9    | 34        | 4.43%   |
| 5/4     | 10        | 1.3%    |
| 3/2     | 9         | 1.17%   |
| Unknown | 9         | 1.17%   |
| 32/9    | 6         | 0.78%   |
| 4/3     | 4         | 0.52%   |
| 3.40    | 1         | 0.13%   |
| 3.20    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 219       | 26.35%  |
| 201-250        | 124       | 14.92%  |
| 81-90          | 122       | 14.68%  |
| 351-500        | 74        | 8.9%    |
| 301-350        | 69        | 8.3%    |
| 121-130        | 40        | 4.81%   |
| 71-80          | 36        | 4.33%   |
| 251-300        | 27        | 3.25%   |
| 151-200        | 26        | 3.13%   |
| More than 1000 | 22        | 2.65%   |
| 61-70          | 16        | 1.93%   |
| Unknown        | 15        | 1.81%   |
| 501-1000       | 14        | 1.68%   |
| 141-150        | 12        | 1.44%   |
| 51-60          | 9         | 1.08%   |
| 111-120        | 4         | 0.48%   |
| 91-100         | 2         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 266       | 32.84%  |
| 51-100        | 236       | 29.14%  |
| 101-120       | 200       | 24.69%  |
| 161-240       | 53        | 6.54%   |
| More than 240 | 22        | 2.72%   |
| 1-50          | 18        | 2.22%   |
| Unknown       | 15        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 583       | 77.63%  |
| 2     | 131       | 17.44%  |
| 0     | 20        | 2.66%   |
| 3     | 16        | 2.13%   |
| 6     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 400       | 34.72%  |
| Intel                                 | 381       | 33.07%  |
| Qualcomm Atheros                      | 135       | 11.72%  |
| Broadcom                              | 61        | 5.3%    |
| MediaTek                              | 29        | 2.52%   |
| Broadcom Limited                      | 23        | 2%      |
| TP-Link                               | 12        | 1.04%   |
| Marvell Technology Group              | 9         | 0.78%   |
| Ralink Technology                     | 8         | 0.69%   |
| Samsung Electronics                   | 7         | 0.61%   |
| Nvidia                                | 7         | 0.61%   |
| Ralink                                | 6         | 0.52%   |
| ASIX Electronics                      | 6         | 0.52%   |
| Xiaomi                                | 5         | 0.43%   |
| NetGear                               | 5         | 0.43%   |
| DisplayLink                           | 5         | 0.43%   |
| Dell                                  | 5         | 0.43%   |
| ASUSTek Computer                      | 5         | 0.43%   |
| Aquantia                              | 5         | 0.43%   |
| Microsoft                             | 4         | 0.35%   |
| Qualcomm Atheros Communications       | 3         | 0.26%   |
| OPPO Electronics                      | 2         | 0.17%   |
| InterBiometrics                       | 2         | 0.17%   |
| Huawei Technologies                   | 2         | 0.17%   |
| Hewlett-Packard                       | 2         | 0.17%   |
| D-Link                                | 2         | 0.17%   |
| STMicroelectronics                    | 1         | 0.09%   |
| Sitecom Europe                        | 1         | 0.09%   |
| SIEMENS                               | 1         | 0.09%   |
| Qualcomm                              | 1         | 0.09%   |
| Prolific Technology                   | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.09%   |
| Motorola PCS                          | 1         | 0.09%   |
| Micro Star International              | 1         | 0.09%   |
| Mellanox Technologies                 | 1         | 0.09%   |
| Lenovo                                | 1         | 0.09%   |
| JMicron Technology                    | 1         | 0.09%   |
| IMC Networks                          | 1         | 0.09%   |
| Hyperkin                              | 1         | 0.09%   |
| Google                                | 1         | 0.09%   |
| Gemtek                                | 1         | 0.09%   |
| Ericsson Business Mobile Networks     | 1         | 0.09%   |
| D-Link System                         | 1         | 0.09%   |
| Belkin Components                     | 1         | 0.09%   |
| AVM                                   | 1         | 0.09%   |
| Accton Technology                     | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 258       | 19.04%  |
| Intel Wi-Fi 6 AX200                                               | 62        | 4.58%   |
| Intel I211 Gigabit Network Connection                             | 43        | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 1.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 19        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 1.33%   |
| Intel Wireless 8265 / 8275                                        | 18        | 1.33%   |
| Intel Wireless 7265                                               | 17        | 1.25%   |
| Intel Ethernet Controller I225-V                                  | 17        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 17        | 1.25%   |
| Intel Wireless 7260                                               | 16        | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.03%   |
| Intel Wireless 8260                                               | 13        | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 0.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 13        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 10        | 0.74%   |
| Realtek 802.11ac NIC                                              | 9         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 0.59%   |
| Intel Wireless-AC 9260                                            | 8         | 0.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 8         | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 6         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 6         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.37%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.37%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 303       | 45.91%  |
| Qualcomm Atheros                      | 107       | 16.21%  |
| Realtek Semiconductor                 | 93        | 14.09%  |
| Broadcom                              | 47        | 7.12%   |
| MediaTek                              | 28        | 4.24%   |
| Broadcom Limited                      | 22        | 3.33%   |
| TP-Link                               | 10        | 1.52%   |
| Ralink Technology                     | 8         | 1.21%   |
| Ralink                                | 6         | 0.91%   |
| NetGear                               | 5         | 0.76%   |
| Dell                                  | 5         | 0.76%   |
| Microsoft                             | 4         | 0.61%   |
| Marvell Technology Group              | 4         | 0.61%   |
| ASUSTek Computer                      | 4         | 0.61%   |
| Qualcomm Atheros Communications       | 3         | 0.45%   |
| D-Link                                | 2         | 0.3%    |
| Sitecom Europe                        | 1         | 0.15%   |
| Micro Star International              | 1         | 0.15%   |
| IMC Networks                          | 1         | 0.15%   |
| Gemtek                                | 1         | 0.15%   |
| D-Link System                         | 1         | 0.15%   |
| Belkin Components                     | 1         | 0.15%   |
| AVM                                   | 1         | 0.15%   |
| Accton Technology                     | 1         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 62        | 9.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 3.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19        | 2.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 19        | 2.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 2.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 2.7%    |
| Intel Wireless 8265 / 8275                                     | 18        | 2.7%    |
| Intel Wireless 7265                                            | 17        | 2.55%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 2.55%   |
| Intel Wireless 7260                                            | 16        | 2.4%    |
| Intel Wi-Fi 6 AX201                                            | 16        | 2.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 16        | 2.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 15        | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 14        | 2.1%    |
| Intel Wireless 8260                                            | 13        | 1.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 13        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 10        | 1.5%    |
| Realtek 802.11ac NIC                                           | 9         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8         | 1.2%    |
| Intel Wireless-AC 9260                                         | 8         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 8         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 0.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6         | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 0.75%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.6%    |
| Realtek Realtek Network controller                             | 4         | 0.6%    |
| MediaTek WLAN controller                                       | 4         | 0.6%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 4         | 0.6%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.45%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 0.45%   |
| NetGear A6210                                                  | 3         | 0.45%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3         | 0.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.45%   |
| Intel Wireless Gigabit 17265                                   | 3         | 0.45%   |
| Intel Wireless 3165                                            | 3         | 0.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.45%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.45%   |
| Dell Hub of E-Port Replicator                                  | 3         | 0.45%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 0.45%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 355       | 52.91%  |
| Intel                         | 189       | 28.17%  |
| Qualcomm Atheros              | 42        | 6.26%   |
| Broadcom                      | 29        | 4.32%   |
| Samsung Electronics           | 7         | 1.04%   |
| Nvidia                        | 7         | 1.04%   |
| ASIX Electronics              | 6         | 0.89%   |
| Xiaomi                        | 5         | 0.75%   |
| Marvell Technology Group      | 5         | 0.75%   |
| DisplayLink                   | 5         | 0.75%   |
| Aquantia                      | 5         | 0.75%   |
| TP-Link                       | 2         | 0.3%    |
| OPPO Electronics              | 2         | 0.3%    |
| Huawei Technologies           | 2         | 0.3%    |
| Qualcomm                      | 1         | 0.15%   |
| OnePlus Technology (Shenzhen) | 1         | 0.15%   |
| Motorola PCS                  | 1         | 0.15%   |
| Mellanox Technologies         | 1         | 0.15%   |
| Lenovo                        | 1         | 0.15%   |
| JMicron Technology            | 1         | 0.15%   |
| Hewlett-Packard               | 1         | 0.15%   |
| Google                        | 1         | 0.15%   |
| Broadcom Limited              | 1         | 0.15%   |
| ASUSTek Computer              | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 258       | 38%     |
| Intel I211 Gigabit Network Connection                             | 43        | 6.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 5.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 3.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 3.09%   |
| Intel Ethernet Controller I225-V                                  | 17        | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 15        | 2.21%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 2.06%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 1.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.03%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.74%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.29%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.29%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 2         | 0.29%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.29%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.29%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.29%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.29%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.29%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.29%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.29%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.29%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.29%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.29%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.29%   |
| Huawei LYA-L09                                                    | 2         | 0.29%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.29%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.29%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 0.29%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.29%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 626       | 49.76%  |
| Ethernet | 623       | 49.52%  |
| Modem    | 7         | 0.56%   |
| Unknown  | 2         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 468       | 60.62%  |
| Ethernet | 304       | 39.38%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 416       | 55.91%  |
| 1     | 292       | 39.25%  |
| 3     | 25        | 3.36%   |
| 0     | 8         | 1.08%   |
| 4     | 3         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 523       | 70.2%   |
| Yes  | 222       | 29.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 267       | 50.66%  |
| Qualcomm Atheros Communications | 46        | 8.73%   |
| Apple                           | 40        | 7.59%   |
| Realtek Semiconductor           | 34        | 6.45%   |
| IMC Networks                    | 30        | 5.69%   |
| Foxconn / Hon Hai               | 21        | 3.98%   |
| Cambridge Silicon Radio         | 20        | 3.8%    |
| Broadcom                        | 20        | 3.8%    |
| Lite-On Technology              | 16        | 3.04%   |
| ASUSTek Computer                | 9         | 1.71%   |
| Toshiba                         | 4         | 0.76%   |
| Marvell Semiconductor           | 4         | 0.76%   |
| Hewlett-Packard                 | 3         | 0.57%   |
| Dell                            | 3         | 0.57%   |
| Realtek                         | 2         | 0.38%   |
| Opticis                         | 2         | 0.38%   |
| TP-Link                         | 1         | 0.19%   |
| Ralink Technology               | 1         | 0.19%   |
| Ralink                          | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| MediaTek                        | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 63        | 11.95%  |
| Intel AX201 Bluetooth                               | 61        | 11.57%  |
| Intel AX200 Bluetooth                               | 57        | 10.82%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 40        | 7.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 31        | 5.88%   |
| Realtek Bluetooth Radio                             | 27        | 5.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 3.8%    |
| Apple Bluetooth USB Host Controller                 | 19        | 3.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 2.85%   |
| Intel Bluetooth Device                              | 15        | 2.85%   |
| Apple Bluetooth Host Controller                     | 15        | 2.85%   |
| IMC Networks Wireless_Device                        | 13        | 2.47%   |
| Intel AX210 Bluetooth                               | 12        | 2.28%   |
| IMC Networks Bluetooth Device                       | 9         | 1.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 1.71%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 6         | 1.14%   |
| Lite-On Bluetooth Device                            | 4         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.76%   |
| IMC Networks Bluetooth Radio                        | 4         | 0.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.76%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.57%   |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.57%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.57%   |
| Broadcom BCM20702A0                                 | 3         | 0.57%   |
| ASUS Bluetooth Radio                                | 3         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.57%   |
| Apple Bluetooth HCI                                 | 3         | 0.57%   |
| Realtek Bluetooth Radio                             | 2         | 0.38%   |
| Opticis Bluetooth Radio                             | 2         | 0.38%   |
| Lite-On Wireless_Device                             | 2         | 0.38%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.38%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.38%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.38%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.38%   |
| ASUS ASUS USB-BT500                                 | 2         | 0.38%   |
| TP-Link TP-hink UB500 Adapter                       | 1         | 0.19%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.19%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.19%   |
| Toshiba Bluetooth Radio                             | 1         | 0.19%   |
| Toshiba BCM43142A0                                  | 1         | 0.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.19%   |
| Ralink CSR BS8510                                   | 1         | 0.19%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.19%   |
| Micro Star International Bluetooth Device           | 1         | 0.19%   |
| MediaTek Wireless_Device                            | 1         | 0.19%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.19%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.19%   |
| Lite-On Bluetooth Radio                             | 1         | 0.19%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.19%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.19%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 490       | 42.53%  |
| AMD                                  | 270       | 23.44%  |
| Nvidia                               | 241       | 20.92%  |
| C-Media Electronics                  | 18        | 1.56%   |
| Logitech                             | 13        | 1.13%   |
| Kingston Technology                  | 11        | 0.95%   |
| SteelSeries ApS                      | 6         | 0.52%   |
| JMTek                                | 6         | 0.52%   |
| Focusrite-Novation                   | 6         | 0.52%   |
| Creative Labs                        | 6         | 0.52%   |
| GN Netcom                            | 5         | 0.43%   |
| Texas Instruments                    | 4         | 0.35%   |
| Sony                                 | 4         | 0.35%   |
| Razer USA                            | 4         | 0.35%   |
| Micro Star International             | 4         | 0.35%   |
| Corsair                              | 4         | 0.35%   |
| Sennheiser Communications            | 3         | 0.26%   |
| Lenovo                               | 3         | 0.26%   |
| Antlion Audio                        | 3         | 0.26%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.17%   |
| Realtek Semiconductor                | 2         | 0.17%   |
| Hewlett-Packard                      | 2         | 0.17%   |
| Generalplus Technology               | 2         | 0.17%   |
| Creative Technology                  | 2         | 0.17%   |
| ASUSTek Computer                     | 2         | 0.17%   |
| Yamaha                               | 1         | 0.09%   |
| Valve Software                       | 1         | 0.09%   |
| USB MIDI                             | 1         | 0.09%   |
| Unknown                              | 1         | 0.09%   |
| Turtle Beach                         | 1         | 0.09%   |
| TerraTec Electronic                  | 1         | 0.09%   |
| Tenx Technology                      | 1         | 0.09%   |
| Solid State System                   | 1         | 0.09%   |
| Shure                                | 1         | 0.09%   |
| Shenzhen Rapoo Technology            | 1         | 0.09%   |
| SAVITECH                             | 1         | 0.09%   |
| Samsung Electronics                  | 1         | 0.09%   |
| Samson Technologies                  | 1         | 0.09%   |
| Plantronics                          | 1         | 0.09%   |
| Native Instruments                   | 1         | 0.09%   |
| Microsoft                            | 1         | 0.09%   |
| Micronas                             | 1         | 0.09%   |
| Medeli Electronics                   | 1         | 0.09%   |
| Mackie Designs                       | 1         | 0.09%   |
| JOUNIVO JV601                        | 1         | 0.09%   |
| Jieli Technology                     | 1         | 0.09%   |
| iConnectivity                        | 1         | 0.09%   |
| GYROCOM C&C                          | 1         | 0.09%   |
| Google                               | 1         | 0.09%   |
| Giga-Byte Technology                 | 1         | 0.09%   |
| GEMBIRD                              | 1         | 0.09%   |
| FiiO Electronics Technology          | 1         | 0.09%   |
| fifinemicrophone.com                 | 1         | 0.09%   |
| FIFINE Microphones                   | 1         | 0.09%   |
| DEXP BK-20                           | 1         | 0.09%   |
| DCMT Technology                      | 1         | 0.09%   |
| Cambridge Silicon Radio              | 1         | 0.09%   |
| C&T                                  | 1         | 0.09%   |
| Blue Microphones                     | 1         | 0.09%   |
| BEHRINGER International              | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 99        | 7.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 67        | 4.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 59        | 4.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 51        | 3.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 43        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 38        | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33        | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 31        | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                      | 30        | 2.15%   |
| Intel 8 Series HD Audio Controller                                         | 29        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 1.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 24        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24        | 1.72%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 1.65%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 1.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 1.58%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 22        | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 1.5%    |
| Nvidia GA106 High Definition Audio Controller                              | 21        | 1.5%    |
| Intel Comet Lake PCH cAVS                                                  | 21        | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21        | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 20        | 1.43%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 1.29%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 16        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 16        | 1.15%   |
| Nvidia TU104 HD Audio Controller                                           | 15        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 15        | 1.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 13        | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                     | 10        | 0.72%   |
| Nvidia GA102 High Definition Audio Controller                              | 9         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 0.57%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8         | 0.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.57%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.5%    |
| Kingston Technology HyperX 7.1 Audio                                       | 7         | 0.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7         | 0.5%    |
| Nvidia MCP79 High Definition Audio                                         | 6         | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 0.43%   |
| Intel Audio device                                                         | 6         | 0.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 0.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 0.43%   |
| Nvidia TU102 High Definition Audio Controller                              | 5         | 0.36%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.36%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5         | 0.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.36%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5         | 0.36%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 24.74%  |
| SK hynix            | 40        | 20.62%  |
| Micron Technology   | 18        | 9.28%   |
| Corsair             | 18        | 9.28%   |
| Kingston            | 11        | 5.67%   |
| G.Skill             | 10        | 5.15%   |
| Crucial             | 8         | 4.12%   |
| Unknown             | 6         | 3.09%   |
| Unknown             | 6         | 3.09%   |
| Team                | 5         | 2.58%   |
| Smart               | 4         | 2.06%   |
| Neo Forza           | 3         | 1.55%   |
| A-DATA Technology   | 3         | 1.55%   |
| PNY                 | 2         | 1.03%   |
| Avant               | 2         | 1.03%   |
| Unknown (8A02)      | 1         | 0.52%   |
| Timetec             | 1         | 0.52%   |
| Teikon              | 1         | 0.52%   |
| Smart Brazil        | 1         | 0.52%   |
| Ramaxel Technology  | 1         | 0.52%   |
| Patriot Memory      | 1         | 0.52%   |
| GSkill              | 1         | 0.52%   |
| Goldkey             | 1         | 0.52%   |
| Gold Key            | 1         | 0.52%   |
| Elpida              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 6         | 3%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 5         | 2.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 4         | 2%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 4         | 2%      |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 2%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.5%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 3         | 1.5%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 3         | 1.5%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s                 | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 1%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1%      |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 1%      |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 1%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 2         | 1%      |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 2         | 1%      |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s            | 2         | 1%      |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s                | 2         | 1%      |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.5%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.5%    |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                          | 1         | 0.5%    |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                  | 1         | 0.5%    |
| Unknown (8A02) RAM 8G2400MHz 8GB SODIMM DDR4 2667MT/s               | 1         | 0.5%    |
| Timetec RAM 32NUS2R8-32G 32GB SODIMM DDR4 3200MT/s                  | 1         | 0.5%    |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s              | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s                  | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                  | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.5%    |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s               | 1         | 0.5%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 1         | 0.5%    |
| Smart RAM SG564568FG8NWKFSQR 2GB SODIMM DDR2 800MT/s                | 1         | 0.5%    |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s               | 1         | 0.5%    |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 3200MT/s        | 1         | 0.5%    |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 3200MT/s              | 1         | 0.5%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.5%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.5%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PBA 4GB DIMM DDR3 1600MT/s               | 1         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.5%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.5%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.5%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.5%    |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.5%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s    | 1         | 0.5%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 122       | 72.19%  |
| DDR3    | 24        | 14.2%   |
| LPDDR4  | 10        | 5.92%   |
| LPDDR3  | 6         | 3.55%   |
| Unknown | 3         | 1.78%   |
| DDR2    | 2         | 1.18%   |
| SDRAM   | 1         | 0.59%   |
| LPDDR5  | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 101       | 58.72%  |
| DIMM         | 45        | 26.16%  |
| Row Of Chips | 25        | 14.53%  |
| Chip         | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 92        | 51.98%  |
| 4096  | 36        | 20.34%  |
| 16384 | 31        | 17.51%  |
| 32768 | 12        | 6.78%   |
| 2048  | 6         | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 57        | 32.02%  |
| 2667  | 28        | 15.73%  |
| 1600  | 21        | 11.8%   |
| 3600  | 15        | 8.43%   |
| 2133  | 10        | 5.62%   |
| 4267  | 7         | 3.93%   |
| 2400  | 6         | 3.37%   |
| 1333  | 5         | 2.81%   |
| 8400  | 4         | 2.25%   |
| 3466  | 4         | 2.25%   |
| 3266  | 3         | 1.69%   |
| 3000  | 3         | 1.69%   |
| 6400  | 2         | 1.12%   |
| 1867  | 2         | 1.12%   |
| 800   | 2         | 1.12%   |
| 4800  | 1         | 0.56%   |
| 4266  | 1         | 0.56%   |
| 3733  | 1         | 0.56%   |
| 3100  | 1         | 0.56%   |
| 3067  | 1         | 0.56%   |
| 2800  | 1         | 0.56%   |
| 2666  | 1         | 0.56%   |
| 2048  | 1         | 0.56%   |
| 1866  | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 28.57%  |
| Samsung Electronics | 3         | 21.43%  |
| Brother Industries  | 3         | 21.43%  |
| Seiko Epson         | 1         | 7.14%   |
| QinHeng Electronics | 1         | 7.14%   |
| Dymo-CoStar         | 1         | 7.14%   |
| Canon               | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson WF-4830 Series             | 1         | 6.67%   |
| Samsung SCX-3400 Series                | 1         | 6.67%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1         | 6.67%   |
| Samsung M2070 Series                   | 1         | 6.67%   |
| QinHeng CH340S                         | 1         | 6.67%   |
| HP PSC-1315/PSC-1317                   | 1         | 6.67%   |
| HP LaserJet P2035                      | 1         | 6.67%   |
| HP Ink Tank Wireless 410 series        | 1         | 6.67%   |
| HP ENVY Pro 6400 series                | 1         | 6.67%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1         | 6.67%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 6.67%   |
| Canon Pro9000II series                 | 1         | 6.67%   |
| Brother MFC-L2700DW                    | 1         | 6.67%   |
| Brother MFC-5440CN                     | 1         | 6.67%   |
| Brother HL-2130 series                 | 1         | 6.67%   |

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


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LiDE 60 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 100       | 20.49%  |
| Microdia                               | 49        | 10.04%  |
| Acer                                   | 49        | 10.04%  |
| Realtek Semiconductor                  | 43        | 8.81%   |
| IMC Networks                           | 41        | 8.4%    |
| Logitech                               | 30        | 6.15%   |
| Apple                                  | 27        | 5.53%   |
| Sunplus Innovation Technology          | 26        | 5.33%   |
| Quanta                                 | 21        | 4.3%    |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.07%   |
| Suyin                                  | 12        | 2.46%   |
| Samsung Electronics                    | 8         | 1.64%   |
| Syntek                                 | 7         | 1.43%   |
| SunplusIT                              | 6         | 1.23%   |
| Microsoft                              | 6         | 1.23%   |
| Silicon Motion                         | 5         | 1.02%   |
| Luxvisions Innotech Limited            | 5         | 1.02%   |
| Lite-On Technology                     | 4         | 0.82%   |
| Sonix Technology                       | 3         | 0.61%   |
| Generalplus Technology                 | 3         | 0.61%   |
| Alcor Micro                            | 3         | 0.61%   |
| Sunplus IT                             | 2         | 0.41%   |
| Razer USA                              | 2         | 0.41%   |
| Jieli Technology                       | 2         | 0.41%   |
| ARC International                      | 2         | 0.41%   |
| Z-Star Microelectronics                | 1         | 0.2%    |
| YGTek                                  | 1         | 0.2%    |
| XHT-210518                             | 1         | 0.2%    |
| WaveRider Communications               | 1         | 0.2%    |
| Valve Software                         | 1         | 0.2%    |
| Unknown                                | 1         | 0.2%    |
| SJ-180517-N                            | 1         | 0.2%    |
| Ricoh                                  | 1         | 0.2%    |
| Primax Electronics                     | 1         | 0.2%    |
| MacroSilicon                           | 1         | 0.2%    |
| LG Electronics                         | 1         | 0.2%    |
| Importek                               | 1         | 0.2%    |
| icSpring                               | 1         | 0.2%    |
| Hewlett-Packard                        | 1         | 0.2%    |
| GenesysLogic Technology                | 1         | 0.2%    |
| eMeet                                  | 1         | 0.2%    |
| Creative Technology                    | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 20        | 4.06%   |
| Microdia Integrated_Webcam_HD                    | 18        | 3.65%   |
| Chicony Integrated Camera                        | 18        | 3.65%   |
| IMC Networks USB2.0 HD UVC WebCam                | 17        | 3.45%   |
| Chicony HD WebCam                                | 13        | 2.64%   |
| Acer Integrated Camera                           | 11        | 2.23%   |
| Acer HD Webcam                                   | 10        | 2.03%   |
| Apple iPhone 5/5C/5S/6/SE                        | 9         | 1.83%   |
| Acer BisonCam,NB Pro                             | 9         | 1.83%   |
| Samsung Galaxy A5 (MTP)                          | 8         | 1.62%   |
| IMC Networks Integrated Camera                   | 8         | 1.62%   |
| Apple Built-in iSight                            | 8         | 1.62%   |
| Syntek Integrated Camera                         | 7         | 1.42%   |
| Logitech Webcam C270                             | 7         | 1.42%   |
| Sunplus Integrated_Webcam_HD                     | 6         | 1.22%   |
| Quanta HP HD Camera                              | 6         | 1.22%   |
| Microdia Integrated Webcam                       | 6         | 1.22%   |
| Logitech HD Pro Webcam C920                      | 6         | 1.22%   |
| Apple FaceTime HD Camera (Built-in)              | 6         | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam                    | 5         | 1.01%   |
| Chicony USB2.0 Camera                            | 5         | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                  | 5         | 1.01%   |
| Apple FaceTime HD Camera                         | 5         | 1.01%   |
| Suyin HP Truevision HD                           | 4         | 0.81%   |
| Quanta HD User Facing                            | 4         | 0.81%   |
| Microdia Integrated Webcam HD                    | 4         | 0.81%   |
| Logitech C922 Pro Stream Webcam                  | 4         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)          | 4         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                       | 3         | 0.61%   |
| Quanta HD Webcam                                 | 3         | 0.61%   |
| Microsoft LifeCam Cinema                         | 3         | 0.61%   |
| Microdia HDP Webcam USB                          | 3         | 0.61%   |
| IMC Networks USB2.0 UVC HD Webcam                | 3         | 0.61%   |
| Generalplus WEB CAM                              | 3         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 0.61%   |
| Chicony USB 2.0 Camera                           | 3         | 0.61%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 0.61%   |
| Chicony HP HD Webcam                             | 3         | 0.61%   |
| Chicony HP HD Camera                             | 3         | 0.61%   |
| Chicony HD User Facing                           | 3         | 0.61%   |
| Chicony EasyCamera                               | 3         | 0.61%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 3         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 3         | 0.61%   |
| Acer EasyCamera                                  | 3         | 0.61%   |
| Suyin Integrated_Webcam_HD                       | 2         | 0.41%   |
| Suyin 1.3M HD WebCam                             | 2         | 0.41%   |
| SunplusIT 720p HD Camera                         | 2         | 0.41%   |
| SunplusIT 1080p FHD Camera                       | 2         | 0.41%   |
| Sunplus IT AUKEY PC-LM1 USB Camera               | 2         | 0.41%   |
| Sunplus SPCA2281 Web Camera                      | 2         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 2         | 0.41%   |
| Sunplus Laptop Integrated Webcam FHD             | 2         | 0.41%   |
| Sunplus HD WebCam                                | 2         | 0.41%   |
| Sunplus Full HD webcam                           | 2         | 0.41%   |
| Sunplus 1.3M HD WebCam                           | 2         | 0.41%   |
| Silicon Motion Web Camera                        | 2         | 0.41%   |
| Realtek USB2.0 HD UVC WebCam                     | 2         | 0.41%   |
| Realtek USB Camera                               | 2         | 0.41%   |
| Realtek MTD camera                               | 2         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 29        | 38.67%  |
| Validity Sensors           | 16        | 21.33%  |
| Shenzhen Goodix Technology | 15        | 20%     |
| LighTuning Technology      | 4         | 5.33%   |
| Elan Microelectronics      | 3         | 4%      |
| Upek                       | 2         | 2.67%   |
| HOLTEK                     | 2         | 2.67%   |
| AuthenTec                  | 2         | 2.67%   |
| Samsung Electronics        | 1         | 1.33%   |
| DigitalPersona             | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 9         | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 8         | 10.67%  |
| Shenzhen Goodix  FingerPrint Device                       | 6         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader                | 5         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                        | 5         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 5.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 4         | 5.33%   |
| Shenzhen Goodix FingerPrint                               | 4         | 5.33%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 3         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 2.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 2.67%   |
| Synaptics WBDI Device                                     | 2         | 2.67%   |
| Synaptics  WBDI                                           | 2         | 2.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 2.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 2.67%   |
| HOLTEK FocalTech Fingerprint Device                       | 2         | 2.67%   |
| Elan ELAN:ARM-M4                                          | 2         | 2.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1.33%   |
| Validity Sensors VFS491                                   | 1         | 1.33%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 1.33%   |
| Validity Sensors Synaptics WBDI                           | 1         | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.33%   |
| Validity Sensors Fingerprint scanner                      | 1         | 1.33%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 1.33%   |
| Elan ELAN:Fingerprint                                     | 1         | 1.33%   |
| DigitalPersona Fingerprint Reader                         | 1         | 1.33%   |
| AuthenTec AES2810                                         | 1         | 1.33%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 1.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 18        | 60%     |
| Alcor Micro      | 5         | 16.67%  |
| O2 Micro         | 3         | 10%     |
| Upek             | 2         | 6.67%   |
| SCM Microsystems | 1         | 3.33%   |
| Lenovo           | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 7         | 23.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 3.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 511       | 68.22%  |
| 1     | 199       | 26.57%  |
| 2     | 32        | 4.27%   |
| 3     | 6         | 0.8%    |
| 4     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 72        | 25.99%  |
| Net/wireless             | 48        | 17.33%  |
| Multimedia controller    | 44        | 15.88%  |
| Bluetooth                | 30        | 10.83%  |
| Chipcard                 | 29        | 10.47%  |
| Graphics card            | 28        | 10.11%  |
| Net/ethernet             | 4         | 1.44%   |
| Communication controller | 4         | 1.44%   |
| Unassigned class         | 3         | 1.08%   |
| Storage/ide              | 3         | 1.08%   |
| Network                  | 3         | 1.08%   |
| Storage                  | 2         | 0.72%   |
| Sound                    | 2         | 0.72%   |
| Modem                    | 2         | 0.72%   |
| Card reader              | 2         | 0.72%   |
| Camera                   | 1         | 0.36%   |

