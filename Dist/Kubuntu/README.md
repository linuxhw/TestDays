Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 5733

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [97c78c17bd](https://linux-hardware.org/?probe=97c78c17bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| AZW           | SER V01                     | Mini pc     | [542d8da36c](https://linux-hardware.org/?probe=542d8da36c) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [3d156d18e6](https://linux-hardware.org/?probe=3d156d18e6) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [cb3d78955a](https://linux-hardware.org/?probe=cb3d78955a) | Aug 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | 158A                        | Desktop     | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 3031h                       | Desktop     | [95b5c80f67](https://linux-hardware.org/?probe=95b5c80f67) | Aug 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| HP            | 3031h                       | Desktop     | [04c8ac1eee](https://linux-hardware.org/?probe=04c8ac1eee) | Aug 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [5e552472e5](https://linux-hardware.org/?probe=5e552472e5) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | 158A                        | Desktop     | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb493cc8c8](https://linux-hardware.org/?probe=cb493cc8c8) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Google        | Zako                        | Desktop     | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [65a741810c](https://linux-hardware.org/?probe=65a741810c) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [e5ad011556](https://linux-hardware.org/?probe=e5ad011556) | Jul 30, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7c5e9b6bc6](https://linux-hardware.org/?probe=7c5e9b6bc6) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| AZW           | SER V01                     | Mini pc     | [440a88b8bf](https://linux-hardware.org/?probe=440a88b8bf) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | Desktop     | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | G62                         | Notebook    | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c5028381e5](https://linux-hardware.org/?probe=c5028381e5) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | 83E9                        | Desktop     | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [392b85a82b](https://linux-hardware.org/?probe=392b85a82b) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [0b447416c6](https://linux-hardware.org/?probe=0b447416c6) | Jul 15, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0008f72dbf](https://linux-hardware.org/?probe=0008f72dbf) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [745fa6a1b4](https://linux-hardware.org/?probe=745fa6a1b4) | Jul 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c453f1df6b](https://linux-hardware.org/?probe=c453f1df6b) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [93b2067918](https://linux-hardware.org/?probe=93b2067918) | Jul 11, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [6f62e1063c](https://linux-hardware.org/?probe=6f62e1063c) | Jul 11, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | Notebook    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [9400bf75de](https://linux-hardware.org/?probe=9400bf75de) | Jul 09, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Dell          | G3 3779                     | Notebook    | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| AZW           | SER V01                     | Mini pc     | [49552e2240](https://linux-hardware.org/?probe=49552e2240) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [673c5bfa9a](https://linux-hardware.org/?probe=673c5bfa9a) | Jul 04, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [e76be78ba9](https://linux-hardware.org/?probe=e76be78ba9) | Jul 02, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | Desktop     | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [f953c21e8e](https://linux-hardware.org/?probe=f953c21e8e) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | Notebook                    | Notebook    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [e2c3a51177](https://linux-hardware.org/?probe=e2c3a51177) | Jun 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Irbis         | NB123                       | Notebook    | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [1b099710b7](https://linux-hardware.org/?probe=1b099710b7) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [9bf82397c3](https://linux-hardware.org/?probe=9bf82397c3) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Packard Be... | MCP73                       | Desktop     | [e180017a10](https://linux-hardware.org/?probe=e180017a10) | May 29, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| Packard Be... | MCP73                       | Desktop     | [1203dc5301](https://linux-hardware.org/?probe=1203dc5301) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [80c62a0473](https://linux-hardware.org/?probe=80c62a0473) | May 21, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| HP            | 350 G1                      | Notebook    | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | Desktop     | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Samsung       | Galaxy TabPro S LTE         | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [1ab8b910e4](https://linux-hardware.org/?probe=1ab8b910e4) | May 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [a3c89effff](https://linux-hardware.org/?probe=a3c89effff) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f83e11ca39](https://linux-hardware.org/?probe=f83e11ca39) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [d96138627b](https://linux-hardware.org/?probe=d96138627b) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| HP            | 630                         | Notebook    | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [c34c2e032c](https://linux-hardware.org/?probe=c34c2e032c) | Apr 15, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ffa823032e](https://linux-hardware.org/?probe=ffa823032e) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f7197973](https://linux-hardware.org/?probe=62f7197973) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Google        | Eve                         | Convertible | [551ff8d7c2](https://linux-hardware.org/?probe=551ff8d7c2) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [9b96a245f1](https://linux-hardware.org/?probe=9b96a245f1) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ddceb8b5b0](https://linux-hardware.org/?probe=ddceb8b5b0) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [cb0fa70953](https://linux-hardware.org/?probe=cb0fa70953) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | Notebook    | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4f9eed1de2](https://linux-hardware.org/?probe=4f9eed1de2) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [e313c99b98](https://linux-hardware.org/?probe=e313c99b98) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fd1273ed2e](https://linux-hardware.org/?probe=fd1273ed2e) | Mar 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [046b4b7497](https://linux-hardware.org/?probe=046b4b7497) | Mar 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0f38ea375f](https://linux-hardware.org/?probe=0f38ea375f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [f354a2f03e](https://linux-hardware.org/?probe=f354a2f03e) | Mar 27, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [e7b44d994b](https://linux-hardware.org/?probe=e7b44d994b) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [6d1a1f7bd2](https://linux-hardware.org/?probe=6d1a1f7bd2) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4077bee378](https://linux-hardware.org/?probe=4077bee378) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [e1cfc1c76d](https://linux-hardware.org/?probe=e1cfc1c76d) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | Notebook    | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [0cfaf0934d](https://linux-hardware.org/?probe=0cfaf0934d) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [ede048bc5d](https://linux-hardware.org/?probe=ede048bc5d) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [619a36ed2f](https://linux-hardware.org/?probe=619a36ed2f) | Mar 19, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [8cf99eb521](https://linux-hardware.org/?probe=8cf99eb521) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b0b8ac79d9](https://linux-hardware.org/?probe=b0b8ac79d9) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | Notebook    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HP            | 2B52                        | Desktop     | [b541e6085e](https://linux-hardware.org/?probe=b541e6085e) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c5a25ab496](https://linux-hardware.org/?probe=c5a25ab496) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASRockRack    | ROMED6U-2L2T                | Desktop     | [1af076312d](https://linux-hardware.org/?probe=1af076312d) | Mar 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [1b49e21822](https://linux-hardware.org/?probe=1b49e21822) | Mar 11, 2023 |
| HP            | 0AACh                       | Desktop     | [83f0c7df93](https://linux-hardware.org/?probe=83f0c7df93) | Mar 10, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [8fbb4566ac](https://linux-hardware.org/?probe=8fbb4566ac) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | Notebook    | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | Notebook    | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [483a11d21e](https://linux-hardware.org/?probe=483a11d21e) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4d68c19c3e](https://linux-hardware.org/?probe=4d68c19c3e) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6c007c983c](https://linux-hardware.org/?probe=6c007c983c) | Mar 02, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | 05R2TK A01                  | All in one  | [efa9d9069d](https://linux-hardware.org/?probe=efa9d9069d) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [727ce4b27e](https://linux-hardware.org/?probe=727ce4b27e) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [bbc9bc409c](https://linux-hardware.org/?probe=bbc9bc409c) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c872892cfd](https://linux-hardware.org/?probe=c872892cfd) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2943aa6cd7](https://linux-hardware.org/?probe=2943aa6cd7) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [844de888cd](https://linux-hardware.org/?probe=844de888cd) | Feb 25, 2023 |
| System76      | Gazelle                     | Notebook    | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [471b84b6d4](https://linux-hardware.org/?probe=471b84b6d4) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| Shuttle       | FL10J                       | Desktop     | [943316a9c5](https://linux-hardware.org/?probe=943316a9c5) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [c81213c25e](https://linux-hardware.org/?probe=c81213c25e) | Feb 22, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d6ec8781f4](https://linux-hardware.org/?probe=d6ec8781f4) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | Notebook    | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | Notebook    | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [2744ec3c4a](https://linux-hardware.org/?probe=2744ec3c4a) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | Notebook    | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [146c38cbdf](https://linux-hardware.org/?probe=146c38cbdf) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361eb28148](https://linux-hardware.org/?probe=361eb28148) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [62a320f515](https://linux-hardware.org/?probe=62a320f515) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5d2153f4f2](https://linux-hardware.org/?probe=5d2153f4f2) | Feb 14, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [05bc165699](https://linux-hardware.org/?probe=05bc165699) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5b93510482](https://linux-hardware.org/?probe=5b93510482) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [874ccdcf1a](https://linux-hardware.org/?probe=874ccdcf1a) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [dec32b9b60](https://linux-hardware.org/?probe=dec32b9b60) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [f493bc6d9d](https://linux-hardware.org/?probe=f493bc6d9d) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [518a58b5ca](https://linux-hardware.org/?probe=518a58b5ca) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [223378c538](https://linux-hardware.org/?probe=223378c538) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [00006691a6](https://linux-hardware.org/?probe=00006691a6) | Feb 05, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| HP            | 0AACh                       | Desktop     | [86d994993f](https://linux-hardware.org/?probe=86d994993f) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Chuwi         | Hi10 Go                     | Notebook    | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c91d5b265b](https://linux-hardware.org/?probe=c91d5b265b) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef1817a829](https://linux-hardware.org/?probe=ef1817a829) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4b6904f9b1](https://linux-hardware.org/?probe=4b6904f9b1) | Feb 01, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ab92a33bdf](https://linux-hardware.org/?probe=ab92a33bdf) | Feb 01, 2023 |
| HP            | 0AACh                       | Desktop     | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | Notebook    | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [8f3278e68a](https://linux-hardware.org/?probe=8f3278e68a) | Jan 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1410      | 34.19%  |
| Kubuntu 22.04   | 951       | 23.06%  |
| Kubuntu 22.10   | 297       | 7.2%    |
| Kubuntu 20.10   | 256       | 6.21%   |
| Kubuntu 21.10   | 242       | 5.87%   |
| Kubuntu 21.04   | 214       | 5.19%   |
| Kubuntu 18.04   | 201       | 4.87%   |
| Kubuntu 23.04   | 186       | 4.51%   |
| Kubuntu 19.10   | 178       | 4.32%   |
| Kubuntu 11      | 94        | 2.28%   |
| Kubuntu 11.1    | 26        | 0.63%   |
| Kubuntu 19.04   | 22        | 0.53%   |
| Kubuntu 16.04   | 13        | 0.32%   |
| Kubuntu         | 8         | 0.19%   |
| Kubuntu 18.10   | 7         | 0.17%   |
| Kubuntu 2.0     | 6         | 0.15%   |
| Kubuntu 23.10   | 4         | 0.1%    |
| Kubuntu 17.10   | 3         | 0.07%   |
| Kubuntu 17.04   | 2         | 0.05%   |
| Kubuntu 14.04   | 2         | 0.05%   |
| Kubuntu 20.08.3 | 1         | 0.02%   |
| Kubuntu 12.04   | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 3937      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.27%   |
| 5.15.0-52-generic | 84        | 1.85%   |
| 5.15.0-56-generic | 80        | 1.77%   |
| 6.2.0-20-generic  | 77        | 1.7%    |
| 5.19.0-35-generic | 70        | 1.55%   |
| 5.4.0-52-generic  | 68        | 1.5%    |
| 5.4.0-58-generic  | 59        | 1.3%    |
| 5.4.0-48-generic  | 59        | 1.3%    |
| 5.15.0-48-generic | 58        | 1.28%   |
| 5.15.0-46-generic | 53        | 1.17%   |
| 5.13.0-39-generic | 53        | 1.17%   |
| 5.19.0-23-generic | 52        | 1.15%   |
| 5.4.0-40-generic  | 47        | 1.04%   |
| 5.19.0-38-generic | 47        | 1.04%   |
| 5.13.0-28-generic | 44        | 0.97%   |
| 5.19.0-31-generic | 43        | 0.95%   |
| 5.19.0-26-generic | 42        | 0.93%   |
| 5.15.0-58-generic | 42        | 0.93%   |
| 5.15.0-43-generic | 42        | 0.93%   |
| 5.15.0-47-generic | 41        | 0.91%   |
| 5.15.0-41-generic | 39        | 0.86%   |
| 5.11.0-37-generic | 38        | 0.84%   |
| 5.11.0-25-generic | 38        | 0.84%   |
| 5.15.0-53-generic | 37        | 0.82%   |
| 5.13.0-30-generic | 37        | 0.82%   |
| 5.4.0-47-generic  | 36        | 0.79%   |
| 5.4.0-65-generic  | 35        | 0.77%   |
| 5.8.0-48-generic  | 34        | 0.75%   |
| 5.3.0-40-generic  | 34        | 0.75%   |
| 5.4.0-37-generic  | 33        | 0.73%   |
| 5.4.0-29-generic  | 33        | 0.73%   |
| 5.19.0-29-generic | 32        | 0.71%   |
| 5.15.0-60-generic | 32        | 0.71%   |
| 5.13.0-22-generic | 32        | 0.71%   |
| 5.4.0-45-generic  | 30        | 0.66%   |
| 5.8.0-50-generic  | 29        | 0.64%   |
| 5.15.0-67-generic | 29        | 0.64%   |
| 5.13.0-35-generic | 29        | 0.64%   |
| 6.2.0-26-generic  | 28        | 0.62%   |
| 5.8.0-63-generic  | 28        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 943       | 22.46%  |
| 5.15.0  | 836       | 19.91%  |
| 5.19.0  | 438       | 10.43%  |
| 5.13.0  | 409       | 9.74%   |
| 5.8.0   | 406       | 9.67%   |
| 5.11.0  | 327       | 7.79%   |
| 5.3.0   | 224       | 5.33%   |
| 6.2.0   | 166       | 3.95%   |
| 4.15.0  | 69        | 1.64%   |
| 5.0.0   | 36        | 0.86%   |
| 5.17.0  | 21        | 0.5%    |
| 5.10.0  | 18        | 0.43%   |
| 5.6.0   | 15        | 0.36%   |
| 4.4.0   | 10        | 0.24%   |
| 6.1.0   | 9         | 0.21%   |
| 6.0.0   | 9         | 0.21%   |
| 5.14.0  | 8         | 0.19%   |
| 4.18.0  | 8         | 0.19%   |
| 6.0.9   | 6         | 0.14%   |
| 5.9.0   | 5         | 0.12%   |
| 6.4.0   | 4         | 0.1%    |
| 6.3.0   | 4         | 0.1%    |
| 5.7.0   | 4         | 0.1%    |
| 6.4.8   | 3         | 0.07%   |
| 6.3.8   | 3         | 0.07%   |
| 6.3.6   | 3         | 0.07%   |
| 6.3.1   | 3         | 0.07%   |
| 6.1.5   | 3         | 0.07%   |
| 5.8.18  | 3         | 0.07%   |
| 5.18.4  | 3         | 0.07%   |
| 5.18.10 | 3         | 0.07%   |
| 5.16.0  | 3         | 0.07%   |
| 5.12.8  | 3         | 0.07%   |
| 5.12.0  | 3         | 0.07%   |
| 4.13.0  | 3         | 0.07%   |
| 4.10.0  | 3         | 0.07%   |
| 6.3.7   | 2         | 0.05%   |
| 6.3.4   | 2         | 0.05%   |
| 6.2.5   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 950       | 22.66%  |
| 5.15    | 850       | 20.28%  |
| 5.19    | 444       | 10.59%  |
| 5.8     | 422       | 10.07%  |
| 5.13    | 419       | 10%     |
| 5.11    | 333       | 7.94%   |
| 5.3     | 227       | 5.42%   |
| 6.2     | 174       | 4.15%   |
| 4.15    | 70        | 1.67%   |
| 5.0     | 37        | 0.88%   |
| 5.10    | 30        | 0.72%   |
| 5.17    | 28        | 0.67%   |
| 6.1     | 25        | 0.6%    |
| 6.3     | 21        | 0.5%    |
| 6.0     | 21        | 0.5%    |
| 5.6     | 20        | 0.48%   |
| 5.14    | 17        | 0.41%   |
| 5.9     | 13        | 0.31%   |
| 5.12    | 13        | 0.31%   |
| 5.18    | 12        | 0.29%   |
| 5.7     | 11        | 0.26%   |
| 5.16    | 10        | 0.24%   |
| 4.4     | 10        | 0.24%   |
| 4.18    | 10        | 0.24%   |
| 6.4     | 9         | 0.21%   |
| 5.5     | 5         | 0.12%   |
| 4.13    | 3         | 0.07%   |
| 4.10    | 3         | 0.07%   |
| 5.1     | 2         | 0.05%   |
| 4.17    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3918      | 99.52%  |
| i686    | 12        | 0.3%    |
| aarch64 | 5         | 0.13%   |
| riscv64 | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 3027      | 75.58%  |
| KDE        | 918       | 22.92%  |
| GNOME      | 21        | 0.52%   |
| Cinnamon   | 11        | 0.27%   |
| Budgie     | 8         | 0.2%    |
| MATE       | 6         | 0.15%   |
| XFCE       | 3         | 0.07%   |
| LXQt       | 3         | 0.07%   |
| KDE4       | 3         | 0.07%   |
| X-Cinnamon | 1         | 0.02%   |
| Unity      | 1         | 0.02%   |
| i3         | 1         | 0.02%   |
| GNUstep    | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3762      | 94.95%  |
| Wayland | 153       | 3.86%   |
| Tty     | 46        | 1.16%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2360      | 58.78%  |
| Unknown | 1376      | 34.27%  |
| GDM     | 112       | 2.79%   |
| GDM3    | 75        | 1.87%   |
| LightDM | 68        | 1.69%   |
| TDM     | 21        | 0.52%   |
| SLiM    | 2         | 0.05%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1696      | 42.69%  |
| de_DE   | 332       | 8.36%   |
| ru_RU   | 202       | 5.08%   |
| en_GB   | 194       | 4.88%   |
| fr_FR   | 180       | 4.53%   |
| pt_BR   | 170       | 4.28%   |
| it_IT   | 162       | 4.08%   |
| en_CA   | 82        | 2.06%   |
| es_ES   | 81        | 2.04%   |
| Unknown | 77        | 1.94%   |
| en_AU   | 75        | 1.89%   |
| pl_PL   | 74        | 1.86%   |
| en_IN   | 71        | 1.79%   |
| C       | 44        | 1.11%   |
| hu_HU   | 30        | 0.76%   |
| es_MX   | 26        | 0.65%   |
| ru_UA   | 23        | 0.58%   |
| nl_NL   | 23        | 0.58%   |
| es_AR   | 23        | 0.58%   |
| en_ZA   | 23        | 0.58%   |
| cs_CZ   | 22        | 0.55%   |
| de_AT   | 21        | 0.53%   |
| en_NZ   | 18        | 0.45%   |
| tr_TR   | 15        | 0.38%   |
| de_CH   | 14        | 0.35%   |
| sv_SE   | 13        | 0.33%   |
| pt_PT   | 12        | 0.3%    |
| zh_CN   | 11        | 0.28%   |
| es_CO   | 11        | 0.28%   |
| es_CL   | 11        | 0.28%   |
| en_IE   | 11        | 0.28%   |
| el_GR   | 11        | 0.28%   |
| fi_FI   | 10        | 0.25%   |
| en_PH   | 10        | 0.25%   |
| fr_BE   | 9         | 0.23%   |
| es_VE   | 9         | 0.23%   |
| en_IL   | 9         | 0.23%   |
| uk_UA   | 8         | 0.2%    |
| nl_BE   | 8         | 0.2%    |
| sl_SI   | 7         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2192      | 54.79%  |
| BIOS | 1809      | 45.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3549      | 89.33%  |
| Btrfs    | 161       | 4.05%   |
| Overlay  | 99        | 2.49%   |
| Tmpfs    | 78        | 1.96%   |
| Xfs      | 39        | 0.98%   |
| Zfs      | 21        | 0.53%   |
| Unknown  | 12        | 0.3%    |
| Ext3     | 5         | 0.13%   |
| Ext2     | 4         | 0.1%    |
| XXXX     | 1         | 0.03%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| F2fs     | 1         | 0.03%   |
| ExX4     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2039      | 50.85%  |
| Unknown | 1615      | 40.27%  |
| MBR     | 356       | 8.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3460      | 86.89%  |
| Yes       | 522       | 13.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2464      | 61.86%  |
| Yes       | 1519      | 38.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 648       | 16.46%  |
| Lenovo              | 603       | 15.32%  |
| Dell                | 538       | 13.67%  |
| Hewlett-Packard     | 525       | 13.34%  |
| Gigabyte Technology | 313       | 7.95%   |
| MSI                 | 262       | 6.65%   |
| Acer                | 186       | 4.72%   |
| ASRock              | 138       | 3.51%   |
| Apple               | 59        | 1.5%    |
| Samsung Electronics | 47        | 1.19%   |
| Intel               | 47        | 1.19%   |
| HUAWEI              | 45        | 1.14%   |
| Unknown             | 32        | 0.81%   |
| Toshiba             | 26        | 0.66%   |
| Notebook            | 25        | 0.64%   |
| Google              | 25        | 0.64%   |
| Fujitsu             | 23        | 0.58%   |
| Sony                | 21        | 0.53%   |
| TUXEDO              | 19        | 0.48%   |
| Alienware           | 17        | 0.43%   |
| Pegatron            | 15        | 0.38%   |
| Medion              | 15        | 0.38%   |
| Timi                | 13        | 0.33%   |
| Positivo            | 13        | 0.33%   |
| Biostar             | 13        | 0.33%   |
| Packard Bell        | 10        | 0.25%   |
| Microsoft           | 10        | 0.25%   |
| Foxconn             | 10        | 0.25%   |
| AZW                 | 10        | 0.25%   |
| Supermicro          | 9         | 0.23%   |
| ZOTAC               | 8         | 0.2%    |
| System76            | 8         | 0.2%    |
| PC Specialist       | 8         | 0.2%    |
| ECS                 | 8         | 0.2%    |
| Chuwi               | 8         | 0.2%    |
| GPU Company         | 7         | 0.18%   |
| Shuttle             | 6         | 0.15%   |
| Razer               | 6         | 0.15%   |
| LG Electronics      | 6         | 0.15%   |
| Huanan              | 6         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 47        | 1.19%   |
| Unknown                            | 46        | 1.17%   |
| ASUS ROG STRIX B550-F GAMING       | 12        | 0.3%    |
| Gigabyte B450M DS3H                | 11        | 0.28%   |
| HP Notebook                        | 10        | 0.25%   |
| MSI MS-7C37                        | 9         | 0.23%   |
| MSI MS-7B79                        | 9         | 0.23%   |
| HP Pavilion g6                     | 9         | 0.23%   |
| HP Pavilion dv6                    | 9         | 0.23%   |
| Dell XPS 15 9560                   | 9         | 0.23%   |
| Dell OptiPlex 9020                 | 9         | 0.23%   |
| Dell OptiPlex 7010                 | 9         | 0.23%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.2%    |
| Gigabyte A320M-S2H                 | 8         | 0.2%    |
| ASUS ROG STRIX X570-E GAMING       | 8         | 0.2%    |
| ASUS PRIME B350-PLUS               | 8         | 0.2%    |
| ASUS PRIME A320M-K                 | 8         | 0.2%    |
| MSI MS-7C91                        | 7         | 0.18%   |
| MSI MS-7817                        | 7         | 0.18%   |
| HP Pavilion dv7                    | 7         | 0.18%   |
| HP Pavilion 15                     | 7         | 0.18%   |
| HP ENVY x360 Convertible 13-ay0xxx | 7         | 0.18%   |
| HP EliteBook 840 G5                | 7         | 0.18%   |
| Gigabyte X570 AORUS MASTER         | 7         | 0.18%   |
| Gigabyte 970A-DS3P                 | 7         | 0.18%   |
| Dell XPS 15 9570                   | 7         | 0.18%   |
| ASUS PRIME B450M-A                 | 7         | 0.18%   |
| MSI MS-7A34                        | 6         | 0.15%   |
| MSI MS-7693                        | 6         | 0.15%   |
| HUAWEI HVY-WXX9                    | 6         | 0.15%   |
| HP EliteBook 840 G6                | 6         | 0.15%   |
| HP EliteBook 840 G3                | 6         | 0.15%   |
| Dell XPS 15 7590                   | 6         | 0.15%   |
| Dell Latitude 5480                 | 6         | 0.15%   |
| ASUS TUF Gaming X570-PLUS          | 6         | 0.15%   |
| ASUS TUF Gaming B550-PLUS          | 6         | 0.15%   |
| ASRock A320M-HDV R4.0              | 6         | 0.15%   |
| MSI MS-7C02                        | 5         | 0.13%   |
| HP Compaq Elite 8300 SFF           | 5         | 0.13%   |
| HP 255 G8 Notebook PC              | 5         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 278       | 7.06%   |
| Dell Latitude      | 145       | 3.68%   |
| Dell Inspiron      | 131       | 3.33%   |
| Acer Aspire        | 118       | 3%      |
| Lenovo IdeaPad     | 112       | 2.84%   |
| HP Pavilion        | 104       | 2.64%   |
| ASUS ROG           | 92        | 2.34%   |
| ASUS PRIME         | 89        | 2.26%   |
| Dell XPS           | 77        | 1.96%   |
| HP EliteBook       | 65        | 1.65%   |
| HP ProBook         | 64        | 1.63%   |
| Dell Precision     | 59        | 1.5%    |
| HP Laptop          | 54        | 1.37%   |
| Dell OptiPlex      | 54        | 1.37%   |
| ASUS VivoBook      | 53        | 1.35%   |
| ASUS All           | 47        | 1.19%   |
| ASUS TUF           | 46        | 1.17%   |
| Unknown            | 46        | 1.17%   |
| Lenovo ThinkCentre | 36        | 0.91%   |
| HP ENVY            | 35        | 0.89%   |
| HP Compaq          | 33        | 0.84%   |
| Lenovo Yoga        | 32        | 0.81%   |
| Dell Vostro        | 31        | 0.79%   |
| Lenovo Legion      | 27        | 0.69%   |
| Acer Nitro         | 26        | 0.66%   |
| ASUS ASUS          | 25        | 0.64%   |
| Toshiba Satellite  | 22        | 0.56%   |
| Lenovo ThinkBook   | 22        | 0.56%   |
| ASUS Zenbook       | 20        | 0.51%   |
| Gigabyte B450M     | 19        | 0.48%   |
| Gigabyte X570      | 18        | 0.46%   |
| Acer Swift         | 18        | 0.46%   |
| HP ZBook           | 15        | 0.38%   |
| HP Spectre         | 12        | 0.3%    |
| HP EliteDesk       | 12        | 0.3%    |
| Gigabyte B550      | 12        | 0.3%    |
| Gigabyte A320M-S2H | 12        | 0.3%    |
| Dell G3            | 12        | 0.3%    |
| ASUS M5A78L-M      | 11        | 0.28%   |
| Microsoft Surface  | 10        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 483       | 12.27%  |
| 2019    | 463       | 11.76%  |
| 2018    | 428       | 10.87%  |
| 2021    | 356       | 9.04%   |
| 2017    | 286       | 7.26%   |
| 2012    | 263       | 6.68%   |
| 2013    | 261       | 6.63%   |
| 2014    | 233       | 5.92%   |
| 2011    | 227       | 5.77%   |
| 2016    | 187       | 4.75%   |
| 2015    | 177       | 4.5%    |
| 2022    | 167       | 4.24%   |
| 2010    | 131       | 3.33%   |
| 2008    | 99        | 2.51%   |
| 2009    | 96        | 2.44%   |
| 2007    | 38        | 0.97%   |
| 2023    | 22        | 0.56%   |
| 2006    | 9         | 0.23%   |
| Unknown | 7         | 0.18%   |
| 2005    | 3         | 0.08%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2179      | 55.35%  |
| Desktop        | 1468      | 37.29%  |
| Convertible    | 137       | 3.48%   |
| Mini pc        | 60        | 1.52%   |
| All in one     | 43        | 1.09%   |
| Tablet         | 28        | 0.71%   |
| Server         | 16        | 0.41%   |
| System on chip | 5         | 0.13%   |
| Stick pc       | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3608      | 91.04%  |
| Enabled  | 355       | 8.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3905      | 99.19%  |
| Yes  | 32        | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1019      | 25.65%  |
| 4.01-8.0        | 884       | 22.26%  |
| 8.01-16.0       | 731       | 18.4%   |
| 32.01-64.0      | 553       | 13.92%  |
| 3.01-4.0        | 456       | 11.48%  |
| 64.01-256.0     | 142       | 3.58%   |
| 24.01-32.0      | 107       | 2.69%   |
| 1.01-2.0        | 54        | 1.36%   |
| 2.01-3.0        | 23        | 0.58%   |
| More than 256.0 | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1094      | 25.67%  |
| 4.01-8.0    | 1015      | 23.82%  |
| 1.01-2.0    | 945       | 22.18%  |
| 3.01-4.0    | 725       | 17.01%  |
| 8.01-16.0   | 312       | 7.32%   |
| 0.51-1.0    | 88        | 2.07%   |
| 16.01-24.0  | 48        | 1.13%   |
| 24.01-32.0  | 16        | 0.38%   |
| 32.01-64.0  | 9         | 0.21%   |
| 0.01-0.5    | 7         | 0.16%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2164      | 53.52%  |
| 2      | 1092      | 27.01%  |
| 3      | 374       | 9.25%   |
| 4      | 203       | 5.02%   |
| 5      | 104       | 2.57%   |
| 6      | 46        | 1.14%   |
| 7      | 28        | 0.69%   |
| 0      | 13        | 0.32%   |
| 8      | 6         | 0.15%   |
| 9      | 5         | 0.12%   |
| 10     | 3         | 0.07%   |
| 12     | 2         | 0.05%   |
| 11     | 2         | 0.05%   |
| 13     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2700      | 68.1%   |
| Yes       | 1265      | 31.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3318      | 84.17%  |
| No        | 624       | 15.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3075      | 77.75%  |
| No        | 880       | 22.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2644      | 66.6%   |
| No        | 1326      | 33.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 771       | 19.53%  |
| Germany      | 449       | 11.38%  |
| Russia       | 271       | 6.87%   |
| France       | 224       | 5.68%   |
| Brazil       | 221       | 5.6%    |
| Italy        | 208       | 5.27%   |
| UK           | 184       | 4.66%   |
| Spain        | 117       | 2.96%   |
| Canada       | 102       | 2.58%   |
| Poland       | 99        | 2.51%   |
| Netherlands  | 93        | 2.36%   |
| India        | 75        | 1.9%    |
| Australia    | 73        | 1.85%   |
| Ukraine      | 63        | 1.6%    |
| Mexico       | 50        | 1.27%   |
| Hungary      | 49        | 1.24%   |
| Switzerland  | 46        | 1.17%   |
| Czechia      | 40        | 1.01%   |
| Belgium      | 37        | 0.94%   |
| Argentina    | 36        | 0.91%   |
| Austria      | 34        | 0.86%   |
| Turkey       | 31        | 0.79%   |
| Sweden       | 29        | 0.73%   |
| Indonesia    | 27        | 0.68%   |
| Greece       | 26        | 0.66%   |
| Finland      | 26        | 0.66%   |
| South Africa | 25        | 0.63%   |
| Bulgaria     | 24        | 0.61%   |
| Romania      | 22        | 0.56%   |
| Portugal     | 22        | 0.56%   |
| Denmark      | 22        | 0.56%   |
| Slovenia     | 21        | 0.53%   |
| Serbia       | 20        | 0.51%   |
| New Zealand  | 18        | 0.46%   |
| Colombia     | 18        | 0.46%   |
| Slovakia     | 16        | 0.41%   |
| China        | 16        | 0.41%   |
| Belarus      | 16        | 0.41%   |
| Norway       | 15        | 0.38%   |
| Chile        | 15        | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 75        | 1.82%   |
| Berlin            | 46        | 1.12%   |
| Paris             | 37        | 0.9%    |
| St Petersburg     | 33        | 0.8%    |
| Hamburg           | 32        | 0.78%   |
| Milan             | 30        | 0.73%   |
| Warsaw            | 28        | 0.68%   |
| Rome              | 25        | 0.61%   |
| Sao Paulo         | 24        | 0.58%   |
| Madrid            | 22        | 0.53%   |
| Budapest          | 22        | 0.53%   |
| Vienna            | 20        | 0.48%   |
| Sydney            | 20        | 0.48%   |
| Munich            | 20        | 0.48%   |
| Amsterdam         | 20        | 0.48%   |
| Rio de Janeiro    | 19        | 0.46%   |
| London            | 19        | 0.46%   |
| Cologne           | 19        | 0.46%   |
| Zurich            | 18        | 0.44%   |
| Kyiv              | 18        | 0.44%   |
| Melbourne         | 17        | 0.41%   |
| Frankfurt am Main | 17        | 0.41%   |
| Prague            | 15        | 0.36%   |
| Dallas            | 14        | 0.34%   |
| Belgrade          | 14        | 0.34%   |
| Sofia             | 13        | 0.32%   |
| Montreal          | 13        | 0.32%   |
| Minsk             | 13        | 0.32%   |
| Seattle           | 12        | 0.29%   |
| Novosibirsk       | 12        | 0.29%   |
| Krakow            | 12        | 0.29%   |
| Jakarta           | 12        | 0.29%   |
| Athens            | 12        | 0.29%   |
| Los Angeles       | 11        | 0.27%   |
| Helsinki          | 11        | 0.27%   |
| Auckland          | 11        | 0.27%   |
| Wroclaw           | 10        | 0.24%   |
| San Francisco     | 10        | 0.24%   |
| Phoenix           | 10        | 0.24%   |
| Miami             | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1111      | 1709   | 17.9%   |
| WDC                         | 900       | 1417   | 14.5%   |
| Seagate                     | 791       | 1209   | 12.75%  |
| Kingston                    | 361       | 434    | 5.82%   |
| Toshiba                     | 360       | 488    | 5.8%    |
| SanDisk                     | 343       | 427    | 5.53%   |
| Crucial                     | 254       | 316    | 4.09%   |
| Unknown                     | 207       | 258    | 3.34%   |
| Intel                       | 188       | 249    | 3.03%   |
| SK hynix                    | 162       | 194    | 2.61%   |
| Hitachi                     | 157       | 196    | 2.53%   |
| Micron Technology           | 118       | 131    | 1.9%    |
| HGST                        | 115       | 148    | 1.85%   |
| A-DATA Technology           | 93        | 100    | 1.5%    |
| KIOXIA                      | 53        | 60     | 0.85%   |
| Phison                      | 51        | 66     | 0.82%   |
| China                       | 48        | 65     | 0.77%   |
| Silicon Motion              | 40        | 45     | 0.64%   |
| PNY                         | 37        | 50     | 0.6%    |
| Apple                       | 36        | 42     | 0.58%   |
| SPCC                        | 34        | 43     | 0.55%   |
| Patriot                     | 32        | 43     | 0.52%   |
| Intenso                     | 31        | 37     | 0.5%    |
| Transcend                   | 29        | 31     | 0.47%   |
| Phison Electronics          | 28        | 28     | 0.45%   |
| OCZ                         | 26        | 33     | 0.42%   |
| Maxtor                      | 25        | 28     | 0.4%    |
| LITEON                      | 25        | 27     | 0.4%    |
| Corsair                     | 24        | 37     | 0.39%   |
| Micron/Crucial Technology   | 22        | 29     | 0.35%   |
| Unknown                     | 20        | 21     | 0.32%   |
| JMicron Technology          | 19        | 21     | 0.31%   |
| GOODRAM                     | 19        | 34     | 0.31%   |
| XPG                         | 15        | 16     | 0.24%   |
| Team                        | 15        | 16     | 0.24%   |
| SABRENT                     | 14        | 17     | 0.23%   |
| LITEONIT                    | 14        | 16     | 0.23%   |
| Kingston Technology Company | 14        | 15     | 0.23%   |
| KingSpec                    | 13        | 15     | 0.21%   |
| Gigabyte Technology         | 13        | 14     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 61        | 0.88%   |
| Kingston SA400S37240G 240GB SSD                     | 61        | 0.88%   |
| Samsung SSD 850 EVO 250GB                           | 52        | 0.75%   |
| Samsung SSD 850 EVO 500GB                           | 51        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                     | 44        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                      | 42        | 0.6%    |
| Samsung SSD 860 EVO 1TB                             | 40        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 36        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 35        | 0.5%    |
| Unknown MMC Card  32GB                              | 34        | 0.49%   |
| Unknown MMC Card  64GB                              | 33        | 0.47%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.47%   |
| Toshiba MQ04ABF100 1TB                              | 32        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                        | 32        | 0.46%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                      | 31        | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 31        | 0.45%   |
| HGST HTS721010A9E630 1TB                            | 31        | 0.45%   |
| Samsung NVMe SSD Drive 1TB                          | 30        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 27        | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                      | 26        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB                      | 26        | 0.37%   |
| Samsung SSD 860 EVO 250GB                           | 26        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                      | 25        | 0.36%   |
| Toshiba HDWD110 1TB                                 | 24        | 0.34%   |
| Toshiba DT01ACA100 1TB                              | 24        | 0.34%   |
| Seagate ST500DM002-1BD142 500GB                     | 24        | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB                      | 24        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 23        | 0.33%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.32%   |
| Seagate Expansion 1TB                               | 21        | 0.3%    |
| SanDisk SSD PLUS 240GB                              | 21        | 0.3%    |
| Crucial CT500MX500SSD1 500GB                        | 21        | 0.3%    |
| Seagate ST500LT012-1DG142 500GB                     | 20        | 0.29%   |
| Seagate ST2000DM001-1ER164 2TB                      | 20        | 0.29%   |
| SanDisk NVMe SSD Drive 512GB                        | 20        | 0.29%   |
| Crucial CT240BX500SSD1 240GB                        | 20        | 0.29%   |
| Unknown                                             | 20        | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 19        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 771       | 1169   | 35.4%   |
| WDC                 | 671       | 1092   | 30.81%  |
| Toshiba             | 250       | 342    | 11.48%  |
| Hitachi             | 157       | 196    | 7.21%   |
| HGST                | 114       | 147    | 5.23%   |
| Samsung Electronics | 105       | 164    | 4.82%   |
| Maxtor              | 24        | 27     | 1.1%    |
| Unknown             | 22        | 26     | 1.01%   |
| Apple               | 14        | 14     | 0.64%   |
| JMicron Technology  | 11        | 12     | 0.51%   |
| Fujitsu             | 10        | 13     | 0.46%   |
| ASMT                | 7         | 8      | 0.32%   |
| External            | 5         | 6      | 0.23%   |
| Hewlett-Packard     | 3         | 5      | 0.14%   |
| USB3.0              | 2         | 2      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 2      | 0.05%   |
| LIO-ORG             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| ipTIME              | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| HPE                 | 1         | 6      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| ASMedia             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 559       | 800    | 26.62%  |
| Kingston            | 264       | 315    | 12.57%  |
| Crucial             | 212       | 270    | 10.1%   |
| SanDisk             | 205       | 247    | 9.76%   |
| WDC                 | 115       | 153    | 5.48%   |
| A-DATA Technology   | 66        | 72     | 3.14%   |
| Intel               | 57        | 73     | 2.71%   |
| China               | 47        | 64     | 2.24%   |
| Micron Technology   | 39        | 42     | 1.86%   |
| Toshiba             | 35        | 50     | 1.67%   |
| PNY                 | 33        | 46     | 1.57%   |
| Patriot             | 32        | 43     | 1.52%   |
| SPCC                | 28        | 36     | 1.33%   |
| SK hynix            | 27        | 29     | 1.29%   |
| Intenso             | 27        | 31     | 1.29%   |
| OCZ                 | 26        | 33     | 1.24%   |
| Transcend           | 23        | 23     | 1.1%    |
| LITEON              | 20        | 21     | 0.95%   |
| GOODRAM             | 19        | 34     | 0.9%    |
| Team                | 14        | 14     | 0.67%   |
| LITEONIT            | 14        | 16     | 0.67%   |
| KingSpec            | 13        | 15     | 0.62%   |
| Corsair             | 13        | 24     | 0.62%   |
| Apple               | 12        | 12     | 0.57%   |
| Apacer              | 11        | 16     | 0.52%   |
| Mushkin             | 10        | 11     | 0.48%   |
| Lexar               | 7         | 8      | 0.33%   |
| Emtec               | 7         | 7      | 0.33%   |
| Verbatim            | 6         | 8      | 0.29%   |
| Seagate             | 6         | 11     | 0.29%   |
| Plextor             | 6         | 7      | 0.29%   |
| Netac               | 6         | 7      | 0.29%   |
| Dogfish             | 6         | 6      | 0.29%   |
| Unknown             | 6         | 6      | 0.29%   |
| Hewlett-Packard     | 5         | 5      | 0.24%   |
| Gigabyte Technology | 5         | 5      | 0.24%   |
| Unknown             | 4         | 4      | 0.19%   |
| KingDian            | 4         | 5      | 0.19%   |
| Drevo               | 4         | 5      | 0.19%   |
| Zheino              | 3         | 5      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1806      | 2705   | 32.82%  |
| HDD     | 1760      | 3241   | 31.99%  |
| NVMe    | 1665      | 2257   | 30.26%  |
| MMC     | 183       | 224    | 3.33%   |
| Unknown | 88        | 124    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2737      | 5744   | 56.82%  |
| NVMe | 1655      | 2236   | 34.36%  |
| SAS  | 242       | 347    | 5.02%   |
| MMC  | 183       | 224    | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1916      | 3016   | 50.25%  |
| 0.51-1.0   | 1198      | 1799   | 31.42%  |
| 1.01-2.0   | 396       | 618    | 10.39%  |
| 3.01-4.0   | 131       | 236    | 3.44%   |
| 2.01-3.0   | 80        | 116    | 2.1%    |
| 4.01-10.0  | 80        | 138    | 2.1%    |
| 10.01-20.0 | 12        | 23     | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1000      | 24.48%  |
| 251-500        | 973       | 23.82%  |
| 501-1000       | 749       | 18.34%  |
| 1001-2000      | 434       | 10.62%  |
| More than 3000 | 315       | 7.71%   |
| 51-100         | 204       | 4.99%   |
| 2001-3000      | 191       | 4.68%   |
| 1-20           | 111       | 2.72%   |
| 21-50          | 91        | 2.23%   |
| Unknown        | 17        | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 943       | 22.4%   |
| 101-250        | 732       | 17.39%  |
| 21-50          | 659       | 15.66%  |
| 51-100         | 558       | 13.26%  |
| 251-500        | 491       | 11.67%  |
| 501-1000       | 372       | 8.84%   |
| 1001-2000      | 218       | 5.18%   |
| More than 3000 | 147       | 3.49%   |
| 2001-3000      | 72        | 1.71%   |
| Unknown        | 17        | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 12     | 1.4%    |
| HGST HTS721010A9E630 1TB             | 6         | 7      | 1.4%    |
| Seagate ST500DM002-1BD142 500GB      | 5         | 5      | 1.16%   |
| Seagate ST31000524AS 1TB             | 5         | 6      | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 5      | 1.16%   |
| Toshiba MQ04ABF100 1TB               | 4         | 4      | 0.93%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 10     | 0.93%   |
| Crucial CT1050MX300SSD1 1050GB       | 4         | 4      | 0.93%   |
| WDC WD5000AAKS-00V1A0 500GB          | 3         | 4      | 0.7%    |
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 6      | 0.7%    |
| Toshiba MQ01ABD100 1TB               | 3         | 5      | 0.7%    |
| Seagate ST9500325AS 500GB            | 3         | 4      | 0.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.7%    |
| Seagate ST3500418AS 500GB            | 3         | 3      | 0.7%    |
| Seagate ST31000528AS 1TB             | 3         | 3      | 0.7%    |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.7%    |
| Kingston SV300S37A120G 120GB SSD     | 3         | 3      | 0.7%    |
| Hitachi HTS547564A9E384 640GB        | 3         | 3      | 0.7%    |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 0.7%    |
| HGST HTS541010A9E680 1TB             | 3         | 4      | 0.7%    |
| Crucial CT525MX300SSD1 528GB         | 3         | 3      | 0.7%    |
| WDC WD5000AAKS-00A7B0 500GB          | 2         | 2      | 0.47%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 2         | 2      | 0.47%   |
| WDC WD3200JD-22KLB0 320GB            | 2         | 2      | 0.47%   |
| WDC WD30EZRX-00MMMB0 3TB             | 2         | 2      | 0.47%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 2      | 0.47%   |
| WDC WD15EARS-00Z5B1 1TB              | 2         | 2      | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2      | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 2      | 0.47%   |
| WDC WD10EARS-00MVWB0 1TB             | 2         | 4      | 0.47%   |
| WDC WD10EADS-00L5B1 1TB              | 2         | 2      | 0.47%   |
| WDC WD1001FALS-40U9B0 1TB            | 2         | 2      | 0.47%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 2         | 2      | 0.47%   |
| Toshiba MQ01ABD075 752GB             | 2         | 4      | 0.47%   |
| Toshiba MK1652GSX 160GB              | 2         | 2      | 0.47%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.47%   |
| SK hynix SC401 SATA 512GB SSD        | 2         | 2      | 0.47%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.47%   |
| SK hynix BC711 HFM256GD3JX013N 256GB | 2         | 2      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 117    | 21.88%  |
| WDC                 | 90        | 113    | 21.63%  |
| Samsung Electronics | 42        | 56     | 10.1%   |
| Toshiba             | 34        | 40     | 8.17%   |
| Hitachi             | 28        | 28     | 6.73%   |
| Crucial             | 19        | 23     | 4.57%   |
| SanDisk             | 15        | 16     | 3.61%   |
| HGST                | 15        | 17     | 3.61%   |
| Intel               | 14        | 18     | 3.37%   |
| SK hynix            | 11        | 11     | 2.64%   |
| Kingston            | 10        | 10     | 2.4%    |
| Maxtor              | 6         | 7      | 1.44%   |
| A-DATA Technology   | 6         | 6      | 1.44%   |
| Micron Technology   | 5         | 5      | 1.2%    |
| OCZ                 | 4         | 4      | 0.96%   |
| Apple               | 3         | 3      | 0.72%   |
| LITEONIT            | 2         | 2      | 0.48%   |
| Intenso             | 2         | 2      | 0.48%   |
| Fujitsu             | 2         | 2      | 0.48%   |
| Zheino              | 1         | 2      | 0.24%   |
| XPG                 | 1         | 1      | 0.24%   |
| VISIPRO             | 1         | 2      | 0.24%   |
| VENO                | 1         | 1      | 0.24%   |
| tecmiyo             | 1         | 3      | 0.24%   |
| Team                | 1         | 1      | 0.24%   |
| T-FORCE             | 1         | 1      | 0.24%   |
| SPCC                | 1         | 1      | 0.24%   |
| R580                | 1         | 1      | 0.24%   |
| Phison Electronics  | 1         | 1      | 0.24%   |
| ORTIAL              | 1         | 1      | 0.24%   |
| Neo                 | 1         | 1      | 0.24%   |
| Mushkin             | 1         | 1      | 0.24%   |
| Drevo               | 1         | 1      | 0.24%   |
| BAITITON            | 1         | 3      | 0.24%   |
| ASMT                | 1         | 1      | 0.24%   |
| ASENNO              | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 117    | 32.62%  |
| WDC                 | 87        | 110    | 31.18%  |
| Toshiba             | 29        | 35     | 10.39%  |
| Hitachi             | 28        | 28     | 10.04%  |
| Samsung Electronics | 17        | 29     | 6.09%   |
| HGST                | 15        | 17     | 5.38%   |
| Maxtor              | 6         | 7      | 2.15%   |
| Apple               | 3         | 3      | 1.08%   |
| Fujitsu             | 2         | 2      | 0.72%   |
| ASMT                | 1         | 1      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 254       | 349    | 65.46%  |
| SSD  | 108       | 128    | 27.84%  |
| NVMe | 26        | 26     | 6.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 14.29%  |
| OCZ VERTEX460A 480GB SSD              | 1         | 1      | 14.29%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 14.29%  |
| Acer SSD FA100 256GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 28.57%  |
| Seagate             | 1         | 1      | 14.29%  |
| OCZ                 | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Acer                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2029      | 4468   | 45.78%  |
| Works    | 2019      | 3572   | 45.56%  |
| Malfunc  | 378       | 503    | 8.53%   |
| Failed   | 6         | 8      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2483      | 46.92%  |
| AMD                              | 883       | 16.69%  |
| Samsung Electronics              | 543       | 10.26%  |
| SanDisk                          | 283       | 5.35%   |
| SK hynix                         | 134       | 2.53%   |
| Kingston Technology Company      | 112       | 2.12%   |
| Phison Electronics               | 98        | 1.85%   |
| ASMedia Technology               | 89        | 1.68%   |
| Toshiba America Info Systems     | 86        | 1.63%   |
| Micron Technology                | 79        | 1.49%   |
| Micron/Crucial Technology        | 64        | 1.21%   |
| Silicon Motion                   | 54        | 1.02%   |
| JMicron Technology               | 52        | 0.98%   |
| KIOXIA                           | 50        | 0.94%   |
| Marvell Technology Group         | 43        | 0.81%   |
| ADATA Technology                 | 43        | 0.81%   |
| Nvidia                           | 42        | 0.79%   |
| Realtek Semiconductor            | 24        | 0.45%   |
| Solid State Storage Technology   | 17        | 0.32%   |
| Union Memory (Shenzhen)          | 15        | 0.28%   |
| Broadcom / LSI                   | 13        | 0.25%   |
| LSI Logic / Symbios Logic        | 11        | 0.21%   |
| Lite-On Technology               | 10        | 0.19%   |
| Silicon Image                    | 9         | 0.17%   |
| Apple                            | 8         | 0.15%   |
| VIA Technologies                 | 7         | 0.13%   |
| Seagate Technology               | 7         | 0.13%   |
| Lenovo                           | 5         | 0.09%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| Netac Technology                 | 3         | 0.06%   |
| INNOGRIT                         | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Solidigm                         | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 628       | 10.45%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 303       | 5.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 212       | 3.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 196       | 3.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 162       | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 154       | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 130       | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 123       | 2.05%   |
| Samsung NVMe SSD Controller 980                                                | 99        | 1.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 99        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 99        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 95        | 1.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 87        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 87        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 82        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 80        | 1.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 79        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 78        | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 73        | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 73        | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 72        | 1.2%    |
| Intel SSD 660P Series                                                          | 68        | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 66        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 62        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 60        | 1%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 60        | 1%      |
| Intel SATA Controller [RAID mode]                                              | 59        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 54        | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 52        | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 48        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 47        | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 45        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 45        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 44        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 43        | 0.72%   |
| AMD FCH SATA Controller D                                                      | 43        | 0.72%   |
| AMD 300 Series Chipset SATA Controller                                         | 43        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 42        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 40        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2885      | 54.45%  |
| NVMe | 1650      | 31.14%  |
| RAID | 395       | 7.46%   |
| IDE  | 346       | 6.53%   |
| SAS  | 14        | 0.26%   |
| SCSI | 8         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2823      | 71.7%   |
| AMD           | 1106      | 28.09%  |
| ARM           | 3         | 0.08%   |
| sifive,u74-mc | 2         | 0.05%   |
| QUALCOMM      | 1         | 0.03%   |
| Phytium       | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 64        | 1.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 51        | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 48        | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 42        | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 41        | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 39        | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 39        | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 39        | 0.99%   |
| AMD Ryzen 5 3600 6-Core Processor             | 39        | 0.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 39        | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 38        | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 36        | 0.91%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 35        | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 31        | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 29        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 27        | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 25        | 0.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 25        | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 24        | 0.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 24        | 0.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 24        | 0.61%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 23        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 23        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 21        | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 20        | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 19        | 0.48%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 19        | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 19        | 0.48%   |
| AMD FX-8350 Eight-Core Processor              | 19        | 0.48%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 18        | 0.46%   |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.46%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 18        | 0.46%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 17        | 0.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 16        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 907       | 22.99%  |
| Intel Core i5           | 842       | 21.34%  |
| Other                   | 329       | 8.34%   |
| AMD Ryzen 5             | 310       | 7.86%   |
| AMD Ryzen 7             | 264       | 6.69%   |
| Intel Core i3           | 210       | 5.32%   |
| Intel Celeron           | 137       | 3.47%   |
| AMD Ryzen 9             | 96        | 2.43%   |
| Intel Core 2 Duo        | 91        | 2.31%   |
| Intel Xeon              | 86        | 2.18%   |
| AMD FX                  | 69        | 1.75%   |
| Intel Pentium           | 68        | 1.72%   |
| AMD Ryzen 3             | 47        | 1.19%   |
| Intel Core i9           | 36        | 0.91%   |
| AMD A6                  | 32        | 0.81%   |
| AMD A10                 | 31        | 0.79%   |
| AMD Ryzen 7 PRO         | 28        | 0.71%   |
| AMD A8                  | 28        | 0.71%   |
| Intel Pentium Dual-Core | 26        | 0.66%   |
| Intel Atom              | 26        | 0.66%   |
| Intel Core 2 Quad       | 24        | 0.61%   |
| AMD Phenom II X4        | 22        | 0.56%   |
| AMD Ryzen 5 PRO         | 18        | 0.46%   |
| Intel Pentium Silver    | 17        | 0.43%   |
| AMD Athlon II X4        | 14        | 0.35%   |
| AMD A4                  | 14        | 0.35%   |
| AMD Athlon              | 13        | 0.33%   |
| AMD Ryzen Threadripper  | 11        | 0.28%   |
| AMD Athlon II X2        | 10        | 0.25%   |
| AMD Athlon 64 X2        | 9         | 0.23%   |
| Intel Pentium Dual      | 8         | 0.2%    |
| Intel Genuine           | 8         | 0.2%    |
| AMD E1                  | 8         | 0.2%    |
| AMD E                   | 8         | 0.2%    |
| Intel Core m3           | 6         | 0.15%   |
| AMD Phenom II X6        | 6         | 0.15%   |
| AMD E2                  | 6         | 0.15%   |
| Intel Core 2            | 5         | 0.13%   |
| Intel Celeron Dual-Core | 5         | 0.13%   |
| AMD Sempron             | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1572      | 39.86%  |
| 2       | 1212      | 30.73%  |
| 6       | 514       | 13.03%  |
| 8       | 383       | 9.71%   |
| 12      | 88        | 2.23%   |
| 16      | 48        | 1.22%   |
| 1       | 38        | 0.96%   |
| 14      | 27        | 0.68%   |
| 10      | 25        | 0.63%   |
| 3       | 11        | 0.28%   |
| 24      | 10        | 0.25%   |
| 32      | 5         | 0.13%   |
| 20      | 3         | 0.08%   |
| Unknown | 3         | 0.08%   |
| 18      | 2         | 0.05%   |
| 64      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3905      | 99.19%  |
| 2       | 26        | 0.66%   |
| Unknown | 3         | 0.08%   |
| 4       | 2         | 0.05%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2975      | 75.37%  |
| 1       | 969       | 24.55%  |
| Unknown | 3         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3931      | 99.85%  |
| Unknown        | 3         | 0.08%   |
| 32-bit         | 2         | 0.05%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1172      | 28.9%   |
| 0x306a9    | 177       | 4.36%   |
| 0x306c3    | 164       | 4.04%   |
| 0x206a7    | 155       | 3.82%   |
| 0x906ea    | 127       | 3.13%   |
| 0x806ec    | 111       | 2.74%   |
| 0x806c1    | 107       | 2.64%   |
| 0x806ea    | 101       | 2.49%   |
| 0x40651    | 81        | 2%      |
| 0x1067a    | 79        | 1.95%   |
| 0x906e9    | 77        | 1.9%    |
| 0x806e9    | 76        | 1.87%   |
| 0x08701021 | 76        | 1.87%   |
| 0x506e3    | 74        | 1.82%   |
| 0x406e3    | 62        | 1.53%   |
| 0x0a50000c | 59        | 1.45%   |
| 0x08108109 | 54        | 1.33%   |
| 0x08600106 | 46        | 1.13%   |
| 0x0800820d | 46        | 1.13%   |
| 0x306d4    | 45        | 1.11%   |
| 0x906a3    | 41        | 1.01%   |
| 0x06000852 | 40        | 0.99%   |
| 0x706e5    | 38        | 0.94%   |
| 0x08701013 | 38        | 0.94%   |
| 0x08108102 | 38        | 0.94%   |
| 0xa0652    | 36        | 0.89%   |
| 0x906ed    | 32        | 0.79%   |
| 0x806eb    | 32        | 0.79%   |
| 0x706a1    | 28        | 0.69%   |
| 0x08608103 | 28        | 0.69%   |
| 0x010000c8 | 28        | 0.69%   |
| 0x20655    | 27        | 0.67%   |
| 0x706a8    | 24        | 0.59%   |
| 0x406c4    | 23        | 0.57%   |
| 0x08600104 | 22        | 0.54%   |
| 0x806d1    | 20        | 0.49%   |
| 0x30678    | 20        | 0.49%   |
| 0x06001119 | 20        | 0.49%   |
| 0xa0653    | 19        | 0.47%   |
| 0x506c9    | 19        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 750       | 19%     |
| Haswell          | 377       | 9.55%   |
| IvyBridge        | 266       | 6.74%   |
| Zen 2            | 253       | 6.41%   |
| SandyBridge      | 225       | 5.7%    |
| Skylake          | 194       | 4.91%   |
| Zen+             | 191       | 4.84%   |
| Zen 3            | 168       | 4.26%   |
| TigerLake        | 162       | 4.1%    |
| Unknown          | 156       | 3.95%   |
| Penryn           | 130       | 3.29%   |
| CometLake        | 106       | 2.68%   |
| Zen              | 92        | 2.33%   |
| Piledriver       | 88        | 2.23%   |
| IceLake          | 84        | 2.13%   |
| Goldmont plus    | 74        | 1.87%   |
| K10              | 72        | 1.82%   |
| Alderlake Hybrid | 70        | 1.77%   |
| Westmere         | 69        | 1.75%   |
| Broadwell        | 67        | 1.7%    |
| Silvermont       | 61        | 1.55%   |
| Core             | 53        | 1.34%   |
| Excavator        | 45        | 1.14%   |
| Nehalem          | 44        | 1.11%   |
| Goldmont         | 25        | 0.63%   |
| Steamroller      | 19        | 0.48%   |
| Puma             | 19        | 0.48%   |
| K10 Llano        | 19        | 0.48%   |
| K8 Hammer        | 16        | 0.41%   |
| Jaguar           | 15        | 0.38%   |
| Bobcat           | 14        | 0.35%   |
| NetBurst         | 7         | 0.18%   |
| Bulldozer        | 7         | 0.18%   |
| Bonnell          | 5         | 0.13%   |
| Tremont          | 2         | 0.05%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2186      | 45.79%  |
| Nvidia                           | 1433      | 30.02%  |
| AMD                              | 1135      | 23.77%  |
| Matrox Electronics Systems       | 8         | 0.17%   |
| ASPEED Technology                | 8         | 0.17%   |
| ATI Technologies                 | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 154       | 3.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 149       | 3.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 148       | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 131       | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 124       | 2.54%   |
| Intel UHD Graphics 620                                                                   | 113       | 2.32%   |
| AMD Renoir                                                                               | 113       | 2.32%   |
| Intel HD Graphics 620                                                                    | 98        | 2.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 95        | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 92        | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 88        | 1.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 84        | 1.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 83        | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 81        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 78        | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 75        | 1.54%   |
| Intel HD Graphics 630                                                                    | 61        | 1.25%   |
| Intel HD Graphics 530                                                                    | 61        | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 59        | 1.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 54        | 1.11%   |
| Intel HD Graphics 5500                                                                   | 52        | 1.07%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 48        | 0.98%   |
| AMD Lucienne                                                                             | 48        | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 47        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 42        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 39        | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 38        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 35        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 33        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 31        | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 31        | 0.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 28        | 0.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 28        | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 0.55%   |
| AMD Rembrandt [Radeon 680M]                                                              | 26        | 0.53%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.51%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 25        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1445      | 36.55%  |
| 1 x AMD                  | 887       | 22.44%  |
| 1 x Nvidia               | 734       | 18.57%  |
| Intel + Nvidia           | 590       | 14.93%  |
| Intel + AMD              | 102       | 2.58%   |
| AMD + Nvidia             | 85        | 2.15%   |
| 2 x AMD                  | 61        | 1.54%   |
| 2 x Nvidia               | 16        | 0.4%    |
| Other                    | 9         | 0.23%   |
| Nvidia + ASPEED          | 4         | 0.1%    |
| 1 x ASPEED               | 4         | 0.1%    |
| Nvidia + Matrox          | 3         | 0.08%   |
| 1 x Matrox               | 3         | 0.08%   |
| 3 x Nvidia               | 2         | 0.05%   |
| 2 x Intel                | 2         | 0.05%   |
| AMD + Matrox             | 2         | 0.05%   |
| 1 x Zhaoxin              | 1         | 0.03%   |
| 1 x SiS                  | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2872      | 72.05%  |
| Proprietary | 1032      | 25.89%  |
| Unknown     | 82        | 2.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2218      | 54.96%  |
| 1.01-2.0   | 463       | 11.47%  |
| 0.01-0.5   | 350       | 8.67%   |
| 3.01-4.0   | 306       | 7.58%   |
| 0.51-1.0   | 280       | 6.94%   |
| 7.01-8.0   | 204       | 5.05%   |
| 5.01-6.0   | 113       | 2.8%    |
| 8.01-16.0  | 53        | 1.31%   |
| 2.01-3.0   | 35        | 0.87%   |
| 16.01-24.0 | 10        | 0.25%   |
| 4.01-5.0   | 3         | 0.07%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 587       | 12.65%  |
| AU Optronics            | 496       | 10.69%  |
| BOE                     | 423       | 9.11%   |
| LG Display              | 395       | 8.51%   |
| Chimei Innolux          | 375       | 8.08%   |
| Dell                    | 305       | 6.57%   |
| Goldstar                | 254       | 5.47%   |
| Acer                    | 165       | 3.56%   |
| Hewlett-Packard         | 162       | 3.49%   |
| BenQ                    | 120       | 2.59%   |
| Philips                 | 114       | 2.46%   |
| AOC                     | 111       | 2.39%   |
| Ancor Communications    | 111       | 2.39%   |
| Sharp                   | 109       | 2.35%   |
| Lenovo                  | 63        | 1.36%   |
| ASUSTek Computer        | 61        | 1.31%   |
| Iiyama                  | 57        | 1.23%   |
| ViewSonic               | 55        | 1.19%   |
| Apple                   | 48        | 1.03%   |
| PANDA                   | 47        | 1.01%   |
| Chi Mei Optoelectronics | 44        | 0.95%   |
| InfoVision              | 37        | 0.8%    |
| LG Electronics          | 31        | 0.67%   |
| Sony                    | 24        | 0.52%   |
| Unknown                 | 23        | 0.5%    |
| NEC Computers           | 20        | 0.43%   |
| Panasonic               | 19        | 0.41%   |
| Sceptre Tech            | 15        | 0.32%   |
| CSO                     | 15        | 0.32%   |
| HannStar                | 14        | 0.3%    |
| Eizo                    | 13        | 0.28%   |
| MSI                     | 12        | 0.26%   |
| Medion                  | 11        | 0.24%   |
| Vizio                   | 10        | 0.22%   |
| Toshiba                 | 10        | 0.22%   |
| Vestel Elektronik       | 8         | 0.17%   |
| Idek Iiyama             | 8         | 0.17%   |
| LG Philips              | 7         | 0.15%   |
| Gigabyte Technology     | 7         | 0.15%   |
| Fujitsu Siemens         | 6         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 21        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 20        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 20        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 20        | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 19        | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 19        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 17        | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 16        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 14        | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 13        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 13        | 0.27%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 13        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 12        | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 12        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 11        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10        | 0.21%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 9         | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9         | 0.19%   |
| LG Display LCD Monitor LGD0563 1920x1080 340x190mm 15.3-inch          | 9         | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9         | 0.19%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 8         | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8         | 0.17%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 8         | 0.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 8         | 0.17%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch        | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 8         | 0.17%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 7         | 0.14%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 7         | 0.14%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 7         | 0.14%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 7         | 0.14%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 7         | 0.14%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 7         | 0.14%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 7         | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2101      | 48.09%  |
| 1366x768 (WXGA)    | 619       | 14.17%  |
| 3840x2160 (4K)     | 316       | 7.23%   |
| 2560x1440 (QHD)    | 237       | 5.42%   |
| 1600x900 (HD+)     | 153       | 3.5%    |
| 1920x1200 (WUXGA)  | 140       | 3.2%    |
| 1680x1050 (WSXGA+) | 106       | 2.43%   |
| 1280x1024 (SXGA)   | 87        | 1.99%   |
| Unknown            | 76        | 1.74%   |
| 3440x1440          | 58        | 1.33%   |
| 1440x900 (WXGA+)   | 58        | 1.33%   |
| 2560x1080          | 47        | 1.08%   |
| 1280x800 (WXGA)    | 40        | 0.92%   |
| 2560x1600          | 35        | 0.8%    |
| 3840x1080          | 34        | 0.78%   |
| 1360x768           | 31        | 0.71%   |
| 2880x1800          | 26        | 0.6%    |
| 3840x2400          | 19        | 0.43%   |
| 2160x1440          | 19        | 0.43%   |
| 1920x540           | 14        | 0.32%   |
| 1600x1200          | 13        | 0.3%    |
| 1024x768 (XGA)     | 12        | 0.27%   |
| 3840x1200          | 9         | 0.21%   |
| 2240x1400          | 9         | 0.21%   |
| 3200x1800 (QHD+)   | 7         | 0.16%   |
| 2256x1504          | 7         | 0.16%   |
| 4480x1440          | 6         | 0.14%   |
| 1920x1280          | 6         | 0.14%   |
| 3840x1600          | 5         | 0.11%   |
| 2736x1824          | 5         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.11%   |
| 5760x1080          | 4         | 0.09%   |
| 3072x1920          | 4         | 0.09%   |
| 2520x1680          | 4         | 0.09%   |
| 2288x1287          | 4         | 0.09%   |
| 5760x2160          | 3         | 0.07%   |
| 3600x1080          | 3         | 0.07%   |
| 3456x2160          | 3         | 0.07%   |
| 3200x1080          | 3         | 0.07%   |
| 7680x2160          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1104      | 23.89%  |
| 27      | 398       | 8.61%   |
| 24      | 387       | 8.37%   |
| 13      | 376       | 8.14%   |
| 14      | 365       | 7.9%    |
| 23      | 328       | 7.1%    |
| 17      | 266       | 5.76%   |
| 21      | 255       | 5.52%   |
| Unknown | 240       | 5.19%   |
| 31      | 108       | 2.34%   |
| 34      | 91        | 1.97%   |
| 19      | 89        | 1.93%   |
| 22      | 67        | 1.45%   |
| 20      | 57        | 1.23%   |
| 12      | 55        | 1.19%   |
| 16      | 53        | 1.15%   |
| 18      | 51        | 1.1%    |
| 11      | 51        | 1.1%    |
| 32      | 30        | 0.65%   |
| 84      | 28        | 0.61%   |
| 25      | 24        | 0.52%   |
| 72      | 23        | 0.5%    |
| 54      | 22        | 0.48%   |
| 40      | 20        | 0.43%   |
| 26      | 16        | 0.35%   |
| 28      | 9         | 0.19%   |
| 48      | 8         | 0.17%   |
| 47      | 8         | 0.17%   |
| 46      | 8         | 0.17%   |
| 42      | 7         | 0.15%   |
| 37      | 7         | 0.15%   |
| 65      | 6         | 0.13%   |
| 52      | 5         | 0.11%   |
| 36      | 5         | 0.11%   |
| 10      | 5         | 0.11%   |
| 69      | 4         | 0.09%   |
| 60      | 4         | 0.09%   |
| 49      | 4         | 0.09%   |
| 39      | 4         | 0.09%   |
| 35      | 4         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1698      | 37.71%  |
| 501-600        | 1016      | 22.56%  |
| 401-500        | 463       | 10.28%  |
| 351-400        | 314       | 6.97%   |
| 201-300        | 296       | 6.57%   |
| Unknown        | 240       | 5.33%   |
| 601-700        | 164       | 3.64%   |
| 701-800        | 128       | 2.84%   |
| 1001-1500      | 72        | 1.6%    |
| 1501-2000      | 59        | 1.31%   |
| 801-900        | 37        | 0.82%   |
| 901-1000       | 9         | 0.2%    |
| More than 2000 | 3         | 0.07%   |
| 101-200        | 2         | 0.04%   |
| 1-100          | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3087      | 76.54%  |
| 16/10   | 446       | 11.06%  |
| Unknown | 209       | 5.18%   |
| 21/9    | 103       | 2.55%   |
| 5/4     | 80        | 1.98%   |
| 3/2     | 53        | 1.31%   |
| 4/3     | 30        | 0.74%   |
| 32/9    | 14        | 0.35%   |
| 1.00    | 3         | 0.07%   |
| 6/5     | 2         | 0.05%   |
| 1.96    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1104      | 24.31%  |
| 201-250        | 788       | 17.35%  |
| 81-90          | 583       | 12.84%  |
| 301-350        | 411       | 9.05%   |
| 351-500        | 241       | 5.31%   |
| Unknown        | 240       | 5.28%   |
| 151-200        | 210       | 4.62%   |
| 121-130        | 200       | 4.4%    |
| 71-80          | 163       | 3.59%   |
| 251-300        | 150       | 3.3%    |
| More than 1000 | 107       | 2.36%   |
| 141-150        | 81        | 1.78%   |
| 501-1000       | 72        | 1.59%   |
| 51-60          | 52        | 1.14%   |
| 61-70          | 46        | 1.01%   |
| 111-120        | 46        | 1.01%   |
| 131-140        | 27        | 0.59%   |
| 91-100         | 12        | 0.26%   |
| 41-50          | 5         | 0.11%   |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1377      | 31.24%  |
| 121-160       | 1295      | 29.38%  |
| 101-120       | 965       | 21.89%  |
| 161-240       | 293       | 6.65%   |
| Unknown       | 240       | 5.44%   |
| More than 240 | 134       | 3.04%   |
| 1-50          | 104       | 2.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2963      | 73.76%  |
| 2     | 849       | 21.14%  |
| 3     | 105       | 2.61%   |
| 0     | 87        | 2.17%   |
| 4     | 13        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2232      | 37.52%  |
| Intel                             | 2030      | 34.12%  |
| Qualcomm Atheros                  | 585       | 9.83%   |
| Broadcom                          | 252       | 4.24%   |
| MediaTek                          | 123       | 2.07%   |
| TP-Link                           | 68        | 1.14%   |
| Ralink Technology                 | 65        | 1.09%   |
| Ralink                            | 56        | 0.94%   |
| Broadcom Limited                  | 43        | 0.72%   |
| Nvidia                            | 34        | 0.57%   |
| Marvell Technology Group          | 31        | 0.52%   |
| ASIX Electronics                  | 31        | 0.52%   |
| Samsung Electronics               | 28        | 0.47%   |
| Aquantia                          | 23        | 0.39%   |
| Qualcomm Atheros Communications   | 20        | 0.34%   |
| Lenovo                            | 20        | 0.34%   |
| NetGear                           | 18        | 0.3%    |
| DisplayLink                       | 18        | 0.3%    |
| Xiaomi                            | 17        | 0.29%   |
| Qualcomm                          | 17        | 0.29%   |
| Microsoft                         | 17        | 0.29%   |
| Sierra Wireless                   | 16        | 0.27%   |
| Huawei Technologies               | 16        | 0.27%   |
| D-Link                            | 15        | 0.25%   |
| Dell                              | 12        | 0.2%    |
| ASUSTek Computer                  | 11        | 0.18%   |
| Ericsson Business Mobile Networks | 10        | 0.17%   |
| Edimax Technology                 | 9         | 0.15%   |
| Hewlett-Packard                   | 8         | 0.13%   |
| JMicron Technology                | 7         | 0.12%   |
| Apple                             | 7         | 0.12%   |
| Linksys                           | 6         | 0.1%    |
| Google                            | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| Belkin Components                 | 6         | 0.1%    |
| Fibocom                           | 5         | 0.08%   |
| AVM                               | 5         | 0.08%   |
| VIA Technologies                  | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.05%   |
| Wacom                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1527      | 21.91%  |
| Intel Wi-Fi 6 AX200                                               | 232       | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 194       | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 138       | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 138       | 1.98%   |
| Intel Wireless 8265 / 8275                                        | 126       | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 124       | 1.78%   |
| Intel I211 Gigabit Network Connection                             | 118       | 1.69%   |
| Intel Wi-Fi 6 AX201                                               | 113       | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 104       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 100       | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 92        | 1.32%   |
| Intel Wireless 7260                                               | 92        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 89        | 1.28%   |
| Intel Wireless 7265                                               | 87        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 84        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 75        | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 74        | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 73        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 68        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 64        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 63        | 0.9%    |
| Intel Wireless 3165                                               | 61        | 0.88%   |
| Intel Wireless 8260                                               | 58        | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 58        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 57        | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 56        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 55        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 51        | 0.73%   |
| Intel Wireless-AC 9260                                            | 50        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 47        | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 43        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 41        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 41        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 37        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 36        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 36        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 34        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 33        | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 31        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1564      | 48.29%  |
| Realtek Semiconductor                 | 532       | 16.42%  |
| Qualcomm Atheros                      | 459       | 14.17%  |
| Broadcom                              | 167       | 5.16%   |
| MediaTek                              | 119       | 3.67%   |
| Ralink Technology                     | 65        | 2.01%   |
| TP-Link                               | 62        | 1.91%   |
| Ralink                                | 56        | 1.73%   |
| Broadcom Limited                      | 33        | 1.02%   |
| Qualcomm Atheros Communications       | 20        | 0.62%   |
| NetGear                               | 18        | 0.56%   |
| Sierra Wireless                       | 16        | 0.49%   |
| Microsoft                             | 16        | 0.49%   |
| D-Link                                | 15        | 0.46%   |
| Qualcomm                              | 11        | 0.34%   |
| ASUSTek Computer                      | 11        | 0.34%   |
| Edimax Technology                     | 9         | 0.28%   |
| Dell                                  | 7         | 0.22%   |
| Marvell Technology Group              | 6         | 0.19%   |
| Belkin Components                     | 6         | 0.19%   |
| Linksys                               | 5         | 0.15%   |
| Fibocom                               | 5         | 0.15%   |
| AVM                                   | 5         | 0.15%   |
| Ericsson Business Mobile Networks     | 4         | 0.12%   |
| D-Link System                         | 4         | 0.12%   |
| Wacom                                 | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| ZyDAS                                 | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| Wilocity                              | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| LG Electronics                        | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 232       | 7.1%    |
| Intel Wireless 8265 / 8275                                     | 126       | 3.86%   |
| Intel Wi-Fi 6 AX201                                            | 113       | 3.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 104       | 3.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 100       | 3.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 92        | 2.82%   |
| Intel Wireless 7260                                            | 92        | 2.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 89        | 2.73%   |
| Intel Wireless 7265                                            | 87        | 2.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 84        | 2.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 75        | 2.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 74        | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 73        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 64        | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 63        | 1.93%   |
| Intel Wireless 3165                                            | 61        | 1.87%   |
| Intel Wireless 8260                                            | 58        | 1.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 57        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 55        | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 51        | 1.56%   |
| Intel Wireless-AC 9260                                         | 50        | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 47        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 43        | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 37        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 36        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 34        | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 33        | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 31        | 0.95%   |
| Ralink MT7601U Wireless Adapter                                | 30        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 29        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 28        | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 28        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 27        | 0.83%   |
| Intel Wireless 3160                                            | 26        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 25        | 0.77%   |
| Realtek 802.11ac NIC                                           | 25        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 24        | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 22        | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 22        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1996      | 56.23%  |
| Intel                            | 999       | 28.14%  |
| Qualcomm Atheros                 | 165       | 4.65%   |
| Broadcom                         | 109       | 3.07%   |
| Nvidia                           | 34        | 0.96%   |
| ASIX Electronics                 | 31        | 0.87%   |
| Marvell Technology Group         | 25        | 0.7%    |
| Aquantia                         | 23        | 0.65%   |
| Lenovo                           | 20        | 0.56%   |
| Samsung Electronics              | 19        | 0.54%   |
| DisplayLink                      | 18        | 0.51%   |
| Xiaomi                           | 17        | 0.48%   |
| Huawei Technologies              | 13        | 0.37%   |
| Broadcom Limited                 | 11        | 0.31%   |
| JMicron Technology               | 7         | 0.2%    |
| Apple                            | 7         | 0.2%    |
| TP-Link                          | 6         | 0.17%   |
| Qualcomm                         | 6         | 0.17%   |
| Google                           | 6         | 0.17%   |
| VIA Technologies                 | 4         | 0.11%   |
| MediaTek                         | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.08%   |
| T & A Mobile Phones              | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Motorola PCS                     | 2         | 0.06%   |
| Mellanox Technologies            | 2         | 0.06%   |
| D-Link System                    | 2         | 0.06%   |
| 3Com                             | 2         | 0.06%   |
| Tenda                            | 1         | 0.03%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| IBM                              | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Elecom                           | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1527      | 41.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 194       | 5.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 138       | 3.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 138       | 3.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 124       | 3.4%    |
| Intel I211 Gigabit Network Connection                             | 118       | 3.23%   |
| Intel Ethernet Connection (2) I219-V                              | 68        | 1.86%   |
| Intel Ethernet Connection I217-LM                                 | 58        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 56        | 1.53%   |
| Intel Ethernet Connection (7) I219-V                              | 41        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 41        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 36        | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 31        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 27        | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.69%   |
| Intel I210 Gigabit Network Connection                             | 23        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 17        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.41%   |
| Intel Ethernet Connection (13) I219-V                             | 15        | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3311      | 51.43%  |
| WiFi     | 3075      | 47.76%  |
| Modem    | 48        | 0.75%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2403      | 57.71%  |
| Ethernet | 1760      | 42.27%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2118      | 53.76%  |
| 1     | 1654      | 41.98%  |
| 3     | 89        | 2.26%   |
| 0     | 59        | 1.5%    |
| 4     | 15        | 0.38%   |
| 6     | 3         | 0.08%   |
| 5     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3197      | 80.05%  |
| Yes     | 796       | 19.93%  |
| Unknown | 1         | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1351      | 50.35%  |
| Realtek Semiconductor           | 277       | 10.32%  |
| Qualcomm Atheros Communications | 206       | 7.68%   |
| Cambridge Silicon Radio         | 180       | 6.71%   |
| Broadcom                        | 122       | 4.55%   |
| IMC Networks                    | 108       | 4.03%   |
| Lite-On Technology              | 84        | 3.13%   |
| Foxconn / Hon Hai               | 81        | 3.02%   |
| Apple                           | 51        | 1.9%    |
| ASUSTek Computer                | 42        | 1.57%   |
| Dell                            | 34        | 1.27%   |
| Realtek                         | 29        | 1.08%   |
| Ralink                          | 15        | 0.56%   |
| MediaTek                        | 14        | 0.52%   |
| Hewlett-Packard                 | 13        | 0.48%   |
| Toshiba                         | 11        | 0.41%   |
| Foxconn International           | 8         | 0.3%    |
| TP-Link                         | 7         | 0.26%   |
| Marvell Semiconductor           | 7         | 0.26%   |
| Ralink Technology               | 5         | 0.19%   |
| Dynex                           | 5         | 0.19%   |
| ISSC                            | 4         | 0.15%   |
| Edimax Technology               | 4         | 0.15%   |
| Alps Electric                   | 4         | 0.15%   |
| USI                             | 2         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| D-Link                          | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 435       | 16.2%   |
| Intel AX201 Bluetooth                               | 271       | 10.09%  |
| Intel AX200 Bluetooth                               | 226       | 8.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 195       | 7.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 180       | 6.7%    |
| Realtek Bluetooth Radio                             | 173       | 6.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 110       | 4.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 2.83%   |
| Intel Bluetooth Device                              | 51        | 1.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 48        | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 1.64%   |
| Intel AX210 Bluetooth                               | 37        | 1.38%   |
| IMC Networks Bluetooth Radio                        | 34        | 1.27%   |
| IMC Networks Wireless_Device                        | 33        | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 31        | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 31        | 1.15%   |
| Lite-On Bluetooth Device                            | 28        | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 28        | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 1.01%   |
| Realtek 802.11ac WLAN Adapter                       | 23        | 0.86%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 23        | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 0.82%   |
| Lite-On Wireless_Device                             | 20        | 0.74%   |
| IMC Networks Bluetooth Device                       | 20        | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.74%   |
| Apple Bluetooth USB Host Controller                 | 20        | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.67%   |
| Apple Bluetooth Host Controller                     | 18        | 0.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.6%    |
| Ralink RT3290 Bluetooth                             | 15        | 0.56%   |
| MediaTek Wireless_Device                            | 14        | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.45%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.45%   |
| ASUS ASUS USB-BT500                                 | 12        | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 12        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2748      | 47.35%  |
| AMD                        | 1298      | 22.36%  |
| Nvidia                     | 1046      | 18.02%  |
| C-Media Electronics        | 110       | 1.9%    |
| Logitech                   | 44        | 0.76%   |
| GN Netcom                  | 39        | 0.67%   |
| Creative Labs              | 38        | 0.65%   |
| JMTek                      | 32        | 0.55%   |
| Realtek Semiconductor      | 31        | 0.53%   |
| Texas Instruments          | 23        | 0.4%    |
| Corsair                    | 20        | 0.34%   |
| ASUSTek Computer           | 20        | 0.34%   |
| Generalplus Technology     | 19        | 0.33%   |
| Razer USA                  | 18        | 0.31%   |
| Lenovo                     | 18        | 0.31%   |
| Creative Technology        | 16        | 0.28%   |
| Hewlett-Packard            | 15        | 0.26%   |
| Plantronics                | 14        | 0.24%   |
| SteelSeries ApS            | 12        | 0.21%   |
| Kingston Technology        | 12        | 0.21%   |
| Focusrite-Novation         | 10        | 0.17%   |
| VIA Technologies           | 9         | 0.16%   |
| Blue Microphones           | 9         | 0.16%   |
| Tenx Technology            | 8         | 0.14%   |
| Sony                       | 7         | 0.12%   |
| Dell                       | 7         | 0.12%   |
| SAVITECH                   | 6         | 0.1%    |
| Micro Star International   | 5         | 0.09%   |
| Yamaha                     | 4         | 0.07%   |
| Trust                      | 4         | 0.07%   |
| Sennheiser Communications  | 4         | 0.07%   |
| Scarlett                   | 4         | 0.07%   |
| PreSonus Audio Electronics | 4         | 0.07%   |
| M-Audio                    | 4         | 0.07%   |
| GYROCOM C&C                | 4         | 0.07%   |
| BEHRINGER International    | 4         | 0.07%   |
| ZOOM                       | 3         | 0.05%   |
| TerraTec Electronic        | 3         | 0.05%   |
| TEAC                       | 3         | 0.05%   |
| Samson Technologies        | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 459       | 6.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 310       | 4.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 244       | 3.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 234       | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 219       | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 214       | 3.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 198       | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 197       | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 172       | 2.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 162       | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 151       | 2.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 132       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 122       | 1.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 112       | 1.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 111       | 1.6%    |
| AMD FCH Azalia Controller                                                  | 104       | 1.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 101       | 1.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 94        | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 93        | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 91        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 85        | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 82        | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 76        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 75        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 74        | 1.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 73        | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 72        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 68        | 0.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 67        | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 66        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 65        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 60        | 0.87%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 59        | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 59        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 53        | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 51        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 51        | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 50        | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 50        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 640       | 21.84%  |
| SK hynix            | 470       | 16.04%  |
| Kingston            | 380       | 12.97%  |
| Micron Technology   | 303       | 10.34%  |
| Crucial             | 216       | 7.37%   |
| Unknown             | 196       | 6.69%   |
| Corsair             | 180       | 6.14%   |
| G.Skill             | 133       | 4.54%   |
| A-DATA Technology   | 54        | 1.84%   |
| Ramaxel Technology  | 50        | 1.71%   |
| Unknown (ABCD)      | 39        | 1.33%   |
| Elpida              | 31        | 1.06%   |
| Nanya Technology    | 30        | 1.02%   |
| Team                | 24        | 0.82%   |
| Patriot             | 19        | 0.65%   |
| Unknown             | 18        | 0.61%   |
| Transcend           | 15        | 0.51%   |
| Smart               | 15        | 0.51%   |
| Goodram             | 8         | 0.27%   |
| AMD                 | 8         | 0.27%   |
| Silicon Power       | 7         | 0.24%   |
| Apacer              | 6         | 0.2%    |
| Wilk                | 5         | 0.17%   |
| Teikon              | 5         | 0.17%   |
| Smart Brazil        | 5         | 0.17%   |
| Avant               | 5         | 0.17%   |
| PNY                 | 4         | 0.14%   |
| ASint Technology    | 4         | 0.14%   |
| SHARETRONIC         | 3         | 0.1%    |
| Goldkey             | 3         | 0.1%    |
| CSX                 | 3         | 0.1%    |
| V-GeN               | 2         | 0.07%   |
| Unifosa             | 2         | 0.07%   |
| Reboto              | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| Kingmax             | 2         | 0.07%   |
| Imation             | 2         | 0.07%   |
| Hewlett-Packard     | 2         | 0.07%   |
| GLOWAY              | 2         | 0.07%   |
| GeIL                | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 31        | 0.99%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 22        | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 18        | 0.57%   |
| Unknown                                                          | 18        | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 17        | 0.54%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 17        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.45%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 14        | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 13        | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.41%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 12        | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.32%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.32%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.32%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.32%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.32%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1436      | 57.14%  |
| DDR3    | 680       | 27.06%  |
| LPDDR4  | 111       | 4.42%   |
| Unknown | 61        | 2.43%   |
| LPDDR3  | 58        | 2.31%   |
| DDR2    | 50        | 1.99%   |
| DDR5    | 46        | 1.83%   |
| SDRAM   | 37        | 1.47%   |
| LPDDR5  | 23        | 0.92%   |
| DDR     | 10        | 0.4%    |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1444      | 57.21%  |
| DIMM         | 851       | 33.72%  |
| Row Of Chips | 201       | 7.96%   |
| Chip         | 14        | 0.55%   |
| Unknown      | 9         | 0.36%   |
| FB-DIMM      | 3         | 0.12%   |
| RIMM         | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1204      | 43.81%  |
| 4096  | 667       | 24.27%  |
| 16384 | 521       | 18.96%  |
| 2048  | 222       | 8.08%   |
| 32768 | 101       | 3.68%   |
| 1024  | 29        | 1.06%   |
| 12288 | 1         | 0.04%   |
| 512   | 1         | 0.04%   |
| 256   | 1         | 0.04%   |
| 128   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 487       | 17.88%  |
| 3200    | 474       | 17.41%  |
| 1600    | 463       | 17%     |
| 2400    | 241       | 8.85%   |
| 1333    | 159       | 5.84%   |
| 2133    | 134       | 4.92%   |
| 3600    | 91        | 3.34%   |
| 1334    | 60        | 2.2%    |
| 4267    | 47        | 1.73%   |
| 1867    | 41        | 1.51%   |
| 4800    | 34        | 1.25%   |
| 800     | 34        | 1.25%   |
| 3266    | 30        | 1.1%    |
| 667     | 29        | 1.07%   |
| 6400    | 25        | 0.92%   |
| 3000    | 23        | 0.84%   |
| 2666    | 23        | 0.84%   |
| Unknown | 22        | 0.81%   |
| 3800    | 21        | 0.77%   |
| 3400    | 21        | 0.77%   |
| 2933    | 20        | 0.73%   |
| 3733    | 19        | 0.7%    |
| 1067    | 16        | 0.59%   |
| 1066    | 16        | 0.59%   |
| 8400    | 14        | 0.51%   |
| 1866    | 13        | 0.48%   |
| 3866    | 12        | 0.44%   |
| 1800    | 11        | 0.4%    |
| 4199    | 10        | 0.37%   |
| 2800    | 10        | 0.37%   |
| 400     | 9         | 0.33%   |
| 4266    | 8         | 0.29%   |
| 3666    | 8         | 0.29%   |
| 3533    | 8         | 0.29%   |
| 3333    | 7         | 0.26%   |
| 3066    | 7         | 0.26%   |
| 3466    | 6         | 0.22%   |
| 3151    | 5         | 0.18%   |
| 2048    | 5         | 0.18%   |
| 2000    | 5         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 48        | 38.71%  |
| Brother Industries     | 28        | 22.58%  |
| Seiko Epson            | 13        | 10.48%  |
| Samsung Electronics    | 11        | 8.87%   |
| Canon                  | 9         | 7.26%   |
| Xerox                  | 2         | 1.61%   |
| Prolific Technology    | 2         | 1.61%   |
| Dymo-CoStar            | 2         | 1.61%   |
| Zebra                  | 1         | 0.81%   |
| QinHeng Electronics    | 1         | 0.81%   |
| Pantum                 | 1         | 0.81%   |
| Panasonic (Matsushita) | 1         | 0.81%   |
| Kyocera                | 1         | 0.81%   |
| ICS Advent             | 1         | 0.81%   |
| Datamax-O'Neil         | 1         | 0.81%   |
| BESTEASY               | 1         | 0.81%   |
| Apple                  | 1         | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.38%   |
| Seiko Epson L360 Series                                | 2         | 1.59%   |
| Seiko Epson L3110 Series                               | 2         | 1.59%   |
| Samsung M2070 Series                                   | 2         | 1.59%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.59%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.59%   |
| HP LaserJet P2015 series                               | 2         | 1.59%   |
| HP LaserJet 1020                                       | 2         | 1.59%   |
| HP LaserJet 1018                                       | 2         | 1.59%   |
| HP ENVY 4500 series                                    | 2         | 1.59%   |
| HP DeskJet 2700 series                                 | 2         | 1.59%   |
| HP DeskJet 2620 All-in-One Printer                     | 2         | 1.59%   |
| Brother MFC-J460DW                                     | 2         | 1.59%   |
| Brother HL-L2320D series                               | 2         | 1.59%   |
| Brother HL-2230 series                                 | 2         | 1.59%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.79%   |
| Xerox Phaser 6500DN                                    | 1         | 0.79%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.79%   |
| Seiko Epson XP-7100 Series                             | 1         | 0.79%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.79%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.79%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.79%   |
| Seiko Epson Printer                                    | 1         | 0.79%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.79%   |
| Seiko Epson L120 Series                                | 1         | 0.79%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.79%   |
| Seiko Epson ET-2700 Series                             | 1         | 0.79%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.79%   |
| Samsung SCX-3200 Series                                | 1         | 0.79%   |
| Samsung ML-2250 Series                                 | 1         | 0.79%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.79%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.79%   |
| Samsung M2020 Series                                   | 1         | 0.79%   |
| Samsung CLX-3180 Series                                | 1         | 0.79%   |
| Samsung CLX-3170 Series                                | 1         | 0.79%   |
| Samsung CLP-360 Series                                 | 1         | 0.79%   |
| QinHeng CH340S                                         | 1         | 0.79%   |
| Pantum P2200 series                                    | 1         | 0.79%   |
| Panasonic (Matsushita) KX-MB1500RU                     | 1         | 0.79%   |
| Kyocera Mita FS-820                                    | 1         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 14        | 51.85%  |
| Seiko Epson     | 7         | 25.93%  |
| Mustek Systems  | 3         | 11.11%  |
| Hewlett-Packard | 3         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20                      | 3         | 11.11%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 7.41%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 7.41%   |
| Canon CanoScan LiDE 220                                 | 2         | 7.41%   |
| Canon CanoScan LiDE 210                                 | 2         | 7.41%   |
| Canon CanoScan LiDE 110                                 | 2         | 7.41%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.7%    |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.7%    |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.7%    |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.7%    |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.7%    |
| HP ScanJet G4010                                        | 1         | 3.7%    |
| HP ScanJet 82x0C                                        | 1         | 3.7%    |
| HP ScanJet 3770                                         | 1         | 3.7%    |
| Canon CanoScan LiDE 60                                  | 1         | 3.7%    |
| Canon CanoScan LIDE 25                                  | 1         | 3.7%    |
| Canon CanoScan LiDE 120                                 | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 488       | 18.56%  |
| IMC Networks                           | 265       | 10.08%  |
| Microdia                               | 238       | 9.05%   |
| Realtek Semiconductor                  | 200       | 7.6%    |
| Logitech                               | 199       | 7.57%   |
| Quanta                                 | 145       | 5.51%   |
| Sunplus Innovation Technology          | 136       | 5.17%   |
| Bison Electronics                      | 123       | 4.68%   |
| Cheng Uei Precision Industry (Foxlink) | 104       | 3.95%   |
| Acer                                   | 96        | 3.65%   |
| Syntek                                 | 57        | 2.17%   |
| Apple                                  | 51        | 1.94%   |
| Suyin                                  | 48        | 1.83%   |
| Silicon Motion                         | 44        | 1.67%   |
| Lite-On Technology                     | 42        | 1.6%    |
| Luxvisions Innotech Limited            | 40        | 1.52%   |
| Microsoft                              | 34        | 1.29%   |
| Samsung Electronics                    | 30        | 1.14%   |
| Alcor Micro                            | 30        | 1.14%   |
| Generalplus Technology                 | 18        | 0.68%   |
| Ricoh                                  | 16        | 0.61%   |
| Sonix Technology                       | 14        | 0.53%   |
| Lenovo                                 | 14        | 0.53%   |
| Z-Star Microelectronics                | 13        | 0.49%   |
| SunplusIT                              | 9         | 0.34%   |
| KYE Systems (Mouse Systems)            | 9         | 0.34%   |
| ARC International                      | 9         | 0.34%   |
| Genesys Logic                          | 8         | 0.3%    |
| Y Media                                | 7         | 0.27%   |
| Huawei Technologies                    | 7         | 0.27%   |
| Sunplus Technology                     | 6         | 0.23%   |
| MacroSilicon                           | 6         | 0.23%   |
| GEMBIRD                                | 6         | 0.23%   |
| Cubeternet                             | 6         | 0.23%   |
| LG Electronics                         | 5         | 0.19%   |
| Importek                               | 5         | 0.19%   |
| icSpring                               | 5         | 0.19%   |
| Creative Technology                    | 5         | 0.19%   |
| Razer USA                              | 4         | 0.15%   |
| Primax Electronics                     | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 115       | 4.33%   |
| Microdia Integrated_Webcam_HD                                              | 102       | 3.84%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 82        | 3.09%   |
| Realtek Integrated_Webcam_HD                                               | 81        | 3.05%   |
| IMC Networks Integrated Camera                                             | 80        | 3.01%   |
| Sunplus Integrated_Webcam_HD                                               | 57        | 2.14%   |
| Chicony HD WebCam                                                          | 50        | 1.88%   |
| Logitech HD Pro Webcam C920                                                | 43        | 1.62%   |
| Syntek Integrated Camera                                                   | 40        | 1.5%    |
| Logitech Webcam C270                                                       | 40        | 1.5%    |
| Bison Integrated Camera                                                    | 37        | 1.39%   |
| Acer Integrated Camera                                                     | 36        | 1.35%   |
| Chicony HP HD Camera                                                       | 32        | 1.2%    |
| Chicony USB2.0 Camera                                                      | 31        | 1.17%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 29        | 1.09%   |
| Quanta HD User Facing                                                      | 29        | 1.09%   |
| Chicony HD User Facing                                                     | 26        | 0.98%   |
| Microdia Integrated Webcam                                                 | 22        | 0.83%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 0.75%   |
| Microdia Webcam Vitade AF                                                  | 20        | 0.75%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.75%   |
| Chicony Integrated Camera (1280x720@30)                                    | 19        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 19        | 0.71%   |
| Quanta HP HD Camera                                                        | 18        | 0.68%   |
| Acer BisonCam,NB Pro                                                       | 18        | 0.68%   |
| Realtek USB Camera                                                         | 17        | 0.64%   |
| Lite-On Integrated Camera                                                  | 17        | 0.64%   |
| IMC Networks HD Camera                                                     | 17        | 0.64%   |
| Bison HD Webcam                                                            | 17        | 0.64%   |
| Chicony HP TrueVision HD                                                   | 16        | 0.6%    |
| Bison Lenovo EasyCamera                                                    | 16        | 0.6%    |
| Quanta HD Webcam                                                           | 15        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 15        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 15        | 0.56%   |
| Alcor Micro USB 2.0 Camera                                                 | 15        | 0.56%   |
| Realtek Integrated Webcam                                                  | 14        | 0.53%   |
| Microsoft LifeCam HD-3000                                                  | 14        | 0.53%   |
| Microdia Integrated_Webcam_FHD                                             | 14        | 0.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 14        | 0.53%   |
| Sunplus HD WebCam                                                          | 13        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 178       | 33.09%  |
| Validity Sensors                   | 138       | 25.65%  |
| Shenzhen Goodix Technology         | 108       | 20.07%  |
| Elan Microelectronics              | 38        | 7.06%   |
| AuthenTec                          | 22        | 4.09%   |
| Upek                               | 21        | 3.9%    |
| LighTuning Technology              | 21        | 3.9%    |
| STMicroelectronics                 | 6         | 1.12%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.56%   |
| Focal-systems.Corp                 | 2         | 0.37%   |
| DigitalPersona                     | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 61        | 11.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 55        | 10.22%  |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 5.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 4.28%   |
| Synaptics UWP WBDI                                                         | 23        | 4.28%   |
| Elan ELAN:Fingerprint                                                      | 22        | 4.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 3.9%    |
| Shenzhen Goodix FingerPrint                                                | 17        | 3.16%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 2.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 2.6%    |
| Elan ELAN:ARM-M4                                                           | 14        | 2.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.42%   |
| Synaptics WBDI                                                             | 13        | 2.42%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 2.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.04%   |
| Synaptics  WBDI                                                            | 11        | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.86%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 1.49%   |
| AuthenTec AES2810                                                          | 8         | 1.49%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.3%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.3%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.12%   |
| Validity Sensors VFS491                                                    | 6         | 1.12%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.12%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.93%   |
| Unknown                                                                    | 5         | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.74%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.56%   |
| Synaptics WBDI Device                                                      | 2         | 0.37%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 94        | 41.05%  |
| Alcor Micro               | 67        | 29.26%  |
| Upek                      | 14        | 6.11%   |
| O2 Micro                  | 9         | 3.93%   |
| Lenovo                    | 8         | 3.49%   |
| Advanced Card Systems     | 6         | 2.62%   |
| SCM Microsystems          | 4         | 1.75%   |
| Yubico.com                | 3         | 1.31%   |
| OmniKey                   | 3         | 1.31%   |
| Gemalto (was Gemplus)     | 3         | 1.31%   |
| Reiner SCT Kartensysteme  | 2         | 0.87%   |
| Realtek Semiconductor     | 2         | 0.87%   |
| Fujitsu Siemens Computers | 2         | 0.87%   |
| Clay Logic                | 2         | 0.87%   |
| BIT4ID                    | 2         | 0.87%   |
| Aladdin R.D.              | 2         | 0.87%   |
| Watchdata                 | 1         | 0.44%   |
| In Focus Systems          | 1         | 0.44%   |
| Giesecke & Devrient       | 1         | 0.44%   |
| Chicony Electronics       | 1         | 0.44%   |
| Aladdin Knowledge Systems | 1         | 0.44%   |
| Aktiv                     | 1         | 0.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 65        | 28.38%  |
| Broadcom 5880                                                                | 27        | 11.79%  |
| Broadcom 58200                                                               | 26        | 11.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 24        | 10.48%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 6.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 6.11%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 3.93%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.49%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.75%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.31%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.31%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.87%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.87%   |
| OmniKey CardMan 1021                                                         | 2         | 0.87%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.87%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.87%   |
| BIT4ID miniLector EVO                                                        | 2         | 0.87%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.87%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.87%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.87%   |
| Watchdata USB Key                                                            | 1         | 0.44%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.44%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.44%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.44%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.44%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.44%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.44%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.44%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.44%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.44%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.44%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.44%   |
| Aktiv Rutoken lite                                                           | 1         | 0.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2741      | 68.3%   |
| 1     | 1026      | 25.57%  |
| 2     | 205       | 5.11%   |
| 3     | 21        | 0.52%   |
| 4     | 9         | 0.22%   |
| 6     | 4         | 0.1%    |
| 7     | 3         | 0.07%   |
| 5     | 3         | 0.07%   |
| 9     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 529       | 34.64%  |
| Graphics card            | 256       | 16.76%  |
| Chipcard                 | 197       | 12.9%   |
| Net/wireless             | 180       | 11.79%  |
| Camera                   | 74        | 4.85%   |
| Multimedia controller    | 63        | 4.13%   |
| Sound                    | 42        | 2.75%   |
| Bluetooth                | 41        | 2.69%   |
| Communication controller | 36        | 2.36%   |
| Unassigned class         | 34        | 2.23%   |
| Card reader              | 22        | 1.44%   |
| Storage                  | 17        | 1.11%   |
| Net/ethernet             | 10        | 0.65%   |
| Network                  | 8         | 0.52%   |
| Modem                    | 6         | 0.39%   |
| Storage/ide              | 5         | 0.33%   |
| Firewire controller      | 4         | 0.26%   |
| Dvb card                 | 3         | 0.2%    |

