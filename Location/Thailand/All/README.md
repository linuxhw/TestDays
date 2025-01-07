Linux in Thailand - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Thailand/Desktop/README.md) and [notebooks](/Location/Thailand/Notebook/README.md).

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

Total: 1021

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [adec02cbc1](https://linux-hardware.org/?probe=adec02cbc1) | Jan 04, 2025 |
| Acer          | Nitro AN515-51              | Notebook    | [3555e1e029](https://linux-hardware.org/?probe=3555e1e029) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [3865b761f5](https://linux-hardware.org/?probe=3865b761f5) | Dec 30, 2024 |
| Dell          | Latitude E7270              | Notebook    | [5e521085a0](https://linux-hardware.org/?probe=5e521085a0) | Dec 29, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [5320a7c488](https://linux-hardware.org/?probe=5320a7c488) | Dec 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [e26f1dfa00](https://linux-hardware.org/?probe=e26f1dfa00) | Dec 26, 2024 |
| MiTAC         | PD10EHI                     | Desktop     | [0879837e1b](https://linux-hardware.org/?probe=0879837e1b) | Dec 24, 2024 |
| HP            | ENVY m6                     | Notebook    | [e732571527](https://linux-hardware.org/?probe=e732571527) | Dec 18, 2024 |
| HP            | ENVY m6                     | Notebook    | [4060abf5de](https://linux-hardware.org/?probe=4060abf5de) | Dec 18, 2024 |
| MiTAC         | PD10EHI                     | Desktop     | [677c9d3ee3](https://linux-hardware.org/?probe=677c9d3ee3) | Dec 18, 2024 |
| Acer          | Nitro AN515-51              | Notebook    | [3bf6da80b5](https://linux-hardware.org/?probe=3bf6da80b5) | Dec 17, 2024 |
| Intel         | X99                         | Desktop     | [1a147ad6e0](https://linux-hardware.org/?probe=1a147ad6e0) | Dec 16, 2024 |
| Fujitsu       | FMVU09001                   | Notebook    | [2be0996b78](https://linux-hardware.org/?probe=2be0996b78) | Dec 16, 2024 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [4a41974e06](https://linux-hardware.org/?probe=4a41974e06) | Dec 14, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7aebeb376d](https://linux-hardware.org/?probe=7aebeb376d) | Dec 14, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [5a9ee5fc61](https://linux-hardware.org/?probe=5a9ee5fc61) | Dec 12, 2024 |
| ASUSTek       | K53SD                       | Notebook    | [b5122b5304](https://linux-hardware.org/?probe=b5122b5304) | Dec 11, 2024 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [94bf662079](https://linux-hardware.org/?probe=94bf662079) | Dec 11, 2024 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [dbee87ee50](https://linux-hardware.org/?probe=dbee87ee50) | Dec 10, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [727d64bac6](https://linux-hardware.org/?probe=727d64bac6) | Dec 07, 2024 |
| ASRock        | A520M-HVS                   | Desktop     | [13eb428010](https://linux-hardware.org/?probe=13eb428010) | Dec 01, 2024 |
| Toshiba       | Satellite M840              | Notebook    | [63307beb47](https://linux-hardware.org/?probe=63307beb47) | Dec 01, 2024 |
| Acer          | TravelMate 8372             | Notebook    | [fb1751719f](https://linux-hardware.org/?probe=fb1751719f) | Nov 30, 2024 |
| MicroByte     | ezbook                      | Notebook    | [167d9d082a](https://linux-hardware.org/?probe=167d9d082a) | Nov 28, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [74716c6624](https://linux-hardware.org/?probe=74716c6624) | Nov 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e26ba621b4](https://linux-hardware.org/?probe=e26ba621b4) | Nov 22, 2024 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [280d94072f](https://linux-hardware.org/?probe=280d94072f) | Nov 21, 2024 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [00e3211d51](https://linux-hardware.org/?probe=00e3211d51) | Nov 21, 2024 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [cfd782d9d8](https://linux-hardware.org/?probe=cfd782d9d8) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [38a3d9518c](https://linux-hardware.org/?probe=38a3d9518c) | Nov 21, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A2FXTH    | Notebook    | [8609525ceb](https://linux-hardware.org/?probe=8609525ceb) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [f5867243e1](https://linux-hardware.org/?probe=f5867243e1) | Nov 17, 2024 |
| Lenovo        | ThinkPad X260 20F5S80000    | Notebook    | [9985d70e53](https://linux-hardware.org/?probe=9985d70e53) | Nov 17, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [850969e625](https://linux-hardware.org/?probe=850969e625) | Nov 14, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [6f60e0749d](https://linux-hardware.org/?probe=6f60e0749d) | Nov 12, 2024 |
| MSI           | B365M PRO-VDH               | Desktop     | [82d0c85a4c](https://linux-hardware.org/?probe=82d0c85a4c) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [684a2baf0f](https://linux-hardware.org/?probe=684a2baf0f) | Nov 11, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [4654b5620b](https://linux-hardware.org/?probe=4654b5620b) | Nov 11, 2024 |
| MiTAC         | PD10EHI                     | Desktop     | [378a9691e4](https://linux-hardware.org/?probe=378a9691e4) | Nov 09, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [026f2ca004](https://linux-hardware.org/?probe=026f2ca004) | Nov 07, 2024 |
| Lenovo        | 31900059 STD                | Desktop     | [eb4e9fd174](https://linux-hardware.org/?probe=eb4e9fd174) | Oct 31, 2024 |
| Dell          | 0CRWCR A01                  | All in one  | [e755d7e7ce](https://linux-hardware.org/?probe=e755d7e7ce) | Oct 31, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [566d913cf0](https://linux-hardware.org/?probe=566d913cf0) | Oct 31, 2024 |
| IBM           | 4852E66 4852E66             | All in one  | [cbb7da4932](https://linux-hardware.org/?probe=cbb7da4932) | Oct 27, 2024 |
| Acer          | Swift SF514-55TA            | Notebook    | [71713d1366](https://linux-hardware.org/?probe=71713d1366) | Oct 26, 2024 |
| ASRock        | X570 Pro4                   | Desktop     | [aeb453702e](https://linux-hardware.org/?probe=aeb453702e) | Oct 25, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [96ae96801f](https://linux-hardware.org/?probe=96ae96801f) | Oct 24, 2024 |
| HP            | 1497                        | Desktop     | [f60b700334](https://linux-hardware.org/?probe=f60b700334) | Oct 21, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [e15a88b4e1](https://linux-hardware.org/?probe=e15a88b4e1) | Oct 19, 2024 |
| ASRock        | B550 Steel Legend           | Desktop     | [c4ffd7734d](https://linux-hardware.org/?probe=c4ffd7734d) | Oct 19, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3113b0c26d](https://linux-hardware.org/?probe=3113b0c26d) | Oct 17, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [627376d603](https://linux-hardware.org/?probe=627376d603) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [168fc0f98f](https://linux-hardware.org/?probe=168fc0f98f) | Oct 16, 2024 |
| Dell          | 0C3YXR A01                  | Desktop     | [702872562a](https://linux-hardware.org/?probe=702872562a) | Oct 15, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [1a67aa42ba](https://linux-hardware.org/?probe=1a67aa42ba) | Oct 14, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [4e25e3a952](https://linux-hardware.org/?probe=4e25e3a952) | Oct 12, 2024 |
| HP            | 802F                        | Desktop     | [2678cdc4b4](https://linux-hardware.org/?probe=2678cdc4b4) | Oct 10, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [9e148491d9](https://linux-hardware.org/?probe=9e148491d9) | Oct 08, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8834968175](https://linux-hardware.org/?probe=8834968175) | Oct 08, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [94d19939d7](https://linux-hardware.org/?probe=94d19939d7) | Oct 08, 2024 |
| Acer          | IAXBT-BL                    | All in one  | [59fb4c7892](https://linux-hardware.org/?probe=59fb4c7892) | Oct 04, 2024 |
| MiTAC         | PD10EHI                     | Desktop     | [d3d62dd202](https://linux-hardware.org/?probe=d3d62dd202) | Oct 03, 2024 |
| Acer          | Aspire E5-553G              | Notebook    | [d98fc4f350](https://linux-hardware.org/?probe=d98fc4f350) | Oct 03, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [da3e7efc69](https://linux-hardware.org/?probe=da3e7efc69) | Oct 01, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | Notebook    | [e44bc0da2c](https://linux-hardware.org/?probe=e44bc0da2c) | Oct 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cc1e30dfc8](https://linux-hardware.org/?probe=cc1e30dfc8) | Sep 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [42eb3e876f](https://linux-hardware.org/?probe=42eb3e876f) | Sep 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c14174367](https://linux-hardware.org/?probe=4c14174367) | Sep 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b5dd25d1cb](https://linux-hardware.org/?probe=b5dd25d1cb) | Sep 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [39d4e1989e](https://linux-hardware.org/?probe=39d4e1989e) | Sep 27, 2024 |
| AIC           | LYNX 01                     | Server      | [409cde8b44](https://linux-hardware.org/?probe=409cde8b44) | Sep 24, 2024 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [1a476e389a](https://linux-hardware.org/?probe=1a476e389a) | Sep 23, 2024 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [95ff9e205d](https://linux-hardware.org/?probe=95ff9e205d) | Sep 22, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [2cd69a8fee](https://linux-hardware.org/?probe=2cd69a8fee) | Sep 21, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [2f3706f0c5](https://linux-hardware.org/?probe=2f3706f0c5) | Sep 21, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [afa733200b](https://linux-hardware.org/?probe=afa733200b) | Sep 21, 2024 |
| HP            | 802F                        | Desktop     | [8f5648baef](https://linux-hardware.org/?probe=8f5648baef) | Sep 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [cfa989ddee](https://linux-hardware.org/?probe=cfa989ddee) | Sep 20, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [068811de2e](https://linux-hardware.org/?probe=068811de2e) | Sep 19, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0ce2994685](https://linux-hardware.org/?probe=0ce2994685) | Sep 16, 2024 |
| HP            | 8298                        | Desktop     | [33696766f2](https://linux-hardware.org/?probe=33696766f2) | Sep 15, 2024 |
| Fujitsu       | FARQ06006                   | Notebook    | [c52b3facb2](https://linux-hardware.org/?probe=c52b3facb2) | Sep 14, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [c6d88ef79f](https://linux-hardware.org/?probe=c6d88ef79f) | Sep 13, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [2f3b657d09](https://linux-hardware.org/?probe=2f3b657d09) | Sep 09, 2024 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [727745c91c](https://linux-hardware.org/?probe=727745c91c) | Sep 09, 2024 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [64da4e01a4](https://linux-hardware.org/?probe=64da4e01a4) | Sep 07, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [9214328551](https://linux-hardware.org/?probe=9214328551) | Sep 05, 2024 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [5d923690c3](https://linux-hardware.org/?probe=5d923690c3) | Sep 04, 2024 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b7fe8367ba](https://linux-hardware.org/?probe=b7fe8367ba) | Sep 04, 2024 |
| Fujitsu       | FMVU09001                   | Notebook    | [ca8d3f84d7](https://linux-hardware.org/?probe=ca8d3f84d7) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [21f8d3a8bd](https://linux-hardware.org/?probe=21f8d3a8bd) | Sep 02, 2024 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [ecabfa5d24](https://linux-hardware.org/?probe=ecabfa5d24) | Sep 01, 2024 |
| JINGSHA       | B85M-I                      | Desktop     | [0ec5002083](https://linux-hardware.org/?probe=0ec5002083) | Aug 31, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [ac446ca7d3](https://linux-hardware.org/?probe=ac446ca7d3) | Aug 31, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [1a3c5dec3d](https://linux-hardware.org/?probe=1a3c5dec3d) | Aug 30, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [7380931289](https://linux-hardware.org/?probe=7380931289) | Aug 24, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [02aa95e332](https://linux-hardware.org/?probe=02aa95e332) | Aug 23, 2024 |
| Lenovo        | ThinkPad T420 4236NUT       | Notebook    | [4581717488](https://linux-hardware.org/?probe=4581717488) | Aug 22, 2024 |
| Lenovo        | ThinkPad T420 4236NUT       | Notebook    | [83a280dff5](https://linux-hardware.org/?probe=83a280dff5) | Aug 22, 2024 |
| JINGSHA       | B85M-I                      | Desktop     | [d7094aabed](https://linux-hardware.org/?probe=d7094aabed) | Aug 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [8a2fda7948](https://linux-hardware.org/?probe=8a2fda7948) | Aug 18, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [79d367ec57](https://linux-hardware.org/?probe=79d367ec57) | Aug 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [d3b1fb1bb3](https://linux-hardware.org/?probe=d3b1fb1bb3) | Aug 14, 2024 |
| Hardkernel    | ODROID XU4                  | Soc         | [eec93a2806](https://linux-hardware.org/?probe=eec93a2806) | Aug 12, 2024 |
| ASUSTek       | N43SL                       | Notebook    | [3e0b4fda49](https://linux-hardware.org/?probe=3e0b4fda49) | Aug 09, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [90f8587ff4](https://linux-hardware.org/?probe=90f8587ff4) | Aug 09, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [81cf5de97d](https://linux-hardware.org/?probe=81cf5de97d) | Aug 08, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [b56672c1f5](https://linux-hardware.org/?probe=b56672c1f5) | Aug 07, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [1ffb6a19c0](https://linux-hardware.org/?probe=1ffb6a19c0) | Aug 05, 2024 |
| Lenovo        | 315F NO DPK                 | Desktop     | [f2ab02a574](https://linux-hardware.org/?probe=f2ab02a574) | Aug 04, 2024 |
| Lenovo        | 315F NO DPK                 | Desktop     | [f5da233c67](https://linux-hardware.org/?probe=f5da233c67) | Aug 04, 2024 |
| MSI           | Z270 GAMING M5              | Desktop     | [c094b9de0f](https://linux-hardware.org/?probe=c094b9de0f) | Aug 02, 2024 |
| Intel         | X99-P4 V5.1                 | Desktop     | [def260ec4e](https://linux-hardware.org/?probe=def260ec4e) | Jul 28, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [723eb360ba](https://linux-hardware.org/?probe=723eb360ba) | Jul 27, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | Notebook    | [40e0d919ba](https://linux-hardware.org/?probe=40e0d919ba) | Jul 25, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [31381d6558](https://linux-hardware.org/?probe=31381d6558) | Jul 22, 2024 |
| Dell          | 0T7D40 A00                  | Desktop     | [bea004e3ba](https://linux-hardware.org/?probe=bea004e3ba) | Jul 20, 2024 |
| Chuwi         | FreeBook                    | Notebook    | [c0a077d454](https://linux-hardware.org/?probe=c0a077d454) | Jul 19, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [d8feb4c87f](https://linux-hardware.org/?probe=d8feb4c87f) | Jul 18, 2024 |
| Google        | Nami                        | Notebook    | [c8a8ef90f9](https://linux-hardware.org/?probe=c8a8ef90f9) | Jul 17, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | Desktop     | [77d830aa2e](https://linux-hardware.org/?probe=77d830aa2e) | Jul 12, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [73ede5365f](https://linux-hardware.org/?probe=73ede5365f) | Jul 12, 2024 |
| HP            | 802F                        | Desktop     | [287eec5051](https://linux-hardware.org/?probe=287eec5051) | Jul 08, 2024 |
| HP            | 82DD 0010                   | All in one  | [b0bf9decaa](https://linux-hardware.org/?probe=b0bf9decaa) | Jul 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [e72b46be95](https://linux-hardware.org/?probe=e72b46be95) | Jul 08, 2024 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [5cef5a4211](https://linux-hardware.org/?probe=5cef5a4211) | Jul 07, 2024 |
| Shenzhen M... | DRFXI                       | Desktop     | [d5d17b7674](https://linux-hardware.org/?probe=d5d17b7674) | Jul 03, 2024 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [6ef4464c82](https://linux-hardware.org/?probe=6ef4464c82) | Jul 03, 2024 |
| Acer          | Veriton N4640G              | Desktop     | [316499457a](https://linux-hardware.org/?probe=316499457a) | Jul 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [20f4910501](https://linux-hardware.org/?probe=20f4910501) | Jul 01, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [f00a1ad952](https://linux-hardware.org/?probe=f00a1ad952) | Jun 28, 2024 |
| Gigabyte      | G5 GE                       | Notebook    | [9085f25eed](https://linux-hardware.org/?probe=9085f25eed) | Jun 27, 2024 |
| Dell          | Precision 7520              | Notebook    | [14c00c9b20](https://linux-hardware.org/?probe=14c00c9b20) | Jun 21, 2024 |
| Fujitsu       | FARQ06006                   | Notebook    | [897e538222](https://linux-hardware.org/?probe=897e538222) | Jun 20, 2024 |
| Fujitsu       | FARQ06006                   | Notebook    | [84f8c73a60](https://linux-hardware.org/?probe=84f8c73a60) | Jun 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [ede7202c2c](https://linux-hardware.org/?probe=ede7202c2c) | Jun 19, 2024 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [25b2cd256f](https://linux-hardware.org/?probe=25b2cd256f) | Jun 17, 2024 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [f95edc487c](https://linux-hardware.org/?probe=f95edc487c) | Jun 16, 2024 |
| Acer          | Aspire 7730G                | Notebook    | [eef984b21a](https://linux-hardware.org/?probe=eef984b21a) | Jun 13, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [8f801983ae](https://linux-hardware.org/?probe=8f801983ae) | Jun 13, 2024 |
| Acer          | Aspire 7730G                | Notebook    | [9654289a93](https://linux-hardware.org/?probe=9654289a93) | Jun 10, 2024 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [63bb05f431](https://linux-hardware.org/?probe=63bb05f431) | Jun 07, 2024 |
| Dell          | Vostro 5391                 | Notebook    | [4a3e155011](https://linux-hardware.org/?probe=4a3e155011) | Jun 07, 2024 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [5870ebece8](https://linux-hardware.org/?probe=5870ebece8) | Jun 05, 2024 |
| ASUSTek       | K56CB                       | Notebook    | [3d1e7093df](https://linux-hardware.org/?probe=3d1e7093df) | May 31, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [23b5315d04](https://linux-hardware.org/?probe=23b5315d04) | May 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a9f80409ae](https://linux-hardware.org/?probe=a9f80409ae) | May 22, 2024 |
| Timi          | RedmiBook 15                | Notebook    | [f86f533af7](https://linux-hardware.org/?probe=f86f533af7) | May 19, 2024 |
| AMI           | Intel                       | Desktop     | [aefdd71c5e](https://linux-hardware.org/?probe=aefdd71c5e) | May 18, 2024 |
| HP            | 1998                        | Desktop     | [7d652e5edc](https://linux-hardware.org/?probe=7d652e5edc) | May 13, 2024 |
| Fujitsu       | FMVNA6GE                    | Notebook    | [8345368849](https://linux-hardware.org/?probe=8345368849) | May 13, 2024 |
| Fujitsu       | FMVNA6GE                    | Notebook    | [00946ec874](https://linux-hardware.org/?probe=00946ec874) | May 13, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [92d8a990de](https://linux-hardware.org/?probe=92d8a990de) | Apr 29, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [88d63b7ebb](https://linux-hardware.org/?probe=88d63b7ebb) | Apr 29, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [0d725519b9](https://linux-hardware.org/?probe=0d725519b9) | Apr 29, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [37c91e715a](https://linux-hardware.org/?probe=37c91e715a) | Apr 22, 2024 |
| Acer          | Aspire 4736 V1.04           | Other       | [e514221b1f](https://linux-hardware.org/?probe=e514221b1f) | Apr 22, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [6636df5576](https://linux-hardware.org/?probe=6636df5576) | Apr 20, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [eae63cf682](https://linux-hardware.org/?probe=eae63cf682) | Apr 15, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [c468075794](https://linux-hardware.org/?probe=c468075794) | Apr 11, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [1b09cf1322](https://linux-hardware.org/?probe=1b09cf1322) | Apr 10, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [46ec5edae0](https://linux-hardware.org/?probe=46ec5edae0) | Apr 10, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [071a57efd2](https://linux-hardware.org/?probe=071a57efd2) | Apr 07, 2024 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8d0c1e98f2](https://linux-hardware.org/?probe=8d0c1e98f2) | Apr 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [21ef6a026f](https://linux-hardware.org/?probe=21ef6a026f) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [d55fe0350b](https://linux-hardware.org/?probe=d55fe0350b) | Mar 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a9cd8ee448](https://linux-hardware.org/?probe=a9cd8ee448) | Mar 22, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | Desktop     | [11963d204b](https://linux-hardware.org/?probe=11963d204b) | Mar 21, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | Desktop     | [908360069c](https://linux-hardware.org/?probe=908360069c) | Mar 21, 2024 |
| HP            | 82A5                        | Mini pc     | [3186019a11](https://linux-hardware.org/?probe=3186019a11) | Mar 13, 2024 |
| Gigabyte      | H81M-DS2                    | Desktop     | [dde5a90821](https://linux-hardware.org/?probe=dde5a90821) | Mar 12, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [3890a0c9b5](https://linux-hardware.org/?probe=3890a0c9b5) | Mar 09, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [6570fe8279](https://linux-hardware.org/?probe=6570fe8279) | Mar 07, 2024 |
| ASUSTek       | F80Q                        | Notebook    | [613ffc9f22](https://linux-hardware.org/?probe=613ffc9f22) | Mar 05, 2024 |
| HP            | 82A5                        | Mini pc     | [82b95125a4](https://linux-hardware.org/?probe=82b95125a4) | Mar 04, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [68d8ddbe50](https://linux-hardware.org/?probe=68d8ddbe50) | Mar 04, 2024 |
| Fujitsu       | FMVC05005                   | Notebook    | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| ASRock        | X299 Taichi                 | Desktop     | [5a5309bb52](https://linux-hardware.org/?probe=5a5309bb52) | Mar 03, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [a0684dfb38](https://linux-hardware.org/?probe=a0684dfb38) | Feb 25, 2024 |
| HP            | ProBook 430 G3              | Notebook    | [e718712840](https://linux-hardware.org/?probe=e718712840) | Feb 24, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [109256318a](https://linux-hardware.org/?probe=109256318a) | Feb 20, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [b05150cb04](https://linux-hardware.org/?probe=b05150cb04) | Feb 19, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [dae19ec723](https://linux-hardware.org/?probe=dae19ec723) | Feb 18, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [8c9f92e873](https://linux-hardware.org/?probe=8c9f92e873) | Feb 17, 2024 |
| Dell          | 08WKV3 A00                  | Desktop     | [5bff5d79c2](https://linux-hardware.org/?probe=5bff5d79c2) | Feb 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [edb077d9e9](https://linux-hardware.org/?probe=edb077d9e9) | Feb 15, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [0fbc4b07a6](https://linux-hardware.org/?probe=0fbc4b07a6) | Feb 12, 2024 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [c44d89b0dc](https://linux-hardware.org/?probe=c44d89b0dc) | Feb 11, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [de7b828cc8](https://linux-hardware.org/?probe=de7b828cc8) | Feb 10, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [c7ad65ef28](https://linux-hardware.org/?probe=c7ad65ef28) | Feb 10, 2024 |
| Dell          | 0VFD52 A00                  | Desktop     | [cc2714d2cf](https://linux-hardware.org/?probe=cc2714d2cf) | Feb 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d72d765d84](https://linux-hardware.org/?probe=d72d765d84) | Feb 06, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [0d44d5cc60](https://linux-hardware.org/?probe=0d44d5cc60) | Feb 06, 2024 |
| IBM           | 01GR489 0C                  | Server      | [8f78b06549](https://linux-hardware.org/?probe=8f78b06549) | Feb 06, 2024 |
| Nvidia        | Tegra                       | Soc         | [409382bec1](https://linux-hardware.org/?probe=409382bec1) | Feb 04, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [d6023b78a2](https://linux-hardware.org/?probe=d6023b78a2) | Feb 02, 2024 |
| MSI           | X99A SLI PLUS               | Desktop     | [216026fc45](https://linux-hardware.org/?probe=216026fc45) | Jan 30, 2024 |
| ASRock        | H470 Phantom Gaming 4       | Desktop     | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Fujitsu       | FARQ10003                   | Notebook    | [6084280fc9](https://linux-hardware.org/?probe=6084280fc9) | Jan 27, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [326dd5b81f](https://linux-hardware.org/?probe=326dd5b81f) | Jan 23, 2024 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [93137ffd8d](https://linux-hardware.org/?probe=93137ffd8d) | Jan 21, 2024 |
| Toshiba       | Satellite L640              | Notebook    | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| Gigabyte      | H310M DS2 x.x               | Desktop     | [dcbb993ea5](https://linux-hardware.org/?probe=dcbb993ea5) | Jan 18, 2024 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [6690260fd8](https://linux-hardware.org/?probe=6690260fd8) | Jan 18, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [4b39b1cbe0](https://linux-hardware.org/?probe=4b39b1cbe0) | Jan 17, 2024 |
| Dell          | Vostro 5471                 | Notebook    | [d3ef161a9e](https://linux-hardware.org/?probe=d3ef161a9e) | Jan 14, 2024 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [c617b55175](https://linux-hardware.org/?probe=c617b55175) | Jan 13, 2024 |
| Apple         | MacBookPro3,1               | Notebook    | [87d8854210](https://linux-hardware.org/?probe=87d8854210) | Jan 12, 2024 |
| Samsung       | 900X3L                      | Notebook    | [d77974be8d](https://linux-hardware.org/?probe=d77974be8d) | Jan 07, 2024 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [b811bdcbfd](https://linux-hardware.org/?probe=b811bdcbfd) | Jan 07, 2024 |
| HP            | ENVY m6                     | Notebook    | [d63a06fb89](https://linux-hardware.org/?probe=d63a06fb89) | Jan 04, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [cf4135541d](https://linux-hardware.org/?probe=cf4135541d) | Jan 03, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [b74d7acff4](https://linux-hardware.org/?probe=b74d7acff4) | Jan 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1b62649586](https://linux-hardware.org/?probe=1b62649586) | Jan 02, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [d01ee5a226](https://linux-hardware.org/?probe=d01ee5a226) | Jan 02, 2024 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [19be3bdc5b](https://linux-hardware.org/?probe=19be3bdc5b) | Dec 31, 2023 |
| HP            | 82B4                        | Desktop     | [02bcf6a9d1](https://linux-hardware.org/?probe=02bcf6a9d1) | Dec 31, 2023 |
| Acer          | SF314-71-50E8               | Notebook    | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| Gigabyte      | H310M DS2 x.x               | Desktop     | [47c95a8cc5](https://linux-hardware.org/?probe=47c95a8cc5) | Dec 26, 2023 |
| MicroByte     | ezbook                      | Notebook    | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| HP            | ENVY m6                     | Notebook    | [237331a1ba](https://linux-hardware.org/?probe=237331a1ba) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [3dee3cb4bf](https://linux-hardware.org/?probe=3dee3cb4bf) | Dec 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [a32cb7798b](https://linux-hardware.org/?probe=a32cb7798b) | Dec 19, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [7866cd7449](https://linux-hardware.org/?probe=7866cd7449) | Dec 16, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [83b004a254](https://linux-hardware.org/?probe=83b004a254) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [9227c29b16](https://linux-hardware.org/?probe=9227c29b16) | Dec 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [f561fb6a85](https://linux-hardware.org/?probe=f561fb6a85) | Dec 12, 2023 |
| Intel         | X99                         | Desktop     | [6988251bb1](https://linux-hardware.org/?probe=6988251bb1) | Dec 11, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b6d0160123](https://linux-hardware.org/?probe=b6d0160123) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ac764bedcc](https://linux-hardware.org/?probe=ac764bedcc) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [b5726693c1](https://linux-hardware.org/?probe=b5726693c1) | Dec 04, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [3cd6a2e9dc](https://linux-hardware.org/?probe=3cd6a2e9dc) | Dec 03, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [a0306c58e5](https://linux-hardware.org/?probe=a0306c58e5) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [a03bc4e394](https://linux-hardware.org/?probe=a03bc4e394) | Dec 03, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [40a0a394cc](https://linux-hardware.org/?probe=40a0a394cc) | Dec 01, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [fe332ae4ef](https://linux-hardware.org/?probe=fe332ae4ef) | Nov 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c1777b379](https://linux-hardware.org/?probe=8c1777b379) | Nov 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [284f7d2451](https://linux-hardware.org/?probe=284f7d2451) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [420d9baddf](https://linux-hardware.org/?probe=420d9baddf) | Nov 21, 2023 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [ae2a0fceac](https://linux-hardware.org/?probe=ae2a0fceac) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [ab7e55f5b9](https://linux-hardware.org/?probe=ab7e55f5b9) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e551d74658](https://linux-hardware.org/?probe=e551d74658) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [9d8548f39a](https://linux-hardware.org/?probe=9d8548f39a) | Nov 15, 2023 |
| Acer          | Aspire 4350                 | Notebook    | [32da8a19ac](https://linux-hardware.org/?probe=32da8a19ac) | Nov 13, 2023 |
| HP            | Pavilion 14                 | Notebook    | [344b8f4865](https://linux-hardware.org/?probe=344b8f4865) | Nov 13, 2023 |
| HP            | Pavilion 14                 | Notebook    | [e34aa57010](https://linux-hardware.org/?probe=e34aa57010) | Nov 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [36763f453f](https://linux-hardware.org/?probe=36763f453f) | Nov 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [661492882b](https://linux-hardware.org/?probe=661492882b) | Nov 13, 2023 |
| Google        | Panther                     | Desktop     | [bd2af6ba92](https://linux-hardware.org/?probe=bd2af6ba92) | Nov 13, 2023 |
| HP            | 802F                        | Desktop     | [e5d90a5987](https://linux-hardware.org/?probe=e5d90a5987) | Nov 09, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [701d46485b](https://linux-hardware.org/?probe=701d46485b) | Nov 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [048559335e](https://linux-hardware.org/?probe=048559335e) | Nov 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d17a8bc08a](https://linux-hardware.org/?probe=d17a8bc08a) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [313770aff1](https://linux-hardware.org/?probe=313770aff1) | Oct 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [057e350f82](https://linux-hardware.org/?probe=057e350f82) | Oct 27, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [3aa43f0bf7](https://linux-hardware.org/?probe=3aa43f0bf7) | Oct 26, 2023 |
| HP            | 802F                        | Desktop     | [d01e0550a3](https://linux-hardware.org/?probe=d01e0550a3) | Oct 20, 2023 |
| Lenovo        | ThinkPad T580 20L90024GE    | Notebook    | [5853b175c4](https://linux-hardware.org/?probe=5853b175c4) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d561271316](https://linux-hardware.org/?probe=d561271316) | Oct 19, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [dd8c738dc7](https://linux-hardware.org/?probe=dd8c738dc7) | Oct 18, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [45639896bd](https://linux-hardware.org/?probe=45639896bd) | Oct 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e44d1b7e3c](https://linux-hardware.org/?probe=e44d1b7e3c) | Oct 14, 2023 |
| AMI           | Intel                       | Desktop     | [888a4e1a0f](https://linux-hardware.org/?probe=888a4e1a0f) | Oct 13, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [4bb18fddab](https://linux-hardware.org/?probe=4bb18fddab) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [423d2de75a](https://linux-hardware.org/?probe=423d2de75a) | Oct 06, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [5d39adb330](https://linux-hardware.org/?probe=5d39adb330) | Oct 05, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [54c8de587a](https://linux-hardware.org/?probe=54c8de587a) | Oct 05, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [62740874ab](https://linux-hardware.org/?probe=62740874ab) | Sep 30, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [618cd9dd90](https://linux-hardware.org/?probe=618cd9dd90) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cce7c03059](https://linux-hardware.org/?probe=cce7c03059) | Sep 29, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [36905cc47d](https://linux-hardware.org/?probe=36905cc47d) | Sep 28, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [f46006f6ce](https://linux-hardware.org/?probe=f46006f6ce) | Sep 28, 2023 |
| MiTAC         | PD10EHI                     | Desktop     | [29716ecb18](https://linux-hardware.org/?probe=29716ecb18) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a7d0f8e075](https://linux-hardware.org/?probe=a7d0f8e075) | Sep 26, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [48fb2a7ee3](https://linux-hardware.org/?probe=48fb2a7ee3) | Sep 25, 2023 |
| Dell          | 0D4MD1 A04                  | Desktop     | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | Desktop     | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [2310ddb9a7](https://linux-hardware.org/?probe=2310ddb9a7) | Sep 21, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [bec0346d1d](https://linux-hardware.org/?probe=bec0346d1d) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [038434c6a8](https://linux-hardware.org/?probe=038434c6a8) | Sep 16, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [73af90ca23](https://linux-hardware.org/?probe=73af90ca23) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | Desktop     | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | Desktop     | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| Dell          | 048DY8 A00                  | Desktop     | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| Google        | Panther                     | Desktop     | [1adc816fcb](https://linux-hardware.org/?probe=1adc816fcb) | Sep 12, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| Dell          | 088DT1 A00                  | Desktop     | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [4ad00f4c17](https://linux-hardware.org/?probe=4ad00f4c17) | Sep 10, 2023 |
| Intel         | NUC8CYB J69922-405          | Mini pc     | [00ad48fba7](https://linux-hardware.org/?probe=00ad48fba7) | Sep 10, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a09c6ad4a9](https://linux-hardware.org/?probe=a09c6ad4a9) | Sep 08, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| Dell          | 0MCD6J A01                  | Server      | [f73ae91625](https://linux-hardware.org/?probe=f73ae91625) | Sep 07, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1bc029ed5e](https://linux-hardware.org/?probe=1bc029ed5e) | Sep 07, 2023 |
| Dell          | 0MCD6J A01                  | Server      | [051518ebc8](https://linux-hardware.org/?probe=051518ebc8) | Sep 07, 2023 |
| Dell          | 0MCD6J A03                  | Server      | [22cd3a08c6](https://linux-hardware.org/?probe=22cd3a08c6) | Sep 07, 2023 |
| Dell          | 0MCD6J A01                  | Server      | [51344d733f](https://linux-hardware.org/?probe=51344d733f) | Sep 07, 2023 |
| Dell          | 0MCD6J A01                  | Server      | [8d286f93a4](https://linux-hardware.org/?probe=8d286f93a4) | Sep 07, 2023 |
| Dell          | 0MCD6J A01                  | Server      | [2677109010](https://linux-hardware.org/?probe=2677109010) | Sep 07, 2023 |
| Dell          | 0MCD6J A01                  | Server      | [f12a8bcc1b](https://linux-hardware.org/?probe=f12a8bcc1b) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [9d45d79cb0](https://linux-hardware.org/?probe=9d45d79cb0) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [ea1d0861a1](https://linux-hardware.org/?probe=ea1d0861a1) | Sep 05, 2023 |
| ASRock        | NF6-GLAN                    | Desktop     | [80d9233886](https://linux-hardware.org/?probe=80d9233886) | Sep 04, 2023 |
| Acer          | Aspire E5-471G              | Notebook    | [b1332205f3](https://linux-hardware.org/?probe=b1332205f3) | Sep 03, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| HP            | 1000                        | Notebook    | [aedfad957a](https://linux-hardware.org/?probe=aedfad957a) | Sep 02, 2023 |
| ViewSonic     | VPC14-WP                    | Desktop     | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| ECS           | A780GM-A                    | Desktop     | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [dda651a1c4](https://linux-hardware.org/?probe=dda651a1c4) | Aug 30, 2023 |
| HP            | 802F                        | Desktop     | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf8f795045](https://linux-hardware.org/?probe=bf8f795045) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| MiTAC         | PD10EHI                     | Desktop     | [972fe64be0](https://linux-hardware.org/?probe=972fe64be0) | Aug 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [df9818b791](https://linux-hardware.org/?probe=df9818b791) | Aug 23, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5247fcf1af](https://linux-hardware.org/?probe=5247fcf1af) | Aug 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [1f1ce97787](https://linux-hardware.org/?probe=1f1ce97787) | Aug 19, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [405bf1e224](https://linux-hardware.org/?probe=405bf1e224) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [c711cf46d7](https://linux-hardware.org/?probe=c711cf46d7) | Aug 14, 2023 |
| Dell          | 0HY9JP A01                  | Desktop     | [48d92d85c7](https://linux-hardware.org/?probe=48d92d85c7) | Aug 11, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [60cfdb5283](https://linux-hardware.org/?probe=60cfdb5283) | Aug 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [0b3bf57b84](https://linux-hardware.org/?probe=0b3bf57b84) | Aug 07, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [ffb1e25ac0](https://linux-hardware.org/?probe=ffb1e25ac0) | Jul 24, 2023 |
| ASUSTek       | X45U                        | Notebook    | [53a411cd41](https://linux-hardware.org/?probe=53a411cd41) | Jul 23, 2023 |
| HP            | 304Ah                       | Desktop     | [81682ebb2d](https://linux-hardware.org/?probe=81682ebb2d) | Jul 20, 2023 |
| Fujitsu       | FMVNA9K3C                   | Notebook    | [64c67e920e](https://linux-hardware.org/?probe=64c67e920e) | Jul 20, 2023 |
| Fujitsu       | FMVNA9K3C                   | Notebook    | [0b0d110403](https://linux-hardware.org/?probe=0b0d110403) | Jul 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [fe1ab04658](https://linux-hardware.org/?probe=fe1ab04658) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [be44ef471d](https://linux-hardware.org/?probe=be44ef471d) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [3de307450d](https://linux-hardware.org/?probe=3de307450d) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [5633b6ed54](https://linux-hardware.org/?probe=5633b6ed54) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Gigabyte      | P75-D3P                     | Desktop     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| Acer          | Aspire E5-471G              | Notebook    | [c958efdb37](https://linux-hardware.org/?probe=c958efdb37) | Jul 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [83e08e8aca](https://linux-hardware.org/?probe=83e08e8aca) | Jul 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| NEC Comput... | PC-VK27MBZCG                | Notebook    | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [87cc790852](https://linux-hardware.org/?probe=87cc790852) | Jul 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| ASUSTek       | A3402WBA                    | All in one  | [f2f0b0cc99](https://linux-hardware.org/?probe=f2f0b0cc99) | Jun 23, 2023 |
| HP            | 802F                        | Desktop     | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| HP            | 802F                        | Desktop     | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [592b7aa556](https://linux-hardware.org/?probe=592b7aa556) | Jun 21, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| Acer          | Aspire E5-471               | Notebook    | [48154f868d](https://linux-hardware.org/?probe=48154f868d) | Jun 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e57372edd4](https://linux-hardware.org/?probe=e57372edd4) | Jun 16, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [9cba8f7730](https://linux-hardware.org/?probe=9cba8f7730) | Jun 15, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [4a0de9eca8](https://linux-hardware.org/?probe=4a0de9eca8) | Jun 14, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [48f92f1f3f](https://linux-hardware.org/?probe=48f92f1f3f) | Jun 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [628ee9ac88](https://linux-hardware.org/?probe=628ee9ac88) | Jun 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [1bdfa737bc](https://linux-hardware.org/?probe=1bdfa737bc) | Jun 08, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8fa7afa4a1](https://linux-hardware.org/?probe=8fa7afa4a1) | Jun 04, 2023 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [3e68e53c33](https://linux-hardware.org/?probe=3e68e53c33) | Jun 03, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| Dell          | 07WP95 A01                  | Desktop     | [b9f3afed0c](https://linux-hardware.org/?probe=b9f3afed0c) | May 31, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| Dell          | 07WP95 A01                  | Desktop     | [a58adc500e](https://linux-hardware.org/?probe=a58adc500e) | May 30, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| Lenovo        | 313A NOK                    | Desktop     | [a1ffbc1e1e](https://linux-hardware.org/?probe=a1ffbc1e1e) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | Desktop     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Acer          | Veriton M2610G              | Desktop     | [001e547ddf](https://linux-hardware.org/?probe=001e547ddf) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | Notebook    | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| ASUSTek       | D320SF                      | Desktop     | [bbfd29fb88](https://linux-hardware.org/?probe=bbfd29fb88) | May 08, 2023 |
| ASUSTek       | D320SF                      | Desktop     | [fdb3953309](https://linux-hardware.org/?probe=fdb3953309) | May 08, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e35b234e43](https://linux-hardware.org/?probe=e35b234e43) | May 07, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [aaf53ecd65](https://linux-hardware.org/?probe=aaf53ecd65) | May 05, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [bbe145a1a2](https://linux-hardware.org/?probe=bbe145a1a2) | May 05, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2ebe14f5d0](https://linux-hardware.org/?probe=2ebe14f5d0) | May 04, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [71bf54960f](https://linux-hardware.org/?probe=71bf54960f) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [206f95ee6f](https://linux-hardware.org/?probe=206f95ee6f) | May 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | Notebook    | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3166746b52](https://linux-hardware.org/?probe=3166746b52) | Apr 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [52e50e17de](https://linux-hardware.org/?probe=52e50e17de) | Apr 11, 2023 |
| Lenovo        | No DPK                      | Desktop     | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [422a85d62b](https://linux-hardware.org/?probe=422a85d62b) | Apr 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [2c68190118](https://linux-hardware.org/?probe=2c68190118) | Apr 03, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| HP            | 802F                        | Desktop     | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fda0ab85e6](https://linux-hardware.org/?probe=fda0ab85e6) | Mar 18, 2023 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [8c266d3142](https://linux-hardware.org/?probe=8c266d3142) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2a40386fb8](https://linux-hardware.org/?probe=2a40386fb8) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [89194cffbe](https://linux-hardware.org/?probe=89194cffbe) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| Acer          | Aspire TC-390               | Desktop     | [2d092d008e](https://linux-hardware.org/?probe=2d092d008e) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [388f28c258](https://linux-hardware.org/?probe=388f28c258) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [715d043ec7](https://linux-hardware.org/?probe=715d043ec7) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| HP            | 1998                        | Desktop     | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | A4110                       | All in one  | [69f378f0b5](https://linux-hardware.org/?probe=69f378f0b5) | Feb 24, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [990ffa68f4](https://linux-hardware.org/?probe=990ffa68f4) | Feb 23, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [73dde5b3db](https://linux-hardware.org/?probe=73dde5b3db) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [daf7b5a6cc](https://linux-hardware.org/?probe=daf7b5a6cc) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | Notebook    | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [06c1b9f781](https://linux-hardware.org/?probe=06c1b9f781) | Feb 20, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| HP            | 83E4                        | All in one  | [cdefba9e55](https://linux-hardware.org/?probe=cdefba9e55) | Feb 09, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | Notebook    | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [064806786c](https://linux-hardware.org/?probe=064806786c) | Jan 23, 2023 |
| Acer          | Aspire A515-55G             | Notebook    | [7a4e781669](https://linux-hardware.org/?probe=7a4e781669) | Jan 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [40560e6bcd](https://linux-hardware.org/?probe=40560e6bcd) | Jan 21, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [22b5c66553](https://linux-hardware.org/?probe=22b5c66553) | Jan 12, 2023 |
| Dell          | 054KM3 A00                  | Desktop     | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| AZW           | GTR V01                     | Mini pc     | [4ab41ad921](https://linux-hardware.org/?probe=4ab41ad921) | Jan 08, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| Lenovo        | IdeaPad 300S-11IBR 80KU     | Notebook    | [6335e974a1](https://linux-hardware.org/?probe=6335e974a1) | Jan 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [9c9e1b06f9](https://linux-hardware.org/?probe=9c9e1b06f9) | Jan 07, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [67103caf92](https://linux-hardware.org/?probe=67103caf92) | Jan 07, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [631c1eea14](https://linux-hardware.org/?probe=631c1eea14) | Jan 06, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Dell          | G3 3579                     | Notebook    | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| HP            | 802F                        | Desktop     | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [26ed239f3c](https://linux-hardware.org/?probe=26ed239f3c) | Dec 23, 2022 |
| Gigabyte      | P75-D3P                     | Desktop     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [b0a81337c4](https://linux-hardware.org/?probe=b0a81337c4) | Dec 13, 2022 |
| Supermicro    | X9DRW                       | Server      | [ead67ca4f7](https://linux-hardware.org/?probe=ead67ca4f7) | Dec 13, 2022 |
| Acer          | TravelMate P214-41-G2       | Notebook    | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2ac449d25f](https://linux-hardware.org/?probe=2ac449d25f) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [af31550cae](https://linux-hardware.org/?probe=af31550cae) | Nov 27, 2022 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [8b44a7deaa](https://linux-hardware.org/?probe=8b44a7deaa) | Nov 21, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [e60a1f8fc4](https://linux-hardware.org/?probe=e60a1f8fc4) | Nov 20, 2022 |
| HP            | 82F2 A01                    | Desktop     | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Dell          | Precision 5530              | Notebook    | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7c284b1dfd](https://linux-hardware.org/?probe=7c284b1dfd) | Oct 20, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [7c689396eb](https://linux-hardware.org/?probe=7c689396eb) | Oct 19, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [357ad9257d](https://linux-hardware.org/?probe=357ad9257d) | Oct 19, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7d71e688f4](https://linux-hardware.org/?probe=7d71e688f4) | Oct 08, 2022 |
| HP            | Laptop                      | Notebook    | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| Timi          | TM1701                      | Notebook    | [59153cc5fe](https://linux-hardware.org/?probe=59153cc5fe) | Sep 27, 2022 |
| HP            | Laptop                      | Notebook    | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [c0fcc47188](https://linux-hardware.org/?probe=c0fcc47188) | Sep 03, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [576dfabbf6](https://linux-hardware.org/?probe=576dfabbf6) | Aug 29, 2022 |
| OEM           | Intel H81                   | Desktop     | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [65f638768e](https://linux-hardware.org/?probe=65f638768e) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [0008869bb6](https://linux-hardware.org/?probe=0008869bb6) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c0e9a2e062](https://linux-hardware.org/?probe=c0e9a2e062) | Aug 27, 2022 |
| OEM           | Intel H81                   | Desktop     | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [51a98d93a6](https://linux-hardware.org/?probe=51a98d93a6) | Aug 20, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [dc65bd0f38](https://linux-hardware.org/?probe=dc65bd0f38) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [93b2d066d6](https://linux-hardware.org/?probe=93b2d066d6) | Aug 17, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [5cdd2332d5](https://linux-hardware.org/?probe=5cdd2332d5) | Aug 14, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| HP            | 8062                        | Desktop     | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [1b9f19b21e](https://linux-hardware.org/?probe=1b9f19b21e) | Aug 13, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | Desktop     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| Acer          | TravelMate P643-M           | Notebook    | [33254cfb1e](https://linux-hardware.org/?probe=33254cfb1e) | Aug 03, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [d736692861](https://linux-hardware.org/?probe=d736692861) | Jul 31, 2022 |
| Dell          | Latitude 3320               | Notebook    | [183ae38016](https://linux-hardware.org/?probe=183ae38016) | Jul 31, 2022 |
| Dell          | Latitude 3320               | Notebook    | [a849c0d90a](https://linux-hardware.org/?probe=a849c0d90a) | Jul 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| Acer          | TravelMate P643-M           | Notebook    | [0357bf32d7](https://linux-hardware.org/?probe=0357bf32d7) | Jul 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| Lenovo        | SHARKBAY 31900059 WIN       | All in one  | [f27df86fda](https://linux-hardware.org/?probe=f27df86fda) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus X APEX          | Desktop     | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [cfa0dde1d0](https://linux-hardware.org/?probe=cfa0dde1d0) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [334719e6a2](https://linux-hardware.org/?probe=334719e6a2) | Jun 30, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | Notebook    | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| AFOX          | AF IH81-MA3 V1.0            | Desktop     | [4ce7ccc125](https://linux-hardware.org/?probe=4ce7ccc125) | Jun 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| MSI           | GE76 Raider 10UH            | Notebook    | [77ef5acb4c](https://linux-hardware.org/?probe=77ef5acb4c) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e3bb4dee4b](https://linux-hardware.org/?probe=e3bb4dee4b) | Jun 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c5c6eed0d9](https://linux-hardware.org/?probe=c5c6eed0d9) | Jun 14, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [fd7d146eb1](https://linux-hardware.org/?probe=fd7d146eb1) | Jun 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b12802bc7a](https://linux-hardware.org/?probe=b12802bc7a) | Jun 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| Acer          | One Z1402                   | Notebook    | [4278b806cf](https://linux-hardware.org/?probe=4278b806cf) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [dadda333d2](https://linux-hardware.org/?probe=dadda333d2) | May 28, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [3dbf1858d0](https://linux-hardware.org/?probe=3dbf1858d0) | May 27, 2022 |
| Dell          | Latitude 3120               | Notebook    | [e97cf58459](https://linux-hardware.org/?probe=e97cf58459) | May 23, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8949bc2cf8](https://linux-hardware.org/?probe=8949bc2cf8) | May 22, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| Acer          | One Z1402                   | Notebook    | [ae69c0fdbd](https://linux-hardware.org/?probe=ae69c0fdbd) | May 21, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [90bfbc9f6b](https://linux-hardware.org/?probe=90bfbc9f6b) | May 16, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [07e54c3c41](https://linux-hardware.org/?probe=07e54c3c41) | May 12, 2022 |
| Intel         | D54250WYK H13922-305        | Desktop     | [6d1745c79b](https://linux-hardware.org/?probe=6d1745c79b) | May 11, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [e765b34181](https://linux-hardware.org/?probe=e765b34181) | May 11, 2022 |
| Lenovo        | ThinkPad X230 23257Y1       | Notebook    | [0c4e13a23d](https://linux-hardware.org/?probe=0c4e13a23d) | May 11, 2022 |
| HP            | 18E7                        | Desktop     | [52a59840d8](https://linux-hardware.org/?probe=52a59840d8) | May 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJS... | Notebook    | [fb11780c46](https://linux-hardware.org/?probe=fb11780c46) | May 07, 2022 |
| ASRock        | H370 Pro4                   | Desktop     | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fec983464c](https://linux-hardware.org/?probe=fec983464c) | Apr 29, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| HP            | Pro Tablet 608 G1           | Notebook    | [a8b97ee7cf](https://linux-hardware.org/?probe=a8b97ee7cf) | Apr 25, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [377315649e](https://linux-hardware.org/?probe=377315649e) | Apr 22, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [6d291b9c9c](https://linux-hardware.org/?probe=6d291b9c9c) | Apr 21, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [218e8b7d2a](https://linux-hardware.org/?probe=218e8b7d2a) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | Notebook    | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [95744e46d1](https://linux-hardware.org/?probe=95744e46d1) | Apr 18, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| Acer          | Aspire E5-471G              | Notebook    | [a7179e1ba3](https://linux-hardware.org/?probe=a7179e1ba3) | Apr 16, 2022 |
| ASRock        | B460M-ITX/ac                | Desktop     | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Framework     | Laptop                      | Notebook    | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c0df9a1ac0](https://linux-hardware.org/?probe=c0df9a1ac0) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Dell          | Latitude 3120               | Notebook    | [69b7d6b1a3](https://linux-hardware.org/?probe=69b7d6b1a3) | Mar 26, 2022 |
| Dell          | Latitude 3120               | Notebook    | [78ae48c482](https://linux-hardware.org/?probe=78ae48c482) | Mar 26, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [d534c1e639](https://linux-hardware.org/?probe=d534c1e639) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [c2f6faf193](https://linux-hardware.org/?probe=c2f6faf193) | Mar 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [afa2ad19c8](https://linux-hardware.org/?probe=afa2ad19c8) | Mar 04, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASRock        | H410M-HDV R2.0              | Desktop     | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Acer          | AOA150                      | Notebook    | [aeb35f9f12](https://linux-hardware.org/?probe=aeb35f9f12) | Feb 13, 2022 |
| Acer          | AOA150                      | Notebook    | [7d493dd5d5](https://linux-hardware.org/?probe=7d493dd5d5) | Feb 13, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5d3d7c5340](https://linux-hardware.org/?probe=5d3d7c5340) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1488d5e773](https://linux-hardware.org/?probe=1488d5e773) | Feb 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dfc4821588](https://linux-hardware.org/?probe=dfc4821588) | Feb 08, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | Desktop     | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | Desktop     | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [c90234250e](https://linux-hardware.org/?probe=c90234250e) | Jan 31, 2022 |
| Lenovo        | ThinkPad P50 20EQS2AB00     | Notebook    | [bdc680b5f1](https://linux-hardware.org/?probe=bdc680b5f1) | Jan 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [31f48cd25e](https://linux-hardware.org/?probe=31f48cd25e) | Jan 19, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [2c877954ab](https://linux-hardware.org/?probe=2c877954ab) | Jan 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [dfe91144b0](https://linux-hardware.org/?probe=dfe91144b0) | Jan 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [247f2934b0](https://linux-hardware.org/?probe=247f2934b0) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [608af1b572](https://linux-hardware.org/?probe=608af1b572) | Jan 04, 2022 |
| HP            | 82B4                        | Desktop     | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| ASRock        | M3A770DE                    | Desktop     | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2e71480673](https://linux-hardware.org/?probe=2e71480673) | Dec 24, 2021 |
| HP            | 82B4                        | Desktop     | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | Desktop     | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | Desktop     | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | Desktop     | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | Desktop     | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | Notebook    | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0d0596e9ea](https://linux-hardware.org/?probe=0d0596e9ea) | Nov 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| MSI           | 3666h                       | Desktop     | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | Desktop     | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [4083699145](https://linux-hardware.org/?probe=4083699145) | Nov 14, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [e3825be547](https://linux-hardware.org/?probe=e3825be547) | Nov 14, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [d1b6520785](https://linux-hardware.org/?probe=d1b6520785) | Nov 13, 2021 |
| HP            | EliteBook 6930p (FL488AW... | Notebook    | [af8e63842a](https://linux-hardware.org/?probe=af8e63842a) | Oct 28, 2021 |
| Acer          | Aspire ES1-131              | Notebook    | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1193264475](https://linux-hardware.org/?probe=1193264475) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [514642d183](https://linux-hardware.org/?probe=514642d183) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [e4fb99f5b8](https://linux-hardware.org/?probe=e4fb99f5b8) | Sep 30, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [8141d6fa89](https://linux-hardware.org/?probe=8141d6fa89) | Sep 22, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [74fe90715f](https://linux-hardware.org/?probe=74fe90715f) | Sep 22, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Dell          | 02P9X9 A03                  | Server      | [56b5e62268](https://linux-hardware.org/?probe=56b5e62268) | Sep 17, 2021 |
| Dell          | 02P9X9 A03                  | Server      | [cb07eeaf33](https://linux-hardware.org/?probe=cb07eeaf33) | Sep 17, 2021 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | Desktop     | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Dell          | Latitude D630               | Notebook    | [3af0cdbc54](https://linux-hardware.org/?probe=3af0cdbc54) | Sep 09, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| Acer          | Aspire V3-575G              | Notebook    | [28e06e0c2b](https://linux-hardware.org/?probe=28e06e0c2b) | Aug 28, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [8e060f6c6c](https://linux-hardware.org/?probe=8e060f6c6c) | Aug 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | Desktop     | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [7f7c5133ad](https://linux-hardware.org/?probe=7f7c5133ad) | Aug 18, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| Dell          | 0D24M8 A00                  | Desktop     | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1a50426a2c](https://linux-hardware.org/?probe=1a50426a2c) | Aug 02, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [94623b82cf](https://linux-hardware.org/?probe=94623b82cf) | Aug 02, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | Desktop     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [65ad8ece4a](https://linux-hardware.org/?probe=65ad8ece4a) | Jul 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [10b4953c7e](https://linux-hardware.org/?probe=10b4953c7e) | Jul 26, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [9d13b7e8df](https://linux-hardware.org/?probe=9d13b7e8df) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [bde4a22e40](https://linux-hardware.org/?probe=bde4a22e40) | Jul 19, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [5c7365be9d](https://linux-hardware.org/?probe=5c7365be9d) | Jul 16, 2021 |
| Acer          | One 10 SW110-1CT            | Tablet      | [51296db584](https://linux-hardware.org/?probe=51296db584) | Jul 14, 2021 |
| Acer          | One 10 SW110-1CT            | Tablet      | [9a40d5c9da](https://linux-hardware.org/?probe=9a40d5c9da) | Jul 14, 2021 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [f5bfb0ada6](https://linux-hardware.org/?probe=f5bfb0ada6) | Jul 09, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [e69ebc683f](https://linux-hardware.org/?probe=e69ebc683f) | Jul 09, 2021 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| HP            | Stream Notebook             | Notebook    | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| ASUSTek       | X450LN                      | Notebook    | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| Lenovo        | B50-80 80LT                 | Notebook    | [ef615e10ea](https://linux-hardware.org/?probe=ef615e10ea) | May 27, 2021 |
| Intel         | H61M S1                     | Desktop     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| ASUSTek       | X450LN                      | Notebook    | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| Toshiba       | Satellite L645              | Notebook    | [a3c061e392](https://linux-hardware.org/?probe=a3c061e392) | May 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0d99884dcd](https://linux-hardware.org/?probe=0d99884dcd) | May 17, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [e8e3c50f4b](https://linux-hardware.org/?probe=e8e3c50f4b) | May 16, 2021 |
| Dell          | Latitude 3410               | Notebook    | [b29d7ddfe8](https://linux-hardware.org/?probe=b29d7ddfe8) | May 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [1a7d88c72a](https://linux-hardware.org/?probe=1a7d88c72a) | May 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [7b00c56952](https://linux-hardware.org/?probe=7b00c56952) | May 02, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Dell          | Latitude 3410               | Notebook    | [b6748a9a7e](https://linux-hardware.org/?probe=b6748a9a7e) | Apr 25, 2021 |
| Acer          | Veriton X2665G              | Desktop     | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | Desktop     | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | Desktop     | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| Dell          | G7 7590                     | Notebook    | [be5780df0a](https://linux-hardware.org/?probe=be5780df0a) | Mar 09, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Unknown       | Unknown                     | Tablet      | [315c09fd74](https://linux-hardware.org/?probe=315c09fd74) | Mar 04, 2021 |
| Gigabyte      | Z490 UD                     | Desktop     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Samsung       | R780/R778                   | Notebook    | [0c57a7241e](https://linux-hardware.org/?probe=0c57a7241e) | Feb 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [1faf0b360f](https://linux-hardware.org/?probe=1faf0b360f) | Feb 19, 2021 |
| ASUSTek       | K45VM                       | Notebook    | [26690f314d](https://linux-hardware.org/?probe=26690f314d) | Feb 15, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [1b2994e7f3](https://linux-hardware.org/?probe=1b2994e7f3) | Feb 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [40bcb4aaf2](https://linux-hardware.org/?probe=40bcb4aaf2) | Feb 15, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [0392f08b03](https://linux-hardware.org/?probe=0392f08b03) | Feb 15, 2021 |
| HP            | 1998                        | Desktop     | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [401fa9d58e](https://linux-hardware.org/?probe=401fa9d58e) | Feb 13, 2021 |
| Dell          | 0F8096                      | Desktop     | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| HP            | 1000                        | Notebook    | [16b305a6f5](https://linux-hardware.org/?probe=16b305a6f5) | Feb 13, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [20b10721e2](https://linux-hardware.org/?probe=20b10721e2) | Feb 09, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [360e7155d7](https://linux-hardware.org/?probe=360e7155d7) | Feb 06, 2021 |
| Dell          | 0F8096                      | Desktop     | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | Desktop     | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Sony          | SVF14N25CXB                 | Notebook    | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| Acer          | Aspire M1935                | Desktop     | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | Desktop     | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [731a44edca](https://linux-hardware.org/?probe=731a44edca) | Jan 16, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [1a065f105a](https://linux-hardware.org/?probe=1a065f105a) | Jan 16, 2021 |
| Lenovo        | IdeaPad Y450                | Notebook    | [1285c5deb9](https://linux-hardware.org/?probe=1285c5deb9) | Jan 11, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [788c6c2caf](https://linux-hardware.org/?probe=788c6c2caf) | Jan 07, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [fcdcacd2bc](https://linux-hardware.org/?probe=fcdcacd2bc) | Jan 07, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| Fujitsu       | JIM76YK3                    | Desktop     | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [e28d350fac](https://linux-hardware.org/?probe=e28d350fac) | Dec 24, 2020 |
| ASUSTek       | X450CC                      | Notebook    | [750f666a09](https://linux-hardware.org/?probe=750f666a09) | Dec 23, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| Lenovo        | ThinkPad E15 20RES51Y00     | Notebook    | [66b1afc07c](https://linux-hardware.org/?probe=66b1afc07c) | Dec 15, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Dell          | Inspiron 5468               | Notebook    | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [cb5f05e67d](https://linux-hardware.org/?probe=cb5f05e67d) | Dec 02, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [53a62697ed](https://linux-hardware.org/?probe=53a62697ed) | Dec 01, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [719a24bc0f](https://linux-hardware.org/?probe=719a24bc0f) | Nov 30, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [90b21f8369](https://linux-hardware.org/?probe=90b21f8369) | Nov 23, 2020 |
| Acer          | Aspire VN7-793G             | Notebook    | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [43c71a128c](https://linux-hardware.org/?probe=43c71a128c) | Nov 20, 2020 |
| Dell          | G5 5590                     | Notebook    | [007ad64378](https://linux-hardware.org/?probe=007ad64378) | Nov 20, 2020 |
| MSI           | GE75 Raider 10SGS           | Notebook    | [025deb9bbe](https://linux-hardware.org/?probe=025deb9bbe) | Nov 19, 2020 |
| Dell          | G5 5590                     | Notebook    | [e82ed4c1d0](https://linux-hardware.org/?probe=e82ed4c1d0) | Nov 19, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [f90473f671](https://linux-hardware.org/?probe=f90473f671) | Nov 16, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bf8d99074a](https://linux-hardware.org/?probe=bf8d99074a) | Nov 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Hampoo        | Unknown                     | Notebook    | [b713cd21d1](https://linux-hardware.org/?probe=b713cd21d1) | Oct 24, 2020 |
| Hampoo        | Unknown                     | Notebook    | [03640b9aac](https://linux-hardware.org/?probe=03640b9aac) | Oct 24, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [8c3ccf4956](https://linux-hardware.org/?probe=8c3ccf4956) | Oct 19, 2020 |
| ASRock        | Z270 Killer SLI             | Desktop     | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Dell          | Precision 7740              | Notebook    | [814a0ec705](https://linux-hardware.org/?probe=814a0ec705) | Oct 15, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [1691661a18](https://linux-hardware.org/?probe=1691661a18) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [e0d54e69ff](https://linux-hardware.org/?probe=e0d54e69ff) | Oct 11, 2020 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2b12ebd1f3](https://linux-hardware.org/?probe=2b12ebd1f3) | Oct 09, 2020 |
| Gigabyte      | F2A85XM-HD3                 | Desktop     | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| HP            | Pavilion dv7                | Notebook    | [058179daf5](https://linux-hardware.org/?probe=058179daf5) | Sep 24, 2020 |
| ASRock        | B460M Steel Legend          | Desktop     | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | Desktop     | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| HP            | Pavilion dv6                | Notebook    | [acce68d947](https://linux-hardware.org/?probe=acce68d947) | Sep 09, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [9fc26445da](https://linux-hardware.org/?probe=9fc26445da) | Sep 03, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [fd56e29478](https://linux-hardware.org/?probe=fd56e29478) | Sep 03, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [e55f750fc2](https://linux-hardware.org/?probe=e55f750fc2) | Sep 02, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [cc7e35217e](https://linux-hardware.org/?probe=cc7e35217e) | Sep 02, 2020 |
| ASRock        | B450M Steel Legend          | Desktop     | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [706847f6cd](https://linux-hardware.org/?probe=706847f6cd) | Aug 30, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Lenovo        | No DPK                      | All in one  | [08057029e5](https://linux-hardware.org/?probe=08057029e5) | Aug 23, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | Desktop     | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| ASUSTek       | X411UN                      | Notebook    | [212932d80d](https://linux-hardware.org/?probe=212932d80d) | Jul 27, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Acer          | Swift SF314-57G             | Notebook    | [c74653b694](https://linux-hardware.org/?probe=c74653b694) | Jul 15, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [405d399549](https://linux-hardware.org/?probe=405d399549) | Jul 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4175ac62a0](https://linux-hardware.org/?probe=4175ac62a0) | Jul 10, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [7c061a0688](https://linux-hardware.org/?probe=7c061a0688) | Jul 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [1457f6e3b5](https://linux-hardware.org/?probe=1457f6e3b5) | Jul 04, 2020 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [adc28756a8](https://linux-hardware.org/?probe=adc28756a8) | Jun 29, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [6e947dfc9d](https://linux-hardware.org/?probe=6e947dfc9d) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | K42JB                       | Notebook    | [5f87f39c75](https://linux-hardware.org/?probe=5f87f39c75) | Jun 27, 2020 |
| MSI           | MS-14Y1                     | Notebook    | [c585b33393](https://linux-hardware.org/?probe=c585b33393) | Jun 25, 2020 |
| ASUSTek       | S340MF                      | Desktop     | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [8d0c93ef24](https://linux-hardware.org/?probe=8d0c93ef24) | Jun 17, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Lenovo        | No DPK                      | All in one  | [72809cb04b](https://linux-hardware.org/?probe=72809cb04b) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| MSI           | MS-14Y1                     | Notebook    | [657c6d539f](https://linux-hardware.org/?probe=657c6d539f) | Jun 03, 2020 |
| Sony          | SVF14N25CXB                 | Notebook    | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [0bb72c8f71](https://linux-hardware.org/?probe=0bb72c8f71) | Jun 01, 2020 |
| Lenovo        | Yoga S740-15IRH 81NX        | Convertible | [6af9fd9245](https://linux-hardware.org/?probe=6af9fd9245) | May 31, 2020 |
| Lenovo        | No DPK                      | All in one  | [f2bbfbe37d](https://linux-hardware.org/?probe=f2bbfbe37d) | May 27, 2020 |
| ASUSTek       | M2N                         | Desktop     | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [645ef14cb4](https://linux-hardware.org/?probe=645ef14cb4) | May 21, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4827cdc9b5](https://linux-hardware.org/?probe=4827cdc9b5) | May 21, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | Notebook    | [338493712f](https://linux-hardware.org/?probe=338493712f) | May 19, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | Notebook    | [17f5a0932c](https://linux-hardware.org/?probe=17f5a0932c) | May 19, 2020 |
| Samsung       | RV418/RV518/RV718           | Notebook    | [ff8f525d6b](https://linux-hardware.org/?probe=ff8f525d6b) | May 18, 2020 |
| Lenovo        | G480 20156                  | Notebook    | [6cb3a28f6a](https://linux-hardware.org/?probe=6cb3a28f6a) | May 18, 2020 |
| Lenovo        | G480 20156                  | Notebook    | [7487bf67c4](https://linux-hardware.org/?probe=7487bf67c4) | May 18, 2020 |
| Unknown       | Unknown                     | Desktop     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | Desktop     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | Desktop     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| Acer          | Nitro AN515-42              | Notebook    | [5c659d6268](https://linux-hardware.org/?probe=5c659d6268) | May 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [f286a38265](https://linux-hardware.org/?probe=f286a38265) | Apr 30, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [bbd3e36751](https://linux-hardware.org/?probe=bbd3e36751) | Apr 16, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [8bca0c818d](https://linux-hardware.org/?probe=8bca0c818d) | Apr 16, 2020 |
| Pegatron      | 2A99                        | Desktop     | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Lenovo        | ThinkPad T420 4180JH1       | Notebook    | [4d0e9109bb](https://linux-hardware.org/?probe=4d0e9109bb) | Mar 21, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [d577b178a1](https://linux-hardware.org/?probe=d577b178a1) | Mar 06, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [cc28243d3d](https://linux-hardware.org/?probe=cc28243d3d) | Mar 06, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [1d2bb93475](https://linux-hardware.org/?probe=1d2bb93475) | Mar 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [626f7fb341](https://linux-hardware.org/?probe=626f7fb341) | Feb 29, 2020 |
| Packard Be... | IMEDIA S3720                | Desktop     | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Predator PH315-51           | Notebook    | [b3edf8c190](https://linux-hardware.org/?probe=b3edf8c190) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [8d16cc2992](https://linux-hardware.org/?probe=8d16cc2992) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [ffbfac004c](https://linux-hardware.org/?probe=ffbfac004c) | Feb 23, 2020 |
| Dell          | Precision 5510              | Notebook    | [0e30ff12b4](https://linux-hardware.org/?probe=0e30ff12b4) | Feb 18, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [ac7b752d68](https://linux-hardware.org/?probe=ac7b752d68) | Feb 13, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | Compaq 15                   | Notebook    | [e8597ab3e4](https://linux-hardware.org/?probe=e8597ab3e4) | Feb 06, 2020 |
| MSI           | X460/X460DX                 | Notebook    | [faf3829102](https://linux-hardware.org/?probe=faf3829102) | Feb 04, 2020 |
| HP            | 3048h                       | Desktop     | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | Desktop     | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | Desktop     | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| Acer          | Veriton Z4660G              | All in one  | [866f2f8c49](https://linux-hardware.org/?probe=866f2f8c49) | Dec 28, 2019 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [670b5a0247](https://linux-hardware.org/?probe=670b5a0247) | Dec 27, 2019 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [fc21e1c322](https://linux-hardware.org/?probe=fc21e1c322) | Dec 18, 2019 |
| Lenovo        | ThinkPad P50 20EQS5XE00     | Notebook    | [65dc93e325](https://linux-hardware.org/?probe=65dc93e325) | Dec 18, 2019 |
| HP            | 2B15A                       | Desktop     | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | Desktop     | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [c00057fc87](https://linux-hardware.org/?probe=c00057fc87) | Dec 01, 2019 |
| Clevo         | M540SR VT6363A              | Notebook    | [97181c941c](https://linux-hardware.org/?probe=97181c941c) | Nov 23, 2019 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [0223eca896](https://linux-hardware.org/?probe=0223eca896) | Nov 22, 2019 |
| Lenovo        | G710 20252                  | Notebook    | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| Lenovo        | G710 20252                  | Notebook    | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [b65742b189](https://linux-hardware.org/?probe=b65742b189) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [6ccf378246](https://linux-hardware.org/?probe=6ccf378246) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [29d4434f82](https://linux-hardware.org/?probe=29d4434f82) | Oct 26, 2019 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| Acer          | Swift SF113-31              | Notebook    | [a37935b2e0](https://linux-hardware.org/?probe=a37935b2e0) | Sep 27, 2019 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | Notebook    | [ccf2eacdd1](https://linux-hardware.org/?probe=ccf2eacdd1) | Sep 14, 2019 |
| Acer          | Aspire E5-552G              | Notebook    | [5c4bd87bc9](https://linux-hardware.org/?probe=5c4bd87bc9) | Sep 04, 2019 |
| Dell          | Vostro 3458                 | Notebook    | [a62197181c](https://linux-hardware.org/?probe=a62197181c) | Sep 04, 2019 |
| Lenovo        | G460 20041                  | Notebook    | [7b5945bfc2](https://linux-hardware.org/?probe=7b5945bfc2) | Aug 31, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2d5f51cdd8](https://linux-hardware.org/?probe=2d5f51cdd8) | Aug 23, 2019 |
| ASUSTek       | H81M-CS                     | Desktop     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe49019be0](https://linux-hardware.org/?probe=fe49019be0) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7551b403e2](https://linux-hardware.org/?probe=7551b403e2) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef69a20f15](https://linux-hardware.org/?probe=ef69a20f15) | Aug 07, 2019 |
| ASUSTek       | H81M-E                      | Desktop     | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | Desktop     | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| HP            | ENVY Laptop ah0xxx          | Notebook    | [defe18c4c3](https://linux-hardware.org/?probe=defe18c4c3) | Jul 09, 2019 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | Desktop     | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Dell          | Latitude E6430              | Notebook    | [c8334c6a31](https://linux-hardware.org/?probe=c8334c6a31) | Jun 22, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [26db49d8f2](https://linux-hardware.org/?probe=26db49d8f2) | Jun 19, 2019 |
| Lenovo        | G460 20041                  | Notebook    | [62697bf35b](https://linux-hardware.org/?probe=62697bf35b) | Jun 16, 2019 |
| Biostar       | A10N-8800E                  | Desktop     | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [1dd80d33e5](https://linux-hardware.org/?probe=1dd80d33e5) | May 24, 2019 |
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [1ad0a80b86](https://linux-hardware.org/?probe=1ad0a80b86) | May 24, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [6d4aebc3ef](https://linux-hardware.org/?probe=6d4aebc3ef) | May 22, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | Desktop     | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [f878e784e2](https://linux-hardware.org/?probe=f878e784e2) | May 04, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Thailand/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 75        | 10.56%  |
| Ubuntu 22.04                 | 49        | 6.9%    |
| Ubuntu 18.04                 | 34        | 4.79%   |
| Arch Rolling                 | 21        | 2.96%   |
| Ubuntu 24.04                 | 19        | 2.68%   |
| Pop!_OS 22.04                | 17        | 2.39%   |
| OpenMandriva 4.2             | 16        | 2.25%   |
| Fedora 38                    | 16        | 2.25%   |
| OpenMandriva 23.08           | 14        | 1.97%   |
| Debian 11                    | 14        | 1.97%   |
| OpenMandriva 4.3             | 12        | 1.69%   |
| KDE neon 20.04               | 12        | 1.69%   |
| Fedora 37                    | 11        | 1.55%   |
| Debian 12                    | 11        | 1.55%   |
| ArcoLinux Rolling            | 10        | 1.41%   |
| OpenMandriva 23.01           | 9         | 1.27%   |
| Fedora 39                    | 9         | 1.27%   |
| Zorin 16                     | 8         | 1.13%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 1.13%   |
| Manjaro                      | 8         | 1.13%   |
| KDE neon 22.04               | 8         | 1.13%   |
| Fedora 40                    | 8         | 1.13%   |
| Zorin 15                     | 7         | 0.99%   |
| Linux Mint 21.3              | 7         | 0.99%   |
| Linux Mint 21                | 7         | 0.99%   |
| Kubuntu 22.04                | 7         | 0.99%   |
| Arch                         | 7         | 0.99%   |
| Xubuntu 18.04                | 6         | 0.85%   |
| Ubuntu 19.10                 | 6         | 0.85%   |
| OpenMandriva 5.0             | 6         | 0.85%   |
| Linux Mint 20.3              | 6         | 0.85%   |
| Linux Mint 20.2              | 6         | 0.85%   |
| Fedora 36                    | 6         | 0.85%   |
| Zorin 17                     | 5         | 0.7%    |
| Xubuntu 20.04                | 5         | 0.7%    |
| Ubuntu 19.04                 | 5         | 0.7%    |
| NixOS 24.05                  | 5         | 0.7%    |
| Linux Mint 21.2              | 5         | 0.7%    |
| Fedora 35                    | 5         | 0.7%    |
| Debian Testing               | 5         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 199       | 29.61%  |
| OpenMandriva  | 63        | 9.38%   |
| Fedora        | 62        | 9.23%   |
| Linux Mint    | 49        | 7.29%   |
| Debian        | 37        | 5.51%   |
| Arch          | 28        | 4.17%   |
| Pop!_OS       | 27        | 4.02%   |
| KDE neon      | 22        | 3.27%   |
| Zorin         | 20        | 2.98%   |
| Kubuntu       | 15        | 2.23%   |
| Endless       | 14        | 2.08%   |
| Xubuntu       | 13        | 1.93%   |
| openSUSE      | 11        | 1.64%   |
| Manjaro       | 11        | 1.64%   |
| ArcoLinux     | 10        | 1.49%   |
| Ubuntu MATE   | 8         | 1.19%   |
| Kali          | 8         | 1.19%   |
| Elementary    | 8         | 1.19%   |
| NixOS         | 7         | 1.04%   |
| MX            | 5         | 0.74%   |
| Clear Linux   | 5         | 0.74%   |
| Xero          | 4         | 0.6%    |
| EndeavourOS   | 4         | 0.6%    |
| Ultramarine   | 3         | 0.45%   |
| SteamOS       | 3         | 0.45%   |
| Lubuntu       | 3         | 0.45%   |
| Void Linux    | 2         | 0.3%    |
| UbuntuDDE     | 2         | 0.3%    |
| ROSA          | 2         | 0.3%    |
| Reborn OS     | 2         | 0.3%    |
| Nobara        | 2         | 0.3%    |
| Linux Lite    | 2         | 0.3%    |
| Gentoo        | 2         | 0.3%    |
| CentOS        | 2         | 0.3%    |
| BlackPanther  | 2         | 0.3%    |
| Archcraft     | 2         | 0.3%    |
| Ubuntu Unity  | 1         | 0.15%   |
| Ubuntu Budgie | 1         | 0.15%   |
| TUXEDO OS     | 1         | 0.15%   |
| Solus         | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 2%      |
| 6.4.11-desktop-1omv2390  | 14        | 1.75%   |
| 5.16.7-desktop-1omv4003  | 10        | 1.25%   |
| 6.1.1-desktop-1omv2290   | 9         | 1.13%   |
| 5.15.0-46-generic        | 9         | 1.13%   |
| 5.4.0-42-generic         | 7         | 0.88%   |
| 6.8.0-45-generic         | 6         | 0.75%   |
| 6.8.0-40-generic         | 6         | 0.75%   |
| 6.6.2-desktop-1omv2390   | 6         | 0.75%   |
| 5.4.0-48-generic         | 6         | 0.75%   |
| 5.15.0-56-generic        | 6         | 0.75%   |
| 4.18.0-15-generic        | 6         | 0.75%   |
| 6.8.0-48-generic         | 5         | 0.63%   |
| 5.4.0-156-generic        | 5         | 0.63%   |
| 5.3.0-28-generic         | 5         | 0.63%   |
| 5.15.0-58-generic        | 5         | 0.63%   |
| 5.15.0-43-generic        | 5         | 0.63%   |
| 6.8.0-49-generic         | 4         | 0.5%    |
| 6.8.0-41-generic         | 4         | 0.5%    |
| 6.2.0-39-generic         | 4         | 0.5%    |
| 6.2.0-37-generic         | 4         | 0.5%    |
| 6.0.12-76060006-generic  | 4         | 0.5%    |
| 5.8.0-59-generic         | 4         | 0.5%    |
| 5.4.0-59-generic         | 4         | 0.5%    |
| 5.3.0-23-generic         | 4         | 0.5%    |
| 5.19.0-43-generic        | 4         | 0.5%    |
| 5.11.0-40-generic        | 4         | 0.5%    |
| 5.10.0-21-amd64          | 4         | 0.5%    |
| 5.0.0-32-generic         | 4         | 0.5%    |
| 6.7.3-arch1-2            | 3         | 0.38%   |
| 6.5.6-300.fc39.x86_64    | 3         | 0.38%   |
| 6.5.0-35-generic         | 3         | 0.38%   |
| 6.5.0-21-generic         | 3         | 0.38%   |
| 6.4.15-200.fc38.x86_64   | 3         | 0.38%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.38%   |
| 6.2.0-34-generic         | 3         | 0.38%   |
| 6.2.0-33-generic         | 3         | 0.38%   |
| 6.2.0-32-generic         | 3         | 0.38%   |
| 6.2.0-26-generic         | 3         | 0.38%   |
| 6.12.1-desktop-1omv2490  | 3         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 80        | 10.32%  |
| 5.15.0  | 69        | 8.9%    |
| 6.8.0   | 34        | 4.39%   |
| 5.13.0  | 28        | 3.61%   |
| 5.8.0   | 26        | 3.35%   |
| 6.2.0   | 24        | 3.1%    |
| 4.15.0  | 24        | 3.1%    |
| 5.3.0   | 22        | 2.84%   |
| 6.5.0   | 20        | 2.58%   |
| 5.19.0  | 20        | 2.58%   |
| 5.11.0  | 19        | 2.45%   |
| 6.4.11  | 17        | 2.19%   |
| 5.10.14 | 16        | 2.06%   |
| 5.0.0   | 16        | 2.06%   |
| 4.18.0  | 14        | 1.81%   |
| 6.1.1   | 11        | 1.42%   |
| 6.1.0   | 11        | 1.42%   |
| 5.10.0  | 11        | 1.42%   |
| 5.16.7  | 10        | 1.29%   |
| 4.19.0  | 7         | 0.9%    |
| 6.6.2   | 6         | 0.77%   |
| 6.0.12  | 6         | 0.77%   |
| 5.17.5  | 6         | 0.77%   |
| 6.5.5   | 5         | 0.65%   |
| 6.2.6   | 4         | 0.52%   |
| 6.2.15  | 4         | 0.52%   |
| 6.12.1  | 4         | 0.52%   |
| 5.16.0  | 4         | 0.52%   |
| 6.9.8   | 3         | 0.39%   |
| 6.9.7   | 3         | 0.39%   |
| 6.9.3   | 3         | 0.39%   |
| 6.7.3   | 3         | 0.39%   |
| 6.6.1   | 3         | 0.39%   |
| 6.5.9   | 3         | 0.39%   |
| 6.5.6   | 3         | 0.39%   |
| 6.5.4   | 3         | 0.39%   |
| 6.5.3   | 3         | 0.39%   |
| 6.4.15  | 3         | 0.39%   |
| 6.2.9   | 3         | 0.39%   |
| 6.10.1  | 3         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 86        | 11.27%  |
| 5.15    | 79        | 10.35%  |
| 6.8     | 44        | 5.77%   |
| 6.2     | 44        | 5.77%   |
| 6.5     | 43        | 5.64%   |
| 5.13    | 33        | 4.33%   |
| 6.1     | 32        | 4.19%   |
| 5.10    | 32        | 4.19%   |
| 6.6     | 30        | 3.93%   |
| 5.8     | 30        | 3.93%   |
| 6.4     | 27        | 3.54%   |
| 5.19    | 27        | 3.54%   |
| 5.16    | 25        | 3.28%   |
| 5.3     | 24        | 3.15%   |
| 4.15    | 24        | 3.15%   |
| 5.11    | 19        | 2.49%   |
| 5.0     | 17        | 2.23%   |
| 6.0     | 15        | 1.97%   |
| 4.18    | 15        | 1.97%   |
| 6.9     | 14        | 1.83%   |
| 6.10    | 13        | 1.7%    |
| 5.17    | 13        | 1.7%    |
| 6.3     | 11        | 1.44%   |
| 6.7     | 8         | 1.05%   |
| 5.18    | 7         | 0.92%   |
| 4.19    | 7         | 0.92%   |
| 6.12    | 6         | 0.79%   |
| 5.6     | 6         | 0.79%   |
| 6.11    | 5         | 0.66%   |
| 5.9     | 5         | 0.66%   |
| 5.5     | 5         | 0.66%   |
| 5.12    | 5         | 0.66%   |
| 5.14    | 4         | 0.52%   |
| 5.7     | 2         | 0.26%   |
| 4.20    | 2         | 0.26%   |
| 5.1     | 1         | 0.13%   |
| 4.9     | 1         | 0.13%   |
| 4.4     | 1         | 0.13%   |
| 4.17    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 635       | 98.76%  |
| i686    | 4         | 0.62%   |
| aarch64 | 3         | 0.47%   |
| armv7l  | 1         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 314       | 45.91%  |
| KDE5             | 114       | 16.67%  |
| Unknown          | 73        | 10.67%  |
| XFCE             | 45        | 6.58%   |
| X-Cinnamon       | 45        | 6.58%   |
| KDE              | 17        | 2.49%   |
| KDE6             | 13        | 1.9%    |
| MATE             | 12        | 1.75%   |
| LXQt             | 9         | 1.32%   |
| Pantheon         | 8         | 1.17%   |
| Budgie           | 6         | 0.88%   |
| Deepin           | 4         | 0.58%   |
| Cinnamon         | 4         | 0.58%   |
| sway             | 3         | 0.44%   |
| i3               | 3         | 0.44%   |
| Hyprland         | 3         | 0.44%   |
| Unity            | 2         | 0.29%   |
| lightdm-xsession | 2         | 0.29%   |
| XFCE:GNOME:      | 1         | 0.15%   |
| TOS:GNOME        | 1         | 0.15%   |
| openbox          | 1         | 0.15%   |
| LXDE             | 1         | 0.15%   |
| GNOME Classic    | 1         | 0.15%   |
| bspwm            | 1         | 0.15%   |
| awesome          | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 425       | 63.72%  |
| Wayland | 190       | 28.49%  |
| Unknown | 42        | 6.3%    |
| Tty     | 10        | 1.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 309       | 45.91%  |
| SDDM    | 117       | 17.38%  |
| GDM3    | 98        | 14.56%  |
| GDM     | 71        | 10.55%  |
| LightDM | 66        | 9.81%   |
| TDM     | 9         | 1.34%   |
| XDM     | 1         | 0.15%   |
| Ly      | 1         | 0.15%   |
| GREETD  | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_US          | 456       | 69.83%  |
| Unknown        | 58        | 8.88%   |
| en_GB          | 32        | 4.9%    |
| th_TH          | 31        | 4.75%   |
| de_DE          | 22        | 3.37%   |
| C              | 17        | 2.6%    |
| it_IT          | 7         | 1.07%   |
| en_SG          | 7         | 1.07%   |
| fr_FR          | 6         | 0.92%   |
| ru_RU          | 4         | 0.61%   |
| fi_FI          | 2         | 0.31%   |
| en_AU          | 2         | 0.31%   |
| zh_CN          | 1         | 0.15%   |
| sv_SE          | 1         | 0.15%   |
| he_IL          | 1         | 0.15%   |
| es_MX          | 1         | 0.15%   |
| en_US.iso88591 | 1         | 0.15%   |
| en_IE          | 1         | 0.15%   |
| en_DK          | 1         | 0.15%   |
| de_CH          | 1         | 0.15%   |
| C.UTF8         | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 359       | 54.56%  |
| BIOS | 299       | 45.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 450       | 67.16%  |
| Btrfs   | 86        | 12.84%  |
| Overlay | 55        | 8.21%   |
| Tmpfs   | 49        | 7.31%   |
| Xfs     | 13        | 1.94%   |
| Unknown | 12        | 1.79%   |
| Zfs     | 5         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 321       | 48.34%  |
| Unknown | 307       | 46.23%  |
| MBR     | 36        | 5.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 551       | 83.11%  |
| Yes       | 112       | 16.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 455       | 68.63%  |
| Yes       | 208       | 31.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 109       | 16.95%  |
| Lenovo                               | 92        | 14.31%  |
| Acer                                 | 68        | 10.58%  |
| Dell                                 | 65        | 10.11%  |
| Hewlett-Packard                      | 58        | 9.02%   |
| Gigabyte Technology                  | 54        | 8.4%    |
| ASRock                               | 39        | 6.07%   |
| MSI                                  | 33        | 5.13%   |
| Apple                                | 22        | 3.42%   |
| Intel                                | 11        | 1.71%   |
| HUAWEI                               | 10        | 1.56%   |
| Fujitsu                              | 10        | 1.56%   |
| Samsung Electronics                  | 7         | 1.09%   |
| Toshiba                              | 5         | 0.78%   |
| Unknown                              | 5         | 0.78%   |
| AMI                                  | 3         | 0.47%   |
| Valve                                | 2         | 0.31%   |
| Timi                                 | 2         | 0.31%   |
| Supermicro                           | 2         | 0.31%   |
| MiTAC                                | 2         | 0.31%   |
| Microsoft                            | 2         | 0.31%   |
| MicroByte                            | 2         | 0.31%   |
| Infinix                              | 2         | 0.31%   |
| IBM                                  | 2         | 0.31%   |
| Huanan                               | 2         | 0.31%   |
| Google                               | 2         | 0.31%   |
| Biostar                              | 2         | 0.31%   |
| ViewSonic                            | 1         | 0.16%   |
| VIA Technologies                     | 1         | 0.16%   |
| Sony                                 | 1         | 0.16%   |
| SmbiosType1_SystemManufacturer       | 1         | 0.16%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.16%   |
| SHARKBAY                             | 1         | 0.16%   |
| Razer                                | 1         | 0.16%   |
| Raspberry Pi Foundation              | 1         | 0.16%   |
| Pegatron                             | 1         | 0.16%   |
| Packard Bell                         | 1         | 0.16%   |
| OEM                                  | 1         | 0.16%   |
| Nvidia                               | 1         | 0.16%   |
| Notebook                             | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 9         | 1.4%    |
| Unknown                                | 7         | 1.09%   |
| Dell PowerEdge R7625                   | 5         | 0.78%   |
| HUAWEI BOHB-WAX9                       | 4         | 0.62%   |
| Dell OptiPlex 7010                     | 4         | 0.62%   |
| ASRock B450 Steel Legend               | 4         | 0.62%   |
| Lenovo Z50-70 20354                    | 3         | 0.47%   |
| Lenovo MIIX 520-12IKB 81CG             | 3         | 0.47%   |
| Dell Inspiron 3847                     | 3         | 0.47%   |
| ASUS P8H61-M LE                        | 3         | 0.47%   |
| Acer Veriton N4640G                    | 3         | 0.47%   |
| Acer Aspire E5-471G                    | 3         | 0.47%   |
| Valve Jupiter                          | 2         | 0.31%   |
| Samsung NC208/NC108                    | 2         | 0.31%   |
| MSI GF65 Thin 10UE                     | 2         | 0.31%   |
| MicroByte ezbook                       | 2         | 0.31%   |
| Lenovo Yoga 7 14ITL5 82BH              | 2         | 0.31%   |
| Lenovo ThinkPad X240 20AMS00100        | 2         | 0.31%   |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000 | 2         | 0.31%   |
| Lenovo ThinkBook 14 G2 ITL 20VD        | 2         | 0.31%   |
| Lenovo G460 20041                      | 2         | 0.31%   |
| Lenovo G40-45 80E1                     | 2         | 0.31%   |
| Intel X99                              | 2         | 0.31%   |
| Infinix INBOOK X2                      | 2         | 0.31%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.31%   |
| HP Z240 Tower Workstation              | 2         | 0.31%   |
| HP Laptop 14-ck0xxx                    | 2         | 0.31%   |
| HP Laptop 14-bs0xx                     | 2         | 0.31%   |
| HP EliteDesk 800 G1 SFF PC             | 2         | 0.31%   |
| HP Compaq 6200 Pro SFF PC              | 2         | 0.31%   |
| Gigabyte Z97X-UD3H-BK                  | 2         | 0.31%   |
| Gigabyte H81M-DS2                      | 2         | 0.31%   |
| Gigabyte H61M-DS2                      | 2         | 0.31%   |
| Gigabyte H110M-DS2                     | 2         | 0.31%   |
| Gigabyte F2A88XM-HD3P                  | 2         | 0.31%   |
| Gigabyte F2A68HM-DS2                   | 2         | 0.31%   |
| Gigabyte B250-HD3                      | 2         | 0.31%   |
| Fujitsu FMVU09001                      | 2         | 0.31%   |
| Dell OptiPlex 9020                     | 2         | 0.31%   |
| Dell OptiPlex 7050                     | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 40        | 6.22%   |
| Acer Aspire        | 38        | 5.91%   |
| Dell OptiPlex      | 18        | 2.8%    |
| ASUS VivoBook      | 16        | 2.49%   |
| Lenovo IdeaPad     | 13        | 2.02%   |
| HP Pavilion        | 12        | 1.87%   |
| Dell Inspiron      | 11        | 1.71%   |
| HP Laptop          | 9         | 1.4%    |
| Dell Precision     | 9         | 1.4%    |
| Dell Latitude      | 9         | 1.4%    |
| ASUS PRIME         | 9         | 1.4%    |
| ASUS All           | 9         | 1.4%    |
| ASUS ROG           | 8         | 1.24%   |
| ASUS ASUS          | 8         | 1.24%   |
| Acer Veriton       | 8         | 1.24%   |
| Lenovo Yoga        | 7         | 1.09%   |
| HP Compaq          | 7         | 1.09%   |
| Dell Vostro        | 7         | 1.09%   |
| ASUS TUF           | 7         | 1.09%   |
| Acer Swift         | 7         | 1.09%   |
| Unknown            | 7         | 1.09%   |
| Dell PowerEdge     | 6         | 0.93%   |
| ASUS ZenBook       | 6         | 0.93%   |
| ASRock B450        | 6         | 0.93%   |
| Lenovo ThinkBook   | 5         | 0.78%   |
| Acer Nitro         | 5         | 0.78%   |
| Toshiba Satellite  | 4         | 0.62%   |
| Lenovo MIIX        | 4         | 0.62%   |
| HUAWEI BOHB-WAX9   | 4         | 0.62%   |
| HP ProDesk         | 4         | 0.62%   |
| HP EliteDesk       | 4         | 0.62%   |
| HP EliteBook       | 4         | 0.62%   |
| ASUS M5A78L-M      | 4         | 0.62%   |
| ASRock B450M       | 4         | 0.62%   |
| Acer TravelMate    | 4         | 0.62%   |
| Lenovo Z50-70      | 3         | 0.47%   |
| Lenovo ThinkCentre | 3         | 0.47%   |
| HP ENVY            | 3         | 0.47%   |
| ASUS P8H61-M       | 3         | 0.47%   |
| ASRock X570        | 3         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 64        | 9.95%   |
| 2020    | 59        | 9.18%   |
| 2019    | 54        | 8.4%    |
| 2021    | 49        | 7.62%   |
| 2016    | 49        | 7.62%   |
| 2012    | 48        | 7.47%   |
| 2014    | 46        | 7.15%   |
| 2017    | 45        | 7%      |
| 2013    | 41        | 6.38%   |
| 2011    | 36        | 5.6%    |
| 2015    | 30        | 4.67%   |
| 2023    | 28        | 4.35%   |
| 2022    | 24        | 3.73%   |
| 2010    | 19        | 2.95%   |
| 2008    | 18        | 2.8%    |
| 2009    | 17        | 2.64%   |
| 2007    | 5         | 0.78%   |
| Unknown | 4         | 0.62%   |
| 2024    | 3         | 0.47%   |
| 2006    | 3         | 0.47%   |
| 2005    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 328       | 51.01%  |
| Desktop        | 252       | 39.19%  |
| All in one     | 16        | 2.49%   |
| Convertible    | 12        | 1.87%   |
| Mini pc        | 11        | 1.71%   |
| Tablet         | 10        | 1.56%   |
| Server         | 9         | 1.4%    |
| System on chip | 4         | 0.62%   |
| Other          | 1         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 594       | 91.24%  |
| Enabled  | 57        | 8.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 641       | 99.69%  |
| Yes  | 2         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 155       | 23.56%  |
| 16.01-24.0      | 137       | 20.82%  |
| 3.01-4.0        | 119       | 18.09%  |
| 8.01-16.0       | 119       | 18.09%  |
| 32.01-64.0      | 67        | 10.18%  |
| 1.01-2.0        | 22        | 3.34%   |
| 24.01-32.0      | 14        | 2.13%   |
| 64.01-256.0     | 14        | 2.13%   |
| More than 256.0 | 6         | 0.91%   |
| 2.01-3.0        | 3         | 0.46%   |
| 0.51-1.0        | 2         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 230       | 31.68%  |
| 2.01-3.0        | 212       | 29.2%   |
| 4.01-8.0        | 114       | 15.7%   |
| 3.01-4.0        | 100       | 13.77%  |
| 8.01-16.0       | 32        | 4.41%   |
| 0.51-1.0        | 25        | 3.44%   |
| 16.01-24.0      | 4         | 0.55%   |
| 64.01-256.0     | 3         | 0.41%   |
| 0.01-0.5        | 3         | 0.41%   |
| More than 256.0 | 2         | 0.28%   |
| 24.01-32.0      | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 387       | 57.25%  |
| 2      | 171       | 25.3%   |
| 3      | 60        | 8.88%   |
| 4      | 19        | 2.81%   |
| 5      | 12        | 1.78%   |
| 0      | 10        | 1.48%   |
| 6      | 6         | 0.89%   |
| 17     | 4         | 0.59%   |
| 10     | 2         | 0.3%    |
| 7      | 2         | 0.3%    |
| 51     | 1         | 0.15%   |
| 32     | 1         | 0.15%   |
| 9      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 469       | 72.38%  |
| Yes       | 179       | 27.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 535       | 82.95%  |
| No        | 110       | 17.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 505       | 77.45%  |
| No        | 147       | 22.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 422       | 64.33%  |
| No        | 234       | 35.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Thailand | 643       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Bangkok                  | 286       | 41.27%  |
| Chiang Mai               | 50        | 7.22%   |
| Phuket                   | 24        | 3.46%   |
| Khon Kaen                | 19        | 2.74%   |
| Nonthaburi               | 17        | 2.45%   |
| Nakhon Ratchasima        | 16        | 2.31%   |
| Nakhon Pathom            | 16        | 2.31%   |
| Bang Lamung              | 15        | 2.16%   |
| Chon Buri                | 13        | 1.88%   |
| Ban Nong Sala            | 13        | 1.88%   |
| Mueang Samut Prakan      | 8         | 1.15%   |
| Songkhla                 | 7         | 1.01%   |
| Pattaya                  | 7         | 1.01%   |
| Surin                    | 6         | 0.87%   |
| Surat Thani              | 6         | 0.87%   |
| Hua Hin                  | 6         | 0.87%   |
| Si Racha                 | 5         | 0.72%   |
| Hat Yai                  | 5         | 0.72%   |
| Ban Du                   | 5         | 0.72%   |
| Si Sa Ket                | 4         | 0.58%   |
| Phitsanulok              | 4         | 0.58%   |
| Pathum Thani             | 4         | 0.58%   |
| Pak Kret                 | 4         | 0.58%   |
| Lampang                  | 4         | 0.58%   |
| Khlong Luang             | 4         | 0.58%   |
| Ban Phan Don             | 4         | 0.58%   |
| Suan Luang               | 3         | 0.43%   |
| Rayong                   | 3         | 0.43%   |
| Phetchaburi              | 3         | 0.43%   |
| Maha Sarakham            | 3         | 0.43%   |
| Lat Krabang              | 3         | 0.43%   |
| Ko Samui                 | 3         | 0.43%   |
| Chiang Rai               | 3         | 0.43%   |
| Bang Khae                | 3         | 0.43%   |
| Bang Bon                 | 3         | 0.43%   |
| Ban Yang Sam Ton         | 3         | 0.43%   |
| Samut Prakan             | 2         | 0.29%   |
| Salaya                   | 2         | 0.29%   |
| Phra Nakhon Si Ayutthaya | 2         | 0.29%   |
| Phetchabun               | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 183       | 287    | 18.83%  |
| Seagate                     | 135       | 219    | 13.89%  |
| Samsung Electronics         | 112       | 165    | 11.52%  |
| SanDisk                     | 73        | 111    | 7.51%   |
| Toshiba                     | 55        | 110    | 5.66%   |
| Kingston                    | 46        | 58     | 4.73%   |
| Unknown                     | 42        | 56     | 4.32%   |
| Intel                       | 25        | 27     | 2.57%   |
| SK hynix                    | 22        | 102    | 2.26%   |
| Micron Technology           | 20        | 30     | 2.06%   |
| Hitachi                     | 17        | 18     | 1.75%   |
| Crucial                     | 16        | 18     | 1.65%   |
| HGST                        | 15        | 24     | 1.54%   |
| China                       | 13        | 19     | 1.34%   |
| HS-SSD-C100                 | 12        | 26     | 1.23%   |
| Apple                       | 11        | 11     | 1.13%   |
| Apacer                      | 11        | 13     | 1.13%   |
| Transcend                   | 9         | 10     | 0.93%   |
| Silicon Motion              | 8         | 12     | 0.82%   |
| Hikvision                   | 8         | 8      | 0.82%   |
| MAXIO Technology (Hangzhou) | 7         | 8      | 0.72%   |
| SPCC                        | 6         | 6      | 0.62%   |
| Phison Electronics          | 6         | 10     | 0.62%   |
| Phison                      | 6         | 11     | 0.62%   |
| Realtek Semiconductor       | 5         | 5      | 0.51%   |
| A-DATA Technology           | 5         | 8      | 0.51%   |
| USB3.0                      | 4         | 6      | 0.41%   |
| TO Exter                    | 4         | 4      | 0.41%   |
| Plextor                     | 4         | 4      | 0.41%   |
| Pioneer                     | 4         | 4      | 0.41%   |
| Lexar                       | 4         | 5      | 0.41%   |
| KIOXIA                      | 4         | 7      | 0.41%   |
| KingSpec                    | 4         | 6      | 0.41%   |
| JMicron Technology          | 4         | 4      | 0.41%   |
| GALAX                       | 4         | 4      | 0.41%   |
| Colorful                    | 4         | 8      | 0.41%   |
| Kingston Technology Company | 3         | 3      | 0.31%   |
| Hewlett-Packard             | 3         | 5      | 0.31%   |
| Fujitsu                     | 3         | 5      | 0.31%   |
| External                    | 3         | 3      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB                      | 11        | 1.02%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 11        | 1.02%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 9         | 0.84%   |
| Unknown MMC Card  32GB                               | 9         | 0.84%   |
| Toshiba MQ04ABF100 1TB                               | 9         | 0.84%   |
| Toshiba MQ01ABD100 1TB                               | 9         | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB                       | 9         | 0.84%   |
| Seagate ST1000DM003-1ER162 1TB                       | 9         | 0.84%   |
| Kingston SA400S37240G 240GB SSD                      | 9         | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 8         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB                      | 8         | 0.74%   |
| SanDisk NVMe SSD Drive 1TB                           | 8         | 0.74%   |
| Crucial CT500MX500SSD1 500GB                         | 8         | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 7         | 0.65%   |
| Unknown MMC Card  64GB                               | 7         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB                       | 7         | 0.65%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 6         | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 6         | 0.56%   |
| WDC WD10EZEX-00WN4A0 1TB                             | 6         | 0.56%   |
| Unknown SD/MMC/MS PRO 128GB                          | 6         | 0.56%   |
| Seagate ST2000VX008-2E3164 2TB                       | 6         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 6         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 6         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 6         | 0.56%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 6         | 0.56%   |
| Kingston SUV400S37120G 120GB SSD                     | 6         | 0.56%   |
| WDC WD20EZAZ-00GGJB0 2TB                             | 5         | 0.46%   |
| WDC WD10EZEX-60WN4A0 1TB                             | 5         | 0.46%   |
| Toshiba DT01ACA100 1TB                               | 5         | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 5         | 0.46%   |
| SanDisk NVMe SSD Drive 250GB                         | 5         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 5         | 0.46%   |
| Samsung HD103SJ 1TB                                  | 5         | 0.46%   |
| HS-SSD-C100 240G                                     | 5         | 0.46%   |
| HS-SSD-C100 120G                                     | 5         | 0.46%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 4         | 0.37%   |
| WDC WD5000AAKX-001CA0 500GB                          | 4         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 4         | 0.37%   |
| USB3.0 Super Speed 500GB SSD                         | 4         | 0.37%   |
| Unknown MMC Card  128GB                              | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 130       | 208    | 34.76%  |
| WDC                 | 124       | 189    | 33.16%  |
| Toshiba             | 46        | 97     | 12.3%   |
| Hitachi             | 17        | 18     | 4.55%   |
| Samsung Electronics | 15        | 23     | 4.01%   |
| HGST                | 15        | 24     | 4.01%   |
| Unknown             | 7         | 12     | 1.87%   |
| TO Exter            | 4         | 4      | 1.07%   |
| JMicron Technology  | 3         | 3      | 0.8%    |
| Fujitsu             | 3         | 5      | 0.8%    |
| External            | 3         | 3      | 0.8%    |
| Hewlett-Packard     | 2         | 4      | 0.53%   |
| Apple               | 2         | 2      | 0.53%   |
| Initio              | 1         | 1      | 0.27%   |
| IBM-ESXS            | 1         | 2      | 0.27%   |
| ASMedia             | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 50        | 71     | 16.61%  |
| Samsung Electronics | 44        | 65     | 14.62%  |
| Kingston            | 29        | 35     | 9.63%   |
| SanDisk             | 26        | 42     | 8.64%   |
| Crucial             | 16        | 18     | 5.32%   |
| China               | 13        | 19     | 4.32%   |
| Apacer              | 11        | 13     | 3.65%   |
| Intel               | 8         | 8      | 2.66%   |
| Apple               | 8         | 8      | 2.66%   |
| SK hynix            | 7         | 68     | 2.33%   |
| Transcend           | 6         | 7      | 1.99%   |
| SPCC                | 6         | 6      | 1.99%   |
| Micron Technology   | 6         | 7      | 1.99%   |
| Hikvision           | 6         | 6      | 1.99%   |
| USB3.0              | 4         | 6      | 1.33%   |
| Plextor             | 4         | 4      | 1.33%   |
| Pioneer             | 4         | 4      | 1.33%   |
| Lexar               | 4         | 5      | 1.33%   |
| KingSpec            | 4         | 6      | 1.33%   |
| GALAX               | 4         | 4      | 1.33%   |
| Colorful            | 3         | 7      | 1%      |
| A-DATA Technology   | 3         | 6      | 1%      |
| walram              | 2         | 2      | 0.66%   |
| Seagate             | 2         | 2      | 0.66%   |
| PNY                 | 2         | 3      | 0.66%   |
| LITEON              | 2         | 3      | 0.66%   |
| Kingmax             | 2         | 9      | 0.66%   |
| Intenso             | 2         | 13     | 0.66%   |
| Acer                | 2         | 6      | 0.66%   |
| ZADAK               | 1         | 1      | 0.33%   |
| WDC WDS             | 1         | 1      | 0.33%   |
| Verbatim            | 1         | 1      | 0.33%   |
| Toshiba             | 1         | 1      | 0.33%   |
| Teelkoou            | 1         | 1      | 0.33%   |
| Team                | 1         | 1      | 0.33%   |
| TARGET              | 1         | 1      | 0.33%   |
| StoreJet            | 1         | 1      | 0.33%   |
| SPCC M.2            | 1         | 1      | 0.33%   |
| OCZ                 | 1         | 1      | 0.33%   |
| MSI                 | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 305       | 596    | 35.47%  |
| SSD     | 257       | 474    | 29.88%  |
| NVMe    | 240       | 370    | 27.91%  |
| MMC     | 33        | 42     | 3.84%   |
| Unknown | 25        | 44     | 2.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 461       | 1044   | 59.18%  |
| NVMe | 240       | 361    | 30.81%  |
| SAS  | 45        | 79     | 5.78%   |
| MMC  | 33        | 42     | 4.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 320       | 522    | 52.72%  |
| 0.51-1.0   | 191       | 278    | 31.47%  |
| 1.01-2.0   | 59        | 89     | 9.72%   |
| 3.01-4.0   | 19        | 129    | 3.13%   |
| 2.01-3.0   | 8         | 17     | 1.32%   |
| 4.01-10.0  | 8         | 24     | 1.32%   |
| 10.01-20.0 | 2         | 11     | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 167       | 23.96%  |
| 251-500        | 138       | 19.8%   |
| 501-1000       | 104       | 14.92%  |
| 1-20           | 67        | 9.61%   |
| 51-100         | 55        | 7.89%   |
| 1001-2000      | 52        | 7.46%   |
| 21-50          | 37        | 5.31%   |
| 2001-3000      | 29        | 4.16%   |
| More than 3000 | 24        | 3.44%   |
| Unknown        | 24        | 3.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 281       | 39.47%  |
| 21-50          | 119       | 16.71%  |
| 101-250        | 86        | 12.08%  |
| 51-100         | 69        | 9.69%   |
| 251-500        | 56        | 7.87%   |
| 501-1000       | 40        | 5.62%   |
| Unknown        | 24        | 3.37%   |
| 1001-2000      | 19        | 2.67%   |
| More than 3000 | 13        | 1.83%   |
| 2001-3000      | 5         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 3         | 3      | 4.84%   |
| USB3.0 Super Speed 500GB SSD             | 2         | 4      | 3.23%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 3.23%   |
| Seagate ST500DM002-1BD14 500GB           | 2         | 3      | 3.23%   |
| Seagate ST3500418AS 500GB                | 2         | 3      | 3.23%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 3.23%   |
| Samsung Electronics SSD 830 Series 128GB | 2         | 2      | 3.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 1.61%   |
| WDC WD7500BPVT-00HXZT3 752GB             | 1         | 1      | 1.61%   |
| WDC WD6402AAEX-00Y9A0 640GB              | 1         | 1      | 1.61%   |
| WDC WD20EZRX-00DC0B0 2TB                 | 1         | 1      | 1.61%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 1.61%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 3      | 1.61%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1         | 1      | 1.61%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1         | 1      | 1.61%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 1         | 1      | 1.61%   |
| WDC WD10EARX-00N0YB0 1TB                 | 1         | 1      | 1.61%   |
| WDC WD1002FAEX-00Y9A0 1TB                | 1         | 1      | 1.61%   |
| WDC WD Blue SA510 2.5 500GB              | 1         | 1      | 1.61%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 1.61%   |
| Toshiba MK6475GSX 640GB                  | 1         | 1      | 1.61%   |
| Toshiba HDWL110 1TB                      | 1         | 1      | 1.61%   |
| TARGET SSD 128G                          | 1         | 1      | 1.61%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 1.61%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 1.61%   |
| Seagate ST9120822AS 120GB                | 1         | 1      | 1.61%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 1.61%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 1.61%   |
| Seagate ST500LM000-SSHD-8GB              | 1         | 1      | 1.61%   |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1      | 1.61%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 1.61%   |
| Seagate ST2000DM006-2DM164 2TB           | 1         | 1      | 1.61%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB      | 1         | 1      | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 1.61%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1         | 1      | 1.61%   |
| SanDisk SDSSDX240GG25 240GB              | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 870 QVO 1TB      | 1         | 1      | 1.61%   |
| Samsung Electronics HM160HI 160GB        | 1         | 2      | 1.61%   |
| Samsung Electronics HD322GJ 320GB        | 1         | 2      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 31.15%  |
| WDC                 | 14        | 17     | 22.95%  |
| Samsung Electronics | 7         | 10     | 11.48%  |
| Toshiba             | 5         | 5      | 8.2%    |
| HGST                | 4         | 4      | 6.56%   |
| USB3.0              | 2         | 4      | 3.28%   |
| Kingston            | 2         | 2      | 3.28%   |
| Apple               | 2         | 2      | 3.28%   |
| TARGET              | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| SanDisk             | 1         | 1      | 1.64%   |
| Intel               | 1         | 1      | 1.64%   |
| Hitachi             | 1         | 1      | 1.64%   |
| Colorful            | 1         | 4      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 42.22%  |
| WDC                 | 12        | 15     | 26.67%  |
| Toshiba             | 5         | 5      | 11.11%  |
| Samsung Electronics | 4         | 7      | 8.89%   |
| HGST                | 4         | 4      | 8.89%   |
| Hitachi             | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 53     | 74.14%  |
| SSD  | 14        | 20     | 24.14%  |
| NVMe | 1         | 1      | 1.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 2         | 2      | 50%     |
| WDC WD30EFRX-68EUZN0 3TB        | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 401       | 852    | 56.64%  |
| Works    | 247       | 596    | 34.89%  |
| Malfunc  | 56        | 74     | 7.91%   |
| Failed   | 4         | 4      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 411       | 49.76%  |
| AMD                          | 119       | 14.41%  |
| SanDisk                      | 70        | 8.47%   |
| Samsung Electronics          | 65        | 7.87%   |
| Kingston Technology Company  | 20        | 2.42%   |
| SK hynix                     | 15        | 1.82%   |
| ASMedia Technology           | 15        | 1.82%   |
| Micron Technology            | 14        | 1.69%   |
| Phison Electronics           | 13        | 1.57%   |
| Nvidia                       | 13        | 1.57%   |
| MAXIO Technology (Hangzhou)  | 10        | 1.21%   |
| Silicon Motion               | 9         | 1.09%   |
| Toshiba America Info Systems | 8         | 0.97%   |
| Broadcom / LSI               | 8         | 0.97%   |
| Realtek Semiconductor        | 5         | 0.61%   |
| Marvell Technology Group     | 4         | 0.48%   |
| KIOXIA                       | 4         | 0.48%   |
| Yangtze Memory Technologies  | 3         | 0.36%   |
| VIA Technologies             | 3         | 0.36%   |
| LSI Logic / Symbios Logic    | 3         | 0.36%   |
| ADATA Technology             | 3         | 0.36%   |
| Shenzhen Longsys Electronics | 2         | 0.24%   |
| Micron/Crucial Technology    | 2         | 0.24%   |
| JMicron Technology           | 2         | 0.24%   |
| Transcend                    | 1         | 0.12%   |
| O2 Micro                     | 1         | 0.12%   |
| Lite-On Technology           | 1         | 0.12%   |
| Apple                        | 1         | 0.12%   |
| Unknown                      | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 84        | 9.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 33        | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 29        | 3.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 24        | 2.6%    |
| AMD 400 Series Chipset SATA Controller                                           | 22        | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 2.28%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 20        | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 17        | 1.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 15        | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.63%   |
| AMD 500 Series Chipset SATA Controller                                           | 14        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 13        | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 12        | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12        | 1.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 12        | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 11        | 1.19%   |
| Intel SATA Controller [RAID mode]                                                | 11        | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 10        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 10        | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 1.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 10        | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 9         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 9         | 0.98%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 8         | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 8         | 0.87%   |
| Intel SSD 660P Series                                                            | 8         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 7         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 6         | 0.65%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 473       | 57.19%  |
| NVMe | 244       | 29.5%   |
| IDE  | 57        | 6.89%   |
| RAID | 49        | 5.93%   |
| SAS  | 2         | 0.24%   |
| SCSI | 2         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 483       | 75.12%  |
| AMD          | 155       | 24.11%  |
| ARM          | 4         | 0.62%   |
| CentaurHauls | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.24%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 1.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 7         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 1.08%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 6         | 0.93%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 5         | 0.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.77%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.77%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.77%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.77%   |
| AMD EPYC 9534 64-Core Processor               | 5         | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.62%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.62%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 0.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.62%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.62%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 0.62%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 4         | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 0.62%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.46%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.46%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.46%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 3         | 0.46%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 140       | 21.71%  |
| Intel Core i7           | 123       | 19.07%  |
| Intel Core i3           | 62        | 9.61%   |
| AMD Ryzen 5             | 52        | 8.06%   |
| Other                   | 42        | 6.51%   |
| AMD Ryzen 7             | 26        | 4.03%   |
| Intel Celeron           | 24        | 3.72%   |
| Intel Xeon              | 21        | 3.26%   |
| Intel Core 2 Duo        | 21        | 3.26%   |
| Intel Pentium           | 16        | 2.48%   |
| Intel Atom              | 14        | 2.17%   |
| AMD Ryzen 9             | 12        | 1.86%   |
| AMD Ryzen 3             | 9         | 1.4%    |
| AMD FX                  | 7         | 1.09%   |
| Intel Core i9           | 6         | 0.93%   |
| AMD A10                 | 6         | 0.93%   |
| Intel Core 2 Quad       | 5         | 0.78%   |
| AMD EPYC                | 5         | 0.78%   |
| AMD Athlon II X2        | 5         | 0.78%   |
| AMD A4                  | 5         | 0.78%   |
| AMD Ryzen 7 PRO         | 4         | 0.62%   |
| AMD Athlon 64 X2        | 4         | 0.62%   |
| Intel Pentium Silver    | 3         | 0.47%   |
| Intel Pentium Dual-Core | 3         | 0.47%   |
| AMD Athlon              | 3         | 0.47%   |
| AMD A6                  | 3         | 0.47%   |
| Intel Pentium Dual      | 2         | 0.31%   |
| Intel Core m3           | 2         | 0.31%   |
| Intel Core              | 2         | 0.31%   |
| AMD Phenom II X6        | 2         | 0.31%   |
| AMD Phenom II X4        | 2         | 0.31%   |
| AMD E2                  | 2         | 0.31%   |
| AMD A8                  | 2         | 0.31%   |
| Intel Xeon Gold         | 1         | 0.16%   |
| Intel Pentium Gold      | 1         | 0.16%   |
| Intel Pentium D         | 1         | 0.16%   |
| Intel Pentium 4         | 1         | 0.16%   |
| CentaurHauls VIA Eden   | 1         | 0.16%   |
| AMD Turion 64 X2 Mobile | 1         | 0.16%   |
| AMD Ryzen 5 PRO         | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 255       | 39.41%  |
| 2       | 219       | 33.85%  |
| 6       | 76        | 11.75%  |
| 8       | 50        | 7.73%   |
| 12      | 12        | 1.85%   |
| 16      | 7         | 1.08%   |
| 14      | 7         | 1.08%   |
| 1       | 6         | 0.93%   |
| 128     | 5         | 0.77%   |
| 24      | 2         | 0.31%   |
| 10      | 2         | 0.31%   |
| 3       | 2         | 0.31%   |
| 40      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |
| 5       | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 628       | 97.67%  |
| 2       | 14        | 2.18%   |
| Unknown | 1         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 457       | 70.63%  |
| 1       | 189       | 29.21%  |
| Unknown | 1         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 635       | 98.76%  |
| Unknown        | 7         | 1.09%   |
| 32-bit         | 1         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 291       | 42.86%  |
| 0x306c3    | 25        | 3.68%   |
| 0x206a7    | 24        | 3.53%   |
| 0x306a9    | 23        | 3.39%   |
| 0x506e3    | 16        | 2.36%   |
| 0x40651    | 15        | 2.21%   |
| 0x906ea    | 14        | 2.06%   |
| 0x806ea    | 13        | 1.91%   |
| 0x1067a    | 13        | 1.91%   |
| 0x806e9    | 11        | 1.62%   |
| 0x906e9    | 10        | 1.47%   |
| 0x806ec    | 10        | 1.47%   |
| 0x20655    | 10        | 1.47%   |
| 0x806c1    | 9         | 1.33%   |
| 0x0a50000c | 9         | 1.33%   |
| 0x406e3    | 7         | 1.03%   |
| 0x406c4    | 7         | 1.03%   |
| 0x406c3    | 6         | 0.88%   |
| 0x08600106 | 6         | 0.88%   |
| 0x08108102 | 6         | 0.88%   |
| 0x0800820d | 6         | 0.88%   |
| 0xa0652    | 5         | 0.74%   |
| 0x30678    | 5         | 0.74%   |
| 0x0810100b | 5         | 0.74%   |
| 0x06001119 | 5         | 0.74%   |
| 0x706a1    | 4         | 0.59%   |
| 0x20652    | 4         | 0.59%   |
| 0x0a101116 | 4         | 0.59%   |
| 0x08701021 | 4         | 0.59%   |
| 0x08608103 | 4         | 0.59%   |
| 0x08108109 | 4         | 0.59%   |
| 0x010000c8 | 4         | 0.59%   |
| 0xb06a2    | 3         | 0.44%   |
| 0xa0655    | 3         | 0.44%   |
| 0x906ec    | 3         | 0.44%   |
| 0x906c0    | 3         | 0.44%   |
| 0x706a8    | 3         | 0.44%   |
| 0x6fd      | 3         | 0.44%   |
| 0x406f1    | 3         | 0.44%   |
| 0x106e5    | 3         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 101       | 15.66%  |
| Haswell           | 69        | 10.7%   |
| Skylake           | 52        | 8.06%   |
| IvyBridge         | 44        | 6.82%   |
| Unknown           | 40        | 6.2%    |
| SandyBridge       | 37        | 5.74%   |
| Zen 2             | 30        | 4.65%   |
| Zen+              | 26        | 4.03%   |
| Silvermont        | 25        | 3.88%   |
| Penryn            | 24        | 3.72%   |
| CometLake         | 23        | 3.57%   |
| Zen 3             | 21        | 3.26%   |
| TigerLake         | 18        | 2.79%   |
| Westmere          | 17        | 2.64%   |
| Zen               | 13        | 2.02%   |
| Piledriver        | 10        | 1.55%   |
| Broadwell         | 10        | 1.55%   |
| K10               | 9         | 1.4%    |
| Goldmont plus     | 9         | 1.4%    |
| Core              | 9         | 1.4%    |
| Alderlake Hybrid  | 9         | 1.4%    |
| IceLake           | 7         | 1.09%   |
| Excavator         | 6         | 0.93%   |
| K8 Hammer         | 5         | 0.78%   |
| Tremont           | 4         | 0.62%   |
| Goldmont          | 4         | 0.62%   |
| Bonnell           | 4         | 0.62%   |
| Puma              | 3         | 0.47%   |
| Nehalem           | 3         | 0.47%   |
| Steamroller       | 2         | 0.31%   |
| NetBurst          | 2         | 0.31%   |
| Meteorlake Hybrid | 2         | 0.31%   |
| Bobcat            | 2         | 0.31%   |
| K10 Llano         | 1         | 0.16%   |
| Jaguar            | 1         | 0.16%   |
| Gracemont         | 1         | 0.16%   |
| CannonLake        | 1         | 0.16%   |
| Bulldozer         | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 373       | 46.57%  |
| Nvidia                     | 243       | 30.34%  |
| AMD                        | 173       | 21.6%   |
| Matrox Electronics Systems | 7         | 0.87%   |
| VIA Technologies           | 2         | 0.25%   |
| ASPEED Technology          | 2         | 0.25%   |
| ATI Technologies           | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 3.52%   |
| Intel HD Graphics 530                                                                    | 25        | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.79%   |
| Intel UHD Graphics 620                                                                   | 18        | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 2.06%   |
| Intel HD Graphics 620                                                                    | 16        | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 1.7%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 14        | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.33%   |
| Intel HD Graphics 630                                                                    | 10        | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.97%   |
| AMD Lucienne                                                                             | 8         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7         | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 0.85%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.85%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.73%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 236       | 35.98%  |
| 1 x AMD              | 130       | 19.82%  |
| 1 x Nvidia           | 112       | 17.07%  |
| Intel + Nvidia       | 107       | 16.31%  |
| AMD + Nvidia         | 19        | 2.9%    |
| Intel + AMD          | 16        | 2.44%   |
| 2 x AMD              | 12        | 1.83%   |
| 1 x Matrox           | 7         | 1.07%   |
| Other                | 4         | 0.61%   |
| Intel + 2 x Nvidia   | 3         | 0.46%   |
| 1 x VIA              | 2         | 0.3%    |
| 3 x Nvidia           | 1         | 0.15%   |
| 2 x Nvidia           | 1         | 0.15%   |
| 2 x Intel            | 1         | 0.15%   |
| 2 x AMD + 2 x Nvidia | 1         | 0.15%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.15%   |
| Nvidia + ASPEED      | 1         | 0.15%   |
| 1 x ASPEED           | 1         | 0.15%   |
| AMD + 2 x Nvidia     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 515       | 77.33%  |
| Proprietary | 121       | 18.17%  |
| Unknown     | 30        | 4.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 385       | 57.89%  |
| 1.01-2.0   | 75        | 11.28%  |
| 0.01-0.5   | 62        | 9.32%   |
| 3.01-4.0   | 60        | 9.02%   |
| 0.51-1.0   | 36        | 5.41%   |
| 7.01-8.0   | 27        | 4.06%   |
| 5.01-6.0   | 12        | 1.8%    |
| 8.01-16.0  | 3         | 0.45%   |
| 2.01-3.0   | 2         | 0.3%    |
| 16.01-24.0 | 2         | 0.3%    |
| 4.01-5.0   | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 95        | 13.67%  |
| AU Optronics            | 87        | 12.52%  |
| Chimei Innolux          | 58        | 8.35%   |
| BOE                     | 54        | 7.77%   |
| Acer                    | 54        | 7.77%   |
| Goldstar                | 48        | 6.91%   |
| LG Display              | 42        | 6.04%   |
| Dell                    | 42        | 6.04%   |
| Hewlett-Packard         | 22        | 3.17%   |
| AOC                     | 20        | 2.88%   |
| Apple                   | 18        | 2.59%   |
| Lenovo                  | 14        | 2.01%   |
| Sharp                   | 12        | 1.73%   |
| PANDA                   | 12        | 1.73%   |
| BenQ                    | 9         | 1.29%   |
| ViewSonic               | 8         | 1.15%   |
| MSI                     | 6         | 0.86%   |
| LG Electronics          | 6         | 0.86%   |
| Philips                 | 5         | 0.72%   |
| InfoVision              | 5         | 0.72%   |
| Unknown (XXX)           | 4         | 0.58%   |
| RTK                     | 4         | 0.58%   |
| MStar                   | 4         | 0.58%   |
| Chi Mei Optoelectronics | 4         | 0.58%   |
| SGT                     | 3         | 0.43%   |
| Mi                      | 3         | 0.43%   |
| ASUSTek Computer        | 3         | 0.43%   |
| Ancor Communications    | 3         | 0.43%   |
| Valve                   | 2         | 0.29%   |
| Toshiba                 | 2         | 0.29%   |
| SKY                     | 2         | 0.29%   |
| Microstep               | 2         | 0.29%   |
| IOD                     | 2         | 0.29%   |
| HJC                     | 2         | 0.29%   |
| Fujitsu Siemens         | 2         | 0.29%   |
| Fujitsu                 | 2         | 0.29%   |
| CS_                     | 2         | 0.29%   |
| CSO                     | 2         | 0.29%   |
| ___                     | 1         | 0.14%   |
| UTV                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.84%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.84%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.7%    |
| Acer k222HQL ACR0512 1920x1080 477x268mm 21.5-inch                    | 5         | 0.7%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.56%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.56%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 4         | 0.56%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 4         | 0.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.56%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.56%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 4         | 0.56%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 4         | 0.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.42%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 3         | 0.42%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.42%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                      | 3         | 0.42%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 3         | 0.42%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.42%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch        | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.42%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3         | 0.42%   |
| AOC 2381 AOC2381 1920x1080 509x286mm 23.0-inch                        | 3         | 0.42%   |
| Acer S200HQL  ACR0359 1600x900 430x240mm 19.4-inch                    | 3         | 0.42%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2         | 0.28%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.28%   |
| Sharp LQ133M1JW28 SHP1483 1920x1080 294x165mm 13.3-inch               | 2         | 0.28%   |
| SGT '' SGT2380 1920x1080 530x290mm 23.8-inch                          | 2         | 0.28%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2         | 0.28%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 2         | 0.28%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2         | 0.28%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2         | 0.28%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch     | 2         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 301       | 45.4%   |
| 1366x768 (WXGA)    | 128       | 19.31%  |
| 3840x2160 (4K)     | 45        | 6.79%   |
| 1600x900 (HD+)     | 32        | 4.83%   |
| 2560x1440 (QHD)    | 27        | 4.07%   |
| 1440x900 (WXGA+)   | 18        | 2.71%   |
| 1920x1200 (WUXGA)  | 14        | 2.11%   |
| 1680x1050 (WSXGA+) | 10        | 1.51%   |
| 1280x1024 (SXGA)   | 10        | 1.51%   |
| 2880x1800          | 9         | 1.36%   |
| 1360x768           | 9         | 1.36%   |
| 2560x1080          | 8         | 1.21%   |
| 2560x1600          | 7         | 1.06%   |
| Unknown            | 7         | 1.06%   |
| 1280x800 (WXGA)    | 6         | 0.9%    |
| 3840x2400          | 4         | 0.6%    |
| 3440x1440          | 3         | 0.45%   |
| 2160x1440          | 3         | 0.45%   |
| 1920x1280          | 3         | 0.45%   |
| 800x1280           | 2         | 0.3%    |
| 3840x1080          | 2         | 0.3%    |
| 3520x1080          | 2         | 0.3%    |
| 2256x1504          | 2         | 0.3%    |
| 1600x1200          | 2         | 0.3%    |
| 5120x1440          | 1         | 0.15%   |
| 2736x1824          | 1         | 0.15%   |
| 2732x768           | 1         | 0.15%   |
| 1920x515           | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |
| 1280x960           | 1         | 0.15%   |
| 1280x720 (HD)      | 1         | 0.15%   |
| 1024x768 (XGA)     | 1         | 0.15%   |
| 1024x600           | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 135       | 19.42%  |
| 14      | 70        | 10.07%  |
| 13      | 68        | 9.78%   |
| 23      | 58        | 8.35%   |
| 24      | 50        | 7.19%   |
| 21      | 43        | 6.19%   |
| 27      | 38        | 5.47%   |
| Unknown | 31        | 4.46%   |
| 18      | 24        | 3.45%   |
| 20      | 23        | 3.31%   |
| 19      | 22        | 3.17%   |
| 17      | 20        | 2.88%   |
| 11      | 16        | 2.3%    |
| 31      | 14        | 2.01%   |
| 16      | 14        | 2.01%   |
| 12      | 12        | 1.73%   |
| 34      | 9         | 1.29%   |
| 84      | 7         | 1.01%   |
| 22      | 7         | 1.01%   |
| 54      | 5         | 0.72%   |
| 26      | 5         | 0.72%   |
| 72      | 3         | 0.43%   |
| 52      | 3         | 0.43%   |
| 40      | 3         | 0.43%   |
| 46      | 2         | 0.29%   |
| 32      | 2         | 0.29%   |
| 10      | 2         | 0.29%   |
| 7       | 2         | 0.29%   |
| 86      | 1         | 0.14%   |
| 74      | 1         | 0.14%   |
| 60      | 1         | 0.14%   |
| 57      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 29      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 253       | 37.32%  |
| 501-600     | 140       | 20.65%  |
| 401-500     | 114       | 16.81%  |
| 201-300     | 64        | 9.44%   |
| Unknown     | 31        | 4.57%   |
| 351-400     | 21        | 3.1%    |
| 601-700     | 15        | 2.21%   |
| 1001-1500   | 12        | 1.77%   |
| 701-800     | 11        | 1.62%   |
| 1501-2000   | 10        | 1.47%   |
| 801-900     | 4         | 0.59%   |
| 1-100       | 2         | 0.29%   |
| 101-200     | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 477       | 77.31%  |
| 16/10   | 75        | 12.16%  |
| Unknown | 24        | 3.89%   |
| 5/4     | 11        | 1.78%   |
| 3/2     | 11        | 1.78%   |
| 21/9    | 9         | 1.46%   |
| 4/3     | 2         | 0.32%   |
| 2.00    | 2         | 0.32%   |
| 0.67    | 2         | 0.32%   |
| 0.56    | 2         | 0.32%   |
| 6/5     | 1         | 0.16%   |
| 3.73    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 135       | 19.57%  |
| 201-250        | 132       | 19.13%  |
| 81-90          | 115       | 16.67%  |
| 151-200        | 55        | 7.97%   |
| 301-350        | 41        | 5.94%   |
| Unknown        | 31        | 4.49%   |
| 141-150        | 27        | 3.91%   |
| 351-500        | 26        | 3.77%   |
| 71-80          | 23        | 3.33%   |
| More than 1000 | 21        | 3.04%   |
| 51-60          | 18        | 2.61%   |
| 251-300        | 15        | 2.17%   |
| 121-130        | 13        | 1.88%   |
| 61-70          | 12        | 1.74%   |
| 111-120        | 12        | 1.74%   |
| 501-1000       | 6         | 0.87%   |
| 131-140        | 4         | 0.58%   |
| 1-40           | 3         | 0.43%   |
| 91-100         | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 224       | 33.73%  |
| 121-160       | 170       | 25.6%   |
| 101-120       | 154       | 23.19%  |
| 161-240       | 52        | 7.83%   |
| Unknown       | 31        | 4.67%   |
| More than 240 | 19        | 2.86%   |
| 1-50          | 14        | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 522       | 77.91%  |
| 2     | 101       | 15.07%  |
| 0     | 35        | 5.22%   |
| 3     | 12        | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 375       | 37.2%   |
| Intel                             | 292       | 28.97%  |
| Qualcomm Atheros                  | 111       | 11.01%  |
| Broadcom                          | 58        | 5.75%   |
| MediaTek                          | 24        | 2.38%   |
| Ralink Technology                 | 16        | 1.59%   |
| TP-Link                           | 13        | 1.29%   |
| Broadcom Limited                  | 13        | 1.29%   |
| D-Link                            | 11        | 1.09%   |
| ASIX Electronics                  | 10        | 0.99%   |
| Nvidia                            | 9         | 0.89%   |
| Xiaomi                            | 6         | 0.6%    |
| Ralink                            | 6         | 0.6%    |
| Dell                              | 6         | 0.6%    |
| D-Link System                     | 6         | 0.6%    |
| Qualcomm                          | 5         | 0.5%    |
| Marvell Technology Group          | 5         | 0.5%    |
| Sierra Wireless                   | 4         | 0.4%    |
| Edimax Technology                 | 4         | 0.4%    |
| Samsung Electronics               | 3         | 0.3%    |
| Mercucys                          | 3         | 0.3%    |
| ASUSTek Computer                  | 3         | 0.3%    |
| VIA Technologies                  | 2         | 0.2%    |
| OPPO Electronics                  | 2         | 0.2%    |
| Huawei Technologies               | 2         | 0.2%    |
| Ericsson Business Mobile Networks | 2         | 0.2%    |
| vivo                              | 1         | 0.1%    |
| Raspberry Pi                      | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| QinHeng Electronics               | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| Lenovo                            | 1         | 0.1%    |
| JMicron Technology                | 1         | 0.1%    |
| IBM                               | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| BUFFALO                           | 1         | 0.1%    |
| AVM                               | 1         | 0.1%    |
| Aquantia                          | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 285       | 24.7%   |
| Intel Wi-Fi 6 AX200                                                    | 28        | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 24        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 22        | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 19        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 1.65%   |
| Intel Wireless 8260                                                    | 16        | 1.39%   |
| Intel Wireless 7265                                                    | 15        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 15        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 14        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.13%   |
| Intel Wireless 8265 / 8275                                             | 13        | 1.13%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 1.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 12        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 11        | 0.95%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 10        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 10        | 0.87%   |
| Intel I211 Gigabit Network Connection                                  | 10        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 10        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                          | 10        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 9         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 0.78%   |
| Intel Wireless 3160                                                    | 9         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 8         | 0.69%   |
| Realtek 802.11ac NIC                                                   | 7         | 0.61%   |
| Ralink MT7601U Wireless Adapter                                        | 7         | 0.61%   |
| Intel Wireless 7260                                                    | 7         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7         | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 7         | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 6         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 222       | 40.22%  |
| Realtek Semiconductor           | 95        | 17.21%  |
| Qualcomm Atheros                | 95        | 17.21%  |
| Broadcom                        | 32        | 5.8%    |
| MediaTek                        | 22        | 3.99%   |
| Ralink Technology               | 16        | 2.9%    |
| TP-Link                         | 13        | 2.36%   |
| D-Link                          | 11        | 1.99%   |
| Broadcom Limited                | 11        | 1.99%   |
| Ralink                          | 6         | 1.09%   |
| Sierra Wireless                 | 4         | 0.72%   |
| Qualcomm                        | 4         | 0.72%   |
| Edimax Technology               | 4         | 0.72%   |
| D-Link System                   | 4         | 0.72%   |
| Mercucys                        | 3         | 0.54%   |
| ASUSTek Computer                | 3         | 0.54%   |
| Qualcomm Atheros Communications | 1         | 0.18%   |
| Marvell Technology Group        | 1         | 0.18%   |
| Linksys                         | 1         | 0.18%   |
| Fibocom                         | 1         | 0.18%   |
| Dell                            | 1         | 0.18%   |
| BUFFALO                         | 1         | 0.18%   |
| AVM                             | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 28        | 5.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 24        | 4.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 22        | 3.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 19        | 3.42%   |
| Intel Wireless 8260                                                  | 16        | 2.88%   |
| Intel Wireless 7265                                                  | 15        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 15        | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 14        | 2.52%   |
| Intel Wireless 8265 / 8275                                           | 13        | 2.34%   |
| Intel Wi-Fi 6 AX201                                                  | 13        | 2.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 12        | 2.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 11        | 1.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 10        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 10        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 10        | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 10        | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                        | 10        | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 9         | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 9         | 1.62%   |
| Intel Wireless 3160                                                  | 9         | 1.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 8         | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 8         | 1.44%   |
| Realtek 802.11ac NIC                                                 | 7         | 1.26%   |
| Ralink MT7601U Wireless Adapter                                      | 7         | 1.26%   |
| Intel Wireless 7260                                                  | 7         | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 7         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 7         | 1.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 6         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 6         | 1.08%   |
| Intel Wireless 3165                                                  | 6         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 6         | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 5         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 5         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 5         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 0.9%    |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]        | 5         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 4         | 0.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 4         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 4         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 332       | 58.35%  |
| Intel                         | 125       | 21.97%  |
| Broadcom                      | 31        | 5.45%   |
| Qualcomm Atheros              | 24        | 4.22%   |
| ASIX Electronics              | 10        | 1.76%   |
| Nvidia                        | 9         | 1.58%   |
| Xiaomi                        | 6         | 1.05%   |
| Dell                          | 5         | 0.88%   |
| Marvell Technology Group      | 4         | 0.7%    |
| VIA Technologies              | 2         | 0.35%   |
| Samsung Electronics           | 2         | 0.35%   |
| OPPO Electronics              | 2         | 0.35%   |
| MediaTek                      | 2         | 0.35%   |
| D-Link System                 | 2         | 0.35%   |
| Broadcom Limited              | 2         | 0.35%   |
| vivo                          | 1         | 0.18%   |
| Raspberry Pi                  | 1         | 0.18%   |
| OnePlus Technology (Shenzhen) | 1         | 0.18%   |
| Motorola PCS                  | 1         | 0.18%   |
| Lenovo                        | 1         | 0.18%   |
| JMicron Technology            | 1         | 0.18%   |
| IBM                           | 1         | 0.18%   |
| Huawei Technologies           | 1         | 0.18%   |
| Aquantia                      | 1         | 0.18%   |
| Apple                         | 1         | 0.18%   |
| American Megatrends           | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 285       | 48.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 2.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.86%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 1.86%   |
| Intel I211 Gigabit Network Connection                                  | 10        | 1.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.02%   |
| Intel Ethernet Connection I217-V                                       | 6         | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                                  | 6         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.85%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.85%   |
| Dell iDRAC Virtual NIC                                                 | 5         | 0.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 5         | 0.85%   |
| Broadcom BCM57454 NetXtreme-E 10Gb/25Gb/40Gb/50Gb/100Gb Ethernet       | 5         | 0.85%   |
| Broadcom BCM57414 NetXtreme-E 10Gb/25Gb RDMA Ethernet Controller       | 5         | 0.85%   |
| Nvidia MCP61 Ethernet                                                  | 4         | 0.68%   |
| Intel Ethernet Connection I219-V                                       | 4         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.51%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.51%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 0.51%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 0.34%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.34%   |
| OPPO OnePlus Nord 4                                                    | 2         | 0.34%   |
| Nvidia MCP73 Ethernet                                                  | 2         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 533       | 51%     |
| WiFi     | 505       | 48.33%  |
| Modem    | 6         | 0.57%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 417       | 62.43%  |
| Ethernet | 251       | 37.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 333       | 51.39%  |
| 1     | 285       | 43.98%  |
| 0     | 12        | 1.85%   |
| 3     | 9         | 1.39%   |
| 8     | 5         | 0.77%   |
| 4     | 3         | 0.46%   |
| 5     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 461       | 68.81%  |
| Yes  | 209       | 31.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 187       | 42.89%  |
| Cambridge Silicon Radio         | 38        | 8.72%   |
| Realtek Semiconductor           | 32        | 7.34%   |
| IMC Networks                    | 31        | 7.11%   |
| Lite-On Technology              | 26        | 5.96%   |
| Qualcomm Atheros Communications | 25        | 5.73%   |
| Apple                           | 24        | 5.5%    |
| Broadcom                        | 13        | 2.98%   |
| Foxconn / Hon Hai               | 11        | 2.52%   |
| MediaTek                        | 6         | 1.38%   |
| ASUSTek Computer                | 6         | 1.38%   |
| Toshiba                         | 5         | 1.15%   |
| Realtek                         | 5         | 1.15%   |
| TP-Link                         | 4         | 0.92%   |
| Foxconn International           | 4         | 0.92%   |
| Dell                            | 4         | 0.92%   |
| USI                             | 3         | 0.69%   |
| SINO WEALTH                     | 2         | 0.46%   |
| Ralink                          | 2         | 0.46%   |
| Hewlett-Packard                 | 2         | 0.46%   |
| Actions                         | 2         | 0.46%   |
| Unknown                         | 2         | 0.46%   |
| Marvell Semiconductor           | 1         | 0.23%   |
| Askey Computer                  | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 64        | 14.65%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38        | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 31        | 7.09%   |
| Intel AX201 Bluetooth                               | 30        | 6.86%   |
| Intel AX200 Bluetooth                               | 25        | 5.72%   |
| Realtek Bluetooth Radio                             | 16        | 3.66%   |
| Intel AX211 Bluetooth                               | 11        | 2.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 2.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 2.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 2.29%   |
| IMC Networks Bluetooth Radio                        | 10        | 2.29%   |
| IMC Networks Bluetooth Device                       | 10        | 2.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 2.06%   |
| IMC Networks Wireless_Device                        | 9         | 2.06%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.6%    |
| Intel AX210 Bluetooth                               | 7         | 1.6%    |
| Apple Bluetooth Host Controller                     | 7         | 1.6%    |
| MediaTek Wireless_Device                            | 6         | 1.37%   |
| Lite-On Bluetooth Device                            | 6         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 1.37%   |
| Realtek Bluetooth Radio                             | 5         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.14%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 4         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.92%   |
| USI Bluetooth Device                                | 3         | 0.69%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.69%   |
| Lite-On Wireless_Device                             | 3         | 0.69%   |
| Lite-On Bluetooth Radio                             | 3         | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.69%   |
| Apple Bluetooth HCI                                 | 3         | 0.69%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.46%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.46%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.46%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 462       | 50.88%  |
| AMD                                          | 187       | 20.59%  |
| Nvidia                                       | 168       | 18.5%   |
| C-Media Electronics                          | 14        | 1.54%   |
| JMTek                                        | 10        | 1.1%    |
| Razer USA                                    | 6         | 0.66%   |
| Generalplus Technology                       | 5         | 0.55%   |
| Logitech                                     | 3         | 0.33%   |
| Focusrite-Novation                           | 3         | 0.33%   |
| Elan Microelectronics                        | 3         | 0.33%   |
| Creative Labs                                | 3         | 0.33%   |
| VIA Technologies                             | 2         | 0.22%   |
| Texas Instruments                            | 2         | 0.22%   |
| SAVITECH                                     | 2         | 0.22%   |
| Samson Technologies                          | 2         | 0.22%   |
| Earth Computer Technologies                  | 2         | 0.22%   |
| Dell                                         | 2         | 0.22%   |
| Creative Technology                          | 2         | 0.22%   |
| Audio-Technica                               | 2         | 0.22%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.11%   |
| Walmart                                      | 1         | 0.11%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.11%   |
| Syntek                                       | 1         | 0.11%   |
| Synaptics                                    | 1         | 0.11%   |
| Samsung Electronics                          | 1         | 0.11%   |
| Nordic Semiconductor ASA                     | 1         | 0.11%   |
| Lenovo                                       | 1         | 0.11%   |
| KTMicro                                      | 1         | 0.11%   |
| Kingston Technology                          | 1         | 0.11%   |
| JIAYZMicro                                   | 1         | 0.11%   |
| Huawei Technologies                          | 1         | 0.11%   |
| Hewlett-Packard                              | 1         | 0.11%   |
| HECATE                                       | 1         | 0.11%   |
| ESS Technology                               | 1         | 0.11%   |
| Ensoniq                                      | 1         | 0.11%   |
| EDIFIER                                      | 1         | 0.11%   |
| DSEA A/S                                     | 1         | 0.11%   |
| Digidesign                                   | 1         | 0.11%   |
| Corsair                                      | 1         | 0.11%   |
| Cayin                                        | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 70        | 6.41%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 43        | 3.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 39        | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 3.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 31        | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 26        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 20        | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 1.65%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18        | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 17        | 1.56%   |
| AMD FCH Azalia Controller                                                                         | 15        | 1.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 12        | 1.1%    |
| Nvidia High Definition Audio Controller                                                           | 12        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 11        | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 11        | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 9         | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 0.82%   |
| AMD Navi 10 HDMI Audio                                                                            | 9         | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 8         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 7         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 90        | 22.67%  |
| Kingston            | 84        | 21.16%  |
| SK hynix            | 75        | 18.89%  |
| Micron Technology   | 41        | 10.33%  |
| Unknown             | 28        | 7.05%   |
| Corsair             | 17        | 4.28%   |
| Ramaxel Technology  | 8         | 2.02%   |
| Crucial             | 7         | 1.76%   |
| Transcend           | 6         | 1.51%   |
| Team                | 6         | 1.51%   |
| Elpida              | 6         | 1.51%   |
| A-DATA Technology   | 6         | 1.51%   |
| Nanya Technology    | 4         | 1.01%   |
| G.Skill             | 3         | 0.76%   |
| Apacer              | 3         | 0.76%   |
| Unknown (ABCD)      | 2         | 0.5%    |
| Unknown             | 2         | 0.5%    |
| Unknown (0x8325)    | 1         | 0.25%   |
| Unknown (0x02BA)    | 1         | 0.25%   |
| Unknown (08B5)      | 1         | 0.25%   |
| Lexar               | 1         | 0.25%   |
| Kingmax             | 1         | 0.25%   |
| KingFast            | 1         | 0.25%   |
| Hikvision           | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 9         | 2.12%   |
| SK hynix RAM HMCG94AEBRA109N 64GB DIMM DDR5 4800MT/s           | 5         | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 5         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 5         | 1.18%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 5         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 0.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 4         | 0.94%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 0.71%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 3         | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 3         | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s           | 3         | 0.71%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 3         | 0.71%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s           | 3         | 0.71%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 3         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                    | 2         | 0.47%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s            | 2         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.47%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s           | 2         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.47%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 2         | 0.47%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 2         | 0.47%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.47%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 2         | 0.47%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 2         | 0.47%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s          | 2         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 158       | 47.31%  |
| DDR3    | 107       | 32.04%  |
| LPDDR4  | 20        | 5.99%   |
| DDR5    | 15        | 4.49%   |
| DDR2    | 8         | 2.4%    |
| SDRAM   | 7         | 2.1%    |
| LPDDR5  | 6         | 1.8%    |
| LPDDR3  | 6         | 1.8%    |
| Unknown | 4         | 1.2%    |
| DDR     | 2         | 0.6%    |
| DRAM    | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 184       | 55.93%  |
| DIMM         | 110       | 33.43%  |
| Row Of Chips | 32        | 9.73%   |
| RIMM         | 1         | 0.3%    |
| FB-DIMM      | 1         | 0.3%    |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 139       | 39.38%  |
| 4096  | 104       | 29.46%  |
| 16384 | 46        | 13.03%  |
| 2048  | 40        | 11.33%  |
| 32768 | 11        | 3.12%   |
| 1024  | 7         | 1.98%   |
| 65536 | 5         | 1.42%   |
| 3072  | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 74        | 20.22%  |
| 3200    | 57        | 15.57%  |
| 2667    | 41        | 11.2%   |
| 2400    | 32        | 8.74%   |
| 1333    | 28        | 7.65%   |
| 2133    | 18        | 4.92%   |
| 4800    | 11        | 3.01%   |
| 3733    | 9         | 2.46%   |
| 4267    | 8         | 2.19%   |
| 1867    | 8         | 2.19%   |
| 1334    | 8         | 2.19%   |
| 3600    | 6         | 1.64%   |
| 3266    | 5         | 1.37%   |
| 1067    | 5         | 1.37%   |
| 6400    | 4         | 1.09%   |
| 3400    | 4         | 1.09%   |
| 667     | 4         | 1.09%   |
| 4266    | 3         | 0.82%   |
| 3466    | 3         | 0.82%   |
| 3000    | 3         | 0.82%   |
| 2666    | 3         | 0.82%   |
| 1866    | 3         | 0.82%   |
| 1800    | 3         | 0.82%   |
| 5600    | 2         | 0.55%   |
| 3534    | 2         | 0.55%   |
| 3151    | 2         | 0.55%   |
| 800     | 2         | 0.55%   |
| 533     | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |
| 8400    | 1         | 0.27%   |
| 7500    | 1         | 0.27%   |
| 7467    | 1         | 0.27%   |
| 6800    | 1         | 0.27%   |
| 5808    | 1         | 0.27%   |
| 4199    | 1         | 0.27%   |
| 3800    | 1         | 0.27%   |
| 3666    | 1         | 0.27%   |
| 3333    | 1         | 0.27%   |
| 2800    | 1         | 0.27%   |
| 2000    | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 5         | 31.25%  |
| Seiko Epson         | 4         | 25%     |
| Hewlett-Packard     | 2         | 12.5%   |
| Canon               | 2         | 12.5%   |
| STMicroelectronics  | 1         | 6.25%   |
| Samsung Electronics | 1         | 6.25%   |
| Pantum              | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seiko Epson L360 Series             | 2         | 12.5%   |
| STMicroelectronics USB Printer Port | 1         | 6.25%   |
| Seiko Epson ME-100 Series           | 1         | 6.25%   |
| Seiko Epson LQ-310                  | 1         | 6.25%   |
| Samsung SCX-4300 Series             | 1         | 6.25%   |
| Pantum P2500W series                | 1         | 6.25%   |
| HP HP LaserJet Pro M404-M405        | 1         | 6.25%   |
| HP DeskJet 2130 series              | 1         | 6.25%   |
| Canon PIXMA MP280                   | 1         | 6.25%   |
| Canon E4200 series                  | 1         | 6.25%   |
| Brother HL-1110 series              | 1         | 6.25%   |
| Brother DCP-T510W                   | 1         | 6.25%   |
| Brother DCP-T300                    | 1         | 6.25%   |
| Brother DCP-L3551CDW                | 1         | 6.25%   |
| Brother DCP-1510                    | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 81        | 22.19%  |
| IMC Networks                           | 42        | 11.51%  |
| Bison Electronics                      | 36        | 9.86%   |
| Realtek Semiconductor                  | 26        | 7.12%   |
| Microdia                               | 23        | 6.3%    |
| Quanta                                 | 21        | 5.75%   |
| Logitech                               | 16        | 4.38%   |
| Sunplus Innovation Technology          | 13        | 3.56%   |
| Apple                                  | 13        | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.01%   |
| Suyin                                  | 7         | 1.92%   |
| Microsoft                              | 7         | 1.92%   |
| Lite-On Technology                     | 7         | 1.92%   |
| Acer                                   | 7         | 1.92%   |
| Silicon Motion                         | 6         | 1.64%   |
| Syntek                                 | 5         | 1.37%   |
| Sonix Technology                       | 5         | 1.37%   |
| ShineTech                              | 5         | 1.37%   |
| Generalplus Technology                 | 5         | 1.37%   |
| Aveo Technology                        | 4         | 1.1%    |
| MacroSilicon                           | 3         | 0.82%   |
| Luxvisions Innotech Limited            | 3         | 0.82%   |
| Z-Star Microelectronics                | 2         | 0.55%   |
| Samsung Electronics                    | 2         | 0.55%   |
| OPPO Electronics                       | 2         | 0.55%   |
| Alcor Micro                            | 2         | 0.55%   |
| WCM_USB                                | 1         | 0.27%   |
| vivo                                   | 1         | 0.27%   |
| Sony Electronics                       | 1         | 0.27%   |
| Razer USA                              | 1         | 0.27%   |
| Owon                                   | 1         | 0.27%   |
| Lenovo                                 | 1         | 0.27%   |
| icSpring                               | 1         | 0.27%   |
| Huawei Technologies                    | 1         | 0.27%   |
| DRFCB0ABIHX4E3                         | 1         | 0.27%   |
| Dell                                   | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam    | 17        | 4.63%   |
| Chicony Integrated Camera            | 15        | 4.09%   |
| Chicony HD WebCam                    | 13        | 3.54%   |
| Realtek Integrated_Webcam_HD         | 8         | 2.18%   |
| Microdia Integrated_Webcam_HD        | 8         | 2.18%   |
| Bison Integrated Camera              | 8         | 2.18%   |
| Chicony HP TrueVision HD Camera      | 7         | 1.91%   |
| IMC Networks Integrated Camera       | 6         | 1.63%   |
| Chicony HD User Facing               | 6         | 1.63%   |
| Apple Built-in iSight                | 6         | 1.63%   |
| Microsoft MicrosoftÂ LifeCam Cinema | 5         | 1.36%   |
| Bison SunplusIT Integrated Camera    | 5         | 1.36%   |
| Bison Lenovo EasyCamera              | 5         | 1.36%   |
| Sonix USB2.0 HD UVC WebCam           | 4         | 1.09%   |
| ShineTech USB2.0 HD UVC WebCam       | 4         | 1.09%   |
| Realtek HD WebCam                    | 4         | 1.09%   |
| Microdia USB 2.0 Camera              | 4         | 1.09%   |
| Logitech Webcam C270                 | 4         | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 4         | 1.09%   |
| IMC Networks HD Camera               | 4         | 1.09%   |
| Generalplus GENERAL WEBCAM           | 4         | 1.09%   |
| Chicony Lenovo EasyCamera            | 4         | 1.09%   |
| Chicony FJ Camera                    | 4         | 1.09%   |
| Syntek Integrated Camera             | 3         | 0.82%   |
| Sunplus Integrated_Webcam_HD         | 3         | 0.82%   |
| Silicon Motion WebCam SCB-0385N      | 3         | 0.82%   |
| Quanta USB2.0 HD UVC WebCam          | 3         | 0.82%   |
| Quanta HD Webcam                     | 3         | 0.82%   |
| Quanta HD Camera                     | 3         | 0.82%   |
| Microdia Camera                      | 3         | 0.82%   |
| MacroSilicon USB Video               | 3         | 0.82%   |
| Logitech HD Pro Webcam C920          | 3         | 0.82%   |
| Lite-On Integrated Camera            | 3         | 0.82%   |
| Lite-On HP Wide Vision HD Camera     | 3         | 0.82%   |
| Chicony TOSHIBA Web Camera - HD      | 3         | 0.82%   |
| Chicony HP Wide Vision HD Camera     | 3         | 0.82%   |
| Bison ThinkPad Integrated Camera     | 3         | 0.82%   |
| Bison HD Webcam                      | 3         | 0.82%   |
| Aveo USB2.0 Camera                   | 3         | 0.82%   |
| Apple FaceTime HD Camera (Built-in)  | 3         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 28.79%  |
| Shenzhen Goodix Technology | 16        | 24.24%  |
| Validity Sensors           | 9         | 13.64%  |
| LighTuning Technology      | 8         | 12.12%  |
| Elan Microelectronics      | 6         | 9.09%   |
| AuthenTec                  | 5         | 7.58%   |
| Upek                       | 3         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 7         | 10.61%  |
| Shenzhen Goodix Fingerprint Reader                       | 7         | 10.61%  |
| Synaptics WBDI                                           | 4         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 4         | 6.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 4         | 6.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 3         | 4.55%   |
| Elan ELAN:ARM-M4                                         | 3         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor                | 2         | 3.03%   |
| Synaptics UWP WBDI Device                                | 2         | 3.03%   |
| Synaptics  WBDI                                          | 2         | 3.03%   |
| Shenzhen Goodix FingerPrint                              | 2         | 3.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 3.03%   |
| Elan WBF Fingerprint Sensor                              | 2         | 3.03%   |
| AuthenTec AES2810                                        | 2         | 3.03%   |
| AuthenTec AES1600                                        | 2         | 3.03%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 1.52%   |
| Validity Sensors Synaptics WBDI                          | 1         | 1.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 1.52%   |
| Synaptics Prometheus Fingerprint Reader                  | 1         | 1.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.52%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.52%   |
| LighTuning Fingerprint Sensor                            | 1         | 1.52%   |
| LighTuning Fingerprint Reader                            | 1         | 1.52%   |
| Elan ELAN:Fingerprint                                    | 1         | 1.52%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 6         | 40%     |
| Broadcom              | 4         | 26.67%  |
| O2 Micro              | 3         | 20%     |
| OmniKey               | 1         | 6.67%   |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 20%     |
| Broadcom 5880                                                                | 2         | 13.33%  |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 6.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom 58200                                                               | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 468       | 70.27%  |
| 1     | 161       | 24.17%  |
| 2     | 29        | 4.35%   |
| 3     | 5         | 0.75%   |
| 7     | 1         | 0.15%   |
| 5     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 65        | 27.54%  |
| Graphics card            | 52        | 22.03%  |
| Net/wireless             | 33        | 13.98%  |
| Multimedia controller    | 27        | 11.44%  |
| Chipcard                 | 13        | 5.51%   |
| Unassigned class         | 8         | 3.39%   |
| Sound                    | 8         | 3.39%   |
| Communication controller | 8         | 3.39%   |
| Camera                   | 7         | 2.97%   |
| Bluetooth                | 4         | 1.69%   |
| Net/ethernet             | 3         | 1.27%   |
| Storage/raid             | 2         | 0.85%   |
| Card reader              | 2         | 0.85%   |
| Wireless                 | 1         | 0.42%   |
| Storage/ide              | 1         | 0.42%   |
| Network                  | 1         | 0.42%   |
| Flash memory             | 1         | 0.42%   |

