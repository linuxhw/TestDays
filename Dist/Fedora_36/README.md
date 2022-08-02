Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

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

Total: 1280

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | H81M-E34                    | Desktop     | [c0be356e96](https://linux-hardware.org/?probe=c0be356e96) | Aug 01, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3a496f366f](https://linux-hardware.org/?probe=3a496f366f) | Aug 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| Dell          | Latitude D620               | Notebook    | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [827883d38c](https://linux-hardware.org/?probe=827883d38c) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [7a0035ad18](https://linux-hardware.org/?probe=7a0035ad18) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d8bfe4a00b](https://linux-hardware.org/?probe=d8bfe4a00b) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0f72d43717](https://linux-hardware.org/?probe=0f72d43717) | Jul 31, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6699e8b6ea](https://linux-hardware.org/?probe=6699e8b6ea) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [f43e0c2c81](https://linux-hardware.org/?probe=f43e0c2c81) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [85208906cd](https://linux-hardware.org/?probe=85208906cd) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [ec939adba9](https://linux-hardware.org/?probe=ec939adba9) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81MD     | Tablet      | [d21006410b](https://linux-hardware.org/?probe=d21006410b) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | M4A77TD                     | Desktop     | [f10ef09086](https://linux-hardware.org/?probe=f10ef09086) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ebe9fe3b1a](https://linux-hardware.org/?probe=ebe9fe3b1a) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [cd5aa49da7](https://linux-hardware.org/?probe=cd5aa49da7) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | Notebook    | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [e4dfdaf9a0](https://linux-hardware.org/?probe=e4dfdaf9a0) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [25d688e258](https://linux-hardware.org/?probe=25d688e258) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [93caf82d7a](https://linux-hardware.org/?probe=93caf82d7a) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [87d143ab3d](https://linux-hardware.org/?probe=87d143ab3d) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | Notebook    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [256172b01e](https://linux-hardware.org/?probe=256172b01e) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| HP            | 348 G4                      | Notebook    | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [ba8e73bd09](https://linux-hardware.org/?probe=ba8e73bd09) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [066e5eb95d](https://linux-hardware.org/?probe=066e5eb95d) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [af4d396115](https://linux-hardware.org/?probe=af4d396115) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| HP            | 1494                        | Desktop     | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [2816cacd1b](https://linux-hardware.org/?probe=2816cacd1b) | Jul 27, 2022 |
| Clevo         | M570TU                      | Notebook    | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [2773e9510b](https://linux-hardware.org/?probe=2773e9510b) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [015e810904](https://linux-hardware.org/?probe=015e810904) | Jul 26, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d63a6f2607](https://linux-hardware.org/?probe=d63a6f2607) | Jul 26, 2022 |
| HP            | Notebook                    | Notebook    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| ASRock        | Z690 PG Riptide             | Desktop     | [87c499b088](https://linux-hardware.org/?probe=87c499b088) | Jul 26, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [4a49386ad2](https://linux-hardware.org/?probe=4a49386ad2) | Jul 26, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [8194e1dc19](https://linux-hardware.org/?probe=8194e1dc19) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| Dell          | Latitude 7320               | Notebook    | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [a3eeaecb07](https://linux-hardware.org/?probe=a3eeaecb07) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [0675bbd9d0](https://linux-hardware.org/?probe=0675bbd9d0) | Jul 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [24fec424ff](https://linux-hardware.org/?probe=24fec424ff) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [6a75ac249a](https://linux-hardware.org/?probe=6a75ac249a) | Jul 24, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [85e3fee140](https://linux-hardware.org/?probe=85e3fee140) | Jul 24, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | Notebook    | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2ae14bcbc1](https://linux-hardware.org/?probe=2ae14bcbc1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [9c0899916c](https://linux-hardware.org/?probe=9c0899916c) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [88c35211e1](https://linux-hardware.org/?probe=88c35211e1) | Jul 23, 2022 |
| Lenovo        | 3702 SDK0J40700 WIN 3258... | All in one  | [95af4e4f8e](https://linux-hardware.org/?probe=95af4e4f8e) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | Notebook    | [6a1cb48f15](https://linux-hardware.org/?probe=6a1cb48f15) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [6889befce9](https://linux-hardware.org/?probe=6889befce9) | Jul 23, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Lenovo        | 81FV                        | Notebook    | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f2eb36554b](https://linux-hardware.org/?probe=f2eb36554b) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | Desktop     | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | Notebook    | [55f1eaa96c](https://linux-hardware.org/?probe=55f1eaa96c) | Jul 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | Notebook    | [090cc78b83](https://linux-hardware.org/?probe=090cc78b83) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [6bf181ed49](https://linux-hardware.org/?probe=6bf181ed49) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| Acer          | Aspire V3-572               | Notebook    | [5938905628](https://linux-hardware.org/?probe=5938905628) | Jul 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [946035188a](https://linux-hardware.org/?probe=946035188a) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| HP            | 240 G4                      | Notebook    | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [41dbccf7d9](https://linux-hardware.org/?probe=41dbccf7d9) | Jul 21, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | Notebook    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [afa7d8ba6c](https://linux-hardware.org/?probe=afa7d8ba6c) | Jul 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [46fa52e67a](https://linux-hardware.org/?probe=46fa52e67a) | Jul 21, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [a34ee52169](https://linux-hardware.org/?probe=a34ee52169) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c763e49e7e](https://linux-hardware.org/?probe=c763e49e7e) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | Notebook    | [ea200c839f](https://linux-hardware.org/?probe=ea200c839f) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4cde663cf9](https://linux-hardware.org/?probe=4cde663cf9) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | Notebook    | [effe49f996](https://linux-hardware.org/?probe=effe49f996) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | Notebook    | [8d18b6813f](https://linux-hardware.org/?probe=8d18b6813f) | Jul 20, 2022 |
| NCR           | Pocono BIOS.6.0             | Desktop     | [3026f24fe3](https://linux-hardware.org/?probe=3026f24fe3) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [190936df71](https://linux-hardware.org/?probe=190936df71) | Jul 19, 2022 |
| Dell          | G3 3590                     | Notebook    | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [944ba71eef](https://linux-hardware.org/?probe=944ba71eef) | Jul 19, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | Notebook                    | Notebook    | [79c0f60f74](https://linux-hardware.org/?probe=79c0f60f74) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [5d7f42f3f9](https://linux-hardware.org/?probe=5d7f42f3f9) | Jul 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [2c43b01e55](https://linux-hardware.org/?probe=2c43b01e55) | Jul 18, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a66cad27e9](https://linux-hardware.org/?probe=a66cad27e9) | Jul 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [709a460528](https://linux-hardware.org/?probe=709a460528) | Jul 18, 2022 |
| ASUSTek       | M11BB                       | Desktop     | [582292657c](https://linux-hardware.org/?probe=582292657c) | Jul 18, 2022 |
| MSI           | MS-B090                     | All in one  | [b5df4140d1](https://linux-hardware.org/?probe=b5df4140d1) | Jul 18, 2022 |
| MSI           | MS-14Y1                     | Notebook    | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Google        | Kohaku                      | Notebook    | [2f21de3ff6](https://linux-hardware.org/?probe=2f21de3ff6) | Jul 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [e52633f694](https://linux-hardware.org/?probe=e52633f694) | Jul 17, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [39fd39c3b0](https://linux-hardware.org/?probe=39fd39c3b0) | Jul 17, 2022 |
| Pegatron      | D15K                        | Notebook    | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [a3a42d9ae3](https://linux-hardware.org/?probe=a3a42d9ae3) | Jul 17, 2022 |
| Framework     | Laptop                      | Notebook    | [84d20eb09a](https://linux-hardware.org/?probe=84d20eb09a) | Jul 17, 2022 |
| Framework     | Laptop                      | Notebook    | [0489cc39db](https://linux-hardware.org/?probe=0489cc39db) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [aae1bec902](https://linux-hardware.org/?probe=aae1bec902) | Jul 17, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [7518095b97](https://linux-hardware.org/?probe=7518095b97) | Jul 17, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [df94c841af](https://linux-hardware.org/?probe=df94c841af) | Jul 17, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [1d4583cea8](https://linux-hardware.org/?probe=1d4583cea8) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [502c19838a](https://linux-hardware.org/?probe=502c19838a) | Jul 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Huanan        | B75                         | Desktop     | [0580a5a948](https://linux-hardware.org/?probe=0580a5a948) | Jul 17, 2022 |
| Huanan        | B75                         | Desktop     | [e1788853ec](https://linux-hardware.org/?probe=e1788853ec) | Jul 17, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [3caa5cc13d](https://linux-hardware.org/?probe=3caa5cc13d) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [326c97ba50](https://linux-hardware.org/?probe=326c97ba50) | Jul 16, 2022 |
| Dell          | Latitude E5440              | Notebook    | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Dell          | Inspiron 5482               | Convertible | [5d4f4ba0de](https://linux-hardware.org/?probe=5d4f4ba0de) | Jul 16, 2022 |
| HP            | 250 G5                      | Notebook    | [979d1aea6f](https://linux-hardware.org/?probe=979d1aea6f) | Jul 16, 2022 |
| Dell          | Inspiron 5482               | Convertible | [aab7583472](https://linux-hardware.org/?probe=aab7583472) | Jul 16, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [3ac265beda](https://linux-hardware.org/?probe=3ac265beda) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| Alienware     | x17 R1                      | Notebook    | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c72b02d7d4](https://linux-hardware.org/?probe=c72b02d7d4) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d60e6afc41](https://linux-hardware.org/?probe=d60e6afc41) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| System76      | Bonobo Extreme              | Notebook    | [6c7f545300](https://linux-hardware.org/?probe=6c7f545300) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [41517adf39](https://linux-hardware.org/?probe=41517adf39) | Jul 16, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [eff723b9f2](https://linux-hardware.org/?probe=eff723b9f2) | Jul 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fc316a6331](https://linux-hardware.org/?probe=fc316a6331) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | Notebook    | [48dd04e4c8](https://linux-hardware.org/?probe=48dd04e4c8) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | Notebook    | [3378b0fc15](https://linux-hardware.org/?probe=3378b0fc15) | Jul 16, 2022 |
| Toshiba       | Satellite L505D             | Notebook    | [1d7b1ed7c8](https://linux-hardware.org/?probe=1d7b1ed7c8) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| HP            | 88BF                        | Desktop     | [92b12df551](https://linux-hardware.org/?probe=92b12df551) | Jul 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1338941bd0](https://linux-hardware.org/?probe=1338941bd0) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [7efe67fd9a](https://linux-hardware.org/?probe=7efe67fd9a) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Dell          | G3 3590                     | Notebook    | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [b9476b6cf9](https://linux-hardware.org/?probe=b9476b6cf9) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [e963ba85db](https://linux-hardware.org/?probe=e963ba85db) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [165cdc7df2](https://linux-hardware.org/?probe=165cdc7df2) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea3f033d93](https://linux-hardware.org/?probe=ea3f033d93) | Jul 14, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [7486493ea1](https://linux-hardware.org/?probe=7486493ea1) | Jul 14, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [4355281f8e](https://linux-hardware.org/?probe=4355281f8e) | Jul 13, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [36f96a4ef6](https://linux-hardware.org/?probe=36f96a4ef6) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [fbaf6e2d8f](https://linux-hardware.org/?probe=fbaf6e2d8f) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [33853365fd](https://linux-hardware.org/?probe=33853365fd) | Jul 13, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [98ffa2e8b0](https://linux-hardware.org/?probe=98ffa2e8b0) | Jul 13, 2022 |
| Gigabyte      | AERO 17 KC                  | Notebook    | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | Notebook    | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f91143bc89](https://linux-hardware.org/?probe=f91143bc89) | Jul 13, 2022 |
| GPD           | G1621-02                    | Notebook    | [25da86e752](https://linux-hardware.org/?probe=25da86e752) | Jul 13, 2022 |
| Sony          | SVF1531V8CW                 | Notebook    | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [a687046e06](https://linux-hardware.org/?probe=a687046e06) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c4b25937a7](https://linux-hardware.org/?probe=c4b25937a7) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [de328d9562](https://linux-hardware.org/?probe=de328d9562) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| HP            | 1632                        | Desktop     | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| Lenovo        | ThinkPad T490s 20NYS0LY0... | Notebook    | [882680a962](https://linux-hardware.org/?probe=882680a962) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| HP            | 8768 A                      | Desktop     | [f4afb80e18](https://linux-hardware.org/?probe=f4afb80e18) | Jul 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [cce19df6f9](https://linux-hardware.org/?probe=cce19df6f9) | Jul 12, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [3ec331da1f](https://linux-hardware.org/?probe=3ec331da1f) | Jul 12, 2022 |
| HP            | Sona                        | Notebook    | [504fddb8e9](https://linux-hardware.org/?probe=504fddb8e9) | Jul 12, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [59a92ab345](https://linux-hardware.org/?probe=59a92ab345) | Jul 12, 2022 |
| MSI           | Z370-OC PRO                 | Desktop     | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c69dd8da85](https://linux-hardware.org/?probe=c69dd8da85) | Jul 12, 2022 |
| MSI           | H97M-G43                    | Desktop     | [c8b2844540](https://linux-hardware.org/?probe=c8b2844540) | Jul 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [ea08980c33](https://linux-hardware.org/?probe=ea08980c33) | Jul 11, 2022 |
| VALE          | Notebook Classic C140       | Notebook    | [d6cc520dbe](https://linux-hardware.org/?probe=d6cc520dbe) | Jul 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| HP            | 3646h                       | Desktop     | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| HP            | ProBook 6570b               | Notebook    | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [66e3305634](https://linux-hardware.org/?probe=66e3305634) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| Lenovo        | SHARKBAY 31900059 WIN       | All in one  | [f27df86fda](https://linux-hardware.org/?probe=f27df86fda) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Framework     | Laptop                      | Notebook    | [a13ef2beee](https://linux-hardware.org/?probe=a13ef2beee) | Jul 11, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [b6771bbe08](https://linux-hardware.org/?probe=b6771bbe08) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | Desktop     | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [ccb360e8fe](https://linux-hardware.org/?probe=ccb360e8fe) | Jul 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [314c3aaf0e](https://linux-hardware.org/?probe=314c3aaf0e) | Jul 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [4b10924d6a](https://linux-hardware.org/?probe=4b10924d6a) | Jul 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [d6f1e47bf5](https://linux-hardware.org/?probe=d6f1e47bf5) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | Notebook    | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | Notebook    | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [45e46ac933](https://linux-hardware.org/?probe=45e46ac933) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| Intel         | DH61WW AAG23116-301         | Desktop     | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [8270068517](https://linux-hardware.org/?probe=8270068517) | Jul 09, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [c696783c30](https://linux-hardware.org/?probe=c696783c30) | Jul 09, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [36151ae5c3](https://linux-hardware.org/?probe=36151ae5c3) | Jul 09, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| Dell          | Vostro 3590                 | Notebook    | [7195de93ae](https://linux-hardware.org/?probe=7195de93ae) | Jul 09, 2022 |
| HP            | Laptop 17z-cp000            | Notebook    | [f6f0740c36](https://linux-hardware.org/?probe=f6f0740c36) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [b6c6516360](https://linux-hardware.org/?probe=b6c6516360) | Jul 09, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [6513be6d44](https://linux-hardware.org/?probe=6513be6d44) | Jul 09, 2022 |
| Dell          | Latitude 3400               | Notebook    | [6a36fb9dd9](https://linux-hardware.org/?probe=6a36fb9dd9) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [e72ccdd0c6](https://linux-hardware.org/?probe=e72ccdd0c6) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [37de891a60](https://linux-hardware.org/?probe=37de891a60) | Jul 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [30085f92b1](https://linux-hardware.org/?probe=30085f92b1) | Jul 08, 2022 |
| HP            | 8455                        | Desktop     | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [84f475721b](https://linux-hardware.org/?probe=84f475721b) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [447ba923ac](https://linux-hardware.org/?probe=447ba923ac) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [75f67b342a](https://linux-hardware.org/?probe=75f67b342a) | Jul 08, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [69b6f2bdad](https://linux-hardware.org/?probe=69b6f2bdad) | Jul 08, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3672d4926e](https://linux-hardware.org/?probe=3672d4926e) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [546a26c882](https://linux-hardware.org/?probe=546a26c882) | Jul 07, 2022 |
| HP            | 8455                        | Desktop     | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [e850b43a12](https://linux-hardware.org/?probe=e850b43a12) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [234b2b0ee8](https://linux-hardware.org/?probe=234b2b0ee8) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e1f5b40789](https://linux-hardware.org/?probe=e1f5b40789) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [81b2d3fa4f](https://linux-hardware.org/?probe=81b2d3fa4f) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [342362a5f8](https://linux-hardware.org/?probe=342362a5f8) | Jul 06, 2022 |
| Toshiba       | Satellite L505D             | Notebook    | [cf5fedc6e5](https://linux-hardware.org/?probe=cf5fedc6e5) | Jul 06, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [aeb16eb1eb](https://linux-hardware.org/?probe=aeb16eb1eb) | Jul 06, 2022 |
| Lenovo        | ThinkPad L380 20M5000FUS    | Notebook    | [9c6ab1a171](https://linux-hardware.org/?probe=9c6ab1a171) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [dcbe63005c](https://linux-hardware.org/?probe=dcbe63005c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [8c15268c47](https://linux-hardware.org/?probe=8c15268c47) | Jul 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [a0a2cd9568](https://linux-hardware.org/?probe=a0a2cd9568) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [699e033557](https://linux-hardware.org/?probe=699e033557) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5afb466a35](https://linux-hardware.org/?probe=5afb466a35) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [162080ffcf](https://linux-hardware.org/?probe=162080ffcf) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | Notebook    | [4df173f8f2](https://linux-hardware.org/?probe=4df173f8f2) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | Notebook    | [8dbec85d36](https://linux-hardware.org/?probe=8dbec85d36) | Jul 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [54f8e71da0](https://linux-hardware.org/?probe=54f8e71da0) | Jul 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [0954f0b44c](https://linux-hardware.org/?probe=0954f0b44c) | Jul 06, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [a3c85d395b](https://linux-hardware.org/?probe=a3c85d395b) | Jul 05, 2022 |
| System76      | Oryx Pro                    | Notebook    | [338a8ed5ab](https://linux-hardware.org/?probe=338a8ed5ab) | Jul 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [4826df34b3](https://linux-hardware.org/?probe=4826df34b3) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [2cbcdfe2db](https://linux-hardware.org/?probe=2cbcdfe2db) | Jul 05, 2022 |
| Acer          | Aspire Z3-715               | All in one  | [03c59534f5](https://linux-hardware.org/?probe=03c59534f5) | Jul 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [cea4b92a7d](https://linux-hardware.org/?probe=cea4b92a7d) | Jul 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [0ffa87cfad](https://linux-hardware.org/?probe=0ffa87cfad) | Jul 04, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [7f64f81a29](https://linux-hardware.org/?probe=7f64f81a29) | Jul 04, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f1de99a0da](https://linux-hardware.org/?probe=f1de99a0da) | Jul 04, 2022 |
| HP            | ProBook 645 G3              | Notebook    | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [59a1c1c8b1](https://linux-hardware.org/?probe=59a1c1c8b1) | Jul 04, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a19593fa3e](https://linux-hardware.org/?probe=a19593fa3e) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [9e9a46d8ec](https://linux-hardware.org/?probe=9e9a46d8ec) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [5a6c158296](https://linux-hardware.org/?probe=5a6c158296) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | Notebook    | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | Notebook    | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Notebook                    | Notebook    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [58b8e08cf9](https://linux-hardware.org/?probe=58b8e08cf9) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7f4faab065](https://linux-hardware.org/?probe=7f4faab065) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [24d32e73bd](https://linux-hardware.org/?probe=24d32e73bd) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [d0e94cff94](https://linux-hardware.org/?probe=d0e94cff94) | Jul 03, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [0c8bcdbcb1](https://linux-hardware.org/?probe=0c8bcdbcb1) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | Notebook    | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | Notebook    | [576f59ec1b](https://linux-hardware.org/?probe=576f59ec1b) | Jul 02, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [963029db26](https://linux-hardware.org/?probe=963029db26) | Jul 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2d22d14874](https://linux-hardware.org/?probe=2d22d14874) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | Notebook    | [4d9cb098c8](https://linux-hardware.org/?probe=4d9cb098c8) | Jul 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | Notebook    | [1b45ef7d10](https://linux-hardware.org/?probe=1b45ef7d10) | Jul 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [16413aeb23](https://linux-hardware.org/?probe=16413aeb23) | Jul 01, 2022 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c9d0d64896](https://linux-hardware.org/?probe=c9d0d64896) | Jul 01, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [febb798e92](https://linux-hardware.org/?probe=febb798e92) | Jul 01, 2022 |
| Framework     | Laptop                      | Notebook    | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [e72232ee43](https://linux-hardware.org/?probe=e72232ee43) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [5e80242b43](https://linux-hardware.org/?probe=5e80242b43) | Jun 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [2049536427](https://linux-hardware.org/?probe=2049536427) | Jun 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [9c512247ff](https://linux-hardware.org/?probe=9c512247ff) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [85b8793585](https://linux-hardware.org/?probe=85b8793585) | Jun 29, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ddfd26738](https://linux-hardware.org/?probe=8ddfd26738) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | Notebook    | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Getac         | B300-X                      | Notebook    | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1eed1dcced](https://linux-hardware.org/?probe=1eed1dcced) | Jun 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [392d5c7c12](https://linux-hardware.org/?probe=392d5c7c12) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [43c87260b2](https://linux-hardware.org/?probe=43c87260b2) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Alienware     | 17                          | Notebook    | [715b5b0dce](https://linux-hardware.org/?probe=715b5b0dce) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Dell          | Precision M6800             | Notebook    | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| Dell          | Latitude 5511               | Notebook    | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [4ba4d14a1a](https://linux-hardware.org/?probe=4ba4d14a1a) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Toshiba       | Satellite C855-12R          | Notebook    | [e94a109546](https://linux-hardware.org/?probe=e94a109546) | Jun 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [239e8c86c0](https://linux-hardware.org/?probe=239e8c86c0) | Jun 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [c450ce45a6](https://linux-hardware.org/?probe=c450ce45a6) | Jun 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [5d2f94f859](https://linux-hardware.org/?probe=5d2f94f859) | Jun 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [ba68b99167](https://linux-hardware.org/?probe=ba68b99167) | Jun 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f688527838](https://linux-hardware.org/?probe=f688527838) | Jun 27, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [d2b55252d8](https://linux-hardware.org/?probe=d2b55252d8) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [f20fc8c349](https://linux-hardware.org/?probe=f20fc8c349) | Jun 27, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [de3ca4e422](https://linux-hardware.org/?probe=de3ca4e422) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| Timi          | A35S                        | Notebook    | [606e376264](https://linux-hardware.org/?probe=606e376264) | Jun 26, 2022 |
| Dell          | Latitude 7300               | Notebook    | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f4500ddad](https://linux-hardware.org/?probe=2f4500ddad) | Jun 26, 2022 |
| HP            | 3398                        | Desktop     | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [9a853085ea](https://linux-hardware.org/?probe=9a853085ea) | Jun 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [400eaba39f](https://linux-hardware.org/?probe=400eaba39f) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [519e378380](https://linux-hardware.org/?probe=519e378380) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [5948b56a82](https://linux-hardware.org/?probe=5948b56a82) | Jun 25, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [e8a4e37cc6](https://linux-hardware.org/?probe=e8a4e37cc6) | Jun 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [81a9b9847d](https://linux-hardware.org/?probe=81a9b9847d) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3c48bb18e](https://linux-hardware.org/?probe=c3c48bb18e) | Jun 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [6e62883390](https://linux-hardware.org/?probe=6e62883390) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| HP            | 89D8 SMVB                   | Desktop     | [f92ff0c37f](https://linux-hardware.org/?probe=f92ff0c37f) | Jun 24, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [7c532e5712](https://linux-hardware.org/?probe=7c532e5712) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | Notebook    | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| MSI           | IONA                        | Desktop     | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [2c0b9c6402](https://linux-hardware.org/?probe=2c0b9c6402) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [bb8541d805](https://linux-hardware.org/?probe=bb8541d805) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a4d7f0fbeb](https://linux-hardware.org/?probe=a4d7f0fbeb) | Jun 24, 2022 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Dell          | Precision 5550              | Notebook    | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [5129e4893a](https://linux-hardware.org/?probe=5129e4893a) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [dbfad9b8fe](https://linux-hardware.org/?probe=dbfad9b8fe) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [6f13e0f8a0](https://linux-hardware.org/?probe=6f13e0f8a0) | Jun 23, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [926d4055f7](https://linux-hardware.org/?probe=926d4055f7) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| Medion        | AXA                         | All in one  | [0cbda6d693](https://linux-hardware.org/?probe=0cbda6d693) | Jun 23, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ec1b55ac0](https://linux-hardware.org/?probe=6ec1b55ac0) | Jun 23, 2022 |
| Unknown       | HX90                        | Desktop     | [837e70229a](https://linux-hardware.org/?probe=837e70229a) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9f67f6836e](https://linux-hardware.org/?probe=9f67f6836e) | Jun 23, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [32a4f6d3e0](https://linux-hardware.org/?probe=32a4f6d3e0) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [5dd91493a8](https://linux-hardware.org/?probe=5dd91493a8) | Jun 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 2B05                        | Desktop     | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [45871f6d61](https://linux-hardware.org/?probe=45871f6d61) | Jun 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [f002062377](https://linux-hardware.org/?probe=f002062377) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [58c9da7f20](https://linux-hardware.org/?probe=58c9da7f20) | Jun 22, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f140cafa9f](https://linux-hardware.org/?probe=f140cafa9f) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b60cfda63f](https://linux-hardware.org/?probe=b60cfda63f) | Jun 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | Desktop     | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [e02fbb350d](https://linux-hardware.org/?probe=e02fbb350d) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Acer          | NC-E5-774G-75TJ             | Notebook    | [55fce68116](https://linux-hardware.org/?probe=55fce68116) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [04927da7b6](https://linux-hardware.org/?probe=04927da7b6) | Jun 22, 2022 |
| HP            | ZBook 17 G4                 | Notebook    | [bf03eb0fa7](https://linux-hardware.org/?probe=bf03eb0fa7) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8c621a2c68](https://linux-hardware.org/?probe=8c621a2c68) | Jun 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [ae54449547](https://linux-hardware.org/?probe=ae54449547) | Jun 21, 2022 |
| GEO           | GeoBook 240                 | Notebook    | [f08637137c](https://linux-hardware.org/?probe=f08637137c) | Jun 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R5CT... | Convertible | [79c59719f7](https://linux-hardware.org/?probe=79c59719f7) | Jun 21, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [dc134b17e9](https://linux-hardware.org/?probe=dc134b17e9) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012G... | Notebook    | [92638f1b46](https://linux-hardware.org/?probe=92638f1b46) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [a384703b5e](https://linux-hardware.org/?probe=a384703b5e) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Google        | Droid                       | Notebook    | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [9a543a0273](https://linux-hardware.org/?probe=9a543a0273) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [9cf3c1f84c](https://linux-hardware.org/?probe=9cf3c1f84c) | Jun 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| HP            | 2B05                        | Desktop     | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [4fc1134f6d](https://linux-hardware.org/?probe=4fc1134f6d) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [e09cfb9236](https://linux-hardware.org/?probe=e09cfb9236) | Jun 19, 2022 |
| HP            | Pavilion dv7                | Notebook    | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b9d3cb4755](https://linux-hardware.org/?probe=b9d3cb4755) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [76f5dd0027](https://linux-hardware.org/?probe=76f5dd0027) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [32713d6759](https://linux-hardware.org/?probe=32713d6759) | Jun 18, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [91af0ec6df](https://linux-hardware.org/?probe=91af0ec6df) | Jun 18, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [a6116d2e8c](https://linux-hardware.org/?probe=a6116d2e8c) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [674addd96b](https://linux-hardware.org/?probe=674addd96b) | Jun 17, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e0b7e5c636](https://linux-hardware.org/?probe=e0b7e5c636) | Jun 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [9cbdc324b7](https://linux-hardware.org/?probe=9cbdc324b7) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | Notebook    | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7205fff536](https://linux-hardware.org/?probe=7205fff536) | Jun 17, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [df4b512aa8](https://linux-hardware.org/?probe=df4b512aa8) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [9074247e52](https://linux-hardware.org/?probe=9074247e52) | Jun 17, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | Notebook    | [91f1df8a58](https://linux-hardware.org/?probe=91f1df8a58) | Jun 17, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [7e65c001a5](https://linux-hardware.org/?probe=7e65c001a5) | Jun 17, 2022 |
| Dell          | 0XC7MM A01                  | Desktop     | [8c8a1ef522](https://linux-hardware.org/?probe=8c8a1ef522) | Jun 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4e53a55031](https://linux-hardware.org/?probe=4e53a55031) | Jun 16, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [7dbb9f4adf](https://linux-hardware.org/?probe=7dbb9f4adf) | Jun 16, 2022 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [c6d123b5ec](https://linux-hardware.org/?probe=c6d123b5ec) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [d28d429121](https://linux-hardware.org/?probe=d28d429121) | Jun 16, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [08527d664b](https://linux-hardware.org/?probe=08527d664b) | Jun 16, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [f83da947b8](https://linux-hardware.org/?probe=f83da947b8) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Itautec       | Infoway w7430               | Notebook    | [776d876064](https://linux-hardware.org/?probe=776d876064) | Jun 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [388285efe8](https://linux-hardware.org/?probe=388285efe8) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6b73227c17](https://linux-hardware.org/?probe=6b73227c17) | Jun 15, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [155af690bd](https://linux-hardware.org/?probe=155af690bd) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6f25a1e394](https://linux-hardware.org/?probe=6f25a1e394) | Jun 15, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [788b7856ca](https://linux-hardware.org/?probe=788b7856ca) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| Dell          | Precision 3551              | Notebook    | [3499839fd0](https://linux-hardware.org/?probe=3499839fd0) | Jun 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6f26fecef](https://linux-hardware.org/?probe=b6f26fecef) | Jun 14, 2022 |
| HP            | Notebook                    | Notebook    | [390f55db2e](https://linux-hardware.org/?probe=390f55db2e) | Jun 14, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [61104911ed](https://linux-hardware.org/?probe=61104911ed) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1bb2aa2c68](https://linux-hardware.org/?probe=1bb2aa2c68) | Jun 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e2385e525c](https://linux-hardware.org/?probe=e2385e525c) | Jun 14, 2022 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [605cab3041](https://linux-hardware.org/?probe=605cab3041) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [33c22b2507](https://linux-hardware.org/?probe=33c22b2507) | Jun 13, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [61d456c166](https://linux-hardware.org/?probe=61d456c166) | Jun 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [20bd05081e](https://linux-hardware.org/?probe=20bd05081e) | Jun 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d147676849](https://linux-hardware.org/?probe=d147676849) | Jun 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [a5d23b52d1](https://linux-hardware.org/?probe=a5d23b52d1) | Jun 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [b8b4869fa1](https://linux-hardware.org/?probe=b8b4869fa1) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e69ce900b7](https://linux-hardware.org/?probe=e69ce900b7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [1c5488bdf7](https://linux-hardware.org/?probe=1c5488bdf7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [fd8af28ed5](https://linux-hardware.org/?probe=fd8af28ed5) | Jun 13, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [17d6efccfa](https://linux-hardware.org/?probe=17d6efccfa) | Jun 12, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [08a04e0c7c](https://linux-hardware.org/?probe=08a04e0c7c) | Jun 12, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [967ef390e0](https://linux-hardware.org/?probe=967ef390e0) | Jun 12, 2022 |
| HP            | 18E5                        | Desktop     | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dbe7d6b6bf](https://linux-hardware.org/?probe=dbe7d6b6bf) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [554002fe47](https://linux-hardware.org/?probe=554002fe47) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a677849f96](https://linux-hardware.org/?probe=a677849f96) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M                    | Desktop     | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [6748bf6f1e](https://linux-hardware.org/?probe=6748bf6f1e) | Jun 11, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [8f468e1fc9](https://linux-hardware.org/?probe=8f468e1fc9) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4180BE1       | Notebook    | [a3c2ffc8e0](https://linux-hardware.org/?probe=a3c2ffc8e0) | Jun 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [18240b9552](https://linux-hardware.org/?probe=18240b9552) | Jun 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [3c8959c8dc](https://linux-hardware.org/?probe=3c8959c8dc) | Jun 11, 2022 |
| HP            | Laptop 17-bs1xx             | Notebook    | [aa23e1d53e](https://linux-hardware.org/?probe=aa23e1d53e) | Jun 11, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [63f76026b7](https://linux-hardware.org/?probe=63f76026b7) | Jun 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [1967d32245](https://linux-hardware.org/?probe=1967d32245) | Jun 10, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [661f4f701b](https://linux-hardware.org/?probe=661f4f701b) | Jun 10, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [272c6283d4](https://linux-hardware.org/?probe=272c6283d4) | Jun 10, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [86b61f1ef6](https://linux-hardware.org/?probe=86b61f1ef6) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | Notebook    | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [4458c8a8ca](https://linux-hardware.org/?probe=4458c8a8ca) | Jun 09, 2022 |
| HP            | ZBook 15                    | Notebook    | [540fada7d4](https://linux-hardware.org/?probe=540fada7d4) | Jun 09, 2022 |
| HP            | ZBook 15                    | Notebook    | [5e3ff70430](https://linux-hardware.org/?probe=5e3ff70430) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Intel         | X79 V2.4E                   | Desktop     | [12a530acde](https://linux-hardware.org/?probe=12a530acde) | Jun 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e934effe87](https://linux-hardware.org/?probe=e934effe87) | Jun 09, 2022 |
| HP            | ENVY dv7                    | Notebook    | [f7401e6566](https://linux-hardware.org/?probe=f7401e6566) | Jun 09, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [e0505ec400](https://linux-hardware.org/?probe=e0505ec400) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [35b29ccf1d](https://linux-hardware.org/?probe=35b29ccf1d) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e12c11bc94](https://linux-hardware.org/?probe=e12c11bc94) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 6475AJ1       | Notebook    | [3ef905b44a](https://linux-hardware.org/?probe=3ef905b44a) | Jun 08, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [0d87deee9d](https://linux-hardware.org/?probe=0d87deee9d) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [7f2eeb5b16](https://linux-hardware.org/?probe=7f2eeb5b16) | Jun 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [73823d7212](https://linux-hardware.org/?probe=73823d7212) | Jun 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c45207e9ed](https://linux-hardware.org/?probe=c45207e9ed) | Jun 07, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [14a3f31e7d](https://linux-hardware.org/?probe=14a3f31e7d) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5cd425083f](https://linux-hardware.org/?probe=5cd425083f) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4120531ac](https://linux-hardware.org/?probe=f4120531ac) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa7cd44609](https://linux-hardware.org/?probe=fa7cd44609) | Jun 07, 2022 |
| HP            | 8710                        | Mini pc     | [a4b6fd8f8a](https://linux-hardware.org/?probe=a4b6fd8f8a) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c446ea33eb](https://linux-hardware.org/?probe=c446ea33eb) | Jun 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c8e7bd54a3](https://linux-hardware.org/?probe=c8e7bd54a3) | Jun 07, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [937c62f908](https://linux-hardware.org/?probe=937c62f908) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [8446232909](https://linux-hardware.org/?probe=8446232909) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [6c562bbebb](https://linux-hardware.org/?probe=6c562bbebb) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [0d56225d08](https://linux-hardware.org/?probe=0d56225d08) | Jun 06, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [5f55cd1869](https://linux-hardware.org/?probe=5f55cd1869) | Jun 06, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [75d7cde897](https://linux-hardware.org/?probe=75d7cde897) | Jun 06, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [178b330cc1](https://linux-hardware.org/?probe=178b330cc1) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9fe17edc24](https://linux-hardware.org/?probe=9fe17edc24) | Jun 06, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [d1409ca910](https://linux-hardware.org/?probe=d1409ca910) | Jun 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [bec76e5f74](https://linux-hardware.org/?probe=bec76e5f74) | Jun 06, 2022 |
| Dell          | 0XC7MM A01                  | Desktop     | [ed376c819b](https://linux-hardware.org/?probe=ed376c819b) | Jun 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| HP            | 250 G5                      | Notebook    | [1cbf1a1c53](https://linux-hardware.org/?probe=1cbf1a1c53) | Jun 06, 2022 |
| Lenovo        | 81WE                        | Notebook    | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0b042e37b3](https://linux-hardware.org/?probe=0b042e37b3) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | Notebook    | [e7e658bc95](https://linux-hardware.org/?probe=e7e658bc95) | Jun 06, 2022 |
| Dell          | 08K0X7 A00                  | Desktop     | [28a29e32c6](https://linux-hardware.org/?probe=28a29e32c6) | Jun 06, 2022 |
| Dell          | 06JWJY A00                  | Desktop     | [577bbe62e1](https://linux-hardware.org/?probe=577bbe62e1) | Jun 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [568a879289](https://linux-hardware.org/?probe=568a879289) | Jun 06, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [28c5fad176](https://linux-hardware.org/?probe=28c5fad176) | Jun 06, 2022 |
| HP            | Elite Dragonfly Max Note... | Convertible | [3b16bdeb2c](https://linux-hardware.org/?probe=3b16bdeb2c) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | Notebook    | [e51b9086bd](https://linux-hardware.org/?probe=e51b9086bd) | Jun 06, 2022 |
| HP            | 250 G5                      | Notebook    | [7cbd2a6796](https://linux-hardware.org/?probe=7cbd2a6796) | Jun 06, 2022 |
| HP            | 250 G5                      | Notebook    | [6668b9ad94](https://linux-hardware.org/?probe=6668b9ad94) | Jun 06, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [f5ded88514](https://linux-hardware.org/?probe=f5ded88514) | Jun 06, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f9ac66019f](https://linux-hardware.org/?probe=f9ac66019f) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [8fbfe75f53](https://linux-hardware.org/?probe=8fbfe75f53) | Jun 06, 2022 |
| Intel         | AB2L .A001                  | All in one  | [21da21e426](https://linux-hardware.org/?probe=21da21e426) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4177CTO       | Notebook    | [fe28db8adc](https://linux-hardware.org/?probe=fe28db8adc) | Jun 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [9cd1c3d383](https://linux-hardware.org/?probe=9cd1c3d383) | Jun 05, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [8b87017c24](https://linux-hardware.org/?probe=8b87017c24) | Jun 05, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [afb7427d61](https://linux-hardware.org/?probe=afb7427d61) | Jun 05, 2022 |
| Foxconn       | H81MXV FAB A                | Desktop     | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [63a565a5e1](https://linux-hardware.org/?probe=63a565a5e1) | Jun 05, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7084316e82](https://linux-hardware.org/?probe=7084316e82) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [155a8dd1a5](https://linux-hardware.org/?probe=155a8dd1a5) | Jun 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [feb1fc06d4](https://linux-hardware.org/?probe=feb1fc06d4) | Jun 05, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [0c40d3f3d2](https://linux-hardware.org/?probe=0c40d3f3d2) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [feec15b490](https://linux-hardware.org/?probe=feec15b490) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | Desktop     | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [be6fcc008b](https://linux-hardware.org/?probe=be6fcc008b) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1813b3a9a5](https://linux-hardware.org/?probe=1813b3a9a5) | Jun 04, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [31de2e546e](https://linux-hardware.org/?probe=31de2e546e) | Jun 04, 2022 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [11834759e2](https://linux-hardware.org/?probe=11834759e2) | Jun 04, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d0797577a9](https://linux-hardware.org/?probe=d0797577a9) | Jun 04, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2e9cc784ac](https://linux-hardware.org/?probe=2e9cc784ac) | Jun 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| Dell          | Precision 5540              | Notebook    | [641aabe445](https://linux-hardware.org/?probe=641aabe445) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| Intel         | AB2L .A001                  | All in one  | [84023f2b4d](https://linux-hardware.org/?probe=84023f2b4d) | Jun 03, 2022 |
| Chuwi         | UBOOK                       | Convertible | [6e2b3d6ee7](https://linux-hardware.org/?probe=6e2b3d6ee7) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [38de8409ef](https://linux-hardware.org/?probe=38de8409ef) | Jun 02, 2022 |
| Framework     | Laptop                      | Notebook    | [625917cfcd](https://linux-hardware.org/?probe=625917cfcd) | Jun 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| ASUSTek       | N82JV                       | Notebook    | [623436f0c3](https://linux-hardware.org/?probe=623436f0c3) | Jun 02, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ff63d0c19b](https://linux-hardware.org/?probe=ff63d0c19b) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [ad66932f23](https://linux-hardware.org/?probe=ad66932f23) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [aed2597085](https://linux-hardware.org/?probe=aed2597085) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [5c8bb97759](https://linux-hardware.org/?probe=5c8bb97759) | Jun 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [86b732afda](https://linux-hardware.org/?probe=86b732afda) | Jun 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [af6a91d3c7](https://linux-hardware.org/?probe=af6a91d3c7) | Jun 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [b68bcf6b84](https://linux-hardware.org/?probe=b68bcf6b84) | Jun 01, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [942b343fff](https://linux-hardware.org/?probe=942b343fff) | Jun 01, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [1ab6112525](https://linux-hardware.org/?probe=1ab6112525) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [3d32754542](https://linux-hardware.org/?probe=3d32754542) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [9bbdfc95bb](https://linux-hardware.org/?probe=9bbdfc95bb) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [38f4cc4c5a](https://linux-hardware.org/?probe=38f4cc4c5a) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [53dbc2fe14](https://linux-hardware.org/?probe=53dbc2fe14) | May 31, 2022 |
| HP            | 255 G1                      | Notebook    | [86f7198193](https://linux-hardware.org/?probe=86f7198193) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ece9950c65](https://linux-hardware.org/?probe=ece9950c65) | May 31, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [586a31368f](https://linux-hardware.org/?probe=586a31368f) | May 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [07a1bcfa9e](https://linux-hardware.org/?probe=07a1bcfa9e) | May 30, 2022 |
| Google        | Droid                       | Notebook    | [35e3edeab3](https://linux-hardware.org/?probe=35e3edeab3) | May 30, 2022 |
| Framework     | Laptop                      | Notebook    | [f1c2a80b70](https://linux-hardware.org/?probe=f1c2a80b70) | May 30, 2022 |
| Lenovo        | ThinkPad X240 20AM0040BR    | Notebook    | [e0ff07b590](https://linux-hardware.org/?probe=e0ff07b590) | May 30, 2022 |
| IT Channel... | PA70Hx                      | Notebook    | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [60a88b2d81](https://linux-hardware.org/?probe=60a88b2d81) | May 30, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [378e6ca9c6](https://linux-hardware.org/?probe=378e6ca9c6) | May 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b27373492](https://linux-hardware.org/?probe=7b27373492) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [c1fd0c2d4f](https://linux-hardware.org/?probe=c1fd0c2d4f) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [cdc051336a](https://linux-hardware.org/?probe=cdc051336a) | May 30, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2e1fd846a3](https://linux-hardware.org/?probe=2e1fd846a3) | May 30, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [15fb1b0353](https://linux-hardware.org/?probe=15fb1b0353) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [23c83c37e6](https://linux-hardware.org/?probe=23c83c37e6) | May 29, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [7d8d96d851](https://linux-hardware.org/?probe=7d8d96d851) | May 29, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [c7c6e27cae](https://linux-hardware.org/?probe=c7c6e27cae) | May 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [159516aefb](https://linux-hardware.org/?probe=159516aefb) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bd9b967f9b](https://linux-hardware.org/?probe=bd9b967f9b) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| Notebook      | P65_P67SG                   | Notebook    | [a2aecd5cd3](https://linux-hardware.org/?probe=a2aecd5cd3) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [df2d7a274d](https://linux-hardware.org/?probe=df2d7a274d) | May 28, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [512d3f18ce](https://linux-hardware.org/?probe=512d3f18ce) | May 28, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Samsung       | 950QDB                      | Convertible | [99178c7961](https://linux-hardware.org/?probe=99178c7961) | May 27, 2022 |
| Timi          | A35S                        | Notebook    | [8a1bee3210](https://linux-hardware.org/?probe=8a1bee3210) | May 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [93d1ebbb72](https://linux-hardware.org/?probe=93d1ebbb72) | May 27, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | Notebook    | [5643c9fb9b](https://linux-hardware.org/?probe=5643c9fb9b) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | Notebook    | [644f3a8dbc](https://linux-hardware.org/?probe=644f3a8dbc) | May 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| Lenovo        | 14w 81MQS02H00              | Notebook    | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [3171915433](https://linux-hardware.org/?probe=3171915433) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | Notebook    | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | Notebook    | [88aabea122](https://linux-hardware.org/?probe=88aabea122) | May 27, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [5507c9109e](https://linux-hardware.org/?probe=5507c9109e) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [9b4287fa8b](https://linux-hardware.org/?probe=9b4287fa8b) | May 26, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [f9df0f4196](https://linux-hardware.org/?probe=f9df0f4196) | May 26, 2022 |
| HP            | Pavilion TS 14              | Notebook    | [b7b3d504e2](https://linux-hardware.org/?probe=b7b3d504e2) | May 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [90ee31b219](https://linux-hardware.org/?probe=90ee31b219) | May 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [4aa126f1e7](https://linux-hardware.org/?probe=4aa126f1e7) | May 26, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ebb7ce2605](https://linux-hardware.org/?probe=ebb7ce2605) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| Samsung       | 550XDA                      | Notebook    | [807781d70e](https://linux-hardware.org/?probe=807781d70e) | May 26, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f754f78f66](https://linux-hardware.org/?probe=f754f78f66) | May 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6f5b6d8d03](https://linux-hardware.org/?probe=6f5b6d8d03) | May 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [06e3526c59](https://linux-hardware.org/?probe=06e3526c59) | May 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [c5ae648f10](https://linux-hardware.org/?probe=c5ae648f10) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [05e785c8c2](https://linux-hardware.org/?probe=05e785c8c2) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [17ca21b3a4](https://linux-hardware.org/?probe=17ca21b3a4) | May 25, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [dcbaf5defc](https://linux-hardware.org/?probe=dcbaf5defc) | May 25, 2022 |
| HP            | Unknown                     | Notebook    | [c6b346ecc6](https://linux-hardware.org/?probe=c6b346ecc6) | May 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | Notebook    | [376f43287f](https://linux-hardware.org/?probe=376f43287f) | May 25, 2022 |
| ASUSTek       | KCMA-D8                     | Desktop     | [2d8bea4f55](https://linux-hardware.org/?probe=2d8bea4f55) | May 24, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 0PU052                      | Desktop     | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| ROCK Pi       | Unknown                     | Notebook    | [aa891c0178](https://linux-hardware.org/?probe=aa891c0178) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [282c849b82](https://linux-hardware.org/?probe=282c849b82) | May 24, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [71657d24c1](https://linux-hardware.org/?probe=71657d24c1) | May 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [385a286d0d](https://linux-hardware.org/?probe=385a286d0d) | May 24, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [eccd990241](https://linux-hardware.org/?probe=eccd990241) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [4f43d0fc78](https://linux-hardware.org/?probe=4f43d0fc78) | May 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7e8bde85cc](https://linux-hardware.org/?probe=7e8bde85cc) | May 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02c35436fd](https://linux-hardware.org/?probe=02c35436fd) | May 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | Notebook    | [8d62205131](https://linux-hardware.org/?probe=8d62205131) | May 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | Notebook    | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [7d35f08c28](https://linux-hardware.org/?probe=7d35f08c28) | May 23, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [49ebd9e68d](https://linux-hardware.org/?probe=49ebd9e68d) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [413a708e81](https://linux-hardware.org/?probe=413a708e81) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [a76a3417d7](https://linux-hardware.org/?probe=a76a3417d7) | May 23, 2022 |
| Toshiba       | Unknown                     | Notebook    | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Lenovo        | ThinkPad X230 2325AC7       | Notebook    | [bf82ad1cc3](https://linux-hardware.org/?probe=bf82ad1cc3) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Sony          | VPCSA2Z9R                   | Notebook    | [5697622de7](https://linux-hardware.org/?probe=5697622de7) | May 22, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [bdb9536c9c](https://linux-hardware.org/?probe=bdb9536c9c) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| ASUSTek       | P8P67-M                     | Desktop     | [83917315b7](https://linux-hardware.org/?probe=83917315b7) | May 22, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [0ea1ce7372](https://linux-hardware.org/?probe=0ea1ce7372) | May 22, 2022 |
| HP            | 15-dc1018ur                 | Notebook    | [aceb1a1011](https://linux-hardware.org/?probe=aceb1a1011) | May 22, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [2b87bae835](https://linux-hardware.org/?probe=2b87bae835) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [4be19d46e1](https://linux-hardware.org/?probe=4be19d46e1) | May 21, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [1c2288918d](https://linux-hardware.org/?probe=1c2288918d) | May 21, 2022 |
| HP            | Unknown                     | Notebook    | [2277c14d4d](https://linux-hardware.org/?probe=2277c14d4d) | May 21, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [06943bb7f1](https://linux-hardware.org/?probe=06943bb7f1) | May 21, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Dell          | Latitude 5490               | Notebook    | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [702e495c23](https://linux-hardware.org/?probe=702e495c23) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [c90fe96957](https://linux-hardware.org/?probe=c90fe96957) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [1984313b19](https://linux-hardware.org/?probe=1984313b19) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d5b9f1fd4a](https://linux-hardware.org/?probe=d5b9f1fd4a) | May 20, 2022 |
| HP            | Pavilion g4                 | Notebook    | [b29455a037](https://linux-hardware.org/?probe=b29455a037) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [567c91351f](https://linux-hardware.org/?probe=567c91351f) | May 20, 2022 |
| HP            | Pavilion g4                 | Notebook    | [001f7d91d2](https://linux-hardware.org/?probe=001f7d91d2) | May 20, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [f6f8622b30](https://linux-hardware.org/?probe=f6f8622b30) | May 20, 2022 |
| Google        | Glimmer                     | Notebook    | [78c39ceda9](https://linux-hardware.org/?probe=78c39ceda9) | May 20, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Samsung       | 550XDA                      | Notebook    | [1f77e9f8f6](https://linux-hardware.org/?probe=1f77e9f8f6) | May 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [8c31783747](https://linux-hardware.org/?probe=8c31783747) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [e8df231af7](https://linux-hardware.org/?probe=e8df231af7) | May 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [711e483bb9](https://linux-hardware.org/?probe=711e483bb9) | May 19, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [68d0cdd597](https://linux-hardware.org/?probe=68d0cdd597) | May 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [28b26566bf](https://linux-hardware.org/?probe=28b26566bf) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0e0fc0905a](https://linux-hardware.org/?probe=0e0fc0905a) | May 19, 2022 |
| SKIKK         | GREEN 4                     | Notebook    | [f58c4904f7](https://linux-hardware.org/?probe=f58c4904f7) | May 19, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [94d2bd3233](https://linux-hardware.org/?probe=94d2bd3233) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | Notebook    | [819420bd66](https://linux-hardware.org/?probe=819420bd66) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | Notebook    | [479ab8b5d7](https://linux-hardware.org/?probe=479ab8b5d7) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [592a32a1af](https://linux-hardware.org/?probe=592a32a1af) | May 18, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [e83ddc569f](https://linux-hardware.org/?probe=e83ddc569f) | May 18, 2022 |
| HP            | 8767 A                      | Desktop     | [0f564fe004](https://linux-hardware.org/?probe=0f564fe004) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Dell          | Latitude E6420              | Notebook    | [0f06571934](https://linux-hardware.org/?probe=0f06571934) | May 18, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [8a6fc346c5](https://linux-hardware.org/?probe=8a6fc346c5) | May 18, 2022 |
| ASUSTek       | X556URK                     | Notebook    | [b217fd2c65](https://linux-hardware.org/?probe=b217fd2c65) | May 18, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [ac9f539524](https://linux-hardware.org/?probe=ac9f539524) | May 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [5e6298871c](https://linux-hardware.org/?probe=5e6298871c) | May 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| HP            | 8767 A                      | Desktop     | [caad4001f1](https://linux-hardware.org/?probe=caad4001f1) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [8d8783e43f](https://linux-hardware.org/?probe=8d8783e43f) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [6e01c5c9f5](https://linux-hardware.org/?probe=6e01c5c9f5) | May 18, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [a3931c5e60](https://linux-hardware.org/?probe=a3931c5e60) | May 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Dell          | Latitude E6230              | Notebook    | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [ef70fd2699](https://linux-hardware.org/?probe=ef70fd2699) | May 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f86ea538c8](https://linux-hardware.org/?probe=f86ea538c8) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [331099a3da](https://linux-hardware.org/?probe=331099a3da) | May 17, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [9159a8f839](https://linux-hardware.org/?probe=9159a8f839) | May 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [c006d01be7](https://linux-hardware.org/?probe=c006d01be7) | May 17, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [2179a16a87](https://linux-hardware.org/?probe=2179a16a87) | May 17, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [de37f2b586](https://linux-hardware.org/?probe=de37f2b586) | May 17, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [94494528f6](https://linux-hardware.org/?probe=94494528f6) | May 16, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [ffee0745b6](https://linux-hardware.org/?probe=ffee0745b6) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e99a8117ba](https://linux-hardware.org/?probe=e99a8117ba) | May 16, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [cf7f597752](https://linux-hardware.org/?probe=cf7f597752) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [efe02f8593](https://linux-hardware.org/?probe=efe02f8593) | May 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| Lenovo        | ThinkPad T440p 20AW000KU... | Notebook    | [66fc91a0d0](https://linux-hardware.org/?probe=66fc91a0d0) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [fa17134027](https://linux-hardware.org/?probe=fa17134027) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [16bd9d3c6d](https://linux-hardware.org/?probe=16bd9d3c6d) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [a15788c695](https://linux-hardware.org/?probe=a15788c695) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [12d277d32c](https://linux-hardware.org/?probe=12d277d32c) | May 15, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4e824e7eac](https://linux-hardware.org/?probe=4e824e7eac) | May 15, 2022 |
| Positivo      | H14BU08                     | Notebook    | [ba7d402358](https://linux-hardware.org/?probe=ba7d402358) | May 15, 2022 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [57c85dd37a](https://linux-hardware.org/?probe=57c85dd37a) | May 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [74cb2084ef](https://linux-hardware.org/?probe=74cb2084ef) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c635e0f3d](https://linux-hardware.org/?probe=6c635e0f3d) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Acer          | AO532h                      | Notebook    | [6055013560](https://linux-hardware.org/?probe=6055013560) | May 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6fc56522d6](https://linux-hardware.org/?probe=6fc56522d6) | May 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1bde2ca3e7](https://linux-hardware.org/?probe=1bde2ca3e7) | May 14, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3112931a28](https://linux-hardware.org/?probe=3112931a28) | May 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [210d27dd90](https://linux-hardware.org/?probe=210d27dd90) | May 14, 2022 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [b04a0b8046](https://linux-hardware.org/?probe=b04a0b8046) | May 13, 2022 |
| ASRock        | B560M-C                     | Desktop     | [b4946d836b](https://linux-hardware.org/?probe=b4946d836b) | May 13, 2022 |
| ASRock        | B560M-C                     | Desktop     | [16360de6cd](https://linux-hardware.org/?probe=16360de6cd) | May 13, 2022 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [8c71a3bd1b](https://linux-hardware.org/?probe=8c71a3bd1b) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [deb6fa57ef](https://linux-hardware.org/?probe=deb6fa57ef) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [50946adee3](https://linux-hardware.org/?probe=50946adee3) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| ICL           | Unknown                     | Notebook    | [cfb2a7c82f](https://linux-hardware.org/?probe=cfb2a7c82f) | May 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9baa4a9f57](https://linux-hardware.org/?probe=9baa4a9f57) | May 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6212c4d612](https://linux-hardware.org/?probe=6212c4d612) | May 12, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [da0e4e32b4](https://linux-hardware.org/?probe=da0e4e32b4) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad X395 20NL0007US    | Notebook    | [aea9571086](https://linux-hardware.org/?probe=aea9571086) | May 11, 2022 |
| Acer          | Aspire M3985                | Desktop     | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b0951956fa](https://linux-hardware.org/?probe=b0951956fa) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | Notebook    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [607c0a2833](https://linux-hardware.org/?probe=607c0a2833) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [9ead3d53b0](https://linux-hardware.org/?probe=9ead3d53b0) | May 11, 2022 |
| Positivo      | C41TB                       | Notebook    | [2df08b295b](https://linux-hardware.org/?probe=2df08b295b) | May 11, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [7dd92b7a41](https://linux-hardware.org/?probe=7dd92b7a41) | May 11, 2022 |
| Positivo      | C41TB                       | Notebook    | [164d3a45c4](https://linux-hardware.org/?probe=164d3a45c4) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | Notebook    | [352c705bf3](https://linux-hardware.org/?probe=352c705bf3) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | Desktop     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | Notebook    | [cb100c3884](https://linux-hardware.org/?probe=cb100c3884) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [9762e9155b](https://linux-hardware.org/?probe=9762e9155b) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [a8c09f53de](https://linux-hardware.org/?probe=a8c09f53de) | May 10, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [a5630f81ad](https://linux-hardware.org/?probe=a5630f81ad) | May 10, 2022 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [73e6cb3b6b](https://linux-hardware.org/?probe=73e6cb3b6b) | May 10, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [fb1d5703eb](https://linux-hardware.org/?probe=fb1d5703eb) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [03fc6852e2](https://linux-hardware.org/?probe=03fc6852e2) | May 10, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2c069935d3](https://linux-hardware.org/?probe=2c069935d3) | May 10, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a0dd43509d](https://linux-hardware.org/?probe=a0dd43509d) | May 09, 2022 |
| Standard      | Unknown                     | Notebook    | [3d9f8907fd](https://linux-hardware.org/?probe=3d9f8907fd) | May 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d7e92b0ac7](https://linux-hardware.org/?probe=d7e92b0ac7) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [86acc529d3](https://linux-hardware.org/?probe=86acc529d3) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| LG Electro... | 16Z90P-K.AAS9U1             | Notebook    | [26536e15bf](https://linux-hardware.org/?probe=26536e15bf) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [11cb46c902](https://linux-hardware.org/?probe=11cb46c902) | May 08, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a1f8265785](https://linux-hardware.org/?probe=a1f8265785) | May 08, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d24bbea844](https://linux-hardware.org/?probe=d24bbea844) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Huanan        | X99-BD4 V1.1, NALEX         | Desktop     | [e69b3ef962](https://linux-hardware.org/?probe=e69b3ef962) | May 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [52d956751f](https://linux-hardware.org/?probe=52d956751f) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | Desktop     | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Dell          | Precision 3520              | Notebook    | [2d5c4aa671](https://linux-hardware.org/?probe=2d5c4aa671) | May 05, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f255a41930](https://linux-hardware.org/?probe=f255a41930) | May 05, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8ca57528af](https://linux-hardware.org/?probe=8ca57528af) | May 04, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [3bc61ca207](https://linux-hardware.org/?probe=3bc61ca207) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [302e27b974](https://linux-hardware.org/?probe=302e27b974) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a9cf3bc268](https://linux-hardware.org/?probe=a9cf3bc268) | May 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| HP            | 1589                        | Desktop     | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7636de5c44](https://linux-hardware.org/?probe=7636de5c44) | May 02, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [72f6ebfc11](https://linux-hardware.org/?probe=72f6ebfc11) | May 01, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [0205c9da07](https://linux-hardware.org/?probe=0205c9da07) | May 01, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [6d0ad0b8f2](https://linux-hardware.org/?probe=6d0ad0b8f2) | May 01, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [6cefd4f4de](https://linux-hardware.org/?probe=6cefd4f4de) | May 01, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [cb6d49fe71](https://linux-hardware.org/?probe=cb6d49fe71) | Apr 30, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83e47f9c91](https://linux-hardware.org/?probe=83e47f9c91) | Apr 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c4d7dc5e80](https://linux-hardware.org/?probe=c4d7dc5e80) | Apr 30, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [07cb268e5e](https://linux-hardware.org/?probe=07cb268e5e) | Apr 30, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [128cdc0a61](https://linux-hardware.org/?probe=128cdc0a61) | Apr 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [0d3c8ed904](https://linux-hardware.org/?probe=0d3c8ed904) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7ad22b030d](https://linux-hardware.org/?probe=7ad22b030d) | Apr 24, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [187db4f8e4](https://linux-hardware.org/?probe=187db4f8e4) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8c3b142c85](https://linux-hardware.org/?probe=8c3b142c85) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [5ce1623306](https://linux-hardware.org/?probe=5ce1623306) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| Wiltronic     | iVIEW i896QW                | Notebook    | [34e1873984](https://linux-hardware.org/?probe=34e1873984) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [466f67adb3](https://linux-hardware.org/?probe=466f67adb3) | Apr 20, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [9e1d98199a](https://linux-hardware.org/?probe=9e1d98199a) | Apr 18, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [81b837dc13](https://linux-hardware.org/?probe=81b837dc13) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Dell          | Studio 1537                 | Notebook    | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Nvidia        | Jetson Xavier NX Develop... | Soc         | [a786d1f74e](https://linux-hardware.org/?probe=a786d1f74e) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | Desktop     | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [77a3c1a7ce](https://linux-hardware.org/?probe=77a3c1a7ce) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [48c7781b77](https://linux-hardware.org/?probe=48c7781b77) | Apr 14, 2022 |
| Dell          | Precision 7540              | Notebook    | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [43769378a7](https://linux-hardware.org/?probe=43769378a7) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | Desktop     | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Dell          | 00NH4P A14                  | Server      | [274931609f](https://linux-hardware.org/?probe=274931609f) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [7349c76e13](https://linux-hardware.org/?probe=7349c76e13) | Apr 11, 2022 |
| Intel         | W7650                       | Notebook    | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| Dell          | Studio 1537                 | Notebook    | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [84927bf894](https://linux-hardware.org/?probe=84927bf894) | Apr 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar       | B550MH                      | Desktop     | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [f00fb05977](https://linux-hardware.org/?probe=f00fb05977) | Apr 07, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [92966a1240](https://linux-hardware.org/?probe=92966a1240) | Apr 06, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [45a343796d](https://linux-hardware.org/?probe=45a343796d) | Apr 06, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1cc5b6fbc3](https://linux-hardware.org/?probe=1cc5b6fbc3) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| HP            | EliteBook x360 830 G5       | Convertible | [d384ca307e](https://linux-hardware.org/?probe=d384ca307e) | Mar 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [fd1c735c98](https://linux-hardware.org/?probe=fd1c735c98) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [927252e84e](https://linux-hardware.org/?probe=927252e84e) | Mar 20, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [be2a3fd33b](https://linux-hardware.org/?probe=be2a3fd33b) | Mar 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [841ab4ffe2](https://linux-hardware.org/?probe=841ab4ffe2) | Mar 01, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Lenovo        | ThinkPad 10 20C10027SP      | Tablet      | [1c4e6ab62b](https://linux-hardware.org/?probe=1c4e6ab62b) | Nov 29, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| HP            | 304Ah                       | Desktop     | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                      | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64                                       | 88        | 8.62%   |
| 5.18.11-200.fc36.x86_64                                      | 86        | 8.42%   |
| 5.18.5-200.fc36.x86_64                                       | 74        | 7.25%   |
| 5.17.6-300.fc36.x86_64                                       | 74        | 7.25%   |
| 5.18.13-200.fc36.x86_64                                      | 71        | 6.95%   |
| 5.17.11-300.fc36.x86_64                                      | 71        | 6.95%   |
| 5.17.13-300.fc36.x86_64                                      | 54        | 5.29%   |
| 5.17.12-300.fc36.x86_64                                      | 47        | 4.6%    |
| 5.18.9-200.fc36.x86_64                                       | 46        | 4.51%   |
| 5.18.10-200.fc36.x86_64                                      | 44        | 4.31%   |
| 5.17.8-300.fc36.x86_64                                       | 43        | 4.21%   |
| 5.18.6-200.fc36.x86_64                                       | 39        | 3.82%   |
| 5.18.7-200.fc36.x86_64                                       | 35        | 3.43%   |
| 5.17.7-300.fc36.x86_64                                       | 33        | 3.23%   |
| 5.17.9-300.fc36.x86_64                                       | 29        | 2.84%   |
| 5.17.1-300.fc36.x86_64                                       | 29        | 2.84%   |
| 5.17.2-300.fc36.x86_64                                       | 25        | 2.45%   |
| 5.17.3-302.fc36.x86_64                                       | 20        | 1.96%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                 | 18        | 1.76%   |
| 5.17.14-300.fc36.x86_64                                      | 8         | 0.78%   |
| 5.18.1-200.fc36.x86_64                                       | 5         | 0.49%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                 | 5         | 0.49%   |
| 5.18.5-201.fsync.fc36.x86_64                                 | 4         | 0.39%   |
| 5.17.4-300.fc36.x86_64                                       | 4         | 0.39%   |
| 5.17.0-300.fc36.x86_64                                       | 4         | 0.39%   |
| 5.18.10-201.fsync.fc36.x86_64                                | 3         | 0.29%   |
| 5.17.5-301.fsync.fc36.x86_64                                 | 3         | 0.29%   |
| 5.18.2-200.fc36.x86_64                                       | 2         | 0.2%    |
| 5.18.1-602.inttf.fc36.x86_64                                 | 2         | 0.2%    |
| 5.17.7-301.fsync.fc36.x86_64                                 | 2         | 0.2%    |
| 5.17.11-602.inttf.fc36.x86_64                                | 2         | 0.2%    |
| 5.15.0-0.rc6.47.fc36.x86_64                                  | 2         | 0.2%    |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64          | 2         | 0.2%    |
| 5.19.0-rc7+                                                  | 1         | 0.1%    |
| 5.19.0-0.rc5.39.fc37.x86_64                                  | 1         | 0.1%    |
| 5.18.9-gnu                                                   | 1         | 0.1%    |
| 5.18.9-201.fsync.fc36.x86_64                                 | 1         | 0.1%    |
| 5.18.9-100.fc35.x86_64                                       | 1         | 0.1%    |
| 5.18.8-xm1.0.fc36.x86_64                                     | 1         | 0.1%    |
| 5.18.8-200.fsync.fc36.x86_64                                 | 1         | 0.1%    |
| 5.18.8-200.fc36.x86_64                                       | 1         | 0.1%    |
| 5.18.7-1.surface.fc36.x86_64                                 | 1         | 0.1%    |
| 5.18.6-201.fsync.fc36.x86_64                                 | 1         | 0.1%    |
| 5.18.5-gnu                                                   | 1         | 0.1%    |
| 5.18.5-250.vanilla.1.fc36.x86_64                             | 1         | 0.1%    |
| 5.18.4-xm1.0.fc36.x86_64                                     | 1         | 0.1%    |
| 5.18.4-125.vanilla.1.fc36.x86_64                             | 1         | 0.1%    |
| 5.18.4-1.surface.fc36.x86_64                                 | 1         | 0.1%    |
| 5.18.2-rc1_MY                                                | 1         | 0.1%    |
| 5.18.10-250.vanilla.1.fc36.x86_64                            | 1         | 0.1%    |
| 5.18.0-0.rc4.20220428git8f4dd16603ce834.36.fc37.x86_64       | 1         | 0.1%    |
| 5.18.0-0.rc3.220422.d569e86915b7f2f.31.vanilla.1.fc36.x86_64 | 1         | 0.1%    |
| 5.18.0                                                       | 1         | 0.1%    |
| 5.17.9-602.inttf.fc36.x86_64                                 | 1         | 0.1%    |
| 5.17.9-302.fsync.fc36.x86_64                                 | 1         | 0.1%    |
| 5.17.9-301.fsync.fc36.x86_64                                 | 1         | 0.1%    |
| 5.17.6-602.inttf.fc36.x86_64                                 | 1         | 0.1%    |
| 5.17.6-300.mbp.fc33.x86_64                                   | 1         | 0.1%    |
| 5.17.6-300.fc36.aarch64                                      | 1         | 0.1%    |
| 5.17.3-301.fsync.fc36.x86_64                                 | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 91        | 8.92%   |
| 5.18.11 | 86        | 8.43%   |
| 5.18.5  | 80        | 7.84%   |
| 5.17.6  | 77        | 7.55%   |
| 5.17.11 | 74        | 7.25%   |
| 5.18.13 | 71        | 6.96%   |
| 5.17.13 | 54        | 5.29%   |
| 5.18.9  | 49        | 4.8%    |
| 5.18.10 | 48        | 4.71%   |
| 5.17.12 | 48        | 4.71%   |
| 5.17.8  | 43        | 4.22%   |
| 5.18.6  | 40        | 3.92%   |
| 5.18.7  | 36        | 3.53%   |
| 5.17.7  | 35        | 3.43%   |
| 5.17.9  | 32        | 3.14%   |
| 5.17.1  | 30        | 2.94%   |
| 5.17.0  | 27        | 2.65%   |
| 5.17.2  | 26        | 2.55%   |
| 5.17.3  | 22        | 2.16%   |
| 5.17.14 | 8         | 0.78%   |
| 5.15.0  | 8         | 0.78%   |
| 5.18.1  | 7         | 0.69%   |
| 5.17.4  | 4         | 0.39%   |
| 5.18.8  | 3         | 0.29%   |
| 5.18.4  | 3         | 0.29%   |
| 5.18.2  | 3         | 0.29%   |
| 5.18.0  | 3         | 0.29%   |
| 5.19.0  | 2         | 0.2%    |
| 5.16.9  | 2         | 0.2%    |
| 5.16.0  | 2         | 0.2%    |
| 5.14.0  | 2         | 0.2%    |
| 5.16.17 | 1         | 0.1%    |
| 5.16.16 | 1         | 0.1%    |
| 5.14.14 | 1         | 0.1%    |
| 5.14.10 | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 550       | 55.78%  |
| 5.18    | 416       | 42.19%  |
| 5.15    | 8         | 0.81%   |
| 5.16    | 6         | 0.61%   |
| 5.14    | 4         | 0.41%   |
| 5.19    | 2         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 953       | 99.69%  |
| aarch64 | 3         | 0.31%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 725       | 75.52%  |
| KDE5          | 148       | 15.42%  |
| Unknown       | 24        | 2.5%    |
| XFCE          | 16        | 1.67%   |
| X-Cinnamon    | 14        | 1.46%   |
| Cinnamon      | 14        | 1.46%   |
| i3            | 6         | 0.63%   |
| MATE          | 5         | 0.52%   |
| GNOME Classic | 2         | 0.21%   |
| Deepin        | 2         | 0.21%   |
| awesome       | 2         | 0.21%   |
| openbox       | 1         | 0.1%    |
| LXQt          | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 699       | 72.51%  |
| X11     | 229       | 23.76%  |
| Tty     | 23        | 2.39%   |
| Unknown | 11        | 1.14%   |
| Web     | 2         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 526       | 54.73%  |
| GDM     | 310       | 32.26%  |
| SDDM    | 74        | 7.7%    |
| LightDM | 50        | 5.2%    |
| Ly      | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 517       | 54.02%  |
| ru_RU   | 71        | 7.42%   |
| en_GB   | 48        | 5.02%   |
| pt_BR   | 47        | 4.91%   |
| de_DE   | 32        | 3.34%   |
| en_AU   | 29        | 3.03%   |
| fr_FR   | 24        | 2.51%   |
| pl_PL   | 21        | 2.19%   |
| es_ES   | 16        | 1.67%   |
| it_IT   | 15        | 1.57%   |
| en_IN   | 11        | 1.15%   |
| en_CA   | 10        | 1.04%   |
| es_MX   | 9         | 0.94%   |
| en_NZ   | 9         | 0.94%   |
| es_AR   | 8         | 0.84%   |
| es_CL   | 6         | 0.63%   |
| cs_CZ   | 6         | 0.63%   |
| nl_NL   | 5         | 0.52%   |
| nl_BE   | 5         | 0.52%   |
| de_AT   | 5         | 0.52%   |
| zh_CN   | 4         | 0.42%   |
| tr_TR   | 4         | 0.42%   |
| pt_PT   | 3         | 0.31%   |
| hu_HU   | 3         | 0.31%   |
| C       | 3         | 0.31%   |
| sv_SE   | 2         | 0.21%   |
| sr_RS   | 2         | 0.21%   |
| ru_UA   | 2         | 0.21%   |
| ja_JP   | 2         | 0.21%   |
| hr_HR   | 2         | 0.21%   |
| fr_BE   | 2         | 0.21%   |
| fi_FI   | 2         | 0.21%   |
| es_EC   | 2         | 0.21%   |
| en_ZA   | 2         | 0.21%   |
| en_IL   | 2         | 0.21%   |
| en_IE   | 2         | 0.21%   |
| en_DK   | 2         | 0.21%   |
| de_CH   | 2         | 0.21%   |
| da_DK   | 2         | 0.21%   |
| sk_SK   | 1         | 0.1%    |
| nb_NO   | 1         | 0.1%    |
| id_ID   | 1         | 0.1%    |
| gl_ES   | 1         | 0.1%    |
| fr_CA   | 1         | 0.1%    |
| es_VE   | 1         | 0.1%    |
| es_UY   | 1         | 0.1%    |
| es_SV   | 1         | 0.1%    |
| es_GT   | 1         | 0.1%    |
| es_CO   | 1         | 0.1%    |
| en_SG   | 1         | 0.1%    |
| en_PH   | 1         | 0.1%    |
| en_NL   | 1         | 0.1%    |
| el_GR   | 1         | 0.1%    |
| ca_ES   | 1         | 0.1%    |
| ba_RU   | 1         | 0.1%    |
| ar_SA   | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 786       | 82.05%  |
| BIOS | 172       | 17.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 774       | 80.96%  |
| Ext4    | 151       | 15.79%  |
| Xfs     | 28        | 2.93%   |
| F2fs    | 2         | 0.21%   |
| Unknown | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 525       | 54.63%  |
| GPT     | 382       | 39.75%  |
| MBR     | 54        | 5.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 849       | 88.53%  |
| Yes       | 110       | 11.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 760       | 79.25%  |
| Yes       | 199       | 20.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 202       | 21.13%  |
| ASUSTek Computer        | 175       | 18.31%  |
| Hewlett-Packard         | 130       | 13.6%   |
| Dell                    | 108       | 11.3%   |
| MSI                     | 69        | 7.22%   |
| Gigabyte Technology     | 64        | 6.69%   |
| Acer                    | 32        | 3.35%   |
| ASRock                  | 26        | 2.72%   |
| Apple                   | 24        | 2.51%   |
| HUAWEI                  | 9         | 0.94%   |
| Samsung Electronics     | 8         | 0.84%   |
| Intel                   | 8         | 0.84%   |
| Toshiba                 | 6         | 0.63%   |
| Microsoft               | 6         | 0.63%   |
| Framework               | 6         | 0.63%   |
| Unknown                 | 6         | 0.63%   |
| Sony                    | 5         | 0.52%   |
| Positivo                | 5         | 0.52%   |
| Notebook                | 5         | 0.52%   |
| Timi                    | 3         | 0.31%   |
| System76                | 3         | 0.31%   |
| Chuwi                   | 3         | 0.31%   |
| ZOTAC                   | 2         | 0.21%   |
| VALE                    | 2         | 0.21%   |
| Raspberry Pi Foundation | 2         | 0.21%   |
| Pegatron                | 2         | 0.21%   |
| Panasonic               | 2         | 0.21%   |
| Huanan                  | 2         | 0.21%   |
| GPU Company             | 2         | 0.21%   |
| Google                  | 2         | 0.21%   |
| Fujitsu                 | 2         | 0.21%   |
| Foxconn                 | 2         | 0.21%   |
| Biostar                 | 2         | 0.21%   |
| BESSTAR Tech            | 2         | 0.21%   |
| Alienware               | 2         | 0.21%   |
| ZoomSmart               | 1         | 0.1%    |
| Wiltronic               | 1         | 0.1%    |
| VIT                     | 1         | 0.1%    |
| TUXEDO                  | 1         | 0.1%    |
| Standard                | 1         | 0.1%    |
| SLIMBOOK                | 1         | 0.1%    |
| SKIKK                   | 1         | 0.1%    |
| ROCK Pi                 | 1         | 0.1%    |
| Packard Bell            | 1         | 0.1%    |
| Nvidia                  | 1         | 0.1%    |
| NCR                     | 1         | 0.1%    |
| Micro Electronics       | 1         | 0.1%    |
| Medion                  | 1         | 0.1%    |
| Login Informatica       | 1         | 0.1%    |
| LG Electronics          | 1         | 0.1%    |
| Itautec                 | 1         | 0.1%    |
| IT Channel Pty          | 1         | 0.1%    |
| ICL                     | 1         | 0.1%    |
| HONOR                   | 1         | 0.1%    |
| GPD                     | 1         | 0.1%    |
| Getac                   | 1         | 0.1%    |
| GEO                     | 1         | 0.1%    |
| eMachines               | 1         | 0.1%    |
| ECS                     | 1         | 0.1%    |
| Clevo                   | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 1.36%   |
| MSI MS-7A38                            | 6         | 0.63%   |
| Framework Laptop                       | 6         | 0.63%   |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.63%   |
| ASUS All Series                        | 6         | 0.63%   |
| HP Notebook                            | 5         | 0.52%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 4         | 0.42%   |
| HP Pavilion g6                         | 4         | 0.42%   |
| HP EliteBook 8470p                     | 4         | 0.42%   |
| MSI MS-7C95                            | 3         | 0.31%   |
| MSI MS-7C91                            | 3         | 0.31%   |
| MSI MS-7C37                            | 3         | 0.31%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 3         | 0.31%   |
| Lenovo ThinkBook 14 G3 ACL 21A2        | 3         | 0.31%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 3         | 0.31%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 3         | 0.31%   |
| Dell XPS 15 9570                       | 3         | 0.31%   |
| Dell XPS 13 9310                       | 3         | 0.31%   |
| Dell OptiPlex 9020                     | 3         | 0.31%   |
| ASUS TUF Gaming B550M-PLUS             | 3         | 0.31%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 3         | 0.31%   |
| ASUS ROG Strix G513QY_G513QY           | 3         | 0.31%   |
| ASUS ROG STRIX B550-I GAMING           | 3         | 0.31%   |
| ASUS PRIME X470-PRO                    | 3         | 0.31%   |
| ASUS CROSSHAIR V FORMULA-Z             | 3         | 0.31%   |
| Timi A35S                              | 2         | 0.21%   |
| Samsung 550XDA                         | 2         | 0.21%   |
| MSI MS-7D43                            | 2         | 0.21%   |
| MSI MS-7C92                            | 2         | 0.21%   |
| MSI MS-7C56                            | 2         | 0.21%   |
| MSI MS-7B86                            | 2         | 0.21%   |
| MSI MS-7B79                            | 2         | 0.21%   |
| MSI MS-7996                            | 2         | 0.21%   |
| MSI MS-7817                            | 2         | 0.21%   |
| Microsoft Surface Pro 7                | 2         | 0.21%   |
| Microsoft Surface Pro                  | 2         | 0.21%   |
| Lenovo Yoga C740-15IML 81TD            | 2         | 0.21%   |
| Lenovo ThinkBook 16p Gen 2 20YM        | 2         | 0.21%   |
| Lenovo IdeaPad 530S-14IKB 81EU         | 2         | 0.21%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 2         | 0.21%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 2         | 0.21%   |
| Lenovo IdeaPad 5 14ALC05 82LM          | 2         | 0.21%   |
| Intel DH77EB AAG39073-304              | 2         | 0.21%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.21%   |
| HP ZBook Fury 15 G7 Mobile Workstation | 2         | 0.21%   |
| HP ZBook 17 G5                         | 2         | 0.21%   |
| HP Z2 Tower G4 Workstation             | 2         | 0.21%   |
| HP ProBook 470 G5                      | 2         | 0.21%   |
| HP Pavilion Laptop 15-cw1xxx           | 2         | 0.21%   |
| HP Pavilion Laptop 15-cs0xxx           | 2         | 0.21%   |
| HP ENVY x360 Convertible 13-ay0xxx     | 2         | 0.21%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx   | 2         | 0.21%   |
| HP 250 G7 Notebook PC                  | 2         | 0.21%   |
| GPU Company GWNR51416                  | 2         | 0.21%   |
| Gigabyte B450 AORUS M                  | 2         | 0.21%   |
| Gigabyte 970A-DS3P                     | 2         | 0.21%   |
| Dell XPS 17 9710                       | 2         | 0.21%   |
| Dell XPS 15 9560                       | 2         | 0.21%   |
| Dell XPS 15 9520                       | 2         | 0.21%   |
| Dell XPS 13 9370                       | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 99        | 10.36%  |
| ASUS ROG           | 53        | 5.54%   |
| Lenovo IdeaPad     | 50        | 5.23%   |
| Dell XPS           | 30        | 3.14%   |
| HP Pavilion        | 29        | 3.03%   |
| Dell Inspiron      | 26        | 2.72%   |
| ASUS PRIME         | 23        | 2.41%   |
| Dell Latitude      | 21        | 2.2%    |
| HP Laptop          | 16        | 1.67%   |
| HP EliteBook       | 16        | 1.67%   |
| ASUS TUF           | 16        | 1.67%   |
| Acer Aspire        | 16        | 1.67%   |
| Dell Precision     | 14        | 1.46%   |
| ASUS VivoBook      | 14        | 1.46%   |
| Unknown            | 13        | 1.36%   |
| HP ProBook         | 12        | 1.26%   |
| Lenovo ThinkBook   | 11        | 1.15%   |
| HP ENVY            | 11        | 1.15%   |
| Lenovo Yoga        | 10        | 1.05%   |
| Dell OptiPlex      | 10        | 1.05%   |
| HP ZBook           | 9         | 0.94%   |
| ASUS ASUS          | 8         | 0.84%   |
| Acer Swift         | 7         | 0.73%   |
| MSI MS-7A38        | 6         | 0.63%   |
| Microsoft Surface  | 6         | 0.63%   |
| Lenovo IdeaPadFlex | 6         | 0.63%   |
| Framework Laptop   | 6         | 0.63%   |
| ASUS All           | 6         | 0.63%   |
| Toshiba Satellite  | 5         | 0.52%   |
| Lenovo Legion      | 5         | 0.52%   |
| HP Notebook        | 5         | 0.52%   |
| HP Compaq          | 5         | 0.52%   |
| Acer Nitro         | 5         | 0.52%   |
| ASUS Zenbook       | 4         | 0.42%   |
| ASUS CROSSHAIR     | 4         | 0.42%   |
| MSI MS-7C95        | 3         | 0.31%   |
| MSI MS-7C91        | 3         | 0.31%   |
| MSI MS-7C37        | 3         | 0.31%   |
| Lenovo ThinkCentre | 3         | 0.31%   |
| HP Z2              | 3         | 0.31%   |
| HP OMEN            | 3         | 0.31%   |
| HP 250             | 3         | 0.31%   |
| Gigabyte B550      | 3         | 0.31%   |
| Gigabyte B450      | 3         | 0.31%   |
| Dell Vostro        | 3         | 0.31%   |
| ASUS ProArt        | 3         | 0.31%   |
| ASRock B450M       | 3         | 0.31%   |
| VALE Notebook      | 2         | 0.21%   |
| Timi A35S          | 2         | 0.21%   |
| Samsung 550XDA     | 2         | 0.21%   |
| RPi Raspberry      | 2         | 0.21%   |
| MSI MS-7D43        | 2         | 0.21%   |
| MSI MS-7C92        | 2         | 0.21%   |
| MSI MS-7C56        | 2         | 0.21%   |
| MSI MS-7B86        | 2         | 0.21%   |
| MSI MS-7B79        | 2         | 0.21%   |
| MSI MS-7996        | 2         | 0.21%   |
| MSI MS-7817        | 2         | 0.21%   |
| MSI GF63           | 2         | 0.21%   |
| Lenovo IdeaCentre  | 2         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 168       | 17.57%  |
| 2021    | 166       | 17.36%  |
| 2019    | 109       | 11.4%   |
| 2018    | 100       | 10.46%  |
| 2017    | 56        | 5.86%   |
| 2012    | 50        | 5.23%   |
| 2013    | 49        | 5.13%   |
| 2022    | 45        | 4.71%   |
| 2015    | 44        | 4.6%    |
| 2016    | 43        | 4.5%    |
| 2011    | 42        | 4.39%   |
| 2014    | 34        | 3.56%   |
| 2010    | 16        | 1.67%   |
| 2009    | 14        | 1.46%   |
| 2008    | 12        | 1.26%   |
| 2007    | 4         | 0.42%   |
| 2006    | 2         | 0.21%   |
| 2005    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 557       | 58.26%  |
| Desktop        | 312       | 32.64%  |
| Convertible    | 48        | 5.02%   |
| All in one     | 16        | 1.67%   |
| Tablet         | 13        | 1.36%   |
| Mini pc        | 6         | 0.63%   |
| System on chip | 3         | 0.31%   |
| Server         | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 775       | 80.9%   |
| Enabled  | 183       | 19.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 953       | 99.69%  |
| Yes  | 3         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 239       | 24.92%  |
| 16.01-24.0  | 223       | 23.25%  |
| 8.01-16.0   | 195       | 20.33%  |
| 32.01-64.0  | 164       | 17.1%   |
| 3.01-4.0    | 67        | 6.99%   |
| 64.01-256.0 | 44        | 4.59%   |
| 24.01-32.0  | 16        | 1.67%   |
| 1.01-2.0    | 7         | 0.73%   |
| 2.01-3.0    | 3         | 0.31%   |
| 0.51-1.0    | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 298       | 30.07%  |
| 2.01-3.0   | 271       | 27.35%  |
| 3.01-4.0   | 233       | 23.51%  |
| 1.01-2.0   | 100       | 10.09%  |
| 8.01-16.0  | 63        | 6.36%   |
| 0.51-1.0   | 12        | 1.21%   |
| 16.01-24.0 | 8         | 0.81%   |
| 24.01-32.0 | 3         | 0.3%    |
| 0.01-0.5   | 3         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 563       | 58.46%  |
| 2      | 242       | 25.13%  |
| 3      | 84        | 8.72%   |
| 4      | 47        | 4.88%   |
| 5      | 10        | 1.04%   |
| 6      | 8         | 0.83%   |
| 7      | 6         | 0.62%   |
| 10     | 2         | 0.21%   |
| 0      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 761       | 79.6%   |
| Yes       | 195       | 20.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 740       | 77.41%  |
| No        | 216       | 22.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 803       | 84%     |
| No        | 153       | 16%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 722       | 75.44%  |
| No        | 235       | 24.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 207       | 21.54%  |
| Russia             | 79        | 8.22%   |
| Brazil             | 65        | 6.76%   |
| Germany            | 57        | 5.93%   |
| Poland             | 36        | 3.75%   |
| India              | 34        | 3.54%   |
| Australia          | 32        | 3.33%   |
| France             | 31        | 3.23%   |
| UK                 | 30        | 3.12%   |
| Italy              | 28        | 2.91%   |
| Netherlands        | 24        | 2.5%    |
| Spain              | 23        | 2.39%   |
| Mexico             | 21        | 2.19%   |
| Turkey             | 16        | 1.66%   |
| Belgium            | 16        | 1.66%   |
| Canada             | 15        | 1.56%   |
| Indonesia          | 13        | 1.35%   |
| Argentina          | 11        | 1.14%   |
| Switzerland        | 10        | 1.04%   |
| Sweden             | 10        | 1.04%   |
| Norway             | 9         | 0.94%   |
| Israel             | 9         | 0.94%   |
| Finland            | 9         | 0.94%   |
| Czechia            | 9         | 0.94%   |
| Hungary            | 8         | 0.83%   |
| Austria            | 8         | 0.83%   |
| New Zealand        | 7         | 0.73%   |
| Chile              | 7         | 0.73%   |
| Belarus            | 7         | 0.73%   |
| South Africa       | 5         | 0.52%   |
| Romania            | 5         | 0.52%   |
| Portugal           | 5         | 0.52%   |
| Philippines        | 5         | 0.52%   |
| Japan              | 5         | 0.52%   |
| Croatia            | 5         | 0.52%   |
| Colombia           | 5         | 0.52%   |
| Bulgaria           | 5         | 0.52%   |
| Ukraine            | 4         | 0.42%   |
| Slovakia           | 4         | 0.42%   |
| Singapore          | 4         | 0.42%   |
| Ireland            | 4         | 0.42%   |
| Greece             | 4         | 0.42%   |
| Estonia            | 4         | 0.42%   |
| China              | 4         | 0.42%   |
| Thailand           | 3         | 0.31%   |
| Taiwan             | 3         | 0.31%   |
| Saudi Arabia       | 3         | 0.31%   |
| Moldova            | 3         | 0.31%   |
| Ecuador            | 3         | 0.31%   |
| Denmark            | 3         | 0.31%   |
| Venezuela          | 2         | 0.21%   |
| Serbia             | 2         | 0.21%   |
| Puerto Rico        | 2         | 0.21%   |
| Nepal              | 2         | 0.21%   |
| Kazakhstan         | 2         | 0.21%   |
| Iceland            | 2         | 0.21%   |
| Hong Kong          | 2         | 0.21%   |
| El Salvador        | 2         | 0.21%   |
| Egypt              | 2         | 0.21%   |
| Dominican Republic | 2         | 0.21%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 21        | 2.15%   |
| St Petersburg  | 14        | 1.44%   |
| Sao Paulo      | 12        | 1.23%   |
| Warsaw         | 11        | 1.13%   |
| Melbourne      | 9         | 0.92%   |
| Launceston     | 9         | 0.92%   |
| Paris          | 7         | 0.72%   |
| Minsk          | 7         | 0.72%   |
| Berlin         | 7         | 0.72%   |
| Munich         | 6         | 0.62%   |
| Istanbul       | 6         | 0.62%   |
| Budapest       | 6         | 0.62%   |
| Auckland       | 6         | 0.62%   |
| Oslo           | 5         | 0.51%   |
| New York       | 5         | 0.51%   |
| Mexico City    | 5         | 0.51%   |
| Los Angeles    | 5         | 0.51%   |
| Kolkata        | 5         | 0.51%   |
| Chicago        | 5         | 0.51%   |
| Vienna         | 4         | 0.41%   |
| Tallinn        | 4         | 0.41%   |
| Sydney         | 4         | 0.41%   |
| Singapore      | 4         | 0.41%   |
| Santiago       | 4         | 0.41%   |
| Prague         | 4         | 0.41%   |
| Pasco          | 4         | 0.41%   |
| Novosibirsk    | 4         | 0.41%   |
| Montreal       | 4         | 0.41%   |
| Marietta       | 4         | 0.41%   |
| Jakarta        | 4         | 0.41%   |
| Helsinki       | 4         | 0.41%   |
| Brussels       | 4         | 0.41%   |
| Brisbane       | 4         | 0.41%   |
| Zurich         | 3         | 0.31%   |
| Zagreb         | 3         | 0.31%   |
| Wroclaw        | 3         | 0.31%   |
| Vitória       | 3         | 0.31%   |
| Tel Aviv       | 3         | 0.31%   |
| Stockholm      | 3         | 0.31%   |
| Sofia          | 3         | 0.31%   |
| Seattle        | 3         | 0.31%   |
| Rotterdam      | 3         | 0.31%   |
| Rostov-on-Don  | 3         | 0.31%   |
| Rome           | 3         | 0.31%   |
| Rio de Janeiro | 3         | 0.31%   |
| Porto Alegre   | 3         | 0.31%   |
| Petaẖ Tiqwa  | 3         | 0.31%   |
| Parker         | 3         | 0.31%   |
| Oulu           | 3         | 0.31%   |
| Milan          | 3         | 0.31%   |
| Liverpool      | 3         | 0.31%   |
| Lima           | 3         | 0.31%   |
| Las Vegas      | 3         | 0.31%   |
| Krakow         | 3         | 0.31%   |
| Izmir          | 3         | 0.31%   |
| Bucharest      | 3         | 0.31%   |
| Brooklyn       | 3         | 0.31%   |
| Bratislava     | 3         | 0.31%   |
| Bogotá        | 3         | 0.31%   |
| Bogor          | 3         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 291       | 393    | 20.06%  |
| WDC                            | 178       | 244    | 12.27%  |
| Seagate                        | 163       | 206    | 11.23%  |
| SanDisk                        | 90        | 101    | 6.2%    |
| Kingston                       | 85        | 94     | 5.86%   |
| Toshiba                        | 80        | 87     | 5.51%   |
| Crucial                        | 61        | 67     | 4.2%    |
| SK hynix                       | 54        | 56     | 3.72%   |
| Intel                          | 47        | 59     | 3.24%   |
| Unknown                        | 38        | 50     | 2.62%   |
| Micron Technology              | 38        | 42     | 2.62%   |
| Phison                         | 24        | 26     | 1.65%   |
| KIOXIA                         | 23        | 32     | 1.59%   |
| A-DATA Technology              | 22        | 24     | 1.52%   |
| Hitachi                        | 16        | 17     | 1.1%    |
| HGST                           | 15        | 17     | 1.03%   |
| China                          | 15        | 16     | 1.03%   |
| Apple                          | 13        | 13     | 0.9%    |
| Unknown                        | 12        | 12     | 0.83%   |
| XPG                            | 9         | 11     | 0.62%   |
| Silicon Motion                 | 8         | 8      | 0.55%   |
| PNY                            | 8         | 11     | 0.55%   |
| Micron/Crucial Technology      | 8         | 9      | 0.55%   |
| SABRENT                        | 7         | 9      | 0.48%   |
| LITEON                         | 7         | 7      | 0.48%   |
| Corsair                        | 7         | 9      | 0.48%   |
| UMIS                           | 6         | 6      | 0.41%   |
| Patriot                        | 6         | 8      | 0.41%   |
| Intenso                        | 6         | 7      | 0.41%   |
| SSSTC                          | 5         | 5      | 0.34%   |
| SPCC                           | 5         | 8      | 0.34%   |
| Netac                          | 4         | 4      | 0.28%   |
| Goodram                        | 4         | 5      | 0.28%   |
| Gigabyte Technology            | 4         | 7      | 0.28%   |
| Transcend                      | 3         | 3      | 0.21%   |
| Solid State Storage Technology | 3         | 3      | 0.21%   |
| Realtek Semiconductor          | 3         | 3      | 0.21%   |
| OCZ                            | 3         | 3      | 0.21%   |
| LITEONIT                       | 3         | 3      | 0.21%   |
| Lite-On                        | 3         | 3      | 0.21%   |
| Lenovo                         | 3         | 4      | 0.21%   |
| KingDian                       | 3         | 3      | 0.21%   |
| Hewlett-Packard                | 3         | 3      | 0.21%   |
| GALAX                          | 3         | 3      | 0.21%   |
| Fujitsu                        | 3         | 3      | 0.21%   |
| Team                           | 2         | 2      | 0.14%   |
| T-FORCE                        | 2         | 2      | 0.14%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.14%   |
| Lexar                          | 2         | 2      | 0.14%   |
| KingFast                       | 2         | 2      | 0.14%   |
| JMicron Technology             | 2         | 2      | 0.14%   |
| Apacer                         | 2         | 2      | 0.14%   |
| AMicro                         | 2         | 2      | 0.14%   |
| ADATA Technology               | 2         | 2      | 0.14%   |
| WXC-M3                         | 1         | 1      | 0.07%   |
| WDC WDS2                       | 1         | 1      | 0.07%   |
| Vaseky                         | 1         | 1      | 0.07%   |
| USB3.0                         | 1         | 1      | 0.07%   |
| USB                            | 1         | 1      | 0.07%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.07%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB         | 25        | 1.57%   |
| SanDisk NVMe SSD Drive 512GB       | 19        | 1.19%   |
| Samsung NVMe SSD Drive 512GB       | 19        | 1.19%   |
| Kingston SA400S37240G 240GB SSD    | 19        | 1.19%   |
| Samsung NVMe SSD Drive 1024GB      | 17        | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 15        | 0.94%   |
| Intel NVMe SSD Drive 512GB         | 15        | 0.94%   |
| Samsung SSD 850 EVO 250GB          | 14        | 0.88%   |
| Samsung NVMe SSD Drive 500GB       | 14        | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB     | 13        | 0.82%   |
| Samsung NVMe SSD Drive 2TB         | 13        | 0.82%   |
| Samsung NVMe SSD Drive 256GB       | 13        | 0.82%   |
| SK hynix NVMe SSD Drive 512GB      | 12        | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB     | 12        | 0.75%   |
| Unknown                            | 12        | 0.75%   |
| Seagate ST500DM002-1BD142 500GB    | 10        | 0.63%   |
| SanDisk NVMe SSD Drive 500GB       | 10        | 0.63%   |
| HGST HTS721010A9E630 1TB           | 10        | 0.63%   |
| Crucial CT500MX500SSD1 500GB       | 10        | 0.63%   |
| Crucial CT1000MX500SSD1 1TB        | 10        | 0.63%   |
| Unknown MMC Card  64GB             | 9         | 0.57%   |
| SanDisk NVMe SSD Drive 1TB         | 9         | 0.57%   |
| Samsung SSD 860 EVO 500GB          | 9         | 0.57%   |
| Crucial CT480BX500SSD1 480GB       | 9         | 0.57%   |
| Crucial CT240BX500SSD1 240GB       | 9         | 0.57%   |
| Toshiba NVMe SSD Drive 256GB       | 8         | 0.5%    |
| Samsung SSD 850 EVO 500GB          | 8         | 0.5%    |
| Micron NVMe SSD Drive 512GB        | 8         | 0.5%    |
| KIOXIA NVMe SSD Drive 512GB        | 8         | 0.5%    |
| Kingston SA400S37120G 120GB SSD    | 8         | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB           | 7         | 0.44%   |
| Toshiba NVMe SSD Drive 512GB       | 7         | 0.44%   |
| Toshiba MQ01ABD100 1TB             | 7         | 0.44%   |
| SanDisk NVMe SSD Drive 1024GB      | 7         | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB     | 7         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB       | 7         | 0.44%   |
| SABRENT Disk 1TB                   | 7         | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 6         | 0.38%   |
| WDC WD40EFRX-68N32N0 4TB           | 6         | 0.38%   |
| Unknown MMC Card  32GB             | 6         | 0.38%   |
| Toshiba MQ04ABF100 1TB             | 6         | 0.38%   |
| SK hynix NVMe SSD Drive 256GB      | 6         | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB     | 6         | 0.38%   |
| Seagate Expansion 1TB              | 6         | 0.38%   |
| Samsung SSD 980 PRO 1TB            | 6         | 0.38%   |
| Samsung SSD 870 EVO 500GB          | 6         | 0.38%   |
| Samsung SSD 860 EVO 250GB          | 6         | 0.38%   |
| Samsung SSD 860 EVO 1TB            | 6         | 0.38%   |
| Samsung SSD 850 EVO 1TB            | 6         | 0.38%   |
| Samsung SSD 840 EVO 250GB          | 6         | 0.38%   |
| Kingston NVMe SSD Drive 1TB        | 6         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 5         | 0.31%   |
| WDC WD10EZEX-00WN4A0 1TB           | 5         | 0.31%   |
| Unknown MMC Card  128GB            | 5         | 0.31%   |
| SK hynix NVMe SSD Drive 1024GB     | 5         | 0.31%   |
| Samsung SSD 870 QVO 2TB            | 5         | 0.31%   |
| Samsung NVMe SSD Drive 250GB       | 5         | 0.31%   |
| Phison NVMe SSD Drive 512GB        | 5         | 0.31%   |
| Phison NVMe SSD Drive 1024GB       | 5         | 0.31%   |
| Micron NVMe SSD Drive 1024GB       | 5         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 198    | 40.41%  |
| WDC                 | 122       | 175    | 31.61%  |
| Toshiba             | 45        | 49     | 11.66%  |
| Hitachi             | 16        | 17     | 4.15%   |
| HGST                | 15        | 17     | 3.89%   |
| SABRENT             | 7         | 9      | 1.81%   |
| Samsung Electronics | 6         | 7      | 1.55%   |
| Apple               | 5         | 5      | 1.3%    |
| Unknown             | 4         | 5      | 1.04%   |
| Fujitsu             | 3         | 3      | 0.78%   |
| USB                 | 1         | 1      | 0.26%   |
| Maxtor              | 1         | 2      | 0.26%   |
| Intenso             | 1         | 1      | 0.26%   |
| IB-AC703            | 1         | 1      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| ASMT106x            | 1         | 1      | 0.26%   |
| ASMT                | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 123       | 158    | 27.58%  |
| Kingston            | 55        | 62     | 12.33%  |
| Crucial             | 54        | 60     | 12.11%  |
| SanDisk             | 35        | 37     | 7.85%   |
| WDC                 | 25        | 32     | 5.61%   |
| China               | 14        | 15     | 3.14%   |
| Intel               | 12        | 12     | 2.69%   |
| Micron Technology   | 11        | 11     | 2.47%   |
| A-DATA Technology   | 11        | 12     | 2.47%   |
| PNY                 | 7         | 9      | 1.57%   |
| Apple               | 7         | 7      | 1.57%   |
| Patriot             | 6         | 8      | 1.35%   |
| LITEON              | 6         | 6      | 1.35%   |
| Toshiba             | 5         | 5      | 1.12%   |
| SPCC                | 5         | 8      | 1.12%   |
| Intenso             | 5         | 6      | 1.12%   |
| Corsair             | 5         | 6      | 1.12%   |
| Seagate             | 4         | 4      | 0.9%    |
| Netac               | 4         | 4      | 0.9%    |
| GOODRAM             | 4         | 5      | 0.9%    |
| Gigabyte Technology | 4         | 7      | 0.9%    |
| Transcend           | 3         | 3      | 0.67%   |
| SK hynix            | 3         | 3      | 0.67%   |
| OCZ                 | 3         | 3      | 0.67%   |
| LITEONIT            | 3         | 3      | 0.67%   |
| GALAX               | 3         | 3      | 0.67%   |
| Lexar               | 2         | 2      | 0.45%   |
| KingDian            | 2         | 2      | 0.45%   |
| Apacer              | 2         | 2      | 0.45%   |
| Unknown             | 2         | 2      | 0.45%   |
| WDC WDS2            | 1         | 1      | 0.22%   |
| Vaseky              | 1         | 1      | 0.22%   |
| USB3.0              | 1         | 1      | 0.22%   |
| Timetec             | 1         | 1      | 0.22%   |
| Teclast             | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| Origin              | 1         | 1      | 0.22%   |
| OCZ-VERTEX3         | 1         | 1      | 0.22%   |
| MyDigitalSSD        | 1         | 1      | 0.22%   |
| Leven               | 1         | 1      | 0.22%   |
| KUIJIA              | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| KingFast            | 1         | 1      | 0.22%   |
| HPE                 | 1         | 1      | 0.22%   |
| GLOWAY              | 1         | 1      | 0.22%   |
| EZCOOL              | 1         | 1      | 0.22%   |
| EAGET               | 1         | 1      | 0.22%   |
| Drevo               | 1         | 1      | 0.22%   |
| Dogfish             | 1         | 1      | 0.22%   |
| ADATA SU            | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 542       | 676    | 41.37%  |
| SSD     | 373       | 518    | 28.47%  |
| HDD     | 334       | 493    | 25.5%   |
| MMC     | 36        | 50     | 2.75%   |
| Unknown | 25        | 30     | 1.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 561       | 972    | 47.06%  |
| NVMe | 542       | 674    | 45.47%  |
| SAS  | 53        | 71     | 4.45%   |
| MMC  | 36        | 50     | 3.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 372       | 514    | 49.14%  |
| 0.51-1.0   | 262       | 323    | 34.61%  |
| 1.01-2.0   | 66        | 93     | 8.72%   |
| 3.01-4.0   | 33        | 49     | 4.36%   |
| 2.01-3.0   | 11        | 11     | 1.45%   |
| 4.01-10.0  | 11        | 17     | 1.45%   |
| 10.01-20.0 | 2         | 4      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 206       | 21.15%  |
| 251-500        | 172       | 17.66%  |
| 1001-2000      | 142       | 14.58%  |
| 101-250        | 123       | 12.63%  |
| 1-20           | 98        | 10.06%  |
| More than 3000 | 70        | 7.19%   |
| Unknown        | 66        | 6.78%   |
| 2001-3000      | 46        | 4.72%   |
| 51-100         | 37        | 3.8%    |
| 21-50          | 14        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 303       | 30.82%  |
| 21-50          | 146       | 14.85%  |
| 51-100         | 116       | 11.8%   |
| 101-250        | 113       | 11.5%   |
| 251-500        | 99        | 10.07%  |
| Unknown        | 66        | 6.71%   |
| 501-1000       | 65        | 6.61%   |
| 1001-2000      | 44        | 4.48%   |
| More than 3000 | 21        | 2.14%   |
| 2001-3000      | 10        | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 3         | 3      | 5.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 3      | 5.08%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 3.39%   |
| Samsung Electronics SSD 870 EVO 1TB          | 2         | 2      | 3.39%   |
| Samsung Electronics HD322HJ 320GB            | 2         | 2      | 3.39%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 3.39%   |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 3.39%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 1.69%   |
| WDC WD5000LPCX-00VHAT0 500GB                 | 1         | 1      | 1.69%   |
| WDC WD5000AAKX-08ERMA0 500GB                 | 1         | 1      | 1.69%   |
| WDC WD5000AAKX-003CA0 500GB                  | 1         | 1      | 1.69%   |
| WDC WD3200AAKS-75B3A0 320GB                  | 1         | 1      | 1.69%   |
| WDC WD30EZRX-00SPEB0 3TB                     | 1         | 1      | 1.69%   |
| WDC WD2500AAKX-753CA1 250GB                  | 1         | 1      | 1.69%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1         | 1      | 1.69%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 1      | 1.69%   |
| WDC WD2003FYYS-02W0B1 2TB                    | 1         | 6      | 1.69%   |
| WDC WD10EZEX-60ZF5A0 1TB                     | 1         | 1      | 1.69%   |
| WDC WD10EARS-22Y5B1 1TB                      | 1         | 1      | 1.69%   |
| WDC WD1003FBYX-01Y7B1 752GB                  | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 2      | 1.69%   |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 1.69%   |
| Toshiba MK3275GSX 320GB                      | 1         | 1      | 1.69%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1      | 1.69%   |
| SPCC Solid State Disk 1TB                    | 1         | 2      | 1.69%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.69%   |
| Seagate ST500LM030-2E717D 500GB              | 1         | 1      | 1.69%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.69%   |
| Seagate ST4000VN008-2DR166 4TB               | 1         | 1      | 1.69%   |
| Seagate ST3500418AS 500GB                    | 1         | 1      | 1.69%   |
| Seagate ST32000542AS 2TB                     | 1         | 2      | 1.69%   |
| Seagate ST31000528AS 1TB                     | 1         | 1      | 1.69%   |
| Seagate ST2000DX001-1CM164 2TB               | 1         | 1      | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1      | 1.69%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 1.69%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 1.69%   |
| Samsung Electronics SSD 870 EVO 2TB          | 1         | 1      | 1.69%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 1      | 1.69%   |
| Samsung Electronics SSD 840 Series 250GB     | 1         | 1      | 1.69%   |
| Samsung Electronics HD502HJ 500GB            | 1         | 1      | 1.69%   |
| Samsung Electronics HD501LJ 500GB            | 1         | 2      | 1.69%   |
| Origin Inception TLC830 Pro Series 256GB SSD | 1         | 1      | 1.69%   |
| OCZ-VERTEX3 MI 120GB SSD                     | 1         | 1      | 1.69%   |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 1.69%   |
| LITEONIT LCS-128M6S-HP 128GB SSD             | 1         | 1      | 1.69%   |
| Lenovo LENSE20512GMSP34MEAT2TA 512GB         | 1         | 1      | 1.69%   |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 1.69%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.69%   |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1      | 1.69%   |
| Fujitsu MJA2500BH G1 500GB                   | 1         | 1      | 1.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 28.07%  |
| WDC                 | 12        | 18     | 21.05%  |
| Samsung Electronics | 10        | 11     | 17.54%  |
| Toshiba             | 4         | 5      | 7.02%   |
| Hitachi             | 3         | 3      | 5.26%   |
| Intel               | 2         | 2      | 3.51%   |
| HGST                | 2         | 2      | 3.51%   |
| SPCC                | 1         | 2      | 1.75%   |
| SanDisk             | 1         | 1      | 1.75%   |
| Origin              | 1         | 1      | 1.75%   |
| OCZ-VERTEX3         | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| LITEONIT            | 1         | 1      | 1.75%   |
| Lenovo              | 1         | 1      | 1.75%   |
| Fujitsu             | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 38.1%   |
| WDC                 | 12        | 18     | 28.57%  |
| Toshiba             | 4         | 5      | 9.52%   |
| Samsung Electronics | 4         | 5      | 9.52%   |
| Hitachi             | 3         | 3      | 7.14%   |
| HGST                | 2         | 2      | 4.76%   |
| Fujitsu             | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 52     | 73.21%  |
| SSD  | 14        | 15     | 25%     |
| NVMe | 1         | 1      | 1.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 573       | 1059   | 55.63%  |
| Works    | 401       | 638    | 38.93%  |
| Malfunc  | 55        | 68     | 5.34%   |
| Failed   | 1         | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 532       | 39.58%  |
| AMD                            | 213       | 15.85%  |
| Samsung Electronics            | 193       | 14.36%  |
| SanDisk                        | 85        | 6.32%   |
| SK hynix                       | 50        | 3.72%   |
| Toshiba America Info Systems   | 33        | 2.46%   |
| Phison Electronics             | 30        | 2.23%   |
| Kingston Technology Company    | 30        | 2.23%   |
| Micron Technology              | 27        | 2.01%   |
| ASMedia Technology             | 23        | 1.71%   |
| KIOXIA                         | 21        | 1.56%   |
| ADATA Technology               | 20        | 1.49%   |
| Micron/Crucial Technology      | 15        | 1.12%   |
| Silicon Motion                 | 10        | 0.74%   |
| Marvell Technology Group       | 9         | 0.67%   |
| Union Memory (Shenzhen)        | 7         | 0.52%   |
| Solid State Storage Technology | 7         | 0.52%   |
| Nvidia                         | 7         | 0.52%   |
| JMicron Technology             | 7         | 0.52%   |
| Realtek Semiconductor          | 4         | 0.3%    |
| Lite-On Technology             | 4         | 0.3%    |
| Lenovo                         | 3         | 0.22%   |
| Unknown                        | 2         | 0.15%   |
| Silicon Image                  | 2         | 0.15%   |
| Seagate Technology             | 2         | 0.15%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.15%   |
| VIA Technologies               | 1         | 0.07%   |
| ULi Electronics                | 1         | 0.07%   |
| LSI Logic / Symbios Logic      | 1         | 0.07%   |
| Broadcom / LSI                 | 1         | 0.07%   |
| Biwin Storage Technology       | 1         | 0.07%   |
| Apple                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 144       | 9.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 86        | 5.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 51        | 3.46%   |
| Samsung NVMe SSD Controller 980                                                | 46        | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 44        | 2.99%   |
| AMD 400 Series Chipset SATA Controller                                         | 40        | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 39        | 2.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 36        | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34        | 2.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 2.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 32        | 2.17%   |
| SanDisk Non-Volatile memory controller                                         | 27        | 1.83%   |
| Micron Non-Volatile memory controller                                          | 27        | 1.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23        | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 1.56%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 22        | 1.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 21        | 1.43%   |
| SK hynix Gold P31 SSD                                                          | 20        | 1.36%   |
| Phison E12 NVMe Controller                                                     | 20        | 1.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 19        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 19        | 1.29%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 19        | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 17        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 17        | 1.15%   |
| Intel SATA Controller [RAID mode]                                              | 15        | 1.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 15        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 15        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 0.95%   |
| Intel Non-Volatile memory controller                                           | 14        | 0.95%   |
| Intel SSD 660P Series                                                          | 13        | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 13        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 12        | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 12        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 11        | 0.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 0.68%   |
| SK hynix BC511                                                                 | 9         | 0.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 0.54%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 7         | 0.48%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 7         | 0.48%   |
| Solid State Storage Non-Volatile memory controller                             | 7         | 0.48%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 7         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 7         | 0.48%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 7         | 0.48%   |
| Kingston Company Company Non-Volatile memory controller                        | 7         | 0.48%   |
| Kingston Company A2000 NVMe SSD                                                | 7         | 0.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 0.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.48%   |
| SK hynix Non-Volatile memory controller                                        | 6         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 0.41%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 0.41%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 6         | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 640       | 48.12%  |
| NVMe | 541       | 40.68%  |
| RAID | 97        | 7.29%   |
| IDE  | 50        | 3.76%   |
| SAS  | 2         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 648       | 67.78%  |
| AMD     | 304       | 31.8%   |
| ARM     | 2         | 0.21%   |
| Unknown | 2         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 29        | 3.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 1.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.67%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 1.57%   |
| AMD Ryzen 5 3600 6-Core Processor             | 13        | 1.36%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 12        | 1.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 1.25%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 11        | 1.15%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 1.04%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 9         | 0.94%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 9         | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.73%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 7         | 0.73%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 7         | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 7         | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.73%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 6         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 0.63%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 6         | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.63%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 6         | 0.63%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 6         | 0.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 6         | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.63%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 6         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.52%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.52%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 5         | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 5         | 0.52%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.52%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 5         | 0.52%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 4         | 0.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.42%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.42%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.42%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.42%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 4         | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.42%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 4         | 0.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.42%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 203       | 21.21%  |
| Intel Core i5           | 202       | 21.11%  |
| Other                   | 113       | 11.81%  |
| AMD Ryzen 5             | 112       | 11.7%   |
| AMD Ryzen 7             | 74        | 7.73%   |
| Intel Core i3           | 48        | 5.02%   |
| AMD Ryzen 9             | 44        | 4.6%    |
| Intel Celeron           | 21        | 2.19%   |
| Intel Core 2 Duo        | 15        | 1.57%   |
| AMD Ryzen 7 PRO         | 13        | 1.36%   |
| AMD FX                  | 13        | 1.36%   |
| Intel Core i9           | 12        | 1.25%   |
| AMD Ryzen 3             | 12        | 1.25%   |
| Intel Xeon              | 11        | 1.15%   |
| Intel Atom              | 10        | 1.04%   |
| AMD A10                 | 9         | 0.94%   |
| Intel Pentium           | 7         | 0.73%   |
| Intel Pentium Silver    | 5         | 0.52%   |
| AMD A8                  | 4         | 0.42%   |
| AMD Phenom II X4        | 3         | 0.31%   |
| AMD Phenom II X2        | 3         | 0.31%   |
| AMD A6                  | 3         | 0.31%   |
| Intel Pentium Dual-Core | 2         | 0.21%   |
| Intel Core 2 Quad       | 2         | 0.21%   |
| AMD Athlon Dual Core    | 2         | 0.21%   |
| AMD Athlon 64 X2        | 2         | 0.21%   |
| Intel Pentium Gold      | 1         | 0.1%    |
| Intel Genuine           | 1         | 0.1%    |
| Intel Core 2            | 1         | 0.1%    |
| AMD Ryzen 5 PRO         | 1         | 0.1%    |
| AMD PRO A8              | 1         | 0.1%    |
| AMD Phenom II           | 1         | 0.1%    |
| AMD Opteron             | 1         | 0.1%    |
| AMD E1                  | 1         | 0.1%    |
| AMD Athlon X4           | 1         | 0.1%    |
| AMD Athlon II Dual-Core | 1         | 0.1%    |
| AMD Athlon II           | 1         | 0.1%    |
| AMD Athlon 64           | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 368       | 38.45%  |
| 2       | 236       | 24.66%  |
| 6       | 158       | 16.51%  |
| 8       | 132       | 13.79%  |
| 12      | 26        | 2.72%   |
| 16      | 11        | 1.15%   |
| 14      | 7         | 0.73%   |
| 10      | 7         | 0.73%   |
| 3       | 6         | 0.63%   |
| Unknown | 3         | 0.31%   |
| 1       | 2         | 0.21%   |
| 18      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 950       | 99.37%  |
| 2       | 3         | 0.31%   |
| Unknown | 3         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 795       | 83.16%  |
| 1       | 158       | 16.53%  |
| Unknown | 3         | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 955       | 99.9%   |
| 64-bit         | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 66        | 6.89%   |
| 0x306a9    | 48        | 5.01%   |
| 0x0a50000c | 46        | 4.8%    |
| 0x906ea    | 43        | 4.49%   |
| 0x306c3    | 41        | 4.28%   |
| 0x806ea    | 40        | 4.18%   |
| 0x206a7    | 39        | 4.07%   |
| Unknown    | 39        | 4.07%   |
| 0x806ec    | 34        | 3.55%   |
| 0xa0652    | 26        | 2.71%   |
| 0x806e9    | 25        | 2.61%   |
| 0x0a201016 | 24        | 2.51%   |
| 0x08701021 | 24        | 2.51%   |
| 0x40651    | 23        | 2.4%    |
| 0x506e3    | 22        | 2.3%    |
| 0x08108109 | 22        | 2.3%    |
| 0x08608103 | 20        | 2.09%   |
| 0x906e9    | 18        | 1.88%   |
| 0x406e3    | 18        | 1.88%   |
| 0x306d4    | 18        | 1.88%   |
| 0x08600106 | 17        | 1.77%   |
| 0x0800820d | 15        | 1.57%   |
| 0x706e5    | 13        | 1.36%   |
| 0x1067a    | 12        | 1.25%   |
| 0x90672    | 10        | 1.04%   |
| 0x08108102 | 10        | 1.04%   |
| 0x0a404101 | 9         | 0.94%   |
| 0x08600104 | 9         | 0.94%   |
| 0xa0671    | 8         | 0.84%   |
| 0xa0655    | 8         | 0.84%   |
| 0xa0653    | 8         | 0.84%   |
| 0x906ed    | 8         | 0.84%   |
| 0x906a3    | 8         | 0.84%   |
| 0x806eb    | 7         | 0.73%   |
| 0x706a8    | 7         | 0.73%   |
| 0x0a201009 | 7         | 0.73%   |
| 0x06000822 | 7         | 0.73%   |
| 0x806d1    | 6         | 0.63%   |
| 0x506c9    | 6         | 0.63%   |
| 0x106e5    | 6         | 0.63%   |
| 0x20655    | 5         | 0.52%   |
| 0x10676    | 5         | 0.52%   |
| 0x08608102 | 5         | 0.52%   |
| 0x08600103 | 5         | 0.52%   |
| 0x906c0    | 4         | 0.42%   |
| 0x706a1    | 4         | 0.42%   |
| 0x406c4    | 4         | 0.42%   |
| 0x30678    | 4         | 0.42%   |
| 0x20652    | 4         | 0.42%   |
| 0x08701013 | 4         | 0.42%   |
| 0x08101016 | 4         | 0.42%   |
| 0x0810100b | 4         | 0.42%   |
| 0x08001137 | 4         | 0.42%   |
| 0x906ec    | 3         | 0.31%   |
| 0x6fb      | 3         | 0.31%   |
| 0x406c3    | 3         | 0.31%   |
| 0x306f2    | 3         | 0.31%   |
| 0x206d7    | 3         | 0.31%   |
| 0x0a50000d | 3         | 0.31%   |
| 0x0a50000b | 3         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 184       | 19.23%  |
| Zen 3            | 96        | 10.03%  |
| Haswell          | 71        | 7.42%   |
| TigerLake        | 70        | 7.31%   |
| Zen 2            | 61        | 6.37%   |
| Zen+             | 48        | 5.02%   |
| IvyBridge        | 48        | 5.02%   |
| CometLake        | 45        | 4.7%    |
| Skylake          | 43        | 4.49%   |
| Unknown          | 43        | 4.49%   |
| SandyBridge      | 42        | 4.39%   |
| Icelake          | 27        | 2.82%   |
| Broadwell        | 20        | 2.09%   |
| Alderlake Hybrid | 20        | 2.09%   |
| Penryn           | 18        | 1.88%   |
| Zen              | 17        | 1.78%   |
| Piledriver       | 14        | 1.46%   |
| Westmere         | 11        | 1.15%   |
| Silvermont       | 11        | 1.15%   |
| Goldmont plus    | 11        | 1.15%   |
| K10              | 10        | 1.04%   |
| Excavator        | 9         | 0.94%   |
| Nehalem          | 6         | 0.63%   |
| Goldmont         | 6         | 0.63%   |
| K8 Hammer        | 5         | 0.52%   |
| Tremont          | 4         | 0.42%   |
| Core             | 4         | 0.42%   |
| Bonnell          | 4         | 0.42%   |
| Bulldozer        | 3         | 0.31%   |
| K10 Llano        | 2         | 0.21%   |
| Steamroller      | 1         | 0.1%    |
| Puma             | 1         | 0.1%    |
| Jaguar           | 1         | 0.1%    |
| Bobcat           | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 519       | 44.32%  |
| Nvidia                     | 331       | 28.27%  |
| AMD                        | 319       | 27.24%  |
| Matrox Electronics Systems | 1         | 0.09%   |
| ASPEED Technology          | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 65        | 5.41%   |
| AMD Cezanne                                                                              | 45        | 3.74%   |
| Intel UHD Graphics 620                                                                   | 42        | 3.49%   |
| AMD Renoir                                                                               | 33        | 2.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 33        | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 2.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 26        | 2.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 2.08%   |
| AMD Lucienne                                                                             | 25        | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 2%      |
| Intel HD Graphics 620                                                                    | 23        | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 15        | 1.25%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 14        | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 1.08%   |
| Intel HD Graphics 530                                                                    | 13        | 1.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 13        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 0.92%   |
| AMD Rembrandt [Radeon 680M]                                                              | 11        | 0.92%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 10        | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.75%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 9         | 0.75%   |
| Intel HD Graphics 630                                                                    | 8         | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 8         | 0.67%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 8         | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 8         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.58%   |
| Nvidia TU117M                                                                            | 7         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 7         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7         | 0.58%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 7         | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.58%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.58%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.5%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.5%    |
| Intel AlderLake-S GT1                                                                    | 6         | 0.5%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 6         | 0.5%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 5         | 0.42%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.42%   |
| Nvidia GP108M [GeForce MX250]                                                            | 5         | 0.42%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5         | 0.42%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.42%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 329       | 34.41%  |
| 1 x AMD         | 244       | 25.52%  |
| Intel + Nvidia  | 153       | 16%     |
| 1 x Nvidia      | 147       | 15.38%  |
| AMD + Nvidia    | 29        | 3.03%   |
| 2 x AMD         | 24        | 2.51%   |
| Intel + AMD     | 21        | 2.2%    |
| Other           | 4         | 0.42%   |
| 2 x Nvidia      | 2         | 0.21%   |
| 1 x Matrox      | 1         | 0.1%    |
| Intel + 2 x AMD | 1         | 0.1%    |
| 1 x ASPEED      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 771       | 80.15%  |
| Proprietary | 168       | 17.46%  |
| Unknown     | 23        | 2.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 460       | 47.87%  |
| 1.01-2.0   | 133       | 13.84%  |
| 0.01-0.5   | 111       | 11.55%  |
| 3.01-4.0   | 92        | 9.57%   |
| 7.01-8.0   | 59        | 6.14%   |
| 0.51-1.0   | 50        | 5.2%    |
| 8.01-16.0  | 26        | 2.71%   |
| 5.01-6.0   | 23        | 2.39%   |
| 2.01-3.0   | 7         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 153       | 13.85%  |
| BOE                     | 125       | 11.31%  |
| Samsung Electronics     | 97        | 8.78%   |
| Chimei Innolux          | 94        | 8.51%   |
| LG Display              | 93        | 8.42%   |
| Goldstar                | 78        | 7.06%   |
| Dell                    | 69        | 6.24%   |
| Philips                 | 32        | 2.9%    |
| Sharp                   | 30        | 2.71%   |
| Hewlett-Packard         | 30        | 2.71%   |
| Lenovo                  | 28        | 2.53%   |
| BenQ                    | 26        | 2.35%   |
| Apple                   | 23        | 2.08%   |
| Acer                    | 22        | 1.99%   |
| AOC                     | 21        | 1.9%    |
| ViewSonic               | 17        | 1.54%   |
| Ancor Communications    | 16        | 1.45%   |
| PANDA                   | 13        | 1.18%   |
| CSO                     | 12        | 1.09%   |
| Iiyama                  | 11        | 1%      |
| ASUSTek Computer        | 10        | 0.9%    |
| InfoVision              | 9         | 0.81%   |
| Chi Mei Optoelectronics | 8         | 0.72%   |
| MSI                     | 7         | 0.63%   |
| Gigabyte Technology     | 7         | 0.63%   |
| TMX                     | 6         | 0.54%   |
| Sceptre Tech            | 6         | 0.54%   |
| Vizio                   | 3         | 0.27%   |
| Sony                    | 3         | 0.27%   |
| NEC Computers           | 3         | 0.27%   |
| Mi                      | 3         | 0.27%   |
| HUAWEI                  | 3         | 0.27%   |
| HannStar                | 3         | 0.27%   |
| Eizo                    | 3         | 0.27%   |
| Unknown                 | 2         | 0.18%   |
| SKY                     | 2         | 0.18%   |
| SGT                     | 2         | 0.18%   |
| RTK                     | 2         | 0.18%   |
| ONN                     | 2         | 0.18%   |
| Mitsubishi              | 2         | 0.18%   |
| Marantz                 | 2         | 0.18%   |
| Insignia                | 2         | 0.18%   |
| Unknown (CEC)           | 1         | 0.09%   |
| Unknown (1080)          | 1         | 0.09%   |
| Toshiba                 | 1         | 0.09%   |
| Pixio                   | 1         | 0.09%   |
| Panasonic               | 1         | 0.09%   |
| Packard Bell            | 1         | 0.09%   |
| Onkyo                   | 1         | 0.09%   |
| NEX                     | 1         | 0.09%   |
| MIT                     | 1         | 0.09%   |
| Medion                  | 1         | 0.09%   |
| LG Philips              | 1         | 0.09%   |
| JDI                     | 1         | 0.09%   |
| INS                     | 1         | 0.09%   |
| HVR                     | 1         | 0.09%   |
| HKC                     | 1         | 0.09%   |
| Fujitsu Siemens         | 1         | 0.09%   |
| FOX                     | 1         | 0.09%   |
| Element                 | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 7         | 0.61%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 6         | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 6         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 6         | 0.53%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                     | 6         | 0.53%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 5         | 0.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.44%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 5         | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 4         | 0.35%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 4         | 0.35%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch              | 4         | 0.35%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                       | 4         | 0.35%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 4         | 0.35%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 4         | 0.35%   |
| Dell E2216H DELF069 1920x1080 476x268mm 21.5-inch                         | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch          | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 4         | 0.35%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                     | 4         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 4         | 0.35%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 4         | 0.35%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 3         | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch     | 3         | 0.26%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                  | 3         | 0.26%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                   | 3         | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.26%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                          | 3         | 0.26%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 3         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 3         | 0.26%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch                 | 3         | 0.26%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                  | 3         | 0.26%   |
| Goldstar LG ULTRAGEAR GSM774B 3440x1440 800x330mm 34.1-inch               | 3         | 0.26%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                     | 3         | 0.26%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch           | 3         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch          | 3         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 3         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.26%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                     | 3         | 0.26%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                     | 3         | 0.26%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO6496 1920x1200 286x178mm 13.3-inch            | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch            | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch             | 3         | 0.26%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 3         | 0.26%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch          | 3         | 0.26%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch                 | 2         | 0.18%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 540       | 51.63%  |
| 1366x768 (WXGA)    | 120       | 11.47%  |
| 3840x2160 (4K)     | 84        | 8.03%   |
| 2560x1440 (QHD)    | 79        | 7.55%   |
| 1920x1200 (WUXGA)  | 40        | 3.82%   |
| 3440x1440          | 29        | 2.77%   |
| 1600x900 (HD+)     | 26        | 2.49%   |
| 1280x1024 (SXGA)   | 15        | 1.43%   |
| 2560x1080          | 13        | 1.24%   |
| 2560x1600          | 12        | 1.15%   |
| 1680x1050 (WSXGA+) | 10        | 0.96%   |
| 3840x2400          | 8         | 0.76%   |
| 1440x900 (WXGA+)   | 8         | 0.76%   |
| 1280x800 (WXGA)    | 7         | 0.67%   |
| 2256x1504          | 6         | 0.57%   |
| 2160x1440          | 6         | 0.57%   |
| 3456x2160          | 5         | 0.48%   |
| 2880x1800          | 5         | 0.48%   |
| 2736x1824          | 4         | 0.38%   |
| 1360x768           | 4         | 0.38%   |
| 1920x540           | 3         | 0.29%   |
| 3840x1600          | 2         | 0.19%   |
| 3840x1080          | 2         | 0.19%   |
| 3200x2000          | 2         | 0.19%   |
| 2288x1287          | 2         | 0.19%   |
| 2240x1400          | 2         | 0.19%   |
| 1920x1280          | 2         | 0.19%   |
| 1600x1200          | 2         | 0.19%   |
| 1024x768 (XGA)     | 2         | 0.19%   |
| 3200x1800 (QHD+)   | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2200x1650          | 1         | 0.1%    |
| 2160x1200          | 1         | 0.1%    |
| 1920x550           | 1         | 0.1%    |
| 1024x600           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 265       | 23.79%  |
| 13      | 138       | 12.39%  |
| 14      | 124       | 11.13%  |
| 27      | 113       | 10.14%  |
| 24      | 81        | 7.27%   |
| 21      | 67        | 6.01%   |
| 23      | 59        | 5.3%    |
| 17      | 43        | 3.86%   |
| 31      | 39        | 3.5%    |
| 34      | 33        | 2.96%   |
| 12      | 20        | 1.8%    |
| 18      | 17        | 1.53%   |
| 20      | 11        | 0.99%   |
| Unknown | 11        | 0.99%   |
| 22      | 9         | 0.81%   |
| 16      | 9         | 0.81%   |
| 19      | 8         | 0.72%   |
| 72      | 7         | 0.63%   |
| 32      | 7         | 0.63%   |
| 11      | 6         | 0.54%   |
| 40      | 5         | 0.45%   |
| 26      | 5         | 0.45%   |
| 25      | 4         | 0.36%   |
| 84      | 3         | 0.27%   |
| 48      | 3         | 0.27%   |
| 39      | 3         | 0.27%   |
| 29      | 3         | 0.27%   |
| 10      | 3         | 0.27%   |
| 142     | 2         | 0.18%   |
| 100     | 2         | 0.18%   |
| 54      | 2         | 0.18%   |
| 42      | 2         | 0.18%   |
| 37      | 2         | 0.18%   |
| 75      | 1         | 0.09%   |
| 69      | 1         | 0.09%   |
| 49      | 1         | 0.09%   |
| 46      | 1         | 0.09%   |
| 38      | 1         | 0.09%   |
| 36      | 1         | 0.09%   |
| 35      | 1         | 0.09%   |
| 28      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 460       | 42.01%  |
| 501-600        | 235       | 21.46%  |
| 401-500        | 103       | 9.41%   |
| 201-300        | 103       | 9.41%   |
| 601-700        | 55        | 5.02%   |
| 351-400        | 51        | 4.66%   |
| 701-800        | 40        | 3.65%   |
| 1501-2000      | 12        | 1.1%    |
| 801-900        | 11        | 1%      |
| Unknown        | 11        | 1%      |
| 1001-1500      | 6         | 0.55%   |
| More than 2000 | 4         | 0.37%   |
| 901-1000       | 4         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 782       | 80.12%  |
| 16/10   | 105       | 10.76%  |
| 21/9    | 40        | 4.1%    |
| 3/2     | 20        | 2.05%   |
| 5/4     | 12        | 1.23%   |
| 4/3     | 6         | 0.61%   |
| 32/9    | 3         | 0.31%   |
| Unknown | 3         | 0.31%   |
| 6/5     | 2         | 0.2%    |
| 1.00    | 2         | 0.2%    |
| 1.96    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 267       | 24.21%  |
| 81-90          | 200       | 18.13%  |
| 201-250        | 160       | 14.51%  |
| 301-350        | 120       | 10.88%  |
| 351-500        | 80        | 7.25%   |
| 71-80          | 66        | 5.98%   |
| 151-200        | 43        | 3.9%    |
| 121-130        | 35        | 3.17%   |
| 251-300        | 31        | 2.81%   |
| 141-150        | 20        | 1.81%   |
| More than 1000 | 19        | 1.72%   |
| 501-1000       | 17        | 1.54%   |
| 61-70          | 14        | 1.27%   |
| Unknown        | 11        | 1%      |
| 111-120        | 7         | 0.63%   |
| 51-60          | 6         | 0.54%   |
| 41-50          | 3         | 0.27%   |
| 131-140        | 3         | 0.27%   |
| 91-100         | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 378       | 35.13%  |
| 51-100        | 278       | 25.84%  |
| 101-120       | 229       | 21.28%  |
| 161-240       | 121       | 11.25%  |
| More than 240 | 43        | 4%      |
| 1-50          | 16        | 1.49%   |
| Unknown       | 11        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 736       | 76.59%  |
| 2     | 169       | 17.59%  |
| 0     | 26        | 2.71%   |
| 3     | 22        | 2.29%   |
| 4     | 7         | 0.73%   |
| 5     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 539       | 38.64%  |
| Realtek Semiconductor             | 506       | 36.27%  |
| Qualcomm Atheros                  | 104       | 7.46%   |
| Broadcom                          | 49        | 3.51%   |
| MediaTek                          | 43        | 3.08%   |
| TP-Link                           | 18        | 1.29%   |
| Broadcom Limited                  | 11        | 0.79%   |
| Ralink Technology                 | 9         | 0.65%   |
| Marvell Technology Group          | 8         | 0.57%   |
| Lenovo                            | 8         | 0.57%   |
| Ralink                            | 7         | 0.5%    |
| Nvidia                            | 7         | 0.5%    |
| ASIX Electronics                  | 7         | 0.5%    |
| Sierra Wireless                   | 6         | 0.43%   |
| Aquantia                          | 6         | 0.43%   |
| Qualcomm Atheros Communications   | 5         | 0.36%   |
| Xiaomi                            | 4         | 0.29%   |
| Samsung Electronics               | 4         | 0.29%   |
| Qualcomm                          | 4         | 0.29%   |
| Microsoft                         | 4         | 0.29%   |
| D-Link                            | 4         | 0.29%   |
| ASUSTek Computer                  | 4         | 0.29%   |
| Ericsson Business Mobile Networks | 3         | 0.22%   |
| Belkin Components                 | 3         | 0.22%   |
| Apple                             | 3         | 0.22%   |
| MicroPython                       | 2         | 0.14%   |
| Mellanox Technologies             | 2         | 0.14%   |
| Hewlett-Packard                   | 2         | 0.14%   |
| Fibocom                           | 2         | 0.14%   |
| Edimax Technology                 | 2         | 0.14%   |
| DisplayLink                       | 2         | 0.14%   |
| U-Blox                            | 1         | 0.07%   |
| QNAP System                       | 1         | 0.07%   |
| Prolific Technology               | 1         | 0.07%   |
| PLANEX                            | 1         | 0.07%   |
| OPPO Electronics                  | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Microchip Technology              | 1         | 0.07%   |
| LSI                               | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |
| InterBiometrics                   | 1         | 0.07%   |
| Huawei Technologies               | 1         | 0.07%   |
| Google                            | 1         | 0.07%   |
| Dell                              | 1         | 0.07%   |
| Conexant Systems                  | 1         | 0.07%   |
| Adafruit                          | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 307       | 18.25%  |
| Intel Wi-Fi 6 AX200                                               | 84        | 4.99%   |
| Intel Wi-Fi 6 AX201                                               | 54        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 42        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 2.5%    |
| Intel Wireless 8265 / 8275                                        | 38        | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 37        | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.84%   |
| Intel I211 Gigabit Network Connection                             | 31        | 1.84%   |
| Intel Ethernet Controller I225-V                                  | 30        | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 26        | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 22        | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 20        | 1.19%   |
| Intel Wireless 7265                                               | 19        | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 1.01%   |
| Intel Wireless 7260                                               | 16        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 15        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 0.89%   |
| Intel Wireless 8260                                               | 14        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 0.77%   |
| Intel Wireless-AC 9260                                            | 13        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 12        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 12        | 0.71%   |
| Intel Wireless 3165                                               | 11        | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 11        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                    | 10        | 0.59%   |
| Intel Wireless 3160                                               | 9         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.48%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 0.48%   |
| MediaTek WLAN controller                                          | 7         | 0.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 7         | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 7         | 0.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7         | 0.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.42%   |
| TP-Link 802.11ac NIC                                              | 6         | 0.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.36%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 0.36%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.36%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 6         | 0.36%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 6         | 0.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 441       | 52.38%  |
| Realtek Semiconductor           | 148       | 17.58%  |
| Qualcomm Atheros                | 87        | 10.33%  |
| MediaTek                        | 43        | 5.11%   |
| Broadcom                        | 42        | 4.99%   |
| TP-Link                         | 17        | 2.02%   |
| Ralink Technology               | 9         | 1.07%   |
| Broadcom Limited                | 9         | 1.07%   |
| Ralink                          | 7         | 0.83%   |
| Sierra Wireless                 | 6         | 0.71%   |
| Qualcomm Atheros Communications | 5         | 0.59%   |
| Qualcomm                        | 4         | 0.48%   |
| Microsoft                       | 4         | 0.48%   |
| Marvell Technology Group        | 4         | 0.48%   |
| D-Link                          | 3         | 0.36%   |
| Belkin Components               | 3         | 0.36%   |
| ASUSTek Computer                | 3         | 0.36%   |
| Fibocom                         | 2         | 0.24%   |
| Edimax Technology               | 2         | 0.24%   |
| PLANEX                          | 1         | 0.12%   |
| NetGear                         | 1         | 0.12%   |
| Linksys                         | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 84        | 9.95%   |
| Intel Wi-Fi 6 AX201                                            | 54        | 6.4%    |
| Intel Wireless 8265 / 8275                                     | 38        | 4.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 3.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 29        | 3.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29        | 3.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 27        | 3.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 26        | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 22        | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 2.37%   |
| Intel Wireless 7265                                            | 19        | 2.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 2.01%   |
| Intel Wireless 7260                                            | 16        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 1.78%   |
| Intel Wireless 8260                                            | 14        | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 1.54%   |
| Intel Wireless-AC 9260                                         | 13        | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.42%   |
| Intel Wireless 3165                                            | 11        | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 1.3%    |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.18%   |
| Intel Wireless 3160                                            | 9         | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 0.95%   |
| MediaTek WLAN controller                                       | 7         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 0.83%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7         | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7         | 0.83%   |
| TP-Link 802.11ac NIC                                           | 6         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 0.71%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 0.59%   |
| Realtek 802.11ac NIC                                           | 5         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 0.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 0.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 0.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 0.47%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 4         | 0.47%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.47%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 0.36%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3         | 0.36%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.36%   |
| Intel WiFi Link 5100                                           | 3         | 0.36%   |
| D-Link 802.11ac NIC                                            | 3         | 0.36%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 437       | 54.56%  |
| Intel                    | 259       | 32.33%  |
| Qualcomm Atheros         | 28        | 3.5%    |
| Broadcom                 | 18        | 2.25%   |
| Lenovo                   | 8         | 1%      |
| Nvidia                   | 7         | 0.87%   |
| ASIX Electronics         | 7         | 0.87%   |
| Aquantia                 | 6         | 0.75%   |
| Xiaomi                   | 4         | 0.5%    |
| Samsung Electronics      | 4         | 0.5%    |
| Marvell Technology Group | 4         | 0.5%    |
| Apple                    | 3         | 0.37%   |
| TP-Link                  | 2         | 0.25%   |
| DisplayLink              | 2         | 0.25%   |
| Broadcom Limited         | 2         | 0.25%   |
| QNAP System              | 1         | 0.12%   |
| OPPO Electronics         | 1         | 0.12%   |
| Microchip Technology     | 1         | 0.12%   |
| Mellanox Technologies    | 1         | 0.12%   |
| LG Electronics           | 1         | 0.12%   |
| Huawei Technologies      | 1         | 0.12%   |
| Hewlett-Packard          | 1         | 0.12%   |
| Google                   | 1         | 0.12%   |
| D-Link                   | 1         | 0.12%   |
| ASUSTek Computer         | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 307       | 37.3%   |
| Realtek RTL8125 2.5GbE Controller                                   | 42        | 5.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 42        | 5.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 37        | 4.5%    |
| Intel I211 Gigabit Network Connection                               | 31        | 3.77%   |
| Intel Ethernet Controller I225-V                                    | 30        | 3.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 29        | 3.52%   |
| Intel Ethernet Connection (2) I219-V                                | 15        | 1.82%   |
| Intel Ethernet Connection I217-LM                                   | 12        | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                               | 11        | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                | 10        | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                               | 10        | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                               | 9         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                | 8         | 0.97%   |
| Intel Ethernet Connection (13) I219-V                               | 8         | 0.97%   |
| Intel Ethernet Connection I218-LM                                   | 7         | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                       | 7         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 6         | 0.73%   |
| Intel Ethernet Connection I219-LM                                   | 6         | 0.73%   |
| Intel Ethernet Connection (10) I219-V                               | 6         | 0.73%   |
| Intel 82579V Gigabit Network Connection                             | 6         | 0.73%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 6         | 0.73%   |
| Realtek Killer E3000 2.5GbE Controller                              | 5         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 5         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                | 5         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 5         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 4         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 4         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 4         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4         | 0.49%   |
| Intel I210 Gigabit Network Connection                               | 4         | 0.49%   |
| Intel Ethernet Connection I217-V                                    | 4         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                            | 4         | 0.49%   |
| Intel 82574L Gigabit Network Connection                             | 4         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 3         | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 3         | 0.36%   |
| Nvidia MCP79 Ethernet                                               | 3         | 0.36%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 3         | 0.36%   |
| Lenovo ThinkPad Lan                                                 | 3         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                                | 3         | 0.36%   |
| Intel Ethernet Connection (6) I219-LM                               | 3         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                               | 3         | 0.36%   |
| Intel Ethernet Connection (13) I219-LM                              | 3         | 0.36%   |
| Intel Ethernet Connection (11) I219-V                               | 3         | 0.36%   |
| Intel Ethernet Connection (11) I219-LM                              | 3         | 0.36%   |
| Intel 82583V Gigabit Network Connection                             | 3         | 0.36%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                   | 3         | 0.36%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 2         | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 2         | 0.24%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2         | 0.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 2         | 0.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                               | 2         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 2         | 0.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 2         | 0.24%   |
| Nvidia MCP61 Ethernet                                               | 2         | 0.24%   |
| Intel Ethernet Controller I225-LM                                   | 2         | 0.24%   |
| Intel Ethernet Connection (3) I218-LM                               | 2         | 0.24%   |
| Intel Ethernet Connection (14) I219-LM                              | 2         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 805       | 51.64%  |
| Ethernet | 739       | 47.4%   |
| Modem    | 12        | 0.77%   |
| Unknown  | 3         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 651       | 64.97%  |
| Ethernet | 351       | 35.03%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 492       | 51.41%  |
| 1     | 417       | 43.57%  |
| 3     | 35        | 3.66%   |
| 0     | 11        | 1.15%   |
| 4     | 2         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 709       | 73.85%  |
| Yes  | 251       | 26.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 389       | 53.14%  |
| Realtek Semiconductor           | 95        | 12.98%  |
| Qualcomm Atheros Communications | 49        | 6.69%   |
| IMC Networks                    | 33        | 4.51%   |
| Cambridge Silicon Radio         | 30        | 4.1%    |
| Foxconn / Hon Hai               | 28        | 3.83%   |
| Broadcom                        | 24        | 3.28%   |
| Apple                           | 24        | 3.28%   |
| Lite-On Technology              | 15        | 2.05%   |
| ASUSTek Computer                | 12        | 1.64%   |
| Realtek                         | 5         | 0.68%   |
| MediaTek                        | 5         | 0.68%   |
| Ralink                          | 4         | 0.55%   |
| Marvell Semiconductor           | 4         | 0.55%   |
| Dell                            | 4         | 0.55%   |
| TP-Link                         | 3         | 0.41%   |
| Toshiba                         | 2         | 0.27%   |
| Hewlett-Packard                 | 2         | 0.27%   |
| USI                             | 1         | 0.14%   |
| Qcom                            | 1         | 0.14%   |
| Opticis                         | 1         | 0.14%   |
| HTC (High Tech Computer)        | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 102       | 13.93%  |
| Intel AX201 Bluetooth                                                               | 90        | 12.3%   |
| Intel AX200 Bluetooth                                                               | 81        | 11.07%  |
| Realtek Bluetooth Radio                                                             | 64        | 8.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 52        | 7.1%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 34        | 4.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 30        | 4.1%    |
| Intel AX210 Bluetooth                                                               | 27        | 3.69%   |
| Intel Bluetooth Device                                                              | 19        | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 18        | 2.46%   |
| IMC Networks Wireless_Device                                                        | 16        | 2.19%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 14        | 1.91%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 11        | 1.5%    |
| Apple Bluetooth USB Host Controller                                                 | 11        | 1.5%    |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 7         | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 0.96%   |
| Apple Bluetooth Host Controller                                                     | 7         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 0.82%   |
| Realtek Bluetooth Radio                                                             | 5         | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 0.68%   |
| MediaTek Wireless_Device                                                            | 5         | 0.68%   |
| Lite-On Wireless_Device                                                             | 5         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.68%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 5         | 0.68%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.55%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 4         | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.55%   |
| ASUS ASUS USB-BT500                                                                 | 4         | 0.55%   |
| TP-Link TP-hink UB500 Adapter                                                       | 3         | 0.41%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.41%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.41%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.41%   |
| ASUS Bluetooth Radio                                                                | 3         | 0.41%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.27%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.27%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.27%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.27%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.27%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.27%   |
| Broadcom BCM2045A0                                                                  | 2         | 0.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.27%   |
| USI Bluetooth Device                                                                | 1         | 0.14%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.14%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.14%   |
| Realtek Bluetooth 5.1 Radio                                                         | 1         | 0.14%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.14%   |
| Opticis Bluetooth Radio                                                             | 1         | 0.14%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.14%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.14%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.14%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.14%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703)                | 1         | 0.14%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.14%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.14%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 636       | 44.32%  |
| AMD                         | 347       | 24.18%  |
| Nvidia                      | 240       | 16.72%  |
| C-Media Electronics         | 25        | 1.74%   |
| Logitech                    | 12        | 0.84%   |
| Plantronics                 | 9         | 0.63%   |
| Lenovo                      | 9         | 0.63%   |
| GN Netcom                   | 9         | 0.63%   |
| Texas Instruments           | 8         | 0.56%   |
| Realtek Semiconductor       | 8         | 0.56%   |
| Creative Technology         | 8         | 0.56%   |
| Corsair                     | 8         | 0.56%   |
| Creative Labs               | 7         | 0.49%   |
| JMTek                       | 6         | 0.42%   |
| Hewlett-Packard             | 6         | 0.42%   |
| Focusrite-Novation          | 6         | 0.42%   |
| XMOS                        | 5         | 0.35%   |
| SteelSeries ApS             | 5         | 0.35%   |
| Kingston Technology         | 5         | 0.35%   |
| Razer USA                   | 4         | 0.28%   |
| Conexant Systems            | 4         | 0.28%   |
| Blue Microphones            | 4         | 0.28%   |
| Sony                        | 3         | 0.21%   |
| Samson Technologies         | 3         | 0.21%   |
| Generalplus Technology      | 3         | 0.21%   |
| FiiO Electronics Technology | 3         | 0.21%   |
| Tenx Technology             | 2         | 0.14%   |
| Schiit Audio                | 2         | 0.14%   |
| Samsung Electronics         | 2         | 0.14%   |
| RODE Microphones            | 2         | 0.14%   |
| No brand                    | 2         | 0.14%   |
| Native Instruments          | 2         | 0.14%   |
| Micro Star International    | 2         | 0.14%   |
| FIFINE Microphones          | 2         | 0.14%   |
| Yamaha                      | 1         | 0.07%   |
| VIA Technologies            | 1         | 0.07%   |
| USB PnP Sound Device        | 1         | 0.07%   |
| USB MICROPHONE              | 1         | 0.07%   |
| Turtle Beach                | 1         | 0.07%   |
| Trust                       | 1         | 0.07%   |
| TerraTec Electronic         | 1         | 0.07%   |
| Sennheiser Communications   | 1         | 0.07%   |
| ROCCAT                      | 1         | 0.07%   |
| PreSonus Audio Electronics  | 1         | 0.07%   |
| Microdia                    | 1         | 0.07%   |
| M-Audio                     | 1         | 0.07%   |
| KORG                        | 1         | 0.07%   |
| iRiver                      | 1         | 0.07%   |
| Huawei Technologies         | 1         | 0.07%   |
| Hangzhou Worlde             | 1         | 0.07%   |
| GYROCOM C&C                 | 1         | 0.07%   |
| Goldvish                    | 1         | 0.07%   |
| Giga-Byte Technology        | 1         | 0.07%   |
| fifinemicrophone.com        | 1         | 0.07%   |
| FIFINE 683 Microphone       | 1         | 0.07%   |
| Elgato Systems              | 1         | 0.07%   |
| DSEA A/S                    | 1         | 0.07%   |
| Dell                        | 1         | 0.07%   |
| DCMT Technology             | 1         | 0.07%   |
| Cooler Master               | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 158       | 9.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 101       | 5.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 88        | 5.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 70        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 65        | 3.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 51        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 45        | 2.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 2.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 40        | 2.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 37        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36        | 2.05%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 2%      |
| Nvidia GP107GL High Definition Audio Controller                            | 25        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 25        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24        | 1.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24        | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 23        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 23        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 21        | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 21        | 1.2%    |
| Intel Broadwell-U Audio Controller                                         | 20        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 17        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 17        | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 0.91%   |
| Intel Alder Lake-S HD Audio Controller                                     | 15        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 14        | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 14        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 13        | 0.74%   |
| AMD Navi 10 HDMI Audio                                                     | 13        | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 11        | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 0.63%   |
| AMD FCH Azalia Controller                                                  | 11        | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                              | 10        | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10        | 0.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                         | 9         | 0.51%   |
| Intel CM238 HD Audio Controller                                            | 9         | 0.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 0.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 0.51%   |
| C-Media Electronics USB Audio Device                                       | 9         | 0.51%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 0.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 0.51%   |
| Nvidia GM204 High Definition Audio Controller                              | 8         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                         | 8         | 0.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 0.46%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 8         | 0.46%   |
| Realtek Semiconductor USB Audio                                            | 7         | 0.4%    |
| Nvidia TU104 HD Audio Controller                                           | 7         | 0.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 0.4%    |
| Nvidia High Definition Audio Controller                                    | 6         | 0.34%   |
| Nvidia GA102 High Definition Audio Controller                              | 6         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 125       | 23.54%  |
| SK hynix            | 99        | 18.64%  |
| Micron Technology   | 66        | 12.43%  |
| Kingston            | 53        | 9.98%   |
| Crucial             | 38        | 7.16%   |
| Unknown             | 31        | 5.84%   |
| G.Skill             | 27        | 5.08%   |
| Corsair             | 22        | 4.14%   |
| Ramaxel Technology  | 12        | 2.26%   |
| A-DATA Technology   | 8         | 1.51%   |
| Unknown (ABCD)      | 6         | 1.13%   |
| Team                | 5         | 0.94%   |
| Smart               | 5         | 0.94%   |
| Patriot             | 5         | 0.94%   |
| Unknown             | 5         | 0.94%   |
| Nanya Technology    | 4         | 0.75%   |
| Silicon Power       | 2         | 0.38%   |
| V-GeN               | 1         | 0.19%   |
| Timetec             | 1         | 0.19%   |
| Sesame              | 1         | 0.19%   |
| Samsung 1           | 1         | 0.19%   |
| Qimonda             | 1         | 0.19%   |
| PUSKILL             | 1         | 0.19%   |
| PNY                 | 1         | 0.19%   |
| Neo Forza           | 1         | 0.19%   |
| Mushkin             | 1         | 0.19%   |
| Mircon              | 1         | 0.19%   |
| Kllisre             | 1         | 0.19%   |
| Hikvision           | 1         | 0.19%   |
| Goodram             | 1         | 0.19%   |
| Goldkey             | 1         | 0.19%   |
| Elpida              | 1         | 0.19%   |
| Atermiter           | 1         | 0.19%   |
| AMD                 | 1         | 0.19%   |
| A-TECH              | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 1.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 1.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 6         | 1.07%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.07%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 5         | 0.89%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.89%   |
| Unknown                                                          | 5         | 0.89%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.71%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.71%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 4         | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.53%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 3         | 0.53%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 3         | 0.53%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.53%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.53%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 3         | 0.53%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s            | 3         | 0.53%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 2         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.36%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 2         | 0.36%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.36%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.36%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2         | 0.36%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 2         | 0.36%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.36%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 2         | 0.36%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.36%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.36%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 2         | 0.36%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.36%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.36%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 2         | 0.36%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.36%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.36%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.36%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 2         | 0.36%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.36%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.36%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 2         | 0.36%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 264       | 58.67%  |
| DDR3    | 102       | 22.67%  |
| LPDDR4  | 33        | 7.33%   |
| Unknown | 22        | 4.89%   |
| LPDDR3  | 18        | 4%      |
| DDR2    | 6         | 1.33%   |
| LPDDR5  | 3         | 0.67%   |
| SDRAM   | 1         | 0.22%   |
| DDR     | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 262       | 57.21%  |
| DIMM         | 129       | 28.17%  |
| Row Of Chips | 61        | 13.32%  |
| Chip         | 3         | 0.66%   |
| RIMM         | 2         | 0.44%   |
| Unknown      | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 204       | 42.15%  |
| 4096  | 138       | 28.51%  |
| 16384 | 78        | 16.12%  |
| 2048  | 32        | 6.61%   |
| 32768 | 23        | 4.75%   |
| 1024  | 8         | 1.65%   |
| 3072  | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 119       | 24.69%  |
| 1600    | 81        | 16.8%   |
| 2667    | 80        | 16.6%   |
| 2133    | 31        | 6.43%   |
| 2400    | 30        | 6.22%   |
| 4267    | 17        | 3.53%   |
| 3600    | 15        | 3.11%   |
| 1867    | 15        | 3.11%   |
| 1333    | 13        | 2.7%    |
| 4800    | 8         | 1.66%   |
| 3266    | 6         | 1.24%   |
| Unknown | 6         | 1.24%   |
| 667     | 5         | 1.04%   |
| 6400    | 4         | 0.83%   |
| 3466    | 4         | 0.83%   |
| 2933    | 4         | 0.83%   |
| 1334    | 4         | 0.83%   |
| 1067    | 4         | 0.83%   |
| 4266    | 3         | 0.62%   |
| 3733    | 3         | 0.62%   |
| 3000    | 3         | 0.62%   |
| 800     | 3         | 0.62%   |
| 400     | 3         | 0.62%   |
| 3866    | 2         | 0.41%   |
| 3400    | 2         | 0.41%   |
| 2800    | 2         | 0.41%   |
| 2666    | 2         | 0.41%   |
| 1066    | 2         | 0.41%   |
| 8400    | 1         | 0.21%   |
| 5200    | 1         | 0.21%   |
| 3467    | 1         | 0.21%   |
| 3333    | 1         | 0.21%   |
| 2733    | 1         | 0.21%   |
| 2600    | 1         | 0.21%   |
| 2048    | 1         | 0.21%   |
| 1639    | 1         | 0.21%   |
| 1200    | 1         | 0.21%   |
| 333     | 1         | 0.21%   |
| 200     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 40%     |
| Brother Industries  | 2         | 20%     |
| Samsung Electronics | 1         | 10%     |
| Prolific Technology | 1         | 10%     |
| Kyocera             | 1         | 10%     |
| Graphtec America    | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Samsung M2070 Series              | 1         | 10%     |
| Prolific PL2305 Parallel Port     | 1         | 10%     |
| Kyocera ECOSYS M5521cdw           | 1         | 10%     |
| HP Neverstop Laser 100x           | 1         | 10%     |
| HP Ink Tank 310 series            | 1         | 10%     |
| HP DeskJet 3700 series            | 1         | 10%     |
| HP DeskJet 3630 series            | 1         | 10%     |
| Graphtec America Graphtec Printer | 1         | 10%     |
| Brother Printer                   | 1         | 10%     |
| Brother DCP-T510W                 | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 83.33%  |
| Seiko Epson | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100               | 2         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 16.67%  |
| Canon CanoScan LiDE 220               | 1         | 16.67%  |
| Canon CanoScan LiDE 210               | 1         | 16.67%  |
| Canon CanoScan LiDE 200               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 135       | 20.21%  |
| IMC Networks                           | 87        | 13.02%  |
| Microdia                               | 53        | 7.93%   |
| Acer                                   | 53        | 7.93%   |
| Realtek Semiconductor                  | 50        | 7.49%   |
| Logitech                               | 45        | 6.74%   |
| Quanta                                 | 38        | 5.69%   |
| Sunplus Innovation Technology          | 28        | 4.19%   |
| Syntek                                 | 26        | 3.89%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 3.74%   |
| Apple                                  | 22        | 3.29%   |
| Lite-On Technology                     | 17        | 2.54%   |
| Luxvisions Innotech Limited            | 15        | 2.25%   |
| Suyin                                  | 8         | 1.2%    |
| Microsoft                              | 7         | 1.05%   |
| Silicon Motion                         | 6         | 0.9%    |
| Samsung Electronics                    | 5         | 0.75%   |
| Ricoh                                  | 5         | 0.75%   |
| SunplusIT                              | 4         | 0.6%    |
| Primax Electronics                     | 4         | 0.6%    |
| Lenovo                                 | 4         | 0.6%    |
| KYE Systems (Mouse Systems)            | 4         | 0.6%    |
| Hewlett-Packard                        | 3         | 0.45%   |
| Alcor Micro                            | 3         | 0.45%   |
| Unknown                                | 2         | 0.3%    |
| Sonix Technology                       | 2         | 0.3%    |
| Intel                                  | 2         | 0.3%    |
| Creative Technology                    | 2         | 0.3%    |
| Asuscom Network                        | 2         | 0.3%    |
| Z-Star Microelectronics                | 1         | 0.15%   |
| Xiaomi                                 | 1         | 0.15%   |
| OPPO Electronics                       | 1         | 0.15%   |
| MacroSilicon                           | 1         | 0.15%   |
| Jieli Technology                       | 1         | 0.15%   |
| icSpring                               | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| FPL-2053-191010                        | 1         | 0.15%   |
| BKX-210918                             | 1         | 0.15%   |
| Aveo Technology                        | 1         | 0.15%   |
| ARC International                      | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 44        | 6.49%   |
| IMC Networks Integrated Camera                          | 38        | 5.6%    |
| Microdia Integrated_Webcam_HD                           | 35        | 5.16%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 28        | 4.13%   |
| Acer Integrated Camera                                  | 20        | 2.95%   |
| Realtek Integrated_Webcam_HD                            | 19        | 2.8%    |
| Syntek Integrated Camera                                | 18        | 2.65%   |
| Logitech HD Pro Webcam C920                             | 15        | 2.21%   |
| Chicony HD Webcam                                       | 15        | 2.21%   |
| Chicony Integrated Camera (1280x720@30)                 | 10        | 1.47%   |
| Apple FaceTime HD Camera (Built-in)                     | 10        | 1.47%   |
| Quanta HD User Facing                                   | 9         | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 9         | 1.33%   |
| Chicony HP Wide Vision HD Camera                        | 9         | 1.33%   |
| Quanta HP HD Camera                                     | 8         | 1.18%   |
| Lite-On Integrated Camera                               | 8         | 1.18%   |
| Chicony HP TrueVision HD Camera                         | 8         | 1.18%   |
| Sunplus Integrated_Webcam_HD                            | 6         | 0.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 6         | 0.88%   |
| Samsung Galaxy A5 (MTP)                                 | 5         | 0.74%   |
| Quanta HP TrueVision HD Camera                          | 5         | 0.74%   |
| Logitech C920 PRO HD Webcam                             | 5         | 0.74%   |
| Lite-On HP Wide Vision HD Camera                        | 5         | 0.74%   |
| Chicony USB 2.0 Camera                                  | 5         | 0.74%   |
| Chicony HP HD Camera                                    | 5         | 0.74%   |
| Sunplus HD 720P webcam                                  | 4         | 0.59%   |
| Realtek Integrated Webcam                               | 4         | 0.59%   |
| Primax HP HD Webcam [Fixed]                             | 4         | 0.59%   |
| Logitech Webcam C270                                    | 4         | 0.59%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 4         | 0.59%   |
| Chicony EasyCamera                                      | 4         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 4         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera        | 4         | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE                               | 4         | 0.59%   |
| Apple Built-in iSight                                   | 4         | 0.59%   |
| Acer Lenovo EasyCamera                                  | 4         | 0.59%   |
| Acer BisonCam, NB Pro                                   | 4         | 0.59%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.44%   |
| Syntek EasyCamera                                       | 3         | 0.44%   |
| Sunplus HD WebCam                                       | 3         | 0.44%   |
| Realtek Integrated Camera 5M                            | 3         | 0.44%   |
| Realtek Front Camera                                    | 3         | 0.44%   |
| Quanta HP Wide Vision HD Camera                         | 3         | 0.44%   |
| Quanta HP Webcam                                        | 3         | 0.44%   |
| Microdia Amcrest AWC2198 USB Webcam                     | 3         | 0.44%   |
| Luxvisions Innotech Limited Integrated Camera           | 3         | 0.44%   |
| Logitech C922 Pro Stream Webcam                         | 3         | 0.44%   |
| Logitech BRIO Ultra HD Webcam                           | 3         | 0.44%   |
| Lite-On HP HD Camera                                    | 3         | 0.44%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera        | 3         | 0.44%   |
| IMC Networks HD Camera                                  | 3         | 0.44%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 0.44%   |
| Chicony USB2.0 Camera                                   | 3         | 0.44%   |
| Chicony HP Webcam                                       | 3         | 0.44%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 0.44%   |
| Apple FaceTime HD Camera                                | 3         | 0.44%   |
| Acer SunplusIT Integrated Camera                        | 3         | 0.44%   |
| Acer HD Webcam                                          | 3         | 0.44%   |
| Acer HD Camera                                          | 3         | 0.44%   |
| Acer BisonCam,NB Pro                                    | 3         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 71        | 40.11%  |
| Validity Sensors           | 39        | 22.03%  |
| Shenzhen Goodix Technology | 36        | 20.34%  |
| Elan Microelectronics      | 9         | 5.08%   |
| LighTuning Technology      | 8         | 4.52%   |
| Upek                       | 6         | 3.39%   |
| Focal-systems.Corp         | 3         | 1.69%   |
| AuthenTec                  | 3         | 1.69%   |
| DigitalPersona             | 2         | 1.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 16.95%  |
| Unknown                                                                    | 17        | 9.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 9.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 8.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 5.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 3.95%   |
| Validity Sensors VFS491                                                    | 6         | 3.39%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 3.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 2.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.82%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.82%   |
| Synaptics  WBDI                                                            | 5         | 2.82%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.82%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.82%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.26%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.69%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.13%   |
| Synaptics WBDI Device                                                      | 2         | 1.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.13%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 1.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.56%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.56%   |
| AuthenTec AES2810                                                          | 1         | 0.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 22        | 45.83%  |
| Broadcom              | 18        | 37.5%   |
| Upek                  | 2         | 4.17%   |
| OmniKey               | 2         | 4.17%   |
| SCM Microsystems      | 1         | 2.08%   |
| Realtek Semiconductor | 1         | 2.08%   |
| O2 Micro              | 1         | 2.08%   |
| Gemalto (was Gemplus) | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 21        | 43.75%  |
| Broadcom 58200                                                               | 7         | 14.58%  |
| Broadcom 5880                                                                | 5         | 10.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.17%   |
| OmniKey CardMan 1021                                                         | 2         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.17%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 2.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.08%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.08%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.08%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 613       | 63.66%  |
| 1     | 276       | 28.66%  |
| 2     | 62        | 6.44%   |
| 3     | 10        | 1.04%   |
| 8     | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 175       | 41.87%  |
| Graphics card            | 88        | 21.05%  |
| Net/wireless             | 44        | 10.53%  |
| Multimedia controller    | 42        | 10.05%  |
| Camera                   | 17        | 4.07%   |
| Bluetooth                | 10        | 2.39%   |
| Chipcard                 | 9         | 2.15%   |
| Card reader              | 7         | 1.67%   |
| Sound                    | 5         | 1.2%    |
| Unassigned class         | 4         | 0.96%   |
| Storage                  | 4         | 0.96%   |
| Modem                    | 4         | 0.96%   |
| Network                  | 3         | 0.72%   |
| Net/ethernet             | 2         | 0.48%   |
| Communication controller | 2         | 0.48%   |
| Wireless                 | 1         | 0.24%   |
| Firewire controller      | 1         | 0.24%   |

