Linux in Israel - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Israel/Desktop/README.md) and [notebooks](/Location/Israel/Notebook/README.md).

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

Total: 1605

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [85f7ec5a23](https://linux-hardware.org/?probe=85f7ec5a23) | Jan 03, 2026 |
| Intel         | Unknown                     | Notebook    | [c889b92d2d](https://linux-hardware.org/?probe=c889b92d2d) | Jan 03, 2026 |
| Lenovo        | IdeaPad Slim 3 16IAH8 83... | Notebook    | [edccdf2860](https://linux-hardware.org/?probe=edccdf2860) | Jan 03, 2026 |
| Lenovo        | IdeaPad Slim 3 16IAH8 83... | Notebook    | [7d780cf9c6](https://linux-hardware.org/?probe=7d780cf9c6) | Jan 03, 2026 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [21ab6eac53](https://linux-hardware.org/?probe=21ab6eac53) | Jan 02, 2026 |
| HP            | ProLiant DL380 Gen9         | Server      | [9f2d042a46](https://linux-hardware.org/?probe=9f2d042a46) | Jan 02, 2026 |
| HP            | ProLiant DL380 Gen9         | Server      | [c0c1229614](https://linux-hardware.org/?probe=c0c1229614) | Jan 01, 2026 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [61c09caa84](https://linux-hardware.org/?probe=61c09caa84) | Dec 30, 2025 |
| Dell          | Vostro 3580                 | Notebook    | [44dbaa20c4](https://linux-hardware.org/?probe=44dbaa20c4) | Dec 28, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [91651b261b](https://linux-hardware.org/?probe=91651b261b) | Dec 27, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [2db529768c](https://linux-hardware.org/?probe=2db529768c) | Dec 26, 2025 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [b8602ec35e](https://linux-hardware.org/?probe=b8602ec35e) | Dec 24, 2025 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | Desktop     | [62bc3060b1](https://linux-hardware.org/?probe=62bc3060b1) | Dec 22, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | Notebook    | [5d314c2908](https://linux-hardware.org/?probe=5d314c2908) | Dec 22, 2025 |
| Dell          | Vostro 16 5630              | Notebook    | [12e06fe276](https://linux-hardware.org/?probe=12e06fe276) | Dec 21, 2025 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [109783f988](https://linux-hardware.org/?probe=109783f988) | Dec 20, 2025 |
| Lenovo        | ThinkPad E490 20N8000RIV    | Notebook    | [edc1162616](https://linux-hardware.org/?probe=edc1162616) | Dec 19, 2025 |
| Dell          | Precision 7540              | Notebook    | [b97fc320de](https://linux-hardware.org/?probe=b97fc320de) | Dec 18, 2025 |
| HP            | 1494                        | Desktop     | [0847fe437b](https://linux-hardware.org/?probe=0847fe437b) | Dec 17, 2025 |
| Acer          | Aspire ES1-521              | Notebook    | [c0f3f1fa14](https://linux-hardware.org/?probe=c0f3f1fa14) | Dec 17, 2025 |
| ASUSTek       | ASUS Vivobook S 14 S5406... | Notebook    | [bcc0492109](https://linux-hardware.org/?probe=bcc0492109) | Dec 17, 2025 |
| ASUSTek       | ASUS Vivobook S 14 S5406... | Notebook    | [3bd0bf5773](https://linux-hardware.org/?probe=3bd0bf5773) | Dec 17, 2025 |
| Lenovo        | ThinkPad P16 Gen 3 21RQ0... | Notebook    | [350c2026b5](https://linux-hardware.org/?probe=350c2026b5) | Dec 15, 2025 |
| Lenovo        | ThinkPad T460 20FMS0GF01    | Notebook    | [5eb6ad8d88](https://linux-hardware.org/?probe=5eb6ad8d88) | Dec 13, 2025 |
| ASUSTek       | PRIME B850-PLUS             | Desktop     | [3319d6f365](https://linux-hardware.org/?probe=3319d6f365) | Dec 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [7893526d39](https://linux-hardware.org/?probe=7893526d39) | Dec 11, 2025 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [52ba83ab78](https://linux-hardware.org/?probe=52ba83ab78) | Dec 10, 2025 |
| Lenovo        | ThinkPad P16 Gen 3 21RQ0... | Notebook    | [5ba8b97694](https://linux-hardware.org/?probe=5ba8b97694) | Dec 09, 2025 |
| Gigabyte      | Z590M                       | Desktop     | [c13c673eed](https://linux-hardware.org/?probe=c13c673eed) | Dec 07, 2025 |
| Gigabyte      | Z590M                       | Desktop     | [831dbe5517](https://linux-hardware.org/?probe=831dbe5517) | Dec 07, 2025 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [41fc59c967](https://linux-hardware.org/?probe=41fc59c967) | Dec 05, 2025 |
| Dell          | Vostro 3580                 | Notebook    | [d319f195e5](https://linux-hardware.org/?probe=d319f195e5) | Dec 04, 2025 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [b5bad82aa1](https://linux-hardware.org/?probe=b5bad82aa1) | Dec 03, 2025 |
| Lenovo        | ThinkPad E14 20RAS0PS00     | Notebook    | [e5265d8206](https://linux-hardware.org/?probe=e5265d8206) | Dec 03, 2025 |
| GMKtec        | NucBoxG3 Plus               | Other       | [d4306b6395](https://linux-hardware.org/?probe=d4306b6395) | Dec 03, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [4524ff2e53](https://linux-hardware.org/?probe=4524ff2e53) | Dec 03, 2025 |
| ASUSTek       | PRIME B850-PLUS             | Desktop     | [957ce1e8c2](https://linux-hardware.org/?probe=957ce1e8c2) | Dec 02, 2025 |
| ASUSTek       | NUC14RVB 60AS0080-MB0A02    | Mini pc     | [e22943512e](https://linux-hardware.org/?probe=e22943512e) | Dec 02, 2025 |
| Dell          | XPS 15 9530                 | Notebook    | [9258d29bc1](https://linux-hardware.org/?probe=9258d29bc1) | Dec 02, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [76186f40ba](https://linux-hardware.org/?probe=76186f40ba) | Dec 02, 2025 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [b0bdfbe723](https://linux-hardware.org/?probe=b0bdfbe723) | Nov 29, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b902aac5fa](https://linux-hardware.org/?probe=b902aac5fa) | Nov 29, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [61049440ff](https://linux-hardware.org/?probe=61049440ff) | Nov 28, 2025 |
| ASUSTek       | GL502VMK                    | Notebook    | [35ab18bc87](https://linux-hardware.org/?probe=35ab18bc87) | Nov 27, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [022acc53e2](https://linux-hardware.org/?probe=022acc53e2) | Nov 27, 2025 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [302266c401](https://linux-hardware.org/?probe=302266c401) | Nov 26, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [7fc57873df](https://linux-hardware.org/?probe=7fc57873df) | Nov 26, 2025 |
| Dell          | XPS 15 9530                 | Notebook    | [cfc1ad77fe](https://linux-hardware.org/?probe=cfc1ad77fe) | Nov 25, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [94e684032b](https://linux-hardware.org/?probe=94e684032b) | Nov 24, 2025 |
| Unknown       | Unknown                     | Desktop     | [3a80899432](https://linux-hardware.org/?probe=3a80899432) | Nov 24, 2025 |
| Intel         | JSL MRD                     | Desktop     | [1cef161567](https://linux-hardware.org/?probe=1cef161567) | Nov 24, 2025 |
| Intel         | X99                         | Desktop     | [d5f620a9a2](https://linux-hardware.org/?probe=d5f620a9a2) | Nov 24, 2025 |
| HP            | 829A                        | Mini pc     | [b9047d1aa2](https://linux-hardware.org/?probe=b9047d1aa2) | Nov 24, 2025 |
| HP            | 829A                        | Mini pc     | [cbef3f8558](https://linux-hardware.org/?probe=cbef3f8558) | Nov 24, 2025 |
| Lenovo        | 3111 NOK                    | Desktop     | [fec6efc117](https://linux-hardware.org/?probe=fec6efc117) | Nov 24, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6914900269](https://linux-hardware.org/?probe=6914900269) | Nov 24, 2025 |
| Dell          | Vostro 5490                 | Notebook    | [f9ebd41a74](https://linux-hardware.org/?probe=f9ebd41a74) | Nov 24, 2025 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a8a10f6f7f](https://linux-hardware.org/?probe=a8a10f6f7f) | Nov 19, 2025 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [6333333a47](https://linux-hardware.org/?probe=6333333a47) | Nov 19, 2025 |
| Pegatron      | 2AB5                        | Desktop     | [784582192c](https://linux-hardware.org/?probe=784582192c) | Nov 17, 2025 |
| Dell          | Vostro 3580                 | Notebook    | [7c6ea3f854](https://linux-hardware.org/?probe=7c6ea3f854) | Nov 16, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405CA... | Notebook    | [11002bc86c](https://linux-hardware.org/?probe=11002bc86c) | Nov 16, 2025 |
| Valve         | Galileo                     | Notebook    | [262eb1a867](https://linux-hardware.org/?probe=262eb1a867) | Nov 15, 2025 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [c5566f5a30](https://linux-hardware.org/?probe=c5566f5a30) | Nov 10, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [64f00ff33e](https://linux-hardware.org/?probe=64f00ff33e) | Nov 09, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [7c89aa0dd2](https://linux-hardware.org/?probe=7c89aa0dd2) | Nov 08, 2025 |
| MSI           | MAG B850 TOMAHAWK MAX WI... | Desktop     | [4293c72f36](https://linux-hardware.org/?probe=4293c72f36) | Nov 04, 2025 |
| ASUSTek       | TUF Gaming B850M-PLUS       | Desktop     | [9763e240c4](https://linux-hardware.org/?probe=9763e240c4) | Nov 04, 2025 |
| Gigabyte      | B760M DS3H                  | Desktop     | [f482907595](https://linux-hardware.org/?probe=f482907595) | Nov 03, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [7cdaef669e](https://linux-hardware.org/?probe=7cdaef669e) | Nov 03, 2025 |
| ASUSTek       | Z170-P                      | Desktop     | [759db0b018](https://linux-hardware.org/?probe=759db0b018) | Nov 03, 2025 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [14172561f0](https://linux-hardware.org/?probe=14172561f0) | Nov 02, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [bdc227f42b](https://linux-hardware.org/?probe=bdc227f42b) | Nov 02, 2025 |
| Gigabyte      | B760M DS3H AX               | Desktop     | [379112f760](https://linux-hardware.org/?probe=379112f760) | Nov 01, 2025 |
| ASUSTek       | X501A                       | Notebook    | [417cacba3b](https://linux-hardware.org/?probe=417cacba3b) | Nov 01, 2025 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [a10a72c361](https://linux-hardware.org/?probe=a10a72c361) | Oct 31, 2025 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c34cf00b99](https://linux-hardware.org/?probe=c34cf00b99) | Oct 29, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | Notebook    | [4ef43272e2](https://linux-hardware.org/?probe=4ef43272e2) | Oct 29, 2025 |
| Gigabyte      | H81M-S2V                    | Desktop     | [85493e4498](https://linux-hardware.org/?probe=85493e4498) | Oct 27, 2025 |
| Gigabyte      | G31M-S2C                    | Desktop     | [a5d67d265d](https://linux-hardware.org/?probe=a5d67d265d) | Oct 25, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRU9 83... | Notebook    | [e8de1b3ccd](https://linux-hardware.org/?probe=e8de1b3ccd) | Oct 20, 2025 |
| Lenovo        | IdeaPad 3 17IRU7 82X9       | Notebook    | [3c73310969](https://linux-hardware.org/?probe=3c73310969) | Oct 19, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [9bab3c0d27](https://linux-hardware.org/?probe=9bab3c0d27) | Oct 18, 2025 |
| Lenovo        | 317C NO DPK                 | Desktop     | [043f0aa1da](https://linux-hardware.org/?probe=043f0aa1da) | Oct 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [de8505a719](https://linux-hardware.org/?probe=de8505a719) | Oct 16, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [ae9a3947cd](https://linux-hardware.org/?probe=ae9a3947cd) | Oct 16, 2025 |
| HP            | Pavilion dv9000             | Notebook    | [d124de116b](https://linux-hardware.org/?probe=d124de116b) | Oct 15, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [f5e9488008](https://linux-hardware.org/?probe=f5e9488008) | Oct 15, 2025 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [b89488a46d](https://linux-hardware.org/?probe=b89488a46d) | Oct 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [2d9f02661a](https://linux-hardware.org/?probe=2d9f02661a) | Oct 12, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [fc3cee2d11](https://linux-hardware.org/?probe=fc3cee2d11) | Oct 09, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [9190615d31](https://linux-hardware.org/?probe=9190615d31) | Oct 09, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [c740c9ee42](https://linux-hardware.org/?probe=c740c9ee42) | Oct 08, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRU9 83... | Notebook    | [9d4154db61](https://linux-hardware.org/?probe=9d4154db61) | Oct 02, 2025 |
| HP            | ProLiant DL380 Gen9         | Server      | [a9bcfce5ab](https://linux-hardware.org/?probe=a9bcfce5ab) | Oct 02, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [2f2ba59e01](https://linux-hardware.org/?probe=2f2ba59e01) | Oct 01, 2025 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c51bd704fd](https://linux-hardware.org/?probe=c51bd704fd) | Oct 01, 2025 |
| HP            | 1998                        | Desktop     | [4712012fa2](https://linux-hardware.org/?probe=4712012fa2) | Oct 01, 2025 |
| HP            | 1998                        | Desktop     | [293fd36c3f](https://linux-hardware.org/?probe=293fd36c3f) | Oct 01, 2025 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [00c079e6b7](https://linux-hardware.org/?probe=00c079e6b7) | Sep 27, 2025 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [545fe971c1](https://linux-hardware.org/?probe=545fe971c1) | Sep 26, 2025 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [1d83d0c816](https://linux-hardware.org/?probe=1d83d0c816) | Sep 25, 2025 |
| ASUSTek       | PRIME X399-A                | Desktop     | [e52c6172e4](https://linux-hardware.org/?probe=e52c6172e4) | Sep 22, 2025 |
| HP            | 255 G8 Notebook PC          | Notebook    | [491871ffff](https://linux-hardware.org/?probe=491871ffff) | Sep 21, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f319a2764b](https://linux-hardware.org/?probe=f319a2764b) | Sep 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [386ab76f00](https://linux-hardware.org/?probe=386ab76f00) | Sep 17, 2025 |
| Gigabyte      | A520M S2H                   | Desktop     | [82e277d7e6](https://linux-hardware.org/?probe=82e277d7e6) | Sep 14, 2025 |
| Gigabyte      | A520M S2H                   | Desktop     | [dce3a0f9f4](https://linux-hardware.org/?probe=dce3a0f9f4) | Sep 14, 2025 |
| Lenovo        | ThinkPad T490 20N20075MX    | Notebook    | [f10871a57c](https://linux-hardware.org/?probe=f10871a57c) | Sep 14, 2025 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [91e0d6984d](https://linux-hardware.org/?probe=91e0d6984d) | Sep 14, 2025 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [c8da642ab9](https://linux-hardware.org/?probe=c8da642ab9) | Sep 13, 2025 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [2ef9eb95be](https://linux-hardware.org/?probe=2ef9eb95be) | Sep 06, 2025 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [bd81b067f6](https://linux-hardware.org/?probe=bd81b067f6) | Sep 06, 2025 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [1044fd09c6](https://linux-hardware.org/?probe=1044fd09c6) | Sep 06, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | Notebook    | [ffe97ae211](https://linux-hardware.org/?probe=ffe97ae211) | Sep 04, 2025 |
| MAXSUN        | MS-MoDT 12450H ITX WIFI ... | Desktop     | [e5fc66ced9](https://linux-hardware.org/?probe=e5fc66ced9) | Sep 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [fef19eb161](https://linux-hardware.org/?probe=fef19eb161) | Sep 01, 2025 |
| AZW           | SER V2.0                    | Mini pc     | [f1e271f3c9](https://linux-hardware.org/?probe=f1e271f3c9) | Aug 29, 2025 |
| Samsung       | 270E5G/270E5U               | Notebook    | [8f79294284](https://linux-hardware.org/?probe=8f79294284) | Aug 25, 2025 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [84412a90c0](https://linux-hardware.org/?probe=84412a90c0) | Aug 24, 2025 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [5521e376af](https://linux-hardware.org/?probe=5521e376af) | Aug 22, 2025 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [abdacafef8](https://linux-hardware.org/?probe=abdacafef8) | Aug 17, 2025 |
| Intel         | DH55HC AAE70933-504         | Desktop     | [0fdf5fa883](https://linux-hardware.org/?probe=0fdf5fa883) | Aug 15, 2025 |
| Gigabyte      | B85M-D2V                    | Desktop     | [8bbec6c350](https://linux-hardware.org/?probe=8bbec6c350) | Aug 14, 2025 |
| MAXSUN        | MS-MoDT 12450H ITX WIFI ... | Desktop     | [4b97e2df68](https://linux-hardware.org/?probe=4b97e2df68) | Aug 13, 2025 |
| Intel         | D54250WYK H13922-302        | Desktop     | [7850217229](https://linux-hardware.org/?probe=7850217229) | Aug 10, 2025 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [77e4e64416](https://linux-hardware.org/?probe=77e4e64416) | Aug 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [107a9184d2](https://linux-hardware.org/?probe=107a9184d2) | Aug 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7dc34bf605](https://linux-hardware.org/?probe=7dc34bf605) | Aug 05, 2025 |
| Lenovo        | ThinkPad X260 20F6006AUS    | Notebook    | [1868e83ee0](https://linux-hardware.org/?probe=1868e83ee0) | Aug 03, 2025 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [b23849255a](https://linux-hardware.org/?probe=b23849255a) | Aug 02, 2025 |
| HP            | ProBook 445 14 inch G11 ... | Notebook    | [aa9159ea10](https://linux-hardware.org/?probe=aa9159ea10) | Jul 31, 2025 |
| Dell          | Pro 14 Plus PB14250         | Notebook    | [026fa9ae3c](https://linux-hardware.org/?probe=026fa9ae3c) | Jul 30, 2025 |
| ASRock        | G41C-GS                     | Desktop     | [2796589b2e](https://linux-hardware.org/?probe=2796589b2e) | Jul 30, 2025 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [7890e6e270](https://linux-hardware.org/?probe=7890e6e270) | Jul 30, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f65ba6b836](https://linux-hardware.org/?probe=f65ba6b836) | Jul 29, 2025 |
| Unknown       | A.1                         | Desktop     | [7e06d197f2](https://linux-hardware.org/?probe=7e06d197f2) | Jul 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [d6788d26e7](https://linux-hardware.org/?probe=d6788d26e7) | Jul 17, 2025 |
| Unknown       | Mini PC                     | Mini pc     | [5e05863242](https://linux-hardware.org/?probe=5e05863242) | Jul 17, 2025 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f932a4471a](https://linux-hardware.org/?probe=f932a4471a) | Jul 09, 2025 |
| Dell          | Latitude E5540              | Notebook    | [d6157f3592](https://linux-hardware.org/?probe=d6157f3592) | Jul 07, 2025 |
| AZW           | SER V2.0                    | Mini pc     | [4328966bfb](https://linux-hardware.org/?probe=4328966bfb) | Jul 07, 2025 |
| Microsoft     | Surface Go 4                | Tablet      | [9d752693fd](https://linux-hardware.org/?probe=9d752693fd) | Jul 07, 2025 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [748a7ecb5a](https://linux-hardware.org/?probe=748a7ecb5a) | Jul 07, 2025 |
| Gigabyte      | B860 DS3H WIFI6E            | Desktop     | [ff0d491aba](https://linux-hardware.org/?probe=ff0d491aba) | Jul 05, 2025 |
| Dell          | Latitude 5421               | Notebook    | [7da034b78d](https://linux-hardware.org/?probe=7da034b78d) | Jul 04, 2025 |
| ASUSTek       | ROG STRIX X870-F GAMING ... | Desktop     | [cd2aa8c814](https://linux-hardware.org/?probe=cd2aa8c814) | Jul 03, 2025 |
| Dell          | Latitude 5420               | Notebook    | [d8234e66cb](https://linux-hardware.org/?probe=d8234e66cb) | Jul 02, 2025 |
| Unknown       | Unknown                     | Tablet      | [ee6ee26294](https://linux-hardware.org/?probe=ee6ee26294) | Jul 02, 2025 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [5eee0c03f8](https://linux-hardware.org/?probe=5eee0c03f8) | Jun 30, 2025 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d0516bd525](https://linux-hardware.org/?probe=d0516bd525) | Jun 28, 2025 |
| Dell          | 0Y56T3 A01                  | Desktop     | [cdda2c7903](https://linux-hardware.org/?probe=cdda2c7903) | Jun 27, 2025 |
| Dell          | Vostro 15-3568              | Notebook    | [bfdbbdc965](https://linux-hardware.org/?probe=bfdbbdc965) | Jun 27, 2025 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [01de85be72](https://linux-hardware.org/?probe=01de85be72) | Jun 27, 2025 |
| HP            | 88BE                        | Desktop     | [95d46e4175](https://linux-hardware.org/?probe=95d46e4175) | Jun 25, 2025 |
| Lenovo        | Y50-70 20378                | Notebook    | [3eaed721d6](https://linux-hardware.org/?probe=3eaed721d6) | Jun 23, 2025 |
| Lenovo        | Y50-70 20378                | Notebook    | [fee3673629](https://linux-hardware.org/?probe=fee3673629) | Jun 23, 2025 |
| ASUSTek       | NUC14RVB 60AS0080-MB0A02    | Mini pc     | [ca575e14ff](https://linux-hardware.org/?probe=ca575e14ff) | Jun 23, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | Notebook    | [9f5efd32fd](https://linux-hardware.org/?probe=9f5efd32fd) | Jun 22, 2025 |
| Dell          | Vostro 3580                 | Notebook    | [d15df0928b](https://linux-hardware.org/?probe=d15df0928b) | Jun 19, 2025 |
| Lenovo        | Legion Go S 8ARP1 83L3      | Tablet      | [ccabe8518b](https://linux-hardware.org/?probe=ccabe8518b) | Jun 18, 2025 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [661116425b](https://linux-hardware.org/?probe=661116425b) | Jun 16, 2025 |
| HP            | Laptop 14t-ep100            | Notebook    | [d7bc7ffeab](https://linux-hardware.org/?probe=d7bc7ffeab) | Jun 16, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [14bf557fb9](https://linux-hardware.org/?probe=14bf557fb9) | Jun 13, 2025 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [7024e8d2c0](https://linux-hardware.org/?probe=7024e8d2c0) | Jun 11, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [8c03c5fb14](https://linux-hardware.org/?probe=8c03c5fb14) | Jun 08, 2025 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [4e484ecb32](https://linux-hardware.org/?probe=4e484ecb32) | Jun 08, 2025 |
| Valve         | Galileo                     | Notebook    | [99396ddf3c](https://linux-hardware.org/?probe=99396ddf3c) | Jun 07, 2025 |
| Alienware     | 17 R3                       | Notebook    | [6a88a5f778](https://linux-hardware.org/?probe=6a88a5f778) | Jun 02, 2025 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [8d7aa88f8b](https://linux-hardware.org/?probe=8d7aa88f8b) | Jun 01, 2025 |
| Dell          | Vostro 3550                 | Notebook    | [e5539aeb46](https://linux-hardware.org/?probe=e5539aeb46) | May 29, 2025 |
| Lenovo        | ThinkPad E470 20H1004VIV    | Notebook    | [c3beaadda9](https://linux-hardware.org/?probe=c3beaadda9) | May 28, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [f3fb213141](https://linux-hardware.org/?probe=f3fb213141) | May 27, 2025 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [98d836b313](https://linux-hardware.org/?probe=98d836b313) | May 23, 2025 |
| MSI           | Z390-A PRO                  | Desktop     | [bf37e30ef6](https://linux-hardware.org/?probe=bf37e30ef6) | May 23, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2218923e55](https://linux-hardware.org/?probe=2218923e55) | May 20, 2025 |
| ASUSTek       | ROG Strix G16 G614JVR_G6... | Notebook    | [fe7269558f](https://linux-hardware.org/?probe=fe7269558f) | May 20, 2025 |
| Intel         | X99E V1.0                   | Desktop     | [b69afe6901](https://linux-hardware.org/?probe=b69afe6901) | May 20, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7e4955273c](https://linux-hardware.org/?probe=7e4955273c) | May 19, 2025 |
| Dell          | XPS 16 9640                 | Notebook    | [9c581659c7](https://linux-hardware.org/?probe=9c581659c7) | May 19, 2025 |
| Dell          | Vostro 14 5401              | Notebook    | [2d9f4cd960](https://linux-hardware.org/?probe=2d9f4cd960) | May 19, 2025 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [3eb26f33bf](https://linux-hardware.org/?probe=3eb26f33bf) | May 18, 2025 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0e2e093aaf](https://linux-hardware.org/?probe=0e2e093aaf) | May 18, 2025 |
| Dell          | 04JYW6 A01                  | Desktop     | [c648532888](https://linux-hardware.org/?probe=c648532888) | May 12, 2025 |
| Lenovo        | Yoga Pro 7 14ASP9 83HN      | Notebook    | [563618d5ad](https://linux-hardware.org/?probe=563618d5ad) | May 09, 2025 |
| Lenovo        | 3176 SDK0L22692 WIN 3306... | Notebook    | [86af928c32](https://linux-hardware.org/?probe=86af928c32) | May 09, 2025 |
| Shenzhen M... | F7BSI                       | Mini pc     | [5a6acfd43c](https://linux-hardware.org/?probe=5a6acfd43c) | May 07, 2025 |
| Gigabyte      | Z790 AORUS ELITE X WIFI7    | Desktop     | [9277b5cbbf](https://linux-hardware.org/?probe=9277b5cbbf) | May 07, 2025 |
| Lenovo        | Yoga Pro 7 14ASP9 83HN      | Notebook    | [f22419a54c](https://linux-hardware.org/?probe=f22419a54c) | May 06, 2025 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [da69229ee6](https://linux-hardware.org/?probe=da69229ee6) | May 06, 2025 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [68469e687a](https://linux-hardware.org/?probe=68469e687a) | May 06, 2025 |
| ASUSTek       | K53E                        | Notebook    | [2c5cde70c2](https://linux-hardware.org/?probe=2c5cde70c2) | May 05, 2025 |
| Dell          | Vostro 14 5401              | Notebook    | [5f66076293](https://linux-hardware.org/?probe=5f66076293) | May 05, 2025 |
| AYANEO        | NEXT                        | Tablet      | [9efefb6420](https://linux-hardware.org/?probe=9efefb6420) | May 04, 2025 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [7ebf32fed3](https://linux-hardware.org/?probe=7ebf32fed3) | May 02, 2025 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [8534604a73](https://linux-hardware.org/?probe=8534604a73) | Apr 29, 2025 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [3f5c176ce9](https://linux-hardware.org/?probe=3f5c176ce9) | Apr 29, 2025 |
| Gigabyte      | A520M S2H                   | Desktop     | [1fe5d63e73](https://linux-hardware.org/?probe=1fe5d63e73) | Apr 26, 2025 |
| GMKtec        | NucBox K4                   | Desktop     | [dfc38ac59b](https://linux-hardware.org/?probe=dfc38ac59b) | Apr 26, 2025 |
| Lenovo        | 3778 WIN SDK0T76528 3556... | All in one  | [583d5efb8a](https://linux-hardware.org/?probe=583d5efb8a) | Apr 26, 2025 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [2549548ff7](https://linux-hardware.org/?probe=2549548ff7) | Apr 20, 2025 |
| Sony          | VJPG11                      | Notebook    | [f13f61e34f](https://linux-hardware.org/?probe=f13f61e34f) | Apr 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [0077d613a4](https://linux-hardware.org/?probe=0077d613a4) | Apr 18, 2025 |
| Dell          | Latitude 5450               | Notebook    | [08974c7b0d](https://linux-hardware.org/?probe=08974c7b0d) | Apr 15, 2025 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [5d400ed9d2](https://linux-hardware.org/?probe=5d400ed9d2) | Apr 10, 2025 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e04d1fd3f9](https://linux-hardware.org/?probe=e04d1fd3f9) | Apr 09, 2025 |
| Dell          | 0TTDMJ A00                  | Desktop     | [ea900123cc](https://linux-hardware.org/?probe=ea900123cc) | Apr 09, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [aa963970fe](https://linux-hardware.org/?probe=aa963970fe) | Apr 07, 2025 |
| MSI           | PRO B650-P WIFI             | Desktop     | [a71fe4014e](https://linux-hardware.org/?probe=a71fe4014e) | Mar 30, 2025 |
| Dell          | Latitude 7490               | Notebook    | [de85cc9d7f](https://linux-hardware.org/?probe=de85cc9d7f) | Mar 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [2c32ce8133](https://linux-hardware.org/?probe=2c32ce8133) | Mar 29, 2025 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [4959e6a11c](https://linux-hardware.org/?probe=4959e6a11c) | Mar 28, 2025 |
| ASRock        | B760M Pro RS                | Desktop     | [b5b54c28d4](https://linux-hardware.org/?probe=b5b54c28d4) | Mar 25, 2025 |
| MSI           | PRO B650-P WIFI             | Desktop     | [4d31279a12](https://linux-hardware.org/?probe=4d31279a12) | Mar 24, 2025 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [0f45d8891a](https://linux-hardware.org/?probe=0f45d8891a) | Mar 22, 2025 |
| Dell          | Vostro 3550                 | Notebook    | [ee230fc148](https://linux-hardware.org/?probe=ee230fc148) | Mar 22, 2025 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [b8980bd7a4](https://linux-hardware.org/?probe=b8980bd7a4) | Mar 20, 2025 |
| Lenovo        | IdeaPad 5 2-in-1 14IRH9 ... | Convertible | [bf90e2d33f](https://linux-hardware.org/?probe=bf90e2d33f) | Mar 19, 2025 |
| Shenzhen M... | DRFXL                       | Desktop     | [d6867703d7](https://linux-hardware.org/?probe=d6867703d7) | Mar 17, 2025 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [337ec97cc0](https://linux-hardware.org/?probe=337ec97cc0) | Mar 16, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRU9 83... | Notebook    | [d5780fcd88](https://linux-hardware.org/?probe=d5780fcd88) | Mar 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d139fa0e2b](https://linux-hardware.org/?probe=d139fa0e2b) | Mar 15, 2025 |
| Dell          | Vostro 3550                 | Notebook    | [3f89835d0a](https://linux-hardware.org/?probe=3f89835d0a) | Mar 15, 2025 |
| Lenovo        | ThinkPad P1 20MD0014RT      | Notebook    | [9cf3072357](https://linux-hardware.org/?probe=9cf3072357) | Mar 15, 2025 |
| Dell          | 0F5C5X A00                  | Desktop     | [897e1147ac](https://linux-hardware.org/?probe=897e1147ac) | Mar 15, 2025 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [58a6b2b6a6](https://linux-hardware.org/?probe=58a6b2b6a6) | Mar 15, 2025 |
| ASUSTek       | PRIME X399-A                | Desktop     | [18503c9d67](https://linux-hardware.org/?probe=18503c9d67) | Mar 14, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRU9 83... | Notebook    | [4cacca188d](https://linux-hardware.org/?probe=4cacca188d) | Mar 11, 2025 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [79d0d4fced](https://linux-hardware.org/?probe=79d0d4fced) | Mar 09, 2025 |
| Lenovo        | IdeaPadFlex 5 16IAU7 82R... | Convertible | [999943ce13](https://linux-hardware.org/?probe=999943ce13) | Mar 09, 2025 |
| Lenovo        | IdeaPadFlex 5 16IAU7 82R... | Convertible | [1bc97f70d5](https://linux-hardware.org/?probe=1bc97f70d5) | Mar 09, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRU9 83... | Notebook    | [f5178b0815](https://linux-hardware.org/?probe=f5178b0815) | Mar 09, 2025 |
| ASUSTek       | X501A                       | Notebook    | [aec782432b](https://linux-hardware.org/?probe=aec782432b) | Mar 08, 2025 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [83af6fd310](https://linux-hardware.org/?probe=83af6fd310) | Mar 07, 2025 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [f8fcd6abc9](https://linux-hardware.org/?probe=f8fcd6abc9) | Mar 06, 2025 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [bcd975c749](https://linux-hardware.org/?probe=bcd975c749) | Mar 02, 2025 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [c372ec159d](https://linux-hardware.org/?probe=c372ec159d) | Mar 01, 2025 |
| Lenovo        | ThinkPad X270 20HN0016IV    | Notebook    | [00c147768c](https://linux-hardware.org/?probe=00c147768c) | Feb 26, 2025 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [c46531eb09](https://linux-hardware.org/?probe=c46531eb09) | Feb 23, 2025 |
| ASUSTek       | B150M-K                     | Desktop     | [f71db79bbc](https://linux-hardware.org/?probe=f71db79bbc) | Feb 22, 2025 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7e6ea2fc59](https://linux-hardware.org/?probe=7e6ea2fc59) | Feb 22, 2025 |
| MSI           | B450M MORTAR MAX            | Desktop     | [673b7dc969](https://linux-hardware.org/?probe=673b7dc969) | Feb 18, 2025 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4577def586](https://linux-hardware.org/?probe=4577def586) | Feb 18, 2025 |
| HP            | EliteBook x360 830 G6       | Convertible | [77c8537c3f](https://linux-hardware.org/?probe=77c8537c3f) | Feb 16, 2025 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [a85355dc50](https://linux-hardware.org/?probe=a85355dc50) | Feb 14, 2025 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [e253fc7e30](https://linux-hardware.org/?probe=e253fc7e30) | Feb 12, 2025 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d450f1e0e4](https://linux-hardware.org/?probe=d450f1e0e4) | Feb 12, 2025 |
| Congatec      | conga-B7XD A.1              | Mini pc     | [29f42e1700](https://linux-hardware.org/?probe=29f42e1700) | Feb 12, 2025 |
| Congatec      | conga-B7XD A.1              | Mini pc     | [ca0a07614e](https://linux-hardware.org/?probe=ca0a07614e) | Feb 12, 2025 |
| Dell          | 054M2X A01                  | Server      | [bc055c8a01](https://linux-hardware.org/?probe=bc055c8a01) | Feb 12, 2025 |
| Dell          | 054M2X A01                  | Server      | [f1a2387385](https://linux-hardware.org/?probe=f1a2387385) | Feb 12, 2025 |
| Dell          | Latitude E5540              | Notebook    | [dafcec39ca](https://linux-hardware.org/?probe=dafcec39ca) | Feb 06, 2025 |
| Dell          | Vostro 3550                 | Notebook    | [f80b8c9ae3](https://linux-hardware.org/?probe=f80b8c9ae3) | Feb 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [9d8aa07266](https://linux-hardware.org/?probe=9d8aa07266) | Feb 01, 2025 |
| Gigabyte      | H510M S2H V2                | Desktop     | [bd73d384b7](https://linux-hardware.org/?probe=bd73d384b7) | Jan 29, 2025 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [0ed4fad141](https://linux-hardware.org/?probe=0ed4fad141) | Jan 27, 2025 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [5d1e386461](https://linux-hardware.org/?probe=5d1e386461) | Jan 26, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [dae37279c1](https://linux-hardware.org/?probe=dae37279c1) | Jan 25, 2025 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [071d25e6f4](https://linux-hardware.org/?probe=071d25e6f4) | Jan 25, 2025 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [bf8da118d9](https://linux-hardware.org/?probe=bf8da118d9) | Jan 25, 2025 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [f108ca039d](https://linux-hardware.org/?probe=f108ca039d) | Jan 25, 2025 |
| HP            | Pavilion g6                 | Notebook    | [ad489a8bfd](https://linux-hardware.org/?probe=ad489a8bfd) | Jan 25, 2025 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [3d9b3509e4](https://linux-hardware.org/?probe=3d9b3509e4) | Jan 24, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [76f216f314](https://linux-hardware.org/?probe=76f216f314) | Jan 24, 2025 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | Desktop     | [106a54ad29](https://linux-hardware.org/?probe=106a54ad29) | Jan 22, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | Desktop     | [6301a10b52](https://linux-hardware.org/?probe=6301a10b52) | Jan 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [83f8c4edaa](https://linux-hardware.org/?probe=83f8c4edaa) | Jan 16, 2025 |
| Dell          | Latitude E5540              | Notebook    | [6b6a8b5bf5](https://linux-hardware.org/?probe=6b6a8b5bf5) | Jan 13, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | Desktop     | [6694d8316f](https://linux-hardware.org/?probe=6694d8316f) | Jan 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [c67c29c777](https://linux-hardware.org/?probe=c67c29c777) | Jan 09, 2025 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [269fca6eb9](https://linux-hardware.org/?probe=269fca6eb9) | Jan 08, 2025 |
| Lenovo        | IdeaPad Flex-15IML 81XH     | Convertible | [9579158217](https://linux-hardware.org/?probe=9579158217) | Jan 03, 2025 |
| Lenovo        | IdeaPad C340-15IIL 81XJ     | Convertible | [21702287f9](https://linux-hardware.org/?probe=21702287f9) | Dec 30, 2024 |
| Lenovo        | ThinkPad X201 3680X08       | Notebook    | [29505fa5be](https://linux-hardware.org/?probe=29505fa5be) | Dec 30, 2024 |
| Lenovo        | IdeaPad Flex-15IML 81XH     | Convertible | [954e8986ce](https://linux-hardware.org/?probe=954e8986ce) | Dec 29, 2024 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [0574e44035](https://linux-hardware.org/?probe=0574e44035) | Dec 27, 2024 |
| MSI           | Creator 15 A11UE            | Notebook    | [c6e4f39a97](https://linux-hardware.org/?probe=c6e4f39a97) | Dec 24, 2024 |
| MSI           | Creator 15 A11UE            | Notebook    | [9beee8397d](https://linux-hardware.org/?probe=9beee8397d) | Dec 23, 2024 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ba9c0c5153](https://linux-hardware.org/?probe=ba9c0c5153) | Dec 23, 2024 |
| Intel         | NUC13ANBi7 N13084-202       | Mini pc     | [b3512c9ee2](https://linux-hardware.org/?probe=b3512c9ee2) | Dec 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P1512CEA... | Notebook    | [50c7d7cd7d](https://linux-hardware.org/?probe=50c7d7cd7d) | Dec 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [0c9e61a477](https://linux-hardware.org/?probe=0c9e61a477) | Dec 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7ce6a920fc](https://linux-hardware.org/?probe=7ce6a920fc) | Dec 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c62449864b](https://linux-hardware.org/?probe=c62449864b) | Dec 16, 2024 |
| Dell          | 0NC2VH A01                  | Desktop     | [4810f67ef7](https://linux-hardware.org/?probe=4810f67ef7) | Dec 15, 2024 |
| ASUSTek       | ASUS Vivobook 15 X1504VA... | Notebook    | [f1a3ece9ad](https://linux-hardware.org/?probe=f1a3ece9ad) | Dec 14, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [f4068911f7](https://linux-hardware.org/?probe=f4068911f7) | Dec 11, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [ff4dba5e4a](https://linux-hardware.org/?probe=ff4dba5e4a) | Dec 11, 2024 |
| Dell          | 0TTDMJ A00                  | Desktop     | [4ee281d915](https://linux-hardware.org/?probe=4ee281d915) | Dec 11, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [5ddf12e747](https://linux-hardware.org/?probe=5ddf12e747) | Dec 11, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [8b0aec2d81](https://linux-hardware.org/?probe=8b0aec2d81) | Dec 11, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [6e65ff5ccb](https://linux-hardware.org/?probe=6e65ff5ccb) | Dec 11, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [c4c1d233eb](https://linux-hardware.org/?probe=c4c1d233eb) | Dec 11, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [269aaa66b9](https://linux-hardware.org/?probe=269aaa66b9) | Dec 11, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [7c77f0a04f](https://linux-hardware.org/?probe=7c77f0a04f) | Dec 09, 2024 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [e25da0298a](https://linux-hardware.org/?probe=e25da0298a) | Dec 06, 2024 |
| Dell          | Latitude 5420               | Notebook    | [1d2ec04557](https://linux-hardware.org/?probe=1d2ec04557) | Dec 05, 2024 |
| Dell          | XPS 9320                    | Notebook    | [811e6628a8](https://linux-hardware.org/?probe=811e6628a8) | Dec 05, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [7342faf26d](https://linux-hardware.org/?probe=7342faf26d) | Nov 29, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3419013123](https://linux-hardware.org/?probe=3419013123) | Nov 29, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [0dc0dd7a62](https://linux-hardware.org/?probe=0dc0dd7a62) | Nov 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db45208c40](https://linux-hardware.org/?probe=db45208c40) | Nov 18, 2024 |
| Lenovo        | S40-70 80GQ                 | Notebook    | [b0d5d5f873](https://linux-hardware.org/?probe=b0d5d5f873) | Nov 14, 2024 |
| MSI           | H370 GAMING PLUS            | Desktop     | [73b7ffd3d7](https://linux-hardware.org/?probe=73b7ffd3d7) | Nov 13, 2024 |
| MSI           | H370 GAMING PLUS            | Desktop     | [967037bf19](https://linux-hardware.org/?probe=967037bf19) | Nov 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [77c6929edc](https://linux-hardware.org/?probe=77c6929edc) | Nov 13, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [fb1cba8a45](https://linux-hardware.org/?probe=fb1cba8a45) | Nov 11, 2024 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [2a7fa5eed7](https://linux-hardware.org/?probe=2a7fa5eed7) | Nov 11, 2024 |
| Lenovo        | G560 0679                   | Notebook    | [c1388a004e](https://linux-hardware.org/?probe=c1388a004e) | Nov 11, 2024 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [d244f80fd9](https://linux-hardware.org/?probe=d244f80fd9) | Nov 10, 2024 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [f711f4d637](https://linux-hardware.org/?probe=f711f4d637) | Nov 06, 2024 |
| Gigabyte      | B365M DS3H                  | Desktop     | [6dc9cbaf0c](https://linux-hardware.org/?probe=6dc9cbaf0c) | Nov 06, 2024 |
| Gigabyte      | B365M DS3H                  | Desktop     | [532b386733](https://linux-hardware.org/?probe=532b386733) | Nov 06, 2024 |
| Dell          | Latitude 3540               | Notebook    | [a479cc9719](https://linux-hardware.org/?probe=a479cc9719) | Nov 04, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [1b69401ca3](https://linux-hardware.org/?probe=1b69401ca3) | Nov 03, 2024 |
| Micro Comp... | V3                          | Tablet      | [db12421235](https://linux-hardware.org/?probe=db12421235) | Oct 30, 2024 |
| Micro Comp... | V3                          | Tablet      | [42d391649b](https://linux-hardware.org/?probe=42d391649b) | Oct 30, 2024 |
| GPD           | G1619-04                    | Notebook    | [8d4edea2b8](https://linux-hardware.org/?probe=8d4edea2b8) | Oct 28, 2024 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [83c95a2454](https://linux-hardware.org/?probe=83c95a2454) | Oct 26, 2024 |
| Dell          | Latitude E5540              | Notebook    | [da1eff5497](https://linux-hardware.org/?probe=da1eff5497) | Oct 24, 2024 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [1f2717878d](https://linux-hardware.org/?probe=1f2717878d) | Oct 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [e9e3c256d2](https://linux-hardware.org/?probe=e9e3c256d2) | Oct 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [03eebd41be](https://linux-hardware.org/?probe=03eebd41be) | Oct 18, 2024 |
| HP            | ProBook 445 G7              | Notebook    | [d98cc0dea5](https://linux-hardware.org/?probe=d98cc0dea5) | Oct 17, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8366c88c2a](https://linux-hardware.org/?probe=8366c88c2a) | Oct 17, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [f872a97890](https://linux-hardware.org/?probe=f872a97890) | Oct 16, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [725759c6d6](https://linux-hardware.org/?probe=725759c6d6) | Oct 14, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [441346e35f](https://linux-hardware.org/?probe=441346e35f) | Oct 14, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [6a20c0ad19](https://linux-hardware.org/?probe=6a20c0ad19) | Oct 11, 2024 |
| System76      | Lemur Pro                   | Notebook    | [0e513dcca4](https://linux-hardware.org/?probe=0e513dcca4) | Oct 09, 2024 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [b3f66f8d51](https://linux-hardware.org/?probe=b3f66f8d51) | Oct 07, 2024 |
| Lenovo        | Yoga 500-15ISK 80R6         | Notebook    | [8fadc9f74b](https://linux-hardware.org/?probe=8fadc9f74b) | Oct 07, 2024 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [21cc874a16](https://linux-hardware.org/?probe=21cc874a16) | Oct 03, 2024 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [4a6207dc35](https://linux-hardware.org/?probe=4a6207dc35) | Oct 03, 2024 |
| HP            | 8597                        | Desktop     | [39f106b002](https://linux-hardware.org/?probe=39f106b002) | Sep 29, 2024 |
| HP            | 340S G7                     | Notebook    | [289c918fd8](https://linux-hardware.org/?probe=289c918fd8) | Sep 25, 2024 |
| HP            | 340S G7                     | Notebook    | [df45d811d6](https://linux-hardware.org/?probe=df45d811d6) | Sep 25, 2024 |
| Lenovo        | Yoga 9 2-in-1 14IMH9 83A... | Convertible | [3841765926](https://linux-hardware.org/?probe=3841765926) | Sep 19, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [b2095e6211](https://linux-hardware.org/?probe=b2095e6211) | Sep 16, 2024 |
| Framework     | Laptop                      | Notebook    | [ac09197e5d](https://linux-hardware.org/?probe=ac09197e5d) | Sep 16, 2024 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [8593e26a94](https://linux-hardware.org/?probe=8593e26a94) | Sep 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [160a67618d](https://linux-hardware.org/?probe=160a67618d) | Sep 09, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [cc11d84cd6](https://linux-hardware.org/?probe=cc11d84cd6) | Sep 09, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [8279710a58](https://linux-hardware.org/?probe=8279710a58) | Sep 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | Notebook    | [32b933b3d1](https://linux-hardware.org/?probe=32b933b3d1) | Sep 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | Notebook    | [815ddf6853](https://linux-hardware.org/?probe=815ddf6853) | Sep 05, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [64d3ba9633](https://linux-hardware.org/?probe=64d3ba9633) | Sep 02, 2024 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [508cc6407e](https://linux-hardware.org/?probe=508cc6407e) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [07a2f372ea](https://linux-hardware.org/?probe=07a2f372ea) | Aug 30, 2024 |
| MSI           | MPG Z790I EDGE WIFI         | Desktop     | [befece1a07](https://linux-hardware.org/?probe=befece1a07) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | Desktop     | [73df0e9be3](https://linux-hardware.org/?probe=73df0e9be3) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | Desktop     | [c3687b0959](https://linux-hardware.org/?probe=c3687b0959) | Aug 28, 2024 |
| HP            | 15 TS                       | Notebook    | [b23e3c74fc](https://linux-hardware.org/?probe=b23e3c74fc) | Aug 23, 2024 |
| HP            | 15 TS                       | Notebook    | [1498cfa38b](https://linux-hardware.org/?probe=1498cfa38b) | Aug 23, 2024 |
| HP            | 18E4                        | Desktop     | [d92f2ebee9](https://linux-hardware.org/?probe=d92f2ebee9) | Aug 22, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [d91c8a70ea](https://linux-hardware.org/?probe=d91c8a70ea) | Aug 21, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ff71054b4c](https://linux-hardware.org/?probe=ff71054b4c) | Aug 20, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [1cceda0c67](https://linux-hardware.org/?probe=1cceda0c67) | Aug 20, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [7e7177ec16](https://linux-hardware.org/?probe=7e7177ec16) | Aug 19, 2024 |
| HP            | 1497                        | Desktop     | [3eea55dbb0](https://linux-hardware.org/?probe=3eea55dbb0) | Aug 18, 2024 |
| ASUSTek       | H61M-E                      | Desktop     | [61f7b339bb](https://linux-hardware.org/?probe=61f7b339bb) | Aug 16, 2024 |
| Alienware     | 17 R4                       | Notebook    | [c88b350309](https://linux-hardware.org/?probe=c88b350309) | Aug 14, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c670222db7](https://linux-hardware.org/?probe=c670222db7) | Aug 12, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [92bd64ed1f](https://linux-hardware.org/?probe=92bd64ed1f) | Aug 10, 2024 |
| PC Engines    | APU2                        | Desktop     | [d9b2540ad8](https://linux-hardware.org/?probe=d9b2540ad8) | Aug 09, 2024 |
| PC Engines    | APU2                        | Desktop     | [eb8b44a1a2](https://linux-hardware.org/?probe=eb8b44a1a2) | Aug 09, 2024 |
| AMI           | PC1068                      | Notebook    | [c4eb235653](https://linux-hardware.org/?probe=c4eb235653) | Aug 09, 2024 |
| JINGSHA       | X99-D8I                     | Desktop     | [562c50431e](https://linux-hardware.org/?probe=562c50431e) | Aug 07, 2024 |
| ASUSTek       | X401U                       | Notebook    | [ea3228e385](https://linux-hardware.org/?probe=ea3228e385) | Aug 07, 2024 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [f97ebe97b9](https://linux-hardware.org/?probe=f97ebe97b9) | Aug 04, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [75d20750c2](https://linux-hardware.org/?probe=75d20750c2) | Aug 04, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [6cdf96758d](https://linux-hardware.org/?probe=6cdf96758d) | Aug 01, 2024 |
| HP            | 15 TS                       | Notebook    | [75411019b4](https://linux-hardware.org/?probe=75411019b4) | Jul 28, 2024 |
| HP            | 15 TS                       | Notebook    | [1407e7426f](https://linux-hardware.org/?probe=1407e7426f) | Jul 28, 2024 |
| HP            | 8715                        | Mini pc     | [2d257afc82](https://linux-hardware.org/?probe=2d257afc82) | Jul 26, 2024 |
| Apple         | MacBookPro13,1              | Notebook    | [f5b3a5f6d2](https://linux-hardware.org/?probe=f5b3a5f6d2) | Jul 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [74167b2017](https://linux-hardware.org/?probe=74167b2017) | Jul 21, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [8bf224e337](https://linux-hardware.org/?probe=8bf224e337) | Jul 19, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6262d5ff9d](https://linux-hardware.org/?probe=6262d5ff9d) | Jul 19, 2024 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [aa09fbc967](https://linux-hardware.org/?probe=aa09fbc967) | Jul 19, 2024 |
| HP            | EPROM DATA AREA             | Notebook    | [e227613970](https://linux-hardware.org/?probe=e227613970) | Jul 17, 2024 |
| Dell          | Latitude 7440               | Notebook    | [11f78bffe8](https://linux-hardware.org/?probe=11f78bffe8) | Jul 16, 2024 |
| GMKtec        | V1.0                        | Mini pc     | [4985ea8f29](https://linux-hardware.org/?probe=4985ea8f29) | Jul 15, 2024 |
| Dell          | Inspiron 7720               | Notebook    | [faa5f6deff](https://linux-hardware.org/?probe=faa5f6deff) | Jul 15, 2024 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [6b85eb16fe](https://linux-hardware.org/?probe=6b85eb16fe) | Jul 14, 2024 |
| ASRock        | H71M-DGS                    | Desktop     | [53971fc966](https://linux-hardware.org/?probe=53971fc966) | Jul 06, 2024 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bb1db7e4cf](https://linux-hardware.org/?probe=bb1db7e4cf) | Jul 06, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d97e407301](https://linux-hardware.org/?probe=d97e407301) | Jul 05, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [63adc91261](https://linux-hardware.org/?probe=63adc91261) | Jul 01, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [e09d0fb605](https://linux-hardware.org/?probe=e09d0fb605) | Jul 01, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [f91526c63f](https://linux-hardware.org/?probe=f91526c63f) | Jul 01, 2024 |
| MiTAC         | PH10CI AAG92370-407         | All in one  | [75f967b327](https://linux-hardware.org/?probe=75f967b327) | Jun 28, 2024 |
| MiTAC         | PH10CI AAG92370-407         | All in one  | [3b287b8f18](https://linux-hardware.org/?probe=3b287b8f18) | Jun 28, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [dbbac5dc30](https://linux-hardware.org/?probe=dbbac5dc30) | Jun 26, 2024 |
| Razer         | Blade 18 - RZ09-0509        | Notebook    | [d0e4380367](https://linux-hardware.org/?probe=d0e4380367) | Jun 23, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [2f77a86e56](https://linux-hardware.org/?probe=2f77a86e56) | Jun 23, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [c3f8e03876](https://linux-hardware.org/?probe=c3f8e03876) | Jun 22, 2024 |
| MSI           | PRO Z790-S WIFI             | Desktop     | [b2e22eb2a7](https://linux-hardware.org/?probe=b2e22eb2a7) | Jun 21, 2024 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [ce50118d2f](https://linux-hardware.org/?probe=ce50118d2f) | Jun 20, 2024 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [3ed708f769](https://linux-hardware.org/?probe=3ed708f769) | Jun 14, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [4ca7b4e167](https://linux-hardware.org/?probe=4ca7b4e167) | Jun 14, 2024 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [85ba61cf34](https://linux-hardware.org/?probe=85ba61cf34) | Jun 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4d3e8553c1](https://linux-hardware.org/?probe=4d3e8553c1) | Jun 11, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4d2d75e2c0](https://linux-hardware.org/?probe=4d2d75e2c0) | Jun 10, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e2b3f11050](https://linux-hardware.org/?probe=e2b3f11050) | Jun 08, 2024 |
| Lenovo        | IdeaPad Pro 5 16AHP9 83D... | Notebook    | [bc1e30a54a](https://linux-hardware.org/?probe=bc1e30a54a) | Jun 07, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [d4368125e3](https://linux-hardware.org/?probe=d4368125e3) | Jun 05, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [173ed79481](https://linux-hardware.org/?probe=173ed79481) | Jun 05, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [2662a521a5](https://linux-hardware.org/?probe=2662a521a5) | Jun 05, 2024 |
| Gigabyte      | H97M-D3H                    | Desktop     | [81620a0d8c](https://linux-hardware.org/?probe=81620a0d8c) | Jun 04, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [1cecc324c7](https://linux-hardware.org/?probe=1cecc324c7) | Jun 04, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [3240239bf4](https://linux-hardware.org/?probe=3240239bf4) | Jun 03, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [af64297908](https://linux-hardware.org/?probe=af64297908) | Jun 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4495279510](https://linux-hardware.org/?probe=4495279510) | May 28, 2024 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [a2dba1270b](https://linux-hardware.org/?probe=a2dba1270b) | May 27, 2024 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [361b16629e](https://linux-hardware.org/?probe=361b16629e) | May 27, 2024 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [5e056a0de3](https://linux-hardware.org/?probe=5e056a0de3) | May 25, 2024 |
| HP            | EPROM DATA AREA             | Notebook    | [0e28fcd875](https://linux-hardware.org/?probe=0e28fcd875) | May 24, 2024 |
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [efdbd13c32](https://linux-hardware.org/?probe=efdbd13c32) | May 24, 2024 |
| HP            | ProBook 430 G6              | Notebook    | [a0f5af084f](https://linux-hardware.org/?probe=a0f5af084f) | May 23, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [db403a9f18](https://linux-hardware.org/?probe=db403a9f18) | May 21, 2024 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [7fd5b705f5](https://linux-hardware.org/?probe=7fd5b705f5) | May 21, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [142f9d9e7f](https://linux-hardware.org/?probe=142f9d9e7f) | May 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [0040469fe5](https://linux-hardware.org/?probe=0040469fe5) | May 19, 2024 |
| Apple         | MacBookPro13,1              | Notebook    | [2d6a6783dc](https://linux-hardware.org/?probe=2d6a6783dc) | May 18, 2024 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [3e0b220a58](https://linux-hardware.org/?probe=3e0b220a58) | May 17, 2024 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7daed94e02](https://linux-hardware.org/?probe=7daed94e02) | May 15, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [dc23737df9](https://linux-hardware.org/?probe=dc23737df9) | May 12, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [775f9b664d](https://linux-hardware.org/?probe=775f9b664d) | May 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5c44adf6ab](https://linux-hardware.org/?probe=5c44adf6ab) | May 10, 2024 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [53dc445161](https://linux-hardware.org/?probe=53dc445161) | May 10, 2024 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [6fd6f40abe](https://linux-hardware.org/?probe=6fd6f40abe) | May 08, 2024 |
| N-one         | Nbook Ultra                 | Notebook    | [ae1609d065](https://linux-hardware.org/?probe=ae1609d065) | May 03, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [ab7c916d4c](https://linux-hardware.org/?probe=ab7c916d4c) | Apr 30, 2024 |
| Acer          | Aspire A115-32              | Notebook    | [32a4949c7c](https://linux-hardware.org/?probe=32a4949c7c) | Apr 30, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [44057fd7b0](https://linux-hardware.org/?probe=44057fd7b0) | Apr 30, 2024 |
| MSI           | H170M PRO-VDH               | Desktop     | [88dbd5e70e](https://linux-hardware.org/?probe=88dbd5e70e) | Apr 29, 2024 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [14706b4b9f](https://linux-hardware.org/?probe=14706b4b9f) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [dfcd535d56](https://linux-hardware.org/?probe=dfcd535d56) | Apr 27, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8eb518c57d](https://linux-hardware.org/?probe=8eb518c57d) | Apr 26, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [82c3a3a90b](https://linux-hardware.org/?probe=82c3a3a90b) | Apr 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55dc7f440b](https://linux-hardware.org/?probe=55dc7f440b) | Apr 24, 2024 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [8031865fea](https://linux-hardware.org/?probe=8031865fea) | Apr 23, 2024 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [d53dd10be1](https://linux-hardware.org/?probe=d53dd10be1) | Apr 23, 2024 |
| Lenovo        | B50-10 80QR                 | Notebook    | [3ac8b8986f](https://linux-hardware.org/?probe=3ac8b8986f) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a7180ee8da](https://linux-hardware.org/?probe=a7180ee8da) | Apr 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [4f61acab6e](https://linux-hardware.org/?probe=4f61acab6e) | Apr 19, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [267091524b](https://linux-hardware.org/?probe=267091524b) | Apr 18, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [8c33938518](https://linux-hardware.org/?probe=8c33938518) | Apr 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [21882b12a8](https://linux-hardware.org/?probe=21882b12a8) | Apr 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [a75cf3dc0f](https://linux-hardware.org/?probe=a75cf3dc0f) | Apr 10, 2024 |
| Dell          | 0KP561                      | Desktop     | [dd6f49d82f](https://linux-hardware.org/?probe=dd6f49d82f) | Apr 06, 2024 |
| Lenovo        | ThinkPad Edge 021722G       | Notebook    | [c737a0d5d1](https://linux-hardware.org/?probe=c737a0d5d1) | Apr 06, 2024 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8603f205ba](https://linux-hardware.org/?probe=8603f205ba) | Apr 05, 2024 |
| Lenovo        | Yoga 500-15ISK 80R6         | Notebook    | [a3712304cd](https://linux-hardware.org/?probe=a3712304cd) | Apr 05, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [690e191e65](https://linux-hardware.org/?probe=690e191e65) | Mar 26, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [8f0042ce48](https://linux-hardware.org/?probe=8f0042ce48) | Mar 25, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [d51e75a4b6](https://linux-hardware.org/?probe=d51e75a4b6) | Mar 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [0cee79fd45](https://linux-hardware.org/?probe=0cee79fd45) | Mar 24, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a72ba0acf1](https://linux-hardware.org/?probe=a72ba0acf1) | Mar 20, 2024 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [13aa36af3e](https://linux-hardware.org/?probe=13aa36af3e) | Mar 20, 2024 |
| Nvidia        | Tegra                       | Soc         | [08cba116d3](https://linux-hardware.org/?probe=08cba116d3) | Mar 19, 2024 |
| Nvidia        | Tegra                       | Soc         | [bfafae4c46](https://linux-hardware.org/?probe=bfafae4c46) | Mar 19, 2024 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [972b9375c7](https://linux-hardware.org/?probe=972b9375c7) | Mar 16, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [57bcbad84b](https://linux-hardware.org/?probe=57bcbad84b) | Mar 14, 2024 |
| Lenovo        | ThinkPad T420 4178B9G       | Notebook    | [6c729a3045](https://linux-hardware.org/?probe=6c729a3045) | Mar 13, 2024 |
| HP            | ProBook 6450b               | Notebook    | [6fe298067d](https://linux-hardware.org/?probe=6fe298067d) | Mar 13, 2024 |
| Lenovo        | 3176 SDK0K17763 WIN 1801... | Desktop     | [51143831ed](https://linux-hardware.org/?probe=51143831ed) | Mar 12, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [859c361cb9](https://linux-hardware.org/?probe=859c361cb9) | Mar 12, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [120f62e576](https://linux-hardware.org/?probe=120f62e576) | Mar 08, 2024 |
| AMI           | PC1068                      | Notebook    | [9b34e1b326](https://linux-hardware.org/?probe=9b34e1b326) | Mar 07, 2024 |
| Dell          | 0NC2VH A01                  | Desktop     | [3b3cdc41db](https://linux-hardware.org/?probe=3b3cdc41db) | Mar 07, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [6cffe59389](https://linux-hardware.org/?probe=6cffe59389) | Mar 02, 2024 |
| Gigabyte      | Z490 VISION G               | Desktop     | [23347b4c30](https://linux-hardware.org/?probe=23347b4c30) | Mar 02, 2024 |
| Gigabyte      | Z490 VISION G               | Desktop     | [f202c83002](https://linux-hardware.org/?probe=f202c83002) | Mar 02, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [b827b5e796](https://linux-hardware.org/?probe=b827b5e796) | Feb 29, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [20be6de7bc](https://linux-hardware.org/?probe=20be6de7bc) | Feb 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [f03ada23b3](https://linux-hardware.org/?probe=f03ada23b3) | Feb 27, 2024 |
| Lenovo        | ThinkPad T420 4178B9G       | Notebook    | [c3206e3d16](https://linux-hardware.org/?probe=c3206e3d16) | Feb 26, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4141eaaff5](https://linux-hardware.org/?probe=4141eaaff5) | Feb 25, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [c3f8f76b3a](https://linux-hardware.org/?probe=c3f8f76b3a) | Feb 24, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [e24927a5e5](https://linux-hardware.org/?probe=e24927a5e5) | Feb 19, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [6e61ee4b06](https://linux-hardware.org/?probe=6e61ee4b06) | Feb 18, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [2814bf63c1](https://linux-hardware.org/?probe=2814bf63c1) | Feb 18, 2024 |
| Lenovo        | ThinkPad T420 4178B9G       | Notebook    | [cce168db8a](https://linux-hardware.org/?probe=cce168db8a) | Feb 17, 2024 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [f940559e53](https://linux-hardware.org/?probe=f940559e53) | Feb 16, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [9adf8fd817](https://linux-hardware.org/?probe=9adf8fd817) | Feb 12, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [7841583f57](https://linux-hardware.org/?probe=7841583f57) | Feb 12, 2024 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [082308a172](https://linux-hardware.org/?probe=082308a172) | Feb 12, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [953b2c870f](https://linux-hardware.org/?probe=953b2c870f) | Feb 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [621267c761](https://linux-hardware.org/?probe=621267c761) | Feb 09, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [44bda25372](https://linux-hardware.org/?probe=44bda25372) | Feb 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [bb080b509b](https://linux-hardware.org/?probe=bb080b509b) | Feb 07, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [87f113db8c](https://linux-hardware.org/?probe=87f113db8c) | Feb 03, 2024 |
| Lenovo        | V14 G4 IRU 83A0             | Notebook    | [4f65dbee97](https://linux-hardware.org/?probe=4f65dbee97) | Feb 03, 2024 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | Notebook    | [001809149c](https://linux-hardware.org/?probe=001809149c) | Jan 31, 2024 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [d3aaef580d](https://linux-hardware.org/?probe=d3aaef580d) | Jan 28, 2024 |
| HP            | Pavilion 15                 | Notebook    | [3aed9dffe5](https://linux-hardware.org/?probe=3aed9dffe5) | Jan 26, 2024 |
| HP            | Pavilion 15                 | Notebook    | [5d449f9a23](https://linux-hardware.org/?probe=5d449f9a23) | Jan 26, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [fff575809c](https://linux-hardware.org/?probe=fff575809c) | Jan 25, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [a80c29ee33](https://linux-hardware.org/?probe=a80c29ee33) | Jan 23, 2024 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [27878d88fd](https://linux-hardware.org/?probe=27878d88fd) | Jan 23, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [a84ee0f485](https://linux-hardware.org/?probe=a84ee0f485) | Jan 23, 2024 |
| Lenovo        | IdeaPad Slim 3 16IRU8 82... | Notebook    | [7c0ccbc993](https://linux-hardware.org/?probe=7c0ccbc993) | Jan 17, 2024 |
| Lenovo        | LOQ 16IRH8 82XW             | Notebook    | [4bebc58063](https://linux-hardware.org/?probe=4bebc58063) | Jan 15, 2024 |
| Lenovo        | LOQ 16IRH8 82XW             | Notebook    | [2eef3e875d](https://linux-hardware.org/?probe=2eef3e875d) | Jan 15, 2024 |
| ASUSTek       | ROG Strix G532LW_G532LW     | Notebook    | [c2778b6624](https://linux-hardware.org/?probe=c2778b6624) | Jan 13, 2024 |
| Dell          | G5 5587                     | Notebook    | [a1342378d3](https://linux-hardware.org/?probe=a1342378d3) | Jan 10, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [26b15c1102](https://linux-hardware.org/?probe=26b15c1102) | Jan 08, 2024 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [042f4d56ce](https://linux-hardware.org/?probe=042f4d56ce) | Jan 06, 2024 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [3607077350](https://linux-hardware.org/?probe=3607077350) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [f42a6325e3](https://linux-hardware.org/?probe=f42a6325e3) | Dec 29, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [0d4c53d42f](https://linux-hardware.org/?probe=0d4c53d42f) | Dec 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [94cf6bda69](https://linux-hardware.org/?probe=94cf6bda69) | Dec 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [69ec584b3a](https://linux-hardware.org/?probe=69ec584b3a) | Dec 25, 2023 |
| Lenovo        | Unknown                     | Notebook    | [9faf2278bb](https://linux-hardware.org/?probe=9faf2278bb) | Dec 24, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [5267b86c06](https://linux-hardware.org/?probe=5267b86c06) | Dec 24, 2023 |
| Gigabyte      | B460M GAMING HD             | Desktop     | [6669971369](https://linux-hardware.org/?probe=6669971369) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9425eb3c77](https://linux-hardware.org/?probe=9425eb3c77) | Dec 23, 2023 |
| Lenovo        | M30-70 80H8                 | Notebook    | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [2464a532b8](https://linux-hardware.org/?probe=2464a532b8) | Dec 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7a4d520ba9](https://linux-hardware.org/?probe=7a4d520ba9) | Dec 20, 2023 |
| Intel         | H61                         | Desktop     | [01b739e240](https://linux-hardware.org/?probe=01b739e240) | Dec 20, 2023 |
| Lenovo        | 310C SDK0J40705 WIN 3425... | Desktop     | [c1ee1cd84d](https://linux-hardware.org/?probe=c1ee1cd84d) | Dec 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [c20f7cf0e0](https://linux-hardware.org/?probe=c20f7cf0e0) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [20edb747d9](https://linux-hardware.org/?probe=20edb747d9) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [44c8944047](https://linux-hardware.org/?probe=44c8944047) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1c015093b2](https://linux-hardware.org/?probe=1c015093b2) | Dec 18, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [22d7c1e77c](https://linux-hardware.org/?probe=22d7c1e77c) | Dec 16, 2023 |
| Unknown       | Unknown                     | Soc         | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| HP            | 18E4                        | Desktop     | [1dd0e805dc](https://linux-hardware.org/?probe=1dd0e805dc) | Dec 13, 2023 |
| Acer          | Predator G3610              | Desktop     | [0a8a3e6bc5](https://linux-hardware.org/?probe=0a8a3e6bc5) | Dec 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [9bb3c76c9f](https://linux-hardware.org/?probe=9bb3c76c9f) | Dec 10, 2023 |
| ASUSTek       | D540MA-C                    | Desktop     | [a5beb93a51](https://linux-hardware.org/?probe=a5beb93a51) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [eea00eb64c](https://linux-hardware.org/?probe=eea00eb64c) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5940ba1d2c](https://linux-hardware.org/?probe=5940ba1d2c) | Dec 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee3494fa57](https://linux-hardware.org/?probe=ee3494fa57) | Dec 06, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [a7dd623bb6](https://linux-hardware.org/?probe=a7dd623bb6) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [d28a7f3ad6](https://linux-hardware.org/?probe=d28a7f3ad6) | Dec 04, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [20e77986a2](https://linux-hardware.org/?probe=20e77986a2) | Dec 03, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [55eb62ad2f](https://linux-hardware.org/?probe=55eb62ad2f) | Dec 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8952a98c](https://linux-hardware.org/?probe=ff8952a98c) | Dec 01, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [dac97296b0](https://linux-hardware.org/?probe=dac97296b0) | Nov 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [be36e8725c](https://linux-hardware.org/?probe=be36e8725c) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [a719bb0ba3](https://linux-hardware.org/?probe=a719bb0ba3) | Nov 25, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a59b920838](https://linux-hardware.org/?probe=a59b920838) | Nov 24, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d188fc3095](https://linux-hardware.org/?probe=d188fc3095) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [ab7968d6da](https://linux-hardware.org/?probe=ab7968d6da) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [95f01d6e47](https://linux-hardware.org/?probe=95f01d6e47) | Nov 15, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [74a1a56aff](https://linux-hardware.org/?probe=74a1a56aff) | Oct 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [42a94f2f97](https://linux-hardware.org/?probe=42a94f2f97) | Oct 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [37e69bd8a8](https://linux-hardware.org/?probe=37e69bd8a8) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| HP            | 83EB                        | All in one  | [f655dc8e65](https://linux-hardware.org/?probe=f655dc8e65) | Oct 18, 2023 |
| MSI           | MS-1T31                     | Desktop     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [9ed8384df0](https://linux-hardware.org/?probe=9ed8384df0) | Oct 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5b710d03c5](https://linux-hardware.org/?probe=5b710d03c5) | Oct 09, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [3dc549dba2](https://linux-hardware.org/?probe=3dc549dba2) | Oct 09, 2023 |
| Dell          | Latitude 5411               | Notebook    | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | Latitude 7400               | Notebook    | [1c4da154d8](https://linux-hardware.org/?probe=1c4da154d8) | Oct 07, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d5b22876c6](https://linux-hardware.org/?probe=d5b22876c6) | Oct 04, 2023 |
| Dell          | Precision 5750              | Notebook    | [839fea4442](https://linux-hardware.org/?probe=839fea4442) | Oct 04, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [9dc3e0f9f9](https://linux-hardware.org/?probe=9dc3e0f9f9) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [18c399ea1e](https://linux-hardware.org/?probe=18c399ea1e) | Oct 04, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [3d7d389342](https://linux-hardware.org/?probe=3d7d389342) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4095fbc19e](https://linux-hardware.org/?probe=4095fbc19e) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [faf68444bc](https://linux-hardware.org/?probe=faf68444bc) | Sep 24, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d3f5dd9d13](https://linux-hardware.org/?probe=d3f5dd9d13) | Sep 19, 2023 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [264e42215e](https://linux-hardware.org/?probe=264e42215e) | Sep 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [243f46cfa8](https://linux-hardware.org/?probe=243f46cfa8) | Sep 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5cd83bcad9](https://linux-hardware.org/?probe=5cd83bcad9) | Sep 15, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [951faca7d0](https://linux-hardware.org/?probe=951faca7d0) | Sep 11, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [433e6a45a9](https://linux-hardware.org/?probe=433e6a45a9) | Sep 11, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [139a93ab8b](https://linux-hardware.org/?probe=139a93ab8b) | Sep 09, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [29d9f2566a](https://linux-hardware.org/?probe=29d9f2566a) | Sep 06, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [5c165fd73b](https://linux-hardware.org/?probe=5c165fd73b) | Sep 06, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [681020d244](https://linux-hardware.org/?probe=681020d244) | Sep 01, 2023 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [dc7b90d27f](https://linux-hardware.org/?probe=dc7b90d27f) | Sep 01, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [b37d00fb4d](https://linux-hardware.org/?probe=b37d00fb4d) | Sep 01, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [c1a4e5d47f](https://linux-hardware.org/?probe=c1a4e5d47f) | Aug 30, 2023 |
| ASUSTek       | D540MA-C                    | Desktop     | [67eb1455a6](https://linux-hardware.org/?probe=67eb1455a6) | Aug 30, 2023 |
| Dell          | 0X75JG A01                  | Desktop     | [bdf9baca2f](https://linux-hardware.org/?probe=bdf9baca2f) | Aug 29, 2023 |
| HP            | 255 G2                      | Notebook    | [23bf2dd515](https://linux-hardware.org/?probe=23bf2dd515) | Aug 29, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3c5aa8e05a](https://linux-hardware.org/?probe=3c5aa8e05a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [1562efcaf2](https://linux-hardware.org/?probe=1562efcaf2) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [e45572b49a](https://linux-hardware.org/?probe=e45572b49a) | Aug 23, 2023 |
| Dell          | 0215PR A02                  | Desktop     | [dd5966ce9b](https://linux-hardware.org/?probe=dd5966ce9b) | Aug 23, 2023 |
| ASUSTek       | Z10PG-D24 Series            | Desktop     | [127be55832](https://linux-hardware.org/?probe=127be55832) | Aug 23, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [a554b5fcd4](https://linux-hardware.org/?probe=a554b5fcd4) | Aug 22, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [71520ab551](https://linux-hardware.org/?probe=71520ab551) | Aug 22, 2023 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [3b1c4bacb9](https://linux-hardware.org/?probe=3b1c4bacb9) | Aug 21, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [a662b29087](https://linux-hardware.org/?probe=a662b29087) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [97ed27473e](https://linux-hardware.org/?probe=97ed27473e) | Aug 20, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [28a27adc22](https://linux-hardware.org/?probe=28a27adc22) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [498c86055c](https://linux-hardware.org/?probe=498c86055c) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [7a389ac976](https://linux-hardware.org/?probe=7a389ac976) | Aug 19, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [41bbf2a956](https://linux-hardware.org/?probe=41bbf2a956) | Aug 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [8ef1bbdcec](https://linux-hardware.org/?probe=8ef1bbdcec) | Aug 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [8360dc045f](https://linux-hardware.org/?probe=8360dc045f) | Aug 06, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [cad443cf78](https://linux-hardware.org/?probe=cad443cf78) | Aug 06, 2023 |
| HP            | 805D                        | Desktop     | [672e431e69](https://linux-hardware.org/?probe=672e431e69) | Aug 06, 2023 |
| Dell          | Latitude 5480               | Notebook    | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Lenovo        | ThinkPad X280 20KES3D900    | Notebook    | [865dbfa247](https://linux-hardware.org/?probe=865dbfa247) | Aug 03, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [0e28c2aae2](https://linux-hardware.org/?probe=0e28c2aae2) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [4172f7fd39](https://linux-hardware.org/?probe=4172f7fd39) | Jul 21, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [7b7cf50cba](https://linux-hardware.org/?probe=7b7cf50cba) | Jul 18, 2023 |
| Lenovo        | ThinkPad X240 20AMA04FIV    | Notebook    | [e16d9ae667](https://linux-hardware.org/?probe=e16d9ae667) | Jul 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| HP            | 8267 A01                    | Mini pc     | [442a7f8911](https://linux-hardware.org/?probe=442a7f8911) | Jul 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [5ac5b565cd](https://linux-hardware.org/?probe=5ac5b565cd) | Jul 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f79821f2eb](https://linux-hardware.org/?probe=f79821f2eb) | Jul 09, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f003f0aa32](https://linux-hardware.org/?probe=f003f0aa32) | Jul 06, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [a39f1dd1ad](https://linux-hardware.org/?probe=a39f1dd1ad) | Jul 04, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [7aed7e46ad](https://linux-hardware.org/?probe=7aed7e46ad) | Jul 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [a4a8cc1e65](https://linux-hardware.org/?probe=a4a8cc1e65) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [d5cb3d4bfa](https://linux-hardware.org/?probe=d5cb3d4bfa) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L50-A         | Notebook    | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | Notebook    | [a2e5b66940](https://linux-hardware.org/?probe=a2e5b66940) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [6c260b1543](https://linux-hardware.org/?probe=6c260b1543) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7c906bbd1c](https://linux-hardware.org/?probe=7c906bbd1c) | Jun 20, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [65385cc189](https://linux-hardware.org/?probe=65385cc189) | Jun 19, 2023 |
| Framework     | Laptop                      | Notebook    | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| Razer         | Blade Stealth               | Notebook    | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Google        | Atlas                       | Notebook    | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [d183d47822](https://linux-hardware.org/?probe=d183d47822) | Jun 12, 2023 |
| Dell          | Latitude 7440               | Notebook    | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [9e3dfb25be](https://linux-hardware.org/?probe=9e3dfb25be) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | Notebook    | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [bb29d15c61](https://linux-hardware.org/?probe=bb29d15c61) | Jun 05, 2023 |
| Huanan        | X79 V7.11                   | Desktop     | [79bbc880ba](https://linux-hardware.org/?probe=79bbc880ba) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [9cba800830](https://linux-hardware.org/?probe=9cba800830) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [00e3bf6a3e](https://linux-hardware.org/?probe=00e3bf6a3e) | May 17, 2023 |
| Dell          | Latitude 5401               | Notebook    | [4304efbed6](https://linux-hardware.org/?probe=4304efbed6) | May 15, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [0b26ce1a71](https://linux-hardware.org/?probe=0b26ce1a71) | May 12, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [c821704a04](https://linux-hardware.org/?probe=c821704a04) | May 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [9bd04974e8](https://linux-hardware.org/?probe=9bd04974e8) | May 09, 2023 |
| MSI           | H61M-E23                    | Desktop     | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Razer         | Blade                       | Notebook    | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [b577b4aa25](https://linux-hardware.org/?probe=b577b4aa25) | May 06, 2023 |
| Apple         | MacBook10,1                 | Notebook    | [b951048d8f](https://linux-hardware.org/?probe=b951048d8f) | May 05, 2023 |
| Apple         | MacBook10,1                 | Notebook    | [6796aa4cf0](https://linux-hardware.org/?probe=6796aa4cf0) | May 05, 2023 |
| Acer          | Aspire one                  | Notebook    | [90d59ac61a](https://linux-hardware.org/?probe=90d59ac61a) | May 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [aeabc8c63c](https://linux-hardware.org/?probe=aeabc8c63c) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [18de5959b7](https://linux-hardware.org/?probe=18de5959b7) | May 01, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [b80d03be6d](https://linux-hardware.org/?probe=b80d03be6d) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [09d116d762](https://linux-hardware.org/?probe=09d116d762) | Apr 23, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [0baff3522f](https://linux-hardware.org/?probe=0baff3522f) | Apr 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [56768ba5a6](https://linux-hardware.org/?probe=56768ba5a6) | Apr 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | Notebook    | [5a17f65715](https://linux-hardware.org/?probe=5a17f65715) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| Dell          | Latitude 5491               | Notebook    | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| Intel         | D945GCCR AAD78647-301       | Desktop     | [fac1992089](https://linux-hardware.org/?probe=fac1992089) | Apr 13, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [917791ff47](https://linux-hardware.org/?probe=917791ff47) | Apr 12, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [e9790ea3b6](https://linux-hardware.org/?probe=e9790ea3b6) | Apr 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c871e7c68b](https://linux-hardware.org/?probe=c871e7c68b) | Apr 07, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | 8455                        | Desktop     | [a52e3d086a](https://linux-hardware.org/?probe=a52e3d086a) | Apr 04, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| ASUSTek       | PN51-S1                     | Mini pc     | [2b534dd0fa](https://linux-hardware.org/?probe=2b534dd0fa) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [4cfac9a162](https://linux-hardware.org/?probe=4cfac9a162) | Mar 30, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [507f441bfc](https://linux-hardware.org/?probe=507f441bfc) | Mar 30, 2023 |
| Acer          | Aspire 5820                 | Notebook    | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| ASUSTek       | PN62                        | Mini pc     | [9cd806cb31](https://linux-hardware.org/?probe=9cd806cb31) | Mar 20, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| Gigabyte      | AORUS 17G XC                | Notebook    | [fb998b9957](https://linux-hardware.org/?probe=fb998b9957) | Mar 12, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [35a78f2cf1](https://linux-hardware.org/?probe=35a78f2cf1) | Mar 08, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [c0e9304de5](https://linux-hardware.org/?probe=c0e9304de5) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [2d713931d2](https://linux-hardware.org/?probe=2d713931d2) | Feb 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| HP            | Pavilion TS 14              | Notebook    | [37296c42c3](https://linux-hardware.org/?probe=37296c42c3) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [323b6463a9](https://linux-hardware.org/?probe=323b6463a9) | Feb 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Alienware     | 15 R2                       | Notebook    | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7415192b86](https://linux-hardware.org/?probe=7415192b86) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [e958da375f](https://linux-hardware.org/?probe=e958da375f) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [e47bb0ee84](https://linux-hardware.org/?probe=e47bb0ee84) | Feb 19, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [6f8fadfe19](https://linux-hardware.org/?probe=6f8fadfe19) | Feb 15, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [26ea96167c](https://linux-hardware.org/?probe=26ea96167c) | Feb 12, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [bb53ff2532](https://linux-hardware.org/?probe=bb53ff2532) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [ab928273ba](https://linux-hardware.org/?probe=ab928273ba) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [5995e0b36b](https://linux-hardware.org/?probe=5995e0b36b) | Feb 11, 2023 |
| Heptagon S... | HQ-BOX2 Server              | Notebook    | [476197a287](https://linux-hardware.org/?probe=476197a287) | Feb 09, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | Notebook    | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [f7f587188e](https://linux-hardware.org/?probe=f7f587188e) | Feb 03, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK U554               | Notebook    | [22bf4111de](https://linux-hardware.org/?probe=22bf4111de) | Jan 23, 2023 |
| Acer          | TravelMate P257-M           | Notebook    | [1345fa56c4](https://linux-hardware.org/?probe=1345fa56c4) | Jan 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [79a45b9ea0](https://linux-hardware.org/?probe=79a45b9ea0) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Dell          | Vostro 14 5401              | Notebook    | [b56e81d82d](https://linux-hardware.org/?probe=b56e81d82d) | Jan 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [3965f2f9f4](https://linux-hardware.org/?probe=3965f2f9f4) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [78a20b41ee](https://linux-hardware.org/?probe=78a20b41ee) | Jan 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [abe344877a](https://linux-hardware.org/?probe=abe344877a) | Jan 09, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [6a5da8e502](https://linux-hardware.org/?probe=6a5da8e502) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9767004b24](https://linux-hardware.org/?probe=9767004b24) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [87c4201895](https://linux-hardware.org/?probe=87c4201895) | Jan 07, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [874b25fc88](https://linux-hardware.org/?probe=874b25fc88) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4641833cab](https://linux-hardware.org/?probe=4641833cab) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Dell          | 0PV9DG A01                  | Server      | [7f408923fa](https://linux-hardware.org/?probe=7f408923fa) | Dec 27, 2022 |
| GPD           | G1621-02                    | Notebook    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [10f4ac5e13](https://linux-hardware.org/?probe=10f4ac5e13) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b9b1f8140b](https://linux-hardware.org/?probe=b9b1f8140b) | Dec 18, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | Notebook    | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [dc13dde66a](https://linux-hardware.org/?probe=dc13dde66a) | Nov 29, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [504222de34](https://linux-hardware.org/?probe=504222de34) | Nov 20, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [f685fd9050](https://linux-hardware.org/?probe=f685fd9050) | Nov 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [ae100dd7e2](https://linux-hardware.org/?probe=ae100dd7e2) | Nov 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [c22dce3d23](https://linux-hardware.org/?probe=c22dce3d23) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| HP            | 88BE                        | Desktop     | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [f04bf95806](https://linux-hardware.org/?probe=f04bf95806) | Nov 08, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [da03d56b4e](https://linux-hardware.org/?probe=da03d56b4e) | Nov 07, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4099d3c69b](https://linux-hardware.org/?probe=4099d3c69b) | Nov 05, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c35a514fe5](https://linux-hardware.org/?probe=c35a514fe5) | Nov 05, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [be2ceae6ca](https://linux-hardware.org/?probe=be2ceae6ca) | Nov 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4457c6182e](https://linux-hardware.org/?probe=4457c6182e) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [66b04ff6f8](https://linux-hardware.org/?probe=66b04ff6f8) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [b98f2dc115](https://linux-hardware.org/?probe=b98f2dc115) | Oct 08, 2022 |
| Dell          | 014GRG A01                  | Desktop     | [05a023826f](https://linux-hardware.org/?probe=05a023826f) | Oct 06, 2022 |
| AYANEO        | AIR                         | Tablet      | [a5e36506b9](https://linux-hardware.org/?probe=a5e36506b9) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [bc43cff31b](https://linux-hardware.org/?probe=bc43cff31b) | Sep 23, 2022 |
| Dell          | 0WCJNT A06                  | Server      | [4cc4b2f914](https://linux-hardware.org/?probe=4cc4b2f914) | Sep 22, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [c996a3c4dd](https://linux-hardware.org/?probe=c996a3c4dd) | Sep 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [4d7948b375](https://linux-hardware.org/?probe=4d7948b375) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [1e4d0a6189](https://linux-hardware.org/?probe=1e4d0a6189) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0796b79ff6](https://linux-hardware.org/?probe=0796b79ff6) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | Latitude E4300              | Notebook    | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| Dell          | 0CRH6C A01                  | Desktop     | [d4a37f016b](https://linux-hardware.org/?probe=d4a37f016b) | Sep 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [e7f6559a38](https://linux-hardware.org/?probe=e7f6559a38) | Aug 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | 18E7                        | Desktop     | [f1c1f9c891](https://linux-hardware.org/?probe=f1c1f9c891) | Aug 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [b9f6292104](https://linux-hardware.org/?probe=b9f6292104) | Aug 07, 2022 |
| Lenovo        | G50-80 80L0                 | Notebook    | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | Notebook    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [06d2014c22](https://linux-hardware.org/?probe=06d2014c22) | Aug 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d1ca5eafe5](https://linux-hardware.org/?probe=d1ca5eafe5) | Aug 03, 2022 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [6362df4235](https://linux-hardware.org/?probe=6362df4235) | Jul 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1512e3bf4d](https://linux-hardware.org/?probe=1512e3bf4d) | Jul 22, 2022 |
| Dell          | G7 7500                     | Notebook    | [f5e6475121](https://linux-hardware.org/?probe=f5e6475121) | Jul 22, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [e52633f694](https://linux-hardware.org/?probe=e52633f694) | Jul 17, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [8f556b89fc](https://linux-hardware.org/?probe=8f556b89fc) | Jul 16, 2022 |
| ASUSTek       | G53JW                       | Notebook    | [2090800f5c](https://linux-hardware.org/?probe=2090800f5c) | Jul 06, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [c186124284](https://linux-hardware.org/?probe=c186124284) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [fce4d4547c](https://linux-hardware.org/?probe=fce4d4547c) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| TYAN Compu... | S7010                       | Server      | [af4d333445](https://linux-hardware.org/?probe=af4d333445) | Jun 28, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| Dell          | Latitude 7300               | Notebook    | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [5708a69dc1](https://linux-hardware.org/?probe=5708a69dc1) | Jun 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [150ea72986](https://linux-hardware.org/?probe=150ea72986) | Jun 23, 2022 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [755c2fc534](https://linux-hardware.org/?probe=755c2fc534) | Jun 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Purism        | Librem 14                   | Notebook    | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1c8e5b49d3](https://linux-hardware.org/?probe=1c8e5b49d3) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [00d3a71a00](https://linux-hardware.org/?probe=00d3a71a00) | Jun 06, 2022 |
| Foxconn       | H81MXV FAB A                | Desktop     | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e308c653b2](https://linux-hardware.org/?probe=e308c653b2) | May 30, 2022 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| HP            | 8298                        | Desktop     | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Dell          | 0R4CNN A01                  | Server      | [b12db2e5d7](https://linux-hardware.org/?probe=b12db2e5d7) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | Notebook    | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | Notebook    | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [f51fab0e09](https://linux-hardware.org/?probe=f51fab0e09) | Apr 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Dell          | Latitude 7400               | Notebook    | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Acer          | Aspire V7-482PG             | Notebook    | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| ASUSTek       | D540MA-C                    | Desktop     | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | Notebook    | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f242f094a9](https://linux-hardware.org/?probe=f242f094a9) | Apr 09, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [76ddd6a6bc](https://linux-hardware.org/?probe=76ddd6a6bc) | Apr 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9e98e995e7](https://linux-hardware.org/?probe=9e98e995e7) | Mar 18, 2022 |
| MSI           | H61M-E22                    | Desktop     | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | Notebook    | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [63caa45089](https://linux-hardware.org/?probe=63caa45089) | Mar 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | Notebook    | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte      | H55M-D2H                    | Desktop     | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle       | FH87                        | Desktop     | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518NR8    | Desktop     | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP            | 2B34                        | Desktop     | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [52699a1847](https://linux-hardware.org/?probe=52699a1847) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [46a851b841](https://linux-hardware.org/?probe=46a851b841) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M91p 4524B96    | Desktop     | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Dell          | Latitude 3350               | Notebook    | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [195c9a8567](https://linux-hardware.org/?probe=195c9a8567) | Dec 29, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| AZW           | U59                         | Desktop     | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [d4f31ef495](https://linux-hardware.org/?probe=d4f31ef495) | Dec 01, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | Notebook    | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [8d8d873287](https://linux-hardware.org/?probe=8d8d873287) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Israel/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 144       | 12.1%   |
| Ubuntu 22.04                 | 66        | 5.55%   |
| Ubuntu 18.04                 | 65        | 5.46%   |
| Ubuntu 24.04                 | 38        | 3.19%   |
| Arch Rolling                 | 38        | 3.19%   |
| Fedora 40                    | 20        | 1.68%   |
| Pop!_OS 22.04                | 17        | 1.43%   |
| OpenMandriva 4.3             | 17        | 1.43%   |
| OpenMandriva 4.2             | 16        | 1.34%   |
| Manjaro                      | 16        | 1.34%   |
| Fedora 41                    | 16        | 1.34%   |
| Debian 13                    | 16        | 1.34%   |
| Debian 12                    | 15        | 1.26%   |
| ROSA R11                     | 14        | 1.18%   |
| Fedora 42                    | 14        | 1.18%   |
| OpenMandriva 23.08           | 13        | 1.09%   |
| Fedora 38                    | 13        | 1.09%   |
| Fedora 37                    | 13        | 1.09%   |
| ArcoLinux Rolling            | 12        | 1.01%   |
| Ubuntu 23.10                 | 11        | 0.92%   |
| Ubuntu 21.04                 | 11        | 0.92%   |
| Ubuntu 19.04                 | 11        | 0.92%   |
| Fedora 36                    | 11        | 0.92%   |
| Ubuntu 23.04                 | 10        | 0.84%   |
| Linux Mint 20.3              | 10        | 0.84%   |
| Linux Mint 20.1              | 10        | 0.84%   |
| Fedora 35                    | 10        | 0.84%   |
| Debian 11                    | 10        | 0.84%   |
| Zorin 17                     | 9         | 0.76%   |
| OpenMandriva 24.12           | 9         | 0.76%   |
| Fedora 43                    | 9         | 0.76%   |
| Zorin 16                     | 8         | 0.67%   |
| Ubuntu 20.10                 | 8         | 0.67%   |
| Ubuntu 19.10                 | 8         | 0.67%   |
| ROSA R11.1                   | 8         | 0.67%   |
| Pop!_OS 21.04                | 8         | 0.67%   |
| Linux Mint 21.1              | 8         | 0.67%   |
| Arch                         | 8         | 0.67%   |
| ROSA R10                     | 7         | 0.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 377       | 34.37%  |
| Fedora        | 115       | 10.48%  |
| OpenMandriva  | 94        | 8.57%   |
| Linux Mint    | 73        | 6.65%   |
| Debian        | 49        | 4.47%   |
| Arch          | 46        | 4.19%   |
| ROSA          | 42        | 3.83%   |
| Pop!_OS       | 40        | 3.65%   |
| Manjaro       | 36        | 3.28%   |
| Zorin         | 28        | 2.55%   |
| Kubuntu       | 21        | 1.91%   |
| SteamOS       | 17        | 1.55%   |
| Xubuntu       | 16        | 1.46%   |
| ArcoLinux     | 13        | 1.19%   |
| Elementary    | 10        | 0.91%   |
| Endless       | 9         | 0.82%   |
| openSUSE      | 8         | 0.73%   |
| Nobara        | 8         | 0.73%   |
| Ubuntu MATE   | 7         | 0.64%   |
| Kali          | 6         | 0.55%   |
| CentOS        | 6         | 0.55%   |
| Bazzite       | 6         | 0.55%   |
| KDE neon      | 5         | 0.46%   |
| Ubuntu Unity  | 4         | 0.36%   |
| Rocky Linux   | 4         | 0.36%   |
| NixOS         | 4         | 0.36%   |
| Clear Linux   | 4         | 0.36%   |
| Ubuntu Budgie | 3         | 0.27%   |
| MX            | 3         | 0.27%   |
| Gentoo        | 3         | 0.27%   |
| Garuda Linux  | 3         | 0.27%   |
| BlackPanther  | 3         | 0.27%   |
| Ubuntu Studio | 2         | 0.18%   |
| Pikaos        | 2         | 0.18%   |
| Neptune OS    | 2         | 0.18%   |
| Lubuntu       | 2         | 0.18%   |
| LMDE          | 2         | 0.18%   |
| EndeavourOS   | 2         | 0.18%   |
| Devuan        | 2         | 0.18%   |
| CachyOS       | 2         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 26        | 2%      |
| 6.14.2-desktop-3omv2590         | 17        | 1.31%   |
| 5.16.7-desktop-1omv4003         | 17        | 1.31%   |
| 5.10.14-desktop-1omv4002        | 15        | 1.15%   |
| 5.4.0-48-generic                | 14        | 1.08%   |
| 6.4.11-desktop-1omv2390         | 10        | 0.77%   |
| 6.12.57+deb13-amd64             | 10        | 0.77%   |
| 6.12.1-desktop-1omv2490         | 10        | 0.77%   |
| 5.4.0-52-generic                | 10        | 0.77%   |
| 6.6.2-desktop-1omv2390          | 8         | 0.61%   |
| 6.2.0-20-generic                | 7         | 0.54%   |
| 5.15.0-91-generic               | 7         | 0.54%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 7         | 0.54%   |
| 6.8.7-300.fc40.x86_64           | 6         | 0.46%   |
| 6.8.0-45-generic                | 6         | 0.46%   |
| 6.5.0-14-generic                | 6         | 0.46%   |
| 6.2.6-desktop-1omv2390          | 6         | 0.46%   |
| 5.4.0-72-generic                | 6         | 0.46%   |
| 5.4.0-65-generic                | 6         | 0.46%   |
| 5.4.0-26-generic                | 6         | 0.46%   |
| 5.15.0-56-generic               | 6         | 0.46%   |
| 5.11.0-37-generic               | 6         | 0.46%   |
| 6.9.3-76060903-generic          | 5         | 0.38%   |
| 6.8.0-51-generic                | 5         | 0.38%   |
| 6.2.0-39-generic                | 5         | 0.38%   |
| 6.11.0-17-generic               | 5         | 0.38%   |
| 5.4.0-58-generic                | 5         | 0.38%   |
| 5.3.0-46-generic                | 5         | 0.38%   |
| 5.15.0-47-generic               | 5         | 0.38%   |
| 5.13.0-30-generic               | 5         | 0.38%   |
| 5.11.0-40-generic               | 5         | 0.38%   |
| 5.11.0-27-generic               | 5         | 0.38%   |
| 5.0.0-23-generic                | 5         | 0.38%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5         | 0.38%   |
| 6.8.11-300.fc40.x86_64          | 4         | 0.31%   |
| 6.8.0-52-generic                | 4         | 0.31%   |
| 6.8.0-41-generic                | 4         | 0.31%   |
| 6.8.0-31-generic                | 4         | 0.31%   |
| 6.2.0-26-generic                | 4         | 0.31%   |
| 6.14.0-29-generic               | 4         | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 137       | 11.04%  |
| 5.15.0  | 73        | 5.88%   |
| 4.15.0  | 52        | 4.19%   |
| 6.8.0   | 48        | 3.87%   |
| 5.8.0   | 43        | 3.46%   |
| 5.11.0  | 38        | 3.06%   |
| 6.5.0   | 35        | 2.82%   |
| 5.13.0  | 35        | 2.82%   |
| 5.3.0   | 31        | 2.5%    |
| 6.2.0   | 30        | 2.42%   |
| 5.0.0   | 25        | 2.01%   |
| 6.14.0  | 24        | 1.93%   |
| 5.19.0  | 23        | 1.85%   |
| 6.1.0   | 22        | 1.77%   |
| 6.11.0  | 21        | 1.69%   |
| 6.14.2  | 17        | 1.37%   |
| 5.16.7  | 17        | 1.37%   |
| 5.10.14 | 15        | 1.21%   |
| 4.18.0  | 13        | 1.05%   |
| 6.12.1  | 11        | 0.89%   |
| 5.10.0  | 11        | 0.89%   |
| 6.6.2   | 10        | 0.81%   |
| 6.4.11  | 10        | 0.81%   |
| 6.12.57 | 10        | 0.81%   |
| 6.2.6   | 8         | 0.64%   |
| 6.8.7   | 7         | 0.56%   |
| 6.3.5   | 6         | 0.48%   |
| 6.12.10 | 6         | 0.48%   |
| 4.9.60  | 6         | 0.48%   |
| 6.9.3   | 5         | 0.4%    |
| 6.2.9   | 5         | 0.4%    |
| 6.12.9  | 5         | 0.4%    |
| 6.11.4  | 5         | 0.4%    |
| 6.11.11 | 5         | 0.4%    |
| 6.9.9   | 4         | 0.32%   |
| 6.8.11  | 4         | 0.32%   |
| 6.17.7  | 4         | 0.32%   |
| 6.14.4  | 4         | 0.32%   |
| 6.1.52  | 4         | 0.32%   |
| 6.1.12  | 4         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 142       | 11.72%  |
| 5.15    | 94        | 7.76%   |
| 6.8     | 65        | 5.36%   |
| 6.1     | 54        | 4.46%   |
| 6.14    | 53        | 4.37%   |
| 6.12    | 52        | 4.29%   |
| 4.15    | 52        | 4.29%   |
| 5.8     | 50        | 4.13%   |
| 6.2     | 49        | 4.04%   |
| 5.11    | 45        | 3.71%   |
| 6.5     | 42        | 3.47%   |
| 5.10    | 41        | 3.38%   |
| 5.13    | 39        | 3.22%   |
| 6.11    | 38        | 3.14%   |
| 5.3     | 33        | 2.72%   |
| 5.19    | 30        | 2.48%   |
| 5.16    | 30        | 2.48%   |
| 6.6     | 28        | 2.31%   |
| 5.0     | 26        | 2.15%   |
| 6.4     | 21        | 1.73%   |
| 6.9     | 17        | 1.4%    |
| 6.17    | 16        | 1.32%   |
| 6.10    | 16        | 1.32%   |
| 4.18    | 16        | 1.32%   |
| 6.0     | 15        | 1.24%   |
| 4.9     | 15        | 1.24%   |
| 6.15    | 13        | 1.07%   |
| 6.13    | 13        | 1.07%   |
| 5.14    | 12        | 0.99%   |
| 6.7     | 11        | 0.91%   |
| 5.9     | 11        | 0.91%   |
| 6.3     | 9         | 0.74%   |
| 5.18    | 9         | 0.74%   |
| 5.17    | 8         | 0.66%   |
| 4.19    | 8         | 0.66%   |
| 6.16    | 7         | 0.58%   |
| 5.12    | 6         | 0.5%    |
| 4.1     | 6         | 0.5%    |
| 5.7     | 5         | 0.41%   |
| 5.6     | 4         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1042      | 98.02%  |
| i686    | 14        | 1.32%   |
| aarch64 | 7         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 498       | 44.62%  |
| KDE5            | 181       | 16.22%  |
| Unknown         | 101       | 9.05%   |
| KDE6            | 87        | 7.8%    |
| X-Cinnamon      | 67        | 6%      |
| XFCE            | 56        | 5.02%   |
| KDE4            | 30        | 2.69%   |
| Cinnamon        | 19        | 1.7%    |
| MATE            | 15        | 1.34%   |
| KDE             | 15        | 1.34%   |
| Pantheon        | 10        | 0.9%    |
| i3              | 7         | 0.63%   |
| Hyprland        | 6         | 0.54%   |
| Unity           | 5         | 0.45%   |
| LXQt            | 5         | 0.45%   |
| Budgie          | 3         | 0.27%   |
| LXDE            | 2         | 0.18%   |
| GNOME Classic   | 2         | 0.18%   |
| Trinity         | 1         | 0.09%   |
| i3-with-shmlog  | 1         | 0.09%   |
| GNOME Flashback | 1         | 0.09%   |
| Endless:GNOME   | 1         | 0.09%   |
| dwm             | 1         | 0.09%   |
| Deepin          | 1         | 0.09%   |
| chadwm          | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 708       | 63.78%  |
| Wayland | 313       | 28.2%   |
| Unknown | 58        | 5.23%   |
| Tty     | 31        | 2.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 458       | 41.45%  |
| SDDM    | 194       | 17.56%  |
| GDM3    | 177       | 16.02%  |
| GDM     | 134       | 12.13%  |
| LightDM | 92        | 8.33%   |
| KDM     | 28        | 2.53%   |
| TDM     | 17        | 1.54%   |
| XDM     | 2         | 0.18%   |
| LY-DM   | 1         | 0.09%   |
| LXDM    | 1         | 0.09%   |
| GREETD  | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 435       | 39.55%  |
| en_IL       | 380       | 34.55%  |
| Unknown     | 100       | 9.09%   |
| ru_RU       | 66        | 6%      |
| he_IL       | 39        | 3.55%   |
| C           | 34        | 3.09%   |
| en_GB       | 7         | 0.64%   |
| fr_FR       | 6         | 0.55%   |
| en_AG       | 5         | 0.45%   |
| uk_UA       | 3         | 0.27%   |
| ru_UA       | 3         | 0.27%   |
| es_ES       | 3         | 0.27%   |
| POSIX       | 2         | 0.18%   |
| de_DE       | 2         | 0.18%   |
| pt_BR       | 1         | 0.09%   |
| it_IT       | 1         | 0.09%   |
| is          | 1         | 0.09%   |
| en_US.UTF8  | 1         | 0.09%   |
| en_US.utf-8 | 1         | 0.09%   |
| en_NZ       | 1         | 0.09%   |
| en_IN       | 1         | 0.09%   |
| en_IE       | 1         | 0.09%   |
| en_DK       | 1         | 0.09%   |
| en_CA       | 1         | 0.09%   |
| en_AU       | 1         | 0.09%   |
| enUS        | 1         | 0.09%   |
| C.UTF8      | 1         | 0.09%   |
| ar_EG       | 1         | 0.09%   |
| aa_DJ       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 575       | 52.51%  |
| BIOS | 520       | 47.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 718       | 65.39%  |
| Btrfs   | 160       | 14.57%  |
| Overlay | 88        | 8.01%   |
| Tmpfs   | 74        | 6.74%   |
| Unknown | 25        | 2.28%   |
| Xfs     | 23        | 2.09%   |
| Zfs     | 6         | 0.55%   |
| Ext3    | 2         | 0.18%   |
| F2fs    | 1         | 0.09%   |
| Ext2    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 531       | 48.67%  |
| Unknown | 457       | 41.89%  |
| MBR     | 103       | 9.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 918       | 84.53%  |
| Yes       | 168       | 15.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 774       | 71.4%   |
| Yes       | 310       | 28.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 241       | 22.69%  |
| Lenovo                               | 207       | 19.49%  |
| Dell                                 | 145       | 13.65%  |
| Gigabyte Technology                  | 132       | 12.43%  |
| Hewlett-Packard                      | 110       | 10.36%  |
| MSI                                  | 33        | 3.11%   |
| Intel                                | 25        | 2.35%   |
| Apple                                | 17        | 1.6%    |
| Acer                                 | 16        | 1.51%   |
| ASRock                               | 13        | 1.22%   |
| Unknown                              | 13        | 1.22%   |
| Valve                                | 12        | 1.13%   |
| Samsung Electronics                  | 9         | 0.85%   |
| Toshiba                              | 8         | 0.75%   |
| Razer                                | 4         | 0.38%   |
| Raspberry Pi Foundation              | 4         | 0.38%   |
| Fujitsu                              | 4         | 0.38%   |
| Alienware                            | 4         | 0.38%   |
| Timi                                 | 3         | 0.28%   |
| Supermicro                           | 3         | 0.28%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.28%   |
| Pegatron                             | 3         | 0.28%   |
| Nvidia                               | 3         | 0.28%   |
| LG Electronics                       | 3         | 0.28%   |
| GMKtec                               | 3         | 0.28%   |
| AMI                                  | 3         | 0.28%   |
| System76                             | 2         | 0.19%   |
| Microsoft                            | 2         | 0.19%   |
| Huanan                               | 2         | 0.19%   |
| GPD                                  | 2         | 0.19%   |
| Fujitsu Siemens                      | 2         | 0.19%   |
| Foxconn                              | 2         | 0.19%   |
| AZW                                  | 2         | 0.19%   |
| AYANEO                               | 2         | 0.19%   |
| XIAOMI                               | 1         | 0.09%   |
| TYAN Computer                        | 1         | 0.09%   |
| TUXEDO                               | 1         | 0.09%   |
| Sony                                 | 1         | 0.09%   |
| Shuttle                              | 1         | 0.09%   |
| Purism                               | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 19        | 1.79%   |
| ASUS All Series                          | 11        | 1.04%   |
| Valve Jupiter                            | 10        | 0.94%   |
| Gigabyte H61M-S2PV                       | 5         | 0.47%   |
| Gigabyte G31M-ES2L                       | 4         | 0.38%   |
| RPi Raspberry Pi 4 Model B Rev 1.4       | 3         | 0.28%   |
| Nvidia Tegra                             | 3         | 0.28%   |
| MSI MS-7592                              | 3         | 0.28%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 3         | 0.28%   |
| Lenovo G560 0679                         | 3         | 0.28%   |
| HP Pavilion Notebook                     | 3         | 0.28%   |
| HP Compaq Presario CQ61                  | 3         | 0.28%   |
| Gigabyte H61M-S1                         | 3         | 0.28%   |
| Dell Vostro 5490                         | 3         | 0.28%   |
| Dell Vostro 15-3568                      | 3         | 0.28%   |
| Dell Latitude 7400                       | 3         | 0.28%   |
| Dell Latitude 5420                       | 3         | 0.28%   |
| Dell Inspiron 3593                       | 3         | 0.28%   |
| ASUS VivoBook_ASUSLaptop K5404VA_K5404VA | 3         | 0.28%   |
| ASUS UX331UA                             | 3         | 0.28%   |
| ASUS ROG STRIX X570-F GAMING             | 3         | 0.28%   |
| ASUS PRIME Z490-P                        | 3         | 0.28%   |
| ASUS PRIME H610M-K D4                    | 3         | 0.28%   |
| ASUS PRIME H310M-E R2.0                  | 3         | 0.28%   |
| ASUS P8H61-M LX R2.0                     | 3         | 0.28%   |
| ASUS H110M-K                             | 3         | 0.28%   |
| ASUS H110M-A/M.2                         | 3         | 0.28%   |
| Valve Galileo                            | 2         | 0.19%   |
| MSI MS-7E07                              | 2         | 0.19%   |
| MSI MS-7982                              | 2         | 0.19%   |
| Lenovo Yoga 500-15ISK 80R6               | 2         | 0.19%   |
| Lenovo V14-IIL 82C4                      | 2         | 0.19%   |
| Lenovo ThinkPad P14s Gen 4 21HF000KIV    | 2         | 0.19%   |
| Lenovo ThinkPad P1 Gen 7 21KV0029IV      | 2         | 0.19%   |
| Lenovo Legion Y530-15ICH 81FV            | 2         | 0.19%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 2         | 0.19%   |
| Lenovo IdeaPad Slim 3 15IAH8 83ER        | 2         | 0.19%   |
| Lenovo IdeaPad L340-15IWL 81LG           | 2         | 0.19%   |
| Lenovo IdeaPad Flex-14API 81SS           | 2         | 0.19%   |
| Lenovo IdeaPad 530S-14IKB 81EU           | 2         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 85        | 8%      |
| ASUS PRIME         | 52        | 4.9%    |
| Dell Latitude      | 44        | 4.14%   |
| ASUS Vivobook      | 41        | 3.86%   |
| Lenovo IdeaPad     | 39        | 3.67%   |
| ASUS ROG           | 34        | 3.2%    |
| Dell Inspiron      | 26        | 2.45%   |
| Dell Vostro        | 25        | 2.35%   |
| HP Pavilion        | 19        | 1.79%   |
| Unknown            | 19        | 1.79%   |
| Dell OptiPlex      | 16        | 1.51%   |
| Dell XPS           | 14        | 1.32%   |
| Lenovo Yoga        | 13        | 1.22%   |
| Acer Aspire        | 13        | 1.22%   |
| Lenovo ThinkCentre | 12        | 1.13%   |
| ASUS TUF           | 12        | 1.13%   |
| ASUS ASUS          | 11        | 1.04%   |
| ASUS All           | 11        | 1.04%   |
| Valve Jupiter      | 10        | 0.94%   |
| Lenovo Legion      | 10        | 0.94%   |
| HP EliteBook       | 10        | 0.94%   |
| HP ProBook         | 9         | 0.85%   |
| HP Laptop          | 9         | 0.85%   |
| HP Compaq          | 9         | 0.85%   |
| Dell Precision     | 9         | 0.85%   |
| HP ZBook           | 8         | 0.75%   |
| Gigabyte Z690      | 7         | 0.66%   |
| ASUS ZenBook       | 7         | 0.66%   |
| HP ProDesk         | 6         | 0.56%   |
| Toshiba Satellite  | 5         | 0.47%   |
| Lenovo IdeaPadFlex | 5         | 0.47%   |
| HP EliteDesk       | 5         | 0.47%   |
| Gigabyte H61M-S2PV | 5         | 0.47%   |
| Dell PowerEdge     | 5         | 0.47%   |
| Razer Blade        | 4         | 0.38%   |
| RPi Raspberry      | 4         | 0.38%   |
| Gigabyte Z790      | 4         | 0.38%   |
| Gigabyte X570      | 4         | 0.38%   |
| Gigabyte G31M-ES2L | 4         | 0.38%   |
| Fujitsu LIFEBOOK   | 4         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 104       | 9.79%   |
| 2018    | 104       | 9.79%   |
| 2019    | 103       | 9.7%    |
| 2021    | 86        | 8.1%    |
| 2017    | 65        | 6.12%   |
| 2012    | 65        | 6.12%   |
| 2022    | 64        | 6.03%   |
| 2016    | 60        | 5.65%   |
| 2023    | 59        | 5.56%   |
| 2015    | 56        | 5.27%   |
| 2011    | 50        | 4.71%   |
| 2013    | 49        | 4.61%   |
| 2014    | 46        | 4.33%   |
| 2010    | 40        | 3.77%   |
| 2024    | 32        | 3.01%   |
| 2009    | 28        | 2.64%   |
| 2008    | 20        | 1.88%   |
| 2007    | 14        | 1.32%   |
| 2025    | 10        | 0.94%   |
| Unknown | 4         | 0.38%   |
| 2006    | 3         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 547       | 51.51%  |
| Desktop        | 413       | 38.89%  |
| Convertible    | 31        | 2.92%   |
| Mini pc        | 30        | 2.82%   |
| Tablet         | 12        | 1.13%   |
| Server         | 11        | 1.04%   |
| All in one     | 9         | 0.85%   |
| System on chip | 8         | 0.75%   |
| Other          | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 982       | 91.78%  |
| Enabled  | 88        | 8.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1058      | 99.62%  |
| Yes  | 4         | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 246       | 22.69%  |
| 4.01-8.0        | 216       | 19.93%  |
| 32.01-64.0      | 198       | 18.27%  |
| 8.01-16.0       | 179       | 16.51%  |
| 3.01-4.0        | 111       | 10.24%  |
| 64.01-256.0     | 65        | 6%      |
| 1.01-2.0        | 31        | 2.86%   |
| 24.01-32.0      | 23        | 2.12%   |
| 2.01-3.0        | 7         | 0.65%   |
| More than 256.0 | 4         | 0.37%   |
| 0.51-1.0        | 3         | 0.28%   |
| Unknown         | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 290       | 24.43%  |
| 2.01-3.0    | 254       | 21.4%   |
| 4.01-8.0    | 231       | 19.46%  |
| 3.01-4.0    | 188       | 15.84%  |
| 8.01-16.0   | 125       | 10.53%  |
| 0.51-1.0    | 53        | 4.47%   |
| 16.01-24.0  | 16        | 1.35%   |
| 0.01-0.5    | 11        | 0.93%   |
| 32.01-64.0  | 9         | 0.76%   |
| 24.01-32.0  | 5         | 0.42%   |
| 64.01-256.0 | 3         | 0.25%   |
| Unknown     | 2         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 681       | 62.14%  |
| 2      | 242       | 22.08%  |
| 3      | 101       | 9.22%   |
| 4      | 31        | 2.83%   |
| 5      | 16        | 1.46%   |
| 0      | 9         | 0.82%   |
| 6      | 6         | 0.55%   |
| 10     | 3         | 0.27%   |
| 8      | 3         | 0.27%   |
| 7      | 3         | 0.27%   |
| 12     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 802       | 74.74%  |
| Yes       | 271       | 25.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 900       | 84.43%  |
| No        | 166       | 15.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 774       | 72.27%  |
| No        | 297       | 27.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 686       | 63.81%  |
| No        | 389       | 36.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Israel  | 1062      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Tel Aviv              | 433       | 37.04%  |
| Ramat Gan             | 78        | 6.67%   |
| Jerusalem             | 60        | 5.13%   |
| Haifa                 | 60        | 5.13%   |
| Petah Tikva           | 43        | 3.68%   |
| Rishon LeTsiyyon      | 35        | 2.99%   |
| Herzliya              | 28        | 2.4%    |
| Petaẖ Tiqwa         | 27        | 2.31%   |
| Holon                 | 24        | 2.05%   |
| Netanya               | 22        | 1.88%   |
| Rehovot               | 19        | 1.63%   |
| Rishon LeZiyyon       | 18        | 1.54%   |
| Qiryat Ata            | 18        | 1.54%   |
| Givatayim             | 16        | 1.37%   |
| Rosh HaAyin           | 14        | 1.2%    |
| Ashdod                | 13        | 1.11%   |
| Raanana               | 12        | 1.03%   |
| Kfar Saba             | 12        | 1.03%   |
| Beersheba             | 11        | 0.94%   |
| Ashquelon             | 11        | 0.94%   |
| Ramat HaSharon        | 10        | 0.86%   |
| Nahariya              | 9         | 0.77%   |
| Kiryat Ono            | 9         | 0.77%   |
| Hod HaSharon          | 9         | 0.77%   |
| Bat Yam               | 8         | 0.68%   |
| Lod                   | 7         | 0.6%    |
| Bet Shemesh           | 7         | 0.6%    |
| Ramla                 | 5         | 0.43%   |
| Ness Ziona            | 5         | 0.43%   |
| Karmi’el            | 5         | 0.43%   |
| Hadera                | 5         | 0.43%   |
| Shefa-'Amr            | 4         | 0.34%   |
| Pardes Hanna Karkur   | 4         | 0.34%   |
| Modiin Makkabbim Reut | 4         | 0.34%   |
| Harish                | 4         | 0.34%   |
| Givat Shmuel          | 4         | 0.34%   |
| Ge'a                  | 4         | 0.34%   |
| Ganei Tikva           | 4         | 0.34%   |
| Be'er Ya'aqov         | 4         | 0.34%   |
| Afula                 | 4         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 246       | 440    | 16.04%  |
| WDC                         | 229       | 392    | 14.93%  |
| Seagate                     | 152       | 224    | 9.91%   |
| Sandisk                     | 142       | 176    | 9.26%   |
| Kingston                    | 85        | 103    | 5.54%   |
| Toshiba                     | 69        | 80     | 4.5%    |
| Intel                       | 59        | 89     | 3.85%   |
| Hitachi                     | 58        | 93     | 3.78%   |
| SK hynix                    | 49        | 71     | 3.19%   |
| Micron Technology           | 47        | 60     | 3.06%   |
| Crucial                     | 38        | 65     | 2.48%   |
| Unknown                     | 34        | 44     | 2.22%   |
| Transcend                   | 34        | 47     | 2.22%   |
| HGST                        | 31        | 36     | 2.02%   |
| KIOXIA                      | 26        | 36     | 1.69%   |
| Corsair                     | 14        | 25     | 0.91%   |
| A-DATA Technology           | 14        | 17     | 0.91%   |
| China                       | 11        | 16     | 0.72%   |
| Apple                       | 11        | 16     | 0.72%   |
| Phison Electronics          | 10        | 13     | 0.65%   |
| Micron/Crucial Technology   | 10        | 10     | 0.65%   |
| Unknown                     | 10        | 11     | 0.65%   |
| StoreJet                    | 9         | 10     | 0.59%   |
| Silicon Motion              | 9         | 9      | 0.59%   |
| Phison                      | 7         | 8      | 0.46%   |
| MAXIO Technology (Hangzhou) | 7         | 8      | 0.46%   |
| Kingston Technology Company | 7         | 7      | 0.46%   |
| ADATA Technology            | 7         | 7      | 0.46%   |
| XPG                         | 6         | 12     | 0.39%   |
| SPCC                        | 6         | 6      | 0.39%   |
| PNY                         | 5         | 6      | 0.33%   |
| LITEON                      | 5         | 5      | 0.33%   |
| KIOXIA-EXCERIA              | 5         | 6      | 0.33%   |
| OCZ                         | 4         | 4      | 0.26%   |
| Netac                       | 4         | 4      | 0.26%   |
| JMicron Technology          | 4         | 4      | 0.26%   |
| Fujitsu                     | 4         | 5      | 0.26%   |
| Realtek Semiconductor       | 3         | 3      | 0.2%    |
| LITEONIT                    | 3         | 3      | 0.2%    |
| Gigabyte Technology         | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 23        | 1.35%   |
| SanDisk SSD PLUS 240GB                             | 22        | 1.29%   |
| Kingston SA400S37240G 240GB SSD                    | 18        | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 15        | 0.88%   |
| Seagate ST500DM002-1BD142 500GB                    | 13        | 0.76%   |
| Samsung SSD 990 PRO 1TB                            | 11        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                       | 11        | 0.65%   |
| Hitachi HDS721050CLA362 500GB                      | 11        | 0.65%   |
| Samsung SSD 860 EVO 500GB                          | 10        | 0.59%   |
| Unknown                                            | 10        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 9         | 0.53%   |
| Unknown MMC Card  64GB                             | 9         | 0.53%   |
| Seagate ST500LT012-1DG142 500GB                    | 9         | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 9         | 0.53%   |
| Kingston SV300S37A120G 120GB SSD                   | 9         | 0.53%   |
| Toshiba DT01ACA100 1TB                             | 8         | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                     | 8         | 0.47%   |
| Samsung SSD 980 1TB                                | 8         | 0.47%   |
| Samsung SSD 850 EVO 250GB                          | 8         | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                          | 8         | 0.47%   |
| Samsung SSD 990 PRO 2TB                            | 7         | 0.41%   |
| Samsung SSD 850 EVO 500GB                          | 7         | 0.41%   |
| Intel NVMe SSD Drive 512GB                         | 7         | 0.41%   |
| HGST HTS721010A9E630 1TB                           | 7         | 0.41%   |
| HGST HTS545050A7E680 500GB                         | 7         | 0.41%   |
| Crucial CT500MX500SSD1 500GB                       | 7         | 0.41%   |
| WDC WD20PURX-64P6ZY0 2TB                           | 6         | 0.35%   |
| SK hynix NVMe SSD Drive 256GB                      | 6         | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 6         | 0.35%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB    | 6         | 0.35%   |
| SanDisk SDSSDA120G 120GB                           | 6         | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                         | 6         | 0.35%   |
| Samsung SSD 860 QVO 1TB                            | 6         | 0.35%   |
| Samsung SSD 860 EVO 250GB                          | 6         | 0.35%   |
| Samsung NVMe SSD Drive 500GB                       | 6         | 0.35%   |
| Kingston SUV400S37240G 240GB SSD                   | 6         | 0.35%   |
| Kingston SUV400S37120G 120GB SSD                   | 6         | 0.35%   |
| Kingston SA400S37120G 120GB SSD                    | 6         | 0.35%   |
| Crucial CT250MX500SSD1 250GB                       | 6         | 0.35%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 5         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 187       | 323    | 37.03%  |
| Seagate             | 150       | 221    | 29.7%   |
| Hitachi             | 58        | 93     | 11.49%  |
| Toshiba             | 45        | 53     | 8.91%   |
| HGST                | 31        | 36     | 6.14%   |
| Samsung Electronics | 11        | 17     | 2.18%   |
| Fujitsu             | 4         | 5      | 0.79%   |
| Apple               | 4         | 4      | 0.79%   |
| USB3.0              | 2         | 2      | 0.4%    |
| Unknown             | 2         | 2      | 0.4%    |
| JMicron Technology  | 2         | 2      | 0.4%    |
| Unknown             | 2         | 2      | 0.4%    |
| TPH01204000GB       | 1         | 1      | 0.2%    |
| StoreJet            | 1         | 1      | 0.2%    |
| Mercury             | 1         | 1      | 0.2%    |
| Lenovo              | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| External            | 1         | 1      | 0.2%    |
| ASMT                | 1         | 2      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 93        | 188    | 20.99%  |
| SanDisk             | 69        | 88     | 15.58%  |
| Kingston            | 62        | 74     | 14%     |
| Crucial             | 29        | 54     | 6.55%   |
| Transcend           | 27        | 40     | 6.09%   |
| Intel               | 18        | 21     | 4.06%   |
| WDC                 | 17        | 33     | 3.84%   |
| Micron Technology   | 16        | 20     | 3.61%   |
| A-DATA Technology   | 12        | 14     | 2.71%   |
| SK hynix            | 11        | 22     | 2.48%   |
| Corsair             | 11        | 20     | 2.48%   |
| China               | 10        | 15     | 2.26%   |
| Toshiba             | 9         | 10     | 2.03%   |
| PNY                 | 5         | 6      | 1.13%   |
| LITEON              | 5         | 5      | 1.13%   |
| StoreJet            | 4         | 4      | 0.9%    |
| SPCC                | 4         | 4      | 0.9%    |
| OCZ                 | 4         | 4      | 0.9%    |
| Apple               | 4         | 4      | 0.9%    |
| Netac               | 3         | 3      | 0.68%   |
| LITEONIT            | 3         | 3      | 0.68%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.68%   |
| Apacer              | 3         | 3      | 0.68%   |
| XrayDisk            | 1         | 2      | 0.23%   |
| Wicgtyp             | 1         | 1      | 0.23%   |
| Verbatim            | 1         | 1      | 0.23%   |
| Team                | 1         | 1      | 0.23%   |
| ShiJi               | 1         | 1      | 0.23%   |
| Seagate             | 1         | 1      | 0.23%   |
| Plextor             | 1         | 1      | 0.23%   |
| Pioneer             | 1         | 1      | 0.23%   |
| Patriot             | 1         | 1      | 0.23%   |
| ORICO               | 1         | 2      | 0.23%   |
| OCZ-VERTEX3         | 1         | 1      | 0.23%   |
| NGFF                | 1         | 1      | 0.23%   |
| LuminouTek          | 1         | 1      | 0.23%   |
| LS600               | 1         | 1      | 0.23%   |
| Lenovo              | 1         | 1      | 0.23%   |
| KingSpec            | 1         | 1      | 0.23%   |
| KingDian            | 1         | 2      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 516       | 738    | 37.42%  |
| HDD     | 419       | 768    | 30.38%  |
| SSD     | 390       | 662    | 28.28%  |
| MMC     | 33        | 46     | 2.39%   |
| Unknown | 21        | 25     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 633       | 1377   | 50.72%  |
| NVMe | 514       | 734    | 41.19%  |
| SAS  | 68        | 82     | 5.45%   |
| MMC  | 33        | 46     | 2.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 479       | 802    | 56.55%  |
| 0.51-1.0   | 224       | 379    | 26.45%  |
| 1.01-2.0   | 87        | 150    | 10.27%  |
| 3.01-4.0   | 26        | 50     | 3.07%   |
| 2.01-3.0   | 17        | 26     | 2.01%   |
| 4.01-10.0  | 10        | 14     | 1.18%   |
| 10.01-20.0 | 3         | 8      | 0.35%   |
| 20.01-50.0 | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 249       | 22.25%  |
| 251-500        | 248       | 22.16%  |
| 501-1000       | 194       | 17.34%  |
| 1001-2000      | 101       | 9.03%   |
| 1-20           | 90        | 8.04%   |
| More than 3000 | 63        | 5.63%   |
| 2001-3000      | 49        | 4.38%   |
| 51-100         | 49        | 4.38%   |
| 21-50          | 40        | 3.57%   |
| Unknown        | 36        | 3.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 412       | 35.36%  |
| 21-50          | 199       | 17.08%  |
| 101-250        | 158       | 13.56%  |
| 51-100         | 106       | 9.1%    |
| 251-500        | 92        | 7.9%    |
| 501-1000       | 71        | 6.09%   |
| 1001-2000      | 47        | 4.03%   |
| Unknown        | 36        | 3.09%   |
| More than 3000 | 22        | 1.89%   |
| 2001-3000      | 19        | 1.63%   |
| 0              | 3         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 5         | 7      | 4.55%   |
| WDC WD10EARS-00Y5B1 1TB          | 3         | 5      | 2.73%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2         | 2      | 1.82%   |
| WDC WD10EADS-00L5B1 1TB          | 2         | 2      | 1.82%   |
| Seagate ST9120817AS 120GB        | 2         | 2      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB  | 2         | 2      | 1.82%   |
| Seagate ST320LT012-9WS14C 320GB  | 2         | 2      | 1.82%   |
| SanDisk SSD PLUS 240GB           | 2         | 3      | 1.82%   |
| Hitachi HTS545050B9A300 500GB    | 2         | 2      | 1.82%   |
| Hitachi HTS545025B9A300 250GB    | 2         | 2      | 1.82%   |
| Hitachi HDS721050DLE630 500GB    | 2         | 2      | 1.82%   |
| Hitachi HDS721050CLA362 500GB    | 2         | 3      | 1.82%   |
| Hitachi HDP725050GLA360 500GB    | 2         | 2      | 1.82%   |
| HGST HTS545050A7E380 500GB       | 2         | 2      | 1.82%   |
| WDC WDS240G1G0B-00RC30 240GB SSD | 1         | 1      | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1         | 2      | 0.91%   |
| WDC WD6400BPVT-80HXZT1 640GB     | 1         | 1      | 0.91%   |
| WDC WD6400BPVT-75HXZT1 640GB     | 1         | 1      | 0.91%   |
| WDC WD5001AALS-00LWTA0 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000BPVT-75HXZT1 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-221CA1 500GB      | 1         | 1      | 0.91%   |
| WDC WD5000AADS-00S9B0 500GB      | 1         | 1      | 0.91%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1         | 1      | 0.91%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1         | 1      | 0.91%   |
| WDC WD3003FZEX-00Z4SA0 3TB       | 1         | 2      | 0.91%   |
| WDC WD2500BEVT-24A23T0 250GB     | 1         | 1      | 0.91%   |
| WDC WD2500BEVT-22A23T0 250GB     | 1         | 2      | 0.91%   |
| WDC WD2500AAJS-00VTA0 250GB      | 1         | 1      | 0.91%   |
| WDC WD20EARS-00MVWB0 2TB         | 1         | 2      | 0.91%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1         | 2      | 0.91%   |
| WDC WD1600JS-00SGB0 160GB        | 1         | 1      | 0.91%   |
| WDC WD1600BJKT-75F4T0 160GB      | 1         | 1      | 0.91%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 2      | 0.91%   |
| WDC WD10EZEX-00ZF5A0 1TB         | 1         | 1      | 0.91%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1         | 1      | 0.91%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1         | 1      | 0.91%   |
| WDC WD10EAVS-32D7B1 1TB          | 1         | 1      | 0.91%   |
| WDC WD10EADS-00M2B0 1TB          | 1         | 1      | 0.91%   |
| WDC WD1001FALS-00J7B1 1TB        | 1         | 1      | 0.91%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 41     | 28.57%  |
| Seagate             | 19        | 24     | 18.1%   |
| Hitachi             | 19        | 24     | 18.1%   |
| HGST                | 10        | 12     | 9.52%   |
| Toshiba             | 6         | 6      | 5.71%   |
| SanDisk             | 4         | 5      | 3.81%   |
| Samsung Electronics | 4         | 5      | 3.81%   |
| Intel               | 3         | 3      | 2.86%   |
| Corsair             | 3         | 4      | 2.86%   |
| SK hynix            | 2         | 6      | 1.9%    |
| Transcend           | 1         | 1      | 0.95%   |
| ShiJi               | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |
| Crucial             | 1         | 1      | 0.95%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 38     | 32.94%  |
| Seagate             | 19        | 24     | 22.35%  |
| Hitachi             | 19        | 24     | 22.35%  |
| HGST                | 10        | 12     | 11.76%  |
| Toshiba             | 6         | 6      | 7.06%   |
| Samsung Electronics | 2         | 3      | 2.35%   |
| Fujitsu             | 1         | 1      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 72        | 108    | 78.26%  |
| SSD  | 17        | 24     | 18.48%  |
| NVMe | 3         | 3      | 3.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                             | Computers | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| Transcend TS1TMTE110S 1TB                         | 1         | 1      | 16.67%  |
| Toshiba MK3256GSY 320GB                           | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 980 500GB S64DNF0R648337E | 1         | 1      | 16.67%  |
| Samsung Electronics HD103SJ 1TB                   | 1         | 1      | 16.67%  |
| Hitachi HTS547550A9E384 500GB                     | 1         | 2      | 16.67%  |
| Corsair Neutron XT SSD 240GB                      | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 33.33%  |
| Transcend           | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 2      | 16.67%  |
| Corsair             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 584       | 1179   | 50.83%  |
| Works    | 472       | 918    | 41.08%  |
| Malfunc  | 88        | 135    | 7.66%   |
| Failed   | 5         | 7      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 755       | 53.21%  |
| Samsung Electronics                     | 164       | 11.56%  |
| SanDisk                                 | 99        | 6.98%   |
| AMD                                     | 98        | 6.91%   |
| SK hynix                                | 38        | 2.68%   |
| Micron Technology                       | 32        | 2.26%   |
| Kingston Technology Company             | 32        | 2.26%   |
| KIOXIA                                  | 27        | 1.9%    |
| Phison Electronics                      | 19        | 1.34%   |
| Micron/Crucial Technology               | 18        | 1.27%   |
| Toshiba America Info Systems            | 17        | 1.2%    |
| ADATA Technology                        | 14        | 0.99%   |
| Silicon Motion                          | 13        | 0.92%   |
| ASMedia Technology                      | 13        | 0.92%   |
| Nvidia                                  | 10        | 0.7%    |
| Marvell Technology Group                | 10        | 0.7%    |
| JMicron Technology                      | 10        | 0.7%    |
| MAXIO Technology (Hangzhou)             | 8         | 0.56%   |
| Transcend                               | 7         | 0.49%   |
| Realtek Semiconductor                   | 6         | 0.42%   |
| Solidigm                                | 4         | 0.28%   |
| Solid State Storage Technology          | 3         | 0.21%   |
| LSI Logic / Symbios Logic               | 3         | 0.21%   |
| Apple                                   | 3         | 0.21%   |
| VIA Technologies                        | 2         | 0.14%   |
| Union Memory (Shenzhen)                 | 2         | 0.14%   |
| O2 Micro                                | 2         | 0.14%   |
| Hewlett-Packard                         | 2         | 0.14%   |
| Broadcom / LSI                          | 2         | 0.14%   |
| Biwin Storage Technology                | 2         | 0.14%   |
| Shenzhen Unionmemory Information System | 1         | 0.07%   |
| Shenzhen Longsys Electronics            | 1         | 0.07%   |
| Hosin Global Electronics                | 1         | 0.07%   |
| Adaptec                                 | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 72        | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 65        | 4.1%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 62        | 3.91%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 47        | 2.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 44        | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 41        | 2.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 38        | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 33        | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 28        | 1.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 27        | 1.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 24        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 24        | 1.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22        | 1.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 22        | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21        | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 21        | 1.33%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 20        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 20        | 1.26%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 19        | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 18        | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 17        | 1.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 16        | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 16        | 1.01%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 16        | 1.01%   |
| Intel SSD 660P Series                                                                   | 16        | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 16        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 1.01%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 15        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 14        | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14        | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13        | 0.82%   |
| AMD 600 Series Chipset SATA Controller                                                  | 13        | 0.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 13        | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                   | 12        | 0.76%   |
| Intel RST Volume Management Device Controller                                           | 12        | 0.76%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 12        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 698       | 48.98%  |
| NVMe | 515       | 36.14%  |
| RAID | 119       | 8.35%   |
| IDE  | 87        | 6.11%   |
| SAS  | 6         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 905       | 85.22%  |
| AMD          | 149       | 14.03%  |
| ARM          | 6         | 0.56%   |
| CentaurHauls | 1         | 0.09%   |
| Unknown      | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 22        | 2.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 20        | 1.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 13        | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 13        | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 12        | 1.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 11        | 1.03%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 11        | 1.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 11        | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 10        | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 10        | 0.94%   |
| AMD Custom APU 0405                         | 10        | 0.94%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 9         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 9         | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 9         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 9         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 8         | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 8         | 0.75%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 7         | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 7         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 7         | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 7         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7         | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 7         | 0.65%   |
| Intel 12th Gen Core i7-1255U                | 7         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 6         | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 6         | 0.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 6         | 0.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6         | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 6         | 0.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 6         | 0.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 6         | 0.56%   |
| Intel 12th Gen Core i7-12700H               | 6         | 0.56%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 5         | 0.47%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 5         | 0.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5         | 0.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5         | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5         | 0.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 253       | 23.73%  |
| Intel Core i5           | 229       | 21.48%  |
| Other                   | 180       | 16.89%  |
| Intel Core i3           | 81        | 7.6%    |
| AMD Ryzen 7             | 36        | 3.38%   |
| AMD Ryzen 5             | 36        | 3.38%   |
| Intel Xeon              | 31        | 2.91%   |
| Intel Pentium Dual-Core | 21        | 1.97%   |
| Intel Pentium           | 21        | 1.97%   |
| Intel Core 2 Duo        | 21        | 1.97%   |
| AMD Ryzen 9             | 21        | 1.97%   |
| Intel Celeron           | 18        | 1.69%   |
| Intel Core i9           | 16        | 1.5%    |
| Intel Core              | 16        | 1.5%    |
| Intel Atom              | 13        | 1.22%   |
| Intel Pentium Dual      | 7         | 0.66%   |
| Intel Pentium Gold      | 5         | 0.47%   |
| Intel Genuine           | 5         | 0.47%   |
| AMD Ryzen 7 PRO         | 5         | 0.47%   |
| AMD Ryzen 3             | 5         | 0.47%   |
| AMD FX                  | 4         | 0.38%   |
| AMD A8                  | 4         | 0.38%   |
| AMD A6                  | 4         | 0.38%   |
| Intel Core 2 Quad       | 3         | 0.28%   |
| AMD A10                 | 3         | 0.28%   |
| Intel Xeon Gold         | 2         | 0.19%   |
| Intel Core m3           | 2         | 0.19%   |
| AMD Turion 64 X2 Mobile | 2         | 0.19%   |
| AMD Ryzen Threadripper  | 2         | 0.19%   |
| AMD E1                  | 2         | 0.19%   |
| Intel Pentium Silver    | 1         | 0.09%   |
| Intel Pentium 4         | 1         | 0.09%   |
| Intel Core M            | 1         | 0.09%   |
| Intel Core 2            | 1         | 0.09%   |
| Intel Celeron Dual-Core | 1         | 0.09%   |
| CentaurHauls VIA C7     | 1         | 0.09%   |
| ARM BCM                 | 1         | 0.09%   |
| AMD Ryzen 5 PRO         | 1         | 0.09%   |
| AMD Ryzen 3 PRO         | 1         | 0.09%   |
| AMD Phenom II X4        | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 404       | 37.93%  |
| 2       | 291       | 27.32%  |
| 8       | 109       | 10.23%  |
| 6       | 107       | 10.05%  |
| 12      | 34        | 3.19%   |
| 14      | 32        | 3%      |
| 10      | 31        | 2.91%   |
| 16      | 22        | 2.07%   |
| 1       | 10        | 0.94%   |
| 24      | 9         | 0.85%   |
| 20      | 7         | 0.66%   |
| Unknown | 3         | 0.28%   |
| 3       | 2         | 0.19%   |
| 48      | 1         | 0.09%   |
| 44      | 1         | 0.09%   |
| 36      | 1         | 0.09%   |
| 32      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1044      | 98.31%  |
| 2       | 14        | 1.32%   |
| Unknown | 3         | 0.28%   |
| 4       | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 800       | 74.91%  |
| 1       | 265       | 24.81%  |
| Unknown | 3         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1045      | 98.4%   |
| Unknown        | 14        | 1.32%   |
| 32-bit         | 3         | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 556       | 49.73%  |
| 0x306c3    | 34        | 3.04%   |
| 0x206a7    | 33        | 2.95%   |
| 0x806ea    | 31        | 2.77%   |
| 0x306a9    | 30        | 2.68%   |
| 0x1067a    | 27        | 2.42%   |
| 0x806ec    | 26        | 2.33%   |
| 0x806c1    | 26        | 2.33%   |
| 0x506e3    | 25        | 2.24%   |
| 0x906e9    | 22        | 1.97%   |
| 0x906ea    | 19        | 1.7%    |
| 0x406e3    | 18        | 1.61%   |
| 0x806e9    | 15        | 1.34%   |
| 0x706e5    | 14        | 1.25%   |
| 0x906ed    | 12        | 1.07%   |
| 0x306d4    | 12        | 1.07%   |
| 0x20655    | 11        | 0.98%   |
| 0xa0652    | 9         | 0.81%   |
| 0x90672    | 9         | 0.81%   |
| 0x6fd      | 9         | 0.81%   |
| 0x40651    | 9         | 0.81%   |
| 0x08108109 | 7         | 0.63%   |
| 0xa0671    | 6         | 0.54%   |
| 0x806eb    | 6         | 0.54%   |
| 0x106e5    | 6         | 0.54%   |
| 0xa0655    | 5         | 0.45%   |
| 0xa0653    | 5         | 0.45%   |
| 0x906a4    | 5         | 0.45%   |
| 0x906a3    | 5         | 0.45%   |
| 0x306e4    | 5         | 0.45%   |
| 0x08701021 | 5         | 0.45%   |
| 0x706a1    | 4         | 0.36%   |
| 0x10676    | 4         | 0.36%   |
| 0x0a50000c | 4         | 0.36%   |
| 0x08600104 | 4         | 0.36%   |
| 0xb06a3    | 3         | 0.27%   |
| 0x806d1    | 3         | 0.27%   |
| 0x406c4    | 3         | 0.27%   |
| 0x106ca    | 3         | 0.27%   |
| 0x106c2    | 3         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KabyLake           | 240       | 22.47%  |
| Unknown            | 123       | 11.52%  |
| Haswell            | 79        | 7.4%    |
| Skylake            | 75        | 7.02%   |
| Alderlake Hybrid   | 59        | 5.52%   |
| SandyBridge        | 56        | 5.24%   |
| IvyBridge          | 56        | 5.24%   |
| TigerLake          | 45        | 4.21%   |
| Penryn             | 44        | 4.12%   |
| CometLake          | 39        | 3.65%   |
| IceLake            | 34        | 3.18%   |
| Broadwell          | 28        | 2.62%   |
| Zen 2              | 27        | 2.53%   |
| Zen 3              | 23        | 2.15%   |
| Westmere           | 23        | 2.15%   |
| Zen+               | 16        | 1.5%    |
| Core               | 15        | 1.4%    |
| Silvermont         | 12        | 1.12%   |
| Nehalem            | 11        | 1.03%   |
| Zen                | 8         | 0.75%   |
| Piledriver         | 8         | 0.75%   |
| Goldmont plus      | 8         | 0.75%   |
| Meteorlake Hybrid  | 6         | 0.56%   |
| Bonnell            | 5         | 0.47%   |
| Tremont            | 4         | 0.37%   |
| Puma               | 4         | 0.37%   |
| Steamroller        | 3         | 0.28%   |
| K8 Hammer          | 3         | 0.28%   |
| K10                | 3         | 0.28%   |
| Gracemont          | 3         | 0.28%   |
| NetBurst           | 1         | 0.09%   |
| Lunarlake Hybrid   | 1         | 0.09%   |
| Jaguar             | 1         | 0.09%   |
| Goldmont           | 1         | 0.09%   |
| Excavator          | 1         | 0.09%   |
| Bulldozer          | 1         | 0.09%   |
| Bobcat             | 1         | 0.09%   |
| ArrowLake-H Hybrid | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 715       | 55.47%  |
| Nvidia                     | 390       | 30.26%  |
| AMD                        | 175       | 13.58%  |
| Matrox Electronics Systems | 5         | 0.39%   |
| ASPEED Technology          | 3         | 0.23%   |
| VIA Technologies           | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 42        | 3.19%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 41        | 3.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 2.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33        | 2.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 2.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 2.05%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 24        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 1.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 24        | 1.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 1.82%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 22        | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16        | 1.21%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 15        | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 1.14%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 15        | 1.14%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 14        | 1.06%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 14        | 1.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 12        | 0.91%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 12        | 0.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 12        | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 0.84%   |
| Intel Iris Plus Graphics G7                                                              | 11        | 0.84%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                                | 11        | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 11        | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.76%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 10        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.76%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 0.76%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10        | 0.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 0.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.68%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 0.68%   |
| AMD Raphael                                                                              | 9         | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                               | 8         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 511       | 47.49%  |
| 1 x Nvidia           | 199       | 18.49%  |
| Intel + Nvidia       | 167       | 15.52%  |
| 1 x AMD              | 126       | 11.71%  |
| AMD + Nvidia         | 20        | 1.86%   |
| Intel + AMD          | 16        | 1.49%   |
| 2 x AMD              | 11        | 1.02%   |
| Other                | 9         | 0.84%   |
| 2 x Intel            | 5         | 0.46%   |
| Nvidia + Matrox      | 4         | 0.37%   |
| 1 x ASPEED           | 2         | 0.19%   |
| 2 x Nvidia           | 1         | 0.09%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.09%   |
| 1 x VIA              | 1         | 0.09%   |
| Nvidia + ASPEED      | 1         | 0.09%   |
| 1 x Matrox           | 1         | 0.09%   |
| AMD + 2 x Nvidia     | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 781       | 72.38%  |
| Proprietary | 210       | 19.46%  |
| Unknown     | 88        | 8.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 737       | 67.49%  |
| 1.01-2.0   | 98        | 8.97%   |
| 3.01-4.0   | 70        | 6.41%   |
| 7.01-8.0   | 50        | 4.58%   |
| 0.01-0.5   | 50        | 4.58%   |
| 0.51-1.0   | 38        | 3.48%   |
| 5.01-6.0   | 19        | 1.74%   |
| 8.01-16.0  | 19        | 1.74%   |
| 2.01-3.0   | 6         | 0.55%   |
| 16.01-24.0 | 4         | 0.37%   |
| 24.01-32.0 | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 196       | 16.08%  |
| Dell                    | 141       | 11.57%  |
| AU Optronics            | 116       | 9.52%   |
| BOE                     | 106       | 8.7%    |
| Chimei Innolux          | 96        | 7.88%   |
| LG Display              | 82        | 6.73%   |
| Goldstar                | 57        | 4.68%   |
| Philips                 | 48        | 3.94%   |
| Lenovo                  | 43        | 3.53%   |
| AOC                     | 25        | 2.05%   |
| Sharp                   | 24        | 1.97%   |
| Hewlett-Packard         | 22        | 1.8%    |
| ASUSTek Computer        | 17        | 1.39%   |
| Ancor Communications    | 17        | 1.39%   |
| Chi Mei Optoelectronics | 12        | 0.98%   |
| BenQ                    | 12        | 0.98%   |
| Valve                   | 11        | 0.9%    |
| Apple                   | 11        | 0.9%    |
| Acer                    | 11        | 0.9%    |
| HJW                     | 10        | 0.82%   |
| ViewSonic               | 9         | 0.74%   |
| InfoVision              | 9         | 0.74%   |
| Unknown                 | 8         | 0.66%   |
| PANDA                   | 8         | 0.66%   |
| CSO                     | 7         | 0.57%   |
| Gigabyte Technology     | 6         | 0.49%   |
| Toshiba                 | 5         | 0.41%   |
| LG Philips              | 5         | 0.41%   |
| VIE                     | 4         | 0.33%   |
| Sony                    | 4         | 0.33%   |
| MSI                     | 4         | 0.33%   |
| LG Electronics          | 4         | 0.33%   |
| Lenovo Group Limited    | 4         | 0.33%   |
| Hyundai ImageQuest      | 4         | 0.33%   |
| TMX                     | 3         | 0.25%   |
| SANYO                   | 3         | 0.25%   |
| Panasonic               | 3         | 0.25%   |
| Mi                      | 3         | 0.25%   |
| Iiyama                  | 3         | 0.25%   |
| HKC                     | 3         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 9         | 0.71%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.71%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 8         | 0.63%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 8         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.63%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                 | 7         | 0.55%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 7         | 0.55%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 0.55%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 6         | 0.47%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6         | 0.47%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 6         | 0.47%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 6         | 0.47%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 6         | 0.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.39%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.31%   |
| Philips 222EL PHLC052 1920x1080 476x268mm 21.5-inch                   | 4         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.31%   |
| Lenovo E27q-20 LEN62D0 2560x1440 597x336mm 27.0-inch                  | 4         | 0.31%   |
| Hyundai ImageQuest L90D+ D-SUB HIQ91DA 1280x1024 376x301mm 19.0-inch  | 4         | 0.31%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 4         | 0.31%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4         | 0.31%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 4         | 0.31%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 4         | 0.31%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.31%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                 | 4         | 0.31%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.31%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch  | 3         | 0.24%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch  | 3         | 0.24%   |
| Samsung Electronics S25HG5x SAM0DD5 1920x1080 544x303mm 24.5-inch     | 3         | 0.24%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 3         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 3         | 0.24%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 3         | 0.24%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 576       | 50.31%  |
| 1366x768 (WXGA)    | 122       | 10.66%  |
| 3840x2160 (4K)     | 94        | 8.21%   |
| 2560x1440 (QHD)    | 78        | 6.81%   |
| 1920x1200 (WUXGA)  | 50        | 4.37%   |
| 1680x1050 (WSXGA+) | 28        | 2.45%   |
| 1280x1024 (SXGA)   | 25        | 2.18%   |
| 2560x1600          | 21        | 1.83%   |
| 2880x1800          | 16        | 1.4%    |
| 1280x800 (WXGA)    | 14        | 1.22%   |
| Unknown            | 14        | 1.22%   |
| 3440x1440          | 12        | 1.05%   |
| 800x1280           | 11        | 0.96%   |
| 1600x900 (HD+)     | 11        | 0.96%   |
| 1440x900 (WXGA+)   | 11        | 0.96%   |
| 2560x1080          | 10        | 0.87%   |
| 3200x1800 (QHD+)   | 5         | 0.44%   |
| 2880x1620          | 5         | 0.44%   |
| 3840x1080          | 4         | 0.35%   |
| 3200x2000          | 3         | 0.26%   |
| 2160x1440          | 3         | 0.26%   |
| 1024x768 (XGA)     | 3         | 0.26%   |
| 3840x2400          | 2         | 0.17%   |
| 3456x2160          | 2         | 0.17%   |
| 1920x540           | 2         | 0.17%   |
| 1600x2560          | 2         | 0.17%   |
| 1360x768           | 2         | 0.17%   |
| 1280x768           | 2         | 0.17%   |
| 1024x600           | 2         | 0.17%   |
| 5360x1440          | 1         | 0.09%   |
| 5120x1440          | 1         | 0.09%   |
| 4480x1440          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3600x1080          | 1         | 0.09%   |
| 3520x1080          | 1         | 0.09%   |
| 3200x1200          | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2304x1440          | 1         | 0.09%   |
| 2304x1024          | 1         | 0.09%   |
| 2288x1287          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 248       | 20.45%  |
| 24      | 130       | 10.72%  |
| 27      | 126       | 10.39%  |
| 13      | 120       | 9.89%   |
| 14      | 103       | 8.49%   |
| 23      | 86        | 7.09%   |
| 21      | 77        | 6.35%   |
| Unknown | 41        | 3.38%   |
| 22      | 31        | 2.56%   |
| 31      | 30        | 2.47%   |
| 17      | 28        | 2.31%   |
| 16      | 24        | 1.98%   |
| 34      | 17        | 1.4%    |
| 19      | 17        | 1.4%    |
| 12      | 14        | 1.15%   |
| 32      | 12        | 0.99%   |
| 84      | 11        | 0.91%   |
| 40      | 11        | 0.91%   |
| 7       | 11        | 0.91%   |
| 20      | 10        | 0.82%   |
| 72      | 8         | 0.66%   |
| 26      | 7         | 0.58%   |
| 33      | 6         | 0.49%   |
| 18      | 6         | 0.49%   |
| 11      | 4         | 0.33%   |
| 8       | 4         | 0.33%   |
| 60      | 3         | 0.25%   |
| 48      | 3         | 0.25%   |
| 25      | 3         | 0.25%   |
| 10      | 3         | 0.25%   |
| 86      | 2         | 0.16%   |
| 65      | 2         | 0.16%   |
| 54      | 2         | 0.16%   |
| 43      | 2         | 0.16%   |
| 37      | 2         | 0.16%   |
| 28      | 2         | 0.16%   |
| 142     | 1         | 0.08%   |
| 75      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 442       | 37.11%  |
| 501-600        | 321       | 26.95%  |
| 401-500        | 124       | 10.41%  |
| 201-300        | 78        | 6.55%   |
| 601-700        | 44        | 3.69%   |
| Unknown        | 41        | 3.44%   |
| 351-400        | 39        | 3.27%   |
| 701-800        | 35        | 2.94%   |
| 1501-2000      | 20        | 1.68%   |
| 1001-1500      | 15        | 1.26%   |
| 801-900        | 13        | 1.09%   |
| 1-100          | 11        | 0.92%   |
| 101-200        | 4         | 0.34%   |
| 901-1000       | 3         | 0.25%   |
| More than 2000 | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 798       | 74.93%  |
| 16/10   | 158       | 14.84%  |
| Unknown | 39        | 3.66%   |
| 5/4     | 21        | 1.97%   |
| 21/9    | 18        | 1.69%   |
| 0.67    | 9         | 0.85%   |
| 3/2     | 8         | 0.75%   |
| 4/3     | 5         | 0.47%   |
| 0.62    | 2         | 0.19%   |
| 0.58    | 2         | 0.19%   |
| 0.56    | 2         | 0.19%   |
| 32/9    | 1         | 0.09%   |
| 1.96    | 1         | 0.09%   |
| 1.00    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 257       | 21.43%  |
| 101-110        | 248       | 20.68%  |
| 81-90          | 170       | 14.18%  |
| 301-350        | 133       | 11.09%  |
| 351-500        | 67        | 5.59%   |
| 71-80          | 49        | 4.09%   |
| 151-200        | 44        | 3.67%   |
| 251-300        | 42        | 3.5%    |
| Unknown        | 41        | 3.42%   |
| More than 1000 | 34        | 2.84%   |
| 111-120        | 23        | 1.92%   |
| 501-1000       | 18        | 1.5%    |
| 1-40           | 15        | 1.25%   |
| 61-70          | 14        | 1.17%   |
| 141-150        | 14        | 1.17%   |
| 121-130        | 14        | 1.17%   |
| 51-60          | 5         | 0.42%   |
| 131-140        | 5         | 0.42%   |
| 91-100         | 4         | 0.33%   |
| 41-50          | 2         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 397       | 34.31%  |
| 121-160       | 293       | 25.32%  |
| 101-120       | 242       | 20.92%  |
| 161-240       | 113       | 9.77%   |
| More than 240 | 47        | 4.06%   |
| Unknown       | 42        | 3.63%   |
| 1-50          | 23        | 1.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 808       | 73.99%  |
| 2     | 205       | 18.77%  |
| 0     | 49        | 4.49%   |
| 3     | 28        | 2.56%   |
| 4     | 2         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 575       | 36.32%  |
| Intel                           | 564       | 35.63%  |
| Qualcomm Atheros                | 128       | 8.09%   |
| Broadcom                        | 50        | 3.16%   |
| MediaTek                        | 45        | 2.84%   |
| TP-Link                         | 24        | 1.52%   |
| Ralink Technology               | 22        | 1.39%   |
| Broadcom Limited                | 20        | 1.26%   |
| Lenovo                          | 13        | 0.82%   |
| Edimax Technology               | 12        | 0.76%   |
| Samsung Electronics             | 11        | 0.69%   |
| ASIX Electronics                | 11        | 0.69%   |
| Xiaomi                          | 9         | 0.57%   |
| DisplayLink                     | 8         | 0.51%   |
| Marvell Technology Group        | 7         | 0.44%   |
| Qualcomm Atheros Communications | 6         | 0.38%   |
| Nvidia                          | 6         | 0.38%   |
| Shenzhen Goodix Technology      | 5         | 0.32%   |
| Ralink                          | 5         | 0.32%   |
| Qualcomm                        | 5         | 0.32%   |
| Google                          | 5         | 0.32%   |
| D-Link                          | 4         | 0.25%   |
| Aquantia                        | 4         | 0.25%   |
| OPPO Electronics                | 3         | 0.19%   |
| Huawei Technologies             | 3         | 0.19%   |
| U-Blox                          | 2         | 0.13%   |
| Texas Instruments               | 2         | 0.13%   |
| STMicroelectronics              | 2         | 0.13%   |
| QinHeng Electronics             | 2         | 0.13%   |
| Microsoft                       | 2         | 0.13%   |
| Linksys                         | 2         | 0.13%   |
| ICS Advent                      | 2         | 0.13%   |
| Hewlett-Packard                 | 2         | 0.13%   |
| VIA Technologies                | 1         | 0.06%   |
| U.S. Robotics                   | 1         | 0.06%   |
| Toshiba                         | 1         | 0.06%   |
| Sierra Wireless                 | 1         | 0.06%   |
| ROCCAT                          | 1         | 0.06%   |
| Raspberry Pi                    | 1         | 0.06%   |
| PEAK-System Technik             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 362       | 19.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 52        | 2.76%   |
| Realtek RTL8125 2.5GbE Controller                                      | 51        | 2.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 47        | 2.5%    |
| Intel Wireless 8265 / 8275                                             | 38        | 2.02%   |
| Intel Wi-Fi 6 AX200                                                    | 35        | 1.86%   |
| Intel Wi-Fi 6 AX201                                                    | 34        | 1.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 1.44%   |
| Intel Ethernet Connection (2) I219-V                                   | 25        | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 24        | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 21        | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 21        | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 20        | 1.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 1.06%   |
| Intel I211 Gigabit Network Connection                                  | 19        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 18        | 0.96%   |
| Intel Wireless 8260                                                    | 18        | 0.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 17        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 16        | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                  | 16        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 16        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 16        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 0.8%    |
| Intel Ethernet Controller I225-V                                       | 15        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 0.8%    |
| Realtek 802.11ac NIC                                                   | 14        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 0.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 14        | 0.74%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 13        | 0.69%   |
| Intel Wireless 3165                                                    | 13        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                   | 13        | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                   | 13        | 0.69%   |
| Intel Wireless 3160                                                    | 12        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 11        | 0.58%   |
| Intel Wireless 7265                                                    | 11        | 0.58%   |
| Intel Wireless 7260                                                    | 11        | 0.58%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 11        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 407       | 49.63%  |
| Realtek Semiconductor           | 130       | 15.85%  |
| Qualcomm Atheros                | 103       | 12.56%  |
| Broadcom                        | 41        | 5%      |
| MediaTek                        | 38        | 4.63%   |
| TP-Link                         | 23        | 2.8%    |
| Ralink Technology               | 22        | 2.68%   |
| Broadcom Limited                | 14        | 1.71%   |
| Edimax Technology               | 12        | 1.46%   |
| Qualcomm Atheros Communications | 6         | 0.73%   |
| Ralink                          | 5         | 0.61%   |
| Qualcomm                        | 5         | 0.61%   |
| D-Link                          | 4         | 0.49%   |
| Microsoft                       | 2         | 0.24%   |
| Sierra Wireless                 | 1         | 0.12%   |
| Marvell Technology Group        | 1         | 0.12%   |
| Linksys                         | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Dell                            | 1         | 0.12%   |
| BUFFALO                         | 1         | 0.12%   |
| ASUSTek Computer                | 1         | 0.12%   |
| Unknown                         | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 38        | 4.59%   |
| Intel Wi-Fi 6 AX200                                                  | 35        | 4.23%   |
| Intel Wi-Fi 6 AX201                                                  | 34        | 4.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 24        | 2.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 21        | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 20        | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 20        | 2.42%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 20        | 2.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 18        | 2.17%   |
| Intel Wireless 8260                                                  | 18        | 2.17%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 17        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 16        | 1.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 16        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 16        | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 15        | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 15        | 1.81%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 15        | 1.81%   |
| Realtek 802.11ac NIC                                                 | 14        | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 14        | 1.69%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 13        | 1.57%   |
| Intel Wireless 3165                                                  | 13        | 1.57%   |
| Intel Wireless 3160                                                  | 12        | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 12        | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 11        | 1.33%   |
| Intel Wireless 7265                                                  | 11        | 1.33%   |
| Intel Wireless 7260                                                  | 11        | 1.33%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 11        | 1.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 10        | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 10        | 1.21%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 9         | 1.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 9         | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 8         | 0.97%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 8         | 0.97%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 8         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 8         | 0.97%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 8         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 8         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 7         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 7         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 520       | 52.47%  |
| Intel                    | 309       | 31.18%  |
| Qualcomm Atheros         | 39        | 3.94%   |
| Broadcom                 | 21        | 2.12%   |
| Lenovo                   | 13        | 1.31%   |
| Samsung Electronics      | 11        | 1.11%   |
| ASIX Electronics         | 11        | 1.11%   |
| Xiaomi                   | 9         | 0.91%   |
| DisplayLink              | 8         | 0.81%   |
| Broadcom Limited         | 7         | 0.71%   |
| Nvidia                   | 6         | 0.61%   |
| MediaTek                 | 6         | 0.61%   |
| Marvell Technology Group | 6         | 0.61%   |
| Google                   | 5         | 0.5%    |
| Aquantia                 | 4         | 0.4%    |
| OPPO Electronics         | 3         | 0.3%    |
| ICS Advent               | 2         | 0.2%    |
| Huawei Technologies      | 2         | 0.2%    |
| VIA Technologies         | 1         | 0.1%    |
| TP-Link                  | 1         | 0.1%    |
| Raspberry Pi             | 1         | 0.1%    |
| Mellanox Technologies    | 1         | 0.1%    |
| Linksys                  | 1         | 0.1%    |
| HMD Global               | 1         | 0.1%    |
| Davicom Semiconductor    | 1         | 0.1%    |
| Attansic Technology      | 1         | 0.1%    |
| Accton Technology        | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 362       | 35.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 52        | 5.06%   |
| Realtek RTL8125 2.5GbE Controller                                      | 51        | 4.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 47        | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 2.63%   |
| Intel Ethernet Connection (2) I219-V                                   | 25        | 2.43%   |
| Intel I211 Gigabit Network Connection                                  | 19        | 1.85%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 16        | 1.56%   |
| Intel Ethernet Controller I225-V                                       | 15        | 1.46%   |
| Intel Ethernet Connection (7) I219-V                                   | 13        | 1.27%   |
| Intel Ethernet Connection (6) I219-V                                   | 13        | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 10        | 0.97%   |
| Intel I210 Gigabit Network Connection                                  | 10        | 0.97%   |
| Intel Ethernet Connection (13) I219-V                                  | 10        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 0.78%   |
| Intel Ethernet Controller I226-V                                       | 8         | 0.78%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.68%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 7         | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                                  | 7         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 0.68%   |
| Intel Ethernet Connection (14) I219-V                                  | 7         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                                  | 7         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                                 | 6         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.39%   |
| Lenovo USB-C Dock Ethernet                                             | 4         | 0.39%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.39%   |
| Intel Ethernet Connection (14) I219-LM                                 | 4         | 0.39%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 898       | 52.89%  |
| WiFi     | 774       | 45.58%  |
| Modem    | 23        | 1.35%   |
| Unknown  | 3         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 567       | 51.13%  |
| Ethernet | 541       | 48.78%  |
| Modem    | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 517       | 48.41%  |
| 2     | 509       | 47.66%  |
| 3     | 24        | 2.25%   |
| 0     | 10        | 0.94%   |
| 4     | 5         | 0.47%   |
| 7     | 1         | 0.09%   |
| 6     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 796       | 72.69%  |
| Yes  | 299       | 27.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 381       | 54.82%  |
| Realtek Semiconductor           | 59        | 8.49%   |
| IMC Networks                    | 52        | 7.48%   |
| Qualcomm Atheros Communications | 50        | 7.19%   |
| Cambridge Silicon Radio         | 40        | 5.76%   |
| Foxconn / Hon Hai               | 21        | 3.02%   |
| Broadcom                        | 17        | 2.45%   |
| Apple                           | 15        | 2.16%   |
| MediaTek                        | 10        | 1.44%   |
| Lite-On Technology              | 10        | 1.44%   |
| TP-Link                         | 6         | 0.86%   |
| Dell                            | 6         | 0.86%   |
| Realtek                         | 5         | 0.72%   |
| ASUSTek Computer                | 5         | 0.72%   |
| Hewlett-Packard                 | 4         | 0.58%   |
| Unknown                         | 4         | 0.58%   |
| USI                             | 2         | 0.29%   |
| Toshiba                         | 2         | 0.29%   |
| Askey Computer                  | 2         | 0.29%   |
| Opticis                         | 1         | 0.14%   |
| Marvell Semiconductor           | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |
| Actions                         | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 109       | 15.68%  |
| Intel AX201 Bluetooth                               | 90        | 12.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 57        | 8.2%    |
| Intel Bluetooth Device                              | 50        | 7.19%   |
| Realtek Bluetooth Radio                             | 42        | 6.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 40        | 5.76%   |
| Intel AX200 Bluetooth                               | 32        | 4.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 3.45%   |
| IMC Networks Wireless_Device                        | 23        | 3.31%   |
| Intel AX210 Bluetooth                               | 17        | 2.45%   |
| IMC Networks Bluetooth Radio                        | 17        | 2.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 1.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 1.44%   |
| MediaTek Wireless_Device                            | 9         | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.15%   |
| Apple Bluetooth Host Controller                     | 7         | 1.01%   |
| TP-Link TP-T@- UB500 Adapter                        | 6         | 0.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 0.86%   |
| Lite-On Bluetooth Device                            | 6         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.86%   |
| IMC Networks Bluetooth Device                       | 6         | 0.86%   |
| Realtek Bluetooth Radio                             | 5         | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.72%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.58%   |
| Unknown                                             | 4         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.43%   |
| USI Bluetooth Device                                | 2         | 0.29%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.29%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.29%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.29%   |
| Foxconn / Hon Hai BT                                | 2         | 0.29%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 875       | 56.82%  |
| Nvidia                                       | 290       | 18.83%  |
| AMD                                          | 186       | 12.08%  |
| Logitech                                     | 21        | 1.36%   |
| C-Media Electronics                          | 17        | 1.1%    |
| Lenovo                                       | 16        | 1.04%   |
| Hewlett-Packard                              | 9         | 0.58%   |
| Creative Labs                                | 9         | 0.58%   |
| XMOS                                         | 7         | 0.45%   |
| Realtek Semiconductor                        | 7         | 0.45%   |
| GN Netcom                                    | 7         | 0.45%   |
| Micro Star International                     | 6         | 0.39%   |
| Texas Instruments                            | 5         | 0.32%   |
| Microsoft                                    | 5         | 0.32%   |
| JMTek                                        | 5         | 0.32%   |
| Generalplus Technology                       | 5         | 0.32%   |
| Focusrite-Novation                           | 5         | 0.32%   |
| Creative Technology                          | 5         | 0.32%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.26%   |
| Razer USA                                    | 4         | 0.26%   |
| ASUSTek Computer                             | 4         | 0.26%   |
| Unknown                                      | 4         | 0.26%   |
| SteelSeries ApS                              | 3         | 0.19%   |
| Plantronics                                  | 3         | 0.19%   |
| Kingston Technology                          | 3         | 0.19%   |
| Comtrue                                      | 3         | 0.19%   |
| Cambridge Silicon Radio                      | 3         | 0.19%   |
| VIA Technologies                             | 2         | 0.13%   |
| FIFINE Microphones                           | 2         | 0.13%   |
| Dell                                         | 2         | 0.13%   |
| Blue Microphones                             | 2         | 0.13%   |
| Sony                                         | 1         | 0.06%   |
| Sennheiser Communications                    | 1         | 0.06%   |
| Samson Technologies                          | 1         | 0.06%   |
| Roland                                       | 1         | 0.06%   |
| RODE Microphones                             | 1         | 0.06%   |
| PreSonus Audio Electronics                   | 1         | 0.06%   |
| MV-SILICON                                   | 1         | 0.06%   |
| Meridian                                     | 1         | 0.06%   |
| Mackie Designs                               | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 95        | 5.45%   |
| AMD Ryzen HD Audio Controller                                              | 75        | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 65        | 3.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 55        | 3.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 45        | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 44        | 2.53%   |
| Intel 200 Series PCH HD Audio                                              | 44        | 2.53%   |
| AMD Radeon High Definition Audio Controller                                | 44        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 42        | 2.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 42        | 2.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 40        | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 2.12%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 32        | 1.84%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 29        | 1.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 28        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 27        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 27        | 1.55%   |
| Intel Comet Lake PCH-LP cAVS                                               | 26        | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 25        | 1.44%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 25        | 1.44%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                     | 22        | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 21        | 1.21%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 21        | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 20        | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 19        | 1.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 1.09%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 1.09%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 1.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 1.03%   |
| Intel Raptor Lake High Definition Audio Controller                         | 18        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 17        | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 17        | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17        | 0.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 15        | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 14        | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 14        | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 149       | 20.47%  |
| SK hynix            | 131       | 17.99%  |
| Kingston            | 103       | 14.15%  |
| Micron Technology   | 102       | 14.01%  |
| Unknown             | 51        | 7.01%   |
| Crucial             | 42        | 5.77%   |
| G.Skill             | 35        | 4.81%   |
| Corsair             | 33        | 4.53%   |
| Ramaxel Technology  | 21        | 2.88%   |
| A-DATA Technology   | 11        | 1.51%   |
| Nanya Technology    | 9         | 1.24%   |
| Transcend           | 8         | 1.1%    |
| Elpida              | 6         | 0.82%   |
| Team                | 5         | 0.69%   |
| Unknown             | 4         | 0.55%   |
| Lexar Co Limited    | 3         | 0.41%   |
| GeIL                | 2         | 0.27%   |
| V-Color             | 1         | 0.14%   |
| Unknown (09D5)      | 1         | 0.14%   |
| Unknown (08C8)      | 1         | 0.14%   |
| Undefined-004F      | 1         | 0.14%   |
| Patriot             | 1         | 0.14%   |
| Lexar               | 1         | 0.14%   |
| KingSpec            | 1         | 0.14%   |
| KETECH              | 1         | 0.14%   |
| Hewlett-Packard     | 1         | 0.14%   |
| Avant               | 1         | 0.14%   |
| ASint Technology    | 1         | 0.14%   |
| Ankowall            | 1         | 0.14%   |
| 48spaces            | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.77%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 6         | 0.77%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.64%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.64%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 5         | 0.64%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s            | 5         | 0.64%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 4         | 0.51%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 4         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 4         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 4         | 0.51%   |
| Kingston RAM KF2666C16S4/32G 32GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s             | 4         | 0.51%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s             | 4         | 0.51%   |
| Unknown                                                          | 4         | 0.51%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.39%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.39%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.39%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.39%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 3         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.39%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s         | 3         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 334       | 54.05%  |
| DDR3    | 126       | 20.39%  |
| DDR5    | 41        | 6.63%   |
| LPDDR5  | 28        | 4.53%   |
| Unknown | 25        | 4.05%   |
| DDR2    | 20        | 3.24%   |
| LPDDR3  | 18        | 2.91%   |
| LPDDR4  | 11        | 1.78%   |
| SDRAM   | 8         | 1.29%   |
| DDR     | 5         | 0.81%   |
| DRAM    | 2         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 336       | 54.37%  |
| DIMM         | 222       | 35.92%  |
| Row Of Chips | 55        | 8.9%    |
| Unknown      | 3         | 0.49%   |
| Chip         | 2         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 234       | 34.21%  |
| 16384 | 168       | 24.56%  |
| 4096  | 156       | 22.81%  |
| 2048  | 55        | 8.04%   |
| 32768 | 50        | 7.31%   |
| 1024  | 18        | 2.63%   |
| 49152 | 1         | 0.15%   |
| 24576 | 1         | 0.15%   |
| 12288 | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 126       | 18.67%  |
| 2667    | 99        | 14.67%  |
| 1600    | 93        | 13.78%  |
| 2400    | 45        | 6.67%   |
| 2133    | 42        | 6.22%   |
| 1333    | 23        | 3.41%   |
| 6400    | 20        | 2.96%   |
| 800     | 18        | 2.67%   |
| 3600    | 17        | 2.52%   |
| 5600    | 15        | 2.22%   |
| 4800    | 15        | 2.22%   |
| 667     | 15        | 2.22%   |
| 1334    | 10        | 1.48%   |
| 1867    | 9         | 1.33%   |
| Unknown | 9         | 1.33%   |
| 4267    | 8         | 1.19%   |
| 3800    | 8         | 1.19%   |
| 1067    | 8         | 1.19%   |
| 6000    | 7         | 1.04%   |
| 3733    | 7         | 1.04%   |
| 3266    | 7         | 1.04%   |
| 7500    | 6         | 0.89%   |
| 3466    | 6         | 0.89%   |
| 2666    | 6         | 0.89%   |
| 2933    | 4         | 0.59%   |
| 8400    | 3         | 0.44%   |
| 3933    | 3         | 0.44%   |
| 3151    | 3         | 0.44%   |
| 2800    | 3         | 0.44%   |
| 2000    | 3         | 0.44%   |
| 1866    | 3         | 0.44%   |
| 1800    | 3         | 0.44%   |
| 533     | 3         | 0.44%   |
| 7467    | 2         | 0.3%    |
| 5900    | 2         | 0.3%    |
| 4199    | 2         | 0.3%    |
| 4000    | 2         | 0.3%    |
| 3467    | 2         | 0.3%    |
| 3000    | 2         | 0.3%    |
| 1648    | 2         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 51.85%  |
| Samsung Electronics   | 5         | 18.52%  |
| Canon                 | 2         | 7.41%   |
| Brother Industries    | 2         | 7.41%   |
| Seiko Epson           | 1         | 3.7%    |
| Lexmark International | 1         | 3.7%    |
| GODEX INTERNATIONAL   | 1         | 3.7%    |
| BIXOLON               | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP Officejet 4500 G510g-m          | 3         | 11.11%  |
| HP DeskJet 4670 series             | 3         | 11.11%  |
| Samsung M2070 Series               | 2         | 7.41%   |
| HP Printing Support                | 2         | 7.41%   |
| Seiko Epson ET-2710 Series         | 1         | 3.7%    |
| Samsung SCX-4623 Series            | 1         | 3.7%    |
| Samsung ML-1610 Mono Laser Printer | 1         | 3.7%    |
| Samsung M288x Series               | 1         | 3.7%    |
| Lexmark International CS417dn      | 1         | 3.7%    |
| HP Smart Tank 510 series           | 1         | 3.7%    |
| HP OfficeJet 5600 (USBHUB)         | 1         | 3.7%    |
| HP LaserJet M14-M17                | 1         | 3.7%    |
| HP LaserJet 3050                   | 1         | 3.7%    |
| HP Deskjet 4640 series             | 1         | 3.7%    |
| HP DeskJet 2700 series             | 1         | 3.7%    |
| GODEX INTERNATIONAL DT2            | 1         | 3.7%    |
| Canon TR7500 series                | 1         | 3.7%    |
| Canon PIXMA MX490 Series           | 1         | 3.7%    |
| Brother Printer                    | 1         | 3.7%    |
| Brother MFC-J497DW                 | 1         | 3.7%    |
| BIXOLON BIXOLON_SLP-T400           | 1         | 3.7%    |

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


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                                  | 2         | 40%     |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 20%     |
| Canon CanoScan LiDE 220                                  | 1         | 20%     |
| Canon CanoScan LiDE 110                                  | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 92        | 13.81%  |
| Chicony Electronics                    | 92        | 13.81%  |
| Realtek Semiconductor                  | 68        | 10.21%  |
| Logitech                               | 53        | 7.96%   |
| Microdia                               | 44        | 6.61%   |
| Sunplus Innovation Technology          | 39        | 5.86%   |
| Bison Electronics                      | 39        | 5.86%   |
| Microsoft                              | 34        | 5.11%   |
| Luxvisions Innotech Limited            | 27        | 4.05%   |
| Quanta                                 | 17        | 2.55%   |
| Apple                                  | 17        | 2.55%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 2.4%    |
| Syntek                                 | 14        | 2.1%    |
| Lite-On Technology                     | 13        | 1.95%   |
| Suyin                                  | 10        | 1.5%    |
| Sonix Technology                       | 10        | 1.5%    |
| Generalplus Technology                 | 9         | 1.35%   |
| Silicon Motion                         | 7         | 1.05%   |
| Samsung Electronics                    | 7         | 1.05%   |
| Lenovo                                 | 6         | 0.9%    |
| ShineTech                              | 5         | 0.75%   |
| Acer                                   | 5         | 0.75%   |
| Alcor Micro                            | 4         | 0.6%    |
| Ricoh                                  | 2         | 0.3%    |
| Jieli Technology                       | 2         | 0.3%    |
| icSpring                               | 2         | 0.3%    |
| GEMBIRD                                | 2         | 0.3%    |
| Cubeternet                             | 2         | 0.3%    |
| ALi                                    | 2         | 0.3%    |
| Z-Star Microelectronics                | 1         | 0.15%   |
| YGTek                                  | 1         | 0.15%   |
| Yealink Network Technology             | 1         | 0.15%   |
| Xiaomi                                 | 1         | 0.15%   |
| WaveRider Communications               | 1         | 0.15%   |
| USB CAMERA                             | 1         | 0.15%   |
| Tripath Technology                     | 1         | 0.15%   |
| Tobii Technology AB                    | 1         | 0.15%   |
| SunplusIT                              | 1         | 0.15%   |
| Shine-optics                           | 1         | 0.15%   |
| Razer USA                              | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 38        | 5.69%   |
| Chicony Integrated Camera                           | 38        | 5.69%   |
| Realtek Integrated_Webcam_HD                        | 30        | 4.49%   |
| IMC Networks Integrated Camera                      | 22        | 3.29%   |
| Microsoft LifeCam HD-3000                           | 21        | 3.14%   |
| Microdia Integrated_Webcam_HD                       | 19        | 2.84%   |
| Bison Integrated Camera                             | 14        | 2.1%    |
| Luxvisions Innotech Limited Integrated Camera       | 13        | 1.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 13        | 1.95%   |
| Syntek Integrated Camera                            | 11        | 1.65%   |
| Logitech Webcam C270                                | 8         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 8         | 1.2%    |
| Sunplus Integrated Camera                           | 7         | 1.05%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 1.05%   |
| Logitech C922 Pro Stream Webcam                     | 7         | 1.05%   |
| Chicony Lenovo EasyCamera                           | 7         | 1.05%   |
| Bison Lenovo EasyCamera                             | 7         | 1.05%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 0.9%    |
| Sonix USB2.0 FHD UVC WebCam                         | 6         | 0.9%    |
| Logitech HD Pro Webcam C920                         | 6         | 0.9%    |
| Chicony HP HD Camera                                | 6         | 0.9%    |
| Realtek USB Camera                                  | 5         | 0.75%   |
| Lite-On HP HD Camera                                | 5         | 0.75%   |
| Generalplus GENERAL WEBCAM                          | 5         | 0.75%   |
| Chicony HP TrueVision HD Camera                     | 5         | 0.75%   |
| Chicony EasyCamera                                  | 5         | 0.75%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.6%    |
| Realtek Lenovo EasyCamera                           | 4         | 0.6%    |
| Realtek Integrated_Webcam_FHD                       | 4         | 0.6%    |
| Realtek Integrated Webcam HD                        | 4         | 0.6%    |
| Luxvisions Innotech Limited Integrated RGB Camera   | 4         | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 0.6%    |
| Logitech Webcam C310                                | 4         | 0.6%    |
| Logitech C920 PRO HD Webcam                         | 4         | 0.6%    |
| Logitech BRIO Ultra HD Webcam                       | 4         | 0.6%    |
| Lite-On Integrated Camera                           | 4         | 0.6%    |
| IMC Networks USB2.0 HD IR UVC WebCam                | 4         | 0.6%    |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.6%    |
| Bison SunplusIT Integrated Camera                   | 4         | 0.6%    |
| Sunplus Integrated_Webcam_FHD                       | 3         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 57        | 45.6%   |
| Validity Sensors                   | 33        | 26.4%   |
| Shenzhen Goodix Technology         | 15        | 12%     |
| Elan Microelectronics              | 8         | 6.4%    |
| Upek                               | 4         | 3.2%    |
| AuthenTec                          | 3         | 2.4%    |
| STMicroelectronics                 | 2         | 1.6%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.6%    |
| LighTuning Technology              | 1         | 0.8%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 16.8%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 5.6%    |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 5.6%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 5.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 4.8%    |
| Synaptics WBDI                                                             | 6         | 4.8%    |
| Validity Sensors Synaptics WBDI                                            | 5         | 4%      |
| Synaptics  WBDI                                                            | 5         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 4%      |
| Elan ELAN:Fingerprint                                                      | 5         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.2%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 2.4%    |
| Synaptics UWP WBDI Device                                                  | 3         | 2.4%    |
| Synaptics UWP WBDI                                                         | 3         | 2.4%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.4%    |
| Elan ELAN:ARM-M4                                                           | 3         | 2.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.6%    |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.6%    |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.6%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.6%    |
| Validity Sensors VFS491                                                    | 1         | 0.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.8%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.8%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.8%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.8%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.8%    |
| AuthenTec AES2810                                                          | 1         | 0.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.8%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 33        | 56.9%   |
| Alcor Micro                | 22        | 37.93%  |
| O2 Micro                   | 2         | 3.45%   |
| Athena Smartcard Solutions | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 37.93%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 10        | 17.24%  |
| Broadcom 5880                                                                | 9         | 15.52%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 12.07%  |
| Broadcom 58200                                                               | 5         | 8.62%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.45%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 3.45%   |
| Athena Smartcard Solutions ASEDrive V3C                                      | 1         | 1.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 741       | 67.98%  |
| 1     | 274       | 25.14%  |
| 2     | 59        | 5.41%   |
| 3     | 11        | 1.01%   |
| 4     | 2         | 0.18%   |
| 7     | 1         | 0.09%   |
| 6     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 123       | 28.87%  |
| Graphics card            | 100       | 23.47%  |
| Net/wireless             | 67        | 15.73%  |
| Chipcard                 | 48        | 11.27%  |
| Communication controller | 18        | 4.23%   |
| Multimedia controller    | 17        | 3.99%   |
| Camera                   | 17        | 3.99%   |
| Unassigned class         | 13        | 3.05%   |
| Bluetooth                | 6         | 1.41%   |
| Card reader              | 5         | 1.17%   |
| Net/ethernet             | 4         | 0.94%   |
| Network                  | 3         | 0.7%    |
| Storage                  | 2         | 0.47%   |
| Sound                    | 2         | 0.47%   |
| Firewire controller      | 1         | 0.23%   |

