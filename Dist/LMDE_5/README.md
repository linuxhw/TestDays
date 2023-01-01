LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 323

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Google        | Ultima                      | Notebook    | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | Notebook    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | Notebook    | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [5a75bbfc48](https://linux-hardware.org/?probe=5a75bbfc48) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | 8299                        | Desktop     | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | Notebook    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | Notebook    | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | Notebook    | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Dell          | 0N826N A03                  | Desktop     | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [8d633d6712](https://linux-hardware.org/?probe=8d633d6712) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [d23c74b1f2](https://linux-hardware.org/?probe=d23c74b1f2) | Nov 05, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| HP            | 8299                        | Desktop     | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| Dell          | XPS L701X                   | Notebook    | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| HP            | 8299                        | Desktop     | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| AZW           | MINI S                      | Desktop     | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ff09bb4e1](https://linux-hardware.org/?probe=8ff09bb4e1) | Sep 22, 2022 |
| Gateway       | DX4870                      | Desktop     | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Medion        | P15648                      | Notebook    | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | Notebook    | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | Desktop     | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | Desktop     | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | Desktop     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-12-amd64          | 40        | 15.94%  |
| 5.10.0-19-amd64          | 37        | 14.74%  |
| 5.10.0-14-amd64          | 30        | 11.95%  |
| 5.10.0-13-amd64          | 27        | 10.76%  |
| 5.10.0-18-amd64          | 24        | 9.56%   |
| 5.10.0-17-amd64          | 20        | 7.97%   |
| 5.10.0-15-amd64          | 19        | 7.57%   |
| 5.10.0-16-amd64          | 14        | 5.58%   |
| 5.10.0-20-amd64          | 11        | 4.38%   |
| 5.10.0-13-686            | 6         | 2.39%   |
| 5.18.0-0.bpo.1-amd64     | 4         | 1.59%   |
| 5.16.0-0.bpo.4-amd64     | 3         | 1.2%    |
| 5.19.0-0.deb11.2-amd64   | 2         | 0.8%    |
| 6.0.2-x64v2-rt11-xanmod1 | 1         | 0.4%    |
| 6.0.0-0.deb11.2-amd64    | 1         | 0.4%    |
| 5.19.10-xanmod1          | 1         | 0.4%    |
| 5.18.0-4-amd64           | 1         | 0.4%    |
| 5.18.0-3-amd64           | 1         | 0.4%    |
| 5.16.0-0.bpo.3-amd64     | 1         | 0.4%    |
| 5.15.78-xanmod1          | 1         | 0.4%    |
| 5.15.70-xanmod1          | 1         | 0.4%    |
| 5.15.0-0.bpo.3-amd64     | 1         | 0.4%    |
| 5.10.0-19-686            | 1         | 0.4%    |
| 5.10.0-17-686            | 1         | 0.4%    |
| 5.10.0-14-686            | 1         | 0.4%    |
| 5.10.0-12-686            | 1         | 0.4%    |
| 5.10.0-11-686            | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 222       | 92.89%  |
| 5.18.0  | 6         | 2.51%   |
| 5.16.0  | 3         | 1.26%   |
| 5.19.0  | 2         | 0.84%   |
| 6.0.2   | 1         | 0.42%   |
| 6.0.0   | 1         | 0.42%   |
| 5.19.10 | 1         | 0.42%   |
| 5.15.78 | 1         | 0.42%   |
| 5.15.70 | 1         | 0.42%   |
| 5.15.0  | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 222       | 93.28%  |
| 5.18    | 6         | 2.52%   |
| 5.19    | 3         | 1.26%   |
| 5.16    | 3         | 1.26%   |
| 6.0     | 2         | 0.84%   |
| 5.15    | 2         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 224       | 95.32%  |
| i686   | 11        | 4.68%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 211       | 89.41%  |
| Cinnamon   | 18        | 7.63%   |
| XFCE       | 2         | 0.85%   |
| MATE       | 2         | 0.85%   |
| KDE5       | 1         | 0.42%   |
| KDE        | 1         | 0.42%   |
| Unknown    | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 235       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 62.45%  |
| LightDM | 86        | 36.29%  |
| SDDM    | 2         | 0.84%   |
| GDM     | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 83        | 35.17%  |
| de_DE | 32        | 13.56%  |
| ru_RU | 20        | 8.47%   |
| pt_BR | 14        | 5.93%   |
| fr_FR | 12        | 5.08%   |
| en_GB | 12        | 5.08%   |
| it_IT | 8         | 3.39%   |
| es_ES | 7         | 2.97%   |
| pl_PL | 6         | 2.54%   |
| en_CA | 4         | 1.69%   |
| es_MX | 3         | 1.27%   |
| tr_TR | 2         | 0.85%   |
| sv_SE | 2         | 0.85%   |
| ko_KR | 2         | 0.85%   |
| fr_CA | 2         | 0.85%   |
| es_BO | 2         | 0.85%   |
| en_IE | 2         | 0.85%   |
| da_DK | 2         | 0.85%   |
| cs_CZ | 2         | 0.85%   |
| sk_SK | 1         | 0.42%   |
| pt_PT | 1         | 0.42%   |
| nn_NO | 1         | 0.42%   |
| nl_AW | 1         | 0.42%   |
| it_CH | 1         | 0.42%   |
| hu_HU | 1         | 0.42%   |
| fr_BE | 1         | 0.42%   |
| es_VE | 1         | 0.42%   |
| es_PE | 1         | 0.42%   |
| es_NI | 1         | 0.42%   |
| es_EC | 1         | 0.42%   |
| es_CR | 1         | 0.42%   |
| en_ZA | 1         | 0.42%   |
| en_NZ | 1         | 0.42%   |
| en_IN | 1         | 0.42%   |
| en_AU | 1         | 0.42%   |
| de_CH | 1         | 0.42%   |
| de_AT | 1         | 0.42%   |
| ar_EG | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 141       | 59.75%  |
| BIOS | 95        | 40.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 215       | 91.49%  |
| Tmpfs   | 6         | 2.55%   |
| Overlay | 6         | 2.55%   |
| Btrfs   | 6         | 2.55%   |
| Xfs     | 2         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 62.45%  |
| GPT     | 64        | 27%     |
| MBR     | 25        | 10.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 219       | 92.8%   |
| Yes       | 17        | 7.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 210       | 89.36%  |
| Yes       | 25        | 10.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 46        | 19.57%  |
| Lenovo              | 33        | 14.04%  |
| Dell                | 33        | 14.04%  |
| ASUSTek Computer    | 33        | 14.04%  |
| Acer                | 18        | 7.66%   |
| MSI                 | 12        | 5.11%   |
| Apple               | 9         | 3.83%   |
| Gigabyte Technology | 8         | 3.4%    |
| Toshiba             | 3         | 1.28%   |
| Sony                | 3         | 1.28%   |
| Samsung Electronics | 3         | 1.28%   |
| Fujitsu             | 3         | 1.28%   |
| ASRock              | 3         | 1.28%   |
| Medion              | 2         | 0.85%   |
| Google              | 2         | 0.85%   |
| Unknown             | 2         | 0.85%   |
| Wortmann AG         | 1         | 0.43%   |
| TUXEDO              | 1         | 0.43%   |
| SiYW                | 1         | 0.43%   |
| Philco              | 1         | 0.43%   |
| Pegatron            | 1         | 0.43%   |
| Panasonic           | 1         | 0.43%   |
| Packard Bell        | 1         | 0.43%   |
| Multilaser          | 1         | 0.43%   |
| Microtech           | 1         | 0.43%   |
| LincPlus            | 1         | 0.43%   |
| Kruger&Matz         | 1         | 0.43%   |
| Intel               | 1         | 0.43%   |
| Howard Computers    | 1         | 0.43%   |
| Gateway             | 1         | 0.43%   |
| Framework           | 1         | 0.43%   |
| eMachines           | 1         | 0.43%   |
| Dynabook            | 1         | 0.43%   |
| Dixonsxp            | 1         | 0.43%   |
| Digiboard           | 1         | 0.43%   |
| AZW                 | 1         | 0.43%   |
| AMI                 | 1         | 0.43%   |
| Alienware           | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 4         | 1.7%    |
| Lenovo IdeaPad 3 15ADA05 81W1       | 2         | 0.85%   |
| Lenovo G500 20236                   | 2         | 0.85%   |
| HP Notebook                         | 2         | 0.85%   |
| HP Laptop 15z-ef2xxx                | 2         | 0.85%   |
| HP Laptop 15-dw3xxx                 | 2         | 0.85%   |
| Dell Latitude E6400                 | 2         | 0.85%   |
| Dell Latitude E5540                 | 2         | 0.85%   |
| ASUS PRIME B350M-A                  | 2         | 0.85%   |
| Acer Aspire E1-570G                 | 2         | 0.85%   |
| Acer Aspire 5930                    | 2         | 0.85%   |
| Wortmann AG TERRA_MOBILE_1713A      | 1         | 0.43%   |
| TUXEDO N8xxEZ                       | 1         | 0.43%   |
| Toshiba Satellite M55               | 1         | 0.43%   |
| Toshiba Satellite L855D             | 1         | 0.43%   |
| Toshiba Satellite L455              | 1         | 0.43%   |
| Sony SVF1532W4E                     | 1         | 0.43%   |
| Sony SVE1713Y1RB                    | 1         | 0.43%   |
| Sony SVE1512G1RW                    | 1         | 0.43%   |
| SiYW V200 Series                    | 1         | 0.43%   |
| Samsung DeskTop System              | 1         | 0.43%   |
| Samsung 730QDA                      | 1         | 0.43%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.43%   |
| Philco 10D                          | 1         | 0.43%   |
| Pegatron Pro 3015 Microtower PC     | 1         | 0.43%   |
| Panasonic CF-H2BJJHZDE              | 1         | 0.43%   |
| Packard Bell DOT S                  | 1         | 0.43%   |
| Multilaser PC150                    | 1         | 0.43%   |
| MSI U180                            | 1         | 0.43%   |
| MSI MS-7D54                         | 1         | 0.43%   |
| MSI MS-7C52                         | 1         | 0.43%   |
| MSI MS-7B79                         | 1         | 0.43%   |
| MSI MS-7B23                         | 1         | 0.43%   |
| MSI MS-7B17                         | 1         | 0.43%   |
| MSI MS-7A40                         | 1         | 0.43%   |
| MSI MS-7984                         | 1         | 0.43%   |
| MSI MS-7977                         | 1         | 0.43%   |
| MSI MS-7974                         | 1         | 0.43%   |
| MSI MS-7851                         | 1         | 0.43%   |
| MSI GL73 8SE                        | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 14        | 5.96%   |
| Lenovo ThinkPad        | 10        | 4.26%   |
| HP Laptop              | 10        | 4.26%   |
| Dell Latitude          | 9         | 3.83%   |
| Lenovo IdeaPad         | 8         | 3.4%    |
| Dell Inspiron          | 8         | 3.4%    |
| HP EliteBook           | 6         | 2.55%   |
| ASUS PRIME             | 6         | 2.55%   |
| HP Pavilion            | 5         | 2.13%   |
| ASUS VivoBook          | 5         | 2.13%   |
| Dell Vostro            | 4         | 1.7%    |
| Dell Precision         | 4         | 1.7%    |
| Unknown                | 4         | 1.7%    |
| Toshiba Satellite      | 3         | 1.28%   |
| HP ProBook             | 3         | 1.28%   |
| HP Compaq              | 3         | 1.28%   |
| Dell XPS               | 3         | 1.28%   |
| Dell OptiPlex          | 3         | 1.28%   |
| ASUS ROG               | 3         | 1.28%   |
| Lenovo Yoga            | 2         | 0.85%   |
| Lenovo ThinkCentre     | 2         | 0.85%   |
| Lenovo Legion          | 2         | 0.85%   |
| Lenovo G500            | 2         | 0.85%   |
| HP ZBook               | 2         | 0.85%   |
| HP Notebook            | 2         | 0.85%   |
| HP 255                 | 2         | 0.85%   |
| Gigabyte B450          | 2         | 0.85%   |
| Wortmann AG TERRA      | 1         | 0.43%   |
| TUXEDO N8xxEZ          | 1         | 0.43%   |
| Sony SVF1532W4E        | 1         | 0.43%   |
| Sony SVE1713Y1RB       | 1         | 0.43%   |
| Sony SVE1512G1RW       | 1         | 0.43%   |
| SiYW V200              | 1         | 0.43%   |
| Samsung DeskTop        | 1         | 0.43%   |
| Samsung 730QDA         | 1         | 0.43%   |
| Samsung 355V4C         | 1         | 0.43%   |
| Philco 10D             | 1         | 0.43%   |
| Pegatron Pro           | 1         | 0.43%   |
| Panasonic CF-H2BJJHZDE | 1         | 0.43%   |
| Packard Bell DOT       | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 28        | 11.91%  |
| 2012 | 24        | 10.21%  |
| 2018 | 22        | 9.36%   |
| 2020 | 20        | 8.51%   |
| 2013 | 18        | 7.66%   |
| 2019 | 15        | 6.38%   |
| 2017 | 14        | 5.96%   |
| 2010 | 14        | 5.96%   |
| 2015 | 13        | 5.53%   |
| 2009 | 13        | 5.53%   |
| 2016 | 10        | 4.26%   |
| 2022 | 9         | 3.83%   |
| 2011 | 9         | 3.83%   |
| 2014 | 7         | 2.98%   |
| 2008 | 7         | 2.98%   |
| 2007 | 7         | 2.98%   |
| 2006 | 5         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 153       | 65.11%  |
| Desktop     | 71        | 30.21%  |
| Convertible | 4         | 1.7%    |
| All in one  | 3         | 1.28%   |
| Tablet      | 2         | 0.85%   |
| Mini pc     | 2         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 215       | 90.72%  |
| Enabled  | 22        | 9.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 232       | 98.72%  |
| Yes  | 3         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 26.69%  |
| 16.01-24.0  | 45        | 19.07%  |
| 8.01-16.0   | 43        | 18.22%  |
| 3.01-4.0    | 42        | 17.8%   |
| 32.01-64.0  | 15        | 6.36%   |
| 1.01-2.0    | 13        | 5.51%   |
| 2.01-3.0    | 7         | 2.97%   |
| 64.01-256.0 | 4         | 1.69%   |
| 24.01-32.0  | 3         | 1.27%   |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 99        | 40.57%  |
| 2.01-3.0   | 79        | 32.38%  |
| 3.01-4.0   | 26        | 10.66%  |
| 4.01-8.0   | 23        | 9.43%   |
| 0.51-1.0   | 13        | 5.33%   |
| 8.01-16.0  | 3         | 1.23%   |
| 32.01-64.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 159       | 66.81%  |
| 2      | 50        | 21.01%  |
| 3      | 18        | 7.56%   |
| 4      | 6         | 2.52%   |
| 5      | 3         | 1.26%   |
| 6      | 2         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 62.98%  |
| Yes       | 87        | 37.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 82.98%  |
| No        | 40        | 17.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 81.28%  |
| No        | 44        | 18.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 60%     |
| No        | 94        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 44        | 18.57%  |
| Germany      | 34        | 14.35%  |
| Russia       | 23        | 9.7%    |
| Brazil       | 16        | 6.75%   |
| Italy        | 14        | 5.91%   |
| France       | 14        | 5.91%   |
| UK           | 11        | 4.64%   |
| Canada       | 9         | 3.8%    |
| Poland       | 8         | 3.38%   |
| Spain        | 7         | 2.95%   |
| Sweden       | 4         | 1.69%   |
| Mexico       | 4         | 1.69%   |
| Turkey       | 3         | 1.27%   |
| Belgium      | 3         | 1.27%   |
| Vietnam      | 2         | 0.84%   |
| Venezuela    | 2         | 0.84%   |
| South Korea  | 2         | 0.84%   |
| Romania      | 2         | 0.84%   |
| Portugal     | 2         | 0.84%   |
| Hungary      | 2         | 0.84%   |
| Denmark      | 2         | 0.84%   |
| Chile        | 2         | 0.84%   |
| Bolivia      | 2         | 0.84%   |
| Belarus      | 2         | 0.84%   |
| Austria      | 2         | 0.84%   |
| Australia    | 2         | 0.84%   |
| South Africa | 1         | 0.42%   |
| Slovenia     | 1         | 0.42%   |
| Slovakia     | 1         | 0.42%   |
| Peru         | 1         | 0.42%   |
| Paraguay     | 1         | 0.42%   |
| Norway       | 1         | 0.42%   |
| Nicaragua    | 1         | 0.42%   |
| New Zealand  | 1         | 0.42%   |
| Malaysia     | 1         | 0.42%   |
| Lithuania    | 1         | 0.42%   |
| Latvia       | 1         | 0.42%   |
| Kenya        | 1         | 0.42%   |
| Ireland      | 1         | 0.42%   |
| India        | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 6         | 2.5%    |
| Berlin                | 4         | 1.67%   |
| Rome                  | 3         | 1.25%   |
| Krakow                | 3         | 1.25%   |
| Frankfurt am Main     | 3         | 1.25%   |
| St Petersburg         | 2         | 0.83%   |
| Oruro                 | 2         | 0.83%   |
| Neasden               | 2         | 0.83%   |
| Munich                | 2         | 0.83%   |
| Montreal              | 2         | 0.83%   |
| Melbourne             | 2         | 0.83%   |
| London                | 2         | 0.83%   |
| Freiburg im Breisgau  | 2         | 0.83%   |
| Bend                  | 2         | 0.83%   |
| Belém                | 2         | 0.83%   |
| Zaragoza              | 1         | 0.42%   |
| Wroclaw               | 1         | 0.42%   |
| Weimar                | 1         | 0.42%   |
| Washington            | 1         | 0.42%   |
| Voronezh              | 1         | 0.42%   |
| Volta Redonda         | 1         | 0.42%   |
| Vitória da Conquista | 1         | 0.42%   |
| Vincennes             | 1         | 0.42%   |
| Vilshofen             | 1         | 0.42%   |
| Vilnius               | 1         | 0.42%   |
| Villeneuve-d'Ascq     | 1         | 0.42%   |
| Viggianello           | 1         | 0.42%   |
| Viet Tri              | 1         | 0.42%   |
| Vicente Guerrero      | 1         | 0.42%   |
| Veurne                | 1         | 0.42%   |
| Vaslui                | 1         | 0.42%   |
| Vancouver             | 1         | 0.42%   |
| Valsoyfjord           | 1         | 0.42%   |
| Ulyanovsk             | 1         | 0.42%   |
| Uiwang                | 1         | 0.42%   |
| Turku                 | 1         | 0.42%   |
| Tula                  | 1         | 0.42%   |
| Troisdorf             | 1         | 0.42%   |
| Trieste               | 1         | 0.42%   |
| Toulouse              | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 51        | 65     | 15.69%  |
| Seagate                        | 45        | 57     | 13.85%  |
| Samsung Electronics            | 41        | 56     | 12.62%  |
| SanDisk                        | 22        | 25     | 6.77%   |
| Kingston                       | 20        | 21     | 6.15%   |
| Unknown                        | 16        | 21     | 4.92%   |
| Toshiba                        | 12        | 13     | 3.69%   |
| Hitachi                        | 12        | 13     | 3.69%   |
| Crucial                        | 12        | 13     | 3.69%   |
| SK hynix                       | 8         | 9      | 2.46%   |
| Intel                          | 7         | 7      | 2.15%   |
| Micron Technology              | 6         | 6      | 1.85%   |
| Apple                          | 6         | 11     | 1.85%   |
| China                          | 5         | 6      | 1.54%   |
| A-DATA Technology              | 5         | 6      | 1.54%   |
| PNY                            | 4         | 5      | 1.23%   |
| Patriot                        | 3         | 3      | 0.92%   |
| HGST                           | 3         | 3      | 0.92%   |
| Unknown                        | 3         | 4      | 0.92%   |
| Team                           | 2         | 2      | 0.62%   |
| SPCC                           | 2         | 2      | 0.62%   |
| Phison                         | 2         | 2      | 0.62%   |
| KIOXIA                         | 2         | 5      | 0.62%   |
| KingSpec                       | 2         | 2      | 0.62%   |
| Intenso                        | 2         | 2      | 0.62%   |
| Gigabyte Technology            | 2         | 4      | 0.62%   |
| XrayDisk                       | 1         | 2      | 0.31%   |
| Union Memory                   | 1         | 1      | 0.31%   |
| UMIS                           | 1         | 1      | 0.31%   |
| Transcend                      | 1         | 2      | 0.31%   |
| SSD PHIS                       | 1         | 1      | 0.31%   |
| Solid State Storage Technology | 1         | 1      | 0.31%   |
| ShiJi                          | 1         | 1      | 0.31%   |
| SABRENT                        | 1         | 1      | 0.31%   |
| Phison Electronics             | 1         | 1      | 0.31%   |
| Oyen                           | 1         | 1      | 0.31%   |
| ORICO                          | 1         | 1      | 0.31%   |
| OCZ-VERTEX                     | 1         | 1      | 0.31%   |
| Netac                          | 1         | 1      | 0.31%   |
| Microtech                      | 1         | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 6         | 1.71%   |
| Samsung SSD 850 EVO 250GB               | 6         | 1.71%   |
| Samsung SSD 850 EVO 500GB               | 5         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 1.14%   |
| Kingston SA400S37480G 480GB SSD         | 4         | 1.14%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 1.14%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 1.14%   |
| Unknown SD/MMC/MS PRO 64GB              | 3         | 0.86%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 0.86%   |
| Micron NVMe SSD Drive 512GB             | 3         | 0.86%   |
| Crucial CT480BX500SSD1 480GB            | 3         | 0.86%   |
| Unknown                                 | 3         | 0.86%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 0.57%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 2         | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 0.57%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 2         | 0.57%   |
| Unknown SC128  128GB                    | 2         | 0.57%   |
| Unknown MMC Card  64GB                  | 2         | 0.57%   |
| Unknown MMC Card  32GB                  | 2         | 0.57%   |
| Unknown MMC Card  128GB                 | 2         | 0.57%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.57%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.57%   |
| Seagate ST3320418AS 320GB               | 2         | 0.57%   |
| Seagate ST3250318AS 250GB               | 2         | 0.57%   |
| Seagate ST2000LX001-1RG174 2TB          | 2         | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB    | 2         | 0.57%   |
| SanDisk SDSSDA240G 240GB                | 2         | 0.57%   |
| Samsung SSD 980 PRO 1TB                 | 2         | 0.57%   |
| Samsung SSD 980 1TB                     | 2         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.57%   |
| Samsung SSD 970 EVO 500GB               | 2         | 0.57%   |
| Samsung PM991a NVMe 512GB               | 2         | 0.57%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 0.57%   |
| Samsung NVMe SSD Drive 250GB            | 2         | 0.57%   |
| Patriot Burst 240GB SSD                 | 2         | 0.57%   |
| Intenso External USB 3.0 1TB            | 2         | 0.57%   |
| Crucial CT525MX300SSD1 528GB            | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 56     | 36.89%  |
| WDC                 | 41        | 54     | 33.61%  |
| Hitachi             | 12        | 13     | 9.84%   |
| Toshiba             | 9         | 10     | 7.38%   |
| Samsung Electronics | 4         | 4      | 3.28%   |
| Unknown             | 3         | 3      | 2.46%   |
| HGST                | 3         | 3      | 2.46%   |
| Intenso             | 2         | 2      | 1.64%   |
| Initio              | 1         | 1      | 0.82%   |
| Fujitsu             | 1         | 1      | 0.82%   |
| ASMedia             | 1         | 1      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 25     | 15.52%  |
| Kingston            | 17        | 18     | 14.66%  |
| Crucial             | 12        | 13     | 10.34%  |
| SanDisk             | 10        | 10     | 8.62%   |
| China               | 5         | 6      | 4.31%   |
| Apple               | 5         | 5      | 4.31%   |
| A-DATA Technology   | 5         | 6      | 4.31%   |
| WDC                 | 4         | 4      | 3.45%   |
| PNY                 | 4         | 5      | 3.45%   |
| Patriot             | 3         | 3      | 2.59%   |
| Intel               | 3         | 3      | 2.59%   |
| Unknown             | 3         | 4      | 2.59%   |
| Toshiba             | 2         | 2      | 1.72%   |
| Team                | 2         | 2      | 1.72%   |
| KingSpec            | 2         | 2      | 1.72%   |
| Gigabyte Technology | 2         | 4      | 1.72%   |
| Transcend           | 1         | 2      | 0.86%   |
| SSD PHIS            | 1         | 1      | 0.86%   |
| SPCC                | 1         | 1      | 0.86%   |
| SK hynix            | 1         | 1      | 0.86%   |
| ORICO               | 1         | 1      | 0.86%   |
| OCZ-VERTEX          | 1         | 1      | 0.86%   |
| Netac               | 1         | 1      | 0.86%   |
| Microtech           | 1         | 2      | 0.86%   |
| Micron Technology   | 1         | 1      | 0.86%   |
| LITEON              | 1         | 1      | 0.86%   |
| HXY                 | 1         | 1      | 0.86%   |
| Hewlett-Packard     | 1         | 1      | 0.86%   |
| GOODRAM             | 1         | 1      | 0.86%   |
| FORESEE             | 1         | 1      | 0.86%   |
| Corsair             | 1         | 1      | 0.86%   |
| BHT                 | 1         | 2      | 0.86%   |
| Apacer              | 1         | 1      | 0.86%   |
| Acer                | 1         | 1      | 0.86%   |
| 2.5''               | 1         | 1      | 0.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 148    | 36.42%  |
| SSD     | 105       | 134    | 34.77%  |
| NVMe    | 67        | 90     | 22.19%  |
| MMC     | 13        | 17     | 4.3%    |
| Unknown | 7         | 9      | 2.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 177       | 271    | 65.8%   |
| NVMe | 66        | 89     | 24.54%  |
| SAS  | 13        | 21     | 4.83%   |
| MMC  | 13        | 17     | 4.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 135       | 181    | 64.29%  |
| 0.51-1.0   | 55        | 76     | 26.19%  |
| 1.01-2.0   | 10        | 12     | 4.76%   |
| 2.01-3.0   | 4         | 7      | 1.9%    |
| 4.01-10.0  | 4         | 4      | 1.9%    |
| 3.01-4.0   | 2         | 2      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 29.83%  |
| 251-500        | 58        | 24.37%  |
| 501-1000       | 31        | 13.03%  |
| 1001-2000      | 24        | 10.08%  |
| 51-100         | 16        | 6.72%   |
| 1-20           | 11        | 4.62%   |
| More than 3000 | 10        | 4.2%    |
| 21-50          | 9         | 3.78%   |
| 2001-3000      | 8         | 3.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 109       | 44.67%  |
| 21-50          | 45        | 18.44%  |
| 51-100         | 26        | 10.66%  |
| 101-250        | 19        | 7.79%   |
| 501-1000       | 17        | 6.97%   |
| 251-500        | 16        | 6.56%   |
| 1001-2000      | 6         | 2.46%   |
| More than 3000 | 3         | 1.23%   |
| 2001-3000      | 3         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 6.67%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 6.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 6.67%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 6.67%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 6.67%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 6.67%   |
| Phison ES 512GB                       | 1         | 1      | 6.67%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 6.67%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 28.57%  |
| Samsung Electronics | 3         | 3      | 21.43%  |
| WDC                 | 1         | 2      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| SK hynix            | 1         | 1      | 7.14%   |
| Phison              | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 50%     |
| WDC                 | 1         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 57.14%  |
| NVMe | 3         | 3      | 21.43%  |
| SSD  | 3         | 3      | 21.43%  |

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
| Detected | 160       | 263    | 62.75%  |
| Works    | 81        | 120    | 31.76%  |
| Malfunc  | 14        | 15     | 5.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 161       | 55.71%  |
| AMD                            | 45        | 15.57%  |
| Samsung Electronics            | 23        | 7.96%   |
| SanDisk                        | 15        | 5.19%   |
| SK hynix                       | 7         | 2.42%   |
| Micron Technology              | 5         | 1.73%   |
| Phison Electronics             | 4         | 1.38%   |
| Nvidia                         | 4         | 1.38%   |
| Marvell Technology Group       | 3         | 1.04%   |
| KIOXIA                         | 3         | 1.04%   |
| Kingston Technology Company    | 3         | 1.04%   |
| JMicron Technology             | 3         | 1.04%   |
| ASMedia Technology             | 3         | 1.04%   |
| Union Memory (Shenzhen)        | 2         | 0.69%   |
| Broadcom / LSI                 | 2         | 0.69%   |
| Toshiba America Info Systems   | 1         | 0.35%   |
| Solid State Storage Technology | 1         | 0.35%   |
| Micron/Crucial Technology      | 1         | 0.35%   |
| LSI Logic / Symbios Logic      | 1         | 0.35%   |
| Apple                          | 1         | 0.35%   |
| ADATA Technology               | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 10.18%  |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 4.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 3.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 3.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 3.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 2.99%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 2.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 2.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.1%    |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 2.1%    |
| SanDisk Non-Volatile memory controller                                         | 6         | 1.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 6         | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.8%    |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.8%    |
| Micron Non-Volatile memory controller                                          | 5         | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.5%    |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 4         | 1.2%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.9%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                             | 3         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.9%    |
| AMD FCH SATA Controller D                                                      | 3         | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.9%    |
| SK hynix BC511                                                                 | 2         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 173       | 57.1%   |
| NVMe | 67        | 22.11%  |
| IDE  | 31        | 10.23%  |
| RAID | 30        | 9.9%    |
| SAS  | 1         | 0.33%   |
| SCSI | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 179       | 76.17%  |
| AMD    | 56        | 23.83%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 9         | 3.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 6         | 2.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 2.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 1.7%    |
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 1.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 1.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.28%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2         | 0.85%   |
| Intel Pentium M processor 1.73GHz           | 2         | 0.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.85%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 0.85%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 0.85%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.85%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 0.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 0.85%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2         | 0.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 0.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 0.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 0.85%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 0.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 0.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 0.85%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 0.85%   |
| AMD Ryzen 5 5600H with Radeon Graphics      | 2         | 0.85%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2         | 0.85%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 2         | 0.85%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2         | 0.85%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 0.85%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.43%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1         | 0.43%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.43%   |
| Intel Xeon CPU 3.40GHz                      | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 20.43%  |
| Intel Core i7           | 32        | 13.62%  |
| Other                   | 20        | 8.51%   |
| Intel Core i3           | 15        | 6.38%   |
| AMD Ryzen 5             | 14        | 5.96%   |
| Intel Celeron           | 13        | 5.53%   |
| AMD Ryzen 7             | 11        | 4.68%   |
| Intel Core 2 Duo        | 10        | 4.26%   |
| Intel Atom              | 8         | 3.4%    |
| Intel Pentium           | 7         | 2.98%   |
| AMD Ryzen 3             | 7         | 2.98%   |
| Intel Xeon              | 6         | 2.55%   |
| Intel Pentium Dual-Core | 3         | 1.28%   |
| Intel Core 2 Quad       | 3         | 1.28%   |
| Intel Core 2            | 3         | 1.28%   |
| Intel Pentium Silver    | 2         | 0.85%   |
| Intel Pentium M         | 2         | 0.85%   |
| Intel Pentium Gold      | 2         | 0.85%   |
| Intel Pentium D         | 2         | 0.85%   |
| Intel Celeron M         | 2         | 0.85%   |
| AMD Ryzen 9             | 2         | 0.85%   |
| AMD FX                  | 2         | 0.85%   |
| AMD E2                  | 2         | 0.85%   |
| AMD E1                  | 2         | 0.85%   |
| AMD Athlon II X2        | 2         | 0.85%   |
| AMD Athlon              | 2         | 0.85%   |
| AMD A4                  | 2         | 0.85%   |
| AMD A10                 | 2         | 0.85%   |
| Intel Core i9           | 1         | 0.43%   |
| Intel Core 2 Extreme    | 1         | 0.43%   |
| AMD Phenom II X6        | 1         | 0.43%   |
| AMD Phenom II X4        | 1         | 0.43%   |
| AMD G                   | 1         | 0.43%   |
| AMD C-50                | 1         | 0.43%   |
| AMD Athlon II           | 1         | 0.43%   |
| AMD A8                  | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 108       | 45.96%  |
| 4      | 84        | 35.74%  |
| 6      | 17        | 7.23%   |
| 8      | 16        | 6.81%   |
| 1      | 7         | 2.98%   |
| 16     | 3         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 231       | 98.3%   |
| 2      | 4         | 1.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 150       | 63.83%  |
| 1      | 85        | 36.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 229       | 97.45%  |
| 32-bit         | 6         | 2.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 23        | 9.62%   |
| 0x806c1    | 17        | 7.11%   |
| 0x206a7    | 11        | 4.6%    |
| 0x08108109 | 11        | 4.6%    |
| Unknown    | 10        | 4.18%   |
| 0x1067a    | 9         | 3.77%   |
| 0x40651    | 8         | 3.35%   |
| 0x306c3    | 7         | 2.93%   |
| 0x806ec    | 6         | 2.51%   |
| 0x506e3    | 6         | 2.51%   |
| 0x406e3    | 6         | 2.51%   |
| 0x08608103 | 6         | 2.51%   |
| 0x806ea    | 5         | 2.09%   |
| 0x806e9    | 5         | 2.09%   |
| 0x406c4    | 5         | 2.09%   |
| 0x106e5    | 5         | 2.09%   |
| 0x906ea    | 4         | 1.67%   |
| 0x6fd      | 4         | 1.67%   |
| 0x30661    | 4         | 1.67%   |
| 0x0a50000c | 4         | 1.67%   |
| 0x906ed    | 3         | 1.26%   |
| 0x906c0    | 3         | 1.26%   |
| 0x706a1    | 3         | 1.26%   |
| 0x6f6      | 3         | 1.26%   |
| 0x20652    | 3         | 1.26%   |
| 0x10676    | 3         | 1.26%   |
| 0x06006705 | 3         | 1.26%   |
| 0x010000c8 | 3         | 1.26%   |
| 0xa0652    | 2         | 0.84%   |
| 0x90675    | 2         | 0.84%   |
| 0x806eb    | 2         | 0.84%   |
| 0x706e5    | 2         | 0.84%   |
| 0x6d8      | 2         | 0.84%   |
| 0x206d7    | 2         | 0.84%   |
| 0x106c2    | 2         | 0.84%   |
| 0x08701021 | 2         | 0.84%   |
| 0x08101016 | 2         | 0.84%   |
| 0x06001119 | 2         | 0.84%   |
| 0xf65      | 1         | 0.42%   |
| 0xf47      | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 11.02%  |
| IvyBridge     | 24        | 10.17%  |
| TigerLake     | 17        | 7.2%    |
| Haswell       | 15        | 6.36%   |
| Zen+          | 13        | 5.51%   |
| SandyBridge   | 13        | 5.51%   |
| Skylake       | 12        | 5.08%   |
| Penryn        | 12        | 5.08%   |
| Unknown       | 11        | 4.66%   |
| Core          | 9         | 3.81%   |
| Zen 3         | 8         | 3.39%   |
| Silvermont    | 7         | 2.97%   |
| Bonnell       | 7         | 2.97%   |
| Westmere      | 6         | 2.54%   |
| Nehalem       | 6         | 2.54%   |
| Zen           | 5         | 2.12%   |
| K10           | 5         | 2.12%   |
| Excavator     | 5         | 2.12%   |
| Goldmont plus | 4         | 1.69%   |
| Zen 2         | 3         | 1.27%   |
| Tremont       | 3         | 1.27%   |
| Piledriver    | 3         | 1.27%   |
| P6            | 3         | 1.27%   |
| NetBurst      | 3         | 1.27%   |
| Icelake       | 3         | 1.27%   |
| CometLake     | 3         | 1.27%   |
| Puma          | 2         | 0.85%   |
| Jaguar        | 2         | 0.85%   |
| Broadwell     | 2         | 0.85%   |
| Bobcat        | 2         | 0.85%   |
| Goldmont      | 1         | 0.42%   |
| Bulldozer     | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 131       | 48.16%  |
| Nvidia | 82        | 30.15%  |
| AMD    | 59        | 21.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 4.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 2.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.14%   |
| AMD Lucienne                                                                             | 6         | 2.14%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.42%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.42%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.42%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.42%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.42%   |
| Intel HD Graphics 620                                                                    | 4         | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.42%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.42%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.07%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.07%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 1.07%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.07%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.07%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.07%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.07%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.71%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.71%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.71%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.71%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 42.62%  |
| 1 x Nvidia     | 52        | 21.94%  |
| 1 x AMD        | 45        | 18.99%  |
| Intel + Nvidia | 25        | 10.55%  |
| AMD + Nvidia   | 6         | 2.53%   |
| 2 x AMD        | 4         | 1.69%   |
| Intel + AMD    | 4         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 198       | 83.54%  |
| Proprietary | 26        | 10.97%  |
| Unknown     | 13        | 5.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 50.21%  |
| 0.01-0.5   | 41        | 17.15%  |
| 1.01-2.0   | 39        | 16.32%  |
| 3.01-4.0   | 16        | 6.69%   |
| 0.51-1.0   | 14        | 5.86%   |
| 5.01-6.0   | 4         | 1.67%   |
| 7.01-8.0   | 2         | 0.84%   |
| 2.01-3.0   | 2         | 0.84%   |
| 8.01-16.0  | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 14.77%  |
| BOE                     | 26        | 10.97%  |
| LG Display              | 25        | 10.55%  |
| Chimei Innolux          | 25        | 10.55%  |
| Samsung Electronics     | 18        | 7.59%   |
| Goldstar                | 10        | 4.22%   |
| Apple                   | 9         | 3.8%    |
| Acer                    | 9         | 3.8%    |
| Dell                    | 8         | 3.38%   |
| Philips                 | 6         | 2.53%   |
| Hewlett-Packard         | 6         | 2.53%   |
| BenQ                    | 6         | 2.53%   |
| LG Philips              | 5         | 2.11%   |
| Lenovo                  | 4         | 1.69%   |
| InfoVision              | 4         | 1.69%   |
| HannStar                | 4         | 1.69%   |
| Chi Mei Optoelectronics | 4         | 1.69%   |
| Unknown                 | 3         | 1.27%   |
| AOC                     | 3         | 1.27%   |
| Ancor Communications    | 3         | 1.27%   |
| Sharp                   | 2         | 0.84%   |
| PANDA                   | 2         | 0.84%   |
| Insignia                | 2         | 0.84%   |
| Iiyama                  | 2         | 0.84%   |
| ___                     | 1         | 0.42%   |
| ViewSonic               | 1         | 0.42%   |
| Vestel Elektronik       | 1         | 0.42%   |
| TR_                     | 1         | 0.42%   |
| Sony                    | 1         | 0.42%   |
| SKY                     | 1         | 0.42%   |
| Quanta Display          | 1         | 0.42%   |
| PLN                     | 1         | 0.42%   |
| Planar                  | 1         | 0.42%   |
| Packard Bell            | 1         | 0.42%   |
| MStar                   | 1         | 0.42%   |
| Medion                  | 1         | 0.42%   |
| Lenovo Group Limited    | 1         | 0.42%   |
| DENON                   | 1         | 0.42%   |
| ASUSTek Computer        | 1         | 0.42%   |
| Unknown                 | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.23%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 2         | 0.82%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 0.82%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.82%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 0.82%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 2         | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 0.82%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1         | 0.41%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch              | 1         | 0.41%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 1         | 0.41%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                    | 1         | 0.41%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                  | 1         | 0.41%   |
| Unknown LCD Monitor SAMSUNG                                           | 1         | 0.41%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.41%   |
| Sony LCD Monitor TV 3840x1080                                         | 1         | 0.41%   |
| SKY TV-monitor SKY1402 3840x2160 708x398mm 32.0-inch                  | 1         | 0.41%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                         | 1         | 0.41%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.41%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.41%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 99        | 43.42%  |
| 1366x768 (WXGA)    | 48        | 21.05%  |
| 1600x900 (HD+)     | 12        | 5.26%   |
| 1920x1200 (WUXGA)  | 9         | 3.95%   |
| 1680x1050 (WSXGA+) | 8         | 3.51%   |
| 1440x900 (WXGA+)   | 7         | 3.07%   |
| 1280x800 (WXGA)    | 7         | 3.07%   |
| 3840x2160 (4K)     | 6         | 2.63%   |
| 1024x600           | 5         | 2.19%   |
| 2560x1440 (QHD)    | 4         | 1.75%   |
| 1280x1024 (SXGA)   | 4         | 1.75%   |
| Unknown            | 3         | 1.32%   |
| 3840x1080          | 2         | 0.88%   |
| 3440x1440          | 2         | 0.88%   |
| 2880x1800          | 2         | 0.88%   |
| 2560x1080          | 2         | 0.88%   |
| 1360x768           | 2         | 0.88%   |
| 4480x1440          | 1         | 0.44%   |
| 2560x1600          | 1         | 0.44%   |
| 2256x1504          | 1         | 0.44%   |
| 1280x768           | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |
| 1024x768 (XGA)     | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 80        | 33.76%  |
| 13      | 25        | 10.55%  |
| 14      | 18        | 7.59%   |
| Unknown | 18        | 7.59%   |
| 17      | 15        | 6.33%   |
| 24      | 13        | 5.49%   |
| 21      | 11        | 4.64%   |
| 27      | 10        | 4.22%   |
| 23      | 8         | 3.38%   |
| 10      | 5         | 2.11%   |
| 22      | 4         | 1.69%   |
| 20      | 4         | 1.69%   |
| 19      | 3         | 1.27%   |
| 12      | 3         | 1.27%   |
| 11      | 3         | 1.27%   |
| 72      | 2         | 0.84%   |
| 34      | 2         | 0.84%   |
| 32      | 2         | 0.84%   |
| 31      | 2         | 0.84%   |
| 18      | 2         | 0.84%   |
| 84      | 1         | 0.42%   |
| 52      | 1         | 0.42%   |
| 33      | 1         | 0.42%   |
| 28      | 1         | 0.42%   |
| 25      | 1         | 0.42%   |
| 16      | 1         | 0.42%   |
| 8       | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 48.26%  |
| 501-600     | 30        | 13.04%  |
| 201-300     | 22        | 9.57%   |
| 401-500     | 19        | 8.26%   |
| Unknown     | 18        | 7.83%   |
| 351-400     | 17        | 7.39%   |
| 701-800     | 5         | 2.17%   |
| 601-700     | 3         | 1.3%    |
| 1501-2000   | 3         | 1.3%    |
| 101-200     | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 160       | 74.07%  |
| 16/10   | 30        | 13.89%  |
| Unknown | 16        | 7.41%   |
| 5/4     | 4         | 1.85%   |
| 21/9    | 4         | 1.85%   |
| 4/3     | 1         | 0.46%   |
| 3/2     | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 33.9%   |
| 81-90          | 33        | 13.98%  |
| 201-250        | 30        | 12.71%  |
| Unknown        | 18        | 7.63%   |
| 71-80          | 10        | 4.24%   |
| 301-350        | 10        | 4.24%   |
| 121-130        | 9         | 3.81%   |
| 351-500        | 7         | 2.97%   |
| 251-300        | 7         | 2.97%   |
| 151-200        | 7         | 2.97%   |
| 41-50          | 5         | 2.12%   |
| More than 1000 | 4         | 1.69%   |
| 141-150        | 4         | 1.69%   |
| 131-140        | 4         | 1.69%   |
| 61-70          | 3         | 1.27%   |
| 51-60          | 3         | 1.27%   |
| 1-40           | 1         | 0.42%   |
| 91-100         | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 74        | 31.9%   |
| 101-120       | 67        | 28.88%  |
| 51-100        | 60        | 25.86%  |
| Unknown       | 18        | 7.76%   |
| 161-240       | 10        | 4.31%   |
| 1-50          | 2         | 0.86%   |
| More than 240 | 1         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 195       | 82.28%  |
| 2     | 27        | 11.39%  |
| 0     | 12        | 5.06%   |
| 3     | 3         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 125       | 35.92%  |
| Intel                         | 106       | 30.46%  |
| Qualcomm Atheros              | 42        | 12.07%  |
| Broadcom                      | 28        | 8.05%   |
| Ralink Technology             | 5         | 1.44%   |
| Marvell Technology Group      | 5         | 1.44%   |
| Broadcom Limited              | 5         | 1.44%   |
| Nvidia                        | 4         | 1.15%   |
| TP-Link                       | 3         | 0.86%   |
| MediaTek                      | 3         | 0.86%   |
| Xiaomi                        | 2         | 0.57%   |
| Samsung Electronics           | 2         | 0.57%   |
| Huawei Technologies           | 2         | 0.57%   |
| Ralink                        | 1         | 0.29%   |
| Qualcomm                      | 1         | 0.29%   |
| OnePlus Technology (Shenzhen) | 1         | 0.29%   |
| NetGear                       | 1         | 0.29%   |
| Microchip Technology          | 1         | 0.29%   |
| Mercucys                      | 1         | 0.29%   |
| Lenovo                        | 1         | 0.29%   |
| JMicron Technology            | 1         | 0.29%   |
| HTC (High Tech Computer)      | 1         | 0.29%   |
| Hewlett-Packard               | 1         | 0.29%   |
| Google                        | 1         | 0.29%   |
| Fibocom                       | 1         | 0.29%   |
| Edimax Technology             | 1         | 0.29%   |
| Dell                          | 1         | 0.29%   |
| Davicom Semiconductor         | 1         | 0.29%   |
| Belkin Components             | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 17.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 3.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.14%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 2.14%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.66%   |
| Intel Wireless 3165                                               | 7         | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.19%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.95%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.95%   |
| Intel Wireless 7260                                               | 4         | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.95%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.71%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.71%   |
| Intel Wireless 8260                                               | 3         | 0.71%   |
| Intel Wireless 7265                                               | 3         | 0.71%   |
| Intel WiFi Link 5100                                              | 3         | 0.71%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.71%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 38.42%  |
| Realtek Semiconductor | 52        | 25.62%  |
| Qualcomm Atheros      | 29        | 14.29%  |
| Broadcom              | 21        | 10.34%  |
| Ralink Technology     | 5         | 2.46%   |
| Broadcom Limited      | 5         | 2.46%   |
| TP-Link               | 3         | 1.48%   |
| MediaTek              | 3         | 1.48%   |
| Xiaomi                | 1         | 0.49%   |
| Ralink                | 1         | 0.49%   |
| NetGear               | 1         | 0.49%   |
| Mercucys              | 1         | 0.49%   |
| Fibocom               | 1         | 0.49%   |
| Edimax Technology     | 1         | 0.49%   |
| Belkin Components     | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 6.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 4.33%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 4.33%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.37%   |
| Intel Wireless 3165                                            | 7         | 3.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.4%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.92%   |
| Intel Wireless 7260                                            | 4         | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.44%   |
| Intel Wireless 8260                                            | 3         | 1.44%   |
| Intel Wireless 7265                                            | 3         | 1.44%   |
| Intel WiFi Link 5100                                           | 3         | 1.44%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.96%   |
| Realtek 802.11ac NIC                                           | 2         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.96%   |
| Intel Wireless-AC 9260                                         | 2         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.96%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 104       | 50%     |
| Intel                         | 54        | 25.96%  |
| Qualcomm Atheros              | 19        | 9.13%   |
| Broadcom                      | 8         | 3.85%   |
| Marvell Technology Group      | 5         | 2.4%    |
| Nvidia                        | 4         | 1.92%   |
| Samsung Electronics           | 2         | 0.96%   |
| Huawei Technologies           | 2         | 0.96%   |
| Xiaomi                        | 1         | 0.48%   |
| Qualcomm                      | 1         | 0.48%   |
| OnePlus Technology (Shenzhen) | 1         | 0.48%   |
| Microchip Technology          | 1         | 0.48%   |
| Lenovo                        | 1         | 0.48%   |
| JMicron Technology            | 1         | 0.48%   |
| HTC (High Tech Computer)      | 1         | 0.48%   |
| Hewlett-Packard               | 1         | 0.48%   |
| Google                        | 1         | 0.48%   |
| Davicom Semiconductor         | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 35.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 7.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.9%    |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.9%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 1.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.95%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.95%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.95%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.95%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.95%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.95%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.95%   |
| Huawei STK-L21                                                    | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.47%   |
| Qualcomm Android                                                  | 1         | 0.47%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.47%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.47%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 194       | 50.13%  |
| WiFi     | 191       | 49.35%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 58.02%  |
| Ethernet | 102       | 41.98%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 136       | 57.87%  |
| 1     | 93        | 39.57%  |
| 0     | 6         | 2.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 72.03%  |
| Yes  | 66        | 27.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 43.36%  |
| Realtek Semiconductor           | 28        | 19.58%  |
| Foxconn / Hon Hai               | 8         | 5.59%   |
| Broadcom                        | 7         | 4.9%    |
| Apple                           | 7         | 4.9%    |
| Qualcomm Atheros Communications | 6         | 4.2%    |
| Lite-On Technology              | 6         | 4.2%    |
| Cambridge Silicon Radio         | 6         | 4.2%    |
| Hewlett-Packard                 | 4         | 2.8%    |
| Dell                            | 4         | 2.8%    |
| IMC Networks                    | 3         | 2.1%    |
| Foxconn International           | 2         | 1.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 16.78%  |
| Realtek Bluetooth Radio                                     | 20        | 13.99%  |
| Intel AX201 Bluetooth                                       | 14        | 9.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 8.39%   |
| Realtek  Bluetooth 4.2 Adapter                              | 6         | 4.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 4.2%    |
| Intel AX200 Bluetooth                                       | 5         | 3.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.1%    |
| Foxconn / Hon Hai Wireless_Device                           | 3         | 2.1%    |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.4%    |
| Lite-On Bluetooth Device                                    | 2         | 1.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.4%    |
| Intel AX210 Bluetooth                                       | 2         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.4%    |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.4%    |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.4%    |
| Apple Bluetooth USB Host Controller                         | 2         | 1.4%    |
| Apple Bluetooth Host Controller                             | 2         | 1.4%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.7%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.7%    |
| IMC Networks Bluetooth Radio                                | 1         | 0.7%    |
| IMC Networks Bluetooth Device                               | 1         | 0.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.7%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                          | 1         | 0.7%    |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.7%    |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.7%    |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.7%    |
| Dell BT Mini-Receiver                                       | 1         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.7%    |
| Broadcom HP Portable SoftSailing                            | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 173       | 55.81%  |
| AMD                      | 66        | 21.29%  |
| Nvidia                   | 58        | 18.71%  |
| C-Media Electronics      | 3         | 0.97%   |
| Texas Instruments        | 2         | 0.65%   |
| GN Netcom                | 2         | 0.65%   |
| Yamaha                   | 1         | 0.32%   |
| Realtek Semiconductor    | 1         | 0.32%   |
| Native Instruments       | 1         | 0.32%   |
| Micro Star International | 1         | 0.32%   |
| JMTek                    | 1         | 0.32%   |
| Audioengine              | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 8.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 6.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 4.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 3.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 3.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 2.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.9%    |
| AMD FCH Azalia Controller                                                                         | 6         | 1.63%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 0.81%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.81%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.81%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 30        | 29.7%   |
| SK hynix                     | 20        | 19.8%   |
| Unknown                      | 14        | 13.86%  |
| Micron Technology            | 6         | 5.94%   |
| Kingston                     | 5         | 4.95%   |
| Crucial                      | 5         | 4.95%   |
| Nanya Technology             | 3         | 2.97%   |
| G.Skill                      | 3         | 2.97%   |
| Corsair                      | 3         | 2.97%   |
| A-DATA Technology            | 3         | 2.97%   |
| Unknown (ABCD)               | 2         | 1.98%   |
| Unknown                      | 2         | 1.98%   |
| Smart                        | 1         | 0.99%   |
| Ramaxel Technology           | 1         | 0.99%   |
| Patriot Memory (PDP Systems) | 1         | 0.99%   |
| Elpida                       | 1         | 0.99%   |
| AVEXIR                       | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 1.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.85%   |
| Unknown                                                          | 2         | 1.85%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.93%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.93%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.93%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.93%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 0.93%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.93%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.93%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 48.91%  |
| DDR3    | 30        | 32.61%  |
| DDR2    | 6         | 6.52%   |
| SDRAM   | 4         | 4.35%   |
| LPDDR4  | 3         | 3.26%   |
| Unknown | 2         | 2.17%   |
| LPDDR3  | 1         | 1.09%   |
| DDR     | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 74.19%  |
| DIMM         | 20        | 21.51%  |
| Row Of Chips | 3         | 3.23%   |
| Unknown      | 1         | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 39        | 38.61%  |
| 4096  | 24        | 23.76%  |
| 2048  | 18        | 17.82%  |
| 16384 | 11        | 10.89%  |
| 32768 | 4         | 3.96%   |
| 1024  | 4         | 3.96%   |
| 512   | 1         | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 22        | 22.92%  |
| 1600    | 22        | 22.92%  |
| 2667    | 12        | 12.5%   |
| 2400    | 9         | 9.38%   |
| 667     | 4         | 4.17%   |
| Unknown | 4         | 4.17%   |
| 1334    | 3         | 3.13%   |
| 1333    | 3         | 3.13%   |
| 3600    | 2         | 2.08%   |
| 1067    | 2         | 2.08%   |
| 4267    | 1         | 1.04%   |
| 4199    | 1         | 1.04%   |
| 3400    | 1         | 1.04%   |
| 3266    | 1         | 1.04%   |
| 2666    | 1         | 1.04%   |
| 2267    | 1         | 1.04%   |
| 2133    | 1         | 1.04%   |
| 2048    | 1         | 1.04%   |
| 1867    | 1         | 1.04%   |
| 1866    | 1         | 1.04%   |
| 1200    | 1         | 1.04%   |
| 800     | 1         | 1.04%   |
| 533     | 1         | 1.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Konica Minolta     | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Konica Minolta 185    | 1         | 33.33%  |
| HP OfficeJet Pro 8730 | 1         | 33.33%  |
| Brother MFC-L2685DW   | 1         | 33.33%  |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 17.22%  |
| Microdia                               | 15        | 9.93%   |
| IMC Networks                           | 15        | 9.93%   |
| Acer                                   | 14        | 9.27%   |
| Suyin                                  | 9         | 5.96%   |
| Quanta                                 | 9         | 5.96%   |
| Sunplus Innovation Technology          | 8         | 5.3%    |
| Realtek Semiconductor                  | 8         | 5.3%    |
| Luxvisions Innotech Limited            | 7         | 4.64%   |
| Logitech                               | 6         | 3.97%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.65%   |
| Apple                                  | 4         | 2.65%   |
| Alcor Micro                            | 4         | 2.65%   |
| Z-Star Microelectronics                | 2         | 1.32%   |
| Syntek                                 | 2         | 1.32%   |
| Lenovo                                 | 2         | 1.32%   |
| Importek                               | 2         | 1.32%   |
| Creative Technology                    | 2         | 1.32%   |
| USB Camera                             | 1         | 0.66%   |
| Unknown                                | 1         | 0.66%   |
| Silicon Motion                         | 1         | 0.66%   |
| Pixart Imaging                         | 1         | 0.66%   |
| OmniVision Technologies                | 1         | 0.66%   |
| MacroSilicon                           | 1         | 0.66%   |
| Lite-On Technology                     | 1         | 0.66%   |
| Intel                                  | 1         | 0.66%   |
| Huawei Technologies                    | 1         | 0.66%   |
| eMPIA Technology                       | 1         | 0.66%   |
| ARC International                      | 1         | 0.66%   |
| ALi                                    | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 9         | 5.96%   |
| Chicony Integrated Camera                            | 7         | 4.64%   |
| Acer Integrated Camera                               | 7         | 4.64%   |
| Chicony HD WebCam                                    | 4         | 2.65%   |
| Sunplus HD WebCam                                    | 3         | 1.99%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.99%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 1.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 1.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 1.99%   |
| IMC Networks Integrated Camera                       | 3         | 1.99%   |
| Chicony HP TrueVision HD Camera                      | 3         | 1.99%   |
| Syntek Integrated Camera                             | 2         | 1.32%   |
| Suyin HP TrueVision HD                               | 2         | 1.32%   |
| Suyin HD Video WebCam                                | 2         | 1.32%   |
| Realtek Lenovo EasyCamera                            | 2         | 1.32%   |
| Quanta HP Webcam                                     | 2         | 1.32%   |
| Quanta HP HD Camera                                  | 2         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 1.32%   |
| IMC Networks EasyCamera                              | 2         | 1.32%   |
| Chicony HP HD Camera                                 | 2         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 2         | 1.32%   |
| Apple Built-in iSight                                | 2         | 1.32%   |
| Alcor Micro USB 2.0 Camera                           | 2         | 1.32%   |
| Acer USB2.0 Camera                                   | 2         | 1.32%   |
| Z-Star WebCam SC-03FFL11739P                         | 1         | 0.66%   |
| Z-Star Venus USB2.0 Camera                           | 1         | 0.66%   |
| USB Camera USB Camera                                | 1         | 0.66%   |
| Unknown 720p HD Camera                               | 1         | 0.66%   |
| Suyin HP Webcam-101                                  | 1         | 0.66%   |
| Suyin HD WebCam                                      | 1         | 0.66%   |
| Suyin Acer/Lenovo Webcam [CN0316]                    | 1         | 0.66%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.66%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.66%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 0.66%   |
| Sunplus HP TrueVision HD Camera                      | 1         | 0.66%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 0.66%   |
| Sunplus AAPDQT-0622-W                                | 1         | 0.66%   |
| Sunplus 1.3M HD WebCam                               | 1         | 0.66%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 42.86%  |
| Synaptics                  | 3         | 14.29%  |
| Shenzhen Goodix Technology | 2         | 9.52%   |
| AuthenTec                  | 2         | 9.52%   |
| Upek                       | 1         | 4.76%   |
| STMicroelectronics         | 1         | 4.76%   |
| Samsung Electronics        | 1         | 4.76%   |
| Focal-systems.Corp         | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 14.29%  |
| Unknown                                                | 3         | 14.29%  |
| Validity Sensors Synaptics WBDI                        | 2         | 9.52%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 9.52%   |
| Validity Sensors VFS491                                | 1         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.76%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.76%   |
| Samsung Fingerprint Sensor Device - 730B               | 1         | 4.76%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.76%   |
| AuthenTec AES1600                                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| O2 Micro    | 1         | 12.5%   |
| Lenovo      | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 37.5%   |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader            | 1         | 12.5%   |
| Broadcom 5880                                  | 1         | 12.5%   |
| Broadcom 58200                                 | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 161       | 67.08%  |
| 1     | 67        | 27.92%  |
| 2     | 10        | 4.17%   |
| 4     | 1         | 0.42%   |
| 3     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 24        | 26.09%  |
| Graphics card            | 20        | 21.74%  |
| Fingerprint reader       | 20        | 21.74%  |
| Multimedia controller    | 14        | 15.22%  |
| Chipcard                 | 7         | 7.61%   |
| Communication controller | 2         | 2.17%   |
| Unassigned class         | 1         | 1.09%   |
| Dvb card                 | 1         | 1.09%   |
| Card reader              | 1         | 1.09%   |
| Camera                   | 1         | 1.09%   |
| Bluetooth                | 1         | 1.09%   |

