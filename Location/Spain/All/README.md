Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 6133

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [d19e0fb48b](https://linux-hardware.org/?probe=d19e0fb48b) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4707a778dc](https://linux-hardware.org/?probe=4707a778dc) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [255a0a928a](https://linux-hardware.org/?probe=255a0a928a) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [77d108e391](https://linux-hardware.org/?probe=77d108e391) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| HP            | 2B35                        | Desktop     | [724e0d61e3](https://linux-hardware.org/?probe=724e0d61e3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Acer          | Aspire X1900                | Desktop     | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | Notebook    | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [173834876c](https://linux-hardware.org/?probe=173834876c) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | Notebook    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [40b47d9065](https://linux-hardware.org/?probe=40b47d9065) | Sep 23, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [d00d31309a](https://linux-hardware.org/?probe=d00d31309a) | Sep 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [cb519b4bfe](https://linux-hardware.org/?probe=cb519b4bfe) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Sony          | VPCEB1Z1E                   | Notebook    | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | Notebook    | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Minix         | NEO G41V-4 Max              | Desktop     | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Unknown       | 1.0                         | Desktop     | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | Notebook    | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [f10501b259](https://linux-hardware.org/?probe=f10501b259) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [7ea35cc80a](https://linux-hardware.org/?probe=7ea35cc80a) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0b32a9e842](https://linux-hardware.org/?probe=0b32a9e842) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [fab04fe2c7](https://linux-hardware.org/?probe=fab04fe2c7) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | Notebook    | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | Notebook    | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | Notebook    | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| BESSTAR Te... | T3 MRD                      | Notebook    | [0b03396c93](https://linux-hardware.org/?probe=0b03396c93) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Acer          | Aspire X3990                | Desktop     | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [c5ebccdc5d](https://linux-hardware.org/?probe=c5ebccdc5d) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [74a9860a2e](https://linux-hardware.org/?probe=74a9860a2e) | Sep 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | Notebook    | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [93a5a7089c](https://linux-hardware.org/?probe=93a5a7089c) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | Notebook    | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | Notebook    | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [6fb2f6034c](https://linux-hardware.org/?probe=6fb2f6034c) | Sep 10, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [0caf1e7324](https://linux-hardware.org/?probe=0caf1e7324) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [06d3f051d1](https://linux-hardware.org/?probe=06d3f051d1) | Sep 09, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Medion        | H61H2-LM3 V1.0              | Desktop     | [96b497db35](https://linux-hardware.org/?probe=96b497db35) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [c0ad8b81fa](https://linux-hardware.org/?probe=c0ad8b81fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9128ddb611](https://linux-hardware.org/?probe=9128ddb611) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6596b0d415](https://linux-hardware.org/?probe=6596b0d415) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [088dad5cba](https://linux-hardware.org/?probe=088dad5cba) | Sep 02, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b84d0acafb](https://linux-hardware.org/?probe=b84d0acafb) | Sep 01, 2022 |
| Dell          | 07PXPY A04                  | Server      | [f0b9cd86ef](https://linux-hardware.org/?probe=f0b9cd86ef) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | Notebook    | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3955b91269](https://linux-hardware.org/?probe=3955b91269) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3148482797](https://linux-hardware.org/?probe=3148482797) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [12033c4a8b](https://linux-hardware.org/?probe=12033c4a8b) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| MSI           | H97M-G43                    | Desktop     | [978d5b45be](https://linux-hardware.org/?probe=978d5b45be) | Aug 31, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [71ce0b707c](https://linux-hardware.org/?probe=71ce0b707c) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [b9d306c31b](https://linux-hardware.org/?probe=b9d306c31b) | Aug 31, 2022 |
| HP            | Compaq 8510w                | Notebook    | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | F3F                         | Notebook    | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [64cefbec58](https://linux-hardware.org/?probe=64cefbec58) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | Notebook    | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [437b0cd64f](https://linux-hardware.org/?probe=437b0cd64f) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [28ebe8cc1f](https://linux-hardware.org/?probe=28ebe8cc1f) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| Gigabyte      | H81M-D3H                    | Desktop     | [89ced19bd4](https://linux-hardware.org/?probe=89ced19bd4) | Aug 25, 2022 |
| Fujitsu       | D3173-A1 S26361-D3173-A1    | Mini pc     | [273ce0954a](https://linux-hardware.org/?probe=273ce0954a) | Aug 25, 2022 |
| MSI           | H97M-G43                    | Desktop     | [3f781247f0](https://linux-hardware.org/?probe=3f781247f0) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | Notebook    | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HP            | 3647h                       | Desktop     | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | Notebook    | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [2edb743fb5](https://linux-hardware.org/?probe=2edb743fb5) | Aug 20, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [216ea6f436](https://linux-hardware.org/?probe=216ea6f436) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Gateway       | DS50                        | Desktop     | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [02f9463f2b](https://linux-hardware.org/?probe=02f9463f2b) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | Notebook    | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| sunxi         | Unknown                     | Soc         | [a57117f63f](https://linux-hardware.org/?probe=a57117f63f) | Aug 15, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [f223d64d8f](https://linux-hardware.org/?probe=f223d64d8f) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [26811058c5](https://linux-hardware.org/?probe=26811058c5) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b69d60f568](https://linux-hardware.org/?probe=b69d60f568) | Aug 15, 2022 |
| GPD           | G1618-03                    | Notebook    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | Notebook    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Pegatron      | 2A94                        | Desktop     | [81b0cdd377](https://linux-hardware.org/?probe=81b0cdd377) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fd9bae65fa](https://linux-hardware.org/?probe=fd9bae65fa) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [1840f48c85](https://linux-hardware.org/?probe=1840f48c85) | Aug 12, 2022 |
| Dell          | Latitude D630               | Notebook    | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [be29e8b357](https://linux-hardware.org/?probe=be29e8b357) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | Notebook    | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | 3397                        | Desktop     | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [f04f6e3bed](https://linux-hardware.org/?probe=f04f6e3bed) | Aug 07, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [305bf6182f](https://linux-hardware.org/?probe=305bf6182f) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | Notebook    | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| ASUSTek       | M3A78                       | Desktop     | [bda5207234](https://linux-hardware.org/?probe=bda5207234) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | Notebook    | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ab497e8975](https://linux-hardware.org/?probe=ab497e8975) | Aug 04, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f013fa996e](https://linux-hardware.org/?probe=f013fa996e) | Aug 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [c290aae7c6](https://linux-hardware.org/?probe=c290aae7c6) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [19d2273e6b](https://linux-hardware.org/?probe=19d2273e6b) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [8e83e6141d](https://linux-hardware.org/?probe=8e83e6141d) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Acer          | Aspire X3470                | Desktop     | [88ad041430](https://linux-hardware.org/?probe=88ad041430) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | 2AF7                        | Desktop     | [da51487005](https://linux-hardware.org/?probe=da51487005) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e3a44e4c5b](https://linux-hardware.org/?probe=e3a44e4c5b) | Jul 30, 2022 |
| HP            | Compaq 8510p                | Notebook    | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [db241f583d](https://linux-hardware.org/?probe=db241f583d) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | Notebook    | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [d29d943a24](https://linux-hardware.org/?probe=d29d943a24) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | Notebook    | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | Notebook    | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [6b300beb70](https://linux-hardware.org/?probe=6b300beb70) | Jul 25, 2022 |
| Acer          | Aspire 5749                 | Notebook    | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [c7c46e080e](https://linux-hardware.org/?probe=c7c46e080e) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7cc616f3c8](https://linux-hardware.org/?probe=7cc616f3c8) | Jul 24, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [ce14e41b96](https://linux-hardware.org/?probe=ce14e41b96) | Jul 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| Dell          | 0GM819                      | Desktop     | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [89fadaa563](https://linux-hardware.org/?probe=89fadaa563) | Jul 23, 2022 |
| HP            | Stream Notebook             | Notebook    | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | Notebook    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| Dell          | 0GM819                      | Desktop     | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [7ff3bd3639](https://linux-hardware.org/?probe=7ff3bd3639) | Jul 20, 2022 |
| Foxconn       | ETON                        | Desktop     | [1686897e74](https://linux-hardware.org/?probe=1686897e74) | Jul 20, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [67faad589b](https://linux-hardware.org/?probe=67faad589b) | Jul 19, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | Notebook    | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | Notebook    | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [03fca40d38](https://linux-hardware.org/?probe=03fca40d38) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | Notebook    | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| MSI           | Boston                      | Desktop     | [c1474f9d2f](https://linux-hardware.org/?probe=c1474f9d2f) | Jul 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c7a2ebd9dc](https://linux-hardware.org/?probe=c7a2ebd9dc) | Jul 15, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [383c62eca2](https://linux-hardware.org/?probe=383c62eca2) | Jul 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | Notebook    | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [3fe93a38f6](https://linux-hardware.org/?probe=3fe93a38f6) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Acer          | Aspire X3470                | Desktop     | [61b7216da0](https://linux-hardware.org/?probe=61b7216da0) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [3ec331da1f](https://linux-hardware.org/?probe=3ec331da1f) | Jul 12, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [26c70348e9](https://linux-hardware.org/?probe=26c70348e9) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | 318D                        | All in one  | [6c8aa85c66](https://linux-hardware.org/?probe=6c8aa85c66) | Jul 10, 2022 |
| HP            | 805E                        | All in one  | [c7570f51e8](https://linux-hardware.org/?probe=c7570f51e8) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [75f0ca97b8](https://linux-hardware.org/?probe=75f0ca97b8) | Jul 08, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [560e81bb64](https://linux-hardware.org/?probe=560e81bb64) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [4f57a8d7f4](https://linux-hardware.org/?probe=4f57a8d7f4) | Jul 08, 2022 |
| Dell          | Latitude 5285               | Notebook    | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| HP            | 18E7                        | Desktop     | [68781cd22f](https://linux-hardware.org/?probe=68781cd22f) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [aed7de4f94](https://linux-hardware.org/?probe=aed7de4f94) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [8e5892c130](https://linux-hardware.org/?probe=8e5892c130) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | Notebook    | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| MSI           | Z87 MPOWER                  | Desktop     | [ba26baf84a](https://linux-hardware.org/?probe=ba26baf84a) | Jun 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [6dff126482](https://linux-hardware.org/?probe=6dff126482) | Jun 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| HP            | 3647h                       | Desktop     | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [ace3582eee](https://linux-hardware.org/?probe=ace3582eee) | Jun 28, 2022 |
| HP            | 805E                        | All in one  | [efbad579d1](https://linux-hardware.org/?probe=efbad579d1) | Jun 27, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [5d18d90cda](https://linux-hardware.org/?probe=5d18d90cda) | Jun 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [6c18625cb3](https://linux-hardware.org/?probe=6c18625cb3) | Jun 27, 2022 |
| ASUSTek       | P5K                         | Desktop     | [e401eb71bc](https://linux-hardware.org/?probe=e401eb71bc) | Jun 27, 2022 |
| Lenovo        | YB1-X91F                    | Convertible | [0a0f43a4af](https://linux-hardware.org/?probe=0a0f43a4af) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [48cbc869da](https://linux-hardware.org/?probe=48cbc869da) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [ea31080862](https://linux-hardware.org/?probe=ea31080862) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | Notebook    | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | Notebook    | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [2d1c05fefc](https://linux-hardware.org/?probe=2d1c05fefc) | Jun 26, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [5047471b41](https://linux-hardware.org/?probe=5047471b41) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [874e7081c6](https://linux-hardware.org/?probe=874e7081c6) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [b91a1b0ded](https://linux-hardware.org/?probe=b91a1b0ded) | Jun 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | Notebook    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| Acer          | Aspire X1700                | Desktop     | [6a67f8cba0](https://linux-hardware.org/?probe=6a67f8cba0) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | Notebook    | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | Notebook    | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | Notebook    | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | 18E7                        | Desktop     | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [5f5c3fcba9](https://linux-hardware.org/?probe=5f5c3fcba9) | Jun 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [a5d23b52d1](https://linux-hardware.org/?probe=a5d23b52d1) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d22ca1b39a](https://linux-hardware.org/?probe=d22ca1b39a) | Jun 12, 2022 |
| HP            | 1496                        | Desktop     | [d6fba97175](https://linux-hardware.org/?probe=d6fba97175) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 460 20EMCT... | Convertible | [2e1daf6e92](https://linux-hardware.org/?probe=2e1daf6e92) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a3ca1ea153](https://linux-hardware.org/?probe=a3ca1ea153) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |
| Alienware     | m15 R4                      | Notebook    | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [839663a1af](https://linux-hardware.org/?probe=839663a1af) | Jun 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [eb7ee3a693](https://linux-hardware.org/?probe=eb7ee3a693) | Jun 10, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| HP            | Compaq 6715b (GR667ET#AB... | Notebook    | [44de2345bb](https://linux-hardware.org/?probe=44de2345bb) | Jun 09, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [40c1095611](https://linux-hardware.org/?probe=40c1095611) | Jun 08, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [ceae668577](https://linux-hardware.org/?probe=ceae668577) | Jun 07, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [4ca91078a2](https://linux-hardware.org/?probe=4ca91078a2) | Jun 07, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [c46dcc9b6f](https://linux-hardware.org/?probe=c46dcc9b6f) | Jun 07, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 805E                        | All in one  | [68c1d719ea](https://linux-hardware.org/?probe=68c1d719ea) | Jun 05, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Lenovo        | 318D                        | All in one  | [266c9dd651](https://linux-hardware.org/?probe=266c9dd651) | Jun 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3dd8394bb5](https://linux-hardware.org/?probe=3dd8394bb5) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [1f88a2c07c](https://linux-hardware.org/?probe=1f88a2c07c) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [3cc513c431](https://linux-hardware.org/?probe=3cc513c431) | Jun 04, 2022 |
| Acer          | F90M R01-D1                 | Desktop     | [ecc8d1f955](https://linux-hardware.org/?probe=ecc8d1f955) | Jun 03, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb96d40d38](https://linux-hardware.org/?probe=bb96d40d38) | Jun 03, 2022 |
| eMachines     | eME732                      | Notebook    | [c6d57c850c](https://linux-hardware.org/?probe=c6d57c850c) | Jun 03, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [8c60f1e8e0](https://linux-hardware.org/?probe=8c60f1e8e0) | Jun 03, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2e621739e6](https://linux-hardware.org/?probe=2e621739e6) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [3210714de1](https://linux-hardware.org/?probe=3210714de1) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [9b01043ab8](https://linux-hardware.org/?probe=9b01043ab8) | Jun 03, 2022 |
| Chuwi         | UBOOK                       | Convertible | [6e2b3d6ee7](https://linux-hardware.org/?probe=6e2b3d6ee7) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | TX201LA                     | Notebook    | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | Notebook    | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [185587d5e1](https://linux-hardware.org/?probe=185587d5e1) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [65f67bae3c](https://linux-hardware.org/?probe=65f67bae3c) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [41cad28720](https://linux-hardware.org/?probe=41cad28720) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | Notebook    | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [c996bce6b5](https://linux-hardware.org/?probe=c996bce6b5) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | Notebook    | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fe1f2d0f](https://linux-hardware.org/?probe=08fe1f2d0f) | May 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1dfbe3337](https://linux-hardware.org/?probe=a1dfbe3337) | May 31, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [22b617425d](https://linux-hardware.org/?probe=22b617425d) | May 31, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [ab330f08f1](https://linux-hardware.org/?probe=ab330f08f1) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580abb0cf9](https://linux-hardware.org/?probe=580abb0cf9) | May 30, 2022 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [867e55cbfe](https://linux-hardware.org/?probe=867e55cbfe) | May 30, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [4c4e4e6690](https://linux-hardware.org/?probe=4c4e4e6690) | May 30, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [23d012c738](https://linux-hardware.org/?probe=23d012c738) | May 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [4fadee73e4](https://linux-hardware.org/?probe=4fadee73e4) | May 29, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [432c1135b8](https://linux-hardware.org/?probe=432c1135b8) | May 29, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [60128f5782](https://linux-hardware.org/?probe=60128f5782) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [b0e56c97d2](https://linux-hardware.org/?probe=b0e56c97d2) | May 28, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [774d5a9eae](https://linux-hardware.org/?probe=774d5a9eae) | May 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2b5230c5f8](https://linux-hardware.org/?probe=2b5230c5f8) | May 27, 2022 |
| ASUSTek       | P5K                         | Desktop     | [b816732403](https://linux-hardware.org/?probe=b816732403) | May 27, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [475179d795](https://linux-hardware.org/?probe=475179d795) | May 27, 2022 |
| MSI           | PR600                       | Notebook    | [09b736e706](https://linux-hardware.org/?probe=09b736e706) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| Medion        | S6421 MD60703               | Notebook    | [9fffed019c](https://linux-hardware.org/?probe=9fffed019c) | May 27, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [e4082f489e](https://linux-hardware.org/?probe=e4082f489e) | May 27, 2022 |
| HP            | 8767 A                      | Desktop     | [553a8de02a](https://linux-hardware.org/?probe=553a8de02a) | May 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4673dbdffc](https://linux-hardware.org/?probe=4673dbdffc) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0d0af584d5](https://linux-hardware.org/?probe=0d0af584d5) | May 26, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [57d71fca8a](https://linux-hardware.org/?probe=57d71fca8a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [cca34ae407](https://linux-hardware.org/?probe=cca34ae407) | May 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d998776096](https://linux-hardware.org/?probe=d998776096) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [8e49a588d4](https://linux-hardware.org/?probe=8e49a588d4) | May 25, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [29dd7760ba](https://linux-hardware.org/?probe=29dd7760ba) | May 25, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [2ab0d31bce](https://linux-hardware.org/?probe=2ab0d31bce) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | Notebook    | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ca5eb0e4ff](https://linux-hardware.org/?probe=ca5eb0e4ff) | May 24, 2022 |
| MSI           | Prestige 15 A11SCS          | Notebook    | [2433529434](https://linux-hardware.org/?probe=2433529434) | May 24, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [bb4ce9afdd](https://linux-hardware.org/?probe=bb4ce9afdd) | May 24, 2022 |
| Unknown       | Aspire E                    | Notebook    | [d437b15b97](https://linux-hardware.org/?probe=d437b15b97) | May 24, 2022 |
| Unknown       | Aspire E                    | Notebook    | [f46b38824f](https://linux-hardware.org/?probe=f46b38824f) | May 24, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [dbc555961b](https://linux-hardware.org/?probe=dbc555961b) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| HP            | 15                          | Notebook    | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8cd4fba0ca](https://linux-hardware.org/?probe=8cd4fba0ca) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c4c8431707](https://linux-hardware.org/?probe=c4c8431707) | May 22, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [eda69f1faf](https://linux-hardware.org/?probe=eda69f1faf) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a8e1b16b1b](https://linux-hardware.org/?probe=a8e1b16b1b) | May 22, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [85fe027fff](https://linux-hardware.org/?probe=85fe027fff) | May 22, 2022 |
| Dell          | G15 5510                    | Notebook    | [0ca1f736f9](https://linux-hardware.org/?probe=0ca1f736f9) | May 22, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [c146b79bd6](https://linux-hardware.org/?probe=c146b79bd6) | May 22, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [a4275c42f4](https://linux-hardware.org/?probe=a4275c42f4) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c687aa039e](https://linux-hardware.org/?probe=c687aa039e) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b8b132df34](https://linux-hardware.org/?probe=b8b132df34) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| Packard Be... | MCP73PV                     | Desktop     | [14085bdcf2](https://linux-hardware.org/?probe=14085bdcf2) | May 20, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [2f1ec161d1](https://linux-hardware.org/?probe=2f1ec161d1) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [42315f5cab](https://linux-hardware.org/?probe=42315f5cab) | May 19, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [48e5424ecb](https://linux-hardware.org/?probe=48e5424ecb) | May 19, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [a941ac6fa0](https://linux-hardware.org/?probe=a941ac6fa0) | May 19, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [189b62a372](https://linux-hardware.org/?probe=189b62a372) | May 19, 2022 |
| HP            | 8924 0100                   | All in one  | [67c69eba1d](https://linux-hardware.org/?probe=67c69eba1d) | May 19, 2022 |
| HP            | 8924 0100                   | All in one  | [496b64fffa](https://linux-hardware.org/?probe=496b64fffa) | May 19, 2022 |
| HP            | 8591                        | Desktop     | [60c5d4f8ca](https://linux-hardware.org/?probe=60c5d4f8ca) | May 19, 2022 |
| Dell          | Latitude E4310              | Notebook    | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| HP            | 8591                        | Desktop     | [fd05ae27e7](https://linux-hardware.org/?probe=fd05ae27e7) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [badf4d0a88](https://linux-hardware.org/?probe=badf4d0a88) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [7d96e10672](https://linux-hardware.org/?probe=7d96e10672) | May 17, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| HP            | 8924 0100                   | All in one  | [ba5d4617f9](https://linux-hardware.org/?probe=ba5d4617f9) | May 17, 2022 |
| Lenovo        | G580 2189                   | Notebook    | [e7de790c8a](https://linux-hardware.org/?probe=e7de790c8a) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| HP            | 885E A01                    | All in one  | [6b6dd9140a](https://linux-hardware.org/?probe=6b6dd9140a) | May 16, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [bccdb55064](https://linux-hardware.org/?probe=bccdb55064) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [70cde2437b](https://linux-hardware.org/?probe=70cde2437b) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS0LE00    | Notebook    | [59eecf466b](https://linux-hardware.org/?probe=59eecf466b) | May 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [dd305c13de](https://linux-hardware.org/?probe=dd305c13de) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| HP            | 8433 11                     | Desktop     | [d3f305a093](https://linux-hardware.org/?probe=d3f305a093) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [f367f3bb66](https://linux-hardware.org/?probe=f367f3bb66) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e1fc077918](https://linux-hardware.org/?probe=e1fc077918) | May 14, 2022 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2ac5991afa](https://linux-hardware.org/?probe=2ac5991afa) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| Medion        | Z370H4-EM                   | Desktop     | [2030abcd26](https://linux-hardware.org/?probe=2030abcd26) | May 12, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [8134289438](https://linux-hardware.org/?probe=8134289438) | May 12, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8328bbecb9](https://linux-hardware.org/?probe=8328bbecb9) | May 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a6f3293aea](https://linux-hardware.org/?probe=a6f3293aea) | May 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4f5ac891f4](https://linux-hardware.org/?probe=4f5ac891f4) | May 11, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f720d9e031](https://linux-hardware.org/?probe=f720d9e031) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e6d1749248](https://linux-hardware.org/?probe=e6d1749248) | May 10, 2022 |
| MSI           | Modern 14 B11MO             | Notebook    | [75bc7c18db](https://linux-hardware.org/?probe=75bc7c18db) | May 10, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [02925e8fac](https://linux-hardware.org/?probe=02925e8fac) | May 10, 2022 |
| Acer          | TravelMate 6592             | Notebook    | [353516147d](https://linux-hardware.org/?probe=353516147d) | May 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ae80aa69fe](https://linux-hardware.org/?probe=ae80aa69fe) | May 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ceaf962cba](https://linux-hardware.org/?probe=ceaf962cba) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| ECS           | H81H3-I                     | Desktop     | [e184359c46](https://linux-hardware.org/?probe=e184359c46) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f269fd3294](https://linux-hardware.org/?probe=f269fd3294) | May 09, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [29c0818bcd](https://linux-hardware.org/?probe=29c0818bcd) | May 08, 2022 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [39f623cf4d](https://linux-hardware.org/?probe=39f623cf4d) | May 08, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [1d37964706](https://linux-hardware.org/?probe=1d37964706) | May 08, 2022 |
| MSI           | GE62 2QD                    | Notebook    | [cef8637026](https://linux-hardware.org/?probe=cef8637026) | May 08, 2022 |
| SLIMBOOK      | Essential15L                | Notebook    | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | Notebook    | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [255ff705ac](https://linux-hardware.org/?probe=255ff705ac) | May 07, 2022 |
| Acer          | Aspire M1935                | Desktop     | [a679a25c13](https://linux-hardware.org/?probe=a679a25c13) | May 07, 2022 |
| Acer          | Aspire M1935                | Desktop     | [62424ad96d](https://linux-hardware.org/?probe=62424ad96d) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [c0d0f6435b](https://linux-hardware.org/?probe=c0d0f6435b) | May 06, 2022 |
| HP            | 84FD                        | Desktop     | [f99c153a46](https://linux-hardware.org/?probe=f99c153a46) | May 06, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Compaq 15                   | Notebook    | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [1467c3bb41](https://linux-hardware.org/?probe=1467c3bb41) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [e8556f4acf](https://linux-hardware.org/?probe=e8556f4acf) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [917add86ab](https://linux-hardware.org/?probe=917add86ab) | May 05, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [c5fc878a83](https://linux-hardware.org/?probe=c5fc878a83) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| ASRock        | FM2A78M Pro4+               | Desktop     | [7a00557ba5](https://linux-hardware.org/?probe=7a00557ba5) | May 05, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [d6293e8334](https://linux-hardware.org/?probe=d6293e8334) | May 05, 2022 |
| HP            | 1998                        | Desktop     | [b35fc936e5](https://linux-hardware.org/?probe=b35fc936e5) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [0afdbf373d](https://linux-hardware.org/?probe=0afdbf373d) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a30b11f1a0](https://linux-hardware.org/?probe=a30b11f1a0) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ecc7f176ff](https://linux-hardware.org/?probe=ecc7f176ff) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| Acer          | Aspire one 1-131            | Notebook    | [ade813cf7f](https://linux-hardware.org/?probe=ade813cf7f) | May 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d30c5337d6](https://linux-hardware.org/?probe=d30c5337d6) | May 02, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [37dfe53a95](https://linux-hardware.org/?probe=37dfe53a95) | May 02, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [aff42aff28](https://linux-hardware.org/?probe=aff42aff28) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0698d33be4](https://linux-hardware.org/?probe=0698d33be4) | May 02, 2022 |
| MSI           | H170A PC MATE               | Desktop     | [3ebb871ecc](https://linux-hardware.org/?probe=3ebb871ecc) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Notebook                    | Notebook    | [3bdd2a5e96](https://linux-hardware.org/?probe=3bdd2a5e96) | May 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Lenovo        | ThinkCentre M58p 6137E61    | Desktop     | [dbf0d596fc](https://linux-hardware.org/?probe=dbf0d596fc) | May 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| HP            | 650                         | Notebook    | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | TravelMate 6592             | Notebook    | [7d4878ff33](https://linux-hardware.org/?probe=7d4878ff33) | Apr 29, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [dc1c531e45](https://linux-hardware.org/?probe=dc1c531e45) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | Notebook    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | Desktop     | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [c3dad3331c](https://linux-hardware.org/?probe=c3dad3331c) | Apr 28, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| ASUSTek       | Maximus II Formula          | Desktop     | [66a4342140](https://linux-hardware.org/?probe=66a4342140) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| MSI           | H170A PC MATE               | Desktop     | [558be4bee8](https://linux-hardware.org/?probe=558be4bee8) | Apr 26, 2022 |
| Dell          | G15 5510                    | Notebook    | [5126d58147](https://linux-hardware.org/?probe=5126d58147) | Apr 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [3fcb247b21](https://linux-hardware.org/?probe=3fcb247b21) | Apr 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [23747b18ed](https://linux-hardware.org/?probe=23747b18ed) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [a1ff9cf092](https://linux-hardware.org/?probe=a1ff9cf092) | Apr 24, 2022 |
| MSI           | GX700                       | Notebook    | [b2cc52d381](https://linux-hardware.org/?probe=b2cc52d381) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | Notebook    | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [347ded3d71](https://linux-hardware.org/?probe=347ded3d71) | Apr 23, 2022 |
| Foxconn       | 945 7AD Series              | Desktop     | [04346c58f5](https://linux-hardware.org/?probe=04346c58f5) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [14089322a6](https://linux-hardware.org/?probe=14089322a6) | Apr 23, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| Lenovo        | ThinkPad P53 20QN000ESP     | Notebook    | [16b3189bd8](https://linux-hardware.org/?probe=16b3189bd8) | Apr 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7d38b3b29f](https://linux-hardware.org/?probe=7d38b3b29f) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [61d45f784c](https://linux-hardware.org/?probe=61d45f784c) | Apr 21, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [18578239d6](https://linux-hardware.org/?probe=18578239d6) | Apr 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [8034b9ae8c](https://linux-hardware.org/?probe=8034b9ae8c) | Apr 21, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [37ec4fb91d](https://linux-hardware.org/?probe=37ec4fb91d) | Apr 21, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [e1c710c88f](https://linux-hardware.org/?probe=e1c710c88f) | Apr 21, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [8e6566a555](https://linux-hardware.org/?probe=8e6566a555) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0ceaadd5e3](https://linux-hardware.org/?probe=0ceaadd5e3) | Apr 20, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [bc5f8558f3](https://linux-hardware.org/?probe=bc5f8558f3) | Apr 20, 2022 |
| Acer          | Aspire 9410                 | Notebook    | [f6c795c09a](https://linux-hardware.org/?probe=f6c795c09a) | Apr 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| eMachines     | D730                        | Notebook    | [09350021b3](https://linux-hardware.org/?probe=09350021b3) | Apr 20, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a9126e3886](https://linux-hardware.org/?probe=a9126e3886) | Apr 19, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | Notebook    | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a5584e7ec2](https://linux-hardware.org/?probe=a5584e7ec2) | Apr 18, 2022 |
| Chuwi         | Unknown                     | Notebook    | [a44bd392c5](https://linux-hardware.org/?probe=a44bd392c5) | Apr 18, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [10e97d2168](https://linux-hardware.org/?probe=10e97d2168) | Apr 18, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [c278a421cd](https://linux-hardware.org/?probe=c278a421cd) | Apr 18, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [fb3e0b6b22](https://linux-hardware.org/?probe=fb3e0b6b22) | Apr 18, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [e693d05883](https://linux-hardware.org/?probe=e693d05883) | Apr 17, 2022 |
| Unknown       | Unknown                     | All in one  | [85f7750f62](https://linux-hardware.org/?probe=85f7750f62) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4058d0c1ca](https://linux-hardware.org/?probe=4058d0c1ca) | Apr 17, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [d921190f7e](https://linux-hardware.org/?probe=d921190f7e) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [4ce545cc86](https://linux-hardware.org/?probe=4ce545cc86) | Apr 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a016ec1bce](https://linux-hardware.org/?probe=a016ec1bce) | Apr 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [65edd32378](https://linux-hardware.org/?probe=65edd32378) | Apr 16, 2022 |
| ASUSTek       | P5VD2-MX                    | Desktop     | [57fec52891](https://linux-hardware.org/?probe=57fec52891) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | Notebook    | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Medion        | MS-7728                     | Desktop     | [443a5ff3dd](https://linux-hardware.org/?probe=443a5ff3dd) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| Toshiba       | NB520                       | Notebook    | [105666a973](https://linux-hardware.org/?probe=105666a973) | Apr 15, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [72af1b2afe](https://linux-hardware.org/?probe=72af1b2afe) | Apr 15, 2022 |
| AMI           | Intel                       | Notebook    | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | Notebook    | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [55b07b48b3](https://linux-hardware.org/?probe=55b07b48b3) | Apr 14, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [48794f7ff0](https://linux-hardware.org/?probe=48794f7ff0) | Apr 14, 2022 |
| SLIMBOOK      | PRO                         | Notebook    | [97f545c3d4](https://linux-hardware.org/?probe=97f545c3d4) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [45b5664eb1](https://linux-hardware.org/?probe=45b5664eb1) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | Notebook    | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [558d84adac](https://linux-hardware.org/?probe=558d84adac) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [f0f5bfea81](https://linux-hardware.org/?probe=f0f5bfea81) | Apr 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [63f76ffc2b](https://linux-hardware.org/?probe=63f76ffc2b) | Apr 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [3a9245cdab](https://linux-hardware.org/?probe=3a9245cdab) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [0fbee9d8dc](https://linux-hardware.org/?probe=0fbee9d8dc) | Apr 13, 2022 |
| Gateway       | DS71                        | Desktop     | [3bd1ad84ce](https://linux-hardware.org/?probe=3bd1ad84ce) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [1acc227c33](https://linux-hardware.org/?probe=1acc227c33) | Apr 13, 2022 |
| Sony          | VGN-NW21EF_S                | Notebook    | [4ade997baf](https://linux-hardware.org/?probe=4ade997baf) | Apr 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c5c12d6818](https://linux-hardware.org/?probe=c5c12d6818) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [a5bf5ddddf](https://linux-hardware.org/?probe=a5bf5ddddf) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [760d46f52e](https://linux-hardware.org/?probe=760d46f52e) | Apr 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [19ccaef18f](https://linux-hardware.org/?probe=19ccaef18f) | Apr 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dabfb4bb05](https://linux-hardware.org/?probe=dabfb4bb05) | Apr 11, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f986565b6b](https://linux-hardware.org/?probe=f986565b6b) | Apr 10, 2022 |
| Gigabyte      | Q67M-D2H                    | Desktop     | [c95352a142](https://linux-hardware.org/?probe=c95352a142) | Apr 10, 2022 |
| ASUSTek       | Z87-WS                      | Desktop     | [7706049c53](https://linux-hardware.org/?probe=7706049c53) | Apr 10, 2022 |
| Medion        | MS-7366                     | Desktop     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [22502631b3](https://linux-hardware.org/?probe=22502631b3) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9cc7cc23d6](https://linux-hardware.org/?probe=9cc7cc23d6) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3845180872](https://linux-hardware.org/?probe=3845180872) | Apr 10, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [2eb11881fa](https://linux-hardware.org/?probe=2eb11881fa) | Apr 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [862e7ffc88](https://linux-hardware.org/?probe=862e7ffc88) | Apr 09, 2022 |
| Dell          | Latitude D630               | Notebook    | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [e20b365083](https://linux-hardware.org/?probe=e20b365083) | Apr 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [a0001e2492](https://linux-hardware.org/?probe=a0001e2492) | Apr 09, 2022 |
| Medion        | MS-7366                     | Desktop     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| HP            | Compaq 15                   | Notebook    | [e3c3ac6478](https://linux-hardware.org/?probe=e3c3ac6478) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f45b500a83](https://linux-hardware.org/?probe=f45b500a83) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6271f39c13](https://linux-hardware.org/?probe=6271f39c13) | Apr 08, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [9bd404657b](https://linux-hardware.org/?probe=9bd404657b) | Apr 08, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [b90df26c2a](https://linux-hardware.org/?probe=b90df26c2a) | Apr 08, 2022 |
| ASRock        | C226 WS                     | Desktop     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ECS           | Nettle2                     | Desktop     | [65cedbb00d](https://linux-hardware.org/?probe=65cedbb00d) | Apr 07, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [72c98b5e79](https://linux-hardware.org/?probe=72c98b5e79) | Apr 07, 2022 |
| Dell          | Studio 1749                 | Notebook    | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [de86ebaf94](https://linux-hardware.org/?probe=de86ebaf94) | Apr 06, 2022 |
| HP            | 18E5                        | Desktop     | [b79c804a6a](https://linux-hardware.org/?probe=b79c804a6a) | Apr 05, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| Acer          | Extensa 2511                | Notebook    | [00d24bfb95](https://linux-hardware.org/?probe=00d24bfb95) | Apr 05, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [939722b6a7](https://linux-hardware.org/?probe=939722b6a7) | Apr 05, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0437f62b89](https://linux-hardware.org/?probe=0437f62b89) | Apr 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [91bae7b644](https://linux-hardware.org/?probe=91bae7b644) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [db18e71352](https://linux-hardware.org/?probe=db18e71352) | Apr 05, 2022 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | Notebook    | [c5fcd04bc5](https://linux-hardware.org/?probe=c5fcd04bc5) | Apr 04, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45188a0370](https://linux-hardware.org/?probe=45188a0370) | Apr 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7894bcc256](https://linux-hardware.org/?probe=7894bcc256) | Apr 03, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [46756b95b5](https://linux-hardware.org/?probe=46756b95b5) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| Medion        | Z370H4-EM                   | Desktop     | [0f9b0bf367](https://linux-hardware.org/?probe=0f9b0bf367) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | Notebook    | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| Lenovo        | G580 2189                   | Notebook    | [da5b37bf9f](https://linux-hardware.org/?probe=da5b37bf9f) | Apr 02, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [a3aea1cbf5](https://linux-hardware.org/?probe=a3aea1cbf5) | Apr 02, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ccea23c3b5](https://linux-hardware.org/?probe=ccea23c3b5) | Apr 01, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [4c01aec65d](https://linux-hardware.org/?probe=4c01aec65d) | Apr 01, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [d3d1814f5d](https://linux-hardware.org/?probe=d3d1814f5d) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [47e2449cf5](https://linux-hardware.org/?probe=47e2449cf5) | Apr 01, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [e4ef535529](https://linux-hardware.org/?probe=e4ef535529) | Mar 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| LG Electro... | 22V270 2                    | All in one  | [1454b8c602](https://linux-hardware.org/?probe=1454b8c602) | Mar 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [afd4df967a](https://linux-hardware.org/?probe=afd4df967a) | Mar 29, 2022 |
| HP            | 355 G2                      | Notebook    | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [dddc946b70](https://linux-hardware.org/?probe=dddc946b70) | Mar 29, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e2dcac3e1a](https://linux-hardware.org/?probe=e2dcac3e1a) | Mar 29, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [aa3fb80f72](https://linux-hardware.org/?probe=aa3fb80f72) | Mar 29, 2022 |
| Chuwi         | LapBook SE                  | Notebook    | [69b963a8c0](https://linux-hardware.org/?probe=69b963a8c0) | Mar 28, 2022 |
| ASUSTek       | D940MX                      | Desktop     | [bdc8831182](https://linux-hardware.org/?probe=bdc8831182) | Mar 28, 2022 |
| LG Electro... | 14Z90N-V.AR55B              | Notebook    | [4942a692f0](https://linux-hardware.org/?probe=4942a692f0) | Mar 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [9579421df6](https://linux-hardware.org/?probe=9579421df6) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 6464W4J        | Notebook    | [5f73680acf](https://linux-hardware.org/?probe=5f73680acf) | Mar 28, 2022 |
| HP            | Pavilion g6                 | Notebook    | [954723d6f4](https://linux-hardware.org/?probe=954723d6f4) | Mar 27, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [078c1af4c3](https://linux-hardware.org/?probe=078c1af4c3) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7c852d78e1](https://linux-hardware.org/?probe=7c852d78e1) | Mar 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ba743bbb3b](https://linux-hardware.org/?probe=ba743bbb3b) | Mar 27, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [f852a0cb0d](https://linux-hardware.org/?probe=f852a0cb0d) | Mar 26, 2022 |
| Apple         | MacBook10,1                 | Notebook    | [62a1f4a38b](https://linux-hardware.org/?probe=62a1f4a38b) | Mar 25, 2022 |
| Apple         | MacBook10,1                 | Notebook    | [b58112c801](https://linux-hardware.org/?probe=b58112c801) | Mar 25, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [4a7e22384f](https://linux-hardware.org/?probe=4a7e22384f) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Intel         | B75                         | Desktop     | [9f73efdcc8](https://linux-hardware.org/?probe=9f73efdcc8) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [b2c47467cc](https://linux-hardware.org/?probe=b2c47467cc) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8064b23bf4](https://linux-hardware.org/?probe=8064b23bf4) | Mar 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [9400fdbebf](https://linux-hardware.org/?probe=9400fdbebf) | Mar 24, 2022 |
| Lenovo        | ChiefRiver                  | All in one  | [7b9fe75523](https://linux-hardware.org/?probe=7b9fe75523) | Mar 24, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [794139f740](https://linux-hardware.org/?probe=794139f740) | Mar 24, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [5a64dc1855](https://linux-hardware.org/?probe=5a64dc1855) | Mar 23, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [30003161fe](https://linux-hardware.org/?probe=30003161fe) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [ac9f20a77c](https://linux-hardware.org/?probe=ac9f20a77c) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | Latitude E6330              | Notebook    | [a8d483108b](https://linux-hardware.org/?probe=a8d483108b) | Mar 22, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [012e192ece](https://linux-hardware.org/?probe=012e192ece) | Mar 22, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [5d6041ffc4](https://linux-hardware.org/?probe=5d6041ffc4) | Mar 21, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [7c5dff1166](https://linux-hardware.org/?probe=7c5dff1166) | Mar 21, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [ec8aff9fc7](https://linux-hardware.org/?probe=ec8aff9fc7) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [0d8a2d4ea4](https://linux-hardware.org/?probe=0d8a2d4ea4) | Mar 21, 2022 |
| DIODE         | MS-N014                     | Notebook    | [0b95290c21](https://linux-hardware.org/?probe=0b95290c21) | Mar 21, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [56d8c8496b](https://linux-hardware.org/?probe=56d8c8496b) | Mar 20, 2022 |
| HP            | 18E7                        | Desktop     | [727446a2df](https://linux-hardware.org/?probe=727446a2df) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| ECS           | H87H3-M                     | Desktop     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [28d7818dd8](https://linux-hardware.org/?probe=28d7818dd8) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6dd4a41851](https://linux-hardware.org/?probe=6dd4a41851) | Mar 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [05e0027eda](https://linux-hardware.org/?probe=05e0027eda) | Mar 19, 2022 |
| HP            | EliteBook 2740p             | Notebook    | [b0fbd4018d](https://linux-hardware.org/?probe=b0fbd4018d) | Mar 18, 2022 |
| HP            | Presario CQ57               | Notebook    | [d5985051c5](https://linux-hardware.org/?probe=d5985051c5) | Mar 18, 2022 |
| Unknown       | Intel X79                   | Desktop     | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bca7145550](https://linux-hardware.org/?probe=bca7145550) | Mar 17, 2022 |
| ECS           | H110I-C4P                   | Desktop     | [de40e2a12d](https://linux-hardware.org/?probe=de40e2a12d) | Mar 16, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [56d5f5b8ec](https://linux-hardware.org/?probe=56d5f5b8ec) | Mar 16, 2022 |
| Neousys Te... | NVS-7000 Rev. A2            | Server      | [c807a0d0f2](https://linux-hardware.org/?probe=c807a0d0f2) | Mar 16, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [cf2893ebfd](https://linux-hardware.org/?probe=cf2893ebfd) | Mar 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [75a7099e71](https://linux-hardware.org/?probe=75a7099e71) | Mar 15, 2022 |
| ASRock        | B150 Gaming K4              | Desktop     | [a03321659f](https://linux-hardware.org/?probe=a03321659f) | Mar 15, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8b37f4a75d](https://linux-hardware.org/?probe=8b37f4a75d) | Mar 15, 2022 |
| HP            | 1497                        | Desktop     | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [adad5f6ce0](https://linux-hardware.org/?probe=adad5f6ce0) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e284a60544](https://linux-hardware.org/?probe=e284a60544) | Mar 14, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6b45f989ae](https://linux-hardware.org/?probe=6b45f989ae) | Mar 13, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [e0efdaa76a](https://linux-hardware.org/?probe=e0efdaa76a) | Mar 13, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [144a20f079](https://linux-hardware.org/?probe=144a20f079) | Mar 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [06b1c7d30a](https://linux-hardware.org/?probe=06b1c7d30a) | Mar 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [41737e64bb](https://linux-hardware.org/?probe=41737e64bb) | Mar 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e0e46ae824](https://linux-hardware.org/?probe=e0e46ae824) | Mar 13, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [2dd60fe836](https://linux-hardware.org/?probe=2dd60fe836) | Mar 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1de76aac69](https://linux-hardware.org/?probe=1de76aac69) | Mar 12, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [8ec8e7be46](https://linux-hardware.org/?probe=8ec8e7be46) | Mar 12, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [dc4a07851f](https://linux-hardware.org/?probe=dc4a07851f) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [f225ce7d58](https://linux-hardware.org/?probe=f225ce7d58) | Mar 12, 2022 |
| HP            | 3398                        | Desktop     | [6afe044e03](https://linux-hardware.org/?probe=6afe044e03) | Mar 12, 2022 |
| ASUSTek       | K53U                        | Notebook    | [7f78b941ce](https://linux-hardware.org/?probe=7f78b941ce) | Mar 11, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [aa9bcbb679](https://linux-hardware.org/?probe=aa9bcbb679) | Mar 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a7ca755c8e](https://linux-hardware.org/?probe=a7ca755c8e) | Mar 11, 2022 |
| HP            | ENVY Notebook               | Notebook    | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Teclast       | F15S                        | Notebook    | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [72775a871a](https://linux-hardware.org/?probe=72775a871a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS08Q0... | Notebook    | [10655c6e60](https://linux-hardware.org/?probe=10655c6e60) | Mar 11, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [b58520e2a7](https://linux-hardware.org/?probe=b58520e2a7) | Mar 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [570c07ee5c](https://linux-hardware.org/?probe=570c07ee5c) | Mar 10, 2022 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [2d72940994](https://linux-hardware.org/?probe=2d72940994) | Mar 10, 2022 |
| Acer          | Aspire S3                   | Notebook    | [6ae9c3b307](https://linux-hardware.org/?probe=6ae9c3b307) | Mar 10, 2022 |
| Dell          | Latitude 5520               | Notebook    | [bb234c5fd0](https://linux-hardware.org/?probe=bb234c5fd0) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [3df16e8d72](https://linux-hardware.org/?probe=3df16e8d72) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [a67d3468f1](https://linux-hardware.org/?probe=a67d3468f1) | Mar 10, 2022 |
| MSI           | Z270 GAMING M3              | Desktop     | [989eec2f5f](https://linux-hardware.org/?probe=989eec2f5f) | Mar 10, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [463ca7f3a3](https://linux-hardware.org/?probe=463ca7f3a3) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| ASUSTek       | K52F                        | Notebook    | [8e1b16c60b](https://linux-hardware.org/?probe=8e1b16c60b) | Mar 09, 2022 |
| Timi          | TM1703                      | Notebook    | [f9a954eea3](https://linux-hardware.org/?probe=f9a954eea3) | Mar 09, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [4425801f5c](https://linux-hardware.org/?probe=4425801f5c) | Mar 09, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Notebook      | W517GU1                     | Notebook    | [6a4971b810](https://linux-hardware.org/?probe=6a4971b810) | Mar 09, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9695618053](https://linux-hardware.org/?probe=9695618053) | Mar 08, 2022 |
| MSI           | Prestige 15 A11SCS          | Notebook    | [20757cc7e0](https://linux-hardware.org/?probe=20757cc7e0) | Mar 08, 2022 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [60bdf00035](https://linux-hardware.org/?probe=60bdf00035) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [13a7b2300c](https://linux-hardware.org/?probe=13a7b2300c) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [245ea26d7f](https://linux-hardware.org/?probe=245ea26d7f) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [d681586515](https://linux-hardware.org/?probe=d681586515) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [459b5909e6](https://linux-hardware.org/?probe=459b5909e6) | Mar 07, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [c75eb0d27f](https://linux-hardware.org/?probe=c75eb0d27f) | Mar 07, 2022 |
| Dell          | System XPS L322X            | Notebook    | [2aa0c05f64](https://linux-hardware.org/?probe=2aa0c05f64) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [6e8e3f12d0](https://linux-hardware.org/?probe=6e8e3f12d0) | Mar 06, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [04d9923f43](https://linux-hardware.org/?probe=04d9923f43) | Mar 06, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [6a8be21d50](https://linux-hardware.org/?probe=6a8be21d50) | Mar 06, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [72960138d6](https://linux-hardware.org/?probe=72960138d6) | Mar 06, 2022 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [77ffb9a5a6](https://linux-hardware.org/?probe=77ffb9a5a6) | Mar 05, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [703034e8c4](https://linux-hardware.org/?probe=703034e8c4) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [167b8de1e1](https://linux-hardware.org/?probe=167b8de1e1) | Mar 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 699       | 15.78%  |
| Ubuntu 18.04      | 499       | 11.26%  |
| OpenMandriva 4.2  | 180       | 4.06%   |
| Debian 11         | 165       | 3.72%   |
| KDE neon 20.04    | 105       | 2.37%   |
| Ubuntu 22.04      | 91        | 2.05%   |
| OpenMandriva 4.3  | 90        | 2.03%   |
| Debian 10         | 80        | 1.81%   |
| Ubuntu 20.10      | 72        | 1.63%   |
| Linux Mint 19.3   | 70        | 1.58%   |
| Manjaro           | 68        | 1.53%   |
| Arch              | 65        | 1.47%   |
| Zorin 16          | 62        | 1.4%    |
| Ubuntu 19.04      | 61        | 1.38%   |
| Linux Mint 20.3   | 60        | 1.35%   |
| Xubuntu 20.04     | 59        | 1.33%   |
| Ubuntu 19.10      | 58        | 1.31%   |
| Linux Mint 20.1   | 57        | 1.29%   |
| Ubuntu 21.04      | 53        | 1.2%    |
| Linux Mint 20     | 51        | 1.15%   |
| Ubuntu 21.10      | 50        | 1.13%   |
| Arch Rolling      | 49        | 1.11%   |
| Fedora 35         | 47        | 1.06%   |
| Xubuntu 18.04     | 45        | 1.02%   |
| Linux Mint 20.2   | 45        | 1.02%   |
| ROSA R10          | 43        | 0.97%   |
| Kubuntu 20.04     | 41        | 0.93%   |
| Fedora 36         | 41        | 0.93%   |
| Fedora 34         | 40        | 0.9%    |
| Zorin 15          | 39        | 0.88%   |
| Pop!_OS 20.04     | 37        | 0.84%   |
| Fedora 33         | 37        | 0.84%   |
| Ubuntu 18.10      | 33        | 0.74%   |
| Linux Mint 19.2   | 30        | 0.68%   |
| Ubuntu 16.04      | 29        | 0.65%   |
| ROSA R11          | 28        | 0.63%   |
| Debian Testing    | 28        | 0.63%   |
| BlackPanther 18.1 | 26        | 0.59%   |
| Fedora 32         | 25        | 0.56%   |
| Ubuntu MATE 20.04 | 24        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1579      | 37.41%  |
| Linux Mint    | 334       | 7.91%   |
| OpenMandriva  | 292       | 6.92%   |
| Debian        | 291       | 6.89%   |
| Fedora        | 199       | 4.71%   |
| Manjaro       | 163       | 3.86%   |
| Endless       | 120       | 2.84%   |
| Xubuntu       | 118       | 2.8%    |
| KDE neon      | 117       | 2.77%   |
| Arch          | 112       | 2.65%   |
| Zorin         | 106       | 2.51%   |
| ROSA          | 105       | 2.49%   |
| Pop!_OS       | 99        | 2.35%   |
| Kubuntu       | 85        | 2.01%   |
| Ubuntu MATE   | 48        | 1.14%   |
| Elementary    | 44        | 1.04%   |
| Gentoo        | 41        | 0.97%   |
| openSUSE      | 39        | 0.92%   |
| Ubuntu Unity  | 37        | 0.88%   |
| BlackPanther  | 28        | 0.66%   |
| ArcoLinux     | 25        | 0.59%   |
| Lubuntu       | 22        | 0.52%   |
| LMDE          | 18        | 0.43%   |
| Kali          | 17        | 0.4%    |
| Parrot        | 15        | 0.36%   |
| Clear Linux   | 14        | 0.33%   |
| MX            | 13        | 0.31%   |
| Ubuntu Budgie | 10        | 0.24%   |
| SteamOS       | 10        | 0.24%   |
| EndeavourOS   | 10        | 0.24%   |
| Reborn OS     | 8         | 0.19%   |
| CentOS        | 8         | 0.19%   |
| Garuda Linux  | 6         | 0.14%   |
| Deepin        | 6         | 0.14%   |
| Solus         | 5         | 0.12%   |
| RHEL          | 5         | 0.12%   |
| Peppermint    | 5         | 0.12%   |
| UbuntuDDE     | 3         | 0.07%   |
| Slackware     | 3         | 0.07%   |
| Raspbian      | 3         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 176       | 3.64%   |
| 5.4.0-42-generic                | 95        | 1.96%   |
| 5.16.7-desktop-1omv4003         | 90        | 1.86%   |
| 5.4.0-58-generic                | 60        | 1.24%   |
| 5.10.0-8-amd64                  | 56        | 1.16%   |
| 5.4.0-52-generic                | 49        | 1.01%   |
| 5.4.0-54-generic                | 48        | 0.99%   |
| 5.4.0-26-generic                | 47        | 0.97%   |
| 5.3.0-28-generic                | 42        | 0.87%   |
| 5.4.0-48-generic                | 39        | 0.81%   |
| 5.3.0-40-generic                | 37        | 0.76%   |
| 5.11.0-27-generic               | 36        | 0.74%   |
| 5.0.0-37-generic                | 36        | 0.74%   |
| 5.4.0-29-generic                | 34        | 0.7%    |
| 5.3.0-46-generic                | 32        | 0.66%   |
| 5.4.0-65-generic                | 31        | 0.64%   |
| 5.11.0-43-generic               | 30        | 0.62%   |
| 5.0.0-32-generic                | 30        | 0.62%   |
| 5.4.0-72-generic                | 29        | 0.6%    |
| 5.4.0-40-generic                | 29        | 0.6%    |
| 5.13.0-30-generic               | 29        | 0.6%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.6%    |
| 5.4.0-47-generic                | 27        | 0.56%   |
| 5.4.0-37-generic                | 27        | 0.56%   |
| 5.3.0-51-generic                | 27        | 0.56%   |
| 5.13.0-39-generic               | 26        | 0.54%   |
| 5.13.0-28-generic               | 26        | 0.54%   |
| 5.11.0-41-generic               | 26        | 0.54%   |
| 5.8.0-43-generic                | 25        | 0.52%   |
| 5.8.0-44-generic                | 24        | 0.5%    |
| 5.11.0-37-generic               | 24        | 0.5%    |
| 5.4.0-70-generic                | 23        | 0.48%   |
| 5.3.0-45-generic                | 23        | 0.48%   |
| 5.8.0-48-generic                | 22        | 0.45%   |
| 5.4.0-56-generic                | 22        | 0.45%   |
| 5.15.0-47-generic               | 22        | 0.45%   |
| 5.13.0-27-generic               | 22        | 0.45%   |
| 5.10.0-18-amd64                 | 22        | 0.45%   |
| 5.4.0-74-generic                | 21        | 0.43%   |
| 5.4.0-53-generic                | 21        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 914       | 20.17%  |
| 4.15.0  | 410       | 9.05%   |
| 5.11.0  | 269       | 5.94%   |
| 5.8.0   | 266       | 5.87%   |
| 5.3.0   | 254       | 5.6%    |
| 5.13.0  | 222       | 4.9%    |
| 5.10.0  | 207       | 4.57%   |
| 5.0.0   | 198       | 4.37%   |
| 5.10.14 | 178       | 3.93%   |
| 5.15.0  | 153       | 3.38%   |
| 4.18.0  | 113       | 2.49%   |
| 5.16.7  | 94        | 2.07%   |
| 4.19.0  | 82        | 1.81%   |
| 4.9.60  | 33        | 0.73%   |
| 4.4.0   | 22        | 0.49%   |
| 4.18.16 | 22        | 0.49%   |
| 5.14.0  | 16        | 0.35%   |
| 5.9.16  | 15        | 0.33%   |
| 5.18.0  | 14        | 0.31%   |
| 5.17.5  | 14        | 0.31%   |
| 5.9.0   | 13        | 0.29%   |
| 5.7.0   | 12        | 0.26%   |
| 5.3.18  | 12        | 0.26%   |
| 5.12.4  | 12        | 0.26%   |
| 4.9.20  | 12        | 0.26%   |
| 5.19.0  | 11        | 0.24%   |
| 5.16.11 | 11        | 0.24%   |
| 5.16.0  | 11        | 0.24%   |
| 5.15.6  | 11        | 0.24%   |
| 5.8.11  | 10        | 0.22%   |
| 5.6.0   | 10        | 0.22%   |
| 5.15.32 | 10        | 0.22%   |
| 5.13.12 | 10        | 0.22%   |
| 5.11.12 | 10        | 0.22%   |
| 5.17.1  | 9         | 0.2%    |
| 5.15.15 | 9         | 0.2%    |
| 5.14.14 | 9         | 0.2%    |
| 5.11.11 | 9         | 0.2%    |
| 4.9.0   | 9         | 0.2%    |
| 5.19.9  | 8         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 976       | 21.76%  |
| 5.10    | 463       | 10.32%  |
| 4.15    | 410       | 9.14%   |
| 5.8     | 326       | 7.27%   |
| 5.11    | 325       | 7.25%   |
| 5.3     | 282       | 6.29%   |
| 5.13    | 260       | 5.8%    |
| 5.15    | 250       | 5.57%   |
| 5.0     | 202       | 4.5%    |
| 5.16    | 152       | 3.39%   |
| 4.18    | 136       | 3.03%   |
| 4.19    | 97        | 2.16%   |
| 4.9     | 79        | 1.76%   |
| 5.14    | 68        | 1.52%   |
| 5.18    | 57        | 1.27%   |
| 5.9     | 52        | 1.16%   |
| 5.6     | 51        | 1.14%   |
| 5.19    | 49        | 1.09%   |
| 5.17    | 46        | 1.03%   |
| 5.7     | 45        | 1%      |
| 5.12    | 44        | 0.98%   |
| 5.5     | 26        | 0.58%   |
| 4.4     | 26        | 0.58%   |
| 4.1     | 9         | 0.2%    |
| 5.2     | 8         | 0.18%   |
| 5.1     | 7         | 0.16%   |
| 4.16    | 6         | 0.13%   |
| 3.10    | 6         | 0.13%   |
| 4.20    | 4         | 0.09%   |
| 4.17    | 4         | 0.09%   |
| 4.13    | 4         | 0.09%   |
| 4.8     | 3         | 0.07%   |
| 4.14    | 3         | 0.07%   |
| 3.16    | 3         | 0.07%   |
| 6.0     | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 3.18    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3882      | 95.12%  |
| i686    | 170       | 4.17%   |
| aarch64 | 22        | 0.54%   |
| armv7l  | 6         | 0.15%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1826      | 42.48%  |
| KDE5            | 671       | 15.61%  |
| Unknown         | 615       | 14.31%  |
| XFCE            | 315       | 7.33%   |
| X-Cinnamon      | 256       | 5.96%   |
| KDE             | 157       | 3.65%   |
| MATE            | 131       | 3.05%   |
| KDE4            | 47        | 1.09%   |
| Cinnamon        | 46        | 1.07%   |
| Pantheon        | 40        | 0.93%   |
| Unity           | 36        | 0.84%   |
| LXQt            | 33        | 0.77%   |
| i3              | 23        | 0.54%   |
| LXDE            | 18        | 0.42%   |
| Budgie          | 18        | 0.42%   |
| Deepin          | 17        | 0.4%    |
| GNOME Flashback | 13        | 0.3%    |
| openbox         | 8         | 0.19%   |
| qtile           | 4         | 0.09%   |
| GNOME Classic   | 4         | 0.09%   |
| bspwm           | 4         | 0.09%   |
| enlightenment   | 3         | 0.07%   |
| DWM             | 3         | 0.07%   |
| xmonad          | 2         | 0.05%   |
| Trinity         | 2         | 0.05%   |
| river           | 1         | 0.02%   |
| Lubuntu         | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| i3-with-shmlog  | 1         | 0.02%   |
| fvwm            | 1         | 0.02%   |
| Cutefish        | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3370      | 80.41%  |
| Wayland | 436       | 10.4%   |
| Unknown | 328       | 7.83%   |
| Tty     | 57        | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2396      | 56.7%   |
| SDDM    | 607       | 14.36%  |
| GDM     | 486       | 11.5%   |
| LightDM | 268       | 6.34%   |
| GDM3    | 247       | 5.84%   |
| TDM     | 150       | 3.55%   |
| KDM     | 47        | 1.11%   |
| XDM     | 13        | 0.31%   |
| Ly      | 5         | 0.12%   |
| LXDM    | 4         | 0.09%   |
| SLiM    | 3         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 2414      | 57.44%  |
| en_US          | 652       | 15.51%  |
| Unknown        | 631       | 15.01%  |
| ca_ES          | 153       | 3.64%   |
| en_GB          | 88        | 2.09%   |
| C              | 41        | 0.98%   |
| gl_ES          | 31        | 0.74%   |
| de_DE          | 27        | 0.64%   |
| eu_ES          | 21        | 0.5%    |
| fr_FR          | 17        | 0.4%    |
| ru_RU          | 16        | 0.38%   |
| it_IT          | 11        | 0.26%   |
| an_ES          | 10        | 0.24%   |
| es_MX          | 8         | 0.19%   |
| es_AR          | 7         | 0.17%   |
| pt_BR          | 6         | 0.14%   |
| en_IE          | 6         | 0.14%   |
| C.UTF8         | 5         | 0.12%   |
| ro_RO          | 4         | 0.1%    |
| pl_PL          | 4         | 0.1%    |
| ca_AD          | 4         | 0.1%    |
| nl_NL          | 3         | 0.07%   |
| fr_BE          | 3         | 0.07%   |
| es_ES.UTF8     | 3         | 0.07%   |
| ca_ES@valencia | 3         | 0.07%   |
| pt_PT          | 2         | 0.05%   |
| POSIX          | 2         | 0.05%   |
| fr_CH          | 2         | 0.05%   |
| es_US          | 2         | 0.05%   |
| es_BO          | 2         | 0.05%   |
| en_DK          | 2         | 0.05%   |
| en_AU          | 2         | 0.05%   |
| bg_BG          | 2         | 0.05%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |
| et_EE          | 1         | 0.02%   |
| es_VE          | 1         | 0.02%   |
| es_PE          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2201      | 52.81%  |
| EFI  | 1967      | 47.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3266      | 78.34%  |
| Overlay  | 328       | 7.87%   |
| Btrfs    | 227       | 5.44%   |
| Unknown  | 212       | 5.09%   |
| Xfs      | 55        | 1.32%   |
| Ext3     | 32        | 0.77%   |
| Zfs      | 18        | 0.43%   |
| Ext2     | 15        | 0.36%   |
| Tmpfs    | 7         | 0.17%   |
| Reiserfs | 4         | 0.1%    |
| Jfs      | 2         | 0.05%   |
| Aufs     | 2         | 0.05%   |
| F2fs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2602      | 62.56%  |
| GPT     | 1131      | 27.19%  |
| MBR     | 426       | 10.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3504      | 84.09%  |
| Yes       | 663       | 15.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2777      | 66.82%  |
| Yes       | 1379      | 33.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 800       | 19.61%  |
| Hewlett-Packard         | 587       | 14.39%  |
| Lenovo                  | 478       | 11.72%  |
| MSI                     | 344       | 8.43%   |
| Gigabyte Technology     | 338       | 8.29%   |
| Acer                    | 276       | 6.77%   |
| Dell                    | 261       | 6.4%    |
| ASRock                  | 110       | 2.7%    |
| Toshiba                 | 95        | 2.33%   |
| Apple                   | 90        | 2.21%   |
| Intel                   | 61        | 1.5%    |
| Unknown                 | 55        | 1.35%   |
| Packard Bell            | 40        | 0.98%   |
| Sony                    | 35        | 0.86%   |
| Medion                  | 32        | 0.78%   |
| Chuwi                   | 29        | 0.71%   |
| HUAWEI                  | 26        | 0.64%   |
| Samsung Electronics     | 25        | 0.61%   |
| SLIMBOOK                | 23        | 0.56%   |
| Notebook                | 22        | 0.54%   |
| Raspberry Pi Foundation | 19        | 0.47%   |
| LG Electronics          | 19        | 0.47%   |
| Pegatron                | 17        | 0.42%   |
| Fujitsu                 | 17        | 0.42%   |
| eMachines               | 17        | 0.42%   |
| ECS                     | 16        | 0.39%   |
| Teclast                 | 12        | 0.29%   |
| Fujitsu Siemens         | 12        | 0.29%   |
| BESSTAR Tech            | 12        | 0.29%   |
| Timi                    | 11        | 0.27%   |
| Foxconn                 | 11        | 0.27%   |
| Huanan                  | 10        | 0.25%   |
| AMI                     | 10        | 0.25%   |
| Valve                   | 7         | 0.17%   |
| Clevo                   | 7         | 0.17%   |
| Supermicro              | 6         | 0.15%   |
| Shuttle                 | 6         | 0.15%   |
| IBM                     | 6         | 0.15%   |
| AZW                     | 6         | 0.15%   |
| Hampoo                  | 5         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 80        | 1.96%   |
| ASUS All Series                            | 49        | 1.2%    |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.54%   |
| HP Pavilion g6                             | 19        | 0.47%   |
| HP Pavilion dv6                            | 19        | 0.47%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.44%   |
| HP Notebook                                | 16        | 0.39%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.37%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 14        | 0.34%   |
| MSI MS-7C37                                | 11        | 0.27%   |
| RPi Raspberry Pi                           | 10        | 0.25%   |
| HP Laptop 15-da0xxx                        | 10        | 0.25%   |
| HP G62                                     | 10        | 0.25%   |
| Gigabyte 970A-DS3P                         | 10        | 0.25%   |
| Dell XPS 13 7390                           | 10        | 0.25%   |
| ASUS P5G41T-M LX                           | 10        | 0.25%   |
| MSI MS-7817                                | 9         | 0.22%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.22%   |
| Gigabyte B450M DS3H                        | 9         | 0.22%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.2%    |
| MSI MS-7B79                                | 8         | 0.2%    |
| HP Pavilion 15                             | 8         | 0.2%    |
| Gigabyte H110M-S2H                         | 8         | 0.2%    |
| ASUS X540NA                                | 8         | 0.2%    |
| ASUS PRIME A320M-K                         | 8         | 0.2%    |
| Valve Jupiter                              | 7         | 0.17%   |
| MSI MS-7C02                                | 7         | 0.17%   |
| MSI MS-7B86                                | 7         | 0.17%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.17%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 7         | 0.17%   |
| Lenovo G50-70 20351                        | 7         | 0.17%   |
| HP Pavilion dv7                            | 7         | 0.17%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.17%   |
| Gigabyte H61M-DS2                          | 7         | 0.17%   |
| Gigabyte B450 AORUS M                      | 7         | 0.17%   |
| ASUS X555LAB                               | 7         | 0.17%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 7         | 0.17%   |
| ASUS PRIME B450M-A                         | 7         | 0.17%   |
| ASUS P5K                                   | 7         | 0.17%   |
| Acer Aspire 5750G                          | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 199       | 4.88%   |
| Lenovo ThinkPad       | 151       | 3.7%    |
| HP Pavilion           | 128       | 3.14%   |
| Lenovo IdeaPad        | 110       | 2.7%    |
| HP Compaq             | 82        | 2.01%   |
| Unknown               | 80        | 1.96%   |
| Dell Latitude         | 77        | 1.89%   |
| Toshiba Satellite     | 74        | 1.81%   |
| ASUS VivoBook         | 66        | 1.62%   |
| ASUS PRIME            | 65        | 1.59%   |
| HP Laptop             | 63        | 1.54%   |
| HP EliteBook          | 54        | 1.32%   |
| ASUS TUF              | 53        | 1.3%    |
| Dell XPS              | 52        | 1.27%   |
| ASUS ROG              | 52        | 1.27%   |
| ASUS All              | 49        | 1.2%    |
| Lenovo ThinkCentre    | 48        | 1.18%   |
| Dell OptiPlex         | 43        | 1.05%   |
| Dell Inspiron         | 36        | 0.88%   |
| HP ProBook            | 34        | 0.83%   |
| ASUS ZenBook          | 31        | 0.76%   |
| Packard Bell EasyNote | 28        | 0.69%   |
| HP 250                | 28        | 0.69%   |
| MSI Prestige          | 24        | 0.59%   |
| Lenovo Yoga           | 22        | 0.54%   |
| RPi Raspberry         | 19        | 0.47%   |
| HP OMEN               | 19        | 0.47%   |
| Gigabyte X570         | 19        | 0.47%   |
| Dell Precision        | 17        | 0.42%   |
| HP Notebook           | 16        | 0.39%   |
| HP ENVY               | 16        | 0.39%   |
| Acer TravelMate       | 16        | 0.39%   |
| Acer Extensa          | 16        | 0.39%   |
| MSI Modern            | 15        | 0.37%   |
| Lenovo Legion         | 15        | 0.37%   |
| Lenovo ThinkBook      | 14        | 0.34%   |
| Gigabyte B450M        | 14        | 0.34%   |
| Gigabyte B450         | 14        | 0.34%   |
| HP EliteDesk          | 13        | 0.32%   |
| ASUS P5KPL-AM         | 12        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 436       | 10.69%  |
| 2019    | 396       | 9.71%   |
| 2020    | 344       | 8.43%   |
| 2014    | 294       | 7.21%   |
| 2013    | 266       | 6.52%   |
| 2017    | 256       | 6.28%   |
| 2012    | 252       | 6.18%   |
| 2011    | 248       | 6.08%   |
| 2015    | 231       | 5.66%   |
| 2010    | 230       | 5.64%   |
| 2008    | 208       | 5.1%    |
| 2021    | 202       | 4.95%   |
| 2009    | 201       | 4.93%   |
| 2016    | 193       | 4.73%   |
| 2007    | 145       | 3.55%   |
| 2006    | 81        | 1.99%   |
| 2022    | 32        | 0.78%   |
| Unknown | 28        | 0.69%   |
| 2005    | 22        | 0.54%   |
| 2004    | 7         | 0.17%   |
| 2003    | 3         | 0.07%   |
| 2002    | 2         | 0.05%   |
| 2001    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2241      | 54.94%  |
| Desktop        | 1568      | 38.44%  |
| All in one     | 66        | 1.62%   |
| Convertible    | 60        | 1.47%   |
| Mini pc        | 57        | 1.4%    |
| Tablet         | 34        | 0.83%   |
| System on chip | 25        | 0.61%   |
| Server         | 24        | 0.59%   |
| Phone          | 3         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3845      | 93.71%  |
| Enabled  | 258       | 6.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4075      | 99.9%   |
| Yes  | 4         | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 921       | 22.22%  |
| 4.01-8.0        | 886       | 21.38%  |
| 16.01-24.0      | 841       | 20.29%  |
| 8.01-16.0       | 755       | 18.22%  |
| 32.01-64.0      | 314       | 7.58%   |
| 1.01-2.0        | 208       | 5.02%   |
| 2.01-3.0        | 71        | 1.71%   |
| 0.51-1.0        | 54        | 1.3%    |
| 64.01-256.0     | 52        | 1.25%   |
| 24.01-32.0      | 35        | 0.84%   |
| More than 256.0 | 4         | 0.1%    |
| 0.01-0.5        | 2         | 0.05%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1820      | 40.38%  |
| 2.01-3.0   | 1119      | 24.83%  |
| 4.01-8.0   | 530       | 11.76%  |
| 3.01-4.0   | 457       | 10.14%  |
| 0.51-1.0   | 372       | 8.25%   |
| 8.01-16.0  | 140       | 3.11%   |
| 0.01-0.5   | 54        | 1.2%    |
| 24.01-32.0 | 7         | 0.16%   |
| 16.01-24.0 | 6         | 0.13%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2518      | 59.8%   |
| 2       | 1046      | 24.84%  |
| 3       | 349       | 8.29%   |
| 4       | 146       | 3.47%   |
| 5       | 58        | 1.38%   |
| 0       | 38        | 0.9%    |
| 6       | 27        | 0.64%   |
| 7       | 10        | 0.24%   |
| 8       | 6         | 0.14%   |
| 9       | 5         | 0.12%   |
| 11      | 2         | 0.05%   |
| 10      | 2         | 0.05%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2369      | 57.57%  |
| Yes       | 1746      | 42.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3552      | 86.8%   |
| No        | 540       | 13.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3038      | 73.9%   |
| No        | 1073      | 26.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2274      | 55.07%  |
| No        | 1855      | 44.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 4079      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 652       | 14.69%  |
| Barcelona                  | 458       | 10.32%  |
| Seville                    | 151       | 3.4%    |
| Valencia                   | 149       | 3.36%   |
| Zaragoza                   | 69        | 1.56%   |
| Málaga                    | 60        | 1.35%   |
| Granada                    | 57        | 1.28%   |
| Sabadell                   | 45        | 1.01%   |
| Palma                      | 45        | 1.01%   |
| Valladolid                 | 42        | 0.95%   |
| Las Palmas de Gran Canaria | 40        | 0.9%    |
| Vigo                       | 38        | 0.86%   |
| Córdoba                   | 38        | 0.86%   |
| Bilbao                     | 38        | 0.86%   |
| Ourense                    | 37        | 0.83%   |
| Alcobendas                 | 37        | 0.83%   |
| Murcia                     | 32        | 0.72%   |
| Pamplona                   | 31        | 0.7%    |
| Alcalá de Henares         | 28        | 0.63%   |
| Gijón                     | 26        | 0.59%   |
| Donostia / San Sebastian   | 25        | 0.56%   |
| Almería                   | 25        | 0.56%   |
| Alicante                   | 25        | 0.56%   |
| A Coruña                  | 25        | 0.56%   |
| Oviedo                     | 24        | 0.54%   |
| Santa Cruz de Tenerife     | 23        | 0.52%   |
| León                      | 23        | 0.52%   |
| Barakaldo                  | 23        | 0.52%   |
| Santiago de Compostela     | 22        | 0.5%    |
| Vitoria-Gasteiz            | 21        | 0.47%   |
| Mostoles                   | 20        | 0.45%   |
| Burgos                     | 20        | 0.45%   |
| Salamanca                  | 19        | 0.43%   |
| Albacete                   | 19        | 0.43%   |
| Santander                  | 18        | 0.41%   |
| Reus                       | 17        | 0.38%   |
| Pontevedra                 | 17        | 0.38%   |
| Getxo                      | 17        | 0.38%   |
| Cartagena                  | 17        | 0.38%   |
| Logroño                   | 15        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1056      | 1621   | 17.81%  |
| WDC                       | 853       | 1227   | 14.39%  |
| Samsung Electronics       | 765       | 1094   | 12.9%   |
| Kingston                  | 671       | 924    | 11.32%  |
| Toshiba                   | 467       | 694    | 7.88%   |
| SanDisk                   | 312       | 409    | 5.26%   |
| Unknown                   | 228       | 287    | 3.85%   |
| Crucial                   | 210       | 289    | 3.54%   |
| Hitachi                   | 194       | 233    | 3.27%   |
| SK hynix                  | 140       | 180    | 2.36%   |
| Intel                     | 119       | 154    | 2.01%   |
| HGST                      | 108       | 135    | 1.82%   |
| Micron Technology         | 76        | 85     | 1.28%   |
| China                     | 50        | 66     | 0.84%   |
| Phison                    | 47        | 53     | 0.79%   |
| Fujitsu                   | 42        | 48     | 0.71%   |
| Maxtor                    | 35        | 45     | 0.59%   |
| KIOXIA                    | 32        | 38     | 0.54%   |
| Apple                     | 30        | 44     | 0.51%   |
| OCZ                       | 28        | 35     | 0.47%   |
| Micron/Crucial Technology | 22        | 28     | 0.37%   |
| Silicon Motion            | 19        | 25     | 0.32%   |
| Netac                     | 19        | 26     | 0.32%   |
| LITEON                    | 19        | 20     | 0.32%   |
| JMicron Technology        | 19        | 20     | 0.32%   |
| A-DATA Technology         | 19        | 23     | 0.32%   |
| Transcend                 | 18        | 38     | 0.3%    |
| KingSpec                  | 18        | 24     | 0.3%    |
| Corsair                   | 18        | 22     | 0.3%    |
| KingDian                  | 16        | 18     | 0.27%   |
| Unknown                   | 15        | 17     | 0.25%   |
| USB30                     | 14        | 28     | 0.24%   |
| PNY                       | 13        | 21     | 0.22%   |
| KIOXIA-EXCERIA            | 12        | 16     | 0.2%    |
| Emtec                     | 11        | 11     | 0.19%   |
| Patriot                   | 9         | 15     | 0.15%   |
| Drevo                     | 9         | 12     | 0.15%   |
| Teclast                   | 8         | 8      | 0.13%   |
| FORESEE                   | 8         | 9      | 0.13%   |
| GOODRAM                   | 7         | 8      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 223       | 3.43%   |
| Kingston SA400S37480G 480GB SSD    | 83        | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB     | 78        | 1.2%    |
| Kingston SA400S37120G 120GB SSD    | 74        | 1.14%   |
| Seagate ST500DM002-1BD142 500GB    | 68        | 1.05%   |
| Kingston SV300S37A120G 120GB SSD   | 62        | 0.95%   |
| Seagate ST3500418AS 500GB          | 55        | 0.85%   |
| Samsung SSD 860 EVO 500GB          | 52        | 0.8%    |
| Unknown MMC Card  64GB             | 46        | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB     | 43        | 0.66%   |
| Unknown MMC Card  32GB             | 42        | 0.65%   |
| Samsung SSD 850 EVO 500GB          | 41        | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB     | 40        | 0.61%   |
| Toshiba MQ01ABD100 1TB             | 38        | 0.58%   |
| Samsung SSD 850 EVO 250GB          | 38        | 0.58%   |
| Toshiba DT01ACA100 1TB             | 37        | 0.57%   |
| Seagate ST9500325AS 500GB          | 36        | 0.55%   |
| Seagate ST500LT012-1DG142 500GB    | 36        | 0.55%   |
| Samsung NVMe SSD Drive 512GB       | 36        | 0.55%   |
| Samsung NVMe SSD Drive 500GB       | 36        | 0.55%   |
| Kingston SUV400S37240G 240GB SSD   | 36        | 0.55%   |
| Crucial CT500MX500SSD1 500GB       | 35        | 0.54%   |
| SK hynix NVMe SSD Drive 512GB      | 34        | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB     | 34        | 0.52%   |
| HGST HTS721010A9E630 1TB           | 34        | 0.52%   |
| Toshiba MQ01ABF050 500GB           | 33        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 32        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB       | 32        | 0.49%   |
| Kingston SV300S37A240G 240GB SSD   | 32        | 0.49%   |
| SanDisk SSD PLUS 480GB             | 31        | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB     | 30        | 0.46%   |
| Intel NVMe SSD Drive 512GB         | 30        | 0.46%   |
| Seagate ST31000528AS 1TB           | 28        | 0.43%   |
| Samsung NVMe SSD Drive 256GB       | 28        | 0.43%   |
| Toshiba MQ04ABF100 1TB             | 27        | 0.42%   |
| Unknown SD/MMC/MS PRO 2GB          | 26        | 0.4%    |
| Toshiba TR200 240GB SSD            | 26        | 0.4%    |
| Toshiba MQ01ABD050 500GB           | 26        | 0.4%    |
| Seagate Expansion 1TB              | 26        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB           | 23        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1047      | 1607   | 40.32%  |
| WDC                 | 674       | 964    | 25.95%  |
| Toshiba             | 335       | 464    | 12.9%   |
| Hitachi             | 194       | 233    | 7.47%   |
| HGST                | 108       | 135    | 4.16%   |
| Samsung Electronics | 103       | 130    | 3.97%   |
| Fujitsu             | 41        | 47     | 1.58%   |
| Maxtor              | 30        | 39     | 1.16%   |
| Unknown             | 26        | 31     | 1%      |
| Apple               | 13        | 17     | 0.5%    |
| USB3.0              | 5         | 5      | 0.19%   |
| ASMT                | 4         | 7      | 0.15%   |
| Hewlett-Packard     | 3         | 4      | 0.12%   |
| USB                 | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| OEM                 | 1         | 1      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| Inateck             | 1         | 1      | 0.04%   |
| IBM-207x            | 1         | 8      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Generic-            | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 615       | 845    | 30.52%  |
| Samsung Electronics | 357       | 491    | 17.72%  |
| SanDisk             | 194       | 242    | 9.63%   |
| Crucial             | 189       | 259    | 9.38%   |
| WDC                 | 104       | 142    | 5.16%   |
| Toshiba             | 90        | 159    | 4.47%   |
| China               | 48        | 64     | 2.38%   |
| SK hynix            | 34        | 37     | 1.69%   |
| Intel               | 31        | 47     | 1.54%   |
| Micron Technology   | 30        | 36     | 1.49%   |
| OCZ                 | 28        | 35     | 1.39%   |
| Netac               | 19        | 26     | 0.94%   |
| LITEON              | 18        | 18     | 0.89%   |
| KingSpec            | 18        | 24     | 0.89%   |
| Transcend           | 17        | 37     | 0.84%   |
| A-DATA Technology   | 16        | 20     | 0.79%   |
| KingDian            | 15        | 17     | 0.74%   |
| USB30               | 14        | 28     | 0.69%   |
| Apple               | 13        | 16     | 0.65%   |
| PNY                 | 9         | 17     | 0.45%   |
| KIOXIA-EXCERIA      | 9         | 12     | 0.45%   |
| Emtec               | 9         | 9      | 0.45%   |
| Teclast             | 8         | 8      | 0.4%    |
| Patriot             | 8         | 14     | 0.4%    |
| FORESEE             | 8         | 9      | 0.4%    |
| Corsair             | 8         | 11     | 0.4%    |
| Unknown             | 7         | 7      | 0.35%   |
| GOODRAM             | 6         | 7      | 0.3%    |
| Drevo               | 6         | 8      | 0.3%    |
| Maxtor              | 5         | 6      | 0.25%   |
| LITEONIT            | 4         | 5      | 0.2%    |
| Intenso             | 4         | 5      | 0.2%    |
| Hoodisk             | 4         | 5      | 0.2%    |
| BAITITON            | 4         | 4      | 0.2%    |
| Unknown             | 3         | 3      | 0.15%   |
| TCSUNBOW            | 3         | 3      | 0.15%   |
| Plextor             | 3         | 4      | 0.15%   |
| Hewlett-Packard     | 3         | 8      | 0.15%   |
| Dogfish             | 3         | 3      | 0.15%   |
| ASMT                | 3         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2217      | 3704   | 41.92%  |
| SSD     | 1743      | 2752   | 32.96%  |
| NVMe    | 1059      | 1462   | 20.02%  |
| MMC     | 206       | 268    | 3.89%   |
| Unknown | 64        | 81     | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3184      | 6301   | 68.74%  |
| NVMe | 1047      | 1443   | 22.6%   |
| MMC  | 206       | 268    | 4.45%   |
| SAS  | 195       | 255    | 4.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2557      | 4174   | 62.93%  |
| 0.51-1.0   | 1081      | 1588   | 26.61%  |
| 1.01-2.0   | 275       | 424    | 6.77%   |
| 2.01-3.0   | 64        | 102    | 1.58%   |
| 3.01-4.0   | 61        | 99     | 1.5%    |
| 4.01-10.0  | 24        | 68     | 0.59%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1230      | 28.48%  |
| 251-500        | 1007      | 23.32%  |
| 501-1000       | 562       | 13.01%  |
| 1-20           | 317       | 7.34%   |
| 51-100         | 304       | 7.04%   |
| 1001-2000      | 291       | 6.74%   |
| 21-50          | 189       | 4.38%   |
| More than 3000 | 160       | 3.7%    |
| 2001-3000      | 152       | 3.52%   |
| Unknown        | 107       | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1776      | 39.51%  |
| 21-50          | 770       | 17.13%  |
| 101-250        | 568       | 12.64%  |
| 51-100         | 462       | 10.28%  |
| 251-500        | 329       | 7.32%   |
| 501-1000       | 234       | 5.21%   |
| 1001-2000      | 141       | 3.14%   |
| Unknown        | 107       | 2.38%   |
| More than 3000 | 60        | 1.33%   |
| 2001-3000      | 46        | 1.02%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 11        | 11     | 2.98%   |
| Kingston SV300S37A120G 120GB SSD   | 11        | 13     | 2.98%   |
| Seagate ST3500418AS 500GB          | 10        | 16     | 2.71%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 2.17%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 1.63%   |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 7      | 1.63%   |
| SanDisk SSD PLUS 480GB             | 5         | 6      | 1.36%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 6      | 1.08%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 1.08%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 1.08%   |
| Seagate ST3500320AS 500GB          | 4         | 7      | 1.08%   |
| Seagate ST31000528AS 1TB           | 4         | 5      | 1.08%   |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 7      | 1.08%   |
| HGST HTS545050A7E680 500GB         | 4         | 6      | 1.08%   |
| Drevo X1 SSD 120GB                 | 4         | 6      | 1.08%   |
| WDC WD20EZRX-00DC0B0 2TB           | 3         | 3      | 0.81%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 0.81%   |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.81%   |
| Seagate ST31500341AS 1TB           | 3         | 3      | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 3      | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 0.81%   |
| HGST HTS721010A9E630 1TB           | 3         | 3      | 0.81%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.81%   |
| Fujitsu MHZ2250BH G2 250GB         | 3         | 4      | 0.81%   |
| WDC WD6400AAKS-22A7B0 640GB        | 2         | 2      | 0.54%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 0.54%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 2         | 2      | 0.54%   |
| WDC WD40EZRX-00SPEB0 4TB           | 2         | 3      | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 2      | 0.54%   |
| WDC WD2500AAJS-00B4A0 250GB        | 2         | 2      | 0.54%   |
| WDC WD10EARS-00Y5B1 1TB            | 2         | 2      | 0.54%   |
| Toshiba Q300. 240GB SSD            | 2         | 2      | 0.54%   |
| Toshiba MQ01ABD075 752GB           | 2         | 3      | 0.54%   |
| Toshiba MK5076GSX 500GB            | 2         | 2      | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 2      | 0.54%   |
| Seagate ST3500830AS 500GB          | 2         | 3      | 0.54%   |
| Seagate ST3500820AS 500GB          | 2         | 2      | 0.54%   |
| Seagate ST3500312CS 500GB          | 2         | 2      | 0.54%   |
| Seagate ST320LT012-9WS14C 320GB    | 2         | 2      | 0.54%   |
| Seagate ST3200822AS 200GB          | 2         | 5      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 127       | 164    | 35.18%  |
| WDC                 | 64        | 74     | 17.73%  |
| Toshiba             | 25        | 27     | 6.93%   |
| Samsung Electronics | 25        | 26     | 6.93%   |
| Hitachi             | 24        | 26     | 6.65%   |
| Kingston            | 19        | 25     | 5.26%   |
| HGST                | 14        | 17     | 3.88%   |
| SanDisk             | 9         | 10     | 2.49%   |
| Intel               | 9         | 9      | 2.49%   |
| Maxtor              | 7         | 7      | 1.94%   |
| Crucial             | 7         | 8      | 1.94%   |
| Fujitsu             | 6         | 7      | 1.66%   |
| Drevo               | 5         | 7      | 1.39%   |
| OCZ                 | 3         | 3      | 0.83%   |
| China               | 3         | 4      | 0.83%   |
| Micron Technology   | 2         | 2      | 0.55%   |
| KingDian            | 2         | 2      | 0.55%   |
| Transcend           | 1         | 4      | 0.28%   |
| SK hynix            | 1         | 1      | 0.28%   |
| Patriot             | 1         | 1      | 0.28%   |
| Intenso             | 1         | 1      | 0.28%   |
| IBM                 | 1         | 1      | 0.28%   |
| Hypertec            | 1         | 1      | 0.28%   |
| ASMT                | 1         | 2      | 0.28%   |
| Apple               | 1         | 1      | 0.28%   |
| A-DATA Technology   | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 127       | 164    | 45.36%  |
| WDC                 | 63        | 73     | 22.5%   |
| Hitachi             | 24        | 26     | 8.57%   |
| Toshiba             | 20        | 22     | 7.14%   |
| Samsung Electronics | 15        | 16     | 5.36%   |
| HGST                | 14        | 17     | 5%      |
| Maxtor              | 7         | 7      | 2.5%    |
| Fujitsu             | 6         | 7      | 2.14%   |
| IBM                 | 1         | 1      | 0.36%   |
| China               | 1         | 1      | 0.36%   |
| ASMT                | 1         | 2      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 262       | 337    | 77.51%  |
| SSD  | 71        | 90     | 21.01%  |
| NVMe | 5         | 5      | 1.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB     | 1         | 1      | 11.11%  |
| Toshiba DT01ACA200 2TB          | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 11.11%  |
| Seagate ST3500830AS 500GB       | 1         | 1      | 11.11%  |
| Seagate ST31000528AS 1TB        | 1         | 1      | 11.11%  |
| Seagate ST31000520AS 1TB        | 1         | 1      | 11.11%  |
| Seagate ST31000333AS 1TB        | 1         | 1      | 11.11%  |
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 11.11%  |
| Hitachi HDS721010DLE630 1TB     | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 55.56%  |
| WDC                 | 1         | 1      | 11.11%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2693      | 5350   | 61.01%  |
| Works    | 1388      | 2476   | 31.45%  |
| Malfunc  | 324       | 432    | 7.34%   |
| Failed   | 9         | 9      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2815      | 57.15%  |
| AMD                              | 697       | 14.15%  |
| Samsung Electronics              | 359       | 7.29%   |
| SanDisk                          | 207       | 4.2%    |
| SK hynix                         | 97        | 1.97%   |
| Nvidia                           | 97        | 1.97%   |
| JMicron Technology               | 71        | 1.44%   |
| Phison Electronics               | 70        | 1.42%   |
| ASMedia Technology               | 69        | 1.4%    |
| Kingston Technology Company      | 66        | 1.34%   |
| Marvell Technology Group         | 56        | 1.14%   |
| Micron Technology                | 48        | 0.97%   |
| Toshiba America Info Systems     | 47        | 0.95%   |
| Micron/Crucial Technology        | 42        | 0.85%   |
| KIOXIA                           | 42        | 0.85%   |
| VIA Technologies                 | 31        | 0.63%   |
| Silicon Motion                   | 26        | 0.53%   |
| Silicon Integrated Systems [SiS] | 20        | 0.41%   |
| LSI Logic / Symbios Logic        | 11        | 0.22%   |
| Union Memory (Shenzhen)          | 7         | 0.14%   |
| Hewlett-Packard                  | 6         | 0.12%   |
| Silicon Image                    | 5         | 0.1%    |
| Realtek Semiconductor            | 4         | 0.08%   |
| Apple                            | 4         | 0.08%   |
| ADATA Technology                 | 4         | 0.08%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| Adaptec                          | 3         | 0.06%   |
| Unknown                          | 2         | 0.04%   |
| Seagate Technology               | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Lite-On Technology               | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| ULi Electronics                  | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |
| Broadcom / LSI                   | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 491       | 8.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 226       | 3.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 211       | 3.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 204       | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 126       | 2.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 124       | 2.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 119       | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 117       | 2.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 115       | 1.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 112       | 1.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 108       | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 100       | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 84        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 83        | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 81        | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 79        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 77        | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 75        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 74        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 73        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 71        | 1.22%   |
| Intel SATA Controller [RAID mode]                                                       | 71        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 70        | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 68        | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 67        | 1.15%   |
| Samsung NVMe SSD Controller 980                                                         | 62        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 61        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 59        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 57        | 0.98%   |
| Intel SSD 660P Series                                                                   | 55        | 0.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 51        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 51        | 0.87%   |
| Micron Non-Volatile memory controller                                                   | 48        | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 47        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 47        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 46        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 45        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 43        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2911      | 57.74%  |
| NVMe | 1061      | 21.04%  |
| IDE  | 748       | 14.84%  |
| RAID | 309       | 6.13%   |
| SCSI | 9         | 0.18%   |
| SAS  | 4         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3183      | 78.03%  |
| AMD          | 866       | 21.23%  |
| ARM          | 27        | 0.66%   |
| QUALCOMM     | 2         | 0.05%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 55        | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 53        | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 49        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 43        | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 37        | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 35        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 0.81%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 32        | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 32        | 0.78%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 0.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 30        | 0.73%   |
| AMD Ryzen 5 3600 6-Core Processor             | 29        | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.66%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 26        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 24        | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 23        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 22        | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 22        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.54%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 22        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 22        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.51%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.51%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 20        | 0.49%   |
| ARM Processor                                 | 20        | 0.49%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 20        | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 19        | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.46%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.44%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 18        | 0.44%   |
| AMD FX-8350 Eight-Core Processor              | 18        | 0.44%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 17        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 17        | 0.42%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 17        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 790       | 19.32%  |
| Intel Core i5           | 786       | 19.22%  |
| Intel Core i3           | 329       | 8.04%   |
| Intel Celeron           | 258       | 6.31%   |
| Intel Core 2 Duo        | 216       | 5.28%   |
| Other                   | 208       | 5.09%   |
| AMD Ryzen 5             | 201       | 4.91%   |
| AMD Ryzen 7             | 181       | 4.43%   |
| Intel Atom              | 122       | 2.98%   |
| Intel Xeon              | 84        | 2.05%   |
| Intel Pentium           | 76        | 1.86%   |
| Intel Pentium Dual-Core | 70        | 1.71%   |
| Intel Core 2 Quad       | 65        | 1.59%   |
| AMD FX                  | 56        | 1.37%   |
| Intel Pentium Dual      | 49        | 1.2%    |
| Intel Core 2            | 48        | 1.17%   |
| AMD A4                  | 39        | 0.95%   |
| AMD Ryzen 3             | 35        | 0.86%   |
| AMD Ryzen 9             | 31        | 0.76%   |
| AMD A6                  | 31        | 0.76%   |
| Intel Genuine           | 29        | 0.71%   |
| AMD A10                 | 28        | 0.68%   |
| AMD A8                  | 26        | 0.64%   |
| Intel Pentium 4         | 25        | 0.61%   |
| Intel Core i9           | 24        | 0.59%   |
| AMD Athlon 64 X2        | 22        | 0.54%   |
| AMD E1                  | 18        | 0.44%   |
| AMD Athlon II X2        | 18        | 0.44%   |
| AMD Athlon              | 18        | 0.44%   |
| AMD Phenom II X4        | 13        | 0.32%   |
| AMD Ryzen 7 PRO         | 11        | 0.27%   |
| Intel Pentium D         | 10        | 0.24%   |
| AMD Phenom              | 10        | 0.24%   |
| AMD E                   | 10        | 0.24%   |
| Intel Pentium M         | 9         | 0.22%   |
| Intel Pentium Silver    | 8         | 0.2%    |
| Intel Core m3           | 7         | 0.17%   |
| Intel Celeron M         | 7         | 0.17%   |
| AMD Sempron             | 7         | 0.17%   |
| AMD Phenom II X6        | 7         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1744      | 42.59%  |
| 4       | 1450      | 35.41%  |
| 6       | 364       | 8.89%   |
| 8       | 263       | 6.42%   |
| 1       | 163       | 3.98%   |
| 12      | 39        | 0.95%   |
| 3       | 19        | 0.46%   |
| 16      | 13        | 0.32%   |
| Unknown | 12        | 0.29%   |
| 10      | 11        | 0.27%   |
| 14      | 9         | 0.22%   |
| 20      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 32      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4046      | 99.17%  |
| 2       | 32        | 0.78%   |
| Unknown | 2         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2495      | 60.99%  |
| 1       | 1584      | 38.72%  |
| Unknown | 12        | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3895      | 94.84%  |
| Unknown        | 113       | 2.75%   |
| 32-bit         | 66        | 1.61%   |
| 64-bit         | 33        | 0.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 765       | 18.12%  |
| 0x306c3    | 236       | 5.59%   |
| 0x206a7    | 210       | 4.98%   |
| 0x306a9    | 190       | 4.5%    |
| 0x1067a    | 167       | 3.96%   |
| 0x906ea    | 131       | 3.1%    |
| 0x806ea    | 101       | 2.39%   |
| 0x6fd      | 98        | 2.32%   |
| 0x806c1    | 94        | 2.23%   |
| 0x506e3    | 89        | 2.11%   |
| 0x20655    | 88        | 2.08%   |
| 0x40651    | 87        | 2.06%   |
| 0x806ec    | 86        | 2.04%   |
| 0x806e9    | 81        | 1.92%   |
| 0x406e3    | 76        | 1.8%    |
| 0x306d4    | 72        | 1.71%   |
| 0x906e9    | 65        | 1.54%   |
| 0x08108109 | 56        | 1.33%   |
| 0x30678    | 51        | 1.21%   |
| 0x10676    | 50        | 1.18%   |
| 0x6fb      | 44        | 1.04%   |
| 0x20652    | 44        | 1.04%   |
| 0x706a1    | 43        | 1.02%   |
| 0x08701021 | 41        | 0.97%   |
| 0x0800820d | 40        | 0.95%   |
| 0x706e5    | 37        | 0.88%   |
| 0x6f6      | 35        | 0.83%   |
| 0x506c9    | 35        | 0.83%   |
| 0x406c4    | 35        | 0.83%   |
| 0x08108102 | 33        | 0.78%   |
| 0xa0652    | 32        | 0.76%   |
| 0x0a50000c | 32        | 0.76%   |
| 0x08600106 | 31        | 0.73%   |
| 0x06000852 | 31        | 0.73%   |
| 0x010000c8 | 31        | 0.73%   |
| 0x06006705 | 30        | 0.71%   |
| 0x806eb    | 28        | 0.66%   |
| 0x06001119 | 28        | 0.66%   |
| 0x406c3    | 27        | 0.64%   |
| 0x706a8    | 25        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 636       | 15.55%  |
| Haswell          | 405       | 9.9%    |
| Penryn           | 269       | 6.58%   |
| SandyBridge      | 256       | 6.26%   |
| Core             | 234       | 5.72%   |
| IvyBridge        | 224       | 5.48%   |
| Skylake          | 198       | 4.84%   |
| Zen+             | 164       | 4.01%   |
| Zen 2            | 160       | 3.91%   |
| Westmere         | 157       | 3.84%   |
| Silvermont       | 147       | 3.59%   |
| TigerLake        | 120       | 2.93%   |
| Broadwell        | 93        | 2.27%   |
| Piledriver       | 83        | 2.03%   |
| CometLake        | 83        | 2.03%   |
| Goldmont plus    | 82        | 2%      |
| K10              | 81        | 1.98%   |
| Unknown          | 75        | 1.83%   |
| Zen              | 74        | 1.81%   |
| Zen 3            | 71        | 1.74%   |
| Bonnell          | 58        | 1.42%   |
| IceLake          | 56        | 1.37%   |
| Excavator        | 55        | 1.34%   |
| K8 Hammer        | 50        | 1.22%   |
| Goldmont         | 40        | 0.98%   |
| NetBurst         | 38        | 0.93%   |
| Nehalem          | 37        | 0.9%    |
| P6               | 30        | 0.73%   |
| Puma             | 28        | 0.68%   |
| Jaguar           | 23        | 0.56%   |
| Bobcat           | 17        | 0.42%   |
| Steamroller      | 16        | 0.39%   |
| K10 Llano        | 9         | 0.22%   |
| Bulldozer        | 7         | 0.17%   |
| Alderlake Hybrid | 7         | 0.17%   |
| Tremont          | 3         | 0.07%   |
| K8 & K10 hybrid  | 3         | 0.07%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2349      | 49%     |
| Nvidia                                       | 1400      | 29.2%   |
| AMD                                          | 995       | 20.76%  |
| Matrox Electronics Systems                   | 17        | 0.35%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.27%   |
| VIA Technologies                             | 10        | 0.21%   |
| ASPEED Technology                            | 7         | 0.15%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 173       | 3.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 115       | 2.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 114       | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 111       | 2.24%   |
| Intel UHD Graphics 620                                                                   | 101       | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 96        | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 96        | 1.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 94        | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 90        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 87        | 1.75%   |
| Intel HD Graphics 620                                                                    | 82        | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 81        | 1.63%   |
| AMD Renoir                                                                               | 77        | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 76        | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 75        | 1.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 74        | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 71        | 1.43%   |
| Intel HD Graphics 5500                                                                   | 66        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 62        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 60        | 1.21%   |
| Intel HD Graphics 530                                                                    | 60        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 58        | 1.17%   |
| Intel HD Graphics 630                                                                    | 57        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 55        | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 53        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 48        | 0.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 47        | 0.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 42        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 41        | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 41        | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.81%   |
| AMD Cezanne                                                                              | 40        | 0.81%   |
| Intel HD Graphics 500                                                                    | 39        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 39        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 37        | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 0.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1694      | 41.26%  |
| 1 x Nvidia             | 799       | 19.46%  |
| 1 x AMD                | 790       | 19.24%  |
| Intel + Nvidia         | 519       | 12.64%  |
| Intel + AMD            | 84        | 2.05%   |
| AMD + Nvidia           | 65        | 1.58%   |
| 2 x AMD                | 57        | 1.39%   |
| Other                  | 32        | 0.78%   |
| 2 x Nvidia             | 14        | 0.34%   |
| 1 x Matrox             | 14        | 0.34%   |
| 1 x SiS                | 13        | 0.32%   |
| 1 x VIA                | 10        | 0.24%   |
| 1 x ASPEED             | 5         | 0.12%   |
| Nvidia + Matrox        | 3         | 0.07%   |
| Nvidia + ASPEED        | 2         | 0.05%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3280      | 79.11%  |
| Proprietary | 691       | 16.67%  |
| Unknown     | 175       | 4.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2155      | 51.31%  |
| 1.01-2.0   | 598       | 14.24%  |
| 0.01-0.5   | 513       | 12.21%  |
| 3.01-4.0   | 337       | 8.02%   |
| 0.51-1.0   | 323       | 7.69%   |
| 7.01-8.0   | 150       | 3.57%   |
| 5.01-6.0   | 77        | 1.83%   |
| 2.01-3.0   | 25        | 0.6%    |
| 8.01-16.0  | 19        | 0.45%   |
| 16.01-24.0 | 3         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 532       | 12.17%  |
| AU Optronics            | 471       | 10.78%  |
| Chimei Innolux          | 416       | 9.52%   |
| LG Display              | 380       | 8.7%    |
| Goldstar                | 308       | 7.05%   |
| BOE                     | 273       | 6.25%   |
| Hewlett-Packard         | 220       | 5.03%   |
| Dell                    | 172       | 3.94%   |
| BenQ                    | 172       | 3.94%   |
| Acer                    | 156       | 3.57%   |
| Ancor Communications    | 138       | 3.16%   |
| Philips                 | 118       | 2.7%    |
| AOC                     | 87        | 1.99%   |
| Chi Mei Optoelectronics | 84        | 1.92%   |
| Apple                   | 79        | 1.81%   |
| Sharp                   | 74        | 1.69%   |
| Lenovo                  | 68        | 1.56%   |
| LG Electronics          | 50        | 1.14%   |
| PANDA                   | 49        | 1.12%   |
| Unknown                 | 45        | 1.03%   |
| Sony                    | 38        | 0.87%   |
| LG Philips              | 38        | 0.87%   |
| HannStar                | 36        | 0.82%   |
| ASUSTek Computer        | 25        | 0.57%   |
| ViewSonic               | 23        | 0.53%   |
| InfoVision              | 17        | 0.39%   |
| MSI                     | 13        | 0.3%    |
| Eizo                    | 12        | 0.27%   |
| OEM                     | 11        | 0.25%   |
| Toshiba                 | 10        | 0.23%   |
| ___                     | 9         | 0.21%   |
| Panasonic               | 9         | 0.21%   |
| Hitachi                 | 9         | 0.21%   |
| CPT                     | 9         | 0.21%   |
| Packard Bell            | 8         | 0.18%   |
| Vestel Elektronik       | 7         | 0.16%   |
| Quanta Display          | 7         | 0.16%   |
| Iiyama                  | 7         | 0.16%   |
| Xiaomi                  | 6         | 0.14%   |
| NEC Computers           | 6         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 62        | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 30        | 0.66%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 26        | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 24        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.46%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 20        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 19        | 0.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 13        | 0.29%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 12        | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 12        | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 11        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 11        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.22%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch              | 10        | 0.22%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 10        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1786      | 42.85%  |
| 1366x768 (WXGA)    | 888       | 21.31%  |
| 1280x1024 (SXGA)   | 191       | 4.58%   |
| 3840x2160 (4K)     | 180       | 4.32%   |
| 1280x800 (WXGA)    | 147       | 3.53%   |
| 2560x1440 (QHD)    | 141       | 3.38%   |
| 1440x900 (WXGA+)   | 131       | 3.14%   |
| 1680x1050 (WSXGA+) | 130       | 3.12%   |
| 1600x900 (HD+)     | 97        | 2.33%   |
| 1920x1200 (WUXGA)  | 65        | 1.56%   |
| Unknown            | 55        | 1.32%   |
| 2560x1080          | 45        | 1.08%   |
| 1360x768           | 41        | 0.98%   |
| 1024x600           | 37        | 0.89%   |
| 3440x1440          | 25        | 0.6%    |
| 1024x768 (XGA)     | 23        | 0.55%   |
| 2560x1600          | 17        | 0.41%   |
| 2160x1440          | 17        | 0.41%   |
| 3840x1080          | 15        | 0.36%   |
| 1920x540           | 13        | 0.31%   |
| 2880x1800          | 11        | 0.26%   |
| 1600x1200          | 10        | 0.24%   |
| 800x1280           | 7         | 0.17%   |
| 3200x1800 (QHD+)   | 6         | 0.14%   |
| 3200x1080          | 5         | 0.12%   |
| 2288x1287          | 5         | 0.12%   |
| 4480x1080          | 4         | 0.1%    |
| 3840x2400          | 4         | 0.1%    |
| 1280x768           | 4         | 0.1%    |
| 3840x1200          | 3         | 0.07%   |
| 3600x1080          | 3         | 0.07%   |
| 3360x1080          | 3         | 0.07%   |
| 2960x1050          | 3         | 0.07%   |
| 2048x1152          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 5760x2160          | 2         | 0.05%   |
| 4480x1440          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 3200x2000          | 2         | 0.05%   |
| 2944x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1282      | 29.39%  |
| 13      | 329       | 7.54%   |
| 24      | 312       | 7.15%   |
| 21      | 309       | 7.08%   |
| 27      | 275       | 6.3%    |
| Unknown | 272       | 6.24%   |
| 23      | 249       | 5.71%   |
| 17      | 234       | 5.36%   |
| 14      | 218       | 5%      |
| 19      | 142       | 3.26%   |
| 18      | 106       | 2.43%   |
| 22      | 75        | 1.72%   |
| 34      | 63        | 1.44%   |
| 20      | 61        | 1.4%    |
| 12      | 57        | 1.31%   |
| 31      | 55        | 1.26%   |
| 10      | 45        | 1.03%   |
| 11      | 44        | 1.01%   |
| 84      | 36        | 0.83%   |
| 26      | 21        | 0.48%   |
| 72      | 20        | 0.46%   |
| 25      | 20        | 0.46%   |
| 16      | 20        | 0.46%   |
| 54      | 19        | 0.44%   |
| 32      | 18        | 0.41%   |
| 40      | 12        | 0.28%   |
| 52      | 7         | 0.16%   |
| 65      | 6         | 0.14%   |
| 46      | 6         | 0.14%   |
| 28      | 6         | 0.14%   |
| 142     | 4         | 0.09%   |
| 33      | 4         | 0.09%   |
| 8       | 4         | 0.09%   |
| 60      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 47      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 43      | 2         | 0.05%   |
| 39      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1720      | 40.13%  |
| 501-600        | 779       | 18.18%  |
| 401-500        | 622       | 14.51%  |
| 201-300        | 340       | 7.93%   |
| Unknown        | 272       | 6.35%   |
| 351-400        | 237       | 5.53%   |
| 601-700        | 94        | 2.19%   |
| 701-800        | 82        | 1.91%   |
| 1501-2000      | 57        | 1.33%   |
| 1001-1500      | 49        | 1.14%   |
| 801-900        | 18        | 0.42%   |
| 901-1000       | 5         | 0.12%   |
| More than 2000 | 4         | 0.09%   |
| 101-200        | 4         | 0.09%   |
| 1-100          | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2879      | 72.74%  |
| 16/10   | 497       | 12.56%  |
| Unknown | 229       | 5.79%   |
| 5/4     | 176       | 4.45%   |
| 21/9    | 65        | 1.64%   |
| 4/3     | 48        | 1.21%   |
| 3/2     | 42        | 1.06%   |
| 0.62    | 8         | 0.2%    |
| 1.00    | 4         | 0.1%    |
| 32/9    | 3         | 0.08%   |
| 6/5     | 1         | 0.03%   |
| 2.00    | 1         | 0.03%   |
| 1.03    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.58    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1278      | 29.49%  |
| 201-250        | 770       | 17.77%  |
| 81-90          | 384       | 8.86%   |
| 151-200        | 296       | 6.83%   |
| 301-350        | 282       | 6.51%   |
| Unknown        | 272       | 6.28%   |
| 141-150        | 190       | 4.38%   |
| 71-80          | 164       | 3.78%   |
| 351-500        | 139       | 3.21%   |
| 251-300        | 114       | 2.63%   |
| More than 1000 | 101       | 2.33%   |
| 121-130        | 100       | 2.31%   |
| 61-70          | 50        | 1.15%   |
| 41-50          | 45        | 1.04%   |
| 51-60          | 44        | 1.02%   |
| 501-1000       | 35        | 0.81%   |
| 131-140        | 31        | 0.72%   |
| 111-120        | 17        | 0.39%   |
| 91-100         | 14        | 0.32%   |
| 1-40           | 7         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1485      | 35.22%  |
| 101-120       | 1174      | 27.85%  |
| 121-160       | 954       | 22.63%  |
| Unknown       | 272       | 6.45%   |
| 161-240       | 188       | 4.46%   |
| 1-50          | 89        | 2.11%   |
| More than 240 | 54        | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3329      | 79.79%  |
| 2     | 583       | 13.97%  |
| 0     | 189       | 4.53%   |
| 3     | 67        | 1.61%   |
| 4     | 4         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2315      | 37.58%  |
| Intel                             | 1706      | 27.69%  |
| Qualcomm Atheros                  | 812       | 13.18%  |
| Broadcom                          | 386       | 6.27%   |
| Ralink Technology                 | 103       | 1.67%   |
| TP-Link                           | 101       | 1.64%   |
| Marvell Technology Group          | 93        | 1.51%   |
| Broadcom Limited                  | 86        | 1.4%    |
| Nvidia                            | 81        | 1.31%   |
| Ralink                            | 64        | 1.04%   |
| Qualcomm Atheros Communications   | 40        | 0.65%   |
| MediaTek                          | 30        | 0.49%   |
| Xiaomi                            | 24        | 0.39%   |
| Samsung Electronics               | 23        | 0.37%   |
| D-Link                            | 22        | 0.36%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.29%   |
| VIA Technologies                  | 17        | 0.28%   |
| D-Link System                     | 16        | 0.26%   |
| ASIX Electronics                  | 16        | 0.26%   |
| ASUSTek Computer                  | 15        | 0.24%   |
| Qualcomm                          | 13        | 0.21%   |
| Dell                              | 11        | 0.18%   |
| Belkin Components                 | 11        | 0.18%   |
| Ericsson Business Mobile Networks | 10        | 0.16%   |
| Sierra Wireless                   | 9         | 0.15%   |
| Lenovo                            | 9         | 0.15%   |
| JMicron Technology                | 9         | 0.15%   |
| Hewlett-Packard                   | 9         | 0.15%   |
| DisplayLink                       | 9         | 0.15%   |
| Microsoft                         | 7         | 0.11%   |
| Huawei Technologies               | 7         | 0.11%   |
| ZyDAS                             | 5         | 0.08%   |
| Microchip Technology              | 5         | 0.08%   |
| LSI                               | 4         | 0.06%   |
| Gemtek                            | 4         | 0.06%   |
| Edimax Technology                 | 4         | 0.06%   |
| Attansic Technology               | 4         | 0.06%   |
| Toshiba                           | 3         | 0.05%   |
| Texas Instruments                 | 3         | 0.05%   |
| Linksys                           | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1595      | 22.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 271       | 3.82%   |
| Intel Wi-Fi 6 AX200                                                     | 165       | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 119       | 1.68%   |
| Intel Wireless 8265 / 8275                                              | 102       | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 96        | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 94        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 93        | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 92        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 91        | 1.28%   |
| Intel Wi-Fi 6 AX201                                                     | 91        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 89        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 89        | 1.26%   |
| Intel Wireless 7265                                                     | 87        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 79        | 1.11%   |
| Intel Wireless 3165                                                     | 76        | 1.07%   |
| Intel I211 Gigabit Network Connection                                   | 73        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                    | 67        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 58        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 57        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.78%   |
| Realtek 802.11ac NIC                                                    | 54        | 0.76%   |
| Intel Wireless 7260                                                     | 54        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                       | 52        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 41        | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 41        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 41        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 39        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 39        | 0.55%   |
| Intel WiFi Link 5100                                                    | 38        | 0.54%   |
| Intel Wireless 8260                                                     | 37        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 37        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                 | 37        | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 36        | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 36        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 35        | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 35        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1278      | 39.52%  |
| Qualcomm Atheros                  | 622       | 19.23%  |
| Realtek Semiconductor             | 593       | 18.34%  |
| Broadcom                          | 236       | 7.3%    |
| Ralink Technology                 | 103       | 3.18%   |
| TP-Link                           | 84        | 2.6%    |
| Ralink                            | 64        | 1.98%   |
| Broadcom Limited                  | 59        | 1.82%   |
| Qualcomm Atheros Communications   | 40        | 1.24%   |
| MediaTek                          | 29        | 0.9%    |
| D-Link                            | 22        | 0.68%   |
| ASUSTek Computer                  | 15        | 0.46%   |
| Belkin Components                 | 11        | 0.34%   |
| D-Link System                     | 10        | 0.31%   |
| Sierra Wireless                   | 9         | 0.28%   |
| Microsoft                         | 7         | 0.22%   |
| Dell                              | 6         | 0.19%   |
| ZyDAS                             | 5         | 0.15%   |
| Qualcomm                          | 4         | 0.12%   |
| Gemtek                            | 4         | 0.12%   |
| Edimax Technology                 | 4         | 0.12%   |
| Texas Instruments                 | 3         | 0.09%   |
| Marvell Technology Group          | 3         | 0.09%   |
| Linksys                           | 3         | 0.09%   |
| Ericsson Business Mobile Networks | 3         | 0.09%   |
| Sitecom Europe                    | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| Hewlett-Packard                   | 2         | 0.06%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Xiaomi                            | 1         | 0.03%   |
| Wilocity                          | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| TRENDnet                          | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Standard Microsystems             | 1         | 0.03%   |
| Samsung Electronics               | 1         | 0.03%   |
| AirTies Wireless Networks         | 1         | 0.03%   |
| Accton Technology                 | 1         | 0.03%   |
| 3Com                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 165       | 5.07%   |
| Intel Wireless 8265 / 8275                                              | 102       | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 96        | 2.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 94        | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 92        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 91        | 2.8%    |
| Intel Wi-Fi 6 AX201                                                     | 91        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 89        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 89        | 2.74%   |
| Intel Wireless 7265                                                     | 87        | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 79        | 2.43%   |
| Intel Wireless 3165                                                     | 76        | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 58        | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 57        | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 1.69%   |
| Realtek 802.11ac NIC                                                    | 54        | 1.66%   |
| Intel Wireless 7260                                                     | 54        | 1.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 41        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 41        | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 39        | 1.2%    |
| Intel WiFi Link 5100                                                    | 38        | 1.17%   |
| Intel Wireless 8260                                                     | 37        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 37        | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 36        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 36        | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 35        | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 35        | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 34        | 1.05%   |
| Intel Wireless 3160                                                     | 33        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 32        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 31        | 0.95%   |
| Intel Wireless-AC 9260                                                  | 28        | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 24        | 0.74%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 21        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2075      | 55.98%  |
| Intel                                  | 773       | 20.85%  |
| Qualcomm Atheros                       | 264       | 7.12%   |
| Broadcom                               | 193       | 5.21%   |
| Marvell Technology Group               | 91        | 2.45%   |
| Nvidia                                 | 81        | 2.19%   |
| Broadcom Limited                       | 29        | 0.78%   |
| Xiaomi                                 | 23        | 0.62%   |
| Samsung Electronics                    | 22        | 0.59%   |
| Silicon Integrated Systems [SiS]       | 18        | 0.49%   |
| VIA Technologies                       | 17        | 0.46%   |
| TP-Link                                | 17        | 0.46%   |
| ASIX Electronics                       | 16        | 0.43%   |
| Qualcomm                               | 9         | 0.24%   |
| Lenovo                                 | 9         | 0.24%   |
| JMicron Technology                     | 9         | 0.24%   |
| DisplayLink                            | 9         | 0.24%   |
| D-Link System                          | 6         | 0.16%   |
| LSI                                    | 4         | 0.11%   |
| Attansic Technology                    | 4         | 0.11%   |
| Microchip Technology                   | 3         | 0.08%   |
| IBM                                    | 3         | 0.08%   |
| Hewlett-Packard                        | 3         | 0.08%   |
| Apple                                  | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.05%   |
| Huawei Technologies                    | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Davicom Semiconductor                  | 2         | 0.05%   |
| Aquantia                               | 2         | 0.05%   |
| ADMtek                                 | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| National Semiconductor                 | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |
| Meizu                                  | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1595      | 42.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 271       | 7.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 119       | 3.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 93        | 2.46%   |
| Intel I211 Gigabit Network Connection                             | 73        | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 67        | 1.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 41        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 32        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 31        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 30        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 30        | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 26        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 25        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 23        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 22        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                              | 22        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 21        | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 20        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 17        | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 16        | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 15        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 15        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3550      | 53.48%  |
| WiFi     | 3036      | 45.74%  |
| Modem    | 48        | 0.72%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2311      | 54.45%  |
| Ethernet | 1932      | 45.52%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2183      | 53.26%  |
| 1     | 1738      | 42.4%   |
| 0     | 98        | 2.39%   |
| 3     | 58        | 1.41%   |
| 4     | 15        | 0.37%   |
| 6     | 4         | 0.1%    |
| 5     | 3         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3978      | 97.19%  |
| Yes  | 115       | 2.81%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 995       | 43.15%  |
| Realtek Semiconductor           | 265       | 11.49%  |
| Cambridge Silicon Radio         | 217       | 9.41%   |
| Qualcomm Atheros Communications | 141       | 6.11%   |
| IMC Networks                    | 135       | 5.85%   |
| Broadcom                        | 102       | 4.42%   |
| Apple                           | 89        | 3.86%   |
| Lite-On Technology              | 77        | 3.34%   |
| Foxconn / Hon Hai               | 68        | 2.95%   |
| ASUSTek Computer                | 41        | 1.78%   |
| Toshiba                         | 33        | 1.43%   |
| Realtek                         | 26        | 1.13%   |
| Dell                            | 25        | 1.08%   |
| Hewlett-Packard                 | 22        | 0.95%   |
| Ralink                          | 16        | 0.69%   |
| Alps Electric                   | 12        | 0.52%   |
| Belkin Components               | 9         | 0.39%   |
| Integrated System Solution      | 7         | 0.3%    |
| Foxconn International           | 5         | 0.22%   |
| Ralink Technology               | 3         | 0.13%   |
| MediaTek                        | 3         | 0.13%   |
| TP-Link                         | 2         | 0.09%   |
| Roper                           | 2         | 0.09%   |
| Marvell Semiconductor           | 2         | 0.09%   |
| Edimax Technology               | 2         | 0.09%   |
| Askey Computer                  | 2         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 386       | 16.74%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 217       | 9.41%   |
| Realtek Bluetooth Radio                             | 193       | 8.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 172       | 7.46%   |
| Intel AX201 Bluetooth                               | 165       | 7.16%   |
| Intel AX200 Bluetooth                               | 161       | 6.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 59        | 2.56%   |
| IMC Networks Bluetooth Radio                        | 54        | 2.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 51        | 2.21%   |
| IMC Networks Bluetooth Device                       | 45        | 1.95%   |
| Apple Bluetooth Host Controller                     | 38        | 1.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 36        | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 32        | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 32        | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 28        | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.17%   |
| Realtek Bluetooth Radio                             | 26        | 1.13%   |
| Apple Bluetooth USB Host Controller                 | 26        | 1.13%   |
| Lite-On Bluetooth Device                            | 23        | 1%      |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 0.78%   |
| Intel AX210 Bluetooth                               | 17        | 0.74%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.69%   |
| IMC Networks Wireless_Device                        | 15        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.61%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 13        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 12        | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.48%   |
| Apple Bluetooth HCI                                 | 11        | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.43%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.43%   |
| Toshiba Integrated Bluetooth HCI                    | 9         | 0.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.35%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.35%   |
| Foxconn / Hon Hai BCM20702A0                        | 8         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2995      | 54.84%  |
| AMD                                  | 1052      | 19.26%  |
| Nvidia                               | 938       | 17.18%  |
| C-Media Electronics                  | 94        | 1.72%   |
| Creative Labs                        | 35        | 0.64%   |
| Logitech                             | 30        | 0.55%   |
| Silicon Integrated Systems [SiS]     | 20        | 0.37%   |
| Texas Instruments                    | 19        | 0.35%   |
| VIA Technologies                     | 18        | 0.33%   |
| JMTek                                | 18        | 0.33%   |
| GN Netcom                            | 15        | 0.27%   |
| Plantronics                          | 14        | 0.26%   |
| Kingston Technology                  | 13        | 0.24%   |
| Corsair                              | 13        | 0.24%   |
| Focusrite-Novation                   | 11        | 0.2%    |
| Creative Technology                  | 11        | 0.2%    |
| Realtek Semiconductor                | 9         | 0.16%   |
| Lenovo                               | 9         | 0.16%   |
| Generalplus Technology               | 9         | 0.16%   |
| SteelSeries ApS                      | 7         | 0.13%   |
| Ensoniq                              | 6         | 0.11%   |
| ASUSTek Computer                     | 6         | 0.11%   |
| M-Audio                              | 5         | 0.09%   |
| Hewlett-Packard                      | 5         | 0.09%   |
| BEHRINGER International              | 5         | 0.09%   |
| Yamaha                               | 4         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.07%   |
| Tenx Technology                      | 4         | 0.07%   |
| DSEA A/S                             | 4         | 0.07%   |
| Blue Microphones                     | 4         | 0.07%   |
| SAVITECH                             | 3         | 0.05%   |
| QinHeng Electronics                  | 3         | 0.05%   |
| Guillemot                            | 3         | 0.05%   |
| Evolution Electronics                | 3         | 0.05%   |
| Elite Silicon                        | 3         | 0.05%   |
| Apple                                | 3         | 0.05%   |
| XMOS                                 | 2         | 0.04%   |
| Sony                                 | 2         | 0.04%   |
| Sennheiser Communications            | 2         | 0.04%   |
| Razer USA                            | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 283       | 4.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 277       | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 244       | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 240       | 3.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 219       | 3.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 205       | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 184       | 2.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 172       | 2.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 165       | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 158       | 2.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 134       | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 124       | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 120       | 1.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 118       | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 116       | 1.8%    |
| AMD FCH Azalia Controller                                                  | 116       | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 113       | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 112       | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 111       | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 103       | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 99        | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 95        | 1.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 93        | 1.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 91        | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 87        | 1.35%   |
| Intel 200 Series PCH HD Audio                                              | 87        | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 85        | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 82        | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 79        | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 74        | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 69        | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                   | 60        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 56        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 55        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 54        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 54        | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 53        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 48        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 48        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 43        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 500       | 22.5%   |
| SK hynix                     | 352       | 15.84%  |
| Kingston                     | 347       | 15.62%  |
| Unknown                      | 258       | 11.61%  |
| Micron Technology            | 195       | 8.78%   |
| Crucial                      | 148       | 6.66%   |
| Corsair                      | 91        | 4.1%    |
| G.Skill                      | 71        | 3.2%    |
| Ramaxel Technology           | 57        | 2.57%   |
| Unknown (ABCD)               | 33        | 1.49%   |
| Elpida                       | 32        | 1.44%   |
| Nanya Technology             | 19        | 0.86%   |
| A-DATA Technology            | 17        | 0.77%   |
| Silicon Power                | 11        | 0.5%    |
| GOODRAM                      | 10        | 0.45%   |
| Transcend                    | 8         | 0.36%   |
| Unknown                      | 8         | 0.36%   |
| Unifosa                      | 6         | 0.27%   |
| Team                         | 5         | 0.23%   |
| Apacer                       | 5         | 0.23%   |
| Wilk                         | 4         | 0.18%   |
| Patriot                      | 4         | 0.18%   |
| ASint Technology             | 4         | 0.18%   |
| Kllisre                      | 3         | 0.14%   |
| Atermiter                    | 3         | 0.14%   |
| SHARETRONIC                  | 2         | 0.09%   |
| Qimonda                      | 2         | 0.09%   |
| PNY                          | 2         | 0.09%   |
| KomputerBay                  | 2         | 0.09%   |
| Innodisk                     | 2         | 0.09%   |
| Exceleram                    | 2         | 0.09%   |
| Avant                        | 2         | 0.09%   |
| Unknown (AB)                 | 1         | 0.05%   |
| Unknown (07FB)               | 1         | 0.05%   |
| Toshiba                      | 1         | 0.05%   |
| Thermaltake                  | 1         | 0.05%   |
| Pioneer                      | 1         | 0.05%   |
| Patriot Memory (PDP Systems) | 1         | 0.05%   |
| Netlist                      | 1         | 0.05%   |
| Neo Forza                    | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 27        | 1.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 22        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 21        | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 18        | 0.75%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 17        | 0.71%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 17        | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 12        | 0.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 12        | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 11        | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.46%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 11        | 0.46%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s         | 11        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 10        | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 10        | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 10        | 0.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 10        | 0.42%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.38%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 8         | 0.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 8         | 0.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.33%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.33%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 8         | 0.33%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s            | 8         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 890       | 46.09%  |
| DDR3    | 654       | 33.87%  |
| DDR2    | 123       | 6.37%   |
| LPDDR4  | 70        | 3.63%   |
| Unknown | 68        | 3.52%   |
| SDRAM   | 57        | 2.95%   |
| LPDDR3  | 47        | 2.43%   |
| DDR     | 15        | 0.78%   |
| DRAM    | 6         | 0.31%   |
| DDR5    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1142      | 59.02%  |
| DIMM         | 662       | 34.21%  |
| Row Of Chips | 118       | 6.1%    |
| Chip         | 9         | 0.47%   |
| FB-DIMM      | 3         | 0.16%   |
| RIMM         | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 761       | 36%     |
| 4096  | 614       | 29.04%  |
| 2048  | 305       | 14.43%  |
| 16384 | 284       | 13.43%  |
| 1024  | 100       | 4.73%   |
| 32768 | 37        | 1.75%   |
| 512   | 8         | 0.38%   |
| 65536 | 2         | 0.09%   |
| 256   | 2         | 0.09%   |
| 3072  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 408       | 19.45%  |
| 2667    | 313       | 14.92%  |
| 3200    | 283       | 13.49%  |
| 2400    | 174       | 8.29%   |
| 1333    | 152       | 7.24%   |
| 2133    | 107       | 5.1%    |
| 667     | 82        | 3.91%   |
| 1334    | 68        | 3.24%   |
| 800     | 64        | 3.05%   |
| 3600    | 53        | 2.53%   |
| Unknown | 50        | 2.38%   |
| 1867    | 42        | 2%      |
| 8400    | 28        | 1.33%   |
| 4267    | 25        | 1.19%   |
| 3466    | 24        | 1.14%   |
| 1067    | 23        | 1.1%    |
| 3266    | 20        | 0.95%   |
| 2933    | 20        | 0.95%   |
| 1866    | 16        | 0.76%   |
| 1066    | 15        | 0.71%   |
| 533     | 14        | 0.67%   |
| 4199    | 12        | 0.57%   |
| 2733    | 12        | 0.57%   |
| 2048    | 12        | 0.57%   |
| 3000    | 8         | 0.38%   |
| 3400    | 6         | 0.29%   |
| 2666    | 5         | 0.24%   |
| 975     | 5         | 0.24%   |
| 400     | 5         | 0.24%   |
| 3800    | 4         | 0.19%   |
| 3733    | 4         | 0.19%   |
| 3500    | 4         | 0.19%   |
| 1800    | 4         | 0.19%   |
| 1639    | 4         | 0.19%   |
| 4266    | 3         | 0.14%   |
| 333     | 3         | 0.14%   |
| 2800    | 2         | 0.1%    |
| 266     | 2         | 0.1%    |
| 200     | 2         | 0.1%    |
| 57535   | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 56        | 49.12%  |
| Brother Industries       | 21        | 18.42%  |
| Canon                    | 12        | 10.53%  |
| Samsung Electronics      | 9         | 7.89%   |
| Seiko Epson              | 7         | 6.14%   |
| Oki Data                 | 2         | 1.75%   |
| Dymo-CoStar              | 2         | 1.75%   |
| Ricoh                    | 1         | 0.88%   |
| Magic Control Technology | 1         | 0.88%   |
| Lexmark International    | 1         | 0.88%   |
| Kyocera                  | 1         | 0.88%   |
| Apple                    | 1         | 0.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 4.35%   |
| Brother HL-2030 Laser Printer                   | 5         | 4.35%   |
| Canon PIXMA MG2500 Series                       | 4         | 3.48%   |
| HP LaserJet 1020                                | 3         | 2.61%   |
| HP Deskjet 1050 J410                            | 3         | 2.61%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.74%   |
| Samsung M2070 Series                            | 2         | 1.74%   |
| Oki Data USB Device                             | 2         | 1.74%   |
| HP LaserJet 1010                                | 2         | 1.74%   |
| HP ENVY 5540 series                             | 2         | 1.74%   |
| HP ENVY 5000 series                             | 2         | 1.74%   |
| HP ENVY 4520 series                             | 2         | 1.74%   |
| HP DeskJet F2492 All-in-One                     | 2         | 1.74%   |
| HP DeskJet 5550                                 | 2         | 1.74%   |
| HP DeskJet 3630 series                          | 2         | 1.74%   |
| HP DeskJet 2620 All-in-One Printer              | 2         | 1.74%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.74%   |
| Canon LiDE 400                                  | 2         | 1.74%   |
| Brother Printer                                 | 2         | 1.74%   |
| Brother MFC-J5330DW                             | 2         | 1.74%   |
| Brother DCP-1510                                | 2         | 1.74%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.87%   |
| Seiko Epson XP-230 Series                       | 1         | 0.87%   |
| Seiko Epson XP-225 Series                       | 1         | 0.87%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.87%   |
| Seiko Epson Printer                             | 1         | 0.87%   |
| Seiko Epson L555 Series                         | 1         | 0.87%   |
| Seiko Epson L1300 Series                        | 1         | 0.87%   |
| Samsung SCX-4300 Series                         | 1         | 0.87%   |
| Samsung SCX-3400 Series                         | 1         | 0.87%   |
| Samsung SCX-3200 Series                         | 1         | 0.87%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.87%   |
| Samsung M267x 287x Series                       | 1         | 0.87%   |
| Ricoh SP 112                                    | 1         | 0.87%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.87%   |
| Lexmark International B2236dw                   | 1         | 0.87%   |
| Kyocera ECOSYS M5521cdn                         | 1         | 0.87%   |
| HP PSC-1315/PSC-1317                            | 1         | 0.87%   |
| HP PSC 1500 series                              | 1         | 0.87%   |
| HP Printing Support                             | 1         | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 45.16%  |
| Hewlett-Packard             | 8         | 25.81%  |
| Seiko Epson                 | 5         | 16.13%  |
| Acer Peripherals (now BenQ) | 2         | 6.45%   |
| Mustek Systems              | 1         | 3.23%   |
| KYE Systems (Mouse Systems) | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.9%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.45%   |
| HP Scanjet 300                                           | 2         | 6.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.45%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.45%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.45%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.45%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.23%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.23%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.23%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.23%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.23%   |
| HP Scanjet N6010                                         | 1         | 3.23%   |
| HP ScanJet 5200c                                         | 1         | 3.23%   |
| HP ScanJet 4570c                                         | 1         | 3.23%   |
| HP ScanJet 4300c                                         | 1         | 3.23%   |
| HP ScanJet 3570c                                         | 1         | 3.23%   |
| HP ScanJet 3300c                                         | 1         | 3.23%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.23%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.23%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 543       | 23.21%  |
| IMC Networks                           | 253       | 10.81%  |
| Acer                                   | 221       | 9.44%   |
| Realtek Semiconductor                  | 149       | 6.37%   |
| Microdia                               | 147       | 6.28%   |
| Logitech                               | 111       | 4.74%   |
| Suyin                                  | 110       | 4.7%    |
| Sunplus Innovation Technology          | 103       | 4.4%    |
| Quanta                                 | 103       | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 80        | 3.42%   |
| Syntek                                 | 63        | 2.69%   |
| Apple                                  | 60        | 2.56%   |
| Alcor Micro                            | 41        | 1.75%   |
| Lite-On Technology                     | 37        | 1.58%   |
| Ricoh                                  | 28        | 1.2%    |
| Luxvisions Innotech Limited            | 25        | 1.07%   |
| Silicon Motion                         | 19        | 0.81%   |
| Samsung Electronics                    | 19        | 0.81%   |
| Creative Technology                    | 16        | 0.68%   |
| Z-Star Microelectronics                | 14        | 0.6%    |
| GEMBIRD                                | 13        | 0.56%   |
| Microsoft                              | 12        | 0.51%   |
| Generalplus Technology                 | 11        | 0.47%   |
| Lenovo                                 | 9         | 0.38%   |
| Importek                               | 9         | 0.38%   |
| KYE Systems (Mouse Systems)            | 8         | 0.34%   |
| ARC International                      | 8         | 0.34%   |
| ALi                                    | 8         | 0.34%   |
| Jieli Technology                       | 7         | 0.3%    |
| Sunplus Technology                     | 6         | 0.26%   |
| Genesys Logic                          | 6         | 0.26%   |
| 2M UVC CAMERA                          | 6         | 0.26%   |
| Sonix Technology                       | 5         | 0.21%   |
| Primax Electronics                     | 5         | 0.21%   |
| Intel                                  | 5         | 0.21%   |
| icSpring                               | 5         | 0.21%   |
| Cubeternet                             | 5         | 0.21%   |
| OmniVision Technologies                | 4         | 0.17%   |
| Aveo Technology                        | 4         | 0.17%   |
| Arkmicro Technologies                  | 4         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam        | 66        | 2.8%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 62        | 2.63%   |
| Chicony HD WebCam                        | 58        | 2.46%   |
| Microdia Integrated_Webcam_HD            | 52        | 2.21%   |
| Acer Integrated Camera                   | 52        | 2.21%   |
| Chicony Integrated Camera                | 50        | 2.12%   |
| Acer HD Webcam                           | 44        | 1.87%   |
| IMC Networks Integrated Camera           | 39        | 1.66%   |
| Chicony USB2.0 VGA UVC WebCam            | 38        | 1.61%   |
| Realtek Integrated_Webcam_HD             | 30        | 1.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 29        | 1.23%   |
| Quanta HP TrueVision HD Camera           | 29        | 1.23%   |
| Logitech Webcam C270                     | 27        | 1.15%   |
| Chicony EasyCamera                       | 25        | 1.06%   |
| Chicony TOSHIBA Web Camera - HD          | 24        | 1.02%   |
| Apple Built-in iSight                    | 24        | 1.02%   |
| Realtek USB Camera                       | 23        | 0.98%   |
| Chicony USB 2.0 Camera                   | 23        | 0.98%   |
| Syntek Integrated Camera                 | 22        | 0.93%   |
| Sunplus HD WebCam                        | 21        | 0.89%   |
| Acer EasyCamera                          | 20        | 0.85%   |
| Samsung Galaxy A5 (MTP)                  | 19        | 0.81%   |
| Microdia Webcam Vitade AF                | 19        | 0.81%   |
| Chicony USB2.0 HD UVC WebCam             | 18        | 0.76%   |
| Chicony HP Truevision HD                 | 17        | 0.72%   |
| Acer HD Camera                           | 17        | 0.72%   |
| Syntek EasyCamera                        | 16        | 0.68%   |
| Lite-On Integrated Camera                | 16        | 0.68%   |
| Acer Lenovo EasyCamera                   | 16        | 0.68%   |
| Chicony HP TrueVision HD Camera          | 15        | 0.64%   |
| Apple FaceTime HD Camera (Built-in)      | 15        | 0.64%   |
| Syntek Lenovo EasyCamera                 | 14        | 0.59%   |
| Realtek Lenovo EasyCamera                | 14        | 0.59%   |
| Quanta HP HD Camera                      | 14        | 0.59%   |
| Logitech HD Pro Webcam C920              | 14        | 0.59%   |
| Chicony Integrated Camera (1280x720@30)  | 14        | 0.59%   |
| Chicony HP HD Camera                     | 14        | 0.59%   |
| Acer BisonCam, NB Pro                    | 14        | 0.59%   |
| Suyin HP Truevision HD                   | 13        | 0.55%   |
| Quanta HP Webcam                         | 13        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 99        | 29.29%  |
| Validity Sensors           | 81        | 23.96%  |
| Shenzhen Goodix Technology | 53        | 15.68%  |
| Elan Microelectronics      | 35        | 10.36%  |
| AuthenTec                  | 33        | 9.76%   |
| Upek                       | 21        | 6.21%   |
| LighTuning Technology      | 10        | 2.96%   |
| STMicroelectronics         | 6         | 1.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 41        | 12.13%  |
| Shenzhen Goodix  Fingerprint Device                                        | 34        | 10.06%  |
| Elan ELAN:Fingerprint                                                      | 33        | 9.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 7.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 4.73%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 4.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 4.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.25%   |
| Synaptics  WBDI                                                            | 9         | 2.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.07%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.78%   |
| AuthenTec AES1600                                                          | 6         | 1.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.48%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 1.48%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.48%   |
| AuthenTec AES2810                                                          | 5         | 1.48%   |
| Validity Sensors VFS491                                                    | 4         | 1.18%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.18%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.18%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.18%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.18%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.89%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.89%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.59%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.59%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.59%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.59%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.3%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.3%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 62        | 35.03%  |
| Broadcom                  | 45        | 25.42%  |
| O2 Micro                  | 22        | 12.43%  |
| Advanced Card Systems     | 8         | 4.52%   |
| Lenovo                    | 7         | 3.95%   |
| Chicony Electronics       | 5         | 2.82%   |
| Cherry                    | 5         | 2.82%   |
| Upek                      | 4         | 2.26%   |
| Realtek Semiconductor     | 4         | 2.26%   |
| C3PO                      | 4         | 2.26%   |
| Gemalto (was Gemplus)     | 3         | 1.69%   |
| SCM Microsystems          | 2         | 1.13%   |
| OmniKey                   | 2         | 1.13%   |
| Hewlett-Packard           | 2         | 1.13%   |
| In Focus Systems          | 1         | 0.56%   |
| Fujitsu Siemens Computers | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 58        | 32.77%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 11.86%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 9.04%   |
| Broadcom 5880                                                                | 12        | 6.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.08%   |
| Broadcom 58200                                                               | 8         | 4.52%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.95%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 3.39%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 5         | 2.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.26%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.26%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 2.26%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 2.26%   |
| C3PO LTC31v2                                                                 | 3         | 1.69%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.13%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.13%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.13%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.56%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.56%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.56%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.56%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.56%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.56%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.56%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3083      | 73.77%  |
| 1     | 877       | 20.99%  |
| 2     | 181       | 4.33%   |
| 3     | 27        | 0.65%   |
| 4     | 5         | 0.12%   |
| 5     | 3         | 0.07%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 332       | 25.32%  |
| Graphics card            | 316       | 24.1%   |
| Net/wireless             | 197       | 15.03%  |
| Chipcard                 | 143       | 10.91%  |
| Multimedia controller    | 85        | 6.48%   |
| Communication controller | 41        | 3.13%   |
| Bluetooth                | 34        | 2.59%   |
| Camera                   | 33        | 2.52%   |
| Unassigned class         | 24        | 1.83%   |
| Storage                  | 20        | 1.53%   |
| Card reader              | 19        | 1.45%   |
| Sound                    | 16        | 1.22%   |
| Net/ethernet             | 13        | 0.99%   |
| Network                  | 10        | 0.76%   |
| Flash memory             | 10        | 0.76%   |
| Modem                    | 9         | 0.69%   |
| Dvb card                 | 5         | 0.38%   |
| Firewire controller      | 3         | 0.23%   |
| Storage/ide              | 1         | 0.08%   |

