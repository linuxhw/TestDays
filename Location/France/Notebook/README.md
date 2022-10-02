Linux in France - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 5516

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | GF65 Thin 9SEXR             | [537828a21f](https://linux-hardware.org/?probe=537828a21f) | Oct 01, 2022 |
| UNOWHY        | Y13G012S4EI                 | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [462f9bbdbe](https://linux-hardware.org/?probe=462f9bbdbe) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [571271ed93](https://linux-hardware.org/?probe=571271ed93) | Sep 30, 2022 |
| MSI           | Modern 14 A10M              | [9da1f3fe66](https://linux-hardware.org/?probe=9da1f3fe66) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Toshiba       | Satellite L670              | [3b3e7965a5](https://linux-hardware.org/?probe=3b3e7965a5) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [0cbacebb95](https://linux-hardware.org/?probe=0cbacebb95) | Sep 29, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [27c854b1a0](https://linux-hardware.org/?probe=27c854b1a0) | Sep 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Dell          | Latitude E5250              | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| Timi          | TM1604                      | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| MSI           | GS73 Stealth 8RF            | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
| ASUSTek       | X580VD                      | [378e1d3133](https://linux-hardware.org/?probe=378e1d3133) | Sep 26, 2022 |
| Packard Be... | EasyNote LS44SB             | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [0073af9597](https://linux-hardware.org/?probe=0073af9597) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [6935ebecaa](https://linux-hardware.org/?probe=6935ebecaa) | Sep 26, 2022 |
| HP            | Spectre Pro x360 G2         | [d9248f7b2e](https://linux-hardware.org/?probe=d9248f7b2e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| Acer          | Aspire 3810T                | [de19c5a7e9](https://linux-hardware.org/?probe=de19c5a7e9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [6cdacdb935](https://linux-hardware.org/?probe=6cdacdb935) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| HP            | Laptop 17-bs0xx             | [33398b1a21](https://linux-hardware.org/?probe=33398b1a21) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Dell          | Precision 3561              | [78b8d776ed](https://linux-hardware.org/?probe=78b8d776ed) | Sep 23, 2022 |
| Notebook      | NL40_50GU                   | [da07f4c223](https://linux-hardware.org/?probe=da07f4c223) | Sep 23, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| ASUSTek       | UX510UXK                    | [baa57d8e16](https://linux-hardware.org/?probe=baa57d8e16) | Sep 21, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | [869b076838](https://linux-hardware.org/?probe=869b076838) | Sep 21, 2022 |
| Acer          | Aspire E1-572               | [ba47323a29](https://linux-hardware.org/?probe=ba47323a29) | Sep 21, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [e234a2b52a](https://linux-hardware.org/?probe=e234a2b52a) | Sep 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [982931b71f](https://linux-hardware.org/?probe=982931b71f) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98d21fb774](https://linux-hardware.org/?probe=98d21fb774) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [a454bf3aa7](https://linux-hardware.org/?probe=a454bf3aa7) | Sep 20, 2022 |
| Valve         | Jupiter                     | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [5d42a6abab](https://linux-hardware.org/?probe=5d42a6abab) | Sep 20, 2022 |
| Toshiba       | Satellite L875-11M          | [42f3498e9e](https://linux-hardware.org/?probe=42f3498e9e) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Valve         | Jupiter                     | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| PC Special... | NS50MU                      | [1843dfbb66](https://linux-hardware.org/?probe=1843dfbb66) | Sep 19, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [89894daeb7](https://linux-hardware.org/?probe=89894daeb7) | Sep 19, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| HP            | 470 G7 Notebook PC          | [a9f6ad0c32](https://linux-hardware.org/?probe=a9f6ad0c32) | Sep 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [1fa9b05720](https://linux-hardware.org/?probe=1fa9b05720) | Sep 18, 2022 |
| Lenovo        | ThinkPad X200 7458VL3       | [700ff6630e](https://linux-hardware.org/?probe=700ff6630e) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [fde2d03f98](https://linux-hardware.org/?probe=fde2d03f98) | Sep 17, 2022 |
| Dell          | Latitude E5540              | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
| Valve         | Jupiter                     | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7a390e81b1](https://linux-hardware.org/?probe=7a390e81b1) | Sep 16, 2022 |
| HP            | ZBook Firefly 14 inch G9... | [f543e0852f](https://linux-hardware.org/?probe=f543e0852f) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0CN1... | [2f9eaf5711](https://linux-hardware.org/?probe=2f9eaf5711) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [1a1ae1e398](https://linux-hardware.org/?probe=1a1ae1e398) | Sep 15, 2022 |
| Acer          | Aspire A515-51G             | [bc275a0476](https://linux-hardware.org/?probe=bc275a0476) | Sep 15, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [84dee7df6c](https://linux-hardware.org/?probe=84dee7df6c) | Sep 15, 2022 |
| Dell          | Precision 3571              | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [000eb38ea7](https://linux-hardware.org/?probe=000eb38ea7) | Sep 15, 2022 |
| HP            | OMEN by Laptop              | [282afe0352](https://linux-hardware.org/?probe=282afe0352) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude E7470              | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Dell          | Precision 7550              | [f6a8b38020](https://linux-hardware.org/?probe=f6a8b38020) | Sep 14, 2022 |
| Dell          | Inspiron 15 3520            | [1d74f86789](https://linux-hardware.org/?probe=1d74f86789) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Dell          | Precision 7520              | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| HP            | Pavilion dv7                | [f94d6a4e8f](https://linux-hardware.org/?probe=f94d6a4e8f) | Sep 14, 2022 |
| Dell          | Latitude E5550              | [90674e3069](https://linux-hardware.org/?probe=90674e3069) | Sep 13, 2022 |
| ASUSTek       | X750JB                      | [dd6137189b](https://linux-hardware.org/?probe=dd6137189b) | Sep 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [d441c68f40](https://linux-hardware.org/?probe=d441c68f40) | Sep 13, 2022 |
| Samsung       | 950XED                      | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [3e00c86066](https://linux-hardware.org/?probe=3e00c86066) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [999cbe4e8f](https://linux-hardware.org/?probe=999cbe4e8f) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [9211f5de76](https://linux-hardware.org/?probe=9211f5de76) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0e6413e94b](https://linux-hardware.org/?probe=0e6413e94b) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| HP            | 470 G7 Notebook PC          | [f1c4e72e54](https://linux-hardware.org/?probe=f1c4e72e54) | Sep 12, 2022 |
| Dell          | Vostro 5620                 | [6c88032385](https://linux-hardware.org/?probe=6c88032385) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [3d1d8301c3](https://linux-hardware.org/?probe=3d1d8301c3) | Sep 12, 2022 |
| Dell          | Vostro 3400                 | [06c0b65315](https://linux-hardware.org/?probe=06c0b65315) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | [59d8ed6557](https://linux-hardware.org/?probe=59d8ed6557) | Sep 11, 2022 |
| Dell          | Latitude E7240              | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Apple         | MacBookPro13,1              | [4b7f579852](https://linux-hardware.org/?probe=4b7f579852) | Sep 11, 2022 |
| HP            | Laptop 17-bs0xx             | [512a6bd927](https://linux-hardware.org/?probe=512a6bd927) | Sep 11, 2022 |
| HP            | ProBook 6570b               | [998630e822](https://linux-hardware.org/?probe=998630e822) | Sep 10, 2022 |
| Framework     | Laptop                      | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8df1767beb](https://linux-hardware.org/?probe=8df1767beb) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d946b5e886](https://linux-hardware.org/?probe=d946b5e886) | Sep 09, 2022 |
| Dell          | Precision 7560              | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [e42f779622](https://linux-hardware.org/?probe=e42f779622) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| HP            | ZBook 15                    | [89a1ed226b](https://linux-hardware.org/?probe=89a1ed226b) | Sep 08, 2022 |
| System76      | Lemur                       | [5993c130bc](https://linux-hardware.org/?probe=5993c130bc) | Sep 07, 2022 |
| Dell          | Precision M4800             | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Dell          | Precision M4800             | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| Dell          | Latitude 9520               | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| HP            | ProBook 450 G1              | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| ASUSTek       | X302LA                      | [bc5ccb7df4](https://linux-hardware.org/?probe=bc5ccb7df4) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [e61768b292](https://linux-hardware.org/?probe=e61768b292) | Sep 04, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [0a729ebdd9](https://linux-hardware.org/?probe=0a729ebdd9) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| ASUSTek       | X756UAM                     | [23f0391963](https://linux-hardware.org/?probe=23f0391963) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [be1fece9bd](https://linux-hardware.org/?probe=be1fece9bd) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8e1f677318](https://linux-hardware.org/?probe=8e1f677318) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| HP            | 250 G7 Notebook PC          | [45ff2a4622](https://linux-hardware.org/?probe=45ff2a4622) | Sep 02, 2022 |
| Acer          | Aspire 5715Z                | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [525a1bd6b6](https://linux-hardware.org/?probe=525a1bd6b6) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| Acer          | Aspire V3-571G              | [8f4a2b603a](https://linux-hardware.org/?probe=8f4a2b603a) | Aug 31, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| Toshiba       | Satellite Pro L500          | [7f523718cf](https://linux-hardware.org/?probe=7f523718cf) | Aug 31, 2022 |
| Dell          | Inspiron 7720               | [97883c54a3](https://linux-hardware.org/?probe=97883c54a3) | Aug 31, 2022 |
| Dell          | Precision 3551              | [c9ffa625ad](https://linux-hardware.org/?probe=c9ffa625ad) | Aug 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [193310218d](https://linux-hardware.org/?probe=193310218d) | Aug 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d36b7bb077](https://linux-hardware.org/?probe=d36b7bb077) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| ASUSTek       | K501LX                      | [993e5d9848](https://linux-hardware.org/?probe=993e5d9848) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| Dell          | Precision 3570              | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| ASUSTek       | X751LJC                     | [36c35406c9](https://linux-hardware.org/?probe=36c35406c9) | Aug 29, 2022 |
| ASUSTek       | N71Jv                       | [b30a3030ae](https://linux-hardware.org/?probe=b30a3030ae) | Aug 28, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [a66f7c7a3a](https://linux-hardware.org/?probe=a66f7c7a3a) | Aug 28, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [3d1138a71c](https://linux-hardware.org/?probe=3d1138a71c) | Aug 27, 2022 |
| Dell          | Latitude E5470              | [7d49878b0d](https://linux-hardware.org/?probe=7d49878b0d) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3f94d521d4](https://linux-hardware.org/?probe=3f94d521d4) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Apple         | MacBookPro9,2               | [49b01e516c](https://linux-hardware.org/?probe=49b01e516c) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Notebook      | W65_67SZ                    | [0bf839f496](https://linux-hardware.org/?probe=0bf839f496) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| Dell          | Precision M4800             | [b00f73e4a3](https://linux-hardware.org/?probe=b00f73e4a3) | Aug 24, 2022 |
| HP            | Compaq CQ58                 | [c4f7e439a9](https://linux-hardware.org/?probe=c4f7e439a9) | Aug 24, 2022 |
| Dell          | Latitude E7240              | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| HP            | ZBook 15 G6                 | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | [4306baa541](https://linux-hardware.org/?probe=4306baa541) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| Dell          | XPS L421X                   | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [2aa681b773](https://linux-hardware.org/?probe=2aa681b773) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a51a82210b](https://linux-hardware.org/?probe=a51a82210b) | Aug 22, 2022 |
| ASUSTek       | X751LN                      | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [838dcef1f9](https://linux-hardware.org/?probe=838dcef1f9) | Aug 21, 2022 |
| ASUSTek       | K53SD                       | [1b2c4f25a7](https://linux-hardware.org/?probe=1b2c4f25a7) | Aug 21, 2022 |
| HP            | Compaq CQ58                 | [59fadaa084](https://linux-hardware.org/?probe=59fadaa084) | Aug 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Lenovo        | ThinkPad T520 4239CTO       | [c88fbf8cc5](https://linux-hardware.org/?probe=c88fbf8cc5) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bdb88a532f](https://linux-hardware.org/?probe=bdb88a532f) | Aug 19, 2022 |
| Dell          | Latitude 5500               | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f9ec8eaac3](https://linux-hardware.org/?probe=f9ec8eaac3) | Aug 18, 2022 |
| Packard Be... | EasyNote TJ65               | [df3b457c00](https://linux-hardware.org/?probe=df3b457c00) | Aug 18, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [eb159f06ab](https://linux-hardware.org/?probe=eb159f06ab) | Aug 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [36fb0e2471](https://linux-hardware.org/?probe=36fb0e2471) | Aug 17, 2022 |
| Packard Be... | EasyNote TK37               | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| ASUSTek       | X556UQ                      | [cc792932e6](https://linux-hardware.org/?probe=cc792932e6) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e9d1b72a88](https://linux-hardware.org/?probe=e9d1b72a88) | Aug 17, 2022 |
| Toshiba       | Satellite C870-1F3          | [6738afe025](https://linux-hardware.org/?probe=6738afe025) | Aug 17, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [dd79ae2b92](https://linux-hardware.org/?probe=dd79ae2b92) | Aug 17, 2022 |
| MSI           | PS63 Modern 8RD             | [ad3134e010](https://linux-hardware.org/?probe=ad3134e010) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| ASUSTek       | UX303LN                     | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [da0503d5dd](https://linux-hardware.org/?probe=da0503d5dd) | Aug 15, 2022 |
| ASUSTek       | X541UV                      | [d5b4217f4a](https://linux-hardware.org/?probe=d5b4217f4a) | Aug 15, 2022 |
| Dell          | G3 3500                     | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| UNOWHY        | Y13G010S4EI                 | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | ThinkPad W540 20BHS0F206    | [7f24672b73](https://linux-hardware.org/?probe=7f24672b73) | Aug 14, 2022 |
| Toshiba       | Satellite C55-C             | [44a8059d13](https://linux-hardware.org/?probe=44a8059d13) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| HP            | 470 G7 Notebook PC          | [adae536639](https://linux-hardware.org/?probe=adae536639) | Aug 13, 2022 |
| HP            | 470 G7 Notebook PC          | [5a319a7a29](https://linux-hardware.org/?probe=5a319a7a29) | Aug 13, 2022 |
| MSI           | GE75 Raider 10SF            | [0fafeaaa76](https://linux-hardware.org/?probe=0fafeaaa76) | Aug 13, 2022 |
| Panasonic     | CF-31XEUAXMF                | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| HP            | 15                          | [30a35c4e04](https://linux-hardware.org/?probe=30a35c4e04) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX534FAC            | [419660b78b](https://linux-hardware.org/?probe=419660b78b) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| Lenovo        | ThinkPad X200 7458VL3       | [82762528a7](https://linux-hardware.org/?probe=82762528a7) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [2c76534231](https://linux-hardware.org/?probe=2c76534231) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| Notebook      | N141CU                      | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| HP            | Laptop 17-ca1xxx            | [f57b28ff2c](https://linux-hardware.org/?probe=f57b28ff2c) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | XPS 9320                    | [f1ce1578ed](https://linux-hardware.org/?probe=f1ce1578ed) | Aug 10, 2022 |
| Dell          | Inspiron 5523               | [6a6928a8a5](https://linux-hardware.org/?probe=6a6928a8a5) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [2ac0968200](https://linux-hardware.org/?probe=2ac0968200) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| HUAWEI        | KLVC-WXX9                   | [fa0e4ba168](https://linux-hardware.org/?probe=fa0e4ba168) | Aug 09, 2022 |
| Notebook      | N230WU                      | [f00a446001](https://linux-hardware.org/?probe=f00a446001) | Aug 09, 2022 |
| Sony          | VPCYB3V1E                   | [a6cd208cf2](https://linux-hardware.org/?probe=a6cd208cf2) | Aug 09, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [66235597aa](https://linux-hardware.org/?probe=66235597aa) | Aug 09, 2022 |
| Lenovo        | ThinkPad X230 23259T0       | [04b33f4a65](https://linux-hardware.org/?probe=04b33f4a65) | Aug 08, 2022 |
| ASUSTek       | X751LD                      | [e9d631e886](https://linux-hardware.org/?probe=e9d631e886) | Aug 08, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| Dell          | Precision 5510              | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [21e646de39](https://linux-hardware.org/?probe=21e646de39) | Aug 08, 2022 |
| Intel         | JV10_CS                     | [07ca100ab3](https://linux-hardware.org/?probe=07ca100ab3) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| HP            | Compaq 15                   | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [977159d1d8](https://linux-hardware.org/?probe=977159d1d8) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [13a118ae0b](https://linux-hardware.org/?probe=13a118ae0b) | Aug 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [89b2da04d8](https://linux-hardware.org/?probe=89b2da04d8) | Aug 06, 2022 |
| Acer          | Aspire V3-372T              | [9dc2882992](https://linux-hardware.org/?probe=9dc2882992) | Aug 06, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | [1b7557ac14](https://linux-hardware.org/?probe=1b7557ac14) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [237cf11989](https://linux-hardware.org/?probe=237cf11989) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [aec2ac880f](https://linux-hardware.org/?probe=aec2ac880f) | Aug 05, 2022 |
| Notebook      | NJ50_70CU                   | [fc31dfa99e](https://linux-hardware.org/?probe=fc31dfa99e) | Aug 04, 2022 |
| ASUSTek       | X75VC                       | [f293c53dec](https://linux-hardware.org/?probe=f293c53dec) | Aug 04, 2022 |
| Dell          | Latitude E5520              | [1e3f6832b1](https://linux-hardware.org/?probe=1e3f6832b1) | Aug 04, 2022 |
| HP            | Pavilion 17                 | [cbbaa8f0db](https://linux-hardware.org/?probe=cbbaa8f0db) | Aug 03, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [0aa70716b7](https://linux-hardware.org/?probe=0aa70716b7) | Aug 03, 2022 |
| HP            | ZBook 15 G3                 | [06e06f9c67](https://linux-hardware.org/?probe=06e06f9c67) | Aug 03, 2022 |
| Dell          | Latitude E7440              | [4d132a5fd7](https://linux-hardware.org/?probe=4d132a5fd7) | Aug 03, 2022 |
| ASUSTek       | 1225B                       | [a5fb38b287](https://linux-hardware.org/?probe=a5fb38b287) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| ASUSTek       | K50IE                       | [0472e4609b](https://linux-hardware.org/?probe=0472e4609b) | Aug 03, 2022 |
| HP            | Notebook                    | [5320991330](https://linux-hardware.org/?probe=5320991330) | Aug 02, 2022 |
| Toshiba       | PORTEGE R30-A               | [89d09548e4](https://linux-hardware.org/?probe=89d09548e4) | Aug 02, 2022 |
| ASUSTek       | X751LJC                     | [e71a9f6a85](https://linux-hardware.org/?probe=e71a9f6a85) | Aug 02, 2022 |
| Acidanther... | MacBookPro13,1              | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| Dell          | XPS 13 9380                 | [d4524b40db](https://linux-hardware.org/?probe=d4524b40db) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [41b26f984c](https://linux-hardware.org/?probe=41b26f984c) | Aug 01, 2022 |
| ASUSTek       | GL553VE                     | [d67cc48957](https://linux-hardware.org/?probe=d67cc48957) | Aug 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | [7137ca1923](https://linux-hardware.org/?probe=7137ca1923) | Aug 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | [9a5e39bf87](https://linux-hardware.org/?probe=9a5e39bf87) | Aug 01, 2022 |
| Acer          | Aspire 7741                 | [4e266f6d7f](https://linux-hardware.org/?probe=4e266f6d7f) | Jul 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7ae6c1826c](https://linux-hardware.org/?probe=7ae6c1826c) | Jul 31, 2022 |
| Acer          | Aspire 7741                 | [932a460553](https://linux-hardware.org/?probe=932a460553) | Jul 31, 2022 |
| HP            | Pavilion Notebook           | [f312865dc0](https://linux-hardware.org/?probe=f312865dc0) | Jul 31, 2022 |
| ASUSTek       | E200HA                      | [86ef744d76](https://linux-hardware.org/?probe=86ef744d76) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Sony          | SVE1511Y1ESI                | [7e5ced1b91](https://linux-hardware.org/?probe=7e5ced1b91) | Jul 30, 2022 |
| HP            | Pavilion dm4                | [2bde69365c](https://linux-hardware.org/?probe=2bde69365c) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | [fca54dfc19](https://linux-hardware.org/?probe=fca54dfc19) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | [4321f0776b](https://linux-hardware.org/?probe=4321f0776b) | Jul 29, 2022 |
| Dell          | Latitude E6410              | [f2220a772e](https://linux-hardware.org/?probe=f2220a772e) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [74626c2a4d](https://linux-hardware.org/?probe=74626c2a4d) | Jul 29, 2022 |
| Dell          | Latitude 9420               | [1ee70bdfc6](https://linux-hardware.org/?probe=1ee70bdfc6) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Latitude 5480               | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| ASUSTek       | X75A                        | [646a5239a8](https://linux-hardware.org/?probe=646a5239a8) | Jul 28, 2022 |
| HP            | 245 G8 Notebook PC          | [7922ab1018](https://linux-hardware.org/?probe=7922ab1018) | Jul 28, 2022 |
| Notebook      | NL4x_NL5xLU                 | [12d6dbed8b](https://linux-hardware.org/?probe=12d6dbed8b) | Jul 28, 2022 |
| Acer          | Aspire 5755G                | [ba944df1b9](https://linux-hardware.org/?probe=ba944df1b9) | Jul 28, 2022 |
| HP            | EliteBook 820 G2            | [0735a357ee](https://linux-hardware.org/?probe=0735a357ee) | Jul 28, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [7356bc9abc](https://linux-hardware.org/?probe=7356bc9abc) | Jul 28, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [50da53281b](https://linux-hardware.org/?probe=50da53281b) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Dell          | Latitude E6430              | [f04523ef5a](https://linux-hardware.org/?probe=f04523ef5a) | Jul 27, 2022 |
| HP            | Pavilion dv5                | [5e73f42d72](https://linux-hardware.org/?probe=5e73f42d72) | Jul 27, 2022 |
| Acer          | Aspire V3-371               | [0da78400c9](https://linux-hardware.org/?probe=0da78400c9) | Jul 27, 2022 |
| Lenovo        | V145-15AST 81MT             | [ee800b1d9e](https://linux-hardware.org/?probe=ee800b1d9e) | Jul 27, 2022 |
| Notebook      | P7xxDM(-G)                  | [5ec2e8ed2b](https://linux-hardware.org/?probe=5ec2e8ed2b) | Jul 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4f4bdfefd](https://linux-hardware.org/?probe=f4f4bdfefd) | Jul 27, 2022 |
| HP            | Notebook                    | [9a4fc65b6a](https://linux-hardware.org/?probe=9a4fc65b6a) | Jul 26, 2022 |
| ASUSTek       | K50IJ                       | [0d908da71a](https://linux-hardware.org/?probe=0d908da71a) | Jul 26, 2022 |
| Dell          | Latitude E6540              | [d5f66c66fa](https://linux-hardware.org/?probe=d5f66c66fa) | Jul 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3073b497ce](https://linux-hardware.org/?probe=3073b497ce) | Jul 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a1605eaae0](https://linux-hardware.org/?probe=a1605eaae0) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASUSTek       | X751LD                      | [0c7a0b98b4](https://linux-hardware.org/?probe=0c7a0b98b4) | Jul 25, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| Notebook      | N150ZU                      | [6956315543](https://linux-hardware.org/?probe=6956315543) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| MSI           | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | GL502VMZ                    | [5fbc1992e5](https://linux-hardware.org/?probe=5fbc1992e5) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| HP            | EliteBook 2560p             | [6493da2069](https://linux-hardware.org/?probe=6493da2069) | Jul 23, 2022 |
| HP            | Compaq CQ58                 | [73199f32a4](https://linux-hardware.org/?probe=73199f32a4) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Toshiba       | Satellite Pro L500          | [5dd6e66215](https://linux-hardware.org/?probe=5dd6e66215) | Jul 22, 2022 |
| Dell          | XPS 15 9510                 | [6b6e8fd2da](https://linux-hardware.org/?probe=6b6e8fd2da) | Jul 21, 2022 |
| Dell          | Latitude 5420               | [51cf24b119](https://linux-hardware.org/?probe=51cf24b119) | Jul 21, 2022 |
| HP            | ZBook 15 G3                 | [758ce4f6b4](https://linux-hardware.org/?probe=758ce4f6b4) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [29847a6864](https://linux-hardware.org/?probe=29847a6864) | Jul 20, 2022 |
| Dell          | XPS 13 9370                 | [3222136926](https://linux-hardware.org/?probe=3222136926) | Jul 19, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| ASUSTek       | K50IJ                       | [cda673cd62](https://linux-hardware.org/?probe=cda673cd62) | Jul 19, 2022 |
| ASUSTek       | K50IJ                       | [c1d4ce2667](https://linux-hardware.org/?probe=c1d4ce2667) | Jul 19, 2022 |
| HP            | EliteBook 850 G5            | [753ec36553](https://linux-hardware.org/?probe=753ec36553) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| HP            | ProBook 6570b               | [db3db082b6](https://linux-hardware.org/?probe=db3db082b6) | Jul 18, 2022 |
| Apple         | MacBookPro9,1               | [ced057bb18](https://linux-hardware.org/?probe=ced057bb18) | Jul 17, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [f9f25bbbfe](https://linux-hardware.org/?probe=f9f25bbbfe) | Jul 17, 2022 |
| Lenovo        | ThinkPad Edge 0328A11       | [4305889043](https://linux-hardware.org/?probe=4305889043) | Jul 17, 2022 |
| Dell          | System Vostro 3450          | [8c0f346c80](https://linux-hardware.org/?probe=8c0f346c80) | Jul 17, 2022 |
| Valve         | Jupiter                     | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| ASUSTek       | N73SV                       | [db493240aa](https://linux-hardware.org/?probe=db493240aa) | Jul 17, 2022 |
| Toshiba       | PORTEGE R930                | [0e8e3b5a24](https://linux-hardware.org/?probe=0e8e3b5a24) | Jul 17, 2022 |
| Google        | Coral                       | [ebf34e57e6](https://linux-hardware.org/?probe=ebf34e57e6) | Jul 17, 2022 |
| Acer          | Nitro AN515-55              | [c9e61ec6c4](https://linux-hardware.org/?probe=c9e61ec6c4) | Jul 16, 2022 |
| HP            | Laptop 17-cp0xxx            | [17803a39aa](https://linux-hardware.org/?probe=17803a39aa) | Jul 16, 2022 |
| Acer          | Aspire A317-53              | [020dfc5580](https://linux-hardware.org/?probe=020dfc5580) | Jul 16, 2022 |
| Acer          | Aspire A317-53              | [d8838cbae7](https://linux-hardware.org/?probe=d8838cbae7) | Jul 16, 2022 |
| HP            | 350 G1                      | [a95c89dfa1](https://linux-hardware.org/?probe=a95c89dfa1) | Jul 16, 2022 |
| HP            | 350 G1                      | [9a154ddcf2](https://linux-hardware.org/?probe=9a154ddcf2) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| ASUSTek       | X751MA                      | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| Toshiba       | Satellite Pro C660          | [9196a0ceb8](https://linux-hardware.org/?probe=9196a0ceb8) | Jul 16, 2022 |
| Toshiba       | Satellite Pro C660          | [fe173bf190](https://linux-hardware.org/?probe=fe173bf190) | Jul 15, 2022 |
| HP            | Laptop 17-ca1xxx            | [68e5da78cd](https://linux-hardware.org/?probe=68e5da78cd) | Jul 15, 2022 |
| MSI           | GE72 6QL                    | [7c22c38989](https://linux-hardware.org/?probe=7c22c38989) | Jul 15, 2022 |
| Dell          | Latitude E6530              | [67eec0ba19](https://linux-hardware.org/?probe=67eec0ba19) | Jul 15, 2022 |
| Acer          | Aspire 7740                 | [243f8e0be2](https://linux-hardware.org/?probe=243f8e0be2) | Jul 14, 2022 |
| Lenovo        | V145-15AST 81MT             | [8b3e5af205](https://linux-hardware.org/?probe=8b3e5af205) | Jul 14, 2022 |
| Chuwi         | LarkBook                    | [501967d2e1](https://linux-hardware.org/?probe=501967d2e1) | Jul 14, 2022 |
| HP            | 250 G6 Notebook PC          | [00deb1f759](https://linux-hardware.org/?probe=00deb1f759) | Jul 13, 2022 |
| Lenovo        | G50-45 80E3                 | [10f3f2b135](https://linux-hardware.org/?probe=10f3f2b135) | Jul 13, 2022 |
| Notebook      | NL40_50GU                   | [d4e652dc65](https://linux-hardware.org/?probe=d4e652dc65) | Jul 13, 2022 |
| Toshiba       | Satellite Pro R50-C         | [25d6e4de23](https://linux-hardware.org/?probe=25d6e4de23) | Jul 13, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b9a6630267](https://linux-hardware.org/?probe=b9a6630267) | Jul 12, 2022 |
| HP            | ProBook 640 G1              | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Jumper        | EZbook                      | [4b0935af93](https://linux-hardware.org/?probe=4b0935af93) | Jul 11, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1599e9e013](https://linux-hardware.org/?probe=1599e9e013) | Jul 11, 2022 |
| Dell          | Latitude E5440              | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| ASUSTek       | UX310UAK                    | [2574834337](https://linux-hardware.org/?probe=2574834337) | Jul 10, 2022 |
| ASUSTek       | UX310UAK                    | [9cc9bae948](https://linux-hardware.org/?probe=9cc9bae948) | Jul 10, 2022 |
| Dell          | Latitude 5420               | [1cc724cf75](https://linux-hardware.org/?probe=1cc724cf75) | Jul 10, 2022 |
| HP            | Pavilion dv7                | [0dcf6b98e8](https://linux-hardware.org/?probe=0dcf6b98e8) | Jul 10, 2022 |
| HP            | ProBook 470 G2              | [318374978e](https://linux-hardware.org/?probe=318374978e) | Jul 10, 2022 |
| HP            | ProBook 6570b               | [4b10924d6a](https://linux-hardware.org/?probe=4b10924d6a) | Jul 10, 2022 |
| Lenovo        | V15-ADA 82C7                | [3324f369f7](https://linux-hardware.org/?probe=3324f369f7) | Jul 09, 2022 |
| Toshiba       | Satellite L655              | [d8990c4f88](https://linux-hardware.org/?probe=d8990c4f88) | Jul 09, 2022 |
| HP            | ProBook 6570b               | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Packard Be... | EasyNote TS44HR             | [2961959421](https://linux-hardware.org/?probe=2961959421) | Jul 09, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [82ddcf66ec](https://linux-hardware.org/?probe=82ddcf66ec) | Jul 08, 2022 |
| HP            | ProBook 4510s               | [ae51b4e466](https://linux-hardware.org/?probe=ae51b4e466) | Jul 08, 2022 |
| ASUSTek       | S551LN                      | [1e64e5d64e](https://linux-hardware.org/?probe=1e64e5d64e) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4f02f261b3](https://linux-hardware.org/?probe=4f02f261b3) | Jul 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| HP            | Notebook                    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| Dell          | Vostro 5625                 | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| ASUSTek       | X705UAP                     | [cf63a63e99](https://linux-hardware.org/?probe=cf63a63e99) | Jul 07, 2022 |
| ASUSTek       | GL553VD                     | [6b5e1735a7](https://linux-hardware.org/?probe=6b5e1735a7) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [e8806ee656](https://linux-hardware.org/?probe=e8806ee656) | Jul 07, 2022 |
| HP            | ProBook 455 G7              | [ddb273e392](https://linux-hardware.org/?probe=ddb273e392) | Jul 07, 2022 |
| ASUSTek       | ROG Strix G733ZS_G733ZS     | [3df6db337d](https://linux-hardware.org/?probe=3df6db337d) | Jul 06, 2022 |
| HP            | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| Acer          | Aspire E1-531               | [ead9f24980](https://linux-hardware.org/?probe=ead9f24980) | Jul 06, 2022 |
| Alienware     | x17 R2                      | [1ab946220b](https://linux-hardware.org/?probe=1ab946220b) | Jul 05, 2022 |
| Dell          | Inspiron 3558               | [09fd55b256](https://linux-hardware.org/?probe=09fd55b256) | Jul 05, 2022 |
| Acer          | Aspire F5-573G              | [c1978d81c7](https://linux-hardware.org/?probe=c1978d81c7) | Jul 05, 2022 |
| HP            | EliteBook 8570p             | [8782b09be9](https://linux-hardware.org/?probe=8782b09be9) | Jul 05, 2022 |
| ASUSTek       | FX503VD                     | [3f26062c31](https://linux-hardware.org/?probe=3f26062c31) | Jul 04, 2022 |
| ASUSTek       | FX503VD                     | [3749a75218](https://linux-hardware.org/?probe=3749a75218) | Jul 04, 2022 |
| Packard Be... | H17HV                       | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [582d281a5c](https://linux-hardware.org/?probe=582d281a5c) | Jul 04, 2022 |
| Thomson       | N17CSL512                   | [11d0b3229b](https://linux-hardware.org/?probe=11d0b3229b) | Jul 04, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | [842be4aea2](https://linux-hardware.org/?probe=842be4aea2) | Jul 04, 2022 |
| Acer          | Predator PT516-52s          | [3992d41a65](https://linux-hardware.org/?probe=3992d41a65) | Jul 04, 2022 |
| HP            | 470 G7 Notebook PC          | [49d49283d6](https://linux-hardware.org/?probe=49d49283d6) | Jul 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Thomson       | N17V3C8WH512                | [118835a499](https://linux-hardware.org/?probe=118835a499) | Jul 03, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [172847b24c](https://linux-hardware.org/?probe=172847b24c) | Jul 03, 2022 |
| Dell          | Venue 10 Pro 5056           | [7676cdf093](https://linux-hardware.org/?probe=7676cdf093) | Jul 02, 2022 |
| Dell          | Inspiron 5415               | [d906735fe5](https://linux-hardware.org/?probe=d906735fe5) | Jul 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7cdf221ced](https://linux-hardware.org/?probe=7cdf221ced) | Jul 01, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| Framework     | Laptop                      | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Dell          | G5 5500                     | [edfdebf28d](https://linux-hardware.org/?probe=edfdebf28d) | Jun 30, 2022 |
| Thomson       | N17V3C8WH512                | [518a227ae9](https://linux-hardware.org/?probe=518a227ae9) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [03854f8307](https://linux-hardware.org/?probe=03854f8307) | Jun 29, 2022 |
| Notebook      | P7xxDM3(-G)                 | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| HP            | EliteBook 840 G2            | [79a978476b](https://linux-hardware.org/?probe=79a978476b) | Jun 28, 2022 |
| Dell          | Latitude 5420               | [58838b9e58](https://linux-hardware.org/?probe=58838b9e58) | Jun 28, 2022 |
| Acer          | Aspire E5-722               | [eda8e07df0](https://linux-hardware.org/?probe=eda8e07df0) | Jun 28, 2022 |
| Acer          | Aspire E5-722               | [7270206115](https://linux-hardware.org/?probe=7270206115) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| MSI           | VR630                       | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [3fd9c5042f](https://linux-hardware.org/?probe=3fd9c5042f) | Jun 27, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [bde3725b5d](https://linux-hardware.org/?probe=bde3725b5d) | Jun 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [409ca4eba4](https://linux-hardware.org/?probe=409ca4eba4) | Jun 27, 2022 |
| Dell          | Latitude 5510               | [06199cdfe6](https://linux-hardware.org/?probe=06199cdfe6) | Jun 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [aa51c70192](https://linux-hardware.org/?probe=aa51c70192) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [78d7beacec](https://linux-hardware.org/?probe=78d7beacec) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c4351d9d15](https://linux-hardware.org/?probe=c4351d9d15) | Jun 27, 2022 |
| Intel Clie... | LAPKC71F                    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| Toshiba       | Satellite C855-2CF          | [9e062a8425](https://linux-hardware.org/?probe=9e062a8425) | Jun 26, 2022 |
| Acer          | Aspire A114-31              | [8fd4467dfd](https://linux-hardware.org/?probe=8fd4467dfd) | Jun 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [4cee5507af](https://linux-hardware.org/?probe=4cee5507af) | Jun 25, 2022 |
| Dell          | Latitude D630               | [9b1cf4028b](https://linux-hardware.org/?probe=9b1cf4028b) | Jun 25, 2022 |
| Dell          | Latitude D630               | [b3eef0f278](https://linux-hardware.org/?probe=b3eef0f278) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6b59bd5d](https://linux-hardware.org/?probe=8a6b59bd5d) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9d53805c9a](https://linux-hardware.org/?probe=9d53805c9a) | Jun 25, 2022 |
| HP            | Pavilion dv7                | [a0c6c78c33](https://linux-hardware.org/?probe=a0c6c78c33) | Jun 25, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ce17a478c3](https://linux-hardware.org/?probe=ce17a478c3) | Jun 24, 2022 |
| HP            | Pavilion dv7                | [334a6079e5](https://linux-hardware.org/?probe=334a6079e5) | Jun 24, 2022 |
| Fujitsu       | LIFEBOOK U7411              | [2bbef77636](https://linux-hardware.org/?probe=2bbef77636) | Jun 23, 2022 |
| Sony          | SVS1312J3EW                 | [95e0cb21c4](https://linux-hardware.org/?probe=95e0cb21c4) | Jun 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [69e0965863](https://linux-hardware.org/?probe=69e0965863) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [13d9478b12](https://linux-hardware.org/?probe=13d9478b12) | Jun 22, 2022 |
| Dell          | XPS 13 9360                 | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Dell          | Precision 7560              | [760bb908b9](https://linux-hardware.org/?probe=760bb908b9) | Jun 22, 2022 |
| Toshiba       | Satellite Pro L500          | [e745bcf24b](https://linux-hardware.org/?probe=e745bcf24b) | Jun 22, 2022 |
| Dell          | G15 5510                    | [cfd6e8f4d6](https://linux-hardware.org/?probe=cfd6e8f4d6) | Jun 21, 2022 |
| Dell          | Latitude E7270              | [5b1c572f56](https://linux-hardware.org/?probe=5b1c572f56) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [926b001aa9](https://linux-hardware.org/?probe=926b001aa9) | Jun 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ff5ed1835c](https://linux-hardware.org/?probe=ff5ed1835c) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [87abe6b88c](https://linux-hardware.org/?probe=87abe6b88c) | Jun 20, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Notebook      | NL40_50CU                   | [b0b1068b47](https://linux-hardware.org/?probe=b0b1068b47) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [e6bb96869e](https://linux-hardware.org/?probe=e6bb96869e) | Jun 19, 2022 |
| Toshiba       | Satellite Click 10 LX5W-... | [b8f87c8ede](https://linux-hardware.org/?probe=b8f87c8ede) | Jun 19, 2022 |
| MSI           | GE75 Raider 10SF            | [eee0889229](https://linux-hardware.org/?probe=eee0889229) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Packard Be... | H17HV                       | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| Dell          | Latitude 5420               | [14f75e40fd](https://linux-hardware.org/?probe=14f75e40fd) | Jun 18, 2022 |
| Dell          | Latitude E6540              | [e023336620](https://linux-hardware.org/?probe=e023336620) | Jun 18, 2022 |
| MSI           | Creator Z16 A11UET          | [0a6d214b2e](https://linux-hardware.org/?probe=0a6d214b2e) | Jun 18, 2022 |
| Packard Be... | EasyNote TS44HR             | [bc731a2920](https://linux-hardware.org/?probe=bc731a2920) | Jun 18, 2022 |
| ASUSTek       | N71Vg                       | [6926193d76](https://linux-hardware.org/?probe=6926193d76) | Jun 18, 2022 |
| Dell          | G3 3500                     | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| Dell          | Inspiron 7590               | [2e4fc22b64](https://linux-hardware.org/?probe=2e4fc22b64) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| Lenovo        | ThinkPad T460s 20FAS76R0... | [21d6816b13](https://linux-hardware.org/?probe=21d6816b13) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| ASUSTek       | X411UA                      | [da7deca26c](https://linux-hardware.org/?probe=da7deca26c) | Jun 16, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cc3a77a798](https://linux-hardware.org/?probe=cc3a77a798) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d2ec826b81](https://linux-hardware.org/?probe=d2ec826b81) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e889572d35](https://linux-hardware.org/?probe=e889572d35) | Jun 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [5a762627ab](https://linux-hardware.org/?probe=5a762627ab) | Jun 16, 2022 |
| Dell          | Vostro 3525                 | [97e8f44feb](https://linux-hardware.org/?probe=97e8f44feb) | Jun 15, 2022 |
| Lenovo        | ThinkPad E490 20N8002APB    | [3a17ac0192](https://linux-hardware.org/?probe=3a17ac0192) | Jun 15, 2022 |
| HP            | ProBook 430 G6              | [c7b3318ac4](https://linux-hardware.org/?probe=c7b3318ac4) | Jun 14, 2022 |
| Acer          | Aspire E5-722               | [3085e9b7ad](https://linux-hardware.org/?probe=3085e9b7ad) | Jun 14, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [2570d889fd](https://linux-hardware.org/?probe=2570d889fd) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | ENVY m6                     | [f8a6325caa](https://linux-hardware.org/?probe=f8a6325caa) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| ASUSTek       | UX303LN                     | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | [c29e79e22d](https://linux-hardware.org/?probe=c29e79e22d) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | [02e4c63249](https://linux-hardware.org/?probe=02e4c63249) | Jun 12, 2022 |
| Acer          | Aspire ES1-523              | [89fbabafb5](https://linux-hardware.org/?probe=89fbabafb5) | Jun 12, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| HP            | Laptop 17-bs0xx             | [a4587cc1de](https://linux-hardware.org/?probe=a4587cc1de) | Jun 10, 2022 |
| HUAWEI        | HN-WX9X                     | [d57d295c58](https://linux-hardware.org/?probe=d57d295c58) | Jun 10, 2022 |
| Dell          | Latitude 5290               | [930e34a606](https://linux-hardware.org/?probe=930e34a606) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [e33e73a70f](https://linux-hardware.org/?probe=e33e73a70f) | Jun 10, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [e20ce4899d](https://linux-hardware.org/?probe=e20ce4899d) | Jun 09, 2022 |
| Dell          | Latitude 7389               | [88dad6a75c](https://linux-hardware.org/?probe=88dad6a75c) | Jun 09, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Acer          | Aspire V5-531               | [3a462d28a4](https://linux-hardware.org/?probe=3a462d28a4) | Jun 08, 2022 |
| Lenovo        | G50-30 80G0                 | [0de0854560](https://linux-hardware.org/?probe=0de0854560) | Jun 08, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6d9c3da618](https://linux-hardware.org/?probe=6d9c3da618) | Jun 08, 2022 |
| HP            | ProBook 640 G1              | [34ecb184f9](https://linux-hardware.org/?probe=34ecb184f9) | Jun 08, 2022 |
| Fujitsu       | CELSIUS H730                | [734b6c125f](https://linux-hardware.org/?probe=734b6c125f) | Jun 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [7e3c31382f](https://linux-hardware.org/?probe=7e3c31382f) | Jun 08, 2022 |
| Acer          | Aspire E5-722               | [a096ce91cf](https://linux-hardware.org/?probe=a096ce91cf) | Jun 08, 2022 |
| Acer          | Aspire E5-722               | [10fbd3326b](https://linux-hardware.org/?probe=10fbd3326b) | Jun 08, 2022 |
| HP            | EliteBook 8740w             | [a835c8f6c8](https://linux-hardware.org/?probe=a835c8f6c8) | Jun 07, 2022 |
| Lenovo        | ThinkPad T495 20NJ0007US    | [2b3ee11cad](https://linux-hardware.org/?probe=2b3ee11cad) | Jun 07, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Toshiba       | Satellite C850D-115         | [35f95dcc1c](https://linux-hardware.org/?probe=35f95dcc1c) | Jun 06, 2022 |
| Dell          | Latitude E5530 non-vPro     | [e4ba25767a](https://linux-hardware.org/?probe=e4ba25767a) | Jun 06, 2022 |
| Notebook      | NS50MU                      | [d54906a6c5](https://linux-hardware.org/?probe=d54906a6c5) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [9400ad4984](https://linux-hardware.org/?probe=9400ad4984) | Jun 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [3281dce7d5](https://linux-hardware.org/?probe=3281dce7d5) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e7e658bc95](https://linux-hardware.org/?probe=e7e658bc95) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e51b9086bd](https://linux-hardware.org/?probe=e51b9086bd) | Jun 06, 2022 |
| Notebook      | NS50MU                      | [bf6d177bf1](https://linux-hardware.org/?probe=bf6d177bf1) | Jun 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [91abfe378e](https://linux-hardware.org/?probe=91abfe378e) | Jun 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [228fe8f3f1](https://linux-hardware.org/?probe=228fe8f3f1) | Jun 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [f1bad1050e](https://linux-hardware.org/?probe=f1bad1050e) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| Dell          | G3 3500                     | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| AZW           | GT-R                        | [d86ab00f24](https://linux-hardware.org/?probe=d86ab00f24) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [721f0da2de](https://linux-hardware.org/?probe=721f0da2de) | Jun 05, 2022 |
| HP            | Pavilion 17                 | [b2a29d34f0](https://linux-hardware.org/?probe=b2a29d34f0) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| HP            | Pavilion dv6                | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Valve         | Jupiter                     | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| HP            | ProBook 6550b               | [005fa13ca2](https://linux-hardware.org/?probe=005fa13ca2) | Jun 04, 2022 |
| Lenovo        | ThinkPad X230 23259T0       | [d0bb09f4ee](https://linux-hardware.org/?probe=d0bb09f4ee) | Jun 04, 2022 |
| Lenovo        | ThinkPad E470 20H2S01A00    | [b98fdbbd2b](https://linux-hardware.org/?probe=b98fdbbd2b) | Jun 04, 2022 |
| Packard Be... | EasyNote LS11HR             | [78cae55082](https://linux-hardware.org/?probe=78cae55082) | Jun 04, 2022 |
| Lenovo        | Z51-70 80K6                 | [b29848facc](https://linux-hardware.org/?probe=b29848facc) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [befecc30e3](https://linux-hardware.org/?probe=befecc30e3) | Jun 03, 2022 |
| Dell          | XPS 13 9360                 | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| ASUSTek       | 1001PX                      | [097a218d03](https://linux-hardware.org/?probe=097a218d03) | Jun 03, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b47b9118af](https://linux-hardware.org/?probe=b47b9118af) | Jun 02, 2022 |
| Lenovo        | ThinkPad X230 23259T0       | [54fffce502](https://linux-hardware.org/?probe=54fffce502) | Jun 02, 2022 |
| HP            | Pavilion 17                 | [426dba3868](https://linux-hardware.org/?probe=426dba3868) | Jun 01, 2022 |
| Toshiba       | Satellite C660              | [927caeb015](https://linux-hardware.org/?probe=927caeb015) | Jun 01, 2022 |
| Dell          | Precision 3530              | [0371c8be1b](https://linux-hardware.org/?probe=0371c8be1b) | Jun 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P3540FA_... | [46c75dbe1d](https://linux-hardware.org/?probe=46c75dbe1d) | Jun 01, 2022 |
| Dell          | XPS 13 9310                 | [726e3b4cd7](https://linux-hardware.org/?probe=726e3b4cd7) | May 31, 2022 |
| HP            | EliteBook 2570p             | [dabb678748](https://linux-hardware.org/?probe=dabb678748) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Toshiba       | Satellite C850D-115         | [fca373e327](https://linux-hardware.org/?probe=fca373e327) | May 31, 2022 |
| Packard Be... | EasyNote TE11HC             | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| Dell          | Latitude 5400               | [0440362644](https://linux-hardware.org/?probe=0440362644) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Timi          | TM1604                      | [cd9b839800](https://linux-hardware.org/?probe=cd9b839800) | May 29, 2022 |
| Dell          | Latitude E6420              | [e109444519](https://linux-hardware.org/?probe=e109444519) | May 29, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [b9eae1074f](https://linux-hardware.org/?probe=b9eae1074f) | May 29, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d7800ffe07](https://linux-hardware.org/?probe=d7800ffe07) | May 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | [0d556408f3](https://linux-hardware.org/?probe=0d556408f3) | May 29, 2022 |
| Valve         | Jupiter                     | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [a0e5cf5b03](https://linux-hardware.org/?probe=a0e5cf5b03) | May 29, 2022 |
| Dell          | XPS 15 9500                 | [ec336b7bfb](https://linux-hardware.org/?probe=ec336b7bfb) | May 28, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [9f3d329e42](https://linux-hardware.org/?probe=9f3d329e42) | May 28, 2022 |
| HP            | EliteBook 840 G2            | [eeab3d23c4](https://linux-hardware.org/?probe=eeab3d23c4) | May 27, 2022 |
| Dell          | Vostro 15-3568              | [ee23f2618c](https://linux-hardware.org/?probe=ee23f2618c) | May 27, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [8234e83675](https://linux-hardware.org/?probe=8234e83675) | May 27, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [de0614be43](https://linux-hardware.org/?probe=de0614be43) | May 26, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [30eed68f77](https://linux-hardware.org/?probe=30eed68f77) | May 26, 2022 |
| ASUSTek       | X205TA                      | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [aa6a60a379](https://linux-hardware.org/?probe=aa6a60a379) | May 25, 2022 |
| HP            | ZBook 15 G2                 | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| Acer          | Aspire E5-571               | [b43bf0505e](https://linux-hardware.org/?probe=b43bf0505e) | May 25, 2022 |
| Lenovo        | ThinkPad L540 20AUS39X00    | [6a294d74f4](https://linux-hardware.org/?probe=6a294d74f4) | May 25, 2022 |
| Clevo         | W55xEU                      | [c5fd2417f4](https://linux-hardware.org/?probe=c5fd2417f4) | May 25, 2022 |
| Dell          | Inspiron 7501               | [81f3b14e0a](https://linux-hardware.org/?probe=81f3b14e0a) | May 25, 2022 |
| ASUSTek       | X540LA                      | [2015df99d9](https://linux-hardware.org/?probe=2015df99d9) | May 25, 2022 |
| ASUSTek       | X540LJ                      | [dbbcdcd2b5](https://linux-hardware.org/?probe=dbbcdcd2b5) | May 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [0a468b99d2](https://linux-hardware.org/?probe=0a468b99d2) | May 25, 2022 |
| HP            | EliteBook 2560p             | [00b2e6d758](https://linux-hardware.org/?probe=00b2e6d758) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8b214b9114](https://linux-hardware.org/?probe=8b214b9114) | May 24, 2022 |
| Dell          | XPS 13 9305                 | [c06270a534](https://linux-hardware.org/?probe=c06270a534) | May 24, 2022 |
| Apple         | MacBookAir3,2               | [d53c4aa502](https://linux-hardware.org/?probe=d53c4aa502) | May 24, 2022 |
| ASUSTek       | 1001PXD                     | [8c3e0451e1](https://linux-hardware.org/?probe=8c3e0451e1) | May 24, 2022 |
| Dell          | Precision 3561              | [71657d24c1](https://linux-hardware.org/?probe=71657d24c1) | May 24, 2022 |
| Dell          | Precision 3561              | [385a286d0d](https://linux-hardware.org/?probe=385a286d0d) | May 24, 2022 |
| Dell          | XPS 13 9360                 | [41f966f459](https://linux-hardware.org/?probe=41f966f459) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [a59234d081](https://linux-hardware.org/?probe=a59234d081) | May 24, 2022 |
| Acer          | Aspire 5736Z                | [78318327dd](https://linux-hardware.org/?probe=78318327dd) | May 23, 2022 |
| Acer          | Aspire 5736Z                | [621183d005](https://linux-hardware.org/?probe=621183d005) | May 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [64a3f31676](https://linux-hardware.org/?probe=64a3f31676) | May 23, 2022 |
| Timi          | TM1612                      | [50c4a534fb](https://linux-hardware.org/?probe=50c4a534fb) | May 23, 2022 |
| Timi          | TM1612                      | [8eb7ad8654](https://linux-hardware.org/?probe=8eb7ad8654) | May 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [0a9f7ecc76](https://linux-hardware.org/?probe=0a9f7ecc76) | May 23, 2022 |
| ASUSTek       | X705UAP                     | [bd15f53ec3](https://linux-hardware.org/?probe=bd15f53ec3) | May 22, 2022 |
| ASUSTek       | X510UA                      | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| MSI           | Modern 14 A10M              | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| Toshiba       | Satellite L655              | [3ea531093a](https://linux-hardware.org/?probe=3ea531093a) | May 21, 2022 |
| ASUSTek       | F7L                         | [f5bcd583ac](https://linux-hardware.org/?probe=f5bcd583ac) | May 21, 2022 |
| ASUSTek       | K73SD                       | [8c77e10639](https://linux-hardware.org/?probe=8c77e10639) | May 21, 2022 |
| HP            | Notebook                    | [a1be02b2d6](https://linux-hardware.org/?probe=a1be02b2d6) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Acer          | Aspire 7750G                | [0fd6c8569c](https://linux-hardware.org/?probe=0fd6c8569c) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [e876753143](https://linux-hardware.org/?probe=e876753143) | May 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2972e28673](https://linux-hardware.org/?probe=2972e28673) | May 19, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [df0ca9457c](https://linux-hardware.org/?probe=df0ca9457c) | May 18, 2022 |
| Unknown       | Unknown                     | [f3395963a9](https://linux-hardware.org/?probe=f3395963a9) | May 18, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | [6ce320a4ac](https://linux-hardware.org/?probe=6ce320a4ac) | May 18, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | [63e24c7f2d](https://linux-hardware.org/?probe=63e24c7f2d) | May 18, 2022 |
| ASUSTek       | UX305FA                     | [5ec0821cdf](https://linux-hardware.org/?probe=5ec0821cdf) | May 18, 2022 |
| ASUSTek       | X556URK                     | [b217fd2c65](https://linux-hardware.org/?probe=b217fd2c65) | May 18, 2022 |
| Dell          | Latitude D610               | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [331099a3da](https://linux-hardware.org/?probe=331099a3da) | May 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1ccddf153e](https://linux-hardware.org/?probe=1ccddf153e) | May 17, 2022 |
| Dell          | XPS 13 7390                 | [395da9a242](https://linux-hardware.org/?probe=395da9a242) | May 17, 2022 |
| Dell          | XPS 13 7390                 | [b2543f26eb](https://linux-hardware.org/?probe=b2543f26eb) | May 17, 2022 |
| Toshiba       | Satellite L655              | [7709c37037](https://linux-hardware.org/?probe=7709c37037) | May 17, 2022 |
| Toshiba       | Satellite L655              | [1d12d6b59a](https://linux-hardware.org/?probe=1d12d6b59a) | May 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1454db93a0](https://linux-hardware.org/?probe=1454db93a0) | May 16, 2022 |
| Lenovo        | ThinkPad T420 4236JV8       | [93ea3c3211](https://linux-hardware.org/?probe=93ea3c3211) | May 16, 2022 |
| Dell          | Latitude E6400              | [d89696196c](https://linux-hardware.org/?probe=d89696196c) | May 16, 2022 |
| HP            | EliteBook 2560p             | [04c60d52d9](https://linux-hardware.org/?probe=04c60d52d9) | May 16, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [4961cf3603](https://linux-hardware.org/?probe=4961cf3603) | May 16, 2022 |
| Lenovo        | ThinkPad T400 276521G       | [9a2f5118c5](https://linux-hardware.org/?probe=9a2f5118c5) | May 15, 2022 |
| Lenovo        | ThinkPad L540 20AUA27UFR    | [4a6dd68139](https://linux-hardware.org/?probe=4a6dd68139) | May 15, 2022 |
| Acer          | Aspire A317-32              | [8a8e910ffc](https://linux-hardware.org/?probe=8a8e910ffc) | May 15, 2022 |
| Acer          | Swift SF314-54              | [1624fff74b](https://linux-hardware.org/?probe=1624fff74b) | May 15, 2022 |
| Thomson       | NEO14SBK                    | [2ae5fbd212](https://linux-hardware.org/?probe=2ae5fbd212) | May 15, 2022 |
| ASUSTek       | GL552VW                     | [ef37144b46](https://linux-hardware.org/?probe=ef37144b46) | May 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [bf7abc840c](https://linux-hardware.org/?probe=bf7abc840c) | May 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [107ca55bd4](https://linux-hardware.org/?probe=107ca55bd4) | May 14, 2022 |
| Fujitsu       | LIFEBOOK E746               | [dd9eac2f81](https://linux-hardware.org/?probe=dd9eac2f81) | May 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [d8cfc5384f](https://linux-hardware.org/?probe=d8cfc5384f) | May 13, 2022 |
| Lenovo        | ThinkPad L520 5017W5C       | [7e841df590](https://linux-hardware.org/?probe=7e841df590) | May 13, 2022 |
| Dell          | G3 3779                     | [c1da54a43b](https://linux-hardware.org/?probe=c1da54a43b) | May 13, 2022 |
| Apple         | MacBookPro5,2               | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Dell          | Inspiron 16 5620            | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| HUAWEI        | WRTB-WXX9                   | [7f2b79a6fa](https://linux-hardware.org/?probe=7f2b79a6fa) | May 12, 2022 |
| Lenovo        | Yoga 2 13 20344             | [bdd61986c1](https://linux-hardware.org/?probe=bdd61986c1) | May 12, 2022 |
| HP            | ProBook 4330s               | [52494be83b](https://linux-hardware.org/?probe=52494be83b) | May 12, 2022 |
| Fujitsu       | LIFEBOOK E746               | [8551aac5e5](https://linux-hardware.org/?probe=8551aac5e5) | May 12, 2022 |
| Dell          | Latitude E5570              | [ec640c6644](https://linux-hardware.org/?probe=ec640c6644) | May 12, 2022 |
| Lenovo        | ThinkPad E595 20NFS05500    | [8656f72354](https://linux-hardware.org/?probe=8656f72354) | May 11, 2022 |
| ASUSTek       | A7K                         | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [2591f59c80](https://linux-hardware.org/?probe=2591f59c80) | May 11, 2022 |
| MSI           | GT60 2OC/2OD                | [aa055927a2](https://linux-hardware.org/?probe=aa055927a2) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| Dell          | Latitude 5290               | [f83f9858f3](https://linux-hardware.org/?probe=f83f9858f3) | May 10, 2022 |
| MSI           | Modern 15 A11M              | [8fe60eb961](https://linux-hardware.org/?probe=8fe60eb961) | May 10, 2022 |
| Toshiba       | Satellite C55-A-1N0         | [c64d31da4e](https://linux-hardware.org/?probe=c64d31da4e) | May 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [e6d579fd5b](https://linux-hardware.org/?probe=e6d579fd5b) | May 10, 2022 |
| Dell          | XPS 13 9310                 | [cae0934838](https://linux-hardware.org/?probe=cae0934838) | May 10, 2022 |
| Lenovo        | Flex 2-14 20404             | [92ea1dc23f](https://linux-hardware.org/?probe=92ea1dc23f) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | Pavilion Notebook           | [637a04a2d1](https://linux-hardware.org/?probe=637a04a2d1) | May 09, 2022 |
| ASUSTek       | K95VJ                       | [5e07819ad6](https://linux-hardware.org/?probe=5e07819ad6) | May 09, 2022 |
| Dell          | Inspiron 5482               | [fb9b420ea8](https://linux-hardware.org/?probe=fb9b420ea8) | May 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [877b9a8dea](https://linux-hardware.org/?probe=877b9a8dea) | May 08, 2022 |
| Apple         | MacBookAir6,2               | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| Chuwi         | GemiBook Pro                | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Acer          | Aspire 5253G                | [6f6b26ee56](https://linux-hardware.org/?probe=6f6b26ee56) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [8fa9fd80a0](https://linux-hardware.org/?probe=8fa9fd80a0) | May 07, 2022 |
| MSI           | Katana GF76 12UEK           | [10e7f811ff](https://linux-hardware.org/?probe=10e7f811ff) | May 07, 2022 |
| Timi          | TM1604                      | [bc97206a3a](https://linux-hardware.org/?probe=bc97206a3a) | May 07, 2022 |
| Dell          | Latitude 3540               | [e4dd2ae509](https://linux-hardware.org/?probe=e4dd2ae509) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Dell          | Inspiron 15 5510            | [c927d230e7](https://linux-hardware.org/?probe=c927d230e7) | May 06, 2022 |
| Acer          | Aspire A317-32              | [ae2c984a96](https://linux-hardware.org/?probe=ae2c984a96) | May 06, 2022 |
| Acer          | Nitro AN515-45              | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| Packard Be... | EasyNote TSX66HR            | [becf9e42b8](https://linux-hardware.org/?probe=becf9e42b8) | May 05, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| ASUSTek       | K55VD                       | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Dell          | Inspiron 14 5410            | [8cf21cf03f](https://linux-hardware.org/?probe=8cf21cf03f) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Teclast       | F7 Plus                     | [6aedd4e799](https://linux-hardware.org/?probe=6aedd4e799) | May 05, 2022 |
| HP            | ProBook 450 G5              | [cfa52783d2](https://linux-hardware.org/?probe=cfa52783d2) | May 05, 2022 |
| Acer          | Aspire 7740                 | [b7f708e626](https://linux-hardware.org/?probe=b7f708e626) | May 05, 2022 |
| HUAWEI        | WRTB-WXX9                   | [9af4db58d6](https://linux-hardware.org/?probe=9af4db58d6) | May 05, 2022 |
| ASUSTek       | GL552VX                     | [d153ef27fa](https://linux-hardware.org/?probe=d153ef27fa) | May 04, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [eeb6685345](https://linux-hardware.org/?probe=eeb6685345) | May 04, 2022 |
| Dell          | Inspiron 5502               | [ccc57cd99e](https://linux-hardware.org/?probe=ccc57cd99e) | May 04, 2022 |
| HP            | ProBook 470 G0              | [17a1e97761](https://linux-hardware.org/?probe=17a1e97761) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Lenovo        | G50-70 20351                | [95a85a5620](https://linux-hardware.org/?probe=95a85a5620) | May 03, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [840bfcee31](https://linux-hardware.org/?probe=840bfcee31) | May 03, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [79491af642](https://linux-hardware.org/?probe=79491af642) | May 03, 2022 |
| Valve         | Jupiter                     | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Notebook      | NL40_50CU                   | [6cbd46444f](https://linux-hardware.org/?probe=6cbd46444f) | May 02, 2022 |
| Dell          | Latitude E6440              | [d2ab063048](https://linux-hardware.org/?probe=d2ab063048) | May 02, 2022 |
| ASUSTek       | E403SA                      | [c59815fc46](https://linux-hardware.org/?probe=c59815fc46) | May 02, 2022 |
| ASUSTek       | E403SA                      | [1036fd29cb](https://linux-hardware.org/?probe=1036fd29cb) | May 02, 2022 |
| Sony          | VPCS13V9E                   | [0b565d3fac](https://linux-hardware.org/?probe=0b565d3fac) | May 02, 2022 |
| Dell          | Precision 7530              | [ef011e846b](https://linux-hardware.org/?probe=ef011e846b) | May 02, 2022 |
| Dell          | Precision 3520              | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| HP            | ZBook 15 G5                 | [334e009f9c](https://linux-hardware.org/?probe=334e009f9c) | May 02, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f937431614](https://linux-hardware.org/?probe=f937431614) | May 01, 2022 |
| Dell          | Inspiron 7577               | [e039fa0209](https://linux-hardware.org/?probe=e039fa0209) | May 01, 2022 |
| HP            | Laptop 14-dk0xxx            | [c59146fbec](https://linux-hardware.org/?probe=c59146fbec) | May 01, 2022 |
| HP            | EliteBook 8570p             | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Dell          | Inspiron 7577               | [132a55cc40](https://linux-hardware.org/?probe=132a55cc40) | Apr 30, 2022 |
| Dell          | Precision M6500             | [a3d82a4f1a](https://linux-hardware.org/?probe=a3d82a4f1a) | Apr 30, 2022 |
| Dell          | Precision M6500             | [cb7e68eb50](https://linux-hardware.org/?probe=cb7e68eb50) | Apr 30, 2022 |
| Dell          | G5 5590                     | [4738729947](https://linux-hardware.org/?probe=4738729947) | Apr 30, 2022 |
| Acer          | Aspire ES1-512              | [642d72d06d](https://linux-hardware.org/?probe=642d72d06d) | Apr 30, 2022 |
| HP            | Pavilion dv7                | [f66df9ca5b](https://linux-hardware.org/?probe=f66df9ca5b) | Apr 30, 2022 |
| HP            | Pavilion dv7                | [150931746e](https://linux-hardware.org/?probe=150931746e) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Dell          | Latitude 5480               | [ba1ff8183e](https://linux-hardware.org/?probe=ba1ff8183e) | Apr 30, 2022 |
| HP            | ZBook 15 G5                 | [aac5097e2a](https://linux-hardware.org/?probe=aac5097e2a) | Apr 29, 2022 |
| ASUSTek       | S551LN                      | [a5f0e1cee7](https://linux-hardware.org/?probe=a5f0e1cee7) | Apr 29, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4af637024a](https://linux-hardware.org/?probe=4af637024a) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| Apple         | MacBookPro8,2               | [50c8a02c35](https://linux-hardware.org/?probe=50c8a02c35) | Apr 29, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [ac2800ef82](https://linux-hardware.org/?probe=ac2800ef82) | Apr 28, 2022 |
| HP            | Pavilion 17                 | [d865ef2ed1](https://linux-hardware.org/?probe=d865ef2ed1) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [e8349bba13](https://linux-hardware.org/?probe=e8349bba13) | Apr 28, 2022 |
| Dell          | Latitude 5310               | [b4e7215e3b](https://linux-hardware.org/?probe=b4e7215e3b) | Apr 28, 2022 |
| Acer          | Nitro AN515-57              | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| HP            | EliteBook 840 G2            | [8c0c59e517](https://linux-hardware.org/?probe=8c0c59e517) | Apr 27, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1a773927c4](https://linux-hardware.org/?probe=1a773927c4) | Apr 27, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3314e78ec8](https://linux-hardware.org/?probe=3314e78ec8) | Apr 27, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6e793edd01](https://linux-hardware.org/?probe=6e793edd01) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Acer          | Aspire A515-55              | [fa33f58948](https://linux-hardware.org/?probe=fa33f58948) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | X705UA                      | [8c12b4587e](https://linux-hardware.org/?probe=8c12b4587e) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [37a92322aa](https://linux-hardware.org/?probe=37a92322aa) | Apr 25, 2022 |
| MSI           | GF65 Thin 10UE              | [b099b2ab43](https://linux-hardware.org/?probe=b099b2ab43) | Apr 25, 2022 |
| MSI           | GF65 Thin 10UE              | [79fc46c6f0](https://linux-hardware.org/?probe=79fc46c6f0) | Apr 25, 2022 |
| Toshiba       | Satellite C50t-B            | [d2a6276ca3](https://linux-hardware.org/?probe=d2a6276ca3) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a33d02fb0e](https://linux-hardware.org/?probe=a33d02fb0e) | Apr 25, 2022 |
| Lenovo        | G50-30 80G0                 | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| Dell          | Latitude E7270              | [d8dedbd4f6](https://linux-hardware.org/?probe=d8dedbd4f6) | Apr 25, 2022 |
| Dell          | Precision 3561              | [251f19b464](https://linux-hardware.org/?probe=251f19b464) | Apr 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [5b54f10afa](https://linux-hardware.org/?probe=5b54f10afa) | Apr 24, 2022 |
| ASUSTek       | S551LN                      | [779fe5a429](https://linux-hardware.org/?probe=779fe5a429) | Apr 24, 2022 |
| Alienware     | 17 R2                       | [93cc7785c3](https://linux-hardware.org/?probe=93cc7785c3) | Apr 24, 2022 |
| ASUSTek       | X540LA                      | [370a60692a](https://linux-hardware.org/?probe=370a60692a) | Apr 24, 2022 |
| ASUSTek       | X550CC                      | [4f77777c97](https://linux-hardware.org/?probe=4f77777c97) | Apr 24, 2022 |
| Dell          | G3 3500                     | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| HP            | EliteBook 850 G6            | [438ad440d0](https://linux-hardware.org/?probe=438ad440d0) | Apr 24, 2022 |
| Dell          | Latitude E4300              | [0bc4953a89](https://linux-hardware.org/?probe=0bc4953a89) | Apr 23, 2022 |
| Dell          | Precision 3551              | [e1921eba79](https://linux-hardware.org/?probe=e1921eba79) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [ce0b6939ac](https://linux-hardware.org/?probe=ce0b6939ac) | Apr 22, 2022 |
| Timi          | RedmiBook 14-APCS           | [32cb202a0e](https://linux-hardware.org/?probe=32cb202a0e) | Apr 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2c17462cda](https://linux-hardware.org/?probe=2c17462cda) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| Dell          | Inspiron 15 5510            | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| MSI           | Pulse GL76 11UEK            | [beff2fb2f8](https://linux-hardware.org/?probe=beff2fb2f8) | Apr 22, 2022 |
| Dell          | XPS 15 7590                 | [5266d4c66b](https://linux-hardware.org/?probe=5266d4c66b) | Apr 21, 2022 |
| Dell          | XPS 15 7590                 | [70d107a754](https://linux-hardware.org/?probe=70d107a754) | Apr 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| Dell          | Latitude 5400               | [b9d83d936e](https://linux-hardware.org/?probe=b9d83d936e) | Apr 21, 2022 |
| Sony          | SVE1713V1EB                 | [84441dd32d](https://linux-hardware.org/?probe=84441dd32d) | Apr 21, 2022 |
| Dell          | Precision 3561              | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| ASUSTek       | X540LJ                      | [33a74b2070](https://linux-hardware.org/?probe=33a74b2070) | Apr 20, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [b9f3f2d21f](https://linux-hardware.org/?probe=b9f3f2d21f) | Apr 20, 2022 |
| HP            | G72                         | [255c100d4f](https://linux-hardware.org/?probe=255c100d4f) | Apr 20, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ee565a2f35](https://linux-hardware.org/?probe=ee565a2f35) | Apr 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4047b55bcf](https://linux-hardware.org/?probe=4047b55bcf) | Apr 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [b5e3c59f45](https://linux-hardware.org/?probe=b5e3c59f45) | Apr 18, 2022 |
| Toshiba       | Satellite Pro C660          | [6af3fd0dea](https://linux-hardware.org/?probe=6af3fd0dea) | Apr 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [9629510a6c](https://linux-hardware.org/?probe=9629510a6c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [885a3f046f](https://linux-hardware.org/?probe=885a3f046f) | Apr 18, 2022 |
| Acer          | Aspire 7730ZG               | [4129ff8d3a](https://linux-hardware.org/?probe=4129ff8d3a) | Apr 18, 2022 |
| MSI           | Modern 14 B10MW             | [b5d0d5b10b](https://linux-hardware.org/?probe=b5d0d5b10b) | Apr 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c5e6eae8d7](https://linux-hardware.org/?probe=c5e6eae8d7) | Apr 16, 2022 |
| ASUSTek       | G752VY                      | [a497ac3b95](https://linux-hardware.org/?probe=a497ac3b95) | Apr 16, 2022 |
| HP            | 250 G7 Notebook PC          | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | EliteBook 820 G2            | [65c9ced61d](https://linux-hardware.org/?probe=65c9ced61d) | Apr 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | [53eb30d6a6](https://linux-hardware.org/?probe=53eb30d6a6) | Apr 16, 2022 |
| HP            | Pavilion dv7                | [60eee202a1](https://linux-hardware.org/?probe=60eee202a1) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK E746               | [ae8fe4a156](https://linux-hardware.org/?probe=ae8fe4a156) | Apr 16, 2022 |
| Google        | Squawks                     | [a6dc68bba1](https://linux-hardware.org/?probe=a6dc68bba1) | Apr 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [e9a5e187ad](https://linux-hardware.org/?probe=e9a5e187ad) | Apr 15, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [c14702d147](https://linux-hardware.org/?probe=c14702d147) | Apr 15, 2022 |
| Sony          | VGN-NS38E_S                 | [1b8177c97a](https://linux-hardware.org/?probe=1b8177c97a) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | [0f845854f8](https://linux-hardware.org/?probe=0f845854f8) | Apr 14, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [799b4d2e08](https://linux-hardware.org/?probe=799b4d2e08) | Apr 14, 2022 |
| Dell          | Inspiron MP061              | [2e9f19b2e7](https://linux-hardware.org/?probe=2e9f19b2e7) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8b693a6221](https://linux-hardware.org/?probe=8b693a6221) | Apr 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [4d46d1ce45](https://linux-hardware.org/?probe=4d46d1ce45) | Apr 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f3d294f808](https://linux-hardware.org/?probe=f3d294f808) | Apr 14, 2022 |
| Lenovo        | ThinkPad W510 4391DK3       | [d73ef83ae7](https://linux-hardware.org/?probe=d73ef83ae7) | Apr 14, 2022 |
| HP            | Pavilion dv6500             | [31d34f3d2d](https://linux-hardware.org/?probe=31d34f3d2d) | Apr 13, 2022 |
| HP            | OMEN by Laptop              | [3775d7e528](https://linux-hardware.org/?probe=3775d7e528) | Apr 13, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [eff12a28fd](https://linux-hardware.org/?probe=eff12a28fd) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [2edcc0aefa](https://linux-hardware.org/?probe=2edcc0aefa) | Apr 13, 2022 |
| Dell          | Latitude 5310               | [5b0e8b3b6a](https://linux-hardware.org/?probe=5b0e8b3b6a) | Apr 13, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [280c9288d4](https://linux-hardware.org/?probe=280c9288d4) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [c6e4cb5abf](https://linux-hardware.org/?probe=c6e4cb5abf) | Apr 13, 2022 |
| MSI           | PS42 Modern 8RA             | [ed7332a282](https://linux-hardware.org/?probe=ed7332a282) | Apr 13, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [0357e04d4f](https://linux-hardware.org/?probe=0357e04d4f) | Apr 13, 2022 |
| Acer          | Aspire A114-32              | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Dell          | Vostro 3700                 | [32c9c08613](https://linux-hardware.org/?probe=32c9c08613) | Apr 11, 2022 |
| Acer          | Aspire E5-721               | [abdc523e93](https://linux-hardware.org/?probe=abdc523e93) | Apr 11, 2022 |
| Fujitsu       | LIFEBOOK E746               | [9380c2aaf9](https://linux-hardware.org/?probe=9380c2aaf9) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | G7 7790                     | [6cdb296d8e](https://linux-hardware.org/?probe=6cdb296d8e) | Apr 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6QV00    | [315f7326a1](https://linux-hardware.org/?probe=315f7326a1) | Apr 10, 2022 |
| HP            | OMEN by Laptop              | [f83f7f076a](https://linux-hardware.org/?probe=f83f7f076a) | Apr 10, 2022 |
| Dell          | Precision 7560              | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| HP            | Notebook                    | [85a43844c8](https://linux-hardware.org/?probe=85a43844c8) | Apr 09, 2022 |
| HP            | Pavilion dv7                | [031ac42e46](https://linux-hardware.org/?probe=031ac42e46) | Apr 09, 2022 |
| eMachines     | eM350                       | [13c805d75b](https://linux-hardware.org/?probe=13c805d75b) | Apr 09, 2022 |
| System76      | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [225f8e5c86](https://linux-hardware.org/?probe=225f8e5c86) | Apr 09, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [e76eb71b7f](https://linux-hardware.org/?probe=e76eb71b7f) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3AG0... | [b995f1fe33](https://linux-hardware.org/?probe=b995f1fe33) | Apr 09, 2022 |
| MSI           | GS70 6QE                    | [8e387655c0](https://linux-hardware.org/?probe=8e387655c0) | Apr 08, 2022 |
| Dell          | Inspiron N7010              | [c0ce083329](https://linux-hardware.org/?probe=c0ce083329) | Apr 08, 2022 |
| HP            | ENVY 17                     | [dc478e704e](https://linux-hardware.org/?probe=dc478e704e) | Apr 08, 2022 |
| HP            | ENVY 17                     | [41b4c812c5](https://linux-hardware.org/?probe=41b4c812c5) | Apr 08, 2022 |
| System76      | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| ASUSTek       | X556UQ                      | [ee38be8ddd](https://linux-hardware.org/?probe=ee38be8ddd) | Apr 07, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [8ab4c1618d](https://linux-hardware.org/?probe=8ab4c1618d) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0PF0... | [e73d2ba91e](https://linux-hardware.org/?probe=e73d2ba91e) | Apr 07, 2022 |
| Lenovo        | ThinkPad L440 20ASS34K00    | [357d9151c6](https://linux-hardware.org/?probe=357d9151c6) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | [a497a79602](https://linux-hardware.org/?probe=a497a79602) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | [f5d617af1b](https://linux-hardware.org/?probe=f5d617af1b) | Apr 07, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [c4ed41947f](https://linux-hardware.org/?probe=c4ed41947f) | Apr 07, 2022 |
| Dell          | Studio 1747                 | [e1e79d7825](https://linux-hardware.org/?probe=e1e79d7825) | Apr 07, 2022 |
| Dell          | Studio 1747                 | [4c452dc4f5](https://linux-hardware.org/?probe=4c452dc4f5) | Apr 06, 2022 |
| Packard Be... | EasyNote MH45               | [5e33894ebd](https://linux-hardware.org/?probe=5e33894ebd) | Apr 06, 2022 |
| Dell          | G5 5590                     | [86d53d1c79](https://linux-hardware.org/?probe=86d53d1c79) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [dbb3f589ad](https://linux-hardware.org/?probe=dbb3f589ad) | Apr 06, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Star Labs     | Lite                        | [7a49876efc](https://linux-hardware.org/?probe=7a49876efc) | Apr 05, 2022 |
| Valve         | Jupiter                     | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9b7950cd38](https://linux-hardware.org/?probe=9b7950cd38) | Apr 05, 2022 |
| Dell          | XPS 13 9370                 | [a2dd193a18](https://linux-hardware.org/?probe=a2dd193a18) | Apr 05, 2022 |
| Dell          | Precision 7730              | [df577a297b](https://linux-hardware.org/?probe=df577a297b) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| Lenovo        | G50-45 80E3                 | [5eac45729d](https://linux-hardware.org/?probe=5eac45729d) | Apr 04, 2022 |
| Unknown       | Unknown                     | [9ec92432e1](https://linux-hardware.org/?probe=9ec92432e1) | Apr 04, 2022 |
| HP            | 250 G7 Notebook PC          | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| PC Special... | Standard                    | [4584680506](https://linux-hardware.org/?probe=4584680506) | Apr 04, 2022 |
| Dell          | Latitude D820               | [d07a035b7b](https://linux-hardware.org/?probe=d07a035b7b) | Apr 04, 2022 |
| Sony          | VGN-FZ31M                   | [5e1ef6c19a](https://linux-hardware.org/?probe=5e1ef6c19a) | Apr 03, 2022 |
| Dell          | Inspiron N5110              | [cd682e107d](https://linux-hardware.org/?probe=cd682e107d) | Apr 03, 2022 |
| Dell          | Latitude 7490               | [2e43979827](https://linux-hardware.org/?probe=2e43979827) | Apr 03, 2022 |
| eMachines     | eM350                       | [0c2afeefb3](https://linux-hardware.org/?probe=0c2afeefb3) | Apr 03, 2022 |
| Dell          | Precision 5530              | [96b22b6124](https://linux-hardware.org/?probe=96b22b6124) | Apr 03, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [597f814e58](https://linux-hardware.org/?probe=597f814e58) | Apr 03, 2022 |
| Dell          | Latitude E6420              | [41c4a5b886](https://linux-hardware.org/?probe=41c4a5b886) | Apr 02, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [3c89c6c9d8](https://linux-hardware.org/?probe=3c89c6c9d8) | Apr 02, 2022 |
| Dell          | Inspiron 14 5401            | [d357bf876a](https://linux-hardware.org/?probe=d357bf876a) | Apr 02, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [b022cbc8be](https://linux-hardware.org/?probe=b022cbc8be) | Apr 02, 2022 |
| Lenovo        | ThinkPad X240 20AMS00J00    | [f8d2abf5f9](https://linux-hardware.org/?probe=f8d2abf5f9) | Apr 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [712ca55ca9](https://linux-hardware.org/?probe=712ca55ca9) | Apr 01, 2022 |
| Dell          | Inspiron 14 5401            | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [24fe7f7148](https://linux-hardware.org/?probe=24fe7f7148) | Apr 01, 2022 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [97505bf353](https://linux-hardware.org/?probe=97505bf353) | Apr 01, 2022 |
| Samsung       | 305U1A                      | [f69394d574](https://linux-hardware.org/?probe=f69394d574) | Apr 01, 2022 |
| HUAWEI        | HVY-WXX9                    | [6eb9c66f7d](https://linux-hardware.org/?probe=6eb9c66f7d) | Mar 31, 2022 |
| Dell          | XPS 13 9310                 | [cbdf6cd38b](https://linux-hardware.org/?probe=cbdf6cd38b) | Mar 31, 2022 |
| Dell          | XPS 13 9310                 | [54ebfbd580](https://linux-hardware.org/?probe=54ebfbd580) | Mar 31, 2022 |
| Sony          | VGN-NS38E_S                 | [e55061b0ab](https://linux-hardware.org/?probe=e55061b0ab) | Mar 31, 2022 |
| Sony          | VGN-NS38E_S                 | [a6fad3260a](https://linux-hardware.org/?probe=a6fad3260a) | Mar 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [0cfca0c3f1](https://linux-hardware.org/?probe=0cfca0c3f1) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| HP            | Pavilion g7                 | [a162ae9ffa](https://linux-hardware.org/?probe=a162ae9ffa) | Mar 30, 2022 |
| Dell          | Latitude 5520               | [19ae38fc11](https://linux-hardware.org/?probe=19ae38fc11) | Mar 30, 2022 |
| Lenovo        | ThinkPad X230 23259S9       | [a461555ba9](https://linux-hardware.org/?probe=a461555ba9) | Mar 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7abb97f630](https://linux-hardware.org/?probe=7abb97f630) | Mar 30, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c6e30abf8c](https://linux-hardware.org/?probe=c6e30abf8c) | Mar 29, 2022 |
| MSI           | GP62 7QF                    | [c15ac1cd59](https://linux-hardware.org/?probe=c15ac1cd59) | Mar 29, 2022 |
| HUAWEI        | BOHB-WAX9                   | [f398041b40](https://linux-hardware.org/?probe=f398041b40) | Mar 29, 2022 |
| Dell          | Inspiron N5110              | [ce630f6abb](https://linux-hardware.org/?probe=ce630f6abb) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| HP            | Pavilion dv6                | [560cb55002](https://linux-hardware.org/?probe=560cb55002) | Mar 29, 2022 |
| Acer          | Aspire 1640                 | [93f44fda5e](https://linux-hardware.org/?probe=93f44fda5e) | Mar 28, 2022 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [60aa56878d](https://linux-hardware.org/?probe=60aa56878d) | Mar 28, 2022 |
| Thomson       | NEO14-2.32BS                | [7d8d2dd456](https://linux-hardware.org/?probe=7d8d2dd456) | Mar 28, 2022 |
| Samsung       | R530/R730/R540              | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| SHENZHEN Y... | A8S PRO                     | [b4a38330e4](https://linux-hardware.org/?probe=b4a38330e4) | Mar 27, 2022 |
| HP            | EliteBook 850 G6            | [084d60ff3b](https://linux-hardware.org/?probe=084d60ff3b) | Mar 27, 2022 |
| HP            | Compaq 615                  | [906354c0ce](https://linux-hardware.org/?probe=906354c0ce) | Mar 27, 2022 |
| Lenovo        | ThinkPad T495 20NKS13Q00    | [95d0d1e82a](https://linux-hardware.org/?probe=95d0d1e82a) | Mar 27, 2022 |
| HP            | EliteBook 2560p             | [124d170dc9](https://linux-hardware.org/?probe=124d170dc9) | Mar 27, 2022 |
| MSI           | GP62 7QF                    | [f05a7cf0e8](https://linux-hardware.org/?probe=f05a7cf0e8) | Mar 26, 2022 |
| MSI           | GE72 2QF                    | [3966a755c3](https://linux-hardware.org/?probe=3966a755c3) | Mar 26, 2022 |
| Packard Be... | ENLE11BZ                    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [8c3ffc28b7](https://linux-hardware.org/?probe=8c3ffc28b7) | Mar 26, 2022 |
| SHENZHEN Y... | A8S PRO                     | [90d0fd195b](https://linux-hardware.org/?probe=90d0fd195b) | Mar 26, 2022 |
| ASUSTek       | N76VJ                       | [53ec863214](https://linux-hardware.org/?probe=53ec863214) | Mar 26, 2022 |
| HUAWEI        | HVY-WXX9                    | [cc9e9e5839](https://linux-hardware.org/?probe=cc9e9e5839) | Mar 25, 2022 |
| HP            | Compaq 615                  | [28368f4366](https://linux-hardware.org/?probe=28368f4366) | Mar 25, 2022 |
| ASUSTek       | K70IJ                       | [90b9aed933](https://linux-hardware.org/?probe=90b9aed933) | Mar 25, 2022 |
| Dell          | Latitude E5440              | [1aa586207c](https://linux-hardware.org/?probe=1aa586207c) | Mar 25, 2022 |
| Dell          | XPS 15 9570                 | [43c9e3966a](https://linux-hardware.org/?probe=43c9e3966a) | Mar 25, 2022 |
| Lenovo        | G500 20236                  | [bb5a60710e](https://linux-hardware.org/?probe=bb5a60710e) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| HUAWEI        | HVY-WXX9                    | [aa7427e650](https://linux-hardware.org/?probe=aa7427e650) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| MSI           | GE72VR 6RF                  | [b957669e37](https://linux-hardware.org/?probe=b957669e37) | Mar 23, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [c923ffc942](https://linux-hardware.org/?probe=c923ffc942) | Mar 23, 2022 |
| MSI           | GL63 8RC                    | [21ffd75625](https://linux-hardware.org/?probe=21ffd75625) | Mar 23, 2022 |
| Teclast       | F15Plus 2                   | [0aa346d34a](https://linux-hardware.org/?probe=0aa346d34a) | Mar 23, 2022 |
| HP            | ProBook 430 G3              | [71a1efb495](https://linux-hardware.org/?probe=71a1efb495) | Mar 23, 2022 |
| HP            | ProBook 430 G1              | [e62a0f9e56](https://linux-hardware.org/?probe=e62a0f9e56) | Mar 23, 2022 |
| HP            | Pavilion dv5                | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| Acer          | Aspire 5830TG               | [681005049f](https://linux-hardware.org/?probe=681005049f) | Mar 22, 2022 |
| ASUSTek       | G752VY                      | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| ASUSTek       | G75VW                       | [202d109eb5](https://linux-hardware.org/?probe=202d109eb5) | Mar 22, 2022 |
| Thomson       | N17C8SR1T                   | [cbdfe9edf6](https://linux-hardware.org/?probe=cbdfe9edf6) | Mar 22, 2022 |
| Thomson       | N17C8SR1T                   | [1e426be12c](https://linux-hardware.org/?probe=1e426be12c) | Mar 22, 2022 |
| Acer          | Aspire 5100                 | [87b141a6ce](https://linux-hardware.org/?probe=87b141a6ce) | Mar 22, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [c6af42491f](https://linux-hardware.org/?probe=c6af42491f) | Mar 22, 2022 |
| Dell          | XPS 15 9570                 | [d4b19324b2](https://linux-hardware.org/?probe=d4b19324b2) | Mar 22, 2022 |
| Dell          | Latitude E6400              | [49b4e17d7a](https://linux-hardware.org/?probe=49b4e17d7a) | Mar 22, 2022 |
| MSI           | GE72VR 6RF                  | [73be3ca633](https://linux-hardware.org/?probe=73be3ca633) | Mar 22, 2022 |
| MSI           | GP76 Leopard 11UH           | [d398e3284e](https://linux-hardware.org/?probe=d398e3284e) | Mar 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4c23faece4](https://linux-hardware.org/?probe=4c23faece4) | Mar 21, 2022 |
| Dell          | Latitude 5510               | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| Dell          | Latitude E6420              | [dd8dd6e0fa](https://linux-hardware.org/?probe=dd8dd6e0fa) | Mar 21, 2022 |
| ASUSTek       | X705UA                      | [5b05567a86](https://linux-hardware.org/?probe=5b05567a86) | Mar 21, 2022 |
| HP            | ProBook 450 G5              | [8ff982fca7](https://linux-hardware.org/?probe=8ff982fca7) | Mar 21, 2022 |
| Thomson       | N14C4WH64                   | [9b3b9c113d](https://linux-hardware.org/?probe=9b3b9c113d) | Mar 20, 2022 |
| Acer          | Aspire A515-41G             | [50fe287748](https://linux-hardware.org/?probe=50fe287748) | Mar 20, 2022 |
| HP            | ENVY dv7                    | [b15a265c66](https://linux-hardware.org/?probe=b15a265c66) | Mar 20, 2022 |
| Lenovo        | ThinkPad T520 4243M75       | [d7a393fd7b](https://linux-hardware.org/?probe=d7a393fd7b) | Mar 20, 2022 |
| Chuwi         | GemiBook                    | [f7e06f0d6a](https://linux-hardware.org/?probe=f7e06f0d6a) | Mar 20, 2022 |
| Acer          | Acadia V1.21                | [e6541adef3](https://linux-hardware.org/?probe=e6541adef3) | Mar 20, 2022 |
| ASUSTek       | K73SV                       | [515f3d895e](https://linux-hardware.org/?probe=515f3d895e) | Mar 19, 2022 |
| ASUSTek       | K73SV                       | [34bd1f29eb](https://linux-hardware.org/?probe=34bd1f29eb) | Mar 19, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [8e148f567b](https://linux-hardware.org/?probe=8e148f567b) | Mar 19, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [52558a7cc2](https://linux-hardware.org/?probe=52558a7cc2) | Mar 19, 2022 |
| ASUSTek       | X705UAR                     | [c84459b828](https://linux-hardware.org/?probe=c84459b828) | Mar 19, 2022 |
| Timi          | TM1701                      | [5127044e2a](https://linux-hardware.org/?probe=5127044e2a) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | [3c40b29b63](https://linux-hardware.org/?probe=3c40b29b63) | Mar 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [35e488d04a](https://linux-hardware.org/?probe=35e488d04a) | Mar 19, 2022 |
| Acer          | Aspire A717-71G             | [0c30cab21d](https://linux-hardware.org/?probe=0c30cab21d) | Mar 18, 2022 |
| Notebook      | NL4x_NL5xLU                 | [3a2af88613](https://linux-hardware.org/?probe=3a2af88613) | Mar 18, 2022 |
| Samsung       | R530/R730/R540              | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [a736b9986e](https://linux-hardware.org/?probe=a736b9986e) | Mar 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 905       | 22.17%  |
| Ubuntu 18.04      | 298       | 7.3%    |
| OpenMandriva 4.2  | 166       | 4.07%   |
| Debian 11         | 120       | 2.94%   |
| Ubuntu 22.04      | 107       | 2.62%   |
| OpenMandriva 4.3  | 105       | 2.57%   |
| Xubuntu 20.04     | 103       | 2.52%   |
| Linux Mint 20.3   | 97        | 2.38%   |
| Arch              | 81        | 1.98%   |
| Ubuntu 21.10      | 70        | 1.71%   |
| Debian 10         | 68        | 1.67%   |
| Linux Mint 20.2   | 61        | 1.49%   |
| Ubuntu 19.10      | 59        | 1.45%   |
| Ubuntu 21.04      | 56        | 1.37%   |
| Ubuntu 20.10      | 53        | 1.3%    |
| Xubuntu 18.04     | 48        | 1.18%   |
| Linux Mint 19.3   | 48        | 1.18%   |
| Fedora 33         | 48        | 1.18%   |
| Arch Rolling      | 48        | 1.18%   |
| Manjaro           | 45        | 1.1%    |
| Fedora 34         | 43        | 1.05%   |
| Linux Mint 20.1   | 41        | 1%      |
| Kubuntu 20.04     | 41        | 1%      |
| Fedora 32         | 40        | 0.98%   |
| Ubuntu 19.04      | 39        | 0.96%   |
| Pop!_OS 20.04     | 36        | 0.88%   |
| Linux Mint 20     | 36        | 0.88%   |
| KDE neon 20.04    | 36        | 0.88%   |
| Fedora 35         | 34        | 0.83%   |
| Zorin 16          | 32        | 0.78%   |
| Lubuntu 20.04     | 32        | 0.78%   |
| Ubuntu MATE 20.04 | 31        | 0.76%   |
| Pop!_OS 20.10     | 29        | 0.71%   |
| Pop!_OS 21.04     | 28        | 0.69%   |
| Fedora 31         | 27        | 0.66%   |
| Fedora 36         | 25        | 0.61%   |
| Debian Testing    | 25        | 0.61%   |
| Zorin 15          | 24        | 0.59%   |
| ROSA R11          | 24        | 0.59%   |
| ArcoLinux Rolling | 23        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1545      | 39.75%  |
| Linux Mint    | 313       | 8.05%   |
| OpenMandriva  | 297       | 7.64%   |
| Debian        | 239       | 6.15%   |
| Fedora        | 196       | 5.04%   |
| Xubuntu       | 178       | 4.58%   |
| Arch          | 127       | 3.27%   |
| Pop!_OS       | 122       | 3.14%   |
| Manjaro       | 114       | 2.93%   |
| Kubuntu       | 87        | 2.24%   |
| ROSA          | 71        | 1.83%   |
| Zorin         | 57        | 1.47%   |
| Ubuntu MATE   | 51        | 1.31%   |
| Lubuntu       | 49        | 1.26%   |
| KDE neon      | 41        | 1.05%   |
| Endless       | 39        | 1%      |
| openSUSE      | 35        | 0.9%    |
| Kali          | 30        | 0.77%   |
| Gentoo        | 27        | 0.69%   |
| ArcoLinux     | 24        | 0.62%   |
| Elementary    | 22        | 0.57%   |
| Ubuntu Unity  | 20        | 0.51%   |
| Ubuntu Budgie | 19        | 0.49%   |
| BlackPanther  | 18        | 0.46%   |
| EndeavourOS   | 15        | 0.39%   |
| Parrot        | 12        | 0.31%   |
| LMDE          | 12        | 0.31%   |
| Ubuntu Studio | 9         | 0.23%   |
| Kaisen        | 9         | 0.23%   |
| CentOS        | 8         | 0.21%   |
| Clear Linux   | 7         | 0.18%   |
| SteamOS       | 6         | 0.15%   |
| MX            | 6         | 0.15%   |
| RHEL          | 5         | 0.13%   |
| Peppermint    | 5         | 0.13%   |
| NixOS         | 5         | 0.13%   |
| Linux Lite    | 5         | 0.13%   |
| Mageia        | 4         | 0.1%    |
| LinuxFX       | 4         | 0.1%    |
| Xero          | 3         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 156       | 3.5%    |
| 5.16.7-desktop-1omv4003  | 102       | 2.29%   |
| 5.4.0-42-generic         | 73        | 1.64%   |
| 5.11.0-38-generic        | 48        | 1.08%   |
| 5.4.0-58-generic         | 44        | 0.99%   |
| 5.4.0-52-generic         | 43        | 0.97%   |
| 5.11.0-27-generic        | 41        | 0.92%   |
| 5.4.0-26-generic         | 39        | 0.88%   |
| 5.4.0-48-generic         | 36        | 0.81%   |
| 5.8.0-50-generic         | 35        | 0.79%   |
| 5.15.0-46-generic        | 35        | 0.79%   |
| 5.11.0-37-generic        | 35        | 0.79%   |
| 5.8.0-43-generic         | 33        | 0.74%   |
| 5.4.0-65-generic         | 33        | 0.74%   |
| 5.8.0-44-generic         | 32        | 0.72%   |
| 5.4.0-91-generic         | 32        | 0.72%   |
| 5.11.0-43-generic        | 32        | 0.72%   |
| 5.4.0-37-generic         | 31        | 0.7%    |
| 5.11.0-40-generic        | 31        | 0.7%    |
| 5.13.0-40-generic        | 30        | 0.67%   |
| 5.13.0-30-generic        | 30        | 0.67%   |
| 5.11.0-34-generic        | 29        | 0.65%   |
| 5.8.0-59-generic         | 28        | 0.63%   |
| 5.8.0-48-generic         | 28        | 0.63%   |
| 5.4.0-54-generic         | 27        | 0.61%   |
| 5.13.0-28-generic        | 27        | 0.61%   |
| 5.4.0-31-generic         | 26        | 0.58%   |
| 5.15.0-47-generic        | 26        | 0.58%   |
| 5.15.0-41-generic        | 25        | 0.56%   |
| 5.13.0-39-generic        | 25        | 0.56%   |
| 5.8.0-55-generic         | 24        | 0.54%   |
| 5.8.0-41-generic         | 24        | 0.54%   |
| 5.4.0-81-generic         | 24        | 0.54%   |
| 5.4.0-47-generic         | 24        | 0.54%   |
| 5.3.0-40-generic         | 24        | 0.54%   |
| 5.10.0-8-amd64           | 24        | 0.54%   |
| 5.8.0-53-generic         | 23        | 0.52%   |
| 5.4.0-56-generic         | 23        | 0.52%   |
| 5.4.0-29-generic         | 23        | 0.52%   |
| 5.4.0-122-generic        | 23        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 899       | 21.46%  |
| 5.8.0   | 348       | 8.31%   |
| 5.11.0  | 348       | 8.31%   |
| 5.13.0  | 292       | 6.97%   |
| 4.15.0  | 213       | 5.08%   |
| 5.15.0  | 200       | 4.77%   |
| 5.3.0   | 176       | 4.2%    |
| 5.10.14 | 157       | 3.75%   |
| 5.10.0  | 154       | 3.68%   |
| 5.16.7  | 102       | 2.43%   |
| 5.0.0   | 99        | 2.36%   |
| 4.18.0  | 66        | 1.58%   |
| 4.19.0  | 63        | 1.5%    |
| 5.14.0  | 26        | 0.62%   |
| 5.17.5  | 19        | 0.45%   |
| 5.16.0  | 19        | 0.45%   |
| 5.11.12 | 19        | 0.45%   |
| 4.18.16 | 17        | 0.41%   |
| 4.9.20  | 15        | 0.36%   |
| 5.9.0   | 14        | 0.33%   |
| 5.6.0   | 14        | 0.33%   |
| 5.9.11  | 13        | 0.31%   |
| 5.19.0  | 13        | 0.31%   |
| 5.18.12 | 13        | 0.31%   |
| 4.4.0   | 12        | 0.29%   |
| 5.14.9  | 11        | 0.26%   |
| 4.9.0   | 11        | 0.26%   |
| 5.9.16  | 10        | 0.24%   |
| 5.7.0   | 10        | 0.24%   |
| 5.18.0  | 10        | 0.24%   |
| 5.17.1  | 10        | 0.24%   |
| 5.12.4  | 10        | 0.24%   |
| 5.8.18  | 9         | 0.21%   |
| 5.9.14  | 8         | 0.19%   |
| 5.15.10 | 8         | 0.19%   |
| 5.14.14 | 8         | 0.19%   |
| 5.13.12 | 8         | 0.19%   |
| 5.9.1   | 7         | 0.17%   |
| 5.18.16 | 7         | 0.17%   |
| 5.17.0  | 7         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 946       | 22.87%  |
| 5.11    | 399       | 9.65%   |
| 5.8     | 389       | 9.41%   |
| 5.10    | 388       | 9.38%   |
| 5.13    | 329       | 7.95%   |
| 5.15    | 291       | 7.04%   |
| 4.15    | 213       | 5.15%   |
| 5.3     | 200       | 4.84%   |
| 5.16    | 163       | 3.94%   |
| 5.0     | 103       | 2.49%   |
| 4.18    | 85        | 2.06%   |
| 5.14    | 81        | 1.96%   |
| 5.9     | 71        | 1.72%   |
| 4.19    | 69        | 1.67%   |
| 5.18    | 57        | 1.38%   |
| 5.17    | 53        | 1.28%   |
| 5.6     | 50        | 1.21%   |
| 4.9     | 46        | 1.11%   |
| 5.7     | 42        | 1.02%   |
| 5.12    | 38        | 0.92%   |
| 5.19    | 36        | 0.87%   |
| 5.5     | 23        | 0.56%   |
| 4.4     | 14        | 0.34%   |
| 4.1     | 11        | 0.27%   |
| 4.14    | 8         | 0.19%   |
| 5.2     | 7         | 0.17%   |
| 4.13    | 5         | 0.12%   |
| 4.12    | 5         | 0.12%   |
| 4.10    | 4         | 0.1%    |
| 5.1     | 2         | 0.05%   |
| 4.20    | 2         | 0.05%   |
| 3.10    | 2         | 0.05%   |
| 6.0     | 1         | 0.02%   |
| 4.8     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3680      | 97.02%  |
| i686    | 110       | 2.9%    |
| aarch64 | 2         | 0.05%   |
| Unknown | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1866      | 47.44%  |
| KDE5              | 575       | 14.62%  |
| Unknown           | 382       | 9.71%   |
| XFCE              | 371       | 9.43%   |
| X-Cinnamon        | 194       | 4.93%   |
| MATE              | 143       | 3.64%   |
| Cinnamon          | 69        | 1.75%   |
| KDE               | 61        | 1.55%   |
| LXQt              | 51        | 1.3%    |
| KDE4              | 50        | 1.27%   |
| i3                | 45        | 1.14%   |
| Budgie            | 24        | 0.61%   |
| Pantheon          | 22        | 0.56%   |
| Unity             | 21        | 0.53%   |
| LXDE              | 17        | 0.43%   |
| GNOME Flashback   | 12        | 0.31%   |
| Deepin            | 7         | 0.18%   |
| i3-with-shmlog    | 3         | 0.08%   |
| GNOME Classic     | 3         | 0.08%   |
| Trinity           | 2         | 0.05%   |
| sway              | 2         | 0.05%   |
| bspwm             | 2         | 0.05%   |
| awesome           | 2         | 0.05%   |
| Yaru:ubuntu:GNOME | 1         | 0.03%   |
| xmonad            | 1         | 0.03%   |
| wmaker-common     | 1         | 0.03%   |
| qtile             | 1         | 0.03%   |
| openbox           | 1         | 0.03%   |
| lightdm-xsession  | 1         | 0.03%   |
| ICEWM             | 1         | 0.03%   |
| Enlightenment     | 1         | 0.03%   |
| dwm-sc            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3150      | 80.85%  |
| Wayland | 490       | 12.58%  |
| Unknown | 199       | 5.11%   |
| Tty     | 57        | 1.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1650      | 42%     |
| GDM     | 788       | 20.06%  |
| SDDM    | 587       | 14.94%  |
| LightDM | 375       | 9.54%   |
| GDM3    | 285       | 7.25%   |
| TDM     | 182       | 4.63%   |
| KDM     | 48        | 1.22%   |
| XDM     | 8         | 0.2%    |
| SLiM    | 3         | 0.08%   |
| NODM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| Ly      | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| fr_FR      | 2610      | 67.62%  |
| en_US      | 662       | 17.15%  |
| Unknown    | 388       | 10.05%  |
| en_GB      | 61        | 1.58%   |
| C          | 35        | 0.91%   |
| ru_RU      | 10        | 0.26%   |
| it_IT      | 10        | 0.26%   |
| pl_PL      | 9         | 0.23%   |
| es_ES      | 8         | 0.21%   |
| de_DE      | 8         | 0.21%   |
| fr_CH      | 7         | 0.18%   |
| nl_NL      | 5         | 0.13%   |
| POSIX      | 4         | 0.1%    |
| fr_CA      | 4         | 0.1%    |
| fr_BE      | 4         | 0.1%    |
| pt_PT      | 3         | 0.08%   |
| pt_BR      | 3         | 0.08%   |
| hu_HU      | 2         | 0.05%   |
| en_IN      | 2         | 0.05%   |
| en_IE      | 2         | 0.05%   |
| en_CA      | 2         | 0.05%   |
| en_AU      | 2         | 0.05%   |
| cs_CZ      | 2         | 0.05%   |
| sv_SE      | 1         | 0.03%   |
| sk_SK      | 1         | 0.03%   |
| ru_UA      | 1         | 0.03%   |
| ro_RO      | 1         | 0.03%   |
| nb_NO      | 1         | 0.03%   |
| fr_LU      | 1         | 0.03%   |
| fr_FR.UTF8 | 1         | 0.03%   |
| es_VE      | 1         | 0.03%   |
| es_UY      | 1         | 0.03%   |
| es_AR      | 1         | 0.03%   |
| en_ZA      | 1         | 0.03%   |
| en_FR      | 1         | 0.03%   |
| de_CH      | 1         | 0.03%   |
| de_BE      | 1         | 0.03%   |
| de_AT      | 1         | 0.03%   |
| da_DK      | 1         | 0.03%   |
| C.UTF8     | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2163      | 55.98%  |
| BIOS | 1701      | 44.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3167      | 82.22%  |
| Overlay  | 289       | 7.5%    |
| Btrfs    | 219       | 5.69%   |
| Unknown  | 109       | 2.83%   |
| Xfs      | 27        | 0.7%    |
| Zfs      | 18        | 0.47%   |
| Ext2     | 8         | 0.21%   |
| F2fs     | 7         | 0.18%   |
| Ext3     | 6         | 0.16%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1813      | 47.05%  |
| GPT     | 1537      | 39.89%  |
| MBR     | 503       | 13.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3314      | 86.06%  |
| Yes       | 537       | 13.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2669      | 69.49%  |
| Yes       | 1172      | 30.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 678       | 17.88%  |
| Hewlett-Packard     | 637       | 16.8%   |
| ASUSTek Computer    | 628       | 16.56%  |
| Lenovo              | 621       | 16.38%  |
| Acer                | 277       | 7.3%    |
| MSI                 | 142       | 3.74%   |
| Toshiba             | 128       | 3.38%   |
| Apple               | 86        | 2.27%   |
| Notebook            | 73        | 1.93%   |
| Samsung Electronics | 58        | 1.53%   |
| HUAWEI              | 55        | 1.45%   |
| Packard Bell        | 51        | 1.34%   |
| Sony                | 48        | 1.27%   |
| TUXEDO              | 22        | 0.58%   |
| Clevo               | 20        | 0.53%   |
| Timi                | 18        | 0.47%   |
| eMachines           | 17        | 0.45%   |
| Unknown             | 17        | 0.45%   |
| Gigabyte Technology | 14        | 0.37%   |
| Fujitsu Siemens     | 14        | 0.37%   |
| Thomson             | 13        | 0.34%   |
| Fujitsu             | 13        | 0.34%   |
| UNOWHY              | 12        | 0.32%   |
| PC Specialist       | 12        | 0.32%   |
| Razer               | 11        | 0.29%   |
| Medion              | 9         | 0.24%   |
| Chuwi               | 9         | 0.24%   |
| Alienware           | 9         | 0.24%   |
| Teclast             | 8         | 0.21%   |
| Google              | 8         | 0.21%   |
| Valve               | 7         | 0.18%   |
| Intel               | 6         | 0.16%   |
| BESSTAR Tech        | 4         | 0.11%   |
| System76            | 3         | 0.08%   |
| SCHNEIDER           | 3         | 0.08%   |
| Panasonic           | 3         | 0.08%   |
| NEC Computers       | 3         | 0.08%   |
| Insyde              | 3         | 0.08%   |
| HONOR               | 3         | 0.08%   |
| Essentiel B         | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 31        | 0.82%   |
| HP Notebook                                | 28        | 0.74%   |
| HP Pavilion dv6                            | 24        | 0.63%   |
| HP Pavilion dv7                            | 21        | 0.55%   |
| Dell XPS 13 9310                           | 17        | 0.45%   |
| HP Pavilion g7                             | 16        | 0.42%   |
| HP Pavilion 17                             | 16        | 0.42%   |
| Dell XPS 13 7390                           | 14        | 0.37%   |
| Dell XPS 15 7590                           | 13        | 0.34%   |
| HP Pavilion Notebook                       | 12        | 0.32%   |
| HP EliteBook 840 G2                        | 12        | 0.32%   |
| Dell XPS 15 9570                           | 12        | 0.32%   |
| Dell XPS 13 9380                           | 12        | 0.32%   |
| HUAWEI HVY-WXX9                            | 11        | 0.29%   |
| HP Pavilion g6                             | 11        | 0.29%   |
| Dell Latitude E6420                        | 11        | 0.29%   |
| HP ProBook 650 G1                          | 10        | 0.26%   |
| HP Pavilion 15                             | 10        | 0.26%   |
| Dell Latitude E6400                        | 10        | 0.26%   |
| ASUS S551LN                                | 10        | 0.26%   |
| Lenovo G50-30 80G0                         | 9         | 0.24%   |
| HUAWEI NBLK-WAX9X                          | 9         | 0.24%   |
| HP OMEN by Laptop                          | 9         | 0.24%   |
| Lenovo G50-45 80E3                         | 8         | 0.21%   |
| HP ProBook 640 G1                          | 8         | 0.21%   |
| HP EliteBook 840 G3                        | 8         | 0.21%   |
| Dell XPS 15 9500                           | 8         | 0.21%   |
| Dell XPS 13 9370                           | 8         | 0.21%   |
| Dell Latitude 7490                         | 8         | 0.21%   |
| Dell Latitude 5420                         | 8         | 0.21%   |
| ASUS VivoBook_ASUSLaptop X570ZD_X570ZD     | 8         | 0.21%   |
| Acer Aspire ES1-523                        | 8         | 0.21%   |
| Valve Jupiter                              | 7         | 0.18%   |
| UNOWHY Y13G010S4EI                         | 7         | 0.18%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 7         | 0.18%   |
| HP Laptop 15-db0xxx                        | 7         | 0.18%   |
| HP EliteBook 840 G1                        | 7         | 0.18%   |
| Dell XPS 13 9360                           | 7         | 0.18%   |
| Dell Precision 5540                        | 7         | 0.18%   |
| Dell Latitude E5500                        | 7         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 363       | 9.57%   |
| Dell Latitude         | 267       | 7.04%   |
| Acer Aspire           | 193       | 5.09%   |
| HP Pavilion           | 182       | 4.8%    |
| Dell XPS              | 132       | 3.48%   |
| Lenovo IdeaPad        | 114       | 3.01%   |
| HP EliteBook          | 113       | 2.98%   |
| HP ProBook            | 110       | 2.9%    |
| Toshiba Satellite     | 109       | 2.87%   |
| Dell Precision        | 99        | 2.61%   |
| Dell Inspiron         | 96        | 2.53%   |
| ASUS VivoBook         | 88        | 2.32%   |
| HP Laptop             | 55        | 1.45%   |
| Packard Bell EasyNote | 44        | 1.16%   |
| Acer Swift            | 36        | 0.95%   |
| Dell Vostro           | 35        | 0.92%   |
| ASUS ZenBook          | 35        | 0.92%   |
| Unknown               | 31        | 0.82%   |
| Lenovo Legion         | 30        | 0.79%   |
| ASUS ROG              | 30        | 0.79%   |
| HP Notebook           | 28        | 0.74%   |
| HP Compaq             | 27        | 0.71%   |
| HP ZBook              | 25        | 0.66%   |
| HP OMEN               | 18        | 0.47%   |
| Dell G5               | 17        | 0.45%   |
| HP ENVY               | 16        | 0.42%   |
| ASUS TUF              | 16        | 0.42%   |
| Acer Nitro            | 16        | 0.42%   |
| ASUS ASUS             | 15        | 0.4%    |
| MSI Modern            | 14        | 0.37%   |
| Lenovo ThinkBook      | 13        | 0.34%   |
| Acer TravelMate       | 13        | 0.34%   |
| Fujitsu LIFEBOOK      | 12        | 0.32%   |
| Dell G3               | 12        | 0.32%   |
| Razer Blade           | 11        | 0.29%   |
| Lenovo Yoga           | 11        | 0.29%   |
| HUAWEI HVY-WXX9       | 11        | 0.29%   |
| ASUS S551LN           | 10        | 0.26%   |
| Apple MacBookPro5     | 10        | 0.26%   |
| Notebook NL40         | 9         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 417       | 11%     |
| 2020    | 392       | 10.34%  |
| 2018    | 359       | 9.47%   |
| 2012    | 290       | 7.65%   |
| 2013    | 272       | 7.17%   |
| 2011    | 256       | 6.75%   |
| 2015    | 252       | 6.65%   |
| 2021    | 234       | 6.17%   |
| 2017    | 225       | 5.93%   |
| 2016    | 206       | 5.43%   |
| 2010    | 195       | 5.14%   |
| 2014    | 193       | 5.09%   |
| 2008    | 180       | 4.75%   |
| 2009    | 147       | 3.88%   |
| 2007    | 81        | 2.14%   |
| 2022    | 42        | 1.11%   |
| 2006    | 29        | 0.76%   |
| 2005    | 13        | 0.34%   |
| Unknown | 4         | 0.11%   |
| 2004    | 3         | 0.08%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3792      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3371      | 88.18%  |
| Enabled  | 452       | 11.82%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3779      | 99.63%  |
| Yes  | 14        | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1046      | 27.35%  |
| 3.01-4.0    | 954       | 24.95%  |
| 16.01-24.0  | 672       | 17.57%  |
| 8.01-16.0   | 569       | 14.88%  |
| 32.01-64.0  | 232       | 6.07%   |
| 1.01-2.0    | 178       | 4.65%   |
| 2.01-3.0    | 73        | 1.91%   |
| 64.01-256.0 | 36        | 0.94%   |
| 0.51-1.0    | 30        | 0.78%   |
| 24.01-32.0  | 26        | 0.68%   |
| 0.01-0.5    | 6         | 0.16%   |
| Unknown     | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1526      | 36.9%   |
| 2.01-3.0   | 1049      | 25.36%  |
| 4.01-8.0   | 562       | 13.59%  |
| 3.01-4.0   | 507       | 12.26%  |
| 0.51-1.0   | 279       | 6.75%   |
| 8.01-16.0  | 153       | 3.7%    |
| 0.01-0.5   | 41        | 0.99%   |
| 16.01-24.0 | 11        | 0.27%   |
| 24.01-32.0 | 5         | 0.12%   |
| Unknown    | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2823      | 73.4%   |
| 2      | 877       | 22.8%   |
| 3      | 92        | 2.39%   |
| 0      | 34        | 0.88%   |
| 4      | 13        | 0.34%   |
| 5      | 5         | 0.13%   |
| 7      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2282      | 59.91%  |
| Yes       | 1527      | 40.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3143      | 82.6%   |
| No        | 662       | 17.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3725      | 98.13%  |
| No        | 71        | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2862      | 74.55%  |
| No        | 977       | 25.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 3792      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 660       | 16.16%  |
| Lyon             | 91        | 2.23%   |
| Toulouse         | 77        | 1.88%   |
| Marseille        | 69        | 1.69%   |
| Nantes           | 55        | 1.35%   |
| Lille            | 42        | 1.03%   |
| Montpellier      | 39        | 0.95%   |
| Rennes           | 37        | 0.91%   |
| Strasbourg       | 36        | 0.88%   |
| Bordeaux         | 33        | 0.81%   |
| Grenoble         | 31        | 0.76%   |
| Clichy-sous-Bois | 28        | 0.69%   |
| Brest            | 24        | 0.59%   |
| Roubaix          | 22        | 0.54%   |
| Villeurbanne     | 21        | 0.51%   |
| Nice             | 19        | 0.47%   |
| Caen             | 19        | 0.47%   |
| Nancy            | 16        | 0.39%   |
| Rouen            | 15        | 0.37%   |
| Poitiers         | 15        | 0.37%   |
| Cergy            | 15        | 0.37%   |
| Besançon        | 15        | 0.37%   |
| Tours            | 14        | 0.34%   |
| Metz             | 14        | 0.34%   |
| Toulon           | 13        | 0.32%   |
| Orléans         | 13        | 0.32%   |
| La Rochelle      | 13        | 0.32%   |
| Clermont-Ferrand | 13        | 0.32%   |
| Aix-en-Provence  | 13        | 0.32%   |
| Villejuif        | 12        | 0.29%   |
| Versailles       | 12        | 0.29%   |
| Saint-Denis      | 12        | 0.29%   |
| Le Mans          | 12        | 0.29%   |
| Ivry-sur-Seine   | 12        | 0.29%   |
| Colmar           | 12        | 0.29%   |
| Perpignan        | 11        | 0.27%   |
| Palaiseau        | 11        | 0.27%   |
| Béziers         | 11        | 0.27%   |
| Tarbes           | 10        | 0.24%   |
| Reims            | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 684       | 924    | 14.71%  |
| WDC                       | 530       | 656    | 11.4%   |
| Seagate                   | 522       | 668    | 11.23%  |
| Toshiba                   | 416       | 523    | 8.95%   |
| SanDisk                   | 288       | 351    | 6.19%   |
| Crucial                   | 283       | 353    | 6.09%   |
| SK hynix                  | 230       | 275    | 4.95%   |
| Kingston                  | 225       | 267    | 4.84%   |
| Unknown                   | 218       | 285    | 4.69%   |
| HGST                      | 212       | 258    | 4.56%   |
| Hitachi                   | 159       | 179    | 3.42%   |
| Intel                     | 126       | 154    | 2.71%   |
| Micron Technology         | 124       | 146    | 2.67%   |
| KIOXIA                    | 55        | 62     | 1.18%   |
| PNY                       | 40        | 42     | 0.86%   |
| Apple                     | 40        | 54     | 0.86%   |
| Fujitsu                   | 37        | 45     | 0.8%    |
| LDLC                      | 36        | 51     | 0.77%   |
| LITEON                    | 31        | 36     | 0.67%   |
| Transcend                 | 30        | 33     | 0.65%   |
| Phison                    | 20        | 22     | 0.43%   |
| China                     | 19        | 22     | 0.41%   |
| LITEONIT                  | 18        | 18     | 0.39%   |
| Corsair                   | 16        | 19     | 0.34%   |
| SPCC                      | 13        | 14     | 0.28%   |
| JMicron Technology        | 13        | 15     | 0.28%   |
| A-DATA Technology         | 13        | 18     | 0.28%   |
| Micron/Crucial Technology | 12        | 12     | 0.26%   |
| Silicon Motion            | 10        | 12     | 0.22%   |
| Unknown                   | 10        | 11     | 0.22%   |
| Lite-On                   | 9         | 13     | 0.19%   |
| BHT                       | 8         | 10     | 0.17%   |
| Patriot                   | 7         | 8      | 0.15%   |
| OCZ                       | 7         | 11     | 0.15%   |
| Netac                     | 7         | 8      | 0.15%   |
| Lenovo                    | 7         | 9      | 0.15%   |
| Dogfish                   | 7         | 9      | 0.15%   |
| YMTC                      | 6         | 7      | 0.13%   |
| SSSTC                     | 6         | 8      | 0.13%   |
| KingSpec                  | 6         | 7      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 83        | 1.73%   |
| HGST HTS721010A9E630 1TB           | 83        | 1.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 70        | 1.46%   |
| Toshiba MQ01ABD100 1TB             | 68        | 1.41%   |
| Crucial CT500MX500SSD1 500GB       | 52        | 1.08%   |
| Toshiba MQ04ABF100 1TB             | 48        | 1%      |
| Crucial CT240BX500SSD1 240GB       | 48        | 1%      |
| Samsung SSD 860 EVO 500GB          | 46        | 0.96%   |
| Unknown MMC Card  32GB             | 43        | 0.89%   |
| HGST HTS541010A9E680 1TB           | 39        | 0.81%   |
| Samsung NVMe SSD Drive 512GB       | 37        | 0.77%   |
| SanDisk NVMe SSD Drive 512GB       | 36        | 0.75%   |
| Unknown MMC Card  64GB             | 30        | 0.62%   |
| Kingston SA400S37240G 240GB SSD    | 30        | 0.62%   |
| Seagate ST500LT012-1DG142 500GB    | 29        | 0.6%    |
| Seagate ST9500325AS 500GB          | 28        | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB     | 26        | 0.54%   |
| Toshiba NVMe SSD Drive 512GB       | 25        | 0.52%   |
| Samsung NVMe SSD Drive 256GB       | 24        | 0.5%    |
| HGST HTS725050A7E630 500GB         | 24        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB        | 24        | 0.5%    |
| Intel NVMe SSD Drive 512GB         | 23        | 0.48%   |
| Toshiba MQ01ABF050 500GB           | 22        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB      | 22        | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB           | 21        | 0.44%   |
| Seagate ST1000LM049-2GH172 1TB     | 21        | 0.44%   |
| Samsung SSD 870 QVO 1TB            | 20        | 0.42%   |
| Samsung SSD 860 EVO 1TB            | 20        | 0.42%   |
| Samsung NVMe SSD Drive 1TB         | 20        | 0.42%   |
| Crucial CT480BX500SSD1 480GB       | 20        | 0.42%   |
| Crucial CT120BX500SSD1 120GB       | 20        | 0.42%   |
| SanDisk NVMe SSD Drive 256GB       | 19        | 0.4%    |
| Samsung SSD 850 EVO 500GB          | 19        | 0.4%    |
| Samsung SSD 850 EVO 250GB          | 19        | 0.4%    |
| KIOXIA KBG40ZNS512G NVMe 512GB     | 19        | 0.4%    |
| Kingston SA400S37120G 120GB SSD    | 18        | 0.37%   |
| Intel SSDPEKNW512G8 512GB          | 17        | 0.35%   |
| Seagate ST500LM021-1KJ152 500GB    | 16        | 0.33%   |
| Seagate Expansion 1TB              | 16        | 0.33%   |
| Hitachi HTS547575A9E384 752GB      | 16        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 516       | 657    | 31.39%  |
| WDC                 | 360       | 449    | 21.9%   |
| Toshiba             | 288       | 350    | 17.52%  |
| HGST                | 212       | 258    | 12.9%   |
| Hitachi             | 159       | 179    | 9.67%   |
| Samsung Electronics | 36        | 49     | 2.19%   |
| Fujitsu             | 36        | 44     | 2.19%   |
| Unknown             | 8         | 9      | 0.49%   |
| Apple               | 7         | 7      | 0.43%   |
| IBM/Hitachi         | 5         | 6      | 0.3%    |
| JMicron Technology  | 3         | 4      | 0.18%   |
| Inateck             | 2         | 2      | 0.12%   |
| HGST HTS            | 2         | 2      | 0.12%   |
| ASMT                | 2         | 3      | 0.12%   |
| SILICONMOTION       | 1         | 1      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| Magnetic Data       | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Generic-            | 1         | 1      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| APPLE HD            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 347       | 457    | 22.93%  |
| Crucial             | 264       | 333    | 17.45%  |
| SanDisk             | 190       | 231    | 12.56%  |
| Kingston            | 169       | 202    | 11.17%  |
| Micron Technology   | 56        | 74     | 3.7%    |
| SK hynix            | 54        | 66     | 3.57%   |
| Intel               | 36        | 37     | 2.38%   |
| PNY                 | 35        | 37     | 2.31%   |
| WDC                 | 34        | 40     | 2.25%   |
| LDLC                | 30        | 43     | 1.98%   |
| Apple               | 30        | 42     | 1.98%   |
| Transcend           | 28        | 31     | 1.85%   |
| LITEON              | 26        | 29     | 1.72%   |
| Toshiba             | 22        | 29     | 1.45%   |
| LITEONIT            | 18        | 18     | 1.19%   |
| China               | 18        | 21     | 1.19%   |
| SPCC                | 12        | 13     | 0.79%   |
| A-DATA Technology   | 10        | 15     | 0.66%   |
| Corsair             | 8         | 10     | 0.53%   |
| BHT                 | 8         | 10     | 0.53%   |
| OCZ                 | 7         | 11     | 0.46%   |
| Dogfish             | 7         | 9      | 0.46%   |
| Patriot             | 6         | 6      | 0.4%    |
| KingSpec            | 6         | 7      | 0.4%    |
| Emtec               | 6         | 6      | 0.4%    |
| Netac               | 5         | 6      | 0.33%   |
| Unknown             | 5         | 6      | 0.33%   |
| Plextor             | 4         | 5      | 0.26%   |
| KingDian            | 4         | 4      | 0.26%   |
| Unknown             | 3         | 4      | 0.2%    |
| Teclast             | 3         | 5      | 0.2%    |
| TCSUNBOW            | 3         | 4      | 0.2%    |
| BAITITON            | 3         | 3      | 0.2%    |
| ASMT                | 3         | 3      | 0.2%    |
| Verbatim            | 2         | 2      | 0.13%   |
| Union Memory        | 2         | 2      | 0.13%   |
| Seagate             | 2         | 2      | 0.13%   |
| ORICO               | 2         | 2      | 0.13%   |
| NMICRO              | 2         | 2      | 0.13%   |
| Intenso             | 2         | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1597      | 2027   | 35.71%  |
| SSD     | 1404      | 1875   | 31.4%   |
| NVMe    | 1202      | 1527   | 26.88%  |
| MMC     | 218       | 292    | 4.87%   |
| Unknown | 51        | 56     | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2669      | 3791   | 63.19%  |
| NVMe | 1196      | 1517   | 28.31%  |
| MMC  | 218       | 292    | 5.16%   |
| SAS  | 141       | 177    | 3.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1918      | 2547   | 64.15%  |
| 0.51-1.0   | 990       | 1244   | 33.11%  |
| 1.01-2.0   | 70        | 95     | 2.34%   |
| 3.01-4.0   | 6         | 7      | 0.2%    |
| 4.01-10.0  | 3         | 5      | 0.1%    |
| 10.01-20.0 | 2         | 3      | 0.07%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1128      | 28.48%  |
| 251-500        | 1040      | 26.26%  |
| 501-1000       | 660       | 16.67%  |
| 1-20           | 302       | 7.63%   |
| 51-100         | 249       | 6.29%   |
| 1001-2000      | 201       | 5.08%   |
| 21-50          | 175       | 4.42%   |
| Unknown        | 103       | 2.6%    |
| 2001-3000      | 54        | 1.36%   |
| More than 3000 | 48        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1642      | 39.93%  |
| 21-50          | 729       | 17.73%  |
| 101-250        | 560       | 13.62%  |
| 51-100         | 522       | 12.69%  |
| 251-500        | 305       | 7.42%   |
| 501-1000       | 167       | 4.06%   |
| Unknown        | 103       | 2.5%    |
| 1001-2000      | 49        | 1.19%   |
| 2001-3000      | 24        | 0.58%   |
| More than 3000 | 9         | 0.22%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                            | 15        | 17     | 4.48%   |
| HGST HTS541010A9E680 1TB                            | 10        | 10     | 2.99%   |
| Seagate ST9500325AS 500GB                           | 8         | 9      | 2.39%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 9      | 2.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 7      | 2.09%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 6      | 1.79%   |
| Seagate ST500LM021-1KJ152 500GB                     | 6         | 8      | 1.79%   |
| Toshiba MQ01ABD050 500GB                            | 5         | 5      | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 5      | 1.49%   |
| Toshiba MK3265GSX 320GB                             | 4         | 5      | 1.19%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 4         | 4      | 1.19%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 4      | 1.19%   |
| Hitachi HTS545050B9A300 500GB                       | 4         | 4      | 1.19%   |
| Hitachi HTS545050A7E380 500GB                       | 4         | 4      | 1.19%   |
| Hitachi HTS543232A7A384 320GB                       | 4         | 6      | 1.19%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 1.19%   |
| Toshiba MK5055GSX 500GB                             | 3         | 3      | 0.9%    |
| Toshiba MK3261GSYN 320GB                            | 3         | 3      | 0.9%    |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 0.9%    |
| Seagate ST320LT007-9ZV142 320GB                     | 3         | 4      | 0.9%    |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 3      | 0.9%    |
| Hitachi HTS727575A9E364 752GB                       | 3         | 3      | 0.9%    |
| Hitachi HTS547550A9E384 500GB                       | 3         | 3      | 0.9%    |
| Crucial CT525MX300SSD1 528GB                        | 3         | 3      | 0.9%    |
| WDC WD5000BEKT-75KA9T0 500GB                        | 2         | 2      | 0.6%    |
| WDC WD3200BPVT-80ZEST0 320GB                        | 2         | 2      | 0.6%    |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.6%    |
| Toshiba MK8052GSX 80GB                              | 2         | 2      | 0.6%    |
| Toshiba MK7575GSX 752GB                             | 2         | 2      | 0.6%    |
| Toshiba MK5059GSXP 500GB                            | 2         | 2      | 0.6%    |
| Toshiba MK3252GSX 320GB                             | 2         | 2      | 0.6%    |
| Seagate ST9500420AS 500GB                           | 2         | 2      | 0.6%    |
| Seagate ST9250827AS 250GB                           | 2         | 2      | 0.6%    |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 2      | 0.6%    |
| Seagate ST320LT012-9WS14C 320GB                     | 2         | 2      | 0.6%    |
| SanDisk SD7SB3Q128G1002 128GB SSD                   | 2         | 2      | 0.6%    |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 2         | 2      | 0.6%    |
| Samsung Electronics HM320JI 320GB                   | 2         | 2      | 0.6%    |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.6%    |
| LITEON CV8-8E128-HP 128GB SSD                       | 2         | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 77     | 20.06%  |
| Hitachi             | 44        | 46     | 13.17%  |
| Toshiba             | 41        | 45     | 12.28%  |
| WDC                 | 39        | 40     | 11.68%  |
| HGST                | 37        | 39     | 11.08%  |
| Samsung Electronics | 17        | 20     | 5.09%   |
| SK hynix            | 13        | 14     | 3.89%   |
| Crucial             | 13        | 13     | 3.89%   |
| SanDisk             | 12        | 13     | 3.59%   |
| Intel               | 11        | 11     | 3.29%   |
| Kingston            | 9         | 9      | 2.69%   |
| Fujitsu             | 6         | 6      | 1.8%    |
| Micron Technology   | 3         | 3      | 0.9%    |
| LITEON              | 2         | 2      | 0.6%    |
| LDLC                | 2         | 4      | 0.6%    |
| Dogfish             | 2         | 2      | 0.6%    |
| Corsair             | 2         | 2      | 0.6%    |
| Unknown             | 1         | 1      | 0.3%    |
| TakeMS              | 1         | 1      | 0.3%    |
| Phison              | 1         | 1      | 0.3%    |
| OCZ                 | 1         | 1      | 0.3%    |
| Magnetic Data       | 1         | 1      | 0.3%    |
| LITEONIT            | 1         | 1      | 0.3%    |
| KingSpec            | 1         | 1      | 0.3%    |
| Intenso             | 1         | 1      | 0.3%    |
| IBM/Hitachi         | 1         | 1      | 0.3%    |
| China               | 1         | 1      | 0.3%    |
| ASENNO              | 1         | 1      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |
| Apacer              | 1         | 1      | 0.3%    |
| A-DATA Technology   | 1         | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 77     | 27.57%  |
| Hitachi             | 44        | 46     | 18.11%  |
| Toshiba             | 40        | 44     | 16.46%  |
| WDC                 | 38        | 39     | 15.64%  |
| HGST                | 37        | 39     | 15.23%  |
| Samsung Electronics | 8         | 8      | 3.29%   |
| Fujitsu             | 6         | 6      | 2.47%   |
| Unknown             | 1         | 1      | 0.41%   |
| Magnetic Data       | 1         | 1      | 0.41%   |
| IBM/Hitachi         | 1         | 1      | 0.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 240       | 262    | 72.73%  |
| SSD  | 83        | 88     | 25.15%  |
| NVMe | 7         | 10     | 2.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 2      | 13.33%  |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 13.33%  |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 6.67%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 6.67%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 6.67%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 6.67%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 6.67%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 6.67%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 6.67%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 40%     |
| Toshiba             | 5         | 5      | 33.33%  |
| SK hynix            | 1         | 1      | 6.67%   |
| Seagate             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1959      | 3077   | 48.35%  |
| Works    | 1752      | 2324   | 43.24%  |
| Malfunc  | 325       | 360    | 8.02%   |
| Failed   | 15        | 15     | 0.37%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2732      | 61.95%  |
| AMD                              | 433       | 9.82%   |
| Samsung Electronics              | 337       | 7.64%   |
| SanDisk                          | 220       | 4.99%   |
| SK hynix                         | 171       | 3.88%   |
| Toshiba America Info Systems     | 123       | 2.79%   |
| Micron Technology                | 69        | 1.56%   |
| Kingston Technology Company      | 58        | 1.32%   |
| KIOXIA                           | 50        | 1.13%   |
| Nvidia                           | 41        | 0.93%   |
| Phison Electronics               | 37        | 0.84%   |
| Micron/Crucial Technology        | 31        | 0.7%    |
| Silicon Motion                   | 13        | 0.29%   |
| Lite-On Technology               | 13        | 0.29%   |
| Union Memory (Shenzhen)          | 12        | 0.27%   |
| Silicon Integrated Systems [SiS] | 11        | 0.25%   |
| Marvell Technology Group         | 9         | 0.2%    |
| JMicron Technology               | 9         | 0.2%    |
| Yangtze Memory Technologies      | 7         | 0.16%   |
| Solid State Storage Technology   | 7         | 0.16%   |
| Lenovo                           | 6         | 0.14%   |
| Apple                            | 4         | 0.09%   |
| ADATA Technology                 | 4         | 0.09%   |
| VIA Technologies                 | 3         | 0.07%   |
| Silicon Image                    | 3         | 0.07%   |
| Seagate Technology               | 3         | 0.07%   |
| ASMedia Technology               | 2         | 0.05%   |
| ULi Electronics                  | 1         | 0.02%   |
| Realtek Semiconductor            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 354       | 7.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 289       | 6.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 266       | 5.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 231       | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 179       | 3.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 173       | 3.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 161       | 3.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 160       | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 143       | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 119       | 2.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 114       | 2.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 110       | 2.33%   |
| Intel Volume Management Device NVMe RAID Controller                              | 102       | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 98        | 2.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 90        | 1.91%   |
| Samsung NVMe SSD Controller 980                                                  | 87        | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 77        | 1.63%   |
| Micron Non-Volatile memory controller                                            | 69        | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 67        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 60        | 1.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 59        | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 58        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 52        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 51        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 51        | 1.08%   |
| SK hynix Non-Volatile memory controller                                          | 50        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 45        | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 44        | 0.93%   |
| SK hynix Gold P31 SSD                                                            | 43        | 0.91%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 43        | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 42        | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 40        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 40        | 0.85%   |
| Intel SSD 660P Series                                                            | 39        | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 36        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 34        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                              | 34        | 0.72%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 33        | 0.7%    |
| SK hynix BC511                                                                   | 33        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 33        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2721      | 59.55%  |
| NVMe | 1213      | 26.55%  |
| RAID | 349       | 7.64%   |
| IDE  | 286       | 6.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3197      | 84.31%  |
| AMD    | 593       | 15.64%  |
| ARM    | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 79        | 2.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 1.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 59        | 1.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 54        | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 53        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 50        | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 48        | 1.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 46        | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 42        | 1.11%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 42        | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 40        | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 38        | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 37        | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 36        | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 36        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 36        | 0.95%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 33        | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 29        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 26        | 0.68%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 26        | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 25        | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 25        | 0.66%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 25        | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 24        | 0.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.63%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 24        | 0.63%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 22        | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 21        | 0.55%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 21        | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 21        | 0.55%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 21        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.55%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 20        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 944       | 24.88%  |
| Intel Core i7           | 862       | 22.72%  |
| Intel Core i3           | 329       | 8.67%   |
| Other                   | 255       | 6.72%   |
| Intel Core 2 Duo        | 219       | 5.77%   |
| Intel Celeron           | 210       | 5.54%   |
| AMD Ryzen 5             | 135       | 3.56%   |
| Intel Pentium           | 116       | 3.06%   |
| AMD Ryzen 7             | 100       | 2.64%   |
| Intel Atom              | 85        | 2.24%   |
| Intel Pentium Dual-Core | 45        | 1.19%   |
| AMD E1                  | 42        | 1.11%   |
| AMD A4                  | 33        | 0.87%   |
| AMD E2                  | 30        | 0.79%   |
| AMD A6                  | 29        | 0.76%   |
| Intel Pentium Dual      | 26        | 0.69%   |
| AMD Ryzen 7 PRO         | 24        | 0.63%   |
| Intel Core i9           | 23        | 0.61%   |
| AMD Ryzen 9             | 23        | 0.61%   |
| AMD E                   | 23        | 0.61%   |
| Intel Core 2            | 22        | 0.58%   |
| Intel Genuine           | 19        | 0.5%    |
| AMD A8                  | 15        | 0.4%    |
| AMD Ryzen 3             | 14        | 0.37%   |
| Intel Pentium Silver    | 12        | 0.32%   |
| AMD Athlon              | 12        | 0.32%   |
| Intel Celeron Dual-Core | 10        | 0.26%   |
| AMD Ryzen 5 PRO         | 10        | 0.26%   |
| Intel Xeon              | 9         | 0.24%   |
| Intel Pentium M         | 9         | 0.24%   |
| AMD Athlon II           | 9         | 0.24%   |
| Intel Celeron M         | 8         | 0.21%   |
| Intel Core m3           | 7         | 0.18%   |
| AMD Athlon X2           | 7         | 0.18%   |
| AMD Athlon II Dual-Core | 7         | 0.18%   |
| AMD Athlon 64 X2        | 7         | 0.18%   |
| AMD A12                 | 7         | 0.18%   |
| AMD Turion 64 X2 Mobile | 6         | 0.16%   |
| AMD A10                 | 6         | 0.16%   |
| AMD C-60                | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1908      | 50.3%   |
| 4       | 1303      | 34.35%  |
| 6       | 269       | 7.09%   |
| 8       | 177       | 4.67%   |
| 1       | 101       | 2.66%   |
| 12      | 12        | 0.32%   |
| 14      | 10        | 0.26%   |
| Unknown | 9         | 0.24%   |
| 10      | 4         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3790      | 99.92%  |
| 2      | 3         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2699      | 71.05%  |
| 1       | 1091      | 28.72%  |
| Unknown | 9         | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3710      | 97.66%  |
| Unknown        | 48        | 1.26%   |
| 32-bit         | 39        | 1.03%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 643       | 16.47%  |
| 0x306a9    | 247       | 6.33%   |
| 0x206a7    | 238       | 6.1%    |
| 0x806ec    | 159       | 4.07%   |
| 0x906ea    | 158       | 4.05%   |
| 0x1067a    | 148       | 3.79%   |
| 0x806c1    | 138       | 3.54%   |
| 0x306c3    | 125       | 3.2%    |
| 0x406e3    | 120       | 3.07%   |
| 0x306d4    | 120       | 3.07%   |
| 0x806ea    | 118       | 3.02%   |
| 0x40651    | 111       | 2.84%   |
| 0x806e9    | 104       | 2.66%   |
| 0x20655    | 104       | 2.66%   |
| 0x6fd      | 77        | 1.97%   |
| 0x506e3    | 70        | 1.79%   |
| 0x906e9    | 62        | 1.59%   |
| 0xa0652    | 60        | 1.54%   |
| 0x08108109 | 54        | 1.38%   |
| 0x08600106 | 50        | 1.28%   |
| 0x10676    | 48        | 1.23%   |
| 0x706e5    | 47        | 1.2%    |
| 0x406c4    | 44        | 1.13%   |
| 0x30678    | 44        | 1.13%   |
| 0x806eb    | 37        | 0.95%   |
| 0x406c3    | 37        | 0.95%   |
| 0x08108102 | 37        | 0.95%   |
| 0x706a1    | 35        | 0.9%    |
| 0x07030105 | 35        | 0.9%    |
| 0x806d1    | 34        | 0.87%   |
| 0x20652    | 31        | 0.79%   |
| 0x05000119 | 31        | 0.79%   |
| 0x506c9    | 29        | 0.74%   |
| 0x0a50000c | 27        | 0.69%   |
| 0x06006705 | 26        | 0.67%   |
| 0x906ed    | 24        | 0.61%   |
| 0x0810100b | 21        | 0.54%   |
| 0x0700010f | 21        | 0.54%   |
| 0x08608103 | 20        | 0.51%   |
| 0x08600104 | 20        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 791       | 20.85%  |
| Haswell          | 291       | 7.67%   |
| IvyBridge        | 286       | 7.54%   |
| SandyBridge      | 265       | 6.98%   |
| Skylake          | 229       | 6.04%   |
| Penryn           | 222       | 5.85%   |
| TigerLake        | 164       | 4.32%   |
| Silvermont       | 153       | 4.03%   |
| Westmere         | 152       | 4.01%   |
| Core             | 137       | 3.61%   |
| Broadwell        | 136       | 3.58%   |
| Zen 2            | 107       | 2.82%   |
| Zen+             | 102       | 2.69%   |
| Icelake          | 88        | 2.32%   |
| CometLake        | 79        | 2.08%   |
| Goldmont plus    | 58        | 1.53%   |
| Unknown          | 57        | 1.5%    |
| Bobcat           | 56        | 1.48%   |
| Puma             | 53        | 1.4%    |
| Zen 3            | 47        | 1.24%   |
| Excavator        | 46        | 1.21%   |
| Bonnell          | 37        | 0.98%   |
| Goldmont         | 35        | 0.92%   |
| Zen              | 31        | 0.82%   |
| Jaguar           | 28        | 0.74%   |
| K8 Hammer        | 23        | 0.61%   |
| K10              | 23        | 0.61%   |
| P6               | 20        | 0.53%   |
| Alderlake Hybrid | 18        | 0.47%   |
| Nehalem          | 16        | 0.42%   |
| Piledriver       | 14        | 0.37%   |
| K10 Llano        | 12        | 0.32%   |
| K8 & K10 hybrid  | 9         | 0.24%   |
| Tremont          | 3         | 0.08%   |
| NetBurst         | 3         | 0.08%   |
| Steamroller      | 2         | 0.05%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2852      | 58.19%  |
| Nvidia                           | 1194      | 24.36%  |
| AMD                              | 846       | 17.26%  |
| Silicon Integrated Systems [SiS] | 7         | 0.14%   |
| VIA Technologies                 | 2         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 264       | 5.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 237       | 4.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 199       | 3.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 159       | 3.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 135       | 2.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 132       | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 130       | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 128       | 2.54%   |
| Intel UHD Graphics 620                                                                   | 126       | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 121       | 2.4%    |
| Intel HD Graphics 5500                                                                   | 120       | 2.38%   |
| Intel HD Graphics 620                                                                    | 111       | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 111       | 2.2%    |
| AMD Renoir                                                                               | 104       | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 103       | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 96        | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 87        | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 1.6%    |
| Intel HD Graphics 530                                                                    | 77        | 1.53%   |
| Intel HD Graphics 630                                                                    | 66        | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 64        | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 58        | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 58        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 47        | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 46        | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 46        | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 42        | 0.83%   |
| AMD Cezanne                                                                              | 42        | 0.83%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 41        | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 38        | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 36        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 36        | 0.71%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 35        | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 34        | 0.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 32        | 0.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.59%   |
| Nvidia GM108M [GeForce 840M]                                                             | 29        | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 29        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1809      | 47.58%  |
| Intel + Nvidia | 895       | 23.54%  |
| 1 x AMD        | 572       | 15.04%  |
| 1 x Nvidia     | 231       | 6.08%   |
| Intel + AMD    | 149       | 3.92%   |
| 2 x AMD        | 63        | 1.66%   |
| AMD + Nvidia   | 63        | 1.66%   |
| 1 x SiS        | 7         | 0.18%   |
| 2 x Nvidia     | 6         | 0.16%   |
| Other          | 4         | 0.11%   |
| 1 x VIA        | 2         | 0.05%   |
| 2 x Intel      | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3228      | 84.24%  |
| Proprietary | 506       | 13.2%   |
| Unknown     | 98        | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2293      | 59.34%  |
| 0.01-0.5   | 532       | 13.77%  |
| 1.01-2.0   | 468       | 12.11%  |
| 3.01-4.0   | 227       | 5.87%   |
| 0.51-1.0   | 227       | 5.87%   |
| 5.01-6.0   | 64        | 1.66%   |
| 7.01-8.0   | 33        | 0.85%   |
| 2.01-3.0   | 18        | 0.47%   |
| 8.01-16.0  | 2         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 881       | 20.49%  |
| Chimei Innolux          | 573       | 13.33%  |
| LG Display              | 570       | 13.26%  |
| BOE                     | 493       | 11.47%  |
| Samsung Electronics     | 470       | 10.93%  |
| Sharp                   | 147       | 3.42%   |
| Chi Mei Optoelectronics | 123       | 2.86%   |
| Dell                    | 106       | 2.47%   |
| Iiyama                  | 93        | 2.16%   |
| Apple                   | 84        | 1.95%   |
| Lenovo                  | 77        | 1.79%   |
| PANDA                   | 59        | 1.37%   |
| Acer                    | 57        | 1.33%   |
| LG Philips              | 54        | 1.26%   |
| Hewlett-Packard         | 50        | 1.16%   |
| Goldstar                | 44        | 1.02%   |
| InfoVision              | 41        | 0.95%   |
| BenQ                    | 38        | 0.88%   |
| Ancor Communications    | 36        | 0.84%   |
| AOC                     | 33        | 0.77%   |
| Philips                 | 29        | 0.67%   |
| ViewSonic               | 20        | 0.47%   |
| CPT                     | 17        | 0.4%    |
| HannStar                | 14        | 0.33%   |
| CSO                     | 14        | 0.33%   |
| Sony                    | 13        | 0.3%    |
| ASUSTek Computer        | 12        | 0.28%   |
| Fujitsu Siemens         | 11        | 0.26%   |
| Seiko/Epson             | 8         | 0.19%   |
| Vestel Elektronik       | 7         | 0.16%   |
| Toshiba                 | 7         | 0.16%   |
| ANX                     | 7         | 0.16%   |
| TMX                     | 5         | 0.12%   |
| Panasonic               | 5         | 0.12%   |
| LPL                     | 5         | 0.12%   |
| LGD                     | 5         | 0.12%   |
| Unknown                 | 4         | 0.09%   |
| JDI                     | 4         | 0.09%   |
| ___                     | 3         | 0.07%   |
| Quanta Display          | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 40        | 0.92%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch      | 31        | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 29        | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 28        | 0.64%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 24        | 0.55%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 23        | 0.53%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 22        | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 22        | 0.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 22        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 21        | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 21        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 19        | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 18        | 0.41%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 17        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 17        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 16        | 0.37%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 16        | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 16        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 15        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 15        | 0.35%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 14        | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 13        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 13        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 13        | 0.3%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 12        | 0.28%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 12        | 0.28%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 11        | 0.25%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 11        | 0.25%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 11        | 0.25%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 11        | 0.25%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 11        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1724      | 43.11%  |
| 1366x768 (WXGA)    | 1026      | 25.66%  |
| 1600x900 (HD+)     | 388       | 9.7%    |
| 1280x800 (WXGA)    | 160       | 4%      |
| 3840x2160 (4K)     | 128       | 3.2%    |
| 1440x900 (WXGA+)   | 97        | 2.43%   |
| 1920x1200 (WUXGA)  | 94        | 2.35%   |
| 2560x1440 (QHD)    | 81        | 2.03%   |
| 1680x1050 (WSXGA+) | 49        | 1.23%   |
| 1024x600           | 29        | 0.73%   |
| 1280x1024 (SXGA)   | 27        | 0.68%   |
| 2560x1600          | 19        | 0.48%   |
| 2880x1800          | 16        | 0.4%    |
| 3440x1440          | 15        | 0.38%   |
| 2160x1440          | 15        | 0.38%   |
| 3840x2400          | 12        | 0.3%    |
| 3200x1800 (QHD+)   | 11        | 0.28%   |
| 2560x1080          | 11        | 0.28%   |
| Unknown            | 10        | 0.25%   |
| 1360x768           | 8         | 0.2%    |
| 800x1280           | 7         | 0.18%   |
| 1920x540           | 7         | 0.18%   |
| 3840x1080          | 6         | 0.15%   |
| 3000x2000          | 6         | 0.15%   |
| 1680x945           | 6         | 0.15%   |
| 1600x1200          | 5         | 0.13%   |
| 1024x768 (XGA)     | 5         | 0.13%   |
| 1920x515           | 4         | 0.1%    |
| 3840x1200          | 3         | 0.08%   |
| 2288x1287          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 5760x2160          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 720x1280           | 1         | 0.03%   |
| 4480x1600          | 1         | 0.03%   |
| 4480x1440          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1629      | 37.95%  |
| 17      | 602       | 14.03%  |
| 13      | 600       | 13.98%  |
| 14      | 410       | 9.55%   |
| 24      | 174       | 4.05%   |
| 23      | 131       | 3.05%   |
| 12      | 116       | 2.7%    |
| 27      | 114       | 2.66%   |
| 21      | 90        | 2.1%    |
| Unknown | 69        | 1.61%   |
| 11      | 58        | 1.35%   |
| 10      | 40        | 0.93%   |
| 18      | 37        | 0.86%   |
| 16      | 35        | 0.82%   |
| 22      | 30        | 0.7%    |
| 19      | 29        | 0.68%   |
| 34      | 26        | 0.61%   |
| 20      | 16        | 0.37%   |
| 31      | 15        | 0.35%   |
| 72      | 13        | 0.3%    |
| 84      | 9         | 0.21%   |
| 25      | 8         | 0.19%   |
| 54      | 5         | 0.12%   |
| 32      | 5         | 0.12%   |
| 33      | 4         | 0.09%   |
| 49      | 3         | 0.07%   |
| 40      | 3         | 0.07%   |
| 52      | 2         | 0.05%   |
| 48      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 43      | 2         | 0.05%   |
| 26      | 2         | 0.05%   |
| 142     | 1         | 0.02%   |
| 74      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 38      | 1         | 0.02%   |
| 37      | 1         | 0.02%   |
| 35      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2276      | 53.49%  |
| 351-400        | 683       | 16.05%  |
| 201-300        | 539       | 12.67%  |
| 501-600        | 390       | 9.17%   |
| 401-500        | 186       | 4.37%   |
| Unknown        | 69        | 1.62%   |
| 701-800        | 34        | 0.8%    |
| 601-700        | 27        | 0.63%   |
| 1501-2000      | 23        | 0.54%   |
| 1001-1500      | 18        | 0.42%   |
| 801-900        | 7         | 0.16%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3179      | 84.03%  |
| 16/10   | 434       | 11.47%  |
| Unknown | 39        | 1.03%   |
| 3/2     | 33        | 0.87%   |
| 21/9    | 29        | 0.77%   |
| 5/4     | 28        | 0.74%   |
| 4/3     | 19        | 0.5%    |
| 0.62    | 8         | 0.21%   |
| 32/9    | 5         | 0.13%   |
| 3.73    | 3         | 0.08%   |
| 3.20    | 3         | 0.08%   |
| 3.88    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1644      | 38.37%  |
| 81-90          | 736       | 17.18%  |
| 121-130        | 500       | 11.67%  |
| 201-250        | 348       | 8.12%   |
| 71-80          | 274       | 6.39%   |
| 301-350        | 115       | 2.68%   |
| 61-70          | 110       | 2.57%   |
| 131-140        | 91        | 2.12%   |
| 151-200        | 73        | 1.7%    |
| Unknown        | 69        | 1.61%   |
| 51-60          | 58        | 1.35%   |
| 251-300        | 56        | 1.31%   |
| 351-500        | 52        | 1.21%   |
| 141-150        | 42        | 0.98%   |
| 41-50          | 41        | 0.96%   |
| More than 1000 | 33        | 0.77%   |
| 111-120        | 15        | 0.35%   |
| 501-1000       | 14        | 0.33%   |
| 91-100         | 12        | 0.28%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1646      | 39.04%  |
| 101-120       | 1340      | 31.78%  |
| 51-100        | 757       | 17.96%  |
| 161-240       | 269       | 6.38%   |
| More than 240 | 107       | 2.54%   |
| Unknown       | 69        | 1.64%   |
| 1-50          | 28        | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3096      | 79.79%  |
| 2     | 601       | 15.49%  |
| 0     | 108       | 2.78%   |
| 3     | 70        | 1.8%    |
| 4     | 3         | 0.08%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2057      | 34.03%  |
| Realtek Semiconductor             | 1932      | 31.97%  |
| Qualcomm Atheros                  | 977       | 16.16%  |
| Broadcom                          | 412       | 6.82%   |
| Marvell Technology Group          | 83        | 1.37%   |
| Broadcom Limited                  | 82        | 1.36%   |
| Ralink                            | 68        | 1.13%   |
| MediaTek                          | 46        | 0.76%   |
| Dell                              | 37        | 0.61%   |
| ASIX Electronics                  | 30        | 0.5%    |
| Nvidia                            | 28        | 0.46%   |
| Samsung Electronics               | 24        | 0.4%    |
| Ericsson Business Mobile Networks | 22        | 0.36%   |
| Xiaomi                            | 19        | 0.31%   |
| TP-Link                           | 17        | 0.28%   |
| Sierra Wireless                   | 17        | 0.28%   |
| DisplayLink                       | 17        | 0.28%   |
| JMicron Technology                | 16        | 0.26%   |
| Huawei Technologies               | 16        | 0.26%   |
| Attansic Technology               | 13        | 0.22%   |
| Ralink Technology                 | 12        | 0.2%    |
| NetGear                           | 12        | 0.2%    |
| Qualcomm                          | 11        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 10        | 0.17%   |
| Lenovo                            | 10        | 0.17%   |
| Hewlett-Packard                   | 9         | 0.15%   |
| Google                            | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| FIBOCOM                           | 4         | 0.07%   |
| Apple                             | 4         | 0.07%   |
| VIA Technologies                  | 3         | 0.05%   |
| U-Blox                            | 3         | 0.05%   |
| Toshiba                           | 3         | 0.05%   |
| OPPO Electronics                  | 3         | 0.05%   |
| ICS Advent                        | 3         | 0.05%   |
| D-Link                            | 3         | 0.05%   |
| Belkin Components                 | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |
| D-Link System                     | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1184      | 16.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 317       | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 204       | 2.8%    |
| Intel Wi-Fi 6 AX200                                                     | 191       | 2.62%   |
| Intel Wireless 8265 / 8275                                              | 160       | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 158       | 2.17%   |
| Intel Wireless 7265                                                     | 146       | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 141       | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 133       | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 132       | 1.81%   |
| Intel Wi-Fi 6 AX201                                                     | 128       | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 124       | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 1.66%   |
| Intel Wireless 7260                                                     | 110       | 1.51%   |
| Intel Wireless 8260                                                     | 108       | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 95        | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 93        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 92        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 86        | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 81        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 79        | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 77        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 68        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 67        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 59        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 56        | 0.77%   |
| Intel Wireless 3165                                                     | 56        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 53        | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 50        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 50        | 0.69%   |
| Intel Wireless-AC 9260                                                  | 48        | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 48        | 0.66%   |
| Intel WiFi Link 5100                                                    | 46        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                   | 46        | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 45        | 0.62%   |
| Intel Ethernet Connection I217-LM                                       | 45        | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 0.56%   |
| Intel Wireless 3160                                                     | 40        | 0.55%   |
| Intel Ethernet Connection I219-LM                                       | 40        | 0.55%   |
| Intel Centrino Wireless-N 2230                                          | 38        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1949      | 50.4%   |
| Qualcomm Atheros                      | 804       | 20.79%  |
| Realtek Semiconductor                 | 544       | 14.07%  |
| Broadcom                              | 298       | 7.71%   |
| Ralink                                | 68        | 1.76%   |
| Broadcom Limited                      | 55        | 1.42%   |
| MediaTek                              | 40        | 1.03%   |
| Dell                                  | 18        | 0.47%   |
| Sierra Wireless                       | 17        | 0.44%   |
| TP-Link                               | 14        | 0.36%   |
| Ralink Technology                     | 12        | 0.31%   |
| NetGear                               | 9         | 0.23%   |
| Ericsson Business Mobile Networks     | 7         | 0.18%   |
| Qualcomm                              | 6         | 0.16%   |
| Hewlett-Packard                       | 4         | 0.1%    |
| FIBOCOM                               | 4         | 0.1%    |
| Belkin Components                     | 3         | 0.08%   |
| D-Link System                         | 2         | 0.05%   |
| D-Link                                | 2         | 0.05%   |
| ASUSTek Computer                      | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Sagem                                 | 1         | 0.03%   |
| Qualcomm Atheros Communications       | 1         | 0.03%   |
| Microsoft                             | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| Edimax Technology                     | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 191       | 4.91%   |
| Intel Wireless 8265 / 8275                                              | 160       | 4.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 158       | 4.06%   |
| Intel Wireless 7265                                                     | 146       | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 141       | 3.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 132       | 3.39%   |
| Intel Wi-Fi 6 AX201                                                     | 128       | 3.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 124       | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 3.11%   |
| Intel Wireless 7260                                                     | 110       | 2.83%   |
| Intel Wireless 8260                                                     | 108       | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 95        | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 93        | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 92        | 2.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 86        | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 81        | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 79        | 2.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 77        | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 68        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 67        | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 59        | 1.52%   |
| Intel Wireless 3165                                                     | 56        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 50        | 1.29%   |
| Intel Wireless-AC 9260                                                  | 48        | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 48        | 1.23%   |
| Intel WiFi Link 5100                                                    | 46        | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 45        | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 1.05%   |
| Intel Wireless 3160                                                     | 40        | 1.03%   |
| Intel Centrino Wireless-N 2230                                          | 38        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 37        | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 35        | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 35        | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 30        | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 29        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 28        | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 28        | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 28        | 0.72%   |
| Intel Centrino Advanced-N 6235                                          | 28        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1753      | 53.28%  |
| Intel                            | 738       | 22.43%  |
| Qualcomm Atheros                 | 304       | 9.24%   |
| Broadcom                         | 160       | 4.86%   |
| Marvell Technology Group         | 83        | 2.52%   |
| ASIX Electronics                 | 30        | 0.91%   |
| Broadcom Limited                 | 29        | 0.88%   |
| Nvidia                           | 28        | 0.85%   |
| Samsung Electronics              | 23        | 0.7%    |
| Xiaomi                           | 19        | 0.58%   |
| DisplayLink                      | 17        | 0.52%   |
| JMicron Technology               | 16        | 0.49%   |
| Attansic Technology              | 13        | 0.4%    |
| Silicon Integrated Systems [SiS] | 10        | 0.3%    |
| Lenovo                           | 10        | 0.3%    |
| Huawei Technologies              | 10        | 0.3%    |
| MediaTek                         | 6         | 0.18%   |
| Qualcomm                         | 5         | 0.15%   |
| Google                           | 5         | 0.15%   |
| Apple                            | 4         | 0.12%   |
| TP-Link                          | 3         | 0.09%   |
| OPPO Electronics                 | 3         | 0.09%   |
| NetGear                          | 3         | 0.09%   |
| ICS Advent                       | 3         | 0.09%   |
| VIA Technologies                 | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.06%   |
| Cypress Semiconductor            | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| ULi Electronics                  | 1         | 0.03%   |
| Motorola PCS                     | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Hisense                          | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| Archos                           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1184      | 35.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 317       | 9.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 204       | 6.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 133       | 4.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 56        | 1.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 53        | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 1.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 46        | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 40        | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.99%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 32        | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 30        | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 24        | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                             | 23        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 22        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21        | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 21        | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 21        | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 19        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 17        | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 17        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 15        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.42%   |
| Intel Ethernet Connection (11) I219-LM                            | 14        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3725      | 53.67%  |
| Ethernet | 3138      | 45.21%  |
| Modem    | 73        | 1.05%   |
| Unknown  | 5         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3000      | 74.7%   |
| Ethernet | 1016      | 25.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2845      | 74.95%  |
| 1     | 866       | 22.81%  |
| 0     | 52        | 1.37%   |
| 3     | 33        | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2722      | 69.79%  |
| Yes  | 1178      | 30.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1489      | 51.72%  |
| Realtek Semiconductor           | 235       | 8.16%   |
| IMC Networks                    | 212       | 7.36%   |
| Qualcomm Atheros Communications | 207       | 7.19%   |
| Broadcom                        | 149       | 5.18%   |
| Lite-On Technology              | 107       | 3.72%   |
| Foxconn / Hon Hai               | 89        | 3.09%   |
| Apple                           | 83        | 2.88%   |
| Dell                            | 68        | 2.36%   |
| Cambridge Silicon Radio         | 45        | 1.56%   |
| Hewlett-Packard                 | 34        | 1.18%   |
| Realtek                         | 32        | 1.11%   |
| Toshiba                         | 31        | 1.08%   |
| Ralink                          | 29        | 1.01%   |
| Ralink Technology               | 18        | 0.63%   |
| ASUSTek Computer                | 16        | 0.56%   |
| Alps Electric                   | 11        | 0.38%   |
| Foxconn International           | 10        | 0.35%   |
| MediaTek                        | 5         | 0.17%   |
| Chicony Electronics             | 5         | 0.17%   |
| USI                             | 1         | 0.03%   |
| TP-Link                         | 1         | 0.03%   |
| Syntek                          | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 587       | 20.38%  |
| Intel AX201 Bluetooth                               | 295       | 10.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 249       | 8.65%   |
| Intel AX200 Bluetooth                               | 183       | 6.35%   |
| Realtek Bluetooth Radio                             | 150       | 5.21%   |
| IMC Networks Bluetooth Device                       | 93        | 3.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 81        | 2.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 65        | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 58        | 2.01%   |
| IMC Networks Bluetooth Radio                        | 47        | 1.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 45        | 1.56%   |
| Apple Bluetooth Host Controller                     | 45        | 1.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 44        | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 1.18%   |
| Lite-On Bluetooth Device                            | 33        | 1.15%   |
| Realtek Bluetooth Radio                             | 32        | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 1.08%   |
| Ralink RT3290 Bluetooth                             | 29        | 1.01%   |
| Dell DW375 Bluetooth Module                         | 27        | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 24        | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.76%   |
| Apple Bluetooth USB Host Controller                 | 22        | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.66%   |
| Intel Bluetooth Device                              | 18        | 0.63%   |
| Intel AX210 Bluetooth                               | 18        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.63%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 0.52%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 15        | 0.52%   |
| IMC Networks Wireless_Device                        | 14        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.49%   |
| IMC Networks Bluetooth                              | 13        | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 13        | 0.45%   |
| Broadcom HP Portable Bumble Bee                     | 13        | 0.45%   |
| Toshiba Bluetooth Device                            | 12        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3104      | 66.16%  |
| AMD                               | 709       | 15.11%  |
| Nvidia                            | 579       | 12.34%  |
| Realtek Semiconductor             | 48        | 1.02%   |
| GN Netcom                         | 27        | 0.58%   |
| Logitech                          | 24        | 0.51%   |
| C-Media Electronics               | 24        | 0.51%   |
| Plantronics                       | 18        | 0.38%   |
| Kingston Technology               | 18        | 0.38%   |
| JMTek                             | 17        | 0.36%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.23%   |
| Lenovo                            | 11        | 0.23%   |
| Hewlett-Packard                   | 7         | 0.15%   |
| Corsair                           | 7         | 0.15%   |
| SteelSeries ApS                   | 6         | 0.13%   |
| Texas Instruments                 | 4         | 0.09%   |
| VIA Technologies                  | 3         | 0.06%   |
| M-Audio                           | 3         | 0.06%   |
| Focusrite-Novation                | 3         | 0.06%   |
| Elitegroup Computer Systems (ECS) | 3         | 0.06%   |
| DSEA A/S                          | 3         | 0.06%   |
| Blue Microphones                  | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| ZOOM                              | 2         | 0.04%   |
| Sony                              | 2         | 0.04%   |
| Sennheiser Communications         | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| No brand                          | 2         | 0.04%   |
| Generalplus Technology            | 2         | 0.04%   |
| Dell                              | 2         | 0.04%   |
| Conexant Systems                  | 2         | 0.04%   |
| Cambridge Audio                   | 2         | 0.04%   |
| Barco Display Systems             | 2         | 0.04%   |
| Avid Technology                   | 2         | 0.04%   |
| Yealink Network Technology        | 1         | 0.02%   |
| XMOS                              | 1         | 0.02%   |
| ULi Electronics                   | 1         | 0.02%   |
| Trust                             | 1         | 0.02%   |
| TC Electronic                     | 1         | 0.02%   |
| Shenzhen Riitek Technology        | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 400       | 7.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 339       | 6.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 302       | 5.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 220       | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 212       | 3.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 201       | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 168       | 2.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 164       | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 161       | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 152       | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 136       | 2.42%   |
| Intel Broadwell-U Audio Controller                                                                | 136       | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 135       | 2.4%    |
| AMD FCH Azalia Controller                                                                         | 135       | 2.4%    |
| Intel 8 Series HD Audio Controller                                                                | 131       | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 129       | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 123       | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 122       | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 118       | 2.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 95        | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 92        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 83        | 1.48%   |
| Intel CM238 HD Audio Controller                                                                   | 79        | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 71        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 71        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 68        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 62        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 62        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 59        | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 58        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 54        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 52        | 0.92%   |
| AMD Wrestler HDMI Audio                                                                           | 52        | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 51        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 49        | 0.87%   |
| Realtek Semiconductor USB Audio                                                                   | 47        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 46        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 41        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 38        | 0.68%   |
| AMD High Definition Audio Controller                                                              | 36        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 825       | 29.71%  |
| SK hynix                                         | 748       | 26.94%  |
| Micron Technology                                | 327       | 11.78%  |
| Unknown                                          | 198       | 7.13%   |
| Kingston                                         | 186       | 6.7%    |
| Crucial                                          | 143       | 5.15%   |
| Elpida                                           | 60        | 2.16%   |
| Corsair                                          | 49        | 1.76%   |
| Ramaxel Technology                               | 44        | 1.58%   |
| A-DATA Technology                                | 36        | 1.3%    |
| Nanya Technology                                 | 34        | 1.22%   |
| G.Skill                                          | 33        | 1.19%   |
| Unknown (ABCD)                                   | 25        | 0.9%    |
| Transcend                                        | 10        | 0.36%   |
| ASint Technology                                 | 5         | 0.18%   |
| Unknown                                          | 5         | 0.18%   |
| V-Color                                          | 3         | 0.11%   |
| Toshiba                                          | 3         | 0.11%   |
| SHARETRONIC                                      | 3         | 0.11%   |
| PNY                                              | 3         | 0.11%   |
| Patriot                                          | 3         | 0.11%   |
| Apacer                                           | 3         | 0.11%   |
| TEXTORM                                          | 2         | 0.07%   |
| Team                                             | 2         | 0.07%   |
| Goldkey                                          | 2         | 0.07%   |
| Unknown (F301)                                   | 1         | 0.04%   |
| Unknown (0x8634)                                 | 1         | 0.04%   |
| Unknown (0x7301)                                 | 1         | 0.04%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.04%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.04%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.04%   |
| Unknown (07FB)                                   | 1         | 0.04%   |
| Unknown (01F3)                                   | 1         | 0.04%   |
| Silicon Power                                    | 1         | 0.04%   |
| PKI                                              | 1         | 0.04%   |
| OnBoard                                          | 1         | 0.04%   |
| Netlist                                          | 1         | 0.04%   |
| Neo Forza                                        | 1         | 0.04%   |
| Lexar                                            | 1         | 0.04%   |
| KingFast                                         | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 42        | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 41        | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 40        | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 40        | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 38        | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 30        | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 30        | 1.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 29        | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 28        | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 27        | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 26        | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 25        | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 22        | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 19        | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 16        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 16        | 0.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 15        | 0.51%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 15        | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 15        | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 0.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 14        | 0.48%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 14        | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 13        | 0.45%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.45%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 13        | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 12        | 0.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 12        | 0.41%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 12        | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 12        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1100      | 46.3%   |
| DDR3    | 864       | 36.36%  |
| DDR2    | 119       | 5.01%   |
| LPDDR4  | 101       | 4.25%   |
| LPDDR3  | 89        | 3.75%   |
| SDRAM   | 49        | 2.06%   |
| Unknown | 21        | 0.88%   |
| DDR     | 12        | 0.51%   |
| DDR5    | 9         | 0.38%   |
| LPDDR5  | 7         | 0.29%   |
| DRAM    | 5         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2139      | 90.1%   |
| Row Of Chips | 208       | 8.76%   |
| Chip         | 11        | 0.46%   |
| DIMM         | 10        | 0.42%   |
| Unknown      | 6         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 898       | 35.13%  |
| 4096  | 866       | 33.88%  |
| 2048  | 336       | 13.15%  |
| 16384 | 319       | 12.48%  |
| 1024  | 82        | 3.21%   |
| 32768 | 46        | 1.8%    |
| 512   | 8         | 0.31%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 615       | 24.11%  |
| 2667    | 541       | 21.21%  |
| 3200    | 394       | 15.44%  |
| 2400    | 175       | 6.86%   |
| 2133    | 140       | 5.49%   |
| 1334    | 138       | 5.41%   |
| 1333    | 90        | 3.53%   |
| 667     | 68        | 2.67%   |
| 4267    | 50        | 1.96%   |
| Unknown | 44        | 1.72%   |
| 3266    | 41        | 1.61%   |
| 1067    | 41        | 1.61%   |
| 1867    | 36        | 1.41%   |
| 800     | 29        | 1.14%   |
| 4199    | 24        | 0.94%   |
| 2048    | 21        | 0.82%   |
| 1066    | 19        | 0.74%   |
| 4800    | 14        | 0.55%   |
| 533     | 12        | 0.47%   |
| 975     | 11        | 0.43%   |
| 4266    | 9         | 0.35%   |
| 8400    | 8         | 0.31%   |
| 6400    | 8         | 0.31%   |
| 2933    | 4         | 0.16%   |
| 1866    | 4         | 0.16%   |
| 3000    | 3         | 0.12%   |
| 333     | 3         | 0.12%   |
| 1777    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 3733    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 266     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 37.84%  |
| Canon               | 9         | 24.32%  |
| Seiko Epson         | 4         | 10.81%  |
| Samsung Electronics | 4         | 10.81%  |
| Brother Industries  | 3         | 8.11%   |
| Xiaomi              | 1         | 2.7%    |
| STMicroelectronics  | 1         | 2.7%    |
| QinHeng Electronics | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 10.81%  |
| HP DeskJet 3630 series                                    | 3         | 8.11%   |
| Seiko Epson WF-2830 Series                                | 2         | 5.41%   |
| Canon PIXMA MG3600 Series                                 | 2         | 5.41%   |
| Canon PIXMA MG2500 Series                                 | 2         | 5.41%   |
| Xiaomi MiMouse 2                                          | 1         | 2.7%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.7%    |
| Seiko Epson XP-255 257 Series                             | 1         | 2.7%    |
| Seiko Epson XP-2150 Series                                | 1         | 2.7%    |
| Samsung SCX-3200 Series                                   | 1         | 2.7%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.7%    |
| Samsung M2070 Series                                      | 1         | 2.7%    |
| Samsung M2020 Series                                      | 1         | 2.7%    |
| QinHeng CH340S                                            | 1         | 2.7%    |
| HP Photosmart B010 series                                 | 1         | 2.7%    |
| HP OfficeJet Pro 69                                       | 1         | 2.7%    |
| HP OfficeJet 3830 series                                  | 1         | 2.7%    |
| HP ENVY 5540 series                                       | 1         | 2.7%    |
| HP ENVY 4500 series                                       | 1         | 2.7%    |
| HP Deskjet F4500 series                                   | 1         | 2.7%    |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2.7%    |
| Canon TS6100 series                                       | 1         | 2.7%    |
| Canon PIXMA MP495                                         | 1         | 2.7%    |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.7%    |
| Canon PIXMA MG3500 Series                                 | 1         | 2.7%    |
| Canon MG2100 series                                       | 1         | 2.7%    |
| Brother MFC-L2710DW series                                | 1         | 2.7%    |
| Brother MFC-1810                                          | 1         | 2.7%    |
| Brother DCP-L3550CDW                                      | 1         | 2.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 50%     |
| Seiko Epson     | 4         | 40%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 2         | 20%     |
| Seiko Epson Scanner                           | 1         | 10%     |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 10%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 10%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 10%     |
| HP ScanJet 3570c                              | 1         | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 10%     |
| Canon CanoScan N650U/N656U                    | 1         | 10%     |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 837       | 24.76%  |
| IMC Networks                           | 407       | 12.04%  |
| Microdia                               | 336       | 9.94%   |
| Realtek Semiconductor                  | 309       | 9.14%   |
| Acer                                   | 297       | 8.79%   |
| Sunplus Innovation Technology          | 205       | 6.07%   |
| Suyin                                  | 147       | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 144       | 4.26%   |
| Quanta                                 | 109       | 3.22%   |
| Lite-On Technology                     | 99        | 2.93%   |
| Apple                                  | 78        | 2.31%   |
| Syntek                                 | 58        | 1.72%   |
| Alcor Micro                            | 46        | 1.36%   |
| Silicon Motion                         | 40        | 1.18%   |
| Ricoh                                  | 38        | 1.12%   |
| Logitech                               | 33        | 0.98%   |
| Luxvisions Innotech Limited            | 30        | 0.89%   |
| Samsung Electronics                    | 22        | 0.65%   |
| Lenovo                                 | 19        | 0.56%   |
| Primax Electronics                     | 17        | 0.5%    |
| Importek                               | 13        | 0.38%   |
| DigiTech                               | 12        | 0.36%   |
| Z-Star Microelectronics                | 11        | 0.33%   |
| ALi                                    | 9         | 0.27%   |
| GEMBIRD                                | 7         | 0.21%   |
| OmniVision Technologies                | 6         | 0.18%   |
| Sonix Technology                       | 4         | 0.12%   |
| Pixart Imaging                         | 3         | 0.09%   |
| Intel                                  | 3         | 0.09%   |
| Y Media                                | 2         | 0.06%   |
| Sunplus Technology                     | 2         | 0.06%   |
| Novatek Microelectronics               | 2         | 0.06%   |
| Microsoft                              | 2         | 0.06%   |
| Jieli Technology                       | 2         | 0.06%   |
| icSpring                               | 2         | 0.06%   |
| Guillemot                              | 2         | 0.06%   |
| Generalplus Technology                 | 2         | 0.06%   |
| Denron                                 | 2         | 0.06%   |
| ARC International                      | 2         | 0.06%   |
| 2M UVC CAMERA                          | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 186       | 5.48%   |
| Realtek Integrated_Webcam_HD             | 135       | 3.98%   |
| Chicony Integrated Camera                | 126       | 3.71%   |
| IMC Networks USB2.0 HD UVC WebCam        | 92        | 2.71%   |
| Chicony HD WebCam                        | 89        | 2.62%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 76        | 2.24%   |
| IMC Networks Integrated Camera           | 71        | 2.09%   |
| Acer Integrated Camera                   | 62        | 1.83%   |
| Sunplus Integrated_Webcam_HD             | 51        | 1.5%    |
| Acer HD Webcam                           | 44        | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam            | 40        | 1.18%   |
| Realtek USB Camera                       | 39        | 1.15%   |
| Chicony USB2.0 Camera                    | 38        | 1.12%   |
| Chicony USB2.0 HD UVC WebCam             | 37        | 1.09%   |
| Chicony TOSHIBA Web Camera - HD          | 34        | 1%      |
| Acer BisonCam,NB Pro                     | 34        | 1%      |
| Microdia Integrated Webcam               | 33        | 0.97%   |
| Chicony HP HD Webcam                     | 31        | 0.91%   |
| Sunplus ASUS USB2.0 Webcam               | 30        | 0.88%   |
| Chicony USB 2.0 Camera                   | 30        | 0.88%   |
| Lite-On Integrated Camera                | 29        | 0.85%   |
| Chicony HP HD Camera                     | 29        | 0.85%   |
| Realtek USB2.0 HD UVC WebCam             | 28        | 0.82%   |
| Chicony HP Truevision HD                 | 28        | 0.82%   |
| Acer BisonCam, NB Pro                    | 28        | 0.82%   |
| Apple Built-in iSight                    | 27        | 0.8%    |
| Apple iPhone5/5C/5S/6                    | 26        | 0.77%   |
| Acer Lenovo EasyCamera                   | 25        | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 24        | 0.71%   |
| IMC Networks UVC VGA Webcam              | 24        | 0.71%   |
| Syntek Integrated Camera                 | 23        | 0.68%   |
| Chicony VGA Webcam                       | 23        | 0.68%   |
| Samsung Galaxy A5 (MTP)                  | 22        | 0.65%   |
| Chicony HP TrueVision HD Camera          | 21        | 0.62%   |
| Sunplus HD WebCam                        | 20        | 0.59%   |
| Lite-On HP HD Webcam                     | 19        | 0.56%   |
| IMC Networks ov9734_azurewave_camera     | 19        | 0.56%   |
| Quanta HP HD Camera                      | 18        | 0.53%   |
| Chicony EasyCamera                       | 18        | 0.53%   |
| Realtek USB2.0 VGA UVC WebCam            | 17        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 232       | 37.24%  |
| Synaptics                  | 130       | 20.87%  |
| Shenzhen Goodix Technology | 117       | 18.78%  |
| AuthenTec                  | 46        | 7.38%   |
| Elan Microelectronics      | 34        | 5.46%   |
| LighTuning Technology      | 33        | 5.3%    |
| Upek                       | 23        | 3.69%   |
| STMicroelectronics         | 7         | 1.12%   |
| Focal-systems.Corp         | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 66        | 10.59%  |
| Shenzhen Goodix  Fingerprint Device                                        | 56        | 8.99%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 8.51%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 5.62%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 30        | 4.82%   |
| Unknown                                                                    | 30        | 4.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 25        | 4.01%   |
| Elan ELAN:Fingerprint                                                      | 25        | 4.01%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.37%   |
| Validity Sensors VFS491                                                    | 20        | 3.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 3.05%   |
| AuthenTec AES2810                                                          | 18        | 2.89%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 2.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 2.41%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 2.41%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.93%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 1.61%   |
| AuthenTec AES1600                                                          | 10        | 1.61%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.44%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.28%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.28%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.8%    |
| Synaptics WBDI Device                                                      | 5         | 0.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.8%    |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.64%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.64%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.48%   |
| Synaptics  WBDI                                                            | 3         | 0.48%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.48%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.32%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.16%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 178       | 56.69%  |
| Alcor Micro               | 65        | 20.7%   |
| O2 Micro                  | 30        | 9.55%   |
| Upek                      | 14        | 4.46%   |
| Lenovo                    | 11        | 3.5%    |
| Hewlett-Packard           | 5         | 1.59%   |
| Gemalto (was Gemplus)     | 4         | 1.27%   |
| Yubico.com                | 2         | 0.64%   |
| Clay Logic                | 2         | 0.64%   |
| SpringCard                | 1         | 0.32%   |
| OmniKey                   | 1         | 0.32%   |
| Aladdin Knowledge Systems | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 65        | 20.7%   |
| Broadcom BCM5880 Secure Applications Processor                               | 62        | 19.75%  |
| Broadcom 58200                                                               | 48        | 15.29%  |
| Broadcom 5880                                                                | 40        | 12.74%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 27        | 8.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 8.6%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 4.46%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 3.5%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.59%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.96%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.64%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.64%   |
| SpringCard Two                                                               | 1         | 0.32%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.32%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.32%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.32%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2434      | 62.46%  |
| 1     | 1173      | 30.1%   |
| 2     | 228       | 5.85%   |
| 3     | 45        | 1.15%   |
| 4     | 6         | 0.15%   |
| 5     | 5         | 0.13%   |
| 7     | 3         | 0.08%   |
| 6     | 3         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 615       | 34.69%  |
| Graphics card            | 350       | 19.74%  |
| Chipcard                 | 293       | 16.53%  |
| Net/wireless             | 160       | 9.02%   |
| Multimedia controller    | 72        | 4.06%   |
| Camera                   | 58        | 3.27%   |
| Bluetooth                | 56        | 3.16%   |
| Storage                  | 44        | 2.48%   |
| Communication controller | 35        | 1.97%   |
| Card reader              | 27        | 1.52%   |
| Sound                    | 19        | 1.07%   |
| Modem                    | 15        | 0.85%   |
| Net/ethernet             | 13        | 0.73%   |
| Network                  | 5         | 0.28%   |
| Flash memory             | 3         | 0.17%   |
| Unclassified device      | 2         | 0.11%   |
| Wireless                 | 1         | 0.06%   |
| Unassigned class         | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

