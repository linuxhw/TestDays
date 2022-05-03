ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 1771

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [297dca51b9](https://linux-hardware.org/?probe=297dca51b9) | Apr 30, 2022 |
| Biostar       | J3060NH                     | Desktop     | [b058b65094](https://linux-hardware.org/?probe=b058b65094) | Apr 29, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3a7104d6b4](https://linux-hardware.org/?probe=3a7104d6b4) | Apr 29, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2514409f18](https://linux-hardware.org/?probe=2514409f18) | Apr 28, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3b25bc9d0d](https://linux-hardware.org/?probe=3b25bc9d0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [833d1610d5](https://linux-hardware.org/?probe=833d1610d5) | Apr 25, 2022 |
| HP            | 2B47                        | Desktop     | [3805de3dc4](https://linux-hardware.org/?probe=3805de3dc4) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| Biostar       | J3060NH                     | Desktop     | [0c990ac779](https://linux-hardware.org/?probe=0c990ac779) | Apr 22, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [cdc3ddaa2d](https://linux-hardware.org/?probe=cdc3ddaa2d) | Apr 22, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [aa1df63f27](https://linux-hardware.org/?probe=aa1df63f27) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| Biostar       | J3060NH                     | Desktop     | [cd7f6e4843](https://linux-hardware.org/?probe=cd7f6e4843) | Apr 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4a4df2dc70](https://linux-hardware.org/?probe=4a4df2dc70) | Apr 20, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7f83049cd5](https://linux-hardware.org/?probe=7f83049cd5) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [e44ad7d84e](https://linux-hardware.org/?probe=e44ad7d84e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| HP            | 2B2C                        | Desktop     | [5c21edefdc](https://linux-hardware.org/?probe=5c21edefdc) | Apr 18, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [9ba73648b1](https://linux-hardware.org/?probe=9ba73648b1) | Apr 16, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| Dell          | Latitude E7250              | Notebook    | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [499a00bcf8](https://linux-hardware.org/?probe=499a00bcf8) | Apr 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | Notebook    | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [7ce5e071a2](https://linux-hardware.org/?probe=7ce5e071a2) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4c52c99ee9](https://linux-hardware.org/?probe=4c52c99ee9) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [162850d6b3](https://linux-hardware.org/?probe=162850d6b3) | Apr 12, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [542c9c6703](https://linux-hardware.org/?probe=542c9c6703) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [36b98241e2](https://linux-hardware.org/?probe=36b98241e2) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d03632cea9](https://linux-hardware.org/?probe=d03632cea9) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Biostar       | J3060NH                     | Desktop     | [33bc76917c](https://linux-hardware.org/?probe=33bc76917c) | Apr 08, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [b06f6f6879](https://linux-hardware.org/?probe=b06f6f6879) | Apr 08, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [7d87907153](https://linux-hardware.org/?probe=7d87907153) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [41fc926d28](https://linux-hardware.org/?probe=41fc926d28) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [586edef1b9](https://linux-hardware.org/?probe=586edef1b9) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [bb881ed0ee](https://linux-hardware.org/?probe=bb881ed0ee) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9aef69378](https://linux-hardware.org/?probe=d9aef69378) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5370b9e906](https://linux-hardware.org/?probe=5370b9e906) | Apr 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [d1b6ca0f16](https://linux-hardware.org/?probe=d1b6ca0f16) | Apr 07, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4e232c446f](https://linux-hardware.org/?probe=4e232c446f) | Apr 06, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [30591629c3](https://linux-hardware.org/?probe=30591629c3) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [8181b0cd19](https://linux-hardware.org/?probe=8181b0cd19) | Apr 05, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [dd1fef9175](https://linux-hardware.org/?probe=dd1fef9175) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [fe7fdad91b](https://linux-hardware.org/?probe=fe7fdad91b) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [a26b03795a](https://linux-hardware.org/?probe=a26b03795a) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [d467a8e89f](https://linux-hardware.org/?probe=d467a8e89f) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [5cfb35fb9e](https://linux-hardware.org/?probe=5cfb35fb9e) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [42084c0823](https://linux-hardware.org/?probe=42084c0823) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2c39a577ac](https://linux-hardware.org/?probe=2c39a577ac) | Apr 04, 2022 |
| Dell          | Latitude 5421               | Notebook    | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | Notebook    | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | WMCP78M                     | Desktop     | [7c9d2a802f](https://linux-hardware.org/?probe=7c9d2a802f) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a4228141cb](https://linux-hardware.org/?probe=a4228141cb) | Apr 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ea14bf201](https://linux-hardware.org/?probe=9ea14bf201) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0e42cf4c00](https://linux-hardware.org/?probe=0e42cf4c00) | Apr 01, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [5cdc7436c0](https://linux-hardware.org/?probe=5cdc7436c0) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | Desktop     | [f74de3797f](https://linux-hardware.org/?probe=f74de3797f) | Mar 31, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [44eafd5b02](https://linux-hardware.org/?probe=44eafd5b02) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8e7fc0aef9](https://linux-hardware.org/?probe=8e7fc0aef9) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [9a18c2ac1c](https://linux-hardware.org/?probe=9a18c2ac1c) | Mar 31, 2022 |
| Intel         | Unknown                     | Desktop     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceae86aef1](https://linux-hardware.org/?probe=ceae86aef1) | Mar 30, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [e6273d0bd9](https://linux-hardware.org/?probe=e6273d0bd9) | Mar 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [d8d0331e9e](https://linux-hardware.org/?probe=d8d0331e9e) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | Notebook    | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Biostar       | J3060NH                     | Desktop     | [3770e096dd](https://linux-hardware.org/?probe=3770e096dd) | Mar 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [99de1a9e9d](https://linux-hardware.org/?probe=99de1a9e9d) | Mar 30, 2022 |
| Kanji         | Tamura MAX DUO              | Convertible | [1434c90e55](https://linux-hardware.org/?probe=1434c90e55) | Mar 30, 2022 |
| Biostar       | J3060NH                     | Desktop     | [2f5c39da5a](https://linux-hardware.org/?probe=2f5c39da5a) | Mar 28, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [e33537863b](https://linux-hardware.org/?probe=e33537863b) | Mar 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d72468b304](https://linux-hardware.org/?probe=d72468b304) | Mar 27, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [1f36f7eada](https://linux-hardware.org/?probe=1f36f7eada) | Mar 27, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| Biostar       | J3060NH                     | Desktop     | [7bfd914743](https://linux-hardware.org/?probe=7bfd914743) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [170657280c](https://linux-hardware.org/?probe=170657280c) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| Biostar       | J3060NH                     | Desktop     | [6f46c10afd](https://linux-hardware.org/?probe=6f46c10afd) | Mar 24, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | Notebook    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Biostar       | J3060NH                     | Desktop     | [cabe778eeb](https://linux-hardware.org/?probe=cabe778eeb) | Mar 22, 2022 |
| Biostar       | J3060NH                     | Desktop     | [2b4227a591](https://linux-hardware.org/?probe=2b4227a591) | Mar 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [672496577e](https://linux-hardware.org/?probe=672496577e) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Biostar       | J3060NH                     | Desktop     | [90d9af88d8](https://linux-hardware.org/?probe=90d9af88d8) | Mar 18, 2022 |
| Unknown       | Intel X79                   | Desktop     | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | Notebook    | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [908e3fe366](https://linux-hardware.org/?probe=908e3fe366) | Mar 16, 2022 |
| ASRock        | Z87 Professional            | Desktop     | [e75eb7a802](https://linux-hardware.org/?probe=e75eb7a802) | Mar 15, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [13775d028d](https://linux-hardware.org/?probe=13775d028d) | Mar 15, 2022 |
| Dell          | Precision 7540              | Notebook    | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| Biostar       | J3060NH                     | Desktop     | [3a2e487a1a](https://linux-hardware.org/?probe=3a2e487a1a) | Mar 14, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Sony          | VPCEH25FM                   | Notebook    | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [531e740b37](https://linux-hardware.org/?probe=531e740b37) | Mar 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d5ab693301](https://linux-hardware.org/?probe=d5ab693301) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8215dc9a65](https://linux-hardware.org/?probe=8215dc9a65) | Mar 05, 2022 |
| Biostar       | J3060NH                     | Desktop     | [27308af100](https://linux-hardware.org/?probe=27308af100) | Mar 05, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2383184762](https://linux-hardware.org/?probe=2383184762) | Mar 05, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [1b45a09429](https://linux-hardware.org/?probe=1b45a09429) | Mar 03, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [45c8e5fea2](https://linux-hardware.org/?probe=45c8e5fea2) | Mar 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [45e459af5a](https://linux-hardware.org/?probe=45e459af5a) | Mar 01, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | Notebook    | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| Biostar       | J3060NH                     | Desktop     | [e96feeb291](https://linux-hardware.org/?probe=e96feeb291) | Feb 27, 2022 |
| Unknown       | Intel X79                   | Desktop     | [6a9245acd2](https://linux-hardware.org/?probe=6a9245acd2) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [759958a4b0](https://linux-hardware.org/?probe=759958a4b0) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [9bac80064d](https://linux-hardware.org/?probe=9bac80064d) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [c7de16de1e](https://linux-hardware.org/?probe=c7de16de1e) | Feb 25, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [270aaf59b6](https://linux-hardware.org/?probe=270aaf59b6) | Feb 25, 2022 |
| Lenovo        | ThinkPad S430 68852BU       | Notebook    | [7d7bb498fe](https://linux-hardware.org/?probe=7d7bb498fe) | Feb 25, 2022 |
| Biostar       | J3060NH                     | Desktop     | [70d00c5ecb](https://linux-hardware.org/?probe=70d00c5ecb) | Feb 24, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [52bbb8515e](https://linux-hardware.org/?probe=52bbb8515e) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| Medion        | MS-7707                     | Desktop     | [2e4723aea4](https://linux-hardware.org/?probe=2e4723aea4) | Feb 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a1f77fb84a](https://linux-hardware.org/?probe=a1f77fb84a) | Feb 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [3a98eace64](https://linux-hardware.org/?probe=3a98eace64) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| Biostar       | J3060NH                     | Desktop     | [3ab032fa41](https://linux-hardware.org/?probe=3ab032fa41) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [12dc322ece](https://linux-hardware.org/?probe=12dc322ece) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | K54L                        | Notebook    | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [3beffcfd3e](https://linux-hardware.org/?probe=3beffcfd3e) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| Biostar       | J3060NH                     | Desktop     | [3a9a490090](https://linux-hardware.org/?probe=3a9a490090) | Feb 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [732c7ad77e](https://linux-hardware.org/?probe=732c7ad77e) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1982ff9621](https://linux-hardware.org/?probe=1982ff9621) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [35ac77d812](https://linux-hardware.org/?probe=35ac77d812) | Feb 17, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [619f336b27](https://linux-hardware.org/?probe=619f336b27) | Feb 17, 2022 |
| Biostar       | J3060NH                     | Desktop     | [64d3fb3a9a](https://linux-hardware.org/?probe=64d3fb3a9a) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1e8c363a67](https://linux-hardware.org/?probe=1e8c363a67) | Feb 16, 2022 |
| ASUSTek       | K53E                        | Notebook    | [929e5d8462](https://linux-hardware.org/?probe=929e5d8462) | Feb 15, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [046f5cdbd7](https://linux-hardware.org/?probe=046f5cdbd7) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [0ee015dd8e](https://linux-hardware.org/?probe=0ee015dd8e) | Feb 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | Notebook    | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b30a95971c](https://linux-hardware.org/?probe=b30a95971c) | Feb 12, 2022 |
| Biostar       | J3060NH                     | Desktop     | [c485d1f940](https://linux-hardware.org/?probe=c485d1f940) | Feb 11, 2022 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [ca5c3f80ae](https://linux-hardware.org/?probe=ca5c3f80ae) | Feb 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [c50b098929](https://linux-hardware.org/?probe=c50b098929) | Feb 10, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [aa66dba98f](https://linux-hardware.org/?probe=aa66dba98f) | Feb 09, 2022 |
| Biostar       | J3060NH                     | Desktop     | [6b45839143](https://linux-hardware.org/?probe=6b45839143) | Feb 09, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | Notebook    | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| Compal        | PBL21                       | Notebook    | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [e6bc24c5b9](https://linux-hardware.org/?probe=e6bc24c5b9) | Feb 08, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de476d2b5a](https://linux-hardware.org/?probe=de476d2b5a) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8a7cf7aca4](https://linux-hardware.org/?probe=8a7cf7aca4) | Feb 07, 2022 |
| Biostar       | J3060NH                     | Desktop     | [b34126597c](https://linux-hardware.org/?probe=b34126597c) | Feb 07, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [3a067528e2](https://linux-hardware.org/?probe=3a067528e2) | Feb 07, 2022 |
| Biostar       | J3060NH                     | Desktop     | [b7cd4a0856](https://linux-hardware.org/?probe=b7cd4a0856) | Feb 07, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Supermicro    | X11SAE-M                    | Server      | [ecb9ec0d34](https://linux-hardware.org/?probe=ecb9ec0d34) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6c3ac00f6a](https://linux-hardware.org/?probe=6c3ac00f6a) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Biostar       | J3060NH                     | Desktop     | [ab80e70c7f](https://linux-hardware.org/?probe=ab80e70c7f) | Feb 05, 2022 |
| Dell          | Precision 5550              | Notebook    | [2853896d4c](https://linux-hardware.org/?probe=2853896d4c) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [f4a6341837](https://linux-hardware.org/?probe=f4a6341837) | Feb 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [655eea9ee5](https://linux-hardware.org/?probe=655eea9ee5) | Feb 02, 2022 |
| Notebook      | PA70ES                      | Notebook    | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| ASUSTek       | X750LN                      | Notebook    | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [1c3c43b4ce](https://linux-hardware.org/?probe=1c3c43b4ce) | Feb 02, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [f755eb7a78](https://linux-hardware.org/?probe=f755eb7a78) | Feb 01, 2022 |
| Biostar       | J3060NH                     | Desktop     | [dba248e591](https://linux-hardware.org/?probe=dba248e591) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [ccbf2ec4f5](https://linux-hardware.org/?probe=ccbf2ec4f5) | Jan 29, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d2ebf4698b](https://linux-hardware.org/?probe=d2ebf4698b) | Jan 29, 2022 |
| Biostar       | J3060NH                     | Desktop     | [b9a181ab77](https://linux-hardware.org/?probe=b9a181ab77) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [9a1fb4d53e](https://linux-hardware.org/?probe=9a1fb4d53e) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [1db87d66c6](https://linux-hardware.org/?probe=1db87d66c6) | Jan 28, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [1f9df11a59](https://linux-hardware.org/?probe=1f9df11a59) | Jan 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| HP            | 1998                        | Desktop     | [4ee1e4fcee](https://linux-hardware.org/?probe=4ee1e4fcee) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS0QQ00    | Notebook    | [470cd66ae6](https://linux-hardware.org/?probe=470cd66ae6) | Jan 27, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [efe16c5921](https://linux-hardware.org/?probe=efe16c5921) | Jan 27, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7f8d7afb60](https://linux-hardware.org/?probe=7f8d7afb60) | Jan 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [599ea5acd6](https://linux-hardware.org/?probe=599ea5acd6) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0b57afd8bf](https://linux-hardware.org/?probe=0b57afd8bf) | Jan 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [a4172550fa](https://linux-hardware.org/?probe=a4172550fa) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| ASRock        | P75 Pro3                    | Desktop     | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [269d1509c2](https://linux-hardware.org/?probe=269d1509c2) | Jan 24, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2dbb65e1bc](https://linux-hardware.org/?probe=2dbb65e1bc) | Jan 24, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a2ed61ffcd](https://linux-hardware.org/?probe=a2ed61ffcd) | Jan 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [2ce129a03e](https://linux-hardware.org/?probe=2ce129a03e) | Jan 23, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [0d9f79bb17](https://linux-hardware.org/?probe=0d9f79bb17) | Jan 23, 2022 |
| Unknown       | Intel X79                   | Desktop     | [7d1ab99839](https://linux-hardware.org/?probe=7d1ab99839) | Jan 23, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [299f1c8cca](https://linux-hardware.org/?probe=299f1c8cca) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | Notebook    | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Standard      | MB50II                      | Notebook    | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b9dfe5b842](https://linux-hardware.org/?probe=b9dfe5b842) | Jan 21, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | Notebook    | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [09347426df](https://linux-hardware.org/?probe=09347426df) | Jan 20, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [3bc52b8340](https://linux-hardware.org/?probe=3bc52b8340) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0287de904c](https://linux-hardware.org/?probe=0287de904c) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [03aa6d19c1](https://linux-hardware.org/?probe=03aa6d19c1) | Jan 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [30edae47a1](https://linux-hardware.org/?probe=30edae47a1) | Jan 17, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [b123404920](https://linux-hardware.org/?probe=b123404920) | Jan 17, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [5343777492](https://linux-hardware.org/?probe=5343777492) | Jan 16, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9324cf10f9](https://linux-hardware.org/?probe=9324cf10f9) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f87a30cc1b](https://linux-hardware.org/?probe=f87a30cc1b) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7e3aee849](https://linux-hardware.org/?probe=a7e3aee849) | Jan 15, 2022 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | 83E0                        | Desktop     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a27eed4aa9](https://linux-hardware.org/?probe=a27eed4aa9) | Jan 10, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [3ac159be99](https://linux-hardware.org/?probe=3ac159be99) | Jan 10, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [f8400f7913](https://linux-hardware.org/?probe=f8400f7913) | Jan 09, 2022 |
| Dell          | 05CNYF A01                  | Desktop     | [c197ba435d](https://linux-hardware.org/?probe=c197ba435d) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| ASUSTek       | K53E                        | Notebook    | [ed3993d878](https://linux-hardware.org/?probe=ed3993d878) | Jan 08, 2022 |
| ASUSTek       | K53E                        | Notebook    | [f0be64df73](https://linux-hardware.org/?probe=f0be64df73) | Jan 08, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [2e21ca6670](https://linux-hardware.org/?probe=2e21ca6670) | Jan 08, 2022 |
| Acer          | Extensa 5620                | Notebook    | [a10369e225](https://linux-hardware.org/?probe=a10369e225) | Jan 08, 2022 |
| Sony          | VPCEB2B4E                   | Notebook    | [4d3b6ede0c](https://linux-hardware.org/?probe=4d3b6ede0c) | Jan 08, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [c56817a778](https://linux-hardware.org/?probe=c56817a778) | Jan 08, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [9136eda01b](https://linux-hardware.org/?probe=9136eda01b) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5cec5778a0](https://linux-hardware.org/?probe=5cec5778a0) | Jan 06, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | Notebook    | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ed79871c15](https://linux-hardware.org/?probe=ed79871c15) | Jan 05, 2022 |
| HP            | 82F2 A01                    | Desktop     | [416ee28a87](https://linux-hardware.org/?probe=416ee28a87) | Jan 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e2753ebd08](https://linux-hardware.org/?probe=e2753ebd08) | Jan 04, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [e913dca33e](https://linux-hardware.org/?probe=e913dca33e) | Jan 04, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [fe5ca696c8](https://linux-hardware.org/?probe=fe5ca696c8) | Jan 04, 2022 |
| Monster       | ABRA A5 V11.1               | Notebook    | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3383929020](https://linux-hardware.org/?probe=3383929020) | Jan 03, 2022 |
| VS Company    | MCP61M                      | Desktop     | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [14ca887c8f](https://linux-hardware.org/?probe=14ca887c8f) | Jan 02, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [98ed791fc8](https://linux-hardware.org/?probe=98ed791fc8) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3e3a3df7ce](https://linux-hardware.org/?probe=3e3a3df7ce) | Dec 31, 2021 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [46c8424272](https://linux-hardware.org/?probe=46c8424272) | Dec 31, 2021 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [0cf80c2ee3](https://linux-hardware.org/?probe=0cf80c2ee3) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [1bd919981a](https://linux-hardware.org/?probe=1bd919981a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | Notebook    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7376dd6793](https://linux-hardware.org/?probe=7376dd6793) | Dec 29, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [c3caffed3c](https://linux-hardware.org/?probe=c3caffed3c) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Latitude E4310              | Notebook    | [8b6976bdd2](https://linux-hardware.org/?probe=8b6976bdd2) | Dec 28, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [18e1fc7fe1](https://linux-hardware.org/?probe=18e1fc7fe1) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [e453f3473f](https://linux-hardware.org/?probe=e453f3473f) | Dec 27, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [34c9874e50](https://linux-hardware.org/?probe=34c9874e50) | Dec 27, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [66fbe6bde9](https://linux-hardware.org/?probe=66fbe6bde9) | Dec 27, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | Notebook    | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [54774d551c](https://linux-hardware.org/?probe=54774d551c) | Dec 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [9cb5033472](https://linux-hardware.org/?probe=9cb5033472) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9ba8148878](https://linux-hardware.org/?probe=9ba8148878) | Dec 25, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a0df87d44d](https://linux-hardware.org/?probe=a0df87d44d) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e110e5c127](https://linux-hardware.org/?probe=e110e5c127) | Dec 25, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0915144999](https://linux-hardware.org/?probe=0915144999) | Dec 25, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [685afb1399](https://linux-hardware.org/?probe=685afb1399) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| MSI           | MS-AA1511                   | All in one  | [ef477f6784](https://linux-hardware.org/?probe=ef477f6784) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d971e22ea1](https://linux-hardware.org/?probe=d971e22ea1) | Dec 24, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Dell          | Latitude E4310              | Notebook    | [e5b46c1542](https://linux-hardware.org/?probe=e5b46c1542) | Dec 24, 2021 |
| Biostar       | J3060NH                     | Desktop     | [1ce2af5d7d](https://linux-hardware.org/?probe=1ce2af5d7d) | Dec 24, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [b5cd12bc15](https://linux-hardware.org/?probe=b5cd12bc15) | Dec 24, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [ed79d730cd](https://linux-hardware.org/?probe=ed79d730cd) | Dec 24, 2021 |
| ASUSTek       | X450LD                      | Notebook    | [b5e36a24f9](https://linux-hardware.org/?probe=b5e36a24f9) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [82a81d9287](https://linux-hardware.org/?probe=82a81d9287) | Dec 24, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [3b01d877ce](https://linux-hardware.org/?probe=3b01d877ce) | Dec 24, 2021 |
| Biostar       | J3060NH                     | Desktop     | [3e3af2113c](https://linux-hardware.org/?probe=3e3af2113c) | Dec 24, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [af10afb79b](https://linux-hardware.org/?probe=af10afb79b) | Dec 23, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9bd5592765](https://linux-hardware.org/?probe=9bd5592765) | Dec 23, 2021 |
| Medion        | E4213 MD99329               | Notebook    | [8801cfdb2a](https://linux-hardware.org/?probe=8801cfdb2a) | Dec 23, 2021 |
| Teclast       | F15S                        | Notebook    | [8be33fb7e2](https://linux-hardware.org/?probe=8be33fb7e2) | Dec 23, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| Biostar       | J3060NH                     | Desktop     | [e5c412fa6e](https://linux-hardware.org/?probe=e5c412fa6e) | Dec 23, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a54f9967ef](https://linux-hardware.org/?probe=a54f9967ef) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2ca39a2067](https://linux-hardware.org/?probe=2ca39a2067) | Dec 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b73f1f9cb1](https://linux-hardware.org/?probe=b73f1f9cb1) | Dec 23, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [870a0913ee](https://linux-hardware.org/?probe=870a0913ee) | Dec 23, 2021 |
| Biostar       | J3060NH                     | Desktop     | [0f1621c9dc](https://linux-hardware.org/?probe=0f1621c9dc) | Dec 23, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d6c3f77490](https://linux-hardware.org/?probe=d6c3f77490) | Dec 23, 2021 |
| Dell          | Latitude 3410               | Notebook    | [a0b79031ae](https://linux-hardware.org/?probe=a0b79031ae) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d00c0b2ded](https://linux-hardware.org/?probe=d00c0b2ded) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | Notebook    | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2d5a1005a3](https://linux-hardware.org/?probe=2d5a1005a3) | Dec 22, 2021 |
| SYWZ          | S210H Series                | Desktop     | [df3edf9f7b](https://linux-hardware.org/?probe=df3edf9f7b) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6e060be970](https://linux-hardware.org/?probe=6e060be970) | Dec 21, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8b33da2ce4](https://linux-hardware.org/?probe=8b33da2ce4) | Dec 21, 2021 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [7a89a419b9](https://linux-hardware.org/?probe=7a89a419b9) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f203cad33d](https://linux-hardware.org/?probe=f203cad33d) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [de9ccde374](https://linux-hardware.org/?probe=de9ccde374) | Dec 18, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [55e4486324](https://linux-hardware.org/?probe=55e4486324) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bee0b80356](https://linux-hardware.org/?probe=bee0b80356) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bc4e465833](https://linux-hardware.org/?probe=bc4e465833) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [9bd0a6e07d](https://linux-hardware.org/?probe=9bd0a6e07d) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [702be0b615](https://linux-hardware.org/?probe=702be0b615) | Dec 17, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [60d68b4c13](https://linux-hardware.org/?probe=60d68b4c13) | Dec 17, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [14ffa86838](https://linux-hardware.org/?probe=14ffa86838) | Dec 17, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3cc5833948](https://linux-hardware.org/?probe=3cc5833948) | Dec 16, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [082bd4283a](https://linux-hardware.org/?probe=082bd4283a) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e0c828271e](https://linux-hardware.org/?probe=e0c828271e) | Dec 16, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8b9e71b388](https://linux-hardware.org/?probe=8b9e71b388) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [f9f891f9b2](https://linux-hardware.org/?probe=f9f891f9b2) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2633be8cd](https://linux-hardware.org/?probe=e2633be8cd) | Dec 16, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [9cb226408e](https://linux-hardware.org/?probe=9cb226408e) | Dec 15, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | Notebook    | [b7b09dcc5e](https://linux-hardware.org/?probe=b7b09dcc5e) | Dec 15, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | Notebook    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Precision M4800             | Notebook    | [90109636fe](https://linux-hardware.org/?probe=90109636fe) | Dec 15, 2021 |
| Dell          | Precision M4800             | Notebook    | [0d1cfc9a0e](https://linux-hardware.org/?probe=0d1cfc9a0e) | Dec 15, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [0e25c30439](https://linux-hardware.org/?probe=0e25c30439) | Dec 15, 2021 |
| Unknown       | Intel X79                   | Desktop     | [a2ef0675af](https://linux-hardware.org/?probe=a2ef0675af) | Dec 14, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [62f88112f1](https://linux-hardware.org/?probe=62f88112f1) | Dec 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| ASUSTek       | TUF GAMING B550-PRO         | Desktop     | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| ASUSTek       | CM6870                      | Desktop     | [05624c26d2](https://linux-hardware.org/?probe=05624c26d2) | Dec 14, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d5328cbc95](https://linux-hardware.org/?probe=d5328cbc95) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Alienware     | 15 R3                       | Notebook    | [6394aa965a](https://linux-hardware.org/?probe=6394aa965a) | Dec 14, 2021 |
| Acer          | Aspire E5-532G              | Notebook    | [8cbbaee4ad](https://linux-hardware.org/?probe=8cbbaee4ad) | Dec 14, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [05db94d8a5](https://linux-hardware.org/?probe=05db94d8a5) | Dec 14, 2021 |
| EVGA          | 141-HW-E877                 | Desktop     | [a9d6f7c590](https://linux-hardware.org/?probe=a9d6f7c590) | Dec 14, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d2653b1c59](https://linux-hardware.org/?probe=d2653b1c59) | Dec 14, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [36ce439bef](https://linux-hardware.org/?probe=36ce439bef) | Dec 14, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [5faef7686a](https://linux-hardware.org/?probe=5faef7686a) | Dec 14, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [08a3ae4604](https://linux-hardware.org/?probe=08a3ae4604) | Dec 14, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [dc12c3cae7](https://linux-hardware.org/?probe=dc12c3cae7) | Dec 14, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| HP            | 1587h                       | Desktop     | [b9f599ed03](https://linux-hardware.org/?probe=b9f599ed03) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [afbed7279a](https://linux-hardware.org/?probe=afbed7279a) | Dec 13, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [7a34a2de3b](https://linux-hardware.org/?probe=7a34a2de3b) | Dec 13, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ebf80cd948](https://linux-hardware.org/?probe=ebf80cd948) | Dec 13, 2021 |
| Acer          | Extensa 5635ZG              | Notebook    | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e536222841](https://linux-hardware.org/?probe=e536222841) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [fd1da12c59](https://linux-hardware.org/?probe=fd1da12c59) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [91eeb42bcb](https://linux-hardware.org/?probe=91eeb42bcb) | Dec 13, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [2e90062d9a](https://linux-hardware.org/?probe=2e90062d9a) | Dec 12, 2021 |
| Packard Be... | IMEDIA S2185                | Desktop     | [26f91db3d6](https://linux-hardware.org/?probe=26f91db3d6) | Dec 12, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b14b8a40ec](https://linux-hardware.org/?probe=b14b8a40ec) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [666796bd7e](https://linux-hardware.org/?probe=666796bd7e) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [981dc4e673](https://linux-hardware.org/?probe=981dc4e673) | Dec 12, 2021 |
| Dell          | Precision 5550              | Notebook    | [9e88f6034f](https://linux-hardware.org/?probe=9e88f6034f) | Dec 12, 2021 |
| System76      | Galago Pro                  | Notebook    | [9fe1e9175f](https://linux-hardware.org/?probe=9fe1e9175f) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [6343dc8a43](https://linux-hardware.org/?probe=6343dc8a43) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [e59e1a3c29](https://linux-hardware.org/?probe=e59e1a3c29) | Dec 12, 2021 |
| Lenovo        | ThinkPad X201 3680KC5       | Notebook    | [64958365b3](https://linux-hardware.org/?probe=64958365b3) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [c11f61f55f](https://linux-hardware.org/?probe=c11f61f55f) | Dec 12, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [da7c19f0b4](https://linux-hardware.org/?probe=da7c19f0b4) | Dec 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [80e68beff0](https://linux-hardware.org/?probe=80e68beff0) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [48325242e3](https://linux-hardware.org/?probe=48325242e3) | Dec 12, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [539ebca696](https://linux-hardware.org/?probe=539ebca696) | Dec 12, 2021 |
| System76      | Darter Pro                  | Notebook    | [2e84db8ffb](https://linux-hardware.org/?probe=2e84db8ffb) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d25b03b97c](https://linux-hardware.org/?probe=d25b03b97c) | Dec 12, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a2bfa3a5d3](https://linux-hardware.org/?probe=a2bfa3a5d3) | Dec 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [00b5d9eba5](https://linux-hardware.org/?probe=00b5d9eba5) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [b9eda20029](https://linux-hardware.org/?probe=b9eda20029) | Dec 12, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [ed5c21cccd](https://linux-hardware.org/?probe=ed5c21cccd) | Dec 11, 2021 |
| ASUSTek       | X99-S                       | Desktop     | [df25f864d4](https://linux-hardware.org/?probe=df25f864d4) | Dec 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [330425b3b7](https://linux-hardware.org/?probe=330425b3b7) | Dec 11, 2021 |
| HP            | 86EE                        | All in one  | [1865c9ea80](https://linux-hardware.org/?probe=1865c9ea80) | Dec 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c5f999eb1e](https://linux-hardware.org/?probe=c5f999eb1e) | Dec 11, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ccb713df7](https://linux-hardware.org/?probe=9ccb713df7) | Dec 11, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [9bf2d21979](https://linux-hardware.org/?probe=9bf2d21979) | Dec 11, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [dff25b4704](https://linux-hardware.org/?probe=dff25b4704) | Dec 11, 2021 |
| HP            | 8768 A                      | Desktop     | [dddb82f6a8](https://linux-hardware.org/?probe=dddb82f6a8) | Dec 11, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [34dacc4911](https://linux-hardware.org/?probe=34dacc4911) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [96a7160cee](https://linux-hardware.org/?probe=96a7160cee) | Dec 11, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [4e9e6b5c99](https://linux-hardware.org/?probe=4e9e6b5c99) | Dec 11, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1b3b98bfd7](https://linux-hardware.org/?probe=1b3b98bfd7) | Dec 11, 2021 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [efb6380716](https://linux-hardware.org/?probe=efb6380716) | Dec 11, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [684572bd8a](https://linux-hardware.org/?probe=684572bd8a) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [f40860a3ed](https://linux-hardware.org/?probe=f40860a3ed) | Dec 11, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [1676bf41af](https://linux-hardware.org/?probe=1676bf41af) | Dec 11, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [debd9b86e1](https://linux-hardware.org/?probe=debd9b86e1) | Dec 11, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1583ed8a4](https://linux-hardware.org/?probe=d1583ed8a4) | Dec 10, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [ecdd032df4](https://linux-hardware.org/?probe=ecdd032df4) | Dec 10, 2021 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [9115bc7a4e](https://linux-hardware.org/?probe=9115bc7a4e) | Dec 09, 2021 |
| ASUSTek       | K53E                        | Notebook    | [86e5e5850b](https://linux-hardware.org/?probe=86e5e5850b) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e7b92397a3](https://linux-hardware.org/?probe=e7b92397a3) | Dec 09, 2021 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [1a64f6d9ca](https://linux-hardware.org/?probe=1a64f6d9ca) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [464ca4f312](https://linux-hardware.org/?probe=464ca4f312) | Dec 09, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [8fe2d382de](https://linux-hardware.org/?probe=8fe2d382de) | Dec 08, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [a9cb8442ac](https://linux-hardware.org/?probe=a9cb8442ac) | Dec 08, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [cf8576527d](https://linux-hardware.org/?probe=cf8576527d) | Dec 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [ee8b533768](https://linux-hardware.org/?probe=ee8b533768) | Dec 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f01927ee79](https://linux-hardware.org/?probe=f01927ee79) | Dec 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| HP            | ENVY Notebook               | Notebook    | [179bd0eae8](https://linux-hardware.org/?probe=179bd0eae8) | Dec 05, 2021 |
| HP            | ENVY Notebook               | Notebook    | [58488b0351](https://linux-hardware.org/?probe=58488b0351) | Dec 05, 2021 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [b25e4ae64c](https://linux-hardware.org/?probe=b25e4ae64c) | Dec 05, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [5f5964c9a4](https://linux-hardware.org/?probe=5f5964c9a4) | Dec 05, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [8647345ee8](https://linux-hardware.org/?probe=8647345ee8) | Dec 05, 2021 |
| MSI           | Summit E13FlipEvo A11MT     | Convertible | [ed656c15ad](https://linux-hardware.org/?probe=ed656c15ad) | Dec 05, 2021 |
| Razer         | Blade Stealth               | Notebook    | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| Dell          | 07C0H8 A00                  | Desktop     | [8b0b4e0427](https://linux-hardware.org/?probe=8b0b4e0427) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| ASUSTek       | K501UX                      | Notebook    | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| ASUSTek       | K53E                        | Notebook    | [7213694058](https://linux-hardware.org/?probe=7213694058) | Dec 04, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [5efc3e5fc4](https://linux-hardware.org/?probe=5efc3e5fc4) | Dec 03, 2021 |
| HP            | Notebook                    | Notebook    | [9f7082bedb](https://linux-hardware.org/?probe=9f7082bedb) | Dec 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [df01b853dd](https://linux-hardware.org/?probe=df01b853dd) | Dec 03, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [7fd0e9e7cd](https://linux-hardware.org/?probe=7fd0e9e7cd) | Dec 03, 2021 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [f35a1d4b6f](https://linux-hardware.org/?probe=f35a1d4b6f) | Dec 02, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [473e7afa6d](https://linux-hardware.org/?probe=473e7afa6d) | Dec 01, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [53de3c938f](https://linux-hardware.org/?probe=53de3c938f) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [8967a333fa](https://linux-hardware.org/?probe=8967a333fa) | Nov 29, 2021 |
| HP            | Pavilion g7                 | Notebook    | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5e6aa10813](https://linux-hardware.org/?probe=5e6aa10813) | Nov 29, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [f5a807ee34](https://linux-hardware.org/?probe=f5a807ee34) | Nov 29, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [43ec4aeaa5](https://linux-hardware.org/?probe=43ec4aeaa5) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [681845a2e3](https://linux-hardware.org/?probe=681845a2e3) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [b022b376ee](https://linux-hardware.org/?probe=b022b376ee) | Nov 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [73dbadb8f1](https://linux-hardware.org/?probe=73dbadb8f1) | Nov 28, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [d3cfe93dc6](https://linux-hardware.org/?probe=d3cfe93dc6) | Nov 28, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [be44e9c10b](https://linux-hardware.org/?probe=be44e9c10b) | Nov 28, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2f2ac97b5b](https://linux-hardware.org/?probe=2f2ac97b5b) | Nov 26, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a0f72af8d9](https://linux-hardware.org/?probe=a0f72af8d9) | Nov 26, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [38ca30691b](https://linux-hardware.org/?probe=38ca30691b) | Nov 26, 2021 |
| ASUSTek       | K53E                        | Notebook    | [e0191cc961](https://linux-hardware.org/?probe=e0191cc961) | Nov 26, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [3df1e42b0e](https://linux-hardware.org/?probe=3df1e42b0e) | Nov 26, 2021 |
| Dell          | 0H4VK7 A01                  | Desktop     | [83171d6677](https://linux-hardware.org/?probe=83171d6677) | Nov 26, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [5cdb53e7ae](https://linux-hardware.org/?probe=5cdb53e7ae) | Nov 25, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9bc92b5ef9](https://linux-hardware.org/?probe=9bc92b5ef9) | Nov 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [5575758e0a](https://linux-hardware.org/?probe=5575758e0a) | Nov 25, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [071447b964](https://linux-hardware.org/?probe=071447b964) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7d4b6453e9](https://linux-hardware.org/?probe=7d4b6453e9) | Nov 24, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [ce783dccca](https://linux-hardware.org/?probe=ce783dccca) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e9b4b7ecba](https://linux-hardware.org/?probe=e9b4b7ecba) | Nov 24, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e102635d3d](https://linux-hardware.org/?probe=e102635d3d) | Nov 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [485f0b0858](https://linux-hardware.org/?probe=485f0b0858) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| ASRock        | FM2A78M Pro4+               | Desktop     | [1670e83f4d](https://linux-hardware.org/?probe=1670e83f4d) | Nov 24, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [e215995139](https://linux-hardware.org/?probe=e215995139) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d82d0b32b](https://linux-hardware.org/?probe=1d82d0b32b) | Nov 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9dc059644a](https://linux-hardware.org/?probe=9dc059644a) | Nov 23, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| HP            | Laptop 14q-cs0xxx           | Notebook    | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35063b25d7](https://linux-hardware.org/?probe=35063b25d7) | Nov 23, 2021 |
| Dell          | Latitude E5450              | Notebook    | [a1c9396c75](https://linux-hardware.org/?probe=a1c9396c75) | Nov 23, 2021 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [09ee3255d5](https://linux-hardware.org/?probe=09ee3255d5) | Nov 23, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [6994e8dbb3](https://linux-hardware.org/?probe=6994e8dbb3) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [fbc257563e](https://linux-hardware.org/?probe=fbc257563e) | Nov 22, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8338e70267](https://linux-hardware.org/?probe=8338e70267) | Nov 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [47fe68608a](https://linux-hardware.org/?probe=47fe68608a) | Nov 22, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| ASUSTek       | K53E                        | Notebook    | [de7dd823ec](https://linux-hardware.org/?probe=de7dd823ec) | Nov 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a95e047ec3](https://linux-hardware.org/?probe=a95e047ec3) | Nov 20, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [dcc60be203](https://linux-hardware.org/?probe=dcc60be203) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| HP            | 158B                        | Desktop     | [28d106042e](https://linux-hardware.org/?probe=28d106042e) | Nov 20, 2021 |
| ASUSTek       | M5401WUA                    | All in one  | [c1f6b30a92](https://linux-hardware.org/?probe=c1f6b30a92) | Nov 18, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [906510b2cd](https://linux-hardware.org/?probe=906510b2cd) | Nov 18, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [b94e6da627](https://linux-hardware.org/?probe=b94e6da627) | Nov 18, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [b0f06cc210](https://linux-hardware.org/?probe=b0f06cc210) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c5c112ae1d](https://linux-hardware.org/?probe=c5c112ae1d) | Nov 18, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [223642cd17](https://linux-hardware.org/?probe=223642cd17) | Nov 16, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [5fc521fe4b](https://linux-hardware.org/?probe=5fc521fe4b) | Nov 15, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [0f7bccdef0](https://linux-hardware.org/?probe=0f7bccdef0) | Nov 15, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [caba9b6b30](https://linux-hardware.org/?probe=caba9b6b30) | Nov 13, 2021 |
| ASUSTek       | K53E                        | Notebook    | [11aec68b43](https://linux-hardware.org/?probe=11aec68b43) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [6ddb5fdd76](https://linux-hardware.org/?probe=6ddb5fdd76) | Nov 12, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| ASRock        | A55M-VS                     | Desktop     | [3e40db1efb](https://linux-hardware.org/?probe=3e40db1efb) | Nov 09, 2021 |
| HP            | 8055                        | Desktop     | [5d16a78abe](https://linux-hardware.org/?probe=5d16a78abe) | Nov 09, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [b64db5197a](https://linux-hardware.org/?probe=b64db5197a) | Nov 09, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [77b62d6178](https://linux-hardware.org/?probe=77b62d6178) | Nov 09, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [bffba05735](https://linux-hardware.org/?probe=bffba05735) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [4a189c2903](https://linux-hardware.org/?probe=4a189c2903) | Nov 07, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4afe3e309c](https://linux-hardware.org/?probe=4afe3e309c) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0ed60610db](https://linux-hardware.org/?probe=0ed60610db) | Nov 07, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [20fdb1b588](https://linux-hardware.org/?probe=20fdb1b588) | Nov 07, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Dell          | Latitude E6440              | Notebook    | [38e3c1e18a](https://linux-hardware.org/?probe=38e3c1e18a) | Nov 06, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [88d5f57ea9](https://linux-hardware.org/?probe=88d5f57ea9) | Nov 06, 2021 |
| ASRock        | H81M-DG4                    | Desktop     | [33d4154b93](https://linux-hardware.org/?probe=33d4154b93) | Nov 06, 2021 |
| Dell          | Precision 7510              | Notebook    | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7e09d7d036](https://linux-hardware.org/?probe=7e09d7d036) | Nov 04, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [745d661721](https://linux-hardware.org/?probe=745d661721) | Nov 03, 2021 |
| HP            | 630                         | Notebook    | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [f7630e472c](https://linux-hardware.org/?probe=f7630e472c) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [000c804ed5](https://linux-hardware.org/?probe=000c804ed5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T470 20HES01100    | Notebook    | [d3c8a48b29](https://linux-hardware.org/?probe=d3c8a48b29) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [54e81a5d8d](https://linux-hardware.org/?probe=54e81a5d8d) | Nov 02, 2021 |
| Biostar       | J3060NH                     | Desktop     | [45dab1bbf8](https://linux-hardware.org/?probe=45dab1bbf8) | Nov 02, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| ASUSTek       | K53E                        | Notebook    | [a51c252738](https://linux-hardware.org/?probe=a51c252738) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [f581cf8319](https://linux-hardware.org/?probe=f581cf8319) | Nov 01, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [6e17fb6ea4](https://linux-hardware.org/?probe=6e17fb6ea4) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [77006702f8](https://linux-hardware.org/?probe=77006702f8) | Oct 31, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [381023907e](https://linux-hardware.org/?probe=381023907e) | Oct 31, 2021 |
| Intel         | NUC11PHBi7 M26151-403       | Mini pc     | [7f8e6d2da9](https://linux-hardware.org/?probe=7f8e6d2da9) | Oct 31, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [35d876d2dc](https://linux-hardware.org/?probe=35d876d2dc) | Oct 30, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8c2b6cf453](https://linux-hardware.org/?probe=8c2b6cf453) | Oct 30, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [9e0858267b](https://linux-hardware.org/?probe=9e0858267b) | Oct 29, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [d3a4772e4e](https://linux-hardware.org/?probe=d3a4772e4e) | Oct 29, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Razer         | Blade                       | Notebook    | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| ASRock        | B360M Performance           | Desktop     | [2ff008a28d](https://linux-hardware.org/?probe=2ff008a28d) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d0cb96f5b2](https://linux-hardware.org/?probe=d0cb96f5b2) | Oct 26, 2021 |
| Dell          | Latitude E6540              | Notebook    | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eaf56ad62b](https://linux-hardware.org/?probe=eaf56ad62b) | Oct 25, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [7046d52a8d](https://linux-hardware.org/?probe=7046d52a8d) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [46651b942b](https://linux-hardware.org/?probe=46651b942b) | Oct 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d53c49a17f](https://linux-hardware.org/?probe=d53c49a17f) | Oct 23, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [be5c338f64](https://linux-hardware.org/?probe=be5c338f64) | Oct 22, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| ASUSTek       | K53E                        | Notebook    | [e7be61df28](https://linux-hardware.org/?probe=e7be61df28) | Oct 21, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [aff8edafa4](https://linux-hardware.org/?probe=aff8edafa4) | Oct 20, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [94848f2347](https://linux-hardware.org/?probe=94848f2347) | Oct 19, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [08715cfcc4](https://linux-hardware.org/?probe=08715cfcc4) | Oct 18, 2021 |
| MSI           | B150 PC MATE                | Desktop     | [f2e71b602e](https://linux-hardware.org/?probe=f2e71b602e) | Oct 18, 2021 |
| Pegatron      | 2AD4                        | Desktop     | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3d443bfe09](https://linux-hardware.org/?probe=3d443bfe09) | Oct 18, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| Dell          | Latitude E7440              | Notebook    | [98c988645f](https://linux-hardware.org/?probe=98c988645f) | Oct 18, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [d5bcf80b27](https://linux-hardware.org/?probe=d5bcf80b27) | Oct 17, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3061eaa067](https://linux-hardware.org/?probe=3061eaa067) | Oct 17, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [274cba3955](https://linux-hardware.org/?probe=274cba3955) | Oct 17, 2021 |
| Acer          | Aspire SW5-173              | Notebook    | [38872d1422](https://linux-hardware.org/?probe=38872d1422) | Oct 17, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [d9cd722532](https://linux-hardware.org/?probe=d9cd722532) | Oct 17, 2021 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [0c063b9772](https://linux-hardware.org/?probe=0c063b9772) | Oct 17, 2021 |
| ASUSTek       | N53Jq                       | Notebook    | [3cd3bb5eae](https://linux-hardware.org/?probe=3cd3bb5eae) | Oct 16, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [56fe4ab8a1](https://linux-hardware.org/?probe=56fe4ab8a1) | Oct 16, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| Dell          | Precision M4800             | Notebook    | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8fbafb0d7e](https://linux-hardware.org/?probe=8fbafb0d7e) | Oct 16, 2021 |
| System76      | Pangolin                    | Notebook    | [e4fb2b6b8a](https://linux-hardware.org/?probe=e4fb2b6b8a) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [2a03ec745f](https://linux-hardware.org/?probe=2a03ec745f) | Oct 16, 2021 |
| HP            | 8768 A                      | Desktop     | [bd722ad5d5](https://linux-hardware.org/?probe=bd722ad5d5) | Oct 15, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e16a7eaba9](https://linux-hardware.org/?probe=e16a7eaba9) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [eed2a8b965](https://linux-hardware.org/?probe=eed2a8b965) | Oct 15, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e025ccbf40](https://linux-hardware.org/?probe=e025ccbf40) | Oct 15, 2021 |
| ASUSTek       | K53E                        | Notebook    | [9f59e9fe10](https://linux-hardware.org/?probe=9f59e9fe10) | Oct 14, 2021 |
| Dell          | 0RM5DR A00                  | Desktop     | [c35c2fd772](https://linux-hardware.org/?probe=c35c2fd772) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d5411b3f0](https://linux-hardware.org/?probe=3d5411b3f0) | Oct 13, 2021 |
| Dell          | Precision 7510              | Notebook    | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [eb4a97ceef](https://linux-hardware.org/?probe=eb4a97ceef) | Oct 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a94b3893c1](https://linux-hardware.org/?probe=a94b3893c1) | Oct 11, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | Notebook    | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| ASUSTek       | K53E                        | Notebook    | [bbb5cfe8b9](https://linux-hardware.org/?probe=bbb5cfe8b9) | Oct 10, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [fea72dd4e7](https://linux-hardware.org/?probe=fea72dd4e7) | Oct 10, 2021 |
| Razer         | Blade Stealth               | Notebook    | [82e8aefe39](https://linux-hardware.org/?probe=82e8aefe39) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [e309ba4276](https://linux-hardware.org/?probe=e309ba4276) | Oct 09, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [e4e8fba89b](https://linux-hardware.org/?probe=e4e8fba89b) | Oct 09, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [59193a23d9](https://linux-hardware.org/?probe=59193a23d9) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [d8a64024f9](https://linux-hardware.org/?probe=d8a64024f9) | Oct 07, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f50b61b450](https://linux-hardware.org/?probe=f50b61b450) | Oct 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [eb87784b09](https://linux-hardware.org/?probe=eb87784b09) | Oct 06, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [bd9fe373d2](https://linux-hardware.org/?probe=bd9fe373d2) | Oct 06, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [2ff9b97589](https://linux-hardware.org/?probe=2ff9b97589) | Oct 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [ceefec9a7f](https://linux-hardware.org/?probe=ceefec9a7f) | Oct 06, 2021 |
| ASUSTek       | K53E                        | Notebook    | [b71c09ae16](https://linux-hardware.org/?probe=b71c09ae16) | Oct 04, 2021 |
| ASUSTek       | K53E                        | Notebook    | [6ccfe2739d](https://linux-hardware.org/?probe=6ccfe2739d) | Oct 04, 2021 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d9637236c2](https://linux-hardware.org/?probe=d9637236c2) | Oct 04, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [e5d1cb1742](https://linux-hardware.org/?probe=e5d1cb1742) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [9bec53673d](https://linux-hardware.org/?probe=9bec53673d) | Oct 03, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [1129266f95](https://linux-hardware.org/?probe=1129266f95) | Oct 03, 2021 |
| ASUSTek       | X99-A                       | Desktop     | [8645db4302](https://linux-hardware.org/?probe=8645db4302) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [3c24d27d51](https://linux-hardware.org/?probe=3c24d27d51) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1585f476de](https://linux-hardware.org/?probe=1585f476de) | Oct 02, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [1e67c40ae2](https://linux-hardware.org/?probe=1e67c40ae2) | Oct 02, 2021 |
| Dell          | Latitude 5410               | Notebook    | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [2642c47cca](https://linux-hardware.org/?probe=2642c47cca) | Sep 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ee806bc406](https://linux-hardware.org/?probe=ee806bc406) | Sep 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [252520800c](https://linux-hardware.org/?probe=252520800c) | Sep 30, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [4ee2cf61ef](https://linux-hardware.org/?probe=4ee2cf61ef) | Sep 29, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [34b6bc562c](https://linux-hardware.org/?probe=34b6bc562c) | Sep 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [45605570fe](https://linux-hardware.org/?probe=45605570fe) | Sep 29, 2021 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d0f4eaa9f8](https://linux-hardware.org/?probe=d0f4eaa9f8) | Sep 29, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4642e930ca](https://linux-hardware.org/?probe=4642e930ca) | Sep 28, 2021 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [b0981c3629](https://linux-hardware.org/?probe=b0981c3629) | Sep 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [b70d12e2f5](https://linux-hardware.org/?probe=b70d12e2f5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [9cd2ba74a0](https://linux-hardware.org/?probe=9cd2ba74a0) | Sep 27, 2021 |
| ASUSTek       | K53E                        | Notebook    | [2e166e4316](https://linux-hardware.org/?probe=2e166e4316) | Sep 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [557d02fbf7](https://linux-hardware.org/?probe=557d02fbf7) | Sep 27, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [baec321ff8](https://linux-hardware.org/?probe=baec321ff8) | Sep 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e47c168067](https://linux-hardware.org/?probe=e47c168067) | Sep 25, 2021 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c8d45803a2](https://linux-hardware.org/?probe=c8d45803a2) | Sep 25, 2021 |
| Supermicro    | X8DTH                       | Server      | [d3dc168a2a](https://linux-hardware.org/?probe=d3dc168a2a) | Sep 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS07N0... | Notebook    | [cb83c57f1c](https://linux-hardware.org/?probe=cb83c57f1c) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | Notebook    | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [434da8cb2d](https://linux-hardware.org/?probe=434da8cb2d) | Sep 24, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [de3b970f84](https://linux-hardware.org/?probe=de3b970f84) | Sep 23, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [7d9277109c](https://linux-hardware.org/?probe=7d9277109c) | Sep 23, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| ASUSTek       | K53E                        | Notebook    | [32ee9b304e](https://linux-hardware.org/?probe=32ee9b304e) | Sep 23, 2021 |
| Lenovo        | Yoga C740 81TC              | Convertible | [0263be5c11](https://linux-hardware.org/?probe=0263be5c11) | Sep 23, 2021 |
| Toshiba       | IS 1442                     | Notebook    | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [92e151e105](https://linux-hardware.org/?probe=92e151e105) | Sep 22, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [8a40803271](https://linux-hardware.org/?probe=8a40803271) | Sep 22, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [72b58edccd](https://linux-hardware.org/?probe=72b58edccd) | Sep 21, 2021 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [9c968d26f7](https://linux-hardware.org/?probe=9c968d26f7) | Sep 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [855a10f536](https://linux-hardware.org/?probe=855a10f536) | Sep 21, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [2aab2f6ffb](https://linux-hardware.org/?probe=2aab2f6ffb) | Sep 21, 2021 |
| Lenovo        | 36C5 SDK0J40709 WIN 3259... | Desktop     | [49e564cb99](https://linux-hardware.org/?probe=49e564cb99) | Sep 21, 2021 |
| Biostar       | J3060NH                     | Desktop     | [f3f6eeeb90](https://linux-hardware.org/?probe=f3f6eeeb90) | Sep 20, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [75c3385947](https://linux-hardware.org/?probe=75c3385947) | Sep 20, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7f635cc338](https://linux-hardware.org/?probe=7f635cc338) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bd2cfcf1ee](https://linux-hardware.org/?probe=bd2cfcf1ee) | Sep 20, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [17c3ec978f](https://linux-hardware.org/?probe=17c3ec978f) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| ASUSTek       | K53E                        | Notebook    | [9b95329be6](https://linux-hardware.org/?probe=9b95329be6) | Sep 20, 2021 |
| Supermicro    | X8DTH                       | Server      | [d6a6b87b9c](https://linux-hardware.org/?probe=d6a6b87b9c) | Sep 20, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [5703e45a96](https://linux-hardware.org/?probe=5703e45a96) | Sep 19, 2021 |
| Maibenben     | PC34 V1.0                   | Desktop     | [10d3e02dfb](https://linux-hardware.org/?probe=10d3e02dfb) | Sep 19, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [c42c7d1ccc](https://linux-hardware.org/?probe=c42c7d1ccc) | Sep 19, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [edb11a70a9](https://linux-hardware.org/?probe=edb11a70a9) | Sep 19, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [67509b31b1](https://linux-hardware.org/?probe=67509b31b1) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a73053ecf3](https://linux-hardware.org/?probe=a73053ecf3) | Sep 18, 2021 |
| HP            | 2B47                        | Desktop     | [d065e6065e](https://linux-hardware.org/?probe=d065e6065e) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [aed9deb51b](https://linux-hardware.org/?probe=aed9deb51b) | Sep 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [19173612af](https://linux-hardware.org/?probe=19173612af) | Sep 18, 2021 |
| ASUSTek       | UX303LN                     | Notebook    | [9c8bb62a98](https://linux-hardware.org/?probe=9c8bb62a98) | Sep 17, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [06d99f6a80](https://linux-hardware.org/?probe=06d99f6a80) | Sep 17, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [34aff1f974](https://linux-hardware.org/?probe=34aff1f974) | Sep 17, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [8c9476bcae](https://linux-hardware.org/?probe=8c9476bcae) | Sep 17, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [de56866167](https://linux-hardware.org/?probe=de56866167) | Sep 17, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [babdb2f68a](https://linux-hardware.org/?probe=babdb2f68a) | Sep 17, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [7a4eb9f28e](https://linux-hardware.org/?probe=7a4eb9f28e) | Sep 17, 2021 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [547ee4e1ea](https://linux-hardware.org/?probe=547ee4e1ea) | Sep 16, 2021 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [90168ebbeb](https://linux-hardware.org/?probe=90168ebbeb) | Sep 16, 2021 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [086b930d7d](https://linux-hardware.org/?probe=086b930d7d) | Sep 16, 2021 |
| ASUSTek       | K53E                        | Notebook    | [c36494f62f](https://linux-hardware.org/?probe=c36494f62f) | Sep 16, 2021 |
| Unknown       | HX90                        | Desktop     | [7a2e84e05d](https://linux-hardware.org/?probe=7a2e84e05d) | Sep 15, 2021 |
| ASUSTek       | K53E                        | Notebook    | [88c9dd1a13](https://linux-hardware.org/?probe=88c9dd1a13) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Lenovo        | 36EB NOK                    | Desktop     | [f8c3745c72](https://linux-hardware.org/?probe=f8c3745c72) | Sep 13, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [efc14ead6c](https://linux-hardware.org/?probe=efc14ead6c) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9782c3ebac](https://linux-hardware.org/?probe=9782c3ebac) | Sep 13, 2021 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [f7f2edee75](https://linux-hardware.org/?probe=f7f2edee75) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | Notebook    | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | ThinkPad T490 20N3S19L00    | Notebook    | [a19eee5494](https://linux-hardware.org/?probe=a19eee5494) | Sep 11, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [bedc045e2c](https://linux-hardware.org/?probe=bedc045e2c) | Sep 11, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [6a38389900](https://linux-hardware.org/?probe=6a38389900) | Sep 11, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | K53E                        | Notebook    | [17cf695269](https://linux-hardware.org/?probe=17cf695269) | Sep 10, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [1cb1281742](https://linux-hardware.org/?probe=1cb1281742) | Sep 10, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [d239ae254a](https://linux-hardware.org/?probe=d239ae254a) | Sep 09, 2021 |
| ASUSTek       | M4A77T                      | Desktop     | [a013c12dff](https://linux-hardware.org/?probe=a013c12dff) | Sep 09, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [044e6afdf4](https://linux-hardware.org/?probe=044e6afdf4) | Sep 09, 2021 |
| Maibenben     | PC34 V1.0                   | Desktop     | [dd82d2282e](https://linux-hardware.org/?probe=dd82d2282e) | Sep 08, 2021 |
| Pegatron      | T14AF                       | Notebook    | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [70c214c3b6](https://linux-hardware.org/?probe=70c214c3b6) | Sep 07, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [866150f656](https://linux-hardware.org/?probe=866150f656) | Sep 07, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [13781fb053](https://linux-hardware.org/?probe=13781fb053) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [db625f00d5](https://linux-hardware.org/?probe=db625f00d5) | Sep 07, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [b094346e99](https://linux-hardware.org/?probe=b094346e99) | Sep 07, 2021 |
| Lenovo        | ThinkPad T450s 20BWS04K0... | Notebook    | [3c7ed2f9b7](https://linux-hardware.org/?probe=3c7ed2f9b7) | Sep 06, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [2b645d2c16](https://linux-hardware.org/?probe=2b645d2c16) | Sep 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8a53d9eccc](https://linux-hardware.org/?probe=8a53d9eccc) | Sep 05, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9a1ae9ad8d](https://linux-hardware.org/?probe=9a1ae9ad8d) | Sep 05, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [4b8701a2b3](https://linux-hardware.org/?probe=4b8701a2b3) | Sep 05, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [ffa40a366f](https://linux-hardware.org/?probe=ffa40a366f) | Sep 05, 2021 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [bc433a2411](https://linux-hardware.org/?probe=bc433a2411) | Sep 04, 2021 |
| Lenovo        | ThinkPad W540 20BHS0LA00    | Notebook    | [d5b967eeee](https://linux-hardware.org/?probe=d5b967eeee) | Sep 04, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [f07151c6ac](https://linux-hardware.org/?probe=f07151c6ac) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e92353130f](https://linux-hardware.org/?probe=e92353130f) | Sep 04, 2021 |
| Dell          | Latitude E6420              | Notebook    | [0d79becf85](https://linux-hardware.org/?probe=0d79becf85) | Sep 03, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [be98863a94](https://linux-hardware.org/?probe=be98863a94) | Sep 02, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [9b10289848](https://linux-hardware.org/?probe=9b10289848) | Sep 02, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [14d10602c8](https://linux-hardware.org/?probe=14d10602c8) | Sep 02, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [1fd99ca58d](https://linux-hardware.org/?probe=1fd99ca58d) | Sep 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [3f152a9790](https://linux-hardware.org/?probe=3f152a9790) | Sep 02, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [61fdddc7a9](https://linux-hardware.org/?probe=61fdddc7a9) | Sep 01, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| MSI           | MEG X570 ACE                | Desktop     | [f393dc1e30](https://linux-hardware.org/?probe=f393dc1e30) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [c3ae9f4793](https://linux-hardware.org/?probe=c3ae9f4793) | Sep 01, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [1167357f4a](https://linux-hardware.org/?probe=1167357f4a) | Aug 30, 2021 |
| Timi          | TM1607                      | Notebook    | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [ba521aca9f](https://linux-hardware.org/?probe=ba521aca9f) | Aug 29, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [81a53f9837](https://linux-hardware.org/?probe=81a53f9837) | Aug 29, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [53da9f0547](https://linux-hardware.org/?probe=53da9f0547) | Aug 29, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [03c1787182](https://linux-hardware.org/?probe=03c1787182) | Aug 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d438e4ea8c](https://linux-hardware.org/?probe=d438e4ea8c) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2263bc71b6](https://linux-hardware.org/?probe=2263bc71b6) | Aug 29, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [64087c4ed2](https://linux-hardware.org/?probe=64087c4ed2) | Aug 29, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [ed21ca940e](https://linux-hardware.org/?probe=ed21ca940e) | Aug 29, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [14f5f8a179](https://linux-hardware.org/?probe=14f5f8a179) | Aug 28, 2021 |
| Dell          | Inspiron 15-5568            | Notebook    | [81b3e142a3](https://linux-hardware.org/?probe=81b3e142a3) | Aug 28, 2021 |
| MSI           | H170 GAMING M3              | Desktop     | [7affee0cde](https://linux-hardware.org/?probe=7affee0cde) | Aug 28, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [11d1c6d073](https://linux-hardware.org/?probe=11d1c6d073) | Aug 28, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [4ab2284059](https://linux-hardware.org/?probe=4ab2284059) | Aug 28, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| Eluktronic... | MAG-15 2070                 | Notebook    | [28b869ed18](https://linux-hardware.org/?probe=28b869ed18) | Aug 28, 2021 |
| ASUSTek       | K53E                        | Notebook    | [c9705b65ba](https://linux-hardware.org/?probe=c9705b65ba) | Aug 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d99ad5002e](https://linux-hardware.org/?probe=d99ad5002e) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f6fa665265](https://linux-hardware.org/?probe=f6fa665265) | Aug 27, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [0dc125b1e6](https://linux-hardware.org/?probe=0dc125b1e6) | Aug 27, 2021 |
| Gigabyte      | A520M H                     | Desktop     | [4b126be26e](https://linux-hardware.org/?probe=4b126be26e) | Aug 26, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [62f508237e](https://linux-hardware.org/?probe=62f508237e) | Aug 25, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6ab2831848](https://linux-hardware.org/?probe=6ab2831848) | Aug 25, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2509d57e06](https://linux-hardware.org/?probe=2509d57e06) | Aug 25, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d5bb51823f](https://linux-hardware.org/?probe=d5bb51823f) | Aug 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f4f4a32442](https://linux-hardware.org/?probe=f4f4a32442) | Aug 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [46e5ae55be](https://linux-hardware.org/?probe=46e5ae55be) | Aug 25, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e6c79ed475](https://linux-hardware.org/?probe=e6c79ed475) | Aug 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0016FR     | Notebook    | [94091b0705](https://linux-hardware.org/?probe=94091b0705) | Aug 24, 2021 |
| Supermicro    | X8DTH                       | Server      | [e7e8b73641](https://linux-hardware.org/?probe=e7e8b73641) | Aug 24, 2021 |
| System76      | Gazelle                     | Notebook    | [b1f5d2f5db](https://linux-hardware.org/?probe=b1f5d2f5db) | Aug 24, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [72d74408e6](https://linux-hardware.org/?probe=72d74408e6) | Aug 24, 2021 |
| System76      | Gazelle                     | Notebook    | [be7855ec0c](https://linux-hardware.org/?probe=be7855ec0c) | Aug 24, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [ad2bc5b140](https://linux-hardware.org/?probe=ad2bc5b140) | Aug 23, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2aafbc0a72](https://linux-hardware.org/?probe=2aafbc0a72) | Aug 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6eb4797b58](https://linux-hardware.org/?probe=6eb4797b58) | Aug 23, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [4e844d3321](https://linux-hardware.org/?probe=4e844d3321) | Aug 22, 2021 |
| ASRock        | X299 Taichi CLX             | Desktop     | [968a7cc18e](https://linux-hardware.org/?probe=968a7cc18e) | Aug 22, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [7af8fc72d4](https://linux-hardware.org/?probe=7af8fc72d4) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [83c1674e38](https://linux-hardware.org/?probe=83c1674e38) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6dbfd72cd8](https://linux-hardware.org/?probe=6dbfd72cd8) | Aug 21, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [5df36dba53](https://linux-hardware.org/?probe=5df36dba53) | Aug 21, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [376acac039](https://linux-hardware.org/?probe=376acac039) | Aug 21, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [24bbd4d06f](https://linux-hardware.org/?probe=24bbd4d06f) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | Notebook    | [e7fd668005](https://linux-hardware.org/?probe=e7fd668005) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [e17fcec0b4](https://linux-hardware.org/?probe=e17fcec0b4) | Aug 21, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [bff602ded6](https://linux-hardware.org/?probe=bff602ded6) | Aug 21, 2021 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [57676de735](https://linux-hardware.org/?probe=57676de735) | Aug 21, 2021 |
| Dell          | Inspiron 15-5568            | Notebook    | [7fec9a3a5b](https://linux-hardware.org/?probe=7fec9a3a5b) | Aug 21, 2021 |
| Lenovo        | ThinkPad T440 20B70048US    | Notebook    | [14e8d60953](https://linux-hardware.org/?probe=14e8d60953) | Aug 21, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [a679909847](https://linux-hardware.org/?probe=a679909847) | Aug 20, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | Notebook    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| ASUSTek       | K53E                        | Notebook    | [a0381bb99a](https://linux-hardware.org/?probe=a0381bb99a) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 7661ZLF        | Notebook    | [d28b77f82f](https://linux-hardware.org/?probe=d28b77f82f) | Aug 19, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC1K    | Notebook    | [d693db633c](https://linux-hardware.org/?probe=d693db633c) | Aug 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [3d348a9d2a](https://linux-hardware.org/?probe=3d348a9d2a) | Aug 18, 2021 |
| ASUSTek       | X556UA                      | Notebook    | [04710b290b](https://linux-hardware.org/?probe=04710b290b) | Aug 18, 2021 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [b2e8193bf3](https://linux-hardware.org/?probe=b2e8193bf3) | Aug 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [95aad48ba3](https://linux-hardware.org/?probe=95aad48ba3) | Aug 17, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [044b381507](https://linux-hardware.org/?probe=044b381507) | Aug 17, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0e50bea137](https://linux-hardware.org/?probe=0e50bea137) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| Razer         | Blade                       | Notebook    | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4cfe1daabe](https://linux-hardware.org/?probe=4cfe1daabe) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ffa5f6a0e](https://linux-hardware.org/?probe=1ffa5f6a0e) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d00e9f1724](https://linux-hardware.org/?probe=d00e9f1724) | Aug 14, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [157096a598](https://linux-hardware.org/?probe=157096a598) | Aug 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0b6bf691c0](https://linux-hardware.org/?probe=0b6bf691c0) | Aug 14, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [4a86f48291](https://linux-hardware.org/?probe=4a86f48291) | Aug 14, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [1f7bc2a4a6](https://linux-hardware.org/?probe=1f7bc2a4a6) | Aug 13, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [7a8a93a361](https://linux-hardware.org/?probe=7a8a93a361) | Aug 12, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [aeae754f0f](https://linux-hardware.org/?probe=aeae754f0f) | Aug 12, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [e42d32bf2a](https://linux-hardware.org/?probe=e42d32bf2a) | Aug 12, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [835e8af58f](https://linux-hardware.org/?probe=835e8af58f) | Aug 12, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b2227d98e6](https://linux-hardware.org/?probe=b2227d98e6) | Aug 11, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [9d26562113](https://linux-hardware.org/?probe=9d26562113) | Aug 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| Intel         | X99                         | Desktop     | [61e528cf30](https://linux-hardware.org/?probe=61e528cf30) | Aug 09, 2021 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [5aced87a3f](https://linux-hardware.org/?probe=5aced87a3f) | Aug 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [e9d2ccb049](https://linux-hardware.org/?probe=e9d2ccb049) | Aug 09, 2021 |
| ASUSTek       | K53E                        | Notebook    | [e8fff6624c](https://linux-hardware.org/?probe=e8fff6624c) | Aug 09, 2021 |
| Biostar       | J3060NH                     | Desktop     | [02c79db236](https://linux-hardware.org/?probe=02c79db236) | Aug 09, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [7b26cd5c2b](https://linux-hardware.org/?probe=7b26cd5c2b) | Aug 08, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [5f24fa8f98](https://linux-hardware.org/?probe=5f24fa8f98) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [51115b9f9f](https://linux-hardware.org/?probe=51115b9f9f) | Aug 08, 2021 |
| MSI           | B150 PC MATE                | Desktop     | [ba7d5b0b10](https://linux-hardware.org/?probe=ba7d5b0b10) | Aug 08, 2021 |
| ASUSTek       | K53E                        | Notebook    | [5469077205](https://linux-hardware.org/?probe=5469077205) | Aug 07, 2021 |
| Intel         | X99                         | Desktop     | [73ed6726f7](https://linux-hardware.org/?probe=73ed6726f7) | Aug 07, 2021 |
| Intel         | X99                         | Desktop     | [5566d7fc66](https://linux-hardware.org/?probe=5566d7fc66) | Aug 07, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b726ceaba4](https://linux-hardware.org/?probe=b726ceaba4) | Aug 07, 2021 |
| Lenovo        | ThinkPad W541 20EF0000US    | Notebook    | [6150ef8ebc](https://linux-hardware.org/?probe=6150ef8ebc) | Aug 07, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [6222e37530](https://linux-hardware.org/?probe=6222e37530) | Aug 06, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3d75016d62](https://linux-hardware.org/?probe=3d75016d62) | Aug 06, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| ASUSTek       | K53E                        | Notebook    | [abf75647a9](https://linux-hardware.org/?probe=abf75647a9) | Aug 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| Acer          | Nitro AN515-53              | Notebook    | [baf0ccecb1](https://linux-hardware.org/?probe=baf0ccecb1) | Aug 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [c434457251](https://linux-hardware.org/?probe=c434457251) | Aug 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [1e7666d492](https://linux-hardware.org/?probe=1e7666d492) | Aug 03, 2021 |
| AZW           | SEi                         | Notebook    | [de596531ae](https://linux-hardware.org/?probe=de596531ae) | Aug 02, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Lenovo        | ThinkPad X201 3626GWG       | Notebook    | [3709f5744a](https://linux-hardware.org/?probe=3709f5744a) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | Notebook    | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| ASUSTek       | K53E                        | Notebook    | [2868347889](https://linux-hardware.org/?probe=2868347889) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [2b732e43eb](https://linux-hardware.org/?probe=2b732e43eb) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [68b431bc45](https://linux-hardware.org/?probe=68b431bc45) | Aug 01, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0e44549ee5](https://linux-hardware.org/?probe=0e44549ee5) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [a8e52318c8](https://linux-hardware.org/?probe=a8e52318c8) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [949e4af6a7](https://linux-hardware.org/?probe=949e4af6a7) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING II     | Desktop     | [1219c874c4](https://linux-hardware.org/?probe=1219c874c4) | Jul 30, 2021 |
| ASUSTek       | K53E                        | Notebook    | [bc4f2fef5c](https://linux-hardware.org/?probe=bc4f2fef5c) | Jul 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [65d9b956bc](https://linux-hardware.org/?probe=65d9b956bc) | Jul 30, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e84e4c3d4c](https://linux-hardware.org/?probe=e84e4c3d4c) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [43cbf83241](https://linux-hardware.org/?probe=43cbf83241) | Jul 29, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [0904b136a3](https://linux-hardware.org/?probe=0904b136a3) | Jul 29, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [35206ac976](https://linux-hardware.org/?probe=35206ac976) | Jul 29, 2021 |
| Dell          | Precision 7520              | Notebook    | [bb1844c704](https://linux-hardware.org/?probe=bb1844c704) | Jul 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [67ccae17d3](https://linux-hardware.org/?probe=67ccae17d3) | Jul 28, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [3f0188a6fd](https://linux-hardware.org/?probe=3f0188a6fd) | Jul 28, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| ASUSTek       | K53E                        | Notebook    | [45f958be8e](https://linux-hardware.org/?probe=45f958be8e) | Jul 26, 2021 |
| ASUSTek       | K53E                        | Notebook    | [906c44e1dd](https://linux-hardware.org/?probe=906c44e1dd) | Jul 26, 2021 |
| Lenovo        | IdeaPad FLEX 5-1570 81CA    | Convertible | [ccb36e2c39](https://linux-hardware.org/?probe=ccb36e2c39) | Jul 26, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [41b4ea65d2](https://linux-hardware.org/?probe=41b4ea65d2) | Jul 26, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0e4c994a10](https://linux-hardware.org/?probe=0e4c994a10) | Jul 25, 2021 |
| ASUSTek       | K53E                        | Notebook    | [6246986bb2](https://linux-hardware.org/?probe=6246986bb2) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [c73718bf7a](https://linux-hardware.org/?probe=c73718bf7a) | Jul 23, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| Dell          | Latitude 5410               | Notebook    | [cb463b1fc3](https://linux-hardware.org/?probe=cb463b1fc3) | Jul 22, 2021 |
| HP            | Stream Notebook PC 13       | Notebook    | [6631c46029](https://linux-hardware.org/?probe=6631c46029) | Jul 22, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| Gigabyte      | P85-D3                      | Desktop     | [34c0c89c1e](https://linux-hardware.org/?probe=34c0c89c1e) | Jul 21, 2021 |
| ASUSTek       | K53E                        | Notebook    | [b61f2b460f](https://linux-hardware.org/?probe=b61f2b460f) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [64f0e3b193](https://linux-hardware.org/?probe=64f0e3b193) | Jul 20, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [8b1a8c783b](https://linux-hardware.org/?probe=8b1a8c783b) | Jul 20, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [eedd331195](https://linux-hardware.org/?probe=eedd331195) | Jul 20, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ece0155c70](https://linux-hardware.org/?probe=ece0155c70) | Jul 20, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [1ad0ca0404](https://linux-hardware.org/?probe=1ad0ca0404) | Jul 19, 2021 |
| Dell          | Latitude 7370               | Notebook    | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4cb2daf424](https://linux-hardware.org/?probe=4cb2daf424) | Jul 16, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [be2edf1657](https://linux-hardware.org/?probe=be2edf1657) | Jul 14, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [672a2b3117](https://linux-hardware.org/?probe=672a2b3117) | Jul 14, 2021 |
| HP            | Notebook                    | Notebook    | [021a011da8](https://linux-hardware.org/?probe=021a011da8) | Jul 13, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [72497bac92](https://linux-hardware.org/?probe=72497bac92) | Jul 12, 2021 |
| ASUSTek       | K53E                        | Notebook    | [8e034623d9](https://linux-hardware.org/?probe=8e034623d9) | Jul 12, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [1547ca7da5](https://linux-hardware.org/?probe=1547ca7da5) | Jul 12, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7a44c0b8e6](https://linux-hardware.org/?probe=7a44c0b8e6) | Jul 12, 2021 |
| Lenovo        | Yoga C740 81TC              | Convertible | [748c23ca88](https://linux-hardware.org/?probe=748c23ca88) | Jul 12, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [af549dc0a9](https://linux-hardware.org/?probe=af549dc0a9) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [9779eaca87](https://linux-hardware.org/?probe=9779eaca87) | Jul 11, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [329bbc8c40](https://linux-hardware.org/?probe=329bbc8c40) | Jul 10, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [2114ad4f9e](https://linux-hardware.org/?probe=2114ad4f9e) | Jul 10, 2021 |
| Lenovo        | Yoga C740 81TC              | Convertible | [a892538722](https://linux-hardware.org/?probe=a892538722) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [a469d525e3](https://linux-hardware.org/?probe=a469d525e3) | Jul 10, 2021 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [fc7d66f096](https://linux-hardware.org/?probe=fc7d66f096) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [252e038506](https://linux-hardware.org/?probe=252e038506) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [bb7d68bae6](https://linux-hardware.org/?probe=bb7d68bae6) | Jul 08, 2021 |
| Lenovo        | Yoga C740 81TC              | Convertible | [b0b211a9c6](https://linux-hardware.org/?probe=b0b211a9c6) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [4ed05b4d7b](https://linux-hardware.org/?probe=4ed05b4d7b) | Jul 07, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [f1f413aced](https://linux-hardware.org/?probe=f1f413aced) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6f489566ae](https://linux-hardware.org/?probe=6f489566ae) | Jul 06, 2021 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [4fb535811d](https://linux-hardware.org/?probe=4fb535811d) | Jul 05, 2021 |
| ASUSTek       | Q550LF                      | Notebook    | [3aafd6f8a6](https://linux-hardware.org/?probe=3aafd6f8a6) | Jul 05, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [366ee7e017](https://linux-hardware.org/?probe=366ee7e017) | Jul 04, 2021 |
| Dell          | Latitude 7480               | Notebook    | [827e1b8a21](https://linux-hardware.org/?probe=827e1b8a21) | Jul 04, 2021 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [7e6ee2f561](https://linux-hardware.org/?probe=7e6ee2f561) | Jul 04, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [3c8630ec48](https://linux-hardware.org/?probe=3c8630ec48) | Jul 04, 2021 |
| Notebook      | P95_HP                      | Notebook    | [8aa8037e16](https://linux-hardware.org/?probe=8aa8037e16) | Jul 03, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d3e26d256d](https://linux-hardware.org/?probe=d3e26d256d) | Jul 03, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | Notebook    | [e08d79f016](https://linux-hardware.org/?probe=e08d79f016) | Jul 02, 2021 |
| ASRock        | Z370 Killer SLI/ac          | Desktop     | [ff0be1b59c](https://linux-hardware.org/?probe=ff0be1b59c) | Jul 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | Notebook    | [06e8c86830](https://linux-hardware.org/?probe=06e8c86830) | Jul 02, 2021 |
| HP            | 250 G1                      | Notebook    | [bc56e9fe6f](https://linux-hardware.org/?probe=bc56e9fe6f) | Jul 02, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8cf6670ab0](https://linux-hardware.org/?probe=8cf6670ab0) | Jul 02, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c0ed3a3c09](https://linux-hardware.org/?probe=c0ed3a3c09) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [ea85c0f143](https://linux-hardware.org/?probe=ea85c0f143) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [beb6e31fa9](https://linux-hardware.org/?probe=beb6e31fa9) | Jul 02, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [c0c53f7ebf](https://linux-hardware.org/?probe=c0c53f7ebf) | Jul 01, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [01f81586c8](https://linux-hardware.org/?probe=01f81586c8) | Jul 01, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e79d247254](https://linux-hardware.org/?probe=e79d247254) | Jul 01, 2021 |
| Acer          | Swift SF314-41G             | Notebook    | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [bbe226bce0](https://linux-hardware.org/?probe=bbe226bce0) | Jun 29, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [0a8dac703d](https://linux-hardware.org/?probe=0a8dac703d) | Jun 29, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [9f586c4fda](https://linux-hardware.org/?probe=9f586c4fda) | Jun 28, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [924bb2e204](https://linux-hardware.org/?probe=924bb2e204) | Jun 28, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [aac1bf4737](https://linux-hardware.org/?probe=aac1bf4737) | Jun 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [127874b25b](https://linux-hardware.org/?probe=127874b25b) | Jun 28, 2021 |
| ASUSTek       | K53E                        | Notebook    | [3ad8363a7d](https://linux-hardware.org/?probe=3ad8363a7d) | Jun 28, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [ceab39c39a](https://linux-hardware.org/?probe=ceab39c39a) | Jun 28, 2021 |
| Acer          | Predator G3-572             | Notebook    | [982137c856](https://linux-hardware.org/?probe=982137c856) | Jun 28, 2021 |
| Lenovo        | ThinkPad X240 20AM001RGE    | Notebook    | [5e80a2492e](https://linux-hardware.org/?probe=5e80a2492e) | Jun 28, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [29dedcc0c7](https://linux-hardware.org/?probe=29dedcc0c7) | Jun 28, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [c4be5b9bb3](https://linux-hardware.org/?probe=c4be5b9bb3) | Jun 28, 2021 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [ca207b7cd3](https://linux-hardware.org/?probe=ca207b7cd3) | Jun 28, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| AZW           | GT-R                        | Notebook    | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [e6a1412110](https://linux-hardware.org/?probe=e6a1412110) | Jun 28, 2021 |
| Lenovo        | 36DF SDK0J40709 WIN 3259... | All in one  | [caaf57f888](https://linux-hardware.org/?probe=caaf57f888) | Jun 28, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [5fd8e985e9](https://linux-hardware.org/?probe=5fd8e985e9) | Jun 28, 2021 |
| ASUSTek       | ZenBook UX562IA_UM562IA     | Convertible | [8e0a4f8e98](https://linux-hardware.org/?probe=8e0a4f8e98) | Jun 27, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [08c0ec2fb7](https://linux-hardware.org/?probe=08c0ec2fb7) | Jun 27, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [cbf1953567](https://linux-hardware.org/?probe=cbf1953567) | Jun 27, 2021 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [d48faf5072](https://linux-hardware.org/?probe=d48faf5072) | Jun 27, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [6c7968cf75](https://linux-hardware.org/?probe=6c7968cf75) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [58933ebb06](https://linux-hardware.org/?probe=58933ebb06) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Toshiba       | Satellite C600              | Notebook    | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [a07552d987](https://linux-hardware.org/?probe=a07552d987) | Jun 24, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [dbc4494db2](https://linux-hardware.org/?probe=dbc4494db2) | Jun 23, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [9604635e51](https://linux-hardware.org/?probe=9604635e51) | Jun 23, 2021 |
| MSI           | B85M-E45                    | Desktop     | [5508d6a84e](https://linux-hardware.org/?probe=5508d6a84e) | Jun 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0bd06bbe0b](https://linux-hardware.org/?probe=0bd06bbe0b) | Jun 22, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [58070bd585](https://linux-hardware.org/?probe=58070bd585) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a347deb07c](https://linux-hardware.org/?probe=a347deb07c) | Jun 22, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [1155abf435](https://linux-hardware.org/?probe=1155abf435) | Jun 22, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Lenovo        | IdeaPad FLEX 5-1570 81CA    | Convertible | [16b6f0ce3b](https://linux-hardware.org/?probe=16b6f0ce3b) | Jun 18, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [7e2d8c8d09](https://linux-hardware.org/?probe=7e2d8c8d09) | Jun 17, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [5246eabc5f](https://linux-hardware.org/?probe=5246eabc5f) | Jun 17, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | Notebook    | [22aabc71ef](https://linux-hardware.org/?probe=22aabc71ef) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | Notebook    | [99a0a332ec](https://linux-hardware.org/?probe=99a0a332ec) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [b81aa5226f](https://linux-hardware.org/?probe=b81aa5226f) | Jun 17, 2021 |
| Lenovo        | IdeaPad FLEX 5-1570 81CA    | Convertible | [046e8bd427](https://linux-hardware.org/?probe=046e8bd427) | Jun 17, 2021 |
| Lenovo        | IdeaPad FLEX 5-1570 81CA    | Convertible | [d0b80d70d5](https://linux-hardware.org/?probe=d0b80d70d5) | Jun 17, 2021 |
| Alienware     | 17                          | Notebook    | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [ac8e80e0cc](https://linux-hardware.org/?probe=ac8e80e0cc) | Jun 15, 2021 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [8d9cf5ea94](https://linux-hardware.org/?probe=8d9cf5ea94) | Jun 15, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [2f36a0ce80](https://linux-hardware.org/?probe=2f36a0ce80) | Jun 15, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [42e10b10fd](https://linux-hardware.org/?probe=42e10b10fd) | Jun 15, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [cc36c68569](https://linux-hardware.org/?probe=cc36c68569) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [a6cf581d50](https://linux-hardware.org/?probe=a6cf581d50) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [48c28ecda7](https://linux-hardware.org/?probe=48c28ecda7) | Jun 14, 2021 |
| Dell          | Inspiron 5485 2n1           | Notebook    | [cda45b1f3c](https://linux-hardware.org/?probe=cda45b1f3c) | Jun 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [fc9d4907b2](https://linux-hardware.org/?probe=fc9d4907b2) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [908df2d475](https://linux-hardware.org/?probe=908df2d475) | Jun 13, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [2aa987fc0d](https://linux-hardware.org/?probe=2aa987fc0d) | Jun 13, 2021 |
| Medion        | Erazer X7841 MD99556        | Notebook    | [a15e0c5ae0](https://linux-hardware.org/?probe=a15e0c5ae0) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [f6b6b11c24](https://linux-hardware.org/?probe=f6b6b11c24) | Jun 12, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [20ff390b75](https://linux-hardware.org/?probe=20ff390b75) | Jun 11, 2021 |
| ASUSTek       | D425MC                      | Desktop     | [aa893a2c50](https://linux-hardware.org/?probe=aa893a2c50) | Jun 10, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [64db1224d0](https://linux-hardware.org/?probe=64db1224d0) | Jun 10, 2021 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [758cd92d87](https://linux-hardware.org/?probe=758cd92d87) | Jun 10, 2021 |
| HP            | Elite Dragonfly             | Convertible | [a2410d7bf9](https://linux-hardware.org/?probe=a2410d7bf9) | Jun 07, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [172643ea98](https://linux-hardware.org/?probe=172643ea98) | Jun 07, 2021 |
| Razer         | Blade                       | Notebook    | [e6ee630e9b](https://linux-hardware.org/?probe=e6ee630e9b) | Jun 06, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [f6f2cf5f89](https://linux-hardware.org/?probe=f6f2cf5f89) | Jun 05, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [7e5e7767c0](https://linux-hardware.org/?probe=7e5e7767c0) | Jun 04, 2021 |
| Lenovo        | ThinkPad X220 4290LD4       | Notebook    | [22bbadb3dd](https://linux-hardware.org/?probe=22bbadb3dd) | Jun 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [db78e09514](https://linux-hardware.org/?probe=db78e09514) | Jun 03, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [f10a48e6cf](https://linux-hardware.org/?probe=f10a48e6cf) | Jun 03, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [63be8e2205](https://linux-hardware.org/?probe=63be8e2205) | Jun 03, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [fa237f560a](https://linux-hardware.org/?probe=fa237f560a) | Jun 02, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [4d799b19db](https://linux-hardware.org/?probe=4d799b19db) | Jun 02, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [ee0630b07c](https://linux-hardware.org/?probe=ee0630b07c) | Jun 02, 2021 |
| Toshiba       | Satellite L635              | Notebook    | [c5883a9da8](https://linux-hardware.org/?probe=c5883a9da8) | Jun 01, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [021617b9a0](https://linux-hardware.org/?probe=021617b9a0) | May 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| Toshiba       | Satellite L635              | Notebook    | [634bc5add8](https://linux-hardware.org/?probe=634bc5add8) | May 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [e18b16565f](https://linux-hardware.org/?probe=e18b16565f) | May 29, 2021 |
| Toshiba       | Satellite R630              | Notebook    | [0c557895be](https://linux-hardware.org/?probe=0c557895be) | May 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b7175abf98](https://linux-hardware.org/?probe=b7175abf98) | May 29, 2021 |
| Daten Tecn... | ESTELAR                     | Notebook    | [f19e7920ca](https://linux-hardware.org/?probe=f19e7920ca) | May 29, 2021 |
| Dell          | Inspiron 7386               | Convertible | [b07a0cf706](https://linux-hardware.org/?probe=b07a0cf706) | May 27, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| Intel         | H61                         | Desktop     | [3b35e80002](https://linux-hardware.org/?probe=3b35e80002) | May 26, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e71b786be5](https://linux-hardware.org/?probe=e71b786be5) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [1daf88898e](https://linux-hardware.org/?probe=1daf88898e) | May 24, 2021 |
| Huanan        | X99-F8                      | Desktop     | [40e64a9bd9](https://linux-hardware.org/?probe=40e64a9bd9) | May 24, 2021 |
| ZOTAC         | ZBOXNANO-AQ02               | Mini pc     | [eb76ff1c3f](https://linux-hardware.org/?probe=eb76ff1c3f) | May 24, 2021 |
| Huanan        | X99-F8                      | Desktop     | [0158c76f85](https://linux-hardware.org/?probe=0158c76f85) | May 23, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [f98f189d70](https://linux-hardware.org/?probe=f98f189d70) | May 22, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [dc84154113](https://linux-hardware.org/?probe=dc84154113) | May 22, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [affeebefe4](https://linux-hardware.org/?probe=affeebefe4) | May 21, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [302b62a5c7](https://linux-hardware.org/?probe=302b62a5c7) | May 20, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7af662cb94](https://linux-hardware.org/?probe=7af662cb94) | May 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [c188ca866f](https://linux-hardware.org/?probe=c188ca866f) | May 18, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a77184c9c7](https://linux-hardware.org/?probe=a77184c9c7) | May 16, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cf1638450e](https://linux-hardware.org/?probe=cf1638450e) | May 14, 2021 |
| Foxconn       | A85GM                       | Desktop     | [f75d2cd0a7](https://linux-hardware.org/?probe=f75d2cd0a7) | May 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [0d44d30be1](https://linux-hardware.org/?probe=0d44d30be1) | May 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [00aa4c11f4](https://linux-hardware.org/?probe=00aa4c11f4) | May 13, 2021 |
| Sony          | SVE14125CXP                 | Notebook    | [23d5e048cb](https://linux-hardware.org/?probe=23d5e048cb) | May 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [28f6f5a90b](https://linux-hardware.org/?probe=28f6f5a90b) | May 12, 2021 |
| Toshiba       | Satellite L50-A-19N         | Notebook    | [988020930b](https://linux-hardware.org/?probe=988020930b) | May 12, 2021 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [eb55e9a1cd](https://linux-hardware.org/?probe=eb55e9a1cd) | May 12, 2021 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [e1ebffb1f6](https://linux-hardware.org/?probe=e1ebffb1f6) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [da82b1b43f](https://linux-hardware.org/?probe=da82b1b43f) | May 09, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [6d9e2228c3](https://linux-hardware.org/?probe=6d9e2228c3) | May 05, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [e9fe60f89a](https://linux-hardware.org/?probe=e9fe60f89a) | May 05, 2021 |
| MSI           | B150 PC MATE                | Desktop     | [2289424cac](https://linux-hardware.org/?probe=2289424cac) | May 04, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [4bf4556f96](https://linux-hardware.org/?probe=4bf4556f96) | May 03, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | Notebook    | [ab871dcbe2](https://linux-hardware.org/?probe=ab871dcbe2) | May 01, 2021 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [dc100ee99f](https://linux-hardware.org/?probe=dc100ee99f) | May 01, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [7c6c704c51](https://linux-hardware.org/?probe=7c6c704c51) | Apr 30, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | Notebook    | [f8bbdfd850](https://linux-hardware.org/?probe=f8bbdfd850) | Apr 30, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | Notebook    | [2df93a93d1](https://linux-hardware.org/?probe=2df93a93d1) | Apr 30, 2021 |
| HP            | 250 G1                      | Notebook    | [0810673d99](https://linux-hardware.org/?probe=0810673d99) | Apr 29, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [753d42a4a5](https://linux-hardware.org/?probe=753d42a4a5) | Apr 28, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [5c21c8e3b5](https://linux-hardware.org/?probe=5c21c8e3b5) | Apr 28, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [47da354af9](https://linux-hardware.org/?probe=47da354af9) | Apr 27, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3be3ad06bb](https://linux-hardware.org/?probe=3be3ad06bb) | Apr 26, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [f4a2af7fa8](https://linux-hardware.org/?probe=f4a2af7fa8) | Apr 24, 2021 |
| HP            | 83E9                        | Desktop     | [d9a6f8bf8f](https://linux-hardware.org/?probe=d9a6f8bf8f) | Apr 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [535815022c](https://linux-hardware.org/?probe=535815022c) | Apr 23, 2021 |
| Dell          | Latitude E6440              | Notebook    | [a079078493](https://linux-hardware.org/?probe=a079078493) | Apr 23, 2021 |
| HP            | 255 G2                      | Notebook    | [338785dab3](https://linux-hardware.org/?probe=338785dab3) | Apr 22, 2021 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | Notebook    | [f707b24713](https://linux-hardware.org/?probe=f707b24713) | Apr 22, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [c970ef4e84](https://linux-hardware.org/?probe=c970ef4e84) | Apr 21, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [16ab380d72](https://linux-hardware.org/?probe=16ab380d72) | Apr 21, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [16a33b32ac](https://linux-hardware.org/?probe=16a33b32ac) | Apr 21, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [2b122eb7e6](https://linux-hardware.org/?probe=2b122eb7e6) | Apr 21, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [a071188f1c](https://linux-hardware.org/?probe=a071188f1c) | Apr 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d55735e0db](https://linux-hardware.org/?probe=d55735e0db) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [dc1e0bf320](https://linux-hardware.org/?probe=dc1e0bf320) | Apr 19, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [4601ed2bc4](https://linux-hardware.org/?probe=4601ed2bc4) | Apr 19, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f403f4a2](https://linux-hardware.org/?probe=c2f403f4a2) | Apr 19, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [c642353f62](https://linux-hardware.org/?probe=c642353f62) | Apr 18, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [a66644d8f9](https://linux-hardware.org/?probe=a66644d8f9) | Apr 18, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [eeee3c8078](https://linux-hardware.org/?probe=eeee3c8078) | Apr 18, 2021 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [70928b7215](https://linux-hardware.org/?probe=70928b7215) | Apr 16, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [24b652099d](https://linux-hardware.org/?probe=24b652099d) | Apr 16, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [f0a9a9b376](https://linux-hardware.org/?probe=f0a9a9b376) | Apr 15, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [ba1e3ed32e](https://linux-hardware.org/?probe=ba1e3ed32e) | Apr 15, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7633456df0](https://linux-hardware.org/?probe=7633456df0) | Apr 15, 2021 |
| Intel         | DN2820FYK H24582-202        | Desktop     | [920e36be7e](https://linux-hardware.org/?probe=920e36be7e) | Apr 14, 2021 |
| HP            | 1850                        | Desktop     | [5129384114](https://linux-hardware.org/?probe=5129384114) | Apr 14, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [61b2baa2d1](https://linux-hardware.org/?probe=61b2baa2d1) | Apr 13, 2021 |
| HP            | 1998                        | Desktop     | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [9909625298](https://linux-hardware.org/?probe=9909625298) | Apr 12, 2021 |
| HP            | 1998                        | Desktop     | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Acer          | Predator PH315-52           | Notebook    | [97c81f4b56](https://linux-hardware.org/?probe=97c81f4b56) | Apr 11, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [76b41f73e8](https://linux-hardware.org/?probe=76b41f73e8) | Apr 11, 2021 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [61f0309c59](https://linux-hardware.org/?probe=61f0309c59) | Apr 11, 2021 |
| Toshiba       | PORTEGE Z30t-C              | Notebook    | [39dd5ca43b](https://linux-hardware.org/?probe=39dd5ca43b) | Apr 11, 2021 |
| HP            | Elite Dragonfly             | Convertible | [d284325fcf](https://linux-hardware.org/?probe=d284325fcf) | Apr 10, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [8ceda587e7](https://linux-hardware.org/?probe=8ceda587e7) | Apr 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [337a0c3723](https://linux-hardware.org/?probe=337a0c3723) | Apr 08, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [cd260eee11](https://linux-hardware.org/?probe=cd260eee11) | Apr 08, 2021 |
| HP            | 1850                        | Desktop     | [9472ac815b](https://linux-hardware.org/?probe=9472ac815b) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | Notebook    | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5a663fff6e](https://linux-hardware.org/?probe=5a663fff6e) | Apr 05, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a4c88b2a](https://linux-hardware.org/?probe=59a4c88b2a) | Apr 04, 2021 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [7cf8cfd8f8](https://linux-hardware.org/?probe=7cf8cfd8f8) | Apr 04, 2021 |
| HP            | 3397                        | Desktop     | [53b1e2e13d](https://linux-hardware.org/?probe=53b1e2e13d) | Apr 03, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [77a98a9695](https://linux-hardware.org/?probe=77a98a9695) | Apr 03, 2021 |
| ASRock        | Z270M Extreme4              | Desktop     | [11c057ddb1](https://linux-hardware.org/?probe=11c057ddb1) | Apr 03, 2021 |
| Lenovo        | ThinkPad T480 20L6S27S0P    | Notebook    | [6fc0f5a4b6](https://linux-hardware.org/?probe=6fc0f5a4b6) | Apr 03, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Toshiba       | Satellite C55-A-1N0         | Notebook    | [53fe8e1c6c](https://linux-hardware.org/?probe=53fe8e1c6c) | Mar 31, 2021 |
| Dell          | Latitude E7440              | Notebook    | [e0c5eda63a](https://linux-hardware.org/?probe=e0c5eda63a) | Mar 31, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [151b34a749](https://linux-hardware.org/?probe=151b34a749) | Mar 29, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [e4a8b63e16](https://linux-hardware.org/?probe=e4a8b63e16) | Mar 28, 2021 |
| Dell          | Latitude E7440              | Notebook    | [1c004faf2a](https://linux-hardware.org/?probe=1c004faf2a) | Mar 28, 2021 |
| Toshiba       | Satellite C55-A-1N0         | Notebook    | [d316794d0c](https://linux-hardware.org/?probe=d316794d0c) | Mar 27, 2021 |
| Toshiba       | Satellite C55-A-1N0         | Notebook    | [7fe4a33a38](https://linux-hardware.org/?probe=7fe4a33a38) | Mar 27, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | Notebook    | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| Dell          | Latitude 3580               | Notebook    | [0de8d9cd4c](https://linux-hardware.org/?probe=0de8d9cd4c) | Mar 25, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [9ecdb36d8e](https://linux-hardware.org/?probe=9ecdb36d8e) | Mar 25, 2021 |
| Dell          | Latitude E6530              | Notebook    | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad 11e 20D90020US     | Notebook    | [e5948a4e4c](https://linux-hardware.org/?probe=e5948a4e4c) | Mar 24, 2021 |
| HP            | 158B                        | Desktop     | [837cecdae8](https://linux-hardware.org/?probe=837cecdae8) | Mar 23, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [0348f8af6b](https://linux-hardware.org/?probe=0348f8af6b) | Mar 23, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [1f7a0c0323](https://linux-hardware.org/?probe=1f7a0c0323) | Mar 22, 2021 |
| Dell          | Latitude E4310              | Notebook    | [16025a8970](https://linux-hardware.org/?probe=16025a8970) | Mar 21, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b9018d7c8](https://linux-hardware.org/?probe=9b9018d7c8) | Mar 21, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [be77b62a8a](https://linux-hardware.org/?probe=be77b62a8a) | Mar 21, 2021 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [e17cb89c8c](https://linux-hardware.org/?probe=e17cb89c8c) | Mar 20, 2021 |
| Intel         | B75                         | Desktop     | [cf8a32d6bf](https://linux-hardware.org/?probe=cf8a32d6bf) | Mar 19, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Unknown       | VER                         | Desktop     | [2b66d90e15](https://linux-hardware.org/?probe=2b66d90e15) | Mar 18, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [a5c6af7849](https://linux-hardware.org/?probe=a5c6af7849) | Mar 18, 2021 |
| Dell          | Inspiron 5575               | Notebook    | [4b72276133](https://linux-hardware.org/?probe=4b72276133) | Mar 17, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [79e3573fed](https://linux-hardware.org/?probe=79e3573fed) | Mar 17, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [d91551dac1](https://linux-hardware.org/?probe=d91551dac1) | Mar 17, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [88b10a02fe](https://linux-hardware.org/?probe=88b10a02fe) | Mar 17, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [cabd404cf0](https://linux-hardware.org/?probe=cabd404cf0) | Mar 17, 2021 |
| Dell          | Latitude E6440              | Notebook    | [8eb5c8aaa9](https://linux-hardware.org/?probe=8eb5c8aaa9) | Mar 17, 2021 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [d4aede9ce5](https://linux-hardware.org/?probe=d4aede9ce5) | Mar 17, 2021 |
| ASUSTek       | K501UX                      | Notebook    | [0a3c9ff078](https://linux-hardware.org/?probe=0a3c9ff078) | Mar 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1c133a66fe](https://linux-hardware.org/?probe=1c133a66fe) | Mar 16, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [4b3ec85962](https://linux-hardware.org/?probe=4b3ec85962) | Mar 16, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | G62                         | Notebook    | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b40d3ff1b0](https://linux-hardware.org/?probe=b40d3ff1b0) | Mar 12, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0ab96b7281](https://linux-hardware.org/?probe=0ab96b7281) | Mar 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [db1f9d815c](https://linux-hardware.org/?probe=db1f9d815c) | Mar 12, 2021 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3133dbf834](https://linux-hardware.org/?probe=3133dbf834) | Mar 11, 2021 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [1c74d63cc4](https://linux-hardware.org/?probe=1c74d63cc4) | Mar 10, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [06f7468dab](https://linux-hardware.org/?probe=06f7468dab) | Mar 09, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [3204fa323c](https://linux-hardware.org/?probe=3204fa323c) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| Lenovo        | ThinkPad T570 20H90002GE    | Notebook    | [ce32634171](https://linux-hardware.org/?probe=ce32634171) | Mar 09, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| Lenovo        | MAHOBAY No DPK              | Desktop     | [08769f0d3a](https://linux-hardware.org/?probe=08769f0d3a) | Mar 08, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [6377ea853f](https://linux-hardware.org/?probe=6377ea853f) | Mar 07, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [ba76d096ed](https://linux-hardware.org/?probe=ba76d096ed) | Mar 04, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | Notebook    | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [ad390daa6b](https://linux-hardware.org/?probe=ad390daa6b) | Mar 04, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f9d2730cb4](https://linux-hardware.org/?probe=f9d2730cb4) | Mar 02, 2021 |
| HP            | 18E7                        | Desktop     | [a7389fa350](https://linux-hardware.org/?probe=a7389fa350) | Mar 02, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5db3daf51c](https://linux-hardware.org/?probe=5db3daf51c) | Mar 02, 2021 |
| Dell          | Latitude E6530              | Notebook    | [15b1567c06](https://linux-hardware.org/?probe=15b1567c06) | Feb 27, 2021 |
| Dell          | Latitude E6530              | Notebook    | [519e2218aa](https://linux-hardware.org/?probe=519e2218aa) | Feb 27, 2021 |
| Dell          | 0DF42J A00                  | Desktop     | [0a24bf8dca](https://linux-hardware.org/?probe=0a24bf8dca) | Feb 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [602223a1ab](https://linux-hardware.org/?probe=602223a1ab) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| Toshiba       | Satellite L775              | Notebook    | [670f2c264f](https://linux-hardware.org/?probe=670f2c264f) | Feb 24, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [3defa02f89](https://linux-hardware.org/?probe=3defa02f89) | Feb 24, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [55a00ca46d](https://linux-hardware.org/?probe=55a00ca46d) | Feb 24, 2021 |
| Bluechip C... | BUSINESSline                | Notebook    | [740e39daaa](https://linux-hardware.org/?probe=740e39daaa) | Feb 23, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6bbd1714c4](https://linux-hardware.org/?probe=6bbd1714c4) | Feb 23, 2021 |
| ASRock        | Z270 Pro4                   | Desktop     | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| HP            | 1497                        | Desktop     | [08f2159393](https://linux-hardware.org/?probe=08f2159393) | Feb 20, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [d1f52ba806](https://linux-hardware.org/?probe=d1f52ba806) | Feb 19, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [084be10f62](https://linux-hardware.org/?probe=084be10f62) | Feb 19, 2021 |
| HP            | 18E7                        | Desktop     | [8456b19c7e](https://linux-hardware.org/?probe=8456b19c7e) | Feb 19, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [750999a54f](https://linux-hardware.org/?probe=750999a54f) | Feb 18, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [aac7af965f](https://linux-hardware.org/?probe=aac7af965f) | Feb 18, 2021 |
| Dell          | Latitude 5480               | Notebook    | [41472dbe02](https://linux-hardware.org/?probe=41472dbe02) | Feb 18, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [238564a9fc](https://linux-hardware.org/?probe=238564a9fc) | Feb 17, 2021 |
| Dell          | Latitude E6330              | Notebook    | [b27e52570f](https://linux-hardware.org/?probe=b27e52570f) | Feb 17, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [a11127fa47](https://linux-hardware.org/?probe=a11127fa47) | Feb 16, 2021 |
| Biostar       | J3060NH                     | Desktop     | [710471e54c](https://linux-hardware.org/?probe=710471e54c) | Feb 16, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e121595694](https://linux-hardware.org/?probe=e121595694) | Feb 16, 2021 |
| MSI           | H61M-P31                    | Desktop     | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [3c15f6f889](https://linux-hardware.org/?probe=3c15f6f889) | Feb 14, 2021 |
| HP            | 82F2 A01                    | Desktop     | [dce89bfc5d](https://linux-hardware.org/?probe=dce89bfc5d) | Feb 13, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Biostar       | J3060NH                     | Desktop     | [067e13e287](https://linux-hardware.org/?probe=067e13e287) | Feb 12, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [4ec2149aa3](https://linux-hardware.org/?probe=4ec2149aa3) | Feb 11, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| HP            | 18E7                        | Desktop     | [ea4850a633](https://linux-hardware.org/?probe=ea4850a633) | Feb 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [aa9f19288b](https://linux-hardware.org/?probe=aa9f19288b) | Feb 10, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [710e2aada3](https://linux-hardware.org/?probe=710e2aada3) | Feb 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9534354645](https://linux-hardware.org/?probe=9534354645) | Feb 08, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [041c5bffa5](https://linux-hardware.org/?probe=041c5bffa5) | Feb 07, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [cf9cd8fbf4](https://linux-hardware.org/?probe=cf9cd8fbf4) | Feb 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4448c7c05d](https://linux-hardware.org/?probe=4448c7c05d) | Feb 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64733456e8](https://linux-hardware.org/?probe=64733456e8) | Feb 06, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [ca9d4cd0e7](https://linux-hardware.org/?probe=ca9d4cd0e7) | Feb 06, 2021 |
| Notebook      | N2x0WU                      | Notebook    | [e660e0f0da](https://linux-hardware.org/?probe=e660e0f0da) | Feb 05, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [874d0c0e0e](https://linux-hardware.org/?probe=874d0c0e0e) | Feb 05, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [0c8a1fea22](https://linux-hardware.org/?probe=0c8a1fea22) | Feb 04, 2021 |
| Biostar       | J3060NH                     | Desktop     | [4e74b60668](https://linux-hardware.org/?probe=4e74b60668) | Feb 04, 2021 |
| Sony          | VPCF11J1E                   | Notebook    | [a4c36618e9](https://linux-hardware.org/?probe=a4c36618e9) | Feb 03, 2021 |
| HP            | ENVY 17                     | Notebook    | [7b09b4c5b4](https://linux-hardware.org/?probe=7b09b4c5b4) | Feb 02, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f0a2cff7fc](https://linux-hardware.org/?probe=f0a2cff7fc) | Feb 02, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [0521e66a3f](https://linux-hardware.org/?probe=0521e66a3f) | Feb 01, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [ec70bba0fc](https://linux-hardware.org/?probe=ec70bba0fc) | Feb 01, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [4fe3a3cc83](https://linux-hardware.org/?probe=4fe3a3cc83) | Jan 31, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e3b19bb06](https://linux-hardware.org/?probe=1e3b19bb06) | Jan 30, 2021 |
| Google        | Swanky                      | Notebook    | [c4dd59ca8a](https://linux-hardware.org/?probe=c4dd59ca8a) | Jan 29, 2021 |
| PROLINE       | ProlinePartner              | Desktop     | [ebe3099bba](https://linux-hardware.org/?probe=ebe3099bba) | Jan 28, 2021 |
| PROLINE       | ProlinePartner              | Desktop     | [9f76238b74](https://linux-hardware.org/?probe=9f76238b74) | Jan 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [84e86f5d2c](https://linux-hardware.org/?probe=84e86f5d2c) | Jan 25, 2021 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| Dell          | Latitude D820               | Notebook    | [c4b9edad97](https://linux-hardware.org/?probe=c4b9edad97) | Jan 24, 2021 |
| HP            | 2B47                        | Desktop     | [406d514ed5](https://linux-hardware.org/?probe=406d514ed5) | Jan 24, 2021 |
| Lenovo        | IdeaPad Flex 5 14IIL05 8... | Convertible | [0b867b4aea](https://linux-hardware.org/?probe=0b867b4aea) | Jan 23, 2021 |
| Lenovo        | ThinkPad T61 64659TU        | Notebook    | [6bb7d90da6](https://linux-hardware.org/?probe=6bb7d90da6) | Jan 23, 2021 |
| MSI           | B150 PC MATE                | Desktop     | [66479df053](https://linux-hardware.org/?probe=66479df053) | Jan 23, 2021 |
| Lenovo        | ThinkPad T61 64659TU        | Notebook    | [b302c2489e](https://linux-hardware.org/?probe=b302c2489e) | Jan 23, 2021 |
| ASUSTek       | K56CM                       | Notebook    | [e1da558e84](https://linux-hardware.org/?probe=e1da558e84) | Jan 23, 2021 |
| Lenovo        | ThinkPad X201 3680KC5       | Notebook    | [d91cbb0784](https://linux-hardware.org/?probe=d91cbb0784) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [136f6c27fb](https://linux-hardware.org/?probe=136f6c27fb) | Jan 22, 2021 |
| Medion        | E7222                       | Notebook    | [c5b59cdd1a](https://linux-hardware.org/?probe=c5b59cdd1a) | Jan 21, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e6246a62eb](https://linux-hardware.org/?probe=e6246a62eb) | Jan 20, 2021 |
| Acer          | NU-A515-44-R68D             | Notebook    | [69612ffeb2](https://linux-hardware.org/?probe=69612ffeb2) | Jan 20, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [7482661d1c](https://linux-hardware.org/?probe=7482661d1c) | Jan 19, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [66efbfed55](https://linux-hardware.org/?probe=66efbfed55) | Jan 19, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [0598377b14](https://linux-hardware.org/?probe=0598377b14) | Jan 19, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [fc5afc1dc2](https://linux-hardware.org/?probe=fc5afc1dc2) | Jan 18, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f25a998d4f](https://linux-hardware.org/?probe=f25a998d4f) | Jan 18, 2021 |
| Lenovo        | ThinkPad T440S 20AQ005NU... | Notebook    | [356ab4974a](https://linux-hardware.org/?probe=356ab4974a) | Jan 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [12987dd140](https://linux-hardware.org/?probe=12987dd140) | Jan 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [511d8a9322](https://linux-hardware.org/?probe=511d8a9322) | Jan 18, 2021 |
| Lenovo        | 36EB NOK                    | Desktop     | [9a0f9b96dc](https://linux-hardware.org/?probe=9a0f9b96dc) | Jan 17, 2021 |
| HP            | ENVY Notebook               | Notebook    | [e75216ca48](https://linux-hardware.org/?probe=e75216ca48) | Jan 17, 2021 |
| Dell          | Latitude E6530              | Notebook    | [da4602f931](https://linux-hardware.org/?probe=da4602f931) | Jan 16, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [325809a72d](https://linux-hardware.org/?probe=325809a72d) | Jan 16, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [96664f7b59](https://linux-hardware.org/?probe=96664f7b59) | Jan 16, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [605c9b4d80](https://linux-hardware.org/?probe=605c9b4d80) | Jan 15, 2021 |
| MSI           | X470 GAMING PRO MAX         | Desktop     | [ef19f435be](https://linux-hardware.org/?probe=ef19f435be) | Jan 15, 2021 |
| Dell          | Inspiron 7558               | Notebook    | [272d237def](https://linux-hardware.org/?probe=272d237def) | Jan 15, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| HP            | 82F2 A01                    | Desktop     | [33bc407f2f](https://linux-hardware.org/?probe=33bc407f2f) | Jan 13, 2021 |
| HP            | 82F2 A01                    | Desktop     | [ecf02e9a80](https://linux-hardware.org/?probe=ecf02e9a80) | Jan 13, 2021 |
| Lenovo        | Yoga 900-13ISK 80UE         | Notebook    | [7b790852bf](https://linux-hardware.org/?probe=7b790852bf) | Jan 13, 2021 |
| Acer          | Aspire VN7-792G             | Notebook    | [0b1c2de104](https://linux-hardware.org/?probe=0b1c2de104) | Jan 13, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [8956e9185a](https://linux-hardware.org/?probe=8956e9185a) | Jan 13, 2021 |
| Lenovo        | V155-15API 81V5             | Notebook    | [a3143c0638](https://linux-hardware.org/?probe=a3143c0638) | Jan 13, 2021 |
| Gigabyte      | H310N x.x                   | Desktop     | [bce10fe231](https://linux-hardware.org/?probe=bce10fe231) | Jan 12, 2021 |
| Acer          | NU-A515-44-R68D             | Notebook    | [f45afd1e14](https://linux-hardware.org/?probe=f45afd1e14) | Jan 12, 2021 |
| Unknown       | Intel X79                   | Desktop     | [8aa4df594f](https://linux-hardware.org/?probe=8aa4df594f) | Jan 12, 2021 |
| Dell          | Latitude E6540              | Notebook    | [c6ab95a062](https://linux-hardware.org/?probe=c6ab95a062) | Jan 11, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [7917a1f444](https://linux-hardware.org/?probe=7917a1f444) | Jan 11, 2021 |
| MSI           | 2A9C                        | Desktop     | [5da08b027b](https://linux-hardware.org/?probe=5da08b027b) | Jan 11, 2021 |
| Dell          | Latitude E6540              | Notebook    | [565853d023](https://linux-hardware.org/?probe=565853d023) | Jan 10, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ae2c1ae2d1](https://linux-hardware.org/?probe=ae2c1ae2d1) | Jan 10, 2021 |
| Unknown       | X79                         | Desktop     | [a895be79c6](https://linux-hardware.org/?probe=a895be79c6) | Jan 10, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0d0aa5182b](https://linux-hardware.org/?probe=0d0aa5182b) | Jan 10, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [f1e54c6d1d](https://linux-hardware.org/?probe=f1e54c6d1d) | Jan 09, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6ed403563a](https://linux-hardware.org/?probe=6ed403563a) | Jan 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [42fc68c6da](https://linux-hardware.org/?probe=42fc68c6da) | Jan 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1796a84503](https://linux-hardware.org/?probe=1796a84503) | Jan 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [808ef5ae61](https://linux-hardware.org/?probe=808ef5ae61) | Jan 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [08ccb0120e](https://linux-hardware.org/?probe=08ccb0120e) | Jan 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ab63715f96](https://linux-hardware.org/?probe=ab63715f96) | Jan 08, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [1cf9b4e160](https://linux-hardware.org/?probe=1cf9b4e160) | Jan 06, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [860d7e3d8d](https://linux-hardware.org/?probe=860d7e3d8d) | Jan 06, 2021 |
| HP            | 15                          | Notebook    | [7559b865f0](https://linux-hardware.org/?probe=7559b865f0) | Jan 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7f4357bae8](https://linux-hardware.org/?probe=7f4357bae8) | Jan 05, 2021 |
| Gigabyte      | H310N x.x                   | Desktop     | [c5162a33b1](https://linux-hardware.org/?probe=c5162a33b1) | Jan 05, 2021 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [62f0ab94ac](https://linux-hardware.org/?probe=62f0ab94ac) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c56c2c1b79](https://linux-hardware.org/?probe=c56c2c1b79) | Jan 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f3aa67a60f](https://linux-hardware.org/?probe=f3aa67a60f) | Jan 02, 2021 |
| MSI           | B450M PRO-VDH               | Desktop     | [29e1d5935f](https://linux-hardware.org/?probe=29e1d5935f) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [11ab49e949](https://linux-hardware.org/?probe=11ab49e949) | Jan 01, 2021 |
| AWOW          | Unknown                     | Stick pc    | [50585544f9](https://linux-hardware.org/?probe=50585544f9) | Dec 31, 2020 |
| Dell          | XPS L501X                   | Notebook    | [4ced160372](https://linux-hardware.org/?probe=4ced160372) | Dec 31, 2020 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7774d76390](https://linux-hardware.org/?probe=7774d76390) | Dec 29, 2020 |
| System76      | Thelio thelio-r1            | Desktop     | [aa8f2e17ca](https://linux-hardware.org/?probe=aa8f2e17ca) | Dec 29, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [ca0a06995e](https://linux-hardware.org/?probe=ca0a06995e) | Dec 28, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [02e59017b8](https://linux-hardware.org/?probe=02e59017b8) | Dec 28, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c2b36956c2](https://linux-hardware.org/?probe=c2b36956c2) | Dec 28, 2020 |
| HP            | ENVY m6                     | Notebook    | [50e8b7f0f6](https://linux-hardware.org/?probe=50e8b7f0f6) | Dec 28, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [d96119f05d](https://linux-hardware.org/?probe=d96119f05d) | Dec 26, 2020 |
| Dell          | Inspiron 3476               | Notebook    | [c269f527ed](https://linux-hardware.org/?probe=c269f527ed) | Dec 25, 2020 |
| Lenovo        | V155-15API 81V5             | Notebook    | [afd1dcfbae](https://linux-hardware.org/?probe=afd1dcfbae) | Dec 24, 2020 |
| HP            | 8618                        | Desktop     | [a021be4e84](https://linux-hardware.org/?probe=a021be4e84) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | Notebook    | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| Lenovo        | V155-15API 81V5             | Notebook    | [64ec8663fc](https://linux-hardware.org/?probe=64ec8663fc) | Dec 23, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [fafdaae4cb](https://linux-hardware.org/?probe=fafdaae4cb) | Dec 23, 2020 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [eb1f0354f0](https://linux-hardware.org/?probe=eb1f0354f0) | Dec 23, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [88b5ce4f14](https://linux-hardware.org/?probe=88b5ce4f14) | Dec 22, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [ddde2864e6](https://linux-hardware.org/?probe=ddde2864e6) | Dec 22, 2020 |
| Lenovo        | V155-15API 81V5             | Notebook    | [45526695b8](https://linux-hardware.org/?probe=45526695b8) | Dec 21, 2020 |
| Lenovo        | ThinkPad T480s 20L8S8540... | Notebook    | [12fb9652a7](https://linux-hardware.org/?probe=12fb9652a7) | Dec 21, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [47fb295e32](https://linux-hardware.org/?probe=47fb295e32) | Dec 21, 2020 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1b147eb313](https://linux-hardware.org/?probe=1b147eb313) | Dec 20, 2020 |
| Samsung       | NC210/NC110                 | Notebook    | [98057a3a7a](https://linux-hardware.org/?probe=98057a3a7a) | Dec 19, 2020 |
| Samsung       | NC210/NC110                 | Notebook    | [4f3402c9dc](https://linux-hardware.org/?probe=4f3402c9dc) | Dec 19, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [c74c628d8a](https://linux-hardware.org/?probe=c74c628d8a) | Dec 19, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [6e4b2c6326](https://linux-hardware.org/?probe=6e4b2c6326) | Dec 19, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [56d8809172](https://linux-hardware.org/?probe=56d8809172) | Dec 17, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [4aaf32a9fc](https://linux-hardware.org/?probe=4aaf32a9fc) | Dec 17, 2020 |
| Timi          | TM1709                      | Notebook    | [089615b43f](https://linux-hardware.org/?probe=089615b43f) | Dec 16, 2020 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [3600589bf6](https://linux-hardware.org/?probe=3600589bf6) | Dec 15, 2020 |
| HP            | 0AECh D                     | Desktop     | [3c29596884](https://linux-hardware.org/?probe=3c29596884) | Dec 15, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [5e2ff51ade](https://linux-hardware.org/?probe=5e2ff51ade) | Dec 15, 2020 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [8c7c33ba8b](https://linux-hardware.org/?probe=8c7c33ba8b) | Dec 14, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | Notebook    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [354f430cf1](https://linux-hardware.org/?probe=354f430cf1) | Dec 14, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [7d51a3bee8](https://linux-hardware.org/?probe=7d51a3bee8) | Dec 14, 2020 |
| HP            | Notebook                    | Notebook    | [a770f1e52d](https://linux-hardware.org/?probe=a770f1e52d) | Dec 13, 2020 |
| MSI           | Z97 GAMING 7                | Desktop     | [6ce0652b8e](https://linux-hardware.org/?probe=6ce0652b8e) | Dec 13, 2020 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [602a601769](https://linux-hardware.org/?probe=602a601769) | Dec 11, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| HP            | OMEN by HP Laptop           | Notebook    | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| Pegatron      | BOWIE                       | Desktop     | [40f3ca1c9b](https://linux-hardware.org/?probe=40f3ca1c9b) | Dec 10, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [5155111cfa](https://linux-hardware.org/?probe=5155111cfa) | Dec 10, 2020 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [b9e091029f](https://linux-hardware.org/?probe=b9e091029f) | Dec 10, 2020 |
| Acer          | AOD260                      | Notebook    | [635a9139e1](https://linux-hardware.org/?probe=635a9139e1) | Dec 09, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d11b9d7e47](https://linux-hardware.org/?probe=d11b9d7e47) | Dec 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [baf10417f7](https://linux-hardware.org/?probe=baf10417f7) | Dec 08, 2020 |
| MSI           | H170A PC MATE               | Desktop     | [5cc4fd552a](https://linux-hardware.org/?probe=5cc4fd552a) | Dec 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8dbe0b6c4a](https://linux-hardware.org/?probe=8dbe0b6c4a) | Dec 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [4838a6e14f](https://linux-hardware.org/?probe=4838a6e14f) | Dec 05, 2020 |
| MSI           | A320M-HDV R4.0              | Desktop     | [99d3945e94](https://linux-hardware.org/?probe=99d3945e94) | Dec 05, 2020 |
| MSI           | A320M-HDV R4.0              | Desktop     | [b6414b072b](https://linux-hardware.org/?probe=b6414b072b) | Dec 05, 2020 |
| Medion        | MS-7785                     | Desktop     | [7db825feae](https://linux-hardware.org/?probe=7db825feae) | Dec 05, 2020 |
| Dell          | Latitude 5480               | Notebook    | [02680953ae](https://linux-hardware.org/?probe=02680953ae) | Dec 04, 2020 |
| Supermicro    | X8DTH                       | Server      | [c79a74a94e](https://linux-hardware.org/?probe=c79a74a94e) | Dec 03, 2020 |
| ASUSTek       | TUF GAMING FX504GE_FX80G... | Notebook    | [e6ee8ad4bb](https://linux-hardware.org/?probe=e6ee8ad4bb) | Dec 03, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [153a43bcc6](https://linux-hardware.org/?probe=153a43bcc6) | Dec 02, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [25333a85bb](https://linux-hardware.org/?probe=25333a85bb) | Dec 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [52cf6d4786](https://linux-hardware.org/?probe=52cf6d4786) | Dec 02, 2020 |
| MSI           | B150 PC MATE                | Desktop     | [8d4a1b883d](https://linux-hardware.org/?probe=8d4a1b883d) | Dec 02, 2020 |
| ASUSTek       | ZenBook UX461FN_UX461FN     | Convertible | [f734396f31](https://linux-hardware.org/?probe=f734396f31) | Dec 02, 2020 |
| Supermicro    | X8DTH                       | Server      | [ef33404ee7](https://linux-hardware.org/?probe=ef33404ee7) | Dec 01, 2020 |
| Fujitsu       | LIFEBOOK AH562              | Notebook    | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Gigabyte      | B250-D3A-CF                 | Desktop     | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| Supermicro    | X8DTH                       | Server      | [50db231fc1](https://linux-hardware.org/?probe=50db231fc1) | Nov 29, 2020 |
| MSI           | H110M ECO                   | Desktop     | [d848b46f0e](https://linux-hardware.org/?probe=d848b46f0e) | Nov 29, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6042149fcd](https://linux-hardware.org/?probe=6042149fcd) | Nov 29, 2020 |
| Timi          | TM1709                      | Notebook    | [bcccdee6ec](https://linux-hardware.org/?probe=bcccdee6ec) | Nov 29, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [f126a3d4d1](https://linux-hardware.org/?probe=f126a3d4d1) | Nov 28, 2020 |
| System76      | Galago Pro                  | Notebook    | [00eb3fca1a](https://linux-hardware.org/?probe=00eb3fca1a) | Nov 27, 2020 |
| Dell          | Inspiron N4110              | Notebook    | [8d8bd09d64](https://linux-hardware.org/?probe=8d8bd09d64) | Nov 27, 2020 |
| Alienware     | 0J560M A01                  | Desktop     | [ab6a38d6c2](https://linux-hardware.org/?probe=ab6a38d6c2) | Nov 27, 2020 |
| Timi          | TM1709                      | Notebook    | [01d2a19918](https://linux-hardware.org/?probe=01d2a19918) | Nov 27, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4f2f77fbd0](https://linux-hardware.org/?probe=4f2f77fbd0) | Nov 26, 2020 |
| Toshiba       | Satellite S70-B             | Notebook    | [d9925a0d93](https://linux-hardware.org/?probe=d9925a0d93) | Nov 26, 2020 |
| Dell          | Latitude 5310               | Notebook    | [b941f2a157](https://linux-hardware.org/?probe=b941f2a157) | Nov 25, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [cd48e9d406](https://linux-hardware.org/?probe=cd48e9d406) | Nov 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [ce492b1a92](https://linux-hardware.org/?probe=ce492b1a92) | Nov 25, 2020 |
| Dell          | 0WR7PY A02                  | Desktop     | [425d99f3d7](https://linux-hardware.org/?probe=425d99f3d7) | Nov 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e3cfe7597e](https://linux-hardware.org/?probe=e3cfe7597e) | Nov 25, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [2beee5183a](https://linux-hardware.org/?probe=2beee5183a) | Nov 24, 2020 |
| ASRock        | P67 Extreme4                | Desktop     | [2fb0f5003d](https://linux-hardware.org/?probe=2fb0f5003d) | Nov 24, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0f4e6428a8](https://linux-hardware.org/?probe=0f4e6428a8) | Nov 24, 2020 |
| Timi          | TM1709                      | Notebook    | [cf290a19fb](https://linux-hardware.org/?probe=cf290a19fb) | Nov 24, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Lenovo        | G580                        | Notebook    | [bbca803600](https://linux-hardware.org/?probe=bbca803600) | Nov 23, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [6bfb7d2b4c](https://linux-hardware.org/?probe=6bfb7d2b4c) | Nov 23, 2020 |
| ASUSTek       | D425MC                      | Desktop     | [a2a7090e43](https://linux-hardware.org/?probe=a2a7090e43) | Nov 23, 2020 |
| Alienware     | 0KM92T A00                  | Desktop     | [9fd3a31b57](https://linux-hardware.org/?probe=9fd3a31b57) | Nov 22, 2020 |
| ASUSTek       | D425MC                      | Desktop     | [3d64303842](https://linux-hardware.org/?probe=3d64303842) | Nov 22, 2020 |
| Dell          | Latitude 5480               | Notebook    | [30bffef4fc](https://linux-hardware.org/?probe=30bffef4fc) | Nov 22, 2020 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [a4caa995dd](https://linux-hardware.org/?probe=a4caa995dd) | Nov 22, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [e0de72e9a0](https://linux-hardware.org/?probe=e0de72e9a0) | Nov 21, 2020 |
| Lenovo        | 371C SDK0J40700 WIN 3258... | All in one  | [b2ea83f411](https://linux-hardware.org/?probe=b2ea83f411) | Nov 21, 2020 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cd25862710](https://linux-hardware.org/?probe=cd25862710) | Nov 20, 2020 |
| HP            | EliteBook 8540p             | Notebook    | [d9ca357ad7](https://linux-hardware.org/?probe=d9ca357ad7) | Nov 20, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Lenovo        | ThinkPad T430 2347AQ9       | Notebook    | [6fa209f1de](https://linux-hardware.org/?probe=6fa209f1de) | Nov 19, 2020 |
| Entroware     | Apollo                      | Notebook    | [6d7a020174](https://linux-hardware.org/?probe=6d7a020174) | Nov 19, 2020 |
| Dell          | XPS L421X                   | Notebook    | [4efcda4ace](https://linux-hardware.org/?probe=4efcda4ace) | Nov 18, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [6abb25b1de](https://linux-hardware.org/?probe=6abb25b1de) | Nov 18, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [155ae942ef](https://linux-hardware.org/?probe=155ae942ef) | Nov 17, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [d8a43c445c](https://linux-hardware.org/?probe=d8a43c445c) | Nov 17, 2020 |
| Dell          | 0WWJRX A00                  | Desktop     | [79bddf0f48](https://linux-hardware.org/?probe=79bddf0f48) | Nov 17, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [0d8e938368](https://linux-hardware.org/?probe=0d8e938368) | Nov 16, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [e01cf9234b](https://linux-hardware.org/?probe=e01cf9234b) | Nov 16, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [c74cdc7f6f](https://linux-hardware.org/?probe=c74cdc7f6f) | Nov 16, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [b669b71fce](https://linux-hardware.org/?probe=b669b71fce) | Nov 15, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [af8d47e3e4](https://linux-hardware.org/?probe=af8d47e3e4) | Nov 15, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [75d38974bc](https://linux-hardware.org/?probe=75d38974bc) | Nov 15, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [299e10281f](https://linux-hardware.org/?probe=299e10281f) | Nov 15, 2020 |
| Timi          | TM1709                      | Notebook    | [522d6ab484](https://linux-hardware.org/?probe=522d6ab484) | Nov 15, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [eafab55a01](https://linux-hardware.org/?probe=eafab55a01) | Nov 15, 2020 |
| Acer          | Aspire E5-532               | Notebook    | [79948d67b4](https://linux-hardware.org/?probe=79948d67b4) | Nov 15, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [be614c012f](https://linux-hardware.org/?probe=be614c012f) | Nov 15, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [fe00092f17](https://linux-hardware.org/?probe=fe00092f17) | Nov 15, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [ae9800cc49](https://linux-hardware.org/?probe=ae9800cc49) | Nov 14, 2020 |
| Timi          | TM1607                      | Notebook    | [db600ca49e](https://linux-hardware.org/?probe=db600ca49e) | Nov 14, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [316dc021cb](https://linux-hardware.org/?probe=316dc021cb) | Nov 14, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [867148b244](https://linux-hardware.org/?probe=867148b244) | Nov 14, 2020 |
| HP            | EliteBook 8540p             | Notebook    | [10121917da](https://linux-hardware.org/?probe=10121917da) | Nov 13, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f40c1b6361](https://linux-hardware.org/?probe=f40c1b6361) | Nov 13, 2020 |
| HP            | EliteBook 8540p             | Notebook    | [1df463aa08](https://linux-hardware.org/?probe=1df463aa08) | Nov 13, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [addf2ac7fa](https://linux-hardware.org/?probe=addf2ac7fa) | Nov 12, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [9ebd194a93](https://linux-hardware.org/?probe=9ebd194a93) | Nov 12, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [49eef48191](https://linux-hardware.org/?probe=49eef48191) | Nov 12, 2020 |
| Timi          | TM1709                      | Notebook    | [d7a940b8e0](https://linux-hardware.org/?probe=d7a940b8e0) | Nov 12, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [27ecc71233](https://linux-hardware.org/?probe=27ecc71233) | Nov 11, 2020 |
| Lenovo        | ThinkPad X201 3680KC5       | Notebook    | [2f03701216](https://linux-hardware.org/?probe=2f03701216) | Nov 11, 2020 |
| HP            | EliteBook 8540p             | Notebook    | [6a0b95782d](https://linux-hardware.org/?probe=6a0b95782d) | Nov 11, 2020 |
| Timi          | TM1709                      | Notebook    | [b89916b8c1](https://linux-hardware.org/?probe=b89916b8c1) | Nov 10, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [f2fc35bc80](https://linux-hardware.org/?probe=f2fc35bc80) | Nov 10, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0b705dafd1](https://linux-hardware.org/?probe=0b705dafd1) | Nov 10, 2020 |
| ASRock        | B75 Pro3-M                  | Desktop     | [bc564e4cc1](https://linux-hardware.org/?probe=bc564e4cc1) | Nov 10, 2020 |
| HP            | EliteBook 8540p             | Notebook    | [a3264597e8](https://linux-hardware.org/?probe=a3264597e8) | Nov 10, 2020 |
| Lenovo        | Board                       | Desktop     | [7efad9603e](https://linux-hardware.org/?probe=7efad9603e) | Nov 10, 2020 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | Notebook    | [e6ae7e8546](https://linux-hardware.org/?probe=e6ae7e8546) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1dbe42216a](https://linux-hardware.org/?probe=1dbe42216a) | Nov 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [521629e12d](https://linux-hardware.org/?probe=521629e12d) | Nov 10, 2020 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [62b36ce80c](https://linux-hardware.org/?probe=62b36ce80c) | Nov 10, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [636003c419](https://linux-hardware.org/?probe=636003c419) | Nov 09, 2020 |
| ASUSTek       | D425MC                      | Desktop     | [50665babae](https://linux-hardware.org/?probe=50665babae) | Nov 09, 2020 |
| MSI           | A68HM GRENADE               | Desktop     | [f0d0a824e5](https://linux-hardware.org/?probe=f0d0a824e5) | Nov 09, 2020 |
| Lenovo        | G560 0679                   | Notebook    | [35c00cb9bd](https://linux-hardware.org/?probe=35c00cb9bd) | Nov 09, 2020 |
| Medion        | E7212                       | Notebook    | [8979d90ea2](https://linux-hardware.org/?probe=8979d90ea2) | Nov 09, 2020 |
| Medion        | E7212                       | Notebook    | [3650f725ba](https://linux-hardware.org/?probe=3650f725ba) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [5c6c0ac3fa](https://linux-hardware.org/?probe=5c6c0ac3fa) | Nov 09, 2020 |
| Sony          | SVS1511Q9EB                 | Notebook    | [c84684fab0](https://linux-hardware.org/?probe=c84684fab0) | Nov 09, 2020 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [5b499e2547](https://linux-hardware.org/?probe=5b499e2547) | Nov 09, 2020 |
| Sony          | SVS1511Q9EB                 | Notebook    | [57911ec356](https://linux-hardware.org/?probe=57911ec356) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| ASUSTek       | E403NA                      | Notebook    | [c18d0128e0](https://linux-hardware.org/?probe=c18d0128e0) | Nov 09, 2020 |
| Lenovo        | 36DF SDK0J40709 WIN 3259... | All in one  | [f6b6499298](https://linux-hardware.org/?probe=f6b6499298) | Nov 09, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| ASRock        | 970M Pro3                   | Desktop     | [d34d91c84c](https://linux-hardware.org/?probe=d34d91c84c) | Nov 09, 2020 |
| Timi          | TM1709                      | Notebook    | [97dbbf75d8](https://linux-hardware.org/?probe=97dbbf75d8) | Nov 08, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [da0dd4eed3](https://linux-hardware.org/?probe=da0dd4eed3) | Nov 07, 2020 |
| Dell          | Board                       | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Dell          | Board                       | Desktop     | [a74c37f279](https://linux-hardware.org/?probe=a74c37f279) | Nov 03, 2020 |
| Lenovo        | ThinkPad T420 423662U       | Notebook    | [f8954d3570](https://linux-hardware.org/?probe=f8954d3570) | Nov 02, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [b57fd68ea6](https://linux-hardware.org/?probe=b57fd68ea6) | Nov 01, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [859b87566a](https://linux-hardware.org/?probe=859b87566a) | Nov 01, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| ASUSTek       | U36SG                       | Notebook    | [77de00a544](https://linux-hardware.org/?probe=77de00a544) | Oct 29, 2020 |
| HP            | Folio 13                    | Notebook    | [0687b076f8](https://linux-hardware.org/?probe=0687b076f8) | Oct 28, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [655eea2ec8](https://linux-hardware.org/?probe=655eea2ec8) | Oct 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [03f33fb1bf](https://linux-hardware.org/?probe=03f33fb1bf) | Oct 28, 2020 |
| HP            | ENVY 15                     | Notebook    | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [83d1965847](https://linux-hardware.org/?probe=83d1965847) | Oct 25, 2020 |
| Shuttle       | FS110                       | Desktop     | [43b2f8fffb](https://linux-hardware.org/?probe=43b2f8fffb) | Oct 25, 2020 |
| Shuttle       | FS110                       | Desktop     | [7ab4eb4369](https://linux-hardware.org/?probe=7ab4eb4369) | Oct 25, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [26f91cadbf](https://linux-hardware.org/?probe=26f91cadbf) | Oct 23, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [e726afbb3a](https://linux-hardware.org/?probe=e726afbb3a) | Oct 22, 2020 |
| Unknown       | Intel X79                   | Desktop     | [844bc2247d](https://linux-hardware.org/?probe=844bc2247d) | Oct 21, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [d28168f646](https://linux-hardware.org/?probe=d28168f646) | Oct 20, 2020 |
| Lenovo        | ThinkPad T440p 20AWS21V0... | Notebook    | [d38362dbe3](https://linux-hardware.org/?probe=d38362dbe3) | Oct 20, 2020 |
| Fujitsu       | LIFEBOOK P770               | Notebook    | [255c63f72d](https://linux-hardware.org/?probe=255c63f72d) | Oct 17, 2020 |
| HP            | 82F2 A01                    | Desktop     | [8fb1e5339c](https://linux-hardware.org/?probe=8fb1e5339c) | Oct 17, 2020 |
| MSI           | 2A9C                        | Desktop     | [60d4bfc9de](https://linux-hardware.org/?probe=60d4bfc9de) | Oct 16, 2020 |
| Dell          | 0XHGV1 A00                  | Desktop     | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| eMachines     | eME640G                     | Notebook    | [a5176c2926](https://linux-hardware.org/?probe=a5176c2926) | Oct 15, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [efc5e42972](https://linux-hardware.org/?probe=efc5e42972) | Oct 15, 2020 |
| Shuttle       | FS110                       | Desktop     | [5e555b749c](https://linux-hardware.org/?probe=5e555b749c) | Oct 15, 2020 |
| HP            | 843B                        | Desktop     | [86632c3a3e](https://linux-hardware.org/?probe=86632c3a3e) | Oct 15, 2020 |
| HP            | 158B                        | Desktop     | [714dc50b38](https://linux-hardware.org/?probe=714dc50b38) | Oct 15, 2020 |
| ASUSTek       | Z170-AR                     | Desktop     | [68df141e31](https://linux-hardware.org/?probe=68df141e31) | Oct 14, 2020 |
| Dell          | Board                       | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| Lenovo        | 36DF SDK0J40709 WIN 3259... | All in one  | [f5dd18bc22](https://linux-hardware.org/?probe=f5dd18bc22) | Oct 14, 2020 |
| Sony          | VPCEB1E1E                   | Notebook    | [cbd4fefba6](https://linux-hardware.org/?probe=cbd4fefba6) | Oct 14, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [b23c5d6ffd](https://linux-hardware.org/?probe=b23c5d6ffd) | Oct 14, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [930cc6ba98](https://linux-hardware.org/?probe=930cc6ba98) | Oct 14, 2020 |
| Toshiba       | Satellite S70-B             | Notebook    | [7732c2c6d9](https://linux-hardware.org/?probe=7732c2c6d9) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [59bbdc5626](https://linux-hardware.org/?probe=59bbdc5626) | Oct 14, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2bbb556fce](https://linux-hardware.org/?probe=2bbb556fce) | Oct 14, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [4424e49ac7](https://linux-hardware.org/?probe=4424e49ac7) | Oct 14, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [5aa763dbb6](https://linux-hardware.org/?probe=5aa763dbb6) | Oct 14, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [dc914d14e5](https://linux-hardware.org/?probe=dc914d14e5) | Oct 14, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [465d31dc87](https://linux-hardware.org/?probe=465d31dc87) | Oct 14, 2020 |
| Lenovo        | Board                       | Desktop     | [505cd9e4f6](https://linux-hardware.org/?probe=505cd9e4f6) | Oct 13, 2020 |
| ASUSTek       | P5Q-E                       | Desktop     | [b59905555f](https://linux-hardware.org/?probe=b59905555f) | Oct 12, 2020 |
| MSI           | GE62VR 6RF                  | Notebook    | [d6186120ce](https://linux-hardware.org/?probe=d6186120ce) | Oct 11, 2020 |
| Timi          | TM1709                      | Notebook    | [0d3a90e1de](https://linux-hardware.org/?probe=0d3a90e1de) | Oct 11, 2020 |
| MSI           | GE62VR 6RF                  | Notebook    | [cbdaf7b97a](https://linux-hardware.org/?probe=cbdaf7b97a) | Oct 10, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d81625db32](https://linux-hardware.org/?probe=d81625db32) | Oct 08, 2020 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [393ee605a8](https://linux-hardware.org/?probe=393ee605a8) | Oct 07, 2020 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [a0560ef7de](https://linux-hardware.org/?probe=a0560ef7de) | Oct 07, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d8bdfa0313](https://linux-hardware.org/?probe=d8bdfa0313) | Oct 06, 2020 |
| HP            | ENVY 15                     | Notebook    | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [66018917e4](https://linux-hardware.org/?probe=66018917e4) | Oct 05, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [36b807b440](https://linux-hardware.org/?probe=36b807b440) | Oct 05, 2020 |
| Medion        | P7624                       | Notebook    | [a4216be7a9](https://linux-hardware.org/?probe=a4216be7a9) | Oct 05, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [359e6431c4](https://linux-hardware.org/?probe=359e6431c4) | Oct 05, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e43661e28d](https://linux-hardware.org/?probe=e43661e28d) | Oct 05, 2020 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [018b5f5ee7](https://linux-hardware.org/?probe=018b5f5ee7) | Oct 02, 2020 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [77b2ccc8f7](https://linux-hardware.org/?probe=77b2ccc8f7) | Sep 20, 2020 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6b1361f41d](https://linux-hardware.org/?probe=6b1361f41d) | Sep 10, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [aa7011d06b](https://linux-hardware.org/?probe=aa7011d06b) | Sep 10, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [142d422a44](https://linux-hardware.org/?probe=142d422a44) | Sep 09, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [cc20cdc047](https://linux-hardware.org/?probe=cc20cdc047) | Sep 09, 2020 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [779949fca8](https://linux-hardware.org/?probe=779949fca8) | Sep 09, 2020 |
| HP            | 2AF3                        | Desktop     | [436d491c10](https://linux-hardware.org/?probe=436d491c10) | Sep 04, 2020 |
| HP            | 2AF3                        | Desktop     | [9618698fa4](https://linux-hardware.org/?probe=9618698fa4) | Sep 04, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e32223e31d](https://linux-hardware.org/?probe=e32223e31d) | Sep 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| Dell          | 0YJPT1 A00                  | Desktop     | [54ee6486e4](https://linux-hardware.org/?probe=54ee6486e4) | Sep 01, 2020 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1e5956278f](https://linux-hardware.org/?probe=1e5956278f) | Sep 01, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [5bc3c6c748](https://linux-hardware.org/?probe=5bc3c6c748) | Sep 01, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ca6cdad0fc](https://linux-hardware.org/?probe=ca6cdad0fc) | Sep 01, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3fa1727f63](https://linux-hardware.org/?probe=3fa1727f63) | Aug 28, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [62455c5947](https://linux-hardware.org/?probe=62455c5947) | Aug 28, 2020 |
| HP            | 2AFA                        | Desktop     | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | Desktop     | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [a235fadae8](https://linux-hardware.org/?probe=a235fadae8) | Aug 20, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [ec3d93d07c](https://linux-hardware.org/?probe=ec3d93d07c) | Jul 24, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [a24a914659](https://linux-hardware.org/?probe=a24a914659) | Jul 24, 2020 |
| Apple         | MacBookPro14,2              | Notebook    | [0388e1560c](https://linux-hardware.org/?probe=0388e1560c) | Jul 19, 2020 |
| HP            | 0AE8h C                     | Desktop     | [2c1ae8f199](https://linux-hardware.org/?probe=2c1ae8f199) | Jul 18, 2020 |
| Apple         | MacBookPro14,2              | Notebook    | [e6c8216292](https://linux-hardware.org/?probe=e6c8216292) | Jul 18, 2020 |
| Apple         | MacBookPro14,2              | Notebook    | [98f781c69d](https://linux-hardware.org/?probe=98f781c69d) | Jul 18, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ba0d58a56a](https://linux-hardware.org/?probe=ba0d58a56a) | Jul 16, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [3b43913f4f](https://linux-hardware.org/?probe=3b43913f4f) | Jul 07, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Teclast       | Cherry Trail Tablet         | Notebook    | [f975838f9a](https://linux-hardware.org/?probe=f975838f9a) | Jun 26, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [23d10923e3](https://linux-hardware.org/?probe=23d10923e3) | Jun 23, 2020 |
| Dell          | Inspiron 7590 2n1           | Convertible | [a339279078](https://linux-hardware.org/?probe=a339279078) | Jun 21, 2020 |
| Dell          | Inspiron 7590 2n1           | Convertible | [5251b3a3b1](https://linux-hardware.org/?probe=5251b3a3b1) | Jun 21, 2020 |
| HP            | 843B                        | Desktop     | [27dae7b96d](https://linux-hardware.org/?probe=27dae7b96d) | May 25, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [8361eff2e8](https://linux-hardware.org/?probe=8361eff2e8) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [daf65ba215](https://linux-hardware.org/?probe=daf65ba215) | Apr 19, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a76ba909ef](https://linux-hardware.org/?probe=a76ba909ef) | Apr 17, 2020 |
| Dell          | Latitude E6320              | Notebook    | [ddd1262c4d](https://linux-hardware.org/?probe=ddd1262c4d) | Apr 14, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e9be68d1ba](https://linux-hardware.org/?probe=e9be68d1ba) | Apr 13, 2020 |
| HP            | Notebook                    | Notebook    | [a711b56cd0](https://linux-hardware.org/?probe=a711b56cd0) | Apr 13, 2020 |
| HP            | Notebook                    | Notebook    | [c93227aec0](https://linux-hardware.org/?probe=c93227aec0) | Apr 13, 2020 |
| HP            | Notebook                    | Notebook    | [3e6181305b](https://linux-hardware.org/?probe=3e6181305b) | Apr 13, 2020 |
| Dell          | Latitude E6320              | Notebook    | [d1ffc53a12](https://linux-hardware.org/?probe=d1ffc53a12) | Apr 12, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [64daf31a22](https://linux-hardware.org/?probe=64daf31a22) | Apr 05, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Acer          | Aspire VN7-791G             | Notebook    | [cd10eea9ff](https://linux-hardware.org/?probe=cd10eea9ff) | Apr 01, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4823f5bb65](https://linux-hardware.org/?probe=4823f5bb65) | Mar 31, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [165309707f](https://linux-hardware.org/?probe=165309707f) | Mar 24, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e973706460](https://linux-hardware.org/?probe=e973706460) | Mar 24, 2020 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d316d9c7f4](https://linux-hardware.org/?probe=d316d9c7f4) | Mar 09, 2020 |
| ASRock        | P55DE3                      | Desktop     | [af644cb23e](https://linux-hardware.org/?probe=af644cb23e) | Feb 10, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [da709d9bae](https://linux-hardware.org/?probe=da709d9bae) | Feb 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f09c3dfb9f](https://linux-hardware.org/?probe=f09c3dfb9f) | Jan 31, 2020 |
| HP            | Pavilion dv7                | Notebook    | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2f34f5c135](https://linux-hardware.org/?probe=2f34f5c135) | Jan 03, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2aea82baf4](https://linux-hardware.org/?probe=2aea82baf4) | Dec 29, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [15b8ce77ac](https://linux-hardware.org/?probe=15b8ce77ac) | Dec 28, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4cc1554c27](https://linux-hardware.org/?probe=4cc1554c27) | Dec 28, 2019 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0dc9dd21f6](https://linux-hardware.org/?probe=0dc9dd21f6) | Dec 28, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de065f2cfc](https://linux-hardware.org/?probe=de065f2cfc) | Dec 22, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c898033824](https://linux-hardware.org/?probe=c898033824) | Dec 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [833f4e96c9](https://linux-hardware.org/?probe=833f4e96c9) | Dec 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4ec0437226](https://linux-hardware.org/?probe=4ec0437226) | Dec 07, 2019 |
| Dell          | 0H0P0M A00                  | Desktop     | [074175e3f0](https://linux-hardware.org/?probe=074175e3f0) | Nov 05, 2019 |
| Dell          | 0H0P0M A00                  | Desktop     | [ad47c45f44](https://linux-hardware.org/?probe=ad47c45f44) | Nov 05, 2019 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [55f43c974b](https://linux-hardware.org/?probe=55f43c974b) | Sep 26, 2019 |
| Dell          | 05DN3X A00                  | Desktop     | [39bc0ad7b5](https://linux-hardware.org/?probe=39bc0ad7b5) | Sep 22, 2019 |
| Acer          | Nitro AN515-42              | Notebook    | [f592750747](https://linux-hardware.org/?probe=f592750747) | Aug 16, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [6489d4345b](https://linux-hardware.org/?probe=6489d4345b) | Aug 06, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c699e95c85](https://linux-hardware.org/?probe=c699e95c85) | Aug 05, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [37d6087e4e](https://linux-hardware.org/?probe=37d6087e4e) | Aug 02, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [98918645ab](https://linux-hardware.org/?probe=98918645ab) | Aug 02, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [09a098a5aa](https://linux-hardware.org/?probe=09a098a5aa) | Jul 25, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [024cf11765](https://linux-hardware.org/?probe=024cf11765) | Jul 20, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [4b6d3033d0](https://linux-hardware.org/?probe=4b6d3033d0) | Jul 09, 2019 |
| HP            | Laptop 17-ak0xx             | Notebook    | [b53e43fc3c](https://linux-hardware.org/?probe=b53e43fc3c) | May 06, 2019 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d6b9184305](https://linux-hardware.org/?probe=d6b9184305) | Apr 21, 2019 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [66e42457b4](https://linux-hardware.org/?probe=66e42457b4) | Apr 21, 2019 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d5ecd1cb87](https://linux-hardware.org/?probe=d5ecd1cb87) | Apr 09, 2019 |
| ASUSTek       | UX31A                       | Notebook    | [2a30d224cf](https://linux-hardware.org/?probe=2a30d224cf) | Feb 24, 2019 |
| Lenovo        | ThinkPad E420 11417NA       | Notebook    | [9d5fad95db](https://linux-hardware.org/?probe=9d5fad95db) | Aug 22, 2018 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [f0bef09470](https://linux-hardware.org/?probe=f0bef09470) | Jul 13, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 1001      | 88.04%  |
| ArcoLinux             | 88        | 7.74%   |
| ArcoLinux 20.6.5      | 11        | 0.97%   |
| ArcoLinux 20.7.5      | 8         | 0.7%    |
| ArcoLinux 20.3.4      | 4         | 0.35%   |
| ArcoLinux 20.3.3      | 3         | 0.26%   |
| ArcoLinux 20.2.12     | 3         | 0.26%   |
| ArcoLinux 19.12.15    | 3         | 0.26%   |
| ArcoLinux 19.07.11    | 3         | 0.26%   |
| ArcoLinux 20.1.4      | 2         | 0.18%   |
| ArcoLinux 19.02.4     | 2         | 0.18%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.09%   |
| ArcoLinux 6.9.2       | 1         | 0.09%   |
| ArcoLinux 6.9.1       | 1         | 0.09%   |
| ArcoLinux 20.5.7      | 1         | 0.09%   |
| ArcoLinux 20.5.2      | 1         | 0.09%   |
| ArcoLinux 20.4.11     | 1         | 0.09%   |
| ArcoLinux 20.2.9      | 1         | 0.09%   |
| ArcoLinux 19.11.3     | 1         | 0.09%   |
| ArcoLinux 19.03.3     | 1         | 0.09%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 1131      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 51        | 3.75%   |
| 5.13.13-arch1-1   | 39        | 2.87%   |
| 5.15.10-arch1-1   | 36        | 2.65%   |
| 5.14.14-arch1-1   | 26        | 1.91%   |
| 5.13.12-arch1-1   | 23        | 1.69%   |
| 5.14.12-arch1-1   | 21        | 1.54%   |
| 5.17.1-arch1-1    | 20        | 1.47%   |
| 5.16.11-arch1-1   | 20        | 1.47%   |
| 5.8.14-arch1-1    | 16        | 1.18%   |
| 5.12.15-arch1-1   | 16        | 1.18%   |
| 5.12.13-arch1-2   | 16        | 1.18%   |
| 5.9.14-arch1-1    | 15        | 1.1%    |
| 5.16.2-arch1-1    | 15        | 1.1%    |
| 5.15.4-arch1-1    | 14        | 1.03%   |
| 5.10.84-1-lts     | 14        | 1.03%   |
| 5.9.6-arch1-1     | 13        | 0.96%   |
| 5.15.5-arch1-1    | 13        | 0.96%   |
| 5.15.11-arch2-1   | 13        | 0.96%   |
| 5.12.12-arch1-1   | 13        | 0.96%   |
| 5.9.1-arch1-1     | 12        | 0.88%   |
| 5.15.6-arch2-1    | 12        | 0.88%   |
| 5.15.2-arch1-1    | 12        | 0.88%   |
| 5.12.10-arch1-1   | 12        | 0.88%   |
| 5.9.8-arch1-1     | 11        | 0.81%   |
| 5.9.10-arch1-1    | 11        | 0.81%   |
| 5.15.13-arch1-1   | 11        | 0.81%   |
| 5.13.8-arch1-1    | 11        | 0.81%   |
| 5.12.14-arch1-1   | 11        | 0.81%   |
| 5.11.6-arch1-1    | 11        | 0.81%   |
| 5.10.6-arch1-1    | 11        | 0.81%   |
| 5.16.10-arch1-1   | 10        | 0.74%   |
| 5.15.7-zen1-1-zen | 10        | 0.74%   |
| 5.15.12-arch1-1   | 10        | 0.74%   |
| 5.14.6-arch1-1    | 10        | 0.74%   |
| 5.16.16-arch1-1   | 9         | 0.66%   |
| 5.16.12-arch1-1   | 9         | 0.66%   |
| 5.11.16-arch1-1   | 9         | 0.66%   |
| 5.10.88-2-lts     | 9         | 0.66%   |
| 5.10.16-arch1-1   | 9         | 0.66%   |
| 5.9.13-arch1-1    | 8         | 0.59%   |
| 5.9.11-arch2-1    | 8         | 0.59%   |
| 5.17.4-arch1-1    | 8         | 0.59%   |
| 5.14.9-arch2-1    | 8         | 0.59%   |
| 5.14.7-arch1-1    | 8         | 0.59%   |
| 5.14.16-arch1-1   | 8         | 0.59%   |
| 5.10.7-arch1-1    | 8         | 0.59%   |
| 5.10.61-1-lts     | 8         | 0.59%   |
| 5.8.5-arch1-1     | 7         | 0.51%   |
| 5.17.3-arch1-1    | 7         | 0.51%   |
| 5.16.8-arch1-1    | 7         | 0.51%   |
| 5.14.8-arch1-1    | 7         | 0.51%   |
| 5.14.5-arch1-1    | 7         | 0.51%   |
| 5.13.9-arch1-1    | 7         | 0.51%   |
| 5.13.10-arch1-1   | 7         | 0.51%   |
| 5.12.1-arch1-1    | 7         | 0.51%   |
| 5.11.11-arch1-1   | 7         | 0.51%   |
| 5.10.9-arch1-1    | 7         | 0.51%   |
| 5.9.9-arch1-1     | 6         | 0.44%   |
| 5.8.13-arch1-1    | 6         | 0.44%   |
| 5.4.70-1-lts      | 6         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.7  | 63        | 4.63%   |
| 5.13.13 | 39        | 2.87%   |
| 5.15.10 | 38        | 2.79%   |
| 5.14.14 | 28        | 2.06%   |
| 5.17.1  | 27        | 1.99%   |
| 5.13.12 | 25        | 1.84%   |
| 5.14.12 | 24        | 1.76%   |
| 5.16.11 | 22        | 1.62%   |
| 5.9.14  | 19        | 1.4%    |
| 5.16.2  | 19        | 1.4%    |
| 5.15.4  | 19        | 1.4%    |
| 5.12.15 | 19        | 1.4%    |
| 5.9.6   | 18        | 1.32%   |
| 5.12.13 | 18        | 1.32%   |
| 5.8.14  | 17        | 1.25%   |
| 5.9.8   | 16        | 1.18%   |
| 5.9.1   | 15        | 1.1%    |
| 5.15.6  | 15        | 1.1%    |
| 5.15.5  | 15        | 1.1%    |
| 5.15.11 | 14        | 1.03%   |
| 5.12.12 | 14        | 1.03%   |
| 5.10.84 | 14        | 1.03%   |
| 5.9.10  | 13        | 0.96%   |
| 5.15.2  | 13        | 0.96%   |
| 5.15.13 | 13        | 0.96%   |
| 5.14.9  | 13        | 0.96%   |
| 5.11.6  | 13        | 0.96%   |
| 5.10.16 | 13        | 0.96%   |
| 5.16.10 | 12        | 0.88%   |
| 5.15.12 | 12        | 0.88%   |
| 5.14.6  | 12        | 0.88%   |
| 5.14.16 | 12        | 0.88%   |
| 5.12.10 | 12        | 0.88%   |
| 5.9.11  | 11        | 0.81%   |
| 5.16.16 | 11        | 0.81%   |
| 5.16.12 | 11        | 0.81%   |
| 5.14.7  | 11        | 0.81%   |
| 5.13.8  | 11        | 0.81%   |
| 5.12.14 | 11        | 0.81%   |
| 5.11.16 | 11        | 0.81%   |
| 5.10.6  | 11        | 0.81%   |
| 5.11.11 | 10        | 0.74%   |
| 5.9.13  | 9         | 0.66%   |
| 5.17.3  | 9         | 0.66%   |
| 5.16.5  | 9         | 0.66%   |
| 5.10.88 | 9         | 0.66%   |
| 5.10.7  | 9         | 0.66%   |
| 5.9.9   | 8         | 0.59%   |
| 5.8.5   | 8         | 0.59%   |
| 5.17.4  | 8         | 0.59%   |
| 5.16.8  | 8         | 0.59%   |
| 5.14.8  | 8         | 0.59%   |
| 5.14.5  | 8         | 0.59%   |
| 5.14.2  | 8         | 0.59%   |
| 5.14.11 | 8         | 0.59%   |
| 5.13.9  | 8         | 0.59%   |
| 5.10.9  | 8         | 0.59%   |
| 5.10.61 | 8         | 0.59%   |
| 5.8.13  | 7         | 0.51%   |
| 5.15.3  | 7         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 233       | 18.09%  |
| 5.10    | 214       | 16.61%  |
| 5.14    | 131       | 10.17%  |
| 5.16    | 124       | 9.63%   |
| 5.13    | 114       | 8.85%   |
| 5.9     | 110       | 8.54%   |
| 5.12    | 110       | 8.54%   |
| 5.11    | 80        | 6.21%   |
| 5.4     | 60        | 4.66%   |
| 5.17    | 48        | 3.73%   |
| 5.8     | 34        | 2.64%   |
| 5.6     | 7         | 0.54%   |
| 5.7     | 6         | 0.47%   |
| 5.5     | 5         | 0.39%   |
| 5.3     | 3         | 0.23%   |
| 5.0     | 3         | 0.23%   |
| 4.19    | 2         | 0.16%   |
| 5.2     | 1         | 0.08%   |
| 4.20    | 1         | 0.08%   |
| 4.18    | 1         | 0.08%   |
| 4.17    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1131      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 399       | 33.61%  |
| KDE5           | 198       | 16.68%  |
| i3             | 86        | 7.25%   |
| GNOME          | 71        | 5.98%   |
| awesome        | 71        | 5.98%   |
| qtile          | 51        | 4.3%    |
| bspwm          | 43        | 3.62%   |
| X-Cinnamon     | 41        | 3.45%   |
| xmonad         | 40        | 3.37%   |
| dwm            | 35        | 2.95%   |
| KDE            | 24        | 2.02%   |
| Unknown        | 20        | 1.68%   |
| LeftWM         | 16        | 1.35%   |
| Deepin         | 16        | 1.35%   |
| Cinnamon       | 12        | 1.01%   |
| LXQt           | 11        | 0.93%   |
| Budgie         | 11        | 0.93%   |
| MATE           | 10        | 0.84%   |
| i3-with-shmlog | 7         | 0.59%   |
| herbstluftwm   | 7         | 0.59%   |
| Cutefish       | 4         | 0.34%   |
| Unity          | 2         | 0.17%   |
| spectrwm       | 2         | 0.17%   |
| openbox        | 2         | 0.17%   |
| ICEWM          | 2         | 0.17%   |
| dusk           | 2         | 0.17%   |
| sway           | 1         | 0.08%   |
| jwm            | 1         | 0.08%   |
| dwm-sc         | 1         | 0.08%   |
| cwm            | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1045      | 91.91%  |
| Tty     | 66        | 5.8%    |
| Wayland | 20        | 1.76%   |
| Unknown | 6         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 579       | 48.29%  |
| TDM     | 293       | 24.44%  |
| LightDM | 183       | 15.26%  |
| Unknown | 124       | 10.34%  |
| GDM     | 15        | 1.25%   |
| Ly      | 2         | 0.17%   |
| XDM     | 1         | 0.08%   |
| SLiM    | 1         | 0.08%   |
| LXDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 660       | 57.59%  |
| en_GB   | 102       | 8.9%    |
| de_DE   | 57        | 4.97%   |
| en_CA   | 40        | 3.49%   |
| en_IN   | 29        | 2.53%   |
| fr_FR   | 26        | 2.27%   |
| en_AU   | 26        | 2.27%   |
| ru_RU   | 17        | 1.48%   |
| es_ES   | 15        | 1.31%   |
| Unknown | 14        | 1.22%   |
| pt_BR   | 13        | 1.13%   |
| pl_PL   | 13        | 1.13%   |
| hu_HU   | 10        | 0.87%   |
| es_AR   | 8         | 0.7%    |
| sv_SE   | 7         | 0.61%   |
| en_ZA   | 7         | 0.61%   |
| nl_NL   | 6         | 0.52%   |
| it_IT   | 6         | 0.52%   |
| en_IE   | 6         | 0.52%   |
| ru_UA   | 5         | 0.44%   |
| nl_BE   | 5         | 0.44%   |
| en_SG   | 5         | 0.44%   |
| en_DK   | 5         | 0.44%   |
| tr_TR   | 4         | 0.35%   |
| pt_PT   | 4         | 0.35%   |
| fr_CA   | 4         | 0.35%   |
| fi_FI   | 4         | 0.35%   |
| en_IL   | 4         | 0.35%   |
| es_CL   | 3         | 0.26%   |
| el_GR   | 3         | 0.26%   |
| da_DK   | 3         | 0.26%   |
| zh_CN   | 2         | 0.17%   |
| ro_RO   | 2         | 0.17%   |
| ja_JP   | 2         | 0.17%   |
| fr_BE   | 2         | 0.17%   |
| es_MX   | 2         | 0.17%   |
| es_CO   | 2         | 0.17%   |
| en_NZ   | 2         | 0.17%   |
| de_CH   | 2         | 0.17%   |
| de_AT   | 2         | 0.17%   |
| C       | 2         | 0.17%   |
| uk_UA   | 1         | 0.09%   |
| sl_SI   | 1         | 0.09%   |
| nb_NO   | 1         | 0.09%   |
| lv_LV   | 1         | 0.09%   |
| lt_LT   | 1         | 0.09%   |
| fr_CH   | 1         | 0.09%   |
| es_VE   | 1         | 0.09%   |
| es_US   | 1         | 0.09%   |
| es_PY   | 1         | 0.09%   |
| es_EC   | 1         | 0.09%   |
| en_PH   | 1         | 0.09%   |
| en_HK   | 1         | 0.09%   |
| cs_CZ   | 1         | 0.09%   |
| ca_ES   | 1         | 0.09%   |
| bg_BG   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 799       | 70.03%  |
| BIOS | 342       | 29.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 884       | 76.6%   |
| Btrfs   | 180       | 15.6%   |
| Overlay | 56        | 4.85%   |
| Xfs     | 15        | 1.3%    |
| F2fs    | 9         | 0.78%   |
| Unknown | 8         | 0.69%   |
| Jfs     | 2         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 845       | 73.93%  |
| MBR     | 183       | 16.01%  |
| Unknown | 115       | 10.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 893       | 76.78%  |
| Yes       | 270       | 23.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 692       | 60.76%  |
| Yes       | 447       | 39.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 219       | 19.36%  |
| Lenovo              | 211       | 18.66%  |
| Dell                | 127       | 11.23%  |
| Hewlett-Packard     | 110       | 9.73%   |
| MSI                 | 84        | 7.43%   |
| Gigabyte Technology | 83        | 7.34%   |
| Acer                | 51        | 4.51%   |
| ASRock              | 49        | 4.33%   |
| Apple               | 34        | 3.01%   |
| Supermicro          | 13        | 1.15%   |
| Toshiba             | 12        | 1.06%   |
| Intel               | 12        | 1.06%   |
| Unknown             | 10        | 0.88%   |
| System76            | 8         | 0.71%   |
| Medion              | 8         | 0.71%   |
| Sony                | 7         | 0.62%   |
| Samsung Electronics | 7         | 0.62%   |
| Fujitsu             | 7         | 0.62%   |
| Razer               | 6         | 0.53%   |
| Notebook            | 6         | 0.53%   |
| HUAWEI              | 6         | 0.53%   |
| Timi                | 5         | 0.44%   |
| Alienware           | 5         | 0.44%   |
| TUXEDO              | 4         | 0.35%   |
| Pegatron            | 4         | 0.35%   |
| Foxconn             | 3         | 0.27%   |
| ZOTAC               | 2         | 0.18%   |
| Teclast             | 2         | 0.18%   |
| Casper              | 2         | 0.18%   |
| Biostar             | 2         | 0.18%   |
| AZW                 | 2         | 0.18%   |
| VS Company          | 1         | 0.09%   |
| UNITCOM             | 1         | 0.09%   |
| SYWZ                | 1         | 0.09%   |
| Standard            | 1         | 0.09%   |
| SLIMBOOK            | 1         | 0.09%   |
| Shuttle             | 1         | 0.09%   |
| Semp Toshiba        | 1         | 0.09%   |
| SeeedStudio         | 1         | 0.09%   |
| Schenker            | 1         | 0.09%   |
| PROLINE             | 1         | 0.09%   |
| Packard Bell        | 1         | 0.09%   |
| Monster             | 1         | 0.09%   |
| Microsoft           | 1         | 0.09%   |
| Maibenben           | 1         | 0.09%   |
| LG Electronics      | 1         | 0.09%   |
| Kanji               | 1         | 0.09%   |
| Huanan              | 1         | 0.09%   |
| HPE                 | 1         | 0.09%   |
| Google              | 1         | 0.09%   |
| EVGA                | 1         | 0.09%   |
| Entroware           | 1         | 0.09%   |
| eMachines           | 1         | 0.09%   |
| Eluktronics         | 1         | 0.09%   |
| ECS                 | 1         | 0.09%   |
| Daten Tecnologia    | 1         | 0.09%   |
| Compal              | 1         | 0.09%   |
| Chuwi               | 1         | 0.09%   |
| Bluechip Computer   | 1         | 0.09%   |
| BESSTAR Tech        | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 13        | 1.15%   |
| Supermicro SYS-5019A-FTN4           | 10        | 0.88%   |
| ASUS TUF GAMING X570-PLUS           | 10        | 0.88%   |
| ASUS All Series                     | 10        | 0.88%   |
| ASUS ROG STRIX B550-F GAMING        | 8         | 0.71%   |
| MSI MS-7C91                         | 6         | 0.53%   |
| MSI MS-7C37                         | 6         | 0.53%   |
| ASUS PRIME X470-PRO                 | 6         | 0.53%   |
| MSI MS-7B79                         | 5         | 0.44%   |
| ASUS PRIME X570-P                   | 5         | 0.44%   |
| MSI MS-7B89                         | 4         | 0.35%   |
| MSI MS-7971                         | 4         | 0.35%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ    | 4         | 0.35%   |
| HP Pavilion Notebook                | 4         | 0.35%   |
| HP Notebook                         | 4         | 0.35%   |
| ASUS STRIX Z270H GAMING             | 4         | 0.35%   |
| ASUS PRIME B450M-A                  | 4         | 0.35%   |
| ASRock B450M Pro4                   | 4         | 0.35%   |
| Timi TM1607                         | 3         | 0.27%   |
| Razer Blade                         | 3         | 0.27%   |
| MSI MS-7A38                         | 3         | 0.27%   |
| Lenovo IdeaPad 5 14ARE05 81YM       | 3         | 0.27%   |
| HP Laptop 15s-eq2xxx                | 3         | 0.27%   |
| HP EliteDesk 800 G1 SFF             | 3         | 0.27%   |
| HP EliteBook 8460p                  | 3         | 0.27%   |
| HP 255 G7 Notebook PC               | 3         | 0.27%   |
| Gigabyte B450 AORUS ELITE           | 3         | 0.27%   |
| Dell XPS 15 9570                    | 3         | 0.27%   |
| Dell Precision M4800                | 3         | 0.27%   |
| Dell OptiPlex 7010                  | 3         | 0.27%   |
| Dell Latitude E6530                 | 3         | 0.27%   |
| Dell Inspiron 15 7000 Gaming        | 3         | 0.27%   |
| ASUS Z170 PRO GAMING                | 3         | 0.27%   |
| ASUS ROG STRIX X570-E GAMING        | 3         | 0.27%   |
| ASUS ROG STRIX B450-F GAMING        | 3         | 0.27%   |
| ASUS ROG CROSSHAIR VIII HERO        | 3         | 0.27%   |
| ASUS PRIME X570-PRO                 | 3         | 0.27%   |
| ASUS PRIME A320M-K                  | 3         | 0.27%   |
| ASUS M5A78L-M/USB3                  | 3         | 0.27%   |
| ASUS CROSSHAIR VI HERO              | 3         | 0.27%   |
| Apple MacBookPro8,1                 | 3         | 0.27%   |
| Apple MacBookPro11,2                | 3         | 0.27%   |
| Apple MacBookPro11,1                | 3         | 0.27%   |
| Acer Swift SF314-41                 | 3         | 0.27%   |
| System76 Oryx Pro                   | 2         | 0.18%   |
| System76 Galago Pro                 | 2         | 0.18%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 2         | 0.18%   |
| Razer Blade Stealth                 | 2         | 0.18%   |
| MSI MS-7C56                         | 2         | 0.18%   |
| MSI MS-7C02                         | 2         | 0.18%   |
| MSI MS-7B98                         | 2         | 0.18%   |
| MSI MS-7B86                         | 2         | 0.18%   |
| MSI MS-7B85                         | 2         | 0.18%   |
| MSI MS-7B78                         | 2         | 0.18%   |
| MSI MS-7A34                         | 2         | 0.18%   |
| MSI MS-7821                         | 2         | 0.18%   |
| MSI MS-7817                         | 2         | 0.18%   |
| Lenovo Yoga C740-15IML 81TD         | 2         | 0.18%   |
| Lenovo Yoga 900-13ISK 80MK          | 2         | 0.18%   |
| Lenovo V14-ADA 82C6                 | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 101       | 8.93%   |
| Lenovo IdeaPad            | 42        | 3.71%   |
| Dell Inspiron             | 37        | 3.27%   |
| ASUS PRIME                | 36        | 3.18%   |
| Dell Latitude             | 35        | 3.09%   |
| ASUS ROG                  | 35        | 3.09%   |
| Acer Aspire               | 31        | 2.74%   |
| ASUS TUF                  | 28        | 2.48%   |
| Dell XPS                  | 25        | 2.21%   |
| HP Pavilion               | 16        | 1.41%   |
| ASUS VivoBook             | 16        | 1.41%   |
| Lenovo Legion             | 15        | 1.33%   |
| HP Laptop                 | 15        | 1.33%   |
| HP EliteBook              | 14        | 1.24%   |
| Dell OptiPlex             | 14        | 1.24%   |
| Lenovo Yoga               | 13        | 1.15%   |
| Unknown                   | 13        | 1.15%   |
| Toshiba Satellite         | 10        | 0.88%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.88%   |
| ASUS All                  | 10        | 0.88%   |
| Lenovo ThinkCentre        | 9         | 0.8%    |
| HP ENVY                   | 9         | 0.8%    |
| Gigabyte X570             | 9         | 0.8%    |
| Gigabyte B450             | 8         | 0.71%   |
| Dell Precision            | 8         | 0.71%   |
| Apple MacBookPro11        | 8         | 0.71%   |
| Acer Nitro                | 8         | 0.71%   |
| HP EliteDesk              | 7         | 0.62%   |
| ASUS STRIX                | 7         | 0.62%   |
| Razer Blade               | 6         | 0.53%   |
| MSI MS-7C91               | 6         | 0.53%   |
| MSI MS-7C37               | 6         | 0.53%   |
| HP ProBook                | 6         | 0.53%   |
| Fujitsu LIFEBOOK          | 6         | 0.53%   |
| Dell Vostro               | 6         | 0.53%   |
| ASUS P8Z77-V              | 6         | 0.53%   |
| ASRock B450M              | 6         | 0.53%   |
| MSI MS-7B79               | 5         | 0.44%   |
| HP Compaq                 | 5         | 0.44%   |
| Acer Swift                | 5         | 0.44%   |
| MSI MS-7B89               | 4         | 0.35%   |
| MSI MS-7971               | 4         | 0.35%   |
| Lenovo IdeaCentre         | 4         | 0.35%   |
| HP Notebook               | 4         | 0.35%   |
| HP 255                    | 4         | 0.35%   |
| HP 250                    | 4         | 0.35%   |
| Gigabyte B450M            | 4         | 0.35%   |
| Acer Predator             | 4         | 0.35%   |
| Timi TM1607               | 3         | 0.27%   |
| MSI MS-7A38               | 3         | 0.27%   |
| HP ZBook                  | 3         | 0.27%   |
| Gigabyte B365M            | 3         | 0.27%   |
| Gigabyte A520M            | 3         | 0.27%   |
| ASUS Z170                 | 3         | 0.27%   |
| ASUS P8H61-M              | 3         | 0.27%   |
| ASUS M5A78L-M             | 3         | 0.27%   |
| ASUS CROSSHAIR            | 3         | 0.27%   |
| ASRock X570               | 3         | 0.27%   |
| ASRock B450               | 3         | 0.27%   |
| Apple MacBookPro8         | 3         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 161       | 14.24%  |
| 2018    | 159       | 14.06%  |
| 2020    | 146       | 12.91%  |
| 2017    | 110       | 9.73%   |
| 2011    | 75        | 6.63%   |
| 2015    | 72        | 6.37%   |
| 2013    | 69        | 6.1%    |
| 2016    | 67        | 5.92%   |
| 2012    | 67        | 5.92%   |
| 2021    | 57        | 5.04%   |
| 2014    | 53        | 4.69%   |
| 2010    | 49        | 4.33%   |
| 2009    | 23        | 2.03%   |
| 2008    | 12        | 1.06%   |
| 2007    | 6         | 0.53%   |
| 2006    | 3         | 0.27%   |
| 2005    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 591       | 52.25%  |
| Desktop     | 484       | 42.79%  |
| Convertible | 26        | 2.3%    |
| All in one  | 14        | 1.24%   |
| Mini pc     | 9         | 0.8%    |
| Tablet      | 3         | 0.27%   |
| Server      | 3         | 0.27%   |
| Stick pc    | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1131      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1127      | 99.65%  |
| Yes  | 4         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 320       | 27.92%  |
| 4.01-8.0    | 260       | 22.69%  |
| 8.01-16.0   | 203       | 17.71%  |
| 32.01-64.0  | 163       | 14.22%  |
| 3.01-4.0    | 115       | 10.03%  |
| 64.01-256.0 | 37        | 3.23%   |
| 24.01-32.0  | 27        | 2.36%   |
| 1.01-2.0    | 15        | 1.31%   |
| 2.01-3.0    | 5         | 0.44%   |
| Unknown     | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 404       | 32.22%  |
| 2.01-3.0   | 320       | 25.52%  |
| 4.01-8.0   | 173       | 13.8%   |
| 3.01-4.0   | 157       | 12.52%  |
| 0.51-1.0   | 121       | 9.65%   |
| 8.01-16.0  | 48        | 3.83%   |
| 0.01-0.5   | 24        | 1.91%   |
| 16.01-24.0 | 4         | 0.32%   |
| 24.01-32.0 | 2         | 0.16%   |
| Unknown    | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 545       | 46.94%  |
| 2      | 331       | 28.51%  |
| 3      | 130       | 11.2%   |
| 4      | 82        | 7.06%   |
| 5      | 37        | 3.19%   |
| 6      | 15        | 1.29%   |
| 7      | 7         | 0.6%    |
| 0      | 6         | 0.52%   |
| 9      | 3         | 0.26%   |
| 8      | 3         | 0.26%   |
| 11     | 1         | 0.09%   |
| 10     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 802       | 70.41%  |
| Yes       | 337       | 29.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1001      | 88.27%  |
| No        | 133       | 11.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 858       | 75.8%   |
| No        | 274       | 24.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 758       | 66.14%  |
| No        | 388       | 33.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 244       | 21.46%  |
| Germany                | 90        | 7.92%   |
| UK                     | 75        | 6.6%    |
| Canada                 | 53        | 4.66%   |
| India                  | 45        | 3.96%   |
| France                 | 33        | 2.9%    |
| Brazil                 | 30        | 2.64%   |
| Belgium                | 29        | 2.55%   |
| Netherlands            | 28        | 2.46%   |
| Australia              | 28        | 2.46%   |
| Poland                 | 23        | 2.02%   |
| Spain                  | 22        | 1.93%   |
| Russia                 | 20        | 1.76%   |
| Sweden                 | 19        | 1.67%   |
| Italy                  | 18        | 1.58%   |
| Hungary                | 17        | 1.5%    |
| Switzerland            | 16        | 1.41%   |
| Ukraine                | 15        | 1.32%   |
| Argentina              | 15        | 1.32%   |
| Romania                | 14        | 1.23%   |
| Turkey                 | 13        | 1.14%   |
| Norway                 | 13        | 1.14%   |
| Indonesia              | 13        | 1.14%   |
| Greece                 | 13        | 1.14%   |
| Finland                | 12        | 1.06%   |
| Bulgaria               | 12        | 1.06%   |
| Portugal               | 9         | 0.79%   |
| Ireland                | 9         | 0.79%   |
| Bangladesh             | 9         | 0.79%   |
| South Africa           | 8         | 0.7%    |
| Denmark                | 8         | 0.7%    |
| Colombia               | 8         | 0.7%    |
| Mexico                 | 7         | 0.62%   |
| Czechia                | 7         | 0.62%   |
| China                  | 7         | 0.62%   |
| Austria                | 7         | 0.62%   |
| Vietnam                | 6         | 0.53%   |
| Malaysia               | 6         | 0.53%   |
| Chile                  | 6         | 0.53%   |
| Slovenia               | 5         | 0.44%   |
| Serbia                 | 5         | 0.44%   |
| Lithuania              | 5         | 0.44%   |
| Lebanon                | 5         | 0.44%   |
| Japan                  | 5         | 0.44%   |
| Hong Kong              | 5         | 0.44%   |
| Estonia                | 5         | 0.44%   |
| Egypt                  | 5         | 0.44%   |
| Croatia                | 5         | 0.44%   |
| Slovakia               | 4         | 0.35%   |
| Morocco                | 4         | 0.35%   |
| Israel                 | 4         | 0.35%   |
| Algeria                | 4         | 0.35%   |
| Singapore              | 3         | 0.26%   |
| Latvia                 | 3         | 0.26%   |
| Kenya                  | 3         | 0.26%   |
| Iran                   | 3         | 0.26%   |
| Bosnia and Herzegovina | 3         | 0.26%   |
| Azerbaijan             | 3         | 0.26%   |
| UAE                    | 2         | 0.18%   |
| Tunisia                | 2         | 0.18%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 14        | 1.17%   |
| Sydney            | 13        | 1.09%   |
| Durham            | 12        | 1%      |
| Paris             | 9         | 0.75%   |
| Warsaw            | 7         | 0.59%   |
| London            | 7         | 0.59%   |
| Duffel            | 7         | 0.59%   |
| Budapest          | 7         | 0.59%   |
| Athens            | 7         | 0.59%   |
| Wilrijk           | 6         | 0.5%    |
| Sofia             | 6         | 0.5%    |
| Moscow            | 6         | 0.5%    |
| Madrid            | 6         | 0.5%    |
| Chicago           | 6         | 0.5%    |
| Bengaluru         | 6         | 0.5%    |
| Vienna            | 5         | 0.42%   |
| Tallinn           | 5         | 0.42%   |
| Sao Paulo         | 5         | 0.42%   |
| Rio de Janeiro    | 5         | 0.42%   |
| Pune              | 5         | 0.42%   |
| Oslo              | 5         | 0.42%   |
| New Delhi         | 5         | 0.42%   |
| Melbourne         | 5         | 0.42%   |
| Kyiv              | 5         | 0.42%   |
| Houston           | 5         | 0.42%   |
| Dhaka             | 5         | 0.42%   |
| Denver            | 5         | 0.42%   |
| Dallas            | 5         | 0.42%   |
| Central           | 5         | 0.42%   |
| Brisbane          | 5         | 0.42%   |
| Amsterdam         | 5         | 0.42%   |
| Zurich            | 4         | 0.33%   |
| Tel Aviv          | 4         | 0.33%   |
| Stuttgart         | 4         | 0.33%   |
| Stockholm         | 4         | 0.33%   |
| Santiago          | 4         | 0.33%   |
| Portland          | 4         | 0.33%   |
| Lisbon            | 4         | 0.33%   |
| Lerwick           | 4         | 0.33%   |
| Kuala Lumpur      | 4         | 0.33%   |
| Kolkata           | 4         | 0.33%   |
| Jakarta           | 4         | 0.33%   |
| Frankfurt am Main | 4         | 0.33%   |
| Edmonton          | 4         | 0.33%   |
| Dublin            | 4         | 0.33%   |
| Dagenham          | 4         | 0.33%   |
| Cairo             | 4         | 0.33%   |
| Buenos Aires      | 4         | 0.33%   |
| Bucharest         | 4         | 0.33%   |
| Brooklyn          | 4         | 0.33%   |
| Bergheim          | 4         | 0.33%   |
| Beirut            | 4         | 0.33%   |
| Ankara            | 4         | 0.33%   |
| Tucson            | 3         | 0.25%   |
| Toronto           | 3         | 0.25%   |
| Tehran            | 3         | 0.25%   |
| St Petersburg     | 3         | 0.25%   |
| Spokane           | 3         | 0.25%   |
| Singapore         | 3         | 0.25%   |
| Seville           | 3         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 368       | 599    | 19.27%  |
| WDC                 | 320       | 510    | 16.75%  |
| Seagate             | 271       | 413    | 14.19%  |
| Toshiba             | 131       | 172    | 6.86%   |
| Kingston            | 101       | 121    | 5.29%   |
| SanDisk             | 83        | 95     | 4.35%   |
| Crucial             | 81        | 122    | 4.24%   |
| SK Hynix            | 47        | 58     | 2.46%   |
| Intel               | 47        | 79     | 2.46%   |
| Hitachi             | 40        | 47     | 2.09%   |
| A-DATA Technology   | 37        | 45     | 1.94%   |
| Unknown             | 33        | 44     | 1.73%   |
| HGST                | 26        | 34     | 1.36%   |
| Phison              | 24        | 40     | 1.26%   |
| Apple               | 20        | 30     | 1.05%   |
| PNY                 | 18        | 29     | 0.94%   |
| Micron Technology   | 18        | 19     | 0.94%   |
| SPCC                | 16        | 20     | 0.84%   |
| Corsair             | 16        | 24     | 0.84%   |
| JMicron             | 14        | 17     | 0.73%   |
| LITEON              | 12        | 13     | 0.63%   |
| China               | 12        | 26     | 0.63%   |
| XPG                 | 10        | 13     | 0.52%   |
| Transcend           | 10        | 18     | 0.52%   |
| KIOXIA              | 10        | 12     | 0.52%   |
| Gigabyte Technology | 8         | 8      | 0.42%   |
| Silicon Motion      | 7         | 8      | 0.37%   |
| Patriot             | 7         | 13     | 0.37%   |
| PLEXTOR             | 6         | 6      | 0.31%   |
| OCZ                 | 6         | 7      | 0.31%   |
| Mushkin             | 6         | 9      | 0.31%   |
| LITEONIT            | 6         | 6      | 0.31%   |
| Hewlett-Packard     | 6         | 7      | 0.31%   |
| SABRENT             | 5         | 6      | 0.26%   |
| KingSpec            | 5         | 5      | 0.26%   |
| Intenso             | 4         | 4      | 0.21%   |
| GOODRAM             | 4         | 8      | 0.21%   |
| ASMT                | 4         | 4      | 0.21%   |
| Unknown             | 4         | 4      | 0.21%   |
| MAXTOR              | 3         | 5      | 0.16%   |
| Lexar               | 3         | 3      | 0.16%   |
| Lenovo              | 3         | 4      | 0.16%   |
| Vaseky              | 2         | 4      | 0.1%    |
| Union Memory        | 2         | 2      | 0.1%    |
| TO Exter            | 2         | 2      | 0.1%    |
| Team                | 2         | 2      | 0.1%    |
| Leven               | 2         | 2      | 0.1%    |
| KingFast            | 2         | 2      | 0.1%    |
| HS-SSD-C100         | 2         | 3      | 0.1%    |
| Fantom              | 2         | 3      | 0.1%    |
| External            | 2         | 6      | 0.1%    |
| Drevo               | 2         | 2      | 0.1%    |
| AMD                 | 2         | 3      | 0.1%    |
| addlink             | 2         | 2      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.05%   |
| W800S               | 1         | 3      | 0.05%   |
| Verbatim            | 1         | 1      | 0.05%   |
| V-GeN               | 1         | 2      | 0.05%   |
| USB30               | 1         | 1      | 0.05%   |
| tigo                | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB           | 42        | 1.91%   |
| Seagate ST1000LM035-1RK172 1TB      | 26        | 1.18%   |
| Kingston SA400S37240G 240GB SSD     | 25        | 1.14%   |
| Samsung SSD 970 EVO Plus 500GB      | 22        | 1%      |
| Seagate ST1000DM010-2EP102 1TB      | 20        | 0.91%   |
| Samsung SSD 970 EVO Plus 1TB        | 20        | 0.91%   |
| Samsung SSD 850 EVO 250GB           | 20        | 0.91%   |
| Samsung SSD 850 EVO 500GB           | 19        | 0.86%   |
| Samsung SSD 860 EVO 1TB             | 17        | 0.77%   |
| Samsung SSD 860 EVO 250GB           | 16        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB            | 14        | 0.64%   |
| Toshiba MQ04ABF100 1TB              | 14        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB      | 14        | 0.64%   |
| Kingston SA400S37120G 120GB SSD     | 14        | 0.64%   |
| Toshiba MQ01ABD100 1TB              | 13        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 0.59%   |
| Samsung SSD 970 EVO 1TB             | 13        | 0.59%   |
| Crucial CT1000MX500SSD1 1TB         | 13        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 12        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB      | 12        | 0.55%   |
| Crucial CT500MX500SSD1 500GB        | 12        | 0.55%   |
| Kingston SA400S37480G 480GB SSD     | 11        | 0.5%    |
| Crucial CT1000P1SSD8 1TB            | 11        | 0.5%    |
| Unknown SD/MMC/MS PRO 16GB          | 10        | 0.46%   |
| Toshiba KXG60ZNV1T02 1TB            | 10        | 0.46%   |
| Samsung SSD 840 EVO 250GB           | 10        | 0.46%   |
| Toshiba HDWD110 1TB                 | 9         | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB      | 9         | 0.41%   |
| JMicron Generic 240GB               | 9         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB      | 8         | 0.36%   |
| Seagate Expansion+ 2TB              | 8         | 0.36%   |
| Intel SSDPEKNW010T8 1TB             | 8         | 0.36%   |
| Crucial CT480BX500SSD1 480GB        | 8         | 0.36%   |
| A-DATA SX8200PNP 1TB                | 8         | 0.36%   |
| Toshiba DT01ACA100 1TB              | 7         | 0.32%   |
| Seagate ST31000528AS 1TB            | 7         | 0.32%   |
| Seagate ST1000LM049-2GH172 1TB      | 7         | 0.32%   |
| Samsung SSD 980 PRO 1TB             | 7         | 0.32%   |
| Samsung SSD 840 EVO 120GB           | 7         | 0.32%   |
| HGST HTS721010A9E630 1TB            | 7         | 0.32%   |
| Crucial CT240BX500SSD1 240GB        | 7         | 0.32%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 6         | 0.27%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 6         | 0.27%   |
| Toshiba HDWD120 2TB                 | 6         | 0.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 6         | 0.27%   |
| Seagate ST4000DM004-2CV104 4TB      | 6         | 0.27%   |
| Seagate ST3000DM001-1ER166 3TB      | 6         | 0.27%   |
| SanDisk SSD PLUS 480GB              | 6         | 0.27%   |
| SanDisk SSD PLUS 240GB              | 6         | 0.27%   |
| Samsung SSD 980 PRO 500GB           | 6         | 0.27%   |
| Samsung SSD 970 EVO Plus 250GB      | 6         | 0.27%   |
| Samsung SSD 970 EVO 500GB           | 6         | 0.27%   |
| Samsung SSD 870 QVO 1TB             | 6         | 0.27%   |
| Samsung SSD 870 EVO 1TB             | 6         | 0.27%   |
| Samsung SSD 860 QVO 1TB             | 6         | 0.27%   |
| Samsung SSD 850 EVO 1TB             | 6         | 0.27%   |
| PNY CS900 240GB SSD                 | 6         | 0.27%   |
| A-DATA SX8200PNP 512GB              | 6         | 0.27%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 5         | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 262       | 393    | 37.32%  |
| WDC                 | 212       | 351    | 30.2%   |
| Toshiba             | 96        | 126    | 13.68%  |
| Hitachi             | 40        | 47     | 5.7%    |
| Samsung Electronics | 30        | 38     | 4.27%   |
| HGST                | 26        | 34     | 3.7%    |
| Unknown             | 11        | 15     | 1.57%   |
| Apple               | 5         | 7      | 0.71%   |
| SABRENT             | 3         | 4      | 0.43%   |
| MAXTOR              | 3         | 5      | 0.43%   |
| Hewlett-Packard     | 2         | 3      | 0.28%   |
| Fantom              | 2         | 3      | 0.28%   |
| ASMT                | 2         | 2      | 0.28%   |
| WD MediaMax         | 1         | 1      | 0.14%   |
| KESU                | 1         | 1      | 0.14%   |
| JMicron             | 1         | 4      | 0.14%   |
| Intenso             | 1         | 1      | 0.14%   |
| HGST HUS            | 1         | 1      | 0.14%   |
| Fujitsu             | 1         | 1      | 0.14%   |
| ExcelStor           | 1         | 2      | 0.14%   |
| Unknown             | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 220       | 335    | 29.22%  |
| Kingston            | 81        | 94     | 10.76%  |
| SanDisk             | 72        | 81     | 9.56%   |
| Crucial             | 65        | 93     | 8.63%   |
| WDC                 | 60        | 75     | 7.97%   |
| A-DATA Technology   | 21        | 27     | 2.79%   |
| PNY                 | 17        | 25     | 2.26%   |
| SK Hynix            | 14        | 21     | 1.86%   |
| Intel               | 14        | 25     | 1.86%   |
| Apple               | 13        | 15     | 1.73%   |
| SPCC                | 12        | 14     | 1.59%   |
| China               | 12        | 26     | 1.59%   |
| Toshiba             | 11        | 17     | 1.46%   |
| Micron Technology   | 11        | 12     | 1.46%   |
| Transcend           | 9         | 17     | 1.2%    |
| LITEON              | 9         | 10     | 1.2%    |
| JMicron             | 9         | 9      | 1.2%    |
| Patriot             | 7         | 13     | 0.93%   |
| OCZ                 | 6         | 7      | 0.8%    |
| LITEONIT            | 6         | 6      | 0.8%    |
| KingSpec            | 5         | 5      | 0.66%   |
| Corsair             | 5         | 5      | 0.66%   |
| PLEXTOR             | 4         | 4      | 0.53%   |
| Mushkin             | 4         | 7      | 0.53%   |
| GOODRAM             | 4         | 8      | 0.53%   |
| Gigabyte Technology | 4         | 4      | 0.53%   |
| Unknown             | 3         | 3      | 0.4%    |
| Seagate             | 3         | 5      | 0.4%    |
| Lexar               | 3         | 3      | 0.4%    |
| Intenso             | 3         | 3      | 0.4%    |
| Vaseky              | 2         | 4      | 0.27%   |
| TO Exter            | 2         | 2      | 0.27%   |
| Team                | 2         | 2      | 0.27%   |
| Leven               | 2         | 2      | 0.27%   |
| KingFast            | 2         | 2      | 0.27%   |
| HS-SSD-C100         | 2         | 3      | 0.27%   |
| Hewlett-Packard     | 2         | 2      | 0.27%   |
| External            | 2         | 6      | 0.27%   |
| Drevo               | 2         | 2      | 0.27%   |
| ASMT                | 2         | 2      | 0.27%   |
| AMD                 | 2         | 3      | 0.27%   |
| W800S               | 1         | 3      | 0.13%   |
| Verbatim            | 1         | 1      | 0.13%   |
| V-GeN               | 1         | 2      | 0.13%   |
| USB30               | 1         | 1      | 0.13%   |
| T-FORCE             | 1         | 1      | 0.13%   |
| StoreJet            | 1         | 1      | 0.13%   |
| SSSTC               | 1         | 1      | 0.13%   |
| PALIT               | 1         | 1      | 0.13%   |
| NGFF                | 1         | 1      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |
| KODAK               | 1         | 1      | 0.13%   |
| KingDian            | 1         | 1      | 0.13%   |
| INTEL SS            | 1         | 1      | 0.13%   |
| Integral            | 1         | 1      | 0.13%   |
| HS-SSD-E100         | 1         | 1      | 0.13%   |
| HPE                 | 1         | 1      | 0.13%   |
| Hoodisk             | 1         | 1      | 0.13%   |
| DOGFISH             | 1         | 1      | 0.13%   |
| CT240BX5            | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 611       | 1027   | 36.33%  |
| HDD     | 584       | 1040   | 34.72%  |
| NVMe    | 452       | 667    | 26.87%  |
| MMC     | 21        | 27     | 1.25%   |
| Unknown | 14        | 19     | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 891       | 1925   | 60.78%  |
| NVMe | 452       | 667    | 30.83%  |
| SAS  | 102       | 161    | 6.96%   |
| MMC  | 21        | 27     | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 642       | 1065   | 49.2%   |
| 0.51-1.0   | 436       | 633    | 33.41%  |
| 1.01-2.0   | 134       | 220    | 10.27%  |
| 3.01-4.0   | 47        | 68     | 3.6%    |
| 2.01-3.0   | 25        | 43     | 1.92%   |
| 4.01-10.0  | 18        | 31     | 1.38%   |
| 10.01-20.0 | 3         | 7      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 268       | 22.46%  |
| 251-500        | 245       | 20.54%  |
| 501-1000       | 198       | 16.6%   |
| 1001-2000      | 148       | 12.41%  |
| More than 3000 | 104       | 8.72%   |
| Unknown        | 57        | 4.78%   |
| 1-20           | 56        | 4.69%   |
| 2001-3000      | 49        | 4.11%   |
| 51-100         | 49        | 4.11%   |
| 21-50          | 19        | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 335       | 26.99%  |
| 21-50          | 240       | 19.34%  |
| 101-250        | 178       | 14.34%  |
| 51-100         | 138       | 11.12%  |
| 251-500        | 102       | 8.22%   |
| 501-1000       | 89        | 7.17%   |
| Unknown        | 57        | 4.59%   |
| 1001-2000      | 46        | 3.71%   |
| More than 3000 | 32        | 2.58%   |
| 2001-3000      | 23        | 1.85%   |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 7      | 3.04%   |
| Seagate ST31000528AS 1TB            | 5         | 5      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 5      | 2.17%   |
| Seagate ST9320325AS 320GB           | 4         | 5      | 1.74%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 1.3%    |
| Seagate ST1000DM003-9YN162 1TB      | 3         | 3      | 1.3%    |
| WDC WD5000AAKX-603CA0 500GB         | 2         | 7      | 0.87%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 6      | 0.87%   |
| WDC WD3200AAJS-00L7A0 320GB         | 2         | 2      | 0.87%   |
| WDC WD20EARX-00PASB0 2TB            | 2         | 2      | 0.87%   |
| WDC WD10EARS-00Y5B1 1TB             | 2         | 3      | 0.87%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 0.87%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.87%   |
| Seagate ST9250315AS 250GB           | 2         | 2      | 0.87%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 0.87%   |
| Seagate ST3500413AS 500GB           | 2         | 2      | 0.87%   |
| Seagate ST3500312CS 500GB           | 2         | 5      | 0.87%   |
| Seagate ST31000524AS 1TB            | 2         | 2      | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 3      | 0.87%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 2      | 0.87%   |
| Seagate ST1000LM014-1EJ164 1TB      | 2         | 2      | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2      | 0.87%   |
| SanDisk SSD PLUS 1000GB             | 2         | 3      | 0.87%   |
| Samsung Electronics SSD 870 EVO 1TB | 2         | 2      | 0.87%   |
| MAXTOR STM3250310AS 250GB           | 2         | 3      | 0.87%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 2      | 0.87%   |
| Hitachi HDS723020BLA642 2TB         | 2         | 2      | 0.87%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 3      | 0.87%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 0.87%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 0.87%   |
| XPG SPECTRIX S40G 4TB               | 1         | 1      | 0.43%   |
| WDC WDS500G1X0E-00AFY0 500GB        | 1         | 1      | 0.43%   |
| WDC WD7500BPVT-55HXZT4 752GB        | 1         | 1      | 0.43%   |
| WDC WD6400BEVT-60A0RT0 640GB        | 1         | 9      | 0.43%   |
| WDC WD6400AAKS-22A7B2 640GB         | 1         | 2      | 0.43%   |
| WDC WD60EZRZ-00GZ5B1 6TB            | 1         | 1      | 0.43%   |
| WDC WD5000L 500GB                   | 1         | 1      | 0.43%   |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000BEVT-75A0RT0 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000BEVT-35A0RT0 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000AVCS-632DY1 500GB         | 1         | 1      | 0.43%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 1         | 1      | 0.43%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 3      | 0.43%   |
| WDC WD5000AAKS-60WWPA0 500GB        | 1         | 1      | 0.43%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 1      | 0.43%   |
| WDC WD5000AADS-00M2B0 500GB         | 1         | 1      | 0.43%   |
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 0.43%   |
| WDC WD3200BEKT-75PVMT0 320GB        | 1         | 1      | 0.43%   |
| WDC WD3200AVJS-63B6A0 320GB         | 1         | 1      | 0.43%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 0.43%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1         | 1      | 0.43%   |
| WDC WD30EFRX-68N32N0 3TB            | 1         | 1      | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1         | 1      | 0.43%   |
| WDC WD25EZRX-00MMMB0 2TB            | 1         | 1      | 0.43%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 1      | 0.43%   |
| WDC WD2500AAKX-603CA0 250GB         | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 79     | 29.55%  |
| WDC                 | 56        | 94     | 25.45%  |
| Samsung Electronics | 17        | 18     | 7.73%   |
| Toshiba             | 14        | 16     | 6.36%   |
| Hitachi             | 10        | 12     | 4.55%   |
| HGST                | 8         | 10     | 3.64%   |
| Kingston            | 6         | 10     | 2.73%   |
| Intel               | 6         | 14     | 2.73%   |
| SanDisk             | 5         | 6      | 2.27%   |
| Transcend           | 3         | 3      | 1.36%   |
| Micron Technology   | 3         | 3      | 1.36%   |
| MAXTOR              | 3         | 5      | 1.36%   |
| Corsair             | 3         | 3      | 1.36%   |
| SK Hynix            | 2         | 2      | 0.91%   |
| LITEONIT            | 2         | 2      | 0.91%   |
| DREVO               | 2         | 2      | 0.91%   |
| Crucial             | 2         | 2      | 0.91%   |
| A-DATA Technology   | 2         | 2      | 0.91%   |
| XPG                 | 1         | 1      | 0.45%   |
| SSSTC               | 1         | 1      | 0.45%   |
| SPCC                | 1         | 1      | 0.45%   |
| PLEXTOR             | 1         | 1      | 0.45%   |
| Mushkin             | 1         | 1      | 0.45%   |
| Lenovo              | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| China               | 1         | 2      | 0.45%   |
| ASMedia             | 1         | 2      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| Unknown             | 1         | 1      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 79     | 40.12%  |
| WDC                 | 56        | 93     | 34.57%  |
| Toshiba             | 13        | 15     | 8.02%   |
| Hitachi             | 10        | 12     | 6.17%   |
| HGST                | 8         | 10     | 4.94%   |
| Samsung Electronics | 5         | 5      | 3.09%   |
| MAXTOR              | 3         | 5      | 1.85%   |
| Apple               | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 151       | 221    | 72.6%   |
| SSD  | 48        | 65     | 23.08%  |
| NVMe | 9         | 10     | 4.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB       | 1         | 1      | 16.67%  |
| Seagate ST9320325AS 320GB      | 1         | 1      | 16.67%  |
| Seagate ST32000641AS 2TB       | 1         | 2      | 16.67%  |
| Seagate ST2000DL001-9VT156 2TB | 1         | 1      | 16.67%  |
| HGST HTS721010A9E630 1TB       | 1         | 1      | 16.67%  |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 50%     |
| HGST    | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 907       | 2055   | 66.89%  |
| Detected | 239       | 422    | 17.63%  |
| Malfunc  | 204       | 296    | 15.04%  |
| Failed   | 6         | 7      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 725       | 46.06%  |
| AMD                          | 290       | 18.42%  |
| Samsung Electronics          | 179       | 11.37%  |
| Sandisk                      | 75        | 4.76%   |
| Phison Electronics           | 45        | 2.86%   |
| SK Hynix                     | 34        | 2.16%   |
| ASMedia Technology           | 34        | 2.16%   |
| Marvell Technology Group     | 23        | 1.46%   |
| Kingston Technology Company  | 23        | 1.46%   |
| Toshiba America Info Systems | 21        | 1.33%   |
| Micron/Crucial Technology    | 19        | 1.21%   |
| ADATA Technology             | 18        | 1.14%   |
| KIOXIA                       | 15        | 0.95%   |
| Silicon Motion               | 14        | 0.89%   |
| Nvidia                       | 12        | 0.76%   |
| Realtek Semiconductor        | 8         | 0.51%   |
| Micron Technology            | 7         | 0.44%   |
| Seagate Technology           | 6         | 0.38%   |
| Lite-On Technology           | 5         | 0.32%   |
| JMicron Technology           | 5         | 0.32%   |
| Lenovo                       | 3         | 0.19%   |
| Apple                        | 3         | 0.19%   |
| VIA Technologies             | 2         | 0.13%   |
| Union Memory (Shenzhen)      | 2         | 0.13%   |
| Unknown                      | 1         | 0.06%   |
| Silicon Image                | 1         | 0.06%   |
| Shenzhen Longsys Electronics | 1         | 0.06%   |
| LSI Logic / Symbios Logic    | 1         | 0.06%   |
| Broadcom / LSI               | 1         | 0.06%   |
| Adaptec                      | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 217       | 12.27%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 110       | 6.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 76        | 4.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 72        | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 54        | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 51        | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 43        | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 41        | 2.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 37        | 2.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 35        | 1.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 34        | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 33        | 1.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 33        | 1.87%   |
| Phison E12 NVMe Controller                                                              | 28        | 1.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 28        | 1.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 27        | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 25        | 1.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 22        | 1.24%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 22        | 1.24%   |
| Intel SSD 660P Series                                                                   | 21        | 1.19%   |
| Samsung NVMe SSD Controller 980                                                         | 20        | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 20        | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 17        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 17        | 0.96%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 17        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16        | 0.9%    |
| Intel SATA Controller [RAID mode]                                                       | 15        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 15        | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 14        | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 14        | 0.79%   |
| KIOXIA Non-Volatile memory controller                                                   | 14        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 12        | 0.68%   |
| SK Hynix Gold P31 SSD                                                                   | 11        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11        | 0.62%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 11        | 0.62%   |
| Kingston Company A2000 NVMe SSD                                                         | 11        | 0.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11        | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11        | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 0.62%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 10        | 0.57%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 10        | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10        | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9         | 0.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 0.51%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 8         | 0.45%   |
| Sandisk Non-Volatile memory controller                                                  | 8         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8         | 0.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8         | 0.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.45%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7         | 0.4%    |
| Samsung Apple PCIe SSD                                                                  | 7         | 0.4%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 7         | 0.4%    |
| Micron Non-Volatile memory controller                                                   | 7         | 0.4%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 7         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 907       | 59.87%  |
| NVMe | 452       | 29.83%  |
| IDE  | 80        | 5.28%   |
| RAID | 73        | 4.82%   |
| SAS  | 2         | 0.13%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 799       | 70.65%  |
| AMD     | 331       | 29.27%  |
| Unknown | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 22        | 1.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 1.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 18        | 1.59%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 16        | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 1.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 15        | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 13        | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 1.06%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 11        | 0.97%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 10        | 0.88%   |
| Intel Atom CPU C3758 @ 2.20GHz                | 10        | 0.88%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 10        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.8%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 9         | 0.8%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 9         | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 0.8%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9         | 0.8%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 8         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.71%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 8         | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 8         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 0.71%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 8         | 0.71%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 8         | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 0.62%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 7         | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.62%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 7         | 0.62%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 0.62%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 6         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 6         | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.53%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 6         | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.53%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.53%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 0.53%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 6         | 0.53%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 6         | 0.53%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 5         | 0.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 0.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.44%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 0.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.44%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 0.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 294       | 25.99%  |
| Intel Core i7           | 282       | 24.93%  |
| AMD Ryzen 5             | 100       | 8.84%   |
| AMD Ryzen 7             | 92        | 8.13%   |
| Intel Core i3           | 52        | 4.6%    |
| AMD Ryzen 9             | 34        | 3.01%   |
| Intel Pentium           | 30        | 2.65%   |
| Other                   | 27        | 2.39%   |
| AMD Ryzen 3             | 26        | 2.3%    |
| Intel Xeon              | 24        | 2.12%   |
| Intel Celeron           | 24        | 2.12%   |
| Intel Core 2 Duo        | 21        | 1.86%   |
| Intel Atom              | 18        | 1.59%   |
| AMD FX                  | 12        | 1.06%   |
| Intel Core i9           | 9         | 0.8%    |
| AMD A6                  | 9         | 0.8%    |
| AMD A10                 | 9         | 0.8%    |
| Intel Pentium Dual-Core | 7         | 0.62%   |
| AMD A4                  | 7         | 0.62%   |
| AMD A8                  | 6         | 0.53%   |
| AMD Ryzen Threadripper  | 5         | 0.44%   |
| AMD Ryzen 7 PRO         | 5         | 0.44%   |
| AMD Phenom II X4        | 5         | 0.44%   |
| AMD A12                 | 4         | 0.35%   |
| Intel Core m3           | 3         | 0.27%   |
| Intel Pentium Silver    | 2         | 0.18%   |
| Intel Pentium Dual      | 2         | 0.18%   |
| Intel Core 2 Quad       | 2         | 0.18%   |
| AMD Ryzen 5 PRO         | 2         | 0.18%   |
| AMD Phenom II X6        | 2         | 0.18%   |
| AMD E2                  | 2         | 0.18%   |
| AMD Athlon II X2        | 2         | 0.18%   |
| AMD Athlon 64 X2        | 2         | 0.18%   |
| Intel Xeon Silver       | 1         | 0.09%   |
| Intel Pentium Gold      | 1         | 0.09%   |
| Intel Pentium 4         | 1         | 0.09%   |
| Intel Core m7           | 1         | 0.09%   |
| Intel Core M            | 1         | 0.09%   |
| Intel Core 2            | 1         | 0.09%   |
| AMD Athlon II X4        | 1         | 0.09%   |
| AMD Athlon II X3        | 1         | 0.09%   |
| AMD Athlon II           | 1         | 0.09%   |
| AMD Athlon              | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 435       | 38.43%  |
| 2       | 354       | 31.27%  |
| 6       | 159       | 14.05%  |
| 8       | 125       | 11.04%  |
| 12      | 23        | 2.03%   |
| 16      | 14        | 1.24%   |
| 1       | 9         | 0.8%    |
| 3       | 7         | 0.62%   |
| 10      | 3         | 0.27%   |
| 32      | 1         | 0.09%   |
| 24      | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1128      | 99.65%  |
| 2       | 3         | 0.27%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 867       | 76.66%  |
| 1       | 263       | 23.25%  |
| Unknown | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1124      | 99.38%  |
| Unknown        | 7         | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 10.8%   |
| 0x306c3    | 64        | 5.57%   |
| 0x306a9    | 63        | 5.49%   |
| 0x206a7    | 62        | 5.4%    |
| 0x906ea    | 61        | 5.31%   |
| 0x08701021 | 47        | 4.09%   |
| 0x906e9    | 45        | 3.92%   |
| 0x806ea    | 43        | 3.75%   |
| 0x506e3    | 36        | 3.14%   |
| 0x806e9    | 35        | 3.05%   |
| 0x0800820d | 31        | 2.7%    |
| 0x406e3    | 29        | 2.53%   |
| 0x806ec    | 24        | 2.09%   |
| 0x40651    | 22        | 1.92%   |
| 0x0a201009 | 21        | 1.83%   |
| 0x1067a    | 20        | 1.74%   |
| 0x08108109 | 19        | 1.66%   |
| 0x306d4    | 18        | 1.57%   |
| 0x20655    | 18        | 1.57%   |
| 0x08108102 | 17        | 1.48%   |
| 0x0a201016 | 16        | 1.39%   |
| 0x806c1    | 15        | 1.31%   |
| 0x08600106 | 15        | 1.31%   |
| 0xa0652    | 14        | 1.22%   |
| 0x706e5    | 12        | 1.05%   |
| 0x0a50000c | 12        | 1.05%   |
| 0x106e5    | 11        | 0.96%   |
| 0x08701013 | 11        | 0.96%   |
| 0x506f1    | 10        | 0.87%   |
| 0x30678    | 10        | 0.87%   |
| 0x0810100b | 10        | 0.87%   |
| 0x08101016 | 9         | 0.78%   |
| 0x906ec    | 8         | 0.7%    |
| 0x806eb    | 8         | 0.7%    |
| 0x08600104 | 8         | 0.7%    |
| 0x08600103 | 8         | 0.7%    |
| 0x406c4    | 7         | 0.61%   |
| 0x08001138 | 7         | 0.61%   |
| 0x506c9    | 6         | 0.52%   |
| 0x06006705 | 6         | 0.52%   |
| 0xa0653    | 5         | 0.44%   |
| 0x906ed    | 5         | 0.44%   |
| 0x706a8    | 5         | 0.44%   |
| 0x306f2    | 5         | 0.44%   |
| 0x206c2    | 5         | 0.44%   |
| 0x10676    | 5         | 0.44%   |
| 0x06001119 | 5         | 0.44%   |
| 0xa0655    | 4         | 0.35%   |
| 0x806d1    | 4         | 0.35%   |
| 0x706a1    | 4         | 0.35%   |
| 0x6fd      | 4         | 0.35%   |
| 0x406c3    | 4         | 0.35%   |
| 0x40661    | 4         | 0.35%   |
| 0x20652    | 4         | 0.35%   |
| 0x0a50000b | 4         | 0.35%   |
| 0x08001137 | 4         | 0.35%   |
| 0x06003106 | 4         | 0.35%   |
| 0x06000852 | 4         | 0.35%   |
| 0x010000b6 | 4         | 0.35%   |
| 0xa0671    | 3         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 257       | 22.68%  |
| Haswell       | 103       | 9.09%   |
| Zen 2         | 96        | 8.47%   |
| IvyBridge     | 78        | 6.88%   |
| Zen+          | 74        | 6.53%   |
| Skylake       | 74        | 6.53%   |
| SandyBridge   | 73        | 6.44%   |
| Zen 3         | 56        | 4.94%   |
| Zen           | 34        | 3%      |
| Westmere      | 32        | 2.82%   |
| Penryn        | 27        | 2.38%   |
| CometLake     | 25        | 2.21%   |
| Silvermont    | 23        | 2.03%   |
| Broadwell     | 22        | 1.94%   |
| Excavator     | 21        | 1.85%   |
| Piledriver    | 18        | 1.59%   |
| IceLake       | 18        | 1.59%   |
| TigerLake     | 16        | 1.41%   |
| Goldmont      | 16        | 1.41%   |
| Nehalem       | 14        | 1.24%   |
| K10           | 12        | 1.06%   |
| Goldmont plus | 9         | 0.79%   |
| Core          | 8         | 0.71%   |
| Unknown       | 7         | 0.62%   |
| Steamroller   | 5         | 0.44%   |
| K8 Hammer     | 3         | 0.26%   |
| Jaguar        | 3         | 0.26%   |
| Bonnell       | 3         | 0.26%   |
| Puma          | 2         | 0.18%   |
| Bulldozer     | 2         | 0.18%   |
| NetBurst      | 1         | 0.09%   |
| K10 Llano     | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 600       | 43.51%  |
| Nvidia                     | 462       | 33.5%   |
| AMD                        | 306       | 22.19%  |
| ASPEED Technology          | 10        | 0.73%   |
| Matrox Electronics Systems | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 53        | 3.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 46        | 3.27%   |
| Intel UHD Graphics 620                                                                   | 41        | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 2.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 36        | 2.56%   |
| Intel HD Graphics 630                                                                    | 34        | 2.41%   |
| Intel HD Graphics 620                                                                    | 33        | 2.34%   |
| AMD Renoir                                                                               | 29        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 1.42%   |
| Intel HD Graphics 530                                                                    | 19        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 1.21%   |
| Intel HD Graphics 5500                                                                   | 17        | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16        | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 1.07%   |
| AMD Cezanne                                                                              | 14        | 0.99%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 13        | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 13        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 12        | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 12        | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 11        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 11        | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 11        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 10        | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 10        | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.71%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 10        | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.71%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 9         | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 9         | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 9         | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 0.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.5%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 7         | 0.5%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 7         | 0.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.5%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 0.5%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 6         | 0.43%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 6         | 0.43%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.43%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 6         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 375       | 32.95%  |
| 1 x Nvidia     | 267       | 23.46%  |
| 1 x AMD        | 244       | 21.44%  |
| Intel + Nvidia | 174       | 15.29%  |
| Intel + AMD    | 26        | 2.28%   |
| AMD + Nvidia   | 19        | 1.67%   |
| 2 x AMD        | 17        | 1.49%   |
| 1 x ASPEED     | 10        | 0.88%   |
| Other          | 3         | 0.26%   |
| 2 x Nvidia     | 2         | 0.18%   |
| 1 x Matrox     | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 820       | 71.62%  |
| Proprietary | 285       | 24.89%  |
| Unknown     | 40        | 3.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 609       | 52.64%  |
| 1.01-2.0   | 128       | 11.06%  |
| 3.01-4.0   | 95        | 8.21%   |
| 7.01-8.0   | 92        | 7.95%   |
| 0.01-0.5   | 86        | 7.43%   |
| 0.51-1.0   | 60        | 5.19%   |
| 5.01-6.0   | 40        | 3.46%   |
| 8.01-16.0  | 36        | 3.11%   |
| 2.01-3.0   | 10        | 0.86%   |
| 16.01-24.0 | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 139       | 10.56%  |
| LG Display              | 130       | 9.88%   |
| AU Optronics            | 122       | 9.27%   |
| Chimei Innolux          | 107       | 8.13%   |
| Dell                    | 100       | 7.6%    |
| BOE                     | 97        | 7.37%   |
| Goldstar                | 89        | 6.76%   |
| Acer                    | 54        | 4.1%    |
| BenQ                    | 46        | 3.5%    |
| AOC                     | 41        | 3.12%   |
| Ancor Communications    | 41        | 3.12%   |
| Hewlett-Packard         | 35        | 2.66%   |
| Sharp                   | 29        | 2.2%    |
| Apple                   | 27        | 2.05%   |
| Lenovo                  | 22        | 1.67%   |
| Philips                 | 19        | 1.44%   |
| ASUSTek Computer        | 17        | 1.29%   |
| ViewSonic               | 13        | 0.99%   |
| Sony                    | 13        | 0.99%   |
| Iiyama                  | 12        | 0.91%   |
| PANDA                   | 10        | 0.76%   |
| Eizo                    | 10        | 0.76%   |
| Vizio                   | 8         | 0.61%   |
| Unknown                 | 8         | 0.61%   |
| Panasonic               | 8         | 0.61%   |
| Chi Mei Optoelectronics | 8         | 0.61%   |
| Sceptre Tech            | 7         | 0.53%   |
| MSI                     | 7         | 0.53%   |
| InfoVision              | 7         | 0.53%   |
| CSO                     | 7         | 0.53%   |
| Toshiba                 | 5         | 0.38%   |
| Vestel Elektronik       | 4         | 0.3%    |
| Gigabyte Technology     | 4         | 0.3%    |
| VIE                     | 3         | 0.23%   |
| MStar                   | 3         | 0.23%   |
| HannStar                | 3         | 0.23%   |
| Compal                  | 3         | 0.23%   |
| VIZ                     | 2         | 0.15%   |
| UTV                     | 2         | 0.15%   |
| ONN                     | 2         | 0.15%   |
| NEC Computers           | 2         | 0.15%   |
| MiTAC                   | 2         | 0.15%   |
| Mi                      | 2         | 0.15%   |
| LG Philips              | 2         | 0.15%   |
| LG Electronics          | 2         | 0.15%   |
| InnoLux Display         | 2         | 0.15%   |
| Fujitsu Siemens         | 2         | 0.15%   |
| Denver                  | 2         | 0.15%   |
| CPT                     | 2         | 0.15%   |
| ___                     | 1         | 0.08%   |
| Westinghouse            | 1         | 0.08%   |
| Unknown (XXX)           | 1         | 0.08%   |
| SUNNY                   | 1         | 0.08%   |
| Seiki                   | 1         | 0.08%   |
| RCA                     | 1         | 0.08%   |
| PRISM+                  | 1         | 0.08%   |
| Pixio                   | 1         | 0.08%   |
| Philco                  | 1         | 0.08%   |
| PEGA                    | 1         | 0.08%   |
| Packard Bell            | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 9         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 7         | 0.52%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 5         | 0.37%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 5         | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 5         | 0.37%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 5         | 0.37%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 4         | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.29%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch     | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch | 4         | 0.29%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.29%   |
| Panasonic TV MEIA296 3840x2160 1280x720mm 57.8-inch                   | 4         | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.29%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 4         | 0.29%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.29%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 4         | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 4         | 0.29%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 4         | 0.29%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                     | 4         | 0.29%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.29%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 4         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 3         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.22%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 3         | 0.22%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 3         | 0.22%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 3         | 0.22%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.22%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.22%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 3         | 0.22%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 3         | 0.22%   |
| Goldstar Ultra HD GSM5B09 3780x2160 600x340mm 27.2-inch               | 3         | 0.22%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 3         | 0.22%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 3         | 0.22%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                 | 3         | 0.22%   |
| Dell U2713HM DEL4080 2560x1440 600x340mm 27.2-inch                    | 3         | 0.22%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 609       | 49.55%  |
| 1366x768 (WXGA)    | 174       | 14.16%  |
| 2560x1440 (QHD)    | 98        | 7.97%   |
| 3840x2160 (4K)     | 82        | 6.67%   |
| 1600x900 (HD+)     | 41        | 3.34%   |
| 1280x1024 (SXGA)   | 26        | 2.12%   |
| 2560x1080          | 25        | 2.03%   |
| 1920x1200 (WUXGA)  | 24        | 1.95%   |
| 1680x1050 (WSXGA+) | 22        | 1.79%   |
| 1280x800 (WXGA)    | 21        | 1.71%   |
| 1440x900 (WXGA+)   | 19        | 1.55%   |
| 3440x1440          | 18        | 1.46%   |
| 2880x1800          | 10        | 0.81%   |
| 1360x768           | 9         | 0.73%   |
| 2560x1600          | 7         | 0.57%   |
| 1920x540           | 7         | 0.57%   |
| 3840x1080          | 6         | 0.49%   |
| 3200x1800 (QHD+)   | 6         | 0.49%   |
| 2160x1440          | 5         | 0.41%   |
| Unknown            | 3         | 0.24%   |
| 3840x2400          | 2         | 0.16%   |
| 3840x1600          | 2         | 0.16%   |
| 2160x1350          | 2         | 0.16%   |
| 1600x1200          | 2         | 0.16%   |
| 1024x600           | 2         | 0.16%   |
| 5760x2160          | 1         | 0.08%   |
| 3840x1200          | 1         | 0.08%   |
| 3240x2160          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 2048x1152          | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 299       | 22.86%  |
| 27      | 141       | 10.78%  |
| 24      | 118       | 9.02%   |
| 13      | 104       | 7.95%   |
| 14      | 98        | 7.49%   |
| 23      | 88        | 6.73%   |
| 21      | 79        | 6.04%   |
| 17      | 74        | 5.66%   |
| 31      | 39        | 2.98%   |
| 34      | 35        | 2.68%   |
| 19      | 27        | 2.06%   |
| Unknown | 26        | 1.99%   |
| 12      | 24        | 1.83%   |
| 18      | 17        | 1.3%    |
| 22      | 16        | 1.22%   |
| 84      | 13        | 0.99%   |
| 72      | 12        | 0.92%   |
| 54      | 10        | 0.76%   |
| 20      | 10        | 0.76%   |
| 11      | 7         | 0.54%   |
| 32      | 6         | 0.46%   |
| 25      | 6         | 0.46%   |
| 16      | 6         | 0.46%   |
| 40      | 5         | 0.38%   |
| 28      | 5         | 0.38%   |
| 26      | 5         | 0.38%   |
| 52      | 4         | 0.31%   |
| 39      | 4         | 0.31%   |
| 10      | 4         | 0.31%   |
| 48      | 3         | 0.23%   |
| 35      | 3         | 0.23%   |
| 55      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 46      | 2         | 0.15%   |
| 43      | 2         | 0.15%   |
| 42      | 2         | 0.15%   |
| 37      | 2         | 0.15%   |
| 29      | 2         | 0.15%   |
| 142     | 1         | 0.08%   |
| 74      | 1         | 0.08%   |
| 65      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 36      | 1         | 0.08%   |
| 33      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 452       | 35.56%  |
| 501-600        | 313       | 24.63%  |
| 401-500        | 135       | 10.62%  |
| 201-300        | 98        | 7.71%   |
| 351-400        | 72        | 5.66%   |
| 601-700        | 63        | 4.96%   |
| 701-800        | 43        | 3.38%   |
| Unknown        | 26        | 2.05%   |
| 1501-2000      | 25        | 1.97%   |
| 1001-1500      | 25        | 1.97%   |
| 801-900        | 14        | 1.1%    |
| 901-1000       | 4         | 0.31%   |
| More than 2000 | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 922       | 79.9%   |
| 16/10   | 114       | 9.88%   |
| 21/9    | 46        | 3.99%   |
| 5/4     | 25        | 2.17%   |
| Unknown | 19        | 1.65%   |
| 3/2     | 13        | 1.13%   |
| 4/3     | 8         | 0.69%   |
| 32/9    | 4         | 0.35%   |
| 6/5     | 2         | 0.17%   |
| 1.00    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 294       | 22.86%  |
| 201-250        | 245       | 19.05%  |
| 81-90          | 149       | 11.59%  |
| 301-350        | 143       | 11.12%  |
| 351-500        | 84        | 6.53%   |
| 121-130        | 54        | 4.2%    |
| 71-80          | 53        | 4.12%   |
| 151-200        | 49        | 3.81%   |
| More than 1000 | 43        | 3.34%   |
| 251-300        | 42        | 3.27%   |
| 141-150        | 34        | 2.64%   |
| Unknown        | 26        | 2.02%   |
| 501-1000       | 22        | 1.71%   |
| 61-70          | 20        | 1.56%   |
| 51-60          | 7         | 0.54%   |
| 91-100         | 7         | 0.54%   |
| 131-140        | 6         | 0.47%   |
| 41-50          | 4         | 0.31%   |
| 111-120        | 4         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 411       | 33.07%  |
| 121-160       | 358       | 28.8%   |
| 101-120       | 315       | 25.34%  |
| 161-240       | 72        | 5.79%   |
| 1-50          | 34        | 2.74%   |
| More than 240 | 27        | 2.17%   |
| Unknown       | 26        | 2.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 839       | 73.08%  |
| 2     | 233       | 20.3%   |
| 0     | 47        | 4.09%   |
| 3     | 27        | 2.35%   |
| 4     | 2         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 620       | 37.6%   |
| Realtek Semiconductor             | 618       | 37.48%  |
| Qualcomm Atheros                  | 185       | 11.22%  |
| Broadcom                          | 75        | 4.55%   |
| Ralink Technology                 | 15        | 0.91%   |
| TP-Link                           | 14        | 0.85%   |
| Broadcom Limited                  | 14        | 0.85%   |
| Marvell Technology Group          | 10        | 0.61%   |
| Nvidia                            | 9         | 0.55%   |
| ASIX Electronics                  | 8         | 0.49%   |
| Microsoft                         | 7         | 0.42%   |
| Dell                              | 7         | 0.42%   |
| Sierra Wireless                   | 4         | 0.24%   |
| Ralink                            | 4         | 0.24%   |
| MEDIATEK                          | 4         | 0.24%   |
| Lenovo                            | 4         | 0.24%   |
| D-Link System                     | 4         | 0.24%   |
| Aquantia                          | 4         | 0.24%   |
| Samsung Electronics               | 3         | 0.18%   |
| Qualcomm Atheros Communications   | 3         | 0.18%   |
| Ericsson Business Mobile Networks | 3         | 0.18%   |
| DisplayLink                       | 3         | 0.18%   |
| Qualcomm                          | 2         | 0.12%   |
| Oculus VR                         | 2         | 0.12%   |
| NetGear                           | 2         | 0.12%   |
| Hewlett-Packard                   | 2         | 0.12%   |
| D-Link                            | 2         | 0.12%   |
| ASUSTek Computer                  | 2         | 0.12%   |
| Xiaomi                            | 1         | 0.06%   |
| Tenda                             | 1         | 0.06%   |
| Solarflare Communications         | 1         | 0.06%   |
| Seeed Technology                  | 1         | 0.06%   |
| Motorola PCS                      | 1         | 0.06%   |
| Motorola                          | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| JMicron Technology                | 1         | 0.06%   |
| InterBiometrics                   | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| Google                            | 1         | 0.06%   |
| Fibocom                           | 1         | 0.06%   |
| Emulex                            | 1         | 0.06%   |
| Edimax Technology                 | 1         | 0.06%   |
| CyberTAN Technology               | 1         | 0.06%   |
| Arduino SA                        | 1         | 0.06%   |
| Apple                             | 1         | 0.06%   |
| 3Com                              | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 471       | 23.56%  |
| Intel Wi-Fi 6 AX200                                               | 90        | 4.5%    |
| Intel I211 Gigabit Network Connection                             | 67        | 3.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 52        | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 52        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46        | 2.3%    |
| Intel Wireless 8265 / 8275                                        | 44        | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32        | 1.6%    |
| Intel Wireless 7260                                               | 31        | 1.55%   |
| Intel Ethernet Connection (2) I219-V                              | 31        | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 29        | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 27        | 1.35%   |
| Intel Wireless 8260                                               | 25        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 1.25%   |
| Intel Wireless-AC 9260                                            | 24        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 23        | 1.15%   |
| Intel Wireless 7265                                               | 21        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 20        | 1%      |
| Intel Wireless 3165                                               | 20        | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 19        | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                    | 15        | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 15        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 13        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.5%    |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 0.5%    |
| Intel Centrino Advanced-N 6200                                    | 10        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.4%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 8         | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 8         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 8         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.4%    |
| Intel Centrino Advanced-N 6235                                    | 8         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 7         | 0.35%   |
| Intel Wireless 3160                                               | 7         | 0.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 0.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 473       | 53.09%  |
| Qualcomm Atheros                | 148       | 16.61%  |
| Realtek Semiconductor           | 137       | 15.38%  |
| Broadcom                        | 57        | 6.4%    |
| Ralink Technology               | 15        | 1.68%   |
| TP-Link                         | 13        | 1.46%   |
| Broadcom Limited                | 9         | 1.01%   |
| Microsoft                       | 7         | 0.79%   |
| Sierra Wireless                 | 4         | 0.45%   |
| Ralink                          | 4         | 0.45%   |
| MEDIATEK                        | 4         | 0.45%   |
| Qualcomm Atheros Communications | 3         | 0.34%   |
| Dell                            | 3         | 0.34%   |
| NetGear                         | 2         | 0.22%   |
| D-Link System                   | 2         | 0.22%   |
| D-Link                          | 2         | 0.22%   |
| ASUSTek Computer                | 2         | 0.22%   |
| Tenda                           | 1         | 0.11%   |
| Marvell Technology Group        | 1         | 0.11%   |
| IMC Networks                    | 1         | 0.11%   |
| Fibocom                         | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| CyberTAN Technology             | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 90        | 10.02%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 52        | 5.79%   |
| Intel Wireless 8265 / 8275                                     | 44        | 4.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 32        | 3.56%   |
| Intel Wireless 7260                                            | 31        | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 27        | 3.01%   |
| Intel Wireless 8260                                            | 25        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 2.78%   |
| Intel Wireless-AC 9260                                         | 24        | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 23        | 2.56%   |
| Intel Wireless 7265                                            | 21        | 2.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 20        | 2.23%   |
| Intel Wireless 3165                                            | 20        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 16        | 1.78%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 1.78%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 15        | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 1.56%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 11        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.11%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 8         | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 0.89%   |
| Intel Centrino Advanced-N 6235                                 | 8         | 0.89%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7         | 0.78%   |
| Intel Wireless 3160                                            | 7         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 6         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 0.56%   |
| Realtek 802.11ac NIC                                           | 5         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.56%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 5         | 0.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 5         | 0.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 5         | 0.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 5         | 0.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4         | 0.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.45%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 0.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3         | 0.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 0.33%   |
| Microsoft XBOX ACC                                             | 3         | 0.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 578       | 55.05%  |
| Intel                     | 330       | 31.43%  |
| Qualcomm Atheros          | 53        | 5.05%   |
| Broadcom                  | 30        | 2.86%   |
| Nvidia                    | 9         | 0.86%   |
| Marvell Technology Group  | 9         | 0.86%   |
| ASIX Electronics          | 8         | 0.76%   |
| Broadcom Limited          | 5         | 0.48%   |
| Lenovo                    | 4         | 0.38%   |
| Aquantia                  | 4         | 0.38%   |
| Samsung Electronics       | 3         | 0.29%   |
| DisplayLink               | 3         | 0.29%   |
| Qualcomm                  | 2         | 0.19%   |
| D-Link System             | 2         | 0.19%   |
| Xiaomi                    | 1         | 0.1%    |
| TP-Link                   | 1         | 0.1%    |
| Solarflare Communications | 1         | 0.1%    |
| Motorola PCS              | 1         | 0.1%    |
| MediaTek                  | 1         | 0.1%    |
| JMicron Technology        | 1         | 0.1%    |
| ICS Advent                | 1         | 0.1%    |
| Emulex                    | 1         | 0.1%    |
| Apple                     | 1         | 0.1%    |
| 3Com                      | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 471       | 43.45%  |
| Intel I211 Gigabit Network Connection                                          | 67        | 6.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 52        | 4.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 46        | 4.24%   |
| Intel Ethernet Connection (2) I219-V                                           | 31        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                              | 29        | 2.68%   |
| Intel Ethernet Connection I217-LM                                              | 25        | 2.31%   |
| Intel Ethernet Connection (7) I219-V                                           | 19        | 1.75%   |
| Intel Ethernet Controller I225-V                                               | 13        | 1.2%    |
| Intel 82577LM Gigabit Network Connection                                       | 13        | 1.2%    |
| Intel Ethernet Connection X553 1GbE                                            | 10        | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 9         | 0.83%   |
| Intel Ethernet Connection I218-LM                                              | 9         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                           | 9         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 0.74%   |
| Intel Ethernet Connection I217-V                                               | 8         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                          | 8         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 0.74%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                          | 7         | 0.65%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 6         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 6         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.46%   |
| Nvidia MCP79 Ethernet                                                          | 5         | 0.46%   |
| Intel I210 Gigabit Network Connection                                          | 5         | 0.46%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 5         | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 4         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                                          | 4         | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 3         | 0.28%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.28%   |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 0.28%   |
| Intel 82576 Gigabit Network Connection                                         | 3         | 0.28%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 0.28%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.28%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 3         | 0.28%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.18%   |
| Qualcomm Mi A1                                                                 | 2         | 0.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.18%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.18%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.18%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.18%   |
| Intel Ethernet controller                                                      | 2         | 0.18%   |
| Intel Ethernet Connection (5) I219-V                                           | 2         | 0.18%   |
| Intel Ethernet Connection (12) I219-V                                          | 2         | 0.18%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.18%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 998       | 53.26%  |
| WiFi     | 859       | 45.84%  |
| Modem    | 17        | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 660       | 52.26%  |
| Ethernet | 603       | 47.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 639       | 56.3%   |
| 1     | 440       | 38.77%  |
| 3     | 36        | 3.17%   |
| 4     | 15        | 1.32%   |
| 0     | 4         | 0.35%   |
| 9     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 914       | 79.62%  |
| Yes  | 234       | 20.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 387       | 50.52%  |
| Realtek Semiconductor           | 77        | 10.05%  |
| Qualcomm Atheros Communications | 64        | 8.36%   |
| Cambridge Silicon Radio         | 48        | 6.27%   |
| Broadcom                        | 36        | 4.7%    |
| Apple                           | 33        | 4.31%   |
| IMC Networks                    | 29        | 3.79%   |
| Lite-On Technology              | 27        | 3.52%   |
| ASUSTek Computer                | 21        | 2.74%   |
| Foxconn / Hon Hai               | 15        | 1.96%   |
| Dell                            | 9         | 1.17%   |
| Toshiba                         | 3         | 0.39%   |
| Dynex                           | 3         | 0.39%   |
| Belkin Components               | 3         | 0.39%   |
| Realtek                         | 2         | 0.26%   |
| Hewlett-Packard                 | 2         | 0.26%   |
| Edimax Technology               | 2         | 0.26%   |
| Ralink Technology               | 1         | 0.13%   |
| Ralink                          | 1         | 0.13%   |
| Marvell Semiconductor           | 1         | 0.13%   |
| HTC (High Tech Computer)        | 1         | 0.13%   |
| Chicony Electronics             | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 143       | 18.64%  |
| Intel AX200 Bluetooth                                                               | 87        | 11.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 53        | 6.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 48        | 6.26%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 47        | 6.13%   |
| Intel Bluetooth Device                                                              | 44        | 5.74%   |
| Realtek Bluetooth Radio                                                             | 41        | 5.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 24        | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 23        | 3%      |
| Lite-On Bluetooth Device                                                            | 23        | 3%      |
| Intel Wireless-AC 3168 Bluetooth                                                    | 19        | 2.48%   |
| Apple Bluetooth USB Host Controller                                                 | 19        | 2.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.69%   |
| IMC Networks Bluetooth Device                                                       | 11        | 1.43%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 9         | 1.17%   |
| Apple Bluetooth Host Controller                                                     | 9         | 1.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 8         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 5         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.52%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.52%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 0.39%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.39%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 3         | 0.39%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.39%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 3         | 0.39%   |
| ASUS ASUS USB-BT500                                                                 | 3         | 0.39%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.26%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.26%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.26%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.26%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.26%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.26%   |
| IMC Networks BCM20702A0                                                             | 2         | 0.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.26%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.26%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.26%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.26%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.26%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.26%   |
| Edimax Bluetooth Adapter                                                            | 2         | 0.26%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.26%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.26%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 2         | 0.26%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 2         | 0.26%   |
| ASUS Bluetooth Adapter                                                              | 2         | 0.26%   |
| ASUS BCM20702A0                                                                     | 2         | 0.26%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.13%   |
| Realtek CSR BS8510                                                                  | 1         | 0.13%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.13%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.13%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.13%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 768       | 43.37%  |
| AMD                                  | 392       | 22.13%  |
| Nvidia                               | 369       | 20.84%  |
| C-Media Electronics                  | 38        | 2.15%   |
| Logitech                             | 25        | 1.41%   |
| Kingston Technology                  | 14        | 0.79%   |
| Texas Instruments                    | 11        | 0.62%   |
| JMTek                                | 11        | 0.62%   |
| Focusrite-Novation                   | 11        | 0.62%   |
| Corsair                              | 9         | 0.51%   |
| Creative Technology                  | 8         | 0.45%   |
| Realtek Semiconductor                | 7         | 0.4%    |
| Creative Labs                        | 6         | 0.34%   |
| SteelSeries ApS                      | 5         | 0.28%   |
| Sennheiser Communications            | 5         | 0.28%   |
| RODE Microphones                     | 5         | 0.28%   |
| Blue Microphones                     | 5         | 0.28%   |
| SAVITECH                             | 4         | 0.23%   |
| Razer USA                            | 4         | 0.23%   |
| GN Netcom                            | 4         | 0.23%   |
| Generalplus Technology               | 4         | 0.23%   |
| BEHRINGER International              | 4         | 0.23%   |
| Yamaha                               | 3         | 0.17%   |
| VIA Technologies                     | 3         | 0.17%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.17%   |
| Samson Technologies                  | 3         | 0.17%   |
| Lenovo                               | 3         | 0.17%   |
| Sony                                 | 2         | 0.11%   |
| PreSonus Audio Electronics           | 2         | 0.11%   |
| Native Instruments                   | 2         | 0.11%   |
| Mark of the Unicorn                  | 2         | 0.11%   |
| FIFINE Microphones                   | 2         | 0.11%   |
| Dell                                 | 2         | 0.11%   |
| Cambridge Silicon Radio              | 2         | 0.11%   |
| Asahi Kasei Microsystems             | 2         | 0.11%   |
| XMOS                                 | 1         | 0.06%   |
| USB-MIC                              | 1         | 0.06%   |
| Unknown                              | 1         | 0.06%   |
| Trust                                | 1         | 0.06%   |
| Tdlasunnic                           | 1         | 0.06%   |
| Samsung Electronics                  | 1         | 0.06%   |
| RadioShack (Tandy)                   | 1         | 0.06%   |
| Project                              | 1         | 0.06%   |
| Plantronics                          | 1         | 0.06%   |
| Philips (or NXP)                     | 1         | 0.06%   |
| No brand                             | 1         | 0.06%   |
| Microfone Condensador Avalanche      | 1         | 0.06%   |
| Medeli Electronics                   | 1         | 0.06%   |
| M-Audio                              | 1         | 0.06%   |
| LG Electronics                       | 1         | 0.06%   |
| Lautsprecher Teufel                  | 1         | 0.06%   |
| Harman                               | 1         | 0.06%   |
| GYROCOM C&C                          | 1         | 0.06%   |
| Giga-Byte Technology                 | 1         | 0.06%   |
| DigiTech                             | 1         | 0.06%   |
| DCMT Technology                      | 1         | 0.06%   |
| Cooler Master                        | 1         | 0.06%   |
| Barco Display Systems                | 1         | 0.06%   |
| Bang Olufsen                         | 1         | 0.06%   |
| AudioQuest                           | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 116       | 5.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 114       | 5.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 98        | 4.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 76        | 3.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 72        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 71        | 3.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 65        | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 2.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45        | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 44        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43        | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 40        | 1.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 37        | 1.79%   |
| Intel 200 Series PCH HD Audio                                              | 37        | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34        | 1.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 31        | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                              | 30        | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 28        | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 23        | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 23        | 1.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 22        | 1.06%   |
| Intel CM238 HD Audio Controller                                            | 22        | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 21        | 1.02%   |
| Intel Broadwell-U Audio Controller                                         | 21        | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 21        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.92%   |
| AMD FCH Azalia Controller                                                  | 18        | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17        | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                         | 17        | 0.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                           | 15        | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 15        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 15        | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 15        | 0.73%   |
| AMD Navi 10 HDMI Audio                                                     | 15        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 15        | 0.73%   |
| Nvidia Audio device                                                        | 14        | 0.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14        | 0.68%   |
| Nvidia GP102 HDMI Audio Controller                                         | 13        | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 13        | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                              | 12        | 0.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 0.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 11        | 0.53%   |
| AMD High Definition Audio Controller                                       | 11        | 0.53%   |
| Kingston Technology HyperX 7.1 Audio                                       | 10        | 0.48%   |
| JMTek USB PnP Audio Device                                                 | 10        | 0.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 0.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 9         | 0.44%   |
| Nvidia GK106 HDMI Audio Controller                                         | 8         | 0.39%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8         | 0.39%   |
| Nvidia GA102 High Definition Audio Controller                              | 8         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 254       | 21.15%  |
| SK Hynix            | 199       | 16.57%  |
| Kingston            | 123       | 10.24%  |
| Corsair             | 123       | 10.24%  |
| Micron Technology   | 99        | 8.24%   |
| Crucial             | 94        | 7.83%   |
| Unknown             | 73        | 6.08%   |
| G.Skill             | 68        | 5.66%   |
| A-DATA Technology   | 25        | 2.08%   |
| Team                | 18        | 1.5%    |
| Ramaxel Technology  | 17        | 1.42%   |
| Nanya Technology    | 17        | 1.42%   |
| Elpida              | 15        | 1.25%   |
| Patriot             | 12        | 1%      |
| Unknown             | 6         | 0.5%    |
| Unknown (ABCD)      | 5         | 0.42%   |
| Avant               | 5         | 0.42%   |
| Transcend           | 4         | 0.33%   |
| Silicon Power       | 4         | 0.33%   |
| Goldkey             | 4         | 0.33%   |
| Apacer              | 4         | 0.33%   |
| ASint Technology    | 3         | 0.25%   |
| PNY                 | 2         | 0.17%   |
| Neo Forza           | 2         | 0.17%   |
| Kingmax             | 2         | 0.17%   |
| GOODRAM             | 2         | 0.17%   |
| GEIL                | 2         | 0.17%   |
| Unknown (898F)      | 1         | 0.08%   |
| Unknown (0x8634)    | 1         | 0.08%   |
| Unknown (0x8319)    | 1         | 0.08%   |
| Unknown (09D5)      | 1         | 0.08%   |
| Unifosa             | 1         | 0.08%   |
| Smart               | 1         | 0.08%   |
| Sesame              | 1         | 0.08%   |
| Saikano             | 1         | 0.08%   |
| S                   | 1         | 0.08%   |
| Lexar Co Limited    | 1         | 0.08%   |
| Lexar               | 1         | 0.08%   |
| HPE                 | 1         | 0.08%   |
| EVGA                | 1         | 0.08%   |
| EUDAR               | 1         | 0.08%   |
| DSL                 | 1         | 0.08%   |
| CSX                 | 1         | 0.08%   |
| atermiter           | 1         | 0.08%   |
| AMD                 | 1         | 0.08%   |
| 48spaces            | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 17        | 1.31%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 16        | 1.24%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 15        | 1.16%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 12        | 0.93%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 11        | 0.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 11        | 0.85%   |
| SK Hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s        | 10        | 0.77%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 10        | 0.77%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s        | 10        | 0.77%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 9         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 9         | 0.7%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 8         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 8         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s     | 8         | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 8         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s      | 8         | 0.62%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 0.54%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 7         | 0.54%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 7         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 7         | 0.54%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 6         | 0.46%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 6         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 6         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 6         | 0.46%   |
| Unknown                                                      | 6         | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 5         | 0.39%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 0.39%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 5         | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 5         | 0.39%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 5         | 0.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 5         | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 5         | 0.39%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 5         | 0.39%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s        | 5         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 4         | 0.31%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 4         | 0.31%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 4         | 0.31%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 4         | 0.31%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 4         | 0.31%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 4         | 0.31%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 4         | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 4         | 0.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 4         | 0.31%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 0.31%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.31%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 4         | 0.31%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 4         | 0.31%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s         | 4         | 0.31%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 4         | 0.31%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s       | 4         | 0.31%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 4         | 0.31%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s        | 4         | 0.31%   |
| Corsair RAM CMW32GX4M2C3200C16 16384MB DIMM DDR4 3200MT/s    | 4         | 0.31%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s          | 4         | 0.31%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 3         | 0.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 3         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 590       | 57.73%  |
| DDR3    | 329       | 32.19%  |
| LPDDR3  | 30        | 2.94%   |
| Unknown | 22        | 2.15%   |
| LPDDR4  | 20        | 1.96%   |
| SDRAM   | 14        | 1.37%   |
| DDR2    | 14        | 1.37%   |
| DDR     | 3         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 536       | 52.55%  |
| DIMM         | 426       | 41.76%  |
| Row Of Chips | 51        | 5%      |
| Chip         | 7         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 480       | 43.36%  |
| 4096  | 322       | 29.09%  |
| 16384 | 179       | 16.17%  |
| 2048  | 87        | 7.86%   |
| 32768 | 28        | 2.53%   |
| 1024  | 9         | 0.81%   |
| 64    | 1         | 0.09%   |
| 16    | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 234       | 20.49%  |
| 2667    | 194       | 16.99%  |
| 3200    | 168       | 14.71%  |
| 2400    | 117       | 10.25%  |
| 1333    | 65        | 5.69%   |
| 2133    | 55        | 4.82%   |
| 3600    | 45        | 3.94%   |
| 1334    | 29        | 2.54%   |
| 1867    | 24        | 2.1%    |
| 3466    | 21        | 1.84%   |
| 3266    | 18        | 1.58%   |
| 1067    | 17        | 1.49%   |
| 3000    | 14        | 1.23%   |
| 3733    | 12        | 1.05%   |
| 2933    | 12        | 1.05%   |
| 800     | 12        | 1.05%   |
| 667     | 11        | 0.96%   |
| 2666    | 10        | 0.88%   |
| Unknown | 10        | 0.88%   |
| 4267    | 7         | 0.61%   |
| 2800    | 7         | 0.61%   |
| 3400    | 5         | 0.44%   |
| 4199    | 4         | 0.35%   |
| 3800    | 4         | 0.35%   |
| 1800    | 4         | 0.35%   |
| 1866    | 3         | 0.26%   |
| 1066    | 3         | 0.26%   |
| 975     | 3         | 0.26%   |
| 4266    | 2         | 0.18%   |
| 3866    | 2         | 0.18%   |
| 3533    | 2         | 0.18%   |
| 3334    | 2         | 0.18%   |
| 3333    | 2         | 0.18%   |
| 3067    | 2         | 0.18%   |
| 2934    | 2         | 0.18%   |
| 2465    | 2         | 0.18%   |
| 2200    | 2         | 0.18%   |
| 2048    | 2         | 0.18%   |
| 533     | 2         | 0.18%   |
| 52217   | 1         | 0.09%   |
| 8400    | 1         | 0.09%   |
| 4333    | 1         | 0.09%   |
| 3151    | 1         | 0.09%   |
| 3100    | 1         | 0.09%   |
| 3007    | 1         | 0.09%   |
| 2733    | 1         | 0.09%   |
| 2197    | 1         | 0.09%   |
| 2000    | 1         | 0.09%   |
| 1776    | 1         | 0.09%   |
| 1639    | 1         | 0.09%   |
| 333     | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 38.71%  |
| Brother Industries  | 12        | 38.71%  |
| Seiko Epson         | 2         | 6.45%   |
| Canon               | 2         | 6.45%   |
| Samsung Electronics | 1         | 3.23%   |
| MIIIW               | 1         | 3.23%   |
| Dymo-CoStar         | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson ET-4700 Series             | 2         | 6.45%   |
| HP DeskJet 2620 All-in-One Printer     | 2         | 6.45%   |
| Brother Printer                        | 2         | 6.45%   |
| Brother DCP-7055 scanner/printer       | 2         | 6.45%   |
| Samsung SCX-3400 Series                | 1         | 3.23%   |
| MIIIW MW Keyboard Air Mini             | 1         | 3.23%   |
| HP OfficeJet Pro 6960                  | 1         | 3.23%   |
| HP OfficeJet 5200 series               | 1         | 3.23%   |
| HP OfficeJet 4650 series               | 1         | 3.23%   |
| HP LaserJet Professional P1102w        | 1         | 3.23%   |
| HP LaserJet P1005                      | 1         | 3.23%   |
| HP LaserJet M203-M206                  | 1         | 3.23%   |
| HP ENVY 4500 series                    | 1         | 3.23%   |
| HP Deskjet 4640 series                 | 1         | 3.23%   |
| HP DeskJet 2700 series                 | 1         | 3.23%   |
| HP Deskjet 1050 J410                   | 1         | 3.23%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 3.23%   |
| Canon PIXMA MG3600 Series              | 1         | 3.23%   |
| Canon CanoScan LiDE 300                | 1         | 3.23%   |
| Brother MFC-L3770CDW                   | 1         | 3.23%   |
| Brother MFC-L3750CDW                   | 1         | 3.23%   |
| Brother MFC-J6545DW                    | 1         | 3.23%   |
| Brother MFC-J497DW                     | 1         | 3.23%   |
| Brother MFC-J485DW                     | 1         | 3.23%   |
| Brother MFC-J450DW                     | 1         | 3.23%   |
| Brother HL-3140CW series               | 1         | 3.23%   |
| Brother DCP-1610W                      | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 33.33%  |
| HP ScanJet 2200c                                        | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 159       | 22.62%  |
| IMC Networks                           | 73        | 10.38%  |
| Logitech                               | 63        | 8.96%   |
| Acer                                   | 61        | 8.68%   |
| Realtek Semiconductor                  | 57        | 8.11%   |
| Microdia                               | 52        | 7.4%    |
| Sunplus Innovation Technology          | 34        | 4.84%   |
| Apple                                  | 28        | 3.98%   |
| Quanta                                 | 25        | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.27%   |
| Syntek                                 | 18        | 2.56%   |
| Lite-On Technology                     | 13        | 1.85%   |
| Suyin                                  | 11        | 1.56%   |
| Lenovo                                 | 10        | 1.42%   |
| Microsoft                              | 8         | 1.14%   |
| Silicon Motion                         | 7         | 1%      |
| Samsung Electronics                    | 5         | 0.71%   |
| Primax Electronics                     | 5         | 0.71%   |
| KYE Systems (Mouse Systems)            | 4         | 0.57%   |
| Hewlett-Packard                        | 4         | 0.57%   |
| Generalplus Technology                 | 4         | 0.57%   |
| Creative Technology                    | 4         | 0.57%   |
| Razer USA                              | 3         | 0.43%   |
| Luxvisions Innotech Limited            | 3         | 0.43%   |
| GEMBIRD                                | 3         | 0.43%   |
| Alcor Micro                            | 3         | 0.43%   |
| Sunplus Technology                     | 2         | 0.28%   |
| Ruision                                | 2         | 0.28%   |
| Importek                               | 2         | 0.28%   |
| ARC International                      | 2         | 0.28%   |
| Z-Star Microelectronics                | 1         | 0.14%   |
| WaveRider Communications               | 1         | 0.14%   |
| Unknown                                | 1         | 0.14%   |
| Sonix Technology                       | 1         | 0.14%   |
| Ricoh                                  | 1         | 0.14%   |
| OmniVision Technologies                | 1         | 0.14%   |
| Mimaki Engineering                     | 1         | 0.14%   |
| MacroSilicon                           | 1         | 0.14%   |
| Jeilin Technology                      | 1         | 0.14%   |
| Huawei Technologies                    | 1         | 0.14%   |
| Google                                 | 1         | 0.14%   |
| Aveo Technology                        | 1         | 0.14%   |
| Arkmicro Technologies                  | 1         | 0.14%   |
| ANYKA                                  | 1         | 0.14%   |
| Anker                                  | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 47        | 6.64%   |
| Realtek Integrated_Webcam_HD                     | 24        | 3.39%   |
| Microdia Integrated_Webcam_HD                    | 22        | 3.11%   |
| Acer Integrated Camera                           | 21        | 2.97%   |
| IMC Networks Integrated Camera                   | 19        | 2.68%   |
| Logitech HD Pro Webcam C920                      | 17        | 2.4%    |
| Chicony HD WebCam                                | 17        | 2.4%    |
| Logitech Webcam C270                             | 15        | 2.12%   |
| IMC Networks USB2.0 HD UVC WebCam                | 15        | 2.12%   |
| Syntek Integrated Camera                         | 12        | 1.69%   |
| Sunplus Integrated_Webcam_HD                     | 11        | 1.55%   |
| Lite-On Integrated Camera                        | 10        | 1.41%   |
| Chicony USB2.0 Camera                            | 10        | 1.41%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 9         | 1.27%   |
| Acer EasyCamera                                  | 9         | 1.27%   |
| Microdia Integrated Webcam                       | 8         | 1.13%   |
| Chicony HP Truevision HD                         | 8         | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE                        | 8         | 1.13%   |
| Apple Built-in iSight                            | 8         | 1.13%   |
| Quanta HD WebCam                                 | 7         | 0.99%   |
| Logitech C922 Pro Stream Webcam                  | 6         | 0.85%   |
| Lenovo Integrated Webcam [R5U877]                | 6         | 0.85%   |
| IMC Networks Lenovo EasyCamera                   | 6         | 0.85%   |
| Chicony EasyCamera                               | 6         | 0.85%   |
| Apple FaceTime HD Camera (Built-in)              | 6         | 0.85%   |
| Acer BisonCam,NB Pro                             | 6         | 0.85%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 0.71%   |
| Quanta HD User Facing                            | 5         | 0.71%   |
| Microsoft LifeCam HD-3000                        | 5         | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                    | 5         | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                  | 5         | 0.71%   |
| Chicony Integrated Camera (1280x720@30)          | 5         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 5         | 0.71%   |
| Apple FaceTime HD Camera                         | 5         | 0.71%   |
| Acer SunplusIT Integrated Camera                 | 5         | 0.71%   |
| Realtek USB2.0 VGA UVC WebCam                    | 4         | 0.56%   |
| Microdia Laptop_Integrated_Webcam_HD             | 4         | 0.56%   |
| Logitech Webcam C310                             | 4         | 0.56%   |
| IMC Networks VGA UVC WebCam                      | 4         | 0.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 4         | 0.56%   |
| Chicony HP Wide Vision HD Camera                 | 4         | 0.56%   |
| Chicony HP TrueVision HD Camera                  | 4         | 0.56%   |
| Chicony HP HD Webcam                             | 4         | 0.56%   |
| Chicony HP HD Camera                             | 4         | 0.56%   |
| Chicony FJ Camera                                | 4         | 0.56%   |
| Acer Lenovo EasyCamera                           | 4         | 0.56%   |
| Acer HD Webcam                                   | 4         | 0.56%   |
| Acer BisonCam, NB Pro                            | 4         | 0.56%   |
| Syntek EasyCamera                                | 3         | 0.42%   |
| Suyin HP TrueVision HD                           | 3         | 0.42%   |
| Sunplus Laptop Integrated Webcam HD              | 3         | 0.42%   |
| Sunplus HD WebCam                                | 3         | 0.42%   |
| Silicon Motion WebCam SC-13HDL11939N             | 3         | 0.42%   |
| Realtek Integrated Webcam_HD                     | 3         | 0.42%   |
| Realtek Integrated Webcam HD                     | 3         | 0.42%   |
| Realtek Integrated Webcam                        | 3         | 0.42%   |
| Realtek HD WebCam                                | 3         | 0.42%   |
| Razer USA Gaming Webcam [Kiyo]                   | 3         | 0.42%   |
| Quanta HP TrueVision HD Camera                   | 3         | 0.42%   |
| Primax HP HD Webcam [Fixed]                      | 3         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 51        | 41.13%  |
| Synaptics                  | 27        | 21.77%  |
| Shenzhen Goodix Technology | 22        | 17.74%  |
| Upek                       | 8         | 6.45%   |
| LighTuning Technology      | 6         | 4.84%   |
| Elan Microelectronics      | 5         | 4.03%   |
| AuthenTec                  | 4         | 3.23%   |
| STMicroelectronics         | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 12.1%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 6.45%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 6.45%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 5.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 5.65%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 5.65%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.03%   |
| Synaptics  WBDI                                                            | 5         | 4.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 4.03%   |
| Unknown                                                                    | 5         | 4.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.23%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.61%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.61%   |
| Synaptics WBDI Device                                                      | 2         | 1.61%   |
| Validity Sensors VFS491                                                    | 1         | 0.81%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.81%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.81%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.81%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.81%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.81%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.81%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.81%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.81%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.81%   |
| AuthenTec AES1600                                                          | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 39.66%  |
| Alcor Micro           | 20        | 34.48%  |
| O2 Micro              | 4         | 6.9%    |
| Lenovo                | 4         | 6.9%    |
| Upek                  | 2         | 3.45%   |
| Gemalto (was Gemplus) | 2         | 3.45%   |
| Yubico.com            | 1         | 1.72%   |
| SCM Microsystems      | 1         | 1.72%   |
| Cherry                | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 34.48%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 10.34%  |
| Broadcom 5880                                                                | 5         | 8.62%   |
| Broadcom 58200                                                               | 5         | 8.62%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.9%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 5.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 3.45%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.72%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.72%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.72%   |
| Cherry Smart Card Reader USB                                                 | 1         | 1.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 814       | 70.29%  |
| 1     | 274       | 23.66%  |
| 2     | 65        | 5.61%   |
| 3     | 5         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 123       | 30.37%  |
| Graphics card            | 108       | 26.67%  |
| Chipcard                 | 56        | 13.83%  |
| Net/wireless             | 44        | 10.86%  |
| Multimedia controller    | 20        | 4.94%   |
| Camera                   | 16        | 3.95%   |
| Communication controller | 12        | 2.96%   |
| Unassigned class         | 7         | 1.73%   |
| Bluetooth                | 5         | 1.23%   |
| Network                  | 3         | 0.74%   |
| Card reader              | 3         | 0.74%   |
| Net/ethernet             | 2         | 0.49%   |
| Modem                    | 2         | 0.49%   |
| Dvb card                 | 2         | 0.49%   |
| Storage/nvme             | 1         | 0.25%   |
| Storage                  | 1         | 0.25%   |

