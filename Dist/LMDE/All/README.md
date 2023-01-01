LMDE - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for LMDE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

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

Total: 962

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
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
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
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
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
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
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
| ASRock        | G41M-S3                     | Desktop     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
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
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
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
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
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
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
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
| ASUSTek       | P5QL PRO                    | Desktop     | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
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
| Dell          | 0XR1GT A00                  | Desktop     | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Acer          | AOD270                      | Notebook    | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
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
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
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
| ASUSTek       | 901                         | Notebook    | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Acer          | EG43M                       | Desktop     | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | Notebook    | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| ASUSTek       | P4P800                      | Desktop     | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Acer          | TravelMate 420              | Notebook    | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | Notebook    | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | Notebook    | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | Notebook    | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| Dell          | 0Y2K8N A01                  | Desktop     | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
| ASUSTek       | 901                         | Notebook    | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [311d594372](https://linux-hardware.org/?probe=311d594372) | Jan 13, 2022 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [4fac8e2cb1](https://linux-hardware.org/?probe=4fac8e2cb1) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [ea55ac1aab](https://linux-hardware.org/?probe=ea55ac1aab) | Jan 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [33457cde11](https://linux-hardware.org/?probe=33457cde11) | Jan 09, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | Notebook    | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| Unknown       | K7VM2                       | Desktop     | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | Desktop     | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| Wistron       | ProLiant ML110 G5           | Server      | [8526295a2f](https://linux-hardware.org/?probe=8526295a2f) | Dec 27, 2021 |
| Advent        | Monza T100                  | Notebook    | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | Notebook    | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | Notebook    | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | Desktop     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | Notebook    | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Acer          | RS880M05                    | Desktop     | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | Desktop     | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| Samsung       | 305U1A                      | Notebook    | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Intel         | H61                         | Desktop     | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| HP            | 843C                        | Desktop     | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | Notebook    | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| HUAWEI        | MateBook HZ-W19             | Tablet      | [904decfd32](https://linux-hardware.org/?probe=904decfd32) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Biostar       | G41D3C                      | Desktop     | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | Notebook    | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | Notebook    | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| ASUSTek       | UN62                        | Desktop     | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | Notebook    | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | Notebook    | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | Notebook    | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | Notebook    | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | Notebook    | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| ASUSTek       | M51Sn                       | Notebook    | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | Notebook    | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| HP            | 0AA8h                       | Desktop     | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | Desktop     | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Intel         | BTC-T37                     | Desktop     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | Desktop     | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| Dell          | XPS M1330                   | Notebook    | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | Notebook    | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | Notebook    | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | Notebook    | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| MSI           | H81M-E34                    | Desktop     | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| Samsung       | R59/R60/R61                 | Notebook    | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | Notebook    | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | Notebook    | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | 0A98h                       | Desktop     | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | 0AA8h                       | Desktop     | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | 0AA8h                       | Desktop     | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | Notebook    | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | Notebook    | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | Desktop     | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| ASUSTek       | X555UJ                      | Notebook    | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | Desktop     | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | Desktop     | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| HP            | 530                         | Notebook    | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | Notebook    | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | Notebook    | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | Notebook    | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | Notebook    | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | Desktop     | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | Desktop     | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | Desktop     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Supermicro    | X8DT3                       | Server      | [f645c4227c](https://linux-hardware.org/?probe=f645c4227c) | Apr 02, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | Notebook    | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | Notebook    | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | Notebook    | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| Intel         | H61                         | Desktop     | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| HP            | Unknown                     | Notebook    | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | Desktop     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | Notebook    | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | Notebook    | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Acer          | EG43LMK                     | Desktop     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | Notebook    | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | Notebook    | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Acer          | EG43LMK                     | Desktop     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| Google        | Gnawty                      | Notebook    | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| MSI           | MS-7267                     | Desktop     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | Desktop     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| Notebook      | WID2010                     | Notebook    | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | Notebook    | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | Notebook    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Alienware     | 06G6JW A00                  | Desktop     | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | Notebook    | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | Desktop     | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | Desktop     | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| Exper         | E10IL1                      | Notebook    | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| MSI           | MS-6570                     | Desktop     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| Dell          | Precision M4800             | Notebook    | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | Notebook    | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | Notebook    | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | Gardenia CRB                | All in one  | [53b3108cb8](https://linux-hardware.org/?probe=53b3108cb8) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [862b159eb2](https://linux-hardware.org/?probe=862b159eb2) | Dec 19, 2020 |
| Toshiba       | STI 910123                  | Desktop     | [f9f7a69232](https://linux-hardware.org/?probe=f9f7a69232) | Dec 18, 2020 |
| Toshiba       | STI 910123                  | Desktop     | [ae79e069f3](https://linux-hardware.org/?probe=ae79e069f3) | Dec 18, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [fdc26c9f6d](https://linux-hardware.org/?probe=fdc26c9f6d) | Dec 18, 2020 |
| Exo           | Unknown                     | Notebook    | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| ASUSTek       | P8B75-V                     | Desktop     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | Notebook    | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [5b78a6b7ee](https://linux-hardware.org/?probe=5b78a6b7ee) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | Desktop     | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | Notebook    | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | Notebook    | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | Notebook    | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| HP            | 1496                        | Desktop     | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Acer          | Extensa 4620                | Notebook    | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [a229c68d0e](https://linux-hardware.org/?probe=a229c68d0e) | Nov 27, 2020 |
| Gigabyte      | 945GM-S2                    | Desktop     | [1bbf0f874b](https://linux-hardware.org/?probe=1bbf0f874b) | Nov 26, 2020 |
| MSI           | B85M-G43                    | Desktop     | [dee4fcacb7](https://linux-hardware.org/?probe=dee4fcacb7) | Nov 26, 2020 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | Notebook    | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | Notebook    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | Notebook    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [c03bf04e1e](https://linux-hardware.org/?probe=c03bf04e1e) | Nov 15, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | Notebook    | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | Notebook    | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | Notebook    | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | Notebook    | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | Notebook    | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | Latitude E6220              | Notebook    | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | Notebook    | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | Desktop     | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| Positivo      | DH8BW01                     | All in one  | [b8c805b52b](https://linux-hardware.org/?probe=b8c805b52b) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Gigabyte      | G33M-S2                     | Desktop     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | Desktop     | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | Notebook    | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 304Ah                       | Desktop     | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| HP            | 304Ah                       | Desktop     | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [8ebb392ed7](https://linux-hardware.org/?probe=8ebb392ed7) | Oct 03, 2020 |
| Dell          | 0YDJK3 A05                  | Server      | [825a44fd4e](https://linux-hardware.org/?probe=825a44fd4e) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| HP            | 304Ah                       | Desktop     | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| Positivo      | H14CU01                     | Notebook    | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | Notebook    | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | Notebook    | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | GL503VM                     | Notebook    | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | Notebook    | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [b200995d98](https://linux-hardware.org/?probe=b200995d98) | Sep 08, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [afcf5f7b56](https://linux-hardware.org/?probe=afcf5f7b56) | Sep 08, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [e5260021d2](https://linux-hardware.org/?probe=e5260021d2) | Sep 06, 2020 |
| MSI           | FX610                       | Notebook    | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [4b3e5c5cf9](https://linux-hardware.org/?probe=4b3e5c5cf9) | Sep 03, 2020 |
| Dell          | 0DR845                      | Desktop     | [f9dfefaf63](https://linux-hardware.org/?probe=f9dfefaf63) | Aug 31, 2020 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | Notebook    | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | Notebook    | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| ECS           | KAM1-I                      | Desktop     | [cef51c9cd7](https://linux-hardware.org/?probe=cef51c9cd7) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| MSI           | D2414 S26361-D2414-A10      | Desktop     | [a0ea23eae8](https://linux-hardware.org/?probe=a0ea23eae8) | Aug 10, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [e632211d18](https://linux-hardware.org/?probe=e632211d18) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Intel         | DG33FB AAD81072-309         | Desktop     | [217bfd48bd](https://linux-hardware.org/?probe=217bfd48bd) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [a70d949ebc](https://linux-hardware.org/?probe=a70d949ebc) | Jul 30, 2020 |
| Lenovo        | ThinkCentre M90z 2471W18    | All in one  | [03b15c1544](https://linux-hardware.org/?probe=03b15c1544) | Jul 21, 2020 |
| Positivo      | W310CZ-T                    | Notebook    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | Notebook    | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [4af42f19bb](https://linux-hardware.org/?probe=4af42f19bb) | Jul 14, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | Notebook    | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | 3396                        | Desktop     | [53167bce1a](https://linux-hardware.org/?probe=53167bce1a) | Jul 09, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | Notebook    | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| ASUSTek       | G11DF                       | Desktop     | [73ddfc32aa](https://linux-hardware.org/?probe=73ddfc32aa) | Jun 23, 2020 |
| ASUSTek       | G11DF                       | Desktop     | [497ebd9b60](https://linux-hardware.org/?probe=497ebd9b60) | Jun 23, 2020 |
| Toshiba       | All In One PC MP            | All in one  | [b2175e7054](https://linux-hardware.org/?probe=b2175e7054) | Jun 21, 2020 |
| Biostar       | NF61S-M2A                   | Desktop     | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc82478114](https://linux-hardware.org/?probe=dc82478114) | Jun 21, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a2c192906d](https://linux-hardware.org/?probe=a2c192906d) | Jun 21, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | Notebook    | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | Notebook    | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | Notebook    | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | Notebook    | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| PCWare        | IPMH81G1                    | Desktop     | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Toshiba       | All In One PC MP            | All in one  | [7a08b12375](https://linux-hardware.org/?probe=7a08b12375) | Jun 04, 2020 |
| ASUSTek       | 1005PX                      | Notebook    | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Sony          | VGN-AW41MF_H                | Notebook    | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | 8430 1000                   | All in one  | [c05bc25888](https://linux-hardware.org/?probe=c05bc25888) | May 29, 2020 |
| HP            | 8430 1000                   | All in one  | [f7df6a95b7](https://linux-hardware.org/?probe=f7df6a95b7) | May 29, 2020 |
| Dell          | 0DR845                      | Desktop     | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | Notebook    | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Acer          | Aspire 4830T                | Notebook    | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | Notebook    | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | Notebook    | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| ASRock        | B75M R2.0                   | Desktop     | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Dell          | Latitude E5570              | Notebook    | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | Notebook    | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | Notebook    | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | Notebook    | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | Notebook    | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | Notebook    | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | Notebook    | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| ASRock        | J4205-ITX                   | Desktop     | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | Desktop     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| HP            | Laptop 15-bs2xx             | Notebook    | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | Notebook    | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | Notebook    | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [3cc8e9e496](https://linux-hardware.org/?probe=3cc8e9e496) | Apr 12, 2020 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [8822c3378d](https://linux-hardware.org/?probe=8822c3378d) | Apr 12, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| HP            | 8526 MVB, A                 | Desktop     | [30e90998e1](https://linux-hardware.org/?probe=30e90998e1) | Apr 08, 2020 |
| Dell          | Latitude E6510              | Notebook    | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | Notebook    | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | Notebook    | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [5c90c49af6](https://linux-hardware.org/?probe=5c90c49af6) | Mar 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [e710551f70](https://linux-hardware.org/?probe=e710551f70) | Mar 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [336b94c4dc](https://linux-hardware.org/?probe=336b94c4dc) | Mar 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b660991573](https://linux-hardware.org/?probe=b660991573) | Mar 29, 2020 |
| MSI           | G31M2                       | Desktop     | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| Acer          | Aspire TC-605               | Desktop     | [495fffaa63](https://linux-hardware.org/?probe=495fffaa63) | Mar 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [fb006f397c](https://linux-hardware.org/?probe=fb006f397c) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | Desktop     | [5c7e0a86df](https://linux-hardware.org/?probe=5c7e0a86df) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | Desktop     | [c6a5cf98ee](https://linux-hardware.org/?probe=c6a5cf98ee) | Mar 24, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [0c52aebe31](https://linux-hardware.org/?probe=0c52aebe31) | Mar 23, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [b2c3317256](https://linux-hardware.org/?probe=b2c3317256) | Mar 19, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [2cd8614e59](https://linux-hardware.org/?probe=2cd8614e59) | Mar 17, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [fcb4ff46b5](https://linux-hardware.org/?probe=fcb4ff46b5) | Mar 17, 2020 |
| Intel         | D34010WYK H14771-303        | Desktop     | [0c19bbe87a](https://linux-hardware.org/?probe=0c19bbe87a) | Feb 18, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [7dbce6b0fc](https://linux-hardware.org/?probe=7dbce6b0fc) | Jan 15, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [11b0d93285](https://linux-hardware.org/?probe=11b0d93285) | Jan 15, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [363851a935](https://linux-hardware.org/?probe=363851a935) | Dec 19, 2019 |
| HP            | ProLiant MicroServer        | Desktop     | [708dff507f](https://linux-hardware.org/?probe=708dff507f) | Dec 19, 2019 |
| Dell          | Inspiron 3593               | Notebook    | [9f8af004d3](https://linux-hardware.org/?probe=9f8af004d3) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | Notebook    | [7f4ce08df9](https://linux-hardware.org/?probe=7f4ce08df9) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | Notebook    | [a6ee735c5f](https://linux-hardware.org/?probe=a6ee735c5f) | Nov 29, 2019 |
| Dell          | OptiPlex GX620              | Desktop     | [21f221a304](https://linux-hardware.org/?probe=21f221a304) | May 17, 2019 |
| Dell          | OptiPlex GX620              | Desktop     | [3e9258a7c5](https://linux-hardware.org/?probe=3e9258a7c5) | Apr 15, 2019 |
| Dell          | OptiPlex GX620              | Desktop     | [87babb0fa3](https://linux-hardware.org/?probe=87babb0fa3) | Apr 15, 2019 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [d950de89e7](https://linux-hardware.org/?probe=d950de89e7) | Mar 26, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [9be63e6a28](https://linux-hardware.org/?probe=9be63e6a28) | Jan 09, 2019 |
| HP            | Pavilion dv7                | Notebook    | [4480bf8ff3](https://linux-hardware.org/?probe=4480bf8ff3) | Dec 24, 2018 |
| Acer          | Aspire V3-571               | Notebook    | [bb8f83433e](https://linux-hardware.org/?probe=bb8f83433e) | Nov 27, 2018 |
| Acer          | Aspire V3-571               | Notebook    | [1136588271](https://linux-hardware.org/?probe=1136588271) | Nov 27, 2018 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [d425ca175b](https://linux-hardware.org/?probe=d425ca175b) | Oct 11, 2018 |
| HP            | ProBook 4510s               | Notebook    | [dbc607e890](https://linux-hardware.org/?probe=dbc607e890) | Sep 08, 2018 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [693096a808](https://linux-hardware.org/?probe=693096a808) | Sep 06, 2018 |
| ASUSTek       | P8Z77-V                     | Desktop     | [bcdb9633d9](https://linux-hardware.org/?probe=bcdb9633d9) | Sep 05, 2018 |
| Dell          | Inspiron 11-3162            | Notebook    | [92dcc778ac](https://linux-hardware.org/?probe=92dcc778ac) | Mar 19, 2018 |
| Sony          | VPCEB1M1R                   | Notebook    | [25b5c0689e](https://linux-hardware.org/?probe=25b5c0689e) | Mar 16, 2018 |
| Foxconn       | 945 7MA Series              | Desktop     | [95d9e1dba9](https://linux-hardware.org/?probe=95d9e1dba9) | Nov 14, 2017 |
| ASUSTek       | H61M-K                      | Desktop     | [78a1c15c22](https://linux-hardware.org/?probe=78a1c15c22) | Sep 09, 2017 |
| Sony          | VPCSB3M1R                   | Notebook    | [155309a9eb](https://linux-hardware.org/?probe=155309a9eb) | Aug 23, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 4 | 387       | 60.37%  |
| LMDE 5 | 235       | 36.66%  |
| LMDE 3 | 14        | 2.18%   |
| LMDE 2 | 5         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 637       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-8-amd64         | 45        | 6.41%   |
| 4.19.0-18-amd64        | 45        | 6.41%   |
| 4.19.0-17-amd64        | 41        | 5.84%   |
| 5.10.0-12-amd64        | 40        | 5.7%    |
| 4.19.0-16-amd64        | 40        | 5.7%    |
| 5.10.0-19-amd64        | 37        | 5.27%   |
| 4.19.0-14-amd64        | 31        | 4.42%   |
| 5.10.0-14-amd64        | 30        | 4.27%   |
| 4.19.0-13-amd64        | 30        | 4.27%   |
| 4.19.0-9-amd64         | 29        | 4.13%   |
| 5.10.0-13-amd64        | 27        | 3.85%   |
| 5.10.0-18-amd64        | 24        | 3.42%   |
| 5.10.0-17-amd64        | 20        | 2.85%   |
| 4.19.0-10-amd64        | 20        | 2.85%   |
| 5.10.0-15-amd64        | 19        | 2.71%   |
| 4.19.0-12-amd64        | 19        | 2.71%   |
| 4.19.0-8-686           | 17        | 2.42%   |
| 4.19.0-17-686          | 17        | 2.42%   |
| 5.10.0-16-amd64        | 14        | 1.99%   |
| 4.19.0-16-686          | 14        | 1.99%   |
| 4.19.0-18-686          | 12        | 1.71%   |
| 5.10.0-20-amd64        | 11        | 1.57%   |
| 4.19.0-11-amd64        | 11        | 1.57%   |
| 4.19.0-13-686          | 9         | 1.28%   |
| 4.9.0-8-amd64          | 8         | 1.14%   |
| 5.10.0-13-686          | 6         | 0.85%   |
| 4.19.0-14-686          | 6         | 0.85%   |
| 4.19.0-12-686          | 6         | 0.85%   |
| 4.19.0-19-686          | 5         | 0.71%   |
| 5.18.0-0.bpo.1-amd64   | 4         | 0.57%   |
| 3.16.0-4-amd64         | 4         | 0.57%   |
| 5.4.0-0.bpo.4-amd64    | 3         | 0.43%   |
| 5.16.0-0.bpo.4-amd64   | 3         | 0.43%   |
| 4.19.0-20-amd64        | 3         | 0.43%   |
| 5.19.0-0.deb11.2-amd64 | 2         | 0.28%   |
| 5.15.59-xanmod1        | 2         | 0.28%   |
| 5.10.0-0.bpo.5-amd64   | 2         | 0.28%   |
| 4.9.0-11-amd64         | 2         | 0.28%   |
| 4.19.0-9-686           | 2         | 0.28%   |
| 4.19.0-21-amd64        | 2         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 370       | 57.1%   |
| 5.10.0  | 227       | 35.03%  |
| 4.9.0   | 12        | 1.85%   |
| 5.18.0  | 6         | 0.93%   |
| 3.16.0  | 5         | 0.77%   |
| 5.6.0   | 3         | 0.46%   |
| 5.4.0   | 3         | 0.46%   |
| 5.16.0  | 3         | 0.46%   |
| 5.8.0   | 2         | 0.31%   |
| 5.19.0  | 2         | 0.31%   |
| 5.15.59 | 2         | 0.31%   |
| 5.15.0  | 2         | 0.31%   |
| 6.0.2   | 1         | 0.15%   |
| 6.0.0   | 1         | 0.15%   |
| 5.9.12  | 1         | 0.15%   |
| 5.9.0   | 1         | 0.15%   |
| 5.4.44  | 1         | 0.15%   |
| 5.19.10 | 1         | 0.15%   |
| 5.15.78 | 1         | 0.15%   |
| 5.15.70 | 1         | 0.15%   |
| 5.15.64 | 1         | 0.15%   |
| 5.15.56 | 1         | 0.15%   |
| 4.17.0  | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 370       | 57.36%  |
| 5.10    | 227       | 35.19%  |
| 4.9     | 12        | 1.86%   |
| 5.18    | 6         | 0.93%   |
| 5.15    | 5         | 0.78%   |
| 3.16    | 5         | 0.78%   |
| 5.4     | 4         | 0.62%   |
| 5.6     | 3         | 0.47%   |
| 5.19    | 3         | 0.47%   |
| 5.16    | 3         | 0.47%   |
| 6.0     | 2         | 0.31%   |
| 5.9     | 2         | 0.31%   |
| 5.8     | 2         | 0.31%   |
| 4.17    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 538       | 84.46%  |
| i686   | 99        | 15.54%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 563       | 87.42%  |
| Cinnamon   | 47        | 7.3%    |
| MATE       | 12        | 1.86%   |
| Unknown    | 9         | 1.4%    |
| XFCE       | 4         | 0.62%   |
| LXDE       | 2         | 0.31%   |
| KDE        | 2         | 0.31%   |
| GNOME      | 2         | 0.31%   |
| Trinity    | 1         | 0.16%   |
| LXQt       | 1         | 0.16%   |
| KDE5       | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 637       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 491       | 76.6%   |
| LightDM | 108       | 16.85%  |
| TDM     | 32        | 4.99%   |
| MDM     | 5         | 0.78%   |
| SDDM    | 2         | 0.31%   |
| GDM     | 2         | 0.31%   |
| GDM3    | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 192       | 30%     |
| de_DE   | 73        | 11.41%  |
| pt_BR   | 55        | 8.59%   |
| ru_RU   | 40        | 6.25%   |
| fr_FR   | 29        | 4.53%   |
| en_GB   | 28        | 4.38%   |
| pl_PL   | 22        | 3.44%   |
| it_IT   | 19        | 2.97%   |
| es_ES   | 17        | 2.66%   |
| Unknown | 17        | 2.66%   |
| en_CA   | 13        | 2.03%   |
| en_AU   | 10        | 1.56%   |
| es_MX   | 9         | 1.41%   |
| es_AR   | 9         | 1.41%   |
| de_CH   | 6         | 0.94%   |
| sv_SE   | 5         | 0.78%   |
| cs_CZ   | 5         | 0.78%   |
| tr_TR   | 4         | 0.63%   |
| pt_PT   | 4         | 0.63%   |
| nl_BE   | 4         | 0.63%   |
| en_ZA   | 4         | 0.63%   |
| el_GR   | 4         | 0.63%   |
| de_AT   | 4         | 0.63%   |
| sk_SK   | 3         | 0.47%   |
| nl_NL   | 3         | 0.47%   |
| ja_JP   | 3         | 0.47%   |
| hu_HU   | 3         | 0.47%   |
| fr_CA   | 3         | 0.47%   |
| en_IN   | 3         | 0.47%   |
| da_DK   | 3         | 0.47%   |
| bg_BG   | 3         | 0.47%   |
| unm_US  | 2         | 0.31%   |
| uk_UA   | 2         | 0.31%   |
| ko_KR   | 2         | 0.31%   |
| it_CH   | 2         | 0.31%   |
| fr_BE   | 2         | 0.31%   |
| et_EE   | 2         | 0.31%   |
| es_EC   | 2         | 0.31%   |
| es_CL   | 2         | 0.31%   |
| es_BO   | 2         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 383       | 59.75%  |
| EFI  | 258       | 40.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 594       | 93.1%   |
| Btrfs   | 16        | 2.51%   |
| Tmpfs   | 9         | 1.41%   |
| Unknown | 8         | 1.25%   |
| Overlay | 7         | 1.1%    |
| Xfs     | 2         | 0.31%   |
| Ext3    | 1         | 0.16%   |
| Aufs    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 487       | 75.98%  |
| GPT     | 98        | 15.29%  |
| MBR     | 56        | 8.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 601       | 93.91%  |
| Yes       | 39        | 6.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 588       | 92.31%  |
| Yes       | 49        | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 112       | 17.58%  |
| ASUSTek Computer               | 96        | 15.07%  |
| Dell                           | 79        | 12.4%   |
| Lenovo                         | 66        | 10.36%  |
| Acer                           | 53        | 8.32%   |
| MSI                            | 31        | 4.87%   |
| Gigabyte Technology            | 31        | 4.87%   |
| ASRock                         | 15        | 2.35%   |
| Toshiba                        | 13        | 2.04%   |
| Apple                          | 12        | 1.88%   |
| Sony                           | 10        | 1.57%   |
| Samsung Electronics            | 10        | 1.57%   |
| Intel                          | 9         | 1.41%   |
| Unknown                        | 9         | 1.41%   |
| Fujitsu Siemens                | 6         | 0.94%   |
| Positivo                       | 5         | 0.78%   |
| Fujitsu                        | 5         | 0.78%   |
| LG Electronics                 | 4         | 0.63%   |
| ECS                            | 4         | 0.63%   |
| Pegatron                       | 3         | 0.47%   |
| Packard Bell                   | 3         | 0.47%   |
| Medion                         | 3         | 0.47%   |
| Google                         | 3         | 0.47%   |
| Gateway                        | 3         | 0.47%   |
| Foxconn                        | 3         | 0.47%   |
| TUXEDO                         | 2         | 0.31%   |
| Semp Toshiba                   | 2         | 0.31%   |
| OEM                            | 2         | 0.31%   |
| Matsushita Electric Industrial | 2         | 0.31%   |
| EVGA                           | 2         | 0.31%   |
| eMachines                      | 2         | 0.31%   |
| Biostar                        | 2         | 0.31%   |
| Alienware                      | 2         | 0.31%   |
| Wortmann AG                    | 1         | 0.16%   |
| Wistron                        | 1         | 0.16%   |
| Supermicro                     | 1         | 0.16%   |
| SiYW                           | 1         | 0.16%   |
| SAELITE                        | 1         | 0.16%   |
| Qbex                           | 1         | 0.16%   |
| Philco                         | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 16        | 2.51%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 4         | 0.63%   |
| HP Notebook                                 | 4         | 0.63%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.47%   |
| HP Pavilion dv6                             | 3         | 0.47%   |
| Dell OptiPlex 780                           | 3         | 0.47%   |
| Dell Latitude E6400                         | 3         | 0.47%   |
| ASUS All Series                             | 3         | 0.47%   |
| Acer Aspire E1-570G                         | 3         | 0.47%   |
| Acer Aspire 5930                            | 3         | 0.47%   |
| Acer AOD270                                 | 3         | 0.47%   |
| MSI MS-7C52                                 | 2         | 0.31%   |
| Lenovo V145-15AST 81MT                      | 2         | 0.31%   |
| Lenovo G500 20236                           | 2         | 0.31%   |
| HP Pavilion dv7                             | 2         | 0.31%   |
| HP Pavilion Desktop 590-p0xxx               | 2         | 0.31%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.31%   |
| HP Laptop 15-dw3xxx                         | 2         | 0.31%   |
| HP Laptop 15-bw0xx                          | 2         | 0.31%   |
| HP Laptop 14-df0xxx                         | 2         | 0.31%   |
| HP EliteBook 8540w                          | 2         | 0.31%   |
| HP EliteBook 820 G3                         | 2         | 0.31%   |
| HP Compaq Presario CQ71                     | 2         | 0.31%   |
| HP 255 G7 Notebook PC                       | 2         | 0.31%   |
| HP 14                                       | 2         | 0.31%   |
| Gigabyte B450M DS3H                         | 2         | 0.31%   |
| Dell OptiPlex 3010                          | 2         | 0.31%   |
| Dell Latitude E5540                         | 2         | 0.31%   |
| Dell Inspiron 5566                          | 2         | 0.31%   |
| Dell Inspiron 5559                          | 2         | 0.31%   |
| ASUS X101CH                                 | 2         | 0.31%   |
| ASUS PRIME B350M-A                          | 2         | 0.31%   |
| ASRock A320M-HDV R4.0                       | 2         | 0.31%   |
| Acer Aspire 5735                            | 2         | 0.31%   |
| Acer Aspire 3820                            | 2         | 0.31%   |
| Acer Aspire 3000                            | 2         | 0.31%   |
| Wortmann AG TERRA_MOBILE_1713A              | 1         | 0.16%   |
| Wistron ProLiant ML110 G5                   | 1         | 0.16%   |
| TUXEDO N8xxEZ                               | 1         | 0.16%   |
| TUXEDO BC1510 1710                          | 1         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 41        | 6.44%   |
| Lenovo ThinkPad         | 24        | 3.77%   |
| Dell Latitude           | 21        | 3.3%    |
| Dell Inspiron           | 21        | 3.3%    |
| HP Pavilion             | 18        | 2.83%   |
| HP Laptop               | 18        | 2.83%   |
| Lenovo IdeaPad          | 16        | 2.51%   |
| Unknown                 | 16        | 2.51%   |
| HP Compaq               | 14        | 2.2%    |
| Dell OptiPlex           | 13        | 2.04%   |
| HP EliteBook            | 12        | 1.88%   |
| Toshiba Satellite       | 11        | 1.73%   |
| Dell Precision          | 10        | 1.57%   |
| ASUS PRIME              | 9         | 1.41%   |
| HP ProBook              | 6         | 0.94%   |
| ASUS VivoBook           | 6         | 0.94%   |
| ASUS ROG                | 5         | 0.78%   |
| Lenovo ThinkCentre      | 4         | 0.63%   |
| HP Notebook             | 4         | 0.63%   |
| Dell XPS                | 4         | 0.63%   |
| Dell Vostro             | 4         | 0.63%   |
| Samsung RV411           | 3         | 0.47%   |
| Lenovo Yoga             | 3         | 0.47%   |
| HP Presario             | 3         | 0.47%   |
| HP 255                  | 3         | 0.47%   |
| Gigabyte X570           | 3         | 0.47%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.47%   |
| ASUS All                | 3         | 0.47%   |
| Acer Veriton            | 3         | 0.47%   |
| Acer AOD270             | 3         | 0.47%   |
| Packard Bell EasyNote   | 2         | 0.31%   |
| MSI MS-7C52             | 2         | 0.31%   |
| Lenovo V145-15AST       | 2         | 0.31%   |
| Lenovo Legion           | 2         | 0.31%   |
| Lenovo G500             | 2         | 0.31%   |
| HP ZBook                | 2         | 0.31%   |
| HP Mini                 | 2         | 0.31%   |
| HP ENVY                 | 2         | 0.31%   |
| HP 250                  | 2         | 0.31%   |
| HP 14                   | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 65        | 10.2%   |
| 2009    | 52        | 8.16%   |
| 2018    | 49        | 7.69%   |
| 2010    | 48        | 7.54%   |
| 2013    | 44        | 6.91%   |
| 2011    | 44        | 6.91%   |
| 2007    | 40        | 6.28%   |
| 2019    | 37        | 5.81%   |
| 2008    | 37        | 5.81%   |
| 2014    | 32        | 5.02%   |
| 2020    | 31        | 4.87%   |
| 2021    | 30        | 4.71%   |
| 2017    | 27        | 4.24%   |
| 2015    | 26        | 4.08%   |
| 2016    | 24        | 3.77%   |
| 2006    | 23        | 3.61%   |
| 2005    | 10        | 1.57%   |
| 2022    | 9         | 1.41%   |
| 2003    | 5         | 0.78%   |
| 2004    | 2         | 0.31%   |
| 2002    | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 384       | 60.28%  |
| Desktop     | 226       | 35.48%  |
| All in one  | 9         | 1.41%   |
| Convertible | 7         | 1.1%    |
| Tablet      | 5         | 0.78%   |
| Mini pc     | 3         | 0.47%   |
| Server      | 3         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 605       | 94.38%  |
| Enabled  | 36        | 5.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 633       | 99.37%  |
| Yes  | 4         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 156       | 24.3%   |
| 4.01-8.0    | 126       | 19.63%  |
| 8.01-16.0   | 102       | 15.89%  |
| 16.01-24.0  | 95        | 14.8%   |
| 2.01-3.0    | 59        | 9.19%   |
| 1.01-2.0    | 49        | 7.63%   |
| 32.01-64.0  | 28        | 4.36%   |
| 0.51-1.0    | 15        | 2.34%   |
| 64.01-256.0 | 7         | 1.09%   |
| 24.01-32.0  | 5         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 312       | 46.09%  |
| 2.01-3.0   | 157       | 23.19%  |
| 0.51-1.0   | 92        | 13.59%  |
| 3.01-4.0   | 65        | 9.6%    |
| 4.01-8.0   | 40        | 5.91%   |
| 8.01-16.0  | 6         | 0.89%   |
| 0.01-0.5   | 3         | 0.44%   |
| 32.01-64.0 | 2         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 410       | 62.88%  |
| 2      | 159       | 24.39%  |
| 3      | 41        | 6.29%   |
| 4      | 20        | 3.07%   |
| 5      | 6         | 0.92%   |
| 7      | 5         | 0.77%   |
| 6      | 5         | 0.77%   |
| 0      | 5         | 0.77%   |
| 8      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 50.54%  |
| No        | 318       | 49.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 578       | 90.74%  |
| No        | 59        | 9.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 490       | 76.32%  |
| No        | 152       | 23.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 331       | 51.8%   |
| Yes       | 308       | 48.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 93        | 14.55%  |
| Germany      | 80        | 12.52%  |
| Brazil       | 59        | 9.23%   |
| Russia       | 47        | 7.36%   |
| France       | 32        | 5.01%   |
| Italy        | 27        | 4.23%   |
| UK           | 25        | 3.91%   |
| Poland       | 22        | 3.44%   |
| Canada       | 22        | 3.44%   |
| Spain        | 18        | 2.82%   |
| Australia    | 12        | 1.88%   |
| Ukraine      | 11        | 1.72%   |
| Netherlands  | 11        | 1.72%   |
| Mexico       | 11        | 1.72%   |
| Bulgaria     | 9         | 1.41%   |
| Argentina    | 9         | 1.41%   |
| Turkey       | 7         | 1.1%    |
| Switzerland  | 7         | 1.1%    |
| Sweden       | 7         | 1.1%    |
| Belgium      | 7         | 1.1%    |
| Austria      | 7         | 1.1%    |
| Portugal     | 6         | 0.94%   |
| Greece       | 6         | 0.94%   |
| Romania      | 5         | 0.78%   |
| India        | 5         | 0.78%   |
| Belarus      | 5         | 0.78%   |
| South Africa | 4         | 0.63%   |
| Philippines  | 4         | 0.63%   |
| Hungary      | 4         | 0.63%   |
| Ecuador      | 4         | 0.63%   |
| Czechia      | 4         | 0.63%   |
| Chile        | 4         | 0.63%   |
| Venezuela    | 3         | 0.47%   |
| Indonesia    | 3         | 0.47%   |
| Finland      | 3         | 0.47%   |
| Denmark      | 3         | 0.47%   |
| Bahrain      | 3         | 0.47%   |
| Vietnam      | 2         | 0.31%   |
| Tunisia      | 2         | 0.31%   |
| South Korea  | 2         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 10        | 1.5%    |
| Sao Paulo            | 6         | 0.9%    |
| Frankfurt am Main    | 6         | 0.9%    |
| Berlin               | 6         | 0.9%    |
| St Petersburg        | 5         | 0.75%   |
| Paris                | 5         | 0.75%   |
| Wroclaw              | 4         | 0.6%    |
| Sofia                | 4         | 0.6%    |
| Poznan               | 4         | 0.6%    |
| Perth                | 4         | 0.6%    |
| Montreal             | 4         | 0.6%    |
| Krakow               | 4         | 0.6%    |
| Hamburg              | 4         | 0.6%    |
| Guayaquil            | 4         | 0.6%    |
| Athens               | 4         | 0.6%    |
| Wohlen               | 3         | 0.45%   |
| Voronezh             | 3         | 0.45%   |
| Seville              | 3         | 0.45%   |
| Rome                 | 3         | 0.45%   |
| Rio de Janeiro       | 3         | 0.45%   |
| Oxford               | 3         | 0.45%   |
| Munich               | 3         | 0.45%   |
| Milan                | 3         | 0.45%   |
| Melbourne            | 3         | 0.45%   |
| Manama               | 3         | 0.45%   |
| London               | 3         | 0.45%   |
| Glasgow              | 3         | 0.45%   |
| Freiburg im Breisgau | 3         | 0.45%   |
| Florianópolis       | 3         | 0.45%   |
| Duisburg             | 3         | 0.45%   |
| Zurich               | 2         | 0.3%    |
| Warsaw               | 2         | 0.3%    |
| Victoria             | 2         | 0.3%    |
| Toronto              | 2         | 0.3%    |
| The Hague            | 2         | 0.3%    |
| Stuttgart            | 2         | 0.3%    |
| Stockholm            | 2         | 0.3%    |
| Sao Luís            | 2         | 0.3%    |
| Santa Rosa           | 2         | 0.3%    |
| San Antonio          | 2         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 163       | 232    | 18.44%  |
| Seagate             | 132       | 192    | 14.93%  |
| Samsung Electronics | 122       | 160    | 13.8%   |
| Toshiba             | 46        | 54     | 5.2%    |
| Kingston            | 46        | 52     | 5.2%    |
| Hitachi             | 44        | 48     | 4.98%   |
| SanDisk             | 40        | 50     | 4.52%   |
| Unknown             | 38        | 46     | 4.3%    |
| Crucial             | 28        | 34     | 3.17%   |
| Intel               | 19        | 20     | 2.15%   |
| SK hynix            | 14        | 17     | 1.58%   |
| HGST                | 14        | 15     | 1.58%   |
| A-DATA Technology   | 13        | 15     | 1.47%   |
| China               | 12        | 13     | 1.36%   |
| Micron Technology   | 11        | 12     | 1.24%   |
| Phison              | 10        | 12     | 1.13%   |
| Fujitsu             | 9         | 9      | 1.02%   |
| Intenso             | 7         | 8      | 0.79%   |
| Patriot             | 6         | 7      | 0.68%   |
| Apple               | 6         | 11     | 0.68%   |
| Transcend           | 5         | 7      | 0.57%   |
| PNY                 | 5         | 6      | 0.57%   |
| KingSpec            | 5         | 6      | 0.57%   |
| Gigabyte Technology | 5         | 8      | 0.57%   |
| GOODRAM             | 4         | 4      | 0.45%   |
| Team                | 3         | 4      | 0.34%   |
| OCZ                 | 3         | 5      | 0.34%   |
| Maxtor              | 3         | 5      | 0.34%   |
| KingDian            | 3         | 4      | 0.34%   |
| Hewlett-Packard     | 3         | 4      | 0.34%   |
| Unknown             | 3         | 4      | 0.34%   |
| TCSUNBOW            | 2         | 2      | 0.23%   |
| SPCC                | 2         | 2      | 0.23%   |
| SABRENT             | 2         | 2      | 0.23%   |
| Plextor             | 2         | 3      | 0.23%   |
| Netac               | 2         | 2      | 0.23%   |
| Mushkin             | 2         | 2      | 0.23%   |
| KIOXIA              | 2         | 5      | 0.23%   |
| JMicron Technology  | 2         | 3      | 0.23%   |
| IBM/Hitachi         | 2         | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 10        | 1.04%   |
| Seagate ST500LT012-1DG142 500GB      | 9         | 0.94%   |
| Samsung SSD 860 EVO 500GB            | 9         | 0.94%   |
| Samsung SSD 850 EVO 500GB            | 9         | 0.94%   |
| Kingston SA400S37240G 240GB SSD      | 9         | 0.94%   |
| Kingston SA400S37480G 480GB SSD      | 8         | 0.83%   |
| Kingston SA400S37120G 120GB SSD      | 8         | 0.83%   |
| Unknown MMC Card  32GB               | 7         | 0.73%   |
| Unknown SD/MMC/MS PRO 64GB           | 6         | 0.63%   |
| Toshiba MQ01ABD100 1TB               | 6         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB       | 6         | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 5         | 0.52%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 5         | 0.52%   |
| Unknown MMC Card  128GB              | 5         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 0.52%   |
| SanDisk NVMe SSD Drive 256GB         | 5         | 0.52%   |
| Samsung SSD 860 EVO 1TB              | 5         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.42%   |
| Unknown MMC Card  7GB                | 4         | 0.42%   |
| Unknown MMC Card  64GB               | 4         | 0.42%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.42%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.42%   |
| Seagate Expansion 4TB                | 4         | 0.42%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.42%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 4         | 0.42%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 4         | 0.42%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.42%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.31%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 0.31%   |
| Toshiba HDWD110 1TB                  | 3         | 0.31%   |
| Seagate ST9500325AS 500GB            | 3         | 0.31%   |
| Seagate ST9250315AS 250GB            | 3         | 0.31%   |
| Seagate ST3250318AS 250GB            | 3         | 0.31%   |
| Seagate ST2000LX001-1RG174 2TB       | 3         | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB       | 3         | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 141       | 206    | 33.1%   |
| Seagate             | 131       | 189    | 30.75%  |
| Hitachi             | 44        | 48     | 10.33%  |
| Toshiba             | 37        | 41     | 8.69%   |
| Samsung Electronics | 31        | 39     | 7.28%   |
| HGST                | 14        | 15     | 3.29%   |
| Fujitsu             | 9         | 9      | 2.11%   |
| Unknown             | 6         | 6      | 1.41%   |
| Maxtor              | 3         | 5      | 0.7%    |
| Intenso             | 2         | 2      | 0.47%   |
| IBM/Hitachi         | 2         | 2      | 0.47%   |
| KESU                | 1         | 2      | 0.23%   |
| Initio              | 1         | 1      | 0.23%   |
| HPE                 | 1         | 4      | 0.23%   |
| ExcelStor           | 1         | 1      | 0.23%   |
| DAS                 | 1         | 4      | 0.23%   |
| ASMedia             | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 80     | 20.63%  |
| Kingston            | 41        | 47     | 13.02%  |
| Crucial             | 28        | 34     | 8.89%   |
| SanDisk             | 25        | 32     | 7.94%   |
| WDC                 | 15        | 16     | 4.76%   |
| A-DATA Technology   | 13        | 15     | 4.13%   |
| Intel               | 11        | 11     | 3.49%   |
| China               | 11        | 12     | 3.49%   |
| Toshiba             | 8         | 12     | 2.54%   |
| Patriot             | 6         | 7      | 1.9%    |
| Micron Technology   | 6         | 7      | 1.9%    |
| Transcend           | 5         | 7      | 1.59%   |
| PNY                 | 5         | 6      | 1.59%   |
| Gigabyte Technology | 5         | 8      | 1.59%   |
| Apple               | 5         | 5      | 1.59%   |
| KingSpec            | 4         | 4      | 1.27%   |
| Intenso             | 4         | 5      | 1.27%   |
| GOODRAM             | 4         | 4      | 1.27%   |
| Team                | 3         | 4      | 0.95%   |
| SK hynix            | 3         | 4      | 0.95%   |
| OCZ                 | 3         | 5      | 0.95%   |
| KingDian            | 3         | 4      | 0.95%   |
| Hewlett-Packard     | 3         | 4      | 0.95%   |
| Unknown             | 3         | 4      | 0.95%   |
| Unknown             | 2         | 2      | 0.63%   |
| TCSUNBOW            | 2         | 2      | 0.63%   |
| Plextor             | 2         | 3      | 0.63%   |
| Netac               | 2         | 2      | 0.63%   |
| FORESEE             | 2         | 2      | 0.63%   |
| CT500MX5            | 2         | 2      | 0.63%   |
| Corsair             | 2         | 2      | 0.63%   |
| USB30               | 1         | 2      | 0.32%   |
| SSD PHIS            | 1         | 1      | 0.32%   |
| SPCC                | 1         | 1      | 0.32%   |
| Smartbuy            | 1         | 1      | 0.32%   |
| ORICO               | 1         | 1      | 0.32%   |
| OCZ-VERTEX          | 1         | 1      | 0.32%   |
| Mushkin             | 1         | 1      | 0.32%   |
| Microtech           | 1         | 2      | 0.32%   |
| LITEON              | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 374       | 575    | 47.04%  |
| SSD     | 274       | 379    | 34.47%  |
| NVMe    | 102       | 135    | 12.83%  |
| MMC     | 31        | 37     | 3.9%    |
| Unknown | 14        | 19     | 1.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 552       | 910    | 76.24%  |
| NVMe | 100       | 133    | 13.81%  |
| SAS  | 41        | 65     | 5.66%   |
| MMC  | 31        | 37     | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 456       | 671    | 69.62%  |
| 0.51-1.0   | 142       | 198    | 21.68%  |
| 1.01-2.0   | 30        | 42     | 4.58%   |
| 3.01-4.0   | 11        | 16     | 1.68%   |
| 4.01-10.0  | 9         | 12     | 1.37%   |
| 2.01-3.0   | 7         | 15     | 1.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 226       | 34.72%  |
| 251-500        | 152       | 23.35%  |
| 501-1000       | 72        | 11.06%  |
| 51-100         | 57        | 8.76%   |
| 1001-2000      | 52        | 7.99%   |
| More than 3000 | 32        | 4.92%   |
| 21-50          | 28        | 4.3%    |
| 2001-3000      | 18        | 2.76%   |
| 1-20           | 13        | 2%      |
| Unknown        | 1         | 0.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 287       | 42.33%  |
| 21-50          | 145       | 21.39%  |
| 51-100         | 73        | 10.77%  |
| 101-250        | 64        | 9.44%   |
| 251-500        | 35        | 5.16%   |
| 501-1000       | 32        | 4.72%   |
| 1001-2000      | 18        | 2.65%   |
| More than 3000 | 12        | 1.77%   |
| 2001-3000      | 11        | 1.62%   |
| Unknown        | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 3.45%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 3.45%   |
| WDC WD3200BEVT-26A23T0 320GB          | 1         | 1      | 3.45%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 3.45%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 3.45%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 3.45%   |
| Seagate STM9120817AS 120GB            | 1         | 1      | 3.45%   |
| Seagate ST9640423AS 640GB             | 1         | 1      | 3.45%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 3.45%   |
| Seagate ST9120821AS 120GB             | 1         | 1      | 3.45%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 3.45%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 3.45%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 3.45%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 3.45%   |
| Samsung Electronics SP2004C 200GB     | 1         | 1      | 3.45%   |
| Samsung Electronics MP0402H 40GB      | 1         | 1      | 3.45%   |
| Samsung Electronics HM500JI 500GB     | 1         | 1      | 3.45%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 3.45%   |
| Samsung Electronics HD103SJ 1TB       | 1         | 1      | 3.45%   |
| Phison ES 512GB                       | 1         | 1      | 3.45%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 3.45%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 3.45%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 3.45%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 3.45%   |
| Fujitsu MHZ2080BJ FFS G2 80GB         | 1         | 1      | 3.45%   |
| Crucial M4-CT256M4SSD2 256GB          | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| Samsung Electronics | 7         | 7      | 25%     |
| WDC                 | 3         | 4      | 10.71%  |
| Toshiba             | 1         | 1      | 3.57%   |
| SK hynix            | 1         | 1      | 3.57%   |
| SanDisk             | 1         | 1      | 3.57%   |
| Phison              | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 42.11%  |
| Samsung Electronics | 5         | 5      | 26.32%  |
| WDC                 | 3         | 4      | 15.79%  |
| Hitachi             | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 20     | 67.86%  |
| SSD  | 6         | 6      | 21.43%  |
| NVMe | 3         | 3      | 10.71%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 503       | 897    | 75.53%  |
| Works    | 135       | 219    | 20.27%  |
| Malfunc  | 28        | 29     | 4.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 464       | 61.95%  |
| AMD                              | 106       | 14.15%  |
| Samsung Electronics              | 34        | 4.54%   |
| SanDisk                          | 21        | 2.8%    |
| Nvidia                           | 21        | 2.8%    |
| ASMedia Technology               | 13        | 1.74%   |
| Phison Electronics               | 12        | 1.6%    |
| JMicron Technology               | 12        | 1.6%    |
| SK hynix                         | 11        | 1.47%   |
| Silicon Integrated Systems [SiS] | 8         | 1.07%   |
| Marvell Technology Group         | 8         | 1.07%   |
| VIA Technologies                 | 7         | 0.93%   |
| Micron Technology                | 5         | 0.67%   |
| Kingston Technology Company      | 5         | 0.67%   |
| Broadcom / LSI                   | 4         | 0.53%   |
| KIOXIA                           | 3         | 0.4%    |
| Union Memory (Shenzhen)          | 2         | 0.27%   |
| Toshiba America Info Systems     | 2         | 0.27%   |
| Silicon Motion                   | 2         | 0.27%   |
| Silicon Image                    | 2         | 0.27%   |
| LSI Logic / Symbios Logic        | 2         | 0.27%   |
| Solid State Storage Technology   | 1         | 0.13%   |
| Micron/Crucial Technology        | 1         | 0.13%   |
| Integrated Technology Express    | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |
| ADATA Technology                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 65        | 7.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 36        | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 32        | 3.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 30        | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 2.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 22        | 2.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 22        | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 19        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 19        | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 16        | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 1.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 14        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 13        | 1.42%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 13        | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 12        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 11        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10        | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 10        | 1.09%   |
| SanDisk Non-Volatile memory controller                                         | 9         | 0.98%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 0.98%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 0.98%   |
| Nvidia MCP61 SATA Controller                                                   | 8         | 0.87%   |
| JMicron JMB363 SATA/IDE Controller                                             | 8         | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 8         | 0.87%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 8         | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8         | 0.87%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 7         | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 0.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 0.76%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 6         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 452       | 57.14%  |
| IDE  | 176       | 22.25%  |
| NVMe | 102       | 12.9%   |
| RAID | 55        | 6.95%   |
| SAS  | 3         | 0.38%   |
| SCSI | 3         | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 500       | 78.49%  |
| AMD    | 137       | 21.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz          | 10        | 1.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 7         | 1.1%    |
| Intel Atom CPU N270 @ 1.60GHz           | 7         | 1.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 6         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 0.78%   |
| Intel Core i3-8130U CPU @ 2.20GHz       | 5         | 0.78%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz    | 5         | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 4         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 0.63%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 4         | 0.63%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 4         | 0.63%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4         | 0.63%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz    | 4         | 0.63%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 4         | 0.63%   |
| Intel Celeron CPU N2830 @ 2.16GHz       | 4         | 0.63%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 0.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 4         | 0.63%   |
| Intel Pentium M processor 1.73GHz       | 3         | 0.47%   |
| Intel Pentium D CPU 2.80GHz             | 3         | 0.47%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 3         | 0.47%   |
| Intel Pentium CPU G645 @ 2.90GHz        | 3         | 0.47%   |
| Intel Genuine CPU T2300 @ 1.66GHz       | 3         | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 0.47%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 3         | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 0.47%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 3         | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 0.47%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 3         | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 3         | 0.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 0.47%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3         | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.47%   |
| Intel Core i5 CPU 750 @ 2.67GHz         | 3         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 103       | 16.17%  |
| Intel Core i7           | 84        | 13.19%  |
| Intel Core i3           | 53        | 8.32%   |
| Intel Core 2 Duo        | 52        | 8.16%   |
| Intel Celeron           | 38        | 5.97%   |
| Intel Atom              | 29        | 4.55%   |
| Other                   | 26        | 4.08%   |
| AMD Ryzen 5             | 24        | 3.77%   |
| Intel Pentium           | 22        | 3.45%   |
| AMD Ryzen 7             | 17        | 2.67%   |
| Intel Xeon              | 16        | 2.51%   |
| Intel Core 2 Quad       | 12        | 1.88%   |
| Intel Core 2            | 12        | 1.88%   |
| Intel Pentium Dual-Core | 10        | 1.57%   |
| Intel Pentium Dual      | 8         | 1.26%   |
| Intel Genuine           | 8         | 1.26%   |
| AMD Ryzen 3             | 8         | 1.26%   |
| Intel Pentium M         | 7         | 1.1%    |
| Intel Pentium D         | 7         | 1.1%    |
| AMD FX                  | 7         | 1.1%    |
| AMD A4                  | 7         | 1.1%    |
| AMD Sempron             | 6         | 0.94%   |
| Intel Pentium 4         | 5         | 0.78%   |
| AMD Athlon 64 X2        | 5         | 0.78%   |
| AMD Phenom II X4        | 4         | 0.63%   |
| AMD E2                  | 4         | 0.63%   |
| AMD Athlon              | 4         | 0.63%   |
| Intel Core i9           | 3         | 0.47%   |
| Intel Core Duo          | 3         | 0.47%   |
| AMD Turion 64 X2 Mobile | 3         | 0.47%   |
| AMD Ryzen 9             | 3         | 0.47%   |
| AMD Phenom II X6        | 3         | 0.47%   |
| AMD E1                  | 3         | 0.47%   |
| AMD Athlon XP           | 3         | 0.47%   |
| AMD Athlon II X2        | 3         | 0.47%   |
| AMD Athlon II           | 3         | 0.47%   |
| AMD A8                  | 3         | 0.47%   |
| AMD A10                 | 3         | 0.47%   |
| Intel Pentium Silver    | 2         | 0.31%   |
| Intel Pentium Gold      | 2         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 339       | 53.13%  |
| 4      | 183       | 28.68%  |
| 1      | 53        | 8.31%   |
| 6      | 28        | 4.39%   |
| 8      | 25        | 3.92%   |
| 16     | 4         | 0.63%   |
| 12     | 3         | 0.47%   |
| 3      | 2         | 0.31%   |
| 10     | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 629       | 98.74%  |
| 2      | 8         | 1.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 336       | 52.75%  |
| 1      | 301       | 47.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 588       | 92.31%  |
| 32-bit         | 49        | 7.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 50        | 7.73%   |
| Unknown    | 49        | 7.57%   |
| 0x206a7    | 42        | 6.49%   |
| 0x1067a    | 42        | 6.49%   |
| 0x306c3    | 25        | 3.86%   |
| 0x6fd      | 20        | 3.09%   |
| 0x40651    | 18        | 2.78%   |
| 0x806c1    | 17        | 2.63%   |
| 0x406e3    | 16        | 2.47%   |
| 0x806ea    | 14        | 2.16%   |
| 0x08108109 | 14        | 2.16%   |
| 0x30661    | 12        | 1.85%   |
| 0x20655    | 12        | 1.85%   |
| 0x106c2    | 12        | 1.85%   |
| 0x506e3    | 11        | 1.7%    |
| 0x06006705 | 11        | 1.7%    |
| 0x010000c8 | 11        | 1.7%    |
| 0x6f6      | 10        | 1.55%   |
| 0x106e5    | 10        | 1.55%   |
| 0x806ec    | 9         | 1.39%   |
| 0x806e9    | 9         | 1.39%   |
| 0x10676    | 9         | 1.39%   |
| 0x406c4    | 8         | 1.24%   |
| 0x906ed    | 7         | 1.08%   |
| 0x906ea    | 7         | 1.08%   |
| 0x6fb      | 7         | 1.08%   |
| 0x6ec      | 7         | 1.08%   |
| 0x20652    | 7         | 1.08%   |
| 0x30678    | 6         | 0.93%   |
| 0x08608103 | 6         | 0.93%   |
| 0x806eb    | 5         | 0.77%   |
| 0x706a1    | 5         | 0.77%   |
| 0x6e8      | 5         | 0.77%   |
| 0x6d8      | 5         | 0.77%   |
| 0x306d4    | 5         | 0.77%   |
| 0x10677    | 5         | 0.77%   |
| 0x0a50000c | 5         | 0.77%   |
| 0x06001119 | 5         | 0.77%   |
| 0xf65      | 4         | 0.62%   |
| 0xf29      | 4         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 60        | 9.4%    |
| KabyLake        | 59        | 9.25%   |
| IvyBridge       | 51        | 7.99%   |
| SandyBridge     | 49        | 7.68%   |
| Haswell         | 45        | 7.05%   |
| Core            | 45        | 7.05%   |
| Bonnell         | 28        | 4.39%   |
| Skylake         | 27        | 4.23%   |
| Westmere        | 23        | 3.61%   |
| Zen+            | 21        | 3.29%   |
| P6              | 19        | 2.98%   |
| K10             | 19        | 2.98%   |
| Silvermont      | 18        | 2.82%   |
| TigerLake       | 17        | 2.66%   |
| K8 Hammer       | 16        | 2.51%   |
| NetBurst        | 15        | 2.35%   |
| Zen             | 13        | 2.04%   |
| Nehalem         | 13        | 2.04%   |
| Excavator       | 13        | 2.04%   |
| Unknown         | 11        | 1.72%   |
| Zen 3           | 10        | 1.57%   |
| Piledriver      | 9         | 1.41%   |
| Zen 2           | 7         | 1.1%    |
| Goldmont plus   | 7         | 1.1%    |
| Broadwell       | 7         | 1.1%    |
| Puma            | 5         | 0.78%   |
| Bobcat          | 5         | 0.78%   |
| IceLake         | 4         | 0.63%   |
| CometLake       | 4         | 0.63%   |
| Tremont         | 3         | 0.47%   |
| K6              | 3         | 0.47%   |
| Jaguar          | 3         | 0.47%   |
| Goldmont        | 3         | 0.47%   |
| Bulldozer       | 3         | 0.47%   |
| K8 & K10 hybrid | 2         | 0.31%   |
| K10 Llano       | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 346       | 47.86%  |
| Nvidia                           | 203       | 28.08%  |
| AMD                              | 158       | 21.85%  |
| VIA Technologies                 | 5         | 0.69%   |
| Silicon Integrated Systems [SiS] | 5         | 0.69%   |
| Matrox Electronics Systems       | 4         | 0.55%   |
| S3 Graphics                      | 1         | 0.14%   |
| ASPEED Technology                | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 4.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 3.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 2.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 18        | 2.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 2.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 2.11%   |
| Intel UHD Graphics 620                                                                   | 14        | 1.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.84%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 12        | 1.58%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 1.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.32%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 9         | 1.19%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 1.19%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 9         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.19%   |
| Nvidia GT218 [GeForce 210]                                                               | 8         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.79%   |
| Intel HD Graphics 620                                                                    | 6         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 0.79%   |
| AMD Lucienne                                                                             | 6         | 0.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5         | 0.66%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 0.66%   |
| Intel HD Graphics 530                                                                    | 5         | 0.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.66%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.66%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 5         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 268       | 41.88%  |
| 1 x Nvidia      | 142       | 22.19%  |
| 1 x AMD         | 129       | 20.16%  |
| Intel + Nvidia  | 55        | 8.59%   |
| Intel + AMD     | 15        | 2.34%   |
| 2 x AMD         | 8         | 1.25%   |
| AMD + Nvidia    | 6         | 0.94%   |
| 1 x VIA         | 5         | 0.78%   |
| 1 x SiS         | 5         | 0.78%   |
| 1 x Matrox      | 4         | 0.63%   |
| 2 x Nvidia      | 1         | 0.16%   |
| 1 x S3 Graphics | 1         | 0.16%   |
| 1 x ASPEED      | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 518       | 80.56%  |
| Proprietary | 67        | 10.42%  |
| Unknown     | 58        | 9.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 355       | 55.12%  |
| 0.01-0.5   | 105       | 16.3%   |
| 1.01-2.0   | 77        | 11.96%  |
| 0.51-1.0   | 54        | 8.39%   |
| 3.01-4.0   | 30        | 4.66%   |
| 7.01-8.0   | 11        | 1.71%   |
| 5.01-6.0   | 6         | 0.93%   |
| 2.01-3.0   | 5         | 0.78%   |
| 8.01-16.0  | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 82        | 12.87%  |
| AU Optronics            | 74        | 11.62%  |
| LG Display              | 58        | 9.11%   |
| BOE                     | 52        | 8.16%   |
| Chimei Innolux          | 46        | 7.22%   |
| Goldstar                | 35        | 5.49%   |
| Acer                    | 27        | 4.24%   |
| Dell                    | 26        | 4.08%   |
| BenQ                    | 17        | 2.67%   |
| Chi Mei Optoelectronics | 16        | 2.51%   |
| Lenovo                  | 15        | 2.35%   |
| Hewlett-Packard         | 15        | 2.35%   |
| AOC                     | 14        | 2.2%    |
| Philips                 | 13        | 2.04%   |
| LG Philips              | 13        | 2.04%   |
| Apple                   | 13        | 2.04%   |
| Ancor Communications    | 13        | 2.04%   |
| Unknown                 | 10        | 1.57%   |
| HannStar                | 10        | 1.57%   |
| Sony                    | 7         | 1.1%    |
| InfoVision              | 6         | 0.94%   |
| Iiyama                  | 5         | 0.78%   |
| Fujitsu Siemens         | 4         | 0.63%   |
| Quanta Display          | 3         | 0.47%   |
| PANDA                   | 3         | 0.47%   |
| CPT                     | 3         | 0.47%   |
| ___                     | 2         | 0.31%   |
| ViewSonic               | 2         | 0.31%   |
| Toshiba                 | 2         | 0.31%   |
| Sharp                   | 2         | 0.31%   |
| Sceptre Tech            | 2         | 0.31%   |
| NEC Computers           | 2         | 0.31%   |
| Medion                  | 2         | 0.31%   |
| LG Electronics          | 2         | 0.31%   |
| Insignia                | 2         | 0.31%   |
| eMachines               | 2         | 0.31%   |
| DENON                   | 2         | 0.31%   |
| Belinea                 | 2         | 0.31%   |
| ASUSTek Computer        | 2         | 0.31%   |
| Vestel Elektronik       | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 1.07%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 4         | 0.61%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 4         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 3         | 0.46%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.46%   |
| Unknown LCD Monitor SAMSUNG                                              | 2         | 0.31%   |
| Sony LCD Monitor TV 3840x1080                                            | 2         | 0.31%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 2         | 0.31%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.31%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.31%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 2         | 0.31%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.31%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch              | 2         | 0.31%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.31%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.31%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 2         | 0.31%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 2         | 0.31%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.31%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.31%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 2         | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.31%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                    | 2         | 0.31%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                         | 2         | 0.31%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                        | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 230       | 37.16%  |
| 1366x768 (WXGA)    | 142       | 22.94%  |
| 1280x1024 (SXGA)   | 39        | 6.3%    |
| 1280x800 (WXGA)    | 34        | 5.49%   |
| 1600x900 (HD+)     | 31        | 5.01%   |
| 1680x1050 (WSXGA+) | 22        | 3.55%   |
| 1440x900 (WXGA+)   | 21        | 3.39%   |
| 1024x600           | 16        | 2.58%   |
| 3840x2160 (4K)     | 15        | 2.42%   |
| 1920x1200 (WUXGA)  | 15        | 2.42%   |
| 1360x768           | 8         | 1.29%   |
| 2560x1440 (QHD)    | 7         | 1.13%   |
| 1024x768 (XGA)     | 7         | 1.13%   |
| Unknown            | 7         | 1.13%   |
| 3840x1080          | 4         | 0.65%   |
| 3440x1440          | 4         | 0.65%   |
| 2560x1080          | 3         | 0.48%   |
| 2880x1800          | 2         | 0.32%   |
| 1280x768           | 2         | 0.32%   |
| 7680x2160          | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 4240x1440          | 1         | 0.16%   |
| 2736x1824          | 1         | 0.16%   |
| 2560x1600          | 1         | 0.16%   |
| 2256x1504          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1600x1200          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 193       | 30.54%  |
| 13      | 47        | 7.44%   |
| 14      | 46        | 7.28%   |
| 17      | 45        | 7.12%   |
| Unknown | 44        | 6.96%   |
| 21      | 33        | 5.22%   |
| 24      | 32        | 5.06%   |
| 23      | 31        | 4.91%   |
| 19      | 25        | 3.96%   |
| 27      | 24        | 3.8%    |
| 18      | 20        | 3.16%   |
| 10      | 15        | 2.37%   |
| 20      | 12        | 1.9%    |
| 22      | 11        | 1.74%   |
| 12      | 11        | 1.74%   |
| 11      | 8         | 1.27%   |
| 31      | 6         | 0.95%   |
| 72      | 5         | 0.79%   |
| 34      | 4         | 0.63%   |
| 32      | 3         | 0.47%   |
| 54      | 2         | 0.32%   |
| 52      | 2         | 0.32%   |
| 48      | 2         | 0.32%   |
| 33      | 2         | 0.32%   |
| 16      | 2         | 0.32%   |
| 8       | 2         | 0.32%   |
| 84      | 1         | 0.16%   |
| 65      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 276       | 44.52%  |
| 401-500     | 81        | 13.06%  |
| 501-600     | 80        | 12.9%   |
| 201-300     | 54        | 8.71%   |
| 351-400     | 53        | 8.55%   |
| Unknown     | 44        | 7.1%    |
| 701-800     | 9         | 1.45%   |
| 601-700     | 8         | 1.29%   |
| 1001-1500   | 7         | 1.13%   |
| 1501-2000   | 6         | 0.97%   |
| 101-200     | 2         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 403       | 67.96%  |
| 16/10   | 90        | 15.18%  |
| Unknown | 40        | 6.75%   |
| 5/4     | 35        | 5.9%    |
| 4/3     | 14        | 2.36%   |
| 21/9    | 6         | 1.01%   |
| 3/2     | 4         | 0.67%   |
| 32/9    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 191       | 30.27%  |
| 201-250        | 87        | 13.79%  |
| 81-90          | 76        | 12.04%  |
| 151-200        | 48        | 7.61%   |
| Unknown        | 44        | 6.97%   |
| 141-150        | 33        | 5.23%   |
| 301-350        | 25        | 3.96%   |
| 121-130        | 20        | 3.17%   |
| 71-80          | 16        | 2.54%   |
| 41-50          | 15        | 2.38%   |
| 351-500        | 14        | 2.22%   |
| 251-300        | 14        | 2.22%   |
| More than 1000 | 12        | 1.9%    |
| 61-70          | 10        | 1.58%   |
| 51-60          | 8         | 1.27%   |
| 131-140        | 7         | 1.11%   |
| 91-100         | 4         | 0.63%   |
| 111-120        | 3         | 0.48%   |
| 1-40           | 2         | 0.32%   |
| 501-1000       | 2         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 216       | 35.24%  |
| 101-120       | 194       | 31.65%  |
| 121-160       | 127       | 20.72%  |
| Unknown       | 44        | 7.18%   |
| 161-240       | 15        | 2.45%   |
| 1-50          | 12        | 1.96%   |
| More than 240 | 5         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 534       | 82.66%  |
| 2     | 73        | 11.3%   |
| 0     | 35        | 5.42%   |
| 3     | 4         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 354       | 35.4%   |
| Intel                             | 241       | 24.1%   |
| Qualcomm Atheros                  | 146       | 14.6%   |
| Broadcom                          | 80        | 8%      |
| Marvell Technology Group          | 21        | 2.1%    |
| Nvidia                            | 18        | 1.8%    |
| Broadcom Limited                  | 18        | 1.8%    |
| Ralink Technology                 | 17        | 1.7%    |
| Samsung Electronics               | 9         | 0.9%    |
| TP-Link                           | 8         | 0.8%    |
| Ralink                            | 8         | 0.8%    |
| Silicon Integrated Systems [SiS]  | 6         | 0.6%    |
| VIA Technologies                  | 5         | 0.5%    |
| MediaTek                          | 5         | 0.5%    |
| Huawei Technologies               | 5         | 0.5%    |
| JMicron Technology                | 4         | 0.4%    |
| Xiaomi                            | 3         | 0.3%    |
| Ericsson Business Mobile Networks | 3         | 0.3%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.2%    |
| Sitecom Europe                    | 2         | 0.2%    |
| NetGear                           | 2         | 0.2%    |
| Microsoft                         | 2         | 0.2%    |
| Linksys                           | 2         | 0.2%    |
| Lenovo                            | 2         | 0.2%    |
| Hewlett-Packard                   | 2         | 0.2%    |
| Edimax Technology                 | 2         | 0.2%    |
| DisplayLink                       | 2         | 0.2%    |
| Dell                              | 2         | 0.2%    |
| AVM                               | 2         | 0.2%    |
| Attansic Technology               | 2         | 0.2%    |
| ASUSTek Computer                  | 2         | 0.2%    |
| AMD                               | 2         | 0.2%    |
| ST-Ericsson                       | 1         | 0.1%    |
| Sierra Wireless                   | 1         | 0.1%    |
| Qualcomm                          | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.1%    |
| Microchip Technology              | 1         | 0.1%    |
| Mercucys                          | 1         | 0.1%    |
| Mellanox Technologies             | 1         | 0.1%    |
| Manta                             | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 212       | 18.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 64        | 5.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 15        | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.02%   |
| Intel Wireless 8265 / 8275                                              | 12        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.94%   |
| Intel Wireless 7260                                                     | 10        | 0.85%   |
| Intel WiFi Link 5100                                                    | 10        | 0.85%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 0.85%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.77%   |
| Intel I211 Gigabit Network Connection                                   | 9         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 8         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                       | 8         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.68%   |
| Nvidia MCP61 Ethernet                                                   | 8         | 0.68%   |
| Intel Wireless 3165                                                     | 8         | 0.68%   |
| Intel Wireless 8260                                                     | 7         | 0.6%    |
| Intel 82579V Gigabit Network Connection                                 | 7         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 0.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 6         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 6         | 0.51%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 6         | 0.51%   |
| Intel Wireless 7265                                                     | 6         | 0.51%   |
| Intel Wireless 3160                                                     | 6         | 0.51%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.51%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 166       | 31.98%  |
| Realtek Semiconductor                 | 115       | 22.16%  |
| Qualcomm Atheros                      | 113       | 21.77%  |
| Broadcom                              | 55        | 10.6%   |
| Ralink Technology                     | 17        | 3.28%   |
| Broadcom Limited                      | 10        | 1.93%   |
| TP-Link                               | 8         | 1.54%   |
| Ralink                                | 8         | 1.54%   |
| MediaTek                              | 4         | 0.77%   |
| Sitecom Europe                        | 2         | 0.39%   |
| NetGear                               | 2         | 0.39%   |
| Microsoft                             | 2         | 0.39%   |
| Linksys                               | 2         | 0.39%   |
| Edimax Technology                     | 2         | 0.39%   |
| AVM                                   | 2         | 0.39%   |
| ASUSTek Computer                      | 2         | 0.39%   |
| Xiaomi                                | 1         | 0.19%   |
| Sierra Wireless                       | 1         | 0.19%   |
| Mercucys                              | 1         | 0.19%   |
| Marvell Technology Group              | 1         | 0.19%   |
| Fibocom                               | 1         | 0.19%   |
| D-Link System                         | 1         | 0.19%   |
| Cisco Aironet Wireless Communications | 1         | 0.19%   |
| Belkin Components                     | 1         | 0.19%   |
| Askey Computer                        | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 4.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 4.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 3.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 3.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 2.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 2.28%   |
| Intel Wireless 8265 / 8275                                              | 12        | 2.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 2.09%   |
| Intel Wireless 7260                                                     | 10        | 1.9%    |
| Intel WiFi Link 5100                                                    | 10        | 1.9%    |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.52%   |
| Intel Wireless 3165                                                     | 8         | 1.52%   |
| Intel Wireless 8260                                                     | 7         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 1.14%   |
| Intel Wireless 7265                                                     | 6         | 1.14%   |
| Intel Wireless 3160                                                     | 6         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.95%   |
| Realtek 802.11n WLAN Adapter                                            | 5         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.95%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 5         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 4         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 309       | 50.08%  |
| Intel                            | 132       | 21.39%  |
| Qualcomm Atheros                 | 49        | 7.94%   |
| Broadcom                         | 31        | 5.02%   |
| Marvell Technology Group         | 20        | 3.24%   |
| Nvidia                           | 18        | 2.92%   |
| Samsung Electronics              | 9         | 1.46%   |
| Broadcom Limited                 | 8         | 1.3%    |
| Silicon Integrated Systems [SiS] | 6         | 0.97%   |
| VIA Technologies                 | 5         | 0.81%   |
| JMicron Technology               | 4         | 0.65%   |
| Huawei Technologies              | 4         | 0.65%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.32%   |
| Xiaomi                           | 2         | 0.32%   |
| Lenovo                           | 2         | 0.32%   |
| Hewlett-Packard                  | 2         | 0.32%   |
| DisplayLink                      | 2         | 0.32%   |
| Attansic Technology              | 2         | 0.32%   |
| Qualcomm                         | 1         | 0.16%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.16%   |
| Microchip Technology             | 1         | 0.16%   |
| MediaTek                         | 1         | 0.16%   |
| HTC (High Tech Computer)         | 1         | 0.16%   |
| Google                           | 1         | 0.16%   |
| Gemtek                           | 1         | 0.16%   |
| Davicom Semiconductor            | 1         | 0.16%   |
| ADMtek                           | 1         | 0.16%   |
| 3Com                             | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 212       | 33.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64        | 10.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 3.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 2.4%    |
| Intel I211 Gigabit Network Connection                             | 9         | 1.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 1.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 1.28%   |
| Nvidia MCP61 Ethernet                                             | 8         | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 0.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.96%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 6         | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.96%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.8%    |
| Intel 82573L Gigabit Ethernet Controller                          | 5         | 0.8%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.64%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4         | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4         | 0.64%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 3         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.48%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 3         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 577       | 53.03%  |
| WiFi     | 490       | 45.04%  |
| Modem    | 17        | 1.56%   |
| Unknown  | 4         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 358       | 54.99%  |
| Ethernet | 293       | 45.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 385       | 60.44%  |
| 1     | 234       | 36.73%  |
| 0     | 8         | 1.26%   |
| 3     | 6         | 0.94%   |
| 4     | 4         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 520       | 80.25%  |
| Yes  | 128       | 19.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 33.55%  |
| Realtek Semiconductor           | 49        | 15.65%  |
| Qualcomm Atheros Communications | 25        | 7.99%   |
| Broadcom                        | 25        | 7.99%   |
| Foxconn / Hon Hai               | 18        | 5.75%   |
| Cambridge Silicon Radio         | 18        | 5.75%   |
| Hewlett-Packard                 | 13        | 4.15%   |
| Lite-On Technology              | 12        | 3.83%   |
| Apple                           | 11        | 3.51%   |
| Dell                            | 9         | 2.88%   |
| IMC Networks                    | 8         | 2.56%   |
| ASUSTek Computer                | 5         | 1.6%    |
| Toshiba                         | 3         | 0.96%   |
| Foxconn International           | 3         | 0.96%   |
| Taiyo Yuden                     | 1         | 0.32%   |
| Realtek                         | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Qcom                            | 1         | 0.32%   |
| MediaTek                        | 1         | 0.32%   |
| Marvell Semiconductor           | 1         | 0.32%   |
| Askey Computer                  | 1         | 0.32%   |
| Alps Electric                   | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 47        | 15.02%  |
| Realtek Bluetooth Radio                                                             | 29        | 9.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 18        | 5.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 18        | 5.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 17        | 5.43%   |
| Intel AX201 Bluetooth                                                               | 15        | 4.79%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 3.51%   |
| Intel AX200 Bluetooth                                                               | 10        | 3.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 2.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 1.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.6%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.28%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.28%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 1.28%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.28%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.96%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.96%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 0.96%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.96%   |
| Foxconn / Hon Hai Acer Module                                                       | 3         | 0.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.96%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.64%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.64%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.64%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.64%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.64%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.64%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.64%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 467       | 55.86%  |
| AMD                              | 157       | 18.78%  |
| Nvidia                           | 142       | 16.99%  |
| C-Media Electronics              | 15        | 1.79%   |
| VIA Technologies                 | 9         | 1.08%   |
| Silicon Integrated Systems [SiS] | 8         | 0.96%   |
| GN Netcom                        | 5         | 0.6%    |
| Generalplus Technology           | 5         | 0.6%    |
| Creative Labs                    | 4         | 0.48%   |
| Logitech                         | 3         | 0.36%   |
| JMTek                            | 3         | 0.36%   |
| Yamaha                           | 2         | 0.24%   |
| Texas Instruments                | 2         | 0.24%   |
| Tenx Technology                  | 2         | 0.24%   |
| Xilinx                           | 1         | 0.12%   |
| Realtek Semiconductor            | 1         | 0.12%   |
| Plantronics                      | 1         | 0.12%   |
| Native Instruments               | 1         | 0.12%   |
| Micro Star International         | 1         | 0.12%   |
| M-Audio                          | 1         | 0.12%   |
| GYROCOM C&C                      | 1         | 0.12%   |
| Focusrite-Novation               | 1         | 0.12%   |
| Evolution Electronics            | 1         | 0.12%   |
| Dell                             | 1         | 0.12%   |
| Creative Technology              | 1         | 0.12%   |
| Audioengine                      | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 60        | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 51        | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 44        | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 42        | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 4.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 3.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 30        | 3.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 29        | 3%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 1.86%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 16        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 14        | 1.45%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 1.35%   |
| AMD High Definition Audio Controller                                                              | 12        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.93%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 9         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.93%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 0.83%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.72%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 7         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 0.62%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 0.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 42        | 22.83%  |
| Unknown                      | 34        | 18.48%  |
| SK hynix                     | 34        | 18.48%  |
| Kingston                     | 19        | 10.33%  |
| Crucial                      | 11        | 5.98%   |
| Micron Technology            | 8         | 4.35%   |
| Nanya Technology             | 5         | 2.72%   |
| G.Skill                      | 5         | 2.72%   |
| A-DATA Technology            | 4         | 2.17%   |
| Unknown (ABCD)               | 3         | 1.63%   |
| Smart                        | 3         | 1.63%   |
| Ramaxel Technology           | 3         | 1.63%   |
| Corsair                      | 3         | 1.63%   |
| Unknown                      | 2         | 1.09%   |
| Transcend                    | 1         | 0.54%   |
| PLEXHD                       | 1         | 0.54%   |
| Patriot Memory (PDP Systems) | 1         | 0.54%   |
| Patriot                      | 1         | 0.54%   |
| Kingmax                      | 1         | 0.54%   |
| Exceleram                    | 1         | 0.54%   |
| Elpida                       | 1         | 0.54%   |
| AVEXIR                       | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.52%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 1.02%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 2         | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.02%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.02%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Unknown                                                          | 2         | 1.02%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 0.51%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.51%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.51%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.51%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.51%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.51%   |
| Unknown RAM Module 512MB DIMM 667MT/s                            | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.51%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 39.52%  |
| DDR3    | 60        | 35.93%  |
| DDR2    | 16        | 9.58%   |
| SDRAM   | 8         | 4.79%   |
| DDR     | 6         | 3.59%   |
| Unknown | 6         | 3.59%   |
| LPDDR4  | 4         | 2.4%    |
| LPDDR3  | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 110       | 66.67%  |
| DIMM         | 51        | 30.91%  |
| Row Of Chips | 3         | 1.82%   |
| Unknown      | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 65        | 36.11%  |
| 4096    | 45        | 25%     |
| 2048    | 36        | 20%     |
| 16384   | 14        | 7.78%   |
| 1024    | 12        | 6.67%   |
| 32768   | 4         | 2.22%   |
| 512     | 3         | 1.67%   |
| Unknown | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 22.16%  |
| 2667    | 25        | 14.2%   |
| 3200    | 23        | 13.07%  |
| 2400    | 15        | 8.52%   |
| 1333    | 12        | 6.82%   |
| Unknown | 10        | 5.68%   |
| 800     | 9         | 5.11%   |
| 667     | 8         | 4.55%   |
| 533     | 4         | 2.27%   |
| 3266    | 3         | 1.7%    |
| 2133    | 3         | 1.7%    |
| 1334    | 3         | 1.7%    |
| 1067    | 3         | 1.7%    |
| 3600    | 2         | 1.14%   |
| 2666    | 2         | 1.14%   |
| 2048    | 2         | 1.14%   |
| 975     | 2         | 1.14%   |
| 4267    | 1         | 0.57%   |
| 4266    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3800    | 1         | 0.57%   |
| 3500    | 1         | 0.57%   |
| 3400    | 1         | 0.57%   |
| 2267    | 1         | 0.57%   |
| 1867    | 1         | 0.57%   |
| 1866    | 1         | 0.57%   |
| 1200    | 1         | 0.57%   |
| 400     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 41.18%  |
| Brother Industries  | 3         | 17.65%  |
| Samsung Electronics | 2         | 11.76%  |
| Canon               | 2         | 11.76%  |
| Seiko Epson         | 1         | 5.88%   |
| Ricoh               | 1         | 5.88%   |
| Konica Minolta      | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Brother MFC-L2685DW              | 2         | 11.76%  |
| Seiko Epson XP-3100 Series       | 1         | 5.88%   |
| Samsung SCX-3400 Series          | 1         | 5.88%   |
| Samsung ML-1670 Series           | 1         | 5.88%   |
| Ricoh SP C260SFNw                | 1         | 5.88%   |
| Konica Minolta 185               | 1         | 5.88%   |
| HP OfficeJet Pro 8730            | 1         | 5.88%   |
| HP LaserJet P1006                | 1         | 5.88%   |
| HP LaserJet 3050                 | 1         | 5.88%   |
| HP DeskJet F4200 series          | 1         | 5.88%   |
| HP DeskJet 2700 series           | 1         | 5.88%   |
| HP Deskjet 2540 series           | 1         | 5.88%   |
| HP Deskjet 1050 J410             | 1         | 5.88%   |
| Canon LaserShot LBP-1120 Printer | 1         | 5.88%   |
| Canon iP4200                     | 1         | 5.88%   |
| Brother HL-L2300D series         | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| HP ScanJet 3800c                              | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 19.94%  |
| IMC Networks                           | 32        | 8.99%   |
| Acer                                   | 27        | 7.58%   |
| Microdia                               | 25        | 7.02%   |
| Suyin                                  | 24        | 6.74%   |
| Sunplus Innovation Technology          | 23        | 6.46%   |
| Quanta                                 | 21        | 5.9%    |
| Realtek Semiconductor                  | 18        | 5.06%   |
| Logitech                               | 15        | 4.21%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.09%   |
| Apple                                  | 10        | 2.81%   |
| Silicon Motion                         | 8         | 2.25%   |
| Syntek                                 | 7         | 1.97%   |
| Luxvisions Innotech Limited            | 7         | 1.97%   |
| Z-Star Microelectronics                | 6         | 1.69%   |
| Ricoh                                  | 6         | 1.69%   |
| Importek                               | 5         | 1.4%    |
| Alcor Micro                            | 5         | 1.4%    |
| Microsoft                              | 3         | 0.84%   |
| Lite-On Technology                     | 3         | 0.84%   |
| Lenovo                                 | 3         | 0.84%   |
| ALi                                    | 3         | 0.84%   |
| Sunplus Technology                     | 2         | 0.56%   |
| OmniVision Technologies                | 2         | 0.56%   |
| Generalplus Technology                 | 2         | 0.56%   |
| Creative Technology                    | 2         | 0.56%   |
| Xiongmai                               | 1         | 0.28%   |
| WCM_USB                                | 1         | 0.28%   |
| USB Camera                             | 1         | 0.28%   |
| Unknown                                | 1         | 0.28%   |
| Service & Quality Technology           | 1         | 0.28%   |
| Samsung Electronics                    | 1         | 0.28%   |
| Pixart Imaging                         | 1         | 0.28%   |
| Nintendo                               | 1         | 0.28%   |
| MacroSilicon                           | 1         | 0.28%   |
| LG Electronics                         | 1         | 0.28%   |
| KYE Systems (Mouse Systems)            | 1         | 0.28%   |
| Intel                                  | 1         | 0.28%   |
| Huawei Technologies                    | 1         | 0.28%   |
| eMPIA Technology                       | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 12        | 3.36%   |
| Microdia Integrated_Webcam_HD                                  | 10        | 2.8%    |
| Acer Integrated Camera                                         | 9         | 2.52%   |
| Chicony HD WebCam                                              | 8         | 2.24%   |
| Quanta HP Webcam                                               | 7         | 1.96%   |
| Suyin HP TrueVision HD                                         | 5         | 1.4%    |
| Quanta HP TrueVision HD Camera                                 | 5         | 1.4%    |
| Logitech Webcam C270                                           | 5         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 5         | 1.4%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 5         | 1.4%    |
| IMC Networks Integrated Camera                                 | 5         | 1.4%    |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 1.4%    |
| Chicony HP TrueVision HD Camera                                | 5         | 1.4%    |
| Apple Built-in iSight                                          | 5         | 1.4%    |
| Sunplus HD WebCam                                              | 4         | 1.12%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 1.12%   |
| IMC Networks EasyCamera                                        | 4         | 1.12%   |
| Chicony USB 2.0 Camera                                         | 4         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.12%   |
| Apple iPhone5/5C/5S/6                                          | 4         | 1.12%   |
| Syntek Integrated Camera                                       | 3         | 0.84%   |
| Suyin HD Video WebCam                                          | 3         | 0.84%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 3         | 0.84%   |
| Suyin 1.3M HD WebCam                                           | 3         | 0.84%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 3         | 0.84%   |
| Sunplus HP TrueVision HD Camera                                | 3         | 0.84%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 3         | 0.84%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.84%   |
| Quanta VGA WebCam                                              | 3         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 3         | 0.84%   |
| Microdia Integrated Webcam HD                                  | 3         | 0.84%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 3         | 0.84%   |
| Logitech Webcam C310                                           | 3         | 0.84%   |
| Chicony 2.0M UVC Webcam / CNF7129                              | 3         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 0.84%   |
| Alcor Micro USB 2.0 Camera                                     | 3         | 0.84%   |
| Acer USB Camera                                                | 3         | 0.84%   |
| Acer Lenovo EasyCamera                                         | 3         | 0.84%   |
| Acer HD Webcam                                                 | 3         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 39.22%  |
| AuthenTec                  | 10        | 19.61%  |
| Synaptics                  | 5         | 9.8%    |
| STMicroelectronics         | 4         | 7.84%   |
| LighTuning Technology      | 3         | 5.88%   |
| Elan Microelectronics      | 3         | 5.88%   |
| Upek                       | 2         | 3.92%   |
| Shenzhen Goodix Technology | 2         | 3.92%   |
| Samsung Electronics        | 1         | 1.96%   |
| Focal-systems.Corp         | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 9.8%    |
| Validity Sensors VFS301 Fingerprint Reader             | 4         | 7.84%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 7.84%   |
| Unknown                                                | 4         | 7.84%   |
| Validity Sensors VFS451 Fingerprint Reader             | 3         | 5.88%   |
| Elan ELAN:Fingerprint                                  | 3         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 5.88%   |
| AuthenTec AES1600                                      | 3         | 5.88%   |
| Validity Sensors VFS491                                | 2         | 3.92%   |
| Validity Sensors Synaptics WBDI                        | 2         | 3.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 3.92%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 3.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 3.92%   |
| AuthenTec Fingerprint Sensor                           | 2         | 3.92%   |
| AuthenTec AES2810                                      | 2         | 3.92%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.96%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 1.96%   |
| Validity Sensors Fingerprint scanner                   | 1         | 1.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 1.96%   |
| Samsung Fingerprint Sensor Device - 730B               | 1         | 1.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 1.96%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 1.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 13        | 54.17%  |
| O2 Micro                          | 4         | 16.67%  |
| Alcor Micro                       | 2         | 8.33%   |
| VASCO Data Security International | 1         | 4.17%   |
| OmniKey                           | 1         | 4.17%   |
| Lenovo                            | 1         | 4.17%   |
| Jing-Mold Enterprise              | 1         | 4.17%   |
| Gemalto (was Gemplus)             | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 29.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 8.33%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 4.17%   |
| OmniKey CardMan 1021                                                         | 1         | 4.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.17%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 4.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 4.17%   |
| Broadcom 5880                                                                | 1         | 4.17%   |
| Broadcom 58200                                                               | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 429       | 66.1%   |
| 1     | 172       | 26.5%   |
| 2     | 32        | 4.93%   |
| 3     | 12        | 1.85%   |
| 4     | 3         | 0.46%   |
| 6     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 86        | 31.5%   |
| Net/wireless             | 57        | 20.88%  |
| Fingerprint reader       | 50        | 18.32%  |
| Multimedia controller    | 23        | 8.42%   |
| Chipcard                 | 20        | 7.33%   |
| Communication controller | 12        | 4.4%    |
| Storage                  | 6         | 2.2%    |
| Unassigned class         | 3         | 1.1%    |
| Network                  | 3         | 1.1%    |
| Net/ethernet             | 2         | 0.73%   |
| Flash memory             | 2         | 0.73%   |
| Camera                   | 2         | 0.73%   |
| Bluetooth                | 2         | 0.73%   |
| Storage/ide              | 1         | 0.37%   |
| Sound                    | 1         | 0.37%   |
| Modem                    | 1         | 0.37%   |
| Dvb card                 | 1         | 0.37%   |
| Card reader              | 1         | 0.37%   |

