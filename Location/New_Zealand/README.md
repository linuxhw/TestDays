Linux in New Zealand - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/New_Zealand/Desktop/README.md) and [notebooks](/Location/New_Zealand/Notebook/README.md).

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

Total: 1302

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B560M-ITX/ac                | Desktop     | [9ed6c67efe](https://linux-hardware.org/?probe=9ed6c67efe) | Feb 02, 2024 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [32200add92](https://linux-hardware.org/?probe=32200add92) | Jan 31, 2024 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [38cafaade5](https://linux-hardware.org/?probe=38cafaade5) | Jan 31, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [646a977cdd](https://linux-hardware.org/?probe=646a977cdd) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [40e2ad53e8](https://linux-hardware.org/?probe=40e2ad53e8) | Jan 29, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [99e90d2b89](https://linux-hardware.org/?probe=99e90d2b89) | Jan 29, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [1b5bfa9bcb](https://linux-hardware.org/?probe=1b5bfa9bcb) | Jan 28, 2024 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [185a90aec7](https://linux-hardware.org/?probe=185a90aec7) | Jan 28, 2024 |
| ASUSTek       | P8B75-M                     | Desktop     | [ad1a5f6757](https://linux-hardware.org/?probe=ad1a5f6757) | Jan 28, 2024 |
| HP            | 2AAC                        | Desktop     | [d397b1b3b3](https://linux-hardware.org/?probe=d397b1b3b3) | Jan 26, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [abc0872688](https://linux-hardware.org/?probe=abc0872688) | Jan 24, 2024 |
| Intel         | Unknown                     | Desktop     | [e4094a3abf](https://linux-hardware.org/?probe=e4094a3abf) | Jan 23, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [4f202be1d5](https://linux-hardware.org/?probe=4f202be1d5) | Jan 20, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a1e7338a13](https://linux-hardware.org/?probe=a1e7338a13) | Jan 19, 2024 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [6565fd5500](https://linux-hardware.org/?probe=6565fd5500) | Jan 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [122b72e9f2](https://linux-hardware.org/?probe=122b72e9f2) | Jan 15, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0ab95fc3f5](https://linux-hardware.org/?probe=0ab95fc3f5) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3d7fcea179](https://linux-hardware.org/?probe=3d7fcea179) | Jan 11, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [4a1bc29322](https://linux-hardware.org/?probe=4a1bc29322) | Jan 06, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [7b663d0c10](https://linux-hardware.org/?probe=7b663d0c10) | Jan 05, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [d80a5355a3](https://linux-hardware.org/?probe=d80a5355a3) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [db656f3905](https://linux-hardware.org/?probe=db656f3905) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [251b877f2f](https://linux-hardware.org/?probe=251b877f2f) | Jan 03, 2024 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [24166c136e](https://linux-hardware.org/?probe=24166c136e) | Jan 02, 2024 |
| Dell          | 0D28YY A01                  | Desktop     | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [942c025f11](https://linux-hardware.org/?probe=942c025f11) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [a9dd36da25](https://linux-hardware.org/?probe=a9dd36da25) | Dec 29, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [690962312c](https://linux-hardware.org/?probe=690962312c) | Dec 29, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [8f2f7cd8c9](https://linux-hardware.org/?probe=8f2f7cd8c9) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [19e33f2ead](https://linux-hardware.org/?probe=19e33f2ead) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [476915f215](https://linux-hardware.org/?probe=476915f215) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [ae7d12ef06](https://linux-hardware.org/?probe=ae7d12ef06) | Dec 17, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ee8ea2b093](https://linux-hardware.org/?probe=ee8ea2b093) | Dec 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [f91ead8a19](https://linux-hardware.org/?probe=f91ead8a19) | Dec 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [cedb8ab2b7](https://linux-hardware.org/?probe=cedb8ab2b7) | Dec 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6d5beb948](https://linux-hardware.org/?probe=e6d5beb948) | Dec 01, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8b68261a59](https://linux-hardware.org/?probe=8b68261a59) | Nov 30, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [8a91691d0b](https://linux-hardware.org/?probe=8a91691d0b) | Nov 30, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [a680e370dc](https://linux-hardware.org/?probe=a680e370dc) | Nov 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [71c73a255e](https://linux-hardware.org/?probe=71c73a255e) | Nov 29, 2023 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [c3d0a3a34c](https://linux-hardware.org/?probe=c3d0a3a34c) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [1192e07984](https://linux-hardware.org/?probe=1192e07984) | Nov 24, 2023 |
| HP            | 85A2                        | All in one  | [80b79f2bed](https://linux-hardware.org/?probe=80b79f2bed) | Nov 24, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| Acer          | Aspire X3400                | Desktop     | [26cedbdbde](https://linux-hardware.org/?probe=26cedbdbde) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| Acer          | Aspire X3400                | Desktop     | [83890ec21c](https://linux-hardware.org/?probe=83890ec21c) | Nov 19, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [a9d9ea53da](https://linux-hardware.org/?probe=a9d9ea53da) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [ad44d7ebae](https://linux-hardware.org/?probe=ad44d7ebae) | Nov 15, 2023 |
| Google        | Magolor                     | Notebook    | [375ff87615](https://linux-hardware.org/?probe=375ff87615) | Nov 14, 2023 |
| Google        | Magolor                     | Notebook    | [f287edf382](https://linux-hardware.org/?probe=f287edf382) | Nov 14, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [a88696f0e2](https://linux-hardware.org/?probe=a88696f0e2) | Nov 13, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [0483e390e3](https://linux-hardware.org/?probe=0483e390e3) | Nov 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [14ae5dbe92](https://linux-hardware.org/?probe=14ae5dbe92) | Nov 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [bc514556b3](https://linux-hardware.org/?probe=bc514556b3) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [e00099e8c5](https://linux-hardware.org/?probe=e00099e8c5) | Nov 08, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1801a9c841](https://linux-hardware.org/?probe=1801a9c841) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [52a36f5268](https://linux-hardware.org/?probe=52a36f5268) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | Desktop     | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| HP            | 829A                        | Mini pc     | [d0735e46db](https://linux-hardware.org/?probe=d0735e46db) | Nov 01, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| HP            | 1998                        | Desktop     | [4701148920](https://linux-hardware.org/?probe=4701148920) | Oct 26, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [d1c293b080](https://linux-hardware.org/?probe=d1c293b080) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| HP            | 2B3B                        | All in one  | [b2dac4adaa](https://linux-hardware.org/?probe=b2dac4adaa) | Oct 25, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [2ad6656255](https://linux-hardware.org/?probe=2ad6656255) | Oct 21, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [4aaa66c7bc](https://linux-hardware.org/?probe=4aaa66c7bc) | Oct 20, 2023 |
| HP            | 85A2                        | All in one  | [67234a41ca](https://linux-hardware.org/?probe=67234a41ca) | Oct 18, 2023 |
| HP            | 14                          | Notebook    | [3d65da2b45](https://linux-hardware.org/?probe=3d65da2b45) | Oct 08, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [67df4157ef](https://linux-hardware.org/?probe=67df4157ef) | Oct 06, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [058c6a0ee6](https://linux-hardware.org/?probe=058c6a0ee6) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [bdfa072267](https://linux-hardware.org/?probe=bdfa072267) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [34d3a3bd47](https://linux-hardware.org/?probe=34d3a3bd47) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | Desktop     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [4c34ba59ba](https://linux-hardware.org/?probe=4c34ba59ba) | Oct 02, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e87fdc15ed](https://linux-hardware.org/?probe=e87fdc15ed) | Sep 29, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [b1333a2976](https://linux-hardware.org/?probe=b1333a2976) | Sep 29, 2023 |
| Gigabyte      | P35V3                       | Notebook    | [573f9ea2f5](https://linux-hardware.org/?probe=573f9ea2f5) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [c4387fc499](https://linux-hardware.org/?probe=c4387fc499) | Sep 24, 2023 |
| HP            | 8714                        | Desktop     | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| HP            | 1998                        | Desktop     | [27c06c8617](https://linux-hardware.org/?probe=27c06c8617) | Sep 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e098daf3a4](https://linux-hardware.org/?probe=e098daf3a4) | Sep 20, 2023 |
| Lenovo        | 3190 SDK0T76530 WIN 3556... | Mini pc     | [2179b0b458](https://linux-hardware.org/?probe=2179b0b458) | Sep 19, 2023 |
| HP            | 1998                        | Desktop     | [d65f099f06](https://linux-hardware.org/?probe=d65f099f06) | Sep 19, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [def911de73](https://linux-hardware.org/?probe=def911de73) | Sep 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [22a0210f8f](https://linux-hardware.org/?probe=22a0210f8f) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [4c56913d07](https://linux-hardware.org/?probe=4c56913d07) | Sep 13, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [a6d8eedc84](https://linux-hardware.org/?probe=a6d8eedc84) | Sep 11, 2023 |
| HP            | Notebook                    | Notebook    | [5a36d2a3bf](https://linux-hardware.org/?probe=5a36d2a3bf) | Sep 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [a9db40cece](https://linux-hardware.org/?probe=a9db40cece) | Sep 08, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [fc63e4f764](https://linux-hardware.org/?probe=fc63e4f764) | Sep 08, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [04e5805a67](https://linux-hardware.org/?probe=04e5805a67) | Sep 06, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [bc3d42d633](https://linux-hardware.org/?probe=bc3d42d633) | Sep 06, 2023 |
| MSI           | X79A-GD65                   | Desktop     | [5efb1e3e55](https://linux-hardware.org/?probe=5efb1e3e55) | Sep 06, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [5dac4ae656](https://linux-hardware.org/?probe=5dac4ae656) | Sep 03, 2023 |
| Intel         | NUC7i3BNB J22859-310        | Mini pc     | [cd552285b0](https://linux-hardware.org/?probe=cd552285b0) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| Acer          | Aspire X3400                | Desktop     | [62a78b2a16](https://linux-hardware.org/?probe=62a78b2a16) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | Notebook    | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [9d05ea660f](https://linux-hardware.org/?probe=9d05ea660f) | Aug 31, 2023 |
| Dell          | 0HD5W2 A00                  | Notebook    | [492d08445d](https://linux-hardware.org/?probe=492d08445d) | Aug 28, 2023 |
| Sony          | VPCEB43FG                   | Notebook    | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fed21c9b13](https://linux-hardware.org/?probe=fed21c9b13) | Aug 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c58a917e49](https://linux-hardware.org/?probe=c58a917e49) | Aug 23, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |
| HP            | 18E5                        | Desktop     | [c17629e422](https://linux-hardware.org/?probe=c17629e422) | Aug 22, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [0383dad714](https://linux-hardware.org/?probe=0383dad714) | Aug 18, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| Dell          | 0NKW6Y A00                  | Notebook    | [c48afaf5bd](https://linux-hardware.org/?probe=c48afaf5bd) | Aug 15, 2023 |
| Dell          | 0NKW6Y A00                  | Notebook    | [774306b244](https://linux-hardware.org/?probe=774306b244) | Aug 15, 2023 |
| Dell          | 0NKW6Y A00                  | Notebook    | [14deab8375](https://linux-hardware.org/?probe=14deab8375) | Aug 15, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9e03b48bf3](https://linux-hardware.org/?probe=9e03b48bf3) | Aug 15, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [df9fab1b5b](https://linux-hardware.org/?probe=df9fab1b5b) | Aug 13, 2023 |
| Alienware     | 15                          | Notebook    | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0638b1c2dd](https://linux-hardware.org/?probe=0638b1c2dd) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [ff98e5f807](https://linux-hardware.org/?probe=ff98e5f807) | Aug 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1099f63384](https://linux-hardware.org/?probe=1099f63384) | Jul 30, 2023 |
| HP            | Beats 15                    | Notebook    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | Notebook    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| Acer          | E1-510                      | Notebook    | [2a83ad14c0](https://linux-hardware.org/?probe=2a83ad14c0) | Jul 27, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [823eca937c](https://linux-hardware.org/?probe=823eca937c) | Jul 24, 2023 |
| HP            | Notebook                    | Notebook    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [8d9ea8214d](https://linux-hardware.org/?probe=8d9ea8214d) | Jul 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [0e18492205](https://linux-hardware.org/?probe=0e18492205) | Jul 20, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [61c153902b](https://linux-hardware.org/?probe=61c153902b) | Jul 19, 2023 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [d2b1eef8ac](https://linux-hardware.org/?probe=d2b1eef8ac) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | Desktop     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [b048c3ee50](https://linux-hardware.org/?probe=b048c3ee50) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [f1a7e1dbb3](https://linux-hardware.org/?probe=f1a7e1dbb3) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [773d5ee9aa](https://linux-hardware.org/?probe=773d5ee9aa) | Jul 13, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [dd19d99ba1](https://linux-hardware.org/?probe=dd19d99ba1) | Jul 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [8086d33203](https://linux-hardware.org/?probe=8086d33203) | Jun 29, 2023 |
| Acer          | EG43M                       | Desktop     | [e6d28dd1e5](https://linux-hardware.org/?probe=e6d28dd1e5) | Jun 28, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [15e9b561e3](https://linux-hardware.org/?probe=15e9b561e3) | Jun 27, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [34cf8e17a2](https://linux-hardware.org/?probe=34cf8e17a2) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [ef8876640e](https://linux-hardware.org/?probe=ef8876640e) | Jun 22, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [ea1fabfdc3](https://linux-hardware.org/?probe=ea1fabfdc3) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [207d5f5dbd](https://linux-hardware.org/?probe=207d5f5dbd) | Jun 17, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [744c44deca](https://linux-hardware.org/?probe=744c44deca) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [267010517a](https://linux-hardware.org/?probe=267010517a) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [c0f64d3436](https://linux-hardware.org/?probe=c0f64d3436) | Jun 03, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7a83a98e37](https://linux-hardware.org/?probe=7a83a98e37) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a78aee5f7f](https://linux-hardware.org/?probe=a78aee5f7f) | Jun 02, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [19043cab25](https://linux-hardware.org/?probe=19043cab25) | Jun 01, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [acc54fe70f](https://linux-hardware.org/?probe=acc54fe70f) | Jun 01, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcb29a1ec2](https://linux-hardware.org/?probe=dcb29a1ec2) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| Unknown       | T100                        | Desktop     | [c4a7218b7b](https://linux-hardware.org/?probe=c4a7218b7b) | May 18, 2023 |
| HP            | 8055                        | Desktop     | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| HP            | 8055                        | Desktop     | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [1b444989b5](https://linux-hardware.org/?probe=1b444989b5) | May 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Unknown       | T100                        | Desktop     | [977cdddeb1](https://linux-hardware.org/?probe=977cdddeb1) | May 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| Acer          | Aspire E1-521               | Notebook    | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [80b16a8567](https://linux-hardware.org/?probe=80b16a8567) | May 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| HP            | 81BB                        | All in one  | [8c50716d55](https://linux-hardware.org/?probe=8c50716d55) | May 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [c7308f11ce](https://linux-hardware.org/?probe=c7308f11ce) | May 06, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [088deaf386](https://linux-hardware.org/?probe=088deaf386) | May 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [057eeed322](https://linux-hardware.org/?probe=057eeed322) | May 03, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [69d95c7c30](https://linux-hardware.org/?probe=69d95c7c30) | May 02, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [864b1a4325](https://linux-hardware.org/?probe=864b1a4325) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | Notebook    | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| HP            | 1489                        | All in one  | [ebd3760355](https://linux-hardware.org/?probe=ebd3760355) | Apr 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| HP            | 1489                        | All in one  | [1058adaefd](https://linux-hardware.org/?probe=1058adaefd) | Apr 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [eeed9900b0](https://linux-hardware.org/?probe=eeed9900b0) | Apr 23, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [9896e8b804](https://linux-hardware.org/?probe=9896e8b804) | Apr 22, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [78c8b8578f](https://linux-hardware.org/?probe=78c8b8578f) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [41e83eedd0](https://linux-hardware.org/?probe=41e83eedd0) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ec36fe087a](https://linux-hardware.org/?probe=ec36fe087a) | Apr 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [094563419e](https://linux-hardware.org/?probe=094563419e) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [488dc3a686](https://linux-hardware.org/?probe=488dc3a686) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [bf1af4af46](https://linux-hardware.org/?probe=bf1af4af46) | Mar 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c239e06998](https://linux-hardware.org/?probe=c239e06998) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| Pegatron      | Maureen                     | Desktop     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Google        | Swanky                      | Notebook    | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [7f46837f94](https://linux-hardware.org/?probe=7f46837f94) | Mar 28, 2023 |
| HP            | ProBook 6550b               | Notebook    | [4629264a10](https://linux-hardware.org/?probe=4629264a10) | Mar 27, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ddc916615](https://linux-hardware.org/?probe=8ddc916615) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [7dc2dc172d](https://linux-hardware.org/?probe=7dc2dc172d) | Mar 18, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [67d6333f85](https://linux-hardware.org/?probe=67d6333f85) | Mar 15, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [a1fd7807c6](https://linux-hardware.org/?probe=a1fd7807c6) | Mar 15, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [0185de4fa6](https://linux-hardware.org/?probe=0185de4fa6) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7e668b89fa](https://linux-hardware.org/?probe=7e668b89fa) | Mar 07, 2023 |
| HP            | Notebook                    | Notebook    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [b2b79c4b50](https://linux-hardware.org/?probe=b2b79c4b50) | Mar 06, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [b0b2b55298](https://linux-hardware.org/?probe=b0b2b55298) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [da5eea6a75](https://linux-hardware.org/?probe=da5eea6a75) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [64b2c8d5b9](https://linux-hardware.org/?probe=64b2c8d5b9) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ce2bc0c00d](https://linux-hardware.org/?probe=ce2bc0c00d) | Feb 27, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [69288a8011](https://linux-hardware.org/?probe=69288a8011) | Feb 24, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8ce6b54b09](https://linux-hardware.org/?probe=8ce6b54b09) | Feb 24, 2023 |
| MSI           | GE63VR 7RF                  | Notebook    | [b9aeb1ce18](https://linux-hardware.org/?probe=b9aeb1ce18) | Feb 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a6ebba79c9](https://linux-hardware.org/?probe=a6ebba79c9) | Feb 17, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [f9cfe6d485](https://linux-hardware.org/?probe=f9cfe6d485) | Feb 13, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [23a79acb25](https://linux-hardware.org/?probe=23a79acb25) | Feb 13, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [d1c4626fd3](https://linux-hardware.org/?probe=d1c4626fd3) | Feb 13, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [dfb8064df6](https://linux-hardware.org/?probe=dfb8064df6) | Feb 12, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [deff8d7055](https://linux-hardware.org/?probe=deff8d7055) | Feb 11, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [b11ab46e6e](https://linux-hardware.org/?probe=b11ab46e6e) | Feb 10, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [f0b972d056](https://linux-hardware.org/?probe=f0b972d056) | Feb 10, 2023 |
| Dell          | System XPS L702X            | Notebook    | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [0677b143ac](https://linux-hardware.org/?probe=0677b143ac) | Feb 07, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| Lenovo        | ThinkPad T480 20L5001KAU    | Notebook    | [4b7046e26c](https://linux-hardware.org/?probe=4b7046e26c) | Jan 30, 2023 |
| Acer          | E1-510                      | Notebook    | [659bb96537](https://linux-hardware.org/?probe=659bb96537) | Jan 29, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [93020dd688](https://linux-hardware.org/?probe=93020dd688) | Jan 28, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [9d0f65f90f](https://linux-hardware.org/?probe=9d0f65f90f) | Jan 24, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [3e7a2dabb5](https://linux-hardware.org/?probe=3e7a2dabb5) | Jan 24, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d27e517254](https://linux-hardware.org/?probe=d27e517254) | Jan 21, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [567ae7f5ba](https://linux-hardware.org/?probe=567ae7f5ba) | Jan 21, 2023 |
| DFI           | CR101-CST                   | Desktop     | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [e8d037a152](https://linux-hardware.org/?probe=e8d037a152) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dae35d1c18](https://linux-hardware.org/?probe=dae35d1c18) | Jan 19, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [983230429d](https://linux-hardware.org/?probe=983230429d) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | Notebook    | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [bcb3fca0a2](https://linux-hardware.org/?probe=bcb3fca0a2) | Jan 10, 2023 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [20bfe72df5](https://linux-hardware.org/?probe=20bfe72df5) | Jan 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | Notebook    | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [aaf51b3c3b](https://linux-hardware.org/?probe=aaf51b3c3b) | Jan 09, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [a5638d3bf2](https://linux-hardware.org/?probe=a5638d3bf2) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [ad72a0fad1](https://linux-hardware.org/?probe=ad72a0fad1) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | Notebook    | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [45c8b096c5](https://linux-hardware.org/?probe=45c8b096c5) | Jan 08, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [aa8715fc5c](https://linux-hardware.org/?probe=aa8715fc5c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| Dell          | Precision 7740              | Notebook    | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| HP            | 81BB                        | All in one  | [151d8bcaf3](https://linux-hardware.org/?probe=151d8bcaf3) | Jan 02, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [3f2b642eb0](https://linux-hardware.org/?probe=3f2b642eb0) | Jan 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | 17E2                        | Mini pc     | [8460664f2a](https://linux-hardware.org/?probe=8460664f2a) | Dec 28, 2022 |
| HP            | 3648h                       | Desktop     | [5b3a2d7e48](https://linux-hardware.org/?probe=5b3a2d7e48) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [03c35b7588](https://linux-hardware.org/?probe=03c35b7588) | Dec 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b88840bfdf](https://linux-hardware.org/?probe=b88840bfdf) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [534f769938](https://linux-hardware.org/?probe=534f769938) | Dec 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [56781f9824](https://linux-hardware.org/?probe=56781f9824) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [39bac65c16](https://linux-hardware.org/?probe=39bac65c16) | Dec 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Google        | Laser14                     | Notebook    | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [b333e1030f](https://linux-hardware.org/?probe=b333e1030f) | Dec 16, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d6d4bd4dcd](https://linux-hardware.org/?probe=d6d4bd4dcd) | Dec 14, 2022 |
| HP            | Pavilion dv6                | Notebook    | [2472ce95cb](https://linux-hardware.org/?probe=2472ce95cb) | Dec 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [e2ecbddf15](https://linux-hardware.org/?probe=e2ecbddf15) | Dec 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d9cc4844ac](https://linux-hardware.org/?probe=d9cc4844ac) | Dec 12, 2022 |
| HP            | 81BB                        | All in one  | [7efed40466](https://linux-hardware.org/?probe=7efed40466) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [967204fede](https://linux-hardware.org/?probe=967204fede) | Dec 09, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [5a6ebebd51](https://linux-hardware.org/?probe=5a6ebebd51) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [68004f52cd](https://linux-hardware.org/?probe=68004f52cd) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3912675c64](https://linux-hardware.org/?probe=3912675c64) | Dec 06, 2022 |
| HP            | 81BB                        | All in one  | [0cc2f0b745](https://linux-hardware.org/?probe=0cc2f0b745) | Dec 06, 2022 |
| HP            | 81BB                        | All in one  | [7d64b102e1](https://linux-hardware.org/?probe=7d64b102e1) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| HP            | 1495                        | Desktop     | [138b5bb823](https://linux-hardware.org/?probe=138b5bb823) | Dec 01, 2022 |
| Acer          | E1-510                      | Notebook    | [8aadf699f9](https://linux-hardware.org/?probe=8aadf699f9) | Nov 30, 2022 |
| Dell          | G7 7700                     | Notebook    | [16407c6485](https://linux-hardware.org/?probe=16407c6485) | Nov 27, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [dd85fb5c80](https://linux-hardware.org/?probe=dd85fb5c80) | Nov 22, 2022 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [462cb0ce56](https://linux-hardware.org/?probe=462cb0ce56) | Nov 21, 2022 |
| Google        | Swanky                      | Notebook    | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| HP            | 339A                        | Desktop     | [c995f831b8](https://linux-hardware.org/?probe=c995f831b8) | Nov 13, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2382574dbd](https://linux-hardware.org/?probe=2382574dbd) | Nov 12, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a41cabb3d6](https://linux-hardware.org/?probe=a41cabb3d6) | Nov 04, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a9a5e01e23](https://linux-hardware.org/?probe=a9a5e01e23) | Nov 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6702cb2ca7](https://linux-hardware.org/?probe=6702cb2ca7) | Oct 25, 2022 |
| Dell          | 0GXH08 A01                  | Server      | [f3c7a026b6](https://linux-hardware.org/?probe=f3c7a026b6) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [d5b2d74cd8](https://linux-hardware.org/?probe=d5b2d74cd8) | Oct 21, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [e39bc1af0b](https://linux-hardware.org/?probe=e39bc1af0b) | Oct 20, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [e939a5f236](https://linux-hardware.org/?probe=e939a5f236) | Oct 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [9998a32d98](https://linux-hardware.org/?probe=9998a32d98) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Dell          | Precision 3570              | Notebook    | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | Notebook    | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | Notebook    | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| Dell          | 0UW816 A00                  | Server      | [bd29b42f73](https://linux-hardware.org/?probe=bd29b42f73) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [9959a5f63d](https://linux-hardware.org/?probe=9959a5f63d) | Sep 17, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Google        | Snappy                      | Notebook    | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | MS-98H3                     | Desktop     | [41ad960dd6](https://linux-hardware.org/?probe=41ad960dd6) | Sep 06, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0e3f950f3f](https://linux-hardware.org/?probe=0e3f950f3f) | Sep 02, 2022 |
| The Wareho... | E2037                       | Notebook    | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | Notebook    | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [b41e0fcad5](https://linux-hardware.org/?probe=b41e0fcad5) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | Notebook    | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | Notebook    | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | Notebook    | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [92525ee03c](https://linux-hardware.org/?probe=92525ee03c) | Aug 17, 2022 |
| Lenovo        | 3190 SDK0T76530 WIN 3556... | Mini pc     | [766a8b38a6](https://linux-hardware.org/?probe=766a8b38a6) | Aug 16, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [4ff9f1893d](https://linux-hardware.org/?probe=4ff9f1893d) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [c9e9691195](https://linux-hardware.org/?probe=c9e9691195) | Aug 10, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [91438d7bdd](https://linux-hardware.org/?probe=91438d7bdd) | Aug 06, 2022 |
| Acer          | Spin SP513-51               | Convertible | [7531ebdab5](https://linux-hardware.org/?probe=7531ebdab5) | Aug 05, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [827883d38c](https://linux-hardware.org/?probe=827883d38c) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [773e4afb47](https://linux-hardware.org/?probe=773e4afb47) | Jul 30, 2022 |
| HP            | 2000                        | Notebook    | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | 8054                        | Desktop     | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| HP            | Notebook                    | Notebook    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| Intel         | STK1AW32SC H91596-307       | Desktop     | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| HP            | 3397                        | Desktop     | [83bdaea8fc](https://linux-hardware.org/?probe=83bdaea8fc) | Jul 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | Notebook    | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Intel         | NUC8i5INB K29935-402        | Mini pc     | [27d189d77f](https://linux-hardware.org/?probe=27d189d77f) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Lenovo        | 14w 81MQ0013AU              | Notebook    | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6d6b4c9d06](https://linux-hardware.org/?probe=6d6b4c9d06) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Gigabyte      | B460M D3H                   | Desktop     | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [3c8656100a](https://linux-hardware.org/?probe=3c8656100a) | Jun 29, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [97b8d855bd](https://linux-hardware.org/?probe=97b8d855bd) | Jun 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [9d9ae107c9](https://linux-hardware.org/?probe=9d9ae107c9) | Jun 25, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [788acf13f2](https://linux-hardware.org/?probe=788acf13f2) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [656f558626](https://linux-hardware.org/?probe=656f558626) | Jun 23, 2022 |
| HP            | 18E7                        | Desktop     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | Notebook    | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | Notebook    | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [874c85b694](https://linux-hardware.org/?probe=874c85b694) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bee7f3506c](https://linux-hardware.org/?probe=bee7f3506c) | May 29, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [512d3f18ce](https://linux-hardware.org/?probe=512d3f18ce) | May 28, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [af7e6249f0](https://linux-hardware.org/?probe=af7e6249f0) | May 27, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [44ceac3592](https://linux-hardware.org/?probe=44ceac3592) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | Notebook    | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | Notebook    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Alienware     | x17 R2                      | Notebook    | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| HP            | 1998                        | Desktop     | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6693954f79](https://linux-hardware.org/?probe=6693954f79) | May 07, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [c994128afd](https://linux-hardware.org/?probe=c994128afd) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [8888cb88d3](https://linux-hardware.org/?probe=8888cb88d3) | Apr 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5ec598483e](https://linux-hardware.org/?probe=5ec598483e) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| Dell          | Inspiron 7405 2n1           | Convertible | [9fa115228c](https://linux-hardware.org/?probe=9fa115228c) | Apr 11, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [1a7b7179f7](https://linux-hardware.org/?probe=1a7b7179f7) | Apr 10, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| HP            | 1790                        | Desktop     | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [a7ee814f3a](https://linux-hardware.org/?probe=a7ee814f3a) | Apr 02, 2022 |
| Dell          | Latitude 7480               | Notebook    | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | Notebook    | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [cf9c727b0d](https://linux-hardware.org/?probe=cf9c727b0d) | Mar 24, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| ASUSTek       | P5E                         | Desktop     | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [08dc6f6fe3](https://linux-hardware.org/?probe=08dc6f6fe3) | Mar 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [64f278889f](https://linux-hardware.org/?probe=64f278889f) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [5c169a1d32](https://linux-hardware.org/?probe=5c169a1d32) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [dfebbb508b](https://linux-hardware.org/?probe=dfebbb508b) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [26729d3227](https://linux-hardware.org/?probe=26729d3227) | Feb 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [c7a12417f1](https://linux-hardware.org/?probe=c7a12417f1) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cc2c71140b](https://linux-hardware.org/?probe=cc2c71140b) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [4d1d42c8cc](https://linux-hardware.org/?probe=4d1d42c8cc) | Feb 20, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [024513d4a8](https://linux-hardware.org/?probe=024513d4a8) | Feb 18, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9bc33ce91e](https://linux-hardware.org/?probe=9bc33ce91e) | Feb 16, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc420f69ce](https://linux-hardware.org/?probe=cc420f69ce) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [bf684bced7](https://linux-hardware.org/?probe=bf684bced7) | Feb 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [caf1721ebe](https://linux-hardware.org/?probe=caf1721ebe) | Feb 12, 2022 |
| ASUSTek       | K55A                        | Notebook    | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | Notebook    | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | Notebook    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [24bd4956b6](https://linux-hardware.org/?probe=24bd4956b6) | Feb 05, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | Notebook    | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d8ec503f66](https://linux-hardware.org/?probe=d8ec503f66) | Jan 21, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [b714fa4c7f](https://linux-hardware.org/?probe=b714fa4c7f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | Notebook    | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| MediaVue      | MV-890GX V1.2               | Desktop     | [201163da2f](https://linux-hardware.org/?probe=201163da2f) | Jan 16, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [11bf29bdd1](https://linux-hardware.org/?probe=11bf29bdd1) | Jan 16, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | Notebook    | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b05f843820](https://linux-hardware.org/?probe=b05f843820) | Jan 06, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [7f5484cd91](https://linux-hardware.org/?probe=7f5484cd91) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [51f97b7e46](https://linux-hardware.org/?probe=51f97b7e46) | Dec 25, 2021 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Google        | Kip                         | Notebook    | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3962478b0f](https://linux-hardware.org/?probe=3962478b0f) | Dec 19, 2021 |
| Colorful T... | BATTLE-AX B450M-G DELUXE... | Desktop     | [52614e9f8d](https://linux-hardware.org/?probe=52614e9f8d) | Dec 19, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [8421d8ab8c](https://linux-hardware.org/?probe=8421d8ab8c) | Dec 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [71f69762fe](https://linux-hardware.org/?probe=71f69762fe) | Dec 08, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [572b9da8d1](https://linux-hardware.org/?probe=572b9da8d1) | Dec 06, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [01a565720c](https://linux-hardware.org/?probe=01a565720c) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | Notebook    | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Intel         | NUC7i5DNB J57626-504        | Mini pc     | [d2625c256e](https://linux-hardware.org/?probe=d2625c256e) | Nov 22, 2021 |
| Intel         | NUC7i5DNB J57626-504        | Mini pc     | [12c79d3e71](https://linux-hardware.org/?probe=12c79d3e71) | Nov 21, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2bb3dc142](https://linux-hardware.org/?probe=e2bb3dc142) | Nov 21, 2021 |
| HP            | 3396                        | Desktop     | [db69ec8696](https://linux-hardware.org/?probe=db69ec8696) | Nov 17, 2021 |
| HP            | 3396                        | Desktop     | [70fc3e699a](https://linux-hardware.org/?probe=70fc3e699a) | Nov 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [0c64127bf0](https://linux-hardware.org/?probe=0c64127bf0) | Nov 13, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | Notebook    | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | Notebook    | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | Notebook    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [95e40c6343](https://linux-hardware.org/?probe=95e40c6343) | Oct 30, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [f2ce1a8260](https://linux-hardware.org/?probe=f2ce1a8260) | Oct 26, 2021 |
| HP            | Spectre x2 Detachable       | Notebook    | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [97bd114229](https://linux-hardware.org/?probe=97bd114229) | Oct 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [cfffe6aa63](https://linux-hardware.org/?probe=cfffe6aa63) | Oct 18, 2021 |
| Dell          | Latitude 7490               | Notebook    | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| IBM           | 81Y7071 SVT-R               | Desktop     | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | Notebook    | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | Notebook    | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [8e878489d3](https://linux-hardware.org/?probe=8e878489d3) | Oct 15, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | Latitude 7285               | Notebook    | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [530994c225](https://linux-hardware.org/?probe=530994c225) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| Acer          | Aspire VN7-593G             | Notebook    | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| MSI           | 2AE0                        | Desktop     | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7b579629bb](https://linux-hardware.org/?probe=7b579629bb) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [55620348e7](https://linux-hardware.org/?probe=55620348e7) | Oct 08, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [636ef76e1e](https://linux-hardware.org/?probe=636ef76e1e) | Oct 05, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [ca8c02f319](https://linux-hardware.org/?probe=ca8c02f319) | Sep 29, 2021 |
| JGINYUE       | H97I PLUS V2.0              | Desktop     | [2e66de23a2](https://linux-hardware.org/?probe=2e66de23a2) | Sep 28, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | Notebook    | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [fb59bae064](https://linux-hardware.org/?probe=fb59bae064) | Sep 23, 2021 |
| Lenovo        | Aptio CRB SDK0J40700 WIN... | Mini pc     | [9fc0fe4a5f](https://linux-hardware.org/?probe=9fc0fe4a5f) | Sep 22, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [85b5f14102](https://linux-hardware.org/?probe=85b5f14102) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [2b8efc01ba](https://linux-hardware.org/?probe=2b8efc01ba) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [18b064d0d6](https://linux-hardware.org/?probe=18b064d0d6) | Sep 22, 2021 |
| HP            | 1905                        | Desktop     | [56945cef9c](https://linux-hardware.org/?probe=56945cef9c) | Sep 19, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a7e1713e87](https://linux-hardware.org/?probe=a7e1713e87) | Sep 11, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba       | Satellite C50D-C            | Notebook    | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion        | P6815                       | Notebook    | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion        | P6815                       | Notebook    | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf4c0a5a4d](https://linux-hardware.org/?probe=cf4c0a5a4d) | Aug 28, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| ASRock        | 990FX Killer                | Desktop     | [6dd735449b](https://linux-hardware.org/?probe=6dd735449b) | Aug 27, 2021 |
| Sony          | VPCEB43FG                   | Notebook    | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| HP            | 304Ah                       | Desktop     | [0898c11493](https://linux-hardware.org/?probe=0898c11493) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| TWG           | E2017                       | Notebook    | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| HP            | 3397                        | Desktop     | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| MSI           | MS-7028 10B                 | Desktop     | [d9d570cae6](https://linux-hardware.org/?probe=d9d570cae6) | Aug 12, 2021 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [8e107590a6](https://linux-hardware.org/?probe=8e107590a6) | Aug 09, 2021 |
| Toshiba       | Satellite C50D-C            | Notebook    | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [6f97e49163](https://linux-hardware.org/?probe=6f97e49163) | Aug 08, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP            | Pavilion g6                 | Notebook    | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | Notebook    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP            | Spectre x2 Detachable       | Notebook    | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [bd3b6b4f35](https://linux-hardware.org/?probe=bd3b6b4f35) | Jul 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [744ab63b06](https://linux-hardware.org/?probe=744ab63b06) | Jul 28, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [cd88f96d38](https://linux-hardware.org/?probe=cd88f96d38) | Jul 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [215f44bec5](https://linux-hardware.org/?probe=215f44bec5) | Jul 24, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [120f3a158c](https://linux-hardware.org/?probe=120f3a158c) | Jul 21, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [72cf6d1ac2](https://linux-hardware.org/?probe=72cf6d1ac2) | Jul 20, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f410d6449b](https://linux-hardware.org/?probe=f410d6449b) | Jul 19, 2021 |
| MSI           | MS-7028 10B                 | Desktop     | [2c536a7e90](https://linux-hardware.org/?probe=2c536a7e90) | Jul 18, 2021 |
| MSI           | MS-7028 10B                 | Desktop     | [4077783ab8](https://linux-hardware.org/?probe=4077783ab8) | Jul 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9339298035](https://linux-hardware.org/?probe=9339298035) | Jul 14, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| Gigabyte      | P55-UD3                     | Desktop     | [6431c6f93c](https://linux-hardware.org/?probe=6431c6f93c) | Jul 12, 2021 |
| Gigabyte      | P55-UD3                     | Desktop     | [ac267d27d6](https://linux-hardware.org/?probe=ac267d27d6) | Jul 12, 2021 |
| HP            | 1497                        | Desktop     | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e3ee4893c9](https://linux-hardware.org/?probe=e3ee4893c9) | Jul 07, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [841fb32f2d](https://linux-hardware.org/?probe=841fb32f2d) | Jul 05, 2021 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [9b30ecd00d](https://linux-hardware.org/?probe=9b30ecd00d) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | Notebook    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | Notebook    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | Notebook    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7926c787f0](https://linux-hardware.org/?probe=7926c787f0) | Jun 28, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| Lenovo        | ThinkCentre M58p 7479RS2    | Desktop     | [0a417745c3](https://linux-hardware.org/?probe=0a417745c3) | Jun 20, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [79b90a017a](https://linux-hardware.org/?probe=79b90a017a) | Jun 15, 2021 |
| Sony          | SVE14A15FGS                 | Notebook    | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [259f649837](https://linux-hardware.org/?probe=259f649837) | Jun 13, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [b8540739ff](https://linux-hardware.org/?probe=b8540739ff) | Jun 12, 2021 |
| ASRock        | X370 Taichi                 | Desktop     | [15b3d9a238](https://linux-hardware.org/?probe=15b3d9a238) | Jun 10, 2021 |
| ASRock        | X370 Taichi                 | Desktop     | [1ad5e88410](https://linux-hardware.org/?probe=1ad5e88410) | Jun 10, 2021 |
| Qualcomm T... | SM8150 V2 PM8150 CEPHEUS... | Soc         | [d8411dfab2](https://linux-hardware.org/?probe=d8411dfab2) | Jun 09, 2021 |
| ASRock        | N68-S UCC                   | Desktop     | [155ac9e15e](https://linux-hardware.org/?probe=155ac9e15e) | Jun 09, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [4e107618ab](https://linux-hardware.org/?probe=4e107618ab) | Jun 08, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [90c9163323](https://linux-hardware.org/?probe=90c9163323) | Jun 07, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bebce06283](https://linux-hardware.org/?probe=bebce06283) | Jun 07, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c8d175865c](https://linux-hardware.org/?probe=c8d175865c) | Jun 04, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [c78fc3bdf3](https://linux-hardware.org/?probe=c78fc3bdf3) | Jun 04, 2021 |
| MSI           | MS-7125                     | Desktop     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [78d3325aeb](https://linux-hardware.org/?probe=78d3325aeb) | Jun 04, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [f3ffbcfa47](https://linux-hardware.org/?probe=f3ffbcfa47) | Jun 04, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [7bc9fd5174](https://linux-hardware.org/?probe=7bc9fd5174) | Jun 04, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony          | SVE11126CGB                 | Notebook    | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [9ed34e6d16](https://linux-hardware.org/?probe=9ed34e6d16) | May 27, 2021 |
| Toshiba       | Satellite S70t-B            | Notebook    | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba       | Satellite S70t-B            | Notebook    | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| Dell          | 0RCPW3 A03                  | Desktop     | [536202a82c](https://linux-hardware.org/?probe=536202a82c) | May 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| Dell          | 0RCPW3 A03                  | Desktop     | [ea6ed65a9e](https://linux-hardware.org/?probe=ea6ed65a9e) | May 20, 2021 |
| HP            | ENVY 15                     | Notebook    | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [363912f531](https://linux-hardware.org/?probe=363912f531) | May 14, 2021 |
| Gigabyte      | H470 HD3                    | Desktop     | [fb5a619781](https://linux-hardware.org/?probe=fb5a619781) | May 10, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [16e2e1cd8a](https://linux-hardware.org/?probe=16e2e1cd8a) | May 08, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [dcd72d6f14](https://linux-hardware.org/?probe=dcd72d6f14) | May 08, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [a0c689d79b](https://linux-hardware.org/?probe=a0c689d79b) | May 05, 2021 |
| Acer          | E5-571-551U                 | Notebook    | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | Notebook    | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f409c90490](https://linux-hardware.org/?probe=f409c90490) | May 01, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fbb7ce2f8b](https://linux-hardware.org/?probe=fbb7ce2f8b) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [04a24d00e5](https://linux-hardware.org/?probe=04a24d00e5) | Apr 30, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [088ae8b87b](https://linux-hardware.org/?probe=088ae8b87b) | Apr 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3193d396aa](https://linux-hardware.org/?probe=3193d396aa) | Apr 22, 2021 |
| MSI           | GS63VR 7RF                  | Notebook    | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI           | GS63VR 7RF                  | Notebook    | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [190824abc9](https://linux-hardware.org/?probe=190824abc9) | Apr 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c114a5942](https://linux-hardware.org/?probe=9c114a5942) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e23906e5f0](https://linux-hardware.org/?probe=e23906e5f0) | Apr 15, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [d998403a6d](https://linux-hardware.org/?probe=d998403a6d) | Apr 14, 2021 |
| Toshiba       | PORTEGE M930                | Notebook    | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| HP            | 304Ah                       | Desktop     | [92d8929cdf](https://linux-hardware.org/?probe=92d8929cdf) | Apr 10, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| Lenovo        | ThinkCentre A57 9704A36     | Desktop     | [cdde4de4ea](https://linux-hardware.org/?probe=cdde4de4ea) | Apr 05, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [1343705e98](https://linux-hardware.org/?probe=1343705e98) | Apr 05, 2021 |
| Microsoft     | Surface with Windows RT     | Tablet      | [2eb16ad318](https://linux-hardware.org/?probe=2eb16ad318) | Apr 04, 2021 |
| Lenovo        | YB1-X91F                    | Convertible | [78ca0e0334](https://linux-hardware.org/?probe=78ca0e0334) | Apr 03, 2021 |
| Lenovo        | YB1-X91F                    | Convertible | [2b48d2f3e3](https://linux-hardware.org/?probe=2b48d2f3e3) | Apr 03, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [724ea441e9](https://linux-hardware.org/?probe=724ea441e9) | Apr 03, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [4fdca0857b](https://linux-hardware.org/?probe=4fdca0857b) | Apr 03, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [aaa8a98fce](https://linux-hardware.org/?probe=aaa8a98fce) | Apr 02, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| ASRock        | N68-S UCC                   | Desktop     | [e566e1d5a2](https://linux-hardware.org/?probe=e566e1d5a2) | Mar 31, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6ae91d7edf](https://linux-hardware.org/?probe=6ae91d7edf) | Mar 29, 2021 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [7f8e7a4f95](https://linux-hardware.org/?probe=7f8e7a4f95) | Mar 28, 2021 |
| Metabox       | X170SM                      | Notebook    | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | Notebook    | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| ASUSTek       | KCMA-D8                     | Desktop     | [df17b4ced6](https://linux-hardware.org/?probe=df17b4ced6) | Mar 20, 2021 |
| ASRock        | N68-S UCC                   | Desktop     | [15e00c5d4a](https://linux-hardware.org/?probe=15e00c5d4a) | Mar 20, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [5f378abca9](https://linux-hardware.org/?probe=5f378abca9) | Mar 16, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| HP            | 3399                        | Desktop     | [ca3f4aa75a](https://linux-hardware.org/?probe=ca3f4aa75a) | Mar 15, 2021 |
| HP            | 3399                        | Desktop     | [08dbcb0c9c](https://linux-hardware.org/?probe=08dbcb0c9c) | Mar 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [e4dca1478e](https://linux-hardware.org/?probe=e4dca1478e) | Mar 14, 2021 |
| HP            | ProBook 4540s               | Notebook    | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cf36728751](https://linux-hardware.org/?probe=cf36728751) | Mar 08, 2021 |
| Dell          | 002KVM A00                  | Desktop     | [84dbce50b0](https://linux-hardware.org/?probe=84dbce50b0) | Mar 06, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [ed941773ff](https://linux-hardware.org/?probe=ed941773ff) | Mar 05, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [57d8b65b84](https://linux-hardware.org/?probe=57d8b65b84) | Mar 04, 2021 |
| Toshiba       | Satellite U920t             | Notebook    | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ff15fd93df](https://linux-hardware.org/?probe=ff15fd93df) | Mar 01, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP            | ZBook 14                    | Notebook    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| MSI           | MS-7125                     | Desktop     | [3bab98fcf2](https://linux-hardware.org/?probe=3bab98fcf2) | Feb 25, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3ffa3067b0](https://linux-hardware.org/?probe=3ffa3067b0) | Feb 24, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [0b85af69c2](https://linux-hardware.org/?probe=0b85af69c2) | Feb 23, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [5d129c6417](https://linux-hardware.org/?probe=5d129c6417) | Feb 23, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [446f49d2d6](https://linux-hardware.org/?probe=446f49d2d6) | Feb 22, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [97b32c8185](https://linux-hardware.org/?probe=97b32c8185) | Feb 22, 2021 |
| Dell          | Latitude 7285               | Notebook    | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| HP            | 1495                        | Desktop     | [7e0c673361](https://linux-hardware.org/?probe=7e0c673361) | Feb 17, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d7508c8abc](https://linux-hardware.org/?probe=d7508c8abc) | Feb 16, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [b7ead0e2d5](https://linux-hardware.org/?probe=b7ead0e2d5) | Feb 16, 2021 |
| MSI           | MS-7125                     | Desktop     | [104c9a719f](https://linux-hardware.org/?probe=104c9a719f) | Feb 16, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [bfeecd13dd](https://linux-hardware.org/?probe=bfeecd13dd) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [ced39cce40](https://linux-hardware.org/?probe=ced39cce40) | Feb 15, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [eded5967ea](https://linux-hardware.org/?probe=eded5967ea) | Feb 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [4db8ac896d](https://linux-hardware.org/?probe=4db8ac896d) | Feb 15, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell          | Latitude E4300              | Notebook    | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [edd27d5de6](https://linux-hardware.org/?probe=edd27d5de6) | Feb 13, 2021 |
| HP            | Notebook                    | Notebook    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [308dadd545](https://linux-hardware.org/?probe=308dadd545) | Feb 12, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| Supermicro    | X8DAH                       | Server      | [c83dc07b7c](https://linux-hardware.org/?probe=c83dc07b7c) | Feb 09, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6bee16fdd6](https://linux-hardware.org/?probe=6bee16fdd6) | Feb 08, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [65ca4b3fd8](https://linux-hardware.org/?probe=65ca4b3fd8) | Feb 08, 2021 |
| HP            | 355 G2                      | Notebook    | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| IBM           | 94Y7718 SIT                 | Desktop     | [f45bb4d28d](https://linux-hardware.org/?probe=f45bb4d28d) | Feb 02, 2021 |
| IBM           | 94Y7718 SIT                 | Desktop     | [4eda682182](https://linux-hardware.org/?probe=4eda682182) | Feb 01, 2021 |
| HP            | 82FE 11                     | Desktop     | [e0890897e2](https://linux-hardware.org/?probe=e0890897e2) | Jan 24, 2021 |
| Acer          | ES1-512-P8NA                | Notebook    | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP            | 82FE 11                     | Desktop     | [f11621cd76](https://linux-hardware.org/?probe=f11621cd76) | Jan 24, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba       | Satellite U920t             | Notebook    | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | Notebook    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [47437c1fbe](https://linux-hardware.org/?probe=47437c1fbe) | Jan 07, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [e6bc960206](https://linux-hardware.org/?probe=e6bc960206) | Jan 05, 2021 |
| HP            | 304Ah                       | Desktop     | [484bc076eb](https://linux-hardware.org/?probe=484bc076eb) | Jan 03, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [cff3edf070](https://linux-hardware.org/?probe=cff3edf070) | Dec 22, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [da31ffedd3](https://linux-hardware.org/?probe=da31ffedd3) | Dec 19, 2020 |
| Lenovo        | ThinkPad P52 20M9000KUS     | Notebook    | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [365cef4ed3](https://linux-hardware.org/?probe=365cef4ed3) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [da5b8f33d0](https://linux-hardware.org/?probe=da5b8f33d0) | Dec 14, 2020 |
| HP            | ZBook Studio G5             | Notebook    | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [59bb1dc077](https://linux-hardware.org/?probe=59bb1dc077) | Dec 09, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [d98dd8c58b](https://linux-hardware.org/?probe=d98dd8c58b) | Dec 06, 2020 |
| Dell          | Precision 7530              | Notebook    | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | Desktop     | [9fed57ace1](https://linux-hardware.org/?probe=9fed57ace1) | Dec 03, 2020 |
| Lenovo        | 310C SDK0J40709 WIN 3259... | Desktop     | [1e4de9cf24](https://linux-hardware.org/?probe=1e4de9cf24) | Dec 03, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6c7616d830](https://linux-hardware.org/?probe=6c7616d830) | Nov 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [f420bcff80](https://linux-hardware.org/?probe=f420bcff80) | Nov 29, 2020 |
| eMachines     | eM350                       | Notebook    | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| HP            | Elite Dragonfly             | Convertible | [ce851e2475](https://linux-hardware.org/?probe=ce851e2475) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [879eecaa2c](https://linux-hardware.org/?probe=879eecaa2c) | Nov 24, 2020 |
| HP            | 304Ah                       | Desktop     | [8822926229](https://linux-hardware.org/?probe=8822926229) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [b861a3897c](https://linux-hardware.org/?probe=b861a3897c) | Nov 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [6693dd023e](https://linux-hardware.org/?probe=6693dd023e) | Nov 23, 2020 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [74a9003367](https://linux-hardware.org/?probe=74a9003367) | Nov 20, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0343088b2c](https://linux-hardware.org/?probe=0343088b2c) | Nov 20, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9fb23cbe75](https://linux-hardware.org/?probe=9fb23cbe75) | Nov 17, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b32b7c28e2](https://linux-hardware.org/?probe=b32b7c28e2) | Nov 17, 2020 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [163ddf8d0b](https://linux-hardware.org/?probe=163ddf8d0b) | Nov 16, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell          | 042P49 A00                  | Desktop     | [e88a5663df](https://linux-hardware.org/?probe=e88a5663df) | Nov 15, 2020 |
| Dell          | Latitude D630               | Notebook    | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | Notebook    | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | Notebook    | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T520 424229U       | Notebook    | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| HP            | 304Ah                       | Desktop     | [b306a58bbe](https://linux-hardware.org/?probe=b306a58bbe) | Nov 09, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | Notebook    | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | Notebook    | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Gigabyte      | H55M-USB3                   | Desktop     | [d8003cd392](https://linux-hardware.org/?probe=d8003cd392) | Nov 01, 2020 |
| Gigabyte      | H55M-USB3                   | Desktop     | [eeca2887d3](https://linux-hardware.org/?probe=eeca2887d3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [66e528143c](https://linux-hardware.org/?probe=66e528143c) | Oct 31, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | Notebook    | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | Notebook    | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d5717bdb1](https://linux-hardware.org/?probe=4d5717bdb1) | Oct 26, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| Gigabyte      | H87M-D3H                    | Desktop     | [50cdb98356](https://linux-hardware.org/?probe=50cdb98356) | Oct 26, 2020 |
| HP            | ProLiant ML350 G6           | Desktop     | [862c82ee17](https://linux-hardware.org/?probe=862c82ee17) | Oct 26, 2020 |
| HP            | ProBook 6550b               | Notebook    | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [7851a0c8a4](https://linux-hardware.org/?probe=7851a0c8a4) | Oct 21, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| HP            | 3396                        | Desktop     | [df383be5cf](https://linux-hardware.org/?probe=df383be5cf) | Oct 20, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| HP            | 8055                        | Desktop     | [9cabb3c0e9](https://linux-hardware.org/?probe=9cabb3c0e9) | Oct 18, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | X550EP                      | Notebook    | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f5fdcbbf41](https://linux-hardware.org/?probe=f5fdcbbf41) | Oct 15, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP            | Compaq Presario A900        | Notebook    | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [222313e9d4](https://linux-hardware.org/?probe=222313e9d4) | Oct 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [d8f8b18b1f](https://linux-hardware.org/?probe=d8f8b18b1f) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | Notebook    | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| ASRock        | B450M Steel Legend          | Desktop     | [a01b2e0545](https://linux-hardware.org/?probe=a01b2e0545) | Sep 30, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [42e057fc77](https://linux-hardware.org/?probe=42e057fc77) | Sep 29, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [e1e06a60de](https://linux-hardware.org/?probe=e1e06a60de) | Sep 24, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | Notebook    | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [4737809a8c](https://linux-hardware.org/?probe=4737809a8c) | Sep 16, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP            | ProBook 6560b               | Notebook    | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [c5f5fd0a14](https://linux-hardware.org/?probe=c5f5fd0a14) | Sep 12, 2020 |
| Dell          | Latitude E6430s             | Notebook    | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell          | Latitude E7440              | Notebook    | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [9b05cf5c03](https://linux-hardware.org/?probe=9b05cf5c03) | Sep 04, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 84        | 9.23%   |
| Ubuntu 22.04                 | 57        | 6.26%   |
| Ubuntu 18.04                 | 49        | 5.38%   |
| Arch Rolling                 | 30        | 3.3%    |
| Pop!_OS 22.04                | 28        | 3.08%   |
| Zorin 16                     | 25        | 2.75%   |
| Debian 11                    | 23        | 2.53%   |
| Pop!_OS 20.04                | 17        | 1.87%   |
| OpenMandriva 4.3             | 16        | 1.76%   |
| Ubuntu 20.10                 | 14        | 1.54%   |
| Pop!_OS 20.10                | 14        | 1.54%   |
| Zorin 15                     | 13        | 1.43%   |
| OpenMandriva 4.2             | 12        | 1.32%   |
| Manjaro                      | 12        | 1.32%   |
| Linux Mint 21.1              | 12        | 1.32%   |
| Linux Mint 20.3              | 12        | 1.32%   |
| Fedora 36                    | 12        | 1.32%   |
| Arch                         | 12        | 1.32%   |
| Ubuntu 21.04                 | 11        | 1.21%   |
| Linux Mint 20.2              | 11        | 1.21%   |
| Fedora 37                    | 11        | 1.21%   |
| Fedora 34                    | 11        | 1.21%   |
| Fedora 33                    | 11        | 1.21%   |
| Pop!_OS 21.04                | 10        | 1.1%    |
| Linux Mint 20.1              | 10        | 1.1%    |
| Fedora 31                    | 10        | 1.1%    |
| Debian 10                    | 10        | 1.1%    |
| Ubuntu 21.10                 | 9         | 0.99%   |
| OpenMandriva 23.01           | 9         | 0.99%   |
| Fedora 38                    | 9         | 0.99%   |
| Debian 12                    | 9         | 0.99%   |
| Pop!_OS 21.10                | 8         | 0.88%   |
| Linux Mint 21.2              | 8         | 0.88%   |
| Linux Mint 21                | 8         | 0.88%   |
| Ubuntu 23.04                 | 7         | 0.77%   |
| Ubuntu 22.10                 | 7         | 0.77%   |
| Ubuntu 18.10                 | 7         | 0.77%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.77%   |
| OpenMandriva 23.03           | 7         | 0.77%   |
| Linux Mint 20                | 7         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 250       | 29.69%  |
| Linux Mint       | 80        | 9.5%    |
| Pop!_OS          | 72        | 8.55%   |
| Fedora           | 68        | 8.08%   |
| OpenMandriva     | 49        | 5.82%   |
| Debian           | 44        | 5.23%   |
| Arch             | 41        | 4.87%   |
| Zorin            | 40        | 4.75%   |
| Manjaro          | 24        | 2.85%   |
| Kubuntu          | 19        | 2.26%   |
| Endless          | 15        | 1.78%   |
| KDE neon         | 14        | 1.66%   |
| Xubuntu          | 10        | 1.19%   |
| Nobara           | 9         | 1.07%   |
| Elementary       | 8         | 0.95%   |
| openSUSE         | 7         | 0.83%   |
| EndeavourOS      | 7         | 0.83%   |
| Ubuntu Unity     | 5         | 0.59%   |
| ROSA             | 5         | 0.59%   |
| MX               | 5         | 0.59%   |
| Lubuntu          | 5         | 0.59%   |
| LMDE             | 5         | 0.59%   |
| Kali             | 5         | 0.59%   |
| Gentoo           | 5         | 0.59%   |
| ArcoLinux        | 5         | 0.59%   |
| Ubuntu MATE      | 4         | 0.48%   |
| Peppermint       | 4         | 0.48%   |
| SteamOS          | 3         | 0.36%   |
| Solus            | 3         | 0.36%   |
| RHEL             | 3         | 0.36%   |
| Devuan           | 3         | 0.36%   |
| Clear Linux      | 3         | 0.36%   |
| Parrot           | 2         | 0.24%   |
| org.kde.Platform | 2         | 0.24%   |
| NixOS            | 2         | 0.24%   |
| BuildRoot        | 2         | 0.24%   |
| Void Linux       | 1         | 0.12%   |
| Vanilla          | 1         | 0.12%   |
| Ubuntu Budgie    | 1         | 0.12%   |
| Sparky           | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 22        | 2.14%   |
| 5.16.7-desktop-1omv4003  | 14        | 1.36%   |
| 5.15.0-46-generic        | 13        | 1.26%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.17%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.87%   |
| 5.15.0-60-generic        | 8         | 0.78%   |
| 5.15.0-56-generic        | 8         | 0.78%   |
| 6.0.12-76060006-generic  | 7         | 0.68%   |
| 5.4.0-7634-generic       | 7         | 0.68%   |
| 5.4.0-65-generic         | 7         | 0.68%   |
| 5.15.0-58-generic        | 7         | 0.68%   |
| 6.2.6-desktop-1omv2390   | 6         | 0.58%   |
| 5.4.0-48-generic         | 6         | 0.58%   |
| 5.3.0-46-generic         | 6         | 0.58%   |
| 5.3.0-40-generic         | 6         | 0.58%   |
| 5.13.0-30-generic        | 6         | 0.58%   |
| 5.11.0-7620-generic      | 6         | 0.58%   |
| 5.11.0-37-generic        | 6         | 0.58%   |
| 5.10.0-16-amd64          | 6         | 0.58%   |
| 5.0.0-37-generic         | 6         | 0.58%   |
| 6.5.6-76060506-generic   | 5         | 0.49%   |
| 6.2.0-39-generic         | 5         | 0.49%   |
| 6.2.0-20-generic         | 5         | 0.49%   |
| 5.8.0-43-generic         | 5         | 0.49%   |
| 5.4.0-7642-generic       | 5         | 0.49%   |
| 5.4.0-74-generic         | 5         | 0.49%   |
| 5.4.0-52-generic         | 5         | 0.49%   |
| 5.4.0-45-generic         | 5         | 0.49%   |
| 5.3.16-300.fc31.x86_64   | 5         | 0.49%   |
| 5.3.0-28-generic         | 5         | 0.49%   |
| 5.19.0-35-generic        | 5         | 0.49%   |
| 5.19.0-32-generic        | 5         | 0.49%   |
| 5.15.0-52-generic        | 5         | 0.49%   |
| 5.13.0-7614-generic      | 5         | 0.49%   |
| 5.13.0-39-generic        | 5         | 0.49%   |
| 5.11.0-27-generic        | 5         | 0.49%   |
| 5.10.0-18-amd64          | 5         | 0.49%   |
| 6.2.0-32-generic         | 4         | 0.39%   |
| 5.8.0-7630-generic       | 4         | 0.39%   |
| 5.8.0-53-generic         | 4         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 123       | 12.87%  |
| 5.15.0  | 87        | 9.1%    |
| 5.13.0  | 44        | 4.6%    |
| 5.11.0  | 44        | 4.6%    |
| 5.8.0   | 43        | 4.5%    |
| 4.15.0  | 41        | 4.29%   |
| 5.3.0   | 36        | 3.77%   |
| 5.19.0  | 31        | 3.24%   |
| 6.2.0   | 27        | 2.82%   |
| 5.10.0  | 26        | 2.72%   |
| 5.0.0   | 20        | 2.09%   |
| 4.18.0  | 20        | 2.09%   |
| 6.1.0   | 15        | 1.57%   |
| 5.16.7  | 14        | 1.46%   |
| 5.10.14 | 13        | 1.36%   |
| 6.1.1   | 11        | 1.15%   |
| 6.2.6   | 9         | 0.94%   |
| 6.0.12  | 8         | 0.84%   |
| 4.19.0  | 8         | 0.84%   |
| 6.5.6   | 7         | 0.73%   |
| 6.5.0   | 6         | 0.63%   |
| 6.4.11  | 6         | 0.63%   |
| 5.3.16  | 5         | 0.52%   |
| 5.17.5  | 5         | 0.52%   |
| 6.4.10  | 4         | 0.42%   |
| 6.0.0   | 4         | 0.42%   |
| 5.9.16  | 4         | 0.42%   |
| 5.7.0   | 4         | 0.42%   |
| 5.15.15 | 4         | 0.42%   |
| 5.14.0  | 4         | 0.42%   |
| 6.4.6   | 3         | 0.31%   |
| 6.4.12  | 3         | 0.31%   |
| 6.2.12  | 3         | 0.31%   |
| 6.1.7   | 3         | 0.31%   |
| 5.9.8   | 3         | 0.31%   |
| 5.6.8   | 3         | 0.31%   |
| 5.6.19  | 3         | 0.31%   |
| 5.6.11  | 3         | 0.31%   |
| 5.3.8   | 3         | 0.31%   |
| 5.18.5  | 3         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 131       | 14%     |
| 5.15    | 116       | 12.39%  |
| 5.11    | 56        | 5.98%   |
| 5.8     | 53        | 5.66%   |
| 5.13    | 52        | 5.56%   |
| 5.10    | 50        | 5.34%   |
| 6.1     | 49        | 5.24%   |
| 6.2     | 45        | 4.81%   |
| 5.3     | 43        | 4.59%   |
| 4.15    | 41        | 4.38%   |
| 5.19    | 39        | 4.17%   |
| 5.16    | 26        | 2.78%   |
| 6.0     | 22        | 2.35%   |
| 5.0     | 21        | 2.24%   |
| 4.18    | 21        | 2.24%   |
| 6.5     | 20        | 2.14%   |
| 6.4     | 18        | 1.92%   |
| 5.18    | 17        | 1.82%   |
| 5.17    | 14        | 1.5%    |
| 5.14    | 14        | 1.5%    |
| 6.3     | 12        | 1.28%   |
| 5.9     | 12        | 1.28%   |
| 5.6     | 12        | 1.28%   |
| 5.7     | 11        | 1.18%   |
| 6.6     | 9         | 0.96%   |
| 4.19    | 9         | 0.96%   |
| 5.12    | 7         | 0.75%   |
| 5.5     | 4         | 0.43%   |
| 4.9     | 4         | 0.43%   |
| 5.2     | 2         | 0.21%   |
| 4.20    | 2         | 0.21%   |
| 4.4     | 1         | 0.11%   |
| 4.14    | 1         | 0.11%   |
| 4.13    | 1         | 0.11%   |
| 4.11    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 785       | 98%     |
| i686    | 10        | 1.25%   |
| aarch64 | 4         | 0.5%    |
| armv7l  | 2         | 0.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 403       | 47.69%  |
| KDE5             | 123       | 14.56%  |
| Unknown          | 97        | 11.48%  |
| X-Cinnamon       | 71        | 8.4%    |
| XFCE             | 49        | 5.8%    |
| KDE              | 22        | 2.6%    |
| MATE             | 21        | 2.49%   |
| Cinnamon         | 9         | 1.07%   |
| Pantheon         | 8         | 0.95%   |
| LXQt             | 8         | 0.95%   |
| Unity            | 5         | 0.59%   |
| LXDE             | 5         | 0.59%   |
| i3               | 5         | 0.59%   |
| Deepin           | 4         | 0.47%   |
| Hyprland         | 3         | 0.36%   |
| Budgie           | 3         | 0.36%   |
| xsession         | 1         | 0.12%   |
| sway             | 1         | 0.12%   |
| Openbox          | 1         | 0.12%   |
| lightdm-xsession | 1         | 0.12%   |
| KDE4             | 1         | 0.12%   |
| icewm            | 1         | 0.12%   |
| i3-with-shmlog   | 1         | 0.12%   |
| fluxbox          | 1         | 0.12%   |
| Enlightenment    | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 599       | 72.08%  |
| Wayland | 164       | 19.74%  |
| Unknown | 49        | 5.9%    |
| Tty     | 19        | 2.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 440       | 52.32%  |
| SDDM    | 110       | 13.08%  |
| GDM3    | 89        | 10.58%  |
| LightDM | 87        | 10.34%  |
| GDM     | 80        | 9.51%   |
| TDM     | 25        | 2.97%   |
| SLiM    | 4         | 0.48%   |
| Ly      | 2         | 0.24%   |
| LXDM    | 2         | 0.24%   |
| XDM     | 1         | 0.12%   |
| KDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_NZ   | 498       | 58.93%  |
| en_US   | 170       | 20.12%  |
| Unknown | 83        | 9.82%   |
| en_GB   | 40        | 4.73%   |
| C       | 23        | 2.72%   |
| en_AU   | 21        | 2.49%   |
| zh_CN   | 4         | 0.47%   |
| mi_NZ   | 2         | 0.24%   |
| de_DE   | 2         | 0.24%   |
| pt_BR   | 1         | 0.12%   |
| C.UTF8  | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 411       | 50%     |
| EFI  | 411       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 624       | 74.91%  |
| Btrfs   | 81        | 9.72%   |
| Overlay | 57        | 6.84%   |
| Unknown | 29        | 3.48%   |
| Tmpfs   | 20        | 2.4%    |
| Zfs     | 7         | 0.84%   |
| Xfs     | 7         | 0.84%   |
| Ext2    | 4         | 0.48%   |
| Ext3    | 2         | 0.24%   |
| XXXXXXX | 1         | 0.12%   |
| F2fs    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 442       | 53.64%  |
| GPT     | 309       | 37.5%   |
| MBR     | 73        | 8.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 708       | 85.92%  |
| Yes       | 116       | 14.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 613       | 74.85%  |
| Yes       | 206       | 25.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 178       | 22.22%  |
| ASUSTek Computer                     | 132       | 16.48%  |
| Gigabyte Technology                  | 87        | 10.86%  |
| Dell                                 | 84        | 10.49%  |
| Lenovo                               | 83        | 10.36%  |
| Acer                                 | 39        | 4.87%   |
| MSI                                  | 29        | 3.62%   |
| Intel                                | 28        | 3.5%    |
| Toshiba                              | 22        | 2.75%   |
| Apple                                | 22        | 2.75%   |
| ASRock                               | 20        | 2.5%    |
| Supermicro                           | 7         | 0.87%   |
| Google                               | 7         | 0.87%   |
| Unknown                              | 7         | 0.87%   |
| Sony                                 | 6         | 0.75%   |
| System76                             | 4         | 0.5%    |
| Samsung Electronics                  | 4         | 0.5%    |
| Raspberry Pi Foundation              | 4         | 0.5%    |
| IBM                                  | 4         | 0.5%    |
| Valve                                | 3         | 0.37%   |
| Alienware                            | 3         | 0.37%   |
| Pegatron                             | 2         | 0.25%   |
| Microsoft                            | 2         | 0.25%   |
| Kogan                                | 2         | 0.25%   |
| HUAWEI                               | 2         | 0.25%   |
| YJKC                                 | 1         | 0.12%   |
| TWG                                  | 1         | 0.12%   |
| Timi                                 | 1         | 0.12%   |
| The Warehouse Group                  | 1         | 0.12%   |
| Star Labs                            | 1         | 0.12%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.12%   |
| Qualcomm Technologies                | 1         | 0.12%   |
| OEM                                  | 1         | 0.12%   |
| Metabox                              | 1         | 0.12%   |
| Medion                               | 1         | 0.12%   |
| MediaVue                             | 1         | 0.12%   |
| JGINYUE                              | 1         | 0.12%   |
| Huanan                               | 1         | 0.12%   |
| eMachines                            | 1         | 0.12%   |
| DFI                                  | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| ASUS All Series                           | 9         | 1.12%   |
| Unknown                                   | 9         | 1.12%   |
| Gigabyte H77M-D3H                         | 6         | 0.75%   |
| Dell XPS 13 9360                          | 6         | 0.75%   |
| HP Notebook                               | 5         | 0.62%   |
| ASUS TUF Gaming X570-PLUS                 | 5         | 0.62%   |
| HP ProBook 6550b                          | 4         | 0.5%    |
| HP Pavilion dv6                           | 4         | 0.5%    |
| HP Pavilion 15                            | 4         | 0.5%    |
| HP EliteDesk 800 G1 SFF                   | 4         | 0.5%    |
| Valve Jupiter                             | 3         | 0.37%   |
| Toshiba Satellite L750                    | 3         | 0.37%   |
| MSI MS-7B89                               | 3         | 0.37%   |
| HP ProBook 4540s                          | 3         | 0.37%   |
| HP EliteBook 8560p                        | 3         | 0.37%   |
| HP EliteBook 840 G5                       | 3         | 0.37%   |
| HP Compaq 8200 Elite SFF PC               | 3         | 0.37%   |
| Gigabyte B75M-D3H                         | 3         | 0.37%   |
| Gigabyte B450M S2H                        | 3         | 0.37%   |
| Gigabyte 970A-D3P                         | 3         | 0.37%   |
| Dell OptiPlex 3010                        | 3         | 0.37%   |
| Dell Latitude E6430                       | 3         | 0.37%   |
| ASUS P8B75-M                              | 3         | 0.37%   |
| ASUS ASUS EXPERTBOOK P2451FA_P2451FA      | 3         | 0.37%   |
| ASRock B450M Steel Legend                 | 3         | 0.37%   |
| Acer Aspire F5-573G                       | 3         | 0.37%   |
| Toshiba TECRA Z50-A                       | 2         | 0.25%   |
| Toshiba Satellite C50-B                   | 2         | 0.25%   |
| System76 Oryx Pro                         | 2         | 0.25%   |
| MSI MS-7C91                               | 2         | 0.25%   |
| MSI MS-7C02                               | 2         | 0.25%   |
| MSI GE66 Raider 10SF                      | 2         | 0.25%   |
| Lenovo ThinkPad T460 20FMS2FR00           | 2         | 0.25%   |
| Lenovo ThinkPad T420 4180AQ3              | 2         | 0.25%   |
| Lenovo ThinkCentre M58p 7479RS2           | 2         | 0.25%   |
| Intel NUC8i7HVK                           | 2         | 0.25%   |
| HUAWEI BOHK-WAX9X                         | 2         | 0.25%   |
| HP ZBook Firefly 15 G7 Mobile Workstation | 2         | 0.25%   |
| HP Spectre x360 Convertible 15-eb0xxx     | 2         | 0.25%   |
| HP ProDesk 600 G1 SFF                     | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 44        | 5.49%   |
| HP EliteBook       | 31        | 3.87%   |
| ASUS ROG           | 27        | 3.37%   |
| HP ProBook         | 26        | 3.25%   |
| Acer Aspire        | 26        | 3.25%   |
| HP Pavilion        | 22        | 2.75%   |
| HP Compaq          | 21        | 2.62%   |
| Dell Latitude      | 21        | 2.62%   |
| ASUS PRIME         | 17        | 2.12%   |
| Toshiba Satellite  | 15        | 1.87%   |
| Dell XPS           | 13        | 1.62%   |
| Dell OptiPlex      | 13        | 1.62%   |
| Dell Inspiron      | 13        | 1.62%   |
| Dell Precision     | 12        | 1.5%    |
| ASUS TUF           | 12        | 1.5%    |
| HP EliteDesk       | 10        | 1.25%   |
| Lenovo ThinkCentre | 9         | 1.12%   |
| ASUS All           | 9         | 1.12%   |
| Unknown            | 9         | 1.12%   |
| HP ZBook           | 8         | 1%      |
| HP Laptop          | 7         | 0.87%   |
| ASUS VivoBook      | 7         | 0.87%   |
| Lenovo Yoga        | 6         | 0.75%   |
| HP ProLiant        | 6         | 0.75%   |
| Gigabyte H77M-D3H  | 6         | 0.75%   |
| ASUS ASUS          | 6         | 0.75%   |
| HP Spectre         | 5         | 0.62%   |
| HP Notebook        | 5         | 0.62%   |
| Toshiba PORTEGE    | 4         | 0.5%    |
| RPi Raspberry      | 4         | 0.5%    |
| Gigabyte B550M     | 4         | 0.5%    |
| Gigabyte B550      | 4         | 0.5%    |
| ASUS M5A97         | 4         | 0.5%    |
| Apple MacBookPro5  | 4         | 0.5%    |
| Acer TravelMate    | 4         | 0.5%    |
| Valve Jupiter      | 3         | 0.37%   |
| Toshiba TECRA      | 3         | 0.37%   |
| MSI MS-7B89        | 3         | 0.37%   |
| Lenovo IdeaPad     | 3         | 0.37%   |
| IBM System         | 3         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 104       | 12.98%  |
| 2018    | 69        | 8.61%   |
| 2019    | 65        | 8.11%   |
| 2020    | 64        | 7.99%   |
| 2011    | 64        | 7.99%   |
| 2017    | 55        | 6.87%   |
| 2013    | 47        | 5.87%   |
| 2022    | 44        | 5.49%   |
| 2021    | 44        | 5.49%   |
| 2014    | 43        | 5.37%   |
| 2016    | 40        | 4.99%   |
| 2015    | 36        | 4.49%   |
| 2010    | 36        | 4.49%   |
| 2009    | 29        | 3.62%   |
| 2008    | 29        | 3.62%   |
| 2023    | 12        | 1.5%    |
| 2007    | 8         | 1%      |
| Unknown | 6         | 0.75%   |
| 2005    | 3         | 0.37%   |
| 2006    | 2         | 0.25%   |
| 2004    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 393       | 49.06%  |
| Desktop        | 323       | 40.32%  |
| Mini pc        | 29        | 3.62%   |
| Convertible    | 24        | 3%      |
| All in one     | 13        | 1.62%   |
| Server         | 11        | 1.37%   |
| System on chip | 5         | 0.62%   |
| Tablet         | 3         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 738       | 91.34%  |
| Enabled  | 70        | 8.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 788       | 98.38%  |
| Yes  | 13        | 1.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 185       | 22.53%  |
| 4.01-8.0        | 182       | 22.17%  |
| 8.01-16.0       | 148       | 18.03%  |
| 3.01-4.0        | 120       | 14.62%  |
| 32.01-64.0      | 106       | 12.91%  |
| 64.01-256.0     | 35        | 4.26%   |
| 24.01-32.0      | 19        | 2.31%   |
| 1.01-2.0        | 15        | 1.83%   |
| 2.01-3.0        | 6         | 0.73%   |
| 0.51-1.0        | 4         | 0.49%   |
| More than 256.0 | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 282       | 30.99%  |
| 2.01-3.0   | 247       | 27.14%  |
| 4.01-8.0   | 141       | 15.49%  |
| 3.01-4.0   | 124       | 13.63%  |
| 8.01-16.0  | 47        | 5.16%   |
| 0.51-1.0   | 46        | 5.05%   |
| 16.01-24.0 | 12        | 1.32%   |
| 0.01-0.5   | 7         | 0.77%   |
| 24.01-32.0 | 3         | 0.33%   |
| 32.01-64.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 474       | 56.56%  |
| 2       | 213       | 25.42%  |
| 3       | 76        | 9.07%   |
| 4       | 37        | 4.42%   |
| 6       | 12        | 1.43%   |
| 5       | 12        | 1.43%   |
| 0       | 4         | 0.48%   |
| 7       | 3         | 0.36%   |
| 8       | 2         | 0.24%   |
| Unknown | 2         | 0.24%   |
| 410     | 1         | 0.12%   |
| 20      | 1         | 0.12%   |
| 9       | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 491       | 60.69%  |
| Yes       | 318       | 39.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 709       | 87.97%  |
| No        | 97        | 12.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 614       | 76.18%  |
| No        | 192       | 23.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 496       | 61.01%  |
| No        | 317       | 38.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| New Zealand | 801       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Auckland         | 393       | 46.51%  |
| Wellington       | 103       | 12.19%  |
| Christchurch     | 97        | 11.48%  |
| Hamilton         | 53        | 6.27%   |
| Tauranga         | 30        | 3.55%   |
| Dunedin          | 23        | 2.72%   |
| Palmerston North | 16        | 1.89%   |
| Whangarei        | 13        | 1.54%   |
| Nelson           | 13        | 1.54%   |
| Cambridge        | 11        | 1.3%    |
| Napier City      | 10        | 1.18%   |
| New Plymouth     | 9         | 1.07%   |
| Lower Hutt       | 8         | 0.95%   |
| Whanganui        | 7         | 0.83%   |
| Invercargill     | 7         | 0.83%   |
| Hastings         | 6         | 0.71%   |
| Rotorua          | 4         | 0.47%   |
| Masterton        | 3         | 0.36%   |
| Grafton          | 3         | 0.36%   |
| Ashburton        | 3         | 0.36%   |
| Queenstown       | 2         | 0.24%   |
| Otaki            | 2         | 0.24%   |
| Levin            | 2         | 0.24%   |
| Whatawhata       | 1         | 0.12%   |
| Westport         | 1         | 0.12%   |
| Wellsford        | 1         | 0.12%   |
| Waikanae         | 1         | 0.12%   |
| Waihi            | 1         | 0.12%   |
| Tutukaka         | 1         | 0.12%   |
| Stratford        | 1         | 0.12%   |
| Saint Andrews    | 1         | 0.12%   |
| Porirua          | 1         | 0.12%   |
| Paraparaumu      | 1         | 0.12%   |
| Pakuranga        | 1         | 0.12%   |
| Onekawa          | 1         | 0.12%   |
| Mount Maunganui  | 1         | 0.12%   |
| Mount Eden       | 1         | 0.12%   |
| Milton           | 1         | 0.12%   |
| Kerikeri         | 1         | 0.12%   |
| Katikati         | 1         | 0.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 219       | 399    | 18.5%   |
| Seagate                     | 208       | 362    | 17.57%  |
| WDC                         | 183       | 312    | 15.46%  |
| Crucial                     | 70        | 113    | 5.91%   |
| Toshiba                     | 64        | 80     | 5.41%   |
| Kingston                    | 46        | 69     | 3.89%   |
| SanDisk                     | 45        | 52     | 3.8%    |
| Intel                       | 45        | 60     | 3.8%    |
| Unknown                     | 37        | 54     | 3.13%   |
| Hitachi                     | 29        | 40     | 2.45%   |
| SK hynix                    | 28        | 38     | 2.36%   |
| Micron Technology           | 21        | 26     | 1.77%   |
| HGST                        | 20        | 24     | 1.69%   |
| A-DATA Technology           | 20        | 24     | 1.69%   |
| Micron/Crucial Technology   | 12        | 13     | 1.01%   |
| Team                        | 9         | 10     | 0.76%   |
| China                       | 9         | 11     | 0.76%   |
| Apple                       | 8         | 9      | 0.68%   |
| KIOXIA                      | 7         | 9      | 0.59%   |
| LITEON                      | 6         | 6      | 0.51%   |
| ASMT                        | 6         | 6      | 0.51%   |
| TO Exter                    | 5         | 5      | 0.42%   |
| KingSpec                    | 5         | 5      | 0.42%   |
| Apacer                      | 5         | 6      | 0.42%   |
| Transcend                   | 4         | 4      | 0.34%   |
| Silicon Motion              | 4         | 6      | 0.34%   |
| OCZ                         | 4         | 4      | 0.34%   |
| Gigabyte Technology         | 4         | 5      | 0.34%   |
| External                    | 4         | 5      | 0.34%   |
| XPG                         | 3         | 3      | 0.25%   |
| Lexar                       | 3         | 3      | 0.25%   |
| Kingston Technology Company | 3         | 3      | 0.25%   |
| JMicron Technology          | 3         | 3      | 0.25%   |
| Hewlett-Packard             | 3         | 6      | 0.25%   |
| Corsair                     | 3         | 5      | 0.25%   |
| ShiJi                       | 2         | 2      | 0.17%   |
| ROG                         | 2         | 2      | 0.17%   |
| Phison                      | 2         | 2      | 0.17%   |
| O2 Micro                    | 2         | 2      | 0.17%   |
| Netac                       | 2         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 15        | 1.1%    |
| Samsung SSD 850 EVO 500GB                           | 15        | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.96%   |
| Seagate Expansion Desk 8TB                          | 12        | 0.88%   |
| Crucial CT240BX500SSD1 240GB                        | 12        | 0.88%   |
| Seagate Expansion 1TB                               | 11        | 0.81%   |
| Samsung SSD 980 1TB                                 | 11        | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 11        | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                     | 9         | 0.66%   |
| Samsung SSD 870 EVO 1TB                             | 9         | 0.66%   |
| Samsung SSD 850 EVO 250GB                           | 9         | 0.66%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.66%   |
| Seagate ST500DM002-1BD142 500GB                     | 8         | 0.59%   |
| Seagate ST31000528AS 1TB                            | 8         | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 0.59%   |
| Samsung NVMe SSD Drive 512GB                        | 8         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 8         | 0.59%   |
| Crucial CT500MX500SSD1 500GB                        | 8         | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB                      | 7         | 0.52%   |
| Seagate ST2000DM001-1CH164 2TB                      | 7         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                      | 7         | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7         | 0.52%   |
| Kingston SV300S37A240G 240GB SSD                    | 7         | 0.52%   |
| Intel NVMe SSD Drive 512GB                          | 7         | 0.52%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 6         | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 0.44%   |
| Seagate ST9500325AS 500GB                           | 6         | 0.44%   |
| Samsung SSD 980 PRO 1TB                             | 6         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 6         | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 6         | 0.44%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 6         | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 6         | 0.44%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.44%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.44%   |
| HGST HTS721010A9E630 1TB                            | 6         | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 6         | 0.44%   |
| Crucial CT1000BX500SSD1 1TB                         | 6         | 0.44%   |
| Unknown SD/MMC/MS PRO 256GB                         | 5         | 0.37%   |
| Unknown MMC Card  64GB                              | 5         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 199       | 344    | 41.72%  |
| WDC                 | 158       | 259    | 33.12%  |
| Toshiba             | 34        | 46     | 7.13%   |
| Hitachi             | 29        | 40     | 6.08%   |
| HGST                | 20        | 24     | 4.19%   |
| Unknown             | 5         | 9      | 1.05%   |
| TO Exter            | 5         | 5      | 1.05%   |
| Samsung Electronics | 5         | 7      | 1.05%   |
| External            | 4         | 5      | 0.84%   |
| Apple               | 4         | 4      | 0.84%   |
| JMicron Technology  | 3         | 3      | 0.63%   |
| ASMT                | 3         | 3      | 0.63%   |
| Fujitsu             | 2         | 2      | 0.42%   |
| USB3.0              | 1         | 1      | 0.21%   |
| USB                 | 1         | 2      | 0.21%   |
| StoreJet            | 1         | 1      | 0.21%   |
| QUANTUM             | 1         | 1      | 0.21%   |
| HGST HTS            | 1         | 1      | 0.21%   |
| Ext Hard            | 1         | 2      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 111       | 167    | 28.68%  |
| Crucial             | 61        | 99     | 15.76%  |
| Kingston            | 32        | 48     | 8.27%   |
| SanDisk             | 28        | 33     | 7.24%   |
| Intel               | 22        | 30     | 5.68%   |
| WDC                 | 17        | 33     | 4.39%   |
| A-DATA Technology   | 16        | 19     | 4.13%   |
| Micron Technology   | 14        | 18     | 3.62%   |
| Team                | 9         | 10     | 2.33%   |
| China               | 9         | 11     | 2.33%   |
| Toshiba             | 8         | 9      | 2.07%   |
| Seagate             | 6         | 9      | 1.55%   |
| LITEON              | 5         | 5      | 1.29%   |
| KingSpec            | 5         | 5      | 1.29%   |
| Apacer              | 5         | 6      | 1.29%   |
| SK hynix            | 4         | 4      | 1.03%   |
| OCZ                 | 4         | 4      | 1.03%   |
| Apple               | 4         | 5      | 1.03%   |
| Transcend           | 3         | 3      | 0.78%   |
| Lexar               | 3         | 3      | 0.78%   |
| Gigabyte Technology | 3         | 3      | 0.78%   |
| Corsair             | 3         | 5      | 0.78%   |
| Hewlett-Packard     | 2         | 5      | 0.52%   |
| ASMT                | 2         | 2      | 0.52%   |
| Timetec             | 1         | 1      | 0.26%   |
| T-FORCE             | 1         | 1      | 0.26%   |
| OCZ-VERTEX3         | 1         | 1      | 0.26%   |
| OASDX               | 1         | 1      | 0.26%   |
| Netac               | 1         | 1      | 0.26%   |
| LITEONIT            | 1         | 3      | 0.26%   |
| Innodisk            | 1         | 1      | 0.26%   |
| GAMER               | 1         | 1      | 0.26%   |
| FreeNAS             | 1         | 36     | 0.26%   |
| FreeBSD             | 1         | 372    | 0.26%   |
| Dell                | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 391       | 759    | 36.64%  |
| SSD     | 344       | 955    | 32.24%  |
| NVMe    | 286       | 458    | 26.8%   |
| MMC     | 34        | 45     | 3.19%   |
| Unknown | 12        | 14     | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 586       | 1629   | 60.35%  |
| NVMe | 286       | 457    | 29.45%  |
| SAS  | 65        | 100    | 6.69%   |
| MMC  | 34        | 45     | 3.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 433       | 1110   | 53.13%  |
| 0.51-1.0   | 237       | 375    | 29.08%  |
| 1.01-2.0   | 78        | 126    | 9.57%   |
| 3.01-4.0   | 28        | 48     | 3.44%   |
| 4.01-10.0  | 22        | 29     | 2.7%    |
| 2.01-3.0   | 13        | 15     | 1.6%    |
| 10.01-20.0 | 3         | 9      | 0.37%   |
| 20.01-50.0 | 1         | 2      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 204       | 23.67%  |
| 251-500        | 180       | 20.88%  |
| 501-1000       | 134       | 15.55%  |
| 1001-2000      | 84        | 9.74%   |
| 1-20           | 72        | 8.35%   |
| More than 3000 | 61        | 7.08%   |
| 2001-3000      | 46        | 5.34%   |
| 51-100         | 40        | 4.64%   |
| Unknown        | 22        | 2.55%   |
| 21-50          | 19        | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 327       | 35.93%  |
| 21-50          | 154       | 16.92%  |
| 101-250        | 99        | 10.88%  |
| 51-100         | 95        | 10.44%  |
| 501-1000       | 70        | 7.69%   |
| 251-500        | 65        | 7.14%   |
| 1001-2000      | 37        | 4.07%   |
| Unknown        | 22        | 2.42%   |
| More than 3000 | 21        | 2.31%   |
| 2001-3000      | 20        | 2.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKX-00HPJT0 752GB                | 2         | 2      | 2.41%   |
| WDC WD5000AAKX-001CA0 500GB                 | 2         | 3      | 2.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 2         | 2      | 2.41%   |
| Seagate ST3500418AS 500GB                   | 2         | 2      | 2.41%   |
| Seagate ST31000528AS 1TB                    | 2         | 2      | 2.41%   |
| Samsung Electronics SSD 980 1TB             | 2         | 2      | 2.41%   |
| Samsung Electronics SSD 870 EVO 1TB         | 2         | 2      | 2.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD            | 1         | 1      | 1.2%    |
| WDC WD3200AAKS-00UU3A0 320GB                | 1         | 1      | 1.2%    |
| WDC WD2003FZEX-00Z4SA0 2TB                  | 1         | 1      | 1.2%    |
| WDC WD15EARS-00S0XB0 1TB                    | 1         | 1      | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1      | 1.2%    |
| WDC WD10EFRX-68FYTN0 1TB                    | 1         | 3      | 1.2%    |
| WDC WD10EARS-003BB1 1TB                     | 1         | 1      | 1.2%    |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 2      | 1.2%    |
| USB3.0 Extemal HDD 2TB                      | 1         | 1      | 1.2%    |
| Toshiba MQ01ABD075 752GB                    | 1         | 1      | 1.2%    |
| Toshiba MQ01ABD050 500GB                    | 1         | 1      | 1.2%    |
| Toshiba MK5076GSX 500GB                     | 1         | 1      | 1.2%    |
| Toshiba MK3261GSYN 320GB                    | 1         | 1      | 1.2%    |
| Toshiba MK3256GSY 320GB                     | 1         | 1      | 1.2%    |
| SK hynix SC308 SATA 128GB SSD               | 1         | 1      | 1.2%    |
| SK hynix HFS256G32MND-2900A 256GB SSD       | 1         | 1      | 1.2%    |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 3      | 1.2%    |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB     | 1         | 1      | 1.2%    |
| ShiJi 512GB M.2-NVMe                        | 1         | 1      | 1.2%    |
| Seagate ST9500420ASG 500GB                  | 1         | 1      | 1.2%    |
| Seagate ST9500420AS 500GB                   | 1         | 1      | 1.2%    |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 1.2%    |
| Seagate ST8000VN0022-2EL112 8TB             | 1         | 3      | 1.2%    |
| Seagate ST500NM0011 500GB                   | 1         | 2      | 1.2%    |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.2%    |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 1.2%    |
| Seagate ST4000DX001-1CE168 4TB              | 1         | 1      | 1.2%    |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.2%    |
| Seagate ST3200822A 200GB                    | 1         | 1      | 1.2%    |
| Seagate ST31000524AS 1TB                    | 1         | 1      | 1.2%    |
| Seagate ST3000DM001-9YN166 3TB              | 1         | 1      | 1.2%    |
| Seagate ST2000DX002-2DV164 2TB              | 1         | 1      | 1.2%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 25     | 24.05%  |
| WDC                 | 15        | 19     | 18.99%  |
| Samsung Electronics | 6         | 6      | 7.59%   |
| HGST                | 6         | 7      | 7.59%   |
| Toshiba             | 5         | 5      | 6.33%   |
| Crucial             | 5         | 6      | 6.33%   |
| Intel               | 4         | 4      | 5.06%   |
| SK hynix            | 3         | 6      | 3.8%    |
| SanDisk             | 3         | 3      | 3.8%    |
| Hitachi             | 3         | 3      | 3.8%    |
| Micron Technology   | 2         | 2      | 2.53%   |
| ASMT                | 2         | 2      | 2.53%   |
| USB3.0              | 1         | 1      | 1.27%   |
| ShiJi               | 1         | 1      | 1.27%   |
| OCZ                 | 1         | 1      | 1.27%   |
| Innodisk            | 1         | 1      | 1.27%   |
| HGST HTS            | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 19        | 25     | 37.25%  |
| WDC      | 14        | 18     | 27.45%  |
| HGST     | 6         | 7      | 11.76%  |
| Toshiba  | 5         | 5      | 9.8%    |
| Hitachi  | 3         | 3      | 5.88%   |
| USB3.0   | 1         | 1      | 1.96%   |
| HGST HTS | 1         | 1      | 1.96%   |
| ASMT     | 1         | 1      | 1.96%   |
| Apple    | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 62     | 63.64%  |
| SSD  | 20        | 21     | 25.97%  |
| NVMe | 8         | 11     | 10.39%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 495       | 1104   | 56.25%  |
| Works    | 309       | 1031   | 35.11%  |
| Malfunc  | 74        | 94     | 8.41%   |
| Failed   | 1         | 1      | 0.11%   |
| Limited  | 1         | 1      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 507       | 48.75%  |
| AMD                          | 169       | 16.25%  |
| Samsung Electronics          | 131       | 12.6%   |
| SanDisk                      | 28        | 2.69%   |
| Toshiba America Info Systems | 24        | 2.31%   |
| SK hynix                     | 24        | 2.31%   |
| Nvidia                       | 20        | 1.92%   |
| Micron/Crucial Technology    | 20        | 1.92%   |
| Kingston Technology Company  | 17        | 1.63%   |
| JMicron Technology           | 16        | 1.54%   |
| ASMedia Technology           | 13        | 1.25%   |
| Marvell Technology Group     | 12        | 1.15%   |
| Micron Technology            | 9         | 0.87%   |
| LSI Logic / Symbios Logic    | 7         | 0.67%   |
| Silicon Motion               | 6         | 0.58%   |
| Phison Electronics           | 6         | 0.58%   |
| KIOXIA                       | 6         | 0.58%   |
| Seagate Technology           | 5         | 0.48%   |
| ADATA Technology             | 4         | 0.38%   |
| Hewlett-Packard              | 3         | 0.29%   |
| Realtek Semiconductor        | 2         | 0.19%   |
| O2 Micro                     | 2         | 0.19%   |
| Broadcom / LSI               | 2         | 0.19%   |
| VIA Technologies             | 1         | 0.1%    |
| Union Memory (Shenzhen)      | 1         | 0.1%    |
| Silicon Image                | 1         | 0.1%    |
| Shenzhen Longsys Electronics | 1         | 0.1%    |
| Netac Technology             | 1         | 0.1%    |
| MAXIO Technology (Hangzhou)  | 1         | 0.1%    |
| Lite-On Technology           | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 105       | 8.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 57        | 4.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 40        | 3.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 37        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 32        | 2.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 30        | 2.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 29        | 2.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 27        | 2.23%   |
| AMD 400 Series Chipset SATA Controller                                           | 24        | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 22        | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 21        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 20        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 20        | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 1.57%   |
| Intel SATA Controller [RAID mode]                                                | 19        | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                           | 19        | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                            | 17        | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 16        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 16        | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 0.99%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 12        | 0.99%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 11        | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 0.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 0.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 9         | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 9         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 9         | 0.74%   |
| AMD 300 Series Chipset SATA Controller                                           | 9         | 0.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 8         | 0.66%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 8         | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                               | 8         | 0.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 0.66%   |
| Intel SSD 660P Series                                                            | 8         | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 579       | 55.04%  |
| NVMe | 289       | 27.47%  |
| IDE  | 110       | 10.46%  |
| RAID | 69        | 6.56%   |
| SAS  | 4         | 0.38%   |
| SCSI | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 590       | 73.66%  |
| AMD      | 205       | 25.59%  |
| ARM      | 5         | 0.62%   |
| QUALCOMM | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 11        | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 1%      |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.75%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 6         | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 5         | 0.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.62%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.62%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 0.62%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.62%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 0.62%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 5         | 0.62%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 4         | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.5%    |
| Intel Core i7-10700 CPU @ 2.90GHz             | 4         | 0.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 0.5%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.5%    |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 4         | 0.5%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 4         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 199       | 24.84%  |
| Intel Core i7           | 172       | 21.47%  |
| Other                   | 50        | 6.24%   |
| AMD Ryzen 5             | 43        | 5.37%   |
| Intel Core i3           | 39        | 4.87%   |
| AMD Ryzen 7             | 38        | 4.74%   |
| Intel Core 2 Duo        | 35        | 4.37%   |
| Intel Xeon              | 28        | 3.5%    |
| Intel Celeron           | 27        | 3.37%   |
| AMD Ryzen 9             | 20        | 2.5%    |
| AMD FX                  | 18        | 2.25%   |
| Intel Pentium           | 13        | 1.62%   |
| AMD A6                  | 12        | 1.5%    |
| Intel Core 2 Quad       | 11        | 1.37%   |
| Intel Atom              | 9         | 1.12%   |
| AMD Ryzen 3             | 8         | 1%      |
| AMD A8                  | 7         | 0.87%   |
| AMD Ryzen 5 PRO         | 6         | 0.75%   |
| AMD A4                  | 6         | 0.75%   |
| Intel Core i9           | 5         | 0.62%   |
| AMD Ryzen Threadripper  | 5         | 0.62%   |
| AMD E2                  | 5         | 0.62%   |
| AMD Athlon 64 X2        | 5         | 0.62%   |
| AMD Athlon II X2        | 4         | 0.5%    |
| Intel Pentium Silver    | 2         | 0.25%   |
| Intel Pentium M         | 2         | 0.25%   |
| Intel Pentium Dual-Core | 2         | 0.25%   |
| AMD Ryzen 7 PRO         | 2         | 0.25%   |
| AMD Phenom II X6        | 2         | 0.25%   |
| AMD Phenom II X4        | 2         | 0.25%   |
| AMD Opteron             | 2         | 0.25%   |
| AMD E1                  | 2         | 0.25%   |
| AMD E                   | 2         | 0.25%   |
| AMD Athlon II X4        | 2         | 0.25%   |
| AMD A10                 | 2         | 0.25%   |
| QUALCOMM AArch64        | 1         | 0.12%   |
| Intel Xeon Silver       | 1         | 0.12%   |
| Intel Pentium Dual      | 1         | 0.12%   |
| Intel Pentium 4         | 1         | 0.12%   |
| Intel Genuine           | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 305       | 37.98%  |
| 2      | 275       | 34.25%  |
| 6      | 84        | 10.46%  |
| 8      | 67        | 8.34%   |
| 12     | 22        | 2.74%   |
| 10     | 11        | 1.37%   |
| 1      | 11        | 1.37%   |
| 14     | 9         | 1.12%   |
| 16     | 7         | 0.87%   |
| 3      | 6         | 0.75%   |
| 20     | 3         | 0.37%   |
| 24     | 2         | 0.25%   |
| 64     | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 788       | 98.38%  |
| 2      | 12        | 1.5%    |
| 3      | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 553       | 68.95%  |
| 1      | 248       | 30.92%  |
| 8      | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 787       | 97.28%  |
| Unknown        | 19        | 2.35%   |
| 32-bit         | 3         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 30.51%  |
| 0x306a9    | 50        | 5.96%   |
| 0x206a7    | 49        | 5.84%   |
| 0x306c3    | 28        | 3.34%   |
| 0x1067a    | 24        | 2.86%   |
| 0x806ea    | 19        | 2.26%   |
| 0x806e9    | 18        | 2.15%   |
| 0x806ec    | 16        | 1.91%   |
| 0x906e9    | 15        | 1.79%   |
| 0x406e3    | 15        | 1.79%   |
| 0x08701021 | 15        | 1.79%   |
| 0x20655    | 12        | 1.43%   |
| 0x506e3    | 11        | 1.31%   |
| 0x40651    | 11        | 1.31%   |
| 0xa0652    | 9         | 1.07%   |
| 0x106e5    | 9         | 1.07%   |
| 0x0a50000c | 9         | 1.07%   |
| 0x07030105 | 9         | 1.07%   |
| 0x06000852 | 9         | 1.07%   |
| 0x30678    | 8         | 0.95%   |
| 0x10676    | 8         | 0.95%   |
| 0x906ea    | 7         | 0.83%   |
| 0x506c9    | 7         | 0.83%   |
| 0x306d4    | 7         | 0.83%   |
| 0x0a50000d | 7         | 0.83%   |
| 0x08108109 | 7         | 0.83%   |
| 0x0800820d | 7         | 0.83%   |
| 0xa0655    | 6         | 0.72%   |
| 0x906a4    | 6         | 0.72%   |
| 0x806c1    | 6         | 0.72%   |
| 0x0a601203 | 6         | 0.72%   |
| 0x06001119 | 6         | 0.72%   |
| 0x906a3    | 5         | 0.6%    |
| 0x806eb    | 5         | 0.6%    |
| 0x6fb      | 5         | 0.6%    |
| 0x106a5    | 5         | 0.6%    |
| 0x08600106 | 5         | 0.6%    |
| 0x08001137 | 5         | 0.6%    |
| 0x6fd      | 4         | 0.48%   |
| 0x406c4    | 4         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 126       | 15.73%  |
| IvyBridge        | 72        | 8.99%   |
| SandyBridge      | 67        | 8.36%   |
| Haswell          | 62        | 7.74%   |
| Penryn           | 44        | 5.49%   |
| Skylake          | 42        | 5.24%   |
| Zen 3            | 35        | 4.37%   |
| Zen 2            | 35        | 4.37%   |
| Unknown          | 33        | 4.12%   |
| CometLake        | 28        | 3.5%    |
| Zen+             | 23        | 2.87%   |
| Silvermont       | 23        | 2.87%   |
| Piledriver       | 22        | 2.75%   |
| Westmere         | 21        | 2.62%   |
| Nehalem          | 17        | 2.12%   |
| Alderlake Hybrid | 15        | 1.87%   |
| Zen              | 14        | 1.75%   |
| Puma             | 13        | 1.62%   |
| TigerLake        | 12        | 1.5%    |
| K10              | 12        | 1.5%    |
| Broadwell        | 11        | 1.37%   |
| Excavator        | 10        | 1.25%   |
| Core             | 10        | 1.25%   |
| IceLake          | 8         | 1%      |
| Goldmont         | 8         | 1%      |
| K8 Hammer        | 6         | 0.75%   |
| Jaguar           | 6         | 0.75%   |
| Bulldozer        | 5         | 0.62%   |
| Bonnell          | 5         | 0.62%   |
| Goldmont plus    | 4         | 0.5%    |
| Bobcat           | 4         | 0.5%    |
| Tremont          | 3         | 0.37%   |
| P6               | 2         | 0.25%   |
| NetBurst         | 1         | 0.12%   |
| K8 & K10 hybrid  | 1         | 0.12%   |
| K10 Llano        | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 437       | 46.29%  |
| Nvidia                     | 248       | 26.27%  |
| AMD                        | 244       | 25.85%  |
| Matrox Electronics Systems | 11        | 1.17%   |
| ASPEED Technology          | 4         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 4.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 3.26%   |
| Intel UHD Graphics 620                                                                   | 21        | 2.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 1.94%   |
| Intel HD Graphics 630                                                                    | 19        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17        | 1.73%   |
| Intel HD Graphics 620                                                                    | 17        | 1.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 1.22%   |
| Intel HD Graphics 530                                                                    | 12        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.92%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 8         | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 8         | 0.82%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7         | 0.71%   |
| Intel HD Graphics 500                                                                    | 7         | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7         | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 0.61%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.61%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 0.61%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.61%   |
| AMD Raphael                                                                              | 6         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 312       | 38.57%  |
| 1 x AMD                 | 180       | 22.25%  |
| 1 x Nvidia              | 141       | 17.43%  |
| Intel + Nvidia          | 83        | 10.26%  |
| Intel + AMD             | 29        | 3.58%   |
| 2 x AMD                 | 21        | 2.6%    |
| AMD + Nvidia            | 14        | 1.73%   |
| 1 x Matrox              | 10        | 1.24%   |
| Other                   | 7         | 0.87%   |
| 2 x Nvidia              | 6         | 0.74%   |
| Nvidia + ASPEED         | 2         | 0.25%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.12%   |
| 2 x Intel               | 1         | 0.12%   |
| AMD + Matrox            | 1         | 0.12%   |
| AMD + ASPEED            | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 639       | 78.6%   |
| Proprietary | 144       | 17.71%  |
| Unknown     | 30        | 3.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 468       | 56.32%  |
| 1.01-2.0   | 84        | 10.11%  |
| 0.01-0.5   | 83        | 9.99%   |
| 0.51-1.0   | 62        | 7.46%   |
| 3.01-4.0   | 48        | 5.78%   |
| 7.01-8.0   | 36        | 4.33%   |
| 5.01-6.0   | 22        | 2.65%   |
| 8.01-16.0  | 20        | 2.41%   |
| 2.01-3.0   | 6         | 0.72%   |
| 32.01-64.0 | 1         | 0.12%   |
| 16.01-24.0 | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 120       | 13.04%  |
| AU Optronics            | 85        | 9.24%   |
| Dell                    | 73        | 7.93%   |
| LG Display              | 69        | 7.5%    |
| AOC                     | 68        | 7.39%   |
| Chimei Innolux          | 65        | 7.07%   |
| Goldstar                | 64        | 6.96%   |
| BOE                     | 50        | 5.43%   |
| Philips                 | 37        | 4.02%   |
| Hewlett-Packard         | 27        | 2.93%   |
| ViewSonic               | 26        | 2.83%   |
| Sharp                   | 18        | 1.96%   |
| Chi Mei Optoelectronics | 18        | 1.96%   |
| Sony                    | 16        | 1.74%   |
| Apple                   | 16        | 1.74%   |
| Acer                    | 15        | 1.63%   |
| Lenovo                  | 14        | 1.52%   |
| Panasonic               | 13        | 1.41%   |
| Ancor Communications    | 12        | 1.3%    |
| Denver                  | 10        | 1.09%   |
| BenQ                    | 10        | 1.09%   |
| MiTAC                   | 9         | 0.98%   |
| PANDA                   | 8         | 0.87%   |
| InfoVision              | 8         | 0.87%   |
| LG Electronics          | 4         | 0.43%   |
| ASUSTek Computer        | 4         | 0.43%   |
| Unknown                 | 3         | 0.33%   |
| InnoLux Display         | 3         | 0.33%   |
| Gigabyte Technology     | 3         | 0.33%   |
| Yamaha                  | 2         | 0.22%   |
| Valve                   | 2         | 0.22%   |
| Unknown (AAA)           | 2         | 0.22%   |
| Toshiba                 | 2         | 0.22%   |
| SANYO                   | 2         | 0.22%   |
| Quanta Display          | 2         | 0.22%   |
| PRISM+                  | 2         | 0.22%   |
| Konka                   | 2         | 0.22%   |
| HannStar                | 2         | 0.22%   |
| Unknown                 | 2         | 0.22%   |
| Wacom                   | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 7         | 0.71%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 7         | 0.71%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 6         | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 0.61%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                         | 6         | 0.61%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 5         | 0.51%   |
| MiTAC MStar Demo SZM0030 3840x2160 708x398mm 32.0-inch                   | 5         | 0.51%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch            | 4         | 0.41%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 4         | 0.41%   |
| Denver PGM270 LHC2700 2560x1440 597x336mm 27.0-inch                      | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.41%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 4         | 0.41%   |
| Sony TV SNYEE01 1920x1080                                                | 3         | 0.31%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.31%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 3         | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.31%   |
| Samsung Electronics LS27AG32x SAM71DC 1920x1080 597x336mm 27.0-inch      | 3         | 0.31%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 3         | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 3         | 0.31%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.31%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.31%   |
| Denver UWQHD-100-C LHC3400 3440x1440 795x334mm 33.9-inch                 | 3         | 0.31%   |
| Dell P2416D DELA0C3 2560x1440 527x296mm 23.8-inch                        | 3         | 0.31%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                        | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.31%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                          | 3         | 0.31%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                          | 3         | 0.31%   |
| AOC 2367 AOC2367 1920x1080 509x286mm 23.0-inch                           | 3         | 0.31%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                           | 3         | 0.31%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 3         | 0.31%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 3         | 0.31%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch            | 2         | 0.2%    |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch                 | 2         | 0.2%    |
| ViewSonic VA702-3SERIES VSCB51D 1280x1024 338x270mm 17.0-inch            | 2         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 373       | 41.86%  |
| 1366x768 (WXGA)    | 123       | 13.8%   |
| 3840x2160 (4K)     | 96        | 10.77%  |
| 2560x1440 (QHD)    | 45        | 5.05%   |
| 1600x900 (HD+)     | 40        | 4.49%   |
| 1680x1050 (WSXGA+) | 30        | 3.37%   |
| 1280x1024 (SXGA)   | 25        | 2.81%   |
| 1440x900 (WXGA+)   | 21        | 2.36%   |
| 3440x1440          | 20        | 2.24%   |
| 1280x800 (WXGA)    | 18        | 2.02%   |
| 1920x1200 (WUXGA)  | 15        | 1.68%   |
| Unknown            | 14        | 1.57%   |
| 3840x1080          | 9         | 1.01%   |
| 2560x1600          | 6         | 0.67%   |
| 1360x768           | 6         | 0.67%   |
| 2880x1800          | 5         | 0.56%   |
| 2560x1080          | 5         | 0.56%   |
| 3200x1800 (QHD+)   | 4         | 0.45%   |
| 1024x600           | 4         | 0.45%   |
| 3840x1600          | 3         | 0.34%   |
| 1920x540           | 3         | 0.34%   |
| 800x1280           | 2         | 0.22%   |
| 3456x2160          | 2         | 0.22%   |
| 2288x1287          | 2         | 0.22%   |
| 1600x1200          | 2         | 0.22%   |
| 1024x768 (XGA)     | 2         | 0.22%   |
| 7680x1080          | 1         | 0.11%   |
| 6720x1080          | 1         | 0.11%   |
| 5760x1080          | 1         | 0.11%   |
| 3840x2400          | 1         | 0.11%   |
| 3840x1200          | 1         | 0.11%   |
| 3360x1080          | 1         | 0.11%   |
| 3200x2000          | 1         | 0.11%   |
| 3040x1050          | 1         | 0.11%   |
| 2960x1050          | 1         | 0.11%   |
| 2880x1920          | 1         | 0.11%   |
| 2800x1752          | 1         | 0.11%   |
| 2736x1824          | 1         | 0.11%   |
| 2560x1024          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 187       | 20.17%  |
| 27      | 78        | 8.41%   |
| 13      | 69        | 7.44%   |
| 14      | 67        | 7.23%   |
| 23      | 66        | 7.12%   |
| 21      | 66        | 7.12%   |
| 24      | 65        | 7.01%   |
| 17      | 50        | 5.39%   |
| Unknown | 44        | 4.75%   |
| 31      | 35        | 3.78%   |
| 22      | 22        | 2.37%   |
| 19      | 22        | 2.37%   |
| 20      | 18        | 1.94%   |
| 84      | 14        | 1.51%   |
| 34      | 14        | 1.51%   |
| 72      | 12        | 1.29%   |
| 18      | 9         | 0.97%   |
| 12      | 9         | 0.97%   |
| 32      | 8         | 0.86%   |
| 16      | 8         | 0.86%   |
| 11      | 7         | 0.76%   |
| 40      | 6         | 0.65%   |
| 10      | 6         | 0.65%   |
| 35      | 5         | 0.54%   |
| 52      | 4         | 0.43%   |
| 46      | 4         | 0.43%   |
| 37      | 4         | 0.43%   |
| 29      | 3         | 0.32%   |
| 26      | 3         | 0.32%   |
| 142     | 2         | 0.22%   |
| 33      | 2         | 0.22%   |
| 28      | 2         | 0.22%   |
| 25      | 2         | 0.22%   |
| 7       | 2         | 0.22%   |
| 95      | 1         | 0.11%   |
| 67      | 1         | 0.11%   |
| 65      | 1         | 0.11%   |
| 60      | 1         | 0.11%   |
| 55      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 303       | 33.44%  |
| 501-600        | 186       | 20.53%  |
| 401-500        | 125       | 13.8%   |
| 201-300        | 56        | 6.18%   |
| 601-700        | 55        | 6.07%   |
| 351-400        | 51        | 5.63%   |
| Unknown        | 44        | 4.86%   |
| 701-800        | 26        | 2.87%   |
| 1501-2000      | 25        | 2.76%   |
| 801-900        | 16        | 1.77%   |
| 1001-1500      | 14        | 1.55%   |
| More than 2000 | 2         | 0.22%   |
| 1-100          | 2         | 0.22%   |
| 901-1000       | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 597       | 74.16%  |
| 16/10   | 101       | 12.55%  |
| Unknown | 37        | 4.6%    |
| 5/4     | 24        | 2.98%   |
| 21/9    | 24        | 2.98%   |
| 4/3     | 7         | 0.87%   |
| 3/2     | 5         | 0.62%   |
| 32/9    | 4         | 0.5%    |
| 1.00    | 2         | 0.25%   |
| 0.67    | 2         | 0.25%   |
| 6/5     | 1         | 0.12%   |
| 0.45    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 184       | 20.24%  |
| 201-250        | 179       | 19.69%  |
| 81-90          | 107       | 11.77%  |
| 301-350        | 79        | 8.69%   |
| 351-500        | 69        | 7.59%   |
| 151-200        | 57        | 6.27%   |
| Unknown        | 44        | 4.84%   |
| 121-130        | 35        | 3.85%   |
| More than 1000 | 34        | 3.74%   |
| 71-80          | 30        | 3.3%    |
| 141-150        | 20        | 2.2%    |
| 501-1000       | 19        | 2.09%   |
| 251-300        | 18        | 1.98%   |
| 111-120        | 9         | 0.99%   |
| 61-70          | 7         | 0.77%   |
| 51-60          | 7         | 0.77%   |
| 41-50          | 6         | 0.66%   |
| 1-40           | 2         | 0.22%   |
| 131-140        | 2         | 0.22%   |
| 91-100         | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 298       | 33.48%  |
| 101-120       | 233       | 26.18%  |
| 121-160       | 215       | 24.16%  |
| 161-240       | 48        | 5.39%   |
| Unknown       | 44        | 4.94%   |
| 1-50          | 31        | 3.48%   |
| More than 240 | 21        | 2.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 611       | 72.91%  |
| 2     | 169       | 20.17%  |
| 0     | 33        | 3.94%   |
| 3     | 21        | 2.51%   |
| 4     | 4         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 440       | 35.6%   |
| Realtek Semiconductor           | 395       | 31.96%  |
| Qualcomm Atheros                | 113       | 9.14%   |
| Broadcom                        | 72        | 5.83%   |
| MediaTek                        | 25        | 2.02%   |
| TP-Link                         | 23        | 1.86%   |
| Ralink                          | 17        | 1.38%   |
| Nvidia                          | 17        | 1.38%   |
| Broadcom Limited                | 14        | 1.13%   |
| Ralink Technology               | 13        | 1.05%   |
| Marvell Technology Group        | 11        | 0.89%   |
| ASIX Electronics                | 7         | 0.57%   |
| Hewlett-Packard                 | 6         | 0.49%   |
| Samsung Electronics             | 5         | 0.4%    |
| Qualcomm Atheros Communications | 5         | 0.4%    |
| NetGear                         | 5         | 0.4%    |
| Microsoft                       | 5         | 0.4%    |
| DisplayLink                     | 5         | 0.4%    |
| Aquantia                        | 5         | 0.4%    |
| Sierra Wireless                 | 3         | 0.24%   |
| OPPO Electronics                | 3         | 0.24%   |
| Microchip Technology            | 3         | 0.24%   |
| Lenovo                          | 3         | 0.24%   |
| IBM                             | 3         | 0.24%   |
| Edimax Technology               | 3         | 0.24%   |
| Mellanox Technologies           | 2         | 0.16%   |
| MCS                             | 2         | 0.16%   |
| JMicron Technology              | 2         | 0.16%   |
| Dell                            | 2         | 0.16%   |
| D-Link                          | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.08%   |
| Xiaomi                          | 1         | 0.08%   |
| Wilocity                        | 1         | 0.08%   |
| Wacom                           | 1         | 0.08%   |
| vivo                            | 1         | 0.08%   |
| Toshiba                         | 1         | 0.08%   |
| STMicroelectronics              | 1         | 0.08%   |
| Raspberry Pi                    | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| QinHeng Electronics             | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 269       | 18.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 45        | 3.09%   |
| Intel Wi-Fi 6 AX200                                                    | 38        | 2.61%   |
| Intel Wireless 8265 / 8275                                             | 35        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 28        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                      | 26        | 1.79%   |
| Intel I211 Gigabit Network Connection                                  | 21        | 1.44%   |
| Intel Wireless 8260                                                    | 19        | 1.31%   |
| Intel Wireless 7260                                                    | 18        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 15        | 1.03%   |
| Intel Wireless 3165                                                    | 14        | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 13        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 13        | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 0.82%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 12        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 11        | 0.76%   |
| Intel Wireless 7265                                                    | 11        | 0.76%   |
| Intel Ethernet Controller I225-V                                       | 11        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 10        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 10        | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 0.62%   |
| Nvidia MCP79 Ethernet                                                  | 9         | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.62%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                   | 9         | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 9         | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 9         | 0.62%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.55%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 315       | 48.46%  |
| Qualcomm Atheros                      | 88        | 13.54%  |
| Realtek Semiconductor                 | 77        | 11.85%  |
| Broadcom                              | 47        | 7.23%   |
| MediaTek                              | 24        | 3.69%   |
| TP-Link                               | 22        | 3.38%   |
| Ralink                                | 17        | 2.62%   |
| Ralink Technology                     | 13        | 2%      |
| Broadcom Limited                      | 12        | 1.85%   |
| Qualcomm Atheros Communications       | 5         | 0.77%   |
| NetGear                               | 5         | 0.77%   |
| Microsoft                             | 4         | 0.62%   |
| Sierra Wireless                       | 3         | 0.46%   |
| Hewlett-Packard                       | 3         | 0.46%   |
| Edimax Technology                     | 3         | 0.46%   |
| Dell                                  | 2         | 0.31%   |
| D-Link                                | 2         | 0.31%   |
| Wilocity                              | 1         | 0.15%   |
| Wacom                                 | 1         | 0.15%   |
| Qualcomm                              | 1         | 0.15%   |
| Marvell Technology Group              | 1         | 0.15%   |
| Lite-On Technology                    | 1         | 0.15%   |
| Belkin Components                     | 1         | 0.15%   |
| ASUSTek Computer                      | 1         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 38        | 5.78%   |
| Intel Wireless 8265 / 8275                                     | 35        | 5.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 28        | 4.26%   |
| Intel Wireless 8260                                            | 19        | 2.89%   |
| Intel Wireless 7260                                            | 18        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 2.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.28%   |
| Intel Wireless 3165                                            | 14        | 2.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 13        | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 13        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.67%   |
| Intel Wireless 7265                                            | 11        | 1.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 10        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.37%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 1.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 9         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 7         | 1.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 7         | 1.07%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 1.07%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 6         | 0.91%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.91%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 5         | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 0.76%   |
| Intel WiFi Link 5100                                           | 5         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 361       | 47.31%  |
| Intel                      | 254       | 33.29%  |
| Qualcomm Atheros           | 41        | 5.37%   |
| Broadcom                   | 33        | 4.33%   |
| Nvidia                     | 17        | 2.23%   |
| Marvell Technology Group   | 10        | 1.31%   |
| ASIX Electronics           | 7         | 0.92%   |
| Samsung Electronics        | 5         | 0.66%   |
| DisplayLink                | 5         | 0.66%   |
| Aquantia                   | 5         | 0.66%   |
| OPPO Electronics           | 3         | 0.39%   |
| Lenovo                     | 3         | 0.39%   |
| IBM                        | 3         | 0.39%   |
| JMicron Technology         | 2         | 0.26%   |
| Broadcom Limited           | 2         | 0.26%   |
| ZTE WCDMA Technologies MSM | 1         | 0.13%   |
| Xiaomi                     | 1         | 0.13%   |
| TP-Link                    | 1         | 0.13%   |
| Microsoft                  | 1         | 0.13%   |
| Microchip Technology       | 1         | 0.13%   |
| Mellanox Technologies      | 1         | 0.13%   |
| MediaTek                   | 1         | 0.13%   |
| Insyde Software            | 1         | 0.13%   |
| ICS Advent                 | 1         | 0.13%   |
| Huawei Technologies        | 1         | 0.13%   |
| Attansic Technology        | 1         | 0.13%   |
| Apple                      | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 269       | 34.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 45        | 5.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 4.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 3.47%   |
| Realtek RTL8125 2.5GbE Controller                                      | 26        | 3.35%   |
| Intel I211 Gigabit Network Connection                                  | 21        | 2.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13        | 1.67%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 1.54%   |
| Intel Ethernet Controller I225-V                                       | 11        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                                   | 10        | 1.29%   |
| Nvidia MCP79 Ethernet                                                  | 9         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                                   | 9         | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 9         | 1.16%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.03%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.03%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.03%   |
| Intel 82579V Gigabit Network Connection                                | 8         | 1.03%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.9%    |
| Intel I210 Gigabit Network Connection                                  | 6         | 0.77%   |
| Intel 82574L Gigabit Network Connection                                | 6         | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 5         | 0.64%   |
| Intel 82577LC Gigabit Network Connection                               | 5         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 4         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 3         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.39%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.39%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 709       | 52.83%  |
| WiFi     | 613       | 45.68%  |
| Modem    | 17        | 1.27%   |
| Unknown  | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 453       | 52.86%  |
| Ethernet | 404       | 47.14%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 448       | 55.58%  |
| 1     | 315       | 39.08%  |
| 3     | 27        | 3.35%   |
| 0     | 9         | 1.12%   |
| 4     | 4         | 0.5%    |
| 6     | 2         | 0.25%   |
| 8     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 682       | 83.17%  |
| Yes  | 138       | 16.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 258       | 51.6%   |
| Qualcomm Atheros Communications | 34        | 6.8%    |
| Broadcom                        | 29        | 5.8%    |
| Cambridge Silicon Radio         | 28        | 5.6%    |
| Realtek Semiconductor           | 23        | 4.6%    |
| IMC Networks                    | 20        | 4%      |
| Apple                           | 20        | 4%      |
| Foxconn / Hon Hai               | 19        | 3.8%    |
| Lite-On Technology              | 17        | 3.4%    |
| Hewlett-Packard                 | 12        | 2.4%    |
| ASUSTek Computer                | 8         | 1.6%    |
| Toshiba                         | 6         | 1.2%    |
| MediaTek                        | 5         | 1%      |
| Ralink                          | 4         | 0.8%    |
| Dell                            | 4         | 0.8%    |
| Ralink Technology               | 3         | 0.6%    |
| Edimax Technology               | 3         | 0.6%    |
| Realtek                         | 2         | 0.4%    |
| Alps Electric                   | 2         | 0.4%    |
| Marvell Semiconductor           | 1         | 0.2%    |
| Integrated System Solution      | 1         | 0.2%    |
| HTC (High Tech Computer)        | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 98        | 19.48%  |
| Intel AX201 Bluetooth                               | 37        | 7.36%   |
| Intel AX200 Bluetooth                               | 34        | 6.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 5.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 5.57%   |
| Intel Bluetooth Device                              | 17        | 3.38%   |
| Realtek Bluetooth Radio                             | 16        | 3.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 2.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 2.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 2.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 2.39%   |
| Apple Bluetooth Host Controller                     | 12        | 2.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 2.19%   |
| IMC Networks Wireless_Device                        | 11        | 2.19%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.39%   |
| Intel AX210 Bluetooth                               | 7         | 1.39%   |
| IMC Networks Bluetooth Radio                        | 7         | 1.39%   |
| Lite-On Bluetooth Device                            | 6         | 1.19%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 1.19%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.99%   |
| MediaTek Wireless_Device                            | 5         | 0.99%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.99%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.6%    |
| Foxconn / Hon Hai Acer Module                       | 3         | 0.6%    |
| Broadcom HP Portable SoftSailing                    | 3         | 0.6%    |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.6%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.6%    |
| Broadcom BCM20702A0                                 | 3         | 0.6%    |
| ASUS Bluetooth Radio                                | 3         | 0.6%    |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.4%    |
| Toshiba Bluetooth Radio                             | 2         | 0.4%    |
| Realtek Bluetooth Radio                             | 2         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 561       | 48.2%   |
| AMD                         | 264       | 22.68%  |
| Nvidia                      | 199       | 17.1%   |
| Logitech                    | 20        | 1.72%   |
| C-Media Electronics         | 18        | 1.55%   |
| Hewlett-Packard             | 8         | 0.69%   |
| SteelSeries ApS             | 7         | 0.6%    |
| Kingston Technology         | 6         | 0.52%   |
| Generalplus Technology      | 6         | 0.52%   |
| Realtek Semiconductor       | 5         | 0.43%   |
| Lenovo                      | 5         | 0.43%   |
| Plantronics                 | 4         | 0.34%   |
| GN Netcom                   | 4         | 0.34%   |
| Dell                        | 4         | 0.34%   |
| Razer USA                   | 3         | 0.26%   |
| JMTek                       | 3         | 0.26%   |
| GYROCOM C&C                 | 3         | 0.26%   |
| XMOS                        | 2         | 0.17%   |
| Texas Instruments           | 2         | 0.17%   |
| Microsoft                   | 2         | 0.17%   |
| FiiO Electronics Technology | 2         | 0.17%   |
| Creative Technology         | 2         | 0.17%   |
| Creative Labs               | 2         | 0.17%   |
| ASUSTek Computer            | 2         | 0.17%   |
| AKAI Professional M.I.      | 2         | 0.17%   |
| Trust International         | 1         | 0.09%   |
| Sony                        | 1         | 0.09%   |
| Sennheiser Communications   | 1         | 0.09%   |
| RODE Microphones            | 1         | 0.09%   |
| RME                         | 1         | 0.09%   |
| No brand                    | 1         | 0.09%   |
| Micro Star International    | 1         | 0.09%   |
| Medeli Electronics          | 1         | 0.09%   |
| KTMicro                     | 1         | 0.09%   |
| Harman                      | 1         | 0.09%   |
| Google                      | 1         | 0.09%   |
| Giga-Byte Technology        | 1         | 0.09%   |
| Focusrite-Novation          | 1         | 0.09%   |
| Conexant Systems            | 1         | 0.09%   |
| CMX Systems                 | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 71        | 5.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 64        | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 58        | 4.23%   |
| AMD Family 17h/19h HD Audio Controller                                     | 55        | 4.01%   |
| AMD Starship/Matisse HD Audio Controller                                   | 41        | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 31        | 2.26%   |
| AMD FCH Azalia Controller                                                  | 30        | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28        | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 28        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                   | 20        | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20        | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 1.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 17        | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 15        | 1.09%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14        | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 13        | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13        | 0.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 11        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 0.73%   |
| Nvidia MCP79 High Definition Audio                                         | 10        | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 0.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 0.73%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 106       | 21.68%  |
| SK hynix            | 93        | 19.02%  |
| Micron Technology   | 51        | 10.43%  |
| Kingston            | 50        | 10.22%  |
| Crucial             | 43        | 8.79%   |
| G.Skill             | 36        | 7.36%   |
| Unknown             | 26        | 5.32%   |
| A-DATA Technology   | 18        | 3.68%   |
| Corsair             | 16        | 3.27%   |
| Team                | 10        | 2.04%   |
| Elpida              | 7         | 1.43%   |
| Strontium           | 5         | 1.02%   |
| Transcend           | 4         | 0.82%   |
| Ramaxel Technology  | 4         | 0.82%   |
| Hewlett-Packard     | 3         | 0.61%   |
| Unknown (ABCD)      | 2         | 0.41%   |
| Shenzhen Mic        | 2         | 0.41%   |
| PNY                 | 2         | 0.41%   |
| Neo Forza           | 2         | 0.41%   |
| Nanya Technology    | 2         | 0.41%   |
| Unknown (0x8783)    | 1         | 0.2%    |
| pqi                 | 1         | 0.2%    |
| OCZ                 | 1         | 0.2%    |
| Netac               | 1         | 0.2%    |
| Innodisk            | 1         | 0.2%    |
| fef5                | 1         | 0.2%    |
| Apacer              | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 7         | 1.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 1.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 0.97%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 5         | 0.97%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 4         | 0.78%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 4         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 0.78%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 4         | 0.78%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 4         | 0.78%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s           | 3         | 0.58%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 3         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 0.58%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 3         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                 | 3         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 3         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.58%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 0.58%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 0.58%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 3         | 0.58%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s      | 3         | 0.58%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 2         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 2         | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 2         | 0.39%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s        | 2         | 0.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 0.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 0.39%   |
| SK hynix RAM Module 16GB SODIMM DDR5 4800MT/s                | 2         | 0.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s        | 2         | 0.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s      | 2         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.39%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.39%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.39%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 2         | 0.39%   |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 2         | 0.39%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.39%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 194       | 47.43%  |
| DDR3    | 140       | 34.23%  |
| DDR5    | 13        | 3.18%   |
| DDR2    | 13        | 3.18%   |
| Unknown | 12        | 2.93%   |
| SDRAM   | 11        | 2.69%   |
| LPDDR3  | 11        | 2.69%   |
| LPDDR4  | 9         | 2.2%    |
| LPDDR5  | 5         | 1.22%   |
| DDR     | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 237       | 58.37%  |
| DIMM         | 139       | 34.24%  |
| Row Of Chips | 23        | 5.67%   |
| Chip         | 3         | 0.74%   |
| Unknown      | 3         | 0.74%   |
| FB-DIMM      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 163       | 37.47%  |
| 4096  | 109       | 25.06%  |
| 16384 | 85        | 19.54%  |
| 2048  | 48        | 11.03%  |
| 32768 | 25        | 5.75%   |
| 1024  | 4         | 0.92%   |
| 65536 | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 93        | 21.14%  |
| 3200    | 71        | 16.14%  |
| 2667    | 46        | 10.45%  |
| 1333    | 30        | 6.82%   |
| 2400    | 29        | 6.59%   |
| 3600    | 22        | 5%      |
| 2133    | 20        | 4.55%   |
| 1334    | 17        | 3.86%   |
| 1867    | 11        | 2.5%    |
| 1067    | 9         | 2.05%   |
| 4800    | 8         | 1.82%   |
| 3733    | 8         | 1.82%   |
| 667     | 8         | 1.82%   |
| 6400    | 7         | 1.59%   |
| 800     | 7         | 1.59%   |
| 3800    | 6         | 1.36%   |
| 2666    | 5         | 1.14%   |
| Unknown | 5         | 1.14%   |
| 8400    | 3         | 0.68%   |
| 4267    | 3         | 0.68%   |
| 4199    | 3         | 0.68%   |
| 2800    | 3         | 0.68%   |
| 2048    | 3         | 0.68%   |
| 1066    | 3         | 0.68%   |
| 5600    | 2         | 0.45%   |
| 3466    | 2         | 0.45%   |
| 3400    | 2         | 0.45%   |
| 1800    | 2         | 0.45%   |
| 975     | 2         | 0.45%   |
| 6000    | 1         | 0.23%   |
| 3534    | 1         | 0.23%   |
| 3151    | 1         | 0.23%   |
| 3000    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 2465    | 1         | 0.23%   |
| 2448    | 1         | 0.23%   |
| 2000    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 266     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 30.77%  |
| Brother Industries  | 8         | 30.77%  |
| Canon               | 5         | 19.23%  |
| Sato                | 1         | 3.85%   |
| Samsung Electronics | 1         | 3.85%   |
| Prolific Technology | 1         | 3.85%   |
| Fuji Xerox          | 1         | 3.85%   |
| Dymo-CoStar         | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| HP Officejet 4630 series         | 2         | 7.69%   |
| Brother Printer                  | 2         | 7.69%   |
| Sato WS408 SBPL                  | 1         | 3.85%   |
| Samsung SCX-4100 Scanner         | 1         | 3.85%   |
| Prolific PL2305 Parallel Port    | 1         | 3.85%   |
| HP OfficeJet Pro 9010 series     | 1         | 3.85%   |
| HP OfficeJet 8010 series         | 1         | 3.85%   |
| HP LaserJet Professional P1102w  | 1         | 3.85%   |
| HP ENVY 4520 series              | 1         | 3.85%   |
| HP DeskJet 2300 series           | 1         | 3.85%   |
| HP DeskJet 2130 series           | 1         | 3.85%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 3.85%   |
| Dymo-CoStar LabelWriter 450      | 1         | 3.85%   |
| Canon TS3100 series              | 1         | 3.85%   |
| Canon MB5300 series              | 1         | 3.85%   |
| Canon LBP6000                    | 1         | 3.85%   |
| Canon i950                       | 1         | 3.85%   |
| Canon G3010 series               | 1         | 3.85%   |
| Brother MFC-J430W                | 1         | 3.85%   |
| Brother MFC-9140CDN              | 1         | 3.85%   |
| Brother MFC-7340                 | 1         | 3.85%   |
| Brother HL-L3230CDW series       | 1         | 3.85%   |
| Brother HL-2270DW Laser Printer  | 1         | 3.85%   |
| Brother HL-1430 Laser Printer    | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 500F           | 1         | 33.33%  |
| Canon CanoScan LIDE 25             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 110       | 23.97%  |
| Logitech                               | 39        | 8.5%    |
| IMC Networks                           | 35        | 7.63%   |
| Microdia                               | 32        | 6.97%   |
| Realtek Semiconductor                  | 31        | 6.75%   |
| Sunplus Innovation Technology          | 27        | 5.88%   |
| Quanta                                 | 26        | 5.66%   |
| Bison Electronics                      | 19        | 4.14%   |
| Apple                                  | 18        | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.49%   |
| Suyin                                  | 12        | 2.61%   |
| Lite-On Technology                     | 12        | 2.61%   |
| Luxvisions Innotech Limited            | 11        | 2.4%    |
| Syntek                                 | 8         | 1.74%   |
| Samsung Electronics                    | 7         | 1.53%   |
| Acer                                   | 6         | 1.31%   |
| Ricoh                                  | 4         | 0.87%   |
| Primax Electronics                     | 4         | 0.87%   |
| Alcor Micro                            | 4         | 0.87%   |
| Z-Star Microelectronics                | 3         | 0.65%   |
| Silicon Motion                         | 3         | 0.65%   |
| GEMBIRD                                | 3         | 0.65%   |
| ARC International                      | 3         | 0.65%   |
| ShineTech                              | 2         | 0.44%   |
| Microsoft                              | 2         | 0.44%   |
| KYE Systems (Mouse Systems)            | 2         | 0.44%   |
| Importek                               | 2         | 0.44%   |
| ALi                                    | 2         | 0.44%   |
| Yealink Network Technology             | 1         | 0.22%   |
| Xiongmai                               | 1         | 0.22%   |
| Sonix Technology                       | 1         | 0.22%   |
| SJ-180517-N                            | 1         | 0.22%   |
| OPPO Electronics                       | 1         | 0.22%   |
| Novatek Microelectronics               | 1         | 0.22%   |
| MacroSilicon                           | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |
| Intel                                  | 1         | 0.22%   |
| Google                                 | 1         | 0.22%   |
| Generalplus Technology                 | 1         | 0.22%   |
| EVGA                                   | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 19        | 4.11%   |
| IMC Networks USB2.0 HD UVC WebCam             | 16        | 3.46%   |
| Chicony HP HD Camera                          | 14        | 3.03%   |
| Realtek Integrated_Webcam_HD                  | 12        | 2.6%    |
| Chicony HD WebCam                             | 12        | 2.6%    |
| IMC Networks Integrated Camera                | 11        | 2.38%   |
| Apple Built-in iSight                         | 9         | 1.95%   |
| Logitech Webcam C270                          | 8         | 1.73%   |
| Sunplus Integrated_Webcam_HD                  | 7         | 1.52%   |
| Sunplus HP HD Webcam [Fixed]                  | 7         | 1.52%   |
| Samsung Galaxy series, misc. (MTP mode)       | 7         | 1.52%   |
| Microdia Integrated_Webcam_HD                 | 7         | 1.52%   |
| Bison Integrated Camera                       | 7         | 1.52%   |
| Microdia Integrated Webcam HD                 | 6         | 1.3%    |
| Logitech Webcam C170                          | 6         | 1.3%    |
| Chicony TOSHIBA Web Camera - HD               | 6         | 1.3%    |
| Chicony HP HD Webcam                          | 6         | 1.3%    |
| Realtek HP Truevision HD                      | 5         | 1.08%   |
| Quanta HP HD Camera                           | 5         | 1.08%   |
| Logitech HD Pro Webcam C920                   | 5         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 5         | 1.08%   |
| Syntek Integrated Camera                      | 4         | 0.87%   |
| Quanta HP TrueVision HD Camera                | 4         | 0.87%   |
| Luxvisions Innotech Limited HP HD Camera      | 4         | 0.87%   |
| Chicony HP Wide Vision HD Camera              | 4         | 0.87%   |
| Sunplus HD WebCam                             | 3         | 0.65%   |
| Quanta Laptop_Integrated_Webcam_2HDM          | 3         | 0.65%   |
| Quanta HD User Facing                         | 3         | 0.65%   |
| Luxvisions Innotech Limited HP 5MP Camera     | 3         | 0.65%   |
| Logitech QuickCam Pro 9000                    | 3         | 0.65%   |
| Logitech HD Webcam C510                       | 3         | 0.65%   |
| Lite-On Integrated Camera                     | 3         | 0.65%   |
| Lite-On HP HD Camera                          | 3         | 0.65%   |
| Chicony VGA Webcam                            | 3         | 0.65%   |
| Chicony USB2.0 Camera                         | 3         | 0.65%   |
| Chicony Integrated HP HD Webcam               | 3         | 0.65%   |
| Bison HD Webcam                               | 3         | 0.65%   |
| Bison BisonCam,NB Pro                         | 3         | 0.65%   |
| ARC International Camera                      | 3         | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 3         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 59        | 47.58%  |
| Synaptics                  | 37        | 29.84%  |
| Shenzhen Goodix Technology | 7         | 5.65%   |
| AuthenTec                  | 7         | 5.65%   |
| Elan Microelectronics      | 6         | 4.84%   |
| Upek                       | 5         | 4.03%   |
| LighTuning Technology      | 2         | 1.61%   |
| STMicroelectronics         | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 11.29%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 5.65%   |
| Validity Sensors VFS491                                                    | 7         | 5.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 5.65%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 5.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 4.84%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 4.84%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 4.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 4.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 3.23%   |
| Synaptics UWP WBDI                                                         | 4         | 3.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 3.23%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.23%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.42%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.42%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.61%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.61%   |
| Synaptics WBDI                                                             | 2         | 1.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.61%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.61%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.81%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.81%   |
| Synaptics  WBDI                                                            | 1         | 0.81%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.81%   |
| AuthenTec AES2810                                                          | 1         | 0.81%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.81%   |
| AuthenTec AES1600                                                          | 1         | 0.81%   |
| Unknown                                                                    | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 66.67%  |
| Lenovo      | 3         | 12.5%   |
| Alcor Micro | 3         | 12.5%   |
| Upek        | 1         | 4.17%   |
| O2 Micro    | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 29.17%  |
| Broadcom 58200                                                               | 4         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 12.5%   |
| Broadcom 5880                                                                | 3         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 549       | 65.99%  |
| 1     | 236       | 28.37%  |
| 2     | 39        | 4.69%   |
| 3     | 3         | 0.36%   |
| 6     | 2         | 0.24%   |
| 5     | 2         | 0.24%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 122       | 36.97%  |
| Graphics card            | 62        | 18.79%  |
| Net/wireless             | 49        | 14.85%  |
| Chipcard                 | 22        | 6.67%   |
| Multimedia controller    | 18        | 5.45%   |
| Camera                   | 9         | 2.73%   |
| Bluetooth                | 9         | 2.73%   |
| Communication controller | 7         | 2.12%   |
| Unassigned class         | 6         | 1.82%   |
| Sound                    | 6         | 1.82%   |
| Net/ethernet             | 4         | 1.21%   |
| Modem                    | 3         | 0.91%   |
| Dvb card                 | 3         | 0.91%   |
| Storage/ide              | 2         | 0.61%   |
| Storage                  | 2         | 0.61%   |
| Network                  | 2         | 0.61%   |
| Card reader              | 2         | 0.61%   |
| Storage/raid             | 1         | 0.3%    |
| Flash memory             | 1         | 0.3%    |

