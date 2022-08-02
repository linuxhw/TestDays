Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 10362

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
| Dell          | Precision M6800             | Notebook    | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| EVGA          | 134-KS-E377                 | Desktop     | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [b3d3ab37ef](https://linux-hardware.org/?probe=b3d3ab37ef) | Jul 30, 2022 |
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
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [adb71c8acc](https://linux-hardware.org/?probe=adb71c8acc) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e3dc0a4c49](https://linux-hardware.org/?probe=e3dc0a4c49) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [830913d1ab](https://linux-hardware.org/?probe=830913d1ab) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | Notebook    | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7c25b2c2c7](https://linux-hardware.org/?probe=7c25b2c2c7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [36e0686495](https://linux-hardware.org/?probe=36e0686495) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [97bbabec13](https://linux-hardware.org/?probe=97bbabec13) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [a39ccd24ff](https://linux-hardware.org/?probe=a39ccd24ff) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [71f25aa9f5](https://linux-hardware.org/?probe=71f25aa9f5) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | Desktop     | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | Notebook    | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cfb18dd008](https://linux-hardware.org/?probe=cfb18dd008) | Jul 26, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
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
| Intel Clie... | LAPKC71F                    | Notebook    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d41e7515af](https://linux-hardware.org/?probe=d41e7515af) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fdada0c3a6](https://linux-hardware.org/?probe=fdada0c3a6) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| HP            | 8433 11                     | Desktop     | [a66fb85e77](https://linux-hardware.org/?probe=a66fb85e77) | Jul 23, 2022 |
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
| Positivo      | POS-PIQ77CL                 | Desktop     | [ce9a0fdbbc](https://linux-hardware.org/?probe=ce9a0fdbbc) | Jul 20, 2022 |
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
| Acer          | Nitro AN515-57              | Notebook    | [b9429f25d1](https://linux-hardware.org/?probe=b9429f25d1) | Jul 17, 2022 |
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
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [618141855c](https://linux-hardware.org/?probe=618141855c) | Jul 11, 2022 |
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
| HP            | ProBook 440 G2              | Notebook    | [a2a01affe3](https://linux-hardware.org/?probe=a2a01affe3) | Jul 09, 2022 |
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
| Intel         | NUC8BEB J72693-305          | Mini pc     | [b73dab7637](https://linux-hardware.org/?probe=b73dab7637) | Jul 08, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [92eb60a700](https://linux-hardware.org/?probe=92eb60a700) | Jul 08, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [d4426d8840](https://linux-hardware.org/?probe=d4426d8840) | Jul 08, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| Panasonic     | CF-C2AQAZXLM                | Notebook    | [be9cf3127a](https://linux-hardware.org/?probe=be9cf3127a) | Jul 08, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [f9d5ea94ec](https://linux-hardware.org/?probe=f9d5ea94ec) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [1a40c954fc](https://linux-hardware.org/?probe=1a40c954fc) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [9e40e3f8ad](https://linux-hardware.org/?probe=9e40e3f8ad) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [842c5317f7](https://linux-hardware.org/?probe=842c5317f7) | Jul 07, 2022 |
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
| MSI           | B360-A PRO                  | Desktop     | [4534101418](https://linux-hardware.org/?probe=4534101418) | Jul 06, 2022 |
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
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [82fe9f31c7](https://linux-hardware.org/?probe=82fe9f31c7) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [a21d756ee1](https://linux-hardware.org/?probe=a21d756ee1) | Jul 03, 2022 |
| Notebook      | P65xHP                      | Notebook    | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Notebook    | [80c5bb3483](https://linux-hardware.org/?probe=80c5bb3483) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Acer          | Aspire E5-473G              | Notebook    | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| MSI           | GE62 2QF                    | Notebook    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
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
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fce5196d19](https://linux-hardware.org/?probe=fce5196d19) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [adfbbd03b6](https://linux-hardware.org/?probe=adfbbd03b6) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [3bceb0a396](https://linux-hardware.org/?probe=3bceb0a396) | Jun 29, 2022 |
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
| ASRock        | N68-S                       | Desktop     | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
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
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c5a5527f1d](https://linux-hardware.org/?probe=c5a5527f1d) | Jun 23, 2022 |
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
| System76      | Lemur Pro                   | Notebook    | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
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
| HP            | ProBook 450 G1              | Notebook    | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
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
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
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
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e92127f694](https://linux-hardware.org/?probe=e92127f694) | Jun 10, 2022 |
| Dell          | Latitude E7270              | Notebook    | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| PCWare        | IPX4105G Pro                | Desktop     | [72ac2cedad](https://linux-hardware.org/?probe=72ac2cedad) | Jun 10, 2022 |
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
| PCWare        | IPX4105G Pro                | Desktop     | [ffccee6734](https://linux-hardware.org/?probe=ffccee6734) | Jun 07, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [37e02e84a5](https://linux-hardware.org/?probe=37e02e84a5) | Jun 07, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [d4a2222ff7](https://linux-hardware.org/?probe=d4a2222ff7) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7ca8395543](https://linux-hardware.org/?probe=7ca8395543) | Jun 07, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [7bb51064db](https://linux-hardware.org/?probe=7bb51064db) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ec0e78e0f6](https://linux-hardware.org/?probe=ec0e78e0f6) | Jun 06, 2022 |
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
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [a77acb5d89](https://linux-hardware.org/?probe=a77acb5d89) | Jun 04, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [36951a7dad](https://linux-hardware.org/?probe=36951a7dad) | Jun 04, 2022 |
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
| Dell          | 0R790T A00                  | Desktop     | [f9388b2163](https://linux-hardware.org/?probe=f9388b2163) | May 29, 2022 |
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
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [57a20bde9f](https://linux-hardware.org/?probe=57a20bde9f) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| MSI           | MS-7D52                     | Notebook    | [f70c160542](https://linux-hardware.org/?probe=f70c160542) | May 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | Desktop     | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [dadda333d2](https://linux-hardware.org/?probe=dadda333d2) | May 28, 2022 |
| PC Special... | NH5x_7xDCx_DDx              | Notebook    | [bd70d45ed2](https://linux-hardware.org/?probe=bd70d45ed2) | May 28, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3980ea8269](https://linux-hardware.org/?probe=3980ea8269) | May 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [8746b1aa23](https://linux-hardware.org/?probe=8746b1aa23) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e7b6eddea](https://linux-hardware.org/?probe=6e7b6eddea) | May 27, 2022 |
| Dell          | Precision 5530              | Notebook    | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [084dab5bd4](https://linux-hardware.org/?probe=084dab5bd4) | May 26, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [3baddb9faa](https://linux-hardware.org/?probe=3baddb9faa) | May 26, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [81f3b14e0a](https://linux-hardware.org/?probe=81f3b14e0a) | May 25, 2022 |
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
| Dell          | XPS 15 7590                 | Notebook    | [b5f49ae2e9](https://linux-hardware.org/?probe=b5f49ae2e9) | May 23, 2022 |
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
| Apple         | MacBookAir7,2               | Notebook    | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | Notebook    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | Notebook    | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [1993c161fd](https://linux-hardware.org/?probe=1993c161fd) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [5ebbcedcc1](https://linux-hardware.org/?probe=5ebbcedcc1) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | Desktop     | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [22776216d6](https://linux-hardware.org/?probe=22776216d6) | May 22, 2022 |
| Google        | Lulu                        | Notebook    | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [cd50fa44c3](https://linux-hardware.org/?probe=cd50fa44c3) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | MS-7D52                     | Notebook    | [1144b23f51](https://linux-hardware.org/?probe=1144b23f51) | May 21, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [77d5276ecc](https://linux-hardware.org/?probe=77d5276ecc) | May 20, 2022 |
| ASRock        | TRX40 Creator               | Desktop     | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | Desktop     | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d705be052a](https://linux-hardware.org/?probe=d705be052a) | May 20, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [35c2610913](https://linux-hardware.org/?probe=35c2610913) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | Desktop     | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [9e2c754ed6](https://linux-hardware.org/?probe=9e2c754ed6) | May 19, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [3f9a21ddc1](https://linux-hardware.org/?probe=3f9a21ddc1) | May 19, 2022 |
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
| Infinix       | INBook X1 Pro               | Notebook    | [bb99e2b6ad](https://linux-hardware.org/?probe=bb99e2b6ad) | May 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [b1afeba24a](https://linux-hardware.org/?probe=b1afeba24a) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e4933544b7](https://linux-hardware.org/?probe=e4933544b7) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [aa531d1bf8](https://linux-hardware.org/?probe=aa531d1bf8) | May 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [67b9691645](https://linux-hardware.org/?probe=67b9691645) | May 15, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [c1f5cb662f](https://linux-hardware.org/?probe=c1f5cb662f) | May 15, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [bb296e5f39](https://linux-hardware.org/?probe=bb296e5f39) | May 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| MSI           | CSM-B85M-E45                | Desktop     | [85abf64cf5](https://linux-hardware.org/?probe=85abf64cf5) | May 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [423fbd3a54](https://linux-hardware.org/?probe=423fbd3a54) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | Notebook    | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [44952d0fff](https://linux-hardware.org/?probe=44952d0fff) | May 13, 2022 |
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
| ASUSTek       | G750JM                      | Notebook    | [1bcf5cc7ea](https://linux-hardware.org/?probe=1bcf5cc7ea) | May 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cfae917826](https://linux-hardware.org/?probe=cfae917826) | May 11, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2dd9e88806](https://linux-hardware.org/?probe=2dd9e88806) | May 11, 2022 |
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
| Acer          | RS780HVF                    | Desktop     | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [fd022c446e](https://linux-hardware.org/?probe=fd022c446e) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [20f46751c2](https://linux-hardware.org/?probe=20f46751c2) | May 08, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [c1df33620d](https://linux-hardware.org/?probe=c1df33620d) | May 08, 2022 |
| MSI           | Modern 15 A10RAS            | Notebook    | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | Notebook    | [5eefaba8d3](https://linux-hardware.org/?probe=5eefaba8d3) | May 08, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [17e7dcafe2](https://linux-hardware.org/?probe=17e7dcafe2) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | Desktop     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dcdc07525d](https://linux-hardware.org/?probe=dcdc07525d) | May 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| HP            | 0AE8h C                     | Desktop     | [bc0fa7f9b8](https://linux-hardware.org/?probe=bc0fa7f9b8) | May 08, 2022 |
| HP            | 0AE8h C                     | Desktop     | [fdf9e3acd8](https://linux-hardware.org/?probe=fdf9e3acd8) | May 08, 2022 |
| Acer          | RS780HVF                    | Desktop     | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [057ea02fdb](https://linux-hardware.org/?probe=057ea02fdb) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | Notebook    | [892d07e5cf](https://linux-hardware.org/?probe=892d07e5cf) | May 08, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| MSI           | GS63 7RD                    | Notebook    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| ECS           | Nettle3                     | Desktop     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Google        | Lulu                        | Notebook    | [18ecc4a6e7](https://linux-hardware.org/?probe=18ecc4a6e7) | May 07, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [b345350038](https://linux-hardware.org/?probe=b345350038) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5790e8a0cb](https://linux-hardware.org/?probe=5790e8a0cb) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [632a2af548](https://linux-hardware.org/?probe=632a2af548) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [a716192ef4](https://linux-hardware.org/?probe=a716192ef4) | May 06, 2022 |
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
| Gigabyte      | P65                         | Notebook    | [0bbc07114a](https://linux-hardware.org/?probe=0bbc07114a) | May 04, 2022 |
| Acer          | Spin SP315-51               | Convertible | [b96494c3bc](https://linux-hardware.org/?probe=b96494c3bc) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [ca91daf662](https://linux-hardware.org/?probe=ca91daf662) | May 04, 2022 |
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
| HP            | ENVY dv6                    | Notebook    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| ASUSTek       | GL552JX                     | Notebook    | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | Notebook    | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [f2de7ca21b](https://linux-hardware.org/?probe=f2de7ca21b) | May 03, 2022 |
| Acer          | Spin SP315-51               | Convertible | [227f2d9f45](https://linux-hardware.org/?probe=227f2d9f45) | May 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [8af6378145](https://linux-hardware.org/?probe=8af6378145) | May 02, 2022 |
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
| HP            | EliteBook 850 G3            | Notebook    | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | Desktop     | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | Notebook    | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| System76      | Oryx Pro                    | Notebook    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| Acer          | Aspire V5-573P              | Notebook    | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Dell          | Latitude E5570              | Notebook    | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | Convertible | [fad7884cb4](https://linux-hardware.org/?probe=fad7884cb4) | May 02, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0e40616573](https://linux-hardware.org/?probe=0e40616573) | May 02, 2022 |
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
| Dell          | XPS 13 9365                 | Convertible | [3761721b90](https://linux-hardware.org/?probe=3761721b90) | May 01, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6db8017245](https://linux-hardware.org/?probe=6db8017245) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | Desktop     | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| ASUSTek       | G55VW                       | Notebook    | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [ea3b16fcfd](https://linux-hardware.org/?probe=ea3b16fcfd) | Apr 29, 2022 |
| Dell          | G5 5500                     | Notebook    | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Lenovo        | 3136 SDK0K17763 WIN 1801... | Mini pc     | [7b13bcb624](https://linux-hardware.org/?probe=7b13bcb624) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| System76      | Oryx Pro                    | Notebook    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| HP            | 8704                        | Desktop     | [41d896b51d](https://linux-hardware.org/?probe=41d896b51d) | Apr 29, 2022 |
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
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [59a8e467c6](https://linux-hardware.org/?probe=59a8e467c6) | Apr 28, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [44e25caaa1](https://linux-hardware.org/?probe=44e25caaa1) | Apr 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [1f26415f58](https://linux-hardware.org/?probe=1f26415f58) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [b7443972f3](https://linux-hardware.org/?probe=b7443972f3) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [ad35094812](https://linux-hardware.org/?probe=ad35094812) | Apr 28, 2022 |
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
| ASUSTek       | SABERTOOTH Z170 S           | Desktop     | [21663dc8b3](https://linux-hardware.org/?probe=21663dc8b3) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c9fb277b57](https://linux-hardware.org/?probe=c9fb277b57) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| Lenovo        | ThinkPad T480 20L6SJN400    | Notebook    | [294a5ef80c](https://linux-hardware.org/?probe=294a5ef80c) | Apr 27, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [25041b35de](https://linux-hardware.org/?probe=25041b35de) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [bbb524450f](https://linux-hardware.org/?probe=bbb524450f) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [31b5451ae1](https://linux-hardware.org/?probe=31b5451ae1) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | Notebook    | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [bc3cbdbc1f](https://linux-hardware.org/?probe=bc3cbdbc1f) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [486215d495](https://linux-hardware.org/?probe=486215d495) | Apr 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [a42b1cda2c](https://linux-hardware.org/?probe=a42b1cda2c) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | Desktop     | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [f99a1a0591](https://linux-hardware.org/?probe=f99a1a0591) | Apr 25, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [ed023008e4](https://linux-hardware.org/?probe=ed023008e4) | Apr 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9236e9bc93](https://linux-hardware.org/?probe=9236e9bc93) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [d1d705c163](https://linux-hardware.org/?probe=d1d705c163) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [97ff7b7591](https://linux-hardware.org/?probe=97ff7b7591) | Apr 25, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [256f703e7e](https://linux-hardware.org/?probe=256f703e7e) | Apr 25, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [8a96f457bb](https://linux-hardware.org/?probe=8a96f457bb) | Apr 25, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [f656f0d16f](https://linux-hardware.org/?probe=f656f0d16f) | Apr 24, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [711f26a820](https://linux-hardware.org/?probe=711f26a820) | Apr 24, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [2c1b91769f](https://linux-hardware.org/?probe=2c1b91769f) | Apr 24, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [2e4a211c66](https://linux-hardware.org/?probe=2e4a211c66) | Apr 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [803959fe3c](https://linux-hardware.org/?probe=803959fe3c) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| ASUSTek       | X450LCP                     | Notebook    | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6d999cbc8](https://linux-hardware.org/?probe=d6d999cbc8) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [0534d32a13](https://linux-hardware.org/?probe=0534d32a13) | Apr 23, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [61ab02b4e8](https://linux-hardware.org/?probe=61ab02b4e8) | Apr 23, 2022 |
| ECS           | Iris8                       | Desktop     | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [8ae54427ca](https://linux-hardware.org/?probe=8ae54427ca) | Apr 23, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [0399a90ade](https://linux-hardware.org/?probe=0399a90ade) | Apr 23, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [3cb8eac116](https://linux-hardware.org/?probe=3cb8eac116) | Apr 23, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [e73885a94d](https://linux-hardware.org/?probe=e73885a94d) | Apr 23, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [477b1e873f](https://linux-hardware.org/?probe=477b1e873f) | Apr 23, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [f283519d44](https://linux-hardware.org/?probe=f283519d44) | Apr 22, 2022 |
| ASUSTek       | GL552JX                     | Notebook    | [dae470212d](https://linux-hardware.org/?probe=dae470212d) | Apr 22, 2022 |
| HP            | ENVY x360 Convert 15        | Convertible | [f3071c3072](https://linux-hardware.org/?probe=f3071c3072) | Apr 22, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [4043c70a42](https://linux-hardware.org/?probe=4043c70a42) | Apr 22, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [2c48c81559](https://linux-hardware.org/?probe=2c48c81559) | Apr 22, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [9936062b3c](https://linux-hardware.org/?probe=9936062b3c) | Apr 22, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [017717599c](https://linux-hardware.org/?probe=017717599c) | Apr 22, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [0e3c909996](https://linux-hardware.org/?probe=0e3c909996) | Apr 22, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [c4cfcaf69e](https://linux-hardware.org/?probe=c4cfcaf69e) | Apr 22, 2022 |
| Dell          | Latitude 7275               | Tablet      | [8b373dc563](https://linux-hardware.org/?probe=8b373dc563) | Apr 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [6e37f18366](https://linux-hardware.org/?probe=6e37f18366) | Apr 21, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c32d394b3a](https://linux-hardware.org/?probe=c32d394b3a) | Apr 21, 2022 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [f1a2e57e22](https://linux-hardware.org/?probe=f1a2e57e22) | Apr 21, 2022 |
| CyberPower... | Tracer II                   | Notebook    | [4582a60770](https://linux-hardware.org/?probe=4582a60770) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [329905cab9](https://linux-hardware.org/?probe=329905cab9) | Apr 21, 2022 |
| Gigabyte      | AB350M-HD3-CF               | Desktop     | [dd16ab4768](https://linux-hardware.org/?probe=dd16ab4768) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [480a64a95a](https://linux-hardware.org/?probe=480a64a95a) | Apr 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c568c44d81](https://linux-hardware.org/?probe=c568c44d81) | Apr 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWS19E0... | Notebook    | [c6a1ec3df0](https://linux-hardware.org/?probe=c6a1ec3df0) | Apr 20, 2022 |
| Samsung       | 550XDA                      | Notebook    | [66cb0691e0](https://linux-hardware.org/?probe=66cb0691e0) | Apr 20, 2022 |
| Dell          | Latitude D430               | Notebook    | [00ddfbe46f](https://linux-hardware.org/?probe=00ddfbe46f) | Apr 20, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [7beb17ef96](https://linux-hardware.org/?probe=7beb17ef96) | Apr 20, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [0d5a9fcacc](https://linux-hardware.org/?probe=0d5a9fcacc) | Apr 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [c9ef889715](https://linux-hardware.org/?probe=c9ef889715) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [61ca629904](https://linux-hardware.org/?probe=61ca629904) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [c722e417a1](https://linux-hardware.org/?probe=c722e417a1) | Apr 20, 2022 |
| Toshiba       | Satellite S75-A             | Notebook    | [90ba54ad32](https://linux-hardware.org/?probe=90ba54ad32) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [88764ed497](https://linux-hardware.org/?probe=88764ed497) | Apr 20, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [589bc2d17a](https://linux-hardware.org/?probe=589bc2d17a) | Apr 20, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [0aa2639b59](https://linux-hardware.org/?probe=0aa2639b59) | Apr 20, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [e409d7a8df](https://linux-hardware.org/?probe=e409d7a8df) | Apr 20, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fd661468b9](https://linux-hardware.org/?probe=fd661468b9) | Apr 19, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [6c4022059c](https://linux-hardware.org/?probe=6c4022059c) | Apr 19, 2022 |
| System76      | Galago Pro                  | Notebook    | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7f4254b1b1](https://linux-hardware.org/?probe=7f4254b1b1) | Apr 19, 2022 |
| Positivo      | N1250                       | Notebook    | [c2dfeaab53](https://linux-hardware.org/?probe=c2dfeaab53) | Apr 19, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [29f92aa75f](https://linux-hardware.org/?probe=29f92aa75f) | Apr 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bbc4928d39](https://linux-hardware.org/?probe=bbc4928d39) | Apr 19, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [3654d1f0fa](https://linux-hardware.org/?probe=3654d1f0fa) | Apr 19, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [7290650d08](https://linux-hardware.org/?probe=7290650d08) | Apr 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dc42beaa8d](https://linux-hardware.org/?probe=dc42beaa8d) | Apr 18, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [746e2ea0d2](https://linux-hardware.org/?probe=746e2ea0d2) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [49d51ee541](https://linux-hardware.org/?probe=49d51ee541) | Apr 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7d16b45ebd](https://linux-hardware.org/?probe=7d16b45ebd) | Apr 18, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [9f5287d8cb](https://linux-hardware.org/?probe=9f5287d8cb) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e269a6b9b8](https://linux-hardware.org/?probe=e269a6b9b8) | Apr 18, 2022 |
| ASUSTek       | UL30VT                      | Notebook    | [faad37ee2e](https://linux-hardware.org/?probe=faad37ee2e) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [e1d2871cd8](https://linux-hardware.org/?probe=e1d2871cd8) | Apr 18, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [f460a6924f](https://linux-hardware.org/?probe=f460a6924f) | Apr 18, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [ebe60e3c9e](https://linux-hardware.org/?probe=ebe60e3c9e) | Apr 18, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a315b0490b](https://linux-hardware.org/?probe=a315b0490b) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [a07c515f60](https://linux-hardware.org/?probe=a07c515f60) | Apr 17, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [7b61fb0ba4](https://linux-hardware.org/?probe=7b61fb0ba4) | Apr 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f7008a1e16](https://linux-hardware.org/?probe=f7008a1e16) | Apr 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f5deab7689](https://linux-hardware.org/?probe=f5deab7689) | Apr 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [49c981ee41](https://linux-hardware.org/?probe=49c981ee41) | Apr 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [52a97f186f](https://linux-hardware.org/?probe=52a97f186f) | Apr 17, 2022 |
| Framework     | Laptop                      | Notebook    | [acad8f1ccb](https://linux-hardware.org/?probe=acad8f1ccb) | Apr 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0c4c081e71](https://linux-hardware.org/?probe=0c4c081e71) | Apr 17, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [dc1e145cf3](https://linux-hardware.org/?probe=dc1e145cf3) | Apr 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [a8c0eeb473](https://linux-hardware.org/?probe=a8c0eeb473) | Apr 16, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [a497ac3b95](https://linux-hardware.org/?probe=a497ac3b95) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [9a5d59c375](https://linux-hardware.org/?probe=9a5d59c375) | Apr 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [65edd32378](https://linux-hardware.org/?probe=65edd32378) | Apr 16, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [923a82e975](https://linux-hardware.org/?probe=923a82e975) | Apr 16, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e9e45e7f91](https://linux-hardware.org/?probe=e9e45e7f91) | Apr 16, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d9c6549322](https://linux-hardware.org/?probe=d9c6549322) | Apr 16, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e51d0544a1](https://linux-hardware.org/?probe=e51d0544a1) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [f83ee2cc17](https://linux-hardware.org/?probe=f83ee2cc17) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [eef3c69fcd](https://linux-hardware.org/?probe=eef3c69fcd) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [b0a5b307c9](https://linux-hardware.org/?probe=b0a5b307c9) | Apr 16, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [48deb234f0](https://linux-hardware.org/?probe=48deb234f0) | Apr 15, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Dell          | Precision 5760              | Notebook    | [ba2ce021d0](https://linux-hardware.org/?probe=ba2ce021d0) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7e8c906437](https://linux-hardware.org/?probe=7e8c906437) | Apr 15, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [92da438638](https://linux-hardware.org/?probe=92da438638) | Apr 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [37e172faec](https://linux-hardware.org/?probe=37e172faec) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0bd7facf9b](https://linux-hardware.org/?probe=0bd7facf9b) | Apr 14, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [a10ea959f8](https://linux-hardware.org/?probe=a10ea959f8) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [17622a538e](https://linux-hardware.org/?probe=17622a538e) | Apr 14, 2022 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [19299bc16d](https://linux-hardware.org/?probe=19299bc16d) | Apr 14, 2022 |
| NZXT          | N7 B550                     | Desktop     | [71e92a4807](https://linux-hardware.org/?probe=71e92a4807) | Apr 14, 2022 |
| Wortmann      | 1220663_1470189             | Notebook    | [59eed1073a](https://linux-hardware.org/?probe=59eed1073a) | Apr 14, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [d29ff8a54e](https://linux-hardware.org/?probe=d29ff8a54e) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b40d10cb81](https://linux-hardware.org/?probe=b40d10cb81) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [843c3d4758](https://linux-hardware.org/?probe=843c3d4758) | Apr 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ef76ce862d](https://linux-hardware.org/?probe=ef76ce862d) | Apr 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c372810f3f](https://linux-hardware.org/?probe=c372810f3f) | Apr 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7025b1689c](https://linux-hardware.org/?probe=7025b1689c) | Apr 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [4d46d1ce45](https://linux-hardware.org/?probe=4d46d1ce45) | Apr 14, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [5064c36f02](https://linux-hardware.org/?probe=5064c36f02) | Apr 14, 2022 |
| Dell          | 0H7TGR A00                  | Desktop     | [70bdc97d85](https://linux-hardware.org/?probe=70bdc97d85) | Apr 14, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [f8f13d5514](https://linux-hardware.org/?probe=f8f13d5514) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [3752ecab33](https://linux-hardware.org/?probe=3752ecab33) | Apr 14, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d0933b6a76](https://linux-hardware.org/?probe=d0933b6a76) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4a159b7cd8](https://linux-hardware.org/?probe=4a159b7cd8) | Apr 14, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [9715d61366](https://linux-hardware.org/?probe=9715d61366) | Apr 14, 2022 |
| System76      | Oryx Pro                    | Notebook    | [8521355f49](https://linux-hardware.org/?probe=8521355f49) | Apr 13, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b64e82a4a6](https://linux-hardware.org/?probe=b64e82a4a6) | Apr 13, 2022 |
| ASUSTek       | N56VV                       | Notebook    | [8ae8e89c42](https://linux-hardware.org/?probe=8ae8e89c42) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [392f621ca6](https://linux-hardware.org/?probe=392f621ca6) | Apr 13, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b089bb9293](https://linux-hardware.org/?probe=b089bb9293) | Apr 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [315cbe72dd](https://linux-hardware.org/?probe=315cbe72dd) | Apr 13, 2022 |
| System76      | Thelio Major thelio-majo... | Desktop     | [5924b8c844](https://linux-hardware.org/?probe=5924b8c844) | Apr 13, 2022 |
| System76      | Pangolin                    | Notebook    | [3976805ed7](https://linux-hardware.org/?probe=3976805ed7) | Apr 13, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [8a64db97de](https://linux-hardware.org/?probe=8a64db97de) | Apr 13, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [3e26cc6c66](https://linux-hardware.org/?probe=3e26cc6c66) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e05e4dc47b](https://linux-hardware.org/?probe=e05e4dc47b) | Apr 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| System76      | Oryx Pro                    | Notebook    | [bfba9dbec0](https://linux-hardware.org/?probe=bfba9dbec0) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [a6c665d142](https://linux-hardware.org/?probe=a6c665d142) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [9fa510fc02](https://linux-hardware.org/?probe=9fa510fc02) | Apr 13, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [080cbf45eb](https://linux-hardware.org/?probe=080cbf45eb) | Apr 13, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [c76114b4b3](https://linux-hardware.org/?probe=c76114b4b3) | Apr 13, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [e5744a1f58](https://linux-hardware.org/?probe=e5744a1f58) | Apr 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [47404cf177](https://linux-hardware.org/?probe=47404cf177) | Apr 12, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| System76      | Darter Pro                  | Notebook    | [669d3cf4e4](https://linux-hardware.org/?probe=669d3cf4e4) | Apr 12, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [9ae1f72e77](https://linux-hardware.org/?probe=9ae1f72e77) | Apr 12, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [839b9579c3](https://linux-hardware.org/?probe=839b9579c3) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [9bcf0f1e4f](https://linux-hardware.org/?probe=9bcf0f1e4f) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [52e0e2e934](https://linux-hardware.org/?probe=52e0e2e934) | Apr 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [921b858e18](https://linux-hardware.org/?probe=921b858e18) | Apr 11, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [8c6cc15607](https://linux-hardware.org/?probe=8c6cc15607) | Apr 11, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [92f7a3b948](https://linux-hardware.org/?probe=92f7a3b948) | Apr 11, 2022 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [20e831b4af](https://linux-hardware.org/?probe=20e831b4af) | Apr 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [6c85a524a1](https://linux-hardware.org/?probe=6c85a524a1) | Apr 11, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [cb8b648eac](https://linux-hardware.org/?probe=cb8b648eac) | Apr 10, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [03b442ccf4](https://linux-hardware.org/?probe=03b442ccf4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| eMachines     | EL1850G                     | Desktop     | [cfa8d1c8d5](https://linux-hardware.org/?probe=cfa8d1c8d5) | Apr 10, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [28114b7924](https://linux-hardware.org/?probe=28114b7924) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [117eded7f8](https://linux-hardware.org/?probe=117eded7f8) | Apr 10, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [c42f3e3b5b](https://linux-hardware.org/?probe=c42f3e3b5b) | Apr 10, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [dd511f4bf0](https://linux-hardware.org/?probe=dd511f4bf0) | Apr 09, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [88fba1bae6](https://linux-hardware.org/?probe=88fba1bae6) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [1c57ef464e](https://linux-hardware.org/?probe=1c57ef464e) | Apr 09, 2022 |
| MSI           | GS66 Stealth 11UG           | Notebook    | [1fc8942ea4](https://linux-hardware.org/?probe=1fc8942ea4) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [e641889a70](https://linux-hardware.org/?probe=e641889a70) | Apr 09, 2022 |
| NZXT          | N7 B550                     | Desktop     | [e3f895a70b](https://linux-hardware.org/?probe=e3f895a70b) | Apr 09, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [19450f9d90](https://linux-hardware.org/?probe=19450f9d90) | Apr 09, 2022 |
| ASUSTek       | P8H67-V                     | Desktop     | [a2ae5eb5b9](https://linux-hardware.org/?probe=a2ae5eb5b9) | Apr 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [10d0d3a721](https://linux-hardware.org/?probe=10d0d3a721) | Apr 09, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [1d0d38c7c8](https://linux-hardware.org/?probe=1d0d38c7c8) | Apr 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Dell          | G7 7700                     | Notebook    | [62180a0287](https://linux-hardware.org/?probe=62180a0287) | Apr 09, 2022 |
| Dell          | Latitude E5520              | Notebook    | [3f3548b57e](https://linux-hardware.org/?probe=3f3548b57e) | Apr 09, 2022 |
| Dell          | Latitude E5520              | Notebook    | [dbd85ba35f](https://linux-hardware.org/?probe=dbd85ba35f) | Apr 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2d822ae226](https://linux-hardware.org/?probe=2d822ae226) | Apr 08, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| CyberPower... | Tracer II                   | Notebook    | [735f98bbb9](https://linux-hardware.org/?probe=735f98bbb9) | Apr 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [86fff99f90](https://linux-hardware.org/?probe=86fff99f90) | Apr 08, 2022 |
| Dell          | Latitude E7270              | Notebook    | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [4119278c12](https://linux-hardware.org/?probe=4119278c12) | Apr 08, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [95f7ceba3b](https://linux-hardware.org/?probe=95f7ceba3b) | Apr 08, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7ec2454548](https://linux-hardware.org/?probe=7ec2454548) | Apr 08, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [41ed1dae3d](https://linux-hardware.org/?probe=41ed1dae3d) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ed6ff884fc](https://linux-hardware.org/?probe=ed6ff884fc) | Apr 08, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [bde8b0ab3c](https://linux-hardware.org/?probe=bde8b0ab3c) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| Lenovo        | 3130 SDK0J40700 WIN 3258... | Mini pc     | [b1de91e35f](https://linux-hardware.org/?probe=b1de91e35f) | Apr 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [297454c537](https://linux-hardware.org/?probe=297454c537) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [d98ca9a688](https://linux-hardware.org/?probe=d98ca9a688) | Apr 07, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad W520 4284EE6       | Notebook    | [444497b8b6](https://linux-hardware.org/?probe=444497b8b6) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [d1f213c4f0](https://linux-hardware.org/?probe=d1f213c4f0) | Apr 07, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [944ffb7e3f](https://linux-hardware.org/?probe=944ffb7e3f) | Apr 06, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [e3d9b54f28](https://linux-hardware.org/?probe=e3d9b54f28) | Apr 06, 2022 |
| Toshiba       | Satellite A205              | Notebook    | [a10f998cea](https://linux-hardware.org/?probe=a10f998cea) | Apr 06, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [83ec935bc4](https://linux-hardware.org/?probe=83ec935bc4) | Apr 06, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [520cbf0afa](https://linux-hardware.org/?probe=520cbf0afa) | Apr 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f5106f79ee](https://linux-hardware.org/?probe=f5106f79ee) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3403cf3b8a](https://linux-hardware.org/?probe=3403cf3b8a) | Apr 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c7231b52a](https://linux-hardware.org/?probe=4c7231b52a) | Apr 05, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [568f9433a9](https://linux-hardware.org/?probe=568f9433a9) | Apr 05, 2022 |
| Gigabyte      | H87M-HD3                    | Desktop     | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c95df20756](https://linux-hardware.org/?probe=c95df20756) | Apr 05, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f1a7708b3c](https://linux-hardware.org/?probe=f1a7708b3c) | Apr 05, 2022 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [ac27863283](https://linux-hardware.org/?probe=ac27863283) | Apr 05, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [7f0692eb54](https://linux-hardware.org/?probe=7f0692eb54) | Apr 05, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [aa22c203eb](https://linux-hardware.org/?probe=aa22c203eb) | Apr 05, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [a8ad77f915](https://linux-hardware.org/?probe=a8ad77f915) | Apr 04, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [188a7794dd](https://linux-hardware.org/?probe=188a7794dd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4efbcf88a2](https://linux-hardware.org/?probe=4efbcf88a2) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [8d1d44d764](https://linux-hardware.org/?probe=8d1d44d764) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [3e3b21e230](https://linux-hardware.org/?probe=3e3b21e230) | Apr 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7a354d771f](https://linux-hardware.org/?probe=7a354d771f) | Apr 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [93c2d9ec80](https://linux-hardware.org/?probe=93c2d9ec80) | Apr 03, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [f6d4a4c17e](https://linux-hardware.org/?probe=f6d4a4c17e) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [40077b3761](https://linux-hardware.org/?probe=40077b3761) | Apr 03, 2022 |
| Dell          | Latitude 7275               | Tablet      | [4e3f9ca88e](https://linux-hardware.org/?probe=4e3f9ca88e) | Apr 02, 2022 |
| Dell          | 0K240Y A03                  | Desktop     | [7e3ad9ce02](https://linux-hardware.org/?probe=7e3ad9ce02) | Apr 02, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [312811bfc3](https://linux-hardware.org/?probe=312811bfc3) | Apr 02, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [a4c9ba22ca](https://linux-hardware.org/?probe=a4c9ba22ca) | Apr 02, 2022 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [4c2eb85ea8](https://linux-hardware.org/?probe=4c2eb85ea8) | Apr 02, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [48f0951752](https://linux-hardware.org/?probe=48f0951752) | Apr 02, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [62bdba9365](https://linux-hardware.org/?probe=62bdba9365) | Apr 02, 2022 |
| MOTILE        | M141                        | Notebook    | [d93780c02c](https://linux-hardware.org/?probe=d93780c02c) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | Desktop     | [5d3d268c96](https://linux-hardware.org/?probe=5d3d268c96) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | Desktop     | [3dac9f017e](https://linux-hardware.org/?probe=3dac9f017e) | Apr 02, 2022 |
| Dell          | G7 7588                     | Notebook    | [3ca575dc99](https://linux-hardware.org/?probe=3ca575dc99) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4e2f534de0](https://linux-hardware.org/?probe=4e2f534de0) | Apr 01, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [ca7d796269](https://linux-hardware.org/?probe=ca7d796269) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [625d6cc105](https://linux-hardware.org/?probe=625d6cc105) | Apr 01, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [27836be76e](https://linux-hardware.org/?probe=27836be76e) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [f9bbaea819](https://linux-hardware.org/?probe=f9bbaea819) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [944f40aa28](https://linux-hardware.org/?probe=944f40aa28) | Apr 01, 2022 |
| Dell          | G5 5500                     | Notebook    | [56b5d0d490](https://linux-hardware.org/?probe=56b5d0d490) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [616258c6a5](https://linux-hardware.org/?probe=616258c6a5) | Apr 01, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [cb8702ec94](https://linux-hardware.org/?probe=cb8702ec94) | Apr 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3177873d94](https://linux-hardware.org/?probe=3177873d94) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [254b38e98f](https://linux-hardware.org/?probe=254b38e98f) | Apr 01, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [069ce7ef8f](https://linux-hardware.org/?probe=069ce7ef8f) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a8c1be0abd](https://linux-hardware.org/?probe=a8c1be0abd) | Mar 31, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [e4ef535529](https://linux-hardware.org/?probe=e4ef535529) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| ECS           | A55F-M4                     | Desktop     | [0d29bdddde](https://linux-hardware.org/?probe=0d29bdddde) | Mar 31, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [e983db3f40](https://linux-hardware.org/?probe=e983db3f40) | Mar 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [92eae45686](https://linux-hardware.org/?probe=92eae45686) | Mar 30, 2022 |
| HP            | 300-240                     | Notebook    | [ce3af573e2](https://linux-hardware.org/?probe=ce3af573e2) | Mar 30, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [1f2167e189](https://linux-hardware.org/?probe=1f2167e189) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [3cdc036c09](https://linux-hardware.org/?probe=3cdc036c09) | Mar 30, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d5b2536b95](https://linux-hardware.org/?probe=d5b2536b95) | Mar 30, 2022 |
| Acer          | Swift SF313-53              | Notebook    | [15d4d13a68](https://linux-hardware.org/?probe=15d4d13a68) | Mar 30, 2022 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [a30f5893f6](https://linux-hardware.org/?probe=a30f5893f6) | Mar 30, 2022 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [8fdae867c0](https://linux-hardware.org/?probe=8fdae867c0) | Mar 30, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [d219905770](https://linux-hardware.org/?probe=d219905770) | Mar 30, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [af894bb443](https://linux-hardware.org/?probe=af894bb443) | Mar 30, 2022 |
| Dell          | Latitude D531               | Notebook    | [8aa1b4069b](https://linux-hardware.org/?probe=8aa1b4069b) | Mar 30, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eeef359646](https://linux-hardware.org/?probe=eeef359646) | Mar 30, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [426cd0671d](https://linux-hardware.org/?probe=426cd0671d) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [dddc946b70](https://linux-hardware.org/?probe=dddc946b70) | Mar 29, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [74e7884f94](https://linux-hardware.org/?probe=74e7884f94) | Mar 29, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [b3a7b518b6](https://linux-hardware.org/?probe=b3a7b518b6) | Mar 29, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [db66e10c17](https://linux-hardware.org/?probe=db66e10c17) | Mar 29, 2022 |
| Sony          | SVE15115FXS                 | Notebook    | [fd28d82701](https://linux-hardware.org/?probe=fd28d82701) | Mar 28, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [29e7a23412](https://linux-hardware.org/?probe=29e7a23412) | Mar 28, 2022 |
| HP            | 300-240                     | Notebook    | [48bfec0c03](https://linux-hardware.org/?probe=48bfec0c03) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [9554184dcd](https://linux-hardware.org/?probe=9554184dcd) | Mar 28, 2022 |
| MSI           | P67A-C43                    | Desktop     | [fb5d1f7bc1](https://linux-hardware.org/?probe=fb5d1f7bc1) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [acb42fe25a](https://linux-hardware.org/?probe=acb42fe25a) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [d39c4f7d2b](https://linux-hardware.org/?probe=d39c4f7d2b) | Mar 28, 2022 |
| Positivo      | Q464C                       | Notebook    | [16e296228a](https://linux-hardware.org/?probe=16e296228a) | Mar 28, 2022 |
| MSI           | P67A-C43                    | Desktop     | [dac91a1c12](https://linux-hardware.org/?probe=dac91a1c12) | Mar 28, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [1c9b405e1b](https://linux-hardware.org/?probe=1c9b405e1b) | Mar 27, 2022 |
| Toshiba       | Satellite A135              | Notebook    | [cf23c9bdb5](https://linux-hardware.org/?probe=cf23c9bdb5) | Mar 27, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [48ab5aae1e](https://linux-hardware.org/?probe=48ab5aae1e) | Mar 27, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| Dell          | Latitude 7275               | Tablet      | [1e0ad3b3cd](https://linux-hardware.org/?probe=1e0ad3b3cd) | Mar 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [756231c2f0](https://linux-hardware.org/?probe=756231c2f0) | Mar 27, 2022 |
| HP            | Pavilion g4                 | Notebook    | [893eaf3bca](https://linux-hardware.org/?probe=893eaf3bca) | Mar 27, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [e269e3b44e](https://linux-hardware.org/?probe=e269e3b44e) | Mar 27, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [986e01838e](https://linux-hardware.org/?probe=986e01838e) | Mar 27, 2022 |
| Dell          | Latitude E6430              | Notebook    | [1e9495c4f6](https://linux-hardware.org/?probe=1e9495c4f6) | Mar 27, 2022 |
| HP            | 1495                        | Desktop     | [19569ad62b](https://linux-hardware.org/?probe=19569ad62b) | Mar 27, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [710ec26531](https://linux-hardware.org/?probe=710ec26531) | Mar 27, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [d0d493d449](https://linux-hardware.org/?probe=d0d493d449) | Mar 27, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [3d5b596cf4](https://linux-hardware.org/?probe=3d5b596cf4) | Mar 27, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [f3eb3387fb](https://linux-hardware.org/?probe=f3eb3387fb) | Mar 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [6298903ec7](https://linux-hardware.org/?probe=6298903ec7) | Mar 27, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [2a9d489c50](https://linux-hardware.org/?probe=2a9d489c50) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [d4655e802a](https://linux-hardware.org/?probe=d4655e802a) | Mar 26, 2022 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [f7daea6e27](https://linux-hardware.org/?probe=f7daea6e27) | Mar 26, 2022 |
| MSI           | GE72 2QF                    | Notebook    | [3966a755c3](https://linux-hardware.org/?probe=3966a755c3) | Mar 26, 2022 |
| Dell          | Inspiron 5758               | Notebook    | [ddd5e24256](https://linux-hardware.org/?probe=ddd5e24256) | Mar 26, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [6774be59d3](https://linux-hardware.org/?probe=6774be59d3) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [31106ba339](https://linux-hardware.org/?probe=31106ba339) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [9298b99a93](https://linux-hardware.org/?probe=9298b99a93) | Mar 26, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | X542UR                      | Notebook    | [4d4477bd16](https://linux-hardware.org/?probe=4d4477bd16) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [296d97246f](https://linux-hardware.org/?probe=296d97246f) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1272ec27ff](https://linux-hardware.org/?probe=1272ec27ff) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [74a1c6bd00](https://linux-hardware.org/?probe=74a1c6bd00) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [e352bc299f](https://linux-hardware.org/?probe=e352bc299f) | Mar 26, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [1d78876e0c](https://linux-hardware.org/?probe=1d78876e0c) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [3825c4904e](https://linux-hardware.org/?probe=3825c4904e) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [27f565aeca](https://linux-hardware.org/?probe=27f565aeca) | Mar 26, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [2e45272bc9](https://linux-hardware.org/?probe=2e45272bc9) | Mar 26, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | Desktop     | [aae529497f](https://linux-hardware.org/?probe=aae529497f) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [a2921a6b4c](https://linux-hardware.org/?probe=a2921a6b4c) | Mar 25, 2022 |
| MSI           | IONA                        | Desktop     | [1a625c0505](https://linux-hardware.org/?probe=1a625c0505) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [ca5720c46b](https://linux-hardware.org/?probe=ca5720c46b) | Mar 25, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [a56ed819d1](https://linux-hardware.org/?probe=a56ed819d1) | Mar 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [5340d6cada](https://linux-hardware.org/?probe=5340d6cada) | Mar 25, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [0579061135](https://linux-hardware.org/?probe=0579061135) | Mar 25, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [be7bbfb988](https://linux-hardware.org/?probe=be7bbfb988) | Mar 25, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [bce45f36b9](https://linux-hardware.org/?probe=bce45f36b9) | Mar 25, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [81a6571a8b](https://linux-hardware.org/?probe=81a6571a8b) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [ca13a081ff](https://linux-hardware.org/?probe=ca13a081ff) | Mar 25, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [04bca4a56e](https://linux-hardware.org/?probe=04bca4a56e) | Mar 25, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8064b23bf4](https://linux-hardware.org/?probe=8064b23bf4) | Mar 25, 2022 |
| Dell          | Latitude 9420               | Notebook    | [5227a4fbe3](https://linux-hardware.org/?probe=5227a4fbe3) | Mar 24, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [7f92319a04](https://linux-hardware.org/?probe=7f92319a04) | Mar 24, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [1017a921d7](https://linux-hardware.org/?probe=1017a921d7) | Mar 24, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [0bb5a2b0d1](https://linux-hardware.org/?probe=0bb5a2b0d1) | Mar 24, 2022 |
| Toshiba       | Satellite P50-B-10V         | Notebook    | [1f6acfd782](https://linux-hardware.org/?probe=1f6acfd782) | Mar 24, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [4ee969ac04](https://linux-hardware.org/?probe=4ee969ac04) | Mar 24, 2022 |
| ASRock        | 4X4-V1000                   | Desktop     | [f02931fb21](https://linux-hardware.org/?probe=f02931fb21) | Mar 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f146cb600a](https://linux-hardware.org/?probe=f146cb600a) | Mar 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [3f091e30fe](https://linux-hardware.org/?probe=3f091e30fe) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [bc18447c4b](https://linux-hardware.org/?probe=bc18447c4b) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [f7248b112d](https://linux-hardware.org/?probe=f7248b112d) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0e85a5ee68](https://linux-hardware.org/?probe=0e85a5ee68) | Mar 24, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | Desktop     | [87989ace9b](https://linux-hardware.org/?probe=87989ace9b) | Mar 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ace3fe8d13](https://linux-hardware.org/?probe=ace3fe8d13) | Mar 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3fbd06d734](https://linux-hardware.org/?probe=3fbd06d734) | Mar 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7c31f8a6ac](https://linux-hardware.org/?probe=7c31f8a6ac) | Mar 23, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [53a7830bc0](https://linux-hardware.org/?probe=53a7830bc0) | Mar 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| ASRock        | B560M-HDV                   | Desktop     | [f54eafc909](https://linux-hardware.org/?probe=f54eafc909) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e7181d25ff](https://linux-hardware.org/?probe=e7181d25ff) | Mar 23, 2022 |
| System76      | Lemur Pro                   | Notebook    | [cd847b5e6a](https://linux-hardware.org/?probe=cd847b5e6a) | Mar 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [20f2d24112](https://linux-hardware.org/?probe=20f2d24112) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| MSI           | GS30 2M Shadow              | Notebook    | [5a117cae70](https://linux-hardware.org/?probe=5a117cae70) | Mar 23, 2022 |
| Alienware     | 0FPV4P A00                  | Desktop     | [b1d20542b8](https://linux-hardware.org/?probe=b1d20542b8) | Mar 23, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [ad7882c51c](https://linux-hardware.org/?probe=ad7882c51c) | Mar 23, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| Acer          | Aspire 5830TG               | Notebook    | [681005049f](https://linux-hardware.org/?probe=681005049f) | Mar 22, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3208ae7baf](https://linux-hardware.org/?probe=3208ae7baf) | Mar 22, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | Notebook    | [4d54a6af03](https://linux-hardware.org/?probe=4d54a6af03) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [66f133fcf0](https://linux-hardware.org/?probe=66f133fcf0) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [0e17f0194f](https://linux-hardware.org/?probe=0e17f0194f) | Mar 22, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [67066e47d3](https://linux-hardware.org/?probe=67066e47d3) | Mar 22, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | Desktop     | [35f8ba571f](https://linux-hardware.org/?probe=35f8ba571f) | Mar 22, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [b4511f91a2](https://linux-hardware.org/?probe=b4511f91a2) | Mar 22, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [e8bbca6adf](https://linux-hardware.org/?probe=e8bbca6adf) | Mar 21, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Dell          | Latitude 5420               | Notebook    | [b1a1e20ab3](https://linux-hardware.org/?probe=b1a1e20ab3) | Mar 21, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | Desktop     | [b789768b64](https://linux-hardware.org/?probe=b789768b64) | Mar 21, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [b2fd45aebb](https://linux-hardware.org/?probe=b2fd45aebb) | Mar 21, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [9ff3211d28](https://linux-hardware.org/?probe=9ff3211d28) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [50348e45ec](https://linux-hardware.org/?probe=50348e45ec) | Mar 20, 2022 |
| MSI           | B250M PRO-VH                | Desktop     | [d3885311bc](https://linux-hardware.org/?probe=d3885311bc) | Mar 20, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [30d244eb42](https://linux-hardware.org/?probe=30d244eb42) | Mar 20, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | Desktop     | [db394898e7](https://linux-hardware.org/?probe=db394898e7) | Mar 20, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [6911af9ce1](https://linux-hardware.org/?probe=6911af9ce1) | Mar 20, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [f7e06f0d6a](https://linux-hardware.org/?probe=f7e06f0d6a) | Mar 20, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [949cc3d3c4](https://linux-hardware.org/?probe=949cc3d3c4) | Mar 20, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [cd26d78db2](https://linux-hardware.org/?probe=cd26d78db2) | Mar 20, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a5d8eebb8c](https://linux-hardware.org/?probe=a5d8eebb8c) | Mar 20, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [978401b13f](https://linux-hardware.org/?probe=978401b13f) | Mar 19, 2022 |
| Dell          | Latitude 3540               | Notebook    | [6d95fdc85c](https://linux-hardware.org/?probe=6d95fdc85c) | Mar 19, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [c2085f4682](https://linux-hardware.org/?probe=c2085f4682) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [861e43b0c6](https://linux-hardware.org/?probe=861e43b0c6) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8328ee30d7](https://linux-hardware.org/?probe=8328ee30d7) | Mar 19, 2022 |
| Dell          | System Vostro 3450          | Notebook    | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1c178b66d4](https://linux-hardware.org/?probe=1c178b66d4) | Mar 19, 2022 |
| Dell          | System XPS L502X            | Notebook    | [6de37bd23c](https://linux-hardware.org/?probe=6de37bd23c) | Mar 19, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [893f0d0600](https://linux-hardware.org/?probe=893f0d0600) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [3693169add](https://linux-hardware.org/?probe=3693169add) | Mar 19, 2022 |
| HP            | 2B4B                        | Desktop     | [def1b2ee5b](https://linux-hardware.org/?probe=def1b2ee5b) | Mar 19, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [6c60e6d6af](https://linux-hardware.org/?probe=6c60e6d6af) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d64fc66c4](https://linux-hardware.org/?probe=9d64fc66c4) | Mar 19, 2022 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [a412a37e5f](https://linux-hardware.org/?probe=a412a37e5f) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| Dell          | 0C4Y3R A00                  | Server      | [5e1b9f2f68](https://linux-hardware.org/?probe=5e1b9f2f68) | Mar 18, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [79f6f7d9c1](https://linux-hardware.org/?probe=79f6f7d9c1) | Mar 18, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0c7c91a687](https://linux-hardware.org/?probe=0c7c91a687) | Mar 18, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [188141a9c9](https://linux-hardware.org/?probe=188141a9c9) | Mar 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [e425e911e9](https://linux-hardware.org/?probe=e425e911e9) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [5531c7e4aa](https://linux-hardware.org/?probe=5531c7e4aa) | Mar 18, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [a3c7a555df](https://linux-hardware.org/?probe=a3c7a555df) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a3b5b7c37e](https://linux-hardware.org/?probe=a3b5b7c37e) | Mar 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5d2c6c0279](https://linux-hardware.org/?probe=5d2c6c0279) | Mar 18, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [bf2f07e405](https://linux-hardware.org/?probe=bf2f07e405) | Mar 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [f43e92acdd](https://linux-hardware.org/?probe=f43e92acdd) | Mar 18, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [461d8aa18b](https://linux-hardware.org/?probe=461d8aa18b) | Mar 17, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [984debdd3a](https://linux-hardware.org/?probe=984debdd3a) | Mar 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [1b90446e3a](https://linux-hardware.org/?probe=1b90446e3a) | Mar 17, 2022 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [172c4ac7f6](https://linux-hardware.org/?probe=172c4ac7f6) | Mar 17, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5813e3000a](https://linux-hardware.org/?probe=5813e3000a) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [f0cd55f2b2](https://linux-hardware.org/?probe=f0cd55f2b2) | Mar 17, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [421906c2ff](https://linux-hardware.org/?probe=421906c2ff) | Mar 17, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [e704011071](https://linux-hardware.org/?probe=e704011071) | Mar 16, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ffa4f295ea](https://linux-hardware.org/?probe=ffa4f295ea) | Mar 16, 2022 |
| Notebook      | P65xHP                      | Notebook    | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [147ab6c35e](https://linux-hardware.org/?probe=147ab6c35e) | Mar 16, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [09340e0b12](https://linux-hardware.org/?probe=09340e0b12) | Mar 16, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [1fea8c1b2b](https://linux-hardware.org/?probe=1fea8c1b2b) | Mar 16, 2022 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [09ac53276d](https://linux-hardware.org/?probe=09ac53276d) | Mar 16, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f1f12206d5](https://linux-hardware.org/?probe=f1f12206d5) | Mar 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [38dfe1da08](https://linux-hardware.org/?probe=38dfe1da08) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [c630bfd983](https://linux-hardware.org/?probe=c630bfd983) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5af008b464](https://linux-hardware.org/?probe=5af008b464) | Mar 15, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [be15e65580](https://linux-hardware.org/?probe=be15e65580) | Mar 15, 2022 |
| Dell          | Latitude 5179               | Tablet      | [e2e7d9ce38](https://linux-hardware.org/?probe=e2e7d9ce38) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [ce34107bae](https://linux-hardware.org/?probe=ce34107bae) | Mar 14, 2022 |
| HP            | 8056                        | Desktop     | [4e8b5eb8bd](https://linux-hardware.org/?probe=4e8b5eb8bd) | Mar 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [7c50a4be17](https://linux-hardware.org/?probe=7c50a4be17) | Mar 14, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [47bfa2ee49](https://linux-hardware.org/?probe=47bfa2ee49) | Mar 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [96846ed571](https://linux-hardware.org/?probe=96846ed571) | Mar 14, 2022 |
| Google        | Samus                       | Notebook    | [9e3da82a58](https://linux-hardware.org/?probe=9e3da82a58) | Mar 14, 2022 |
| Dell          | G5 5500                     | Notebook    | [12a4380cad](https://linux-hardware.org/?probe=12a4380cad) | Mar 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a604ce30de](https://linux-hardware.org/?probe=a604ce30de) | Mar 14, 2022 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [446c515964](https://linux-hardware.org/?probe=446c515964) | Mar 14, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [ae1bd048b6](https://linux-hardware.org/?probe=ae1bd048b6) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [ef6a4d20a7](https://linux-hardware.org/?probe=ef6a4d20a7) | Mar 14, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [9c1fd2beff](https://linux-hardware.org/?probe=9c1fd2beff) | Mar 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [911881e47f](https://linux-hardware.org/?probe=911881e47f) | Mar 14, 2022 |
| Lenovo        | Flex 3-1120 80LX            | Notebook    | [181446e2e8](https://linux-hardware.org/?probe=181446e2e8) | Mar 14, 2022 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [38f9d1058f](https://linux-hardware.org/?probe=38f9d1058f) | Mar 14, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [3aded823d8](https://linux-hardware.org/?probe=3aded823d8) | Mar 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [51ecff9e53](https://linux-hardware.org/?probe=51ecff9e53) | Mar 13, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [ed2262d433](https://linux-hardware.org/?probe=ed2262d433) | Mar 13, 2022 |
| Biostar       | TZ590-BTC DUO               | Desktop     | [fa2f8683b7](https://linux-hardware.org/?probe=fa2f8683b7) | Mar 13, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ed5eba97e9](https://linux-hardware.org/?probe=ed5eba97e9) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [9ca31007a9](https://linux-hardware.org/?probe=9ca31007a9) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8748617cf6](https://linux-hardware.org/?probe=8748617cf6) | Mar 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a4a0bfd589](https://linux-hardware.org/?probe=a4a0bfd589) | Mar 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [69776eaddb](https://linux-hardware.org/?probe=69776eaddb) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| ASUSTek       | H110T                       | Desktop     | [5ef8fe35e7](https://linux-hardware.org/?probe=5ef8fe35e7) | Mar 13, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [f8ef0e1c18](https://linux-hardware.org/?probe=f8ef0e1c18) | Mar 12, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [a93650d1a2](https://linux-hardware.org/?probe=a93650d1a2) | Mar 12, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.304     | Desktop     | [e2e15f011b](https://linux-hardware.org/?probe=e2e15f011b) | Mar 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [0e4fb3e1fd](https://linux-hardware.org/?probe=0e4fb3e1fd) | Mar 12, 2022 |
| ASRock        | B560M-HDV                   | Desktop     | [45e9c424b0](https://linux-hardware.org/?probe=45e9c424b0) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6e87cdd1f8](https://linux-hardware.org/?probe=6e87cdd1f8) | Mar 12, 2022 |
| ECS           | Nettle3                     | Desktop     | [7a96fa9c3f](https://linux-hardware.org/?probe=7a96fa9c3f) | Mar 12, 2022 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d27fc1966e](https://linux-hardware.org/?probe=d27fc1966e) | Mar 12, 2022 |
| Dell          | Latitude 5179               | Tablet      | [19e47782ab](https://linux-hardware.org/?probe=19e47782ab) | Mar 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [1d225e4863](https://linux-hardware.org/?probe=1d225e4863) | Mar 12, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [508f6f6c0c](https://linux-hardware.org/?probe=508f6f6c0c) | Mar 11, 2022 |
| Acer          | Aspire V5-552PG             | Notebook    | [5f0d6016fc](https://linux-hardware.org/?probe=5f0d6016fc) | Mar 11, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f306866523](https://linux-hardware.org/?probe=f306866523) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0c4ce09431](https://linux-hardware.org/?probe=0c4ce09431) | Mar 11, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [734698831b](https://linux-hardware.org/?probe=734698831b) | Mar 11, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [034b528c9b](https://linux-hardware.org/?probe=034b528c9b) | Mar 11, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [c79a71b9db](https://linux-hardware.org/?probe=c79a71b9db) | Mar 11, 2022 |
| ASUSTek       | Q501LA                      | Notebook    | [bf2f9b2c1d](https://linux-hardware.org/?probe=bf2f9b2c1d) | Mar 11, 2022 |
| Dell          | G7 7588                     | Notebook    | [bd49253351](https://linux-hardware.org/?probe=bd49253351) | Mar 11, 2022 |
| Dell          | Latitude 5179               | Tablet      | [6430380d5b](https://linux-hardware.org/?probe=6430380d5b) | Mar 11, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [f3a97cad04](https://linux-hardware.org/?probe=f3a97cad04) | Mar 11, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [f72047dc6d](https://linux-hardware.org/?probe=f72047dc6d) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [9de4c6210f](https://linux-hardware.org/?probe=9de4c6210f) | Mar 11, 2022 |
| ASUSTek       | H110T                       | Desktop     | [2e32ea8d20](https://linux-hardware.org/?probe=2e32ea8d20) | Mar 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Dell          | Latitude 5179               | Tablet      | [3e5a3e7110](https://linux-hardware.org/?probe=3e5a3e7110) | Mar 10, 2022 |
| Intel         | H61                         | Desktop     | [8ce8958b88](https://linux-hardware.org/?probe=8ce8958b88) | Mar 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9bb17a1c87](https://linux-hardware.org/?probe=9bb17a1c87) | Mar 10, 2022 |
| ASUSTek       | H110T                       | Desktop     | [1a3a353683](https://linux-hardware.org/?probe=1a3a353683) | Mar 10, 2022 |
| Dell          | Latitude 3500               | Notebook    | [6b355ab81f](https://linux-hardware.org/?probe=6b355ab81f) | Mar 10, 2022 |
| Intel         | H61                         | Desktop     | [cb91470ea7](https://linux-hardware.org/?probe=cb91470ea7) | Mar 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [b60fd7636c](https://linux-hardware.org/?probe=b60fd7636c) | Mar 10, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [8e7b1db68f](https://linux-hardware.org/?probe=8e7b1db68f) | Mar 09, 2022 |
| Gigabyte      | Z77P-D3                     | Desktop     | [55cb8434d9](https://linux-hardware.org/?probe=55cb8434d9) | Mar 09, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [86dc3583ca](https://linux-hardware.org/?probe=86dc3583ca) | Mar 09, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [2eeb109321](https://linux-hardware.org/?probe=2eeb109321) | Mar 09, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [fe8ce505f4](https://linux-hardware.org/?probe=fe8ce505f4) | Mar 09, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [3e80ef6096](https://linux-hardware.org/?probe=3e80ef6096) | Mar 09, 2022 |
| MSI           | Z590 PRO WIFI [CEC]         | Desktop     | [e543f0217a](https://linux-hardware.org/?probe=e543f0217a) | Mar 09, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [60550484ba](https://linux-hardware.org/?probe=60550484ba) | Mar 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [64ff6efbda](https://linux-hardware.org/?probe=64ff6efbda) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [aef8901d13](https://linux-hardware.org/?probe=aef8901d13) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e1e3698dbc](https://linux-hardware.org/?probe=e1e3698dbc) | Mar 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b17f80ef48](https://linux-hardware.org/?probe=b17f80ef48) | Mar 08, 2022 |
| Dell          | Latitude 9420               | Notebook    | [6cb4dd22ee](https://linux-hardware.org/?probe=6cb4dd22ee) | Mar 08, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [35c65c10b0](https://linux-hardware.org/?probe=35c65c10b0) | Mar 08, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [a1a19b3342](https://linux-hardware.org/?probe=a1a19b3342) | Mar 08, 2022 |
| Dell          | Latitude XT3                | Notebook    | [780d68029c](https://linux-hardware.org/?probe=780d68029c) | Mar 08, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [00b59d57b7](https://linux-hardware.org/?probe=00b59d57b7) | Mar 08, 2022 |
| HP            | 8266                        | Desktop     | [3f34cb2ada](https://linux-hardware.org/?probe=3f34cb2ada) | Mar 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [dd0ebc18ce](https://linux-hardware.org/?probe=dd0ebc18ce) | Mar 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [d5c1e965d0](https://linux-hardware.org/?probe=d5c1e965d0) | Mar 07, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [5a711af850](https://linux-hardware.org/?probe=5a711af850) | Mar 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [d00f0e5d1f](https://linux-hardware.org/?probe=d00f0e5d1f) | Mar 07, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| System76      | Lemur Pro                   | Notebook    | [69ce23b9f3](https://linux-hardware.org/?probe=69ce23b9f3) | Mar 07, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [88c5f71c1d](https://linux-hardware.org/?probe=88c5f71c1d) | Mar 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [561f82adc5](https://linux-hardware.org/?probe=561f82adc5) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [8d0b8e2e12](https://linux-hardware.org/?probe=8d0b8e2e12) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [ea3781cdac](https://linux-hardware.org/?probe=ea3781cdac) | Mar 07, 2022 |
| ASRock        | H310M-HDV                   | Desktop     | [5be286e220](https://linux-hardware.org/?probe=5be286e220) | Mar 07, 2022 |
| Intel         | H61                         | Desktop     | [5198074ef6](https://linux-hardware.org/?probe=5198074ef6) | Mar 07, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [422afde3de](https://linux-hardware.org/?probe=422afde3de) | Mar 07, 2022 |
| HP            | 802F                        | Desktop     | [af498c9331](https://linux-hardware.org/?probe=af498c9331) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [b227e92b83](https://linux-hardware.org/?probe=b227e92b83) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [ef72c023ac](https://linux-hardware.org/?probe=ef72c023ac) | Mar 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [a54e3f7d94](https://linux-hardware.org/?probe=a54e3f7d94) | Mar 07, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [2ee17064c4](https://linux-hardware.org/?probe=2ee17064c4) | Mar 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [86796279cb](https://linux-hardware.org/?probe=86796279cb) | Mar 06, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [4c45b3ea17](https://linux-hardware.org/?probe=4c45b3ea17) | Mar 06, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [a76e22e410](https://linux-hardware.org/?probe=a76e22e410) | Mar 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4d84ed2405](https://linux-hardware.org/?probe=4d84ed2405) | Mar 06, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [e893774a5b](https://linux-hardware.org/?probe=e893774a5b) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [632b62bd7c](https://linux-hardware.org/?probe=632b62bd7c) | Mar 06, 2022 |
| HP            | 8054                        | Desktop     | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [8aa740825f](https://linux-hardware.org/?probe=8aa740825f) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [308df080e6](https://linux-hardware.org/?probe=308df080e6) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [71714718d9](https://linux-hardware.org/?probe=71714718d9) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [ccd6a19ec5](https://linux-hardware.org/?probe=ccd6a19ec5) | Mar 06, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [d7c3e61995](https://linux-hardware.org/?probe=d7c3e61995) | Mar 06, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [4b98ae2c5e](https://linux-hardware.org/?probe=4b98ae2c5e) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [2afe92c38f](https://linux-hardware.org/?probe=2afe92c38f) | Mar 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [52a16c13b1](https://linux-hardware.org/?probe=52a16c13b1) | Mar 06, 2022 |
| AZW           | GT-R                        | Notebook    | [a97ebeedcc](https://linux-hardware.org/?probe=a97ebeedcc) | Mar 06, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [50f8055f7f](https://linux-hardware.org/?probe=50f8055f7f) | Mar 05, 2022 |
| System76      | Gazelle                     | Notebook    | [13946c778f](https://linux-hardware.org/?probe=13946c778f) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e508dbbb0f](https://linux-hardware.org/?probe=e508dbbb0f) | Mar 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [eb0e69e637](https://linux-hardware.org/?probe=eb0e69e637) | Mar 05, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [d7d139723f](https://linux-hardware.org/?probe=d7d139723f) | Mar 05, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [95d4a7b220](https://linux-hardware.org/?probe=95d4a7b220) | Mar 05, 2022 |
| MOTILE        | M141                        | Notebook    | [932800cf07](https://linux-hardware.org/?probe=932800cf07) | Mar 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ce783fbb35](https://linux-hardware.org/?probe=ce783fbb35) | Mar 05, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [4c83283b70](https://linux-hardware.org/?probe=4c83283b70) | Mar 05, 2022 |
| System76      | Gazelle                     | Notebook    | [2fcfb8f348](https://linux-hardware.org/?probe=2fcfb8f348) | Mar 05, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [be345eb07f](https://linux-hardware.org/?probe=be345eb07f) | Mar 04, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [779a3314fd](https://linux-hardware.org/?probe=779a3314fd) | Mar 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [9a400ff743](https://linux-hardware.org/?probe=9a400ff743) | Mar 04, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [7c9250a463](https://linux-hardware.org/?probe=7c9250a463) | Mar 04, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [caec25c98b](https://linux-hardware.org/?probe=caec25c98b) | Mar 04, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [3e98f59715](https://linux-hardware.org/?probe=3e98f59715) | Mar 04, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [7557a0afed](https://linux-hardware.org/?probe=7557a0afed) | Mar 03, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [000e4e07d6](https://linux-hardware.org/?probe=000e4e07d6) | Mar 03, 2022 |
| Acer          | Aspire VN7-591G             | Notebook    | [57452c9459](https://linux-hardware.org/?probe=57452c9459) | Mar 03, 2022 |
| ASUSTek       | X102BA                      | Notebook    | [dd03a06a21](https://linux-hardware.org/?probe=dd03a06a21) | Mar 03, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [d42b913693](https://linux-hardware.org/?probe=d42b913693) | Mar 03, 2022 |
| Lenovo        | G40-70 20369                | Notebook    | [fd797ac0c1](https://linux-hardware.org/?probe=fd797ac0c1) | Mar 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [72a9d60f1b](https://linux-hardware.org/?probe=72a9d60f1b) | Mar 03, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [09b1cd7548](https://linux-hardware.org/?probe=09b1cd7548) | Mar 03, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [5b318b52ed](https://linux-hardware.org/?probe=5b318b52ed) | Mar 03, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [0c4fa64cba](https://linux-hardware.org/?probe=0c4fa64cba) | Mar 03, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [84811329cc](https://linux-hardware.org/?probe=84811329cc) | Mar 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [511563dfc4](https://linux-hardware.org/?probe=511563dfc4) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f649eca74f](https://linux-hardware.org/?probe=f649eca74f) | Mar 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [2861edc794](https://linux-hardware.org/?probe=2861edc794) | Mar 02, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [ff0bd61bd4](https://linux-hardware.org/?probe=ff0bd61bd4) | Mar 02, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | Notebook    | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9444d52862](https://linux-hardware.org/?probe=9444d52862) | Mar 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7fc2d5d090](https://linux-hardware.org/?probe=7fc2d5d090) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [e6bb78efda](https://linux-hardware.org/?probe=e6bb78efda) | Mar 02, 2022 |
| Schenker      | XMG CORE (CZN/E21)          | Notebook    | [c2aa5e4261](https://linux-hardware.org/?probe=c2aa5e4261) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ce31110aaa](https://linux-hardware.org/?probe=ce31110aaa) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [3327e56999](https://linux-hardware.org/?probe=3327e56999) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [5e3f7f344c](https://linux-hardware.org/?probe=5e3f7f344c) | Mar 01, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f81d9300](https://linux-hardware.org/?probe=96f81d9300) | Mar 01, 2022 |
| ASUSTek       | G750JM                      | Notebook    | [c93f5b5bc5](https://linux-hardware.org/?probe=c93f5b5bc5) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [65a9b832d2](https://linux-hardware.org/?probe=65a9b832d2) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [738744d850](https://linux-hardware.org/?probe=738744d850) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | Notebook    | [3d50d924b6](https://linux-hardware.org/?probe=3d50d924b6) | Mar 01, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [0224398912](https://linux-hardware.org/?probe=0224398912) | Mar 01, 2022 |
| HP            | 3396                        | Desktop     | [f952a8f044](https://linux-hardware.org/?probe=f952a8f044) | Mar 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2660f37932](https://linux-hardware.org/?probe=2660f37932) | Mar 01, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [a61bbca53e](https://linux-hardware.org/?probe=a61bbca53e) | Mar 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [96867d5b82](https://linux-hardware.org/?probe=96867d5b82) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [965172e73e](https://linux-hardware.org/?probe=965172e73e) | Feb 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [289e96e8c0](https://linux-hardware.org/?probe=289e96e8c0) | Feb 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [f0c13794e9](https://linux-hardware.org/?probe=f0c13794e9) | Feb 28, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [9c482a1888](https://linux-hardware.org/?probe=9c482a1888) | Feb 28, 2022 |
| Dell          | 0XKD8M A00                  | All in one  | [bef244106f](https://linux-hardware.org/?probe=bef244106f) | Feb 28, 2022 |
| Dell          | 0XKD8M A00                  | All in one  | [aaf687cff9](https://linux-hardware.org/?probe=aaf687cff9) | Feb 28, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [122a25202d](https://linux-hardware.org/?probe=122a25202d) | Feb 28, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [f7d139aebd](https://linux-hardware.org/?probe=f7d139aebd) | Feb 28, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [846c33b65f](https://linux-hardware.org/?probe=846c33b65f) | Feb 28, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [0b5acd433c](https://linux-hardware.org/?probe=0b5acd433c) | Feb 28, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [0ca5693900](https://linux-hardware.org/?probe=0ca5693900) | Feb 28, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [1afd9c4ebc](https://linux-hardware.org/?probe=1afd9c4ebc) | Feb 28, 2022 |
| Medion        | MS-7728                     | Desktop     | [c1a78e4700](https://linux-hardware.org/?probe=c1a78e4700) | Feb 28, 2022 |
| Toshiba       | Satellite S75-A             | Notebook    | [fd969044ad](https://linux-hardware.org/?probe=fd969044ad) | Feb 28, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [d1c5534f6d](https://linux-hardware.org/?probe=d1c5534f6d) | Feb 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [e7a8b4af9f](https://linux-hardware.org/?probe=e7a8b4af9f) | Feb 27, 2022 |
| Dell          | Inspiron 5323               | Notebook    | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| System76      | Oryx Pro                    | Notebook    | [fe9b58fb6f](https://linux-hardware.org/?probe=fe9b58fb6f) | Feb 27, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [7cc9909959](https://linux-hardware.org/?probe=7cc9909959) | Feb 27, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [560de0b6fd](https://linux-hardware.org/?probe=560de0b6fd) | Feb 27, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [c607041591](https://linux-hardware.org/?probe=c607041591) | Feb 27, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [84540806f9](https://linux-hardware.org/?probe=84540806f9) | Feb 27, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [532115a4ec](https://linux-hardware.org/?probe=532115a4ec) | Feb 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [197e180922](https://linux-hardware.org/?probe=197e180922) | Feb 26, 2022 |
| Sony          | VAIO                        | All in one  | [4d477a343a](https://linux-hardware.org/?probe=4d477a343a) | Feb 26, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [567a2d4073](https://linux-hardware.org/?probe=567a2d4073) | Feb 26, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [35d85c45c6](https://linux-hardware.org/?probe=35d85c45c6) | Feb 26, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [2ff40eba25](https://linux-hardware.org/?probe=2ff40eba25) | Feb 26, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [101d5588d2](https://linux-hardware.org/?probe=101d5588d2) | Feb 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | Notebook    | [434e981fa5](https://linux-hardware.org/?probe=434e981fa5) | Feb 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | Notebook    | [772d89dccf](https://linux-hardware.org/?probe=772d89dccf) | Feb 26, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [73992b02d0](https://linux-hardware.org/?probe=73992b02d0) | Feb 26, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [a61b7b1a9d](https://linux-hardware.org/?probe=a61b7b1a9d) | Feb 26, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [707dc0d97b](https://linux-hardware.org/?probe=707dc0d97b) | Feb 26, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [678e1eb19b](https://linux-hardware.org/?probe=678e1eb19b) | Feb 26, 2022 |
| Dell          | Latitude 9420               | Notebook    | [47a60ff67c](https://linux-hardware.org/?probe=47a60ff67c) | Feb 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6c7773fcf5](https://linux-hardware.org/?probe=6c7773fcf5) | Feb 25, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [ac581c6a60](https://linux-hardware.org/?probe=ac581c6a60) | Feb 25, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [255c47a106](https://linux-hardware.org/?probe=255c47a106) | Feb 25, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [163b1f4a34](https://linux-hardware.org/?probe=163b1f4a34) | Feb 25, 2022 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [8cf0979b6f](https://linux-hardware.org/?probe=8cf0979b6f) | Feb 25, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [5c169a1d32](https://linux-hardware.org/?probe=5c169a1d32) | Feb 25, 2022 |
| Lenovo        | ThinkPad T460s 20FAS21F0... | Notebook    | [51c148c501](https://linux-hardware.org/?probe=51c148c501) | Feb 25, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [7159c22bcd](https://linux-hardware.org/?probe=7159c22bcd) | Feb 25, 2022 |
| Dell          | 0N185P A01                  | Desktop     | [996f9f7805](https://linux-hardware.org/?probe=996f9f7805) | Feb 24, 2022 |
| LG Electro... | S425-G.BC31P1               | Notebook    | [d08e9c2b6c](https://linux-hardware.org/?probe=d08e9c2b6c) | Feb 24, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [06aa2ee2d6](https://linux-hardware.org/?probe=06aa2ee2d6) | Feb 24, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8aacf2ed8e](https://linux-hardware.org/?probe=8aacf2ed8e) | Feb 24, 2022 |
| HP            | 15                          | Notebook    | [9fad172623](https://linux-hardware.org/?probe=9fad172623) | Feb 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e54a0d2f67](https://linux-hardware.org/?probe=e54a0d2f67) | Feb 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [319fac3323](https://linux-hardware.org/?probe=319fac3323) | Feb 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [95ff70277e](https://linux-hardware.org/?probe=95ff70277e) | Feb 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e9d9cfb3e9](https://linux-hardware.org/?probe=e9d9cfb3e9) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [487957580f](https://linux-hardware.org/?probe=487957580f) | Feb 24, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [20b0cf0db9](https://linux-hardware.org/?probe=20b0cf0db9) | Feb 24, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b334dfe70e](https://linux-hardware.org/?probe=b334dfe70e) | Feb 23, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [d23f71000a](https://linux-hardware.org/?probe=d23f71000a) | Feb 23, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS19E0... | Notebook    | [b1ea22a167](https://linux-hardware.org/?probe=b1ea22a167) | Feb 23, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [182750aa6b](https://linux-hardware.org/?probe=182750aa6b) | Feb 23, 2022 |
| Lenovo        | ThinkPad A485 20MU000NUS    | Notebook    | [86f99d5ba8](https://linux-hardware.org/?probe=86f99d5ba8) | Feb 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [48b7e73a88](https://linux-hardware.org/?probe=48b7e73a88) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fb10931f05](https://linux-hardware.org/?probe=fb10931f05) | Feb 23, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [25023733fa](https://linux-hardware.org/?probe=25023733fa) | Feb 23, 2022 |
| ASRock        | 4X4-V1000                   | Desktop     | [0008774b64](https://linux-hardware.org/?probe=0008774b64) | Feb 23, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [7bb148611f](https://linux-hardware.org/?probe=7bb148611f) | Feb 23, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [0908586213](https://linux-hardware.org/?probe=0908586213) | Feb 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [59846bd87b](https://linux-hardware.org/?probe=59846bd87b) | Feb 22, 2022 |
| HP            | 1589                        | Desktop     | [c7b43e89e4](https://linux-hardware.org/?probe=c7b43e89e4) | Feb 22, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [fd6e6baf9b](https://linux-hardware.org/?probe=fd6e6baf9b) | Feb 22, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [16cc6721c4](https://linux-hardware.org/?probe=16cc6721c4) | Feb 22, 2022 |
| Medion        | Erazer P7647 MD60803        | Notebook    | [e958bf729a](https://linux-hardware.org/?probe=e958bf729a) | Feb 22, 2022 |
| HP            | 1497                        | Desktop     | [1f1bad3464](https://linux-hardware.org/?probe=1f1bad3464) | Feb 22, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [883e979d85](https://linux-hardware.org/?probe=883e979d85) | Feb 22, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [0be5823fc2](https://linux-hardware.org/?probe=0be5823fc2) | Feb 22, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [77ab4a5017](https://linux-hardware.org/?probe=77ab4a5017) | Feb 22, 2022 |
| LG Electro... | R410-L.D211P1               | Notebook    | [db073c90fd](https://linux-hardware.org/?probe=db073c90fd) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a7e2bf2206](https://linux-hardware.org/?probe=a7e2bf2206) | Feb 22, 2022 |
| System76      | Oryx Pro                    | Notebook    | [8809e21feb](https://linux-hardware.org/?probe=8809e21feb) | Feb 22, 2022 |
| Lenovo        | ThinkPad T420 4180LVP       | Notebook    | [f044c1a44d](https://linux-hardware.org/?probe=f044c1a44d) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [37231251ed](https://linux-hardware.org/?probe=37231251ed) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5f4ae11597](https://linux-hardware.org/?probe=5f4ae11597) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [d8c0892058](https://linux-hardware.org/?probe=d8c0892058) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [fa1b42a476](https://linux-hardware.org/?probe=fa1b42a476) | Feb 21, 2022 |
| MSI           | GL63 8SE                    | Notebook    | [5bdd3eb21e](https://linux-hardware.org/?probe=5bdd3eb21e) | Feb 21, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [d4d5aa3b0a](https://linux-hardware.org/?probe=d4d5aa3b0a) | Feb 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| HP            | 212B                        | Desktop     | [5dd25a71c5](https://linux-hardware.org/?probe=5dd25a71c5) | Feb 21, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [d7cea444f3](https://linux-hardware.org/?probe=d7cea444f3) | Feb 20, 2022 |
| Pegatron      | EVE                         | Desktop     | [facec46bd5](https://linux-hardware.org/?probe=facec46bd5) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5b8dafb532](https://linux-hardware.org/?probe=5b8dafb532) | Feb 20, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [544609e7d5](https://linux-hardware.org/?probe=544609e7d5) | Feb 20, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [6f419a41f3](https://linux-hardware.org/?probe=6f419a41f3) | Feb 20, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c9f390cd7c](https://linux-hardware.org/?probe=c9f390cd7c) | Feb 20, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [99db17b61d](https://linux-hardware.org/?probe=99db17b61d) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [83b3333eb0](https://linux-hardware.org/?probe=83b3333eb0) | Feb 20, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [f0964465f1](https://linux-hardware.org/?probe=f0964465f1) | Feb 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8278526d5e](https://linux-hardware.org/?probe=8278526d5e) | Feb 20, 2022 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [a921d03315](https://linux-hardware.org/?probe=a921d03315) | Feb 19, 2022 |
| HP            | ProBook 6475b               | Notebook    | [d1ec585515](https://linux-hardware.org/?probe=d1ec585515) | Feb 19, 2022 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [7202d23361](https://linux-hardware.org/?probe=7202d23361) | Feb 19, 2022 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [07cbf077d9](https://linux-hardware.org/?probe=07cbf077d9) | Feb 19, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8a64c8dde8](https://linux-hardware.org/?probe=8a64c8dde8) | Feb 19, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [00427ca464](https://linux-hardware.org/?probe=00427ca464) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [565ef5309f](https://linux-hardware.org/?probe=565ef5309f) | Feb 19, 2022 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | Desktop     | [f5befc40e5](https://linux-hardware.org/?probe=f5befc40e5) | Feb 19, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [317e098a9e](https://linux-hardware.org/?probe=317e098a9e) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [21e91da000](https://linux-hardware.org/?probe=21e91da000) | Feb 19, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [a7401b2ad7](https://linux-hardware.org/?probe=a7401b2ad7) | Feb 19, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0b554c2d97](https://linux-hardware.org/?probe=0b554c2d97) | Feb 19, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [bce5253028](https://linux-hardware.org/?probe=bce5253028) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [50b1c22625](https://linux-hardware.org/?probe=50b1c22625) | Feb 19, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [012fe96455](https://linux-hardware.org/?probe=012fe96455) | Feb 19, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [7c32edcf20](https://linux-hardware.org/?probe=7c32edcf20) | Feb 18, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [b6f947ed63](https://linux-hardware.org/?probe=b6f947ed63) | Feb 18, 2022 |
| Dell          | Latitude 7275               | Tablet      | [14bcc9219c](https://linux-hardware.org/?probe=14bcc9219c) | Feb 18, 2022 |
| Acer          | Aspire 5741Z                | Notebook    | [93f3b53e77](https://linux-hardware.org/?probe=93f3b53e77) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [bca6717713](https://linux-hardware.org/?probe=bca6717713) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f7e1ab4276](https://linux-hardware.org/?probe=f7e1ab4276) | Feb 18, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440 20B7003LBR    | Notebook    | [74fa6de20d](https://linux-hardware.org/?probe=74fa6de20d) | Feb 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [e0b7b774be](https://linux-hardware.org/?probe=e0b7b774be) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [917db2bac9](https://linux-hardware.org/?probe=917db2bac9) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8791991562](https://linux-hardware.org/?probe=8791991562) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | Notebook    | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [76d8378c4f](https://linux-hardware.org/?probe=76d8378c4f) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [924a8f6b7f](https://linux-hardware.org/?probe=924a8f6b7f) | Feb 16, 2022 |
| Acer          | Aspire M3-581T              | Notebook    | [1229cec202](https://linux-hardware.org/?probe=1229cec202) | Feb 16, 2022 |
| System76      | Galago Pro                  | Notebook    | [01db998e51](https://linux-hardware.org/?probe=01db998e51) | Feb 16, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b205b32b2a](https://linux-hardware.org/?probe=b205b32b2a) | Feb 16, 2022 |
| Dell          | Latitude 7275               | Tablet      | [143e5a0a20](https://linux-hardware.org/?probe=143e5a0a20) | Feb 16, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [b889f04704](https://linux-hardware.org/?probe=b889f04704) | Feb 16, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [e0cc6a9cfc](https://linux-hardware.org/?probe=e0cc6a9cfc) | Feb 16, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f3ee6f9dbb](https://linux-hardware.org/?probe=f3ee6f9dbb) | Feb 16, 2022 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [357bc81fab](https://linux-hardware.org/?probe=357bc81fab) | Feb 16, 2022 |
| MSI           | MS-7250                     | Desktop     | [90d2809bdf](https://linux-hardware.org/?probe=90d2809bdf) | Feb 16, 2022 |
| HP            | DevX                        | Notebook    | [8dc3513586](https://linux-hardware.org/?probe=8dc3513586) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9f433c19b4](https://linux-hardware.org/?probe=9f433c19b4) | Feb 16, 2022 |
| HP            | DevX                        | Notebook    | [c6f8c8e65b](https://linux-hardware.org/?probe=c6f8c8e65b) | Feb 16, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [2505367a60](https://linux-hardware.org/?probe=2505367a60) | Feb 16, 2022 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [81c6849a8d](https://linux-hardware.org/?probe=81c6849a8d) | Feb 15, 2022 |
| Gigabyte      | P65                         | Notebook    | [cdf1c189f5](https://linux-hardware.org/?probe=cdf1c189f5) | Feb 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9dda4043d1](https://linux-hardware.org/?probe=9dda4043d1) | Feb 15, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [b2414fb6fc](https://linux-hardware.org/?probe=b2414fb6fc) | Feb 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [2dd964cf93](https://linux-hardware.org/?probe=2dd964cf93) | Feb 15, 2022 |
| Sony          | VPCEH38FG                   | Notebook    | [15472f67f5](https://linux-hardware.org/?probe=15472f67f5) | Feb 15, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [34fff5bf39](https://linux-hardware.org/?probe=34fff5bf39) | Feb 15, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [00251b219f](https://linux-hardware.org/?probe=00251b219f) | Feb 14, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9055e23b83](https://linux-hardware.org/?probe=9055e23b83) | Feb 14, 2022 |
| Dell          | Latitude 5510               | Notebook    | [380cb3e46b](https://linux-hardware.org/?probe=380cb3e46b) | Feb 14, 2022 |
| Dell          | Latitude 5510               | Notebook    | [37a6c67d71](https://linux-hardware.org/?probe=37a6c67d71) | Feb 14, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [74173b18da](https://linux-hardware.org/?probe=74173b18da) | Feb 14, 2022 |
| Dell          | Inspiron 15-5568            | Notebook    | [515a271915](https://linux-hardware.org/?probe=515a271915) | Feb 14, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [2aad458cd3](https://linux-hardware.org/?probe=2aad458cd3) | Feb 14, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [9f998d72c0](https://linux-hardware.org/?probe=9f998d72c0) | Feb 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f093ba7890](https://linux-hardware.org/?probe=f093ba7890) | Feb 14, 2022 |
| System76      | Oryx Pro                    | Notebook    | [edaa07bb1f](https://linux-hardware.org/?probe=edaa07bb1f) | Feb 14, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [aa3ec329c6](https://linux-hardware.org/?probe=aa3ec329c6) | Feb 14, 2022 |
| HP            | 2AF8                        | Desktop     | [b336741b02](https://linux-hardware.org/?probe=b336741b02) | Feb 14, 2022 |
| System76      | Pangolin                    | Notebook    | [f078284029](https://linux-hardware.org/?probe=f078284029) | Feb 14, 2022 |
| Gigabyte      | M68M-S2P                    | Desktop     | [775639095e](https://linux-hardware.org/?probe=775639095e) | Feb 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [fc63d0ede8](https://linux-hardware.org/?probe=fc63d0ede8) | Feb 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [469ab361d5](https://linux-hardware.org/?probe=469ab361d5) | Feb 13, 2022 |
| Lenovo        | ThinkPad T450 20BUS0GT00    | Notebook    | [08d79afb4a](https://linux-hardware.org/?probe=08d79afb4a) | Feb 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0d41a14486](https://linux-hardware.org/?probe=0d41a14486) | Feb 13, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [d2a90294b3](https://linux-hardware.org/?probe=d2a90294b3) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6a5e3e1b92](https://linux-hardware.org/?probe=6a5e3e1b92) | Feb 13, 2022 |
| ASUSTek       | K84C                        | Notebook    | [4ca657e962](https://linux-hardware.org/?probe=4ca657e962) | Feb 12, 2022 |
| Lenovo        | ThinkPad L380 20M5S08R00    | Notebook    | [a505a2ae47](https://linux-hardware.org/?probe=a505a2ae47) | Feb 12, 2022 |
| Lenovo        | ThinkPad L380 20M5S08R00    | Notebook    | [315d27f7d7](https://linux-hardware.org/?probe=315d27f7d7) | Feb 12, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2d8b23b026](https://linux-hardware.org/?probe=2d8b23b026) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| ECS           | A75F2-M2                    | Desktop     | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [32d9ce9d27](https://linux-hardware.org/?probe=32d9ce9d27) | Feb 12, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [791cf67d84](https://linux-hardware.org/?probe=791cf67d84) | Feb 12, 2022 |
| Dell          | 0DT097 A00                  | Server      | [ca96304cac](https://linux-hardware.org/?probe=ca96304cac) | Feb 12, 2022 |
| Lenovo        | IdeaPad Yoga 13 20226       | Notebook    | [b08c29e9fd](https://linux-hardware.org/?probe=b08c29e9fd) | Feb 12, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [baa5837734](https://linux-hardware.org/?probe=baa5837734) | Feb 12, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [879dbc6171](https://linux-hardware.org/?probe=879dbc6171) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [caf1721ebe](https://linux-hardware.org/?probe=caf1721ebe) | Feb 12, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [0d9d3a0b9b](https://linux-hardware.org/?probe=0d9d3a0b9b) | Feb 12, 2022 |
| Lenovo        | Yoga710-15ISK 80U0          | Notebook    | [79662ddb24](https://linux-hardware.org/?probe=79662ddb24) | Feb 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4b812791ad](https://linux-hardware.org/?probe=4b812791ad) | Feb 12, 2022 |
| System76      | Galago Pro                  | Notebook    | [3795018074](https://linux-hardware.org/?probe=3795018074) | Feb 12, 2022 |
| System76      | Lemur Pro                   | Notebook    | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Samsung       | 530XBB                      | Notebook    | [4da9be49c4](https://linux-hardware.org/?probe=4da9be49c4) | Feb 12, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [2ad209abc4](https://linux-hardware.org/?probe=2ad209abc4) | Feb 12, 2022 |
| Dell          | Latitude E6430              | Notebook    | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| ASUSTek       | K84C                        | Notebook    | [338aea772f](https://linux-hardware.org/?probe=338aea772f) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Dell          | G3 3590                     | Notebook    | [2e84266d29](https://linux-hardware.org/?probe=2e84266d29) | Feb 11, 2022 |
| System76      | Galago Pro                  | Notebook    | [0277e9ff33](https://linux-hardware.org/?probe=0277e9ff33) | Feb 11, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [c400d6b3f2](https://linux-hardware.org/?probe=c400d6b3f2) | Feb 11, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [fcc19d0759](https://linux-hardware.org/?probe=fcc19d0759) | Feb 11, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [1a59a757f0](https://linux-hardware.org/?probe=1a59a757f0) | Feb 11, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [6b2970ce21](https://linux-hardware.org/?probe=6b2970ce21) | Feb 11, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c0afb91a67](https://linux-hardware.org/?probe=c0afb91a67) | Feb 11, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [5afdb45b44](https://linux-hardware.org/?probe=5afdb45b44) | Feb 10, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [4756364ef6](https://linux-hardware.org/?probe=4756364ef6) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [5826f694e9](https://linux-hardware.org/?probe=5826f694e9) | Feb 10, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [8f0eb971ec](https://linux-hardware.org/?probe=8f0eb971ec) | Feb 10, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [97fe6ef143](https://linux-hardware.org/?probe=97fe6ef143) | Feb 10, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [0094ddce46](https://linux-hardware.org/?probe=0094ddce46) | Feb 10, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [b29422e3cd](https://linux-hardware.org/?probe=b29422e3cd) | Feb 10, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0c54ad1557](https://linux-hardware.org/?probe=0c54ad1557) | Feb 10, 2022 |
| ASUSTek       | Z450UAK                     | Notebook    | [d619483cc3](https://linux-hardware.org/?probe=d619483cc3) | Feb 10, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3f8cee48c5](https://linux-hardware.org/?probe=3f8cee48c5) | Feb 10, 2022 |
| ASUSTek       | Rampage II GENE             | Desktop     | [2f13c2e219](https://linux-hardware.org/?probe=2f13c2e219) | Feb 10, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f66de47847](https://linux-hardware.org/?probe=f66de47847) | Feb 10, 2022 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [3df98a2c5e](https://linux-hardware.org/?probe=3df98a2c5e) | Feb 09, 2022 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [6e92f61334](https://linux-hardware.org/?probe=6e92f61334) | Feb 09, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b98ae7b6b2](https://linux-hardware.org/?probe=b98ae7b6b2) | Feb 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [91805c35ac](https://linux-hardware.org/?probe=91805c35ac) | Feb 09, 2022 |
| System76      | Pangolin                    | Notebook    | [2910f58d41](https://linux-hardware.org/?probe=2910f58d41) | Feb 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [5b2eb74790](https://linux-hardware.org/?probe=5b2eb74790) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [032a9ffa7a](https://linux-hardware.org/?probe=032a9ffa7a) | Feb 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [d08f0c4b79](https://linux-hardware.org/?probe=d08f0c4b79) | Feb 08, 2022 |
| Vulcan Ele... | Excursion XC                | Tablet      | [d833657e6c](https://linux-hardware.org/?probe=d833657e6c) | Feb 08, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [ce2c94c97c](https://linux-hardware.org/?probe=ce2c94c97c) | Feb 07, 2022 |
| Jumper        | EZbook                      | Notebook    | [30a733224e](https://linux-hardware.org/?probe=30a733224e) | Feb 07, 2022 |
| Jumper        | EZbook                      | Notebook    | [91c92e09fc](https://linux-hardware.org/?probe=91c92e09fc) | Feb 07, 2022 |
| Dell          | G5 5500                     | Notebook    | [de24d5a5f8](https://linux-hardware.org/?probe=de24d5a5f8) | Feb 07, 2022 |
| ASUSTek       | X55A                        | Notebook    | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| ASUSTek       | X555LP                      | Notebook    | [be0f6bd68e](https://linux-hardware.org/?probe=be0f6bd68e) | Feb 07, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d018a94552](https://linux-hardware.org/?probe=d018a94552) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [f619840852](https://linux-hardware.org/?probe=f619840852) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [0892485b4b](https://linux-hardware.org/?probe=0892485b4b) | Feb 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [49e7ed1d1a](https://linux-hardware.org/?probe=49e7ed1d1a) | Feb 07, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [084f4469b2](https://linux-hardware.org/?probe=084f4469b2) | Feb 07, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [71eb3575ec](https://linux-hardware.org/?probe=71eb3575ec) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [fe0fc0573f](https://linux-hardware.org/?probe=fe0fc0573f) | Feb 07, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [56726f31e3](https://linux-hardware.org/?probe=56726f31e3) | Feb 07, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2a1df5c52b](https://linux-hardware.org/?probe=2a1df5c52b) | Feb 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [972365b3d4](https://linux-hardware.org/?probe=972365b3d4) | Feb 06, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ed4001ca5](https://linux-hardware.org/?probe=9ed4001ca5) | Feb 06, 2022 |
| Dell          | G5 5587                     | Notebook    | [33819e0316](https://linux-hardware.org/?probe=33819e0316) | Feb 06, 2022 |
| Dell          | G5 5587                     | Notebook    | [6fcaa54ab0](https://linux-hardware.org/?probe=6fcaa54ab0) | Feb 06, 2022 |
| Toshiba       | Satellite L55t-B            | Notebook    | [9cc401fb9e](https://linux-hardware.org/?probe=9cc401fb9e) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e5f7c593d7](https://linux-hardware.org/?probe=e5f7c593d7) | Feb 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [87c57369ab](https://linux-hardware.org/?probe=87c57369ab) | Feb 06, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [425dcf3bb9](https://linux-hardware.org/?probe=425dcf3bb9) | Feb 06, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [4512482f07](https://linux-hardware.org/?probe=4512482f07) | Feb 06, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [24bd4956b6](https://linux-hardware.org/?probe=24bd4956b6) | Feb 05, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [4664ace096](https://linux-hardware.org/?probe=4664ace096) | Feb 05, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6e2649ece6](https://linux-hardware.org/?probe=6e2649ece6) | Feb 05, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [bf8d058c93](https://linux-hardware.org/?probe=bf8d058c93) | Feb 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [5de24590cc](https://linux-hardware.org/?probe=5de24590cc) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65a6ca3880](https://linux-hardware.org/?probe=65a6ca3880) | Feb 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a147de0139](https://linux-hardware.org/?probe=a147de0139) | Feb 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b9d4efb68c](https://linux-hardware.org/?probe=b9d4efb68c) | Feb 05, 2022 |
| ASUSTek       | Q501LA                      | Notebook    | [dba764a522](https://linux-hardware.org/?probe=dba764a522) | Feb 05, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b8f7e7d9d8](https://linux-hardware.org/?probe=b8f7e7d9d8) | Feb 05, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [0062581573](https://linux-hardware.org/?probe=0062581573) | Feb 05, 2022 |
| ASUSTek       | Q501LA                      | Notebook    | [40ffb91a0d](https://linux-hardware.org/?probe=40ffb91a0d) | Feb 05, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [0059d3699f](https://linux-hardware.org/?probe=0059d3699f) | Feb 05, 2022 |
| Dell          | G5 5500                     | Notebook    | [edd04957d8](https://linux-hardware.org/?probe=edd04957d8) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [8aab9e3d48](https://linux-hardware.org/?probe=8aab9e3d48) | Feb 05, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a79460f50d](https://linux-hardware.org/?probe=a79460f50d) | Feb 05, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [ba669bd729](https://linux-hardware.org/?probe=ba669bd729) | Feb 05, 2022 |
| Samsung       | 530XBB                      | Notebook    | [ccc2c811de](https://linux-hardware.org/?probe=ccc2c811de) | Feb 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [63f2430481](https://linux-hardware.org/?probe=63f2430481) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [379d3b37b1](https://linux-hardware.org/?probe=379d3b37b1) | Feb 05, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [813388a4b1](https://linux-hardware.org/?probe=813388a4b1) | Feb 04, 2022 |
| System76      | Galago Pro                  | Notebook    | [9d10a7c279](https://linux-hardware.org/?probe=9d10a7c279) | Feb 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [3928781324](https://linux-hardware.org/?probe=3928781324) | Feb 04, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [3fc3a14ef3](https://linux-hardware.org/?probe=3fc3a14ef3) | Feb 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [144717a1f1](https://linux-hardware.org/?probe=144717a1f1) | Feb 04, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a5a7eac778](https://linux-hardware.org/?probe=a5a7eac778) | Feb 04, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [becd915336](https://linux-hardware.org/?probe=becd915336) | Feb 04, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [d14bd1019f](https://linux-hardware.org/?probe=d14bd1019f) | Feb 04, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [872772f278](https://linux-hardware.org/?probe=872772f278) | Feb 04, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [5b314a7764](https://linux-hardware.org/?probe=5b314a7764) | Feb 04, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [9a2365cd5c](https://linux-hardware.org/?probe=9a2365cd5c) | Feb 04, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [6a6b14cdb5](https://linux-hardware.org/?probe=6a6b14cdb5) | Feb 04, 2022 |
| Dell          | Precision 7720              | Notebook    | [7d1d38b364](https://linux-hardware.org/?probe=7d1d38b364) | Feb 04, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9f9151546a](https://linux-hardware.org/?probe=9f9151546a) | Feb 03, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [59386238f2](https://linux-hardware.org/?probe=59386238f2) | Feb 03, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [401d8111bd](https://linux-hardware.org/?probe=401d8111bd) | Feb 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2cedc7632](https://linux-hardware.org/?probe=e2cedc7632) | Feb 03, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [a4978d8283](https://linux-hardware.org/?probe=a4978d8283) | Feb 03, 2022 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [5b21313e24](https://linux-hardware.org/?probe=5b21313e24) | Feb 03, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [1e60876b1e](https://linux-hardware.org/?probe=1e60876b1e) | Feb 03, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [3c8e7bd3eb](https://linux-hardware.org/?probe=3c8e7bd3eb) | Feb 03, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [8f287ca9e1](https://linux-hardware.org/?probe=8f287ca9e1) | Feb 03, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [dfa7d6bf8c](https://linux-hardware.org/?probe=dfa7d6bf8c) | Feb 03, 2022 |
| Intel         | NUC6i7KYB H90766-407        | Mini pc     | [079ab2222e](https://linux-hardware.org/?probe=079ab2222e) | Feb 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [1d86468b90](https://linux-hardware.org/?probe=1d86468b90) | Feb 03, 2022 |
| Multilaser    | PC024                       | Tablet      | [9ad6a77447](https://linux-hardware.org/?probe=9ad6a77447) | Feb 03, 2022 |
| Multilaser    | PC024                       | Tablet      | [bd6cbc4c5e](https://linux-hardware.org/?probe=bd6cbc4c5e) | Feb 03, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b5ae920f3b](https://linux-hardware.org/?probe=b5ae920f3b) | Feb 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [52d5157fd9](https://linux-hardware.org/?probe=52d5157fd9) | Feb 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6ad31c02f7](https://linux-hardware.org/?probe=6ad31c02f7) | Feb 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [c70d2672d3](https://linux-hardware.org/?probe=c70d2672d3) | Feb 02, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47c47a0121](https://linux-hardware.org/?probe=47c47a0121) | Feb 02, 2022 |
| HP            | Pavilion g7                 | Notebook    | [520f4ed91f](https://linux-hardware.org/?probe=520f4ed91f) | Feb 02, 2022 |
| HP            | Pavilion g7                 | Notebook    | [7ff4adf123](https://linux-hardware.org/?probe=7ff4adf123) | Feb 02, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [d9a9a300f6](https://linux-hardware.org/?probe=d9a9a300f6) | Feb 02, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1af8c957ee](https://linux-hardware.org/?probe=1af8c957ee) | Feb 02, 2022 |
| Panasonic     | CF-C2ACAZXLM                | Notebook    | [9de7e5f3b9](https://linux-hardware.org/?probe=9de7e5f3b9) | Feb 02, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [14d778971f](https://linux-hardware.org/?probe=14d778971f) | Feb 02, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ffc510ba8e](https://linux-hardware.org/?probe=ffc510ba8e) | Feb 02, 2022 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d0c774f36d](https://linux-hardware.org/?probe=d0c774f36d) | Feb 02, 2022 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [bde4142497](https://linux-hardware.org/?probe=bde4142497) | Feb 02, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [f12174ddb8](https://linux-hardware.org/?probe=f12174ddb8) | Feb 02, 2022 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [09274c49c4](https://linux-hardware.org/?probe=09274c49c4) | Feb 02, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [7b278e62d8](https://linux-hardware.org/?probe=7b278e62d8) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [ad29a7f260](https://linux-hardware.org/?probe=ad29a7f260) | Feb 01, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [5cc8e8f8d3](https://linux-hardware.org/?probe=5cc8e8f8d3) | Feb 01, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [ac0fd77d33](https://linux-hardware.org/?probe=ac0fd77d33) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f1062af79c](https://linux-hardware.org/?probe=f1062af79c) | Feb 01, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [b12edb18d5](https://linux-hardware.org/?probe=b12edb18d5) | Feb 01, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5616230c16](https://linux-hardware.org/?probe=5616230c16) | Feb 01, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [c8025340af](https://linux-hardware.org/?probe=c8025340af) | Feb 01, 2022 |
| Wortmann      | 1220663_1470189             | Notebook    | [3f09a29186](https://linux-hardware.org/?probe=3f09a29186) | Feb 01, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [15dc80f08b](https://linux-hardware.org/?probe=15dc80f08b) | Feb 01, 2022 |
| Dell          | 08K0X7 A00                  | Desktop     | [8a390406ca](https://linux-hardware.org/?probe=8a390406ca) | Feb 01, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c29b15a852](https://linux-hardware.org/?probe=c29b15a852) | Feb 01, 2022 |
| ASUSTek       | N82JV                       | Notebook    | [8a93115cc9](https://linux-hardware.org/?probe=8a93115cc9) | Feb 01, 2022 |
| ASUSTek       | N82JV                       | Notebook    | [1c29e0d77e](https://linux-hardware.org/?probe=1c29e0d77e) | Feb 01, 2022 |
| Dell          | Precision 5530              | Notebook    | [5408c7e9ce](https://linux-hardware.org/?probe=5408c7e9ce) | Feb 01, 2022 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [42458aca09](https://linux-hardware.org/?probe=42458aca09) | Feb 01, 2022 |
| Lenovo        | ThinkPad Edge 05782GP       | Notebook    | [fc49fcb2f6](https://linux-hardware.org/?probe=fc49fcb2f6) | Jan 31, 2022 |
| Dell          | Precision 5530              | Notebook    | [54fbbcf16a](https://linux-hardware.org/?probe=54fbbcf16a) | Jan 31, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| System76      | Oryx Pro                    | Notebook    | [c6b13cfa37](https://linux-hardware.org/?probe=c6b13cfa37) | Jan 31, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [65e7fc8820](https://linux-hardware.org/?probe=65e7fc8820) | Jan 31, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [69613ba320](https://linux-hardware.org/?probe=69613ba320) | Jan 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [829c0b88a2](https://linux-hardware.org/?probe=829c0b88a2) | Jan 31, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [2cfe7d7f31](https://linux-hardware.org/?probe=2cfe7d7f31) | Jan 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [54b9aa9f99](https://linux-hardware.org/?probe=54b9aa9f99) | Jan 31, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [90a7a21524](https://linux-hardware.org/?probe=90a7a21524) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| System76      | Galago Pro                  | Notebook    | [a7f5f19cbd](https://linux-hardware.org/?probe=a7f5f19cbd) | Jan 30, 2022 |
| ASUSTek       | ZenBook UX363JA_UX363JA     | Convertible | [d240c961cf](https://linux-hardware.org/?probe=d240c961cf) | Jan 30, 2022 |
| HP            | 843B                        | Desktop     | [a769e6bb29](https://linux-hardware.org/?probe=a769e6bb29) | Jan 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccd7847b28](https://linux-hardware.org/?probe=ccd7847b28) | Jan 30, 2022 |
| Alienware     | 13 R2                       | Notebook    | [bc3b8ba7d5](https://linux-hardware.org/?probe=bc3b8ba7d5) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [d3f7315d42](https://linux-hardware.org/?probe=d3f7315d42) | Jan 30, 2022 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a3b9160a9b](https://linux-hardware.org/?probe=a3b9160a9b) | Jan 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [b4f3d4f1ee](https://linux-hardware.org/?probe=b4f3d4f1ee) | Jan 30, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [4aedd751a2](https://linux-hardware.org/?probe=4aedd751a2) | Jan 30, 2022 |
| ASUSTek       | GR8                         | Notebook    | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [98f458a763](https://linux-hardware.org/?probe=98f458a763) | Jan 30, 2022 |
| MSI           | GL65 Leopard 10SFKV         | Notebook    | [30eb9a3b75](https://linux-hardware.org/?probe=30eb9a3b75) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| Alienware     | 13 R2                       | Notebook    | [112514da64](https://linux-hardware.org/?probe=112514da64) | Jan 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [8840e8dbd1](https://linux-hardware.org/?probe=8840e8dbd1) | Jan 29, 2022 |
| HP            | 1998                        | Desktop     | [9c2d7377b6](https://linux-hardware.org/?probe=9c2d7377b6) | Jan 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [ea20e32cbd](https://linux-hardware.org/?probe=ea20e32cbd) | Jan 29, 2022 |
| Dell          | 0XC7MM A01                  | Desktop     | [802d9ec1da](https://linux-hardware.org/?probe=802d9ec1da) | Jan 29, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [625e78374f](https://linux-hardware.org/?probe=625e78374f) | Jan 29, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [b6f35f9625](https://linux-hardware.org/?probe=b6f35f9625) | Jan 29, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [03ef8065a5](https://linux-hardware.org/?probe=03ef8065a5) | Jan 29, 2022 |
| HP            | Notebook                    | Notebook    | [f0fa0c4619](https://linux-hardware.org/?probe=f0fa0c4619) | Jan 29, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [fc189e6c81](https://linux-hardware.org/?probe=fc189e6c81) | Jan 29, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [435c894ed4](https://linux-hardware.org/?probe=435c894ed4) | Jan 29, 2022 |
| Positivo      | Mobile                      | Notebook    | [c461425f95](https://linux-hardware.org/?probe=c461425f95) | Jan 28, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [3fa09080ea](https://linux-hardware.org/?probe=3fa09080ea) | Jan 28, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [f4f305b201](https://linux-hardware.org/?probe=f4f305b201) | Jan 28, 2022 |
| MSI           | GF65 Thin 9SD               | Notebook    | [e834b8aaf6](https://linux-hardware.org/?probe=e834b8aaf6) | Jan 28, 2022 |
| MSI           | H61M-S20                    | Desktop     | [7d0384b2d2](https://linux-hardware.org/?probe=7d0384b2d2) | Jan 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [952dbe0fcf](https://linux-hardware.org/?probe=952dbe0fcf) | Jan 28, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [692c64fd48](https://linux-hardware.org/?probe=692c64fd48) | Jan 28, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [12e15b6f48](https://linux-hardware.org/?probe=12e15b6f48) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [a53478c6b1](https://linux-hardware.org/?probe=a53478c6b1) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [90e1046590](https://linux-hardware.org/?probe=90e1046590) | Jan 28, 2022 |
| ASRock        | H570M Pro4                  | Desktop     | [f773b6ac5b](https://linux-hardware.org/?probe=f773b6ac5b) | Jan 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c32a0ceae2](https://linux-hardware.org/?probe=c32a0ceae2) | Jan 28, 2022 |
| Google        | Elemi                       | Notebook    | [6f39a73d02](https://linux-hardware.org/?probe=6f39a73d02) | Jan 28, 2022 |
| System76      | Serval                      | Notebook    | [4cc9003536](https://linux-hardware.org/?probe=4cc9003536) | Jan 28, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [5d7886a578](https://linux-hardware.org/?probe=5d7886a578) | Jan 28, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b0738bc88e](https://linux-hardware.org/?probe=b0738bc88e) | Jan 28, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [e9a9670c47](https://linux-hardware.org/?probe=e9a9670c47) | Jan 28, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [9e1ad7154f](https://linux-hardware.org/?probe=9e1ad7154f) | Jan 28, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [db9add8409](https://linux-hardware.org/?probe=db9add8409) | Jan 27, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [e7e1ef7da5](https://linux-hardware.org/?probe=e7e1ef7da5) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Dell          | Studio 1555                 | Notebook    | [b287edf684](https://linux-hardware.org/?probe=b287edf684) | Jan 27, 2022 |
| ASRock        | H61M-HG4                    | Desktop     | [442847292d](https://linux-hardware.org/?probe=442847292d) | Jan 27, 2022 |
| Dell          | Studio 1555                 | Notebook    | [85efbe1575](https://linux-hardware.org/?probe=85efbe1575) | Jan 27, 2022 |
| HP            | Notebook                    | Notebook    | [2a363c2ced](https://linux-hardware.org/?probe=2a363c2ced) | Jan 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [de673ddf6a](https://linux-hardware.org/?probe=de673ddf6a) | Jan 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [d3df4ed8e6](https://linux-hardware.org/?probe=d3df4ed8e6) | Jan 26, 2022 |
| MSI           | H310M GAMING ARCTIC         | Desktop     | [842ee88335](https://linux-hardware.org/?probe=842ee88335) | Jan 26, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [fe518d8966](https://linux-hardware.org/?probe=fe518d8966) | Jan 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [d5b37bd94a](https://linux-hardware.org/?probe=d5b37bd94a) | Jan 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2ea8885694](https://linux-hardware.org/?probe=2ea8885694) | Jan 26, 2022 |
| Acer          | Aspire 4741                 | Notebook    | [bb695da9c9](https://linux-hardware.org/?probe=bb695da9c9) | Jan 26, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [80295dd814](https://linux-hardware.org/?probe=80295dd814) | Jan 26, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [39624646b6](https://linux-hardware.org/?probe=39624646b6) | Jan 26, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3ec0bf0bc0](https://linux-hardware.org/?probe=3ec0bf0bc0) | Jan 26, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [f82dab294e](https://linux-hardware.org/?probe=f82dab294e) | Jan 26, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [9db505b8b6](https://linux-hardware.org/?probe=9db505b8b6) | Jan 26, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [acdd3dda23](https://linux-hardware.org/?probe=acdd3dda23) | Jan 26, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [128d6fe128](https://linux-hardware.org/?probe=128d6fe128) | Jan 26, 2022 |
| Dell          | Latitude 5500               | Notebook    | [28d1ea6a16](https://linux-hardware.org/?probe=28d1ea6a16) | Jan 26, 2022 |
| MSI           | B85M-E45                    | Desktop     | [5751d3e736](https://linux-hardware.org/?probe=5751d3e736) | Jan 25, 2022 |
| ASUSTek       | PN50-E1                     | Mini pc     | [f9a8d0f268](https://linux-hardware.org/?probe=f9a8d0f268) | Jan 25, 2022 |
| ASUSTek       | PN50-E1                     | Mini pc     | [aafd5f07b5](https://linux-hardware.org/?probe=aafd5f07b5) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [034f7c3687](https://linux-hardware.org/?probe=034f7c3687) | Jan 25, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [446b36de5b](https://linux-hardware.org/?probe=446b36de5b) | Jan 25, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [f9d319995f](https://linux-hardware.org/?probe=f9d319995f) | Jan 25, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [6ed68d9c3c](https://linux-hardware.org/?probe=6ed68d9c3c) | Jan 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [fbf0ea66aa](https://linux-hardware.org/?probe=fbf0ea66aa) | Jan 25, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [fb556ab9a8](https://linux-hardware.org/?probe=fb556ab9a8) | Jan 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [1ffcad48a5](https://linux-hardware.org/?probe=1ffcad48a5) | Jan 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8b4f45d131](https://linux-hardware.org/?probe=8b4f45d131) | Jan 24, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [9dacac3c89](https://linux-hardware.org/?probe=9dacac3c89) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [7cb75a1cf3](https://linux-hardware.org/?probe=7cb75a1cf3) | Jan 24, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [94fe829346](https://linux-hardware.org/?probe=94fe829346) | Jan 24, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [b30ecb933c](https://linux-hardware.org/?probe=b30ecb933c) | Jan 24, 2022 |
| Alienware     | m15 R6                      | Notebook    | [5e64f0e9a7](https://linux-hardware.org/?probe=5e64f0e9a7) | Jan 23, 2022 |
| Acer          | Aspire A615-51              | Notebook    | [a7cd7b1960](https://linux-hardware.org/?probe=a7cd7b1960) | Jan 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e4b1312fe9](https://linux-hardware.org/?probe=e4b1312fe9) | Jan 23, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c2bf4bf5b9](https://linux-hardware.org/?probe=c2bf4bf5b9) | Jan 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [29ce7637f6](https://linux-hardware.org/?probe=29ce7637f6) | Jan 23, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [6e711f3f7d](https://linux-hardware.org/?probe=6e711f3f7d) | Jan 23, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [e996ff74d5](https://linux-hardware.org/?probe=e996ff74d5) | Jan 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1d1b5d06c7](https://linux-hardware.org/?probe=1d1b5d06c7) | Jan 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [619ebd38aa](https://linux-hardware.org/?probe=619ebd38aa) | Jan 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [cfb12999e8](https://linux-hardware.org/?probe=cfb12999e8) | Jan 23, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [1b2ef9d1dc](https://linux-hardware.org/?probe=1b2ef9d1dc) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [e0197b9fdc](https://linux-hardware.org/?probe=e0197b9fdc) | Jan 23, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [c13943f074](https://linux-hardware.org/?probe=c13943f074) | Jan 23, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [e4f1a055f6](https://linux-hardware.org/?probe=e4f1a055f6) | Jan 23, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2816cb0172](https://linux-hardware.org/?probe=2816cb0172) | Jan 23, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [2d6825d4b2](https://linux-hardware.org/?probe=2d6825d4b2) | Jan 23, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [428c34414b](https://linux-hardware.org/?probe=428c34414b) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | Notebook    | [846db3a265](https://linux-hardware.org/?probe=846db3a265) | Jan 22, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [cbf995ff80](https://linux-hardware.org/?probe=cbf995ff80) | Jan 22, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [90249388ff](https://linux-hardware.org/?probe=90249388ff) | Jan 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d00bdfa39a](https://linux-hardware.org/?probe=d00bdfa39a) | Jan 22, 2022 |
| Huanan        | X99-F8                      | Desktop     | [4e1327b556](https://linux-hardware.org/?probe=4e1327b556) | Jan 22, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e9480f103c](https://linux-hardware.org/?probe=e9480f103c) | Jan 22, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4a0bd17330](https://linux-hardware.org/?probe=4a0bd17330) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3c6b61aac9](https://linux-hardware.org/?probe=3c6b61aac9) | Jan 22, 2022 |
| Dell          | Precision M6500             | Notebook    | [2a4d4ca6dc](https://linux-hardware.org/?probe=2a4d4ca6dc) | Jan 22, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [33d8ae238f](https://linux-hardware.org/?probe=33d8ae238f) | Jan 22, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [552ecc4cd3](https://linux-hardware.org/?probe=552ecc4cd3) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [cf76a7fc3f](https://linux-hardware.org/?probe=cf76a7fc3f) | Jan 22, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [cb552c995b](https://linux-hardware.org/?probe=cb552c995b) | Jan 22, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [33079ee3bf](https://linux-hardware.org/?probe=33079ee3bf) | Jan 22, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [f149fa2604](https://linux-hardware.org/?probe=f149fa2604) | Jan 22, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [535d10bdcb](https://linux-hardware.org/?probe=535d10bdcb) | Jan 22, 2022 |
| Intel         | D54250WYK H13922-304        | Desktop     | [147491a8df](https://linux-hardware.org/?probe=147491a8df) | Jan 22, 2022 |
| ASUSTek       | Rampage II GENE             | Desktop     | [7bda8eb36a](https://linux-hardware.org/?probe=7bda8eb36a) | Jan 21, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5cb8ff854b](https://linux-hardware.org/?probe=5cb8ff854b) | Jan 21, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [291f22ae53](https://linux-hardware.org/?probe=291f22ae53) | Jan 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [b626f9fc62](https://linux-hardware.org/?probe=b626f9fc62) | Jan 21, 2022 |
| MSI           | GE72 2QE                    | Notebook    | [cbd609290e](https://linux-hardware.org/?probe=cbd609290e) | Jan 21, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d3eba9c339](https://linux-hardware.org/?probe=d3eba9c339) | Jan 21, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2882c1a5d4](https://linux-hardware.org/?probe=2882c1a5d4) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [634d45ff9e](https://linux-hardware.org/?probe=634d45ff9e) | Jan 21, 2022 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [ac32945d37](https://linux-hardware.org/?probe=ac32945d37) | Jan 21, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [11de4173b1](https://linux-hardware.org/?probe=11de4173b1) | Jan 21, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [b122aab045](https://linux-hardware.org/?probe=b122aab045) | Jan 21, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [cf1efe764d](https://linux-hardware.org/?probe=cf1efe764d) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d8ec503f66](https://linux-hardware.org/?probe=d8ec503f66) | Jan 21, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [ce8cb0b6e7](https://linux-hardware.org/?probe=ce8cb0b6e7) | Jan 21, 2022 |
| HP            | Laptop 14z-fq0000           | Notebook    | [85c2fdbe47](https://linux-hardware.org/?probe=85c2fdbe47) | Jan 21, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [822b247272](https://linux-hardware.org/?probe=822b247272) | Jan 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [f94829df35](https://linux-hardware.org/?probe=f94829df35) | Jan 20, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [37561394c5](https://linux-hardware.org/?probe=37561394c5) | Jan 20, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [8053ec48d7](https://linux-hardware.org/?probe=8053ec48d7) | Jan 20, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [0f956f27ad](https://linux-hardware.org/?probe=0f956f27ad) | Jan 20, 2022 |
| Dell          | G15 5511                    | Notebook    | [b1a127367b](https://linux-hardware.org/?probe=b1a127367b) | Jan 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [1ab15ca104](https://linux-hardware.org/?probe=1ab15ca104) | Jan 20, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| HP            | 8381 1000                   | All in one  | [acba4af69a](https://linux-hardware.org/?probe=acba4af69a) | Jan 20, 2022 |
| Samsung       | 930QDB                      | Convertible | [e498435120](https://linux-hardware.org/?probe=e498435120) | Jan 20, 2022 |
| System76      | Lemur Pro                   | Notebook    | [7702d19e13](https://linux-hardware.org/?probe=7702d19e13) | Jan 20, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [bbc373d97c](https://linux-hardware.org/?probe=bbc373d97c) | Jan 19, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [be5ef45fee](https://linux-hardware.org/?probe=be5ef45fee) | Jan 19, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [011bdd164f](https://linux-hardware.org/?probe=011bdd164f) | Jan 19, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6edcdd522d](https://linux-hardware.org/?probe=6edcdd522d) | Jan 19, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [7c07d2e27d](https://linux-hardware.org/?probe=7c07d2e27d) | Jan 19, 2022 |
| Dell          | 0KV62T A02                  | Desktop     | [f315491f5a](https://linux-hardware.org/?probe=f315491f5a) | Jan 19, 2022 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [50ce7dd079](https://linux-hardware.org/?probe=50ce7dd079) | Jan 19, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [6d72c9d945](https://linux-hardware.org/?probe=6d72c9d945) | Jan 19, 2022 |
| Samsung       | 930QDB                      | Convertible | [0ed7b7e65d](https://linux-hardware.org/?probe=0ed7b7e65d) | Jan 19, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [c9fc1b6d29](https://linux-hardware.org/?probe=c9fc1b6d29) | Jan 18, 2022 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [0fe0867d33](https://linux-hardware.org/?probe=0fe0867d33) | Jan 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6efcabe998](https://linux-hardware.org/?probe=6efcabe998) | Jan 18, 2022 |
| ASUSTek       | N46VM                       | Notebook    | [0a88f88571](https://linux-hardware.org/?probe=0a88f88571) | Jan 18, 2022 |
| Positivo      | S14SL01                     | Notebook    | [01a64fab08](https://linux-hardware.org/?probe=01a64fab08) | Jan 18, 2022 |
| ASUSTek       | N46VM                       | Notebook    | [4d85d5ff13](https://linux-hardware.org/?probe=4d85d5ff13) | Jan 18, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [977a09eecc](https://linux-hardware.org/?probe=977a09eecc) | Jan 18, 2022 |
| HP            | 1489                        | All in one  | [f321eccadc](https://linux-hardware.org/?probe=f321eccadc) | Jan 18, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a1e32d1e05](https://linux-hardware.org/?probe=a1e32d1e05) | Jan 18, 2022 |
| Dell          | Inspiron 7405 2n1           | Convertible | [8b69cad07c](https://linux-hardware.org/?probe=8b69cad07c) | Jan 18, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29675be978](https://linux-hardware.org/?probe=29675be978) | Jan 18, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [ad25878d8b](https://linux-hardware.org/?probe=ad25878d8b) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [14e649684c](https://linux-hardware.org/?probe=14e649684c) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| Gigabyte      | P65                         | Notebook    | [4664ba9c41](https://linux-hardware.org/?probe=4664ba9c41) | Jan 17, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bfd22356b2](https://linux-hardware.org/?probe=bfd22356b2) | Jan 17, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [faba7de732](https://linux-hardware.org/?probe=faba7de732) | Jan 17, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [4b954d711f](https://linux-hardware.org/?probe=4b954d711f) | Jan 17, 2022 |
| Toshiba       | Satellite A205              | Notebook    | [73774c2271](https://linux-hardware.org/?probe=73774c2271) | Jan 17, 2022 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [229902d68f](https://linux-hardware.org/?probe=229902d68f) | Jan 17, 2022 |
| Acer          | Predator G5900              | Desktop     | [ac6748b172](https://linux-hardware.org/?probe=ac6748b172) | Jan 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2d411179d3](https://linux-hardware.org/?probe=2d411179d3) | Jan 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [abab9725c6](https://linux-hardware.org/?probe=abab9725c6) | Jan 16, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [e7c451f797](https://linux-hardware.org/?probe=e7c451f797) | Jan 16, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [70fcfbfdf5](https://linux-hardware.org/?probe=70fcfbfdf5) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c380a52a13](https://linux-hardware.org/?probe=c380a52a13) | Jan 16, 2022 |
| HP            | ProBook 4540s               | Notebook    | [cdac0ade76](https://linux-hardware.org/?probe=cdac0ade76) | Jan 16, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [5ff3ad853f](https://linux-hardware.org/?probe=5ff3ad853f) | Jan 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [0f5a776f84](https://linux-hardware.org/?probe=0f5a776f84) | Jan 16, 2022 |
| Acer          | Aspire 5749Z                | Notebook    | [8441e54928](https://linux-hardware.org/?probe=8441e54928) | Jan 16, 2022 |
| ASUSTek       | X751YI                      | Notebook    | [7b3834fb55](https://linux-hardware.org/?probe=7b3834fb55) | Jan 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [e68efc018a](https://linux-hardware.org/?probe=e68efc018a) | Jan 16, 2022 |
| HP            | 21F5                        | Desktop     | [ce8e06508d](https://linux-hardware.org/?probe=ce8e06508d) | Jan 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b70c5a1312](https://linux-hardware.org/?probe=b70c5a1312) | Jan 16, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| HP            | 828A                        | Desktop     | [63316bc040](https://linux-hardware.org/?probe=63316bc040) | Jan 16, 2022 |
| Dell          | Latitude 7280               | Notebook    | [d05eb9657d](https://linux-hardware.org/?probe=d05eb9657d) | Jan 16, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [30c9fe2f5f](https://linux-hardware.org/?probe=30c9fe2f5f) | Jan 16, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [baafe7b86f](https://linux-hardware.org/?probe=baafe7b86f) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [7345361fc2](https://linux-hardware.org/?probe=7345361fc2) | Jan 16, 2022 |
| Huanan        | X99-F8                      | Desktop     | [b03aaab88c](https://linux-hardware.org/?probe=b03aaab88c) | Jan 16, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [0baed0f9c8](https://linux-hardware.org/?probe=0baed0f9c8) | Jan 16, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [7fca8e1118](https://linux-hardware.org/?probe=7fca8e1118) | Jan 15, 2022 |
| Acer          | Aspire 5749Z                | Notebook    | [b375496bb6](https://linux-hardware.org/?probe=b375496bb6) | Jan 15, 2022 |
| Dell          | Latitude 3500               | Notebook    | [2b439cb70b](https://linux-hardware.org/?probe=2b439cb70b) | Jan 15, 2022 |
| Dell          | Latitude E4300              | Notebook    | [9112d33b24](https://linux-hardware.org/?probe=9112d33b24) | Jan 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| HP            | 255 G4 Notebook PC          | Notebook    | [34060f3357](https://linux-hardware.org/?probe=34060f3357) | Jan 15, 2022 |
| HP            | 828A                        | Desktop     | [5ecf3c1b51](https://linux-hardware.org/?probe=5ecf3c1b51) | Jan 15, 2022 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [2b7802edc0](https://linux-hardware.org/?probe=2b7802edc0) | Jan 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [e1a43f3dde](https://linux-hardware.org/?probe=e1a43f3dde) | Jan 15, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e045001170](https://linux-hardware.org/?probe=e045001170) | Jan 15, 2022 |
| Dell          | Inspiron 1420               | Notebook    | [35d076d3df](https://linux-hardware.org/?probe=35d076d3df) | Jan 15, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [891e984a74](https://linux-hardware.org/?probe=891e984a74) | Jan 15, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [0b99e83a8a](https://linux-hardware.org/?probe=0b99e83a8a) | Jan 15, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [fdac2f87fe](https://linux-hardware.org/?probe=fdac2f87fe) | Jan 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [0e7f769fd4](https://linux-hardware.org/?probe=0e7f769fd4) | Jan 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [0eecb1e199](https://linux-hardware.org/?probe=0eecb1e199) | Jan 14, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [8ed424ecb0](https://linux-hardware.org/?probe=8ed424ecb0) | Jan 14, 2022 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [eff3de9e51](https://linux-hardware.org/?probe=eff3de9e51) | Jan 14, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d60c747d92](https://linux-hardware.org/?probe=d60c747d92) | Jan 14, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7b12fb3749](https://linux-hardware.org/?probe=7b12fb3749) | Jan 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| MSI           | GE72 2QE                    | Notebook    | [72843af2fc](https://linux-hardware.org/?probe=72843af2fc) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [71480de13b](https://linux-hardware.org/?probe=71480de13b) | Jan 14, 2022 |
| ASUSTek       | TP500LNG                    | Notebook    | [85762ec0a0](https://linux-hardware.org/?probe=85762ec0a0) | Jan 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [23160ed698](https://linux-hardware.org/?probe=23160ed698) | Jan 14, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [2289107616](https://linux-hardware.org/?probe=2289107616) | Jan 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [7dbb72c69c](https://linux-hardware.org/?probe=7dbb72c69c) | Jan 14, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [176be62705](https://linux-hardware.org/?probe=176be62705) | Jan 14, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [9338817523](https://linux-hardware.org/?probe=9338817523) | Jan 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3927618884](https://linux-hardware.org/?probe=3927618884) | Jan 13, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e6827ffa3d](https://linux-hardware.org/?probe=e6827ffa3d) | Jan 13, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [d9ee3ea8d1](https://linux-hardware.org/?probe=d9ee3ea8d1) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [771b852db1](https://linux-hardware.org/?probe=771b852db1) | Jan 12, 2022 |
| HP            | Pavilion dv4                | Notebook    | [56d9d85d29](https://linux-hardware.org/?probe=56d9d85d29) | Jan 12, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [dbbf600ed3](https://linux-hardware.org/?probe=dbbf600ed3) | Jan 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [13b34d87ce](https://linux-hardware.org/?probe=13b34d87ce) | Jan 12, 2022 |
| ASRock        | A320M/ac                    | Desktop     | [e90a9a04aa](https://linux-hardware.org/?probe=e90a9a04aa) | Jan 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [3f856caf75](https://linux-hardware.org/?probe=3f856caf75) | Jan 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2b44f3e733](https://linux-hardware.org/?probe=2b44f3e733) | Jan 12, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [fa62cb2996](https://linux-hardware.org/?probe=fa62cb2996) | Jan 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a8ff8d111b](https://linux-hardware.org/?probe=a8ff8d111b) | Jan 11, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1713b32795](https://linux-hardware.org/?probe=1713b32795) | Jan 11, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [5ed8f41517](https://linux-hardware.org/?probe=5ed8f41517) | Jan 11, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [f67eed490e](https://linux-hardware.org/?probe=f67eed490e) | Jan 11, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [10fa8cf150](https://linux-hardware.org/?probe=10fa8cf150) | Jan 11, 2022 |
| HP            | 0AECh D                     | Desktop     | [88ff603cfe](https://linux-hardware.org/?probe=88ff603cfe) | Jan 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [18943ac7c5](https://linux-hardware.org/?probe=18943ac7c5) | Jan 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [76cb68e427](https://linux-hardware.org/?probe=76cb68e427) | Jan 11, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [2278a225cd](https://linux-hardware.org/?probe=2278a225cd) | Jan 11, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [61a66b9311](https://linux-hardware.org/?probe=61a66b9311) | Jan 11, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [647df46e95](https://linux-hardware.org/?probe=647df46e95) | Jan 11, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [2887c95e00](https://linux-hardware.org/?probe=2887c95e00) | Jan 10, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [cccdc35998](https://linux-hardware.org/?probe=cccdc35998) | Jan 10, 2022 |
| Biostar       | Hi-Fi A70U3P                | Desktop     | [a9e99dfd45](https://linux-hardware.org/?probe=a9e99dfd45) | Jan 10, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [33159068d9](https://linux-hardware.org/?probe=33159068d9) | Jan 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c2c5bfd879](https://linux-hardware.org/?probe=c2c5bfd879) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [f4c9d49611](https://linux-hardware.org/?probe=f4c9d49611) | Jan 10, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [faf4d2a7a7](https://linux-hardware.org/?probe=faf4d2a7a7) | Jan 10, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [96380d6800](https://linux-hardware.org/?probe=96380d6800) | Jan 10, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [bc62713d1d](https://linux-hardware.org/?probe=bc62713d1d) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [5066e9278a](https://linux-hardware.org/?probe=5066e9278a) | Jan 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [6f97aded30](https://linux-hardware.org/?probe=6f97aded30) | Jan 09, 2022 |
| System76      | Serval                      | Notebook    | [3348f9fdec](https://linux-hardware.org/?probe=3348f9fdec) | Jan 09, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [13f90b99ef](https://linux-hardware.org/?probe=13f90b99ef) | Jan 09, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [f212038b15](https://linux-hardware.org/?probe=f212038b15) | Jan 09, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| Acer          | Aspire A514-52G             | Notebook    | [5f6504d850](https://linux-hardware.org/?probe=5f6504d850) | Jan 09, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [2bf3f44e95](https://linux-hardware.org/?probe=2bf3f44e95) | Jan 09, 2022 |
| Dell          | Latitude 7370               | Notebook    | [8126818188](https://linux-hardware.org/?probe=8126818188) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| Dell          | Inspiron 5720               | Notebook    | [8c04c2517c](https://linux-hardware.org/?probe=8c04c2517c) | Jan 09, 2022 |
| Lenovo        | ThinkPad T530 239242U       | Notebook    | [9478dbdc5f](https://linux-hardware.org/?probe=9478dbdc5f) | Jan 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [eeebc29bad](https://linux-hardware.org/?probe=eeebc29bad) | Jan 09, 2022 |
| Dell          | Inspiron 5557               | Notebook    | [fb29216e68](https://linux-hardware.org/?probe=fb29216e68) | Jan 09, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [0ce434e4d9](https://linux-hardware.org/?probe=0ce434e4d9) | Jan 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [5c480976ea](https://linux-hardware.org/?probe=5c480976ea) | Jan 08, 2022 |
| Medion        | BEAST X25                   | Notebook    | [5687f78ea3](https://linux-hardware.org/?probe=5687f78ea3) | Jan 08, 2022 |
| Medion        | BEAST X25                   | Notebook    | [7e8d4b82bc](https://linux-hardware.org/?probe=7e8d4b82bc) | Jan 08, 2022 |
| Dell          | Latitude E6430              | Notebook    | [55794dd17d](https://linux-hardware.org/?probe=55794dd17d) | Jan 08, 2022 |
| Alienware     | M14xR1                      | Notebook    | [cad4426e11](https://linux-hardware.org/?probe=cad4426e11) | Jan 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [86efdd34c0](https://linux-hardware.org/?probe=86efdd34c0) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a23bb3d2c0](https://linux-hardware.org/?probe=a23bb3d2c0) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| ASUSTek       | G56JR                       | Notebook    | [2e4539087b](https://linux-hardware.org/?probe=2e4539087b) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [6be1bf5b86](https://linux-hardware.org/?probe=6be1bf5b86) | Jan 07, 2022 |
| Dell          | Latitude 7370               | Notebook    | [f958ca0b10](https://linux-hardware.org/?probe=f958ca0b10) | Jan 07, 2022 |
| System76      | Serval WS                   | Notebook    | [3c09405e80](https://linux-hardware.org/?probe=3c09405e80) | Jan 07, 2022 |
| MSI           | MS-B0961                    | All in one  | [3136ced425](https://linux-hardware.org/?probe=3136ced425) | Jan 07, 2022 |
| Samsung       | R530/R730                   | Notebook    | [d07e567173](https://linux-hardware.org/?probe=d07e567173) | Jan 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [e7c4424882](https://linux-hardware.org/?probe=e7c4424882) | Jan 06, 2022 |
| MSI           | GE62 2QF                    | Notebook    | [4a961cb5c6](https://linux-hardware.org/?probe=4a961cb5c6) | Jan 06, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e35874c390](https://linux-hardware.org/?probe=e35874c390) | Jan 06, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [bb252bbd37](https://linux-hardware.org/?probe=bb252bbd37) | Jan 06, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b1e07585c2](https://linux-hardware.org/?probe=b1e07585c2) | Jan 06, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [1b1fcf58ee](https://linux-hardware.org/?probe=1b1fcf58ee) | Jan 06, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [179cf54d82](https://linux-hardware.org/?probe=179cf54d82) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [2ec9bc4c20](https://linux-hardware.org/?probe=2ec9bc4c20) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [27181ec03b](https://linux-hardware.org/?probe=27181ec03b) | Jan 06, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [b5ab89a508](https://linux-hardware.org/?probe=b5ab89a508) | Jan 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [f6b5b76a19](https://linux-hardware.org/?probe=f6b5b76a19) | Jan 05, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [7e8a2edc39](https://linux-hardware.org/?probe=7e8a2edc39) | Jan 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [10e8d766de](https://linux-hardware.org/?probe=10e8d766de) | Jan 05, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [5222b66726](https://linux-hardware.org/?probe=5222b66726) | Jan 05, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fffddd6e29](https://linux-hardware.org/?probe=fffddd6e29) | Jan 05, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fec36f1ff0](https://linux-hardware.org/?probe=fec36f1ff0) | Jan 05, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [d628fc0e51](https://linux-hardware.org/?probe=d628fc0e51) | Jan 05, 2022 |
| ASUSTek       | B85-A R2.0                  | Desktop     | [de3800071c](https://linux-hardware.org/?probe=de3800071c) | Jan 05, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [4245c1aed0](https://linux-hardware.org/?probe=4245c1aed0) | Jan 05, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [7ecf7d2f17](https://linux-hardware.org/?probe=7ecf7d2f17) | Jan 05, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [75a92c6550](https://linux-hardware.org/?probe=75a92c6550) | Jan 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8225fd1e60](https://linux-hardware.org/?probe=8225fd1e60) | Jan 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [01462567ad](https://linux-hardware.org/?probe=01462567ad) | Jan 05, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [5f270a7818](https://linux-hardware.org/?probe=5f270a7818) | Jan 04, 2022 |
| Dell          | Inspiron 7586               | Convertible | [9a480f9de9](https://linux-hardware.org/?probe=9a480f9de9) | Jan 04, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [e010eae144](https://linux-hardware.org/?probe=e010eae144) | Jan 04, 2022 |
| ASUSTek       | X550VL                      | Notebook    | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c7b371a826](https://linux-hardware.org/?probe=c7b371a826) | Jan 04, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [27d434def2](https://linux-hardware.org/?probe=27d434def2) | Jan 04, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [faaaf3cc89](https://linux-hardware.org/?probe=faaaf3cc89) | Jan 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [c66b09770b](https://linux-hardware.org/?probe=c66b09770b) | Jan 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [e41a208158](https://linux-hardware.org/?probe=e41a208158) | Jan 04, 2022 |
| Lenovo        | ThinkPad X250 20CLS0E705    | Notebook    | [80a5a608e3](https://linux-hardware.org/?probe=80a5a608e3) | Jan 04, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [8f02ee7ce1](https://linux-hardware.org/?probe=8f02ee7ce1) | Jan 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [6ef9b69e18](https://linux-hardware.org/?probe=6ef9b69e18) | Jan 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [c2d49cd216](https://linux-hardware.org/?probe=c2d49cd216) | Jan 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [24a576a704](https://linux-hardware.org/?probe=24a576a704) | Jan 04, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [a7ec771949](https://linux-hardware.org/?probe=a7ec771949) | Jan 03, 2022 |
| Intel         | B75                         | Desktop     | [303c569097](https://linux-hardware.org/?probe=303c569097) | Jan 03, 2022 |
| System76      | Lemur Pro                   | Notebook    | [6eda434d87](https://linux-hardware.org/?probe=6eda434d87) | Jan 03, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [9b131aecfb](https://linux-hardware.org/?probe=9b131aecfb) | Jan 03, 2022 |
| Alienware     | M14xR1                      | Notebook    | [35a093192f](https://linux-hardware.org/?probe=35a093192f) | Jan 03, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [08864b62d7](https://linux-hardware.org/?probe=08864b62d7) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e325f203ea](https://linux-hardware.org/?probe=e325f203ea) | Jan 03, 2022 |
| MSI           | GS60 2PC Ghost              | Notebook    | [a39693267b](https://linux-hardware.org/?probe=a39693267b) | Jan 03, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [15443b48ca](https://linux-hardware.org/?probe=15443b48ca) | Jan 03, 2022 |
| HP            | 3398                        | Desktop     | [b37e81de0d](https://linux-hardware.org/?probe=b37e81de0d) | Jan 03, 2022 |
| HP            | Pavilion dv4                | Notebook    | [85e045e249](https://linux-hardware.org/?probe=85e045e249) | Jan 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [69b65282f8](https://linux-hardware.org/?probe=69b65282f8) | Jan 03, 2022 |
| Gateway       | NE56R                       | Notebook    | [cf4e3649ab](https://linux-hardware.org/?probe=cf4e3649ab) | Jan 03, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [ac32062ec1](https://linux-hardware.org/?probe=ac32062ec1) | Jan 02, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7a62214858](https://linux-hardware.org/?probe=7a62214858) | Jan 02, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [d727392c87](https://linux-hardware.org/?probe=d727392c87) | Jan 02, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [47887a95e0](https://linux-hardware.org/?probe=47887a95e0) | Jan 02, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f288a91383](https://linux-hardware.org/?probe=f288a91383) | Jan 02, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [d0db4072bf](https://linux-hardware.org/?probe=d0db4072bf) | Jan 02, 2022 |
| Dell          | Latitude E5470              | Notebook    | [f1623fdbd5](https://linux-hardware.org/?probe=f1623fdbd5) | Jan 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [b93cc280ea](https://linux-hardware.org/?probe=b93cc280ea) | Jan 02, 2022 |
| Acer          | Aspire X3400                | Desktop     | [6833137bc8](https://linux-hardware.org/?probe=6833137bc8) | Jan 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [69884555f3](https://linux-hardware.org/?probe=69884555f3) | Jan 02, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2565bdbcf2](https://linux-hardware.org/?probe=2565bdbcf2) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ded316d4d3](https://linux-hardware.org/?probe=ded316d4d3) | Jan 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f6393f5788](https://linux-hardware.org/?probe=f6393f5788) | Jan 01, 2022 |
| System76      | Galago Pro                  | Notebook    | [e5ac474fa4](https://linux-hardware.org/?probe=e5ac474fa4) | Jan 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7774870db](https://linux-hardware.org/?probe=d7774870db) | Jan 01, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [3ad065c802](https://linux-hardware.org/?probe=3ad065c802) | Jan 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9a29b00ea8](https://linux-hardware.org/?probe=9a29b00ea8) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [618b37e477](https://linux-hardware.org/?probe=618b37e477) | Jan 01, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [74de092c5f](https://linux-hardware.org/?probe=74de092c5f) | Jan 01, 2022 |
| Dell          | Latitude E5540              | Notebook    | [1a112d75bc](https://linux-hardware.org/?probe=1a112d75bc) | Jan 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a5cac4ea05](https://linux-hardware.org/?probe=a5cac4ea05) | Jan 01, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [458285856a](https://linux-hardware.org/?probe=458285856a) | Jan 01, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [fb9be834b9](https://linux-hardware.org/?probe=fb9be834b9) | Jan 01, 2022 |
| Positivo      | SW6H                        | Notebook    | [a7566e6187](https://linux-hardware.org/?probe=a7566e6187) | Jan 01, 2022 |
| Dell          | XPS M1530                   | Notebook    | [1d058a526e](https://linux-hardware.org/?probe=1d058a526e) | Dec 31, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [0a7a64e88d](https://linux-hardware.org/?probe=0a7a64e88d) | Dec 31, 2021 |
| Google        | Sion                        | Desktop     | [08215c86b6](https://linux-hardware.org/?probe=08215c86b6) | Dec 31, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [3b65c20517](https://linux-hardware.org/?probe=3b65c20517) | Dec 31, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [2277696526](https://linux-hardware.org/?probe=2277696526) | Dec 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [26643bc267](https://linux-hardware.org/?probe=26643bc267) | Dec 31, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [7cd63ced25](https://linux-hardware.org/?probe=7cd63ced25) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fbd40dba79](https://linux-hardware.org/?probe=fbd40dba79) | Dec 31, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [33497966ff](https://linux-hardware.org/?probe=33497966ff) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [38a2166cb3](https://linux-hardware.org/?probe=38a2166cb3) | Dec 31, 2021 |
| ASRock        | A75M-HVS                    | Desktop     | [d77bbe23b5](https://linux-hardware.org/?probe=d77bbe23b5) | Dec 30, 2021 |
| Samsung       | 550XDA                      | Notebook    | [8f01f7ab00](https://linux-hardware.org/?probe=8f01f7ab00) | Dec 30, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [7e02c5721d](https://linux-hardware.org/?probe=7e02c5721d) | Dec 30, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [49565a2435](https://linux-hardware.org/?probe=49565a2435) | Dec 30, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d2603436d3](https://linux-hardware.org/?probe=d2603436d3) | Dec 30, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [18830ebc64](https://linux-hardware.org/?probe=18830ebc64) | Dec 30, 2021 |
| Samsung       | 930QDB                      | Convertible | [10ba767052](https://linux-hardware.org/?probe=10ba767052) | Dec 30, 2021 |
| Dell          | Latitude E6220              | Notebook    | [f90bddad5c](https://linux-hardware.org/?probe=f90bddad5c) | Dec 30, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [3ef4e652fa](https://linux-hardware.org/?probe=3ef4e652fa) | Dec 30, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a0aa27eb79](https://linux-hardware.org/?probe=a0aa27eb79) | Dec 30, 2021 |
| Google        | Rammus                      | Notebook    | [6f13aafbd1](https://linux-hardware.org/?probe=6f13aafbd1) | Dec 30, 2021 |
| HP            | Compaq 6730s                | Notebook    | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Google        | Rammus                      | Notebook    | [89d97778ab](https://linux-hardware.org/?probe=89d97778ab) | Dec 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [52e697edc3](https://linux-hardware.org/?probe=52e697edc3) | Dec 29, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [a4a22cd651](https://linux-hardware.org/?probe=a4a22cd651) | Dec 29, 2021 |
| ASUSTek       | G751JY                      | Notebook    | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [0184868fb6](https://linux-hardware.org/?probe=0184868fb6) | Dec 29, 2021 |
| System76      | Lemur Pro                   | Notebook    | [287aa601fe](https://linux-hardware.org/?probe=287aa601fe) | Dec 29, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [349b556bd2](https://linux-hardware.org/?probe=349b556bd2) | Dec 29, 2021 |
| Schenker      | XMG CORE (CZN/E21)          | Notebook    | [fa7695f068](https://linux-hardware.org/?probe=fa7695f068) | Dec 29, 2021 |
| Pegatron      | 2AF0                        | Desktop     | [c491a4251a](https://linux-hardware.org/?probe=c491a4251a) | Dec 29, 2021 |
| ASUSTek       | P5E                         | Desktop     | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [12dd615663](https://linux-hardware.org/?probe=12dd615663) | Dec 29, 2021 |
| ASUSTek       | GL503VD                     | Notebook    | [8918ebec98](https://linux-hardware.org/?probe=8918ebec98) | Dec 28, 2021 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [aa4ac7f9c8](https://linux-hardware.org/?probe=aa4ac7f9c8) | Dec 28, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [aa5505f30e](https://linux-hardware.org/?probe=aa5505f30e) | Dec 28, 2021 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [da8ef794e6](https://linux-hardware.org/?probe=da8ef794e6) | Dec 28, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [59d2f4a4da](https://linux-hardware.org/?probe=59d2f4a4da) | Dec 28, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ad0d3ae135](https://linux-hardware.org/?probe=ad0d3ae135) | Dec 28, 2021 |
| ASUSTek       | E402NA                      | Notebook    | [6341af3f2e](https://linux-hardware.org/?probe=6341af3f2e) | Dec 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [be8d1e3f5d](https://linux-hardware.org/?probe=be8d1e3f5d) | Dec 28, 2021 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [9682b75331](https://linux-hardware.org/?probe=9682b75331) | Dec 28, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [8fba60c1a8](https://linux-hardware.org/?probe=8fba60c1a8) | Dec 28, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [469c053f33](https://linux-hardware.org/?probe=469c053f33) | Dec 28, 2021 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [4a81b51d58](https://linux-hardware.org/?probe=4a81b51d58) | Dec 28, 2021 |
| MSI           | MS-7529                     | Desktop     | [c9b87dcf45](https://linux-hardware.org/?probe=c9b87dcf45) | Dec 27, 2021 |
| ASRock        | B85 Pro4                    | Desktop     | [33433ec5e1](https://linux-hardware.org/?probe=33433ec5e1) | Dec 27, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [f4878864ec](https://linux-hardware.org/?probe=f4878864ec) | Dec 27, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2273dcdf3b](https://linux-hardware.org/?probe=2273dcdf3b) | Dec 27, 2021 |
| ASUSTek       | GL503VD                     | Notebook    | [3ef04a0fe1](https://linux-hardware.org/?probe=3ef04a0fe1) | Dec 27, 2021 |
| System76      | Lemur Pro                   | Notebook    | [6dbfd95ccb](https://linux-hardware.org/?probe=6dbfd95ccb) | Dec 27, 2021 |
| Dell          | G15 5515                    | Notebook    | [72c6f7ef61](https://linux-hardware.org/?probe=72c6f7ef61) | Dec 27, 2021 |
| MSI           | GL63 9RCX                   | Notebook    | [ad2628ee28](https://linux-hardware.org/?probe=ad2628ee28) | Dec 27, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [20c1236a23](https://linux-hardware.org/?probe=20c1236a23) | Dec 27, 2021 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [01c5633412](https://linux-hardware.org/?probe=01c5633412) | Dec 27, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [442183a425](https://linux-hardware.org/?probe=442183a425) | Dec 27, 2021 |
| OEM           | I38II                       | Notebook    | [52bc5190dd](https://linux-hardware.org/?probe=52bc5190dd) | Dec 27, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [2a6cc98221](https://linux-hardware.org/?probe=2a6cc98221) | Dec 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [24cecfe4c4](https://linux-hardware.org/?probe=24cecfe4c4) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [8b1b16e186](https://linux-hardware.org/?probe=8b1b16e186) | Dec 26, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [0f7bd5b933](https://linux-hardware.org/?probe=0f7bd5b933) | Dec 26, 2021 |
| System76      | Gazelle                     | Notebook    | [168d3284d3](https://linux-hardware.org/?probe=168d3284d3) | Dec 26, 2021 |
| System76      | Gazelle                     | Notebook    | [1e5b07c8e5](https://linux-hardware.org/?probe=1e5b07c8e5) | Dec 26, 2021 |
| Acer          | Predator PT515-51           | Notebook    | [6b0ffc93de](https://linux-hardware.org/?probe=6b0ffc93de) | Dec 26, 2021 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [d249085990](https://linux-hardware.org/?probe=d249085990) | Dec 26, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [a8fbe33d19](https://linux-hardware.org/?probe=a8fbe33d19) | Dec 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [65b994f10f](https://linux-hardware.org/?probe=65b994f10f) | Dec 26, 2021 |
| Lenovo        | IdeaPad L340 81ly           | Notebook    | [b830077023](https://linux-hardware.org/?probe=b830077023) | Dec 26, 2021 |
| Acer          | TravelMate P255             | Notebook    | [1efdd6ce09](https://linux-hardware.org/?probe=1efdd6ce09) | Dec 26, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [06de3a03ad](https://linux-hardware.org/?probe=06de3a03ad) | Dec 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [eb095b1264](https://linux-hardware.org/?probe=eb095b1264) | Dec 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [046dcdd20d](https://linux-hardware.org/?probe=046dcdd20d) | Dec 25, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [381c7dee2d](https://linux-hardware.org/?probe=381c7dee2d) | Dec 25, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [e72e077346](https://linux-hardware.org/?probe=e72e077346) | Dec 25, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [7f5484cd91](https://linux-hardware.org/?probe=7f5484cd91) | Dec 25, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [1615a0368a](https://linux-hardware.org/?probe=1615a0368a) | Dec 25, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cd5ebfce7](https://linux-hardware.org/?probe=6cd5ebfce7) | Dec 25, 2021 |
| Lenovo        | ThinkPad T420 4236B28       | Notebook    | [1c9b796c43](https://linux-hardware.org/?probe=1c9b796c43) | Dec 25, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [efed26c7ca](https://linux-hardware.org/?probe=efed26c7ca) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [51f97b7e46](https://linux-hardware.org/?probe=51f97b7e46) | Dec 25, 2021 |
| Acer          | Aspire A315-42G             | Notebook    | [453f75585c](https://linux-hardware.org/?probe=453f75585c) | Dec 25, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [a3db8aa97e](https://linux-hardware.org/?probe=a3db8aa97e) | Dec 25, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b13c6ceb2c](https://linux-hardware.org/?probe=b13c6ceb2c) | Dec 25, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3867022c38](https://linux-hardware.org/?probe=3867022c38) | Dec 25, 2021 |
| Dell          | Latitude E6420              | Notebook    | [4f5dab610b](https://linux-hardware.org/?probe=4f5dab610b) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e1713d01a4](https://linux-hardware.org/?probe=e1713d01a4) | Dec 25, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [a45439157c](https://linux-hardware.org/?probe=a45439157c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [93e3145404](https://linux-hardware.org/?probe=93e3145404) | Dec 24, 2021 |
| HP            | 1495                        | Desktop     | [62e7060ad2](https://linux-hardware.org/?probe=62e7060ad2) | Dec 24, 2021 |
| MSI           | GL62 6QC                    | Notebook    | [6f94b1e700](https://linux-hardware.org/?probe=6f94b1e700) | Dec 24, 2021 |
| Dell          | Latitude E6420              | Notebook    | [8018acdc13](https://linux-hardware.org/?probe=8018acdc13) | Dec 24, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f3fd8aa2e](https://linux-hardware.org/?probe=3f3fd8aa2e) | Dec 24, 2021 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [964f340f94](https://linux-hardware.org/?probe=964f340f94) | Dec 24, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| 16216-BM-2... | Z97M GAMING 14655-BV-171... | Desktop     | [c432df16c9](https://linux-hardware.org/?probe=c432df16c9) | Dec 24, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | Notebook    | [ddcf17ca01](https://linux-hardware.org/?probe=ddcf17ca01) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| Apple         | MacBookPro3,1               | Notebook    | [e4e2085912](https://linux-hardware.org/?probe=e4e2085912) | Dec 23, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [d2ce6b29f7](https://linux-hardware.org/?probe=d2ce6b29f7) | Dec 23, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [082e803629](https://linux-hardware.org/?probe=082e803629) | Dec 23, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| Apple         | MacBookPro3,1               | Notebook    | [1dd9331f30](https://linux-hardware.org/?probe=1dd9331f30) | Dec 23, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7830e84ce4](https://linux-hardware.org/?probe=7830e84ce4) | Dec 23, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [0a1cd1d1af](https://linux-hardware.org/?probe=0a1cd1d1af) | Dec 23, 2021 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [c1c7140811](https://linux-hardware.org/?probe=c1c7140811) | Dec 23, 2021 |
| Packard Be... | IXTREME M5850               | Desktop     | [27a73b1bee](https://linux-hardware.org/?probe=27a73b1bee) | Dec 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [be03823889](https://linux-hardware.org/?probe=be03823889) | Dec 23, 2021 |
| Gigabyte      | B550 UD AC                  | Desktop     | [40b52a499f](https://linux-hardware.org/?probe=40b52a499f) | Dec 23, 2021 |
| Sony          | VGN-AW21M_H                 | Notebook    | [b4cf74ec7d](https://linux-hardware.org/?probe=b4cf74ec7d) | Dec 23, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [ea071b8d0b](https://linux-hardware.org/?probe=ea071b8d0b) | Dec 23, 2021 |
| Lenovo        | V470 439627U                | Notebook    | [71387b4f47](https://linux-hardware.org/?probe=71387b4f47) | Dec 23, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [fd30ba561a](https://linux-hardware.org/?probe=fd30ba561a) | Dec 23, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [44387d9605](https://linux-hardware.org/?probe=44387d9605) | Dec 23, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [ed6afea189](https://linux-hardware.org/?probe=ed6afea189) | Dec 23, 2021 |
| HP            | ProBook 4740s               | Notebook    | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| Dell          | G3 3590                     | Notebook    | [0d08aececa](https://linux-hardware.org/?probe=0d08aececa) | Dec 23, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3d2f9b7cc6](https://linux-hardware.org/?probe=3d2f9b7cc6) | Dec 22, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ec93b29eb2](https://linux-hardware.org/?probe=ec93b29eb2) | Dec 22, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9b4dc851c6](https://linux-hardware.org/?probe=9b4dc851c6) | Dec 22, 2021 |
| Dell          | Inspiron 5547               | Notebook    | [605e3df140](https://linux-hardware.org/?probe=605e3df140) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1638195805](https://linux-hardware.org/?probe=1638195805) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| Dell          | Latitude E6420              | Notebook    | [d630ae711a](https://linux-hardware.org/?probe=d630ae711a) | Dec 22, 2021 |
| ASRock        | AM1B-MH                     | Desktop     | [7f05b603cc](https://linux-hardware.org/?probe=7f05b603cc) | Dec 22, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d824937c84](https://linux-hardware.org/?probe=d824937c84) | Dec 22, 2021 |
| HP            | 87C3                        | Desktop     | [b9310a3287](https://linux-hardware.org/?probe=b9310a3287) | Dec 22, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [7d802b5274](https://linux-hardware.org/?probe=7d802b5274) | Dec 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c1f859121a](https://linux-hardware.org/?probe=c1f859121a) | Dec 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [464d10c41d](https://linux-hardware.org/?probe=464d10c41d) | Dec 22, 2021 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [fb84715d28](https://linux-hardware.org/?probe=fb84715d28) | Dec 22, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [88a422a8a4](https://linux-hardware.org/?probe=88a422a8a4) | Dec 22, 2021 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [5d2da923d8](https://linux-hardware.org/?probe=5d2da923d8) | Dec 22, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [4a626ea302](https://linux-hardware.org/?probe=4a626ea302) | Dec 22, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6c55617f07](https://linux-hardware.org/?probe=6c55617f07) | Dec 22, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [27a68b2bf6](https://linux-hardware.org/?probe=27a68b2bf6) | Dec 21, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [f5da6616cc](https://linux-hardware.org/?probe=f5da6616cc) | Dec 21, 2021 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [4ef2bfbf6d](https://linux-hardware.org/?probe=4ef2bfbf6d) | Dec 21, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [be6550186c](https://linux-hardware.org/?probe=be6550186c) | Dec 21, 2021 |
| EVOO          | EV-C-116-7                  | Notebook    | [76a0bc48de](https://linux-hardware.org/?probe=76a0bc48de) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [7f09e89b0f](https://linux-hardware.org/?probe=7f09e89b0f) | Dec 20, 2021 |
| HP            | G42                         | Notebook    | [9253a8caf5](https://linux-hardware.org/?probe=9253a8caf5) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [133dc63868](https://linux-hardware.org/?probe=133dc63868) | Dec 20, 2021 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [e1fb64a7cd](https://linux-hardware.org/?probe=e1fb64a7cd) | Dec 20, 2021 |
| Dell          | G7 7700                     | Notebook    | [4d9c5113e2](https://linux-hardware.org/?probe=4d9c5113e2) | Dec 20, 2021 |
| Google        | Akemi                       | Notebook    | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| ASUSTek       | P5K                         | Desktop     | [d890a56b60](https://linux-hardware.org/?probe=d890a56b60) | Dec 20, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e26f76134b](https://linux-hardware.org/?probe=e26f76134b) | Dec 20, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [86ed52c6c1](https://linux-hardware.org/?probe=86ed52c6c1) | Dec 20, 2021 |
| Dell          | G7 7700                     | Notebook    | [58e0b0cb22](https://linux-hardware.org/?probe=58e0b0cb22) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [f4e89f3e6c](https://linux-hardware.org/?probe=f4e89f3e6c) | Dec 19, 2021 |
| Gigabyte      | H87M-HD3                    | Desktop     | [906e50ad1d](https://linux-hardware.org/?probe=906e50ad1d) | Dec 19, 2021 |
| Google        | Delbin                      | Notebook    | [81442ef3da](https://linux-hardware.org/?probe=81442ef3da) | Dec 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b76cc36b22](https://linux-hardware.org/?probe=b76cc36b22) | Dec 19, 2021 |
| Packard Be... | IXTREME M5850               | Desktop     | [bdef4fbe1b](https://linux-hardware.org/?probe=bdef4fbe1b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [78ed3730cc](https://linux-hardware.org/?probe=78ed3730cc) | Dec 19, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [185e3c7fc3](https://linux-hardware.org/?probe=185e3c7fc3) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Colorful T... | BATTLE-AX B450M-G DELUXE... | Desktop     | [52614e9f8d](https://linux-hardware.org/?probe=52614e9f8d) | Dec 19, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [f692488a75](https://linux-hardware.org/?probe=f692488a75) | Dec 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [a270d3c7c5](https://linux-hardware.org/?probe=a270d3c7c5) | Dec 19, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [3468bb99d3](https://linux-hardware.org/?probe=3468bb99d3) | Dec 19, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [d3ab1ae873](https://linux-hardware.org/?probe=d3ab1ae873) | Dec 18, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [17fbd36a25](https://linux-hardware.org/?probe=17fbd36a25) | Dec 18, 2021 |
| System76      | Lemur Pro                   | Notebook    | [aebe0acb39](https://linux-hardware.org/?probe=aebe0acb39) | Dec 18, 2021 |
| MSI           | MEG X399 CREATION           | Desktop     | [0d985b6497](https://linux-hardware.org/?probe=0d985b6497) | Dec 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [ae21d724ad](https://linux-hardware.org/?probe=ae21d724ad) | Dec 18, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| Dell          | 0WG864                      | Desktop     | [b56e9d7403](https://linux-hardware.org/?probe=b56e9d7403) | Dec 18, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [0b0904b925](https://linux-hardware.org/?probe=0b0904b925) | Dec 18, 2021 |
| HP            | 8055                        | Desktop     | [860c13f3db](https://linux-hardware.org/?probe=860c13f3db) | Dec 18, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ebca5e6d33](https://linux-hardware.org/?probe=ebca5e6d33) | Dec 18, 2021 |
| HP            | 8055                        | Desktop     | [2397bb5a72](https://linux-hardware.org/?probe=2397bb5a72) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [60daadb8b0](https://linux-hardware.org/?probe=60daadb8b0) | Dec 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [adbc02c1c1](https://linux-hardware.org/?probe=adbc02c1c1) | Dec 18, 2021 |
| System76      | Thelio Major thelio-majo... | Desktop     | [209a930352](https://linux-hardware.org/?probe=209a930352) | Dec 18, 2021 |
| System76      | Thelio Major thelio-majo... | Desktop     | [611162ec47](https://linux-hardware.org/?probe=611162ec47) | Dec 17, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [5ae44ae2be](https://linux-hardware.org/?probe=5ae44ae2be) | Dec 17, 2021 |
| Samsung       | 950QCG                      | Convertible | [e489bca893](https://linux-hardware.org/?probe=e489bca893) | Dec 17, 2021 |
| Schenker      | XMG PRO (Late 2021)         | Notebook    | [f78514a539](https://linux-hardware.org/?probe=f78514a539) | Dec 17, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [45bee865bc](https://linux-hardware.org/?probe=45bee865bc) | Dec 17, 2021 |
| ASUSTek       | P5K                         | Desktop     | [34dacc17d4](https://linux-hardware.org/?probe=34dacc17d4) | Dec 17, 2021 |
| Pegatron      | Eureka3                     | Desktop     | [f932c4abaa](https://linux-hardware.org/?probe=f932c4abaa) | Dec 17, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| Acer          | V5-171                      | Notebook    | [2058672bcf](https://linux-hardware.org/?probe=2058672bcf) | Dec 17, 2021 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [953d781070](https://linux-hardware.org/?probe=953d781070) | Dec 17, 2021 |
| ASUSTek       | P5K                         | Desktop     | [3d5aa826f0](https://linux-hardware.org/?probe=3d5aa826f0) | Dec 17, 2021 |
| System76      | Oryx Pro                    | Notebook    | [bb7fdaaa22](https://linux-hardware.org/?probe=bb7fdaaa22) | Dec 17, 2021 |
| Dell          | 02YYK5 A00                  | Desktop     | [517971a926](https://linux-hardware.org/?probe=517971a926) | Dec 17, 2021 |
| System76      | Lemur Pro                   | Notebook    | [91634b0347](https://linux-hardware.org/?probe=91634b0347) | Dec 17, 2021 |
| Lenovo        | ThinkPad T460 20FMS0BX00    | Notebook    | [e056a8147a](https://linux-hardware.org/?probe=e056a8147a) | Dec 17, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [444737e990](https://linux-hardware.org/?probe=444737e990) | Dec 17, 2021 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [9a047a98b7](https://linux-hardware.org/?probe=9a047a98b7) | Dec 17, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [e9cbfcb4b8](https://linux-hardware.org/?probe=e9cbfcb4b8) | Dec 17, 2021 |
| System76      | Thelio Major thelio-majo... | Desktop     | [0c48275428](https://linux-hardware.org/?probe=0c48275428) | Dec 17, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [c21343c233](https://linux-hardware.org/?probe=c21343c233) | Dec 17, 2021 |
| HP            | 1998                        | Desktop     | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| ASRock        | Z87 Pro3                    | Desktop     | [8e1159b4c7](https://linux-hardware.org/?probe=8e1159b4c7) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [609baca194](https://linux-hardware.org/?probe=609baca194) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [35ec8b1dbb](https://linux-hardware.org/?probe=35ec8b1dbb) | Dec 16, 2021 |
| Lenovo        | 310B NOK                    | Mini pc     | [95465fc112](https://linux-hardware.org/?probe=95465fc112) | Dec 16, 2021 |
| Dell          | G5 5590                     | Notebook    | [b628b14dea](https://linux-hardware.org/?probe=b628b14dea) | Dec 16, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [8ba04481a3](https://linux-hardware.org/?probe=8ba04481a3) | Dec 16, 2021 |
| Lenovo        | ThinkPad X230 2324K84       | Notebook    | [fd2fbac9b7](https://linux-hardware.org/?probe=fd2fbac9b7) | Dec 16, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a42a1e13ab](https://linux-hardware.org/?probe=a42a1e13ab) | Dec 16, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [7ca51b2384](https://linux-hardware.org/?probe=7ca51b2384) | Dec 16, 2021 |
| Lenovo        | ThinkPad T490 20RYS07R00    | Notebook    | [0bdc5ce080](https://linux-hardware.org/?probe=0bdc5ce080) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [7cb6974555](https://linux-hardware.org/?probe=7cb6974555) | Dec 16, 2021 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [de9106e830](https://linux-hardware.org/?probe=de9106e830) | Dec 16, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f177028228](https://linux-hardware.org/?probe=f177028228) | Dec 16, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [addc8ac9d2](https://linux-hardware.org/?probe=addc8ac9d2) | Dec 16, 2021 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [02bc8cb963](https://linux-hardware.org/?probe=02bc8cb963) | Dec 16, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [c887764254](https://linux-hardware.org/?probe=c887764254) | Dec 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [66c985876e](https://linux-hardware.org/?probe=66c985876e) | Dec 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c636b137cf](https://linux-hardware.org/?probe=c636b137cf) | Dec 16, 2021 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [99dbb19723](https://linux-hardware.org/?probe=99dbb19723) | Dec 15, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| ASUSTek       | P5QP18L/T5-P5G41E           | Desktop     | [2707ae13b7](https://linux-hardware.org/?probe=2707ae13b7) | Dec 15, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | Notebook    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [da8c18883d](https://linux-hardware.org/?probe=da8c18883d) | Dec 15, 2021 |
| HP            | Presario CQ57               | Notebook    | [70fc50deb9](https://linux-hardware.org/?probe=70fc50deb9) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [86aff395eb](https://linux-hardware.org/?probe=86aff395eb) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6b3727344c](https://linux-hardware.org/?probe=6b3727344c) | Dec 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a25098712e](https://linux-hardware.org/?probe=a25098712e) | Dec 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS4U300    | Notebook    | [475a1f75a2](https://linux-hardware.org/?probe=475a1f75a2) | Dec 15, 2021 |
| ASUSTek       | P5K                         | Desktop     | [f64b97f5d7](https://linux-hardware.org/?probe=f64b97f5d7) | Dec 15, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c8c2b14c7e](https://linux-hardware.org/?probe=c8c2b14c7e) | Dec 15, 2021 |
| MSI           | B85M-E33                    | Desktop     | [40a459840d](https://linux-hardware.org/?probe=40a459840d) | Dec 15, 2021 |
| Toshiba       | Satellite C50t-B            | Notebook    | [9c7132e324](https://linux-hardware.org/?probe=9c7132e324) | Dec 15, 2021 |
| ASUSTek       | PN51-E1                     | Mini pc     | [23354fdfc7](https://linux-hardware.org/?probe=23354fdfc7) | Dec 15, 2021 |
| Dell          | G5 5505                     | Notebook    | [e4a5edb629](https://linux-hardware.org/?probe=e4a5edb629) | Dec 14, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [1771ceeb4e](https://linux-hardware.org/?probe=1771ceeb4e) | Dec 14, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [c0e72732c6](https://linux-hardware.org/?probe=c0e72732c6) | Dec 14, 2021 |
| HP            | 15                          | Notebook    | [70e648805f](https://linux-hardware.org/?probe=70e648805f) | Dec 14, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [397525b971](https://linux-hardware.org/?probe=397525b971) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [b93d5f0c9c](https://linux-hardware.org/?probe=b93d5f0c9c) | Dec 14, 2021 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [620a5a9fb4](https://linux-hardware.org/?probe=620a5a9fb4) | Dec 14, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [aa0253c74b](https://linux-hardware.org/?probe=aa0253c74b) | Dec 14, 2021 |
| Dell          | 0C2XKD A01                  | Desktop     | [7e8d066f7e](https://linux-hardware.org/?probe=7e8d066f7e) | Dec 14, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [40181c9f30](https://linux-hardware.org/?probe=40181c9f30) | Dec 14, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [6a878ff21a](https://linux-hardware.org/?probe=6a878ff21a) | Dec 14, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ea596baf39](https://linux-hardware.org/?probe=ea596baf39) | Dec 14, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [6248556dd7](https://linux-hardware.org/?probe=6248556dd7) | Dec 14, 2021 |
| Lenovo        | ThinkPad X230 23252CG       | Notebook    | [e2ed9e27c3](https://linux-hardware.org/?probe=e2ed9e27c3) | Dec 14, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [e66c15a464](https://linux-hardware.org/?probe=e66c15a464) | Dec 13, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [53588115a6](https://linux-hardware.org/?probe=53588115a6) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [dd9fb384ea](https://linux-hardware.org/?probe=dd9fb384ea) | Dec 13, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [ef791632cf](https://linux-hardware.org/?probe=ef791632cf) | Dec 13, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [4a0647be87](https://linux-hardware.org/?probe=4a0647be87) | Dec 13, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [32652b9e76](https://linux-hardware.org/?probe=32652b9e76) | Dec 13, 2021 |
| Dell          | Latitude E6430              | Notebook    | [aadf9bd175](https://linux-hardware.org/?probe=aadf9bd175) | Dec 13, 2021 |
| System76      | Thelio thelio-r1            | Desktop     | [4d84c05d5a](https://linux-hardware.org/?probe=4d84c05d5a) | Dec 12, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f3ee89047b](https://linux-hardware.org/?probe=f3ee89047b) | Dec 12, 2021 |
| Dell          | G7 7700                     | Notebook    | [5814c7f594](https://linux-hardware.org/?probe=5814c7f594) | Dec 12, 2021 |
| Dell          | Latitude E6530              | Notebook    | [6dad09df7e](https://linux-hardware.org/?probe=6dad09df7e) | Dec 12, 2021 |
| OBSIDIAN-P... | P65xHP                      | Notebook    | [73bbe1f2d5](https://linux-hardware.org/?probe=73bbe1f2d5) | Dec 12, 2021 |
| Medion        | Erazer X7841 MD99556        | Notebook    | [be7c56cb5c](https://linux-hardware.org/?probe=be7c56cb5c) | Dec 12, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ee80547bcb](https://linux-hardware.org/?probe=ee80547bcb) | Dec 12, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [d9958d2f46](https://linux-hardware.org/?probe=d9958d2f46) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [05cbcf49b8](https://linux-hardware.org/?probe=05cbcf49b8) | Dec 12, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [0892c20278](https://linux-hardware.org/?probe=0892c20278) | Dec 12, 2021 |
| HP            | 2AF7                        | Desktop     | [73b1748ae2](https://linux-hardware.org/?probe=73b1748ae2) | Dec 12, 2021 |
| HP            | 2AF7                        | Desktop     | [0f73a4284f](https://linux-hardware.org/?probe=0f73a4284f) | Dec 12, 2021 |
| Toshiba       | Satellite L55D-B            | Notebook    | [ba89ea8182](https://linux-hardware.org/?probe=ba89ea8182) | Dec 12, 2021 |
| Dell          | Precision M6700             | Notebook    | [dd5d0dc75d](https://linux-hardware.org/?probe=dd5d0dc75d) | Dec 12, 2021 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [8d658b6452](https://linux-hardware.org/?probe=8d658b6452) | Dec 11, 2021 |
| ASUSTek       | Zephyrus S GX701GWR_GX70... | Notebook    | [57c068b681](https://linux-hardware.org/?probe=57c068b681) | Dec 11, 2021 |
| Dell          | Latitude E6400              | Notebook    | [38c4f40bce](https://linux-hardware.org/?probe=38c4f40bce) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| ASUSTek       | F7Z                         | Notebook    | [ecfa43fe3b](https://linux-hardware.org/?probe=ecfa43fe3b) | Dec 11, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [ca20d472ea](https://linux-hardware.org/?probe=ca20d472ea) | Dec 11, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1576089d35](https://linux-hardware.org/?probe=1576089d35) | Dec 11, 2021 |
| Framework     | Laptop                      | Notebook    | [a48ace44e8](https://linux-hardware.org/?probe=a48ace44e8) | Dec 11, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [71aee46d69](https://linux-hardware.org/?probe=71aee46d69) | Dec 11, 2021 |
| ASUSTek       | ROG Rampage VI APEX         | Desktop     | [3800fb0041](https://linux-hardware.org/?probe=3800fb0041) | Dec 11, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [60cdd8ce45](https://linux-hardware.org/?probe=60cdd8ce45) | Dec 11, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [41a88a19cb](https://linux-hardware.org/?probe=41a88a19cb) | Dec 11, 2021 |
| ASUSTek       | G60JX                       | Notebook    | [fa6b821544](https://linux-hardware.org/?probe=fa6b821544) | Dec 11, 2021 |
| ASUSTek       | G60JX                       | Notebook    | [01ba59bc22](https://linux-hardware.org/?probe=01ba59bc22) | Dec 11, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [37cd7ae0c0](https://linux-hardware.org/?probe=37cd7ae0c0) | Dec 10, 2021 |
| Samsung       | 950QCG                      | Convertible | [8e3c69f82f](https://linux-hardware.org/?probe=8e3c69f82f) | Dec 10, 2021 |
| Dell          | Inspiron 5547               | Notebook    | [6b6f86a9f7](https://linux-hardware.org/?probe=6b6f86a9f7) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [fe3a7ec790](https://linux-hardware.org/?probe=fe3a7ec790) | Dec 10, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [da984826eb](https://linux-hardware.org/?probe=da984826eb) | Dec 10, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [7788772e68](https://linux-hardware.org/?probe=7788772e68) | Dec 10, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [eb51cb66cb](https://linux-hardware.org/?probe=eb51cb66cb) | Dec 10, 2021 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [40f91d4414](https://linux-hardware.org/?probe=40f91d4414) | Dec 10, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [01cddd0145](https://linux-hardware.org/?probe=01cddd0145) | Dec 10, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [27c454c72c](https://linux-hardware.org/?probe=27c454c72c) | Dec 10, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [e80b991fb4](https://linux-hardware.org/?probe=e80b991fb4) | Dec 10, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [90975ac5a8](https://linux-hardware.org/?probe=90975ac5a8) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [57a7604751](https://linux-hardware.org/?probe=57a7604751) | Dec 09, 2021 |
| Gigabyte      | H410M H                     | Desktop     | [a1b80c28f2](https://linux-hardware.org/?probe=a1b80c28f2) | Dec 09, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [c6f3827cb1](https://linux-hardware.org/?probe=c6f3827cb1) | Dec 09, 2021 |
| Razer         | Blade                       | Notebook    | [4fb43417d3](https://linux-hardware.org/?probe=4fb43417d3) | Dec 09, 2021 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [3d3d7f009e](https://linux-hardware.org/?probe=3d3d7f009e) | Dec 09, 2021 |
| HP            | ZBook 14u G5                | Notebook    | [21df45023e](https://linux-hardware.org/?probe=21df45023e) | Dec 09, 2021 |
| HP            | ZBook 14u G5                | Notebook    | [b01068d8cc](https://linux-hardware.org/?probe=b01068d8cc) | Dec 09, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [04ca55ea2b](https://linux-hardware.org/?probe=04ca55ea2b) | Dec 09, 2021 |
| System76      | Darter Pro                  | Notebook    | [324e5f7aa9](https://linux-hardware.org/?probe=324e5f7aa9) | Dec 09, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [df5e9d6c32](https://linux-hardware.org/?probe=df5e9d6c32) | Dec 09, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [a69abc7731](https://linux-hardware.org/?probe=a69abc7731) | Dec 09, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [9e41ceb42d](https://linux-hardware.org/?probe=9e41ceb42d) | Dec 09, 2021 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [b87ba06410](https://linux-hardware.org/?probe=b87ba06410) | Dec 09, 2021 |
| HP            | Laptop 15g-dx0xxx           | Notebook    | [1bdf2932b8](https://linux-hardware.org/?probe=1bdf2932b8) | Dec 09, 2021 |
| HP            | 3397                        | Desktop     | [9c1590635c](https://linux-hardware.org/?probe=9c1590635c) | Dec 09, 2021 |
| MSI           | H81I                        | Desktop     | [12a48f7014](https://linux-hardware.org/?probe=12a48f7014) | Dec 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [631165b7a9](https://linux-hardware.org/?probe=631165b7a9) | Dec 08, 2021 |
| System76      | Lemur Pro                   | Notebook    | [6e54a15cf2](https://linux-hardware.org/?probe=6e54a15cf2) | Dec 08, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [26bd22464a](https://linux-hardware.org/?probe=26bd22464a) | Dec 08, 2021 |
| ASUSTek       | ET2321I                     | Desktop     | [a464e64057](https://linux-hardware.org/?probe=a464e64057) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [8a99ae8fb7](https://linux-hardware.org/?probe=8a99ae8fb7) | Dec 08, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [6e7dbbfd7a](https://linux-hardware.org/?probe=6e7dbbfd7a) | Dec 08, 2021 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [66be8ec3da](https://linux-hardware.org/?probe=66be8ec3da) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [406f1424c9](https://linux-hardware.org/?probe=406f1424c9) | Dec 08, 2021 |
| Exo           | C14C                        | Notebook    | [2e0765b245](https://linux-hardware.org/?probe=2e0765b245) | Dec 08, 2021 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [765268167e](https://linux-hardware.org/?probe=765268167e) | Dec 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d64e657861](https://linux-hardware.org/?probe=d64e657861) | Dec 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8ee1603edc](https://linux-hardware.org/?probe=8ee1603edc) | Dec 07, 2021 |
| HP            | Laptop 15g-dx0xxx           | Notebook    | [646587b02b](https://linux-hardware.org/?probe=646587b02b) | Dec 07, 2021 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [183160dea8](https://linux-hardware.org/?probe=183160dea8) | Dec 07, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [460575871c](https://linux-hardware.org/?probe=460575871c) | Dec 07, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [8b52558b24](https://linux-hardware.org/?probe=8b52558b24) | Dec 07, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [b82efe27ad](https://linux-hardware.org/?probe=b82efe27ad) | Dec 07, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [d4b308c0c8](https://linux-hardware.org/?probe=d4b308c0c8) | Dec 07, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [c5d73b2d3a](https://linux-hardware.org/?probe=c5d73b2d3a) | Dec 07, 2021 |
| System76      | Gazelle                     | Notebook    | [7c14f115ad](https://linux-hardware.org/?probe=7c14f115ad) | Dec 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [6c0b436855](https://linux-hardware.org/?probe=6c0b436855) | Dec 07, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [2425031333](https://linux-hardware.org/?probe=2425031333) | Dec 07, 2021 |
| Exo           | C14C                        | Notebook    | [1d4221ab9e](https://linux-hardware.org/?probe=1d4221ab9e) | Dec 06, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [cbe9c1fb38](https://linux-hardware.org/?probe=cbe9c1fb38) | Dec 06, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [b44117a400](https://linux-hardware.org/?probe=b44117a400) | Dec 06, 2021 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [b65be23e52](https://linux-hardware.org/?probe=b65be23e52) | Dec 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [3c678945c5](https://linux-hardware.org/?probe=3c678945c5) | Dec 06, 2021 |
| HP            | 1497                        | Desktop     | [520115904e](https://linux-hardware.org/?probe=520115904e) | Dec 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [7803fb89df](https://linux-hardware.org/?probe=7803fb89df) | Dec 06, 2021 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4e6e60b6b1](https://linux-hardware.org/?probe=4e6e60b6b1) | Dec 06, 2021 |
| Dell          | Precision 7710              | Notebook    | [c41229e574](https://linux-hardware.org/?probe=c41229e574) | Dec 05, 2021 |
| INET          | Z12B                        | Mini pc     | [a18fff612e](https://linux-hardware.org/?probe=a18fff612e) | Dec 05, 2021 |
| Sony          | SVP1121M1EBI                | Notebook    | [65e9211e33](https://linux-hardware.org/?probe=65e9211e33) | Dec 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c41080ef38](https://linux-hardware.org/?probe=c41080ef38) | Dec 05, 2021 |
| Toshiba       | Satellite L775D             | Notebook    | [8d5d6d2305](https://linux-hardware.org/?probe=8d5d6d2305) | Dec 05, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [3e6b2c12f8](https://linux-hardware.org/?probe=3e6b2c12f8) | Dec 05, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [0d522a3c93](https://linux-hardware.org/?probe=0d522a3c93) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [dd578dae69](https://linux-hardware.org/?probe=dd578dae69) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [d15350584d](https://linux-hardware.org/?probe=d15350584d) | Dec 05, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [81a9718a11](https://linux-hardware.org/?probe=81a9718a11) | Dec 05, 2021 |
| Gateway       | P-78                        | Notebook    | [1cfe858e35](https://linux-hardware.org/?probe=1cfe858e35) | Dec 05, 2021 |
| MSI           | Z97M GAMING                 | Desktop     | [f9bd8b115b](https://linux-hardware.org/?probe=f9bd8b115b) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [9c595c56b7](https://linux-hardware.org/?probe=9c595c56b7) | Dec 05, 2021 |
| Positivo      | NB50TH                      | Notebook    | [705bae2d39](https://linux-hardware.org/?probe=705bae2d39) | Dec 04, 2021 |
| Sony          | SVF1531GSFB                 | Notebook    | [fb251b93e9](https://linux-hardware.org/?probe=fb251b93e9) | Dec 04, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [106e49c95a](https://linux-hardware.org/?probe=106e49c95a) | Dec 04, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [e16326de62](https://linux-hardware.org/?probe=e16326de62) | Dec 04, 2021 |
| HUAWEI        | VLT-WX0                     | Notebook    | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [2b7412b23b](https://linux-hardware.org/?probe=2b7412b23b) | Dec 04, 2021 |
| HP            | 8433 11                     | Desktop     | [cfff897aa6](https://linux-hardware.org/?probe=cfff897aa6) | Dec 04, 2021 |
| Dell          | G5 5505                     | Notebook    | [20371a8d9d](https://linux-hardware.org/?probe=20371a8d9d) | Dec 04, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [940525ab25](https://linux-hardware.org/?probe=940525ab25) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| Intel         | B75                         | Desktop     | [42982cfe94](https://linux-hardware.org/?probe=42982cfe94) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [235b18ea4b](https://linux-hardware.org/?probe=235b18ea4b) | Dec 03, 2021 |
| Dell          | G5 5505                     | Notebook    | [008e8e2b7b](https://linux-hardware.org/?probe=008e8e2b7b) | Dec 03, 2021 |
| Lenovo        | ThinkPad T500 2089R97       | Notebook    | [6a2cd8a43a](https://linux-hardware.org/?probe=6a2cd8a43a) | Dec 03, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [26541caf1e](https://linux-hardware.org/?probe=26541caf1e) | Dec 03, 2021 |
| Intel         | B75                         | Desktop     | [c76a831e54](https://linux-hardware.org/?probe=c76a831e54) | Dec 03, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [982df1ad36](https://linux-hardware.org/?probe=982df1ad36) | Dec 03, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkPad T500 2089R97       | Notebook    | [690a59fee2](https://linux-hardware.org/?probe=690a59fee2) | Dec 03, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e2e7015852](https://linux-hardware.org/?probe=e2e7015852) | Dec 03, 2021 |
| PC Special... | NH5x_7xDCx_DDx              | Notebook    | [c7f6dbb8de](https://linux-hardware.org/?probe=c7f6dbb8de) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [9189181f51](https://linux-hardware.org/?probe=9189181f51) | Dec 03, 2021 |
| Lenovo        | 30D0 NOK                    | Desktop     | [c6be2b51f3](https://linux-hardware.org/?probe=c6be2b51f3) | Dec 03, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [cfc90f55d7](https://linux-hardware.org/?probe=cfc90f55d7) | Dec 03, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [4012763f85](https://linux-hardware.org/?probe=4012763f85) | Dec 03, 2021 |
| Dell          | 0TP412                      | Desktop     | [f446f1af53](https://linux-hardware.org/?probe=f446f1af53) | Dec 02, 2021 |
| Gigabyte      | H87M-HD3                    | Desktop     | [4624f9164d](https://linux-hardware.org/?probe=4624f9164d) | Dec 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [4d1d806bf8](https://linux-hardware.org/?probe=4d1d806bf8) | Dec 02, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [6491dbee12](https://linux-hardware.org/?probe=6491dbee12) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [97303e7ffa](https://linux-hardware.org/?probe=97303e7ffa) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8eaf4b72e7](https://linux-hardware.org/?probe=8eaf4b72e7) | Dec 02, 2021 |
| ASRock        | H170M-ITX/DL                | Desktop     | [a1583e74ac](https://linux-hardware.org/?probe=a1583e74ac) | Dec 02, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [4201144caa](https://linux-hardware.org/?probe=4201144caa) | Dec 02, 2021 |
| Apple         | MacBookPro4,1               | Notebook    | [6d4816f322](https://linux-hardware.org/?probe=6d4816f322) | Dec 02, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [a22a6ea09a](https://linux-hardware.org/?probe=a22a6ea09a) | Dec 02, 2021 |
| Apple         | MacBookPro4,1               | Notebook    | [aa8c361e26](https://linux-hardware.org/?probe=aa8c361e26) | Dec 02, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6a8021e535](https://linux-hardware.org/?probe=6a8021e535) | Dec 02, 2021 |
| GPU Compan... | GWTN156-1                   | Notebook    | [0f7052d7f4](https://linux-hardware.org/?probe=0f7052d7f4) | Dec 01, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [4b1553b16a](https://linux-hardware.org/?probe=4b1553b16a) | Dec 01, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4dce6fbb79](https://linux-hardware.org/?probe=4dce6fbb79) | Dec 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [89b56db565](https://linux-hardware.org/?probe=89b56db565) | Dec 01, 2021 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [316684da39](https://linux-hardware.org/?probe=316684da39) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [0a1de49219](https://linux-hardware.org/?probe=0a1de49219) | Dec 01, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [a327249b33](https://linux-hardware.org/?probe=a327249b33) | Dec 01, 2021 |
| ASUSTek       | X99-PRO                     | Desktop     | [63ca6eaff3](https://linux-hardware.org/?probe=63ca6eaff3) | Dec 01, 2021 |
| ASUSTek       | GL553VW                     | Notebook    | [4ad555a692](https://linux-hardware.org/?probe=4ad555a692) | Dec 01, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Gigabyte      | Z270X-Gaming 9              | Desktop     | [cfa6af3bdc](https://linux-hardware.org/?probe=cfa6af3bdc) | Nov 30, 2021 |
| Framework     | Laptop                      | Notebook    | [4163fab746](https://linux-hardware.org/?probe=4163fab746) | Nov 30, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [363ac35eac](https://linux-hardware.org/?probe=363ac35eac) | Nov 30, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [64005f7018](https://linux-hardware.org/?probe=64005f7018) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [01ce77a927](https://linux-hardware.org/?probe=01ce77a927) | Nov 30, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Toshiba       | Satellite P50-C             | Notebook    | [6f78408a96](https://linux-hardware.org/?probe=6f78408a96) | Nov 30, 2021 |
| Toshiba       | Satellite P50-C             | Notebook    | [80a1234b6a](https://linux-hardware.org/?probe=80a1234b6a) | Nov 30, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [63228e3c6f](https://linux-hardware.org/?probe=63228e3c6f) | Nov 30, 2021 |
| Dell          | Latitude E7470              | Notebook    | [ff9005d79f](https://linux-hardware.org/?probe=ff9005d79f) | Nov 30, 2021 |
| Dell          | Latitude E7470              | Notebook    | [8159c765ab](https://linux-hardware.org/?probe=8159c765ab) | Nov 30, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [6c194a1d68](https://linux-hardware.org/?probe=6c194a1d68) | Nov 29, 2021 |
| Dell          | 03VTJ7 A01                  | All in one  | [fcd0ef9f0e](https://linux-hardware.org/?probe=fcd0ef9f0e) | Nov 29, 2021 |
| Dell          | 03VTJ7 A01                  | All in one  | [5b0f7ffe69](https://linux-hardware.org/?probe=5b0f7ffe69) | Nov 29, 2021 |
| Acer          | Aspire X1420G               | Desktop     | [0796ab5648](https://linux-hardware.org/?probe=0796ab5648) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [850666540b](https://linux-hardware.org/?probe=850666540b) | Nov 29, 2021 |
| Acer          | Aspire X1420G               | Desktop     | [8bc9624451](https://linux-hardware.org/?probe=8bc9624451) | Nov 29, 2021 |
| Acer          | V5-171                      | Notebook    | [63a4cced51](https://linux-hardware.org/?probe=63a4cced51) | Nov 29, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c4883be3f0](https://linux-hardware.org/?probe=c4883be3f0) | Nov 29, 2021 |
| MSI           | 3664h                       | Desktop     | [c4bc6c8049](https://linux-hardware.org/?probe=c4bc6c8049) | Nov 29, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [ad08779e3f](https://linux-hardware.org/?probe=ad08779e3f) | Nov 29, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [a380d2a0c8](https://linux-hardware.org/?probe=a380d2a0c8) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Sony          | VPCZ12V9R                   | Notebook    | [19d2baf5bf](https://linux-hardware.org/?probe=19d2baf5bf) | Nov 28, 2021 |
| MSI           | B75A-G41                    | Desktop     | [ebedf5b920](https://linux-hardware.org/?probe=ebedf5b920) | Nov 28, 2021 |
| Lenovo        | Y40-70 20347                | Notebook    | [b1f12baf08](https://linux-hardware.org/?probe=b1f12baf08) | Nov 28, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [febc9d2faa](https://linux-hardware.org/?probe=febc9d2faa) | Nov 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [97d18ac1df](https://linux-hardware.org/?probe=97d18ac1df) | Nov 28, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a9a59eb7cb](https://linux-hardware.org/?probe=a9a59eb7cb) | Nov 28, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [af5d6c67cf](https://linux-hardware.org/?probe=af5d6c67cf) | Nov 28, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [3c66514b27](https://linux-hardware.org/?probe=3c66514b27) | Nov 28, 2021 |
| System76      | Thelio thelio-r2            | Desktop     | [b5517ad87d](https://linux-hardware.org/?probe=b5517ad87d) | Nov 28, 2021 |
| Microsoft     | Surface Laptop              | Tablet      | [acc1031944](https://linux-hardware.org/?probe=acc1031944) | Nov 28, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [4c0321b683](https://linux-hardware.org/?probe=4c0321b683) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [11e8a78550](https://linux-hardware.org/?probe=11e8a78550) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [13b8dd7109](https://linux-hardware.org/?probe=13b8dd7109) | Nov 28, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [9993e59d59](https://linux-hardware.org/?probe=9993e59d59) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [999b38ba1f](https://linux-hardware.org/?probe=999b38ba1f) | Nov 28, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [7ea99f6af0](https://linux-hardware.org/?probe=7ea99f6af0) | Nov 27, 2021 |
| GPU Compan... | GWTN156-1                   | Notebook    | [450b474fd7](https://linux-hardware.org/?probe=450b474fd7) | Nov 27, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [25c2d882e7](https://linux-hardware.org/?probe=25c2d882e7) | Nov 27, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [092ae35663](https://linux-hardware.org/?probe=092ae35663) | Nov 27, 2021 |
| Lenovo        | ThinkPad E520 1143AD5       | Notebook    | [c76e2c7b06](https://linux-hardware.org/?probe=c76e2c7b06) | Nov 27, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [3ca0fbac27](https://linux-hardware.org/?probe=3ca0fbac27) | Nov 27, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b44c88e4f4](https://linux-hardware.org/?probe=b44c88e4f4) | Nov 27, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [e2b7b798a8](https://linux-hardware.org/?probe=e2b7b798a8) | Nov 27, 2021 |
| Toshiba       | Satellite L775D             | Notebook    | [4625301b6c](https://linux-hardware.org/?probe=4625301b6c) | Nov 27, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [49c2126e36](https://linux-hardware.org/?probe=49c2126e36) | Nov 26, 2021 |
| Shuttle       | FG41 V20                    | Desktop     | [1ec48380db](https://linux-hardware.org/?probe=1ec48380db) | Nov 26, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | All in one  | [9333b9c923](https://linux-hardware.org/?probe=9333b9c923) | Nov 26, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [4e9a979bca](https://linux-hardware.org/?probe=4e9a979bca) | Nov 26, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [e69007b550](https://linux-hardware.org/?probe=e69007b550) | Nov 26, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [f4106ba538](https://linux-hardware.org/?probe=f4106ba538) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| Dell          | G3 3779                     | Notebook    | [cd6dace549](https://linux-hardware.org/?probe=cd6dace549) | Nov 26, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [65d49ae483](https://linux-hardware.org/?probe=65d49ae483) | Nov 26, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [2e9f47c5fb](https://linux-hardware.org/?probe=2e9f47c5fb) | Nov 26, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3861d9baa5](https://linux-hardware.org/?probe=3861d9baa5) | Nov 26, 2021 |
| MSI           | GE62VR 6RF                  | Notebook    | [48db051c10](https://linux-hardware.org/?probe=48db051c10) | Nov 26, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | All in one  | [50a0baffd0](https://linux-hardware.org/?probe=50a0baffd0) | Nov 26, 2021 |
| ASUSTek       | Unknown                     | Notebook    | [1627a50b96](https://linux-hardware.org/?probe=1627a50b96) | Nov 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [54a9e811f9](https://linux-hardware.org/?probe=54a9e811f9) | Nov 25, 2021 |
| ENTITY        | ENTYA11Q120                 | Notebook    | [38796d7825](https://linux-hardware.org/?probe=38796d7825) | Nov 25, 2021 |
| System76      | Darter Pro                  | Notebook    | [0f577e388f](https://linux-hardware.org/?probe=0f577e388f) | Nov 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89df3f3fb5](https://linux-hardware.org/?probe=89df3f3fb5) | Nov 25, 2021 |
| MSI           | GE66 Raider 11UG            | Notebook    | [f8c0fc5008](https://linux-hardware.org/?probe=f8c0fc5008) | Nov 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [ade3c9d36c](https://linux-hardware.org/?probe=ade3c9d36c) | Nov 25, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [df371e2ae6](https://linux-hardware.org/?probe=df371e2ae6) | Nov 25, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [edeb251a5b](https://linux-hardware.org/?probe=edeb251a5b) | Nov 25, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [f35b231963](https://linux-hardware.org/?probe=f35b231963) | Nov 25, 2021 |
| MSI           | 990FXA GAMING               | Desktop     | [f6d7e7c0a0](https://linux-hardware.org/?probe=f6d7e7c0a0) | Nov 25, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [d8d0d4f7e5](https://linux-hardware.org/?probe=d8d0d4f7e5) | Nov 25, 2021 |
| HP            | ProBook 6460b               | Notebook    | [a072a6246d](https://linux-hardware.org/?probe=a072a6246d) | Nov 25, 2021 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c73ede479](https://linux-hardware.org/?probe=5c73ede479) | Nov 25, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [811cd206bf](https://linux-hardware.org/?probe=811cd206bf) | Nov 25, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0d0596e9ea](https://linux-hardware.org/?probe=0d0596e9ea) | Nov 25, 2021 |
| ASUSTek       | K55A                        | Notebook    | [fe6037c10c](https://linux-hardware.org/?probe=fe6037c10c) | Nov 25, 2021 |
| LG Electro... | S425-L.BC24P1               | Notebook    | [6d6d4fca9b](https://linux-hardware.org/?probe=6d6d4fca9b) | Nov 24, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [34a6ad4baa](https://linux-hardware.org/?probe=34a6ad4baa) | Nov 24, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [7cb7c080e6](https://linux-hardware.org/?probe=7cb7c080e6) | Nov 24, 2021 |
| Dell          | 0G254H A00                  | Desktop     | [2e6c744703](https://linux-hardware.org/?probe=2e6c744703) | Nov 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| Dell          | 02TPVG A06                  | Desktop     | [35be5482f1](https://linux-hardware.org/?probe=35be5482f1) | Nov 24, 2021 |
| Pegatron      | 2ACB                        | Desktop     | [43892a4795](https://linux-hardware.org/?probe=43892a4795) | Nov 24, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [dd5515e9c7](https://linux-hardware.org/?probe=dd5515e9c7) | Nov 24, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ab60997b9e](https://linux-hardware.org/?probe=ab60997b9e) | Nov 24, 2021 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [496b525711](https://linux-hardware.org/?probe=496b525711) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [35779ad04b](https://linux-hardware.org/?probe=35779ad04b) | Nov 24, 2021 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [839f56bd09](https://linux-hardware.org/?probe=839f56bd09) | Nov 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d3b80da0a1](https://linux-hardware.org/?probe=d3b80da0a1) | Nov 24, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [6b926197c9](https://linux-hardware.org/?probe=6b926197c9) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [670534d1c1](https://linux-hardware.org/?probe=670534d1c1) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c14d4d6ad](https://linux-hardware.org/?probe=2c14d4d6ad) | Nov 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2d1b362a70](https://linux-hardware.org/?probe=2d1b362a70) | Nov 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [28205ed54f](https://linux-hardware.org/?probe=28205ed54f) | Nov 23, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| ASUSTek       | GL503VD                     | Notebook    | [f6c3e5dc79](https://linux-hardware.org/?probe=f6c3e5dc79) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| Google        | Akemi                       | Notebook    | [ee405bcedc](https://linux-hardware.org/?probe=ee405bcedc) | Nov 23, 2021 |
| Samsung       | Q430/Q530                   | Notebook    | [a8184ab96c](https://linux-hardware.org/?probe=a8184ab96c) | Nov 22, 2021 |
| HP            | 1495                        | Desktop     | [6be5bb9489](https://linux-hardware.org/?probe=6be5bb9489) | Nov 22, 2021 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [b874076152](https://linux-hardware.org/?probe=b874076152) | Nov 22, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [6e2d7fbaed](https://linux-hardware.org/?probe=6e2d7fbaed) | Nov 22, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [6a0bda5a7d](https://linux-hardware.org/?probe=6a0bda5a7d) | Nov 22, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 2111      | 28.24%  |
| Pop!_OS 21.04 | 1796      | 24.03%  |
| Pop!_OS 20.10 | 1648      | 22.05%  |
| Pop!_OS 21.10 | 1102      | 14.74%  |
| Pop!_OS 22.04 | 743       | 9.94%   |
| Pop!_OS 19.10 | 47        | 0.63%   |
| Pop!_OS 19.04 | 12        | 0.16%   |
| Pop!_OS 18.04 | 11        | 0.15%   |
| Pop!_OS 18.10 | 5         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 7057      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 837       | 10.56%  |
| 5.8.0-7630-generic       | 741       | 9.35%   |
| 5.4.0-7634-generic       | 666       | 8.4%    |
| 5.13.0-7614-generic      | 496       | 6.26%   |
| 5.8.0-7642-generic       | 480       | 6.06%   |
| 5.4.0-7642-generic       | 465       | 5.87%   |
| 5.11.0-7614-generic      | 437       | 5.51%   |
| 5.17.5-76051705-generic  | 429       | 5.41%   |
| 5.13.0-7620-generic      | 411       | 5.19%   |
| 5.15.15-76051515-generic | 280       | 3.53%   |
| 5.16.11-76051611-generic | 262       | 3.31%   |
| 5.15.5-76051505-generic  | 234       | 2.95%   |
| 5.11.0-7612-generic      | 226       | 2.85%   |
| 5.8.0-7625-generic       | 195       | 2.46%   |
| 5.11.0-7633-generic      | 180       | 2.27%   |
| 5.17.15-76051715-generic | 178       | 2.25%   |
| 5.16.19-76051619-generic | 173       | 2.18%   |
| 5.15.8-76051508-generic  | 171       | 2.16%   |
| 5.16.15-76051615-generic | 150       | 1.89%   |
| 5.4.0-7626-generic       | 144       | 1.82%   |
| 5.15.11-76051511-generic | 111       | 1.4%    |
| 5.15.23-76051523-generic | 90        | 1.14%   |
| 5.4.0-7625-generic       | 74        | 0.93%   |
| 5.4.0-7629-generic       | 62        | 0.78%   |
| 5.18.10-76051810-generic | 58        | 0.73%   |
| 5.3.0-7625-generic       | 16        | 0.2%    |
| 5.3.0-7629-generic       | 10        | 0.13%   |
| 5.3.0-7648-generic       | 9         | 0.11%   |
| 5.11.0-051100-generic    | 9         | 0.11%   |
| 5.4.0-7624-generic       | 6         | 0.08%   |
| 5.13.0-1011-raspi        | 6         | 0.08%   |
| 5.3.0-22-generic         | 5         | 0.06%   |
| 5.15.0-76051500-generic  | 5         | 0.06%   |
| 5.8.5-xanmod1            | 4         | 0.05%   |
| 5.8.5-050805-generic     | 4         | 0.05%   |
| 5.8.12-xanmod1           | 4         | 0.05%   |
| 5.7.8-050708-generic     | 4         | 0.05%   |
| 5.7.1-050701-generic     | 4         | 0.05%   |
| 5.7.0-050700-generic     | 4         | 0.05%   |
| 5.6.16-xanmod1           | 4         | 0.05%   |
| 5.3.0-7642-generic       | 4         | 0.05%   |
| 5.3.0-20-generic         | 4         | 0.05%   |
| 5.13.0-051300-generic    | 4         | 0.05%   |
| 5.8.9-050809-generic     | 3         | 0.04%   |
| 5.8.6-050806-generic     | 3         | 0.04%   |
| 5.15.7-xanmod1           | 3         | 0.04%   |
| 5.15.2-76051502-generic  | 3         | 0.04%   |
| 5.13.13-xanmod1          | 3         | 0.04%   |
| 5.13.0-7619-generic      | 3         | 0.04%   |
| 5.12.14-xanmod1          | 3         | 0.04%   |
| 5.10.23-xanmod1          | 3         | 0.04%   |
| 5.0.0-31-generic         | 3         | 0.04%   |
| 4.18.0-16-generic        | 3         | 0.04%   |
| 5.9.12-xanmod1           | 2         | 0.03%   |
| 5.8.6-xanmod1            | 2         | 0.03%   |
| 5.8.18-050818-generic    | 2         | 0.03%   |
| 5.8.17-050817-generic    | 2         | 0.03%   |
| 5.8.12-050812-generic    | 2         | 0.03%   |
| 5.8.11-050811-generic    | 2         | 0.03%   |
| 5.8.1-050801-generic     | 2         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1624      | 21.04%  |
| 5.4.0   | 1370      | 17.75%  |
| 5.8.0   | 1356      | 17.56%  |
| 5.13.0  | 909       | 11.77%  |
| 5.17.5  | 432       | 5.6%    |
| 5.15.15 | 281       | 3.64%   |
| 5.16.11 | 262       | 3.39%   |
| 5.15.5  | 234       | 3.03%   |
| 5.17.15 | 178       | 2.31%   |
| 5.16.19 | 173       | 2.24%   |
| 5.15.8  | 171       | 2.22%   |
| 5.16.15 | 150       | 1.94%   |
| 5.15.11 | 111       | 1.44%   |
| 5.15.23 | 90        | 1.17%   |
| 5.18.10 | 58        | 0.75%   |
| 5.3.0   | 51        | 0.66%   |
| 5.0.0   | 12        | 0.16%   |
| 5.8.5   | 8         | 0.1%    |
| 5.7.0   | 8         | 0.1%    |
| 5.8.12  | 7         | 0.09%   |
| 4.18.0  | 7         | 0.09%   |
| 5.15.0  | 6         | 0.08%   |
| 5.13.12 | 6         | 0.08%   |
| 5.10.0  | 6         | 0.08%   |
| 5.8.6   | 5         | 0.06%   |
| 5.6.16  | 5         | 0.06%   |
| 5.7.8   | 4         | 0.05%   |
| 5.7.1   | 4         | 0.05%   |
| 5.14.0  | 4         | 0.05%   |
| 5.12.14 | 4         | 0.05%   |
| 5.9.1   | 3         | 0.04%   |
| 5.8.9   | 3         | 0.04%   |
| 5.8.11  | 3         | 0.04%   |
| 5.7.15  | 3         | 0.04%   |
| 5.7.12  | 3         | 0.04%   |
| 5.15.7  | 3         | 0.04%   |
| 5.15.2  | 3         | 0.04%   |
| 5.13.13 | 3         | 0.04%   |
| 5.12.0  | 3         | 0.04%   |
| 5.10.23 | 3         | 0.04%   |
| 4.15.0  | 3         | 0.04%   |
| 5.9.12  | 2         | 0.03%   |
| 5.8.18  | 2         | 0.03%   |
| 5.8.17  | 2         | 0.03%   |
| 5.8.16  | 2         | 0.03%   |
| 5.8.10  | 2         | 0.03%   |
| 5.8.1   | 2         | 0.03%   |
| 5.7.16  | 2         | 0.03%   |
| 5.6.7   | 2         | 0.03%   |
| 5.6.0   | 2         | 0.03%   |
| 5.18.11 | 2         | 0.03%   |
| 5.18.0  | 2         | 0.03%   |
| 5.17.7  | 2         | 0.03%   |
| 5.17.2  | 2         | 0.03%   |
| 5.17.1  | 2         | 0.03%   |
| 5.17.0  | 2         | 0.03%   |
| 5.16.0  | 2         | 0.03%   |
| 5.15.4  | 2         | 0.03%   |
| 5.15.24 | 2         | 0.03%   |
| 5.15.22 | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1633      | 21.32%  |
| 5.8     | 1393      | 18.19%  |
| 5.4     | 1373      | 17.93%  |
| 5.13    | 928       | 12.12%  |
| 5.15    | 888       | 11.59%  |
| 5.17    | 610       | 7.96%   |
| 5.16    | 574       | 7.49%   |
| 5.18    | 64        | 0.84%   |
| 5.3     | 51        | 0.67%   |
| 5.10    | 28        | 0.37%   |
| 5.7     | 27        | 0.35%   |
| 5.12    | 18        | 0.24%   |
| 5.14    | 16        | 0.21%   |
| 5.9     | 15        | 0.2%    |
| 5.6     | 15        | 0.2%    |
| 5.0     | 12        | 0.16%   |
| 4.18    | 8         | 0.1%    |
| 4.15    | 3         | 0.04%   |
| 5.19    | 1         | 0.01%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7042      | 99.79%  |
| aarch64 | 15        | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 6829      | 96.16%  |
| KDE             | 59        | 0.83%   |
| KDE5            | 52        | 0.73%   |
| Unknown         | 47        | 0.66%   |
| X-Cinnamon      | 29        | 0.41%   |
| MATE            | 19        | 0.27%   |
| XFCE            | 16        | 0.23%   |
| GNOME Flashback | 13        | 0.18%   |
| Cinnamon        | 12        | 0.17%   |
| LXQt            | 9         | 0.13%   |
| Budgie          | 6         | 0.08%   |
| Unity           | 4         | 0.06%   |
| i3              | 3         | 0.04%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |
| awesome         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6891      | 97.22%  |
| Wayland | 168       | 2.37%   |
| Unknown | 18        | 0.25%   |
| Tty     | 11        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5745      | 80.81%  |
| GDM     | 1191      | 16.75%  |
| GDM3    | 152       | 2.14%   |
| SDDM    | 11        | 0.15%   |
| TDM     | 8         | 0.11%   |
| LightDM | 2         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4012      | 56.48%  |
| en_GB   | 535       | 7.53%   |
| pt_BR   | 531       | 7.48%   |
| de_DE   | 338       | 4.76%   |
| C       | 214       | 3.01%   |
| en_AU   | 187       | 2.63%   |
| en_CA   | 165       | 2.32%   |
| fr_FR   | 149       | 2.1%    |
| es_ES   | 121       | 1.7%    |
| it_IT   | 112       | 1.58%   |
| ru_RU   | 98        | 1.38%   |
| pl_PL   | 66        | 0.93%   |
| Unknown | 63        | 0.89%   |
| sv_SE   | 52        | 0.73%   |
| pt_PT   | 49        | 0.69%   |
| nl_NL   | 45        | 0.63%   |
| en_IN   | 28        | 0.39%   |
| fi_FI   | 21        | 0.3%    |
| en_ZA   | 21        | 0.3%    |
| es_MX   | 18        | 0.25%   |
| nb_NO   | 17        | 0.24%   |
| fr_CA   | 17        | 0.24%   |
| es_AR   | 16        | 0.23%   |
| en_NZ   | 15        | 0.21%   |
| tr_TR   | 14        | 0.2%    |
| en_DK   | 14        | 0.2%    |
| hr_HR   | 12        | 0.17%   |
| sk_SK   | 11        | 0.15%   |
| nl_BE   | 11        | 0.15%   |
| hu_HU   | 11        | 0.15%   |
| es_CL   | 10        | 0.14%   |
| da_DK   | 10        | 0.14%   |
| cs_CZ   | 10        | 0.14%   |
| zh_TW   | 8         | 0.11%   |
| ro_RO   | 8         | 0.11%   |
| zh_CN   | 7         | 0.1%    |
| ja_JP   | 7         | 0.1%    |
| de_AT   | 7         | 0.1%    |
| en_IL   | 6         | 0.08%   |
| es_CO   | 5         | 0.07%   |
| de_CH   | 5         | 0.07%   |
| uk_UA   | 3         | 0.04%   |
| fr_CH   | 3         | 0.04%   |
| fr_BE   | 3         | 0.04%   |
| es_UY   | 3         | 0.04%   |
| es_PE   | 3         | 0.04%   |
| en_SG   | 3         | 0.04%   |
| en_IE   | 3         | 0.04%   |
| el_GR   | 3         | 0.04%   |
| ca_ES   | 3         | 0.04%   |
| ru_UA   | 2         | 0.03%   |
| lv_LV   | 2         | 0.03%   |
| ko_KR   | 2         | 0.03%   |
| es_CR   | 2         | 0.03%   |
| bg_BG   | 2         | 0.03%   |
| vi_VN   | 1         | 0.01%   |
| szl_PL  | 1         | 0.01%   |
| sv_FI   | 1         | 0.01%   |
| lt_LT   | 1         | 0.01%   |
| ks_IN   | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 5252      | 73.41%  |
| EFI  | 1902      | 26.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 6789      | 95.94%  |
| Btrfs   | 140       | 1.98%   |
| Overlay | 108       | 1.53%   |
| Xfs     | 22        | 0.31%   |
| Unknown | 12        | 0.17%   |
| Zfs     | 4         | 0.06%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5711      | 80.38%  |
| GPT     | 1236      | 17.4%   |
| MBR     | 158       | 2.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6895      | 97.44%  |
| Yes       | 181       | 2.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6481      | 91.42%  |
| Yes       | 608       | 8.58%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1222      | 17.32%  |
| Dell                    | 958       | 13.58%  |
| Lenovo                  | 901       | 12.77%  |
| Hewlett-Packard         | 737       | 10.44%  |
| Gigabyte Technology     | 574       | 8.13%   |
| MSI                     | 540       | 7.65%   |
| Acer                    | 342       | 4.85%   |
| ASRock                  | 284       | 4.02%   |
| Apple                   | 283       | 4.01%   |
| System76                | 166       | 2.35%   |
| Intel                   | 97        | 1.37%   |
| Toshiba                 | 83        | 1.18%   |
| Samsung Electronics     | 74        | 1.05%   |
| Sony                    | 44        | 0.62%   |
| HUAWEI                  | 44        | 0.62%   |
| Alienware               | 44        | 0.62%   |
| Notebook                | 40        | 0.57%   |
| Microsoft               | 36        | 0.51%   |
| Fujitsu                 | 33        | 0.47%   |
| Positivo                | 32        | 0.45%   |
| Google                  | 31        | 0.44%   |
| Unknown                 | 26        | 0.37%   |
| Pegatron                | 24        | 0.34%   |
| Medion                  | 21        | 0.3%    |
| Razer                   | 18        | 0.26%   |
| Biostar                 | 16        | 0.23%   |
| Raspberry Pi Foundation | 15        | 0.21%   |
| PC Specialist           | 15        | 0.21%   |
| Foxconn                 | 15        | 0.21%   |
| Supermicro              | 14        | 0.2%    |
| ECS                     | 14        | 0.2%    |
| Timi                    | 13        | 0.18%   |
| LG Electronics          | 13        | 0.18%   |
| Packard Bell            | 11        | 0.16%   |
| Gateway                 | 11        | 0.16%   |
| TUXEDO                  | 10        | 0.14%   |
| Huanan                  | 9         | 0.13%   |
| PCWare                  | 8         | 0.11%   |
| GPU Company             | 8         | 0.11%   |
| Framework               | 8         | 0.11%   |
| Eluktronics             | 7         | 0.1%    |
| Chuwi                   | 7         | 0.1%    |
| Teclast                 | 6         | 0.09%   |
| OEM                     | 6         | 0.09%   |
| Fujitsu Siemens         | 6         | 0.09%   |
| eMachines               | 6         | 0.09%   |
| Panasonic               | 5         | 0.07%   |
| Minix                   | 5         | 0.07%   |
| EVGA                    | 5         | 0.07%   |
| Avell High Performance  | 5         | 0.07%   |
| SLIMBOOK                | 4         | 0.06%   |
| Schenker                | 4         | 0.06%   |
| Quanta                  | 4         | 0.06%   |
| MOTILE                  | 4         | 0.06%   |
| HASEE Computer          | 4         | 0.06%   |
| EVOO                    | 4         | 0.06%   |
| Clevo                   | 4         | 0.06%   |
| BESSTAR Tech            | 4         | 0.06%   |
| AMI                     | 4         | 0.06%   |
| TrekStor                | 3         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 73        | 1.03%   |
| Unknown                        | 38        | 0.54%   |
| System76 Oryx Pro              | 34        | 0.48%   |
| ASUS TUF Gaming X570-PLUS      | 34        | 0.48%   |
| Gigabyte B450M DS3H            | 31        | 0.44%   |
| System76 Lemur Pro             | 29        | 0.41%   |
| MSI MS-7C02                    | 28        | 0.4%    |
| Dell XPS 15 7590               | 27        | 0.38%   |
| MSI MS-7C37                    | 25        | 0.35%   |
| ASUS ROG STRIX B450-F GAMING   | 23        | 0.33%   |
| MSI MS-7B86                    | 22        | 0.31%   |
| Dell OptiPlex 9020             | 20        | 0.28%   |
| ASUS PRIME B450M-A             | 20        | 0.28%   |
| HP Pavilion Notebook           | 19        | 0.27%   |
| Apple MacBookPro9,2            | 19        | 0.27%   |
| Gigabyte X570 AORUS ELITE      | 18        | 0.26%   |
| Dell XPS 15 9500               | 18        | 0.26%   |
| System76 Galago Pro            | 17        | 0.24%   |
| System76 Thelio                | 16        | 0.23%   |
| System76 Gazelle               | 16        | 0.23%   |
| Apple MacBookPro8,1            | 16        | 0.23%   |
| Dell OptiPlex 7010             | 15        | 0.21%   |
| ASRock B450M Steel Legend      | 15        | 0.21%   |
| ASRock B450M Pro4              | 15        | 0.21%   |
| System76 Darter Pro            | 14        | 0.2%    |
| HP Pavilion 15                 | 14        | 0.2%    |
| HP Notebook                    | 14        | 0.2%    |
| Dell XPS 15 9560               | 14        | 0.2%    |
| ASUS ROG STRIX B550-F GAMING   | 14        | 0.2%    |
| HP Pavilion dv6                | 13        | 0.18%   |
| Apple MacBookPro12,1           | 13        | 0.18%   |
| Gigabyte A320M-S2H             | 12        | 0.17%   |
| Dell XPS 15 9570               | 12        | 0.17%   |
| Dell Latitude E6420            | 12        | 0.17%   |
| Apple MacBookAir7,2            | 12        | 0.17%   |
| RPi Raspberry Pi               | 11        | 0.16%   |
| MSI MS-7C91                    | 11        | 0.16%   |
| MSI MS-7B79                    | 11        | 0.16%   |
| Gigabyte X570 AORUS MASTER     | 11        | 0.16%   |
| Gigabyte B450 I AORUS PRO WIFI | 11        | 0.16%   |
| Dell XPS 17 9700               | 11        | 0.16%   |
| Dell OptiPlex 3010             | 11        | 0.16%   |
| ASUS PRIME B450M-GAMING/BR     | 11        | 0.16%   |
| Apple MacBookPro7,1            | 11        | 0.16%   |
| MSI MS-7B89                    | 10        | 0.14%   |
| Microsoft Surface Pro 3        | 10        | 0.14%   |
| Lenovo MIIX 320-10ICR 80XF     | 10        | 0.14%   |
| Lenovo MIIX 310-10ICR 80SG     | 10        | 0.14%   |
| Lenovo IdeaPad S145-15API 81V7 | 10        | 0.14%   |
| Gigabyte B75M-D3H              | 10        | 0.14%   |
| Gigabyte B450 AORUS PRO WIFI   | 10        | 0.14%   |
| Gigabyte B450 AORUS M          | 10        | 0.14%   |
| Dell XPS 13 9380               | 10        | 0.14%   |
| ASUS TUF Gaming X570-PRO       | 10        | 0.14%   |
| ASUS ROG STRIX B350-F GAMING   | 10        | 0.14%   |
| Apple MacBookPro5,5            | 10        | 0.14%   |
| Acer Aspire E5-575G            | 10        | 0.14%   |
| System76 Thelio Major          | 9         | 0.13%   |
| Samsung 340XAA/350XAA/550XAA   | 9         | 0.13%   |
| MSI MS-7C84                    | 9         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 386       | 5.47%   |
| Dell Inspiron      | 276       | 3.91%   |
| Acer Aspire        | 237       | 3.36%   |
| ASUS ROG           | 215       | 3.05%   |
| Lenovo IdeaPad     | 206       | 2.92%   |
| Dell Latitude      | 175       | 2.48%   |
| Dell XPS           | 170       | 2.41%   |
| ASUS PRIME         | 150       | 2.13%   |
| HP Pavilion        | 147       | 2.08%   |
| Dell OptiPlex      | 129       | 1.83%   |
| ASUS TUF           | 116       | 1.64%   |
| HP EliteBook       | 84        | 1.19%   |
| Dell Precision     | 79        | 1.12%   |
| ASUS All           | 73        | 1.03%   |
| Toshiba Satellite  | 71        | 1.01%   |
| HP Laptop          | 69        | 0.98%   |
| Gigabyte X570      | 64        | 0.91%   |
| ASUS VivoBook      | 64        | 0.91%   |
| HP ProBook         | 62        | 0.88%   |
| HP Compaq          | 59        | 0.84%   |
| HP ENVY            | 58        | 0.82%   |
| Lenovo Legion      | 52        | 0.74%   |
| Dell Vostro        | 52        | 0.74%   |
| Lenovo Yoga        | 48        | 0.68%   |
| Gigabyte B450M     | 42        | 0.6%    |
| Gigabyte B450      | 42        | 0.6%    |
| Lenovo ThinkCentre | 41        | 0.58%   |
| Acer Nitro         | 39        | 0.55%   |
| Unknown            | 38        | 0.54%   |
| Microsoft Surface  | 36        | 0.51%   |
| System76 Oryx      | 34        | 0.48%   |
| ASRock B450M       | 34        | 0.48%   |
| System76 Lemur     | 32        | 0.45%   |
| HP OMEN            | 30        | 0.43%   |
| MSI MS-7C02        | 28        | 0.4%    |
| ASUS ASUS          | 28        | 0.4%    |
| ASRock X570        | 26        | 0.37%   |
| Apple MacBookPro9  | 26        | 0.37%   |
| System76 Thelio    | 25        | 0.35%   |
| MSI MS-7C37        | 25        | 0.35%   |
| ASUS ZenBook       | 24        | 0.34%   |
| Apple MacBookPro11 | 24        | 0.34%   |
| Lenovo MIIX        | 23        | 0.33%   |
| Gigabyte B550      | 23        | 0.33%   |
| Apple MacBookPro8  | 23        | 0.33%   |
| Acer Swift         | 23        | 0.33%   |
| MSI MS-7B86        | 22        | 0.31%   |
| ASRock B450        | 20        | 0.28%   |
| System76 Galago    | 19        | 0.27%   |
| HP Spectre         | 19        | 0.27%   |
| ASUS SABERTOOTH    | 19        | 0.27%   |
| System76 Gazelle   | 18        | 0.26%   |
| Razer Blade        | 18        | 0.26%   |
| Apple MacBookPro5  | 18        | 0.26%   |
| Lenovo ThinkBook   | 16        | 0.23%   |
| Gigabyte Z390      | 16        | 0.23%   |
| RPi Raspberry      | 15        | 0.21%   |
| Gigabyte A320M-S2H | 15        | 0.21%   |
| Fujitsu LIFEBOOK   | 15        | 0.21%   |
| System76 Darter    | 14        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 967       | 13.7%   |
| 2018    | 895       | 12.68%  |
| 2020    | 825       | 11.69%  |
| 2012    | 532       | 7.54%   |
| 2017    | 517       | 7.33%   |
| 2021    | 471       | 6.67%   |
| 2013    | 444       | 6.29%   |
| 2011    | 444       | 6.29%   |
| 2015    | 394       | 5.58%   |
| 2014    | 383       | 5.43%   |
| 2016    | 369       | 5.23%   |
| 2010    | 282       | 4%      |
| 2009    | 208       | 2.95%   |
| 2008    | 163       | 2.31%   |
| 2007    | 86        | 1.22%   |
| 2022    | 38        | 0.54%   |
| 2006    | 20        | 0.28%   |
| Unknown | 17        | 0.24%   |
| 2005    | 1         | 0.01%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3813      | 54.03%  |
| Desktop        | 2773      | 39.29%  |
| Convertible    | 178       | 2.52%   |
| All in one     | 88        | 1.25%   |
| Tablet         | 87        | 1.23%   |
| Mini pc        | 81        | 1.15%   |
| Server         | 21        | 0.3%    |
| System on chip | 15        | 0.21%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7052      | 99.93%  |
| Enabled  | 5         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6943      | 98.38%  |
| Yes  | 114       | 1.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1868      | 26.15%  |
| 4.01-8.0        | 1534      | 21.48%  |
| 8.01-16.0       | 1343      | 18.8%   |
| 3.01-4.0        | 945       | 13.23%  |
| 32.01-64.0      | 915       | 12.81%  |
| 64.01-256.0     | 250       | 3.5%    |
| 24.01-32.0      | 128       | 1.79%   |
| 1.01-2.0        | 110       | 1.54%   |
| 2.01-3.0        | 40        | 0.56%   |
| More than 256.0 | 9         | 0.13%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 2397      | 31.2%   |
| 1.01-2.0    | 2222      | 28.92%  |
| 4.01-8.0    | 1342      | 17.47%  |
| 3.01-4.0    | 1338      | 17.42%  |
| 8.01-16.0   | 294       | 3.83%   |
| 16.01-24.0  | 41        | 0.53%   |
| 0.51-1.0    | 18        | 0.23%   |
| 24.01-32.0  | 16        | 0.21%   |
| 32.01-64.0  | 11        | 0.14%   |
| 64.01-256.0 | 2         | 0.03%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3958      | 54.8%   |
| 2      | 1994      | 27.61%  |
| 3      | 655       | 9.07%   |
| 4      | 331       | 4.58%   |
| 5      | 133       | 1.84%   |
| 6      | 59        | 0.82%   |
| 0      | 41        | 0.57%   |
| 7      | 23        | 0.32%   |
| 8      | 9         | 0.12%   |
| 11     | 8         | 0.11%   |
| 9      | 5         | 0.07%   |
| 10     | 2         | 0.03%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4905      | 69.14%  |
| Yes       | 2189      | 30.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6087      | 85.93%  |
| No        | 997       | 14.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5653      | 79.71%  |
| No        | 1439      | 20.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4667      | 65.51%  |
| No        | 2457      | 34.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 2146      | 30.27%  |
| Brazil                 | 711       | 10.03%  |
| Germany                | 470       | 6.63%   |
| UK                     | 355       | 5.01%   |
| Canada                 | 305       | 4.3%    |
| Australia              | 209       | 2.95%   |
| India                  | 207       | 2.92%   |
| France                 | 183       | 2.58%   |
| Italy                  | 170       | 2.4%    |
| Netherlands            | 160       | 2.26%   |
| Sweden                 | 128       | 1.81%   |
| Russia                 | 116       | 1.64%   |
| Poland                 | 107       | 1.51%   |
| Spain                  | 93        | 1.31%   |
| Mexico                 | 81        | 1.14%   |
| South Africa           | 78        | 1.1%    |
| Portugal               | 77        | 1.09%   |
| Switzerland            | 73        | 1.03%   |
| Romania                | 72        | 1.02%   |
| Norway                 | 61        | 0.86%   |
| Finland                | 58        | 0.82%   |
| Austria                | 54        | 0.76%   |
| New Zealand            | 51        | 0.72%   |
| Belgium                | 51        | 0.72%   |
| Philippines            | 49        | 0.69%   |
| Argentina              | 49        | 0.69%   |
| Greece                 | 46        | 0.65%   |
| Denmark                | 44        | 0.62%   |
| Turkey                 | 43        | 0.61%   |
| Indonesia              | 34        | 0.48%   |
| Chile                  | 34        | 0.48%   |
| Japan                  | 32        | 0.45%   |
| Czechia                | 31        | 0.44%   |
| Croatia                | 31        | 0.44%   |
| Ukraine                | 30        | 0.42%   |
| Ireland                | 30        | 0.42%   |
| Bulgaria               | 30        | 0.42%   |
| Malaysia               | 27        | 0.38%   |
| Hungary                | 26        | 0.37%   |
| Israel                 | 24        | 0.34%   |
| Colombia               | 22        | 0.31%   |
| Slovakia               | 21        | 0.3%    |
| Lithuania              | 21        | 0.3%    |
| Vietnam                | 18        | 0.25%   |
| Singapore              | 18        | 0.25%   |
| Serbia                 | 18        | 0.25%   |
| Taiwan                 | 16        | 0.23%   |
| Iceland                | 16        | 0.23%   |
| Egypt                  | 16        | 0.23%   |
| Thailand               | 14        | 0.2%    |
| Saudi Arabia           | 14        | 0.2%    |
| Latvia                 | 13        | 0.18%   |
| Hong Kong              | 13        | 0.18%   |
| Slovenia               | 12        | 0.17%   |
| Peru                   | 12        | 0.17%   |
| Pakistan               | 12        | 0.17%   |
| Bosnia and Herzegovina | 12        | 0.17%   |
| Ecuador                | 11        | 0.16%   |
| China                  | 11        | 0.16%   |
| Iran                   | 9         | 0.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 87        | 1.18%   |
| Sydney         | 60        | 0.82%   |
| Melbourne      | 41        | 0.56%   |
| Berlin         | 39        | 0.53%   |
| Rio de Janeiro | 38        | 0.52%   |
| Brisbane       | 37        | 0.5%    |
| Vienna         | 35        | 0.48%   |
| Dallas         | 33        | 0.45%   |
| Warsaw         | 32        | 0.43%   |
| Moscow         | 31        | 0.42%   |
| London         | 31        | 0.42%   |
| Milan          | 30        | 0.41%   |
| New York       | 28        | 0.38%   |
| Helsinki       | 27        | 0.37%   |
| Bengaluru      | 27        | 0.37%   |
| Amsterdam      | 27        | 0.37%   |
| Toronto        | 26        | 0.35%   |
| Paris          | 26        | 0.35%   |
| Bucharest      | 26        | 0.35%   |
| Auckland       | 26        | 0.35%   |
| Athens         | 26        | 0.35%   |
| Miami          | 25        | 0.34%   |
| Chicago        | 25        | 0.34%   |
| Zurich         | 24        | 0.33%   |
| Denver         | 24        | 0.33%   |
| Johannesburg   | 23        | 0.31%   |
| Zagreb         | 22        | 0.3%    |
| Rome           | 22        | 0.3%    |
| Montreal       | 22        | 0.3%    |
| Brasília      | 22        | 0.3%    |
| Sofia          | 21        | 0.29%   |
| Los Angeles    | 21        | 0.29%   |
| Madrid         | 20        | 0.27%   |
| Calgary        | 20        | 0.27%   |
| Atlanta        | 20        | 0.27%   |
| Stockholm      | 19        | 0.26%   |
| Istanbul       | 19        | 0.26%   |
| Edmonton       | 19        | 0.26%   |
| Cape Town      | 19        | 0.26%   |
| Brooklyn       | 19        | 0.26%   |
| Singapore      | 18        | 0.24%   |
| Porto Alegre   | 18        | 0.24%   |
| Fortaleza      | 18        | 0.24%   |
| Dublin         | 18        | 0.24%   |
| Seattle        | 17        | 0.23%   |
| Phoenix        | 17        | 0.23%   |
| Oslo           | 17        | 0.23%   |
| Buenos Aires   | 17        | 0.23%   |
| Belo Horizonte | 17        | 0.23%   |
| Perth          | 16        | 0.22%   |
| Munich         | 16        | 0.22%   |
| Mexico City    | 16        | 0.22%   |
| Lisbon         | 16        | 0.22%   |
| Hyderabad      | 16        | 0.22%   |
| Browning       | 16        | 0.22%   |
| Washington     | 15        | 0.2%    |
| Portland       | 15        | 0.2%    |
| Birmingham     | 15        | 0.2%    |
| St Petersburg  | 14        | 0.19%   |
| San Jose       | 14        | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1934      | 2906   | 17.74%  |
| Seagate                        | 1549      | 2200   | 14.21%  |
| WDC                            | 1513      | 2090   | 13.88%  |
| SanDisk                        | 704       | 923    | 6.46%   |
| Kingston                       | 632       | 795    | 5.8%    |
| Toshiba                        | 601       | 734    | 5.51%   |
| Crucial                        | 419       | 545    | 3.84%   |
| Unknown                        | 364       | 452    | 3.34%   |
| Intel                          | 303       | 403    | 2.78%   |
| SK hynix                       | 284       | 361    | 2.61%   |
| Hitachi                        | 239       | 294    | 2.19%   |
| Phison                         | 211       | 297    | 1.94%   |
| HGST                           | 196       | 233    | 1.8%    |
| A-DATA Technology              | 170       | 215    | 1.56%   |
| Micron Technology              | 143       | 167    | 1.31%   |
| Apple                          | 126       | 147    | 1.16%   |
| PNY                            | 101       | 123    | 0.93%   |
| Silicon Motion                 | 97        | 131    | 0.89%   |
| China                          | 97        | 129    | 0.89%   |
| Micron/Crucial Technology      | 81        | 109    | 0.74%   |
| OCZ                            | 50        | 62     | 0.46%   |
| LITEON                         | 50        | 58     | 0.46%   |
| SPCC                           | 45        | 58     | 0.41%   |
| XPG                            | 41        | 54     | 0.38%   |
| Transcend                      | 41        | 46     | 0.38%   |
| KIOXIA                         | 39        | 48     | 0.36%   |
| Corsair                        | 38        | 48     | 0.35%   |
| Patriot                        | 35        | 46     | 0.32%   |
| Team                           | 34        | 40     | 0.31%   |
| Maxtor                         | 33        | 34     | 0.3%    |
| Realtek Semiconductor          | 32        | 36     | 0.29%   |
| LITEONIT                       | 32        | 38     | 0.29%   |
| JMicron Technology             | 26        | 33     | 0.24%   |
| Hewlett-Packard                | 24        | 31     | 0.22%   |
| Lexar                          | 22        | 23     | 0.2%    |
| KingSpec                       | 22        | 25     | 0.2%    |
| Intenso                        | 22        | 23     | 0.2%    |
| Fujitsu                        | 22        | 24     | 0.2%    |
| ADATA Technology               | 22        | 31     | 0.2%    |
| ASMT                           | 16        | 22     | 0.15%   |
| SABRENT                        | 15        | 17     | 0.14%   |
| Gigabyte Technology            | 15        | 17     | 0.14%   |
| Union Memory (Shenzhen)        | 14        | 19     | 0.13%   |
| Apacer                         | 14        | 19     | 0.13%   |
| Mushkin                        | 13        | 15     | 0.12%   |
| Goodram                        | 13        | 14     | 0.12%   |
| KingDian                       | 12        | 14     | 0.11%   |
| TO Exter                       | 11        | 14     | 0.1%    |
| Plextor                        | 11        | 15     | 0.1%    |
| Unknown                        | 11        | 12     | 0.1%    |
| Solid State Storage Technology | 10        | 13     | 0.09%   |
| Lite-On                        | 10        | 13     | 0.09%   |
| LaCie                          | 10        | 12     | 0.09%   |
| T-FORCE                        | 9         | 11     | 0.08%   |
| Netac                          | 9         | 9      | 0.08%   |
| KingFast                       | 9         | 11     | 0.08%   |
| Dogfish                        | 9         | 11     | 0.08%   |
| KIOXIA-EXCERIA                 | 8         | 8      | 0.07%   |
| UMIS                           | 7         | 7      | 0.06%   |
| OWC                            | 7         | 16     | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB         | 185       | 1.54%   |
| Samsung NVMe SSD Drive 500GB       | 171       | 1.42%   |
| Kingston SA400S37240G 240GB SSD    | 168       | 1.39%   |
| Samsung NVMe SSD Drive 512GB       | 111       | 0.92%   |
| Samsung SSD 850 EVO 250GB          | 105       | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB     | 101       | 0.84%   |
| SanDisk NVMe SSD Drive 1TB         | 97        | 0.81%   |
| Unknown MMC Card  64GB             | 95        | 0.79%   |
| Samsung SSD 860 EVO 500GB          | 94        | 0.78%   |
| SanDisk NVMe SSD Drive 500GB       | 89        | 0.74%   |
| Samsung SSD 850 EVO 500GB          | 87        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB     | 86        | 0.71%   |
| Samsung NVMe SSD Drive 256GB       | 85        | 0.71%   |
| Samsung SSD 860 EVO 1TB            | 81        | 0.67%   |
| Kingston SA400S37120G 120GB SSD    | 80        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB     | 79        | 0.66%   |
| HGST HTS721010A9E630 1TB           | 73        | 0.61%   |
| Seagate ST500DM002-1BD142 500GB    | 72        | 0.6%    |
| Samsung NVMe SSD Drive 250GB       | 68        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 67        | 0.56%   |
| Intel NVMe SSD Drive 512GB         | 67        | 0.56%   |
| Kingston SA400S37480G 480GB SSD    | 66        | 0.55%   |
| SanDisk NVMe SSD Drive 512GB       | 65        | 0.54%   |
| Toshiba MQ01ABD100 1TB             | 62        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB           | 61        | 0.51%   |
| Unknown MMC Card  32GB             | 61        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB        | 60        | 0.5%    |
| SK hynix NVMe SSD Drive 512GB      | 58        | 0.48%   |
| Samsung NVMe SSD Drive 1024GB      | 57        | 0.47%   |
| Crucial CT500MX500SSD1 500GB       | 56        | 0.46%   |
| Samsung NVMe SSD Drive 2TB         | 53        | 0.44%   |
| Intel NVMe SSD Drive 1024GB        | 50        | 0.42%   |
| Phison NVMe SSD Drive 1TB          | 49        | 0.41%   |
| Samsung SSD 860 EVO 250GB          | 48        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB       | 46        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD   | 45        | 0.37%   |
| Crucial CT240BX500SSD1 240GB       | 45        | 0.37%   |
| Unknown MMC Card  128GB            | 44        | 0.37%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 44        | 0.37%   |
| SK hynix NVMe SSD Drive 256GB      | 43        | 0.36%   |
| Seagate Expansion 1TB              | 42        | 0.35%   |
| SanDisk NVMe SSD Drive 256GB       | 42        | 0.35%   |
| Toshiba MQ04ABF100 1TB             | 41        | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB     | 41        | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB     | 41        | 0.34%   |
| Toshiba DT01ACA100 1TB             | 40        | 0.33%   |
| Seagate ST9500325AS 500GB          | 40        | 0.33%   |
| Samsung SSD 860 QVO 1TB            | 40        | 0.33%   |
| Unknown SD/MMC/MS PRO 64GB         | 39        | 0.32%   |
| Samsung SSD 840 EVO 250GB          | 38        | 0.32%   |
| WDC WD10SPZX-24Z10 1TB             | 37        | 0.31%   |
| Seagate ST4000DM004-2CV104 4TB     | 37        | 0.31%   |
| Seagate ST500LT012-1DG142 500GB    | 35        | 0.29%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 34        | 0.28%   |
| Toshiba NVMe SSD Drive 512GB       | 34        | 0.28%   |
| Phison NVMe SSD Drive 1024GB       | 33        | 0.27%   |
| WDC WD10SPZX-21Z10T0 1TB           | 31        | 0.26%   |
| Toshiba NVMe SSD Drive 256GB       | 31        | 0.26%   |
| SanDisk SSD PLUS 240GB             | 31        | 0.26%   |
| Seagate ST1000LM049-2GH172 1TB     | 30        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1498      | 2087   | 38.92%  |
| WDC                 | 1180      | 1611   | 30.66%  |
| Toshiba             | 433       | 519    | 11.25%  |
| Hitachi             | 239       | 294    | 6.21%   |
| HGST                | 196       | 233    | 5.09%   |
| Samsung Electronics | 124       | 144    | 3.22%   |
| Unknown             | 42        | 49     | 1.09%   |
| Apple               | 38        | 46     | 0.99%   |
| Maxtor              | 25        | 26     | 0.65%   |
| Fujitsu             | 21        | 23     | 0.55%   |
| SABRENT             | 15        | 17     | 0.39%   |
| ASMT                | 7         | 9      | 0.18%   |
| USB                 | 3         | 4      | 0.08%   |
| SATAFIRM            | 3         | 3      | 0.08%   |
| Hewlett-Packard     | 3         | 5      | 0.08%   |
| ExcelStor           | 3         | 3      | 0.08%   |
| Magnetic Data       | 2         | 2      | 0.05%   |
| JMicron Technology  | 2         | 4      | 0.05%   |
| Intenso             | 2         | 2      | 0.05%   |
| RSH-339             | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| OEM                 | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 2      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| HGST HDN            | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |
| Glyph               | 1         | 2      | 0.03%   |
| DAS                 | 1         | 4      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 954       | 1371   | 24.74%  |
| Kingston            | 518       | 637    | 13.43%  |
| Crucial             | 389       | 511    | 10.09%  |
| SanDisk             | 371       | 469    | 9.62%   |
| WDC                 | 260       | 326    | 6.74%   |
| A-DATA Technology   | 138       | 175    | 3.58%   |
| PNY                 | 99        | 121    | 2.57%   |
| China               | 96        | 128    | 2.49%   |
| Intel               | 90        | 106    | 2.33%   |
| Apple               | 75        | 80     | 1.95%   |
| SK hynix            | 72        | 90     | 1.87%   |
| Micron Technology   | 65        | 71     | 1.69%   |
| Toshiba             | 58        | 68     | 1.5%    |
| OCZ                 | 49        | 58     | 1.27%   |
| LITEON              | 46        | 54     | 1.19%   |
| SPCC                | 42        | 53     | 1.09%   |
| Transcend           | 40        | 45     | 1.04%   |
| Patriot             | 35        | 46     | 0.91%   |
| LITEONIT            | 32        | 38     | 0.83%   |
| Corsair             | 31        | 38     | 0.8%    |
| Seagate             | 30        | 44     | 0.78%   |
| Team                | 29        | 35     | 0.75%   |
| Lexar               | 21        | 22     | 0.54%   |
| KingSpec            | 21        | 24     | 0.54%   |
| Hewlett-Packard     | 18        | 23     | 0.47%   |
| Apacer              | 14        | 19     | 0.36%   |
| Intenso             | 13        | 14     | 0.34%   |
| Gigabyte Technology | 12        | 14     | 0.31%   |
| TO Exter            | 11        | 14     | 0.29%   |
| Plextor             | 11        | 15     | 0.29%   |
| KingDian            | 11        | 13     | 0.29%   |
| GOODRAM             | 11        | 12     | 0.29%   |
| Mushkin             | 10        | 12     | 0.26%   |
| Dogfish             | 9         | 11     | 0.23%   |
| Maxtor              | 8         | 8      | 0.21%   |
| ASMT                | 8         | 12     | 0.21%   |
| OWC                 | 7         | 16     | 0.18%   |
| Netac               | 7         | 7      | 0.18%   |
| PNY USB             | 6         | 13     | 0.16%   |
| BHT                 | 6         | 6      | 0.16%   |
| Unknown             | 5         | 5      | 0.13%   |
| KIOXIA-EXCERIA      | 5         | 5      | 0.13%   |
| FORESEE             | 5         | 7      | 0.13%   |
| Colorful            | 4         | 4      | 0.1%    |
| Unknown             | 4         | 4      | 0.1%    |
| Vaseky              | 3         | 4      | 0.08%   |
| Phison              | 3         | 3      | 0.08%   |
| MyDigitalSSD        | 3         | 3      | 0.08%   |
| Kingmax             | 3         | 4      | 0.08%   |
| KingFast            | 3         | 3      | 0.08%   |
| INTEL SS            | 3         | 3      | 0.08%   |
| Zheino              | 2         | 3      | 0.05%   |
| XPG                 | 2         | 3      | 0.05%   |
| W800S               | 2         | 2      | 0.05%   |
| Verbatim            | 2         | 2      | 0.05%   |
| Teclast             | 2         | 2      | 0.05%   |
| RZX                 | 2         | 2      | 0.05%   |
| KIOXIA-E            | 2         | 3      | 0.05%   |
| KINGBANK            | 2         | 2      | 0.05%   |
| Integral            | 2         | 2      | 0.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 3349      | 4970   | 34.24%  |
| HDD     | 3285      | 5099   | 33.59%  |
| NVMe    | 2691      | 3985   | 27.52%  |
| MMC     | 276       | 342    | 2.82%   |
| Unknown | 179       | 234    | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5257      | 9735   | 60.96%  |
| NVMe | 2680      | 3956   | 31.08%  |
| SAS  | 410       | 597    | 4.75%   |
| MMC  | 276       | 342    | 3.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3856      | 5711   | 55.64%  |
| 0.51-1.0   | 2093      | 2880   | 30.2%   |
| 1.01-2.0   | 573       | 805    | 8.27%   |
| 3.01-4.0   | 181       | 295    | 2.61%   |
| 2.01-3.0   | 126       | 181    | 1.82%   |
| 4.01-10.0  | 86        | 161    | 1.24%   |
| 10.01-20.0 | 15        | 36     | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2205      | 30.1%   |
| 251-500        | 1823      | 24.88%  |
| 501-1000       | 1309      | 17.87%  |
| 1001-2000      | 677       | 9.24%   |
| 51-100         | 360       | 4.91%   |
| More than 3000 | 341       | 4.65%   |
| 2001-3000      | 214       | 2.92%   |
| 21-50          | 179       | 2.44%   |
| 1-20           | 171       | 2.33%   |
| Unknown        | 47        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2970      | 38.88%  |
| 21-50          | 1503      | 19.68%  |
| 101-250        | 916       | 11.99%  |
| 51-100         | 884       | 11.57%  |
| 251-500        | 538       | 7.04%   |
| 501-1000       | 364       | 4.77%   |
| 1001-2000      | 222       | 2.91%   |
| More than 3000 | 124       | 1.62%   |
| 2001-3000      | 70        | 0.92%   |
| Unknown        | 47        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 6      | 2.73%   |
| HGST HTS725050A7E630 500GB          | 5         | 6      | 2.27%   |
| HGST HTS721010A9E630 1TB            | 5         | 5      | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 1.82%   |
| HGST HTS541010A9E680 1TB            | 4         | 4      | 1.82%   |
| WDC WD10JPCX-24UE4T0 1TB            | 3         | 3      | 1.36%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 4      | 1.36%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 1.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 3      | 1.36%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 1.36%   |
| Seagate ST1500DL003-9VT16L 1TB      | 3         | 3      | 1.36%   |
| Seagate ST1000LX015-1U7172 1TB      | 3         | 3      | 1.36%   |
| Seagate ST1000DM003-9YN162 1TB      | 3         | 3      | 1.36%   |
| Samsung Electronics HD502HI 500GB   | 3         | 3      | 1.36%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 5      | 1.36%   |
| Hitachi HTS545050A7E380 500GB       | 3         | 4      | 1.36%   |
| Crucial CT525MX300SSD1 528GB        | 3         | 3      | 1.36%   |
| Crucial CT1000P1SSD8 1TB            | 3         | 3      | 1.36%   |
| WDC WD3200AAKS-75B3A0 320GB         | 2         | 2      | 0.91%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 0.91%   |
| Toshiba HDWD110 1TB                 | 2         | 2      | 0.91%   |
| Seagate ST9750420AS 752GB           | 2         | 2      | 0.91%   |
| Seagate ST9500325AS 500GB           | 2         | 3      | 0.91%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB      | 2         | 2      | 0.91%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 0.91%   |
| Samsung Electronics HD103SJ 1TB     | 2         | 2      | 0.91%   |
| Kingston SUV400S37120G 120GB SSD    | 2         | 2      | 0.91%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 3      | 0.91%   |
| Hitachi HDP725050GLA360 500GB       | 2         | 2      | 0.91%   |
| A-DATA Technology SU800 512GB SSD   | 2         | 2      | 0.91%   |
| WDC WD7500BPVT-60HXZT1 752GB        | 1         | 1      | 0.45%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1      | 0.45%   |
| WDC WD6400AAKS-22A7B2 640GB         | 1         | 1      | 0.45%   |
| WDC WD5001AALS-00J7B1 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 2      | 0.45%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 0.45%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 1      | 0.45%   |
| WDC WD5000BEVT-75A0RT0 500GB        | 1         | 2      | 0.45%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000AAKS-41YGA1 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 1      | 0.45%   |
| WDC WD5000AADS-00M2B0 500GB         | 1         | 1      | 0.45%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 1      | 0.45%   |
| WDC WD30EZRX-00SPEB0 3TB            | 1         | 1      | 0.45%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 1      | 0.45%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1         | 1      | 0.45%   |
| WDC WD20EFRX-68AX9N0 2TB            | 1         | 2      | 0.45%   |
| WDC WD2003FYYS-05T9B0 2TB           | 1         | 1      | 0.45%   |
| WDC WD1600BJKT-75F4T0 160GB         | 1         | 1      | 0.45%   |
| WDC WD15EVDS-73V9B0 1TB             | 1         | 1      | 0.45%   |
| WDC WD15EADS-11P8B1 1TB             | 1         | 1      | 0.45%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 1      | 0.45%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 0.45%   |
| WDC WD10SPCX-24HWST1 1TB            | 1         | 1      | 0.45%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 0.45%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 65     | 27.19%  |
| WDC                 | 44        | 49     | 20.28%  |
| Samsung Electronics | 19        | 23     | 8.76%   |
| HGST                | 16        | 17     | 7.37%   |
| Toshiba             | 15        | 15     | 6.91%   |
| Kingston            | 11        | 14     | 5.07%   |
| Hitachi             | 11        | 13     | 5.07%   |
| Crucial             | 8         | 8      | 3.69%   |
| Intel               | 6         | 6      | 2.76%   |
| SK hynix            | 5         | 6      | 2.3%    |
| A-DATA Technology   | 5         | 5      | 2.3%    |
| Micron Technology   | 4         | 4      | 1.84%   |
| SanDisk             | 3         | 3      | 1.38%   |
| China               | 2         | 2      | 0.92%   |
| SPCC                | 1         | 1      | 0.46%   |
| S3+                 | 1         | 1      | 0.46%   |
| Maxtor              | 1         | 1      | 0.46%   |
| LITEON              | 1         | 1      | 0.46%   |
| Lexar               | 1         | 1      | 0.46%   |
| Leven               | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| ASMT                | 1         | 1      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 65     | 38.06%  |
| WDC                 | 44        | 49     | 28.39%  |
| HGST                | 16        | 17     | 10.32%  |
| Toshiba             | 13        | 13     | 8.39%   |
| Hitachi             | 11        | 13     | 7.1%    |
| Samsung Electronics | 9         | 9      | 5.81%   |
| Maxtor              | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 144       | 169    | 69.9%   |
| SSD  | 48        | 56     | 23.3%   |
| NVMe | 14        | 14     | 6.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Seagate ST3500418ASQ 500GB | 1         | 1      | 50%     |
| Patriot Pyro SSD 120GB     | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Patriot | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5781      | 12080  | 78.39%  |
| Works    | 1391      | 2307   | 18.86%  |
| Malfunc  | 200       | 239    | 2.71%   |
| Failed   | 2         | 3      | 0.03%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4445      | 46.68%  |
| AMD                              | 1737      | 18.24%  |
| Samsung Electronics              | 1086      | 11.41%  |
| SanDisk                          | 436       | 4.58%   |
| Phison Electronics               | 227       | 2.38%   |
| SK hynix                         | 211       | 2.22%   |
| ASMedia Technology               | 167       | 1.75%   |
| Nvidia                           | 130       | 1.37%   |
| Toshiba America Info Systems     | 125       | 1.31%   |
| Kingston Technology Company      | 117       | 1.23%   |
| Silicon Motion                   | 109       | 1.14%   |
| Micron/Crucial Technology        | 105       | 1.1%    |
| Marvell Technology Group         | 86        | 0.9%    |
| ADATA Technology                 | 86        | 0.9%    |
| Micron Technology                | 81        | 0.85%   |
| JMicron Technology               | 76        | 0.8%    |
| Realtek Semiconductor            | 43        | 0.45%   |
| KIOXIA                           | 42        | 0.44%   |
| Union Memory (Shenzhen)          | 28        | 0.29%   |
| Solid State Storage Technology   | 25        | 0.26%   |
| Seagate Technology               | 21        | 0.22%   |
| Broadcom / LSI                   | 21        | 0.22%   |
| LSI Logic / Symbios Logic        | 16        | 0.17%   |
| Lite-On Technology               | 15        | 0.16%   |
| Apple                            | 15        | 0.16%   |
| VIA Technologies                 | 10        | 0.11%   |
| Silicon Integrated Systems [SiS] | 10        | 0.11%   |
| Shenzhen Longsys Electronics     | 10        | 0.11%   |
| Lenovo                           | 7         | 0.07%   |
| Silicon Image                    | 6         | 0.06%   |
| Hewlett-Packard                  | 5         | 0.05%   |
| Adaptec                          | 5         | 0.05%   |
| Unknown                          | 4         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.04%   |
| HighPoint Technologies           | 3         | 0.03%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| Integrated Technology Express    | 1         | 0.01%   |
| Enmotus                          | 1         | 0.01%   |
| Dell                             | 1         | 0.01%   |
| Biwin Storage Technology         | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1319      | 12.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 671       | 6.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 384       | 3.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 356       | 3.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 301       | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 291       | 2.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 271       | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 234       | 2.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 208       | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 196       | 1.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 164       | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 160       | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 150       | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 141       | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 141       | 1.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 138       | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 136       | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 133       | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 130       | 1.2%    |
| Phison E12 NVMe Controller                                                              | 121       | 1.12%   |
| Samsung NVMe SSD Controller 980                                                         | 119       | 1.1%    |
| Intel SSD 660P Series                                                                   | 118       | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 117       | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 113       | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 109       | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 106       | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 105       | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 101       | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 99        | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 97        | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 92        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 87        | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 85        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 84        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 81        | 0.75%   |
| Micron Non-Volatile memory controller                                                   | 80        | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 80        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 75        | 0.69%   |
| SK hynix Gold P31 SSD                                                                   | 69        | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 68        | 0.63%   |
| AMD 300 Series Chipset SATA Controller                                                  | 67        | 0.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 62        | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 61        | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 61        | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 61        | 0.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 60        | 0.55%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 59        | 0.55%   |
| AMD FCH SATA Controller D                                                               | 58        | 0.54%   |
| SanDisk Non-Volatile memory controller                                                  | 57        | 0.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 57        | 0.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 55        | 0.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 53        | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 51        | 0.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 51        | 0.47%   |
| Nvidia MCP79 AHCI Controller                                                            | 49        | 0.45%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 48        | 0.44%   |
| Kingston Company A2000 NVMe SSD                                                         | 48        | 0.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 45        | 0.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 44        | 0.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 41        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5398      | 57.61%  |
| NVMe | 2684      | 28.64%  |
| IDE  | 645       | 6.88%   |
| RAID | 597       | 6.37%   |
| SAS  | 32        | 0.34%   |
| SCSI | 14        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 5043      | 71.46%  |
| AMD    | 1999      | 28.33%  |
| ARM    | 15        | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 131       | 1.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 104       | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 99        | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 85        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 79        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 78        | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 74        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 65        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 62        | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 61        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 60        | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 60        | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 59        | 0.83%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 57        | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 57        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 57        | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 54        | 0.76%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 48        | 0.68%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 47        | 0.66%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 46        | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 45        | 0.64%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 45        | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 44        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 44        | 0.62%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 43        | 0.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 42        | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 41        | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 40        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 40        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 38        | 0.54%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 37        | 0.52%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 37        | 0.52%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 36        | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 36        | 0.51%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 36        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 34        | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 34        | 0.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.48%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 34        | 0.48%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 34        | 0.48%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 33        | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 32        | 0.45%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 31        | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 31        | 0.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 31        | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 31        | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 30        | 0.42%   |
| AMD FX-8350 Eight-Core Processor              | 30        | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 29        | 0.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 29        | 0.41%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 29        | 0.41%   |
| AMD FX-6300 Six-Core Processor                | 28        | 0.4%    |
| Intel Core i5-4590 CPU @ 3.30GHz              | 27        | 0.38%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 27        | 0.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.38%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 26        | 0.37%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 26        | 0.37%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 26        | 0.37%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 26        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1748      | 24.73%  |
| Intel Core i5           | 1594      | 22.55%  |
| AMD Ryzen 5             | 648       | 9.17%   |
| AMD Ryzen 7             | 462       | 6.54%   |
| Intel Core i3           | 418       | 5.91%   |
| Other                   | 302       | 4.27%   |
| Intel Core 2 Duo        | 210       | 2.97%   |
| AMD Ryzen 9             | 182       | 2.57%   |
| Intel Celeron           | 179       | 2.53%   |
| Intel Xeon              | 156       | 2.21%   |
| AMD Ryzen 3             | 105       | 1.49%   |
| AMD FX                  | 105       | 1.49%   |
| Intel Core i9           | 99        | 1.4%    |
| Intel Pentium           | 95        | 1.34%   |
| Intel Atom              | 60        | 0.85%   |
| AMD A6                  | 60        | 0.85%   |
| Intel Pentium Dual-Core | 57        | 0.81%   |
| AMD A8                  | 52        | 0.74%   |
| AMD A10                 | 48        | 0.68%   |
| Intel Core 2 Quad       | 45        | 0.64%   |
| AMD Ryzen Threadripper  | 41        | 0.58%   |
| Intel Core 2            | 31        | 0.44%   |
| AMD Phenom II X4        | 31        | 0.44%   |
| AMD A4                  | 31        | 0.44%   |
| AMD Athlon              | 24        | 0.34%   |
| AMD Ryzen 7 PRO         | 23        | 0.33%   |
| Intel Pentium Dual      | 20        | 0.28%   |
| AMD Athlon II X2        | 18        | 0.25%   |
| Intel Core m3           | 16        | 0.23%   |
| Intel Genuine           | 14        | 0.2%    |
| AMD Ryzen 5 PRO         | 14        | 0.2%    |
| AMD Athlon II X4        | 12        | 0.17%   |
| AMD Athlon 64 X2        | 12        | 0.17%   |
| AMD Phenom II X6        | 11        | 0.16%   |
| AMD E1                  | 11        | 0.16%   |
| AMD E                   | 11        | 0.16%   |
| AMD E2                  | 9         | 0.13%   |
| AMD Phenom              | 8         | 0.11%   |
| Intel Pentium Silver    | 7         | 0.1%    |
| AMD Turion 64 X2 Mobile | 7         | 0.1%    |
| Intel Pentium Gold      | 6         | 0.08%   |
| Intel Core m5           | 6         | 0.08%   |
| AMD Sempron             | 5         | 0.07%   |
| AMD PRO A10             | 5         | 0.07%   |
| AMD Athlon X4           | 5         | 0.07%   |
| AMD A12                 | 5         | 0.07%   |
| Intel Pentium D         | 4         | 0.06%   |
| Intel Core M            | 4         | 0.06%   |
| Intel Core 2 Extreme    | 4         | 0.06%   |
| Intel Celeron Dual-Core | 4         | 0.06%   |
| AMD C-60                | 4         | 0.06%   |
| AMD Ryzen 3 PRO         | 3         | 0.04%   |
| AMD Phenom II X3        | 3         | 0.04%   |
| AMD Phenom II X2        | 3         | 0.04%   |
| AMD Opteron             | 3         | 0.04%   |
| AMD Athlon X2           | 3         | 0.04%   |
| AMD Athlon II X3        | 3         | 0.04%   |
| AMD Athlon 64           | 3         | 0.04%   |
| Intel Pentium 4         | 2         | 0.03%   |
| AMD V120                | 2         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2669      | 37.76%  |
| 2       | 2312      | 32.71%  |
| 6       | 1000      | 14.15%  |
| 8       | 717       | 10.14%  |
| 12      | 137       | 1.94%   |
| 16      | 59        | 0.83%   |
| 1       | 49        | 0.69%   |
| 3       | 43        | 0.61%   |
| 10      | 32        | 0.45%   |
| 32      | 16        | 0.23%   |
| 24      | 15        | 0.21%   |
| 14      | 9         | 0.13%   |
| 64      | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 28      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7012      | 99.36%  |
| 2       | 42        | 0.6%    |
| Unknown | 3         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5313      | 75.19%  |
| 1       | 1750      | 24.77%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7034      | 99.67%  |
| 64-bit         | 12        | 0.17%   |
| Unknown        | 11        | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4648      | 64.31%  |
| 0x906ea    | 177       | 2.45%   |
| 0x306a9    | 150       | 2.08%   |
| 0x206a7    | 136       | 1.88%   |
| 0x306c3    | 127       | 1.76%   |
| 0x806ec    | 106       | 1.47%   |
| 0x806ea    | 106       | 1.47%   |
| 0x08701021 | 90        | 1.25%   |
| 0x406e3    | 85        | 1.18%   |
| 0x906e9    | 83        | 1.15%   |
| 0x40651    | 79        | 1.09%   |
| 0x806c1    | 78        | 1.08%   |
| 0x806e9    | 72        | 1%      |
| 0x08701013 | 72        | 1%      |
| 0x506e3    | 70        | 0.97%   |
| 0x0800820d | 69        | 0.95%   |
| 0xa0652    | 58        | 0.8%    |
| 0x1067a    | 56        | 0.77%   |
| 0x08108109 | 44        | 0.61%   |
| 0x08108102 | 44        | 0.61%   |
| 0x906ed    | 40        | 0.55%   |
| 0x306d4    | 38        | 0.53%   |
| 0x806eb    | 34        | 0.47%   |
| 0x0a50000c | 34        | 0.47%   |
| 0x08600106 | 32        | 0.44%   |
| 0x20655    | 29        | 0.4%    |
| 0x08001138 | 27        | 0.37%   |
| 0x406c4    | 26        | 0.36%   |
| 0x0810100b | 25        | 0.35%   |
| 0x806d1    | 23        | 0.32%   |
| 0x706e5    | 23        | 0.32%   |
| 0x06000852 | 23        | 0.32%   |
| 0x08600104 | 19        | 0.26%   |
| 0x06006705 | 19        | 0.26%   |
| 0x06001119 | 19        | 0.26%   |
| 0x706a1    | 17        | 0.24%   |
| 0x08600103 | 16        | 0.22%   |
| 0x906ec    | 15        | 0.21%   |
| 0x10676    | 15        | 0.21%   |
| 0x08608103 | 15        | 0.21%   |
| 0x0a201016 | 14        | 0.19%   |
| 0x0a201009 | 13        | 0.18%   |
| 0x08600102 | 13        | 0.18%   |
| 0x08301039 | 13        | 0.18%   |
| 0xa0655    | 12        | 0.17%   |
| 0x6fd      | 12        | 0.17%   |
| 0x106e5    | 12        | 0.17%   |
| 0x010000c8 | 12        | 0.17%   |
| 0x6fb      | 11        | 0.15%   |
| 0x40661    | 11        | 0.15%   |
| 0xa0660    | 10        | 0.14%   |
| 0x08001137 | 10        | 0.14%   |
| 0x07030105 | 10        | 0.14%   |
| 0x306f2    | 9         | 0.12%   |
| 0x30678    | 9         | 0.12%   |
| 0x206c2    | 9         | 0.12%   |
| 0x106a5    | 9         | 0.12%   |
| 0x0600611a | 9         | 0.12%   |
| 0x05000119 | 9         | 0.12%   |
| 0xa0653    | 8         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1345      | 19.03%  |
| Haswell          | 678       | 9.59%   |
| Zen 2            | 596       | 8.43%   |
| IvyBridge        | 508       | 7.19%   |
| SandyBridge      | 506       | 7.16%   |
| Skylake          | 409       | 5.79%   |
| Zen+             | 392       | 5.55%   |
| Penryn           | 273       | 3.86%   |
| Zen 3            | 250       | 3.54%   |
| CometLake        | 239       | 3.38%   |
| Zen              | 197       | 2.79%   |
| Westmere         | 177       | 2.5%    |
| TigerLake        | 172       | 2.43%   |
| Unknown          | 154       | 2.18%   |
| Broadwell        | 149       | 2.11%   |
| Piledriver       | 148       | 2.09%   |
| Silvermont       | 128       | 1.81%   |
| Core             | 127       | 1.8%    |
| K10              | 101       | 1.43%   |
| Nehalem          | 80        | 1.13%   |
| IceLake          | 80        | 1.13%   |
| Excavator        | 75        | 1.06%   |
| Goldmont plus    | 52        | 0.74%   |
| Puma             | 38        | 0.54%   |
| Steamroller      | 32        | 0.45%   |
| Goldmont         | 29        | 0.41%   |
| K8 Hammer        | 28        | 0.4%    |
| Bobcat           | 26        | 0.37%   |
| K10 Llano        | 22        | 0.31%   |
| Jaguar           | 18        | 0.25%   |
| Bulldozer        | 13        | 0.18%   |
| NetBurst         | 7         | 0.1%    |
| K8 & K10 hybrid  | 7         | 0.1%    |
| Bonnell          | 6         | 0.08%   |
| Alderlake Hybrid | 5         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3690      | 42.98%  |
| Nvidia                           | 2899      | 33.77%  |
| AMD                              | 1972      | 22.97%  |
| Matrox Electronics Systems       | 12        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.09%   |
| ASPEED Technology                | 3         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 350       | 3.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 280       | 3.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 271       | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 227       | 2.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 223       | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 216       | 2.45%   |
| Intel UHD Graphics 620                                                                   | 188       | 2.13%   |
| AMD Renoir                                                                               | 168       | 1.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 164       | 1.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 156       | 1.77%   |
| Intel HD Graphics 620                                                                    | 138       | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 136       | 1.54%   |
| Intel HD Graphics 630                                                                    | 130       | 1.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 127       | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 125       | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 114       | 1.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 109       | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 103       | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.15%   |
| AMD Cezanne                                                                              | 101       | 1.15%   |
| Intel HD Graphics 5500                                                                   | 100       | 1.13%   |
| Intel HD Graphics 530                                                                    | 98        | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 96        | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 92        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 87        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 75        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 74        | 0.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 73        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 69        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 68        | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 61        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 58        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 57        | 0.65%   |
| AMD Lucienne                                                                             | 57        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 55        | 0.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 54        | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 50        | 0.57%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 50        | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 50        | 0.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 50        | 0.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 47        | 0.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 45        | 0.51%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 45        | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 45        | 0.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 44        | 0.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 43        | 0.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 41        | 0.47%   |
| Nvidia TU117M                                                                            | 40        | 0.45%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 40        | 0.45%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 38        | 0.43%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 37        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 36        | 0.41%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 36        | 0.41%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 35        | 0.4%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 35        | 0.4%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 34        | 0.39%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.37%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 33        | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2396      | 33.62%  |
| 1 x Nvidia              | 1638      | 22.98%  |
| 1 x AMD                 | 1514      | 21.24%  |
| Intel + Nvidia          | 1034      | 14.51%  |
| Intel + AMD             | 179       | 2.51%   |
| AMD + Nvidia            | 166       | 2.33%   |
| 2 x AMD                 | 115       | 1.61%   |
| 2 x Nvidia              | 39        | 0.55%   |
| Other                   | 16        | 0.22%   |
| 1 x SiS                 | 8         | 0.11%   |
| 1 x Matrox              | 6         | 0.08%   |
| Nvidia + Matrox         | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| AMD + Matrox            | 2         | 0.03%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Intel + 2 x Nvidia      | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4483      | 62.84%  |
| Proprietary | 2329      | 32.65%  |
| Unknown     | 322       | 4.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4535      | 63.06%  |
| 1.01-2.0   | 594       | 8.26%   |
| 3.01-4.0   | 565       | 7.86%   |
| 7.01-8.0   | 506       | 7.04%   |
| 5.01-6.0   | 386       | 5.37%   |
| 0.01-0.5   | 213       | 2.96%   |
| 0.51-1.0   | 170       | 2.36%   |
| 8.01-16.0  | 123       | 1.71%   |
| 2.01-3.0   | 78        | 1.08%   |
| 16.01-24.0 | 17        | 0.24%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 985       | 12.35%  |
| AU Optronics            | 840       | 10.53%  |
| LG Display              | 692       | 8.68%   |
| Chimei Innolux          | 678       | 8.5%    |
| BOE                     | 586       | 7.35%   |
| Goldstar                | 519       | 6.51%   |
| Dell                    | 506       | 6.35%   |
| Acer                    | 333       | 4.18%   |
| Hewlett-Packard         | 248       | 3.11%   |
| AOC                     | 233       | 2.92%   |
| Apple                   | 223       | 2.8%    |
| Ancor Communications    | 190       | 2.38%   |
| Sharp                   | 188       | 2.36%   |
| BenQ                    | 187       | 2.35%   |
| Philips                 | 129       | 1.62%   |
| ASUSTek Computer        | 115       | 1.44%   |
| Lenovo                  | 111       | 1.39%   |
| PANDA                   | 108       | 1.35%   |
| ViewSonic               | 78        | 0.98%   |
| Chi Mei Optoelectronics | 75        | 0.94%   |
| Iiyama                  | 60        | 0.75%   |
| Sony                    | 58        | 0.73%   |
| Sceptre Tech            | 42        | 0.53%   |
| InfoVision              | 41        | 0.51%   |
| MSI                     | 40        | 0.5%    |
| Vizio                   | 37        | 0.46%   |
| Panasonic               | 34        | 0.43%   |
| Toshiba                 | 29        | 0.36%   |
| Unknown                 | 21        | 0.26%   |
| Gigabyte Technology     | 21        | 0.26%   |
| Insignia                | 17        | 0.21%   |
| Eizo                    | 17        | 0.21%   |
| CSO                     | 17        | 0.21%   |
| Fujitsu Siemens         | 16        | 0.2%    |
| MStar                   | 15        | 0.19%   |
| LG Electronics          | 15        | 0.19%   |
| Hitachi                 | 15        | 0.19%   |
| NEC Computers           | 14        | 0.18%   |
| Vestel Elektronik       | 13        | 0.16%   |
| LG Philips              | 13        | 0.16%   |
| HannStar                | 13        | 0.16%   |
| InnoLux Display         | 11        | 0.14%   |
| ONN                     | 10        | 0.13%   |
| Viotek                  | 9         | 0.11%   |
| TMX                     | 9         | 0.11%   |
| RTK                     | 9         | 0.11%   |
| MiTAC                   | 9         | 0.11%   |
| Mi                      | 9         | 0.11%   |
| Videoseven              | 8         | 0.1%    |
| Pixio                   | 8         | 0.1%    |
| CVT                     | 8         | 0.1%    |
| SGT                     | 7         | 0.09%   |
| Seiki                   | 7         | 0.09%   |
| Medion                  | 7         | 0.09%   |
| JDI                     | 7         | 0.09%   |
| ___                     | 6         | 0.08%   |
| Westinghouse            | 6         | 0.08%   |
| Unknown (XXX)           | 6         | 0.08%   |
| Wacom                   | 5         | 0.06%   |
| Valve                   | 5         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 60        | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 51        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 49        | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 39        | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 37        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 35        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 31        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 29        | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 28        | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 28        | 0.34%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 24        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 24        | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 24        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 24        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 22        | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 21        | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 21        | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 20        | 0.24%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 20        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 20        | 0.24%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 19        | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 19        | 0.23%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                        | 19        | 0.23%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 17        | 0.21%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                  | 16        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 16        | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 15        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 15        | 0.18%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 14        | 0.17%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 14        | 0.17%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 14        | 0.17%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                   | 14        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                  | 14        | 0.17%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                     | 14        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 14        | 0.17%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 14        | 0.17%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 14        | 0.17%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                          | 14        | 0.17%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                         | 14        | 0.17%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch     | 13        | 0.16%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 13        | 0.16%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 13        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 13        | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 12        | 0.15%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 12        | 0.15%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                            | 12        | 0.15%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 12        | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 12        | 0.15%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 12        | 0.15%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 12        | 0.15%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 11        | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3547      | 47.17%  |
| 1366x768 (WXGA)    | 1232      | 16.39%  |
| 3840x2160 (4K)     | 631       | 8.39%   |
| 2560x1440 (QHD)    | 441       | 5.87%   |
| 1600x900 (HD+)     | 255       | 3.39%   |
| 1680x1050 (WSXGA+) | 160       | 2.13%   |
| 1440x900 (WXGA+)   | 150       | 1.99%   |
| 1920x1200 (WUXGA)  | 148       | 1.97%   |
| 2560x1080          | 139       | 1.85%   |
| 1280x1024 (SXGA)   | 133       | 1.77%   |
| 3440x1440          | 127       | 1.69%   |
| 1280x800 (WXGA)    | 108       | 1.44%   |
| 1360x768           | 53        | 0.7%    |
| 2560x1600          | 52        | 0.69%   |
| 2880x1800          | 37        | 0.49%   |
| 1920x540           | 36        | 0.48%   |
| 3840x1080          | 33        | 0.44%   |
| Unknown            | 29        | 0.39%   |
| 3840x2400          | 25        | 0.33%   |
| 2160x1440          | 24        | 0.32%   |
| 3200x1800 (QHD+)   | 15        | 0.2%    |
| 2736x1824          | 15        | 0.2%    |
| 3840x1600          | 12        | 0.16%   |
| 3000x2000          | 12        | 0.16%   |
| 1024x768 (XGA)     | 12        | 0.16%   |
| 2256x1504          | 10        | 0.13%   |
| 1280x720 (HD)      | 10        | 0.13%   |
| 1600x1200          | 9         | 0.12%   |
| 2048x1152          | 5         | 0.07%   |
| 3840x1200          | 4         | 0.05%   |
| 3456x2160          | 3         | 0.04%   |
| 3200x2000          | 3         | 0.04%   |
| 2288x1287          | 3         | 0.04%   |
| 1920x1280          | 3         | 0.04%   |
| 7680x2160          | 2         | 0.03%   |
| 5120x1440          | 2         | 0.03%   |
| 4480x1440          | 2         | 0.03%   |
| 3840x1100          | 2         | 0.03%   |
| 3072x1920          | 2         | 0.03%   |
| 2880x1920          | 2         | 0.03%   |
| 2560x1700          | 2         | 0.03%   |
| 1680x945           | 2         | 0.03%   |
| 1024x600           | 2         | 0.03%   |
| 9840x3840          | 1         | 0.01%   |
| 8320x2160          | 1         | 0.01%   |
| 8160x4627          | 1         | 0.01%   |
| 6400x1440          | 1         | 0.01%   |
| 5280x1080          | 1         | 0.01%   |
| 5200x2160          | 1         | 0.01%   |
| 5120x1080          | 1         | 0.01%   |
| 4096x2160          | 1         | 0.01%   |
| 4080x2030          | 1         | 0.01%   |
| 4080x2026          | 1         | 0.01%   |
| 3360x1080          | 1         | 0.01%   |
| 3280x2048          | 1         | 0.01%   |
| 3280x1080          | 1         | 0.01%   |
| 3040x900           | 1         | 0.01%   |
| 2960x1050          | 1         | 0.01%   |
| 2720x1024          | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2007      | 25.26%  |
| 13      | 748       | 9.41%   |
| 27      | 732       | 9.21%   |
| 24      | 617       | 7.76%   |
| 14      | 537       | 6.76%   |
| 23      | 509       | 6.41%   |
| 21      | 430       | 5.41%   |
| 17      | 407       | 5.12%   |
| 31      | 251       | 3.16%   |
| 34      | 222       | 2.79%   |
| 19      | 153       | 1.93%   |
| Unknown | 143       | 1.8%    |
| 18      | 135       | 1.7%    |
| 12      | 122       | 1.54%   |
| 22      | 108       | 1.36%   |
| 20      | 99        | 1.25%   |
| 84      | 82        | 1.03%   |
| 11      | 72        | 0.91%   |
| 32      | 66        | 0.83%   |
| 72      | 60        | 0.76%   |
| 16      | 42        | 0.53%   |
| 54      | 39        | 0.49%   |
| 26      | 35        | 0.44%   |
| 25      | 33        | 0.42%   |
| 48      | 27        | 0.34%   |
| 40      | 27        | 0.34%   |
| 49      | 22        | 0.28%   |
| 52      | 21        | 0.26%   |
| 35      | 20        | 0.25%   |
| 65      | 19        | 0.24%   |
| 46      | 18        | 0.23%   |
| 28      | 16        | 0.2%    |
| 37      | 13        | 0.16%   |
| 29      | 13        | 0.16%   |
| 33      | 11        | 0.14%   |
| 47      | 9         | 0.11%   |
| 43      | 9         | 0.11%   |
| 42      | 8         | 0.1%    |
| 10      | 8         | 0.1%    |
| 39      | 7         | 0.09%   |
| 74      | 6         | 0.08%   |
| 55      | 5         | 0.06%   |
| 36      | 5         | 0.06%   |
| 69      | 4         | 0.05%   |
| 41      | 4         | 0.05%   |
| 64      | 3         | 0.04%   |
| 57      | 3         | 0.04%   |
| 50      | 3         | 0.04%   |
| 38      | 3         | 0.04%   |
| 60      | 2         | 0.03%   |
| 59      | 2         | 0.03%   |
| 44      | 2         | 0.03%   |
| 30      | 2         | 0.03%   |
| 142     | 1         | 0.01%   |
| 99      | 1         | 0.01%   |
| 86      | 1         | 0.01%   |
| 63      | 1         | 0.01%   |
| 8       | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2936      | 37.73%  |
| 501-600        | 1681      | 21.6%   |
| 401-500        | 837       | 10.76%  |
| 201-300        | 576       | 7.4%    |
| 351-400        | 507       | 6.52%   |
| 601-700        | 379       | 4.87%   |
| 701-800        | 298       | 3.83%   |
| 1001-1500      | 175       | 2.25%   |
| 1501-2000      | 152       | 1.95%   |
| Unknown        | 143       | 1.84%   |
| 801-900        | 72        | 0.93%   |
| 901-1000       | 22        | 0.28%   |
| More than 2000 | 2         | 0.03%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5600      | 80.23%  |
| 16/10   | 729       | 10.44%  |
| 21/9    | 268       | 3.84%   |
| 5/4     | 129       | 1.85%   |
| Unknown | 87        | 1.25%   |
| 3/2     | 74        | 1.06%   |
| 4/3     | 37        | 0.53%   |
| 32/9    | 35        | 0.5%    |
| 6/5     | 8         | 0.11%   |
| 1.96    | 5         | 0.07%   |
| 3.20    | 3         | 0.04%   |
| 3.40    | 2         | 0.03%   |
| 3.73    | 1         | 0.01%   |
| 1.00    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2011      | 25.6%   |
| 201-250        | 1311      | 16.69%  |
| 81-90          | 1014      | 12.91%  |
| 301-350        | 753       | 9.59%   |
| 351-500        | 570       | 7.26%   |
| 151-200        | 389       | 4.95%   |
| 121-130        | 330       | 4.2%    |
| 71-80          | 281       | 3.58%   |
| More than 1000 | 265       | 3.37%   |
| 251-300        | 234       | 2.98%   |
| 141-150        | 165       | 2.1%    |
| Unknown        | 143       | 1.82%   |
| 501-1000       | 140       | 1.78%   |
| 61-70          | 105       | 1.34%   |
| 51-60          | 74        | 0.94%   |
| 111-120        | 27        | 0.34%   |
| 131-140        | 22        | 0.28%   |
| 91-100         | 11        | 0.14%   |
| 41-50          | 8         | 0.1%    |
| 1-40           | 1         | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2428      | 32.09%  |
| 121-160       | 2162      | 28.58%  |
| 101-120       | 1953      | 25.81%  |
| 161-240       | 423       | 5.59%   |
| More than 240 | 231       | 3.05%   |
| 1-50          | 226       | 2.99%   |
| Unknown       | 143       | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5388      | 74.64%  |
| 2     | 1306      | 18.09%  |
| 0     | 371       | 5.14%   |
| 3     | 141       | 1.95%   |
| 4     | 11        | 0.15%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3855      | 35.32%  |
| Intel                                  | 3601      | 32.99%  |
| Qualcomm Atheros                       | 1211      | 11.09%  |
| Broadcom                               | 650       | 5.95%   |
| Broadcom Limited                       | 141       | 1.29%   |
| Ralink Technology                      | 127       | 1.16%   |
| TP-Link                                | 124       | 1.14%   |
| Marvell Technology Group               | 111       | 1.02%   |
| Nvidia                                 | 99        | 0.91%   |
| MediaTek                               | 89        | 0.82%   |
| Ralink                                 | 88        | 0.81%   |
| Microsoft                              | 67        | 0.61%   |
| Samsung Electronics                    | 65        | 0.6%    |
| ASIX Electronics                       | 46        | 0.42%   |
| NetGear                                | 38        | 0.35%   |
| Qualcomm Atheros Communications        | 36        | 0.33%   |
| Xiaomi                                 | 34        | 0.31%   |
| Google                                 | 30        | 0.27%   |
| DisplayLink                            | 29        | 0.27%   |
| Aquantia                               | 29        | 0.27%   |
| ASUSTek Computer                       | 27        | 0.25%   |
| InterBiometrics                        | 26        | 0.24%   |
| Huawei Technologies                    | 25        | 0.23%   |
| Dell                                   | 24        | 0.22%   |
| D-Link                                 | 23        | 0.21%   |
| Lenovo                                 | 21        | 0.19%   |
| Ericsson Business Mobile Networks      | 19        | 0.17%   |
| Sierra Wireless                        | 17        | 0.16%   |
| Linksys                                | 17        | 0.16%   |
| Qualcomm                               | 15        | 0.14%   |
| OnePlus Technology (Shenzhen)          | 15        | 0.14%   |
| JMicron Technology                     | 15        | 0.14%   |
| Motorola PCS                           | 14        | 0.13%   |
| Edimax Technology                      | 14        | 0.13%   |
| Hewlett-Packard                        | 11        | 0.1%    |
| OPPO Electronics                       | 10        | 0.09%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.08%   |
| D-Link System                          | 9         | 0.08%   |
| Belkin Components                      | 9         | 0.08%   |
| AVM                                    | 7         | 0.06%   |
| Sitecom Europe                         | 6         | 0.05%   |
| Apple                                  | 6         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 6         | 0.05%   |
| ICS Advent                             | 5         | 0.05%   |
| Gemtek                                 | 5         | 0.05%   |
| Fibocom                                | 5         | 0.05%   |
| VIA Technologies                       | 4         | 0.04%   |
| Microchip Technology                   | 4         | 0.04%   |
| Mercucys                               | 4         | 0.04%   |
| Mellanox Technologies                  | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| IMC Networks                           | 3         | 0.03%   |
| Arduino SA                             | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.02%   |
| Wilocity                               | 2         | 0.02%   |
| T & A Mobile Phones                    | 2         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.02%   |
| Prolific Technology                    | 2         | 0.02%   |
| Ovislink                               | 2         | 0.02%   |
| Micro Star International               | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2714      | 21.23%  |
| Intel Wi-Fi 6 AX200                                               | 540       | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 405       | 3.17%   |
| Intel I211 Gigabit Network Connection                             | 338       | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 259       | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 227       | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 208       | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 197       | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 181       | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 171       | 1.34%   |
| Intel Wireless 7265                                               | 163       | 1.28%   |
| Intel Wireless 7260                                               | 159       | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 155       | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 152       | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 139       | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 135       | 1.06%   |
| Intel Wireless-AC 9260                                            | 131       | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 131       | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 131       | 1.02%   |
| Intel Wireless 8260                                               | 130       | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 120       | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 119       | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 114       | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 101       | 0.79%   |
| Intel Ethernet Connection I217-LM                                 | 100       | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 99        | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 95        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 94        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 91        | 0.71%   |
| Intel Wireless 3165                                               | 90        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 76        | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 72        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 71        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 64        | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 63        | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 63        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 63        | 0.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 63        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 60        | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 59        | 0.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 59        | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 58        | 0.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 58        | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 57        | 0.45%   |
| Realtek 802.11ac NIC                                              | 54        | 0.42%   |
| Intel Wireless 3160                                               | 52        | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 50        | 0.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 49        | 0.38%   |
| Intel Ethernet Connection I218-LM                                 | 48        | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.38%   |
| Ralink MT7601U Wireless Adapter                                   | 47        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 47        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 46        | 0.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 46        | 0.36%   |
| Intel Ethernet Connection I219-LM                                 | 46        | 0.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 45        | 0.35%   |
| Nvidia MCP79 Ethernet                                             | 43        | 0.34%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 42        | 0.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 42        | 0.33%   |
| Intel Ethernet Connection I217-V                                  | 41        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2804      | 46.77%  |
| Qualcomm Atheros                      | 936       | 15.61%  |
| Realtek Semiconductor                 | 891       | 14.86%  |
| Broadcom                              | 493       | 8.22%   |
| Ralink Technology                     | 127       | 2.12%   |
| TP-Link                               | 115       | 1.92%   |
| Broadcom Limited                      | 109       | 1.82%   |
| Ralink                                | 88        | 1.47%   |
| MediaTek                              | 80        | 1.33%   |
| Microsoft                             | 62        | 1.03%   |
| Qualcomm Atheros Communications       | 36        | 0.6%    |
| NetGear                               | 36        | 0.6%    |
| Marvell Technology Group              | 30        | 0.5%    |
| ASUSTek Computer                      | 25        | 0.42%   |
| D-Link                                | 23        | 0.38%   |
| Dell                                  | 21        | 0.35%   |
| Sierra Wireless                       | 17        | 0.28%   |
| Edimax Technology                     | 14        | 0.23%   |
| Linksys                               | 13        | 0.22%   |
| Qualcomm                              | 9         | 0.15%   |
| Belkin Components                     | 9         | 0.15%   |
| AVM                                   | 7         | 0.12%   |
| Sitecom Europe                        | 6         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6         | 0.1%    |
| Gemtek                                | 5         | 0.08%   |
| D-Link System                         | 5         | 0.08%   |
| Mercucys                              | 4         | 0.07%   |
| IMC Networks                          | 3         | 0.05%   |
| Hewlett-Packard                       | 3         | 0.05%   |
| Wilocity                              | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Ovislink                              | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Accton Technology                     | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fibocom                               | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 540       | 8.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 227       | 3.76%   |
| Intel Wireless 8265 / 8275                                     | 208       | 3.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 181       | 3%      |
| Intel Wireless 7265                                            | 163       | 2.7%    |
| Intel Wireless 7260                                            | 159       | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 155       | 2.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 152       | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 139       | 2.3%    |
| Intel Wireless-AC 9260                                         | 131       | 2.17%   |
| Intel Wi-Fi 6 AX201                                            | 131       | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 131       | 2.17%   |
| Intel Wireless 8260                                            | 130       | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 120       | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 119       | 1.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 114       | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 101       | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 95        | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 94        | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 91        | 1.51%   |
| Intel Wireless 3165                                            | 90        | 1.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 72        | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                  | 71        | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 63        | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 63        | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 63        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 59        | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 59        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 58        | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 58        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 57        | 0.94%   |
| Realtek 802.11ac NIC                                           | 54        | 0.89%   |
| Intel Wireless 3160                                            | 52        | 0.86%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 49        | 0.81%   |
| Ralink MT7601U Wireless Adapter                                | 47        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 46        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 42        | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 42        | 0.7%    |
| Intel Centrino Ultimate-N 6300                                 | 41        | 0.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 40        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 36        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 35        | 0.58%   |
| Intel Centrino Advanced-N 6235                                 | 35        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 34        | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 32        | 0.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 31        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 30        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                | 30        | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 30        | 0.5%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 30        | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 29        | 0.48%   |
| Intel Centrino Wireless-N 2230                                 | 29        | 0.48%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 29        | 0.48%   |
| Microsoft XBOX ACC                                             | 28        | 0.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 28        | 0.46%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 26        | 0.43%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25        | 0.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 25        | 0.41%   |
| Ralink RT5370 Wireless Adapter                                 | 24        | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3510      | 53.83%  |
| Intel                            | 1725      | 26.46%  |
| Qualcomm Atheros                 | 378       | 5.8%    |
| Broadcom                         | 273       | 4.19%   |
| Nvidia                           | 99        | 1.52%   |
| Marvell Technology Group         | 81        | 1.24%   |
| Samsung Electronics              | 63        | 0.97%   |
| ASIX Electronics                 | 46        | 0.71%   |
| Broadcom Limited                 | 36        | 0.55%   |
| Xiaomi                           | 34        | 0.52%   |
| Google                           | 30        | 0.46%   |
| DisplayLink                      | 29        | 0.44%   |
| Aquantia                         | 29        | 0.44%   |
| Huawei Technologies              | 23        | 0.35%   |
| Lenovo                           | 20        | 0.31%   |
| JMicron Technology               | 15        | 0.23%   |
| OnePlus Technology (Shenzhen)    | 12        | 0.18%   |
| OPPO Electronics                 | 10        | 0.15%   |
| Motorola PCS                     | 10        | 0.15%   |
| TP-Link                          | 9         | 0.14%   |
| Silicon Integrated Systems [SiS] | 9         | 0.14%   |
| MediaTek                         | 8         | 0.12%   |
| Qualcomm                         | 6         | 0.09%   |
| Microsoft                        | 5         | 0.08%   |
| ICS Advent                       | 5         | 0.08%   |
| VIA Technologies                 | 4         | 0.06%   |
| Linksys                          | 4         | 0.06%   |
| Fibocom                          | 4         | 0.06%   |
| D-Link System                    | 4         | 0.06%   |
| Apple                            | 4         | 0.06%   |
| LG Electronics                   | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| NetGear                          | 2         | 0.03%   |
| Mellanox Technologies            | 2         | 0.03%   |
| LSI                              | 2         | 0.03%   |
| Hewlett-Packard                  | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| 3Com                             | 2         | 0.03%   |
| Unknown                          | 1         | 0.02%   |
| Tehuti Networks                  | 1         | 0.02%   |
| Solarflare Communications        | 1         | 0.02%   |
| Research In Motion               | 1         | 0.02%   |
| QLogic                           | 1         | 0.02%   |
| NTmore                           | 1         | 0.02%   |
| Netchip Technology               | 1         | 0.02%   |
| Microchip Technology             | 1         | 0.02%   |
| IBM                              | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |
| Hangzhou Silan Microelectronics  | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |
| Emulex                           | 1         | 0.02%   |
| Cypress Semiconductor            | 1         | 0.02%   |
| Corega K.K.                      | 1         | 0.02%   |
| Attansic Technology              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2714      | 40.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 405       | 6.1%    |
| Intel I211 Gigabit Network Connection                             | 338       | 5.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 259       | 3.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 197       | 2.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 171       | 2.58%   |
| Intel Ethernet Connection (2) I219-V                              | 135       | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 100       | 1.51%   |
| Intel Ethernet Connection (7) I219-V                              | 99        | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 76        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 64        | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 63        | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 60        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 50        | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 48        | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 47        | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 46        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 46        | 0.69%   |
| Nvidia MCP79 Ethernet                                             | 43        | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 41        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 41        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 40        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 37        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 35        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 33        | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 33        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 32        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 31        | 0.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 31        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 31        | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 29        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 29        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 28        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 27        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 25        | 0.38%   |
| Google Nexus/Pixel Device (tether)                                | 25        | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 24        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 0.33%   |
| Intel Ethernet Connection (10) I219-V                             | 20        | 0.3%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 20        | 0.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 19        | 0.29%   |
| Huawei LYA-L09                                                    | 19        | 0.29%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 18        | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 17        | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 16        | 0.24%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 0.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.23%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.23%   |
| Intel 82567LM Gigabit Network Connection                          | 15        | 0.23%   |
| Realtek Killer E3000 2.5GbE Controller                            | 14        | 0.21%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 14        | 0.21%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 13        | 0.2%    |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12        | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6080      | 51.35%  |
| WiFi     | 5659      | 47.8%   |
| Modem    | 80        | 0.68%   |
| Unknown  | 21        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4373      | 58.56%  |
| Ethernet | 3091      | 41.39%  |
| Unknown  | 4         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3946      | 55.73%  |
| 1     | 2837      | 40.07%  |
| 3     | 168       | 2.37%   |
| 0     | 92        | 1.3%    |
| 4     | 28        | 0.4%    |
| 5     | 5         | 0.07%   |
| 10    | 2         | 0.03%   |
| 6     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5801      | 81.1%   |
| Yes  | 1352      | 18.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2410      | 51.1%   |
| Qualcomm Atheros Communications | 388       | 8.23%   |
| Realtek Semiconductor           | 354       | 7.51%   |
| Apple                           | 272       | 5.77%   |
| Cambridge Silicon Radio         | 271       | 5.75%   |
| Broadcom                        | 231       | 4.9%    |
| IMC Networks                    | 182       | 3.86%   |
| Lite-On Technology              | 166       | 3.52%   |
| Foxconn / Hon Hai               | 100       | 2.12%   |
| ASUSTek Computer                | 88        | 1.87%   |
| Dell                            | 56        | 1.19%   |
| Marvell Semiconductor           | 32        | 0.68%   |
| Ralink                          | 29        | 0.61%   |
| Hewlett-Packard                 | 26        | 0.55%   |
| Toshiba                         | 25        | 0.53%   |
| Realtek                         | 24        | 0.51%   |
| Foxconn International           | 9         | 0.19%   |
| Ralink Technology               | 7         | 0.15%   |
| Alps Electric                   | 7         | 0.15%   |
| TP-Link                         | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| Qcom                            | 3         | 0.06%   |
| HTC (High Tech Computer)        | 3         | 0.06%   |
| Dynex                           | 3         | 0.06%   |
| Creative Technology             | 3         | 0.06%   |
| USI                             | 2         | 0.04%   |
| Unknown                         | 2         | 0.04%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Opticis                         | 2         | 0.04%   |
| MediaTek                        | 2         | 0.04%   |
| Integrated System Solution      | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Primax Electronics              | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 776       | 16.44%  |
| Intel AX200 Bluetooth                               | 517       | 10.95%  |
| Intel AX201 Bluetooth                               | 375       | 7.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 357       | 7.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 271       | 5.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 260       | 5.51%   |
| Realtek Bluetooth Radio                             | 210       | 4.45%   |
| Intel Bluetooth Device                              | 164       | 3.47%   |
| Apple Bluetooth Host Controller                     | 116       | 2.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 113       | 2.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 97        | 2.06%   |
| Apple Bluetooth USB Host Controller                 | 96        | 2.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 68        | 1.44%   |
| IMC Networks Bluetooth Radio                        | 62        | 1.31%   |
| Intel AX210 Bluetooth                               | 57        | 1.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 55        | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 48        | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 48        | 1.02%   |
| IMC Networks Bluetooth Device                       | 43        | 0.91%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 41        | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 0.85%   |
| Lite-On Bluetooth Device                            | 40        | 0.85%   |
| IMC Networks Wireless_Device                        | 39        | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 33        | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 0.68%   |
| Ralink RT3290 Bluetooth                             | 29        | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 29        | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 27        | 0.57%   |
| Apple Bluetooth HCI                                 | 27        | 0.57%   |
| Realtek Bluetooth Radio                             | 24        | 0.51%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite        | 20        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.4%    |
| ASUS Bluetooth Radio                                | 19        | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 17        | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 17        | 0.36%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.34%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.32%   |
| Foxconn / Hon Hai Wireless_Device                   | 15        | 0.32%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.32%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 15        | 0.32%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 12        | 0.25%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 12        | 0.25%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.25%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.25%   |
| Broadcom HP Portable Bumble Bee                     | 12        | 0.25%   |
| Dell Wireless 365 Bluetooth                         | 11        | 0.23%   |
| Broadcom BCM43142A0 Bluetooth Device                | 11        | 0.23%   |
| Lite-On Bluetooth Radio                             | 10        | 0.21%   |
| Realtek RTL8723B Bluetooth                          | 9         | 0.19%   |
| Lite-On Wireless_Device                             | 9         | 0.19%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 9         | 0.19%   |
| IMC Networks BCM20702A0                             | 9         | 0.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.19%   |
| Foxconn International BCM43142A0 Bluetooth module   | 9         | 0.19%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 9         | 0.19%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.19%   |
| Broadcom BCM20702A0                                 | 9         | 0.19%   |
| Broadcom BCM2070 Bluetooth Device                   | 9         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 4821      | 44.93%  |
| AMD                                             | 2346      | 21.87%  |
| Nvidia                                          | 2294      | 21.38%  |
| C-Media Electronics                             | 193       | 1.8%    |
| Logitech                                        | 105       | 0.98%   |
| JMTek                                           | 57        | 0.53%   |
| Creative Labs                                   | 56        | 0.52%   |
| Corsair                                         | 52        | 0.48%   |
| Kingston Technology                             | 50        | 0.47%   |
| Texas Instruments                               | 47        | 0.44%   |
| Realtek Semiconductor                           | 43        | 0.4%    |
| Razer USA                                       | 43        | 0.4%    |
| SteelSeries ApS                                 | 40        | 0.37%   |
| Focusrite-Novation                              | 30        | 0.28%   |
| GN Netcom                                       | 26        | 0.24%   |
| Creative Technology                             | 26        | 0.24%   |
| Blue Microphones                                | 22        | 0.21%   |
| ASUSTek Computer                                | 21        | 0.2%    |
| Generalplus Technology                          | 20        | 0.19%   |
| Sony                                            | 19        | 0.18%   |
| Lenovo                                          | 19        | 0.18%   |
| Sennheiser Communications                       | 17        | 0.16%   |
| Plantronics                                     | 17        | 0.16%   |
| Giga-Byte Technology                            | 14        | 0.13%   |
| Samson Technologies                             | 13        | 0.12%   |
| Astro Gaming                                    | 13        | 0.12%   |
| Apple                                           | 13        | 0.12%   |
| Yamaha                                          | 11        | 0.1%    |
| Turtle Beach                                    | 11        | 0.1%    |
| Tenx Technology                                 | 11        | 0.1%    |
| Silicon Integrated Systems [SiS]                | 10        | 0.09%   |
| SAVITECH                                        | 10        | 0.09%   |
| Thesycon Systemsoftware & Consulting            | 9         | 0.08%   |
| FiiO Electronics Technology                     | 9         | 0.08%   |
| Valve Software                                  | 8         | 0.07%   |
| M-Audio                                         | 8         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 8         | 0.07%   |
| Hewlett-Packard                                 | 8         | 0.07%   |
| Micro Star International                        | 7         | 0.07%   |
| Audio-Technica                                  | 7         | 0.07%   |
| Unknown                                         | 6         | 0.06%   |
| GYROCOM C&C                                     | 6         | 0.06%   |
| BEHRINGER International                         | 6         | 0.06%   |
| XMOS                                            | 5         | 0.05%   |
| VIA Technologies                                | 5         | 0.05%   |
| ROCCAT                                          | 5         | 0.05%   |
| Microsoft                                       | 5         | 0.05%   |
| AudioQuest                                      | 5         | 0.05%   |
| Dell                                            | 4         | 0.04%   |
| Conexant Systems                                | 4         | 0.04%   |
| Bose                                            | 4         | 0.04%   |
| Trust                                           | 3         | 0.03%   |
| Shure                                           | 3         | 0.03%   |
| Schiit Audio                                    | 3         | 0.03%   |
| Samsung Electronics                             | 3         | 0.03%   |
| PreSonus Audio Electronics                      | 3         | 0.03%   |
| No brand                                        | 3         | 0.03%   |
| Native Instruments                              | 3         | 0.03%   |
| Medeli Electronics                              | 3         | 0.03%   |
| Jieli Technology                                | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 662       | 5.21%   |
| AMD Starship/Matisse HD Audio Controller                                   | 544       | 4.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 538       | 4.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 482       | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 468       | 3.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 416       | 3.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 349       | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 275       | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 269       | 2.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 259       | 2.04%   |
| Intel 8 Series HD Audio Controller                                         | 229       | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 225       | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 223       | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 222       | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 220       | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 203       | 1.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 199       | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 186       | 1.46%   |
| AMD FCH Azalia Controller                                                  | 182       | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 181       | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 173       | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 172       | 1.35%   |
| Nvidia GP104 High Definition Audio Controller                              | 169       | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                              | 162       | 1.27%   |
| Intel 200 Series PCH HD Audio                                              | 157       | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 154       | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 147       | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 147       | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 146       | 1.15%   |
| Intel Broadwell-U Audio Controller                                         | 145       | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 137       | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 136       | 1.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 130       | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 118       | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 113       | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 103       | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 100       | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 92        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 82        | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 80        | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 79        | 0.62%   |
| AMD Kabini HDMI/DP Audio                                                   | 79        | 0.62%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 74        | 0.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 73        | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 73        | 0.57%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 72        | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 71        | 0.56%   |
| Nvidia GA106 High Definition Audio Controller                              | 71        | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 71        | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 67        | 0.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 67        | 0.53%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 65        | 0.51%   |
| Nvidia High Definition Audio Controller                                    | 57        | 0.45%   |
| Nvidia GK104 HDMI Audio Controller                                         | 56        | 0.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 52        | 0.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 51        | 0.4%    |
| Nvidia GM206 High Definition Audio Controller                              | 50        | 0.39%   |
| Nvidia MCP79 High Definition Audio                                         | 49        | 0.39%   |
| Nvidia GP102 HDMI Audio Controller                                         | 46        | 0.36%   |
| AMD High Definition Audio Controller                                       | 44        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 400       | 22.23%  |
| SK hynix            | 321       | 17.84%  |
| Kingston            | 203       | 11.28%  |
| Micron Technology   | 175       | 9.73%   |
| Corsair             | 132       | 7.34%   |
| Crucial             | 126       | 7%      |
| Unknown             | 97        | 5.39%   |
| G.Skill             | 87        | 4.84%   |
| A-DATA Technology   | 44        | 2.45%   |
| Smart               | 27        | 1.5%    |
| Ramaxel Technology  | 25        | 1.39%   |
| Team                | 19        | 1.06%   |
| Elpida              | 18        | 1%      |
| Neo Forza           | 15        | 0.83%   |
| Goldkey             | 15        | 0.83%   |
| Patriot             | 10        | 0.56%   |
| Unknown (ABCD)      | 9         | 0.5%    |
| Smart Brazil        | 9         | 0.5%    |
| Unknown             | 7         | 0.39%   |
| Teikon              | 6         | 0.33%   |
| Apacer              | 5         | 0.28%   |
| Nanya Technology    | 4         | 0.22%   |
| Avant               | 4         | 0.22%   |
| Silicon Power       | 3         | 0.17%   |
| High Bridge         | 3         | 0.17%   |
| GOODRAM             | 3         | 0.17%   |
| Transcend           | 2         | 0.11%   |
| Timetec             | 2         | 0.11%   |
| PNY                 | 2         | 0.11%   |
| Patriot Memory      | 2         | 0.11%   |
| OLOY                | 2         | 0.11%   |
| CSX                 | 2         | 0.11%   |
| AMD                 | 2         | 0.11%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (898F)      | 1         | 0.06%   |
| Unifosa             | 1         | 0.06%   |
| Toshiba             | 1         | 0.06%   |
| RZX                 | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Multilaser          | 1         | 0.06%   |
| Mircon              | 1         | 0.06%   |
| Micron/Elpida       | 1         | 0.06%   |
| Magnum Tech         | 1         | 0.06%   |
| Lenovo              | 1         | 0.06%   |
| HMD                 | 1         | 0.06%   |
| Hewlett-Packard     | 1         | 0.06%   |
| GSkill              | 1         | 0.06%   |
| Gold Key            | 1         | 0.06%   |
| EVGA                | 1         | 0.06%   |
| ChangXin Memory     | 1         | 0.06%   |
| ASint Technology    | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 32        | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 27        | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 24        | 1.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 19        | 1.01%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 17        | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 15        | 0.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 15        | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 15        | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 15        | 0.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 15        | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 14        | 0.74%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 13        | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 11        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 11        | 0.58%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                 | 11        | 0.58%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 10        | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 10        | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 10        | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 9         | 0.48%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 9         | 0.48%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 9         | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s    | 8         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 8         | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.42%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 8         | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.42%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 8         | 0.42%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s              | 8         | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 8         | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.37%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 7         | 0.37%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 7         | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.37%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 0.37%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s            | 7         | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 7         | 0.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 7         | 0.37%   |
| Unknown                                                             | 7         | 0.37%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 6         | 0.32%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 6         | 0.32%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 6         | 0.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 6         | 0.32%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 6         | 0.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 6         | 0.32%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 6         | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.32%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s                | 6         | 0.32%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s                | 6         | 0.32%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 6         | 0.32%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 6         | 0.32%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 6         | 0.32%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 6         | 0.32%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 6         | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 5         | 0.26%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 5         | 0.26%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 5         | 0.26%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1053      | 68.11%  |
| DDR3    | 326       | 21.09%  |
| LPDDR3  | 58        | 3.75%   |
| LPDDR4  | 56        | 3.62%   |
| Unknown | 21        | 1.36%   |
| DDR2    | 20        | 1.29%   |
| SDRAM   | 9         | 0.58%   |
| DDR     | 2         | 0.13%   |
| LPDDR5  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 943       | 60.53%  |
| DIMM         | 459       | 29.46%  |
| Row Of Chips | 144       | 9.24%   |
| Chip         | 10        | 0.64%   |
| RIMM         | 1         | 0.06%   |
| Unknown      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 773       | 46.23%  |
| 4096  | 395       | 23.62%  |
| 16384 | 320       | 19.14%  |
| 2048  | 91        | 5.44%   |
| 32768 | 75        | 4.49%   |
| 1024  | 16        | 0.96%   |
| 512   | 2         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 382       | 22.79%  |
| 3200    | 309       | 18.44%  |
| 1600    | 233       | 13.9%   |
| 2400    | 160       | 9.55%   |
| 2133    | 100       | 5.97%   |
| 3600    | 89        | 5.31%   |
| 1333    | 65        | 3.88%   |
| 1867    | 33        | 1.97%   |
| 4267    | 28        | 1.67%   |
| 3266    | 26        | 1.55%   |
| 3000    | 25        | 1.49%   |
| 3466    | 24        | 1.43%   |
| 1334    | 22        | 1.31%   |
| 8400    | 17        | 1.01%   |
| 800     | 16        | 0.95%   |
| 2933    | 13        | 0.78%   |
| 1866    | 12        | 0.72%   |
| 3400    | 11        | 0.66%   |
| 667     | 11        | 0.66%   |
| 4266    | 10        | 0.6%    |
| 3733    | 10        | 0.6%    |
| 2666    | 9         | 0.54%   |
| Unknown | 8         | 0.48%   |
| 2800    | 7         | 0.42%   |
| 1067    | 6         | 0.36%   |
| 3800    | 4         | 0.24%   |
| 1800    | 4         | 0.24%   |
| 4000    | 3         | 0.18%   |
| 3866    | 3         | 0.18%   |
| 3333    | 3         | 0.18%   |
| 1066    | 3         | 0.18%   |
| 6400    | 2         | 0.12%   |
| 4800    | 2         | 0.12%   |
| 4400    | 2         | 0.12%   |
| 3666    | 2         | 0.12%   |
| 3533    | 2         | 0.12%   |
| 3334    | 2         | 0.12%   |
| 3151    | 2         | 0.12%   |
| 3100    | 2         | 0.12%   |
| 3067    | 2         | 0.12%   |
| 49926   | 1         | 0.06%   |
| 4199    | 1         | 0.06%   |
| 3066    | 1         | 0.06%   |
| 3020    | 1         | 0.06%   |
| 2747    | 1         | 0.06%   |
| 2733    | 1         | 0.06%   |
| 2465    | 1         | 0.06%   |
| 2134    | 1         | 0.06%   |
| 2048    | 1         | 0.06%   |
| 2000    | 1         | 0.06%   |
| 1360    | 1         | 0.06%   |
| 333     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 46        | 31.72%  |
| Brother Industries    | 28        | 19.31%  |
| Canon                 | 20        | 13.79%  |
| Samsung Electronics   | 18        | 12.41%  |
| Seiko Epson           | 17        | 11.72%  |
| Dymo-CoStar           | 4         | 2.76%   |
| Fuji Xerox            | 3         | 2.07%   |
| QinHeng Electronics   | 2         | 1.38%   |
| Xerox                 | 1         | 0.69%   |
| STMicroelectronics    | 1         | 0.69%   |
| Oki Data              | 1         | 0.69%   |
| MIIIW                 | 1         | 0.69%   |
| Lexmark International | 1         | 0.69%   |
| Kyocera               | 1         | 0.69%   |
| Apple                 | 1         | 0.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                                | 5         | 3.42%   |
| Seiko Epson L4150 Series                                   | 3         | 2.05%   |
| Samsung SCX-3400 Series                                    | 3         | 2.05%   |
| Samsung ML-1640 Series Laser Printer                       | 3         | 2.05%   |
| Samsung M2020 Series                                       | 3         | 2.05%   |
| Brother Printer                                            | 3         | 2.05%   |
| Seiko Epson WF-3520 Series                                 | 2         | 1.37%   |
| Seiko Epson L395 Series                                    | 2         | 1.37%   |
| Seiko Epson L355 Series                                    | 2         | 1.37%   |
| Seiko Epson L3110 Series                                   | 2         | 1.37%   |
| Samsung M2070 Series                                       | 2         | 1.37%   |
| QinHeng CH340S                                             | 2         | 1.37%   |
| HP LaserJet Professional P 1102w                           | 2         | 1.37%   |
| HP ENVY Photo 6200 series                                  | 2         | 1.37%   |
| HP ENVY 4520 series                                        | 2         | 1.37%   |
| HP ENVY 4500 series                                        | 2         | 1.37%   |
| HP DeskJet F4100 Printer series                            | 2         | 1.37%   |
| HP Deskjet 2540 series                                     | 2         | 1.37%   |
| HP Deskjet 1000 J110 series                                | 2         | 1.37%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2         | 1.37%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2         | 1.37%   |
| Canon PIXMA MX920 Series                                   | 2         | 1.37%   |
| Brother HL-L3230CDW series                                 | 2         | 1.37%   |
| Brother HL-2270DW Laser Printer                            | 2         | 1.37%   |
| Brother HL-1110 series                                     | 2         | 1.37%   |
| Xerox Phaser 6000B                                         | 1         | 0.68%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1         | 0.68%   |
| Seiko Epson WF-4830 Series                                 | 1         | 0.68%   |
| Seiko Epson L365 Series                                    | 1         | 0.68%   |
| Seiko Epson L132 Series                                    | 1         | 0.68%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 0.68%   |
| Seiko Epson ET-3760 Series                                 | 1         | 0.68%   |
| Seiko Epson ET-3750 Series                                 | 1         | 0.68%   |
| Samsung SCX-4200 series                                    | 1         | 0.68%   |
| Samsung ML-2540 Series Laser Printer                       | 1         | 0.68%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1         | 0.68%   |
| Samsung ML-1670 Series                                     | 1         | 0.68%   |
| Samsung ML-1660 Series                                     | 1         | 0.68%   |
| Samsung Composite Device                                   | 1         | 0.68%   |
| Samsung C43x Series                                        | 1         | 0.68%   |
| Oki Data USB Device                                        | 1         | 0.68%   |
| MIIIW MW Keyboard Air Mini                                 | 1         | 0.68%   |
| Lexmark International Lexmark E238                         | 1         | 0.68%   |
| Kyocera ECOSYS P2035d                                      | 1         | 0.68%   |
| HP PSC-1315/PSC-1317                                       | 1         | 0.68%   |
| HP Printing Support                                        | 1         | 0.68%   |
| HP OfficeJet Pro 8740                                      | 1         | 0.68%   |
| HP OfficeJet Pro 69                                        | 1         | 0.68%   |
| HP OfficeJet 5200 series                                   | 1         | 0.68%   |
| HP OfficeJet 3830 series                                   | 1         | 0.68%   |
| HP LaserJet Pro M148-M149                                  | 1         | 0.68%   |
| HP LaserJet P2035                                          | 1         | 0.68%   |
| HP LaserJet P2015 series                                   | 1         | 0.68%   |
| HP LaserJet M14-M17                                        | 1         | 0.68%   |
| HP LaserJet 1022                                           | 1         | 0.68%   |
| HP Ink Tank Wireless 410 series                            | 1         | 0.68%   |
| HP ENVY Pro 6400 series                                    | 1         | 0.68%   |
| HP ENVY Photo 7800 series                                  | 1         | 0.68%   |
| HP ENVY 4510 series                                        | 1         | 0.68%   |
| HP Deskjet F4400 series                                    | 1         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 61.54%  |
| Seiko Epson     | 3         | 23.08%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson Scanner                    | 2         | 15.38%  |
| Canon CanoScan N1240U/LiDE 30          | 2         | 15.38%  |
| Canon CanoScan LiDE 210                | 2         | 15.38%  |
| Seiko Epson GT-X700 [Perfection 4870]  | 1         | 7.69%   |
| HP Scanjet 300                         | 1         | 7.69%   |
| HP ScanJet 2400c                       | 1         | 7.69%   |
| Canon CanoScan LiDE 60                 | 1         | 7.69%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 7.69%   |
| Canon CanoScan LiDE 220                | 1         | 7.69%   |
| Canon CanoScan LiDE 110                | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 896       | 21.43%  |
| Microdia                               | 391       | 9.35%   |
| IMC Networks                           | 391       | 9.35%   |
| Acer                                   | 369       | 8.82%   |
| Realtek Semiconductor                  | 320       | 7.65%   |
| Logitech                               | 285       | 6.81%   |
| Sunplus Innovation Technology          | 223       | 5.33%   |
| Apple                                  | 212       | 5.07%   |
| Quanta                                 | 170       | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 137       | 3.28%   |
| Suyin                                  | 115       | 2.75%   |
| Syntek                                 | 92        | 2.2%    |
| Lite-On Technology                     | 76        | 1.82%   |
| Silicon Motion                         | 54        | 1.29%   |
| Microsoft                              | 49        | 1.17%   |
| Ricoh                                  | 35        | 0.84%   |
| Luxvisions Innotech Limited            | 35        | 0.84%   |
| Samsung Electronics                    | 33        | 0.79%   |
| Alcor Micro                            | 30        | 0.72%   |
| Generalplus Technology                 | 20        | 0.48%   |
| Z-Star Microelectronics                | 13        | 0.31%   |
| ARC International                      | 12        | 0.29%   |
| ALi                                    | 11        | 0.26%   |
| MacroSilicon                           | 10        | 0.24%   |
| DigiTech                               | 10        | 0.24%   |
| Unknown                                | 9         | 0.22%   |
| Importek                               | 9         | 0.22%   |
| Valve Software                         | 8         | 0.19%   |
| SunplusIT                              | 8         | 0.19%   |
| Razer USA                              | 8         | 0.19%   |
| Primax Electronics                     | 8         | 0.19%   |
| KYE Systems (Mouse Systems)            | 8         | 0.19%   |
| Intel                                  | 8         | 0.19%   |
| Sonix Technology                       | 7         | 0.17%   |
| Lenovo                                 | 7         | 0.17%   |
| Jieli Technology                       | 7         | 0.17%   |
| OmniVision Technologies                | 6         | 0.14%   |
| Huawei Technologies                    | 5         | 0.12%   |
| Hewlett-Packard                        | 5         | 0.12%   |
| Foxconn / Hon Hai                      | 5         | 0.12%   |
| Creative Technology                    | 5         | 0.12%   |
| AVerMedia Technologies                 | 5         | 0.12%   |
| LG Electronics                         | 4         | 0.1%    |
| GEMBIRD                                | 4         | 0.1%    |
| Aveo Technology                        | 4         | 0.1%    |
| Sunplus Technology                     | 3         | 0.07%   |
| icSpring                               | 3         | 0.07%   |
| GenesysLogic Technology                | 3         | 0.07%   |
| Cubeternet                             | 3         | 0.07%   |
| A4Tech                                 | 3         | 0.07%   |
| WCM_USB                                | 2         | 0.05%   |
| Sunplus IT                             | 2         | 0.05%   |
| Mustek Systems                         | 2         | 0.05%   |
| Genesys Logic                          | 2         | 0.05%   |
| Alpha Imaging Technology               | 2         | 0.05%   |
| 2M UVC CAMERA                          | 2         | 0.05%   |
| YGTek                                  | 1         | 0.02%   |
| Yealink Network Technology             | 1         | 0.02%   |
| Xiongmai                               | 1         | 0.02%   |
| XHT-210518                             | 1         | 0.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 187       | 4.43%   |
| Chicony Integrated Camera                        | 161       | 3.82%   |
| Chicony HD WebCam                                | 128       | 3.03%   |
| Realtek Integrated_Webcam_HD                     | 121       | 2.87%   |
| IMC Networks USB2.0 HD UVC WebCam                | 119       | 2.82%   |
| IMC Networks Integrated Camera                   | 119       | 2.82%   |
| Acer Integrated Camera                           | 80        | 1.9%    |
| Chicony USB2.0 Camera                            | 79        | 1.87%   |
| Acer BisonCam,NB Pro                             | 77        | 1.83%   |
| Apple Built-in iSight                            | 69        | 1.64%   |
| Sunplus Integrated_Webcam_HD                     | 68        | 1.61%   |
| Logitech HD Pro Webcam C920                      | 65        | 1.54%   |
| Syntek Integrated Camera                         | 55        | 1.3%    |
| Logitech Webcam C270                             | 51        | 1.21%   |
| Apple FaceTime HD Camera                         | 49        | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE                        | 48        | 1.14%   |
| Acer HD Webcam                                   | 43        | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 41        | 0.97%   |
| Quanta HD User Facing                            | 38        | 0.9%    |
| Apple FaceTime HD Camera (Built-in)              | 36        | 0.85%   |
| Acer BisonCam, NB Pro                            | 36        | 0.85%   |
| Chicony USB 2.0 Camera                           | 31        | 0.73%   |
| Samsung Galaxy A5 (MTP)                          | 30        | 0.71%   |
| Quanta HD Webcam                                 | 30        | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                  | 29        | 0.69%   |
| Sunplus HD WebCam                                | 28        | 0.66%   |
| Lite-On Integrated Camera                        | 28        | 0.66%   |
| Chicony HP Wide Vision HD Camera                 | 28        | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                     | 27        | 0.64%   |
| Microdia Amcrest AWC2198 USB Webcam              | 26        | 0.62%   |
| Logitech C922 Pro Stream Webcam                  | 26        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)          | 26        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD             | 25        | 0.59%   |
| Microdia Integrated Webcam                       | 25        | 0.59%   |
| Acer EasyCamera                                  | 25        | 0.59%   |
| Acer SunplusIT Integrated Camera                 | 23        | 0.55%   |
| Realtek Integrated Webcam HD                     | 22        | 0.52%   |
| Quanta VGA WebCam                                | 21        | 0.5%    |
| Chicony HP HD Camera                             | 21        | 0.5%    |
| Chicony HD User Facing                           | 21        | 0.5%    |
| Syntek EasyCamera                                | 20        | 0.47%   |
| Chicony USB2.0 VGA UVC WebCam                    | 20        | 0.47%   |
| Chicony EasyCamera                               | 20        | 0.47%   |
| Realtek USB Camera                               | 19        | 0.45%   |
| Realtek HD WebCam                                | 19        | 0.45%   |
| Chicony VGA Webcam                               | 19        | 0.45%   |
| Chicony HP HD Webcam                             | 19        | 0.45%   |
| Suyin HP Truevision HD                           | 18        | 0.43%   |
| Sunplus ASUS USB2.0 Webcam                       | 18        | 0.43%   |
| Silicon Motion Web Camera                        | 18        | 0.43%   |
| Realtek Integrated Webcam                        | 18        | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 18        | 0.43%   |
| Generalplus WEB CAM                              | 17        | 0.4%    |
| Chicony HP TrueVision HD Camera                  | 17        | 0.4%    |
| Chicony HP Truevision HD                         | 17        | 0.4%    |
| Acer Lenovo EasyCamera                           | 17        | 0.4%    |
| Syntek Lenovo EasyCamera                         | 16        | 0.38%   |
| Realtek USB2.0 HD UVC WebCam                     | 16        | 0.38%   |
| Quanta HP Wide Vision HD Camera                  | 16        | 0.38%   |
| Lite-On HP HD Camera                             | 16        | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 247       | 32.8%   |
| Validity Sensors           | 217       | 28.82%  |
| Shenzhen Goodix Technology | 141       | 18.73%  |
| Upek                       | 40        | 5.31%   |
| Elan Microelectronics      | 40        | 5.31%   |
| LighTuning Technology      | 31        | 4.12%   |
| AuthenTec                  | 24        | 3.19%   |
| STMicroelectronics         | 7         | 0.93%   |
| Samsung Electronics        | 2         | 0.27%   |
| HOLTEK                     | 2         | 0.27%   |
| DigitalPersona             | 2         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 87        | 11.55%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 8.37%   |
| Shenzhen Goodix  FingerPrint Device                                        | 52        | 6.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 49        | 6.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 48        | 6.37%   |
| Shenzhen Goodix FingerPrint                                                | 40        | 5.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 39        | 5.18%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 37        | 4.91%   |
| Elan ELAN:Fingerprint                                                      | 34        | 4.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 3.59%   |
| Synaptics  WBDI                                                            | 21        | 2.79%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 2.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.39%   |
| Validity Sensors VFS491                                                    | 17        | 2.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.99%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.99%   |
| Synaptics WBDI Device                                                      | 15        | 1.99%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 15        | 1.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.86%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 12        | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.2%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 0.93%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.93%   |
| AuthenTec AES2810                                                          | 7         | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 6         | 0.8%    |
| Elan ELAN:ARM-M4                                                           | 6         | 0.8%    |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 0.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.4%    |
| AuthenTec AES1600                                                          | 3         | 0.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.27%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.27%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.27%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.27%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.27%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.27%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.27%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.27%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 120       | 43.48%  |
| Alcor Micro               | 72        | 26.09%  |
| Upek                      | 28        | 10.14%  |
| O2 Micro                  | 21        | 7.61%   |
| Lenovo                    | 17        | 6.16%   |
| SCM Microsystems          | 7         | 2.54%   |
| OmniKey                   | 3         | 1.09%   |
| Realtek Semiconductor     | 2         | 0.72%   |
| Aladdin Knowledge Systems | 2         | 0.72%   |
| Giesecke & Devrient       | 1         | 0.36%   |
| Gemalto (was Gemplus)     | 1         | 0.36%   |
| Chicony Electronics       | 1         | 0.36%   |
| Advanced Card Systems     | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 25.72%  |
| Broadcom BCM5880 Secure Applications Processor                               | 38        | 13.77%  |
| Broadcom 5880                                                                | 36        | 13.04%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 12.32%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 10.14%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 6.16%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 6.16%   |
| Broadcom 58200                                                               | 10        | 3.62%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.45%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.72%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.72%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.72%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.36%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.36%   |
| OmniKey CardMan 1021                                                         | 1         | 0.36%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.36%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.36%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.36%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.36%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5015      | 69.78%  |
| 1     | 1784      | 24.82%  |
| 2     | 334       | 4.65%   |
| 3     | 44        | 0.61%   |
| 4     | 7         | 0.1%    |
| 5     | 2         | 0.03%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 739       | 29.11%  |
| Net/wireless             | 471       | 18.55%  |
| Graphics card            | 417       | 16.42%  |
| Multimedia controller    | 283       | 11.15%  |
| Chipcard                 | 267       | 10.52%  |
| Bluetooth                | 73        | 2.88%   |
| Communication controller | 49        | 1.93%   |
| Unassigned class         | 38        | 1.5%    |
| Sound                    | 34        | 1.34%   |
| Storage                  | 33        | 1.3%    |
| Net/ethernet             | 33        | 1.3%    |
| Camera                   | 27        | 1.06%   |
| Card reader              | 18        | 0.71%   |
| Network                  | 16        | 0.63%   |
| Storage/raid             | 11        | 0.43%   |
| Storage/ide              | 10        | 0.39%   |
| Modem                    | 8         | 0.32%   |
| Firewire controller      | 4         | 0.16%   |
| Storage/nvme             | 3         | 0.12%   |
| Flash memory             | 2         | 0.08%   |
| Dvb card                 | 2         | 0.08%   |
| Unclassified device      | 1         | 0.04%   |

