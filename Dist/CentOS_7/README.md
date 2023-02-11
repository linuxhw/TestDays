CentOS 7 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for CentOS 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS_7/Desktop/README.md) and [notebooks](/Dist/CentOS_7/Notebook/README.md).

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

Total: 399

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | 870-G45                     | Desktop     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| PCChips       | P49G                        | Desktop     | [24a7d0e02b](https://linux-hardware.org/?probe=24a7d0e02b) | Jan 24, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [762142dfbb](https://linux-hardware.org/?probe=762142dfbb) | Jan 06, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [37905125fc](https://linux-hardware.org/?probe=37905125fc) | Dec 21, 2022 |
| LG Electro... | 15UD480-GX50K               | Notebook    | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Dell          | Precision 7720              | Notebook    | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [164a07eda1](https://linux-hardware.org/?probe=164a07eda1) | Dec 08, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [d7d701ca15](https://linux-hardware.org/?probe=d7d701ca15) | Dec 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| ABIT          | I-45CV                      | Desktop     | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [51120805b1](https://linux-hardware.org/?probe=51120805b1) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [7a809e9dbd](https://linux-hardware.org/?probe=7a809e9dbd) | Dec 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [b79b60e4b3](https://linux-hardware.org/?probe=b79b60e4b3) | Nov 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [74e3fe80fd](https://linux-hardware.org/?probe=74e3fe80fd) | Nov 23, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [bafb634a37](https://linux-hardware.org/?probe=bafb634a37) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [efd2a439bd](https://linux-hardware.org/?probe=efd2a439bd) | Nov 21, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [4cafe39785](https://linux-hardware.org/?probe=4cafe39785) | Nov 19, 2022 |
| MSI           | 870-G45                     | Desktop     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| HP            | 8717                        | Desktop     | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| MSI           | 870-G45                     | Desktop     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| HP            | 8717                        | Desktop     | [00cbc9cd2a](https://linux-hardware.org/?probe=00cbc9cd2a) | Nov 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| NORCO         | BPC-7951                    | Desktop     | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| Lenovo        | 7Z73CTO1WW                  | Server      | [ac182ad6f5](https://linux-hardware.org/?probe=ac182ad6f5) | Oct 18, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [16ab028232](https://linux-hardware.org/?probe=16ab028232) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f4ce3cf768](https://linux-hardware.org/?probe=f4ce3cf768) | Oct 13, 2022 |
| Dell          | 082WXT A03                  | Desktop     | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| MSI           | 870-G45                     | Desktop     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| MSI           | 870-G45                     | Desktop     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [e61dc9628f](https://linux-hardware.org/?probe=e61dc9628f) | Sep 17, 2022 |
| Dell          | 03TJ75 A00                  | Desktop     | [70ef579566](https://linux-hardware.org/?probe=70ef579566) | Sep 15, 2022 |
| Intel         | S1200SP H57533-350          | Server      | [6e17cb41c9](https://linux-hardware.org/?probe=6e17cb41c9) | Sep 15, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [c97eb83b9c](https://linux-hardware.org/?probe=c97eb83b9c) | Aug 16, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [1de43750ce](https://linux-hardware.org/?probe=1de43750ce) | Aug 16, 2022 |
| ASRock        | X299 Professional Gaming... | Desktop     | [759afd2f9a](https://linux-hardware.org/?probe=759afd2f9a) | Aug 04, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [4eec45d964](https://linux-hardware.org/?probe=4eec45d964) | Jul 21, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [15e71f4f03](https://linux-hardware.org/?probe=15e71f4f03) | Jul 21, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| Intel         | D410PT AAE76528-404         | Desktop     | [b7c62fc4a8](https://linux-hardware.org/?probe=b7c62fc4a8) | Jun 29, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f0d321b741](https://linux-hardware.org/?probe=f0d321b741) | Jun 22, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [139ffc0039](https://linux-hardware.org/?probe=139ffc0039) | Jun 16, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f339cce523](https://linux-hardware.org/?probe=f339cce523) | Jun 16, 2022 |
| HP            | 8711                        | Mini pc     | [6ceafddb10](https://linux-hardware.org/?probe=6ceafddb10) | Jun 13, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| HP            | 3397                        | Desktop     | [f2e8417afc](https://linux-hardware.org/?probe=f2e8417afc) | Jun 04, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0353933c85](https://linux-hardware.org/?probe=0353933c85) | Jun 02, 2022 |
| HP            | 1998                        | Desktop     | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8120719b26](https://linux-hardware.org/?probe=8120719b26) | May 26, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [7cbd29cc48](https://linux-hardware.org/?probe=7cbd29cc48) | May 15, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Dell          | Vostro 5581                 | Notebook    | [cdcb310766](https://linux-hardware.org/?probe=cdcb310766) | Apr 30, 2022 |
| Dell          | 0K068D A00                  | Desktop     | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | Notebook    | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [8f3e545e28](https://linux-hardware.org/?probe=8f3e545e28) | Apr 13, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Dell          | 0Y2YM6 A01                  | Desktop     | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| HP            | 0AECh D                     | Desktop     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| MiTAC         | UltraPoint                  | Desktop     | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| HP            | 0A9Ch                       | Desktop     | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| Intel         | S1200SP H57533-210          | Server      | [7c1fa00b21](https://linux-hardware.org/?probe=7c1fa00b21) | Feb 23, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [27bb88805d](https://linux-hardware.org/?probe=27bb88805d) | Feb 10, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [6f558be780](https://linux-hardware.org/?probe=6f558be780) | Feb 10, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f76e2b6c0f](https://linux-hardware.org/?probe=f76e2b6c0f) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [a355e13859](https://linux-hardware.org/?probe=a355e13859) | Jan 11, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a810f7c0fb](https://linux-hardware.org/?probe=a810f7c0fb) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Lenovo        | 7Z71CTO1WW                  | Server      | [ff6113b91d](https://linux-hardware.org/?probe=ff6113b91d) | Dec 17, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | Desktop     | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| ASUSTek       | Pro Q570M-C                 | Desktop     | [d868c52b5a](https://linux-hardware.org/?probe=d868c52b5a) | Dec 15, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0ca333f8b0](https://linux-hardware.org/?probe=0ca333f8b0) | Dec 15, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| HP            | 8717                        | Desktop     | [a00d17d8c4](https://linux-hardware.org/?probe=a00d17d8c4) | Nov 25, 2021 |
| Dell          | 02K9CR A01                  | Desktop     | [36c6a137fb](https://linux-hardware.org/?probe=36c6a137fb) | Nov 23, 2021 |
| Gigabyte      | B360HD3                     | Desktop     | [71a92047fb](https://linux-hardware.org/?probe=71a92047fb) | Nov 23, 2021 |
| Dell          | 02K9CR A01                  | Desktop     | [7d558b813e](https://linux-hardware.org/?probe=7d558b813e) | Nov 17, 2021 |
| Dell          | 06WXJT A01                  | Server      | [fcc6d41c03](https://linux-hardware.org/?probe=fcc6d41c03) | Nov 12, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [6c41e1551e](https://linux-hardware.org/?probe=6c41e1551e) | Nov 09, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [736e182a15](https://linux-hardware.org/?probe=736e182a15) | Nov 09, 2021 |
| HP            | 872C                        | Mini pc     | [36f1254c43](https://linux-hardware.org/?probe=36f1254c43) | Nov 08, 2021 |
| HP            | 872C                        | Mini pc     | [e4450bb253](https://linux-hardware.org/?probe=e4450bb253) | Nov 08, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | Desktop     | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| Huanan        | X79                         | Desktop     | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | Desktop     | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [a68000e142](https://linux-hardware.org/?probe=a68000e142) | Sep 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [41d65e59eb](https://linux-hardware.org/?probe=41d65e59eb) | Sep 26, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [26944912d7](https://linux-hardware.org/?probe=26944912d7) | Sep 17, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [fd6f5273e3](https://linux-hardware.org/?probe=fd6f5273e3) | Sep 02, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [0beccde57d](https://linux-hardware.org/?probe=0beccde57d) | Sep 01, 2021 |
| Supermicro    | X10DRL-CT                   | Server      | [cc00646768](https://linux-hardware.org/?probe=cc00646768) | Aug 28, 2021 |
| Supermicro    | X10DRL-CT                   | Server      | [15df3c0fff](https://linux-hardware.org/?probe=15df3c0fff) | Aug 28, 2021 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| HP            | 8751                        | Desktop     | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Lenovo        | 7X06CTO1WW                  | Server      | [928ee22e71](https://linux-hardware.org/?probe=928ee22e71) | Aug 24, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [5e08b5eafd](https://linux-hardware.org/?probe=5e08b5eafd) | Aug 22, 2021 |
| Supermicro    | X11SSH-F                    | Server      | [35fff898d1](https://linux-hardware.org/?probe=35fff898d1) | Aug 20, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [6e6d5c8f2c](https://linux-hardware.org/?probe=6e6d5c8f2c) | Aug 20, 2021 |
| HP            | Presario C700               | Notebook    | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [8ddb489f03](https://linux-hardware.org/?probe=8ddb489f03) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d19976dabe](https://linux-hardware.org/?probe=d19976dabe) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [d56fdac07b](https://linux-hardware.org/?probe=d56fdac07b) | Aug 05, 2021 |
| HP            | ProLiant DL360 G5           | Server      | [58c9a1d28b](https://linux-hardware.org/?probe=58c9a1d28b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [3eb59a276c](https://linux-hardware.org/?probe=3eb59a276c) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [3d0db6b81f](https://linux-hardware.org/?probe=3d0db6b81f) | Aug 05, 2021 |
| Sun Micros... | S39                         | Server      | [e54a36a0c4](https://linux-hardware.org/?probe=e54a36a0c4) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [1fc2375e54](https://linux-hardware.org/?probe=1fc2375e54) | Aug 05, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [7952948421](https://linux-hardware.org/?probe=7952948421) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a653e9beb2](https://linux-hardware.org/?probe=a653e9beb2) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [9a5d8276bf](https://linux-hardware.org/?probe=9a5d8276bf) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [2165980dd3](https://linux-hardware.org/?probe=2165980dd3) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [4a2adade2a](https://linux-hardware.org/?probe=4a2adade2a) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [78c5e3532b](https://linux-hardware.org/?probe=78c5e3532b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [10bdaec1ef](https://linux-hardware.org/?probe=10bdaec1ef) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [70fc6a65ef](https://linux-hardware.org/?probe=70fc6a65ef) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [80244f2809](https://linux-hardware.org/?probe=80244f2809) | Aug 05, 2021 |
| Sun Micros... | Sun Fire X2270 375-3602-... | Server      | [54eaa5139f](https://linux-hardware.org/?probe=54eaa5139f) | Aug 05, 2021 |
| HP            | 8591                        | Desktop     | [6794bdb00e](https://linux-hardware.org/?probe=6794bdb00e) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f209feb9c8](https://linux-hardware.org/?probe=f209feb9c8) | Aug 05, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [40b8d28af0](https://linux-hardware.org/?probe=40b8d28af0) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [597de4e10b](https://linux-hardware.org/?probe=597de4e10b) | Aug 01, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| HP            | 2B34                        | Desktop     | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | Desktop     | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| HP            | 1494                        | Desktop     | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Intel         | E98683-353                  | Desktop     | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| HP            | 1589                        | Desktop     | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| ASRock        | J3710M                      | Desktop     | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | 8710                        | Mini pc     | [b2a212246b](https://linux-hardware.org/?probe=b2a212246b) | May 14, 2021 |
| HP            | 8594                        | Desktop     | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 829A                        | Mini pc     | [c326081d7d](https://linux-hardware.org/?probe=c326081d7d) | May 14, 2021 |
| HP            | 1825                        | Desktop     | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| ASUSTek       | U35JC                       | Notebook    | [29ea6520a1](https://linux-hardware.org/?probe=29ea6520a1) | May 08, 2021 |
| Lenovo        | ThinkPad X200 7459ZEJ       | Notebook    | [a4f7ad5736](https://linux-hardware.org/?probe=a4f7ad5736) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a9e3962fe5](https://linux-hardware.org/?probe=a9e3962fe5) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a862c9d728](https://linux-hardware.org/?probe=a862c9d728) | May 07, 2021 |
| Lenovo        | 01DC328                     | Server      | [3510dd7b10](https://linux-hardware.org/?probe=3510dd7b10) | May 05, 2021 |
| HP            | 8591                        | Desktop     | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| Lenovo        | 01GR174                     | Server      | [63ec4551f5](https://linux-hardware.org/?probe=63ec4551f5) | Apr 26, 2021 |
| Lenovo        | 01GR174                     | Server      | [c68b7991a5](https://linux-hardware.org/?probe=c68b7991a5) | Apr 26, 2021 |
| HP            | 213D A01                    | Desktop     | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| Hyve          | HS-9216Lite2 5411C405005... | Server      | [20edfbf60b](https://linux-hardware.org/?probe=20edfbf60b) | Apr 06, 2021 |
| Gigabyte      | EP43-DS3                    | Desktop     | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | Desktop     | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | Desktop     | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | Desktop     | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| MiTAC         | PD10BI PD10BI-702           | Desktop     | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | Desktop     | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [72df2af331](https://linux-hardware.org/?probe=72df2af331) | Mar 16, 2021 |
| HP            | 871C                        | All in one  | [2f7fd6200f](https://linux-hardware.org/?probe=2f7fd6200f) | Mar 10, 2021 |
| HP            | 871C                        | All in one  | [7cbfb86cef](https://linux-hardware.org/?probe=7cbfb86cef) | Mar 10, 2021 |
| Dell          | Latitude E7250              | Notebook    | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| HUAWEI        | BC82AMDDA V200R002C00       | Server      | [63bdabb5a4](https://linux-hardware.org/?probe=63bdabb5a4) | Feb 26, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | Desktop     | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| HP            | 81C6 MVB 0C                 | Server      | [9d6e46eca9](https://linux-hardware.org/?probe=9d6e46eca9) | Feb 23, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| HP            | ProBook 6560b               | Notebook    | [57004cab16](https://linux-hardware.org/?probe=57004cab16) | Feb 17, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | Desktop     | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| Intel         | S5000PAL0 FRU Ver           | Server      | [390f15b7f9](https://linux-hardware.org/?probe=390f15b7f9) | Feb 03, 2021 |
| HP            | 8755                        | Mini pc     | [334abf8c53](https://linux-hardware.org/?probe=334abf8c53) | Feb 02, 2021 |
| Lenovo        | ThinkPad T520 4243Y1N       | Notebook    | [66b47b2f1e](https://linux-hardware.org/?probe=66b47b2f1e) | Jan 20, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Dell          | 0HHV7N A00                  | Desktop     | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| Intel         | S1200RP_SE G62252-405       | Server      | [1eaaae85a8](https://linux-hardware.org/?probe=1eaaae85a8) | Jan 04, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| Intel         | DQ67OW AAG12528-309         | Desktop     | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [a06266ed7f](https://linux-hardware.org/?probe=a06266ed7f) | Dec 17, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| Gigabyte      | D525TUD                     | Desktop     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| Toshiba       | Satellite A135              | Notebook    | [310ddb721f](https://linux-hardware.org/?probe=310ddb721f) | Nov 20, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | Notebook    | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [ed3c250112](https://linux-hardware.org/?probe=ed3c250112) | Nov 03, 2020 |
| Dell          | Latitude E6440              | Notebook    | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [97a2b45d12](https://linux-hardware.org/?probe=97a2b45d12) | Oct 21, 2020 |
| Dell          | Latitude E6410              | Notebook    | [926bbbdaf2](https://linux-hardware.org/?probe=926bbbdaf2) | Oct 18, 2020 |
| Dell          | 01NP3N A00                  | Desktop     | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| Lenovo        | G500s 20245                 | Notebook    | [8a975cb577](https://linux-hardware.org/?probe=8a975cb577) | Oct 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a36dab9e9b](https://linux-hardware.org/?probe=a36dab9e9b) | Oct 06, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 0AECh D                     | Desktop     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| HP            | ProLiant DL165 G7           | Server      | [91ad975174](https://linux-hardware.org/?probe=91ad975174) | Sep 14, 2020 |
| AEWIN         | SCB-1711A                   | Desktop     | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [233a83b315](https://linux-hardware.org/?probe=233a83b315) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [fcb2182f02](https://linux-hardware.org/?probe=fcb2182f02) | Sep 08, 2020 |
| Unknown       | 34AS1                       | Notebook    | [cc188d0f25](https://linux-hardware.org/?probe=cc188d0f25) | Sep 08, 2020 |
| Unknown       | 34AS1                       | Notebook    | [0ab59553ea](https://linux-hardware.org/?probe=0ab59553ea) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [751df6a75b](https://linux-hardware.org/?probe=751df6a75b) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [14680221b6](https://linux-hardware.org/?probe=14680221b6) | Sep 07, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [8fdba744ec](https://linux-hardware.org/?probe=8fdba744ec) | Sep 03, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [d7700d73c4](https://linux-hardware.org/?probe=d7700d73c4) | Sep 03, 2020 |
| Zenith        | Orion                       | Desktop     | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| Supermicro    | X8DT3                       | Server      | [c3337aa815](https://linux-hardware.org/?probe=c3337aa815) | Aug 24, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| Dell          | 08HPGT A02                  | Desktop     | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [001888ed9c](https://linux-hardware.org/?probe=001888ed9c) | Aug 02, 2020 |
| Dell          | 0W23H8 A00                  | Server      | [e752263e49](https://linux-hardware.org/?probe=e752263e49) | Jul 27, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| HP            | 0AECh D                     | Desktop     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| HP            | 1589                        | Desktop     | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ce6e9cb36](https://linux-hardware.org/?probe=8ce6e9cb36) | Jul 10, 2020 |
| HP            | Falco                       | Notebook    | [26ace050f7](https://linux-hardware.org/?probe=26ace050f7) | Jul 07, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| Intel         | H81C                        | Desktop     | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Dell          | 0PYVT1 A03                  | Server      | [b7f3606e31](https://linux-hardware.org/?probe=b7f3606e31) | Jun 30, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [670706063d](https://linux-hardware.org/?probe=670706063d) | Jun 25, 2020 |
| Gigabyte      | P85-D3                      | Desktop     | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [bdaf8406b2](https://linux-hardware.org/?probe=bdaf8406b2) | Jun 22, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f2bfe6bfb3](https://linux-hardware.org/?probe=f2bfe6bfb3) | Jun 22, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [b5360affff](https://linux-hardware.org/?probe=b5360affff) | Jun 18, 2020 |
| Supermicro    | X10DRG-H                    | Desktop     | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| IBM           | 00W2263                     | Server      | [fc0558920d](https://linux-hardware.org/?probe=fc0558920d) | Jun 01, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8f5cbe37da](https://linux-hardware.org/?probe=8f5cbe37da) | May 26, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [396660cc0e](https://linux-hardware.org/?probe=396660cc0e) | May 26, 2020 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| IBM           | I/O Port                    | Server      | [7c109612b9](https://linux-hardware.org/?probe=7c109612b9) | May 20, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| ASUSTek       | CM1740                      | Desktop     | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| Dell          | Latitude E6220              | Notebook    | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | Notebook    | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | Notebook    | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0606d60ddb](https://linux-hardware.org/?probe=0606d60ddb) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [c4f288077d](https://linux-hardware.org/?probe=c4f288077d) | Apr 29, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Supermicro    | H12SSW-NT                   | Server      | [7027370293](https://linux-hardware.org/?probe=7027370293) | Apr 27, 2020 |
| Supermicro    | X10SDE-DF                   | Desktop     | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | Desktop     | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| Sony          | VGN-N19VP_B                 | Notebook    | [a2e6c99940](https://linux-hardware.org/?probe=a2e6c99940) | Apr 20, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASRock        | X399 Professional Gaming    | Desktop     | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [2918602e15](https://linux-hardware.org/?probe=2918602e15) | Mar 12, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [8376f889c2](https://linux-hardware.org/?probe=8376f889c2) | Mar 12, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| Dell          | 0FRVY0 A06                  | Server      | [40545e3bb0](https://linux-hardware.org/?probe=40545e3bb0) | Feb 21, 2020 |
| Dell          | 0CNCJW A05                  | Server      | [c436f9e67a](https://linux-hardware.org/?probe=c436f9e67a) | Feb 21, 2020 |
| Dell          | 0CNCJW A05                  | Server      | [0b376dd32a](https://linux-hardware.org/?probe=0b376dd32a) | Feb 21, 2020 |
| HP            | ZBook 17                    | Notebook    | [5937f48c97](https://linux-hardware.org/?probe=5937f48c97) | Feb 13, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| Sony          | VPCSB19GG                   | Notebook    | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| HP            | 18E4                        | Desktop     | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| Dell          | 081N4V A01                  | Server      | [9a09d720c8](https://linux-hardware.org/?probe=9a09d720c8) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| HP            | EliteBook x360 1040 G6      | Notebook    | [7d1585f3cd](https://linux-hardware.org/?probe=7d1585f3cd) | Dec 28, 2019 |
| AIC           | LIBRA                       | Server      | [43ee2001e1](https://linux-hardware.org/?probe=43ee2001e1) | Dec 17, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e795735d5b](https://linux-hardware.org/?probe=e795735d5b) | Dec 14, 2019 |
| Dell          | 0VRJCG A05                  | Server      | [0fc3f83656](https://linux-hardware.org/?probe=0fc3f83656) | Dec 14, 2019 |
| HP            | 0A98h                       | Desktop     | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [02eca27578](https://linux-hardware.org/?probe=02eca27578) | Dec 05, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| Dell          | System XPS L702X            | Notebook    | [ba096189bc](https://linux-hardware.org/?probe=ba096189bc) | Dec 03, 2019 |
| MSI           | GL63 8SD                    | Notebook    | [3cef0087aa](https://linux-hardware.org/?probe=3cef0087aa) | Dec 01, 2019 |
| Dell          | 09KPNV A01                  | Desktop     | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| Dell          | Vostro 5568                 | Notebook    | [a0b3e4d70f](https://linux-hardware.org/?probe=a0b3e4d70f) | Oct 16, 2019 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [aa1be9cbec](https://linux-hardware.org/?probe=aa1be9cbec) | Oct 15, 2019 |
| ECS           | H55H-M                      | Desktop     | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | Desktop     | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [cf99aad395](https://linux-hardware.org/?probe=cf99aad395) | Sep 16, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [de7268071a](https://linux-hardware.org/?probe=de7268071a) | Sep 16, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [550719b1d2](https://linux-hardware.org/?probe=550719b1d2) | Sep 16, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [05d00cc5d7](https://linux-hardware.org/?probe=05d00cc5d7) | Sep 09, 2019 |
| Supermicro    | X8DTL                       | Server      | [f94537400b](https://linux-hardware.org/?probe=f94537400b) | Sep 08, 2019 |
| Gigabyte      | 970A-D3P                    | Desktop     | [6e3666d8c9](https://linux-hardware.org/?probe=6e3666d8c9) | Sep 04, 2019 |
| MSI           | GP62MVR 7RFX                | Notebook    | [5a21834bbd](https://linux-hardware.org/?probe=5a21834bbd) | Sep 01, 2019 |
| Notebook      | WA50SRQ                     | Notebook    | [fd99d2b5e2](https://linux-hardware.org/?probe=fd99d2b5e2) | Aug 09, 2019 |
| AMI           | Cherry Trail CR             | Desktop     | [fe652a02c9](https://linux-hardware.org/?probe=fe652a02c9) | Jul 25, 2019 |
| Dell          | 09KPNV A00                  | Desktop     | [a72c60b73b](https://linux-hardware.org/?probe=a72c60b73b) | Jul 24, 2019 |
| Supermicro    | X8DTL                       | Server      | [e6f0f25fea](https://linux-hardware.org/?probe=e6f0f25fea) | Jul 22, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [b2fac79afd](https://linux-hardware.org/?probe=b2fac79afd) | Jun 27, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [44eb4c1fed](https://linux-hardware.org/?probe=44eb4c1fed) | Jun 25, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [4bb11d6dc0](https://linux-hardware.org/?probe=4bb11d6dc0) | Jun 07, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [3fb7cc0574](https://linux-hardware.org/?probe=3fb7cc0574) | Jun 07, 2019 |
| AAEON         | MF-001 V1.0                 | Desktop     | [19f89f5d4e](https://linux-hardware.org/?probe=19f89f5d4e) | Jun 05, 2019 |
| HP            | 8054                        | Desktop     | [8409fbc1c6](https://linux-hardware.org/?probe=8409fbc1c6) | May 28, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [8418bef88a](https://linux-hardware.org/?probe=8418bef88a) | May 15, 2019 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [24dd606150](https://linux-hardware.org/?probe=24dd606150) | May 13, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [17bf7a3cbc](https://linux-hardware.org/?probe=17bf7a3cbc) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [57fc9bdf47](https://linux-hardware.org/?probe=57fc9bdf47) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [351f393121](https://linux-hardware.org/?probe=351f393121) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [b3519b05fc](https://linux-hardware.org/?probe=b3519b05fc) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [c6069f57f1](https://linux-hardware.org/?probe=c6069f57f1) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [6c1c564ab7](https://linux-hardware.org/?probe=6c1c564ab7) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [5a96f790b1](https://linux-hardware.org/?probe=5a96f790b1) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [a57a14dcc6](https://linux-hardware.org/?probe=a57a14dcc6) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [f55ae15514](https://linux-hardware.org/?probe=f55ae15514) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [e41c677045](https://linux-hardware.org/?probe=e41c677045) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [add4ffbbb0](https://linux-hardware.org/?probe=add4ffbbb0) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [7b74a423d0](https://linux-hardware.org/?probe=7b74a423d0) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [143a54d4b9](https://linux-hardware.org/?probe=143a54d4b9) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [e31de989f7](https://linux-hardware.org/?probe=e31de989f7) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [7d87dd2d1c](https://linux-hardware.org/?probe=7d87dd2d1c) | May 01, 2019 |
| Supermicro    | X10DRT-P                    | Server      | [6c96e4a591](https://linux-hardware.org/?probe=6c96e4a591) | May 01, 2019 |
| Supermicro    | X10DRT-P                    | Server      | [cc949d61be](https://linux-hardware.org/?probe=cc949d61be) | May 01, 2019 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Dell          | Precision M4600             | Notebook    | [9b9a3a238d](https://linux-hardware.org/?probe=9b9a3a238d) | Apr 14, 2019 |
| Dell          | Vostro 5470                 | Notebook    | [e106741644](https://linux-hardware.org/?probe=e106741644) | Apr 10, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [58607accae](https://linux-hardware.org/?probe=58607accae) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [5e5b4e25a0](https://linux-hardware.org/?probe=5e5b4e25a0) | Apr 08, 2019 |
| Dell          | 09T7VV A02                  | Server      | [3a05f2f446](https://linux-hardware.org/?probe=3a05f2f446) | Apr 05, 2019 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [97355011d7](https://linux-hardware.org/?probe=97355011d7) | Apr 05, 2019 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f8301ffe57](https://linux-hardware.org/?probe=f8301ffe57) | Mar 26, 2019 |
| ASRock        | Z87 Extreme6                | Desktop     | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 81C5 MVB                    | Desktop     | [46ea2e591e](https://linux-hardware.org/?probe=46ea2e591e) | Mar 18, 2019 |
| MSI           | X299 RAIDER                 | Desktop     | [f06f57dde9](https://linux-hardware.org/?probe=f06f57dde9) | Mar 07, 2019 |
| Lenovo        | 4030                        | Desktop     | [10455104fd](https://linux-hardware.org/?probe=10455104fd) | Mar 01, 2019 |
| IBM           | 00W2444 08                  | Server      | [b55f7ae6f3](https://linux-hardware.org/?probe=b55f7ae6f3) | Feb 20, 2019 |
| IBM           | 00W2444 08                  | Server      | [1acfafdc9e](https://linux-hardware.org/?probe=1acfafdc9e) | Feb 20, 2019 |
| ASUSTek       | X540SC                      | Notebook    | [f513215ec6](https://linux-hardware.org/?probe=f513215ec6) | Jan 09, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9c8b01fc94](https://linux-hardware.org/?probe=9c8b01fc94) | Dec 22, 2018 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3b0d00f6c9](https://linux-hardware.org/?probe=3b0d00f6c9) | Dec 22, 2018 |
| Lenovo        | ThinkPad T440p 20AWS27B0... | Notebook    | [000dae069a](https://linux-hardware.org/?probe=000dae069a) | Oct 31, 2018 |
| Dell          | 0CD6TV A01                  | Desktop     | [7f702ee88f](https://linux-hardware.org/?probe=7f702ee88f) | Oct 29, 2018 |
| Dell          | 0CD6TV A01                  | Desktop     | [46e3d4f4d9](https://linux-hardware.org/?probe=46e3d4f4d9) | Oct 29, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | Notebook    | [6b8015f1e2](https://linux-hardware.org/?probe=6b8015f1e2) | Oct 26, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | Notebook    | [c834cadf29](https://linux-hardware.org/?probe=c834cadf29) | Oct 26, 2018 |
| Supermicro    | X10SRi-FB                   | Server      | [eee6327556](https://linux-hardware.org/?probe=eee6327556) | Jul 11, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [73b1be59e6](https://linux-hardware.org/?probe=73b1be59e6) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [7b5a78d2db](https://linux-hardware.org/?probe=7b5a78d2db) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [6d7db21504](https://linux-hardware.org/?probe=6d7db21504) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [7e6e74a11d](https://linux-hardware.org/?probe=7e6e74a11d) | May 03, 2018 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |
| Dell          | 0CX0R0 A01                  | Server      | [3f4700f256](https://linux-hardware.org/?probe=3f4700f256) | Jan 29, 2018 |
| HP            | EliteBook 2740p             | Notebook    | [1b72dbb418](https://linux-hardware.org/?probe=1b72dbb418) | Sep 17, 2017 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 3.10.0-862.14.4.el7.x86_64  | 17        | 5.18%   |
| 3.10.0-1160.25.1.el7.x86_64 | 13        | 3.96%   |
| 3.10.0-1160.45.1.el7.x86_64 | 12        | 3.66%   |
| 3.10.0-1160.31.1.el7.x86_64 | 12        | 3.66%   |
| 3.10.0-1062.12.1.el7.x86_64 | 12        | 3.66%   |
| 3.10.0-957.10.1.el7.x86_64  | 10        | 3.05%   |
| 3.10.0-1160.36.2.el7.x86_64 | 10        | 3.05%   |
| 3.10.0-1160.66.1.el7.x86_64 | 9         | 2.74%   |
| 3.10.0-1160.15.2.el7.x86_64 | 9         | 2.74%   |
| 3.10.0-1127.19.1.el7.x86_64 | 9         | 2.74%   |
| 3.10.0-957.1.3.el7.x86_64   | 8         | 2.44%   |
| 3.10.0-1160.76.1.el7.x86_64 | 8         | 2.44%   |
| 3.10.0-1127.el7.x86_64      | 8         | 2.44%   |
| 3.10.0-957.27.2.el7.x86_64  | 7         | 2.13%   |
| 3.10.0-1062.el7.x86_64      | 7         | 2.13%   |
| 3.10.0-957.5.1.el7.x86_64   | 6         | 1.83%   |
| 3.10.0-1160.49.1.el7.x86_64 | 6         | 1.83%   |
| 3.10.0-1127.13.1.el7.x86_64 | 6         | 1.83%   |
| 3.10.0-1127.10.1.el7.x86_64 | 6         | 1.83%   |
| 3.10.0-1062.9.1.el7.x86_64  | 6         | 1.83%   |
| 3.10.0-1062.18.1.el7.x86_64 | 6         | 1.83%   |
| 3.10.0-1160.el7.x86_64      | 5         | 1.52%   |
| 3.10.0-1160.6.1.el7.x86_64  | 5         | 1.52%   |
| 3.10.0-1160.11.1.el7.x86_64 | 5         | 1.52%   |
| 3.10.0-957.el7.x86_64       | 4         | 1.22%   |
| 3.10.0-1160.80.1.el7.x86_64 | 4         | 1.22%   |
| 3.10.0-1160.62.1.el7.x86_64 | 4         | 1.22%   |
| 3.10.0-1160.59.1.el7.x86_64 | 4         | 1.22%   |
| 3.10.0-1160.53.1.el7.x86_64 | 4         | 1.22%   |
| 3.10.0-1160.21.1.el7.x86_64 | 4         | 1.22%   |
| 5.4.118-1.el7.elrepo.x86_64 | 3         | 0.91%   |
| 3.10.0-957.12.2.el7.x86_64  | 3         | 0.91%   |
| 3.10.0-1160.24.1.el7.x86_64 | 3         | 0.91%   |
| 3.10.0-1127.8.2.el7.x86_64  | 3         | 0.91%   |
| 3.10.0-1062.4.1.el7.x86_64  | 3         | 0.91%   |
| 3.10.0-1062.1.2.el7.x86_64  | 3         | 0.91%   |
| 3.10.0-1062.1.1.el7.x86_64  | 3         | 0.91%   |
| 3.10.0-957.21.3.el7.x86_64  | 2         | 0.61%   |
| 3.10.0-957.12.1.el7.x86_64  | 2         | 0.61%   |
| 3.10.0-862.el7.x86_64       | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 3.10.0   | 270       | 87.66%  |
| 5.4.118  | 3         | 0.97%   |
| 5.8.13   | 1         | 0.32%   |
| 5.8.0    | 1         | 0.32%   |
| 5.7.7    | 1         | 0.32%   |
| 5.7.10   | 1         | 0.32%   |
| 5.6.8    | 1         | 0.32%   |
| 5.6.10   | 1         | 0.32%   |
| 5.5.0    | 1         | 0.32%   |
| 5.4.96   | 1         | 0.32%   |
| 5.4.6    | 1         | 0.32%   |
| 5.4.225  | 1         | 0.32%   |
| 5.4.158  | 1         | 0.32%   |
| 5.4.142  | 1         | 0.32%   |
| 5.4.125  | 1         | 0.32%   |
| 5.4.121  | 1         | 0.32%   |
| 5.4.119  | 1         | 0.32%   |
| 5.4.113  | 1         | 0.32%   |
| 5.3.11   | 1         | 0.32%   |
| 5.2.13   | 1         | 0.32%   |
| 5.2.1    | 1         | 0.32%   |
| 5.18.13  | 1         | 0.32%   |
| 5.11.0   | 1         | 0.32%   |
| 5.10.75  | 1         | 0.32%   |
| 5.1.19   | 1         | 0.32%   |
| 4.9.188  | 1         | 0.32%   |
| 4.9.182  | 1         | 0.32%   |
| 4.9.180  | 1         | 0.32%   |
| 4.9.179  | 1         | 0.32%   |
| 4.4.241  | 1         | 0.32%   |
| 4.20.8   | 1         | 0.32%   |
| 4.20.4   | 1         | 0.32%   |
| 4.19.8   | 1         | 0.32%   |
| 4.19.187 | 1         | 0.32%   |
| 4.18.6   | 1         | 0.32%   |
| 4.18.0   | 1         | 0.32%   |
| 4.14.35  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10    | 270       | 88.24%  |
| 5.4     | 11        | 3.59%   |
| 4.9     | 4         | 1.31%   |
| 5.8     | 2         | 0.65%   |
| 5.7     | 2         | 0.65%   |
| 5.6     | 2         | 0.65%   |
| 4.20    | 2         | 0.65%   |
| 4.19    | 2         | 0.65%   |
| 4.18    | 2         | 0.65%   |
| 5.5     | 1         | 0.33%   |
| 5.3     | 1         | 0.33%   |
| 5.2     | 1         | 0.33%   |
| 5.18    | 1         | 0.33%   |
| 5.11    | 1         | 0.33%   |
| 5.10    | 1         | 0.33%   |
| 5.1     | 1         | 0.33%   |
| 4.4     | 1         | 0.33%   |
| 4.14    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 301       | 98.69%  |
| i686    | 3         | 0.98%   |
| aarch64 | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 130       | 42.35%  |
| GNOME         | 91        | 29.64%  |
| KDE4          | 35        | 11.4%   |
| GNOME Classic | 29        | 9.45%   |
| MATE          | 11        | 3.58%   |
| Cinnamon      | 7         | 2.28%   |
| XFCE          | 2         | 0.65%   |
| Xpra          | 1         | 0.33%   |
| X-Cinnamon    | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 231       | 75.74%  |
| Unknown | 73        | 23.93%  |
| Web     | 1         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 151       | 49.19%  |
| GDM     | 143       | 46.58%  |
| LightDM | 9         | 2.93%   |
| TDM     | 3         | 0.98%   |
| SDDM    | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 120       | 38.96%  |
| Unknown     | 80        | 25.97%  |
| C           | 18        | 5.84%   |
| ru_RU       | 17        | 5.52%   |
| fr_FR       | 11        | 3.57%   |
| en_GB       | 9         | 2.92%   |
| de_AT       | 7         | 2.27%   |
| pt_BR       | 6         | 1.95%   |
| zh_CN       | 5         | 1.62%   |
| en_CA       | 5         | 1.62%   |
| en_IN       | 4         | 1.3%    |
| en_AU       | 4         | 1.3%    |
| de_DE       | 4         | 1.3%    |
| pl_PL       | 3         | 0.97%   |
| en_US.utf-8 | 3         | 0.97%   |
| es_ES       | 2         | 0.65%   |
| pt_PT       | 1         | 0.32%   |
| ko_KR       | 1         | 0.32%   |
| ja_JP       | 1         | 0.32%   |
| fr_CA       | 1         | 0.32%   |
| fi_FI       | 1         | 0.32%   |
| es_MX       | 1         | 0.32%   |
| es_AR       | 1         | 0.32%   |
| en_ZA       | 1         | 0.32%   |
| en_SG       | 1         | 0.32%   |
| cs_CZ       | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 174       | 56.86%  |
| EFI  | 132       | 43.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 209       | 68.3%   |
| Ext4    | 80        | 26.14%  |
| Unknown | 13        | 4.25%   |
| Ext3    | 2         | 0.65%   |
| Overlay | 1         | 0.33%   |
| Ext2    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 165       | 53.57%  |
| MBR     | 104       | 33.77%  |
| Unknown | 39        | 12.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 250       | 81.43%  |
| Yes       | 57        | 18.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 268       | 87.58%  |
| Yes       | 38        | 12.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 69        | 22.62%  |
| Hewlett-Packard     | 52        | 17.05%  |
| Supermicro          | 31        | 10.16%  |
| ASUSTek Computer    | 31        | 10.16%  |
| Lenovo              | 27        | 8.85%   |
| Gigabyte Technology | 20        | 6.56%   |
| Intel               | 14        | 4.59%   |
| MSI                 | 7         | 2.3%    |
| ASRock              | 7         | 2.3%    |
| Unknown             | 5         | 1.64%   |
| IBM                 | 3         | 0.98%   |
| ASRockRack          | 3         | 0.98%   |
| AMI                 | 3         | 0.98%   |
| Toshiba             | 2         | 0.66%   |
| Sun Microsystems    | 2         | 0.66%   |
| Sony                | 2         | 0.66%   |
| MiTAC               | 2         | 0.66%   |
| Fujitsu             | 2         | 0.66%   |
| ECS                 | 2         | 0.66%   |
| Acer                | 2         | 0.66%   |
| Zenith              | 1         | 0.33%   |
| Samsung Electronics | 1         | 0.33%   |
| PCChips             | 1         | 0.33%   |
| Panasonic           | 1         | 0.33%   |
| Notebook            | 1         | 0.33%   |
| NORCO               | 1         | 0.33%   |
| LG Electronics      | 1         | 0.33%   |
| Hyve                | 1         | 0.33%   |
| HUAWEI              | 1         | 0.33%   |
| Huanan              | 1         | 0.33%   |
| HONOR               | 1         | 0.33%   |
| Foxconn             | 1         | 0.33%   |
| eMachines           | 1         | 0.33%   |
| Cisco Systems       | 1         | 0.33%   |
| Apple               | 1         | 0.33%   |
| AIC                 | 1         | 0.33%   |
| AEWIN               | 1         | 0.33%   |
| ABIT                | 1         | 0.33%   |
| AAEON               | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Supermicro Super Server                               | 18        | 5.9%    |
| Dell OptiPlex 7040                                    | 8         | 2.62%   |
| Dell OptiPlex 9020                                    | 7         | 2.3%    |
| Unknown                                               | 5         | 1.64%   |
| Supermicro X8DTN+-F                                   | 4         | 1.31%   |
| ASUS All Series                                       | 4         | 1.31%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]-               | 3         | 0.98%   |
| HP ProDesk 400 G7 Microtower PC                       | 3         | 0.98%   |
| HP EliteDesk 800 G6 Desktop Mini PC                   | 3         | 0.98%   |
| HP Compaq Elite 8300 SFF                              | 3         | 0.98%   |
| Dell Precision WorkStation T3500                      | 3         | 0.98%   |
| ASRockRack E3C242D4U2-2T                              | 3         | 0.98%   |
| Supermicro SYS-1028TP-DC1R                            | 2         | 0.66%   |
| Lenovo ThinkSystem SR530 -[7X08CTO1WW]-               | 2         | 0.66%   |
| Lenovo System x3650 M5: -[8871AC1]-                   | 2         | 0.66%   |
| Intel S1200SP                                         | 2         | 0.66%   |
| HP Z800 Workstation                                   | 2         | 0.66%   |
| HP Z420 Workstation                                   | 2         | 0.66%   |
| Gigabyte GA-78LMT-USB3                                | 2         | 0.66%   |
| Fujitsu D3401-H1                                      | 2         | 0.66%   |
| Dell PowerEdge R630                                   | 2         | 0.66%   |
| Dell Inspiron N4050                                   | 2         | 0.66%   |
| Zenith Orion                                          | 1         | 0.33%   |
| Toshiba Satellite Radius 12 P20W-C-106                | 1         | 0.33%   |
| Toshiba Satellite A135                                | 1         | 0.33%   |
| Supermicro X8DTL                                      | 1         | 0.33%   |
| Supermicro X8DT3                                      | 1         | 0.33%   |
| Supermicro SYS-E200-8D                                | 1         | 0.33%   |
| Supermicro SYS-6018R-WTR                              | 1         | 0.33%   |
| Supermicro SYS-5038MD-H24TRF-OS012                    | 1         | 0.33%   |
| Supermicro SYS-1028GR-TR                              | 1         | 0.33%   |
| Supermicro AS -1014S-WTRT                             | 1         | 0.33%   |
| Sun Microsystems Sun Fire X2270                       | 1         | 0.33%   |
| Sun Microsystems Sun Fire X2200 M2                    | 1         | 0.33%   |
| Sony VPCSB19GG                                        | 1         | 0.33%   |
| Sony VGN-N19VP_B                                      | 1         | 0.33%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.33%   |
| PCChips P49G                                          | 1         | 0.33%   |
| Panasonic CF-19ADNAXDY                                | 1         | 0.33%   |
| Notebook WA50SRQ                                      | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell OptiPlex              | 22        | 7.21%   |
| Supermicro Super           | 18        | 5.9%    |
| Dell Precision             | 14        | 4.59%   |
| Lenovo ThinkPad            | 11        | 3.61%   |
| Dell PowerEdge             | 11        | 3.61%   |
| HP EliteDesk               | 10        | 3.28%   |
| Dell Inspiron              | 8         | 2.62%   |
| Lenovo ThinkSystem         | 7         | 2.3%    |
| Dell Latitude              | 6         | 1.97%   |
| HP EliteBook               | 5         | 1.64%   |
| HP Compaq                  | 5         | 1.64%   |
| Dell Vostro                | 5         | 1.64%   |
| ASUS PRIME                 | 5         | 1.64%   |
| Unknown                    | 5         | 1.64%   |
| Supermicro X8DTN+-F        | 4         | 1.31%   |
| HP ProLiant                | 4         | 1.31%   |
| ASUS All                   | 4         | 1.31%   |
| HP ProDesk                 | 3         | 0.98%   |
| HP Pavilion                | 3         | 0.98%   |
| ASRockRack E3C242D4U2-2T   | 3         | 0.98%   |
| Toshiba Satellite          | 2         | 0.66%   |
| Supermicro SYS-1028TP-DC1R | 2         | 0.66%   |
| Sun Microsystems Sun       | 2         | 0.66%   |
| Lenovo ThinkCentre         | 2         | 0.66%   |
| Lenovo System              | 2         | 0.66%   |
| Intel S1200SP              | 2         | 0.66%   |
| IBM System                 | 2         | 0.66%   |
| HP Z800                    | 2         | 0.66%   |
| HP Z420                    | 2         | 0.66%   |
| HP Z2                      | 2         | 0.66%   |
| HP ProBook                 | 2         | 0.66%   |
| Gigabyte GA-78LMT-USB3     | 2         | 0.66%   |
| Gigabyte B360              | 2         | 0.66%   |
| Fujitsu D3401-H1           | 2         | 0.66%   |
| Dell XPS                   | 2         | 0.66%   |
| ASUS ROG                   | 2         | 0.66%   |
| ASUS M5A78L-M              | 2         | 0.66%   |
| Acer Aspire                | 2         | 0.66%   |
| Zenith Orion               | 1         | 0.33%   |
| Supermicro X8DTL           | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 32        | 10.49%  |
| 2017    | 31        | 10.16%  |
| 2018    | 30        | 9.84%   |
| 2016    | 25        | 8.2%    |
| 2011    | 25        | 8.2%    |
| 2014    | 23        | 7.54%   |
| 2010    | 23        | 7.54%   |
| 2013    | 22        | 7.21%   |
| 2012    | 18        | 5.9%    |
| 2021    | 16        | 5.25%   |
| 2020    | 16        | 5.25%   |
| 2015    | 16        | 5.25%   |
| 2008    | 11        | 3.61%   |
| 2009    | 5         | 1.64%   |
| 2007    | 4         | 1.31%   |
| 2006    | 3         | 0.98%   |
| 2022    | 2         | 0.66%   |
| Unknown | 2         | 0.66%   |
| 2001    | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 155       | 50.82%  |
| Server      | 66        | 21.64%  |
| Notebook    | 66        | 21.64%  |
| Mini pc     | 15        | 4.92%   |
| Convertible | 2         | 0.66%   |
| All in one  | 1         | 0.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 296       | 97.05%  |
| Enabled  | 9         | 2.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 303       | 99.34%  |
| Yes  | 2         | 0.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 78        | 25.57%  |
| 32.01-64.0      | 50        | 16.39%  |
| 16.01-24.0      | 38        | 12.46%  |
| 64.01-256.0     | 37        | 12.13%  |
| More than 256.0 | 29        | 9.51%   |
| 3.01-4.0        | 25        | 8.2%    |
| 8.01-16.0       | 25        | 8.2%    |
| 1.01-2.0        | 13        | 4.26%   |
| 24.01-32.0      | 6         | 1.97%   |
| 0.51-1.0        | 3         | 0.98%   |
| 2.01-3.0        | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 68        | 21.45%  |
| 2.01-3.0        | 57        | 17.98%  |
| 4.01-8.0        | 47        | 14.83%  |
| 0.51-1.0        | 44        | 13.88%  |
| 3.01-4.0        | 32        | 10.09%  |
| 8.01-16.0       | 19        | 5.99%   |
| 64.01-256.0     | 16        | 5.05%   |
| 32.01-64.0      | 12        | 3.79%   |
| 0.01-0.5        | 12        | 3.79%   |
| 24.01-32.0      | 4         | 1.26%   |
| 16.01-24.0      | 4         | 1.26%   |
| More than 256.0 | 2         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 134       | 42.81%  |
| 2       | 66        | 21.09%  |
| 3       | 34        | 10.86%  |
| Unknown | 19        | 6.07%   |
| 4       | 14        | 4.47%   |
| 5       | 11        | 3.51%   |
| 6       | 8         | 2.56%   |
| 0       | 6         | 1.92%   |
| 7       | 3         | 0.96%   |
| 15      | 2         | 0.64%   |
| 10      | 2         | 0.64%   |
| 9       | 2         | 0.64%   |
| 8       | 2         | 0.64%   |
| 209     | 1         | 0.32%   |
| 71      | 1         | 0.32%   |
| 68      | 1         | 0.32%   |
| 27      | 1         | 0.32%   |
| 19      | 1         | 0.32%   |
| 18      | 1         | 0.32%   |
| 17      | 1         | 0.32%   |
| 13      | 1         | 0.32%   |
| 12      | 1         | 0.32%   |
| 11      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 200       | 65.15%  |
| Yes       | 107       | 34.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 296       | 97.05%  |
| No        | 9         | 2.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 196       | 64.26%  |
| Yes       | 109       | 35.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 224       | 73.44%  |
| Yes       | 81        | 26.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 81        | 26.3%   |
| Russia       | 44        | 14.29%  |
| Germany      | 15        | 4.87%   |
| France       | 15        | 4.87%   |
| Canada       | 14        | 4.55%   |
| Brazil       | 13        | 4.22%   |
| UK           | 11        | 3.57%   |
| China        | 11        | 3.57%   |
| India        | 10        | 3.25%   |
| Switzerland  | 8         | 2.6%    |
| Australia    | 8         | 2.6%    |
| Finland      | 6         | 1.95%   |
| Poland       | 5         | 1.62%   |
| Czechia      | 5         | 1.62%   |
| Belgium      | 5         | 1.62%   |
| Spain        | 4         | 1.3%    |
| South Korea  | 4         | 1.3%    |
| Norway       | 4         | 1.3%    |
| Bulgaria     | 4         | 1.3%    |
| Ukraine      | 3         | 0.97%   |
| Sweden       | 3         | 0.97%   |
| Netherlands  | 3         | 0.97%   |
| Japan        | 3         | 0.97%   |
| Israel       | 3         | 0.97%   |
| Taiwan       | 2         | 0.65%   |
| South Africa | 2         | 0.65%   |
| Pakistan     | 2         | 0.65%   |
| Mexico       | 2         | 0.65%   |
| Vietnam      | 1         | 0.32%   |
| Singapore    | 1         | 0.32%   |
| Romania      | 1         | 0.32%   |
| Portugal     | 1         | 0.32%   |
| Malaysia     | 1         | 0.32%   |
| Kazakhstan   | 1         | 0.32%   |
| Italy        | 1         | 0.32%   |
| Ireland      | 1         | 0.32%   |
| Iran         | 1         | 0.32%   |
| Hong Kong    | 1         | 0.32%   |
| Greece       | 1         | 0.32%   |
| Gabon        | 1         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 20        | 6.31%   |
| Rochester            | 19        | 5.99%   |
| Madison              | 17        | 5.36%   |
| Frankfurt am Main    | 6         | 1.89%   |
| Bern                 | 5         | 1.58%   |
| Sydney               | 4         | 1.26%   |
| St Petersburg        | 4         | 1.26%   |
| Rio de Janeiro       | 4         | 1.26%   |
| Paris                | 4         | 1.26%   |
| London               | 4         | 1.26%   |
| Helsinki             | 4         | 1.26%   |
| Guwahati             | 4         | 1.26%   |
| Alexandria           | 4         | 1.26%   |
| Victoria             | 3         | 0.95%   |
| Vancouver            | 3         | 0.95%   |
| Ufa                  | 3         | 0.95%   |
| Tampa                | 3         | 0.95%   |
| Sofia                | 3         | 0.95%   |
| Prague               | 3         | 0.95%   |
| Montreal             | 3         | 0.95%   |
| Wahroonga            | 2         | 0.63%   |
| Voronezh             | 2         | 0.63%   |
| Vitry-sur-Seine      | 2         | 0.63%   |
| Twistetal            | 2         | 0.63%   |
| Sao Paulo            | 2         | 0.63%   |
| Perm                 | 2         | 0.63%   |
| Oslo                 | 2         | 0.63%   |
| North Bend           | 2         | 0.63%   |
| Newark               | 2         | 0.63%   |
| Leuven               | 2         | 0.63%   |
| Kyiv                 | 2         | 0.63%   |
| Krasnodar            | 2         | 0.63%   |
| Hyderabad            | 2         | 0.63%   |
| Guangzhou            | 2         | 0.63%   |
| Grovedale            | 2         | 0.63%   |
| Brno                 | 2         | 0.63%   |
| Brandon              | 2         | 0.63%   |
| Blanzy-la-Salonnaise | 2         | 0.63%   |
| Beijing              | 2         | 0.63%   |
| Ashburn              | 2         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 83        | 318    | 19.95%  |
| WDC                          | 72        | 348    | 17.31%  |
| Samsung Electronics          | 60        | 136    | 14.42%  |
| Toshiba                      | 38        | 60     | 9.13%   |
| Kingston                     | 24        | 28     | 5.77%   |
| Intel                        | 20        | 42     | 4.81%   |
| Hitachi                      | 19        | 26     | 4.57%   |
| SanDisk                      | 13        | 16     | 3.13%   |
| HGST                         | 11        | 113    | 2.64%   |
| Unknown                      | 8         | 18     | 1.92%   |
| Micron Technology            | 8         | 14     | 1.92%   |
| Hewlett-Packard              | 6         | 31     | 1.44%   |
| SK hynix                     | 5         | 5      | 1.2%    |
| SPCC                         | 4         | 6      | 0.96%   |
| Toshiba America Info Systems | 3         | 4      | 0.72%   |
| OCZ                          | 3         | 6      | 0.72%   |
| A-DATA Technology            | 3         | 4      | 0.72%   |
| Sun                          | 2         | 6      | 0.48%   |
| StoreJet                     | 2         | 2      | 0.48%   |
| NVMe                         | 2         | 2      | 0.48%   |
| LITEONIT                     | 2         | 2      | 0.48%   |
| KingDian                     | 2         | 6      | 0.48%   |
| Fujitsu                      | 2         | 2      | 0.48%   |
| Crucial                      | 2         | 2      | 0.48%   |
| UNIC2                        | 1         | 1      | 0.24%   |
| Transcend                    | 1         | 1      | 0.24%   |
| TAISU                        | 1         | 1      | 0.24%   |
| Smartbuy                     | 1         | 1      | 0.24%   |
| Realtek                      | 1         | 1      | 0.24%   |
| Phison Electronics           | 1         | 2      | 0.24%   |
| OWC                          | 1         | 1      | 0.24%   |
| NORCO                        | 1         | 1      | 0.24%   |
| Micron/Crucial Technology    | 1         | 1      | 0.24%   |
| Maxtor                       | 1         | 1      | 0.24%   |
| Lexar                        | 1         | 2      | 0.24%   |
| Lenovo                       | 1         | 2      | 0.24%   |
| Kingston Technology Company  | 1         | 1      | 0.24%   |
| Kingston Technologies        | 1         | 1      | 0.24%   |
| KingSpec                     | 1         | 1      | 0.24%   |
| GOODRAM                      | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba DT01ACA050 500GB          | 8         | 1.63%   |
| Seagate ST500DM002-1SB10A 500GB   | 6         | 1.22%   |
| Seagate ST1000DM010-2EP102 1TB    | 6         | 1.22%   |
| Samsung SSD 860 EVO 250GB         | 6         | 1.22%   |
| Seagate ST500DM002-1BD142 500GB   | 5         | 1.02%   |
| Kingston SA400S37240G 240GB SSD   | 5         | 1.02%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 4         | 0.82%   |
| Toshiba DT01ACA100 1TB            | 4         | 0.82%   |
| Intel SSDSC2BA200G4 200GB         | 4         | 0.82%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 3         | 0.61%   |
| Seagate ST6000NM0095 6TB          | 3         | 0.61%   |
| Seagate ST6000NM0034 6TB          | 3         | 0.61%   |
| Seagate ST6000NM0014 6TB          | 3         | 0.61%   |
| Seagate ST4000NXCLAR4000 4TB      | 3         | 0.61%   |
| Seagate ST4000NM0023 4TB          | 3         | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB    | 3         | 0.61%   |
| Seagate BUP Slim 2TB              | 3         | 0.61%   |
| Samsung SSD 970 2TB               | 3         | 0.61%   |
| Kingston SV300S37A120G 120GB SSD  | 3         | 0.61%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 2         | 0.41%   |
| WDC WD3200AAKS-75L9A0 320GB       | 2         | 0.41%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2         | 0.41%   |
| WDC WD10EZEX-22MFCA0 1TB          | 2         | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2         | 0.41%   |
| WDC WD1004FBYZ-23YC 1TB           | 2         | 0.41%   |
| Unknown HUH728080ALE601 8TB       | 2         | 0.41%   |
| Toshiba TR200 240GB SSD           | 2         | 0.41%   |
| Toshiba NVMe SSD Drive 256GB      | 2         | 0.41%   |
| Toshiba DT01ACA200 2TB            | 2         | 0.41%   |
| Sun COMSTAR 112GB                 | 2         | 0.41%   |
| StoreJet Transcend 240GB          | 2         | 0.41%   |
| SPCC Solid State Disk 64GB        | 2         | 0.41%   |
| SK hynix SHGS31-500GS-2 500GB SSD | 2         | 0.41%   |
| Seagate ST600MM0026 600GB         | 2         | 0.41%   |
| Seagate ST4000VM000-2AF166 4TB    | 2         | 0.41%   |
| Seagate ST3000NC002-1DY166 3TB    | 2         | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB    | 2         | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB    | 2         | 0.41%   |
| Seagate ST16000NM001G-2KK103 16TB | 2         | 0.41%   |
| Seagate ST1000NX0423 00AJ142 1TB  | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 83        | 317    | 35.78%  |
| WDC                 | 66        | 131    | 28.45%  |
| Toshiba             | 31        | 48     | 13.36%  |
| Hitachi             | 19        | 26     | 8.19%   |
| HGST                | 11        | 66     | 4.74%   |
| Samsung Electronics | 9         | 66     | 3.88%   |
| Hewlett-Packard     | 4         | 28     | 1.72%   |
| Unknown             | 2         | 11     | 0.86%   |
| Sun                 | 2         | 6      | 0.86%   |
| Fujitsu             | 2         | 2      | 0.86%   |
| Maxtor              | 1         | 1      | 0.43%   |
| Lenovo              | 1         | 2      | 0.43%   |
| ASMT                | 1         | 3      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 41     | 23.36%  |
| Kingston            | 23        | 27     | 16.79%  |
| Intel               | 19        | 40     | 13.87%  |
| WDC                 | 7         | 10     | 5.11%   |
| Micron Technology   | 7         | 13     | 5.11%   |
| SanDisk             | 6         | 6      | 4.38%   |
| Toshiba             | 5         | 9      | 3.65%   |
| SK hynix            | 5         | 5      | 3.65%   |
| SPCC                | 4         | 6      | 2.92%   |
| OCZ                 | 3         | 6      | 2.19%   |
| A-DATA Technology   | 3         | 4      | 2.19%   |
| StoreJet            | 2         | 2      | 1.46%   |
| LITEONIT            | 2         | 2      | 1.46%   |
| KingDian            | 2         | 6      | 1.46%   |
| Hewlett-Packard     | 2         | 3      | 1.46%   |
| Crucial             | 2         | 2      | 1.46%   |
| UNIC2               | 1         | 1      | 0.73%   |
| Transcend           | 1         | 1      | 0.73%   |
| TAISU               | 1         | 1      | 0.73%   |
| Smartbuy            | 1         | 1      | 0.73%   |
| Seagate             | 1         | 1      | 0.73%   |
| OWC                 | 1         | 1      | 0.73%   |
| NORCO               | 1         | 1      | 0.73%   |
| Lexar               | 1         | 2      | 0.73%   |
| GOODRAM             | 1         | 1      | 0.73%   |
| GLOWAY              | 1         | 1      | 0.73%   |
| Corsair             | 1         | 1      | 0.73%   |
| ASUSTek Computer    | 1         | 1      | 0.73%   |
| 2.5"                | 1         | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 189       | 707    | 51.78%  |
| SSD     | 123       | 196    | 33.7%   |
| NVMe    | 42        | 60     | 11.51%  |
| MMC     | 7         | 8      | 1.92%   |
| Unknown | 4         | 253    | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 241       | 733    | 77.74%  |
| NVMe | 42        | 59     | 13.55%  |
| SAS  | 20        | 424    | 6.45%   |
| MMC  | 7         | 8      | 2.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 170       | 349    | 49.42%  |
| 0.51-1.0   | 95        | 188    | 27.62%  |
| 1.01-2.0   | 26        | 67     | 7.56%   |
| 3.01-4.0   | 18        | 119    | 5.23%   |
| 4.01-10.0  | 16        | 108    | 4.65%   |
| 2.01-3.0   | 13        | 29     | 3.78%   |
| 10.01-20.0 | 6         | 43     | 1.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 67        | 21.47%  |
| 101-250        | 60        | 19.23%  |
| More than 3000 | 52        | 16.67%  |
| 501-1000       | 42        | 13.46%  |
| 1001-2000      | 27        | 8.65%   |
| 51-100         | 20        | 6.41%   |
| Unknown        | 14        | 4.49%   |
| 21-50          | 13        | 4.17%   |
| 1-20           | 10        | 3.21%   |
| 2001-3000      | 7         | 2.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 119       | 38.39%  |
| 101-250        | 40        | 12.9%   |
| 51-100         | 32        | 10.32%  |
| 251-500        | 27        | 8.71%   |
| 21-50          | 25        | 8.06%   |
| 501-1000       | 22        | 7.1%    |
| More than 3000 | 17        | 5.48%   |
| Unknown        | 14        | 4.52%   |
| 1001-2000      | 9         | 2.9%    |
| 2001-3000      | 4         | 1.29%   |
| 0              | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 2         | 2      | 3.13%   |
| WDC WD5000AVCS-632DY1 500GB                         | 1         | 1      | 1.56%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 1      | 1.56%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1         | 1      | 1.56%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1         | 1      | 1.56%   |
| WDC WD2500HHTZ-04N21V0 250GB                        | 1         | 1      | 1.56%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 1.56%   |
| WDC WD20EARS-00MVWB0 2TB                            | 1         | 2      | 1.56%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 2      | 1.56%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 1.56%   |
| WDC WD10EZEX-60WN4A1 1TB                            | 1         | 1      | 1.56%   |
| WDC WD10EADS-00L5B1 1TB                             | 1         | 1      | 1.56%   |
| WDC WD1001FALS-00J7B1 1TB                           | 1         | 1      | 1.56%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 1.56%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 1.56%   |
| Toshiba MK8032GSX 80GB                              | 1         | 1      | 1.56%   |
| Smartbuy SSD 120GB                                  | 1         | 1      | 1.56%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 1.56%   |
| Seagate ST380211AS 80GB                             | 1         | 1      | 1.56%   |
| Seagate ST380013AS 80GB                             | 1         | 1      | 1.56%   |
| Seagate ST3250620NS 250GB                           | 1         | 2      | 1.56%   |
| Seagate ST3160813AS 160GB                           | 1         | 1      | 1.56%   |
| Seagate ST31000524NS 1TB                            | 1         | 1      | 1.56%   |
| Seagate ST31000340AS 1TB                            | 1         | 1      | 1.56%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1         | 1      | 1.56%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1         | 1      | 1.56%   |
| Seagate ST2000DM001-9YN164 2TB                      | 1         | 1      | 1.56%   |
| Seagate ST1000NX0313 1TB                            | 1         | 1      | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 1.56%   |
| SanDisk SDSSDX240GG25 240GB                         | 1         | 1      | 1.56%   |
| SanDisk SD9SN8W256G1009 256GB SSD                   | 1         | 1      | 1.56%   |
| Samsung Electronics SSD SM871 2.5 7mm 512GB         | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 2      | 1.56%   |
| Samsung Electronics HD154UI 1TB                     | 1         | 1      | 1.56%   |
| Samsung Electronics HD103UI 1TB                     | 1         | 1      | 1.56%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 1.56%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 1.56%   |
| Maxtor 6Y080L0 81GB                                 | 1         | 1      | 1.56%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                      | 1         | 1      | 1.56%   |
| LITEONIT LCT-256M3S 256GB SSD                       | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 14     | 19.05%  |
| Seagate             | 12        | 14     | 19.05%  |
| Intel               | 8         | 21     | 12.7%   |
| Hitachi             | 8         | 8      | 12.7%   |
| Samsung Electronics | 4         | 5      | 6.35%   |
| Toshiba             | 3         | 3      | 4.76%   |
| Kingston            | 3         | 3      | 4.76%   |
| SanDisk             | 2         | 2      | 3.17%   |
| Micron Technology   | 2         | 2      | 3.17%   |
| LITEONIT            | 2         | 2      | 3.17%   |
| Smartbuy            | 1         | 1      | 1.59%   |
| SK hynix            | 1         | 1      | 1.59%   |
| Maxtor              | 1         | 1      | 1.59%   |
| HGST                | 1         | 1      | 1.59%   |
| Hewlett-Packard     | 1         | 1      | 1.59%   |
| Crucial             | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 14     | 30.77%  |
| Seagate             | 12        | 14     | 30.77%  |
| Hitachi             | 8         | 8      | 20.51%  |
| Toshiba             | 2         | 2      | 5.13%   |
| Samsung Electronics | 2         | 2      | 5.13%   |
| Maxtor              | 1         | 1      | 2.56%   |
| HGST                | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 43     | 57.89%  |
| SSD  | 24        | 38     | 42.11%  |

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
| Works    | 206       | 612    | 63%     |
| Detected | 67        | 531    | 20.49%  |
| Malfunc  | 54        | 81     | 16.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 252       | 61.76%  |
| LSI Logic / Symbios Logic        | 34        | 8.33%   |
| AMD                              | 25        | 6.13%   |
| Samsung Electronics              | 22        | 5.39%   |
| Broadcom / LSI                   | 22        | 5.39%   |
| ASMedia Technology               | 10        | 2.45%   |
| SanDisk                          | 8         | 1.96%   |
| Toshiba America Info Systems     | 5         | 1.23%   |
| Marvell Technology Group         | 4         | 0.98%   |
| JMicron Technology               | 4         | 0.98%   |
| Nvidia                           | 3         | 0.74%   |
| Kingston Technology Company      | 3         | 0.74%   |
| Hewlett-Packard                  | 3         | 0.74%   |
| Adaptec                          | 3         | 0.74%   |
| VIA Technologies                 | 1         | 0.25%   |
| SK hynix                         | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Silicon Image                    | 1         | 0.25%   |
| Phison Electronics               | 1         | 0.25%   |
| Micron/Crucial Technology        | 1         | 0.25%   |
| Micron Technology                | 1         | 0.25%   |
| KIOXIA                           | 1         | 0.25%   |
| Huawei Technologies              | 1         | 0.25%   |
| ADATA Technology                 | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25        | 4.98%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 23        | 4.58%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 22        | 4.38%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 19        | 3.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18        | 3.59%   |
| Intel SATA Controller [RAID mode]                                                       | 16        | 3.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 2.59%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 2.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12        | 2.39%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 2.39%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 11        | 2.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 1.99%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 10        | 1.99%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 10        | 1.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 1.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9         | 1.79%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 8         | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.39%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 1.2%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 5         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 0.8%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 4         | 0.8%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 4         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 0.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 0.8%    |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 216       | 51.67%  |
| RAID | 90        | 21.53%  |
| IDE  | 49        | 11.72%  |
| NVMe | 43        | 10.29%  |
| SAS  | 14        | 3.35%   |
| SCSI | 6         | 1.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 279       | 91.48%  |
| AMD       | 25        | 8.2%    |
| Hisilicon | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz  | 17        | 5.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz     | 11        | 3.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz     | 8         | 2.62%   |
| Intel Xeon CPU X5650 @ 2.67GHz       | 6         | 1.97%   |
| Intel Core i5-10500 CPU @ 3.10GHz    | 5         | 1.64%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz | 4         | 1.31%   |
| Intel Xeon CPU E5620 @ 2.40GHz       | 4         | 1.31%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 4         | 1.31%   |
| Intel Xeon E-2136 CPU @ 3.30GHz      | 3         | 0.98%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz  | 3         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 3         | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 3         | 0.98%   |
| Intel Core i3-6100U CPU @ 2.30GHz    | 3         | 0.98%   |
| AMD FX-6300 Six-Core Processor       | 3         | 0.98%   |
| Intel Xeon W-1290 CPU @ 3.20GHz      | 2         | 0.66%   |
| Intel Xeon CPU X5680 @ 3.33GHz       | 2         | 0.66%   |
| Intel Xeon CPU W3530 @ 2.80GHz       | 2         | 0.66%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz  | 2         | 0.66%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz   | 2         | 0.66%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz  | 2         | 0.66%   |
| Intel Core i9-10900K CPU @ 3.70GHz   | 2         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 2         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz     | 2         | 0.66%   |
| Intel Core i5-9500 CPU @ 3.00GHz     | 2         | 0.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 0.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz     | 2         | 0.66%   |
| Intel Core i5-10500T CPU @ 2.30GHz   | 2         | 0.66%   |
| Intel Core i5 CPU M 560 @ 2.67GHz    | 2         | 0.66%   |
| Intel Core i3-4160 CPU @ 3.60GHz     | 2         | 0.66%   |
| Intel Core i3-3120M CPU @ 2.50GHz    | 2         | 0.66%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 2         | 0.66%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 0.66%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz | 2         | 0.66%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 2         | 0.66%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz    | 2         | 0.66%   |
| Intel Atom CPU D525 @ 1.80GHz        | 2         | 0.66%   |
| AMD Ryzen 5 1600 Six-Core Processor  | 2         | 0.66%   |
| AMD Phenom II X6 1090T Processor     | 2         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Xeon              | 79        | 25.9%   |
| Intel Core i7           | 58        | 19.02%  |
| Intel Core i5           | 52        | 17.05%  |
| Intel Core i3           | 24        | 7.87%   |
| Intel Core 2 Duo        | 12        | 3.93%   |
| Intel Pentium           | 8         | 2.62%   |
| Other                   | 7         | 2.3%    |
| Intel Xeon Silver       | 7         | 2.3%    |
| Intel Celeron           | 7         | 2.3%    |
| Intel Atom              | 7         | 2.3%    |
| Intel Core i9           | 6         | 1.97%   |
| AMD FX                  | 6         | 1.97%   |
| Intel Xeon Gold         | 5         | 1.64%   |
| AMD Ryzen 5             | 4         | 1.31%   |
| Intel Pentium Dual-Core | 3         | 0.98%   |
| Intel Genuine           | 2         | 0.66%   |
| Intel Core 2 Quad       | 2         | 0.66%   |
| AMD Phenom II X6        | 2         | 0.66%   |
| AMD EPYC                | 2         | 0.66%   |
| Intel Pentium Dual      | 1         | 0.33%   |
| Intel Pentium 4         | 1         | 0.33%   |
| AMD Ryzen Threadripper  | 1         | 0.33%   |
| AMD Ryzen 7             | 1         | 0.33%   |
| AMD Ryzen 5 PRO         | 1         | 0.33%   |
| AMD Ryzen 3             | 1         | 0.33%   |
| AMD Opteron             | 1         | 0.33%   |
| AMD GX                  | 1         | 0.33%   |
| AMD E2                  | 1         | 0.33%   |
| AMD Athlon              | 1         | 0.33%   |
| AMD A8                  | 1         | 0.33%   |
| AMD A10                 | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 104       | 34.1%   |
| 2      | 76        | 24.92%  |
| 6      | 35        | 11.48%  |
| 20     | 21        | 6.89%   |
| 8      | 17        | 5.57%   |
| 12     | 13        | 4.26%   |
| 16     | 8         | 2.62%   |
| 24     | 7         | 2.3%    |
| 10     | 5         | 1.64%   |
| 3      | 4         | 1.31%   |
| 1      | 4         | 1.31%   |
| 40     | 2         | 0.66%   |
| 32     | 2         | 0.66%   |
| 14     | 2         | 0.66%   |
| 96     | 1         | 0.33%   |
| 48     | 1         | 0.33%   |
| 36     | 1         | 0.33%   |
| 28     | 1         | 0.33%   |
| 18     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 245       | 80.33%  |
| 2      | 59        | 19.34%  |
| 0      | 1         | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 207       | 67.87%  |
| 1      | 98        | 32.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 289       | 94.75%  |
| Unknown        | 13        | 4.26%   |
| 32-bit         | 3         | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 10.32%  |
| 0x306c3    | 29        | 9.35%   |
| 0x506e3    | 19        | 6.13%   |
| 0x406f1    | 19        | 6.13%   |
| 0x206a7    | 19        | 6.13%   |
| 0x306a9    | 13        | 4.19%   |
| 0x906ea    | 11        | 3.55%   |
| 0x206c2    | 11        | 3.55%   |
| 0x1067a    | 10        | 3.23%   |
| 0x906e9    | 9         | 2.9%    |
| 0xa0653    | 8         | 2.58%   |
| 0x306f2    | 8         | 2.58%   |
| 0x50654    | 7         | 2.26%   |
| 0xa0655    | 6         | 1.94%   |
| 0x40651    | 6         | 1.94%   |
| 0x206d7    | 6         | 1.94%   |
| 0x806ea    | 5         | 1.61%   |
| 0x10676    | 5         | 1.61%   |
| 0x06000852 | 5         | 1.61%   |
| 0x806ec    | 4         | 1.29%   |
| 0x806e9    | 4         | 1.29%   |
| 0x50657    | 4         | 1.29%   |
| 0x20655    | 4         | 1.29%   |
| 0x106ca    | 4         | 1.29%   |
| 0x106a5    | 4         | 1.29%   |
| 0x906ed    | 3         | 0.97%   |
| 0x406e3    | 3         | 0.97%   |
| 0x406c4    | 3         | 0.97%   |
| 0x106e5    | 3         | 0.97%   |
| 0x806c1    | 2         | 0.65%   |
| 0x6fd      | 2         | 0.65%   |
| 0x6fb      | 2         | 0.65%   |
| 0x606a6    | 2         | 0.65%   |
| 0x406c3    | 2         | 0.65%   |
| 0x306e4    | 2         | 0.65%   |
| 0x30678    | 2         | 0.65%   |
| 0x08701013 | 2         | 0.65%   |
| 0x08301034 | 2         | 0.65%   |
| 0x08001137 | 2         | 0.65%   |
| 0x03000027 | 2         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 44        | 14.43%  |
| Skylake          | 41        | 13.44%  |
| KabyLake         | 39        | 12.79%  |
| SandyBridge      | 27        | 8.85%   |
| Broadwell        | 27        | 8.85%   |
| Westmere         | 18        | 5.9%    |
| Penryn           | 18        | 5.9%    |
| IvyBridge        | 15        | 4.92%   |
| CometLake        | 15        | 4.92%   |
| Silvermont       | 7         | 2.3%    |
| Piledriver       | 7         | 2.3%    |
| Nehalem          | 7         | 2.3%    |
| Zen 2            | 6         | 1.97%   |
| Unknown          | 5         | 1.64%   |
| Core             | 4         | 1.31%   |
| Bonnell          | 4         | 1.31%   |
| K10              | 3         | 0.98%   |
| Zen+             | 2         | 0.66%   |
| Zen              | 2         | 0.66%   |
| TigerLake        | 2         | 0.66%   |
| P6               | 2         | 0.66%   |
| K10 Llano        | 2         | 0.66%   |
| Jaguar           | 2         | 0.66%   |
| NetBurst         | 1         | 0.33%   |
| K8 Hammer        | 1         | 0.33%   |
| IceLake          | 1         | 0.33%   |
| Goldmont plus    | 1         | 0.33%   |
| Goldmont         | 1         | 0.33%   |
| Alderlake Hybrid | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 142       | 43.03%  |
| Nvidia                                       | 66        | 20%     |
| AMD                                          | 52        | 15.76%  |
| Matrox Electronics Systems                   | 34        | 10.3%   |
| ASPEED Technology                            | 32        | 9.7%    |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.3%    |
| Silicon Motion                               | 1         | 0.3%    |
| Silicon Integrated Systems [SiS]             | 1         | 0.3%    |
| Huawei Technologies                          | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 32        | 9.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 3.86%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 12        | 3.56%   |
| Matrox Electronics Systems G200eR2                                                       | 10        | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 2.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 10        | 2.97%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 2.67%   |
| Intel HD Graphics 530                                                                    | 9         | 2.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 2.37%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8         | 2.37%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 1.78%   |
| Intel HD Graphics 630                                                                    | 5         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.48%   |
| Nvidia GP107GL [Quadro P400]                                                             | 4         | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.19%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.19%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.19%   |
| AMD ES1000                                                                               | 4         | 1.19%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 3         | 0.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.89%   |
| Intel HD Graphics 620                                                                    | 3         | 0.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.89%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2         | 0.59%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.59%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 2         | 0.59%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2         | 0.59%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 2         | 0.59%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 116       | 38.03%  |
| 1 x Nvidia              | 49        | 16.07%  |
| 1 x AMD                 | 44        | 14.43%  |
| 1 x Matrox              | 34        | 11.15%  |
| 1 x ASPEED              | 31        | 10.16%  |
| Intel + Nvidia          | 14        | 4.59%   |
| Intel + AMD             | 7         | 2.3%    |
| Other                   | 2         | 0.66%   |
| 2 x Nvidia              | 2         | 0.66%   |
| 2 x AMD                 | 1         | 0.33%   |
| 1 x XGI                 | 1         | 0.33%   |
| 1 x SiS                 | 1         | 0.33%   |
| 1 x Silicon Motion      | 1         | 0.33%   |
| Nvidia + ASPEED         | 1         | 0.33%   |
| 1 x Huawei Technologies | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 230       | 75.16%  |
| Unknown     | 44        | 14.38%  |
| Proprietary | 32        | 10.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 63.73%  |
| 1.01-2.0   | 34        | 11.11%  |
| 0.51-1.0   | 30        | 9.8%    |
| 0.01-0.5   | 16        | 5.23%   |
| 3.01-4.0   | 12        | 3.92%   |
| 7.01-8.0   | 11        | 3.59%   |
| 4.01-5.0   | 3         | 0.98%   |
| 5.01-6.0   | 2         | 0.65%   |
| 2.01-3.0   | 2         | 0.65%   |
| 16.01-24.0 | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 55        | 24.23%  |
| Samsung Electronics     | 25        | 11.01%  |
| Hewlett-Packard         | 16        | 7.05%   |
| LG Display              | 15        | 6.61%   |
| Goldstar                | 12        | 5.29%   |
| AU Optronics            | 11        | 4.85%   |
| AOC                     | 11        | 4.85%   |
| Chimei Innolux          | 10        | 4.41%   |
| Acer                    | 10        | 4.41%   |
| Lenovo                  | 8         | 3.52%   |
| Ancor Communications    | 6         | 2.64%   |
| BOE                     | 5         | 2.2%    |
| BenQ                    | 5         | 2.2%    |
| Philips                 | 4         | 1.76%   |
| ___                     | 2         | 0.88%   |
| ViewSonic               | 2         | 0.88%   |
| Unknown                 | 2         | 0.88%   |
| NEC Computers           | 2         | 0.88%   |
| InnoLux Display         | 2         | 0.88%   |
| Westinghouse            | 1         | 0.44%   |
| Sun                     | 1         | 0.44%   |
| Sony                    | 1         | 0.44%   |
| Sharp                   | 1         | 0.44%   |
| Sceptre Tech            | 1         | 0.44%   |
| Pixio                   | 1         | 0.44%   |
| PEP                     | 1         | 0.44%   |
| PANDA                   | 1         | 0.44%   |
| Packard Bell            | 1         | 0.44%   |
| NME                     | 1         | 0.44%   |
| MIT                     | 1         | 0.44%   |
| LG Philips              | 1         | 0.44%   |
| LG Electronics          | 1         | 0.44%   |
| KVM                     | 1         | 0.44%   |
| Insignia                | 1         | 0.44%   |
| HPN                     | 1         | 0.44%   |
| GVV                     | 1         | 0.44%   |
| Founder                 | 1         | 0.44%   |
| Eizo                    | 1         | 0.44%   |
| CHR                     | 1         | 0.44%   |
| Chi Mei Optoelectronics | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 7         | 2.89%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 6         | 2.48%   |
| Dell P2414H DELA09A 1920x1080 530x300mm 24.0-inch                     | 6         | 2.48%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                        | 4         | 1.65%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 2         | 0.83%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 0.83%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch      | 2         | 0.83%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch         | 2         | 0.83%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch            | 2         | 0.83%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.83%   |
| Dell P2417H DELA0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.83%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 2         | 0.83%   |
| ___ LCDTV16 ___0101 1360x768                                          | 1         | 0.41%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.41%   |
| Westinghouse LD-2240 WDT19DA 1920x1080 480x270mm 21.7-inch            | 1         | 0.41%   |
| ViewSonic VA702 SERIES VSC231C 1280x1024 338x270mm 17.0-inch          | 1         | 0.41%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch             | 1         | 0.41%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.41%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 1         | 0.41%   |
| Sun GH18PS SUN0587 1280x1024 359x287mm 18.1-inch                      | 1         | 0.41%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1         | 0.41%   |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch               | 1         | 0.41%   |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch                | 1         | 0.41%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 470x300mm 22.0-inch  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1         | 0.41%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch    | 1         | 0.41%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1         | 0.41%   |
| Samsung Electronics S27E391 SAM0C16 1920x1080 598x336mm 27.0-inch     | 1         | 0.41%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 0.41%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch      | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 91        | 40.99%  |
| 1366x768 (WXGA)    | 32        | 14.41%  |
| 1280x1024 (SXGA)   | 18        | 8.11%   |
| 3840x2160 (4K)     | 11        | 4.95%   |
| 1440x900 (WXGA+)   | 10        | 4.5%    |
| 2560x1440 (QHD)    | 9         | 4.05%   |
| 1920x1200 (WUXGA)  | 9         | 4.05%   |
| 1680x1050 (WSXGA+) | 8         | 3.6%    |
| 1280x800 (WXGA)    | 7         | 3.15%   |
| Unknown            | 6         | 2.7%    |
| 1600x900 (HD+)     | 5         | 2.25%   |
| 1600x1200          | 4         | 1.8%    |
| 3840x1200          | 2         | 0.9%    |
| 3840x1080          | 2         | 0.9%    |
| 1360x768           | 2         | 0.9%    |
| 5760x1080          | 1         | 0.45%   |
| 4480x1440          | 1         | 0.45%   |
| 3456x2160          | 1         | 0.45%   |
| 3440x1440          | 1         | 0.45%   |
| 1280x720 (HD)      | 1         | 0.45%   |
| 1024x768 (XGA)     | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 24      | 33        | 14.47%  |
| 15      | 31        | 13.6%   |
| 23      | 26        | 11.4%   |
| 21      | 21        | 9.21%   |
| 19      | 17        | 7.46%   |
| 27      | 16        | 7.02%   |
| Unknown | 14        | 6.14%   |
| 17      | 12        | 5.26%   |
| 13      | 10        | 4.39%   |
| 18      | 7         | 3.07%   |
| 14      | 7         | 3.07%   |
| 12      | 7         | 3.07%   |
| 22      | 6         | 2.63%   |
| 20      | 5         | 2.19%   |
| 31      | 3         | 1.32%   |
| 72      | 2         | 0.88%   |
| 32      | 2         | 0.88%   |
| 16      | 2         | 0.88%   |
| 55      | 1         | 0.44%   |
| 52      | 1         | 0.44%   |
| 42      | 1         | 0.44%   |
| 36      | 1         | 0.44%   |
| 34      | 1         | 0.44%   |
| 26      | 1         | 0.44%   |
| 25      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 72        | 32.29%  |
| 301-350     | 49        | 21.97%  |
| 401-500     | 44        | 19.73%  |
| 351-400     | 19        | 8.52%   |
| Unknown     | 14        | 6.28%   |
| 201-300     | 11        | 4.93%   |
| 601-700     | 5         | 2.24%   |
| 701-800     | 4         | 1.79%   |
| 1501-2000   | 2         | 0.9%    |
| 1001-1500   | 2         | 0.9%    |
| 901-1000    | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 135       | 65.53%  |
| 16/10   | 33        | 16.02%  |
| 5/4     | 18        | 8.74%   |
| Unknown | 12        | 5.83%   |
| 4/3     | 5         | 2.43%   |
| 3/2     | 2         | 0.97%   |
| 21/9    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 69        | 30.53%  |
| 101-110        | 31        | 13.72%  |
| 151-200        | 28        | 12.39%  |
| 301-350        | 16        | 7.08%   |
| 81-90          | 14        | 6.19%   |
| Unknown        | 14        | 6.19%   |
| 251-300        | 13        | 5.75%   |
| 141-150        | 12        | 5.31%   |
| 61-70          | 7         | 3.1%    |
| 351-500        | 6         | 2.65%   |
| More than 1000 | 4         | 1.77%   |
| 121-130        | 4         | 1.77%   |
| 71-80          | 3         | 1.33%   |
| 111-120        | 2         | 0.88%   |
| 501-1000       | 2         | 0.88%   |
| 131-140        | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 112       | 51.14%  |
| 101-120       | 51        | 23.29%  |
| 121-160       | 33        | 15.07%  |
| Unknown       | 14        | 6.39%   |
| 1-50          | 4         | 1.83%   |
| More than 240 | 3         | 1.37%   |
| 161-240       | 2         | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 167       | 53.7%   |
| 0     | 101       | 32.48%  |
| 2     | 40        | 12.86%  |
| 3     | 3         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 196       | 45.9%   |
| Realtek Semiconductor             | 98        | 22.95%  |
| Broadcom                          | 33        | 7.73%   |
| Qualcomm Atheros                  | 24        | 5.62%   |
| IBM                               | 12        | 2.81%   |
| TP-Link                           | 8         | 1.87%   |
| Ralink Technology                 | 6         | 1.41%   |
| Broadcom Limited                  | 5         | 1.17%   |
| Mellanox Technologies             | 3         | 0.7%    |
| Marvell Technology Group          | 3         | 0.7%    |
| Huawei Technologies               | 3         | 0.7%    |
| D-Link System                     | 3         | 0.7%    |
| Xilinx                            | 2         | 0.47%   |
| Nvidia                            | 2         | 0.47%   |
| D-Link                            | 2         | 0.47%   |
| Aquantia                          | 2         | 0.47%   |
| 3Com                              | 2         | 0.47%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.23%   |
| Xiaomi                            | 1         | 0.23%   |
| VIA Technologies                  | 1         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.23%   |
| Sierra Wireless                   | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| Ralink                            | 1         | 0.23%   |
| Qualcomm Atheros Communications   | 1         | 0.23%   |
| MediaTek                          | 1         | 0.23%   |
| LSI                               | 1         | 0.23%   |
| Linux 2.6.31.6 with s3c-udc       | 1         | 0.23%   |
| Linksys                           | 1         | 0.23%   |
| Lenovo                            | 1         | 0.23%   |
| ICS Advent                        | 1         | 0.23%   |
| Exar                              | 1         | 0.23%   |
| Ericsson Business Mobile Networks | 1         | 0.23%   |
| Emulex                            | 1         | 0.23%   |
| Edimax Technology                 | 1         | 0.23%   |
| Dresden Elektronik                | 1         | 0.23%   |
| Cisco Systems                     | 1         | 0.23%   |
| ASUSTek Computer                  | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |
| Apple                             | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 12.62%  |
| Intel I350 Gigabit Network Connection                             | 26        | 4.9%    |
| Intel Ethernet Connection I217-LM                                 | 18        | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 3.2%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 15        | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 2.64%   |
| IBM RNDIS/CDC ETHER                                               | 12        | 2.26%   |
| Intel I210 Gigabit Network Connection                             | 10        | 1.88%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 10        | 1.88%   |
| Intel Ethernet Connection (11) I219-LM                            | 10        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 1.32%   |
| Intel 82576 Gigabit Network Connection                            | 7         | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.94%   |
| Intel Wireless 7260                                               | 5         | 0.94%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 5         | 0.94%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.75%   |
| Intel Wireless 8260                                               | 4         | 0.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 4         | 0.75%   |
| Intel Ethernet Connection X722 for 1GbE                           | 4         | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.75%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 4         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.56%   |
| Intel Wireless 7265                                               | 3         | 0.56%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.56%   |
| Intel Ethernet Controller X550                                    | 3         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 48.74%  |
| Qualcomm Atheros                | 17        | 14.29%  |
| Realtek Semiconductor           | 16        | 13.45%  |
| TP-Link                         | 6         | 5.04%   |
| Ralink Technology               | 6         | 5.04%   |
| Broadcom                        | 6         | 5.04%   |
| D-Link                          | 2         | 1.68%   |
| Sierra Wireless                 | 1         | 0.84%   |
| Ralink                          | 1         | 0.84%   |
| Qualcomm Atheros Communications | 1         | 0.84%   |
| MediaTek                        | 1         | 0.84%   |
| Linksys                         | 1         | 0.84%   |
| Edimax Technology               | 1         | 0.84%   |
| D-Link System                   | 1         | 0.84%   |
| ASUSTek Computer                | 1         | 0.84%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.17%   |
| Intel Wireless 7260                                                     | 5         | 4.17%   |
| Intel Wireless 8260                                                     | 4         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.5%    |
| Intel Wireless 7265                                                     | 3         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.67%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.67%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.67%   |
| Intel Wireless 3165                                                     | 2         | 1.67%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.67%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 1.67%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 1.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.83%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]     | 1         | 0.83%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.83%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.83%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                         | 1         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.83%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.83%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                  | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 174       | 50%     |
| Realtek Semiconductor            | 92        | 26.44%  |
| Broadcom                         | 27        | 7.76%   |
| IBM                              | 12        | 3.45%   |
| Qualcomm Atheros                 | 9         | 2.59%   |
| Broadcom Limited                 | 5         | 1.44%   |
| Marvell Technology Group         | 3         | 0.86%   |
| Huawei Technologies              | 3         | 0.86%   |
| TP-Link                          | 2         | 0.57%   |
| Nvidia                           | 2         | 0.57%   |
| D-Link System                    | 2         | 0.57%   |
| Aquantia                         | 2         | 0.57%   |
| 3Com                             | 2         | 0.57%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.29%   |
| Xilinx                           | 1         | 0.29%   |
| Xiaomi                           | 1         | 0.29%   |
| VIA Technologies                 | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Samsung Electronics              | 1         | 0.29%   |
| Mellanox Technologies            | 1         | 0.29%   |
| Lenovo                           | 1         | 0.29%   |
| ICS Advent                       | 1         | 0.29%   |
| Emulex                           | 1         | 0.29%   |
| Cisco Systems                    | 1         | 0.29%   |
| ASIX Electronics                 | 1         | 0.29%   |
| Apple                            | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 16.67%  |
| Intel I350 Gigabit Network Connection                             | 26        | 6.47%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 4.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 4.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 15        | 3.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.48%   |
| IBM RNDIS/CDC ETHER                                               | 12        | 2.99%   |
| Intel I210 Gigabit Network Connection                             | 10        | 2.49%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 10        | 2.49%   |
| Intel Ethernet Connection (11) I219-LM                            | 10        | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 1.74%   |
| Intel 82576 Gigabit Network Connection                            | 7         | 1.74%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 1.49%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 5         | 1.24%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5         | 1.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1%      |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 4         | 1%      |
| Intel Ethernet Connection X722 for 1GbE                           | 4         | 1%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 4         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.75%   |
| Intel Ethernet Controller X550                                    | 3         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.75%   |
| Intel 82580 Gigabit Network Connection                            | 3         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 0.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.5%    |
| Intel Ethernet Connection X722                                    | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (3) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 296       | 71.5%   |
| WiFi     | 109       | 26.33%  |
| Modem    | 6         | 1.45%   |
| Unknown  | 3         | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 241       | 79.02%  |
| WiFi     | 63        | 20.66%  |
| Unknown  | 1         | 0.33%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 123       | 40.33%  |
| 1     | 114       | 37.38%  |
| 4     | 30        | 9.84%   |
| 6     | 14        | 4.59%   |
| 3     | 13        | 4.26%   |
| 8     | 3         | 0.98%   |
| 0     | 3         | 0.98%   |
| 5     | 2         | 0.66%   |
| 20    | 1         | 0.33%   |
| 12    | 1         | 0.33%   |
| 10    | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 284       | 91.91%  |
| Yes  | 25        | 8.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 43.37%  |
| Qualcomm Atheros Communications | 12        | 14.46%  |
| Realtek Semiconductor           | 8         | 9.64%   |
| Broadcom                        | 8         | 9.64%   |
| Cambridge Silicon Radio         | 7         | 8.43%   |
| Dell                            | 3         | 3.61%   |
| ASUSTek Computer                | 3         | 3.61%   |
| Lite-On Technology              | 1         | 1.2%    |
| IMC Networks                    | 1         | 1.2%    |
| Foxconn / Hon Hai               | 1         | 1.2%    |
| Dynex                           | 1         | 1.2%    |
| Apple                           | 1         | 1.2%    |
| Alps Electric                   | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 15.66%  |
| Intel Bluetooth Device                                                              | 7         | 8.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 8.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 8.43%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 7.23%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 6.02%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.61%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.41%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 2.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.41%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 2.41%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 2.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 2.41%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 2.41%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 2         | 2.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.2%    |
| Intel AX210 Bluetooth                                                               | 1         | 1.2%    |
| IMC Networks Bluetooth Device                                                       | 1         | 1.2%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.2%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 1.2%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.2%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.2%    |
| Broadcom ANYCOM Blue USB-200/250                                                    | 1         | 1.2%    |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 1.2%    |
| Apple Bluetooth Host Controller                                                     | 1         | 1.2%    |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 188       | 61.44%  |
| AMD                              | 51        | 16.67%  |
| Nvidia                           | 50        | 16.34%  |
| Logitech                         | 3         | 0.98%   |
| Texas Instruments                | 2         | 0.65%   |
| GN Netcom                        | 2         | 0.65%   |
| Creative Labs                    | 2         | 0.65%   |
| C-Media Electronics              | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Realtek Semiconductor            | 1         | 0.33%   |
| Plantronics                      | 1         | 0.33%   |
| Lenovo                           | 1         | 0.33%   |
| Ensoniq                          | 1         | 0.33%   |
| ASUSTek Computer                 | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 25        | 7.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 18        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 17        | 4.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17        | 4.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16        | 4.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13        | 3.77%   |
| Intel Sunrise Point-LP HD Audio                                                   | 11        | 3.19%   |
| Intel Comet Lake PCH cAVS                                                         | 10        | 2.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 10        | 2.9%    |
| Intel 200 Series PCH HD Audio                                                     | 8         | 2.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 2.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7         | 2.03%   |
| Intel Haswell-ULT HD Audio Controller                                             | 6         | 1.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6         | 1.74%   |
| Intel 8 Series HD Audio Controller                                                | 6         | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6         | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5         | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5         | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 5         | 1.45%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5         | 1.45%   |
| AMD FCH Azalia Controller                                                         | 5         | 1.45%   |
| Nvidia TU104 HD Audio Controller                                                  | 4         | 1.16%   |
| Nvidia High Definition Audio Controller                                           | 4         | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 1.16%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4         | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4         | 1.16%   |
| Intel CM238 HD Audio Controller                                                   | 4         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 4         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4         | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 3         | 0.87%   |
| Intel Audio device                                                                | 3         | 0.87%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 0.58%   |
| Nvidia TU102 High Definition Audio Controller                                     | 2         | 0.58%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 72        | 23.84%  |
| SK hynix            | 59        | 19.54%  |
| Micron Technology   | 49        | 16.23%  |
| Kingston            | 45        | 14.9%   |
| Unknown             | 33        | 10.93%  |
| Crucial             | 19        | 6.29%   |
| A-DATA Technology   | 5         | 1.66%   |
| Corsair             | 4         | 1.32%   |
| Transcend           | 3         | 0.99%   |
| Patriot             | 3         | 0.99%   |
| G.Skill             | 3         | 0.99%   |
| Wilk                | 1         | 0.33%   |
| Ramaxel Technology  | 1         | 0.33%   |
| Nanya Technology    | 1         | 0.33%   |
| Mushkin             | 1         | 0.33%   |
| Elpida              | 1         | 0.33%   |
| Apacer              | 1         | 0.33%   |
| Unknown             | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s      | 10        | 3.06%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s       | 6         | 1.83%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s      | 5         | 1.53%   |
| Samsung RAM Module 8192MB DIMM DDR4 3200MT/s              | 4         | 1.22%   |
| Samsung RAM Module 8192MB DIMM DDR3 800MT/s               | 4         | 1.22%   |
| Samsung RAM M393A8G40MB2-CVF 64GB DIMM DDR4 2933MT/s      | 4         | 1.22%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s       | 4         | 1.22%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s      | 4         | 1.22%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2667MT/s  | 4         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 3         | 0.92%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                | 3         | 0.92%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 2         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 2         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 2         | 0.61%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s             | 2         | 0.61%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s      | 2         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.61%   |
| SK hynix RAM HMT41GR7AFR4A-PB 8192MB DIMM DDR3 1600MT/s   | 2         | 0.61%   |
| SK hynix RAM HMA451R7MFR8N-TF 4096MB DIMM DDR4 2133MT/s   | 2         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 0.61%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s      | 2         | 0.61%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3600MT/s      | 2         | 0.61%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2         | 0.61%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s        | 2         | 0.61%   |
| Micron RAM 36ASF4G72PZ-2G3A1 32GB DIMM DDR4 2400MT/s      | 2         | 0.61%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16384MB DIMM DDR4 2667MT/s   | 2         | 0.61%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 2         | 0.61%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s   | 2         | 0.61%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s      | 1         | 0.31%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1         | 0.31%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1         | 0.31%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                   | 1         | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s               | 1         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s             | 1         | 0.31%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s               | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 135       | 50.19%  |
| DDR3    | 99        | 36.8%   |
| DDR2    | 14        | 5.2%    |
| Unknown | 12        | 4.46%   |
| SDRAM   | 2         | 0.74%   |
| LPDDR3  | 2         | 0.74%   |
| DDR5    | 2         | 0.74%   |
| LPDDR4  | 1         | 0.37%   |
| DRAM    | 1         | 0.37%   |
| DDR     | 1         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 189       | 70%     |
| SODIMM       | 76        | 28.15%  |
| RIMM         | 2         | 0.74%   |
| FB-DIMM      | 2         | 0.74%   |
| Row Of Chips | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 83        | 28.82%  |
| 4096  | 77        | 26.74%  |
| 16384 | 44        | 15.28%  |
| 32768 | 37        | 12.85%  |
| 2048  | 33        | 11.46%  |
| 1024  | 8         | 2.78%   |
| 65536 | 6         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 52        | 17.69%  |
| 2400    | 47        | 15.99%  |
| 2667    | 42        | 14.29%  |
| 1333    | 37        | 12.59%  |
| 3200    | 25        | 8.5%    |
| 2133    | 16        | 5.44%   |
| 800     | 14        | 4.76%   |
| 667     | 9         | 3.06%   |
| 2933    | 7         | 2.38%   |
| Unknown | 6         | 2.04%   |
| 2800    | 4         | 1.36%   |
| 3600    | 3         | 1.02%   |
| 1334    | 3         | 1.02%   |
| 4800    | 2         | 0.68%   |
| 3266    | 2         | 0.68%   |
| 2666    | 2         | 0.68%   |
| 2134    | 2         | 0.68%   |
| 2000    | 2         | 0.68%   |
| 1866    | 2         | 0.68%   |
| 1800    | 2         | 0.68%   |
| 1648    | 2         | 0.68%   |
| 1067    | 2         | 0.68%   |
| 1066    | 2         | 0.68%   |
| 65535   | 1         | 0.34%   |
| 4333    | 1         | 0.34%   |
| 4199    | 1         | 0.34%   |
| 3500    | 1         | 0.34%   |
| 3466    | 1         | 0.34%   |
| 2465    | 1         | 0.34%   |
| 1867    | 1         | 0.34%   |
| 533     | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Star Micronics      | 1         | 14.29%  |
| Samsung Electronics | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Star Micronics TSP100ECO/TSP100II | 1         | 14.29%  |
| Samsung M288x Series              | 1         | 14.29%  |
| HP LaserJet 400 M401n             | 1         | 14.29%  |
| HP LaserJet 3030                  | 1         | 14.29%  |
| HP LaserJet 1020                  | 1         | 14.29%  |
| Canon MF210 Series                | 1         | 14.29%  |
| Brother MFC-9130CW                | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 11.11%  |
| Microdia                               | 6         | 9.52%   |
| IMC Networks                           | 6         | 9.52%   |
| Sunplus Innovation Technology          | 5         | 7.94%   |
| Realtek Semiconductor                  | 5         | 7.94%   |
| Quanta                                 | 4         | 6.35%   |
| Logitech                               | 4         | 6.35%   |
| Suyin                                  | 3         | 4.76%   |
| Generalplus Technology                 | 3         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.76%   |
| Acer                                   | 3         | 4.76%   |
| Samsung Electronics                    | 2         | 3.17%   |
| Ricoh                                  | 2         | 3.17%   |
| Microsoft                              | 2         | 3.17%   |
| Lite-On Technology                     | 2         | 3.17%   |
| Apple                                  | 2         | 3.17%   |
| Z-Star Microelectronics                | 1         | 1.59%   |
| Syntek                                 | 1         | 1.59%   |
| Silicon Motion                         | 1         | 1.59%   |
| Alcor Micro                            | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 4         | 6.35%   |
| IMC Networks Integrated Camera           | 4         | 6.35%   |
| Sunplus Integrated_Webcam_HD             | 3         | 4.76%   |
| Generalplus 808 Camera #9 (web-cam mode) | 3         | 4.76%   |
| Suyin Integrated Webcam                  | 2         | 3.17%   |
| Samsung Galaxy A5 (MTP)                  | 2         | 3.17%   |
| Z-Star Venus USB2.0 Camera               | 1         | 1.59%   |
| Syntek EasyCamera                        | 1         | 1.59%   |
| Suyin Asus Integrated Webcam [CN031B]    | 1         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 1.59%   |
| Sunplus Integrated Webcam                | 1         | 1.59%   |
| Silicon Motion WebCam SC-10HDD12636N     | 1         | 1.59%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 1.59%   |
| Ricoh HD Webcam                          | 1         | 1.59%   |
| Realtek USB2.0 VGA UVC WebCam            | 1         | 1.59%   |
| Realtek USB2.0 HD UVC WebCam             | 1         | 1.59%   |
| Realtek USB Camera                       | 1         | 1.59%   |
| Realtek Lenovo EasyCamera                | 1         | 1.59%   |
| Realtek Integrated Webcam HD             | 1         | 1.59%   |
| Quanta USB HD Webcam                     | 1         | 1.59%   |
| Quanta Laptop_Integrated_Webcam_2HDM     | 1         | 1.59%   |
| Quanta HP Webcam                         | 1         | 1.59%   |
| Quanta HP Full-HD Camera                 | 1         | 1.59%   |
| Microsoft LifeCam NX-6000                | 1         | 1.59%   |
| Microsoft LifeCam HD-5000                | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_HD     | 1         | 1.59%   |
| Microdia Dell Integrated HD Webcam       | 1         | 1.59%   |
| Logitech Webcam C310                     | 1         | 1.59%   |
| Logitech Webcam C170                     | 1         | 1.59%   |
| Logitech HD Pro Webcam C920              | 1         | 1.59%   |
| Logitech C922 Pro Stream Webcam          | 1         | 1.59%   |
| Lite-On HP HD Webcam                     | 1         | 1.59%   |
| Lite-On HP HD Camera                     | 1         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 1.59%   |
| IMC Networks HD Camera                   | 1         | 1.59%   |
| Chicony USB2.0 Camera                    | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD          | 1         | 1.59%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 1.59%   |
| Chicony HP Wide Vision HD Camera         | 1         | 1.59%   |
| Chicony HP Webcam [2 MP Macro]           | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 6         | 33.33%  |
| Synaptics          | 5         | 27.78%  |
| AuthenTec          | 4         | 22.22%  |
| STMicroelectronics | 2         | 11.11%  |
| Upek               | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 16.67%  |
| AuthenTec AES2810                                                          | 3         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                      | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 7         | 63.64%  |
| SCM Microsystems | 2         | 18.18%  |
| Lenovo           | 1         | 9.09%   |
| Hewlett-Packard  | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 36.36%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 9.09%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 161       | 52.1%   |
| 1     | 69        | 22.33%  |
| 2     | 48        | 15.53%  |
| 3     | 19        | 6.15%   |
| 4     | 10        | 3.24%   |
| 5     | 2         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 72        | 29.88%  |
| Graphics card            | 52        | 21.58%  |
| Unassigned class         | 45        | 18.67%  |
| Net/wireless             | 21        | 8.71%   |
| Fingerprint reader       | 18        | 7.47%   |
| Net/ethernet             | 15        | 6.22%   |
| Chipcard                 | 6         | 2.49%   |
| Storage                  | 3         | 1.24%   |
| Storage/raid             | 2         | 0.83%   |
| Sound                    | 2         | 0.83%   |
| Network                  | 2         | 0.83%   |
| Multimedia controller    | 1         | 0.41%   |
| Modem                    | 1         | 0.41%   |
| Camera                   | 1         | 0.41%   |

