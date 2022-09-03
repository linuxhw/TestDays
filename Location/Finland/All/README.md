Linux in Finland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Finland/Desktop/README.md) and [notebooks](/Location/Finland/Notebook/README.md).

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

Total: 1532

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 805A                        | Desktop     | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | Notebook    | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| Acer          | Predator G3620              | Desktop     | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| HP            | Compaq 6735s                | Notebook    | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [7deff7707e](https://linux-hardware.org/?probe=7deff7707e) | Aug 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [5cfcfab468](https://linux-hardware.org/?probe=5cfcfab468) | Aug 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Acer          | Predator PO5-600s V:1.0     | Desktop     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | Notebook    | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| Acer          | Aspire VN7-571G             | Notebook    | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| HP            | 805A                        | Desktop     | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2539e9f908](https://linux-hardware.org/?probe=2539e9f908) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a284074100](https://linux-hardware.org/?probe=a284074100) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [365fe3e266](https://linux-hardware.org/?probe=365fe3e266) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [09cd376e43](https://linux-hardware.org/?probe=09cd376e43) | Aug 02, 2022 |
| HP            | Compaq 2510p                | Notebook    | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [8693dca4f6](https://linux-hardware.org/?probe=8693dca4f6) | Jul 30, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [fa46d23eda](https://linux-hardware.org/?probe=fa46d23eda) | Jul 27, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1578510bc0](https://linux-hardware.org/?probe=1578510bc0) | Jul 25, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | Desktop     | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bc85466c3f](https://linux-hardware.org/?probe=bc85466c3f) | Jul 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [96c65556bb](https://linux-hardware.org/?probe=96c65556bb) | Jul 18, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e540c6e30d](https://linux-hardware.org/?probe=e540c6e30d) | Jul 18, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [34ff1068ca](https://linux-hardware.org/?probe=34ff1068ca) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f4f2c80cdd](https://linux-hardware.org/?probe=f4f2c80cdd) | Jul 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [57517e2dc2](https://linux-hardware.org/?probe=57517e2dc2) | Jul 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3a5fc098c4](https://linux-hardware.org/?probe=3a5fc098c4) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [a93792aef3](https://linux-hardware.org/?probe=a93792aef3) | Jul 07, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f525b5f3b0](https://linux-hardware.org/?probe=f525b5f3b0) | Jul 04, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | Notebook    | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| HP            | 3647h                       | Desktop     | [f59774eab5](https://linux-hardware.org/?probe=f59774eab5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [8ecea7fce7](https://linux-hardware.org/?probe=8ecea7fce7) | Jun 28, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| Medion        | AXA                         | All in one  | [0cbda6d693](https://linux-hardware.org/?probe=0cbda6d693) | Jun 23, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f0d321b741](https://linux-hardware.org/?probe=f0d321b741) | Jun 22, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a69564b477](https://linux-hardware.org/?probe=a69564b477) | Jun 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [139ffc0039](https://linux-hardware.org/?probe=139ffc0039) | Jun 16, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f339cce523](https://linux-hardware.org/?probe=f339cce523) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [d4bfcc2d6d](https://linux-hardware.org/?probe=d4bfcc2d6d) | Jun 12, 2022 |
| Dell          | 0RW203                      | Desktop     | [d53558bc85](https://linux-hardware.org/?probe=d53558bc85) | Jun 12, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| HP            | G62                         | Notebook    | [de2464c378](https://linux-hardware.org/?probe=de2464c378) | Jun 08, 2022 |
| HP            | Elite Dragonfly Max Note... | Convertible | [3b16bdeb2c](https://linux-hardware.org/?probe=3b16bdeb2c) | Jun 06, 2022 |
| Supermicro    | X10SBA-LA                   | Desktop     | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [dff99aa7e6](https://linux-hardware.org/?probe=dff99aa7e6) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [48be2e4a99](https://linux-hardware.org/?probe=48be2e4a99) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| Unknown       | Unknown                     | Phone       | [63d3c9a3b6](https://linux-hardware.org/?probe=63d3c9a3b6) | May 28, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Dell          | Latitude 3520               | Notebook    | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [7cbd29cc48](https://linux-hardware.org/?probe=7cbd29cc48) | May 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2f3b6548d0](https://linux-hardware.org/?probe=2f3b6548d0) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [826dfbee64](https://linux-hardware.org/?probe=826dfbee64) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [0065ab0681](https://linux-hardware.org/?probe=0065ab0681) | May 12, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [d94b81d9d3](https://linux-hardware.org/?probe=d94b81d9d3) | May 12, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| HP            | 805F                        | Desktop     | [466bb8cc36](https://linux-hardware.org/?probe=466bb8cc36) | May 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| Acer          | RS780HVF                    | Desktop     | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [df57c0ad60](https://linux-hardware.org/?probe=df57c0ad60) | May 09, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [7e95657ad7](https://linux-hardware.org/?probe=7e95657ad7) | May 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| Acer          | RS780HVF                    | Desktop     | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Acer          | H57M01                      | Desktop     | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Acer          | FX58M                       | Desktop     | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| HP            | 1589                        | Desktop     | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c78066bc19](https://linux-hardware.org/?probe=c78066bc19) | Apr 29, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [2e84d98937](https://linux-hardware.org/?probe=2e84d98937) | Apr 29, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | Notebook    | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [f656f0d16f](https://linux-hardware.org/?probe=f656f0d16f) | Apr 24, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1612f46137](https://linux-hardware.org/?probe=1612f46137) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| Acer          | Aspire 7530G                | Notebook    | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| ASRock        | Z87 Extreme6                | Desktop     | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [5a93c8e68c](https://linux-hardware.org/?probe=5a93c8e68c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | Notebook    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| MSI           | Indio                       | Desktop     | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| HP            | Notebook                    | Notebook    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Acer          | Batman A01                  | Desktop     | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| HP            | 18E7                        | Desktop     | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASRock        | B85M-ITX                    | Desktop     | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Dell          | Latitude 5480               | Notebook    | [2d431aae25](https://linux-hardware.org/?probe=2d431aae25) | Mar 29, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | Notebook    | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ba2686174e](https://linux-hardware.org/?probe=ba2686174e) | Mar 13, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| Acer          | AO725                       | Notebook    | [70febdd28f](https://linux-hardware.org/?probe=70febdd28f) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | Notebook    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| HP            | G62                         | Notebook    | [67bc301ee6](https://linux-hardware.org/?probe=67bc301ee6) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| Acer          | FX58M                       | Desktop     | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [2142681934](https://linux-hardware.org/?probe=2142681934) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2e19b36624](https://linux-hardware.org/?probe=2e19b36624) | Mar 03, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | Notebook    | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0278765ef8](https://linux-hardware.org/?probe=0278765ef8) | Feb 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [0dd55e5b26](https://linux-hardware.org/?probe=0dd55e5b26) | Feb 26, 2022 |
| ABIT          | IP35                        | Desktop     | [278dd592cc](https://linux-hardware.org/?probe=278dd592cc) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [f12d1e47df](https://linux-hardware.org/?probe=f12d1e47df) | Feb 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [5fe85bba2e](https://linux-hardware.org/?probe=5fe85bba2e) | Feb 22, 2022 |
| HP            | G62                         | Notebook    | [337afde8c1](https://linux-hardware.org/?probe=337afde8c1) | Feb 21, 2022 |
| HP            | G62                         | Notebook    | [a175af3dd6](https://linux-hardware.org/?probe=a175af3dd6) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [811ec775f8](https://linux-hardware.org/?probe=811ec775f8) | Feb 19, 2022 |
| powerinter... | Cepter N510-03              | Notebook    | [cd6804144d](https://linux-hardware.org/?probe=cd6804144d) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | Notebook    | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | Notebook    | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| Dell          | Latitude E5420              | Notebook    | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| ASRock        | 890FX Deluxe4               | Desktop     | [33a47b3c4b](https://linux-hardware.org/?probe=33a47b3c4b) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [766e937263](https://linux-hardware.org/?probe=766e937263) | Feb 10, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3d76f83751](https://linux-hardware.org/?probe=3d76f83751) | Feb 10, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [75b31509a3](https://linux-hardware.org/?probe=75b31509a3) | Feb 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [88fdd17fc6](https://linux-hardware.org/?probe=88fdd17fc6) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [22be2d64a2](https://linux-hardware.org/?probe=22be2d64a2) | Feb 06, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e0765c9f5a](https://linux-hardware.org/?probe=e0765c9f5a) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e83deb15fd](https://linux-hardware.org/?probe=e83deb15fd) | Jan 31, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f76e2b6c0f](https://linux-hardware.org/?probe=f76e2b6c0f) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Lenovo        | ThinkPad X390 20Q00057MX    | Notebook    | [326cb714f0](https://linux-hardware.org/?probe=326cb714f0) | Jan 27, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [cf5823e07b](https://linux-hardware.org/?probe=cf5823e07b) | Jan 26, 2022 |
| Packard Be... | IMEDIA S3840                | Desktop     | [eff4bf09ec](https://linux-hardware.org/?probe=eff4bf09ec) | Jan 26, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [63d4ce1086](https://linux-hardware.org/?probe=63d4ce1086) | Jan 23, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [b9d8fc0e46](https://linux-hardware.org/?probe=b9d8fc0e46) | Jan 23, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [88049a6cee](https://linux-hardware.org/?probe=88049a6cee) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [8f7c57b03f](https://linux-hardware.org/?probe=8f7c57b03f) | Jan 18, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [06c4be96aa](https://linux-hardware.org/?probe=06c4be96aa) | Jan 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [39b90ab9c3](https://linux-hardware.org/?probe=39b90ab9c3) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| HP            | 1495                        | Desktop     | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c2406eee73](https://linux-hardware.org/?probe=c2406eee73) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| Toshiba       | Satellite P870              | Notebook    | [e046040d73](https://linux-hardware.org/?probe=e046040d73) | Jan 11, 2022 |
| HP            | Notebook                    | Notebook    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [6291085e58](https://linux-hardware.org/?probe=6291085e58) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| HP            | 3646h                       | Desktop     | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | Desktop     | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [c4ac286105](https://linux-hardware.org/?probe=c4ac286105) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [b2682cb5fe](https://linux-hardware.org/?probe=b2682cb5fe) | Jan 06, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Acer          | WMCP78M                     | Desktop     | [250fa57c5d](https://linux-hardware.org/?probe=250fa57c5d) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 20RA001BMX     | Notebook    | [b34ccf2c06](https://linux-hardware.org/?probe=b34ccf2c06) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [c28c0f7f40](https://linux-hardware.org/?probe=c28c0f7f40) | Jan 04, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [0731f1a6d9](https://linux-hardware.org/?probe=0731f1a6d9) | Jan 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [4ed85a0f7a](https://linux-hardware.org/?probe=4ed85a0f7a) | Dec 30, 2021 |
| HP            | 3397                        | Desktop     | [188bb8c669](https://linux-hardware.org/?probe=188bb8c669) | Dec 28, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [4384deed19](https://linux-hardware.org/?probe=4384deed19) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Dell          | Latitude 5490               | Notebook    | [a9261b4529](https://linux-hardware.org/?probe=a9261b4529) | Dec 16, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0ca333f8b0](https://linux-hardware.org/?probe=0ca333f8b0) | Dec 15, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [002a05b1c7](https://linux-hardware.org/?probe=002a05b1c7) | Dec 14, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [81873c2912](https://linux-hardware.org/?probe=81873c2912) | Dec 14, 2021 |
| Dell          | Precision 7510              | Notebook    | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9b61f8e080](https://linux-hardware.org/?probe=9b61f8e080) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Samsung       | 750XDA                      | Notebook    | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| HP            | 340 G5                      | Notebook    | [8ed2eec9b4](https://linux-hardware.org/?probe=8ed2eec9b4) | Dec 07, 2021 |
| Dell          | Latitude E6400              | Notebook    | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| Lenovo        | ThinkPad W540 20BH002NMS    | Notebook    | [52d66e95f4](https://linux-hardware.org/?probe=52d66e95f4) | Dec 01, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [3284718afd](https://linux-hardware.org/?probe=3284718afd) | Dec 01, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [493153bf7c](https://linux-hardware.org/?probe=493153bf7c) | Nov 30, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [b98f644a91](https://linux-hardware.org/?probe=b98f644a91) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [65d49ae483](https://linux-hardware.org/?probe=65d49ae483) | Nov 26, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Acer          | WMCP78M                     | Desktop     | [5930f530bb](https://linux-hardware.org/?probe=5930f530bb) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| HP            | 3647h                       | Desktop     | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| HP            | 8433 11                     | Desktop     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | Notebook    | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| Google        | Relm                        | Notebook    | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | Desktop     | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e2b68b190](https://linux-hardware.org/?probe=2e2b68b190) | Nov 20, 2021 |
| HP            | Pavilion 17                 | Notebook    | [a633bbd978](https://linux-hardware.org/?probe=a633bbd978) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [646919d578](https://linux-hardware.org/?probe=646919d578) | Nov 20, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [972f96ba1d](https://linux-hardware.org/?probe=972f96ba1d) | Nov 17, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | Notebook    | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Dell          | Latitude 7420               | Notebook    | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [5bed28d52e](https://linux-hardware.org/?probe=5bed28d52e) | Nov 15, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [da8846a5fd](https://linux-hardware.org/?probe=da8846a5fd) | Nov 14, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [d004277425](https://linux-hardware.org/?probe=d004277425) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [438a1236fb](https://linux-hardware.org/?probe=438a1236fb) | Nov 11, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [7a1824b26a](https://linux-hardware.org/?probe=7a1824b26a) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| HP            | 1495                        | Desktop     | [d66a2a8cf5](https://linux-hardware.org/?probe=d66a2a8cf5) | Nov 10, 2021 |
| Lenovo        | Kabini CRB 31900003 STD     | Desktop     | [4d94fd8ba6](https://linux-hardware.org/?probe=4d94fd8ba6) | Nov 10, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b98565dc8e](https://linux-hardware.org/?probe=b98565dc8e) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [224597688f](https://linux-hardware.org/?probe=224597688f) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [0aeea3a3c9](https://linux-hardware.org/?probe=0aeea3a3c9) | Nov 09, 2021 |
| HP            | 1495                        | Desktop     | [22bbd228cb](https://linux-hardware.org/?probe=22bbd228cb) | Nov 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [536b4200f8](https://linux-hardware.org/?probe=536b4200f8) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [33a5ffbf9a](https://linux-hardware.org/?probe=33a5ffbf9a) | Nov 07, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [748d879ed2](https://linux-hardware.org/?probe=748d879ed2) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [a40335233e](https://linux-hardware.org/?probe=a40335233e) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ABIT          | AI7                         | Desktop     | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [ae1af68eae](https://linux-hardware.org/?probe=ae1af68eae) | Nov 03, 2021 |
| Samsung       | R530/R730                   | Notebook    | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [e10152abc8](https://linux-hardware.org/?probe=e10152abc8) | Oct 25, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [0f6daccd63](https://linux-hardware.org/?probe=0f6daccd63) | Oct 25, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [e74dc83f0a](https://linux-hardware.org/?probe=e74dc83f0a) | Oct 24, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [477512ba5c](https://linux-hardware.org/?probe=477512ba5c) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [c487ba6138](https://linux-hardware.org/?probe=c487ba6138) | Oct 22, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| HP            | Compaq 6735s                | Notebook    | [25c73d7c4d](https://linux-hardware.org/?probe=25c73d7c4d) | Oct 20, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d89008ef64](https://linux-hardware.org/?probe=d89008ef64) | Oct 16, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8961245abb](https://linux-hardware.org/?probe=8961245abb) | Oct 15, 2021 |
| Acer          | Aspire 7530G                | Notebook    | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [5a67ea75fe](https://linux-hardware.org/?probe=5a67ea75fe) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [e8ad89cb87](https://linux-hardware.org/?probe=e8ad89cb87) | Oct 12, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [818fe93a6d](https://linux-hardware.org/?probe=818fe93a6d) | Oct 10, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [319f2002de](https://linux-hardware.org/?probe=319f2002de) | Oct 09, 2021 |
| Dell          | 0YC523                      | Desktop     | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [a9d87f6d4e](https://linux-hardware.org/?probe=a9d87f6d4e) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | Notebook    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [2fe4152b53](https://linux-hardware.org/?probe=2fe4152b53) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [28eb3733ca](https://linux-hardware.org/?probe=28eb3733ca) | Oct 06, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [8028a9757c](https://linux-hardware.org/?probe=8028a9757c) | Oct 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [0c5e4a2345](https://linux-hardware.org/?probe=0c5e4a2345) | Oct 02, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| HP            | 0AACh                       | Desktop     | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8fa77435f7](https://linux-hardware.org/?probe=8fa77435f7) | Sep 29, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [b461764429](https://linux-hardware.org/?probe=b461764429) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [89783ad217](https://linux-hardware.org/?probe=89783ad217) | Sep 24, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [867138c338](https://linux-hardware.org/?probe=867138c338) | Sep 22, 2021 |
| Lenovo        | ThinkPad X230 204016Z1ZS    | Notebook    | [eb1d7abffc](https://linux-hardware.org/?probe=eb1d7abffc) | Sep 21, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [7ded59f42f](https://linux-hardware.org/?probe=7ded59f42f) | Sep 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [506a3682b9](https://linux-hardware.org/?probe=506a3682b9) | Sep 15, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [badf707f13](https://linux-hardware.org/?probe=badf707f13) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c8e465fcb0](https://linux-hardware.org/?probe=c8e465fcb0) | Sep 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [94e64b5b30](https://linux-hardware.org/?probe=94e64b5b30) | Sep 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| Dell          | Latitude 7420               | Notebook    | [225b6a0d52](https://linux-hardware.org/?probe=225b6a0d52) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Dell          | Latitude E6430              | Notebook    | [e02c871576](https://linux-hardware.org/?probe=e02c871576) | Sep 06, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d2627b08e](https://linux-hardware.org/?probe=5d2627b08e) | Sep 06, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| Fujitsu       | LIFEBOOK U9310              | Notebook    | [48113d6636](https://linux-hardware.org/?probe=48113d6636) | Sep 02, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7467c9452c](https://linux-hardware.org/?probe=7467c9452c) | Sep 01, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [08ad3775b8](https://linux-hardware.org/?probe=08ad3775b8) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | Notebook    | [8e46956f05](https://linux-hardware.org/?probe=8e46956f05) | Aug 31, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | Notebook    | [8512904445](https://linux-hardware.org/?probe=8512904445) | Aug 29, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [93e2baa57a](https://linux-hardware.org/?probe=93e2baa57a) | Aug 29, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b8aadba448](https://linux-hardware.org/?probe=b8aadba448) | Aug 28, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [adfa074262](https://linux-hardware.org/?probe=adfa074262) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [f15a7392b9](https://linux-hardware.org/?probe=f15a7392b9) | Aug 27, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [fa40b359a1](https://linux-hardware.org/?probe=fa40b359a1) | Aug 27, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [4198aeb0a0](https://linux-hardware.org/?probe=4198aeb0a0) | Aug 26, 2021 |
| Dell          | Latitude 5480               | Notebook    | [3374e57369](https://linux-hardware.org/?probe=3374e57369) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| HP            | Compaq 8710w (GC124EA#AK... | Notebook    | [d7475c57ca](https://linux-hardware.org/?probe=d7475c57ca) | Aug 24, 2021 |
| HP            | ProBook 6360b               | Notebook    | [f8a9a512b2](https://linux-hardware.org/?probe=f8a9a512b2) | Aug 24, 2021 |
| HP            | ProBook 6360b               | Notebook    | [beb76e16b5](https://linux-hardware.org/?probe=beb76e16b5) | Aug 24, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Latitude 7490               | Notebook    | [b4759deb9a](https://linux-hardware.org/?probe=b4759deb9a) | Aug 21, 2021 |
| Acer          | RS780HVF                    | Desktop     | [f051228785](https://linux-hardware.org/?probe=f051228785) | Aug 21, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [97a8f28916](https://linux-hardware.org/?probe=97a8f28916) | Aug 21, 2021 |
| HP            | 255 G1                      | Notebook    | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [78377f3635](https://linux-hardware.org/?probe=78377f3635) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [e91d03b0c4](https://linux-hardware.org/?probe=e91d03b0c4) | Aug 17, 2021 |
| Dell          | Latitude E6430              | Notebook    | [afe966ff62](https://linux-hardware.org/?probe=afe966ff62) | Aug 17, 2021 |
| Dell          | Latitude E6500              | Notebook    | [a707e64d52](https://linux-hardware.org/?probe=a707e64d52) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| Acer          | RS780HVF                    | Desktop     | [32c3b00b51](https://linux-hardware.org/?probe=32c3b00b51) | Aug 14, 2021 |
| Acer          | RS780HVF                    | Desktop     | [858844ae39](https://linux-hardware.org/?probe=858844ae39) | Aug 14, 2021 |
| Acer          | Predator G3-710             | Desktop     | [bc8ec0cacc](https://linux-hardware.org/?probe=bc8ec0cacc) | Aug 14, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | Notebook    | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [33a532dde2](https://linux-hardware.org/?probe=33a532dde2) | Aug 09, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [8d464633db](https://linux-hardware.org/?probe=8d464633db) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [bd3d1ed844](https://linux-hardware.org/?probe=bd3d1ed844) | Aug 08, 2021 |
| Lenovo        | ThinkPad X270 20HMS70400    | Notebook    | [6b647baf7c](https://linux-hardware.org/?probe=6b647baf7c) | Aug 07, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [ab5514ae70](https://linux-hardware.org/?probe=ab5514ae70) | Aug 06, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [a5d694843c](https://linux-hardware.org/?probe=a5d694843c) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | Notebook    | [0297e70b90](https://linux-hardware.org/?probe=0297e70b90) | Aug 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [ec6b248ebe](https://linux-hardware.org/?probe=ec6b248ebe) | Aug 03, 2021 |
| ASRock        | 939A785GMH/128M             | Desktop     | [fe09c8fdc1](https://linux-hardware.org/?probe=fe09c8fdc1) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AN007FM... | Notebook    | [ba75506849](https://linux-hardware.org/?probe=ba75506849) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d6735c5f18](https://linux-hardware.org/?probe=d6735c5f18) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [734237b1dc](https://linux-hardware.org/?probe=734237b1dc) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9ce0842819](https://linux-hardware.org/?probe=9ce0842819) | Aug 02, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0451bc276f](https://linux-hardware.org/?probe=0451bc276f) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [1b2a02afbe](https://linux-hardware.org/?probe=1b2a02afbe) | Jul 31, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| HP            | 8437                        | Desktop     | [06f61b9a3f](https://linux-hardware.org/?probe=06f61b9a3f) | Jul 27, 2021 |
| HP            | 8437                        | Desktop     | [3e06775292](https://linux-hardware.org/?probe=3e06775292) | Jul 27, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [643094a68a](https://linux-hardware.org/?probe=643094a68a) | Jul 26, 2021 |
| Acer          | AO725                       | Notebook    | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| Sony          | VPCEH3D0E                   | Notebook    | [2d04f2e0e8](https://linux-hardware.org/?probe=2d04f2e0e8) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| HP            | 8437                        | Desktop     | [0764df2f0a](https://linux-hardware.org/?probe=0764df2f0a) | Jul 24, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [2c81844355](https://linux-hardware.org/?probe=2c81844355) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| ASRock        | 939A785GMH/128M             | Desktop     | [f363c1063a](https://linux-hardware.org/?probe=f363c1063a) | Jul 22, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [384c090a20](https://linux-hardware.org/?probe=384c090a20) | Jul 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | Notebook    | [550f9db7cd](https://linux-hardware.org/?probe=550f9db7cd) | Jul 22, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [99b906c497](https://linux-hardware.org/?probe=99b906c497) | Jul 21, 2021 |
| Dell          | 0GH911                      | Desktop     | [2aa93c89cd](https://linux-hardware.org/?probe=2aa93c89cd) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Dell          | 0VHWTR A01                  | Desktop     | [5116710fe0](https://linux-hardware.org/?probe=5116710fe0) | Jul 20, 2021 |
| HP            | 802F                        | Desktop     | [469561ff27](https://linux-hardware.org/?probe=469561ff27) | Jul 20, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [4f9f3cbb83](https://linux-hardware.org/?probe=4f9f3cbb83) | Jul 18, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [e7e7f905c7](https://linux-hardware.org/?probe=e7e7f905c7) | Jul 17, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [40f65831a3](https://linux-hardware.org/?probe=40f65831a3) | Jul 17, 2021 |
| MSI           | GS60 2PC Ghost              | Notebook    | [cf537038dd](https://linux-hardware.org/?probe=cf537038dd) | Jul 17, 2021 |
| Dell          | Latitude E7470              | Notebook    | [8c32d73d55](https://linux-hardware.org/?probe=8c32d73d55) | Jul 16, 2021 |
| Dell          | Latitude E7470              | Notebook    | [22583cadb6](https://linux-hardware.org/?probe=22583cadb6) | Jul 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [532e266dcb](https://linux-hardware.org/?probe=532e266dcb) | Jul 13, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Samsung       | R530/R730                   | Notebook    | [103edb36d2](https://linux-hardware.org/?probe=103edb36d2) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d52de582e8](https://linux-hardware.org/?probe=d52de582e8) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| Dell          | G7 7700                     | Notebook    | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [d5eb8c32fb](https://linux-hardware.org/?probe=d5eb8c32fb) | Jul 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [557af42b3d](https://linux-hardware.org/?probe=557af42b3d) | Jul 03, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [def9f42f6c](https://linux-hardware.org/?probe=def9f42f6c) | Jul 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Dell          | Precision 5540              | Notebook    | [a685a9c5bb](https://linux-hardware.org/?probe=a685a9c5bb) | Jun 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e2743844ad](https://linux-hardware.org/?probe=e2743844ad) | Jun 29, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [2043830384](https://linux-hardware.org/?probe=2043830384) | Jun 26, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39f8c7f885](https://linux-hardware.org/?probe=39f8c7f885) | Jun 26, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [110b313bc0](https://linux-hardware.org/?probe=110b313bc0) | Jun 25, 2021 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [52199864f7](https://linux-hardware.org/?probe=52199864f7) | Jun 24, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7767a1cde7](https://linux-hardware.org/?probe=7767a1cde7) | Jun 23, 2021 |
| Dell          | Precision 5550              | Notebook    | [646d84cc95](https://linux-hardware.org/?probe=646d84cc95) | Jun 23, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [fa3749c0c0](https://linux-hardware.org/?probe=fa3749c0c0) | Jun 22, 2021 |
| IBM           | ThinkPad T43 2668F7G        | Notebook    | [93c8e53b04](https://linux-hardware.org/?probe=93c8e53b04) | Jun 15, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [ce648ba480](https://linux-hardware.org/?probe=ce648ba480) | Jun 12, 2021 |
| Dell          | 0GH911                      | Desktop     | [3d8aec55af](https://linux-hardware.org/?probe=3d8aec55af) | Jun 10, 2021 |
| HP            | Compaq 8510p                | Notebook    | [c371bbdff4](https://linux-hardware.org/?probe=c371bbdff4) | Jun 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [54b62ad499](https://linux-hardware.org/?probe=54b62ad499) | Jun 08, 2021 |
| ASUSTek       | K53U                        | Notebook    | [3acb45024a](https://linux-hardware.org/?probe=3acb45024a) | Jun 08, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e0db4d0875](https://linux-hardware.org/?probe=e0db4d0875) | Jun 08, 2021 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [3764e87d16](https://linux-hardware.org/?probe=3764e87d16) | Jun 07, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [493278d567](https://linux-hardware.org/?probe=493278d567) | Jun 05, 2021 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [49a0eec9f5](https://linux-hardware.org/?probe=49a0eec9f5) | Jun 05, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a750453ba5](https://linux-hardware.org/?probe=a750453ba5) | Jun 04, 2021 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [421fa035ee](https://linux-hardware.org/?probe=421fa035ee) | Jun 03, 2021 |
| Dell          | Latitude E7470              | Notebook    | [6be76778ae](https://linux-hardware.org/?probe=6be76778ae) | Jun 03, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [baad40baaa](https://linux-hardware.org/?probe=baad40baaa) | Jun 01, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [ef97789a6a](https://linux-hardware.org/?probe=ef97789a6a) | May 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a266b8dd81](https://linux-hardware.org/?probe=a266b8dd81) | May 27, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [30e8995988](https://linux-hardware.org/?probe=30e8995988) | May 27, 2021 |
| HP            | Compaq 8510p                | Notebook    | [7e17cf2706](https://linux-hardware.org/?probe=7e17cf2706) | May 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [541b3e9cba](https://linux-hardware.org/?probe=541b3e9cba) | May 25, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [ddfe32e6ab](https://linux-hardware.org/?probe=ddfe32e6ab) | May 25, 2021 |
| Acer          | Aspire 8950G                | Notebook    | [d65fb86955](https://linux-hardware.org/?probe=d65fb86955) | May 22, 2021 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [66c62dc8f8](https://linux-hardware.org/?probe=66c62dc8f8) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1b1a173884](https://linux-hardware.org/?probe=1b1a173884) | May 22, 2021 |
| HP            | 8433 11                     | Desktop     | [8670420e76](https://linux-hardware.org/?probe=8670420e76) | May 21, 2021 |
| HP            | 350 G1                      | Notebook    | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [fba004a752](https://linux-hardware.org/?probe=fba004a752) | May 20, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [fa879ee1d2](https://linux-hardware.org/?probe=fa879ee1d2) | May 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [249ab0aa24](https://linux-hardware.org/?probe=249ab0aa24) | May 19, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [09351c4654](https://linux-hardware.org/?probe=09351c4654) | May 18, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [d125abf69e](https://linux-hardware.org/?probe=d125abf69e) | May 12, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [a981f9a0c5](https://linux-hardware.org/?probe=a981f9a0c5) | May 12, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ab2366fd14](https://linux-hardware.org/?probe=ab2366fd14) | May 11, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [4482a1fb69](https://linux-hardware.org/?probe=4482a1fb69) | May 06, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [3ea8d93c76](https://linux-hardware.org/?probe=3ea8d93c76) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Dell          | Latitude E7270              | Notebook    | [6708f53385](https://linux-hardware.org/?probe=6708f53385) | May 04, 2021 |
| HP            | 3647h                       | Desktop     | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [9482db99b9](https://linux-hardware.org/?probe=9482db99b9) | May 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [ef52974aaf](https://linux-hardware.org/?probe=ef52974aaf) | May 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [1c94c5b005](https://linux-hardware.org/?probe=1c94c5b005) | May 03, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [9eb409c988](https://linux-hardware.org/?probe=9eb409c988) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [fbb37a1ceb](https://linux-hardware.org/?probe=fbb37a1ceb) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [1b4573b9c5](https://linux-hardware.org/?probe=1b4573b9c5) | May 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [4ab0e6b099](https://linux-hardware.org/?probe=4ab0e6b099) | May 01, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [40e07b4dad](https://linux-hardware.org/?probe=40e07b4dad) | Apr 26, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [93eb4a6a39](https://linux-hardware.org/?probe=93eb4a6a39) | Apr 24, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c586a3a771](https://linux-hardware.org/?probe=c586a3a771) | Apr 20, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [7e5ffea0b6](https://linux-hardware.org/?probe=7e5ffea0b6) | Apr 20, 2021 |
| Lenovo        | B70-80 80MR                 | Notebook    | [edef8dfd8b](https://linux-hardware.org/?probe=edef8dfd8b) | Apr 19, 2021 |
| HP            | 1998                        | Desktop     | [9bb6ae0565](https://linux-hardware.org/?probe=9bb6ae0565) | Apr 18, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [6a0c5e5bda](https://linux-hardware.org/?probe=6a0c5e5bda) | Apr 18, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [6ac1485bc6](https://linux-hardware.org/?probe=6ac1485bc6) | Apr 17, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [d01dac7a8f](https://linux-hardware.org/?probe=d01dac7a8f) | Apr 16, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [0558c9e99e](https://linux-hardware.org/?probe=0558c9e99e) | Apr 16, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [7ca0cd3696](https://linux-hardware.org/?probe=7ca0cd3696) | Apr 15, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9776a806ac](https://linux-hardware.org/?probe=9776a806ac) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [597f1536e2](https://linux-hardware.org/?probe=597f1536e2) | Apr 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Pegatron      | APX85-GS                    | Desktop     | [3a6accac1f](https://linux-hardware.org/?probe=3a6accac1f) | Apr 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [12fb9fd662](https://linux-hardware.org/?probe=12fb9fd662) | Apr 12, 2021 |
| ASUSTek       | P5E                         | Desktop     | [8689ac73b3](https://linux-hardware.org/?probe=8689ac73b3) | Apr 11, 2021 |
| Pegatron      | 2A99                        | Desktop     | [07a84a3b4d](https://linux-hardware.org/?probe=07a84a3b4d) | Apr 11, 2021 |
| MSI           | GL62M 7REX                  | Notebook    | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [258fbf86ed](https://linux-hardware.org/?probe=258fbf86ed) | Apr 09, 2021 |
| HP            | 0A00h                       | Desktop     | [144a5f7819](https://linux-hardware.org/?probe=144a5f7819) | Apr 09, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| Pegatron      | 2A72h                       | Desktop     | [e1fff3ade4](https://linux-hardware.org/?probe=e1fff3ade4) | Apr 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [c480530d42](https://linux-hardware.org/?probe=c480530d42) | Apr 07, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ecae2e7ad8](https://linux-hardware.org/?probe=ecae2e7ad8) | Apr 06, 2021 |
| Samsung       | R530/R730                   | Notebook    | [0085bebd03](https://linux-hardware.org/?probe=0085bebd03) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [e88c887878](https://linux-hardware.org/?probe=e88c887878) | Apr 01, 2021 |
| HP            | EliteBook 755 G2            | Notebook    | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4ac35c901a](https://linux-hardware.org/?probe=4ac35c901a) | Mar 30, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [2838e1ca6c](https://linux-hardware.org/?probe=2838e1ca6c) | Mar 30, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [d8f1bccb78](https://linux-hardware.org/?probe=d8f1bccb78) | Mar 29, 2021 |
| ASRock        | ALiveNF6G-GLAN              | Desktop     | [1f409f9bf1](https://linux-hardware.org/?probe=1f409f9bf1) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | Notebook    | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| HP            | 1589                        | Desktop     | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [54845ca16f](https://linux-hardware.org/?probe=54845ca16f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [04469024ca](https://linux-hardware.org/?probe=04469024ca) | Mar 27, 2021 |
| HP            | 8054                        | Desktop     | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | Desktop     | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [1f11381bfb](https://linux-hardware.org/?probe=1f11381bfb) | Mar 27, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [c412261d89](https://linux-hardware.org/?probe=c412261d89) | Mar 26, 2021 |
| HP            | ZBook 15 G4                 | Notebook    | [4d3778017f](https://linux-hardware.org/?probe=4d3778017f) | Mar 25, 2021 |
| Samsung       | SF311/SF411/SF511           | Notebook    | [fb1261d331](https://linux-hardware.org/?probe=fb1261d331) | Mar 25, 2021 |
| HP            | 802F                        | Desktop     | [ae40d5cbc9](https://linux-hardware.org/?probe=ae40d5cbc9) | Mar 24, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [ccb057337e](https://linux-hardware.org/?probe=ccb057337e) | Mar 23, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [91409f3c71](https://linux-hardware.org/?probe=91409f3c71) | Mar 23, 2021 |
| Shuttle       | FZ77                        | Desktop     | [ca3dfc266d](https://linux-hardware.org/?probe=ca3dfc266d) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0debcb68ae](https://linux-hardware.org/?probe=0debcb68ae) | Mar 18, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [9af2b46c0a](https://linux-hardware.org/?probe=9af2b46c0a) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [72fc5ffa15](https://linux-hardware.org/?probe=72fc5ffa15) | Mar 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [3c98763834](https://linux-hardware.org/?probe=3c98763834) | Mar 17, 2021 |
| HP            | 1495                        | Desktop     | [23947d4a1e](https://linux-hardware.org/?probe=23947d4a1e) | Mar 17, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [48f8273cdb](https://linux-hardware.org/?probe=48f8273cdb) | Mar 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e9c99960d1](https://linux-hardware.org/?probe=e9c99960d1) | Mar 16, 2021 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [11caeb50ac](https://linux-hardware.org/?probe=11caeb50ac) | Mar 16, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| Acer          | Aspire C24-865              | All in one  | [6dc98b8074](https://linux-hardware.org/?probe=6dc98b8074) | Mar 16, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [2cbefa6c90](https://linux-hardware.org/?probe=2cbefa6c90) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ad7470fc89](https://linux-hardware.org/?probe=ad7470fc89) | Mar 15, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [2417d2d1b5](https://linux-hardware.org/?probe=2417d2d1b5) | Mar 14, 2021 |
| MSI           | H81M-P33                    | Desktop     | [9487818af0](https://linux-hardware.org/?probe=9487818af0) | Mar 13, 2021 |
| HP            | 859C                        | Desktop     | [6434de9da7](https://linux-hardware.org/?probe=6434de9da7) | Mar 13, 2021 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [feedeb2b69](https://linux-hardware.org/?probe=feedeb2b69) | Mar 12, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c6866f0d34](https://linux-hardware.org/?probe=c6866f0d34) | Mar 10, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [112bdb4e2a](https://linux-hardware.org/?probe=112bdb4e2a) | Mar 09, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [e83e8ffa64](https://linux-hardware.org/?probe=e83e8ffa64) | Mar 08, 2021 |
| Lenovo        | ThinkPad T450 20BV001YMS    | Notebook    | [57449243ca](https://linux-hardware.org/?probe=57449243ca) | Mar 07, 2021 |
| Gigabyte      | MZ31-AR0-00 01010101        | Server      | [6d486a7ee9](https://linux-hardware.org/?probe=6d486a7ee9) | Mar 05, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [ee5505ce8e](https://linux-hardware.org/?probe=ee5505ce8e) | Mar 05, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [c4548cb133](https://linux-hardware.org/?probe=c4548cb133) | Mar 04, 2021 |
| ASUSTek       | P5E                         | Desktop     | [adac4a8f70](https://linux-hardware.org/?probe=adac4a8f70) | Mar 04, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [857a1c6e52](https://linux-hardware.org/?probe=857a1c6e52) | Mar 04, 2021 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [1af2ede26c](https://linux-hardware.org/?probe=1af2ede26c) | Mar 03, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [3e423c7d87](https://linux-hardware.org/?probe=3e423c7d87) | Mar 03, 2021 |
| ASUSTek       | UX32A                       | Notebook    | [7debc0a27d](https://linux-hardware.org/?probe=7debc0a27d) | Mar 02, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [8b50e7792e](https://linux-hardware.org/?probe=8b50e7792e) | Mar 02, 2021 |
| Gigabyte      | Z490 VISION D               | Desktop     | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Lenovo        | ThinkPad E580 20KS001RMX    | Notebook    | [5bcb97d47f](https://linux-hardware.org/?probe=5bcb97d47f) | Feb 28, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [1f91d9a631](https://linux-hardware.org/?probe=1f91d9a631) | Feb 27, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [ad443f47c2](https://linux-hardware.org/?probe=ad443f47c2) | Feb 27, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [987d795cb7](https://linux-hardware.org/?probe=987d795cb7) | Feb 27, 2021 |
| ASUSTek       | K54C                        | Notebook    | [467c86ad9a](https://linux-hardware.org/?probe=467c86ad9a) | Feb 26, 2021 |
| Dell          | Latitude E7470              | Notebook    | [93cf5a0e8b](https://linux-hardware.org/?probe=93cf5a0e8b) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| ASUSTek       | K70IO                       | Notebook    | [49623c33e1](https://linux-hardware.org/?probe=49623c33e1) | Feb 25, 2021 |
| HP            | 805A                        | Desktop     | [26d9d2a996](https://linux-hardware.org/?probe=26d9d2a996) | Feb 25, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [cd111b2c04](https://linux-hardware.org/?probe=cd111b2c04) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [762e158923](https://linux-hardware.org/?probe=762e158923) | Feb 25, 2021 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [bcbcbdf158](https://linux-hardware.org/?probe=bcbcbdf158) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5af628a455](https://linux-hardware.org/?probe=5af628a455) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [90fa6e7434](https://linux-hardware.org/?probe=90fa6e7434) | Feb 24, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [601807d0e7](https://linux-hardware.org/?probe=601807d0e7) | Feb 24, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [84ddb6cbec](https://linux-hardware.org/?probe=84ddb6cbec) | Feb 24, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | Notebook    | [8a3e6146db](https://linux-hardware.org/?probe=8a3e6146db) | Feb 23, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [d47c258b89](https://linux-hardware.org/?probe=d47c258b89) | Feb 22, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ccd37902d0](https://linux-hardware.org/?probe=ccd37902d0) | Feb 22, 2021 |
| Dell          | 0YC523                      | Desktop     | [d805d39715](https://linux-hardware.org/?probe=d805d39715) | Feb 22, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [50065d2efb](https://linux-hardware.org/?probe=50065d2efb) | Feb 20, 2021 |
| HP            | Presario CQ56               | Notebook    | [54f5681a51](https://linux-hardware.org/?probe=54f5681a51) | Feb 20, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [c116602ad6](https://linux-hardware.org/?probe=c116602ad6) | Feb 18, 2021 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [b1e9a3d14d](https://linux-hardware.org/?probe=b1e9a3d14d) | Feb 18, 2021 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d90fd08234](https://linux-hardware.org/?probe=d90fd08234) | Feb 17, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [544e6bde0b](https://linux-hardware.org/?probe=544e6bde0b) | Feb 17, 2021 |
| ECS           | Nettle3                     | Desktop     | [fb2a315c43](https://linux-hardware.org/?probe=fb2a315c43) | Feb 16, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [24fb34852c](https://linux-hardware.org/?probe=24fb34852c) | Feb 16, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [d91ab98cb0](https://linux-hardware.org/?probe=d91ab98cb0) | Feb 16, 2021 |
| Dell          | 060K5C A04                  | Server      | [33fde2b5fb](https://linux-hardware.org/?probe=33fde2b5fb) | Feb 15, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [33e13fb990](https://linux-hardware.org/?probe=33e13fb990) | Feb 14, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [ce117380dd](https://linux-hardware.org/?probe=ce117380dd) | Feb 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [573a6ae3c7](https://linux-hardware.org/?probe=573a6ae3c7) | Feb 14, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [2941ebcde6](https://linux-hardware.org/?probe=2941ebcde6) | Feb 13, 2021 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [21e0385b49](https://linux-hardware.org/?probe=21e0385b49) | Feb 13, 2021 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [9862174836](https://linux-hardware.org/?probe=9862174836) | Feb 13, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [99f3171b76](https://linux-hardware.org/?probe=99f3171b76) | Feb 10, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e052a51f58](https://linux-hardware.org/?probe=e052a51f58) | Feb 10, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [dee973015c](https://linux-hardware.org/?probe=dee973015c) | Feb 09, 2021 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c0ada2d30c](https://linux-hardware.org/?probe=c0ada2d30c) | Feb 08, 2021 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [71a56734c1](https://linux-hardware.org/?probe=71a56734c1) | Feb 07, 2021 |
| Dell          | Latitude E5470              | Notebook    | [562dbbdcdd](https://linux-hardware.org/?probe=562dbbdcdd) | Feb 07, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [389456d6b7](https://linux-hardware.org/?probe=389456d6b7) | Feb 06, 2021 |
| Acer          | TravelMate 5744             | Notebook    | [78690829c5](https://linux-hardware.org/?probe=78690829c5) | Feb 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [8370d569ed](https://linux-hardware.org/?probe=8370d569ed) | Feb 06, 2021 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [3e78bc9f2c](https://linux-hardware.org/?probe=3e78bc9f2c) | Feb 06, 2021 |
| Dell          | Precision 3520              | Notebook    | [1e72fdbddc](https://linux-hardware.org/?probe=1e72fdbddc) | Feb 05, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [95af098c68](https://linux-hardware.org/?probe=95af098c68) | Feb 05, 2021 |
| HP            | 0A64h                       | Desktop     | [6b5e34333d](https://linux-hardware.org/?probe=6b5e34333d) | Feb 04, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [e5ac3cd7e2](https://linux-hardware.org/?probe=e5ac3cd7e2) | Feb 04, 2021 |
| Dell          | Precision 3520              | Notebook    | [fb3da7ea03](https://linux-hardware.org/?probe=fb3da7ea03) | Feb 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [47d61a08a0](https://linux-hardware.org/?probe=47d61a08a0) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | Desktop     | [e546964d97](https://linux-hardware.org/?probe=e546964d97) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | Desktop     | [80124b02cf](https://linux-hardware.org/?probe=80124b02cf) | Jan 31, 2021 |
| Samsung       | R530/R730                   | Notebook    | [9b9a4ce82c](https://linux-hardware.org/?probe=9b9a4ce82c) | Jan 31, 2021 |
| ASUSTek       | K73TA                       | Notebook    | [2b15e899ed](https://linux-hardware.org/?probe=2b15e899ed) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [20789a4459](https://linux-hardware.org/?probe=20789a4459) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [c0c66476fe](https://linux-hardware.org/?probe=c0c66476fe) | Jan 30, 2021 |
| ASUSTek       | K73TA                       | Notebook    | [0e4b16a1c5](https://linux-hardware.org/?probe=0e4b16a1c5) | Jan 30, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | Desktop     | [ef58793cd1](https://linux-hardware.org/?probe=ef58793cd1) | Jan 29, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3d1daadbf9](https://linux-hardware.org/?probe=3d1daadbf9) | Jan 28, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [897d7d00d7](https://linux-hardware.org/?probe=897d7d00d7) | Jan 27, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [591c655546](https://linux-hardware.org/?probe=591c655546) | Jan 27, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [10f4ad2179](https://linux-hardware.org/?probe=10f4ad2179) | Jan 27, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [bc43832b9f](https://linux-hardware.org/?probe=bc43832b9f) | Jan 27, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [2d3b61aa15](https://linux-hardware.org/?probe=2d3b61aa15) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [07c16b45cb](https://linux-hardware.org/?probe=07c16b45cb) | Jan 26, 2021 |
| Lenovo        | ThinkPad T430 2349W2P       | Notebook    | [58c2f66dd6](https://linux-hardware.org/?probe=58c2f66dd6) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [0903507e18](https://linux-hardware.org/?probe=0903507e18) | Jan 25, 2021 |
| Acer          | Extensa 5220                | Notebook    | [5d121bc112](https://linux-hardware.org/?probe=5d121bc112) | Jan 25, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [aaedd808e4](https://linux-hardware.org/?probe=aaedd808e4) | Jan 25, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [e6dcbd8319](https://linux-hardware.org/?probe=e6dcbd8319) | Jan 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [7718bb2939](https://linux-hardware.org/?probe=7718bb2939) | Jan 24, 2021 |
| Acer          | Extensa 5220                | Notebook    | [138ec8e43b](https://linux-hardware.org/?probe=138ec8e43b) | Jan 24, 2021 |
| AOpen         | D1007 0BB4                  | Desktop     | [8e09b52f79](https://linux-hardware.org/?probe=8e09b52f79) | Jan 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c50f23fd8b](https://linux-hardware.org/?probe=c50f23fd8b) | Jan 23, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [6a6277a771](https://linux-hardware.org/?probe=6a6277a771) | Jan 22, 2021 |
| Dell          | Latitude 7400               | Notebook    | [0ecb2cacfe](https://linux-hardware.org/?probe=0ecb2cacfe) | Jan 22, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [40e24ed53c](https://linux-hardware.org/?probe=40e24ed53c) | Jan 21, 2021 |
| AOpen         | D1007 0BB4                  | Desktop     | [73d0723981](https://linux-hardware.org/?probe=73d0723981) | Jan 21, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [40dbe0488c](https://linux-hardware.org/?probe=40dbe0488c) | Jan 21, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d4d4c84bc5](https://linux-hardware.org/?probe=d4d4c84bc5) | Jan 19, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [d442be2460](https://linux-hardware.org/?probe=d442be2460) | Jan 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [3d3987411f](https://linux-hardware.org/?probe=3d3987411f) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| HP            | EliteBook 1040 G4           | Notebook    | [b7ba6238f6](https://linux-hardware.org/?probe=b7ba6238f6) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [5d2f2486eb](https://linux-hardware.org/?probe=5d2f2486eb) | Jan 17, 2021 |
| Lenovo        | ThinkPad T420 4236WUL       | Notebook    | [7fcf14c600](https://linux-hardware.org/?probe=7fcf14c600) | Jan 16, 2021 |
| HP            | 844C                        | Desktop     | [f9e65434d6](https://linux-hardware.org/?probe=f9e65434d6) | Jan 16, 2021 |
| Dell          | Latitude 5480               | Notebook    | [de414e3763](https://linux-hardware.org/?probe=de414e3763) | Jan 16, 2021 |
| Dell          | Vostro 5581                 | Notebook    | [b706435c71](https://linux-hardware.org/?probe=b706435c71) | Jan 15, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e5edf7f67](https://linux-hardware.org/?probe=0e5edf7f67) | Jan 14, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4d2826d61b](https://linux-hardware.org/?probe=4d2826d61b) | Jan 13, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [47744c734e](https://linux-hardware.org/?probe=47744c734e) | Jan 13, 2021 |
| Dell          | 0Y958C A00                  | Desktop     | [6a52898067](https://linux-hardware.org/?probe=6a52898067) | Jan 12, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4b8c49c0dd](https://linux-hardware.org/?probe=4b8c49c0dd) | Jan 10, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [f234ba69b3](https://linux-hardware.org/?probe=f234ba69b3) | Jan 09, 2021 |
| Dell          | Latitude 5410               | Notebook    | [dcbd8fa748](https://linux-hardware.org/?probe=dcbd8fa748) | Jan 09, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [9dafe213ae](https://linux-hardware.org/?probe=9dafe213ae) | Jan 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b36e938e43](https://linux-hardware.org/?probe=b36e938e43) | Jan 05, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [750bd00cb1](https://linux-hardware.org/?probe=750bd00cb1) | Jan 05, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ed6d998571](https://linux-hardware.org/?probe=ed6d998571) | Jan 04, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [48b31af6f7](https://linux-hardware.org/?probe=48b31af6f7) | Jan 04, 2021 |
| Dell          | 0YC523                      | Desktop     | [ef04db7b3d](https://linux-hardware.org/?probe=ef04db7b3d) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | Desktop     | [fde14ce5dd](https://linux-hardware.org/?probe=fde14ce5dd) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | Desktop     | [f120a3b7a1](https://linux-hardware.org/?probe=f120a3b7a1) | Jan 04, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f254fc1794](https://linux-hardware.org/?probe=f254fc1794) | Dec 31, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [aa039f37b7](https://linux-hardware.org/?probe=aa039f37b7) | Dec 30, 2020 |
| Packard Be... | RS740                       | Desktop     | [5ce58f1cfb](https://linux-hardware.org/?probe=5ce58f1cfb) | Dec 30, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [f6f6ae0026](https://linux-hardware.org/?probe=f6f6ae0026) | Dec 29, 2020 |
| Lenovo        | ThinkPad W510 431924G       | Notebook    | [e5b63a5115](https://linux-hardware.org/?probe=e5b63a5115) | Dec 29, 2020 |
| MSI           | B360M MORTAR                | Desktop     | [96a4f4f86f](https://linux-hardware.org/?probe=96a4f4f86f) | Dec 29, 2020 |
| MSI           | B360M MORTAR                | Desktop     | [770704b41d](https://linux-hardware.org/?probe=770704b41d) | Dec 29, 2020 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a4ad398189](https://linux-hardware.org/?probe=a4ad398189) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [38bf55661f](https://linux-hardware.org/?probe=38bf55661f) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9c1f8e8a57](https://linux-hardware.org/?probe=9c1f8e8a57) | Dec 28, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [7308662eff](https://linux-hardware.org/?probe=7308662eff) | Dec 28, 2020 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Dell          | Latitude E6540              | Notebook    | [f5a9ac4cec](https://linux-hardware.org/?probe=f5a9ac4cec) | Dec 27, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [7db2c6e8e1](https://linux-hardware.org/?probe=7db2c6e8e1) | Dec 27, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [ad51692f6a](https://linux-hardware.org/?probe=ad51692f6a) | Dec 26, 2020 |
| Apple         | MacBook10,1                 | Notebook    | [ab77e34c6e](https://linux-hardware.org/?probe=ab77e34c6e) | Dec 26, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY007... | Notebook    | [92e373f93e](https://linux-hardware.org/?probe=92e373f93e) | Dec 25, 2020 |
| Intel         | D34010WYK H14771-303        | Desktop     | [3a3ce906e2](https://linux-hardware.org/?probe=3a3ce906e2) | Dec 25, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| Dell          | Latitude E6500              | Notebook    | [2745d38e45](https://linux-hardware.org/?probe=2745d38e45) | Dec 22, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [88c214adee](https://linux-hardware.org/?probe=88c214adee) | Dec 22, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [36d7439921](https://linux-hardware.org/?probe=36d7439921) | Dec 20, 2020 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [4b40fc00f6](https://linux-hardware.org/?probe=4b40fc00f6) | Dec 20, 2020 |
| HP            | 1850                        | Desktop     | [a92e22af3c](https://linux-hardware.org/?probe=a92e22af3c) | Dec 19, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [822e9847fc](https://linux-hardware.org/?probe=822e9847fc) | Dec 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [21eff471d2](https://linux-hardware.org/?probe=21eff471d2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [864204221a](https://linux-hardware.org/?probe=864204221a) | Dec 18, 2020 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [2eb3ffc86c](https://linux-hardware.org/?probe=2eb3ffc86c) | Dec 18, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [48b96a1eb2](https://linux-hardware.org/?probe=48b96a1eb2) | Dec 18, 2020 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [5a169ac50d](https://linux-hardware.org/?probe=5a169ac50d) | Dec 18, 2020 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [53bda46668](https://linux-hardware.org/?probe=53bda46668) | Dec 17, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [4e7ff831eb](https://linux-hardware.org/?probe=4e7ff831eb) | Dec 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| ASUSTek       | G751JT                      | Notebook    | [dc87c4f0ee](https://linux-hardware.org/?probe=dc87c4f0ee) | Dec 14, 2020 |
| Lenovo        | ThinkPad X301 4057W3A       | Notebook    | [ca140372c9](https://linux-hardware.org/?probe=ca140372c9) | Dec 13, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [7aea4d859f](https://linux-hardware.org/?probe=7aea4d859f) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| ASUSTek       | H110M-C                     | Desktop     | [cde1c20a36](https://linux-hardware.org/?probe=cde1c20a36) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [16778aa65b](https://linux-hardware.org/?probe=16778aa65b) | Dec 11, 2020 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [79400c58bc](https://linux-hardware.org/?probe=79400c58bc) | Dec 11, 2020 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3167aca45c](https://linux-hardware.org/?probe=3167aca45c) | Dec 10, 2020 |
| Apple         | MacBookAir3,2               | Notebook    | [da600a761d](https://linux-hardware.org/?probe=da600a761d) | Dec 10, 2020 |
| HP            | 2AF3                        | Desktop     | [66cb088231](https://linux-hardware.org/?probe=66cb088231) | Dec 10, 2020 |
| HP            | 2AF3                        | Desktop     | [839c9749a0](https://linux-hardware.org/?probe=839c9749a0) | Dec 10, 2020 |
| ASUSTek       | M4A785T-M                   | Desktop     | [44e7dff3d3](https://linux-hardware.org/?probe=44e7dff3d3) | Dec 10, 2020 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [b9e091029f](https://linux-hardware.org/?probe=b9e091029f) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [84feb3d2f6](https://linux-hardware.org/?probe=84feb3d2f6) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [92ad61acb2](https://linux-hardware.org/?probe=92ad61acb2) | Dec 10, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [37b50cd4d6](https://linux-hardware.org/?probe=37b50cd4d6) | Dec 09, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e4dc25a528](https://linux-hardware.org/?probe=e4dc25a528) | Dec 09, 2020 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [27f9412b8a](https://linux-hardware.org/?probe=27f9412b8a) | Dec 08, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| HP            | Pavilion dv2000 (RN081EA... | Notebook    | [efffe561da](https://linux-hardware.org/?probe=efffe561da) | Dec 07, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [0347053bb5](https://linux-hardware.org/?probe=0347053bb5) | Dec 06, 2020 |
| Unknown       | Unknown                     | Notebook    | [32c7f47910](https://linux-hardware.org/?probe=32c7f47910) | Dec 06, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [8b9e3a522e](https://linux-hardware.org/?probe=8b9e3a522e) | Dec 05, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [19ad2b41f0](https://linux-hardware.org/?probe=19ad2b41f0) | Dec 02, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [5fcb11c8cc](https://linux-hardware.org/?probe=5fcb11c8cc) | Dec 02, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [17a41f14d5](https://linux-hardware.org/?probe=17a41f14d5) | Dec 02, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [c60a02a67d](https://linux-hardware.org/?probe=c60a02a67d) | Dec 01, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [48c0620183](https://linux-hardware.org/?probe=48c0620183) | Dec 01, 2020 |
| Unknown       | Unknown                     | Notebook    | [d3ce335695](https://linux-hardware.org/?probe=d3ce335695) | Dec 01, 2020 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [0d011c1658](https://linux-hardware.org/?probe=0d011c1658) | Nov 30, 2020 |
| Dell          | Vostro 5568                 | Notebook    | [fdfdbf71f3](https://linux-hardware.org/?probe=fdfdbf71f3) | Nov 29, 2020 |
| HP            | 350 G2                      | Notebook    | [c36419b264](https://linux-hardware.org/?probe=c36419b264) | Nov 28, 2020 |
| HP            | 350 G2                      | Notebook    | [e075d2aae9](https://linux-hardware.org/?probe=e075d2aae9) | Nov 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [45e6832bd6](https://linux-hardware.org/?probe=45e6832bd6) | Nov 26, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [cc791659ec](https://linux-hardware.org/?probe=cc791659ec) | Nov 25, 2020 |
| Acer          | Aspire TC-603               | Desktop     | [79605fa1a1](https://linux-hardware.org/?probe=79605fa1a1) | Nov 24, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [97c1978e12](https://linux-hardware.org/?probe=97c1978e12) | Nov 24, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [3b0c917efa](https://linux-hardware.org/?probe=3b0c917efa) | Nov 24, 2020 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [19c11c3ffd](https://linux-hardware.org/?probe=19c11c3ffd) | Nov 24, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [63ba982c79](https://linux-hardware.org/?probe=63ba982c79) | Nov 23, 2020 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [f4e6fa8cea](https://linux-hardware.org/?probe=f4e6fa8cea) | Nov 22, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [a26299780d](https://linux-hardware.org/?probe=a26299780d) | Nov 22, 2020 |
| Lenovo        | 371C SDK0J40700 WIN 3258... | All in one  | [b2ea83f411](https://linux-hardware.org/?probe=b2ea83f411) | Nov 21, 2020 |
| Acer          | NG-VX5-591G-52AT            | Notebook    | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd25862710](https://linux-hardware.org/?probe=cd25862710) | Nov 20, 2020 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [fcfb9d1f17](https://linux-hardware.org/?probe=fcfb9d1f17) | Nov 19, 2020 |
| HP            | 198E                        | Desktop     | [1c885683dc](https://linux-hardware.org/?probe=1c885683dc) | Nov 19, 2020 |
| Lenovo        | ThinkPad X250 20CM004VMS    | Notebook    | [c4b4e94df8](https://linux-hardware.org/?probe=c4b4e94df8) | Nov 18, 2020 |
| Lenovo        | ThinkPad X250 20CM004VMS    | Notebook    | [7b4d4bf272](https://linux-hardware.org/?probe=7b4d4bf272) | Nov 18, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [e7fe53d106](https://linux-hardware.org/?probe=e7fe53d106) | Nov 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2e4848ae3d](https://linux-hardware.org/?probe=2e4848ae3d) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d4b56e4038](https://linux-hardware.org/?probe=d4b56e4038) | Nov 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [16a35d0af3](https://linux-hardware.org/?probe=16a35d0af3) | Nov 14, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [a3a3bd1c26](https://linux-hardware.org/?probe=a3a3bd1c26) | Nov 14, 2020 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [4d72b1a3cc](https://linux-hardware.org/?probe=4d72b1a3cc) | Nov 13, 2020 |
| HP            | 1998                        | Desktop     | [1346951067](https://linux-hardware.org/?probe=1346951067) | Nov 12, 2020 |
| HP            | 1998                        | Desktop     | [dece9d28a6](https://linux-hardware.org/?probe=dece9d28a6) | Nov 12, 2020 |
| HP            | 1998                        | Desktop     | [00c2c438c0](https://linux-hardware.org/?probe=00c2c438c0) | Nov 11, 2020 |
| HP            | 1998                        | Desktop     | [3772df1169](https://linux-hardware.org/?probe=3772df1169) | Nov 11, 2020 |
| HP            | 1998                        | Desktop     | [7c1b7a3a8f](https://linux-hardware.org/?probe=7c1b7a3a8f) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1fe2eda7db](https://linux-hardware.org/?probe=1fe2eda7db) | Nov 11, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [cae149b8a1](https://linux-hardware.org/?probe=cae149b8a1) | Nov 11, 2020 |
| HP            | 1998                        | Desktop     | [e3874c5181](https://linux-hardware.org/?probe=e3874c5181) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [afee9b144d](https://linux-hardware.org/?probe=afee9b144d) | Nov 11, 2020 |
| ASUSTek       | P8H67                       | Desktop     | [58e6f9543d](https://linux-hardware.org/?probe=58e6f9543d) | Nov 10, 2020 |
| ASUSTek       | P8H67                       | Desktop     | [4ac5a781a1](https://linux-hardware.org/?probe=4ac5a781a1) | Nov 10, 2020 |
| Lenovo        | ThinkPad L450 20DSS0VJ00    | Notebook    | [680974d12f](https://linux-hardware.org/?probe=680974d12f) | Nov 09, 2020 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5234189221](https://linux-hardware.org/?probe=5234189221) | Nov 08, 2020 |
| ASUSTek       | E402NA                      | Notebook    | [22f631fe63](https://linux-hardware.org/?probe=22f631fe63) | Nov 08, 2020 |
| ASUSTek       | E402NA                      | Notebook    | [8f7f5ad515](https://linux-hardware.org/?probe=8f7f5ad515) | Nov 08, 2020 |
| HP            | 1495                        | Desktop     | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [9881503776](https://linux-hardware.org/?probe=9881503776) | Nov 07, 2020 |
| HP            | 1495                        | Desktop     | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Lenovo        | ThinkPad X301 4057AL1       | Notebook    | [b52207277d](https://linux-hardware.org/?probe=b52207277d) | Nov 04, 2020 |
| Lenovo        | B50-30 80ES                 | Notebook    | [fd647f5ce9](https://linux-hardware.org/?probe=fd647f5ce9) | Nov 04, 2020 |
| MSI           | Z97M-G43                    | Desktop     | [58cf86104b](https://linux-hardware.org/?probe=58cf86104b) | Nov 03, 2020 |
| MSI           | B450-A PRO MAX              | Desktop     | [b348fef370](https://linux-hardware.org/?probe=b348fef370) | Nov 02, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [0352b345cb](https://linux-hardware.org/?probe=0352b345cb) | Nov 02, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [0745eca4eb](https://linux-hardware.org/?probe=0745eca4eb) | Oct 31, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | Notebook    | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [5e5eff0a90](https://linux-hardware.org/?probe=5e5eff0a90) | Oct 31, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [a4caa7de36](https://linux-hardware.org/?probe=a4caa7de36) | Oct 30, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [80424d0c76](https://linux-hardware.org/?probe=80424d0c76) | Oct 30, 2020 |
| ASRock        | B150M-DVS R2.0              | Desktop     | [fe0d972e21](https://linux-hardware.org/?probe=fe0d972e21) | Oct 29, 2020 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [cd6162b529](https://linux-hardware.org/?probe=cd6162b529) | Oct 29, 2020 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [1bad9ab1dd](https://linux-hardware.org/?probe=1bad9ab1dd) | Oct 29, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [3f18f3f21e](https://linux-hardware.org/?probe=3f18f3f21e) | Oct 28, 2020 |
| ASUSTek       | P6T                         | Desktop     | [3ac523398e](https://linux-hardware.org/?probe=3ac523398e) | Oct 28, 2020 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [16ed8e04d9](https://linux-hardware.org/?probe=16ed8e04d9) | Oct 27, 2020 |
| HP            | Pavilion dv2000 (RN081EA... | Notebook    | [f5ad331463](https://linux-hardware.org/?probe=f5ad331463) | Oct 27, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [0441a81235](https://linux-hardware.org/?probe=0441a81235) | Oct 27, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [cbea8a1179](https://linux-hardware.org/?probe=cbea8a1179) | Oct 26, 2020 |
| ASUSTek       | G751JT                      | Notebook    | [b3f953e40a](https://linux-hardware.org/?probe=b3f953e40a) | Oct 26, 2020 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [311e5dfe10](https://linux-hardware.org/?probe=311e5dfe10) | Oct 25, 2020 |
| Toshiba       | Satellite P50t-B-113        | Notebook    | [6c087ce8ea](https://linux-hardware.org/?probe=6c087ce8ea) | Oct 24, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [0d6f83e3ac](https://linux-hardware.org/?probe=0d6f83e3ac) | Oct 24, 2020 |
| Dell          | Latitude E6400              | Notebook    | [7716757d6d](https://linux-hardware.org/?probe=7716757d6d) | Oct 24, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [92ccdd2770](https://linux-hardware.org/?probe=92ccdd2770) | Oct 24, 2020 |
| Apple         | MacBookPro5,1               | Notebook    | [501b6aa7d4](https://linux-hardware.org/?probe=501b6aa7d4) | Oct 24, 2020 |
| Apple         | MacBookPro5,1               | Notebook    | [2b2e87b194](https://linux-hardware.org/?probe=2b2e87b194) | Oct 24, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3005... | Notebook    | [cbdcb52cbd](https://linux-hardware.org/?probe=cbdcb52cbd) | Oct 23, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [6b9c08674b](https://linux-hardware.org/?probe=6b9c08674b) | Oct 23, 2020 |
| HP            | Notebook                    | Notebook    | [2609b2ee57](https://linux-hardware.org/?probe=2609b2ee57) | Oct 22, 2020 |
| HP            | Notebook                    | Notebook    | [a2dc7c3048](https://linux-hardware.org/?probe=a2dc7c3048) | Oct 22, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [002d0884a9](https://linux-hardware.org/?probe=002d0884a9) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [9d3c97dea2](https://linux-hardware.org/?probe=9d3c97dea2) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | Notebook    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| ASUSTek       | G751JT                      | Notebook    | [5dcc1e72b6](https://linux-hardware.org/?probe=5dcc1e72b6) | Oct 20, 2020 |
| Lenovo        | ThinkPad W510 431967G       | Notebook    | [8471a7bc92](https://linux-hardware.org/?probe=8471a7bc92) | Oct 20, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [4609337b52](https://linux-hardware.org/?probe=4609337b52) | Oct 20, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [aaeb2157bb](https://linux-hardware.org/?probe=aaeb2157bb) | Oct 19, 2020 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [2779444bba](https://linux-hardware.org/?probe=2779444bba) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8892c91b74](https://linux-hardware.org/?probe=8892c91b74) | Oct 19, 2020 |
| ASUSTek       | X705UDR                     | Notebook    | [f2924b4bc4](https://linux-hardware.org/?probe=f2924b4bc4) | Oct 19, 2020 |
| Lenovo        | ThinkPad T420 4236WUL       | Notebook    | [fa50e94e7f](https://linux-hardware.org/?probe=fa50e94e7f) | Oct 18, 2020 |
| ASRock        | J3710-ITX                   | Desktop     | [3f1b610426](https://linux-hardware.org/?probe=3f1b610426) | Oct 18, 2020 |
| Acer          | Aspire XC-605               | Desktop     | [77bfaa4cf4](https://linux-hardware.org/?probe=77bfaa4cf4) | Oct 17, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [ecadf6d10a](https://linux-hardware.org/?probe=ecadf6d10a) | Oct 15, 2020 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [c7d58d3075](https://linux-hardware.org/?probe=c7d58d3075) | Oct 14, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | Notebook    | [64e01927a8](https://linux-hardware.org/?probe=64e01927a8) | Oct 14, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | Notebook    | [5f45e28ad9](https://linux-hardware.org/?probe=5f45e28ad9) | Oct 14, 2020 |
| MSI           | GE66 Raider 10SF            | Notebook    | [b48275b5f0](https://linux-hardware.org/?probe=b48275b5f0) | Oct 14, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | Notebook    | [b47be1c534](https://linux-hardware.org/?probe=b47be1c534) | Oct 13, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [a998d2147e](https://linux-hardware.org/?probe=a998d2147e) | Oct 12, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [a85c07cc92](https://linux-hardware.org/?probe=a85c07cc92) | Oct 12, 2020 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [423121e43d](https://linux-hardware.org/?probe=423121e43d) | Oct 12, 2020 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [15c757dc32](https://linux-hardware.org/?probe=15c757dc32) | Oct 12, 2020 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [e45eae4fd8](https://linux-hardware.org/?probe=e45eae4fd8) | Oct 12, 2020 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [0ed6d6d071](https://linux-hardware.org/?probe=0ed6d6d071) | Oct 11, 2020 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [0cc918a3bd](https://linux-hardware.org/?probe=0cc918a3bd) | Oct 10, 2020 |
| Apple         | MacBookPro5,1               | Notebook    | [cf84111702](https://linux-hardware.org/?probe=cf84111702) | Oct 10, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [676b5ea89a](https://linux-hardware.org/?probe=676b5ea89a) | Oct 10, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [364ee04c6f](https://linux-hardware.org/?probe=364ee04c6f) | Oct 09, 2020 |
| Lenovo        | ThinkPad P52 20M9002HMX     | Notebook    | [a09d23c8fa](https://linux-hardware.org/?probe=a09d23c8fa) | Oct 08, 2020 |
| Acer          | WMCP78M                     | Desktop     | [85191c5734](https://linux-hardware.org/?probe=85191c5734) | Oct 07, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [db2d04c102](https://linux-hardware.org/?probe=db2d04c102) | Oct 07, 2020 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [a6995dcd50](https://linux-hardware.org/?probe=a6995dcd50) | Oct 07, 2020 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [0de2f730e6](https://linux-hardware.org/?probe=0de2f730e6) | Oct 07, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [fba1eca372](https://linux-hardware.org/?probe=fba1eca372) | Oct 05, 2020 |
| ASUSTek       | P5E                         | Desktop     | [6cb501be5f](https://linux-hardware.org/?probe=6cb501be5f) | Oct 05, 2020 |
| Apple         | MacBookPro5,1               | Notebook    | [6e37cbe673](https://linux-hardware.org/?probe=6e37cbe673) | Oct 04, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [ea7f83191d](https://linux-hardware.org/?probe=ea7f83191d) | Oct 04, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [fe2c088ea6](https://linux-hardware.org/?probe=fe2c088ea6) | Oct 03, 2020 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [2221632b84](https://linux-hardware.org/?probe=2221632b84) | Oct 03, 2020 |
| ASUSTek       | GL553VW                     | Notebook    | [5738100990](https://linux-hardware.org/?probe=5738100990) | Oct 03, 2020 |
| Acer          | Aspire 5920G                | Notebook    | [c1f67cd374](https://linux-hardware.org/?probe=c1f67cd374) | Oct 03, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [e4175eb759](https://linux-hardware.org/?probe=e4175eb759) | Oct 03, 2020 |
| Lenovo        | ThinkPad T420 4236WUL       | Notebook    | [88fb1e9546](https://linux-hardware.org/?probe=88fb1e9546) | Oct 03, 2020 |
| HP            | 3397                        | Desktop     | [3d20bbed7a](https://linux-hardware.org/?probe=3d20bbed7a) | Oct 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3c907dd84e](https://linux-hardware.org/?probe=3c907dd84e) | Oct 03, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | Notebook    | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| HP            | Pavilion dv6                | Notebook    | [d3e271df9f](https://linux-hardware.org/?probe=d3e271df9f) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | Notebook    | [9e3c0ac9b5](https://linux-hardware.org/?probe=9e3c0ac9b5) | Oct 02, 2020 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [3770254bcd](https://linux-hardware.org/?probe=3770254bcd) | Oct 02, 2020 |
| HP            | Pavilion dv6                | Notebook    | [49a54805ee](https://linux-hardware.org/?probe=49a54805ee) | Oct 01, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | Notebook    | [5cde334882](https://linux-hardware.org/?probe=5cde334882) | Sep 30, 2020 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [a57ba9c332](https://linux-hardware.org/?probe=a57ba9c332) | Sep 29, 2020 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [ac4a6958b0](https://linux-hardware.org/?probe=ac4a6958b0) | Sep 29, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [4672bd6cf5](https://linux-hardware.org/?probe=4672bd6cf5) | Sep 29, 2020 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [0bd951036d](https://linux-hardware.org/?probe=0bd951036d) | Sep 29, 2020 |
| Lenovo        | ThinkPad X60s 1703Y1F       | Notebook    | [556ce7876f](https://linux-hardware.org/?probe=556ce7876f) | Sep 28, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bfb9828008](https://linux-hardware.org/?probe=bfb9828008) | Sep 28, 2020 |
| MSI           | MS-B090                     | All in one  | [8e135de620](https://linux-hardware.org/?probe=8e135de620) | Sep 28, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | Desktop     | [37b2dd7af9](https://linux-hardware.org/?probe=37b2dd7af9) | Sep 28, 2020 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [495415d7ad](https://linux-hardware.org/?probe=495415d7ad) | Sep 28, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [63e778d2be](https://linux-hardware.org/?probe=63e778d2be) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9edecf1b35](https://linux-hardware.org/?probe=9edecf1b35) | Sep 28, 2020 |
| HP            | Elite Dragonfly             | Notebook    | [96b14d43d8](https://linux-hardware.org/?probe=96b14d43d8) | Sep 28, 2020 |
| Lenovo        | ThinkPad T420 4236WUL       | Notebook    | [d734549ad6](https://linux-hardware.org/?probe=d734549ad6) | Sep 27, 2020 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [f8df50faeb](https://linux-hardware.org/?probe=f8df50faeb) | Sep 27, 2020 |
| ASUSTek       | G751JT                      | Notebook    | [c5e466e43d](https://linux-hardware.org/?probe=c5e466e43d) | Sep 27, 2020 |
| Lenovo        | ThinkPad T500 20828WG       | Notebook    | [ab464ab430](https://linux-hardware.org/?probe=ab464ab430) | Sep 27, 2020 |
| ASUSTek       | GL502VSK                    | Notebook    | [f9028267d2](https://linux-hardware.org/?probe=f9028267d2) | Sep 26, 2020 |
| Lenovo        | ThinkPad A285 20MXS0S000    | Notebook    | [33e9a9ffc6](https://linux-hardware.org/?probe=33e9a9ffc6) | Sep 23, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [646b48e909](https://linux-hardware.org/?probe=646b48e909) | Sep 23, 2020 |
| MSI           | Z77A-G45                    | Desktop     | [28a219f7b8](https://linux-hardware.org/?probe=28a219f7b8) | Sep 23, 2020 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [d804a8a10d](https://linux-hardware.org/?probe=d804a8a10d) | Sep 23, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [2b84d73699](https://linux-hardware.org/?probe=2b84d73699) | Sep 21, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [80161d700f](https://linux-hardware.org/?probe=80161d700f) | Sep 21, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [333f34e356](https://linux-hardware.org/?probe=333f34e356) | Sep 20, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6fe22c6007](https://linux-hardware.org/?probe=6fe22c6007) | Sep 20, 2020 |
| HP            | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [2dcefee7f7](https://linux-hardware.org/?probe=2dcefee7f7) | Sep 18, 2020 |
| Gigabyte      | MZ31-AR0-00 01010101        | Server      | [9f071203a2](https://linux-hardware.org/?probe=9f071203a2) | Sep 18, 2020 |
| ASUSTek       | KRPA-U16 Series             | Desktop     | [588c3eb0ba](https://linux-hardware.org/?probe=588c3eb0ba) | Sep 18, 2020 |
| Gigabyte      | MZ31-AR0-00 01010101        | Server      | [9ae3d51820](https://linux-hardware.org/?probe=9ae3d51820) | Sep 18, 2020 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [f60b4c96e0](https://linux-hardware.org/?probe=f60b4c96e0) | Sep 18, 2020 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [bfc568f6d8](https://linux-hardware.org/?probe=bfc568f6d8) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [16827d150f](https://linux-hardware.org/?probe=16827d150f) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [10a678dfa9](https://linux-hardware.org/?probe=10a678dfa9) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [b1cc6e2b49](https://linux-hardware.org/?probe=b1cc6e2b49) | Sep 18, 2020 |
| Samsung       | R610                        | Notebook    | [db61c853a2](https://linux-hardware.org/?probe=db61c853a2) | Sep 17, 2020 |
| HP            | Pavilion dv6                | Notebook    | [8efc3f4d67](https://linux-hardware.org/?probe=8efc3f4d67) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1abd7894e1](https://linux-hardware.org/?probe=1abd7894e1) | Sep 16, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | Notebook    | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [0cf8ee1ae8](https://linux-hardware.org/?probe=0cf8ee1ae8) | Sep 16, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [9df4d6c8b1](https://linux-hardware.org/?probe=9df4d6c8b1) | Sep 15, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | Notebook    | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| ASUSTek       | G751JT                      | Notebook    | [a3ae63d29b](https://linux-hardware.org/?probe=a3ae63d29b) | Sep 15, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [81cb15062d](https://linux-hardware.org/?probe=81cb15062d) | Sep 14, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [adb3d38645](https://linux-hardware.org/?probe=adb3d38645) | Sep 13, 2020 |
| HP            | Pavilion dv6                | Notebook    | [62de1ab5a4](https://linux-hardware.org/?probe=62de1ab5a4) | Sep 12, 2020 |
| ASRock        | Z87 Extreme6                | Desktop     | [8e26b54de5](https://linux-hardware.org/?probe=8e26b54de5) | Sep 12, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [086d35ff5c](https://linux-hardware.org/?probe=086d35ff5c) | Sep 12, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [66e104dd81](https://linux-hardware.org/?probe=66e104dd81) | Sep 11, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e5fc7b736b](https://linux-hardware.org/?probe=e5fc7b736b) | Sep 10, 2020 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [517c09218d](https://linux-hardware.org/?probe=517c09218d) | Sep 10, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [5a32535dcd](https://linux-hardware.org/?probe=5a32535dcd) | Sep 10, 2020 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [231f0afb76](https://linux-hardware.org/?probe=231f0afb76) | Sep 09, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [6438af227d](https://linux-hardware.org/?probe=6438af227d) | Sep 09, 2020 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [0b87386e6a](https://linux-hardware.org/?probe=0b87386e6a) | Sep 09, 2020 |
| HP            | Elite Dragonfly             | Notebook    | [54ea905f11](https://linux-hardware.org/?probe=54ea905f11) | Sep 08, 2020 |
| HP            | Elite Dragonfly             | Notebook    | [2489f5215c](https://linux-hardware.org/?probe=2489f5215c) | Sep 08, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [817add6537](https://linux-hardware.org/?probe=817add6537) | Sep 08, 2020 |
| HP            | Pavilion 17                 | Notebook    | [9cedfb1b3b](https://linux-hardware.org/?probe=9cedfb1b3b) | Sep 07, 2020 |
| Lenovo        | ThinkPad T450s 20BX000UM... | Notebook    | [357d9a4c6f](https://linux-hardware.org/?probe=357d9a4c6f) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| HP            | Pavilion dv7                | Notebook    | [e5ff49e4cd](https://linux-hardware.org/?probe=e5ff49e4cd) | Sep 05, 2020 |
| HP            | Pavilion dv7                | Notebook    | [c22e1eac2b](https://linux-hardware.org/?probe=c22e1eac2b) | Sep 05, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [1357806005](https://linux-hardware.org/?probe=1357806005) | Sep 05, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [f181207b61](https://linux-hardware.org/?probe=f181207b61) | Sep 05, 2020 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [342b54e7a0](https://linux-hardware.org/?probe=342b54e7a0) | Sep 04, 2020 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [d3510ce4e2](https://linux-hardware.org/?probe=d3510ce4e2) | Sep 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [bee8512dc1](https://linux-hardware.org/?probe=bee8512dc1) | Sep 04, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [900f200c57](https://linux-hardware.org/?probe=900f200c57) | Sep 03, 2020 |
| ASUSTek       | TP500LA                     | Notebook    | [394d439ddd](https://linux-hardware.org/?probe=394d439ddd) | Sep 03, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [af5f0cfb18](https://linux-hardware.org/?probe=af5f0cfb18) | Sep 03, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [e208d6ec85](https://linux-hardware.org/?probe=e208d6ec85) | Sep 03, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [3c29962537](https://linux-hardware.org/?probe=3c29962537) | Sep 03, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | Notebook    | [aec5429d00](https://linux-hardware.org/?probe=aec5429d00) | Sep 02, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | Notebook    | [30c8e7fd20](https://linux-hardware.org/?probe=30c8e7fd20) | Sep 02, 2020 |
| Dell          | Vostro 5481                 | Notebook    | [28fe85ae8c](https://linux-hardware.org/?probe=28fe85ae8c) | Sep 01, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b511e8b52a](https://linux-hardware.org/?probe=b511e8b52a) | Aug 31, 2020 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [10e5c82714](https://linux-hardware.org/?probe=10e5c82714) | Aug 31, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d24e39c945](https://linux-hardware.org/?probe=d24e39c945) | Aug 29, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2a246d5ea8](https://linux-hardware.org/?probe=2a246d5ea8) | Aug 29, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [7640a283c8](https://linux-hardware.org/?probe=7640a283c8) | Aug 28, 2020 |
| HP            | EliteBook 8770w             | Notebook    | [764d2f801d](https://linux-hardware.org/?probe=764d2f801d) | Aug 28, 2020 |
| HP            | 2AF3                        | Desktop     | [61d714ef58](https://linux-hardware.org/?probe=61d714ef58) | Aug 27, 2020 |
| ASUSTek       | E502MA                      | Notebook    | [634acf19b0](https://linux-hardware.org/?probe=634acf19b0) | Aug 23, 2020 |
| ASUSTek       | E403NA                      | Notebook    | [4cdd86950e](https://linux-hardware.org/?probe=4cdd86950e) | Aug 23, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [7152566435](https://linux-hardware.org/?probe=7152566435) | Aug 23, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [7286ec156e](https://linux-hardware.org/?probe=7286ec156e) | Aug 21, 2020 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [422ee2d231](https://linux-hardware.org/?probe=422ee2d231) | Aug 21, 2020 |
| Lenovo        | ThinkPad E14 20RA001BMX     | Notebook    | [8a145a9898](https://linux-hardware.org/?probe=8a145a9898) | Aug 21, 2020 |
| Lenovo        | ThinkPad E14 20RA001BMX     | Notebook    | [7d802db559](https://linux-hardware.org/?probe=7d802db559) | Aug 20, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| HP            | 0A64h                       | Desktop     | [223ff53d77](https://linux-hardware.org/?probe=223ff53d77) | Aug 18, 2020 |
| Lenovo        | ThinkPad T520 42404BG       | Notebook    | [05b2da899a](https://linux-hardware.org/?probe=05b2da899a) | Aug 18, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [36e63c4f0b](https://linux-hardware.org/?probe=36e63c4f0b) | Aug 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [746aeb7c50](https://linux-hardware.org/?probe=746aeb7c50) | Aug 18, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [8345dd66f0](https://linux-hardware.org/?probe=8345dd66f0) | Aug 17, 2020 |
| HP            | ProBook 470 G2              | Notebook    | [29253da938](https://linux-hardware.org/?probe=29253da938) | Aug 17, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Lenovo        | E31-80 80MX                 | Notebook    | [9291a2c955](https://linux-hardware.org/?probe=9291a2c955) | Aug 15, 2020 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [7831468225](https://linux-hardware.org/?probe=7831468225) | Aug 14, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [8b84e5b951](https://linux-hardware.org/?probe=8b84e5b951) | Aug 14, 2020 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [302127e58b](https://linux-hardware.org/?probe=302127e58b) | Aug 14, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [998c9d10e0](https://linux-hardware.org/?probe=998c9d10e0) | Aug 13, 2020 |
| ASUSTek       | X502CA                      | Notebook    | [86fa60846a](https://linux-hardware.org/?probe=86fa60846a) | Aug 12, 2020 |
| ASUSTek       | G750JM                      | Notebook    | [45fa35695c](https://linux-hardware.org/?probe=45fa35695c) | Aug 11, 2020 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [01515127a6](https://linux-hardware.org/?probe=01515127a6) | Aug 11, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [92e76957f9](https://linux-hardware.org/?probe=92e76957f9) | Aug 10, 2020 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [d6a59a4350](https://linux-hardware.org/?probe=d6a59a4350) | Aug 10, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [61518f1e84](https://linux-hardware.org/?probe=61518f1e84) | Aug 09, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [09e63aa959](https://linux-hardware.org/?probe=09e63aa959) | Aug 09, 2020 |
| ASRock        | Z87 Extreme6                | Desktop     | [9ab8243174](https://linux-hardware.org/?probe=9ab8243174) | Aug 07, 2020 |
| HP            | Elite x2 1012 G1 Tablet     | Notebook    | [9ba83a1b16](https://linux-hardware.org/?probe=9ba83a1b16) | Aug 07, 2020 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ddda943f96](https://linux-hardware.org/?probe=ddda943f96) | Aug 07, 2020 |
| HP            | 198E                        | Desktop     | [321cdddb29](https://linux-hardware.org/?probe=321cdddb29) | Aug 05, 2020 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [0f40a312c4](https://linux-hardware.org/?probe=0f40a312c4) | Aug 03, 2020 |
| Lenovo        | ThinkPad R500 2718WA3       | Notebook    | [dcc1d057ac](https://linux-hardware.org/?probe=dcc1d057ac) | Aug 02, 2020 |
| ASRock        | Z87 Extreme6                | Desktop     | [0ab11e1615](https://linux-hardware.org/?probe=0ab11e1615) | Jul 30, 2020 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [74d141c870](https://linux-hardware.org/?probe=74d141c870) | Jul 30, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [a05ebd9a3d](https://linux-hardware.org/?probe=a05ebd9a3d) | Jul 29, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4a211ec736](https://linux-hardware.org/?probe=4a211ec736) | Jul 29, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [9f29db1cee](https://linux-hardware.org/?probe=9f29db1cee) | Jul 28, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [4f8a67ed01](https://linux-hardware.org/?probe=4f8a67ed01) | Jul 28, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | Notebook    | [813cd0abea](https://linux-hardware.org/?probe=813cd0abea) | Jul 27, 2020 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [a68b2400b4](https://linux-hardware.org/?probe=a68b2400b4) | Jul 27, 2020 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [dcf2273c01](https://linux-hardware.org/?probe=dcf2273c01) | Jul 26, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [022e082270](https://linux-hardware.org/?probe=022e082270) | Jul 25, 2020 |
| Dell          | Latitude E5500              | Notebook    | [8a63e44923](https://linux-hardware.org/?probe=8a63e44923) | Jul 24, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [07df10e271](https://linux-hardware.org/?probe=07df10e271) | Jul 23, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [6595773d87](https://linux-hardware.org/?probe=6595773d87) | Jul 23, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [b0ee65c9cc](https://linux-hardware.org/?probe=b0ee65c9cc) | Jul 23, 2020 |
| MSI           | MS-7388                     | Desktop     | [95f9f16df0](https://linux-hardware.org/?probe=95f9f16df0) | Jul 23, 2020 |
| HP            | Pavilion dv9000 (RE380EA... | Notebook    | [285061cabd](https://linux-hardware.org/?probe=285061cabd) | Jul 22, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [68b2d657db](https://linux-hardware.org/?probe=68b2d657db) | Jul 20, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [f1d6156a56](https://linux-hardware.org/?probe=f1d6156a56) | Jul 20, 2020 |
| ASUSTek       | P5E                         | Desktop     | [bcea9f0625](https://linux-hardware.org/?probe=bcea9f0625) | Jul 14, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [33fcb49009](https://linux-hardware.org/?probe=33fcb49009) | Jul 14, 2020 |
| Bluechip C... | BUSINESSline                | Notebook    | [bc0c1e3029](https://linux-hardware.org/?probe=bc0c1e3029) | Jul 11, 2020 |
| Acer          | Aspire SW5-012              | Notebook    | [49c7eb0013](https://linux-hardware.org/?probe=49c7eb0013) | Jul 11, 2020 |
| Lenovo        | ThinkPad T520 42404BG       | Notebook    | [620cbb9090](https://linux-hardware.org/?probe=620cbb9090) | Jul 10, 2020 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [3426c91797](https://linux-hardware.org/?probe=3426c91797) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8b21c297c5](https://linux-hardware.org/?probe=8b21c297c5) | Jul 03, 2020 |
| Acer          | Lugano M                    | Notebook    | [4e9a4d0db9](https://linux-hardware.org/?probe=4e9a4d0db9) | Jul 02, 2020 |
| Pegatron      | 2A99                        | Desktop     | [a2db447eb2](https://linux-hardware.org/?probe=a2db447eb2) | Jul 01, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41da4c05ab](https://linux-hardware.org/?probe=41da4c05ab) | Jul 01, 2020 |
| HP            | Pavilion 17                 | Notebook    | [a50758bdb0](https://linux-hardware.org/?probe=a50758bdb0) | Jun 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [98d6c0c7b6](https://linux-hardware.org/?probe=98d6c0c7b6) | Jun 27, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [7c52d3e788](https://linux-hardware.org/?probe=7c52d3e788) | Jun 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [c0414a0bb6](https://linux-hardware.org/?probe=c0414a0bb6) | Jun 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [87a34bae25](https://linux-hardware.org/?probe=87a34bae25) | Jun 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [b77a82eb8e](https://linux-hardware.org/?probe=b77a82eb8e) | Jun 24, 2020 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [6209226e93](https://linux-hardware.org/?probe=6209226e93) | Jun 23, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [5ba05ac282](https://linux-hardware.org/?probe=5ba05ac282) | Jun 23, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [458687c748](https://linux-hardware.org/?probe=458687c748) | Jun 23, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [4f731da202](https://linux-hardware.org/?probe=4f731da202) | Jun 23, 2020 |
| Dell          | Latitude XT3                | Notebook    | [0e67c0cd7f](https://linux-hardware.org/?probe=0e67c0cd7f) | Jun 21, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [6db32be766](https://linux-hardware.org/?probe=6db32be766) | Jun 18, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [c006490a04](https://linux-hardware.org/?probe=c006490a04) | Jun 17, 2020 |
| Dell          | Latitude E6430              | Notebook    | [65b260fe65](https://linux-hardware.org/?probe=65b260fe65) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [2a90d0749c](https://linux-hardware.org/?probe=2a90d0749c) | Jun 15, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8ea0db2339](https://linux-hardware.org/?probe=8ea0db2339) | Jun 15, 2020 |
| MSI           | MS-7211                     | Desktop     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Acer          | RS780HVF                    | Desktop     | [83b78f2956](https://linux-hardware.org/?probe=83b78f2956) | Jun 12, 2020 |
| HP            | 1850                        | Desktop     | [2cc6a94d41](https://linux-hardware.org/?probe=2cc6a94d41) | Jun 11, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [94a74cb8d6](https://linux-hardware.org/?probe=94a74cb8d6) | Jun 11, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [80eaa52f0f](https://linux-hardware.org/?probe=80eaa52f0f) | Jun 10, 2020 |
| Dell          | 0WPG9H A01                  | All in one  | [68b61e7f50](https://linux-hardware.org/?probe=68b61e7f50) | Jun 10, 2020 |
| HP            | Compaq 6530b (GB975ET#AK... | Notebook    | [37e2e884f4](https://linux-hardware.org/?probe=37e2e884f4) | Jun 08, 2020 |
| HP            | Compaq 6530b (GB975ET#AK... | Notebook    | [3d6468c782](https://linux-hardware.org/?probe=3d6468c782) | Jun 08, 2020 |
| Lenovo        | ThinkPad E550 20DF009AMS    | Notebook    | [03a348554c](https://linux-hardware.org/?probe=03a348554c) | Jun 07, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [706e3366a8](https://linux-hardware.org/?probe=706e3366a8) | Jun 06, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [cbf8dca3ef](https://linux-hardware.org/?probe=cbf8dca3ef) | Jun 06, 2020 |
| HP            | 844C                        | Desktop     | [9ca2de8699](https://linux-hardware.org/?probe=9ca2de8699) | Jun 04, 2020 |
| HP            | 8596                        | Desktop     | [8a317cad1f](https://linux-hardware.org/?probe=8a317cad1f) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | VM42                        | Desktop     | [0c45d392cd](https://linux-hardware.org/?probe=0c45d392cd) | Jun 01, 2020 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [e31efeb24c](https://linux-hardware.org/?probe=e31efeb24c) | May 31, 2020 |
| ASUSTek       | TUF Gaming FA706II_FX706... | Notebook    | [00373c3ee0](https://linux-hardware.org/?probe=00373c3ee0) | May 30, 2020 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [e66cc02c0f](https://linux-hardware.org/?probe=e66cc02c0f) | May 26, 2020 |
| MSI           | GT83VR 7RF                  | Notebook    | [9d4dd03e4e](https://linux-hardware.org/?probe=9d4dd03e4e) | May 26, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [6c29c691f1](https://linux-hardware.org/?probe=6c29c691f1) | May 26, 2020 |
| ASRock        | X570 Taichi                 | Desktop     | [0a9aa77797](https://linux-hardware.org/?probe=0a9aa77797) | May 25, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [884a9eb467](https://linux-hardware.org/?probe=884a9eb467) | May 24, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [6ac29193c7](https://linux-hardware.org/?probe=6ac29193c7) | May 22, 2020 |
| Lenovo        | ThinkPad T450s 20BX000TM... | Notebook    | [99f86330e0](https://linux-hardware.org/?probe=99f86330e0) | May 20, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [5246632b14](https://linux-hardware.org/?probe=5246632b14) | May 18, 2020 |
| Lenovo        | ThinkPad X220 4293AF4       | Notebook    | [480c0cac17](https://linux-hardware.org/?probe=480c0cac17) | May 17, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4a5527d41](https://linux-hardware.org/?probe=f4a5527d41) | May 17, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [5299e08a50](https://linux-hardware.org/?probe=5299e08a50) | May 12, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [d856bd0613](https://linux-hardware.org/?probe=d856bd0613) | May 12, 2020 |
| Dell          | Latitude E6430              | Notebook    | [68c550913d](https://linux-hardware.org/?probe=68c550913d) | May 12, 2020 |
| HP            | Pavilion dv6                | Notebook    | [e83075226f](https://linux-hardware.org/?probe=e83075226f) | May 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [dac4e0e6ee](https://linux-hardware.org/?probe=dac4e0e6ee) | May 09, 2020 |
| Lenovo        | ThinkPad T490s 20NX001JM... | Notebook    | [72528667c4](https://linux-hardware.org/?probe=72528667c4) | May 06, 2020 |
| ASUSTek       | Z97-E                       | Desktop     | [64ac218015](https://linux-hardware.org/?probe=64ac218015) | May 04, 2020 |
| ASUSTek       | Z97-E                       | Desktop     | [110eb7afe6](https://linux-hardware.org/?probe=110eb7afe6) | May 04, 2020 |
| HP            | 2AFB                        | Desktop     | [ad8b92b3c2](https://linux-hardware.org/?probe=ad8b92b3c2) | Apr 29, 2020 |
| Pegatron      | 2A72h                       | Desktop     | [e91fa26092](https://linux-hardware.org/?probe=e91fa26092) | Apr 29, 2020 |
| Pegatron      | 2A72h                       | Desktop     | [ba42a81415](https://linux-hardware.org/?probe=ba42a81415) | Apr 28, 2020 |
| Lenovo        | G700 20251                  | Notebook    | [9b87ea272b](https://linux-hardware.org/?probe=9b87ea272b) | Apr 26, 2020 |
| HP            | ZBook 15u G6                | Notebook    | [05dc51a56c](https://linux-hardware.org/?probe=05dc51a56c) | Apr 24, 2020 |
| HP            | G72                         | Notebook    | [60ba9ba587](https://linux-hardware.org/?probe=60ba9ba587) | Apr 24, 2020 |
| Lenovo        | ThinkPad X240 20AL007SMS    | Notebook    | [4dea5ea55e](https://linux-hardware.org/?probe=4dea5ea55e) | Apr 23, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [3cef1ebb25](https://linux-hardware.org/?probe=3cef1ebb25) | Apr 23, 2020 |
| ASRock        | X570M Pro4                  | Desktop     | [84162d8ef3](https://linux-hardware.org/?probe=84162d8ef3) | Apr 21, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [b58744cc7c](https://linux-hardware.org/?probe=b58744cc7c) | Apr 20, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [45f9fd21d8](https://linux-hardware.org/?probe=45f9fd21d8) | Apr 18, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [829d027583](https://linux-hardware.org/?probe=829d027583) | Apr 18, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [1c77d3a8d3](https://linux-hardware.org/?probe=1c77d3a8d3) | Apr 17, 2020 |
| Lenovo        | E31-80 80MX                 | Notebook    | [eb8a266d8d](https://linux-hardware.org/?probe=eb8a266d8d) | Apr 17, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [3b4ea27678](https://linux-hardware.org/?probe=3b4ea27678) | Apr 13, 2020 |
| ASUSTek       | E403SA                      | Notebook    | [631c7a5ca7](https://linux-hardware.org/?probe=631c7a5ca7) | Apr 13, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b6ddb425af](https://linux-hardware.org/?probe=b6ddb425af) | Apr 12, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [94771dce64](https://linux-hardware.org/?probe=94771dce64) | Apr 10, 2020 |
| ASUSTek       | Z97-P                       | Desktop     | [1e40acf175](https://linux-hardware.org/?probe=1e40acf175) | Apr 09, 2020 |
| HP            | 255 G1                      | Notebook    | [9aba5d659b](https://linux-hardware.org/?probe=9aba5d659b) | Apr 08, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [8c63995e6a](https://linux-hardware.org/?probe=8c63995e6a) | Apr 07, 2020 |
| Lenovo        | ThinkPad T410s 2924W3X      | Notebook    | [1da6f919e9](https://linux-hardware.org/?probe=1da6f919e9) | Apr 06, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [f5a17b6798](https://linux-hardware.org/?probe=f5a17b6798) | Apr 06, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [0f8a987ceb](https://linux-hardware.org/?probe=0f8a987ceb) | Apr 03, 2020 |
| IBM           | ThinkPad T43 2668F7G        | Notebook    | [5db408d966](https://linux-hardware.org/?probe=5db408d966) | Apr 02, 2020 |
| IBM           | ThinkPad T43 2668F7G        | Notebook    | [533e6c9fdc](https://linux-hardware.org/?probe=533e6c9fdc) | Apr 02, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| HP            | 255 G3                      | Notebook    | [4a56cb73dc](https://linux-hardware.org/?probe=4a56cb73dc) | Apr 02, 2020 |
| Dell          | Precision M4700             | Notebook    | [dd482a877b](https://linux-hardware.org/?probe=dd482a877b) | Apr 02, 2020 |
| ASUSTek       | CM1855                      | Desktop     | [3b029acc71](https://linux-hardware.org/?probe=3b029acc71) | Apr 02, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [caf10e8019](https://linux-hardware.org/?probe=caf10e8019) | Apr 02, 2020 |
| Lenovo        | G70-70 80HW                 | Notebook    | [ccda14206b](https://linux-hardware.org/?probe=ccda14206b) | Apr 01, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [f28361a95d](https://linux-hardware.org/?probe=f28361a95d) | Mar 31, 2020 |
| Lenovo        | G70-70 80HW                 | Notebook    | [67facdce48](https://linux-hardware.org/?probe=67facdce48) | Mar 30, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6072c5667e](https://linux-hardware.org/?probe=6072c5667e) | Mar 30, 2020 |
| Gigabyte      | MFHM17P-00                  | Desktop     | [456a21854c](https://linux-hardware.org/?probe=456a21854c) | Mar 29, 2020 |
| HP            | 2133 (FU345EA)              | Notebook    | [2458279933](https://linux-hardware.org/?probe=2458279933) | Mar 29, 2020 |
| ASUSTek       | K70ID                       | Notebook    | [a75e7d2948](https://linux-hardware.org/?probe=a75e7d2948) | Mar 27, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [3e514aac2e](https://linux-hardware.org/?probe=3e514aac2e) | Mar 27, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [82579034fe](https://linux-hardware.org/?probe=82579034fe) | Mar 27, 2020 |
| ASUSTek       | G750JM                      | Notebook    | [37ae8536bf](https://linux-hardware.org/?probe=37ae8536bf) | Mar 26, 2020 |
| ASUSTek       | G750JM                      | Notebook    | [6218f94cee](https://linux-hardware.org/?probe=6218f94cee) | Mar 26, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d925844b9e](https://linux-hardware.org/?probe=d925844b9e) | Mar 25, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [dc10b9f32a](https://linux-hardware.org/?probe=dc10b9f32a) | Mar 25, 2020 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [1fd7bb6bcc](https://linux-hardware.org/?probe=1fd7bb6bcc) | Mar 24, 2020 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [7449a84a25](https://linux-hardware.org/?probe=7449a84a25) | Mar 24, 2020 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [4303c3c3a0](https://linux-hardware.org/?probe=4303c3c3a0) | Mar 24, 2020 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [572afffcf7](https://linux-hardware.org/?probe=572afffcf7) | Mar 24, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [165309707f](https://linux-hardware.org/?probe=165309707f) | Mar 24, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e973706460](https://linux-hardware.org/?probe=e973706460) | Mar 24, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [34dfe2501f](https://linux-hardware.org/?probe=34dfe2501f) | Mar 24, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [f04b0abbf7](https://linux-hardware.org/?probe=f04b0abbf7) | Mar 24, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1e24f00260](https://linux-hardware.org/?probe=1e24f00260) | Mar 22, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cdc5018f7b](https://linux-hardware.org/?probe=cdc5018f7b) | Mar 20, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [735dc4f753](https://linux-hardware.org/?probe=735dc4f753) | Mar 19, 2020 |
| HP            | 0A64h                       | Desktop     | [e525355c31](https://linux-hardware.org/?probe=e525355c31) | Mar 15, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5b782ed08d](https://linux-hardware.org/?probe=5b782ed08d) | Mar 15, 2020 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [75bc4a9f4b](https://linux-hardware.org/?probe=75bc4a9f4b) | Mar 14, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [ecb8270fa3](https://linux-hardware.org/?probe=ecb8270fa3) | Mar 12, 2020 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [222a13e152](https://linux-hardware.org/?probe=222a13e152) | Mar 12, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [1ef7ef0d05](https://linux-hardware.org/?probe=1ef7ef0d05) | Mar 12, 2020 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [f4da492647](https://linux-hardware.org/?probe=f4da492647) | Mar 11, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [860c0a37d7](https://linux-hardware.org/?probe=860c0a37d7) | Mar 11, 2020 |
| Acer          | Aspire 6920                 | Notebook    | [74408dee8d](https://linux-hardware.org/?probe=74408dee8d) | Mar 10, 2020 |
| Intel         | S1200RP G62251-406          | Server      | [bacfc6e800](https://linux-hardware.org/?probe=bacfc6e800) | Mar 09, 2020 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [c8f36212b2](https://linux-hardware.org/?probe=c8f36212b2) | Mar 06, 2020 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ec4c81e7d9](https://linux-hardware.org/?probe=ec4c81e7d9) | Mar 06, 2020 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [311ee470cb](https://linux-hardware.org/?probe=311ee470cb) | Mar 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [05d4c3ea67](https://linux-hardware.org/?probe=05d4c3ea67) | Mar 06, 2020 |
| HP            | 255 G3                      | Notebook    | [fc1f0f705a](https://linux-hardware.org/?probe=fc1f0f705a) | Mar 05, 2020 |
| HP            | 255 G3                      | Notebook    | [a9a974d797](https://linux-hardware.org/?probe=a9a974d797) | Mar 05, 2020 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [1276eb9896](https://linux-hardware.org/?probe=1276eb9896) | Feb 29, 2020 |
| Samsung       | X120/X170/X171              | Notebook    | [58616f66ea](https://linux-hardware.org/?probe=58616f66ea) | Feb 27, 2020 |
| Samsung       | X120/X170/X171              | Notebook    | [58df38ec38](https://linux-hardware.org/?probe=58df38ec38) | Feb 27, 2020 |
| Lenovo        | ThinkPad R500 2718WA3       | Notebook    | [b831059516](https://linux-hardware.org/?probe=b831059516) | Feb 27, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [739943f0ba](https://linux-hardware.org/?probe=739943f0ba) | Feb 26, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [0dc81f0e45](https://linux-hardware.org/?probe=0dc81f0e45) | Feb 26, 2020 |
| ASUSTek       | G21CN                       | Desktop     | [45598f0644](https://linux-hardware.org/?probe=45598f0644) | Feb 24, 2020 |
| HP            | G7000                       | Notebook    | [e6672524b9](https://linux-hardware.org/?probe=e6672524b9) | Feb 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f1ed2fda91](https://linux-hardware.org/?probe=f1ed2fda91) | Feb 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5a72aef554](https://linux-hardware.org/?probe=5a72aef554) | Feb 22, 2020 |
| ASRock        | Z97 Extreme4                | Desktop     | [60038b2000](https://linux-hardware.org/?probe=60038b2000) | Feb 21, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [8b7f434c80](https://linux-hardware.org/?probe=8b7f434c80) | Feb 21, 2020 |
| HP            | Pavilion g6                 | Notebook    | [4dcefb52d1](https://linux-hardware.org/?probe=4dcefb52d1) | Feb 18, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [ba36629619](https://linux-hardware.org/?probe=ba36629619) | Feb 15, 2020 |
| Dell          | Latitude 5400               | Notebook    | [1d3fda8388](https://linux-hardware.org/?probe=1d3fda8388) | Feb 12, 2020 |
| ASRock        | Z77 Pro3                    | Desktop     | [698b8aaaed](https://linux-hardware.org/?probe=698b8aaaed) | Feb 09, 2020 |
| Dell          | Latitude E7440              | Notebook    | [7ef094eacd](https://linux-hardware.org/?probe=7ef094eacd) | Feb 03, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [c37f970528](https://linux-hardware.org/?probe=c37f970528) | Feb 01, 2020 |
| Gigabyte      | Z97P-D3                     | Desktop     | [f151961dd1](https://linux-hardware.org/?probe=f151961dd1) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [84815d99c6](https://linux-hardware.org/?probe=84815d99c6) | Jan 31, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [6b182f66d9](https://linux-hardware.org/?probe=6b182f66d9) | Jan 31, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [a98ac0b7a3](https://linux-hardware.org/?probe=a98ac0b7a3) | Jan 30, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [0f84eb46c3](https://linux-hardware.org/?probe=0f84eb46c3) | Jan 29, 2020 |
| Dell          | Latitude 3540               | Notebook    | [b6cd260122](https://linux-hardware.org/?probe=b6cd260122) | Jan 29, 2020 |
| Dell          | Latitude 3540               | Notebook    | [77b755c276](https://linux-hardware.org/?probe=77b755c276) | Jan 29, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6059173c99](https://linux-hardware.org/?probe=6059173c99) | Jan 28, 2020 |
| Lenovo        | ThinkPad W520 42844ZG       | Notebook    | [9bf7631448](https://linux-hardware.org/?probe=9bf7631448) | Jan 28, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [948626f9b1](https://linux-hardware.org/?probe=948626f9b1) | Jan 25, 2020 |
| MSI           | B450M PRO-M2                | Desktop     | [04b3edf01b](https://linux-hardware.org/?probe=04b3edf01b) | Jan 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4e9e3904fb](https://linux-hardware.org/?probe=4e9e3904fb) | Jan 25, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [efe2412a0a](https://linux-hardware.org/?probe=efe2412a0a) | Jan 25, 2020 |
| Lenovo        | ThinkPad T440s 20ARS0J60... | Notebook    | [1f90408b82](https://linux-hardware.org/?probe=1f90408b82) | Jan 25, 2020 |
| Lenovo        | ThinkPad T500 2055WAB       | Notebook    | [c80f292866](https://linux-hardware.org/?probe=c80f292866) | Jan 24, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [6eaa1a038c](https://linux-hardware.org/?probe=6eaa1a038c) | Jan 24, 2020 |
| Gigabyte      | X170-WS ECC-CF              | Desktop     | [c284714094](https://linux-hardware.org/?probe=c284714094) | Jan 24, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [a0affc8996](https://linux-hardware.org/?probe=a0affc8996) | Jan 22, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [86ccd9865d](https://linux-hardware.org/?probe=86ccd9865d) | Jan 22, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [c4424c6f03](https://linux-hardware.org/?probe=c4424c6f03) | Jan 22, 2020 |
| ASUSTek       | ZenBook UX334FL_UX334FL     | Notebook    | [e390412733](https://linux-hardware.org/?probe=e390412733) | Jan 22, 2020 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [cda0e88379](https://linux-hardware.org/?probe=cda0e88379) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | Desktop     | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d9fcc1a1fc](https://linux-hardware.org/?probe=d9fcc1a1fc) | Jan 11, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [5ab003017d](https://linux-hardware.org/?probe=5ab003017d) | Jan 09, 2020 |
| Lenovo        | ThinkPad T450s 20BWS3F00... | Notebook    | [cf32529cfe](https://linux-hardware.org/?probe=cf32529cfe) | Jan 09, 2020 |
| Lenovo        | ThinkPad 20QJ001GMX         | Notebook    | [e720c77930](https://linux-hardware.org/?probe=e720c77930) | Jan 09, 2020 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [80297eeeb4](https://linux-hardware.org/?probe=80297eeeb4) | Jan 04, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [ad44824354](https://linux-hardware.org/?probe=ad44824354) | Jan 02, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [a853544a4d](https://linux-hardware.org/?probe=a853544a4d) | Jan 02, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [6c0bf83741](https://linux-hardware.org/?probe=6c0bf83741) | Jan 01, 2020 |
| ASRock        | G31M-GS                     | Desktop     | [857343b33e](https://linux-hardware.org/?probe=857343b33e) | Dec 30, 2019 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [b3b0d2e40e](https://linux-hardware.org/?probe=b3b0d2e40e) | Dec 30, 2019 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [1a77c2b73f](https://linux-hardware.org/?probe=1a77c2b73f) | Dec 29, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [562af84691](https://linux-hardware.org/?probe=562af84691) | Dec 16, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [3973a7cef2](https://linux-hardware.org/?probe=3973a7cef2) | Dec 12, 2019 |
| Lenovo        | ThinkCentre M90p 3652A3G    | Desktop     | [3877a5d3bb](https://linux-hardware.org/?probe=3877a5d3bb) | Dec 09, 2019 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [8e2b5b679e](https://linux-hardware.org/?probe=8e2b5b679e) | Dec 05, 2019 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [b9ff361521](https://linux-hardware.org/?probe=b9ff361521) | Dec 03, 2019 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1f44759168](https://linux-hardware.org/?probe=1f44759168) | Dec 02, 2019 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [c778f5266d](https://linux-hardware.org/?probe=c778f5266d) | Nov 29, 2019 |
| HP            | ProBook 450 G3              | Notebook    | [a0aca3e800](https://linux-hardware.org/?probe=a0aca3e800) | Nov 29, 2019 |
| HP            | 1998                        | Desktop     | [ee17d70239](https://linux-hardware.org/?probe=ee17d70239) | Nov 28, 2019 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8f2d04de46](https://linux-hardware.org/?probe=8f2d04de46) | Nov 28, 2019 |
| HP            | ProBook 450 G3              | Notebook    | [e33e17c851](https://linux-hardware.org/?probe=e33e17c851) | Nov 27, 2019 |
| Dell          | Precision M4700             | Notebook    | [7b41570d1d](https://linux-hardware.org/?probe=7b41570d1d) | Nov 22, 2019 |
| HP            | ProBook 450 G3              | Notebook    | [e7e10c99e5](https://linux-hardware.org/?probe=e7e10c99e5) | Nov 19, 2019 |
| HP            | ProBook 450 G3              | Notebook    | [8dde582a74](https://linux-hardware.org/?probe=8dde582a74) | Nov 18, 2019 |
| HP            | 1998                        | Desktop     | [78481ffcd4](https://linux-hardware.org/?probe=78481ffcd4) | Nov 17, 2019 |
| Foxconn       | A76ML-K 30                  | Desktop     | [cd69cd71e1](https://linux-hardware.org/?probe=cd69cd71e1) | Nov 12, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [1b4018bbd0](https://linux-hardware.org/?probe=1b4018bbd0) | Nov 12, 2019 |
| Lenovo        | ThinkPad T61p 64575KU       | Notebook    | [28ea2cfcfb](https://linux-hardware.org/?probe=28ea2cfcfb) | Nov 09, 2019 |
| Lenovo        | ThinkPad T61p 64575KU       | Notebook    | [d309e30410](https://linux-hardware.org/?probe=d309e30410) | Nov 09, 2019 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [7c4d12968c](https://linux-hardware.org/?probe=7c4d12968c) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [20882efef0](https://linux-hardware.org/?probe=20882efef0) | Nov 05, 2019 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [fcd4b162a4](https://linux-hardware.org/?probe=fcd4b162a4) | Nov 04, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [870d0fe48e](https://linux-hardware.org/?probe=870d0fe48e) | Oct 28, 2019 |
| Lenovo        | ThinkPad X240 20AL007SMS    | Notebook    | [e55c270c05](https://linux-hardware.org/?probe=e55c270c05) | Oct 27, 2019 |
| ASUSTek       | H97M-E                      | Desktop     | [9d2304c49f](https://linux-hardware.org/?probe=9d2304c49f) | Oct 27, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [4dc787cc15](https://linux-hardware.org/?probe=4dc787cc15) | Oct 27, 2019 |
| Timi          | TM1701                      | Notebook    | [b1b825395c](https://linux-hardware.org/?probe=b1b825395c) | Oct 26, 2019 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b05e61e4d9](https://linux-hardware.org/?probe=b05e61e4d9) | Oct 25, 2019 |
| ASRock        | B450 Pro4                   | Desktop     | [dcfc0b3327](https://linux-hardware.org/?probe=dcfc0b3327) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | Desktop     | [a29a11899f](https://linux-hardware.org/?probe=a29a11899f) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | Desktop     | [1740915405](https://linux-hardware.org/?probe=1740915405) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | Desktop     | [ba98645988](https://linux-hardware.org/?probe=ba98645988) | Oct 23, 2019 |
| ASUSTek       | Z87-K                       | Desktop     | [a2c50a6a82](https://linux-hardware.org/?probe=a2c50a6a82) | Oct 22, 2019 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [afd255688a](https://linux-hardware.org/?probe=afd255688a) | Oct 20, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [b194fb82fe](https://linux-hardware.org/?probe=b194fb82fe) | Oct 20, 2019 |
| Acer          | Swift SF315-52              | Notebook    | [c5950fe2b2](https://linux-hardware.org/?probe=c5950fe2b2) | Oct 20, 2019 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [0656361c4f](https://linux-hardware.org/?probe=0656361c4f) | Oct 19, 2019 |
| Lenovo        | ThinkPad T430s 2356GBG      | Notebook    | [d0861c1d33](https://linux-hardware.org/?probe=d0861c1d33) | Oct 17, 2019 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [3f141d1c9d](https://linux-hardware.org/?probe=3f141d1c9d) | Oct 05, 2019 |
| HP            | 0A64h                       | Desktop     | [b3aec62eb9](https://linux-hardware.org/?probe=b3aec62eb9) | Oct 01, 2019 |
| Dell          | XPS 13 9380                 | Notebook    | [9b98ab5761](https://linux-hardware.org/?probe=9b98ab5761) | Oct 01, 2019 |
| Lenovo        | ThinkPad X201 3680WAT       | Notebook    | [84b52bfd0a](https://linux-hardware.org/?probe=84b52bfd0a) | Sep 27, 2019 |
| HP            | Pavilion dv5000 (RE304EA... | Notebook    | [0e1b0b48b1](https://linux-hardware.org/?probe=0e1b0b48b1) | Sep 18, 2019 |
| Lenovo        | ThinkPad X201 3680WAT       | Notebook    | [99e139ffb7](https://linux-hardware.org/?probe=99e139ffb7) | Sep 14, 2019 |
| ASUSTek       | R11CX                       | Notebook    | [26755d5c7f](https://linux-hardware.org/?probe=26755d5c7f) | Sep 11, 2019 |
| ASUSTek       | R11CX                       | Notebook    | [0f1b2ab4e5](https://linux-hardware.org/?probe=0f1b2ab4e5) | Sep 11, 2019 |
| Acer          | Aspire V5-531               | Notebook    | [b7397bb906](https://linux-hardware.org/?probe=b7397bb906) | Sep 04, 2019 |
| Acer          | Aspire V5-531               | Notebook    | [c358492fe9](https://linux-hardware.org/?probe=c358492fe9) | Sep 04, 2019 |
| Acer          | Aspire V5-531               | Notebook    | [8da0ad144c](https://linux-hardware.org/?probe=8da0ad144c) | Sep 04, 2019 |
| MSI           | Z370 SLI PLUS               | Desktop     | [d6f9a54a5e](https://linux-hardware.org/?probe=d6f9a54a5e) | Sep 04, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [c4e7e10b98](https://linux-hardware.org/?probe=c4e7e10b98) | Sep 02, 2019 |
| Packard Be... | MCP73T-AD                   | Desktop     | [897bde5f15](https://linux-hardware.org/?probe=897bde5f15) | Aug 22, 2019 |
| ASUSTek       | P8H77-I                     | Desktop     | [9a5e6f850c](https://linux-hardware.org/?probe=9a5e6f850c) | Aug 16, 2019 |
| MSI           | Z370 SLI PLUS               | Desktop     | [9d169b5017](https://linux-hardware.org/?probe=9d169b5017) | Aug 14, 2019 |
| ASUSTek       | P8H77-I                     | Desktop     | [3ecc7afdb6](https://linux-hardware.org/?probe=3ecc7afdb6) | Aug 03, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [bbe763a2f6](https://linux-hardware.org/?probe=bbe763a2f6) | Jul 30, 2019 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [537d11b224](https://linux-hardware.org/?probe=537d11b224) | Jul 26, 2019 |
| Gigabyte      | P35-DS3                     | Desktop     | [b79ee752b4](https://linux-hardware.org/?probe=b79ee752b4) | Jul 15, 2019 |
| MSI           | IONA                        | Desktop     | [a585eaef35](https://linux-hardware.org/?probe=a585eaef35) | Jul 13, 2019 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e5a38b8f80](https://linux-hardware.org/?probe=e5a38b8f80) | Jul 12, 2019 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [9b815bccc4](https://linux-hardware.org/?probe=9b815bccc4) | Jul 12, 2019 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e2e30d9fb0](https://linux-hardware.org/?probe=e2e30d9fb0) | Jul 09, 2019 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a6b185ca6f](https://linux-hardware.org/?probe=a6b185ca6f) | Jul 09, 2019 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4ee3c4c06c](https://linux-hardware.org/?probe=4ee3c4c06c) | Jul 09, 2019 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4d5087b262](https://linux-hardware.org/?probe=4d5087b262) | Jul 06, 2019 |
| HP            | 2B0A                        | All in one  | [499ea7dfbb](https://linux-hardware.org/?probe=499ea7dfbb) | Jul 06, 2019 |
| HP            | 2B0A                        | All in one  | [c215749cab](https://linux-hardware.org/?probe=c215749cab) | Jul 05, 2019 |
| HP            | 2B0A                        | All in one  | [5b1b46557d](https://linux-hardware.org/?probe=5b1b46557d) | Jul 05, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c1edfcfa1c](https://linux-hardware.org/?probe=c1edfcfa1c) | Jul 04, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [d6587e26ef](https://linux-hardware.org/?probe=d6587e26ef) | Jul 04, 2019 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [941df897aa](https://linux-hardware.org/?probe=941df897aa) | Jul 04, 2019 |
| Intel         | MPAD-MSAE Customer Refer... | Notebook    | [4ffe571137](https://linux-hardware.org/?probe=4ffe571137) | Jul 01, 2019 |
| Intel         | MPAD-MSAE Customer Refer... | Notebook    | [4d75d266a8](https://linux-hardware.org/?probe=4d75d266a8) | Jun 27, 2019 |
| Lenovo        | G480 20156                  | Notebook    | [a82fad253c](https://linux-hardware.org/?probe=a82fad253c) | Jun 26, 2019 |
| Dell          | Latitude 7490               | Notebook    | [2e9a3bab26](https://linux-hardware.org/?probe=2e9a3bab26) | Jun 26, 2019 |
| HP            | 1497                        | Desktop     | [5ce732df30](https://linux-hardware.org/?probe=5ce732df30) | Jun 21, 2019 |
| Lenovo        | ThinkPad T61 7661VWJ        | Notebook    | [8b7af37281](https://linux-hardware.org/?probe=8b7af37281) | Jun 21, 2019 |
| Lenovo        | ThinkPad T61 7661VWJ        | Notebook    | [f26014bd09](https://linux-hardware.org/?probe=f26014bd09) | Jun 21, 2019 |
| ASUSTek       | M4A78                       | Desktop     | [f95aec52e4](https://linux-hardware.org/?probe=f95aec52e4) | Jun 15, 2019 |
| Lenovo        | ThinkPad W530 244759G       | Notebook    | [c087621d89](https://linux-hardware.org/?probe=c087621d89) | Jun 06, 2019 |
| HP            | EliteBook 850 G5            | Notebook    | [240b48eaa4](https://linux-hardware.org/?probe=240b48eaa4) | Jun 01, 2019 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [8efa5879d9](https://linux-hardware.org/?probe=8efa5879d9) | Jun 01, 2019 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [347d0dbf57](https://linux-hardware.org/?probe=347d0dbf57) | May 29, 2019 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [a55280bb16](https://linux-hardware.org/?probe=a55280bb16) | May 25, 2019 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8d3a77af71](https://linux-hardware.org/?probe=8d3a77af71) | May 24, 2019 |
| MSI           | 760GM-E51                   | Desktop     | [b23ed61a74](https://linux-hardware.org/?probe=b23ed61a74) | May 13, 2019 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [a394c4861e](https://linux-hardware.org/?probe=a394c4861e) | May 12, 2019 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [72daf5bb2f](https://linux-hardware.org/?probe=72daf5bb2f) | May 12, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [80e41dc351](https://linux-hardware.org/?probe=80e41dc351) | May 10, 2019 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [3065c56994](https://linux-hardware.org/?probe=3065c56994) | May 08, 2019 |
| Acer          | Aspire V5-122P              | Notebook    | [26c2caf634](https://linux-hardware.org/?probe=26c2caf634) | May 03, 2019 |
| MSI           | 760GM-E51                   | Desktop     | [c77558abf8](https://linux-hardware.org/?probe=c77558abf8) | May 01, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [41a0e2a118](https://linux-hardware.org/?probe=41a0e2a118) | Apr 29, 2019 |
| ASUSTek       | E402NA                      | Notebook    | [b4a8d0e098](https://linux-hardware.org/?probe=b4a8d0e098) | Apr 26, 2019 |
| ASUSTek       | E402NA                      | Notebook    | [f4fbc00320](https://linux-hardware.org/?probe=f4fbc00320) | Apr 25, 2019 |
| ASUSTek       | E402NA                      | Notebook    | [83cd83a710](https://linux-hardware.org/?probe=83cd83a710) | Apr 25, 2019 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [8ce5db772c](https://linux-hardware.org/?probe=8ce5db772c) | Apr 17, 2019 |
| Intel         | DG33TL AAD89517-700         | Desktop     | [90ba96cb73](https://linux-hardware.org/?probe=90ba96cb73) | Apr 16, 2019 |
| Intel         | DG33TL AAD89517-700         | Desktop     | [b151450467](https://linux-hardware.org/?probe=b151450467) | Apr 15, 2019 |
| Dell          | Precision M4600             | Notebook    | [9b9a3a238d](https://linux-hardware.org/?probe=9b9a3a238d) | Apr 14, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [1c1b87dea4](https://linux-hardware.org/?probe=1c1b87dea4) | Apr 13, 2019 |
| ASUSTek       | P6T                         | Desktop     | [4db2f20573](https://linux-hardware.org/?probe=4db2f20573) | Apr 07, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [855fdd6eac](https://linux-hardware.org/?probe=855fdd6eac) | Mar 19, 2019 |
| ASRock        | Z87 Extreme6                | Desktop     | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| Acer          | Aspire V5-531               | Notebook    | [bca94341a4](https://linux-hardware.org/?probe=bca94341a4) | Mar 16, 2019 |
| Lenovo        | ThinkPad T430 2349N5G       | Notebook    | [e8ef93b83a](https://linux-hardware.org/?probe=e8ef93b83a) | Mar 09, 2019 |
| HP            | 1497                        | Desktop     | [357589623a](https://linux-hardware.org/?probe=357589623a) | Feb 23, 2019 |
| Acer          | Aspire V3-571               | Notebook    | [6df0a8894c](https://linux-hardware.org/?probe=6df0a8894c) | Feb 20, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [8b517ca2e8](https://linux-hardware.org/?probe=8b517ca2e8) | Feb 14, 2019 |
| ASUSTek       | P6T                         | Desktop     | [5040f012a9](https://linux-hardware.org/?probe=5040f012a9) | Feb 10, 2019 |
| ASUSTek       | P6T                         | Desktop     | [79dfc022fd](https://linux-hardware.org/?probe=79dfc022fd) | Feb 09, 2019 |
| ASRock        | ALiveNF6G-GLAN              | Desktop     | [a89f20ae20](https://linux-hardware.org/?probe=a89f20ae20) | Feb 08, 2019 |
| Apple         | MacBook3,1                  | Notebook    | [0770a78a4c](https://linux-hardware.org/?probe=0770a78a4c) | Feb 06, 2019 |
| AOpen         | nMCP7ALPx-DE R1.04 Oct.0... | Desktop     | [b778a6096a](https://linux-hardware.org/?probe=b778a6096a) | Jan 30, 2019 |
| ASRock        | ALiveNF6G-GLAN              | Desktop     | [5ab2a6ed4a](https://linux-hardware.org/?probe=5ab2a6ed4a) | Jan 25, 2019 |
| Lenovo        | ThinkPad T400 6475W2W       | Notebook    | [888ced2d7f](https://linux-hardware.org/?probe=888ced2d7f) | Jan 19, 2019 |
| ASUSTek       | UX32A                       | Notebook    | [c21c33634a](https://linux-hardware.org/?probe=c21c33634a) | Jan 17, 2019 |
| ASUSTek       | P5LD2EB-DHS                 | Desktop     | [ece39839eb](https://linux-hardware.org/?probe=ece39839eb) | Jan 05, 2019 |
| Lenovo        | ThinkPad T440 20B7S0CH0R    | Notebook    | [beb89cd93e](https://linux-hardware.org/?probe=beb89cd93e) | Dec 28, 2018 |
| Intel         | DH61DL AAG14066-202         | Desktop     | [8e77a793e3](https://linux-hardware.org/?probe=8e77a793e3) | Dec 19, 2018 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [82325163f4](https://linux-hardware.org/?probe=82325163f4) | Dec 12, 2018 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b699ce4e30](https://linux-hardware.org/?probe=b699ce4e30) | Dec 12, 2018 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [79918271ca](https://linux-hardware.org/?probe=79918271ca) | Dec 12, 2018 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [0e6e8c5fc5](https://linux-hardware.org/?probe=0e6e8c5fc5) | Dec 10, 2018 |
| ASUSTek       | X705UDR                     | Notebook    | [b2f78ec700](https://linux-hardware.org/?probe=b2f78ec700) | Dec 09, 2018 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [ce36a69992](https://linux-hardware.org/?probe=ce36a69992) | Dec 08, 2018 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [35e3d7eec6](https://linux-hardware.org/?probe=35e3d7eec6) | Dec 04, 2018 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [6ae2992c3c](https://linux-hardware.org/?probe=6ae2992c3c) | Dec 01, 2018 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [3f4c1e2d20](https://linux-hardware.org/?probe=3f4c1e2d20) | Dec 01, 2018 |
| HP            | Compaq nx7300 (RU463ET#A... | Notebook    | [b22462b111](https://linux-hardware.org/?probe=b22462b111) | Nov 30, 2018 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [81d31aab82](https://linux-hardware.org/?probe=81d31aab82) | Nov 30, 2018 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [f1e742b9b3](https://linux-hardware.org/?probe=f1e742b9b3) | Nov 30, 2018 |
| Lenovo        | ThinkPad X220 4291VKE       | Notebook    | [d336773a80](https://linux-hardware.org/?probe=d336773a80) | Nov 27, 2018 |
| Lenovo        | ThinkPad X220 4291VKE       | Notebook    | [55b3107b16](https://linux-hardware.org/?probe=55b3107b16) | Nov 27, 2018 |
| Acer          | Aspire 5750G                | Notebook    | [b2048b608c](https://linux-hardware.org/?probe=b2048b608c) | Nov 24, 2018 |
| Acer          | Aspire 5750G                | Notebook    | [8a8e4823b7](https://linux-hardware.org/?probe=8a8e4823b7) | Nov 24, 2018 |
| Acer          | Aspire 5750G                | Notebook    | [c2ccafc934](https://linux-hardware.org/?probe=c2ccafc934) | Nov 24, 2018 |
| HP            | 2B47                        | Desktop     | [e887d07240](https://linux-hardware.org/?probe=e887d07240) | Nov 19, 2018 |
| HP            | 2B47                        | Desktop     | [447f6778a8](https://linux-hardware.org/?probe=447f6778a8) | Nov 19, 2018 |
| HP            | 3048h                       | Desktop     | [4b5985d50d](https://linux-hardware.org/?probe=4b5985d50d) | Nov 18, 2018 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [4863c625bf](https://linux-hardware.org/?probe=4863c625bf) | Nov 13, 2018 |
| Samsung       | RF712                       | Notebook    | [7984717e58](https://linux-hardware.org/?probe=7984717e58) | Nov 13, 2018 |
| Samsung       | RF712                       | Notebook    | [ae13618f58](https://linux-hardware.org/?probe=ae13618f58) | Nov 13, 2018 |
| Sony          | SVS1313R9EB                 | Notebook    | [f05fdf7d0f](https://linux-hardware.org/?probe=f05fdf7d0f) | Nov 09, 2018 |
| Sony          | SVS1313R9EB                 | Notebook    | [cc21510205](https://linux-hardware.org/?probe=cc21510205) | Nov 09, 2018 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [e9ff7d1722](https://linux-hardware.org/?probe=e9ff7d1722) | Nov 05, 2018 |
| HP            | 1494                        | Desktop     | [055a009ae7](https://linux-hardware.org/?probe=055a009ae7) | Nov 04, 2018 |
| HP            | EliteBook 8460p             | Notebook    | [79c41a36c7](https://linux-hardware.org/?probe=79c41a36c7) | Nov 01, 2018 |
| ASUSTek       | P5GD1-VM                    | Desktop     | [22f77f9153](https://linux-hardware.org/?probe=22f77f9153) | Oct 28, 2018 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [ef9f5a1c9b](https://linux-hardware.org/?probe=ef9f5a1c9b) | Oct 25, 2018 |
| Dell          | Precision 7520              | Notebook    | [efa61a5893](https://linux-hardware.org/?probe=efa61a5893) | Oct 22, 2018 |
| Acer          | AOD255E                     | Notebook    | [ae27c4311f](https://linux-hardware.org/?probe=ae27c4311f) | Oct 01, 2018 |
| ASRock        | AB350M Pro4                 | Desktop     | [aa933db296](https://linux-hardware.org/?probe=aa933db296) | Sep 06, 2018 |
| ASUSTek       | X99-E WS                    | Desktop     | [b396839f41](https://linux-hardware.org/?probe=b396839f41) | Jul 31, 2018 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a527c8d1d5](https://linux-hardware.org/?probe=a527c8d1d5) | Jun 26, 2018 |
| Seco          | UDOO x86                    | Notebook    | [5278a91530](https://linux-hardware.org/?probe=5278a91530) | Jun 21, 2018 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [31bf9ac5b7](https://linux-hardware.org/?probe=31bf9ac5b7) | Jun 21, 2018 |
| Sony          | VPCEH3P1E                   | Notebook    | [6320ab14c5](https://linux-hardware.org/?probe=6320ab14c5) | May 27, 2018 |
| Gigabyte      | EP45-DS3R                   | Desktop     | [304f67f539](https://linux-hardware.org/?probe=304f67f539) | Jan 10, 2018 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [a5891a7fe7](https://linux-hardware.org/?probe=a5891a7fe7) | Dec 28, 2017 |
| HP            | ProLiant MicroServer        | Desktop     | [eed6dea797](https://linux-hardware.org/?probe=eed6dea797) | Dec 18, 2017 |
| HP            | 3398                        | Desktop     | [eefaeab3db](https://linux-hardware.org/?probe=eefaeab3db) | Dec 09, 2017 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [5d5433f7bb](https://linux-hardware.org/?probe=5d5433f7bb) | Dec 07, 2017 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [45a3db7122](https://linux-hardware.org/?probe=45a3db7122) | Dec 07, 2017 |
| HP            | EliteBook 2560p             | Notebook    | [a25f24dde8](https://linux-hardware.org/?probe=a25f24dde8) | Nov 27, 2017 |
| Intel         | DH61DL AAG14066-202         | Desktop     | [6fc8f44aa5](https://linux-hardware.org/?probe=6fc8f44aa5) | Oct 18, 2017 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [2b3f698711](https://linux-hardware.org/?probe=2b3f698711) | Sep 20, 2017 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [0f2e040400](https://linux-hardware.org/?probe=0f2e040400) | Sep 11, 2017 |
| HP            | 3398                        | Desktop     | [2685073294](https://linux-hardware.org/?probe=2685073294) | Aug 28, 2017 |
| Samsung       | R610                        | Notebook    | [60e00734b3](https://linux-hardware.org/?probe=60e00734b3) | Jul 11, 2017 |
| Samsung       | R610                        | Notebook    | [641adc42c2](https://linux-hardware.org/?probe=641adc42c2) | Feb 12, 2017 |
| Lenovo        | ThinkCentre M57 6072WUS     | Desktop     | [d300880847](https://linux-hardware.org/?probe=d300880847) | Feb 09, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 183       | 16.14%  |
| Ubuntu 18.04                 | 104       | 9.17%   |
| OpenMandriva 4.2             | 33        | 2.91%   |
| Ubuntu 22.04                 | 29        | 2.56%   |
| Arch Rolling                 | 27        | 2.38%   |
| Arch                         | 26        | 2.29%   |
| Linux Mint 20                | 24        | 2.12%   |
| Ubuntu 21.04                 | 23        | 2.03%   |
| Linux Mint 20.1              | 21        | 1.85%   |
| Debian 11                    | 21        | 1.85%   |
| Pop!_OS 21.04                | 20        | 1.76%   |
| Ubuntu 20.10                 | 19        | 1.68%   |
| Manjaro                      | 19        | 1.68%   |
| Xubuntu 20.04                | 17        | 1.5%    |
| Linux Mint 19.3              | 17        | 1.5%    |
| Fedora 33                    | 17        | 1.5%    |
| Ubuntu 21.10                 | 16        | 1.41%   |
| Pop!_OS 20.04                | 16        | 1.41%   |
| OpenMandriva 4.3             | 16        | 1.41%   |
| Gentoo 2.7                   | 15        | 1.32%   |
| Fedora 32                    | 15        | 1.32%   |
| Debian 10                    | 15        | 1.32%   |
| Linux Mint 20.2              | 14        | 1.23%   |
| Fedora 34                    | 14        | 1.23%   |
| Fedora 31                    | 14        | 1.23%   |
| Ubuntu 19.10                 | 13        | 1.15%   |
| ArcoLinux Rolling            | 12        | 1.06%   |
| Xubuntu 18.04                | 11        | 0.97%   |
| Pop!_OS 21.10                | 11        | 0.97%   |
| Linux Mint 20.3              | 11        | 0.97%   |
| Fedora 36                    | 10        | 0.88%   |
| EndeavourOS Rolling          | 10        | 0.88%   |
| Debian Testing               | 10        | 0.88%   |
| Zorin 16                     | 9         | 0.79%   |
| Ubuntu 19.04                 | 9         | 0.79%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 0.79%   |
| Gentoo 2.6                   | 9         | 0.79%   |
| Ubuntu 16.04                 | 8         | 0.71%   |
| Pop!_OS 20.10                | 8         | 0.71%   |
| KDE neon 20.04               | 8         | 0.71%   |
| Fedora 35                    | 8         | 0.71%   |
| ROSA R10                     | 7         | 0.62%   |
| Pop!_OS 22.04                | 7         | 0.62%   |
| Lubuntu 20.04                | 7         | 0.62%   |
| Kubuntu 20.04                | 7         | 0.62%   |
| Ubuntu MATE 20.04            | 6         | 0.53%   |
| ROSA R11                     | 6         | 0.53%   |
| Kubuntu 20.10                | 6         | 0.53%   |
| CentOS 7                     | 6         | 0.53%   |
| BlackPanther 18.1            | 6         | 0.53%   |
| Manjaro 20.2.1               | 5         | 0.44%   |
| Manjaro 18.1.5               | 5         | 0.44%   |
| Zorin 15                     | 4         | 0.35%   |
| Xubuntu 19.10                | 4         | 0.35%   |
| Ubuntu Budgie 20.04          | 4         | 0.35%   |
| Ubuntu 18.10                 | 4         | 0.35%   |
| ROSA R9                      | 4         | 0.35%   |
| ROSA R8.1                    | 4         | 0.35%   |
| Peppermint 10                | 4         | 0.35%   |
| OpenMandriva 4.50            | 4         | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 391       | 36.27%  |
| Linux Mint    | 85        | 7.88%   |
| Fedora        | 73        | 6.77%   |
| Pop!_OS       | 59        | 5.47%   |
| OpenMandriva  | 53        | 4.92%   |
| Arch          | 53        | 4.92%   |
| Manjaro       | 51        | 4.73%   |
| Debian        | 49        | 4.55%   |
| Xubuntu       | 38        | 3.53%   |
| Gentoo        | 25        | 2.32%   |
| ROSA          | 24        | 2.23%   |
| Kubuntu       | 16        | 1.48%   |
| openSUSE      | 14        | 1.3%    |
| ArcoLinux     | 14        | 1.3%    |
| Zorin         | 13        | 1.21%   |
| Lubuntu       | 11        | 1.02%   |
| EndeavourOS   | 11        | 1.02%   |
| Ubuntu MATE   | 10        | 0.93%   |
| CentOS        | 10        | 0.93%   |
| KDE neon      | 9         | 0.83%   |
| Elementary    | 7         | 0.65%   |
| MX            | 6         | 0.56%   |
| BlackPanther  | 6         | 0.56%   |
| Peppermint    | 5         | 0.46%   |
| Kali          | 5         | 0.46%   |
| Ubuntu Budgie | 4         | 0.37%   |
| Endless       | 4         | 0.37%   |
| Clear Linux   | 4         | 0.37%   |
| Garuda Linux  | 3         | 0.28%   |
| Raspbian      | 2         | 0.19%   |
| Parrot        | 2         | 0.19%   |
| LMDE          | 2         | 0.19%   |
| Devuan        | 2         | 0.19%   |
| Artix         | 2         | 0.19%   |
| antergos      | 2         | 0.19%   |
| UbuntuDDE     | 1         | 0.09%   |
| Ubuntu Studio | 1         | 0.09%   |
| Solus         | 1         | 0.09%   |
| Slackware     | 1         | 0.09%   |
| RHEL          | 1         | 0.09%   |
| Redcore       | 1         | 0.09%   |
| Reborn OS     | 1         | 0.09%   |
| LinuxFX       | 1         | 0.09%   |
| GNOME OS      | 1         | 0.09%   |
| Feren OS      | 1         | 0.09%   |
| Archcraft     | 1         | 0.09%   |
| Android       | 1         | 0.09%   |
| AlmaLinux     | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 37        | 2.99%   |
| 5.10.14-desktop-1omv4002           | 32        | 2.59%   |
| 5.4.0-58-generic                   | 18        | 1.46%   |
| 5.4.0-48-generic                   | 16        | 1.29%   |
| 5.4.0-47-generic                   | 16        | 1.29%   |
| 5.16.7-desktop-1omv4003            | 16        | 1.29%   |
| 5.4.0-52-generic                   | 12        | 0.97%   |
| 5.3.0-40-generic                   | 12        | 0.97%   |
| 5.11.0-7620-generic                | 12        | 0.97%   |
| 5.8.0-44-generic                   | 10        | 0.81%   |
| 5.8.0-41-generic                   | 9         | 0.73%   |
| 5.4.0-65-generic                   | 9         | 0.73%   |
| 5.4.0-56-generic                   | 9         | 0.73%   |
| 5.4.0-53-generic                   | 9         | 0.73%   |
| 5.4.0-45-generic                   | 8         | 0.65%   |
| 5.15.0-46-generic                  | 8         | 0.65%   |
| 5.13.0-7620-generic                | 8         | 0.65%   |
| 5.8.0-43-generic                   | 7         | 0.57%   |
| 5.4.0-92-generic                   | 7         | 0.57%   |
| 5.4.0-66-generic                   | 7         | 0.57%   |
| 5.4.0-54-generic                   | 7         | 0.57%   |
| 5.3.0-46-generic                   | 7         | 0.57%   |
| 5.3.0-42-generic                   | 7         | 0.57%   |
| 5.15.0-27-generic                  | 7         | 0.57%   |
| 5.11.0-25-generic                  | 7         | 0.57%   |
| 5.8.0-7630-generic                 | 6         | 0.49%   |
| 5.4.0-7634-generic                 | 6         | 0.49%   |
| 5.4.0-51-generic                   | 6         | 0.49%   |
| 5.15.0-41-generic                  | 6         | 0.49%   |
| 5.13.0-30-generic                  | 6         | 0.49%   |
| 5.13.0-22-generic                  | 6         | 0.49%   |
| 5.11.0-41-generic                  | 6         | 0.49%   |
| 5.11.0-34-generic                  | 6         | 0.49%   |
| 5.11.0-27-generic                  | 6         | 0.49%   |
| 5.10.0-8-amd64                     | 6         | 0.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 6         | 0.49%   |
| 4.18.16-desktop-1bP                | 6         | 0.49%   |
| 5.8.0-50-generic                   | 5         | 0.4%    |
| 5.8.0-48-generic                   | 5         | 0.4%    |
| 5.4.0-90-generic                   | 5         | 0.4%    |
| 5.4.0-81-generic                   | 5         | 0.4%    |
| 5.4.0-7642-generic                 | 5         | 0.4%    |
| 5.4.0-73-generic                   | 5         | 0.4%    |
| 5.4.0-40-generic                   | 5         | 0.4%    |
| 5.4.0-37-generic                   | 5         | 0.4%    |
| 5.4.0-122-generic                  | 5         | 0.4%    |
| 5.15.15-76051515-generic           | 5         | 0.4%    |
| 5.15.0-43-generic                  | 5         | 0.4%    |
| 5.15.0-25-generic                  | 5         | 0.4%    |
| 5.11.0-40-generic                  | 5         | 0.4%    |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 0.4%    |
| 5.0.0-32-generic                   | 5         | 0.4%    |
| 4.18.0-15-generic                  | 5         | 0.4%    |
| 4.15.0-43-generic                  | 5         | 0.4%    |
| 4.15.0-39-generic                  | 5         | 0.4%    |
| 4.15.0-38-generic                  | 5         | 0.4%    |
| 4.15.0-29-generic                  | 5         | 0.4%    |
| 5.8.0-40-generic                   | 4         | 0.32%   |
| 5.8.0-29-generic                   | 4         | 0.32%   |
| 5.4.0-80-generic                   | 4         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 251       | 21.31%  |
| 5.8.0   | 81        | 6.88%   |
| 4.15.0  | 78        | 6.62%   |
| 5.11.0  | 73        | 6.2%    |
| 5.3.0   | 49        | 4.16%   |
| 5.13.0  | 46        | 3.9%    |
| 5.15.0  | 42        | 3.57%   |
| 5.10.14 | 33        | 2.8%    |
| 5.0.0   | 26        | 2.21%   |
| 5.10.0  | 23        | 1.95%   |
| 4.18.0  | 21        | 1.78%   |
| 4.19.0  | 19        | 1.61%   |
| 5.16.7  | 16        | 1.36%   |
| 5.17.5  | 7         | 0.59%   |
| 4.18.16 | 7         | 0.59%   |
| 5.14.0  | 6         | 0.51%   |
| 4.9.60  | 6         | 0.51%   |
| 3.10.0  | 6         | 0.51%   |
| 5.15.15 | 5         | 0.42%   |
| 5.14.14 | 5         | 0.42%   |
| 5.12.4  | 5         | 0.42%   |
| 5.11.14 | 5         | 0.42%   |
| 5.10.74 | 5         | 0.42%   |
| 5.9.0   | 4         | 0.34%   |
| 5.8.11  | 4         | 0.34%   |
| 5.6.0   | 4         | 0.34%   |
| 5.3.18  | 4         | 0.34%   |
| 5.15.28 | 4         | 0.34%   |
| 5.13.9  | 4         | 0.34%   |
| 5.11.2  | 4         | 0.34%   |
| 5.9.16  | 3         | 0.25%   |
| 5.9.11  | 3         | 0.25%   |
| 5.8.6   | 3         | 0.25%   |
| 5.8.16  | 3         | 0.25%   |
| 5.8.14  | 3         | 0.25%   |
| 5.6.19  | 3         | 0.25%   |
| 5.5.10  | 3         | 0.25%   |
| 5.3.7   | 3         | 0.25%   |
| 5.17.4  | 3         | 0.25%   |
| 5.17.0  | 3         | 0.25%   |
| 5.16.19 | 3         | 0.25%   |
| 5.16.1  | 3         | 0.25%   |
| 5.16.0  | 3         | 0.25%   |
| 5.15.5  | 3         | 0.25%   |
| 5.15.41 | 3         | 0.25%   |
| 5.15.12 | 3         | 0.25%   |
| 5.15.11 | 3         | 0.25%   |
| 5.13.13 | 3         | 0.25%   |
| 5.11.7  | 3         | 0.25%   |
| 4.4.0   | 3         | 0.25%   |
| 5.9.9   | 2         | 0.17%   |
| 5.9.8   | 2         | 0.17%   |
| 5.9.3   | 2         | 0.17%   |
| 5.9.13  | 2         | 0.17%   |
| 5.8.7   | 2         | 0.17%   |
| 5.8.4   | 2         | 0.17%   |
| 5.8.13  | 2         | 0.17%   |
| 5.8.12  | 2         | 0.17%   |
| 5.7.15  | 2         | 0.17%   |
| 5.7.14  | 2         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 276       | 23.83%  |
| 5.8     | 106       | 9.15%   |
| 5.11    | 95        | 8.2%    |
| 5.10    | 91        | 7.86%   |
| 5.15    | 87        | 7.51%   |
| 4.15    | 79        | 6.82%   |
| 5.3     | 62        | 5.35%   |
| 5.13    | 62        | 5.35%   |
| 5.16    | 37        | 3.2%    |
| 4.18    | 29        | 2.5%    |
| 5.17    | 27        | 2.33%   |
| 5.0     | 27        | 2.33%   |
| 4.19    | 24        | 2.07%   |
| 5.9     | 18        | 1.55%   |
| 5.14    | 18        | 1.55%   |
| 5.7     | 17        | 1.47%   |
| 5.12    | 17        | 1.47%   |
| 5.18    | 16        | 1.38%   |
| 5.6     | 14        | 1.21%   |
| 4.9     | 14        | 1.21%   |
| 5.5     | 13        | 1.12%   |
| 3.10    | 6         | 0.52%   |
| 5.19    | 4         | 0.35%   |
| 4.1     | 4         | 0.35%   |
| 5.2     | 3         | 0.26%   |
| 4.4     | 3         | 0.26%   |
| 5.1     | 2         | 0.17%   |
| 4.13    | 2         | 0.17%   |
| 4.20    | 1         | 0.09%   |
| 4.17    | 1         | 0.09%   |
| 4.14    | 1         | 0.09%   |
| 4.12    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1006      | 96.27%  |
| i686    | 30        | 2.87%   |
| aarch64 | 8         | 0.77%   |
| armv6l  | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 458       | 42.02%  |
| Unknown          | 167       | 15.32%  |
| KDE5             | 166       | 15.23%  |
| XFCE             | 90        | 8.26%   |
| X-Cinnamon       | 54        | 4.95%   |
| MATE             | 34        | 3.12%   |
| KDE              | 23        | 2.11%   |
| KDE4             | 13        | 1.19%   |
| Cinnamon         | 13        | 1.19%   |
| LXQt             | 11        | 1.01%   |
| GNOME Flashback  | 9         | 0.83%   |
| i3               | 8         | 0.73%   |
| LXDE             | 7         | 0.64%   |
| Pantheon         | 6         | 0.55%   |
| lightdm-xsession | 6         | 0.55%   |
| Budgie           | 6         | 0.55%   |
| Unity            | 5         | 0.46%   |
| Deepin           | 3         | 0.28%   |
| bspwm            | 3         | 0.28%   |
| LeftWM           | 2         | 0.18%   |
| DWM              | 2         | 0.18%   |
| xubuntu          | 1         | 0.09%   |
| xmonad           | 1         | 0.09%   |
| sway:Unity       | 1         | 0.09%   |
| GNOME Classic    | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 822       | 77.04%  |
| Wayland | 130       | 12.18%  |
| Unknown | 76        | 7.12%   |
| Tty     | 38        | 3.56%   |
| Web     | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 557       | 51.15%  |
| SDDM    | 154       | 14.14%  |
| GDM     | 152       | 13.96%  |
| LightDM | 85        | 7.81%   |
| GDM3    | 63        | 5.79%   |
| TDM     | 61        | 5.6%    |
| KDM     | 14        | 1.29%   |
| XDM     | 1         | 0.09%   |
| Ly      | 1         | 0.09%   |
| LXDM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 436       | 40.82%  |
| fi_FI       | 348       | 32.58%  |
| Unknown     | 138       | 12.92%  |
| en_GB       | 62        | 5.81%   |
| C           | 21        | 1.97%   |
| ru_RU       | 14        | 1.31%   |
| en_FI       | 6         | 0.56%   |
| sv_FI       | 5         | 0.47%   |
| sv_SE       | 4         | 0.37%   |
| C.UTF8      | 4         | 0.37%   |
| pl_PL       | 3         | 0.28%   |
| fr_FR       | 3         | 0.28%   |
| en_DK       | 3         | 0.28%   |
| it_IT       | 2         | 0.19%   |
| et_EE       | 2         | 0.19%   |
| en_SE       | 2         | 0.19%   |
| en_IE       | 2         | 0.19%   |
| de_DE       | 2         | 0.19%   |
| zh_CN       | 1         | 0.09%   |
| UTF-8       | 1         | 0.09%   |
| is_IS       | 1         | 0.09%   |
| ia_FR       | 1         | 0.09%   |
| hu_HU       | 1         | 0.09%   |
| fr_CA       | 1         | 0.09%   |
| en_US.utf-8 | 1         | 0.09%   |
| en_NG       | 1         | 0.09%   |
| en_CA       | 1         | 0.09%   |
| en_AG       | 1         | 0.09%   |
| af_ZA       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 566       | 53.2%   |
| EFI  | 498       | 46.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 808       | 75.8%   |
| Btrfs   | 101       | 9.47%   |
| Overlay | 76        | 7.13%   |
| Unknown | 42        | 3.94%   |
| Xfs     | 19        | 1.78%   |
| Zfs     | 12        | 1.13%   |
| Ext3    | 3         | 0.28%   |
| Ext2    | 3         | 0.28%   |
| F2fs    | 2         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 554       | 52.02%  |
| GPT     | 365       | 34.27%  |
| MBR     | 146       | 13.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 905       | 85.3%   |
| Yes       | 156       | 14.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 773       | 72.92%  |
| Yes       | 287       | 27.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 223       | 21.36%  |
| Lenovo                  | 201       | 19.25%  |
| Hewlett-Packard         | 167       | 16%     |
| Dell                    | 81        | 7.76%   |
| MSI                     | 59        | 5.65%   |
| Acer                    | 59        | 5.65%   |
| Gigabyte Technology     | 51        | 4.89%   |
| ASRock                  | 43        | 4.12%   |
| Fujitsu                 | 25        | 2.39%   |
| Samsung Electronics     | 18        | 1.72%   |
| Apple                   | 18        | 1.72%   |
| Intel                   | 15        | 1.44%   |
| Fujitsu Siemens         | 10        | 0.96%   |
| Pegatron                | 8         | 0.77%   |
| Packard Bell            | 7         | 0.67%   |
| Foxconn                 | 7         | 0.67%   |
| Raspberry Pi Foundation | 6         | 0.57%   |
| Toshiba                 | 5         | 0.48%   |
| Supermicro              | 4         | 0.38%   |
| Sony                    | 4         | 0.38%   |
| Unknown                 | 4         | 0.38%   |
| HUAWEI                  | 3         | 0.29%   |
| Timi                    | 2         | 0.19%   |
| Medion                  | 2         | 0.19%   |
| ASRockRack              | 2         | 0.19%   |
| AOpen                   | 2         | 0.19%   |
| AMI                     | 2         | 0.19%   |
| ABIT                    | 2         | 0.19%   |
| ZOTAC                   | 1         | 0.1%    |
| WeiBu                   | 1         | 0.1%    |
| Shuttle                 | 1         | 0.1%    |
| Seco                    | 1         | 0.1%    |
| powerinternational      | 1         | 0.1%    |
| Pine Microsystems       | 1         | 0.1%    |
| Notebook                | 1         | 0.1%    |
| Microsoft               | 1         | 0.1%    |
| IBM                     | 1         | 0.1%    |
| Google                  | 1         | 0.1%    |
| ECS                     | 1         | 0.1%    |
| Dixonsxp                | 1         | 0.1%    |
| Bluechip Computer       | 1         | 0.1%    |
| Alienware               | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 22        | 2.11%   |
| HP EliteDesk 800 G1 SFF              | 8         | 0.77%   |
| MSI MS-7C37                          | 6         | 0.57%   |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.48%   |
| Unknown                              | 5         | 0.48%   |
| Gigabyte X570 AORUS ELITE            | 4         | 0.38%   |
| ASUS M5A97 R2.0                      | 4         | 0.38%   |
| Samsung R530/R730                    | 3         | 0.29%   |
| MSI MS-7B89                          | 3         | 0.29%   |
| MSI MS-7B48                          | 3         | 0.29%   |
| MSI MS-7A38                          | 3         | 0.29%   |
| Lenovo V145-15AST 81MT               | 3         | 0.29%   |
| Lenovo ThinkPad T420 4180PBG         | 3         | 0.29%   |
| Lenovo MIIX 310-10ICR 80SG           | 3         | 0.29%   |
| HP Pavilion dv6                      | 3         | 0.29%   |
| HP EliteBook 8460p                   | 3         | 0.29%   |
| HP EliteBook 840 G7 Notebook PC      | 3         | 0.29%   |
| HP EliteBook 820 G1                  | 3         | 0.29%   |
| HP EliteBook 2560p                   | 3         | 0.29%   |
| HP Compaq 8200 Elite SFF PC          | 3         | 0.29%   |
| Fujitsu Siemens ESPRIMO Mobile D9500 | 3         | 0.29%   |
| Fujitsu LIFEBOOK A530                | 3         | 0.29%   |
| Dell XPS 13 9380                     | 3         | 0.29%   |
| Dell OptiPlex 780                    | 3         | 0.29%   |
| Dell Latitude 7490                   | 3         | 0.29%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 3         | 0.29%   |
| ASUS ROG STRIX Z370-F GAMING         | 3         | 0.29%   |
| ASUS ROG STRIX B550-I GAMING         | 3         | 0.29%   |
| ASUS Pro WS 565-ACE                  | 3         | 0.29%   |
| ASUS PRIME B350-PLUS                 | 3         | 0.29%   |
| ASUS E402NA                          | 3         | 0.29%   |
| ASRock B450M-HDV R4.0                | 3         | 0.29%   |
| Acer Aspire X3300                    | 3         | 0.29%   |
| Toshiba Satellite C660               | 2         | 0.19%   |
| Samsung R610                         | 2         | 0.19%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 2         | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 2         | 0.19%   |
| MSI MS-7C84                          | 2         | 0.19%   |
| MSI MS-7B49                          | 2         | 0.19%   |
| MSI MS-7B46                          | 2         | 0.19%   |
| MSI MS-7A40                          | 2         | 0.19%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 2         | 0.19%   |
| Lenovo Yoga C740-14IML 81TC          | 2         | 0.19%   |
| Lenovo Yoga 2 Pro 20266              | 2         | 0.19%   |
| Lenovo Y520-15IKBN 80WK              | 2         | 0.19%   |
| Lenovo ThinkPad X230 23253Z5         | 2         | 0.19%   |
| Lenovo ThinkPad T490 20N3S2NJ00      | 2         | 0.19%   |
| Lenovo ThinkPad T480 20L5000BMX      | 2         | 0.19%   |
| Lenovo ThinkPad T410 253725G         | 2         | 0.19%   |
| Lenovo ThinkPad P50 20EN0006MS       | 2         | 0.19%   |
| Lenovo ThinkPad E14 20RA001BMX       | 2         | 0.19%   |
| Lenovo ThinkCentre M90 5485W45       | 2         | 0.19%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 2         | 0.19%   |
| Lenovo IdeaPad 320-15IKB 80XL        | 2         | 0.19%   |
| Lenovo IdeaPad 310-15IKB 80TV        | 2         | 0.19%   |
| Lenovo IdeaPad 120S-14IAP 81A5       | 2         | 0.19%   |
| Lenovo IdeaPad 100S-14IBR 80R9       | 2         | 0.19%   |
| Intel S1200RP                        | 2         | 0.19%   |
| HP Z420 Workstation                  | 2         | 0.19%   |
| HP Z240 Tower Workstation            | 2         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 120       | 11.49%  |
| Acer Aspire             | 39        | 3.74%   |
| HP EliteBook            | 36        | 3.45%   |
| HP Compaq               | 32        | 3.07%   |
| Dell Latitude           | 32        | 3.07%   |
| ASUS PRIME              | 28        | 2.68%   |
| HP Pavilion             | 26        | 2.49%   |
| ASUS All                | 22        | 2.11%   |
| Lenovo IdeaPad          | 18        | 1.72%   |
| ASUS ROG                | 18        | 1.72%   |
| Dell XPS                | 15        | 1.44%   |
| Lenovo Yoga             | 13        | 1.25%   |
| Dell OptiPlex           | 13        | 1.25%   |
| ASUS TUF                | 13        | 1.25%   |
| Dell Precision          | 12        | 1.15%   |
| Lenovo ThinkCentre      | 11        | 1.05%   |
| HP EliteDesk            | 11        | 1.05%   |
| Fujitsu LIFEBOOK        | 11        | 1.05%   |
| HP ProBook              | 10        | 0.96%   |
| HP ProDesk              | 7         | 0.67%   |
| Gigabyte X570           | 7         | 0.67%   |
| Fujitsu Siemens ESPRIMO | 7         | 0.67%   |
| Fujitsu ESPRIMO         | 7         | 0.67%   |
| ASUS VivoBook           | 7         | 0.67%   |
| RPi Raspberry           | 6         | 0.57%   |
| MSI MS-7C37             | 6         | 0.57%   |
| HP Laptop               | 6         | 0.57%   |
| ASUS M5A97              | 6         | 0.57%   |
| Toshiba Satellite       | 5         | 0.48%   |
| Lenovo Legion           | 5         | 0.48%   |
| Acer Swift              | 5         | 0.48%   |
| Unknown                 | 5         | 0.48%   |
| Packard Bell EasyNote   | 4         | 0.38%   |
| HP ZBook                | 4         | 0.38%   |
| Gigabyte B550           | 4         | 0.38%   |
| Dell Inspiron           | 4         | 0.38%   |
| ASUS Pro                | 4         | 0.38%   |
| ASRock B450M-HDV        | 4         | 0.38%   |
| Samsung R530            | 3         | 0.29%   |
| MSI MS-7B89             | 3         | 0.29%   |
| MSI MS-7B48             | 3         | 0.29%   |
| MSI MS-7A38             | 3         | 0.29%   |
| Lenovo V145-15AST       | 3         | 0.29%   |
| Lenovo MIIX             | 3         | 0.29%   |
| HP ENVY                 | 3         | 0.29%   |
| HP Elite                | 3         | 0.29%   |
| HP 255                  | 3         | 0.29%   |
| Dell Vostro             | 3         | 0.29%   |
| ASUS ZenBook            | 3         | 0.29%   |
| ASUS P8Z68-V            | 3         | 0.29%   |
| ASUS E402NA             | 3         | 0.29%   |
| ASRock 970              | 3         | 0.29%   |
| Apple iMac12            | 3         | 0.29%   |
| Acer Predator           | 3         | 0.29%   |
| Acer Nitro              | 3         | 0.29%   |
| Samsung R610            | 2         | 0.19%   |
| Samsung 355V4C          | 2         | 0.19%   |
| Samsung 300E4A          | 2         | 0.19%   |
| Packard Bell IMEDIA     | 2         | 0.19%   |
| MSI MS-7C84             | 2         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 104       | 9.96%   |
| 2012    | 97        | 9.29%   |
| 2018    | 93        | 8.91%   |
| 2013    | 89        | 8.52%   |
| 2011    | 84        | 8.05%   |
| 2017    | 82        | 7.85%   |
| 2020    | 77        | 7.38%   |
| 2014    | 60        | 5.75%   |
| 2015    | 56        | 5.36%   |
| 2008    | 56        | 5.36%   |
| 2016    | 53        | 5.08%   |
| 2009    | 52        | 4.98%   |
| 2010    | 48        | 4.6%    |
| 2007    | 32        | 3.07%   |
| 2021    | 30        | 2.87%   |
| 2006    | 12        | 1.15%   |
| Unknown | 7         | 0.67%   |
| 2022    | 5         | 0.48%   |
| 2005    | 5         | 0.48%   |
| 2004    | 2         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 532       | 50.96%  |
| Desktop        | 449       | 43.01%  |
| Convertible    | 18        | 1.72%   |
| Mini pc        | 12        | 1.15%   |
| All in one     | 11        | 1.05%   |
| Server         | 8         | 0.77%   |
| System on chip | 6         | 0.57%   |
| Tablet         | 6         | 0.57%   |
| Phone          | 2         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 966       | 92.26%  |
| Enabled  | 81        | 7.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1043      | 99.9%   |
| Yes  | 1         | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 227       | 21.54%  |
| 16.01-24.0      | 225       | 21.35%  |
| 3.01-4.0        | 222       | 21.06%  |
| 8.01-16.0       | 165       | 15.65%  |
| 32.01-64.0      | 99        | 9.39%   |
| 1.01-2.0        | 40        | 3.8%    |
| 64.01-256.0     | 33        | 3.13%   |
| 2.01-3.0        | 17        | 1.61%   |
| 24.01-32.0      | 16        | 1.52%   |
| 0.51-1.0        | 5         | 0.47%   |
| More than 256.0 | 4         | 0.38%   |
| 0.01-0.5        | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 414       | 36.16%  |
| 2.01-3.0    | 254       | 22.18%  |
| 4.01-8.0    | 151       | 13.19%  |
| 3.01-4.0    | 131       | 11.44%  |
| 0.51-1.0    | 98        | 8.56%   |
| 8.01-16.0   | 57        | 4.98%   |
| 0.01-0.5    | 19        | 1.66%   |
| 16.01-24.0  | 10        | 0.87%   |
| 32.01-64.0  | 5         | 0.44%   |
| 24.01-32.0  | 3         | 0.26%   |
| 64.01-256.0 | 2         | 0.17%   |
| 0           | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 626       | 58.61%  |
| 2      | 226       | 21.16%  |
| 3      | 96        | 8.99%   |
| 4      | 41        | 3.84%   |
| 5      | 27        | 2.53%   |
| 0      | 19        | 1.78%   |
| 6      | 12        | 1.12%   |
| 7      | 7         | 0.66%   |
| 9      | 5         | 0.47%   |
| 8      | 5         | 0.47%   |
| 10     | 2         | 0.19%   |
| 23     | 1         | 0.09%   |
| 11     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 606       | 57.55%  |
| Yes       | 447       | 42.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 942       | 89.97%  |
| No        | 105       | 10.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 742       | 70.73%  |
| No        | 307       | 29.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 577       | 54.74%  |
| No        | 477       | 45.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Finland | 1044      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Helsinki     | 469       | 41.95%  |
| Tampere      | 105       | 9.39%   |
| Turku        | 84        | 7.51%   |
| Oulu         | 55        | 4.92%   |
| Espoo        | 50        | 4.47%   |
| Kuopio       | 34        | 3.04%   |
| Jyväskylä  | 28        | 2.5%    |
| Lahti        | 26        | 2.33%   |
| Vantaa       | 25        | 2.24%   |
| Vaasa        | 14        | 1.25%   |
| Tuusula      | 12        | 1.07%   |
| Raisio       | 12        | 1.07%   |
| Raahe        | 9         | 0.81%   |
| Lappeenranta | 9         | 0.81%   |
| Joensuu      | 9         | 0.81%   |
| Hyvinkaeae   | 9         | 0.81%   |
| Pori         | 8         | 0.72%   |
| Tenala       | 4         | 0.36%   |
| Solv         | 4         | 0.36%   |
| Seinäjoki   | 4         | 0.36%   |
| Salo         | 4         | 0.36%   |
| Kouvola      | 4         | 0.36%   |
| Kotka        | 4         | 0.36%   |
| Klaukkala    | 4         | 0.36%   |
| Järvenpää | 4         | 0.36%   |
| Rusko        | 3         | 0.27%   |
| Rauma        | 3         | 0.27%   |
| Porlammi     | 3         | 0.27%   |
| Mäntsälä  | 3         | 0.27%   |
| Lempäälä  | 3         | 0.27%   |
| Kokkola      | 3         | 0.27%   |
| Kerava       | 3         | 0.27%   |
| Heinola      | 3         | 0.27%   |
| Hanko        | 3         | 0.27%   |
| Hämeenlinna | 3         | 0.27%   |
| Urjala       | 2         | 0.18%   |
| Tarvasjoki   | 2         | 0.18%   |
| Sastamala    | 2         | 0.18%   |
| Rovaniemi    | 2         | 0.18%   |
| Riihimäki   | 2         | 0.18%   |
| Pirkkala     | 2         | 0.18%   |
| Petäjävesi | 2         | 0.18%   |
| Nummela      | 2         | 0.18%   |
| Nokia        | 2         | 0.18%   |
| Mikkeli      | 2         | 0.18%   |
| Maenttae     | 2         | 0.18%   |
| Lohja        | 2         | 0.18%   |
| Lieto        | 2         | 0.18%   |
| Kangasala    | 2         | 0.18%   |
| Jakobstad    | 2         | 0.18%   |
| Forssa       | 2         | 0.18%   |
| Ylöjärvi   | 1         | 0.09%   |
| Ylaemylly    | 1         | 0.09%   |
| Vörå       | 1         | 0.09%   |
| Vieremä     | 1         | 0.09%   |
| Vesilahti    | 1         | 0.09%   |
| Valkeakoski  | 1         | 0.09%   |
| Vaajakoski   | 1         | 0.09%   |
| Uusikaupunki | 1         | 0.09%   |
| Turenki      | 1         | 0.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 305       | 479    | 20.04%  |
| WDC                            | 222       | 389    | 14.59%  |
| Seagate                        | 194       | 309    | 12.75%  |
| Kingston                       | 175       | 255    | 11.5%   |
| Toshiba                        | 82        | 131    | 5.39%   |
| Intel                          | 59        | 75     | 3.88%   |
| Hitachi                        | 59        | 81     | 3.88%   |
| Unknown                        | 53        | 74     | 3.48%   |
| SK hynix                       | 47        | 58     | 3.09%   |
| SanDisk                        | 46        | 55     | 3.02%   |
| Crucial                        | 42        | 49     | 2.76%   |
| HGST                           | 25        | 46     | 1.64%   |
| Micron Technology              | 24        | 52     | 1.58%   |
| A-DATA Technology              | 20        | 27     | 1.31%   |
| Corsair                        | 13        | 15     | 0.85%   |
| Maxtor                         | 12        | 19     | 0.79%   |
| OCZ                            | 11        | 16     | 0.72%   |
| Transcend                      | 10        | 11     | 0.66%   |
| PNY                            | 10        | 10     | 0.66%   |
| Fujitsu                        | 10        | 12     | 0.66%   |
| Phison                         | 9         | 10     | 0.59%   |
| KIOXIA                         | 9         | 9      | 0.59%   |
| Apple                          | 7         | 9      | 0.46%   |
| Verbatim                       | 6         | 7      | 0.39%   |
| LITEON                         | 6         | 8      | 0.39%   |
| LITEONIT                       | 5         | 6      | 0.33%   |
| XPG                            | 4         | 5      | 0.26%   |
| Patriot                        | 4         | 7      | 0.26%   |
| Intenso                        | 4         | 4      | 0.26%   |
| HUAWEI                         | 3         | 3      | 0.2%    |
| Hewlett-Packard                | 3         | 4      | 0.2%    |
| China                          | 3         | 3      | 0.2%    |
| ASMT                           | 3         | 3      | 0.2%    |
| UMIS                           | 2         | 2      | 0.13%   |
| Plextor                        | 2         | 2      | 0.13%   |
| OCZ-VERTEX3                    | 2         | 2      | 0.13%   |
| Lenovo                         | 2         | 2      | 0.13%   |
| JMicron Technology             | 2         | 5      | 0.13%   |
| BHT                            | 2         | 4      | 0.13%   |
| Vaseky                         | 1         | 1      | 0.07%   |
| USB3.1                         | 1         | 1      | 0.07%   |
| Union Memory (Shenzhen)        | 1         | 3      | 0.07%   |
| TSA                            | 1         | 1      | 0.07%   |
| TO Exter                       | 1         | 1      | 0.07%   |
| SPCC                           | 1         | 1      | 0.07%   |
| Solid State Storage Technology | 1         | 1      | 0.07%   |
| Solid State Storage            | 1         | 1      | 0.07%   |
| sobetter                       | 1         | 1      | 0.07%   |
| Silicon Motion                 | 1         | 1      | 0.07%   |
| RSH-339                        | 1         | 1      | 0.07%   |
| Realtek Semiconductor          | 1         | 1      | 0.07%   |
| Realtek                        | 1         | 1      | 0.07%   |
| Ramsta                         | 1         | 1      | 0.07%   |
| OCZ-VERTEX                     | 1         | 1      | 0.07%   |
| Lite-On                        | 1         | 1      | 0.07%   |
| KingSpec                       | 1         | 1      | 0.07%   |
| KimMiDi                        | 1         | 2      | 0.07%   |
| GOODRAM                        | 1         | 1      | 0.07%   |
| Gigabyte Technology            | 1         | 1      | 0.07%   |
| FORESEE                        | 1         | 1      | 0.07%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 27        | 1.58%   |
| Samsung SSD 850 EVO 250GB            | 26        | 1.52%   |
| Kingston SA400S37120G 120GB SSD      | 20        | 1.17%   |
| Samsung SSD 850 EVO 500GB            | 19        | 1.11%   |
| Samsung NVMe SSD Drive 500GB         | 16        | 0.93%   |
| Kingston SA400S37480G 480GB SSD      | 16        | 0.93%   |
| Unknown MMC Card  64GB               | 14        | 0.82%   |
| Kingston SV300S37A120G 120GB SSD     | 14        | 0.82%   |
| Kingston SHFS37A120G 120GB SSD       | 13        | 0.76%   |
| Samsung SSD 860 EVO 500GB            | 12        | 0.7%    |
| Kingston SV300S37A240G 240GB SSD     | 12        | 0.7%    |
| Seagate ST9500325AS 500GB            | 11        | 0.64%   |
| Samsung NVMe SSD Drive 256GB         | 11        | 0.64%   |
| Seagate ST500DM002-1BD142 500GB      | 10        | 0.58%   |
| Samsung NVMe SSD Drive 512GB         | 10        | 0.58%   |
| Samsung NVMe SSD Drive 1TB           | 10        | 0.58%   |
| Samsung HD103SJ 1TB                  | 10        | 0.58%   |
| HGST HTS721010A9E630 1TB             | 10        | 0.58%   |
| Unknown MMC Card  32GB               | 9         | 0.53%   |
| Crucial CT1000MX500SSD1 1TB          | 9         | 0.53%   |
| Toshiba DT01ACA300 3TB               | 8         | 0.47%   |
| Samsung SSD 960 EVO 500GB            | 8         | 0.47%   |
| Samsung SSD 860 EVO 1TB              | 8         | 0.47%   |
| Samsung HD501LJ 500GB                | 8         | 0.47%   |
| WDC WD30EFRX-68EUZN0 3TB             | 7         | 0.41%   |
| SK hynix NVMe SSD Drive 256GB        | 7         | 0.41%   |
| Samsung SSD 840 EVO 120GB            | 7         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 6         | 0.35%   |
| WDC WD40EFRX-68WT0N0 4TB             | 6         | 0.35%   |
| Toshiba MQ01ABD100 1TB               | 6         | 0.35%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 6         | 0.35%   |
| SK hynix NVMe SSD Drive 512GB        | 6         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB       | 6         | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB       | 6         | 0.35%   |
| Seagate Expansion 500GB              | 6         | 0.35%   |
| SanDisk NVMe SSD Drive 512GB         | 6         | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB       | 6         | 0.35%   |
| PNY CS900 120GB SSD                  | 6         | 0.35%   |
| Intel SSDSC2BW180A3L 180GB           | 6         | 0.35%   |
| Intel SSDPEKNW010T8 1TB              | 6         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 5         | 0.29%   |
| Toshiba DT01ACA100 1TB               | 5         | 0.29%   |
| Seagate ST31000528AS 1TB             | 5         | 0.29%   |
| Seagate ST31000524AS 1TB             | 5         | 0.29%   |
| SanDisk DF4064  64GB                 | 5         | 0.29%   |
| Samsung SSD 970 EVO 500GB            | 5         | 0.29%   |
| Samsung SSD 860 QVO 1TB              | 5         | 0.29%   |
| Samsung SSD 850 PRO 256GB            | 5         | 0.29%   |
| Samsung SSD 830 Series 128GB         | 5         | 0.29%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD | 5         | 0.29%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD | 5         | 0.29%   |
| Kingston SH103S3120G 120GB SSD       | 5         | 0.29%   |
| Intel NVMe SSD Drive 256GB           | 5         | 0.29%   |
| Intel NVMe SSD Drive 1024GB          | 5         | 0.29%   |
| HGST HTS725050A7E630 500GB           | 5         | 0.29%   |
| Crucial CT256MX100SSD1 256GB         | 5         | 0.29%   |
| Crucial CT120BX500SSD1 120GB         | 5         | 0.29%   |
| A-DATA SX8200PNP 1TB                 | 5         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 187       | 299    | 32.24%  |
| WDC                 | 180       | 318    | 31.03%  |
| Hitachi             | 59        | 81     | 10.17%  |
| Toshiba             | 54        | 85     | 9.31%   |
| Samsung Electronics | 41        | 57     | 7.07%   |
| HGST                | 25        | 46     | 4.31%   |
| Maxtor              | 12        | 19     | 2.07%   |
| Fujitsu             | 10        | 12     | 1.72%   |
| Unknown             | 3         | 3      | 0.52%   |
| Intenso             | 2         | 2      | 0.34%   |
| ASMT                | 2         | 2      | 0.34%   |
| Apple               | 2         | 2      | 0.34%   |
| RSH-339             | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 3      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 176       | 252    | 29.58%  |
| Kingston            | 154       | 227    | 25.88%  |
| Crucial             | 41        | 48     | 6.89%   |
| WDC                 | 33        | 47     | 5.55%   |
| Intel               | 27        | 39     | 4.54%   |
| SanDisk             | 25        | 31     | 4.2%    |
| Micron Technology   | 19        | 46     | 3.19%   |
| OCZ                 | 11        | 16     | 1.85%   |
| Transcend           | 10        | 11     | 1.68%   |
| Toshiba             | 10        | 18     | 1.68%   |
| SK hynix            | 10        | 17     | 1.68%   |
| A-DATA Technology   | 10        | 14     | 1.68%   |
| PNY                 | 9         | 9      | 1.51%   |
| Corsair             | 7         | 8      | 1.18%   |
| Verbatim            | 6         | 7      | 1.01%   |
| LITEON              | 6         | 8      | 1.01%   |
| LITEONIT            | 5         | 6      | 0.84%   |
| Patriot             | 4         | 7      | 0.67%   |
| Apple               | 4         | 5      | 0.67%   |
| China               | 3         | 3      | 0.5%    |
| Plextor             | 2         | 2      | 0.34%   |
| OCZ-VERTEX3         | 2         | 2      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| Hewlett-Packard     | 2         | 3      | 0.34%   |
| BHT                 | 2         | 4      | 0.34%   |
| Vaseky              | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |
| TSA                 | 1         | 1      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| SPCC                | 1         | 1      | 0.17%   |
| Seagate             | 1         | 1      | 0.17%   |
| Ramsta              | 1         | 1      | 0.17%   |
| OCZ-VERTEX          | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.17%   |
| GOODRAM             | 1         | 1      | 0.17%   |
| FORESEE             | 1         | 1      | 0.17%   |
| CT240BX5            | 1         | 1      | 0.17%   |
| ATP                 | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 512       | 847    | 37.67%  |
| HDD     | 482       | 931    | 35.47%  |
| NVMe    | 299       | 417    | 22%     |
| MMC     | 52        | 69     | 3.83%   |
| Unknown | 14        | 22     | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 811       | 1729   | 67.25%  |
| NVMe | 298       | 415    | 24.71%  |
| MMC  | 52        | 69     | 4.31%   |
| SAS  | 45        | 73     | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 668       | 1119   | 63.5%   |
| 0.51-1.0   | 239       | 335    | 22.72%  |
| 1.01-2.0   | 64        | 126    | 6.08%   |
| 2.01-3.0   | 29        | 60     | 2.76%   |
| 3.01-4.0   | 28        | 81     | 2.66%   |
| 4.01-10.0  | 22        | 55     | 2.09%   |
| 10.01-20.0 | 2         | 2      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 322       | 29.6%   |
| 251-500        | 209       | 19.21%  |
| 501-1000       | 133       | 12.22%  |
| 51-100         | 86        | 7.9%    |
| More than 3000 | 70        | 6.43%   |
| 1001-2000      | 70        | 6.43%   |
| 1-20           | 69        | 6.34%   |
| Unknown        | 52        | 4.78%   |
| 21-50          | 42        | 3.86%   |
| 2001-3000      | 35        | 3.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 429       | 38.3%   |
| 21-50          | 188       | 16.79%  |
| 51-100         | 117       | 10.45%  |
| 101-250        | 114       | 10.18%  |
| 251-500        | 67        | 5.98%   |
| 501-1000       | 63        | 5.63%   |
| Unknown        | 52        | 4.64%   |
| 1001-2000      | 40        | 3.57%   |
| More than 3000 | 28        | 2.5%    |
| 2001-3000      | 22        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB                         | 3         | 5      | 2.97%   |
| Seagate ST9500325AS 500GB                        | 3         | 4      | 2.97%   |
| Samsung Electronics HD103SJ 1TB                  | 3         | 4      | 2.97%   |
| Kingston SHFS37A120G 120GB SSD                   | 3         | 4      | 2.97%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 1.98%   |
| Micron Technology MTFDDAK512MAM-1K1 512GB SSD    | 2         | 2      | 1.98%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD   | 2         | 4      | 1.98%   |
| Maxtor 7Y250M0 250GB                             | 2         | 2      | 1.98%   |
| HGST HTS725050A7E630 500GB                       | 2         | 2      | 1.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                 | 1         | 1      | 0.99%   |
| WDC WD6400AAKS-07A7B0 640GB                      | 1         | 1      | 0.99%   |
| WDC WD50EZRZ-32RWYB1 5TB                         | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 0.99%   |
| WDC WD5000AAKS-22A7B0 500GB                      | 1         | 1      | 0.99%   |
| WDC WD3200BEVT-22ZCT0 320GB                      | 1         | 1      | 0.99%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 0.99%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 0.99%   |
| WDC WD30EFRX-68EUZN0 3TB                         | 1         | 1      | 0.99%   |
| WDC WD2500AAJS-00V4A0 250GB                      | 1         | 1      | 0.99%   |
| WDC WD2002FAEX-007BA0 2TB                        | 1         | 1      | 0.99%   |
| WDC WD1600BJKT-75F4T0 160GB                      | 1         | 1      | 0.99%   |
| WDC WD10JUCT-63CYNY0 1TB                         | 1         | 1      | 0.99%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 0.99%   |
| WDC WD10EZEX-00WN4A0 1TB                         | 1         | 1      | 0.99%   |
| WDC WD10EADX-22TDHB0 1TB                         | 1         | 1      | 0.99%   |
| WDC WD10EADS-22M2B0 1TB                          | 1         | 1      | 0.99%   |
| Vaseky V800/60G 64GB SSD                         | 1         | 1      | 0.99%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 0.99%   |
| Toshiba MK8052GSX 80GB                           | 1         | 1      | 0.99%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 0.99%   |
| Toshiba MK1652GSX 160GB                          | 1         | 1      | 0.99%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD          | 1         | 1      | 0.99%   |
| Toshiba HDWA120 2TB                              | 1         | 1      | 0.99%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 0.99%   |
| Toshiba DT01ABA200 2TB                           | 1         | 1      | 0.99%   |
| SK hynix PC401 NVMe 512GB                        | 1         | 1      | 0.99%   |
| SK hynix BC711 HFM256GD3JX013N 256GB             | 1         | 1      | 0.99%   |
| Seagate ST9500620NS 500GB                        | 1         | 1      | 0.99%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 0.99%   |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 0.99%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB               | 1         | 1      | 0.99%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 0.99%   |
| Seagate ST500DM002-1BC142 500GB                  | 1         | 1      | 0.99%   |
| Seagate ST3500413AS 500GB                        | 1         | 1      | 0.99%   |
| Seagate ST3250410AS 250GB                        | 1         | 1      | 0.99%   |
| Seagate ST3160318AS 160GB                        | 1         | 1      | 0.99%   |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 0.99%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 0.99%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 0.99%   |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 2      | 0.99%   |
| Seagate ST1000DM003-1CH162 1TB                   | 1         | 1      | 0.99%   |
| SanDisk SD9TN8W-256G-1006 256GB SSD              | 1         | 1      | 0.99%   |
| Samsung Electronics SSD 960 EVO 500GB            | 1         | 1      | 0.99%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 0.99%   |
| Samsung Electronics MZNLN256HAJQ-000H1 256GB SSD | 1         | 1      | 0.99%   |
| Samsung Electronics MZMTD512HAGL-000L1 512GB SSD | 1         | 1      | 0.99%   |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 0.99%   |
| OCZ TRION100 120GB SSD                           | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 22     | 19.19%  |
| Seagate             | 19        | 22     | 19.19%  |
| Toshiba             | 9         | 9      | 9.09%   |
| Hitachi             | 9         | 17     | 9.09%   |
| Samsung Electronics | 8         | 9      | 8.08%   |
| Kingston            | 8         | 9      | 8.08%   |
| Micron Technology   | 5         | 7      | 5.05%   |
| HGST                | 5         | 5      | 5.05%   |
| Intel               | 4         | 4      | 4.04%   |
| Maxtor              | 3         | 3      | 3.03%   |
| SK hynix            | 2         | 2      | 2.02%   |
| Fujitsu             | 2         | 2      | 2.02%   |
| Vaseky              | 1         | 1      | 1.01%   |
| SanDisk             | 1         | 1      | 1.01%   |
| OCZ                 | 1         | 1      | 1.01%   |
| LITEONIT            | 1         | 1      | 1.01%   |
| Corsair             | 1         | 1      | 1.01%   |
| ATP                 | 1         | 1      | 1.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 27.94%  |
| WDC                 | 18        | 21     | 26.47%  |
| Hitachi             | 9         | 17     | 13.24%  |
| Toshiba             | 8         | 8      | 11.76%  |
| HGST                | 5         | 5      | 7.35%   |
| Samsung Electronics | 4         | 5      | 5.88%   |
| Maxtor              | 3         | 3      | 4.41%   |
| Fujitsu             | 2         | 2      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 67        | 83     | 68.37%  |
| SSD  | 27        | 30     | 27.55%  |
| NVMe | 4         | 4      | 4.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 599       | 1268   | 53.24%  |
| Works    | 429       | 900    | 38.13%  |
| Malfunc  | 96        | 117    | 8.53%   |
| Failed   | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 671       | 51.3%   |
| AMD                              | 227       | 17.35%  |
| Samsung Electronics              | 120       | 9.17%   |
| SK hynix                         | 35        | 2.68%   |
| SanDisk                          | 35        | 2.68%   |
| Nvidia                           | 32        | 2.45%   |
| ASMedia Technology               | 32        | 2.45%   |
| JMicron Technology               | 23        | 1.76%   |
| Kingston Technology Company      | 22        | 1.68%   |
| Toshiba America Info Systems     | 20        | 1.53%   |
| Phison Electronics               | 18        | 1.38%   |
| ADATA Technology                 | 14        | 1.07%   |
| Marvell Technology Group         | 11        | 0.84%   |
| KIOXIA                           | 9         | 0.69%   |
| VIA Technologies                 | 6         | 0.46%   |
| Micron Technology                | 5         | 0.38%   |
| Seagate Technology               | 4         | 0.31%   |
| Union Memory (Shenzhen)          | 3         | 0.23%   |
| Silicon Integrated Systems [SiS] | 3         | 0.23%   |
| Realtek Semiconductor            | 3         | 0.23%   |
| LSI Logic / Symbios Logic        | 3         | 0.23%   |
| Broadcom / LSI                   | 3         | 0.23%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Lenovo                           | 2         | 0.15%   |
| Silicon Motion                   | 1         | 0.08%   |
| Micron/Crucial Technology        | 1         | 0.08%   |
| Lite-On Technology               | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |
| Adaptec                          | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 149       | 9.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 73        | 4.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 56        | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 43        | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 43        | 2.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 41        | 2.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 40        | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 34        | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 33        | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 33        | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 30        | 1.93%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 30        | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 30        | 1.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 24        | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 24        | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 23        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 22        | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 21        | 1.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 20        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 19        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 18        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 18        | 1.16%   |
| Intel SSD 660P Series                                                            | 17        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                           | 17        | 1.1%    |
| Intel SATA Controller [RAID mode]                                                | 15        | 0.97%   |
| Kingston Company A2000 NVMe SSD                                                  | 14        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 14        | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 13        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 13        | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 0.84%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 0.84%   |
| AMD 300 Series Chipset SATA Controller                                           | 13        | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 13        | 0.84%   |
| Phison E12 NVMe Controller                                                       | 12        | 0.77%   |
| Nvidia MCP61 SATA Controller                                                     | 12        | 0.77%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 11        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 0.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 0.71%   |
| SK hynix Gold P31 SSD                                                            | 10        | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                               | 10        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 0.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 9         | 0.58%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 9         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 9         | 0.58%   |
| Nvidia MCP61 IDE                                                                 | 8         | 0.52%   |
| JMicron JMB368 IDE controller                                                    | 8         | 0.52%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 8         | 0.52%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.52%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 8         | 0.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 7         | 0.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 7         | 0.45%   |
| SK hynix Non-Volatile memory controller                                          | 6         | 0.39%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 798       | 59.91%  |
| NVMe | 302       | 22.67%  |
| IDE  | 174       | 13.06%  |
| RAID | 52        | 3.9%    |
| SAS  | 4         | 0.3%    |
| SCSI | 2         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 757       | 72.51%  |
| AMD          | 277       | 26.53%  |
| ARM          | 8         | 0.77%   |
| QUALCOMM     | 1         | 0.1%    |
| CentaurHauls | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 14        | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 13        | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 13        | 1.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 12        | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 11        | 1.05%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 11        | 1.05%   |
| AMD Ryzen 5 3600 6-Core Processor           | 11        | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 10        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 9         | 0.86%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 8         | 0.76%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 8         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 0.67%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 7         | 0.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 7         | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7         | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7         | 0.67%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 7         | 0.67%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 7         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 6         | 0.57%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 6         | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6         | 0.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 6         | 0.57%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 0.57%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 6         | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6         | 0.57%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 6         | 0.57%   |
| ARM Processor                               | 6         | 0.57%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6         | 0.57%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6         | 0.57%   |
| AMD FX-8350 Eight-Core Processor            | 6         | 0.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5         | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5         | 0.48%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5         | 0.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5         | 0.48%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 5         | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 5         | 0.48%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 5         | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 5         | 0.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 0.48%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5         | 0.48%   |
| AMD Phenom II X4 965 Processor              | 5         | 0.48%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 0.38%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.38%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 0.38%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 4         | 0.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4         | 0.38%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 4         | 0.38%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 0.38%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4         | 0.38%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 0.38%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 4         | 0.38%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 4         | 0.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 0.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 0.38%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 0.38%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 4         | 0.38%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 261       | 25%     |
| Intel Core i7                        | 187       | 17.91%  |
| Intel Core i3                        | 61        | 5.84%   |
| Intel Core 2 Duo                     | 55        | 5.27%   |
| Intel Celeron                        | 51        | 4.89%   |
| AMD Ryzen 7                          | 51        | 4.89%   |
| AMD Ryzen 5                          | 51        | 4.89%   |
| Intel Pentium                        | 30        | 2.87%   |
| Other                                | 28        | 2.68%   |
| Intel Xeon                           | 23        | 2.2%    |
| AMD Ryzen 9                          | 21        | 2.01%   |
| Intel Atom                           | 18        | 1.72%   |
| AMD FX                               | 18        | 1.72%   |
| Intel Pentium Dual-Core              | 14        | 1.34%   |
| AMD Athlon II X2                     | 12        | 1.15%   |
| AMD Ryzen 3                          | 11        | 1.05%   |
| AMD Phenom II X4                     | 10        | 0.96%   |
| AMD E1                               | 10        | 0.96%   |
| AMD Athlon 64 X2                     | 9         | 0.86%   |
| AMD Ryzen 7 PRO                      | 8         | 0.77%   |
| Intel Genuine                        | 7         | 0.67%   |
| AMD A8                               | 7         | 0.67%   |
| AMD A10                              | 7         | 0.67%   |
| Intel Core 2 Quad                    | 6         | 0.57%   |
| Intel Core 2                         | 6         | 0.57%   |
| AMD A4                               | 6         | 0.57%   |
| Intel Core i9                        | 5         | 0.48%   |
| AMD Phenom                           | 5         | 0.48%   |
| Intel Pentium Dual                   | 4         | 0.38%   |
| Intel Pentium 4                      | 3         | 0.29%   |
| AMD Turion 64 X2 Mobile              | 3         | 0.29%   |
| AMD EPYC                             | 3         | 0.29%   |
| AMD Athlon II X4                     | 3         | 0.29%   |
| AMD Athlon                           | 3         | 0.29%   |
| AMD A6                               | 3         | 0.29%   |
| Intel Core Duo                       | 2         | 0.19%   |
| ARM BCM                              | 2         | 0.19%   |
| AMD Turion X2 Dual-Core Mobile       | 2         | 0.19%   |
| AMD Turion                           | 2         | 0.19%   |
| AMD Sempron                          | 2         | 0.19%   |
| AMD Ryzen Threadripper               | 2         | 0.19%   |
| AMD Ryzen 3 PRO                      | 2         | 0.19%   |
| AMD Phenom II X6                     | 2         | 0.19%   |
| AMD E2                               | 2         | 0.19%   |
| AMD Athlon II Dual-Core              | 2         | 0.19%   |
| AMD A12                              | 2         | 0.19%   |
| QUALCOMM AArch64                     | 1         | 0.1%    |
| Intel Xeon Gold                      | 1         | 0.1%    |
| Intel Pentium M                      | 1         | 0.1%    |
| Intel Core m5                        | 1         | 0.1%    |
| Intel Celeron M                      | 1         | 0.1%    |
| Intel Celeron Dual-Core              | 1         | 0.1%    |
| CentaurHauls VIA C7                  | 1         | 0.1%    |
| AMD Turion II Ultra Dual-Core Mobile | 1         | 0.1%    |
| AMD Turion II Neo                    | 1         | 0.1%    |
| AMD Turion 64 X2                     | 1         | 0.1%    |
| AMD Turion 64 Mobile                 | 1         | 0.1%    |
| AMD Ryzen 5 PRO                      | 1         | 0.1%    |
| AMD PRO A10                          | 1         | 0.1%    |
| AMD Mobile Sempron                   | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 439       | 42.01%  |
| 4      | 389       | 37.22%  |
| 6      | 81        | 7.75%   |
| 8      | 66        | 6.32%   |
| 1      | 24        | 2.3%    |
| 12     | 16        | 1.53%   |
| 3      | 11        | 1.05%   |
| 16     | 10        | 0.96%   |
| 10     | 3         | 0.29%   |
| 24     | 2         | 0.19%   |
| 80     | 1         | 0.1%    |
| 32     | 1         | 0.1%    |
| 14     | 1         | 0.1%    |
| 5      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1043      | 99.9%   |
| 2      | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 639       | 61.09%  |
| 1      | 407       | 38.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1018      | 97.14%  |
| Unknown        | 19        | 1.81%   |
| 32-bit         | 11        | 1.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 234       | 21.87%  |
| 0x206a7    | 68        | 6.36%   |
| 0x306a9    | 58        | 5.42%   |
| 0x306c3    | 53        | 4.95%   |
| 0x1067a    | 41        | 3.83%   |
| 0x506e3    | 35        | 3.27%   |
| 0x806ec    | 30        | 2.8%    |
| 0x40651    | 24        | 2.24%   |
| 0x806ea    | 23        | 2.15%   |
| 0x406e3    | 22        | 2.06%   |
| 0x906ea    | 19        | 1.78%   |
| 0x08701021 | 18        | 1.68%   |
| 0x906e9    | 17        | 1.59%   |
| 0x20655    | 16        | 1.5%    |
| 0x30678    | 15        | 1.4%    |
| 0x20652    | 14        | 1.31%   |
| 0x10676    | 14        | 1.31%   |
| 0x806e9    | 13        | 1.21%   |
| 0x6fd      | 13        | 1.21%   |
| 0x406c4    | 13        | 1.21%   |
| 0x0800820d | 13        | 1.21%   |
| 0x306d4    | 12        | 1.12%   |
| 0x0a201016 | 12        | 1.12%   |
| 0x08701013 | 12        | 1.12%   |
| 0x06000852 | 12        | 1.12%   |
| 0x010000c8 | 12        | 1.12%   |
| 0x806c1    | 10        | 0.93%   |
| 0x6fb      | 10        | 0.93%   |
| 0xa0652    | 8         | 0.75%   |
| 0x906eb    | 8         | 0.75%   |
| 0x506c9    | 8         | 0.75%   |
| 0x08600106 | 7         | 0.65%   |
| 0x08108102 | 7         | 0.65%   |
| 0x06001119 | 7         | 0.65%   |
| 0x906ed    | 6         | 0.56%   |
| 0x806eb    | 6         | 0.56%   |
| 0x706e5    | 6         | 0.56%   |
| 0x05000119 | 6         | 0.56%   |
| 0x706a1    | 5         | 0.47%   |
| 0x0a201009 | 5         | 0.47%   |
| 0x08600103 | 5         | 0.47%   |
| 0x0810100b | 5         | 0.47%   |
| 0x08001138 | 5         | 0.47%   |
| 0x08001137 | 5         | 0.47%   |
| 0x06006705 | 5         | 0.47%   |
| 0x806d1    | 4         | 0.37%   |
| 0x6f6      | 4         | 0.37%   |
| 0x406c3    | 4         | 0.37%   |
| 0x106e5    | 4         | 0.37%   |
| 0x106ca    | 4         | 0.37%   |
| 0x106a5    | 4         | 0.37%   |
| 0x0a50000b | 4         | 0.37%   |
| 0x010000db | 4         | 0.37%   |
| 0xf41      | 3         | 0.28%   |
| 0xa0653    | 3         | 0.28%   |
| 0x906ec    | 3         | 0.28%   |
| 0x6fa      | 3         | 0.28%   |
| 0x6e8      | 3         | 0.28%   |
| 0x206d7    | 3         | 0.28%   |
| 0x08108109 | 3         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 155       | 14.82%  |
| Haswell          | 106       | 10.13%  |
| SandyBridge      | 89        | 8.51%   |
| Skylake          | 71        | 6.79%   |
| IvyBridge        | 69        | 6.6%    |
| Penryn           | 58        | 5.54%   |
| Zen 2            | 54        | 5.16%   |
| Core             | 39        | 3.73%   |
| K10              | 37        | 3.54%   |
| Silvermont       | 36        | 3.44%   |
| Zen+             | 33        | 3.15%   |
| Zen              | 33        | 3.15%   |
| Westmere         | 33        | 3.15%   |
| Zen 3            | 30        | 2.87%   |
| Piledriver       | 24        | 2.29%   |
| K8 Hammer        | 19        | 1.82%   |
| Unknown          | 17        | 1.63%   |
| CometLake        | 16        | 1.53%   |
| Broadwell        | 15        | 1.43%   |
| TigerLake        | 13        | 1.24%   |
| Icelake          | 11        | 1.05%   |
| Nehalem          | 10        | 0.96%   |
| Goldmont         | 10        | 0.96%   |
| Excavator        | 10        | 0.96%   |
| Puma             | 7         | 0.67%   |
| Bobcat           | 7         | 0.67%   |
| P6               | 6         | 0.57%   |
| Jaguar           | 6         | 0.57%   |
| Goldmont plus    | 6         | 0.57%   |
| Bonnell          | 6         | 0.57%   |
| Steamroller      | 5         | 0.48%   |
| NetBurst         | 5         | 0.48%   |
| K8 & K10 hybrid  | 4         | 0.38%   |
| Bulldozer        | 4         | 0.38%   |
| K10 Llano        | 1         | 0.1%    |
| Alderlake Hybrid | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 550       | 46.45%  |
| Nvidia                                       | 345       | 29.14%  |
| AMD                                          | 265       | 22.38%  |
| ASPEED Technology                            | 12        | 1.01%   |
| Matrox Electronics Systems                   | 4         | 0.34%   |
| Silicon Motion                               | 3         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.25%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.08%   |
| VIA Technologies                             | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 64        | 5.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 38        | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 2.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 2.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26        | 2.11%   |
| Intel UHD Graphics 620                                                                   | 25        | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 1.71%   |
| Intel HD Graphics 530                                                                    | 21        | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.54%   |
| Intel HD Graphics 620                                                                    | 17        | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.38%   |
| AMD Renoir                                                                               | 16        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15        | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.06%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 0.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10        | 0.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.81%   |
| Intel HD Graphics 630                                                                    | 10        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.73%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 8         | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 7         | 0.57%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7         | 0.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 0.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.57%   |
| Intel HD Graphics 500                                                                    | 7         | 0.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.49%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.49%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6         | 0.49%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.49%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 6         | 0.49%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 5         | 0.41%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 5         | 0.41%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 5         | 0.41%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 5         | 0.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.41%   |
| AMD RS880 [Radeon HD 4200]                                                               | 5         | 0.41%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 5         | 0.41%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 5         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 425       | 40.32%  |
| 1 x Nvidia         | 238       | 22.58%  |
| 1 x AMD            | 217       | 20.59%  |
| Intel + Nvidia     | 90        | 8.54%   |
| Intel + AMD        | 18        | 1.71%   |
| 2 x AMD            | 17        | 1.61%   |
| 1 x ASPEED         | 12        | 1.14%   |
| AMD + Nvidia       | 12        | 1.14%   |
| Other              | 8         | 0.76%   |
| 2 x Nvidia         | 4         | 0.38%   |
| 1 x SiS            | 3         | 0.28%   |
| 1 x Silicon Motion | 3         | 0.28%   |
| 1 x Matrox         | 3         | 0.28%   |
| 2 x Intel          | 1         | 0.09%   |
| 1 x XGI            | 1         | 0.09%   |
| 1 x VIA            | 1         | 0.09%   |
| Nvidia + Matrox    | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 799       | 75.38%  |
| Proprietary | 204       | 19.25%  |
| Unknown     | 57        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 555       | 51.97%  |
| 0.01-0.5   | 128       | 11.99%  |
| 1.01-2.0   | 123       | 11.52%  |
| 0.51-1.0   | 81        | 7.58%   |
| 3.01-4.0   | 76        | 7.12%   |
| 7.01-8.0   | 62        | 5.81%   |
| 5.01-6.0   | 22        | 2.06%   |
| 2.01-3.0   | 10        | 0.94%   |
| 8.01-16.0  | 9         | 0.84%   |
| 16.01-24.0 | 2         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 171       | 14.78%  |
| AU Optronics            | 129       | 11.15%  |
| LG Display              | 106       | 9.16%   |
| Chimei Innolux          | 66        | 5.7%    |
| Dell                    | 63        | 5.45%   |
| BenQ                    | 61        | 5.27%   |
| Hewlett-Packard         | 55        | 4.75%   |
| BOE                     | 52        | 4.49%   |
| Acer                    | 49        | 4.24%   |
| Lenovo                  | 48        | 4.15%   |
| Ancor Communications    | 45        | 3.89%   |
| Goldstar                | 44        | 3.8%    |
| Fujitsu Siemens         | 20        | 1.73%   |
| Philips                 | 19        | 1.64%   |
| Apple                   | 18        | 1.56%   |
| AOC                     | 18        | 1.56%   |
| Sony                    | 17        | 1.47%   |
| Sharp                   | 16        | 1.38%   |
| ASUSTek Computer        | 16        | 1.38%   |
| ViewSonic               | 13        | 1.12%   |
| InfoVision              | 13        | 1.12%   |
| Eizo                    | 9         | 0.78%   |
| Chi Mei Optoelectronics | 9         | 0.78%   |
| LG Philips              | 8         | 0.69%   |
| Vestel Elektronik       | 6         | 0.52%   |
| Unknown                 | 6         | 0.52%   |
| Toshiba                 | 6         | 0.52%   |
| Panasonic               | 5         | 0.43%   |
| LG Electronics          | 5         | 0.43%   |
| CSO                     | 5         | 0.43%   |
| CPT                     | 4         | 0.35%   |
| PANDA                   | 3         | 0.26%   |
| Packard Bell            | 3         | 0.26%   |
| NEC Computers           | 3         | 0.26%   |
| Lenovo Group Limited    | 3         | 0.26%   |
| Iiyama                  | 3         | 0.26%   |
| IBM                     | 3         | 0.26%   |
| FUS                     | 3         | 0.26%   |
| Onkyo                   | 2         | 0.17%   |
| LGD                     | 2         | 0.17%   |
| DENON                   | 2         | 0.17%   |
| AUS                     | 2         | 0.17%   |
| Arnos Instruments       | 2         | 0.17%   |
| YTH                     | 1         | 0.09%   |
| Unknown (CEC)           | 1         | 0.09%   |
| Unknown (1080)          | 1         | 0.09%   |
| TVT                     | 1         | 0.09%   |
| Tech Concepts           | 1         | 0.09%   |
| STA                     | 1         | 0.09%   |
| SFX                     | 1         | 0.09%   |
| Quanta Display          | 1         | 0.09%   |
| QCM                     | 1         | 0.09%   |
| PKB                     | 1         | 0.09%   |
| Optoma                  | 1         | 0.09%   |
| NXG                     | 1         | 0.09%   |
| NEX                     | 1         | 0.09%   |
| MSI                     | 1         | 0.09%   |
| Marantz                 | 1         | 0.09%   |
| JDI                     | 1         | 0.09%   |
| Idek Iiyama             | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 7         | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 7         | 0.58%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 6         | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 6         | 0.5%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 5         | 0.42%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch   | 4         | 0.33%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch            | 4         | 0.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                | 4         | 0.33%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 4         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch       | 4         | 0.33%   |
| BenQ ZOWIE XL LCD BNQ7F32 1920x1080 531x298mm 24.0-inch                | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch          | 4         | 0.33%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 4         | 0.33%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 4         | 0.33%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 3         | 0.25%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch      | 3         | 0.25%   |
| Samsung Electronics T24D390 SAM0B6C 1920x1080 521x293mm 23.5-inch      | 3         | 0.25%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 3         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 3         | 0.25%   |
| Samsung Electronics CF791 SAM0DC4 3440x1440 797x333mm 34.0-inch        | 3         | 0.25%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 3         | 0.25%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 3         | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 3         | 0.25%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 3         | 0.25%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch           | 3         | 0.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 3         | 0.25%   |
| Lenovo LEN L27q-10 LEN65CE 2560x1440 597x336mm 27.0-inch               | 3         | 0.25%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 3         | 0.25%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                | 3         | 0.25%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                | 3         | 0.25%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                  | 3         | 0.25%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch            | 3         | 0.25%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch           | 3         | 0.25%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 3         | 0.25%   |
| Goldstar E1910      GSM4BEA 1280x1024 370x300mm 18.8-inch              | 3         | 0.25%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch           | 3         | 0.25%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 3         | 0.25%   |
| CPT LCD Monitor CPT1464 1440x900 331x207mm 15.4-inch                   | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.25%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 3         | 0.25%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                     | 3         | 0.25%   |
| BenQ G2400W BNQ780A 1920x1200 519x324mm 24.1-inch                      | 3         | 0.25%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                     | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch          | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch          | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch          | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch          | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch         | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch          | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch          | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 457       | 40.84%  |
| 1366x768 (WXGA)    | 139       | 12.42%  |
| 2560x1440 (QHD)    | 69        | 6.17%   |
| 3840x2160 (4K)     | 68        | 6.08%   |
| 1920x1200 (WUXGA)  | 60        | 5.36%   |
| 1680x1050 (WSXGA+) | 52        | 4.65%   |
| 1600x900 (HD+)     | 50        | 4.47%   |
| 1280x1024 (SXGA)   | 43        | 3.84%   |
| 1440x900 (WXGA+)   | 29        | 2.59%   |
| 1280x800 (WXGA)    | 29        | 2.59%   |
| Unknown            | 25        | 2.23%   |
| 3440x1440          | 16        | 1.43%   |
| 1360x768           | 13        | 1.16%   |
| 3840x1080          | 9         | 0.8%    |
| 3840x2400          | 6         | 0.54%   |
| 4480x1440          | 4         | 0.36%   |
| 1920x540           | 4         | 0.36%   |
| 1280x720 (HD)      | 4         | 0.36%   |
| 1024x600           | 4         | 0.36%   |
| 3200x1800 (QHD+)   | 3         | 0.27%   |
| 2560x1600          | 3         | 0.27%   |
| 2560x1080          | 3         | 0.27%   |
| 1600x1200          | 3         | 0.27%   |
| 5760x2160          | 2         | 0.18%   |
| 5120x1440          | 2         | 0.18%   |
| 3840x1200          | 2         | 0.18%   |
| 3360x1050          | 2         | 0.18%   |
| 1400x1050          | 2         | 0.18%   |
| 5760x1440          | 1         | 0.09%   |
| 5280x1080          | 1         | 0.09%   |
| 3840x1600          | 1         | 0.09%   |
| 3520x1200          | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2880x1800          | 1         | 0.09%   |
| 2800x1752          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2304x1440          | 1         | 0.09%   |
| 2160x1200          | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |
| 1834x1031          | 1         | 0.09%   |
| 1826x1027          | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1360x765           | 1         | 0.09%   |
| 1024x768 (XGA)     | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 216       | 18.88%  |
| 24      | 121       | 10.58%  |
| 13      | 104       | 9.09%   |
| 14      | 93        | 8.13%   |
| 27      | 89        | 7.78%   |
| 23      | 88        | 7.69%   |
| Unknown | 85        | 7.43%   |
| 17      | 55        | 4.81%   |
| 22      | 36        | 3.15%   |
| 19      | 36        | 3.15%   |
| 12      | 31        | 2.71%   |
| 21      | 27        | 2.36%   |
| 31      | 23        | 2.01%   |
| 84      | 19        | 1.66%   |
| 34      | 15        | 1.31%   |
| 18      | 14        | 1.22%   |
| 11      | 13        | 1.14%   |
| 20      | 11        | 0.96%   |
| 25      | 10        | 0.87%   |
| 72      | 9         | 0.79%   |
| 32      | 9         | 0.79%   |
| 40      | 5         | 0.44%   |
| 65      | 4         | 0.35%   |
| 54      | 4         | 0.35%   |
| 28      | 4         | 0.35%   |
| 26      | 4         | 0.35%   |
| 10      | 4         | 0.35%   |
| 55      | 3         | 0.26%   |
| 46      | 2         | 0.17%   |
| 16      | 2         | 0.17%   |
| 66      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 47      | 1         | 0.09%   |
| 39      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 36      | 1         | 0.09%   |
| 33      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 362       | 32.61%  |
| 501-600     | 270       | 24.32%  |
| 201-300     | 100       | 9.01%   |
| 351-400     | 89        | 8.02%   |
| 401-500     | 88        | 7.93%   |
| Unknown     | 85        | 7.66%   |
| 601-700     | 41        | 3.69%   |
| 1501-2000   | 28        | 2.52%   |
| 701-800     | 26        | 2.34%   |
| 1001-1500   | 14        | 1.26%   |
| 801-900     | 7         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 703       | 67.99%  |
| 16/10   | 179       | 17.31%  |
| Unknown | 70        | 6.77%   |
| 5/4     | 42        | 4.06%   |
| 21/9    | 18        | 1.74%   |
| 3/2     | 8         | 0.77%   |
| 4/3     | 7         | 0.68%   |
| 32/9    | 4         | 0.39%   |
| 6/5     | 2         | 0.19%   |
| 0.45    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 216       | 19.22%  |
| 201-250        | 197       | 17.53%  |
| 81-90          | 154       | 13.7%   |
| 301-350        | 92        | 8.19%   |
| Unknown        | 85        | 7.56%   |
| 251-300        | 65        | 5.78%   |
| 151-200        | 58        | 5.16%   |
| 351-500        | 51        | 4.54%   |
| 71-80          | 42        | 3.74%   |
| More than 1000 | 39        | 3.47%   |
| 121-130        | 39        | 3.47%   |
| 61-70          | 31        | 2.76%   |
| 141-150        | 17        | 1.51%   |
| 51-60          | 13        | 1.16%   |
| 501-1000       | 12        | 1.07%   |
| 131-140        | 6         | 0.53%   |
| 41-50          | 4         | 0.36%   |
| 111-120        | 3         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 394       | 36.01%  |
| 121-160       | 296       | 27.06%  |
| 101-120       | 233       | 21.3%   |
| Unknown       | 85        | 7.77%   |
| 161-240       | 40        | 3.66%   |
| 1-50          | 26        | 2.38%   |
| More than 240 | 20        | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 812       | 75.89%  |
| 2     | 176       | 16.45%  |
| 0     | 60        | 5.61%   |
| 3     | 20        | 1.87%   |
| 4     | 2         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 559       | 35.42%  |
| Realtek Semiconductor                  | 463       | 29.34%  |
| Qualcomm Atheros                       | 150       | 9.51%   |
| Broadcom                               | 84        | 5.32%   |
| Huawei Technologies                    | 25        | 1.58%   |
| Nvidia                                 | 24        | 1.52%   |
| Marvell Technology Group               | 23        | 1.46%   |
| Ralink                                 | 21        | 1.33%   |
| Ericsson Business Mobile Networks      | 18        | 1.14%   |
| TP-Link                                | 17        | 1.08%   |
| Hewlett-Packard                        | 14        | 0.89%   |
| Broadcom Limited                       | 14        | 0.89%   |
| ASUSTek Computer                       | 14        | 0.89%   |
| MediaTek                               | 13        | 0.82%   |
| Samsung Electronics                    | 12        | 0.76%   |
| Ralink Technology                      | 12        | 0.76%   |
| ZyXEL Communications                   | 7         | 0.44%   |
| Dell                                   | 7         | 0.44%   |
| Lenovo                                 | 6         | 0.38%   |
| Sierra Wireless                        | 5         | 0.32%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.32%   |
| Microsoft                              | 5         | 0.32%   |
| Fibocom                                | 5         | 0.32%   |
| D-Link System                          | 5         | 0.32%   |
| Motorola PCS                           | 4         | 0.25%   |
| Microchip Technology                   | 4         | 0.25%   |
| ASIX Electronics                       | 4         | 0.25%   |
| Xiaomi                                 | 3         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.19%   |
| HMD Global                             | 3         | 0.19%   |
| Gemtek                                 | 3         | 0.19%   |
| BUFFALO                                | 3         | 0.19%   |
| 3Com                                   | 3         | 0.19%   |
| Qualcomm                               | 2         | 0.13%   |
| Linksys                                | 2         | 0.13%   |
| Edimax Technology                      | 2         | 0.13%   |
| DisplayLink                            | 2         | 0.13%   |
| D-Link                                 | 2         | 0.13%   |
| Aquantia                               | 2         | 0.13%   |
| ZyDAS                                  | 1         | 0.06%   |
| VIA Technologies                       | 1         | 0.06%   |
| Van Ooijen Technische Informatica      | 1         | 0.06%   |
| U-Blox                                 | 1         | 0.06%   |
| Texas Instruments                      | 1         | 0.06%   |
| Standard Microsystems                  | 1         | 0.06%   |
| SEGGER                                 | 1         | 0.06%   |
| Seeed Technology                       | 1         | 0.06%   |
| Realtek                                | 1         | 0.06%   |
| Qualcomm Atheros Communications        | 1         | 0.06%   |
| Primax Electronics                     | 1         | 0.06%   |
| NetGear                                | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Google                                 | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| Fairphone                              | 1         | 0.06%   |
| Dresden Elektronik                     | 1         | 0.06%   |
| dog hunter                             | 1         | 0.06%   |
| Comneon                                | 1         | 0.06%   |
| Bluegiga Technologies                  | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 350       | 18.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 67        | 3.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 40        | 2.1%    |
| Intel Wi-Fi 6 AX200                                                     | 36        | 1.89%   |
| Intel I211 Gigabit Network Connection                                   | 36        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 34        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 28        | 1.47%   |
| Intel Wireless 8265 / 8275                                              | 28        | 1.47%   |
| Intel Wireless 7260                                                     | 28        | 1.47%   |
| Intel Wireless 8260                                                     | 24        | 1.26%   |
| Intel Ethernet Connection (2) I219-V                                    | 23        | 1.21%   |
| Intel Wireless 7265                                                     | 22        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 19        | 1%      |
| Intel Ethernet Connection I217-LM                                       | 19        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 19        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                       | 16        | 0.84%   |
| Intel I210 Gigabit Network Connection                                   | 16        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                   | 15        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                    | 14        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                 | 14        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 0.68%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 0.63%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 0.58%   |
| Nvidia MCP61 Ethernet                                                   | 11        | 0.58%   |
| Intel Ethernet Connection I218-LM                                       | 11        | 0.58%   |
| Intel Ethernet Connection I217-V                                        | 11        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 0.58%   |
| Intel Wireless 3165                                                     | 10        | 0.53%   |
| Intel Ethernet Connection I219-V                                        | 10        | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                   | 10        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 10        | 0.53%   |
| Intel 82566MM Gigabit Network Connection                                | 10        | 0.53%   |
| Huawei JNY-LX1                                                          | 10        | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.47%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.47%   |
| Intel Wireless 3160                                                     | 9         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                                    | 9         | 0.47%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 8         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 0.42%   |
| Intel Ethernet Controller I225-V                                        | 8         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                                    | 8         | 0.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.42%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.42%   |
| Intel 82567LM Gigabit Network Connection                                | 8         | 0.42%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 373       | 47.28%  |
| Qualcomm Atheros                  | 122       | 15.46%  |
| Realtek Semiconductor             | 104       | 13.18%  |
| Broadcom                          | 57        | 7.22%   |
| Ralink                            | 21        | 2.66%   |
| TP-Link                           | 17        | 2.15%   |
| ASUSTek Computer                  | 14        | 1.77%   |
| Ralink Technology                 | 12        | 1.52%   |
| MediaTek                          | 9         | 1.14%   |
| Broadcom Limited                  | 8         | 1.01%   |
| ZyXEL Communications              | 7         | 0.89%   |
| Microsoft                         | 5         | 0.63%   |
| Fibocom                           | 5         | 0.63%   |
| Ericsson Business Mobile Networks | 5         | 0.63%   |
| Hewlett-Packard                   | 4         | 0.51%   |
| Dell                              | 4         | 0.51%   |
| D-Link System                     | 4         | 0.51%   |
| Sierra Wireless                   | 3         | 0.38%   |
| Gemtek                            | 3         | 0.38%   |
| BUFFALO                           | 3         | 0.38%   |
| Edimax Technology                 | 2         | 0.25%   |
| ZyDAS                             | 1         | 0.13%   |
| Realtek                           | 1         | 0.13%   |
| Qualcomm Atheros Communications   | 1         | 0.13%   |
| NetGear                           | 1         | 0.13%   |
| Marvell Technology Group          | 1         | 0.13%   |
| Linksys                           | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 36        | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 34        | 4.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 28        | 3.54%   |
| Intel Wireless 8265 / 8275                                              | 28        | 3.54%   |
| Intel Wireless 7260                                                     | 28        | 3.54%   |
| Intel Wireless 8260                                                     | 24        | 3.03%   |
| Intel Wireless 7265                                                     | 22        | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 19        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 2.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 2.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 1.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.64%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.39%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.39%   |
| Intel Wireless 3165                                                     | 10        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.14%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.14%   |
| Intel Wireless 3160                                                     | 9         | 1.14%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.01%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 1.01%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 7         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 5         | 0.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 5         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.63%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 5         | 0.63%   |
| Ericsson Business Mobile Networks N5321 gw                              | 5         | 0.63%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]               | 5         | 0.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 4         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.51%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 4         | 0.51%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.51%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 4         | 0.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.51%   |
| Intel WiFi Link 5100                                                    | 4         | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.51%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 4         | 0.51%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 4         | 0.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 4         | 0.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 436       | 42.13%  |
| Intel                                  | 383       | 37%     |
| Qualcomm Atheros                       | 38        | 3.67%   |
| Broadcom                               | 37        | 3.57%   |
| Nvidia                                 | 24        | 2.32%   |
| Marvell Technology Group               | 22        | 2.13%   |
| Huawei Technologies                    | 18        | 1.74%   |
| Samsung Electronics                    | 12        | 1.16%   |
| Lenovo                                 | 6         | 0.58%   |
| Broadcom Limited                       | 6         | 0.58%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.39%   |
| MediaTek                               | 4         | 0.39%   |
| ASIX Electronics                       | 4         | 0.39%   |
| Xiaomi                                 | 3         | 0.29%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.29%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.29%   |
| HMD Global                             | 3         | 0.29%   |
| 3Com                                   | 3         | 0.29%   |
| Sierra Wireless                        | 2         | 0.19%   |
| Qualcomm                               | 2         | 0.19%   |
| Motorola PCS                           | 2         | 0.19%   |
| Hewlett-Packard                        | 2         | 0.19%   |
| DisplayLink                            | 2         | 0.19%   |
| Aquantia                               | 2         | 0.19%   |
| VIA Technologies                       | 1         | 0.1%    |
| TP-Link                                | 1         | 0.1%    |
| Standard Microsystems                  | 1         | 0.1%    |
| Microchip Technology                   | 1         | 0.1%    |
| Linksys                                | 1         | 0.1%    |
| ICS Advent                             | 1         | 0.1%    |
| Google                                 | 1         | 0.1%    |
| Foxconn / Hon Hai                      | 1         | 0.1%    |
| D-Link System                          | 1         | 0.1%    |
| D-Link                                 | 1         | 0.1%    |
| Attansic Technology                    | 1         | 0.1%    |
| American Megatrends                    | 1         | 0.1%    |
| AMD                                    | 1         | 0.1%    |
| ADMtek                                 | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 350       | 33.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 67        | 6.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 3.78%   |
| Intel I211 Gigabit Network Connection                             | 36        | 3.4%    |
| Intel Ethernet Connection (2) I219-V                              | 23        | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 1.51%   |
| Intel I210 Gigabit Network Connection                             | 16        | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 1.42%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 1.32%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.13%   |
| Nvidia MCP61 Ethernet                                             | 11        | 1.04%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 11        | 1.04%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.95%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.95%   |
| Huawei JNY-LX1                                                    | 10        | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 8         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.66%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.57%   |
| Huawei E353/E3131                                                 | 6         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.38%   |
| OnePlus (Shenzhen) OnePlus                                        | 4         | 0.38%   |
| MediaTek moto e6s                                                 | 4         | 0.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 4         | 0.38%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.38%   |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.38%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 4         | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.28%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.28%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.28%   |
| Lenovo ThinkPad Lan                                               | 3         | 0.28%   |
| Intel PRO/100 VE Network Connection                               | 3         | 0.28%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 941       | 54.39%  |
| WiFi     | 740       | 42.77%  |
| Modem    | 45        | 2.6%    |
| Unknown  | 4         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 538       | 51%     |
| Ethernet | 516       | 48.91%  |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 576       | 54.91%  |
| 1     | 421       | 40.13%  |
| 0     | 23        | 2.19%   |
| 3     | 19        | 1.81%   |
| 5     | 5         | 0.48%   |
| 4     | 5         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 906       | 84.51%  |
| Yes  | 166       | 15.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 266       | 45.47%  |
| Broadcom                        | 52        | 8.89%   |
| Realtek Semiconductor           | 46        | 7.86%   |
| Cambridge Silicon Radio         | 37        | 6.32%   |
| Qualcomm Atheros Communications | 36        | 6.15%   |
| ASUSTek Computer                | 33        | 5.64%   |
| IMC Networks                    | 20        | 3.42%   |
| Apple                           | 20        | 3.42%   |
| Foxconn / Hon Hai               | 16        | 2.74%   |
| Hewlett-Packard                 | 13        | 2.22%   |
| Lite-On Technology              | 11        | 1.88%   |
| Dell                            | 8         | 1.37%   |
| Askey Computer                  | 6         | 1.03%   |
| Ralink                          | 4         | 0.68%   |
| Foxconn International           | 4         | 0.68%   |
| HTC (High Tech Computer)        | 3         | 0.51%   |
| Edimax Technology               | 2         | 0.34%   |
| Toshiba                         | 1         | 0.17%   |
| Taiyo Yuden                     | 1         | 0.17%   |
| Realtek                         | 1         | 0.17%   |
| MediaTek                        | 1         | 0.17%   |
| Marvell Semiconductor           | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |
| Belkin Components               | 1         | 0.17%   |
| Alps Electric                   | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 117       | 20%     |
| Intel AX201 Bluetooth                                                | 42        | 7.18%   |
| Intel AX200 Bluetooth                                                | 39        | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 37        | 6.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 32        | 5.47%   |
| Realtek Bluetooth Radio                                              | 23        | 3.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 19        | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 14        | 2.39%   |
| Qualcomm Atheros  Bluetooth Device                                   | 14        | 2.39%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 13        | 2.22%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 12        | 2.05%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 10        | 1.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 10        | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 8         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 8         | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8         | 1.37%   |
| IMC Networks Bluetooth Device                                        | 7         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                                     | 7         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 7         | 1.2%    |
| Apple Bluetooth USB Host Controller                                  | 7         | 1.2%    |
| IMC Networks Bluetooth Radio                                         | 6         | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 6         | 1.03%   |
| Broadcom HP Portable Bumble Bee                                      | 6         | 1.03%   |
| Askey Bluetooth Device                                               | 6         | 1.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 1.03%   |
| Realtek RTL8723B Bluetooth                                           | 5         | 0.85%   |
| Lite-On Bluetooth Device                                             | 5         | 0.85%   |
| Ralink RT3290 Bluetooth                                              | 4         | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module                    | 4         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 4         | 0.68%   |
| Broadcom BCM2045 Bluetooth                                           | 4         | 0.68%   |
| Apple Bluetooth Host Controller                                      | 4         | 0.68%   |
| Realtek RTL8821A Bluetooth                                           | 3         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3         | 0.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 3         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 3         | 0.51%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                                     | 3         | 0.51%   |
| Broadcom HP Portable SoftSailing                                     | 3         | 0.51%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 3         | 0.51%   |
| ASUS Bluetooth Radio                                                 | 3         | 0.51%   |
| Apple Bluetooth HCI                                                  | 3         | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                     | 2         | 0.34%   |
| Intel AX210 Bluetooth                                                | 2         | 0.34%   |
| IMC Networks Wireless_Device                                         | 2         | 0.34%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2         | 0.34%   |
| Foxconn / Hon Hai BT                                                 | 2         | 0.34%   |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 0.34%   |
| Foxconn / Hon Hai Acer Bluetooth module                              | 2         | 0.34%   |
| Edimax Bluetooth Adapter                                             | 2         | 0.34%   |
| Dell Wireless 370 Bluetooth Mini-card                                | 2         | 0.34%   |
| Dell DW375 Bluetooth Module                                          | 2         | 0.34%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                                | 2         | 0.34%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 2         | 0.34%   |
| Broadcom BCM2070 Bluetooth Device                                    | 2         | 0.34%   |
| ASUS Bluetooth Adapter                                               | 2         | 0.34%   |
| ASUS BCM20702A0                                                      | 2         | 0.34%   |
| ASUS ASUS USB-BT500                                                  | 2         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 706       | 48.06%  |
| AMD                                  | 301       | 20.49%  |
| Nvidia                               | 286       | 19.47%  |
| C-Media Electronics                  | 23        | 1.57%   |
| Logitech                             | 13        | 0.88%   |
| Creative Labs                        | 11        | 0.75%   |
| ASUSTek Computer                     | 8         | 0.54%   |
| GN Netcom                            | 7         | 0.48%   |
| SteelSeries ApS                      | 6         | 0.41%   |
| Kingston Technology                  | 6         | 0.41%   |
| Creative Technology                  | 6         | 0.41%   |
| VIA Technologies                     | 5         | 0.34%   |
| Texas Instruments                    | 5         | 0.34%   |
| RODE Microphones                     | 5         | 0.34%   |
| Realtek Semiconductor                | 5         | 0.34%   |
| Razer USA                            | 4         | 0.27%   |
| Plantronics                          | 4         | 0.27%   |
| GYROCOM C&C                          | 4         | 0.27%   |
| Focusrite-Novation                   | 4         | 0.27%   |
| Blue Microphones                     | 4         | 0.27%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.2%    |
| Silicon Integrated Systems [SiS]     | 3         | 0.2%    |
| M-Audio                              | 3         | 0.2%    |
| Lenovo                               | 3         | 0.2%    |
| Corsair                              | 3         | 0.2%    |
| Sennheiser Communications            | 2         | 0.14%   |
| Microsoft                            | 2         | 0.14%   |
| Hewlett-Packard                      | 2         | 0.14%   |
| DigiTech                             | 2         | 0.14%   |
| Cambridge Audio                      | 2         | 0.14%   |
| AudioQuest                           | 2         | 0.14%   |
| ZOOM                                 | 1         | 0.07%   |
| Yamaha                               | 1         | 0.07%   |
| XMOS                                 | 1         | 0.07%   |
| Turtle Beach                         | 1         | 0.07%   |
| Trust                                | 1         | 0.07%   |
| Thomann                              | 1         | 0.07%   |
| Tenx Technology                      | 1         | 0.07%   |
| Syntek                               | 1         | 0.07%   |
| Superlux digit                       | 1         | 0.07%   |
| SM900 Microphone                     | 1         | 0.07%   |
| SAVITECH                             | 1         | 0.07%   |
| Pioneer DJ                           | 1         | 0.07%   |
| Philips (or NXP)                     | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)        | 1         | 0.07%   |
| Numark                               | 1         | 0.07%   |
| No brand                             | 1         | 0.07%   |
| Native Instruments                   | 1         | 0.07%   |
| Micro Star International             | 1         | 0.07%   |
| Huawei Technologies                  | 1         | 0.07%   |
| HiFimeDIY Audio                      | 1         | 0.07%   |
| Harman                               | 1         | 0.07%   |
| Generalplus Technology               | 1         | 0.07%   |
| FiiO Electronics Technology          | 1         | 0.07%   |
| Ensoniq                              | 1         | 0.07%   |
| DSEA A/S                             | 1         | 0.07%   |
| DEXP BK-20                           | 1         | 0.07%   |
| Dell                                 | 1         | 0.07%   |
| Astro Gaming                         | 1         | 0.07%   |
| Antlion Audio                        | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 84        | 4.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 71        | 4.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 65        | 3.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 55        | 3.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 54        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 54        | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 53        | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 43        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 2.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 33        | 1.91%   |
| Intel 8 Series HD Audio Controller                                                                | 32        | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 30        | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 30        | 1.74%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 27        | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 25        | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 25        | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 1.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 22        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 1.16%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 16        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 15        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 13        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 0.75%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 13        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                                                | 12        | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 12        | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 12        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 0.69%   |
| AMD Navi 10 HDMI Audio                                                                            | 12        | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 11        | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 11        | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 11        | 0.64%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 11        | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 0.58%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 0.58%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 9         | 0.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 8         | 0.46%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 8         | 0.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 0.46%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 8         | 0.46%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 8         | 0.46%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.46%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 8         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 167       | 24.56%  |
| Kingston            | 126       | 18.53%  |
| SK hynix            | 111       | 16.32%  |
| Unknown             | 67        | 9.85%   |
| Micron Technology   | 61        | 8.97%   |
| Corsair             | 35        | 5.15%   |
| G.Skill             | 31        | 4.56%   |
| Crucial             | 28        | 4.12%   |
| Elpida              | 12        | 1.76%   |
| A-DATA Technology   | 11        | 1.62%   |
| Ramaxel Technology  | 10        | 1.47%   |
| Nanya Technology    | 6         | 0.88%   |
| Team                | 2         | 0.29%   |
| Qimonda             | 2         | 0.29%   |
| Unknown (ABCD)      | 1         | 0.15%   |
| PUSKILL             | 1         | 0.15%   |
| pqi                 | 1         | 0.15%   |
| Patriot             | 1         | 0.15%   |
| Hitachi             | 1         | 0.15%   |
| GOODRAM             | 1         | 0.15%   |
| GIGA-BYTE           | 1         | 0.15%   |
| ASint Technology    | 1         | 0.15%   |
| Apacer              | 1         | 0.15%   |
| 48spaces            | 1         | 0.15%   |
| Unknown             | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 10        | 1.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 8         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 8         | 1.09%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s | 8         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 7         | 0.95%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 7         | 0.95%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 7         | 0.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 6         | 0.81%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s | 6         | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 6         | 0.81%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 6         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s    | 5         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 5         | 0.68%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s    | 5         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 4         | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 4         | 0.54%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s    | 4         | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s | 4         | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 4         | 0.54%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s    | 4         | 0.54%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 4         | 0.54%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 4         | 0.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 3         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2                    | 3         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 3         | 0.41%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 3         | 0.41%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 3         | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 3         | 0.41%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s              | 3         | 0.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 3         | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 3         | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s    | 3         | 0.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 3         | 0.41%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s    | 3         | 0.41%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 3         | 0.41%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 3         | 0.41%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 3         | 0.41%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s  | 3         | 0.41%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 3         | 0.41%   |
| Kingston RAM 9905295-045.A01LF 2GB SODIMM DDR2 667MT/s   | 3         | 0.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 3         | 0.41%   |
| G.Skill RAM F4-3200C16-16GTZ 16384MB DIMM DDR4 2933MT/s  | 3         | 0.41%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s     | 3         | 0.41%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s    | 3         | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 3         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 2         | 0.27%   |
| Unknown RAM Module 4096MB SODIMM                         | 2         | 0.27%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 2         | 0.27%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s               | 2         | 0.27%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 2         | 0.27%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2         | 0.27%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                     | 2         | 0.27%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s           | 2         | 0.27%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s         | 2         | 0.27%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s   | 2         | 0.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 263       | 43.4%   |
| DDR3    | 223       | 36.8%   |
| DDR2    | 50        | 8.25%   |
| SDRAM   | 20        | 3.3%    |
| LPDDR3  | 15        | 2.48%   |
| Unknown | 15        | 2.48%   |
| LPDDR4  | 12        | 1.98%   |
| DDR     | 6         | 0.99%   |
| DRAM    | 1         | 0.17%   |
| DDR5    | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 315       | 52.41%  |
| DIMM         | 252       | 41.93%  |
| Row Of Chips | 27        | 4.49%   |
| Chip         | 4         | 0.67%   |
| RIMM         | 2         | 0.33%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 222       | 34.1%   |
| 4096  | 183       | 28.11%  |
| 2048  | 104       | 15.98%  |
| 16384 | 79        | 12.14%  |
| 1024  | 30        | 4.61%   |
| 32768 | 28        | 4.3%    |
| 512   | 5         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 128       | 19.66%  |
| 2667    | 77        | 11.83%  |
| 3200    | 69        | 10.6%   |
| 1333    | 49        | 7.53%   |
| 2400    | 43        | 6.61%   |
| 2133    | 38        | 5.84%   |
| 667     | 32        | 4.92%   |
| 1334    | 26        | 3.99%   |
| 3600    | 24        | 3.69%   |
| 1867    | 19        | 2.92%   |
| 800     | 19        | 2.92%   |
| 3466    | 15        | 2.3%    |
| Unknown | 13        | 2%      |
| 4267    | 8         | 1.23%   |
| 2933    | 8         | 1.23%   |
| 1067    | 8         | 1.23%   |
| 4199    | 7         | 1.08%   |
| 1066    | 7         | 1.08%   |
| 3800    | 5         | 0.77%   |
| 3000    | 5         | 0.77%   |
| 533     | 5         | 0.77%   |
| 3733    | 4         | 0.61%   |
| 3266    | 4         | 0.61%   |
| 2200    | 4         | 0.61%   |
| 2048    | 4         | 0.61%   |
| 2800    | 3         | 0.46%   |
| 1866    | 3         | 0.46%   |
| 975     | 3         | 0.46%   |
| 2666    | 2         | 0.31%   |
| 1800    | 2         | 0.31%   |
| 1639    | 2         | 0.31%   |
| 49926   | 1         | 0.15%   |
| 8192    | 1         | 0.15%   |
| 4800    | 1         | 0.15%   |
| 4266    | 1         | 0.15%   |
| 4000    | 1         | 0.15%   |
| 3533    | 1         | 0.15%   |
| 3400    | 1         | 0.15%   |
| 3334    | 1         | 0.15%   |
| 3333    | 1         | 0.15%   |
| 3151    | 1         | 0.15%   |
| 2747    | 1         | 0.15%   |
| 2733    | 1         | 0.15%   |
| 2176    | 1         | 0.15%   |
| 400     | 1         | 0.15%   |
| 333     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 33.33%  |
| Samsung Electronics   | 5         | 18.52%  |
| Canon                 | 4         | 14.81%  |
| Seiko Epson           | 3         | 11.11%  |
| Xerox                 | 1         | 3.7%    |
| Prolific Technology   | 1         | 3.7%    |
| Pantum                | 1         | 3.7%    |
| Lexmark International | 1         | 3.7%    |
| Dell                  | 1         | 3.7%    |
| Brother Industries    | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-1660 Series              | 2         | 7.41%   |
| Xerox Phaser 6500DN                 | 1         | 3.7%    |
| Seiko Epson XP-510 Series           | 1         | 3.7%    |
| Seiko Epson Printer                 | 1         | 3.7%    |
| Seiko Epson L555 Series             | 1         | 3.7%    |
| Samsung M2020 Series                | 1         | 3.7%    |
| Samsung CLP-325 Color Laser Printer | 1         | 3.7%    |
| Samsung C43x Series                 | 1         | 3.7%    |
| Prolific PL2305 Parallel Port       | 1         | 3.7%    |
| Pantum P2500W series                | 1         | 3.7%    |
| Lexmark International 2400 series   | 1         | 3.7%    |
| HP PSC 1100 series                  | 1         | 3.7%    |
| HP OfficeJet Pro 69                 | 1         | 3.7%    |
| HP OfficeJet 5200 series            | 1         | 3.7%    |
| HP LaserJet Professional P 1102w    | 1         | 3.7%    |
| HP LaserJet P2055 series            | 1         | 3.7%    |
| HP LaserJet P2015 series            | 1         | 3.7%    |
| HP DeskJet F300 series              | 1         | 3.7%    |
| HP DeskJet 960c                     | 1         | 3.7%    |
| HP DeskJet 2130 series              | 1         | 3.7%    |
| Dell Laser Printer 1720             | 1         | 3.7%    |
| Canon TS3300 series                 | 1         | 3.7%    |
| Canon TS3100 series                 | 1         | 3.7%    |
| Canon PIXMA MG3100 Series           | 1         | 3.7%    |
| Canon LBP6000                       | 1         | 3.7%    |
| Brother DCP-7055 scanner/printer    | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 80%     |
| Seiko Epson | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U            | 2         | 40%     |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 20%     |
| Canon CanoScan LiDE 110               | 1         | 20%     |
| Canon CanoScan LiDE 100               | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 165       | 30.28%  |
| Microdia                               | 42        | 7.71%   |
| IMC Networks                           | 42        | 7.71%   |
| Logitech                               | 39        | 7.16%   |
| Acer                                   | 38        | 6.97%   |
| Realtek Semiconductor                  | 36        | 6.61%   |
| Sunplus Innovation Technology          | 22        | 4.04%   |
| Quanta                                 | 22        | 4.04%   |
| Suyin                                  | 19        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.3%    |
| Apple                                  | 18        | 3.3%    |
| Syntek                                 | 12        | 2.2%    |
| Lite-On Technology                     | 11        | 2.02%   |
| Silicon Motion                         | 9         | 1.65%   |
| Lenovo                                 | 9         | 1.65%   |
| Microsoft                              | 7         | 1.28%   |
| Z-Star Microelectronics                | 4         | 0.73%   |
| Samsung Electronics                    | 4         | 0.73%   |
| Ricoh                                  | 3         | 0.55%   |
| Primax Electronics                     | 3         | 0.55%   |
| Alcor Micro                            | 3         | 0.55%   |
| Luxvisions Innotech Limited            | 2         | 0.37%   |
| Importek                               | 2         | 0.37%   |
| DigiTech                               | 2         | 0.37%   |
| ALi                                    | 2         | 0.37%   |
| Trust                                  | 1         | 0.18%   |
| Technologies                           | 1         | 0.18%   |
| SunplusIT                              | 1         | 0.18%   |
| Sonix Technology                       | 1         | 0.18%   |
| OnePlus                                | 1         | 0.18%   |
| Omnivision                             | 1         | 0.18%   |
| MacroSilicon                           | 1         | 0.18%   |
| LG Electronics                         | 1         | 0.18%   |
| Hewlett-Packard                        | 1         | 0.18%   |
| Google                                 | 1         | 0.18%   |
| Creative Technology                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 43        | 7.86%   |
| Microdia Integrated_Webcam_HD                                            | 17        | 3.11%   |
| Acer Integrated Camera                                                   | 13        | 2.38%   |
| IMC Networks Integrated Camera                                           | 11        | 2.01%   |
| Realtek Integrated_Webcam_HD                                             | 10        | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 10        | 1.83%   |
| Logitech Webcam C270                                                     | 9         | 1.65%   |
| Chicony HP HD Camera                                                     | 9         | 1.65%   |
| Logitech HD Pro Webcam C920                                              | 8         | 1.46%   |
| Syntek Integrated Camera                                                 | 7         | 1.28%   |
| Chicony HP HD Webcam                                                     | 7         | 1.28%   |
| Chicony HD WebCam                                                        | 7         | 1.28%   |
| Chicony FJ Camera                                                        | 7         | 1.28%   |
| Acer Lenovo EasyCamera                                                   | 7         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 6         | 1.1%    |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 1.1%    |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 6         | 1.1%    |
| Chicony EasyCamera                                                       | 6         | 1.1%    |
| Sunplus HD WebCam                                                        | 5         | 0.91%   |
| Realtek Lenovo EasyCamera                                                | 5         | 0.91%   |
| Quanta HP Webcam                                                         | 5         | 0.91%   |
| Microsoft LifeCam HD-3000                                                | 5         | 0.91%   |
| Chicony Integrated Camera [ThinkPad]                                     | 5         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)                                  | 5         | 0.91%   |
| Sunplus Integrated_Webcam_HD                                             | 4         | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 4         | 0.73%   |
| Realtek USB Camera                                                       | 4         | 0.73%   |
| Realtek Integrated Webcam HD                                             | 4         | 0.73%   |
| Microdia Integrated Webcam                                               | 4         | 0.73%   |
| Logitech Webcam C930e                                                    | 4         | 0.73%   |
| Lite-On Integrated Camera                                                | 4         | 0.73%   |
| Lenovo UVC Camera                                                        | 4         | 0.73%   |
| Lenovo Integrated Webcam [R5U877]                                        | 4         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 4         | 0.73%   |
| Chicony Lenovo EasyCamera                                                | 4         | 0.73%   |
| Chicony Integrated HP HD Webcam                                          | 4         | 0.73%   |
| Chicony HP TrueVision HD Camera                                          | 4         | 0.73%   |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 0.73%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 4         | 0.73%   |
| Apple FaceTime HD Camera (Built-in)                                      | 4         | 0.73%   |
| Apple Built-in iSight                                                    | 4         | 0.73%   |
| Suyin HP Truevision HD                                                   | 3         | 0.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 3         | 0.55%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 3         | 0.55%   |
| Quanta USB Webcam                                                        | 3         | 0.55%   |
| Quanta HP Wide Vision HD Camera                                          | 3         | 0.55%   |
| Quanta HD User Facing                                                    | 3         | 0.55%   |
| Primax HP HD Webcam [Fixed]                                              | 3         | 0.55%   |
| Microdia Sonix USB 2.0 Camera                                            | 3         | 0.55%   |
| Microdia Camera                                                          | 3         | 0.55%   |
| Logitech StreamCam                                                       | 3         | 0.55%   |
| Logitech HD Webcam C510                                                  | 3         | 0.55%   |
| Lite-On HP HD Camera                                                     | 3         | 0.55%   |
| IMC Networks EasyCamera                                                  | 3         | 0.55%   |
| Chicony ThinkPad T490 Webcam                                             | 3         | 0.55%   |
| Chicony thinkpad t430s camera                                            | 3         | 0.55%   |
| Chicony HP Wide Vision HD Camera                                         | 3         | 0.55%   |
| Chicony HP Wide Vision FHD Camera                                        | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 55        | 40.74%  |
| Synaptics                  | 27        | 20%     |
| Shenzhen Goodix Technology | 13        | 9.63%   |
| AuthenTec                  | 12        | 8.89%   |
| Upek                       | 10        | 7.41%   |
| STMicroelectronics         | 9         | 6.67%   |
| LighTuning Technology      | 6         | 4.44%   |
| Elan Microelectronics      | 2         | 1.48%   |
| Microsoft                  | 1         | 0.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 9.63%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 8.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 6.67%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 5.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 5.19%   |
| AuthenTec AES2810                                                          | 7         | 5.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 4.44%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 3.7%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.96%   |
| Validity Sensors VFS491                                                    | 3         | 2.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.22%   |
| Unknown                                                                    | 3         | 2.22%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.48%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.48%   |
| Synaptics  WBDI                                                            | 2         | 1.48%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.48%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.48%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.48%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.48%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.74%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.74%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.74%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.74%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 38        | 44.19%  |
| Broadcom                  | 25        | 29.07%  |
| Lenovo                    | 9         | 10.47%  |
| Upek                      | 5         | 5.81%   |
| SCM Microsystems          | 3         | 3.49%   |
| O2 Micro                  | 3         | 3.49%   |
| Fujitsu Siemens Computers | 2         | 2.33%   |
| Advanced Card Systems     | 1         | 1.16%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 38        | 44.19%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 10.47%  |
| Broadcom 5880                                                                | 9         | 10.47%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 9.3%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.81%   |
| Broadcom 58200                                                               | 5         | 5.81%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 3.49%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.49%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 2.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 2.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.16%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.16%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 722       | 67.92%  |
| 1     | 262       | 24.65%  |
| 2     | 59        | 5.55%   |
| 3     | 11        | 1.03%   |
| 5     | 4         | 0.38%   |
| 4     | 3         | 0.28%   |
| 6     | 2         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 134       | 30.73%  |
| Chipcard                 | 76        | 17.43%  |
| Graphics card            | 74        | 16.97%  |
| Net/wireless             | 49        | 11.24%  |
| Communication controller | 18        | 4.13%   |
| Multimedia controller    | 16        | 3.67%   |
| Bluetooth                | 11        | 2.52%   |
| Camera                   | 10        | 2.29%   |
| Unassigned class         | 9         | 2.06%   |
| Net/ethernet             | 8         | 1.83%   |
| Sound                    | 7         | 1.61%   |
| Storage                  | 6         | 1.38%   |
| Card reader              | 6         | 1.38%   |
| Modem                    | 3         | 0.69%   |
| Firewire controller      | 3         | 0.69%   |
| Storage/raid             | 2         | 0.46%   |
| Storage/nvme             | 1         | 0.23%   |
| Network                  | 1         | 0.23%   |
| Flash memory             | 1         | 0.23%   |
| Dvb card                 | 1         | 0.23%   |

