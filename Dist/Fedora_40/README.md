Fedora 40 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 40.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_40/Desktop/README.md) and [notebooks](/Dist/Fedora_40/Notebook/README.md).

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

Total: 4967

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [7fea0bb2a1](https://linux-hardware.org/?probe=7fea0bb2a1) | Jan 06, 2025 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [0c0d5510fc](https://linux-hardware.org/?probe=0c0d5510fc) | Jan 05, 2025 |
| HP            | 2B0D A01                    | All in one  | [5aed288755](https://linux-hardware.org/?probe=5aed288755) | Jan 03, 2025 |
| AMI           | Intel                       | Desktop     | [a5d99b38fe](https://linux-hardware.org/?probe=a5d99b38fe) | Jan 03, 2025 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [2a6b25b609](https://linux-hardware.org/?probe=2a6b25b609) | Jan 02, 2025 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [25af48ddf7](https://linux-hardware.org/?probe=25af48ddf7) | Jan 01, 2025 |
| HP            | 2B0D A01                    | All in one  | [871b4fe736](https://linux-hardware.org/?probe=871b4fe736) | Jan 01, 2025 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [c619b6152e](https://linux-hardware.org/?probe=c619b6152e) | Jan 01, 2025 |
| HP            | 2B0D A01                    | All in one  | [f2958af04d](https://linux-hardware.org/?probe=f2958af04d) | Dec 31, 2024 |
| HP            | 2B0D A01                    | All in one  | [d28496bed0](https://linux-hardware.org/?probe=d28496bed0) | Dec 31, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [04eb3b79c5](https://linux-hardware.org/?probe=04eb3b79c5) | Dec 31, 2024 |
| System76      | Thelio Major thelio-majo... | Desktop     | [4519da1309](https://linux-hardware.org/?probe=4519da1309) | Dec 30, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [05de1b24e3](https://linux-hardware.org/?probe=05de1b24e3) | Dec 30, 2024 |
| Gigabyte      | A620I AX                    | Desktop     | [801e27533c](https://linux-hardware.org/?probe=801e27533c) | Dec 30, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5f6888e1a9](https://linux-hardware.org/?probe=5f6888e1a9) | Dec 30, 2024 |
| ASUSTek       | H170-PRO                    | Desktop     | [04f9098e0d](https://linux-hardware.org/?probe=04f9098e0d) | Dec 26, 2024 |
| MSI           | 785GT-E63                   | Desktop     | [7bef4fbf53](https://linux-hardware.org/?probe=7bef4fbf53) | Dec 26, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | Notebook    | [f1a3b79f94](https://linux-hardware.org/?probe=f1a3b79f94) | Dec 26, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [a16e1a46ec](https://linux-hardware.org/?probe=a16e1a46ec) | Dec 25, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [0659ed4270](https://linux-hardware.org/?probe=0659ed4270) | Dec 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [002375d8d5](https://linux-hardware.org/?probe=002375d8d5) | Dec 25, 2024 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [7852114da0](https://linux-hardware.org/?probe=7852114da0) | Dec 24, 2024 |
| Apple         | MacBookPro14,2              | Notebook    | [fded50dece](https://linux-hardware.org/?probe=fded50dece) | Dec 24, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [abc685fb60](https://linux-hardware.org/?probe=abc685fb60) | Dec 23, 2024 |
| TUXEDO        | N650DU                      | Notebook    | [00621c75d7](https://linux-hardware.org/?probe=00621c75d7) | Dec 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7bfad25e97](https://linux-hardware.org/?probe=7bfad25e97) | Dec 22, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [7e6e91ee61](https://linux-hardware.org/?probe=7e6e91ee61) | Dec 21, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [8c74a99311](https://linux-hardware.org/?probe=8c74a99311) | Dec 21, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [02bf6146b7](https://linux-hardware.org/?probe=02bf6146b7) | Dec 21, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [26283d6910](https://linux-hardware.org/?probe=26283d6910) | Dec 20, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [179a63f113](https://linux-hardware.org/?probe=179a63f113) | Dec 19, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [a20b5ae9f0](https://linux-hardware.org/?probe=a20b5ae9f0) | Dec 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [fff8bed544](https://linux-hardware.org/?probe=fff8bed544) | Dec 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [02f1237767](https://linux-hardware.org/?probe=02f1237767) | Dec 19, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [d4d74d7666](https://linux-hardware.org/?probe=d4d74d7666) | Dec 19, 2024 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | Notebook    | [9c999b2e96](https://linux-hardware.org/?probe=9c999b2e96) | Dec 18, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [736b23610e](https://linux-hardware.org/?probe=736b23610e) | Dec 18, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0316594714](https://linux-hardware.org/?probe=0316594714) | Dec 18, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d30a56ccc6](https://linux-hardware.org/?probe=d30a56ccc6) | Dec 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c80c3adbe0](https://linux-hardware.org/?probe=c80c3adbe0) | Dec 17, 2024 |
| ASUSTek       | X555LF                      | Notebook    | [7c3dbd59b5](https://linux-hardware.org/?probe=7c3dbd59b5) | Dec 17, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [c9737709d2](https://linux-hardware.org/?probe=c9737709d2) | Dec 17, 2024 |
| ASUSTek       | Rampage II GENE             | Desktop     | [92edcfef77](https://linux-hardware.org/?probe=92edcfef77) | Dec 16, 2024 |
| Dell          | Latitude E5570              | Notebook    | [5eb8637f79](https://linux-hardware.org/?probe=5eb8637f79) | Dec 15, 2024 |
| Dell          | Latitude E5570              | Notebook    | [c1af283f5f](https://linux-hardware.org/?probe=c1af283f5f) | Dec 14, 2024 |
| Intel Clie... | LAPBC510                    | Notebook    | [ad76cb1437](https://linux-hardware.org/?probe=ad76cb1437) | Dec 13, 2024 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [41fd350e84](https://linux-hardware.org/?probe=41fd350e84) | Dec 13, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [6b8ce5850b](https://linux-hardware.org/?probe=6b8ce5850b) | Dec 12, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [b8fc7010b0](https://linux-hardware.org/?probe=b8fc7010b0) | Dec 12, 2024 |
| Gigabyte      | H410M H V2                  | Desktop     | [29d08f5d9c](https://linux-hardware.org/?probe=29d08f5d9c) | Dec 11, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8eef7e1da7](https://linux-hardware.org/?probe=8eef7e1da7) | Dec 10, 2024 |
| SLIMBOOK      | ONE-AM5                     | Desktop     | [d0bbc8aa6e](https://linux-hardware.org/?probe=d0bbc8aa6e) | Dec 10, 2024 |
| Lenovo        | ThinkPad E525 12003NG       | Notebook    | [ae0a08738a](https://linux-hardware.org/?probe=ae0a08738a) | Dec 09, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [39eb234a0f](https://linux-hardware.org/?probe=39eb234a0f) | Dec 09, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [80d9b4596e](https://linux-hardware.org/?probe=80d9b4596e) | Dec 08, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6dd73b8ba5](https://linux-hardware.org/?probe=6dd73b8ba5) | Dec 08, 2024 |
| HP            | ProBook 430 G5              | Notebook    | [d6fbd54c05](https://linux-hardware.org/?probe=d6fbd54c05) | Dec 07, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [85d7cd1e9a](https://linux-hardware.org/?probe=85d7cd1e9a) | Dec 06, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [3dafc8c3c6](https://linux-hardware.org/?probe=3dafc8c3c6) | Dec 06, 2024 |
| Acer          | Spin SP513-54N              | Convertible | [3c0060f1b7](https://linux-hardware.org/?probe=3c0060f1b7) | Dec 06, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [34f8b6bc0b](https://linux-hardware.org/?probe=34f8b6bc0b) | Dec 06, 2024 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [988eece545](https://linux-hardware.org/?probe=988eece545) | Dec 06, 2024 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bc1c756ed9](https://linux-hardware.org/?probe=bc1c756ed9) | Dec 05, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [7d778aaa23](https://linux-hardware.org/?probe=7d778aaa23) | Dec 04, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [ce617f14e9](https://linux-hardware.org/?probe=ce617f14e9) | Dec 03, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [047e3e03f0](https://linux-hardware.org/?probe=047e3e03f0) | Dec 03, 2024 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fb898274e9](https://linux-hardware.org/?probe=fb898274e9) | Dec 03, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [46262b8198](https://linux-hardware.org/?probe=46262b8198) | Dec 02, 2024 |
| HONOR         | FRI-FXX                     | Notebook    | [d5c89a650a](https://linux-hardware.org/?probe=d5c89a650a) | Dec 02, 2024 |
| Toshiba       | Satellite L850              | Notebook    | [d7efdeae96](https://linux-hardware.org/?probe=d7efdeae96) | Dec 01, 2024 |
| Toshiba       | Satellite L850              | Notebook    | [510d7773fa](https://linux-hardware.org/?probe=510d7773fa) | Dec 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7af06c00e5](https://linux-hardware.org/?probe=7af06c00e5) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [341c2709d8](https://linux-hardware.org/?probe=341c2709d8) | Nov 29, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [0b901fda6f](https://linux-hardware.org/?probe=0b901fda6f) | Nov 26, 2024 |
| Acer          | Aspire ES1-572              | Notebook    | [612f5558b5](https://linux-hardware.org/?probe=612f5558b5) | Nov 26, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [3bdd24a725](https://linux-hardware.org/?probe=3bdd24a725) | Nov 26, 2024 |
| ASUSTek       | Z97-PRO                     | Desktop     | [06a9dbf820](https://linux-hardware.org/?probe=06a9dbf820) | Nov 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5b7f540652](https://linux-hardware.org/?probe=5b7f540652) | Nov 24, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [146aa6feef](https://linux-hardware.org/?probe=146aa6feef) | Nov 24, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | Notebook    | [9743c11187](https://linux-hardware.org/?probe=9743c11187) | Nov 24, 2024 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [da194d6897](https://linux-hardware.org/?probe=da194d6897) | Nov 23, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | Notebook    | [2b9ffeae7c](https://linux-hardware.org/?probe=2b9ffeae7c) | Nov 23, 2024 |
| HUAWEI        | MDF-XX                      | Notebook    | [5345ae504f](https://linux-hardware.org/?probe=5345ae504f) | Nov 23, 2024 |
| ASUSTek       | TP410UR                     | Convertible | [67e9fe630a](https://linux-hardware.org/?probe=67e9fe630a) | Nov 23, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [bfdfab6c5a](https://linux-hardware.org/?probe=bfdfab6c5a) | Nov 23, 2024 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [a0f8d129fd](https://linux-hardware.org/?probe=a0f8d129fd) | Nov 22, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [40b777045b](https://linux-hardware.org/?probe=40b777045b) | Nov 21, 2024 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [aab56982bc](https://linux-hardware.org/?probe=aab56982bc) | Nov 19, 2024 |
| Samsung       | 960QFG                      | Convertible | [26e99414a4](https://linux-hardware.org/?probe=26e99414a4) | Nov 18, 2024 |
| Lenovo        | ThinkPad P50 20EQS0SM01     | Notebook    | [bd76e1e326](https://linux-hardware.org/?probe=bd76e1e326) | Nov 18, 2024 |
| Samsung       | 550XDA                      | Notebook    | [01ef3193ec](https://linux-hardware.org/?probe=01ef3193ec) | Nov 17, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [4ecadd4fa2](https://linux-hardware.org/?probe=4ecadd4fa2) | Nov 17, 2024 |
| ASUSTek       | X550JK                      | Notebook    | [82b0e4d59c](https://linux-hardware.org/?probe=82b0e4d59c) | Nov 17, 2024 |
| ASUSTek       | X550JK                      | Notebook    | [b343c33a78](https://linux-hardware.org/?probe=b343c33a78) | Nov 17, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [03e416d02a](https://linux-hardware.org/?probe=03e416d02a) | Nov 17, 2024 |
| Dell          | 0KRC95 A02                  | Desktop     | [d155ecd4d2](https://linux-hardware.org/?probe=d155ecd4d2) | Nov 16, 2024 |
| HP            | 15                          | Notebook    | [79f04083ac](https://linux-hardware.org/?probe=79f04083ac) | Nov 16, 2024 |
| ASUSTek       | Z87-A                       | Desktop     | [e328a6c955](https://linux-hardware.org/?probe=e328a6c955) | Nov 16, 2024 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [43c9e814d8](https://linux-hardware.org/?probe=43c9e814d8) | Nov 16, 2024 |
| HP            | 802F                        | Desktop     | [7ed276e4ea](https://linux-hardware.org/?probe=7ed276e4ea) | Nov 15, 2024 |
| HP            | ProBook 650 G4              | Notebook    | [aa662f23e7](https://linux-hardware.org/?probe=aa662f23e7) | Nov 15, 2024 |
| MSI           | B85-G43 GAMING              | Desktop     | [c99693bf24](https://linux-hardware.org/?probe=c99693bf24) | Nov 15, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [cc64e22524](https://linux-hardware.org/?probe=cc64e22524) | Nov 15, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6adb8dd712](https://linux-hardware.org/?probe=6adb8dd712) | Nov 14, 2024 |
| Lenovo        | ThinkPad P1 20TJS2F42V      | Notebook    | [6d7dd4ff42](https://linux-hardware.org/?probe=6d7dd4ff42) | Nov 14, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cea2c5d716](https://linux-hardware.org/?probe=cea2c5d716) | Nov 12, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [37ff07c55e](https://linux-hardware.org/?probe=37ff07c55e) | Nov 12, 2024 |
| Samsung       | 730QED                      | Convertible | [ed0a340998](https://linux-hardware.org/?probe=ed0a340998) | Nov 12, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [8ab1c5f89a](https://linux-hardware.org/?probe=8ab1c5f89a) | Nov 12, 2024 |
| HP            | ProBook 650 G4              | Notebook    | [5211ddeeac](https://linux-hardware.org/?probe=5211ddeeac) | Nov 12, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [23c9b0f6d9](https://linux-hardware.org/?probe=23c9b0f6d9) | Nov 12, 2024 |
| Dell          | Latitude 5540               | Notebook    | [6b66bd70e6](https://linux-hardware.org/?probe=6b66bd70e6) | Nov 12, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [e88d7b46ce](https://linux-hardware.org/?probe=e88d7b46ce) | Nov 12, 2024 |
| Lenovo        | ThinkServer TS140           | Desktop     | [7f64dbb188](https://linux-hardware.org/?probe=7f64dbb188) | Nov 12, 2024 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [0b2580a6fd](https://linux-hardware.org/?probe=0b2580a6fd) | Nov 11, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [2262fccd67](https://linux-hardware.org/?probe=2262fccd67) | Nov 11, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [25efb695c6](https://linux-hardware.org/?probe=25efb695c6) | Nov 11, 2024 |
| Silicom       | 80200-0240-G02 R200         | Desktop     | [547701de33](https://linux-hardware.org/?probe=547701de33) | Nov 11, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7c4be81c18](https://linux-hardware.org/?probe=7c4be81c18) | Nov 11, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [285f82aa26](https://linux-hardware.org/?probe=285f82aa26) | Nov 11, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [ffd1267bca](https://linux-hardware.org/?probe=ffd1267bca) | Nov 10, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [4cf83bb804](https://linux-hardware.org/?probe=4cf83bb804) | Nov 10, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [e16d78d766](https://linux-hardware.org/?probe=e16d78d766) | Nov 10, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [480d5f0266](https://linux-hardware.org/?probe=480d5f0266) | Nov 10, 2024 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [0c527ca448](https://linux-hardware.org/?probe=0c527ca448) | Nov 10, 2024 |
| Lenovo        | ThinkPad T480 20L5S05U00    | Notebook    | [cd6f4884f3](https://linux-hardware.org/?probe=cd6f4884f3) | Nov 09, 2024 |
| Juno Compu... | junotab3                    | Notebook    | [f6d2381f9f](https://linux-hardware.org/?probe=f6d2381f9f) | Nov 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f84abc56e9](https://linux-hardware.org/?probe=f84abc56e9) | Nov 08, 2024 |
| AWOW          | HA7                         | Desktop     | [75a3983b2b](https://linux-hardware.org/?probe=75a3983b2b) | Nov 08, 2024 |
| MSI           | Modern 14 B11MO             | Notebook    | [392e7d82ed](https://linux-hardware.org/?probe=392e7d82ed) | Nov 08, 2024 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [31b44d52d7](https://linux-hardware.org/?probe=31b44d52d7) | Nov 07, 2024 |
| Intel         | NUC6i7KYB H90766-404        | Mini pc     | [55ce99f45f](https://linux-hardware.org/?probe=55ce99f45f) | Nov 07, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1d52579f6c](https://linux-hardware.org/?probe=1d52579f6c) | Nov 06, 2024 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [f711f4d637](https://linux-hardware.org/?probe=f711f4d637) | Nov 06, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [4a06e31cc5](https://linux-hardware.org/?probe=4a06e31cc5) | Nov 06, 2024 |
| Dell          | 0D02VH A01                  | Desktop     | [05f4bb88ff](https://linux-hardware.org/?probe=05f4bb88ff) | Nov 06, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [4fbeaa34cb](https://linux-hardware.org/?probe=4fbeaa34cb) | Nov 05, 2024 |
| Dell          | 08HPGT A01                  | Desktop     | [230e7069ea](https://linux-hardware.org/?probe=230e7069ea) | Nov 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [e218882150](https://linux-hardware.org/?probe=e218882150) | Nov 05, 2024 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [be403477e6](https://linux-hardware.org/?probe=be403477e6) | Nov 04, 2024 |
| Lenovo        | ThinkBook 14s G2 ITL 20V... | Notebook    | [239a991b05](https://linux-hardware.org/?probe=239a991b05) | Nov 04, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [2b932f61ea](https://linux-hardware.org/?probe=2b932f61ea) | Nov 04, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [5b18d864d6](https://linux-hardware.org/?probe=5b18d864d6) | Nov 02, 2024 |
| Dell          | Latitude E5420              | Notebook    | [9e08b522db](https://linux-hardware.org/?probe=9e08b522db) | Nov 02, 2024 |
| Lenovo        | ThinkPad E14 20RA007TUE     | Notebook    | [ced7393b11](https://linux-hardware.org/?probe=ced7393b11) | Nov 02, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [133d4cc06b](https://linux-hardware.org/?probe=133d4cc06b) | Nov 02, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0585569a17](https://linux-hardware.org/?probe=0585569a17) | Nov 02, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [48509f2eb3](https://linux-hardware.org/?probe=48509f2eb3) | Nov 01, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | Notebook    | [e82e4d82e0](https://linux-hardware.org/?probe=e82e4d82e0) | Nov 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS3CV0V    | Notebook    | [9a1a8e0d40](https://linux-hardware.org/?probe=9a1a8e0d40) | Nov 01, 2024 |
| Intel         | Milstead Platform           | Notebook    | [fe0d78d041](https://linux-hardware.org/?probe=fe0d78d041) | Nov 01, 2024 |
| Intel         | Milstead Platform           | Notebook    | [94d678f3f5](https://linux-hardware.org/?probe=94d678f3f5) | Nov 01, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [5c9b330685](https://linux-hardware.org/?probe=5c9b330685) | Nov 01, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [3d257bfc82](https://linux-hardware.org/?probe=3d257bfc82) | Nov 01, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [fbbd1252dc](https://linux-hardware.org/?probe=fbbd1252dc) | Nov 01, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [b48bbd9d54](https://linux-hardware.org/?probe=b48bbd9d54) | Nov 01, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | Notebook    | [02bcf148cc](https://linux-hardware.org/?probe=02bcf148cc) | Oct 31, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2fd4351d4d](https://linux-hardware.org/?probe=2fd4351d4d) | Oct 31, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [d549dd1d0b](https://linux-hardware.org/?probe=d549dd1d0b) | Oct 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [926da4587b](https://linux-hardware.org/?probe=926da4587b) | Oct 31, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [03a09e81fb](https://linux-hardware.org/?probe=03a09e81fb) | Oct 31, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a06eab93a5](https://linux-hardware.org/?probe=a06eab93a5) | Oct 30, 2024 |
| Timi          | TM1707                      | Notebook    | [6f1f7e4e34](https://linux-hardware.org/?probe=6f1f7e4e34) | Oct 30, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2c694b863b](https://linux-hardware.org/?probe=2c694b863b) | Oct 30, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [14cc9b1bd2](https://linux-hardware.org/?probe=14cc9b1bd2) | Oct 30, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [0829e95509](https://linux-hardware.org/?probe=0829e95509) | Oct 30, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [30d0451aa4](https://linux-hardware.org/?probe=30d0451aa4) | Oct 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb3134b841](https://linux-hardware.org/?probe=eb3134b841) | Oct 30, 2024 |
| Acer          | Aspire A514-52K             | Notebook    | [102e60dfa8](https://linux-hardware.org/?probe=102e60dfa8) | Oct 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [e6e3c615dc](https://linux-hardware.org/?probe=e6e3c615dc) | Oct 29, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [0403c46fc9](https://linux-hardware.org/?probe=0403c46fc9) | Oct 29, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [b337c998c8](https://linux-hardware.org/?probe=b337c998c8) | Oct 29, 2024 |
| Apple         | MacBookPro13,1              | Notebook    | [a4cea0834a](https://linux-hardware.org/?probe=a4cea0834a) | Oct 29, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0f6ac1a5b](https://linux-hardware.org/?probe=d0f6ac1a5b) | Oct 29, 2024 |
| Supersonic    | SC-10XX                     | Tablet      | [30541a7ec0](https://linux-hardware.org/?probe=30541a7ec0) | Oct 29, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [29941bb47c](https://linux-hardware.org/?probe=29941bb47c) | Oct 29, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c8b803b5be](https://linux-hardware.org/?probe=c8b803b5be) | Oct 29, 2024 |
| ASUSTek       | UX530UX                     | Notebook    | [b11e1b2e90](https://linux-hardware.org/?probe=b11e1b2e90) | Oct 29, 2024 |
| HUAWEI        | BDZ-WXX9                    | Notebook    | [a775cc4234](https://linux-hardware.org/?probe=a775cc4234) | Oct 29, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [e738c30646](https://linux-hardware.org/?probe=e738c30646) | Oct 29, 2024 |
| HP            | 8437                        | Desktop     | [245b462c51](https://linux-hardware.org/?probe=245b462c51) | Oct 29, 2024 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [0718027c91](https://linux-hardware.org/?probe=0718027c91) | Oct 29, 2024 |
| Lenovo        | ThinkPad T495 20NKS02N00    | Notebook    | [ab02b5d5f4](https://linux-hardware.org/?probe=ab02b5d5f4) | Oct 29, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [4408314643](https://linux-hardware.org/?probe=4408314643) | Oct 29, 2024 |
| Lenovo        | ThinkPad T480s 20L8S4AE0... | Notebook    | [059a8899aa](https://linux-hardware.org/?probe=059a8899aa) | Oct 29, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [75652d2b07](https://linux-hardware.org/?probe=75652d2b07) | Oct 29, 2024 |
| Dell          | 0YJPT1 A00                  | Desktop     | [85c031940f](https://linux-hardware.org/?probe=85c031940f) | Oct 29, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [ff321ce619](https://linux-hardware.org/?probe=ff321ce619) | Oct 29, 2024 |
| Dell          | Precision 7510              | Notebook    | [eaa22e1a44](https://linux-hardware.org/?probe=eaa22e1a44) | Oct 29, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a7aeb69157](https://linux-hardware.org/?probe=a7aeb69157) | Oct 28, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [87f35bbeb2](https://linux-hardware.org/?probe=87f35bbeb2) | Oct 28, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f5d019253b](https://linux-hardware.org/?probe=f5d019253b) | Oct 28, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | Notebook    | [888b01a398](https://linux-hardware.org/?probe=888b01a398) | Oct 28, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [fd6eebf43f](https://linux-hardware.org/?probe=fd6eebf43f) | Oct 28, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [e03059b57f](https://linux-hardware.org/?probe=e03059b57f) | Oct 28, 2024 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [70ef57fad3](https://linux-hardware.org/?probe=70ef57fad3) | Oct 28, 2024 |
| Positivo      | N6440                       | Notebook    | [11f3656786](https://linux-hardware.org/?probe=11f3656786) | Oct 28, 2024 |
| GPD           | G1619-04                    | Notebook    | [8d4edea2b8](https://linux-hardware.org/?probe=8d4edea2b8) | Oct 28, 2024 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [701fca6089](https://linux-hardware.org/?probe=701fca6089) | Oct 28, 2024 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [f5edf5c6c7](https://linux-hardware.org/?probe=f5edf5c6c7) | Oct 28, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4acd5178ba](https://linux-hardware.org/?probe=4acd5178ba) | Oct 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [b48d086216](https://linux-hardware.org/?probe=b48d086216) | Oct 28, 2024 |
| HP            | 1825                        | Desktop     | [4c15d371f4](https://linux-hardware.org/?probe=4c15d371f4) | Oct 28, 2024 |
| HP            | ENVY Notebook               | Notebook    | [3570398b68](https://linux-hardware.org/?probe=3570398b68) | Oct 28, 2024 |
| Lenovo        | ThinkPad P1 20MES14G0M      | Notebook    | [518afdbf37](https://linux-hardware.org/?probe=518afdbf37) | Oct 28, 2024 |
| GPU Compan... | GWTC116-2                   | Notebook    | [3f3a6e5d57](https://linux-hardware.org/?probe=3f3a6e5d57) | Oct 28, 2024 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [5dad085952](https://linux-hardware.org/?probe=5dad085952) | Oct 28, 2024 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [c61011186f](https://linux-hardware.org/?probe=c61011186f) | Oct 28, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [954f4f20de](https://linux-hardware.org/?probe=954f4f20de) | Oct 28, 2024 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [99911b0889](https://linux-hardware.org/?probe=99911b0889) | Oct 28, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [82a2dc3146](https://linux-hardware.org/?probe=82a2dc3146) | Oct 27, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [a3f29d92d6](https://linux-hardware.org/?probe=a3f29d92d6) | Oct 27, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b36ba56662](https://linux-hardware.org/?probe=b36ba56662) | Oct 27, 2024 |
| Acer          | Aspire F5-573               | Notebook    | [127885eb15](https://linux-hardware.org/?probe=127885eb15) | Oct 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2468c65082](https://linux-hardware.org/?probe=2468c65082) | Oct 27, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [686f542a07](https://linux-hardware.org/?probe=686f542a07) | Oct 27, 2024 |
| Avell High... | Avell G1750 MUV / C65 MU... | Notebook    | [5efedd5ac9](https://linux-hardware.org/?probe=5efedd5ac9) | Oct 27, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [87db71f6fe](https://linux-hardware.org/?probe=87db71f6fe) | Oct 27, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [9521917abe](https://linux-hardware.org/?probe=9521917abe) | Oct 27, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [a2e892c47b](https://linux-hardware.org/?probe=a2e892c47b) | Oct 27, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [c157b5e147](https://linux-hardware.org/?probe=c157b5e147) | Oct 27, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [1f24cc9f1f](https://linux-hardware.org/?probe=1f24cc9f1f) | Oct 27, 2024 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [543cfc7093](https://linux-hardware.org/?probe=543cfc7093) | Oct 27, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [eb34cbfa3a](https://linux-hardware.org/?probe=eb34cbfa3a) | Oct 27, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccc9dc22cc](https://linux-hardware.org/?probe=ccc9dc22cc) | Oct 27, 2024 |
| THUNDEROBO... | 911AirD                     | Notebook    | [d14d084c2a](https://linux-hardware.org/?probe=d14d084c2a) | Oct 27, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [59e9489711](https://linux-hardware.org/?probe=59e9489711) | Oct 27, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [d0efe8b27c](https://linux-hardware.org/?probe=d0efe8b27c) | Oct 27, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7daf128f4f](https://linux-hardware.org/?probe=7daf128f4f) | Oct 27, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [cb5e0b58a1](https://linux-hardware.org/?probe=cb5e0b58a1) | Oct 27, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [aa0668c510](https://linux-hardware.org/?probe=aa0668c510) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [72a70468eb](https://linux-hardware.org/?probe=72a70468eb) | Oct 27, 2024 |
| Dell          | 0T0MHW A02                  | Desktop     | [4243a757a6](https://linux-hardware.org/?probe=4243a757a6) | Oct 27, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [03830ecacb](https://linux-hardware.org/?probe=03830ecacb) | Oct 27, 2024 |
| ASRock        | X570S PG Riptide            | Desktop     | [11404c6734](https://linux-hardware.org/?probe=11404c6734) | Oct 27, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [e7fe32e3ab](https://linux-hardware.org/?probe=e7fe32e3ab) | Oct 27, 2024 |
| ASRock        | X570S PG Riptide            | Desktop     | [e227559e6e](https://linux-hardware.org/?probe=e227559e6e) | Oct 27, 2024 |
| MACHINIST     | X79 Z9-D7 V2.0              | Desktop     | [435cdf99e6](https://linux-hardware.org/?probe=435cdf99e6) | Oct 27, 2024 |
| ASUSTek       | UN42                        | Desktop     | [87a8b82a09](https://linux-hardware.org/?probe=87a8b82a09) | Oct 27, 2024 |
| HONOR         | FRI-FXX                     | Notebook    | [762796bb28](https://linux-hardware.org/?probe=762796bb28) | Oct 27, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6001ee3845](https://linux-hardware.org/?probe=6001ee3845) | Oct 26, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [4dd89f3bf0](https://linux-hardware.org/?probe=4dd89f3bf0) | Oct 26, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [95fc0bceda](https://linux-hardware.org/?probe=95fc0bceda) | Oct 26, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [dbd73dea03](https://linux-hardware.org/?probe=dbd73dea03) | Oct 26, 2024 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [090cd0be16](https://linux-hardware.org/?probe=090cd0be16) | Oct 26, 2024 |
| ASRock        | Z68 Professional Gen3       | Desktop     | [e67350c095](https://linux-hardware.org/?probe=e67350c095) | Oct 26, 2024 |
| ASRock        | Z68 Professional Gen3       | Desktop     | [9a1f6eb1d2](https://linux-hardware.org/?probe=9a1f6eb1d2) | Oct 26, 2024 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [17bfc7765c](https://linux-hardware.org/?probe=17bfc7765c) | Oct 26, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [502ef34bb8](https://linux-hardware.org/?probe=502ef34bb8) | Oct 26, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [3096ec1041](https://linux-hardware.org/?probe=3096ec1041) | Oct 26, 2024 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [e0c4e36b31](https://linux-hardware.org/?probe=e0c4e36b31) | Oct 26, 2024 |
| Apple         | MacBookPro3,1               | Notebook    | [6dadd636e6](https://linux-hardware.org/?probe=6dadd636e6) | Oct 26, 2024 |
| Samsung       | 550P5C/550P7C               | Notebook    | [68724c7216](https://linux-hardware.org/?probe=68724c7216) | Oct 26, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [195e8d177d](https://linux-hardware.org/?probe=195e8d177d) | Oct 26, 2024 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b1fe176a80](https://linux-hardware.org/?probe=b1fe176a80) | Oct 26, 2024 |
| Dell          | 051FJ8 A02                  | Desktop     | [46e9a47329](https://linux-hardware.org/?probe=46e9a47329) | Oct 26, 2024 |
| HP            | 8594                        | Desktop     | [463ce43e0f](https://linux-hardware.org/?probe=463ce43e0f) | Oct 26, 2024 |
| HP            | 8594                        | Desktop     | [1fa231373e](https://linux-hardware.org/?probe=1fa231373e) | Oct 26, 2024 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [c10b72972e](https://linux-hardware.org/?probe=c10b72972e) | Oct 26, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [eb27912dd6](https://linux-hardware.org/?probe=eb27912dd6) | Oct 26, 2024 |
| RuggedPC      | RuggedBookJ61               | Tablet      | [e83e0e4efa](https://linux-hardware.org/?probe=e83e0e4efa) | Oct 26, 2024 |
| HONOR         | FRI-HXX                     | Notebook    | [6aa30c6282](https://linux-hardware.org/?probe=6aa30c6282) | Oct 25, 2024 |
| Google        | Lillipup                    | Notebook    | [bde8c2e9fc](https://linux-hardware.org/?probe=bde8c2e9fc) | Oct 25, 2024 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [f8b163024f](https://linux-hardware.org/?probe=f8b163024f) | Oct 25, 2024 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [c3eb35c1d9](https://linux-hardware.org/?probe=c3eb35c1d9) | Oct 25, 2024 |
| Dell          | Latitude E7440              | Notebook    | [59f882ef98](https://linux-hardware.org/?probe=59f882ef98) | Oct 25, 2024 |
| MSI           | GE70 2PE                    | Notebook    | [010126bf70](https://linux-hardware.org/?probe=010126bf70) | Oct 25, 2024 |
| Acer          | Aspire M5-581T              | Notebook    | [be8bfccf68](https://linux-hardware.org/?probe=be8bfccf68) | Oct 25, 2024 |
| Dell          | Latitude E7440              | Notebook    | [48182c2497](https://linux-hardware.org/?probe=48182c2497) | Oct 25, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [bc9ea310da](https://linux-hardware.org/?probe=bc9ea310da) | Oct 25, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [54b3dc0aff](https://linux-hardware.org/?probe=54b3dc0aff) | Oct 25, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [11d0ba0b30](https://linux-hardware.org/?probe=11d0ba0b30) | Oct 25, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [377b923625](https://linux-hardware.org/?probe=377b923625) | Oct 25, 2024 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [43126100f1](https://linux-hardware.org/?probe=43126100f1) | Oct 25, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [22b47c8319](https://linux-hardware.org/?probe=22b47c8319) | Oct 25, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [58feb4525c](https://linux-hardware.org/?probe=58feb4525c) | Oct 25, 2024 |
| Intel         | X99-D4 V2.0                 | Desktop     | [7275a5dadd](https://linux-hardware.org/?probe=7275a5dadd) | Oct 25, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [02c64fea57](https://linux-hardware.org/?probe=02c64fea57) | Oct 25, 2024 |
| Gigabyte      | X870 GAMING X WIFI7         | Desktop     | [5d7501e610](https://linux-hardware.org/?probe=5d7501e610) | Oct 25, 2024 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [cb465c5781](https://linux-hardware.org/?probe=cb465c5781) | Oct 25, 2024 |
| ASUSTek       | N501VW                      | Notebook    | [9a9324955b](https://linux-hardware.org/?probe=9a9324955b) | Oct 25, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [19ab71d343](https://linux-hardware.org/?probe=19ab71d343) | Oct 25, 2024 |
| Dell          | Latitude 5320               | Notebook    | [7302e97437](https://linux-hardware.org/?probe=7302e97437) | Oct 25, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [3facf7a704](https://linux-hardware.org/?probe=3facf7a704) | Oct 25, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [e63c2ce069](https://linux-hardware.org/?probe=e63c2ce069) | Oct 24, 2024 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [57bc043676](https://linux-hardware.org/?probe=57bc043676) | Oct 24, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2ebfa3b8c4](https://linux-hardware.org/?probe=2ebfa3b8c4) | Oct 24, 2024 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | Notebook    | [2bfca1dd72](https://linux-hardware.org/?probe=2bfca1dd72) | Oct 24, 2024 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [7c20ba304d](https://linux-hardware.org/?probe=7c20ba304d) | Oct 24, 2024 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [65f9d4fa03](https://linux-hardware.org/?probe=65f9d4fa03) | Oct 24, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [0fc1305fc4](https://linux-hardware.org/?probe=0fc1305fc4) | Oct 24, 2024 |
| Apple         | MacBookPro3,1               | Notebook    | [3866b77fbe](https://linux-hardware.org/?probe=3866b77fbe) | Oct 24, 2024 |
| Dell          | 0WWJRX A01                  | Desktop     | [2cd4d15e77](https://linux-hardware.org/?probe=2cd4d15e77) | Oct 24, 2024 |
| Micro Comp... | V3                          | Tablet      | [c2fe898a5e](https://linux-hardware.org/?probe=c2fe898a5e) | Oct 24, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [82a1bda877](https://linux-hardware.org/?probe=82a1bda877) | Oct 24, 2024 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [eb57d61b77](https://linux-hardware.org/?probe=eb57d61b77) | Oct 24, 2024 |
| Dell          | Inspiron M5010              | Notebook    | [f8441a09c6](https://linux-hardware.org/?probe=f8441a09c6) | Oct 24, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [f20e803485](https://linux-hardware.org/?probe=f20e803485) | Oct 24, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [6ca982f426](https://linux-hardware.org/?probe=6ca982f426) | Oct 24, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [79c5cfd875](https://linux-hardware.org/?probe=79c5cfd875) | Oct 24, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [4379516edc](https://linux-hardware.org/?probe=4379516edc) | Oct 24, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [2f43fcbe70](https://linux-hardware.org/?probe=2f43fcbe70) | Oct 24, 2024 |
| Pegatron      | Benicia                     | Desktop     | [fcb2ba0f2d](https://linux-hardware.org/?probe=fcb2ba0f2d) | Oct 24, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [264705b101](https://linux-hardware.org/?probe=264705b101) | Oct 24, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ad78b8bf6e](https://linux-hardware.org/?probe=ad78b8bf6e) | Oct 24, 2024 |
| Dell          | Precision M4500             | Notebook    | [b3d982c517](https://linux-hardware.org/?probe=b3d982c517) | Oct 24, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [5dc0afb6b3](https://linux-hardware.org/?probe=5dc0afb6b3) | Oct 24, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [0d3280fcc2](https://linux-hardware.org/?probe=0d3280fcc2) | Oct 24, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | Notebook    | [f697805e66](https://linux-hardware.org/?probe=f697805e66) | Oct 24, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [ee37abd88c](https://linux-hardware.org/?probe=ee37abd88c) | Oct 23, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [e906edeafc](https://linux-hardware.org/?probe=e906edeafc) | Oct 23, 2024 |
| Acer          | Aspire A15-41M              | Notebook    | [b5a44016cd](https://linux-hardware.org/?probe=b5a44016cd) | Oct 23, 2024 |
| Gigabyte      | H310M M.2                   | Desktop     | [2172d12593](https://linux-hardware.org/?probe=2172d12593) | Oct 23, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [b57fff773e](https://linux-hardware.org/?probe=b57fff773e) | Oct 23, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [e9b1483206](https://linux-hardware.org/?probe=e9b1483206) | Oct 23, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [77ef455f9e](https://linux-hardware.org/?probe=77ef455f9e) | Oct 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d52c99f09c](https://linux-hardware.org/?probe=d52c99f09c) | Oct 23, 2024 |
| Gigabyte      | H310M M.2                   | Desktop     | [10acadc6ea](https://linux-hardware.org/?probe=10acadc6ea) | Oct 23, 2024 |
| Positivo B... | VJFE55F11X-B0211H           | Notebook    | [e018b67f9b](https://linux-hardware.org/?probe=e018b67f9b) | Oct 23, 2024 |
| Acer          | TravelMate 5744Z            | Notebook    | [ef9fc07cd1](https://linux-hardware.org/?probe=ef9fc07cd1) | Oct 23, 2024 |
| Gigabyte      | H410M H V2                  | Desktop     | [c054528eeb](https://linux-hardware.org/?probe=c054528eeb) | Oct 23, 2024 |
| PC Special... | GM6PC0X                     | Notebook    | [1c0fa981a9](https://linux-hardware.org/?probe=1c0fa981a9) | Oct 23, 2024 |
| Positivo      | C464C                       | Convertible | [3c54c0d07a](https://linux-hardware.org/?probe=3c54c0d07a) | Oct 23, 2024 |
| Lenovo        | ThinkPad X270 20HMS2C002    | Notebook    | [3bd05e0ee9](https://linux-hardware.org/?probe=3bd05e0ee9) | Oct 23, 2024 |
| Jumper        | EZbook                      | Notebook    | [5532770efb](https://linux-hardware.org/?probe=5532770efb) | Oct 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [071f9330d7](https://linux-hardware.org/?probe=071f9330d7) | Oct 23, 2024 |
| ASUSTek       | ROG Maximus Z790 FORMULA    | Desktop     | [325eceb3a6](https://linux-hardware.org/?probe=325eceb3a6) | Oct 23, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d416e20028](https://linux-hardware.org/?probe=d416e20028) | Oct 23, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [6d336318c3](https://linux-hardware.org/?probe=6d336318c3) | Oct 23, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3fbfc692b5](https://linux-hardware.org/?probe=3fbfc692b5) | Oct 23, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [edbea4a1b6](https://linux-hardware.org/?probe=edbea4a1b6) | Oct 23, 2024 |
| LG Electro... | 15ZD90S-GX56K               | Notebook    | [e9630cc537](https://linux-hardware.org/?probe=e9630cc537) | Oct 23, 2024 |
| HP            | Notebook                    | Notebook    | [c77d9407e6](https://linux-hardware.org/?probe=c77d9407e6) | Oct 23, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d009d7f8d5](https://linux-hardware.org/?probe=d009d7f8d5) | Oct 23, 2024 |
| Dell          | Precision M4500             | Notebook    | [655b69cf4e](https://linux-hardware.org/?probe=655b69cf4e) | Oct 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [f39ba553f4](https://linux-hardware.org/?probe=f39ba553f4) | Oct 23, 2024 |
| Dell          | Inspiron 15 3535            | Notebook    | [54b7377997](https://linux-hardware.org/?probe=54b7377997) | Oct 23, 2024 |
| Dell          | Inspiron 15 3535            | Notebook    | [c38ffd4514](https://linux-hardware.org/?probe=c38ffd4514) | Oct 23, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1aba2900e3](https://linux-hardware.org/?probe=1aba2900e3) | Oct 23, 2024 |
| Alienware     | m16 R1                      | Notebook    | [955ee0df4a](https://linux-hardware.org/?probe=955ee0df4a) | Oct 23, 2024 |
| Alienware     | m16 R1                      | Notebook    | [d871f524b4](https://linux-hardware.org/?probe=d871f524b4) | Oct 23, 2024 |
| Alienware     | m16 R1                      | Notebook    | [3a959e0d23](https://linux-hardware.org/?probe=3a959e0d23) | Oct 23, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1b10590afd](https://linux-hardware.org/?probe=1b10590afd) | Oct 22, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0fd44cbc96](https://linux-hardware.org/?probe=0fd44cbc96) | Oct 22, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 3 ... | Convertible | [42423b8932](https://linux-hardware.org/?probe=42423b8932) | Oct 22, 2024 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [96ff5d9648](https://linux-hardware.org/?probe=96ff5d9648) | Oct 22, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [fadc6eb1c5](https://linux-hardware.org/?probe=fadc6eb1c5) | Oct 22, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9d3eacadee](https://linux-hardware.org/?probe=9d3eacadee) | Oct 22, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [79407ce2bb](https://linux-hardware.org/?probe=79407ce2bb) | Oct 22, 2024 |
| Lenovo        | ThinkPad T580 20L9001YGE    | Notebook    | [9710a2a195](https://linux-hardware.org/?probe=9710a2a195) | Oct 22, 2024 |
| Insyde        | KX210                       | Notebook    | [12b2392210](https://linux-hardware.org/?probe=12b2392210) | Oct 22, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [279ec9d49f](https://linux-hardware.org/?probe=279ec9d49f) | Oct 22, 2024 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [27c3ff8bf4](https://linux-hardware.org/?probe=27c3ff8bf4) | Oct 22, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [a4417e3060](https://linux-hardware.org/?probe=a4417e3060) | Oct 22, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [2c7b38c7b2](https://linux-hardware.org/?probe=2c7b38c7b2) | Oct 22, 2024 |
| Dell          | Vostro 3550                 | Notebook    | [855f0534c1](https://linux-hardware.org/?probe=855f0534c1) | Oct 22, 2024 |
| GPU Compan... | GWTC116-2                   | Notebook    | [149b7cb745](https://linux-hardware.org/?probe=149b7cb745) | Oct 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f5b00c79d2](https://linux-hardware.org/?probe=f5b00c79d2) | Oct 22, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [9dc1b13a4c](https://linux-hardware.org/?probe=9dc1b13a4c) | Oct 22, 2024 |
| Dell          | Precision M4600             | Notebook    | [93cbb268c2](https://linux-hardware.org/?probe=93cbb268c2) | Oct 22, 2024 |
| Alienware     | m18 R2                      | Notebook    | [e39538339d](https://linux-hardware.org/?probe=e39538339d) | Oct 22, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [324b4b4c13](https://linux-hardware.org/?probe=324b4b4c13) | Oct 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [5fde0c28f7](https://linux-hardware.org/?probe=5fde0c28f7) | Oct 22, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [082cb94081](https://linux-hardware.org/?probe=082cb94081) | Oct 22, 2024 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [bc62b4a778](https://linux-hardware.org/?probe=bc62b4a778) | Oct 22, 2024 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [b73c211fdf](https://linux-hardware.org/?probe=b73c211fdf) | Oct 21, 2024 |
| HP            | 89B5 A                      | Desktop     | [9c683ac116](https://linux-hardware.org/?probe=9c683ac116) | Oct 21, 2024 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [cfed3dc7f9](https://linux-hardware.org/?probe=cfed3dc7f9) | Oct 21, 2024 |
| Dell          | Inspiron 5579               | Notebook    | [abd9463583](https://linux-hardware.org/?probe=abd9463583) | Oct 21, 2024 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [4750986fce](https://linux-hardware.org/?probe=4750986fce) | Oct 21, 2024 |
| Dell          | Latitude 5430               | Notebook    | [3519e7a530](https://linux-hardware.org/?probe=3519e7a530) | Oct 21, 2024 |
| ASRock        | Z690 PG Velocita            | Desktop     | [d6f7b880a7](https://linux-hardware.org/?probe=d6f7b880a7) | Oct 21, 2024 |
| Lenovo        | B50-70 20384                | Notebook    | [09f5eef685](https://linux-hardware.org/?probe=09f5eef685) | Oct 21, 2024 |
| Dell          | Latitude 5510               | Notebook    | [98036add3f](https://linux-hardware.org/?probe=98036add3f) | Oct 21, 2024 |
| HP            | 250 15.6 inch G10 Notebo... | Notebook    | [9e94170315](https://linux-hardware.org/?probe=9e94170315) | Oct 21, 2024 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [ea1b8dc52a](https://linux-hardware.org/?probe=ea1b8dc52a) | Oct 21, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [9d3cba48c5](https://linux-hardware.org/?probe=9d3cba48c5) | Oct 21, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [7b9ad509e7](https://linux-hardware.org/?probe=7b9ad509e7) | Oct 21, 2024 |
| System76      | Pangolin                    | Notebook    | [dfaff4a65b](https://linux-hardware.org/?probe=dfaff4a65b) | Oct 21, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1c61630c00](https://linux-hardware.org/?probe=1c61630c00) | Oct 20, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [757f809c22](https://linux-hardware.org/?probe=757f809c22) | Oct 20, 2024 |
| ASUSTek       | K73BY                       | Notebook    | [183ebc94a6](https://linux-hardware.org/?probe=183ebc94a6) | Oct 20, 2024 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [2ec391ffdc](https://linux-hardware.org/?probe=2ec391ffdc) | Oct 20, 2024 |
| Supermicro    | X9DR3-F                     | Desktop     | [5997bb2d87](https://linux-hardware.org/?probe=5997bb2d87) | Oct 20, 2024 |
| MSI           | Alpha 17 C7VG               | Notebook    | [dbcee0fcec](https://linux-hardware.org/?probe=dbcee0fcec) | Oct 20, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [c2c4b8de25](https://linux-hardware.org/?probe=c2c4b8de25) | Oct 20, 2024 |
| Dell          | 0D02VH A01                  | Desktop     | [40e0ae26f3](https://linux-hardware.org/?probe=40e0ae26f3) | Oct 20, 2024 |
| Lenovo        | ThinkPad X270 20HN0016GE    | Notebook    | [6d342bda35](https://linux-hardware.org/?probe=6d342bda35) | Oct 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3795fe9a2b](https://linux-hardware.org/?probe=3795fe9a2b) | Oct 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [90de471428](https://linux-hardware.org/?probe=90de471428) | Oct 20, 2024 |
| Sony          | SVD11223CXB                 | Notebook    | [6b3e7fa3c6](https://linux-hardware.org/?probe=6b3e7fa3c6) | Oct 20, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [e479bd7415](https://linux-hardware.org/?probe=e479bd7415) | Oct 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8S05A0... | Notebook    | [50c322a885](https://linux-hardware.org/?probe=50c322a885) | Oct 20, 2024 |
| MSI           | GT72S 6QE                   | Notebook    | [0cfe32ce18](https://linux-hardware.org/?probe=0cfe32ce18) | Oct 20, 2024 |
| Dell          | Precision 3570              | Notebook    | [1e848b6e97](https://linux-hardware.org/?probe=1e848b6e97) | Oct 20, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [34b8e69dcc](https://linux-hardware.org/?probe=34b8e69dcc) | Oct 20, 2024 |
| Dell          | Latitude E6400              | Notebook    | [45684f9885](https://linux-hardware.org/?probe=45684f9885) | Oct 20, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c9b683dba6](https://linux-hardware.org/?probe=c9b683dba6) | Oct 20, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | Notebook    | [8b03dd3ef4](https://linux-hardware.org/?probe=8b03dd3ef4) | Oct 19, 2024 |
| Dell          | 0KV3RP A00                  | Desktop     | [416d9daf78](https://linux-hardware.org/?probe=416d9daf78) | Oct 19, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [503a2f785d](https://linux-hardware.org/?probe=503a2f785d) | Oct 19, 2024 |
| MSI           | MS-B9051                    | All in one  | [edb7c3720d](https://linux-hardware.org/?probe=edb7c3720d) | Oct 19, 2024 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [674a976e7b](https://linux-hardware.org/?probe=674a976e7b) | Oct 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [71f101364f](https://linux-hardware.org/?probe=71f101364f) | Oct 19, 2024 |
| TECNO         | WinPad 2                    | Notebook    | [1cb685a8f9](https://linux-hardware.org/?probe=1cb685a8f9) | Oct 19, 2024 |
| Gigabyte      | AORUS 16X ASG               | Notebook    | [2d585acb5b](https://linux-hardware.org/?probe=2d585acb5b) | Oct 19, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b25ed1f0fb](https://linux-hardware.org/?probe=b25ed1f0fb) | Oct 19, 2024 |
| MSI           | Z87M GAMING                 | Desktop     | [0b431f4f2e](https://linux-hardware.org/?probe=0b431f4f2e) | Oct 19, 2024 |
| HP            | Elite x2 1013 G3            | Tablet      | [3428068151](https://linux-hardware.org/?probe=3428068151) | Oct 19, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [60584277b0](https://linux-hardware.org/?probe=60584277b0) | Oct 19, 2024 |
| GPU Compan... | GWTC51427                   | Notebook    | [9a2db06e84](https://linux-hardware.org/?probe=9a2db06e84) | Oct 19, 2024 |
| Dell          | Latitude 5540               | Notebook    | [ba75f2134f](https://linux-hardware.org/?probe=ba75f2134f) | Oct 19, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [ba795881fe](https://linux-hardware.org/?probe=ba795881fe) | Oct 19, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [8b50e7ae55](https://linux-hardware.org/?probe=8b50e7ae55) | Oct 19, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [606e0317d4](https://linux-hardware.org/?probe=606e0317d4) | Oct 19, 2024 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [6e59218d2a](https://linux-hardware.org/?probe=6e59218d2a) | Oct 19, 2024 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [4d27146d89](https://linux-hardware.org/?probe=4d27146d89) | Oct 18, 2024 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [0f32c90816](https://linux-hardware.org/?probe=0f32c90816) | Oct 18, 2024 |
| Razer         | Blade Stealth               | Notebook    | [30a96f6443](https://linux-hardware.org/?probe=30a96f6443) | Oct 18, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [339f546673](https://linux-hardware.org/?probe=339f546673) | Oct 18, 2024 |
| HP            | Laptop 15t-dy200            | Notebook    | [a790abfc93](https://linux-hardware.org/?probe=a790abfc93) | Oct 18, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | Notebook    | [d137ac3a49](https://linux-hardware.org/?probe=d137ac3a49) | Oct 18, 2024 |
| ASUSTek       | GL503VS                     | Notebook    | [c2b42dfce0](https://linux-hardware.org/?probe=c2b42dfce0) | Oct 18, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [876b2c0c0d](https://linux-hardware.org/?probe=876b2c0c0d) | Oct 18, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [4cc4056c72](https://linux-hardware.org/?probe=4cc4056c72) | Oct 18, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [53b1e19267](https://linux-hardware.org/?probe=53b1e19267) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MDS... | Notebook    | [2d00c7ffe3](https://linux-hardware.org/?probe=2d00c7ffe3) | Oct 18, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c8ea9da7d2](https://linux-hardware.org/?probe=c8ea9da7d2) | Oct 18, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [2b0f461f62](https://linux-hardware.org/?probe=2b0f461f62) | Oct 18, 2024 |
| Dell          | Latitude E6540              | Notebook    | [6211512b05](https://linux-hardware.org/?probe=6211512b05) | Oct 18, 2024 |
| HP            | 8299                        | Desktop     | [3ccb300bbf](https://linux-hardware.org/?probe=3ccb300bbf) | Oct 18, 2024 |
| Lenovo        | ThinkPad E14 20RA0016PB     | Notebook    | [99c42f786e](https://linux-hardware.org/?probe=99c42f786e) | Oct 18, 2024 |
| Radxa         | ROCK 5 Model B              | Soc         | [3164eae06e](https://linux-hardware.org/?probe=3164eae06e) | Oct 18, 2024 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [dc1c336787](https://linux-hardware.org/?probe=dc1c336787) | Oct 18, 2024 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f2ab342fab](https://linux-hardware.org/?probe=f2ab342fab) | Oct 18, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [1560c4ac35](https://linux-hardware.org/?probe=1560c4ac35) | Oct 18, 2024 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [e9c7afd15b](https://linux-hardware.org/?probe=e9c7afd15b) | Oct 18, 2024 |
| LG Electro... | S425-G.BE35P1               | Notebook    | [31259d6063](https://linux-hardware.org/?probe=31259d6063) | Oct 18, 2024 |
| Lenovo        | ThinkPad W540 20BHS09Y07    | Notebook    | [7d9781e63e](https://linux-hardware.org/?probe=7d9781e63e) | Oct 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [54f11d9d18](https://linux-hardware.org/?probe=54f11d9d18) | Oct 18, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [7e1677822a](https://linux-hardware.org/?probe=7e1677822a) | Oct 18, 2024 |
| ASUSTek       | GL503VS                     | Notebook    | [59987a96a2](https://linux-hardware.org/?probe=59987a96a2) | Oct 17, 2024 |
| HP            | Stream Laptop 14-cb101np    | Notebook    | [e8bc94e534](https://linux-hardware.org/?probe=e8bc94e534) | Oct 17, 2024 |
| Lenovo        | ThinkPad X230 2324FU0       | Notebook    | [1560655db4](https://linux-hardware.org/?probe=1560655db4) | Oct 17, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [b7c7919aeb](https://linux-hardware.org/?probe=b7c7919aeb) | Oct 17, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [878ae06df8](https://linux-hardware.org/?probe=878ae06df8) | Oct 17, 2024 |
| Dell          | 0KRC95 A02                  | Desktop     | [06364479a4](https://linux-hardware.org/?probe=06364479a4) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [537a4d29f8](https://linux-hardware.org/?probe=537a4d29f8) | Oct 17, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [581e0cc59d](https://linux-hardware.org/?probe=581e0cc59d) | Oct 17, 2024 |
| Insyde        | BayTrail                    | Notebook    | [83fca1d770](https://linux-hardware.org/?probe=83fca1d770) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [fe6cbc762f](https://linux-hardware.org/?probe=fe6cbc762f) | Oct 17, 2024 |
| BAKED         | P65xRP                      | Notebook    | [9d26712e83](https://linux-hardware.org/?probe=9d26712e83) | Oct 17, 2024 |
| BAKED         | P65xRP                      | Notebook    | [b843af1c15](https://linux-hardware.org/?probe=b843af1c15) | Oct 17, 2024 |
| MSI           | Z97 GAMING 7                | Desktop     | [b7458e064e](https://linux-hardware.org/?probe=b7458e064e) | Oct 17, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [df2b41f937](https://linux-hardware.org/?probe=df2b41f937) | Oct 17, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [815aad1371](https://linux-hardware.org/?probe=815aad1371) | Oct 17, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | Notebook    | [a15c3e921c](https://linux-hardware.org/?probe=a15c3e921c) | Oct 17, 2024 |
| Samsung       | Galaxy Book 12              | Tablet      | [f27dfbbbfb](https://linux-hardware.org/?probe=f27dfbbbfb) | Oct 17, 2024 |
| Shenzhen M... | AHBTB                       | Desktop     | [5db3f12db9](https://linux-hardware.org/?probe=5db3f12db9) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [63a9495ac8](https://linux-hardware.org/?probe=63a9495ac8) | Oct 17, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [240270535b](https://linux-hardware.org/?probe=240270535b) | Oct 17, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [de2ae00f42](https://linux-hardware.org/?probe=de2ae00f42) | Oct 17, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b6c163527d](https://linux-hardware.org/?probe=b6c163527d) | Oct 17, 2024 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [53be6a83c8](https://linux-hardware.org/?probe=53be6a83c8) | Oct 17, 2024 |
| Alienware     | 17                          | Notebook    | [6923888471](https://linux-hardware.org/?probe=6923888471) | Oct 17, 2024 |
| Alienware     | 17                          | Notebook    | [9c5979e59a](https://linux-hardware.org/?probe=9c5979e59a) | Oct 17, 2024 |
| Samsung       | 940XGK                      | Notebook    | [e6b94cea06](https://linux-hardware.org/?probe=e6b94cea06) | Oct 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [117d3104ce](https://linux-hardware.org/?probe=117d3104ce) | Oct 17, 2024 |
| AMD           | A520                        | Desktop     | [e10a74a5bc](https://linux-hardware.org/?probe=e10a74a5bc) | Oct 16, 2024 |
| Lenovo        | ThinkPad P1 Gen 7 21KV00... | Notebook    | [3af3fb7243](https://linux-hardware.org/?probe=3af3fb7243) | Oct 16, 2024 |
| Lenovo        | IdeaPad Pro 5 16AHP9 83D... | Notebook    | [818bcae40b](https://linux-hardware.org/?probe=818bcae40b) | Oct 16, 2024 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [db9625869b](https://linux-hardware.org/?probe=db9625869b) | Oct 16, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [6ae8586613](https://linux-hardware.org/?probe=6ae8586613) | Oct 16, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [13b45a29d3](https://linux-hardware.org/?probe=13b45a29d3) | Oct 16, 2024 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [ae0ebdeca8](https://linux-hardware.org/?probe=ae0ebdeca8) | Oct 16, 2024 |
| MSI           | PRO Z790-S WIFI             | Desktop     | [067881f9af](https://linux-hardware.org/?probe=067881f9af) | Oct 16, 2024 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [23c459c9f0](https://linux-hardware.org/?probe=23c459c9f0) | Oct 16, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [47c8fdec6e](https://linux-hardware.org/?probe=47c8fdec6e) | Oct 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | Notebook    | [553cb8fd6e](https://linux-hardware.org/?probe=553cb8fd6e) | Oct 16, 2024 |
| MSI           | MS-7388                     | Desktop     | [422aa52e15](https://linux-hardware.org/?probe=422aa52e15) | Oct 16, 2024 |
| HP            | 339A                        | Desktop     | [f0f9699d37](https://linux-hardware.org/?probe=f0f9699d37) | Oct 16, 2024 |
| Toshiba       | TECRA R950                  | Notebook    | [4c64d6dc1c](https://linux-hardware.org/?probe=4c64d6dc1c) | Oct 16, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [c110e51329](https://linux-hardware.org/?probe=c110e51329) | Oct 16, 2024 |
| Google        | Kano                        | Notebook    | [81f269cd85](https://linux-hardware.org/?probe=81f269cd85) | Oct 16, 2024 |
| Dell          | G16 7630                    | Notebook    | [e2f9e14b38](https://linux-hardware.org/?probe=e2f9e14b38) | Oct 16, 2024 |
| ASUSTek       | H170-PLUS D3                | Desktop     | [379530fc58](https://linux-hardware.org/?probe=379530fc58) | Oct 16, 2024 |
| ASRock        | B650I Lightning WiFi        | Desktop     | [8444ecbd6e](https://linux-hardware.org/?probe=8444ecbd6e) | Oct 16, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [5b988280c5](https://linux-hardware.org/?probe=5b988280c5) | Oct 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [91835aeee5](https://linux-hardware.org/?probe=91835aeee5) | Oct 16, 2024 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [754ae30695](https://linux-hardware.org/?probe=754ae30695) | Oct 16, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [721f67c310](https://linux-hardware.org/?probe=721f67c310) | Oct 15, 2024 |
| Dell          | Latitude 3400               | Notebook    | [52efd2e71e](https://linux-hardware.org/?probe=52efd2e71e) | Oct 15, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [d2c23ff5c0](https://linux-hardware.org/?probe=d2c23ff5c0) | Oct 15, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [a344c71a28](https://linux-hardware.org/?probe=a344c71a28) | Oct 15, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [80de2d9f80](https://linux-hardware.org/?probe=80de2d9f80) | Oct 15, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [cac6b26403](https://linux-hardware.org/?probe=cac6b26403) | Oct 15, 2024 |
| HP            | 339A                        | Desktop     | [f141003cda](https://linux-hardware.org/?probe=f141003cda) | Oct 15, 2024 |
| Dell          | Precision M6500             | Notebook    | [102728b70f](https://linux-hardware.org/?probe=102728b70f) | Oct 15, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [09034dd10d](https://linux-hardware.org/?probe=09034dd10d) | Oct 15, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a156cbf522](https://linux-hardware.org/?probe=a156cbf522) | Oct 15, 2024 |
| Lenovo        | ThinkBook 16 G6+ IMH 21L... | Notebook    | [209cffc8c6](https://linux-hardware.org/?probe=209cffc8c6) | Oct 15, 2024 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [293f156926](https://linux-hardware.org/?probe=293f156926) | Oct 15, 2024 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | Notebook    | [8159b5a478](https://linux-hardware.org/?probe=8159b5a478) | Oct 15, 2024 |
| ASUSTek       | Z170-PREMIUM                | Desktop     | [4f43db93a3](https://linux-hardware.org/?probe=4f43db93a3) | Oct 15, 2024 |
| Dell          | Precision M6500             | Notebook    | [5f6091daf1](https://linux-hardware.org/?probe=5f6091daf1) | Oct 15, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9ae59f6ed9](https://linux-hardware.org/?probe=9ae59f6ed9) | Oct 14, 2024 |
| Dell          | Latitude E6410              | Notebook    | [d3476d39f8](https://linux-hardware.org/?probe=d3476d39f8) | Oct 14, 2024 |
| Intel         | NUC12WSBi3 M36953-304       | Mini pc     | [af52008bee](https://linux-hardware.org/?probe=af52008bee) | Oct 14, 2024 |
| Acer          | Aspire V5-471               | Notebook    | [47d623d405](https://linux-hardware.org/?probe=47d623d405) | Oct 14, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2c3c06a948](https://linux-hardware.org/?probe=2c3c06a948) | Oct 14, 2024 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [752eb6d636](https://linux-hardware.org/?probe=752eb6d636) | Oct 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7e6947f44f](https://linux-hardware.org/?probe=7e6947f44f) | Oct 14, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [af042b9879](https://linux-hardware.org/?probe=af042b9879) | Oct 14, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [544aea53d8](https://linux-hardware.org/?probe=544aea53d8) | Oct 14, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a9c9a656c3](https://linux-hardware.org/?probe=a9c9a656c3) | Oct 14, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [4379a607c2](https://linux-hardware.org/?probe=4379a607c2) | Oct 14, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [ea6a9feccf](https://linux-hardware.org/?probe=ea6a9feccf) | Oct 14, 2024 |
| Acer          | Aspire ES1-521              | Notebook    | [152353aceb](https://linux-hardware.org/?probe=152353aceb) | Oct 14, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [f43ac657a5](https://linux-hardware.org/?probe=f43ac657a5) | Oct 14, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [7c2fed3e80](https://linux-hardware.org/?probe=7c2fed3e80) | Oct 14, 2024 |
| Gigabyte      | X58A-UD5                    | Desktop     | [cdab8fc3a6](https://linux-hardware.org/?probe=cdab8fc3a6) | Oct 14, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [8cbc4ad7e7](https://linux-hardware.org/?probe=8cbc4ad7e7) | Oct 14, 2024 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | Desktop     | [c7983f7064](https://linux-hardware.org/?probe=c7983f7064) | Oct 14, 2024 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | Desktop     | [b1b2088801](https://linux-hardware.org/?probe=b1b2088801) | Oct 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [2408ee5d67](https://linux-hardware.org/?probe=2408ee5d67) | Oct 14, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [c868f26f17](https://linux-hardware.org/?probe=c868f26f17) | Oct 13, 2024 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [64e5571acf](https://linux-hardware.org/?probe=64e5571acf) | Oct 13, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [2131d0a645](https://linux-hardware.org/?probe=2131d0a645) | Oct 13, 2024 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [636e84ff70](https://linux-hardware.org/?probe=636e84ff70) | Oct 13, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [12c27f8091](https://linux-hardware.org/?probe=12c27f8091) | Oct 13, 2024 |
| Lenovo        | ThinkCentre M91p 4524W1K    | Desktop     | [8336e2d523](https://linux-hardware.org/?probe=8336e2d523) | Oct 13, 2024 |
| Dell          | 0R1PCR A00                  | Desktop     | [17f0e12923](https://linux-hardware.org/?probe=17f0e12923) | Oct 13, 2024 |
| Supermicro    | C7H170-M                    | Server      | [1cece2a441](https://linux-hardware.org/?probe=1cece2a441) | Oct 13, 2024 |
| Lenovo        | ThinkPad T440p 20AWS1HM0... | Notebook    | [3018939080](https://linux-hardware.org/?probe=3018939080) | Oct 13, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [f20095e3af](https://linux-hardware.org/?probe=f20095e3af) | Oct 13, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [c848e4ca8f](https://linux-hardware.org/?probe=c848e4ca8f) | Oct 13, 2024 |
| MSI           | GT72S 6QE                   | Notebook    | [dd761bfc6f](https://linux-hardware.org/?probe=dd761bfc6f) | Oct 13, 2024 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [2f02059daf](https://linux-hardware.org/?probe=2f02059daf) | Oct 13, 2024 |
| Dell          | 0CRWCR A01                  | All in one  | [aeaa9dbcfc](https://linux-hardware.org/?probe=aeaa9dbcfc) | Oct 13, 2024 |
| HP            | 1790                        | Desktop     | [4f639e54c8](https://linux-hardware.org/?probe=4f639e54c8) | Oct 13, 2024 |
| ASUSTek       | Z87-PRO                     | Desktop     | [07d27ff3f5](https://linux-hardware.org/?probe=07d27ff3f5) | Oct 13, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d16d1a85ec](https://linux-hardware.org/?probe=d16d1a85ec) | Oct 13, 2024 |
| Samsung       | 305V4A/305V5A               | Notebook    | [75ad76a7fb](https://linux-hardware.org/?probe=75ad76a7fb) | Oct 13, 2024 |
| AMI           | Intel                       | Desktop     | [b063594127](https://linux-hardware.org/?probe=b063594127) | Oct 13, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b4a4852367](https://linux-hardware.org/?probe=b4a4852367) | Oct 13, 2024 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [75ab1b387e](https://linux-hardware.org/?probe=75ab1b387e) | Oct 13, 2024 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [e87b219656](https://linux-hardware.org/?probe=e87b219656) | Oct 13, 2024 |
| MSI           | GF65 Thin 10UE              | Notebook    | [a6c169c33b](https://linux-hardware.org/?probe=a6c169c33b) | Oct 13, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [f0e04419cd](https://linux-hardware.org/?probe=f0e04419cd) | Oct 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [5f66268b4a](https://linux-hardware.org/?probe=5f66268b4a) | Oct 13, 2024 |
| HP            | ProBook 4540s               | Notebook    | [38d30c1f16](https://linux-hardware.org/?probe=38d30c1f16) | Oct 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [dddb1827ce](https://linux-hardware.org/?probe=dddb1827ce) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming FX705GM_PX705... | Notebook    | [a66833f881](https://linux-hardware.org/?probe=a66833f881) | Oct 12, 2024 |
| HP            | mt41                        | Notebook    | [56a4716804](https://linux-hardware.org/?probe=56a4716804) | Oct 12, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ccf9ef6105](https://linux-hardware.org/?probe=ccf9ef6105) | Oct 12, 2024 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [d9983b094d](https://linux-hardware.org/?probe=d9983b094d) | Oct 12, 2024 |
| RuggedPC      | RuggedBookJ61               | Tablet      | [459846fbe7](https://linux-hardware.org/?probe=459846fbe7) | Oct 12, 2024 |
| Sony          | VAIO                        | All in one  | [5bb2e62791](https://linux-hardware.org/?probe=5bb2e62791) | Oct 12, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c331d0b34d](https://linux-hardware.org/?probe=c331d0b34d) | Oct 12, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e1c4a5a26f](https://linux-hardware.org/?probe=e1c4a5a26f) | Oct 12, 2024 |
| Samsung       | 270E5G/270E5U               | Notebook    | [5c391c318b](https://linux-hardware.org/?probe=5c391c318b) | Oct 12, 2024 |
| Google        | Lindar                      | Notebook    | [248279b8b2](https://linux-hardware.org/?probe=248279b8b2) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 20HMS2C002    | Notebook    | [1718617fcc](https://linux-hardware.org/?probe=1718617fcc) | Oct 12, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [7700aaaef5](https://linux-hardware.org/?probe=7700aaaef5) | Oct 12, 2024 |
| ASUSTek       | K93SV                       | Notebook    | [4b16fe7309](https://linux-hardware.org/?probe=4b16fe7309) | Oct 12, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [73af5119fe](https://linux-hardware.org/?probe=73af5119fe) | Oct 12, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [729c7d3da6](https://linux-hardware.org/?probe=729c7d3da6) | Oct 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [0df50eaff2](https://linux-hardware.org/?probe=0df50eaff2) | Oct 12, 2024 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [1e827886c1](https://linux-hardware.org/?probe=1e827886c1) | Oct 12, 2024 |
| RuggedPC      | RuggedBookJ61               | Tablet      | [4fdb3d5ad7](https://linux-hardware.org/?probe=4fdb3d5ad7) | Oct 12, 2024 |
| Positivo      | N3240                       | Notebook    | [9c315c6ddb](https://linux-hardware.org/?probe=9c315c6ddb) | Oct 12, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [f5ef0479ee](https://linux-hardware.org/?probe=f5ef0479ee) | Oct 12, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7e989cb766](https://linux-hardware.org/?probe=7e989cb766) | Oct 11, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [25f5532900](https://linux-hardware.org/?probe=25f5532900) | Oct 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [1469fc65e2](https://linux-hardware.org/?probe=1469fc65e2) | Oct 11, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [5ff6f3f1a8](https://linux-hardware.org/?probe=5ff6f3f1a8) | Oct 11, 2024 |
| Dell          | Precision 7530              | Notebook    | [ca12dbc1be](https://linux-hardware.org/?probe=ca12dbc1be) | Oct 11, 2024 |
| MSI           | MS-7388                     | Desktop     | [99b0ab9f8b](https://linux-hardware.org/?probe=99b0ab9f8b) | Oct 11, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [25a6d436a9](https://linux-hardware.org/?probe=25a6d436a9) | Oct 11, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [e7a4183763](https://linux-hardware.org/?probe=e7a4183763) | Oct 11, 2024 |
| Micro Comp... | HX100G                      | Desktop     | [2e97a25812](https://linux-hardware.org/?probe=2e97a25812) | Oct 11, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [cef125c743](https://linux-hardware.org/?probe=cef125c743) | Oct 11, 2024 |
| Gigabyte      | B550 GAMING X               | Desktop     | [689256be03](https://linux-hardware.org/?probe=689256be03) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c9a54bde4c](https://linux-hardware.org/?probe=c9a54bde4c) | Oct 11, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [4a3a5090d1](https://linux-hardware.org/?probe=4a3a5090d1) | Oct 11, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9aeb802c66](https://linux-hardware.org/?probe=9aeb802c66) | Oct 11, 2024 |
| Lenovo        | ThinkBook 15p G2 ITH 21B... | Notebook    | [0da47f72b3](https://linux-hardware.org/?probe=0da47f72b3) | Oct 11, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [f6d8e2dbf5](https://linux-hardware.org/?probe=f6d8e2dbf5) | Oct 11, 2024 |
| HP            | ProLiant MicroServer        | Desktop     | [318bfb0ac5](https://linux-hardware.org/?probe=318bfb0ac5) | Oct 11, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [61b9e50d90](https://linux-hardware.org/?probe=61b9e50d90) | Oct 11, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [299ca005bc](https://linux-hardware.org/?probe=299ca005bc) | Oct 11, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7637f72cf](https://linux-hardware.org/?probe=b7637f72cf) | Oct 11, 2024 |
| Lenovo        | ThinkPad T560 20FJS3HL00    | Notebook    | [3c122324a9](https://linux-hardware.org/?probe=3c122324a9) | Oct 11, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [0e48e35cb0](https://linux-hardware.org/?probe=0e48e35cb0) | Oct 11, 2024 |
| Dell          | 0YXT71 A03                  | Desktop     | [7db9888f0d](https://linux-hardware.org/?probe=7db9888f0d) | Oct 11, 2024 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [2a034b4114](https://linux-hardware.org/?probe=2a034b4114) | Oct 11, 2024 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [b7355dce23](https://linux-hardware.org/?probe=b7355dce23) | Oct 11, 2024 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [daf9be143c](https://linux-hardware.org/?probe=daf9be143c) | Oct 11, 2024 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [61861260ce](https://linux-hardware.org/?probe=61861260ce) | Oct 11, 2024 |
| ASUSTek       | ROG Strix G16 G614JVR_G6... | Notebook    | [78f651233a](https://linux-hardware.org/?probe=78f651233a) | Oct 11, 2024 |
| Dell          | 0PC5F7 A01                  | Desktop     | [2331ed653e](https://linux-hardware.org/?probe=2331ed653e) | Oct 11, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [9565490550](https://linux-hardware.org/?probe=9565490550) | Oct 10, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [808d8ffd44](https://linux-hardware.org/?probe=808d8ffd44) | Oct 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fe4bfb3208](https://linux-hardware.org/?probe=fe4bfb3208) | Oct 10, 2024 |
| Dell          | 0CRWCR A01                  | All in one  | [815bb787d4](https://linux-hardware.org/?probe=815bb787d4) | Oct 10, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [f2fd99c3f0](https://linux-hardware.org/?probe=f2fd99c3f0) | Oct 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [59c4c502f1](https://linux-hardware.org/?probe=59c4c502f1) | Oct 10, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [36e4ba09ca](https://linux-hardware.org/?probe=36e4ba09ca) | Oct 10, 2024 |
| Irbis         | NB656                       | Notebook    | [2bdb435376](https://linux-hardware.org/?probe=2bdb435376) | Oct 10, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [cce2af49f0](https://linux-hardware.org/?probe=cce2af49f0) | Oct 10, 2024 |
| ASUSTek       | Z790 GAMING WIFI7           | Desktop     | [d76d04b462](https://linux-hardware.org/?probe=d76d04b462) | Oct 10, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [ebe3af12a8](https://linux-hardware.org/?probe=ebe3af12a8) | Oct 10, 2024 |
| Acer          | Nitro ANV15-51              | Notebook    | [7a65e38a37](https://linux-hardware.org/?probe=7a65e38a37) | Oct 10, 2024 |
| Gigabyte      | B650E AORUS PRO X USB4      | Desktop     | [441f16f225](https://linux-hardware.org/?probe=441f16f225) | Oct 10, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [b94d479256](https://linux-hardware.org/?probe=b94d479256) | Oct 10, 2024 |
| Positivo      | N3240                       | Notebook    | [ce2105487f](https://linux-hardware.org/?probe=ce2105487f) | Oct 10, 2024 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5064bb0b8d](https://linux-hardware.org/?probe=5064bb0b8d) | Oct 10, 2024 |
| HP            | 2B12                        | Desktop     | [dc89c52ca5](https://linux-hardware.org/?probe=dc89c52ca5) | Oct 10, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [46acb8c4d7](https://linux-hardware.org/?probe=46acb8c4d7) | Oct 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [95d12e5cce](https://linux-hardware.org/?probe=95d12e5cce) | Oct 10, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [8880f8b55c](https://linux-hardware.org/?probe=8880f8b55c) | Oct 10, 2024 |
| Dell          | Precision 7530              | Notebook    | [c386366ce5](https://linux-hardware.org/?probe=c386366ce5) | Oct 10, 2024 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e70ba79a1b](https://linux-hardware.org/?probe=e70ba79a1b) | Oct 10, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [1e73b44291](https://linux-hardware.org/?probe=1e73b44291) | Oct 10, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3A01... | Notebook    | [f69f8fa533](https://linux-hardware.org/?probe=f69f8fa533) | Oct 09, 2024 |
| ASRock        | Z68 Pro3                    | Desktop     | [1c593e0248](https://linux-hardware.org/?probe=1c593e0248) | Oct 09, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [90925b97bb](https://linux-hardware.org/?probe=90925b97bb) | Oct 09, 2024 |
| HP            | 2B12                        | Desktop     | [af8c8f5046](https://linux-hardware.org/?probe=af8c8f5046) | Oct 09, 2024 |
| Gigabyte      | Z490M                       | Desktop     | [90c1b958b7](https://linux-hardware.org/?probe=90c1b958b7) | Oct 09, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [810d5929bd](https://linux-hardware.org/?probe=810d5929bd) | Oct 09, 2024 |
| Samsung       | 305V4A/305V5A               | Notebook    | [2b41086555](https://linux-hardware.org/?probe=2b41086555) | Oct 09, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [5188f7bee3](https://linux-hardware.org/?probe=5188f7bee3) | Oct 09, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a4b3193826](https://linux-hardware.org/?probe=a4b3193826) | Oct 09, 2024 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [977e57020e](https://linux-hardware.org/?probe=977e57020e) | Oct 09, 2024 |
| Intel         | H55                         | Desktop     | [78fc8c6353](https://linux-hardware.org/?probe=78fc8c6353) | Oct 09, 2024 |
| Avell High... | B.ON                        | Notebook    | [6695fdbdac](https://linux-hardware.org/?probe=6695fdbdac) | Oct 09, 2024 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [d385217188](https://linux-hardware.org/?probe=d385217188) | Oct 09, 2024 |
| Microsoft     | Surface 3                   | Tablet      | [3ba6f2d39d](https://linux-hardware.org/?probe=3ba6f2d39d) | Oct 09, 2024 |
| Acer          | Nitro AN515-56              | Notebook    | [7d9e391f34](https://linux-hardware.org/?probe=7d9e391f34) | Oct 09, 2024 |
| Lenovo        | ThinkPad T450s 20BWS12V0... | Notebook    | [62e5d7e94f](https://linux-hardware.org/?probe=62e5d7e94f) | Oct 09, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [fd2a9a08ca](https://linux-hardware.org/?probe=fd2a9a08ca) | Oct 09, 2024 |
| Dell          | 0D02VH A01                  | Desktop     | [41a2c212be](https://linux-hardware.org/?probe=41a2c212be) | Oct 08, 2024 |
| MSI           | Modern 14 A10M              | Notebook    | [e17fa96504](https://linux-hardware.org/?probe=e17fa96504) | Oct 08, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [bd93ac4886](https://linux-hardware.org/?probe=bd93ac4886) | Oct 08, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [7dfd17a2f6](https://linux-hardware.org/?probe=7dfd17a2f6) | Oct 08, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fae42cf78a](https://linux-hardware.org/?probe=fae42cf78a) | Oct 08, 2024 |
| Dell          | Latitude E6410              | Notebook    | [67c1dd89e4](https://linux-hardware.org/?probe=67c1dd89e4) | Oct 08, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [5de475d8be](https://linux-hardware.org/?probe=5de475d8be) | Oct 08, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [7df1e66c9c](https://linux-hardware.org/?probe=7df1e66c9c) | Oct 08, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [8adc49985c](https://linux-hardware.org/?probe=8adc49985c) | Oct 08, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [9f191c5169](https://linux-hardware.org/?probe=9f191c5169) | Oct 08, 2024 |
| HP            | Unknown                     | Notebook    | [3f098896a0](https://linux-hardware.org/?probe=3f098896a0) | Oct 08, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [6e0d9c2a31](https://linux-hardware.org/?probe=6e0d9c2a31) | Oct 08, 2024 |
| HP            | Unknown                     | Notebook    | [8d8a005650](https://linux-hardware.org/?probe=8d8a005650) | Oct 08, 2024 |
| Samsung       | 940XFG                      | Notebook    | [a30f0716a0](https://linux-hardware.org/?probe=a30f0716a0) | Oct 08, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [cb1915dacc](https://linux-hardware.org/?probe=cb1915dacc) | Oct 08, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [4618b6e25f](https://linux-hardware.org/?probe=4618b6e25f) | Oct 08, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [894858ac5a](https://linux-hardware.org/?probe=894858ac5a) | Oct 08, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [855ca0cb21](https://linux-hardware.org/?probe=855ca0cb21) | Oct 08, 2024 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [79c895b3a3](https://linux-hardware.org/?probe=79c895b3a3) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5ffe9c3801](https://linux-hardware.org/?probe=5ffe9c3801) | Oct 08, 2024 |
| Dell          | 00CV7F A00                  | Desktop     | [f485c78376](https://linux-hardware.org/?probe=f485c78376) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5124f0d14b](https://linux-hardware.org/?probe=5124f0d14b) | Oct 08, 2024 |
| HP            | Laptop 15t-dy200            | Notebook    | [5629b2f0c2](https://linux-hardware.org/?probe=5629b2f0c2) | Oct 08, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6f7b819813](https://linux-hardware.org/?probe=6f7b819813) | Oct 08, 2024 |
| Microsoft     | Surface Laptop Go 3         | Tablet      | [13716b091e](https://linux-hardware.org/?probe=13716b091e) | Oct 07, 2024 |
| Gigabyte      | H510M H                     | Desktop     | [e8397b5e41](https://linux-hardware.org/?probe=e8397b5e41) | Oct 07, 2024 |
| Apple         | MacBookPro14,2              | Notebook    | [eb3a502532](https://linux-hardware.org/?probe=eb3a502532) | Oct 07, 2024 |
| Gigabyte      | B650 EAGLE AX               | Desktop     | [45eecb1b5f](https://linux-hardware.org/?probe=45eecb1b5f) | Oct 07, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS D4    | Desktop     | [a90624a194](https://linux-hardware.org/?probe=a90624a194) | Oct 07, 2024 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [94477eb0ba](https://linux-hardware.org/?probe=94477eb0ba) | Oct 07, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [1b038bd2e2](https://linux-hardware.org/?probe=1b038bd2e2) | Oct 07, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [a810910a2d](https://linux-hardware.org/?probe=a810910a2d) | Oct 07, 2024 |
| Jumper        | EZbook                      | Notebook    | [7b2e82cd1f](https://linux-hardware.org/?probe=7b2e82cd1f) | Oct 07, 2024 |
| HP            | Pavilion 15                 | Notebook    | [6f84e0d056](https://linux-hardware.org/?probe=6f84e0d056) | Oct 07, 2024 |
| SHIFT         | SHIFT13mi                   | Tablet      | [0bdd83d289](https://linux-hardware.org/?probe=0bdd83d289) | Oct 07, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [a6659ae060](https://linux-hardware.org/?probe=a6659ae060) | Oct 07, 2024 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [dd98315fff](https://linux-hardware.org/?probe=dd98315fff) | Oct 07, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [c47b6f3b03](https://linux-hardware.org/?probe=c47b6f3b03) | Oct 07, 2024 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [16806fc7d9](https://linux-hardware.org/?probe=16806fc7d9) | Oct 07, 2024 |
| Acer          | Aspire F5-573               | Notebook    | [dde8514a09](https://linux-hardware.org/?probe=dde8514a09) | Oct 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [83788f745f](https://linux-hardware.org/?probe=83788f745f) | Oct 07, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [267a889e66](https://linux-hardware.org/?probe=267a889e66) | Oct 07, 2024 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [b890eaf271](https://linux-hardware.org/?probe=b890eaf271) | Oct 07, 2024 |
| Jumper        | EZbook                      | Notebook    | [58f1d46c13](https://linux-hardware.org/?probe=58f1d46c13) | Oct 07, 2024 |
| Notebook      | NL5xNU                      | Notebook    | [e7e86c089c](https://linux-hardware.org/?probe=e7e86c089c) | Oct 07, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [591dc011b4](https://linux-hardware.org/?probe=591dc011b4) | Oct 07, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b5c390b381](https://linux-hardware.org/?probe=b5c390b381) | Oct 07, 2024 |
| ASUSTek       | Z97-K                       | Desktop     | [9067fbe342](https://linux-hardware.org/?probe=9067fbe342) | Oct 07, 2024 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [ee126ee7ab](https://linux-hardware.org/?probe=ee126ee7ab) | Oct 06, 2024 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e9ef6f096e](https://linux-hardware.org/?probe=e9ef6f096e) | Oct 06, 2024 |
| Infinix       | INBOOK X3 Plus              | Notebook    | [2ea5f65277](https://linux-hardware.org/?probe=2ea5f65277) | Oct 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IRH8 83... | Notebook    | [94d2e36c7b](https://linux-hardware.org/?probe=94d2e36c7b) | Oct 06, 2024 |
| Lenovo        | T530-28ICB                  | Desktop     | [085ab80ca3](https://linux-hardware.org/?probe=085ab80ca3) | Oct 06, 2024 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [5f37948592](https://linux-hardware.org/?probe=5f37948592) | Oct 06, 2024 |
| Dell          | Precision M4400             | Notebook    | [0d412792d5](https://linux-hardware.org/?probe=0d412792d5) | Oct 06, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [6d79b159b0](https://linux-hardware.org/?probe=6d79b159b0) | Oct 06, 2024 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [79a8f8be9d](https://linux-hardware.org/?probe=79a8f8be9d) | Oct 06, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [01da3dd8a1](https://linux-hardware.org/?probe=01da3dd8a1) | Oct 06, 2024 |
| HP            | 21F5 0A                     | Desktop     | [3aa5448519](https://linux-hardware.org/?probe=3aa5448519) | Oct 06, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [052c9e17f8](https://linux-hardware.org/?probe=052c9e17f8) | Oct 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [71902dd97c](https://linux-hardware.org/?probe=71902dd97c) | Oct 06, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [493742aa29](https://linux-hardware.org/?probe=493742aa29) | Oct 06, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [d0e7bbedde](https://linux-hardware.org/?probe=d0e7bbedde) | Oct 06, 2024 |
| PC Special... | N750HU                      | Notebook    | [e0aecc58af](https://linux-hardware.org/?probe=e0aecc58af) | Oct 06, 2024 |
| Lenovo        | LOQ 15IRH8 83EU             | Notebook    | [a7b0ff3425](https://linux-hardware.org/?probe=a7b0ff3425) | Oct 05, 2024 |
| Lenovo        | LOQ 15IRH8 83EU             | Notebook    | [f16315d3be](https://linux-hardware.org/?probe=f16315d3be) | Oct 05, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [ef64b85ad4](https://linux-hardware.org/?probe=ef64b85ad4) | Oct 05, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [1d982586c7](https://linux-hardware.org/?probe=1d982586c7) | Oct 05, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [9a5d9a5065](https://linux-hardware.org/?probe=9a5d9a5065) | Oct 05, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [88d6854174](https://linux-hardware.org/?probe=88d6854174) | Oct 05, 2024 |
| HP            | 1790                        | Desktop     | [c367bc1ccd](https://linux-hardware.org/?probe=c367bc1ccd) | Oct 05, 2024 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [0995faf13e](https://linux-hardware.org/?probe=0995faf13e) | Oct 05, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U60... | Notebook    | [1734e91761](https://linux-hardware.org/?probe=1734e91761) | Oct 05, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [af83a15cb9](https://linux-hardware.org/?probe=af83a15cb9) | Oct 05, 2024 |
| ASUSTek       | X550CL                      | Notebook    | [c561d0fe5b](https://linux-hardware.org/?probe=c561d0fe5b) | Oct 05, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [cecde8755c](https://linux-hardware.org/?probe=cecde8755c) | Oct 05, 2024 |
| Dell          | Precision 7540              | Notebook    | [b7190e112c](https://linux-hardware.org/?probe=b7190e112c) | Oct 05, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [b1fff870c3](https://linux-hardware.org/?probe=b1fff870c3) | Oct 05, 2024 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7a2e256a73](https://linux-hardware.org/?probe=7a2e256a73) | Oct 05, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [d971e6216e](https://linux-hardware.org/?probe=d971e6216e) | Oct 05, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | Notebook    | [33416938d4](https://linux-hardware.org/?probe=33416938d4) | Oct 05, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [54c023b2f6](https://linux-hardware.org/?probe=54c023b2f6) | Oct 05, 2024 |
| Dell          | 03RT16 A00                  | Desktop     | [64aac2f712](https://linux-hardware.org/?probe=64aac2f712) | Oct 05, 2024 |
| Intel         | B75                         | Desktop     | [af5a2821c0](https://linux-hardware.org/?probe=af5a2821c0) | Oct 05, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b4e2660cc8](https://linux-hardware.org/?probe=b4e2660cc8) | Oct 05, 2024 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [7039933c26](https://linux-hardware.org/?probe=7039933c26) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [ba0935bde6](https://linux-hardware.org/?probe=ba0935bde6) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [f3c50b490a](https://linux-hardware.org/?probe=f3c50b490a) | Oct 05, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [984497e592](https://linux-hardware.org/?probe=984497e592) | Oct 05, 2024 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1fd638437e](https://linux-hardware.org/?probe=1fd638437e) | Oct 05, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [25d2e63d80](https://linux-hardware.org/?probe=25d2e63d80) | Oct 05, 2024 |
| Sony          | VGNFW490Y                   | Notebook    | [7341b2c2c6](https://linux-hardware.org/?probe=7341b2c2c6) | Oct 05, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [10bf4a66cb](https://linux-hardware.org/?probe=10bf4a66cb) | Oct 05, 2024 |
| Dell          | Latitude 5430               | Notebook    | [41fd38816a](https://linux-hardware.org/?probe=41fd38816a) | Oct 05, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a3050c25cf](https://linux-hardware.org/?probe=a3050c25cf) | Oct 05, 2024 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [7308a75756](https://linux-hardware.org/?probe=7308a75756) | Oct 05, 2024 |
| MSI           | GF65 Thin 10UE              | Notebook    | [220a1355fa](https://linux-hardware.org/?probe=220a1355fa) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [f314e87727](https://linux-hardware.org/?probe=f314e87727) | Oct 04, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [b6eac5ee59](https://linux-hardware.org/?probe=b6eac5ee59) | Oct 04, 2024 |
| Samsung       | 550XED                      | Notebook    | [da76a0e07b](https://linux-hardware.org/?probe=da76a0e07b) | Oct 04, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [3a685cfdfd](https://linux-hardware.org/?probe=3a685cfdfd) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [884d99dd9f](https://linux-hardware.org/?probe=884d99dd9f) | Oct 04, 2024 |
| Samsung       | 550XED                      | Notebook    | [d8bebe5591](https://linux-hardware.org/?probe=d8bebe5591) | Oct 04, 2024 |
| MSI           | MAG B460M MORTAR            | Desktop     | [3fc82f90a0](https://linux-hardware.org/?probe=3fc82f90a0) | Oct 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [fdfb5cf338](https://linux-hardware.org/?probe=fdfb5cf338) | Oct 04, 2024 |
| HP            | Dev One Notebook PC         | Notebook    | [b43c3029a6](https://linux-hardware.org/?probe=b43c3029a6) | Oct 04, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [34092d7b69](https://linux-hardware.org/?probe=34092d7b69) | Oct 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [23f6034531](https://linux-hardware.org/?probe=23f6034531) | Oct 04, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [ce05e67256](https://linux-hardware.org/?probe=ce05e67256) | Oct 04, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF 20... | Desktop     | [d748225968](https://linux-hardware.org/?probe=d748225968) | Oct 04, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f2b5bbd4de](https://linux-hardware.org/?probe=f2b5bbd4de) | Oct 04, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [6a37860d48](https://linux-hardware.org/?probe=6a37860d48) | Oct 04, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [1206f11457](https://linux-hardware.org/?probe=1206f11457) | Oct 04, 2024 |
| ASUSTek       | Z170-PREMIUM                | Desktop     | [8f7739d0a6](https://linux-hardware.org/?probe=8f7739d0a6) | Oct 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0883f7cd9a](https://linux-hardware.org/?probe=0883f7cd9a) | Oct 04, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [938cbca98c](https://linux-hardware.org/?probe=938cbca98c) | Oct 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [95c32b4c50](https://linux-hardware.org/?probe=95c32b4c50) | Oct 04, 2024 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [b852c4d06d](https://linux-hardware.org/?probe=b852c4d06d) | Oct 04, 2024 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [93fbaead82](https://linux-hardware.org/?probe=93fbaead82) | Oct 03, 2024 |
| eMachines     | E725 V1.03                  | Notebook    | [4a9590683e](https://linux-hardware.org/?probe=4a9590683e) | Oct 03, 2024 |
| ABIT          | B760ITX PLUS D4 V1.1        | Desktop     | [ded6b54f27](https://linux-hardware.org/?probe=ded6b54f27) | Oct 03, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [045cd6bfce](https://linux-hardware.org/?probe=045cd6bfce) | Oct 03, 2024 |
| MSI           | MAG B460M MORTAR            | Desktop     | [62fb810090](https://linux-hardware.org/?probe=62fb810090) | Oct 03, 2024 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [a389bb8701](https://linux-hardware.org/?probe=a389bb8701) | Oct 03, 2024 |
| Dell          | G15 5511                    | Notebook    | [fdfcb44572](https://linux-hardware.org/?probe=fdfcb44572) | Oct 03, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [dd84c0fff7](https://linux-hardware.org/?probe=dd84c0fff7) | Oct 03, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [05f7a6ed10](https://linux-hardware.org/?probe=05f7a6ed10) | Oct 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [0f527314f8](https://linux-hardware.org/?probe=0f527314f8) | Oct 03, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [ec74664078](https://linux-hardware.org/?probe=ec74664078) | Oct 03, 2024 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [2b32bd4957](https://linux-hardware.org/?probe=2b32bd4957) | Oct 03, 2024 |
| MSI           | B560M-A PRO                 | Desktop     | [7b9f73dd13](https://linux-hardware.org/?probe=7b9f73dd13) | Oct 03, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [c3f03cbd94](https://linux-hardware.org/?probe=c3f03cbd94) | Oct 03, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [306ac3f0e3](https://linux-hardware.org/?probe=306ac3f0e3) | Oct 03, 2024 |
| ASUSTek       | EX-H110M-V                  | Desktop     | [1c402f09a1](https://linux-hardware.org/?probe=1c402f09a1) | Oct 03, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [66c92534ee](https://linux-hardware.org/?probe=66c92534ee) | Oct 03, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [384750eca9](https://linux-hardware.org/?probe=384750eca9) | Oct 03, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [074be404b5](https://linux-hardware.org/?probe=074be404b5) | Oct 03, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [395b3fa9c6](https://linux-hardware.org/?probe=395b3fa9c6) | Oct 03, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [2962fab2e4](https://linux-hardware.org/?probe=2962fab2e4) | Oct 03, 2024 |
| ASUSTek       | N552VX                      | Notebook    | [2ef6bdc43a](https://linux-hardware.org/?probe=2ef6bdc43a) | Oct 03, 2024 |
| HP            | 8876 11                     | Desktop     | [907d0fc9d5](https://linux-hardware.org/?probe=907d0fc9d5) | Oct 02, 2024 |
| HP            | 8876 11                     | Desktop     | [2ff5ebf9cf](https://linux-hardware.org/?probe=2ff5ebf9cf) | Oct 02, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [552e4cb346](https://linux-hardware.org/?probe=552e4cb346) | Oct 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5baaadc069](https://linux-hardware.org/?probe=5baaadc069) | Oct 02, 2024 |
| Dell          | G15 5511                    | Notebook    | [c3f5ed0a06](https://linux-hardware.org/?probe=c3f5ed0a06) | Oct 02, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [846d4940ec](https://linux-hardware.org/?probe=846d4940ec) | Oct 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [ed48609437](https://linux-hardware.org/?probe=ed48609437) | Oct 02, 2024 |
| Intel         | JSL MRD                     | Desktop     | [8ccee12f0f](https://linux-hardware.org/?probe=8ccee12f0f) | Oct 02, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [a1110f667e](https://linux-hardware.org/?probe=a1110f667e) | Oct 02, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1693b17ecc](https://linux-hardware.org/?probe=1693b17ecc) | Oct 02, 2024 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [0b07f7fd29](https://linux-hardware.org/?probe=0b07f7fd29) | Oct 02, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [8aa7d83ae5](https://linux-hardware.org/?probe=8aa7d83ae5) | Oct 02, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [5e4a8d8e8b](https://linux-hardware.org/?probe=5e4a8d8e8b) | Oct 02, 2024 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | Desktop     | [cce8e56788](https://linux-hardware.org/?probe=cce8e56788) | Oct 02, 2024 |
| Fujitsu       | FMVA12001                   | Notebook    | [fda024f87c](https://linux-hardware.org/?probe=fda024f87c) | Oct 02, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [5fca760834](https://linux-hardware.org/?probe=5fca760834) | Oct 02, 2024 |
| Supermicro    | X10SL7-F                    | Server      | [ea13c0439b](https://linux-hardware.org/?probe=ea13c0439b) | Oct 02, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [c263b0d128](https://linux-hardware.org/?probe=c263b0d128) | Oct 02, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [6e28788eb8](https://linux-hardware.org/?probe=6e28788eb8) | Oct 02, 2024 |
| Lenovo        | Slim 7 14IMH9 83D8          | Notebook    | [3f13c711a8](https://linux-hardware.org/?probe=3f13c711a8) | Oct 02, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [9a4f4dafdd](https://linux-hardware.org/?probe=9a4f4dafdd) | Oct 02, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [10ce6937b4](https://linux-hardware.org/?probe=10ce6937b4) | Oct 02, 2024 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [ada6d21b48](https://linux-hardware.org/?probe=ada6d21b48) | Oct 02, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c0f1f58a1d](https://linux-hardware.org/?probe=c0f1f58a1d) | Oct 02, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [7f1be258a1](https://linux-hardware.org/?probe=7f1be258a1) | Oct 02, 2024 |
| Intel         | H55                         | Desktop     | [ffc13f79f7](https://linux-hardware.org/?probe=ffc13f79f7) | Oct 02, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [a4ffdce5bf](https://linux-hardware.org/?probe=a4ffdce5bf) | Oct 01, 2024 |
| Dell          | Latitude E6320              | Notebook    | [14bcade039](https://linux-hardware.org/?probe=14bcade039) | Oct 01, 2024 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [bfae8f46d4](https://linux-hardware.org/?probe=bfae8f46d4) | Oct 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [066c22c11b](https://linux-hardware.org/?probe=066c22c11b) | Oct 01, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [1172b05111](https://linux-hardware.org/?probe=1172b05111) | Oct 01, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [2980e898be](https://linux-hardware.org/?probe=2980e898be) | Oct 01, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8887f065db](https://linux-hardware.org/?probe=8887f065db) | Oct 01, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [48137752ca](https://linux-hardware.org/?probe=48137752ca) | Oct 01, 2024 |
| ASRock        | A320M Pro4-F                | Desktop     | [afe4fe8ec5](https://linux-hardware.org/?probe=afe4fe8ec5) | Oct 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | Notebook    | [f3c9aa0b81](https://linux-hardware.org/?probe=f3c9aa0b81) | Oct 01, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [e4dea90fb8](https://linux-hardware.org/?probe=e4dea90fb8) | Oct 01, 2024 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [c68df5226e](https://linux-hardware.org/?probe=c68df5226e) | Oct 01, 2024 |
| AVITA         | NS14A6                      | Notebook    | [360beece3d](https://linux-hardware.org/?probe=360beece3d) | Oct 01, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [362eac7c6c](https://linux-hardware.org/?probe=362eac7c6c) | Oct 01, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5b143a5465](https://linux-hardware.org/?probe=5b143a5465) | Oct 01, 2024 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [451563b4fb](https://linux-hardware.org/?probe=451563b4fb) | Oct 01, 2024 |
| Dell          | Latitude E5470              | Notebook    | [649f2683b3](https://linux-hardware.org/?probe=649f2683b3) | Oct 01, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [605995ef0d](https://linux-hardware.org/?probe=605995ef0d) | Oct 01, 2024 |
| HP            | 83EF                        | Desktop     | [3799ba66c9](https://linux-hardware.org/?probe=3799ba66c9) | Oct 01, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [2b749f43d9](https://linux-hardware.org/?probe=2b749f43d9) | Oct 01, 2024 |
| Dell          | Inspiron 16 5635            | Notebook    | [fa35ff049c](https://linux-hardware.org/?probe=fa35ff049c) | Oct 01, 2024 |
| ASRock        | A320M Pro4-F                | Desktop     | [b1afeb5cb3](https://linux-hardware.org/?probe=b1afeb5cb3) | Oct 01, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [32cd855c59](https://linux-hardware.org/?probe=32cd855c59) | Oct 01, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [0e57e17e13](https://linux-hardware.org/?probe=0e57e17e13) | Oct 01, 2024 |
| ASRock        | A620M-HDV/M.2               | Desktop     | [1f6a1a1295](https://linux-hardware.org/?probe=1f6a1a1295) | Oct 01, 2024 |
| Dell          | 0C2XKD A01                  | Desktop     | [f1458819ca](https://linux-hardware.org/?probe=f1458819ca) | Oct 01, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [5ece32f4de](https://linux-hardware.org/?probe=5ece32f4de) | Sep 30, 2024 |
| Dell          | Latitude 5420               | Notebook    | [1c0a43d055](https://linux-hardware.org/?probe=1c0a43d055) | Sep 30, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d53e38a726](https://linux-hardware.org/?probe=d53e38a726) | Sep 30, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ee4039dadc](https://linux-hardware.org/?probe=ee4039dadc) | Sep 30, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [fb89302a2c](https://linux-hardware.org/?probe=fb89302a2c) | Sep 30, 2024 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [f3244d0419](https://linux-hardware.org/?probe=f3244d0419) | Sep 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd54b4b008](https://linux-hardware.org/?probe=bd54b4b008) | Sep 30, 2024 |
| Dell          | Precision 7780              | Notebook    | [27449211bc](https://linux-hardware.org/?probe=27449211bc) | Sep 30, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [65e2cb6b20](https://linux-hardware.org/?probe=65e2cb6b20) | Sep 30, 2024 |
| Dell          | Precision 7780              | Notebook    | [406157083d](https://linux-hardware.org/?probe=406157083d) | Sep 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [b78b3c6ea8](https://linux-hardware.org/?probe=b78b3c6ea8) | Sep 30, 2024 |
| AMI           | Intel                       | Desktop     | [69a3119f10](https://linux-hardware.org/?probe=69a3119f10) | Sep 30, 2024 |
| Dell          | 08HPGT A01                  | Desktop     | [54145cf256](https://linux-hardware.org/?probe=54145cf256) | Sep 30, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [b0712ef444](https://linux-hardware.org/?probe=b0712ef444) | Sep 30, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [f01b96e5ac](https://linux-hardware.org/?probe=f01b96e5ac) | Sep 30, 2024 |
| MSI           | Summit E13FlipEvo A13MT     | Notebook    | [105c69a831](https://linux-hardware.org/?probe=105c69a831) | Sep 30, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [88f77a4f65](https://linux-hardware.org/?probe=88f77a4f65) | Sep 30, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [c940397cc8](https://linux-hardware.org/?probe=c940397cc8) | Sep 30, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5cdf246355](https://linux-hardware.org/?probe=5cdf246355) | Sep 30, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | Notebook    | [2c916dede8](https://linux-hardware.org/?probe=2c916dede8) | Sep 30, 2024 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [1237ae4821](https://linux-hardware.org/?probe=1237ae4821) | Sep 30, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [4f4ec89b3a](https://linux-hardware.org/?probe=4f4ec89b3a) | Sep 29, 2024 |
| ASUSTek       | G750JHA                     | Notebook    | [c78859f5ae](https://linux-hardware.org/?probe=c78859f5ae) | Sep 29, 2024 |
| ASRock        | B650I Lightning WiFi        | Desktop     | [48210e5691](https://linux-hardware.org/?probe=48210e5691) | Sep 29, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ba8072bee4](https://linux-hardware.org/?probe=ba8072bee4) | Sep 29, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [4d52b9b4ac](https://linux-hardware.org/?probe=4d52b9b4ac) | Sep 29, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8a6390701a](https://linux-hardware.org/?probe=8a6390701a) | Sep 29, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [df4e3d53be](https://linux-hardware.org/?probe=df4e3d53be) | Sep 29, 2024 |
| Toshiba       | Satellite C870-1GD          | Notebook    | [515b2dadd3](https://linux-hardware.org/?probe=515b2dadd3) | Sep 29, 2024 |
| Dell          | 0VNGWR A02                  | All in one  | [af6af4820f](https://linux-hardware.org/?probe=af6af4820f) | Sep 29, 2024 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [43f4d4163d](https://linux-hardware.org/?probe=43f4d4163d) | Sep 29, 2024 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d082c62bb9](https://linux-hardware.org/?probe=d082c62bb9) | Sep 29, 2024 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [d8bf22df1c](https://linux-hardware.org/?probe=d8bf22df1c) | Sep 29, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [b410a8d5ae](https://linux-hardware.org/?probe=b410a8d5ae) | Sep 29, 2024 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [6e0f5e1ba9](https://linux-hardware.org/?probe=6e0f5e1ba9) | Sep 29, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [d1718d14ab](https://linux-hardware.org/?probe=d1718d14ab) | Sep 29, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [458b6c459d](https://linux-hardware.org/?probe=458b6c459d) | Sep 29, 2024 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [34267b7e13](https://linux-hardware.org/?probe=34267b7e13) | Sep 29, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a44ff28e8a](https://linux-hardware.org/?probe=a44ff28e8a) | Sep 29, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [b2b12658a9](https://linux-hardware.org/?probe=b2b12658a9) | Sep 29, 2024 |
| Timi          | TM1701                      | Notebook    | [cfe083e967](https://linux-hardware.org/?probe=cfe083e967) | Sep 29, 2024 |
| HP            | 872C                        | Mini pc     | [e7bf848205](https://linux-hardware.org/?probe=e7bf848205) | Sep 29, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [18420e07e6](https://linux-hardware.org/?probe=18420e07e6) | Sep 29, 2024 |
| Unknown       | Unknown                     | Notebook    | [cdc226d94d](https://linux-hardware.org/?probe=cdc226d94d) | Sep 29, 2024 |
| Unknown       | Unknown                     | Notebook    | [8a4172464a](https://linux-hardware.org/?probe=8a4172464a) | Sep 29, 2024 |
| Dell          | 0T7D40 A00                  | Desktop     | [e6ca601fc3](https://linux-hardware.org/?probe=e6ca601fc3) | Sep 29, 2024 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [dd4516ba37](https://linux-hardware.org/?probe=dd4516ba37) | Sep 29, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [6e01b29e3b](https://linux-hardware.org/?probe=6e01b29e3b) | Sep 29, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [ee50af1163](https://linux-hardware.org/?probe=ee50af1163) | Sep 29, 2024 |
| HP            | Grunt                       | Notebook    | [2264efe866](https://linux-hardware.org/?probe=2264efe866) | Sep 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [767a70e7fe](https://linux-hardware.org/?probe=767a70e7fe) | Sep 29, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [4e7e3890bb](https://linux-hardware.org/?probe=4e7e3890bb) | Sep 29, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcdad05f0a](https://linux-hardware.org/?probe=dcdad05f0a) | Sep 28, 2024 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [f4697c886f](https://linux-hardware.org/?probe=f4697c886f) | Sep 28, 2024 |
| Samsung       | 305V4A/305V5A               | Notebook    | [1da0c18a13](https://linux-hardware.org/?probe=1da0c18a13) | Sep 28, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b27c7324e8](https://linux-hardware.org/?probe=b27c7324e8) | Sep 28, 2024 |
| Schenker      | VISION 14                   | Notebook    | [2d8dc470e9](https://linux-hardware.org/?probe=2d8dc470e9) | Sep 28, 2024 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [775fa87efb](https://linux-hardware.org/?probe=775fa87efb) | Sep 28, 2024 |
| Acer          | Okinawa                     | Notebook    | [dd1134eda8](https://linux-hardware.org/?probe=dd1134eda8) | Sep 28, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [55eb1cb193](https://linux-hardware.org/?probe=55eb1cb193) | Sep 28, 2024 |
| Dell          | Latitude 7480               | Notebook    | [36028e7ce7](https://linux-hardware.org/?probe=36028e7ce7) | Sep 28, 2024 |
| HP            | 83E2                        | Desktop     | [cd3b2554eb](https://linux-hardware.org/?probe=cd3b2554eb) | Sep 28, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [707360a70f](https://linux-hardware.org/?probe=707360a70f) | Sep 28, 2024 |
| Micro Comp... | V3                          | Tablet      | [ff1521c6b1](https://linux-hardware.org/?probe=ff1521c6b1) | Sep 28, 2024 |
| Dell          | Latitude 7490               | Notebook    | [bb2ef7aeaa](https://linux-hardware.org/?probe=bb2ef7aeaa) | Sep 28, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6a8da6585a](https://linux-hardware.org/?probe=6a8da6585a) | Sep 28, 2024 |
| HP            | 1632                        | Desktop     | [7e34c88f03](https://linux-hardware.org/?probe=7e34c88f03) | Sep 28, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [f17e1584e0](https://linux-hardware.org/?probe=f17e1584e0) | Sep 27, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [8cf886ae50](https://linux-hardware.org/?probe=8cf886ae50) | Sep 27, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [4b4ad854bf](https://linux-hardware.org/?probe=4b4ad854bf) | Sep 27, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [b06ebcfa91](https://linux-hardware.org/?probe=b06ebcfa91) | Sep 27, 2024 |
| ASRock        | X670E Taichi                | Desktop     | [38c09012e1](https://linux-hardware.org/?probe=38c09012e1) | Sep 27, 2024 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [0a0cbfcc0c](https://linux-hardware.org/?probe=0a0cbfcc0c) | Sep 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3bd8900d6d](https://linux-hardware.org/?probe=3bd8900d6d) | Sep 27, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [a5db1c0652](https://linux-hardware.org/?probe=a5db1c0652) | Sep 27, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [9f8c1e9038](https://linux-hardware.org/?probe=9f8c1e9038) | Sep 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [2d0c60bf4e](https://linux-hardware.org/?probe=2d0c60bf4e) | Sep 27, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [915bab9e91](https://linux-hardware.org/?probe=915bab9e91) | Sep 27, 2024 |
| HP            | Notebook                    | Notebook    | [cfe81118c3](https://linux-hardware.org/?probe=cfe81118c3) | Sep 27, 2024 |
| Dell          | Vostro 5391                 | Notebook    | [bf2cd1b3a1](https://linux-hardware.org/?probe=bf2cd1b3a1) | Sep 27, 2024 |
| HP            | Notebook                    | Notebook    | [0695d61a4c](https://linux-hardware.org/?probe=0695d61a4c) | Sep 27, 2024 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [c06d37811f](https://linux-hardware.org/?probe=c06d37811f) | Sep 26, 2024 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [b026a73cfc](https://linux-hardware.org/?probe=b026a73cfc) | Sep 26, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [85d39272e0](https://linux-hardware.org/?probe=85d39272e0) | Sep 26, 2024 |
| HP            | ENVY 15                     | Notebook    | [cec3ec4958](https://linux-hardware.org/?probe=cec3ec4958) | Sep 26, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b058e46a12](https://linux-hardware.org/?probe=b058e46a12) | Sep 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [617d6c24ec](https://linux-hardware.org/?probe=617d6c24ec) | Sep 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [914d0011a1](https://linux-hardware.org/?probe=914d0011a1) | Sep 26, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [ed54423315](https://linux-hardware.org/?probe=ed54423315) | Sep 26, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [dbc88b064e](https://linux-hardware.org/?probe=dbc88b064e) | Sep 26, 2024 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [ce1fde6f07](https://linux-hardware.org/?probe=ce1fde6f07) | Sep 26, 2024 |
| Xiaomi        | Pad 5                       | Notebook    | [10df1d4339](https://linux-hardware.org/?probe=10df1d4339) | Sep 26, 2024 |
| Dell          | G7 7790                     | Notebook    | [b118f9066c](https://linux-hardware.org/?probe=b118f9066c) | Sep 26, 2024 |
| Dell          | G7 7790                     | Notebook    | [b9b8f409cf](https://linux-hardware.org/?probe=b9b8f409cf) | Sep 26, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [71e159b497](https://linux-hardware.org/?probe=71e159b497) | Sep 26, 2024 |
| Apple         | Mac-F2218EC8                | All in one  | [d16f154aec](https://linux-hardware.org/?probe=d16f154aec) | Sep 26, 2024 |
| Dell          | Latitude 7400               | Notebook    | [a8fc62b85e](https://linux-hardware.org/?probe=a8fc62b85e) | Sep 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | Notebook    | [d328b51ed5](https://linux-hardware.org/?probe=d328b51ed5) | Sep 26, 2024 |
| ASUSTek       | ASUS ExpertBook P2451FA     | Notebook    | [76efe6a713](https://linux-hardware.org/?probe=76efe6a713) | Sep 26, 2024 |
| MSI           | MS-B9321                    | Desktop     | [43c9954bf1](https://linux-hardware.org/?probe=43c9954bf1) | Sep 26, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [739b6f2f9e](https://linux-hardware.org/?probe=739b6f2f9e) | Sep 26, 2024 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [fd7f6af786](https://linux-hardware.org/?probe=fd7f6af786) | Sep 26, 2024 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [b984e53994](https://linux-hardware.org/?probe=b984e53994) | Sep 26, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [bd364d0579](https://linux-hardware.org/?probe=bd364d0579) | Sep 25, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [ac56f45474](https://linux-hardware.org/?probe=ac56f45474) | Sep 25, 2024 |
| OEM           | M882CWP                     | Tablet      | [c8eb4963e5](https://linux-hardware.org/?probe=c8eb4963e5) | Sep 25, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [15ea23255b](https://linux-hardware.org/?probe=15ea23255b) | Sep 25, 2024 |
| Packard Be... | EasyNote TJ65               | Notebook    | [a49aa6c0b8](https://linux-hardware.org/?probe=a49aa6c0b8) | Sep 25, 2024 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [c19c83f1f1](https://linux-hardware.org/?probe=c19c83f1f1) | Sep 25, 2024 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [24389d85fc](https://linux-hardware.org/?probe=24389d85fc) | Sep 25, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7f07e86f5c](https://linux-hardware.org/?probe=7f07e86f5c) | Sep 25, 2024 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [994fcd21ee](https://linux-hardware.org/?probe=994fcd21ee) | Sep 25, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [4a145a2850](https://linux-hardware.org/?probe=4a145a2850) | Sep 25, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [810b5da055](https://linux-hardware.org/?probe=810b5da055) | Sep 25, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [4cd5e49a76](https://linux-hardware.org/?probe=4cd5e49a76) | Sep 25, 2024 |
| HP            | 1998                        | Desktop     | [b9f2ed006d](https://linux-hardware.org/?probe=b9f2ed006d) | Sep 25, 2024 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1803b90b56](https://linux-hardware.org/?probe=1803b90b56) | Sep 25, 2024 |
| Toshiba       | PORTEGE Z30t-C              | Notebook    | [06807aa903](https://linux-hardware.org/?probe=06807aa903) | Sep 25, 2024 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [413217c3d1](https://linux-hardware.org/?probe=413217c3d1) | Sep 25, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [86c41c5c5b](https://linux-hardware.org/?probe=86c41c5c5b) | Sep 25, 2024 |
| ASUSTek       | T304UA                      | Tablet      | [959d190c5d](https://linux-hardware.org/?probe=959d190c5d) | Sep 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [13e5463ee0](https://linux-hardware.org/?probe=13e5463ee0) | Sep 25, 2024 |
| Alienware     | 15 R3                       | Notebook    | [6c47406fd9](https://linux-hardware.org/?probe=6c47406fd9) | Sep 25, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d598761c2d](https://linux-hardware.org/?probe=d598761c2d) | Sep 25, 2024 |
| Dell          | Inspiron 5565               | Notebook    | [665b2cc68c](https://linux-hardware.org/?probe=665b2cc68c) | Sep 25, 2024 |
| Dell          | Inspiron 5565               | Notebook    | [3763aeacb5](https://linux-hardware.org/?probe=3763aeacb5) | Sep 25, 2024 |
| Lenovo        | Yoga S730-13IML 81U4        | Notebook    | [b411da6d9e](https://linux-hardware.org/?probe=b411da6d9e) | Sep 25, 2024 |
| ASUSTek       | T304UA                      | Tablet      | [3983ce8a2c](https://linux-hardware.org/?probe=3983ce8a2c) | Sep 25, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [adf809b073](https://linux-hardware.org/?probe=adf809b073) | Sep 25, 2024 |
| Google        | Nocturne                    | Tablet      | [e19cc56e22](https://linux-hardware.org/?probe=e19cc56e22) | Sep 25, 2024 |
| Google        | Nocturne                    | Tablet      | [90a1d73796](https://linux-hardware.org/?probe=90a1d73796) | Sep 25, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [94429e8102](https://linux-hardware.org/?probe=94429e8102) | Sep 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [57257bd2a2](https://linux-hardware.org/?probe=57257bd2a2) | Sep 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [e41bee6ced](https://linux-hardware.org/?probe=e41bee6ced) | Sep 25, 2024 |
| Dell          | 0H4VK7 A01                  | Desktop     | [5eabbc1d70](https://linux-hardware.org/?probe=5eabbc1d70) | Sep 25, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [3750216f3e](https://linux-hardware.org/?probe=3750216f3e) | Sep 25, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [60e4b8e20b](https://linux-hardware.org/?probe=60e4b8e20b) | Sep 25, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [5ce8f9d86f](https://linux-hardware.org/?probe=5ce8f9d86f) | Sep 24, 2024 |
| Dell          | Inspiron 5770               | Notebook    | [9ea257bf1a](https://linux-hardware.org/?probe=9ea257bf1a) | Sep 24, 2024 |
| Dell          | Latitude E5470              | Notebook    | [b33fe80d61](https://linux-hardware.org/?probe=b33fe80d61) | Sep 24, 2024 |
| HONOR         | FRI-FXX                     | Notebook    | [1ed83fb238](https://linux-hardware.org/?probe=1ed83fb238) | Sep 24, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [68dfb88101](https://linux-hardware.org/?probe=68dfb88101) | Sep 24, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [845ef2198e](https://linux-hardware.org/?probe=845ef2198e) | Sep 24, 2024 |
| Xiaomi        | Mipad2                      | Tablet      | [5f3a7b7a19](https://linux-hardware.org/?probe=5f3a7b7a19) | Sep 24, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [5d73368fcb](https://linux-hardware.org/?probe=5d73368fcb) | Sep 24, 2024 |
| Acer          | Aspire A315-55G             | Notebook    | [3f77776e4c](https://linux-hardware.org/?probe=3f77776e4c) | Sep 24, 2024 |
| AZW           | SER V1.3                    | Mini pc     | [980105a122](https://linux-hardware.org/?probe=980105a122) | Sep 24, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c468746cd8](https://linux-hardware.org/?probe=c468746cd8) | Sep 24, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [4d94eb8a1c](https://linux-hardware.org/?probe=4d94eb8a1c) | Sep 24, 2024 |
| Lenovo        | ThinkPad E550 20DF002MAU    | Notebook    | [311e26a0a8](https://linux-hardware.org/?probe=311e26a0a8) | Sep 24, 2024 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [6eb428f2a4](https://linux-hardware.org/?probe=6eb428f2a4) | Sep 24, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [c6ab118e9d](https://linux-hardware.org/?probe=c6ab118e9d) | Sep 24, 2024 |
| Microsoft     | Surface Book                | Tablet      | [80d3760888](https://linux-hardware.org/?probe=80d3760888) | Sep 24, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [0f00b39900](https://linux-hardware.org/?probe=0f00b39900) | Sep 24, 2024 |
| Intel         | NUC7JYB M37329-601          | Mini pc     | [f75ff2a7f2](https://linux-hardware.org/?probe=f75ff2a7f2) | Sep 24, 2024 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [43ca7f9dab](https://linux-hardware.org/?probe=43ca7f9dab) | Sep 24, 2024 |
| Dell          | Inspiron M5010              | Notebook    | [f3866be309](https://linux-hardware.org/?probe=f3866be309) | Sep 24, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6fc741f275](https://linux-hardware.org/?probe=6fc741f275) | Sep 24, 2024 |
| Intel         | NUC7JYB M37329-601          | Mini pc     | [73347b3b7d](https://linux-hardware.org/?probe=73347b3b7d) | Sep 24, 2024 |
| Lenovo        | ThinkPad L440 20AT002KUS    | Notebook    | [a25beb7d30](https://linux-hardware.org/?probe=a25beb7d30) | Sep 24, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 1 ... | Convertible | [306fc8c4d0](https://linux-hardware.org/?probe=306fc8c4d0) | Sep 24, 2024 |
| Dell          | Inspiron 3480               | Notebook    | [427d801a8c](https://linux-hardware.org/?probe=427d801a8c) | Sep 24, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3a4ba29240](https://linux-hardware.org/?probe=3a4ba29240) | Sep 24, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [afadf0990e](https://linux-hardware.org/?probe=afadf0990e) | Sep 24, 2024 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | Notebook    | [8be8636936](https://linux-hardware.org/?probe=8be8636936) | Sep 24, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [6d1d288b78](https://linux-hardware.org/?probe=6d1d288b78) | Sep 23, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [7c31f00b6d](https://linux-hardware.org/?probe=7c31f00b6d) | Sep 23, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [f82874c7bf](https://linux-hardware.org/?probe=f82874c7bf) | Sep 23, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_40/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 6.8.5-301.fc40.x86_64        | 438       | 10.66%  |
| 6.8.11-300.fc40.x86_64       | 284       | 6.91%   |
| 6.8.7-300.fc40.x86_64        | 246       | 5.99%   |
| 6.10.6-200.fc40.x86_64       | 231       | 5.62%   |
| 6.8.9-300.fc40.x86_64        | 229       | 5.57%   |
| 6.8.10-300.fc40.x86_64       | 156       | 3.8%    |
| 6.10.12-200.fc40.x86_64      | 149       | 3.63%   |
| 6.10.11-200.fc40.x86_64      | 147       | 3.58%   |
| 6.9.12-200.fc40.x86_64       | 140       | 3.41%   |
| 6.8.8-300.fc40.x86_64        | 129       | 3.14%   |
| 6.11.3-200.fc40.x86_64       | 127       | 3.09%   |
| 6.10.3-200.fc40.x86_64       | 127       | 3.09%   |
| 6.9.7-200.fc40.x86_64        | 122       | 2.97%   |
| 6.10.10-200.fc40.x86_64      | 118       | 2.87%   |
| 6.9.9-200.fc40.x86_64        | 100       | 2.43%   |
| 6.11.4-201.fc40.x86_64       | 94        | 2.29%   |
| 6.10.9-200.fc40.x86_64       | 93        | 2.26%   |
| 6.9.5-200.fc40.x86_64        | 92        | 2.24%   |
| 6.9.4-200.fc40.x86_64        | 92        | 2.24%   |
| 6.9.8-200.fc40.x86_64        | 91        | 2.21%   |
| 6.10.4-200.fc40.x86_64       | 88        | 2.14%   |
| 6.10.7-200.fc40.x86_64       | 87        | 2.12%   |
| 6.9.6-200.fc40.x86_64        | 85        | 2.07%   |
| 6.9.11-200.fc40.x86_64       | 71        | 1.73%   |
| 6.10.8-200.fc40.x86_64       | 61        | 1.48%   |
| 6.9.10-200.fc40.x86_64       | 51        | 1.24%   |
| 6.10.5-200.fc40.x86_64       | 45        | 1.1%    |
| 6.8.9-301.fsync.fc40.x86_64  | 30        | 0.73%   |
| 6.8.2-300.fc40.x86_64        | 30        | 0.73%   |
| 6.11.5-200.fc40.x86_64       | 22        | 0.54%   |
| 6.8.10-301.fsync.fc40.x86_64 | 20        | 0.49%   |
| 6.9.4-201.fsync.fc40.x86_64  | 19        | 0.46%   |
| 6.8.4-300.fc40.x86_64        | 18        | 0.44%   |
| 6.8.0-0.rc6.49.fc40.x86_64   | 18        | 0.44%   |
| 6.11.6-200.fc40.x86_64       | 18        | 0.44%   |
| 6.8.11-301.fsync.fc40.x86_64 | 16        | 0.39%   |
| 6.11.10-200.fc40.x86_64      | 15        | 0.37%   |
| 6.8.7-303.fsync.fc40.x86_64  | 10        | 0.24%   |
| 6.8.7-302.fsync.fc40.x86_64  | 9         | 0.22%   |
| 6.9.6-201.fsync.fc40.x86_64  | 8         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8.5   | 438       | 10.66%  |
| 6.8.11  | 301       | 7.33%   |
| 6.8.7   | 272       | 6.62%   |
| 6.8.9   | 262       | 6.38%   |
| 6.10.6  | 231       | 5.62%   |
| 6.8.10  | 177       | 4.31%   |
| 6.10.12 | 149       | 3.63%   |
| 6.10.11 | 148       | 3.6%    |
| 6.9.12  | 142       | 3.46%   |
| 6.8.8   | 130       | 3.16%   |
| 6.10.3  | 129       | 3.14%   |
| 6.11.3  | 127       | 3.09%   |
| 6.10.10 | 126       | 3.07%   |
| 6.9.7   | 123       | 2.99%   |
| 6.9.4   | 115       | 2.8%    |
| 6.9.9   | 105       | 2.56%   |
| 6.9.6   | 95        | 2.31%   |
| 6.11.4  | 95        | 2.31%   |
| 6.9.5   | 93        | 2.26%   |
| 6.10.9  | 93        | 2.26%   |
| 6.9.8   | 92        | 2.24%   |
| 6.10.4  | 88        | 2.14%   |
| 6.10.7  | 87        | 2.12%   |
| 6.9.11  | 73        | 1.78%   |
| 6.10.8  | 63        | 1.53%   |
| 6.9.10  | 51        | 1.24%   |
| 6.10.5  | 50        | 1.22%   |
| 6.8.2   | 31        | 0.75%   |
| 6.8.0   | 28        | 0.68%   |
| 6.11.5  | 22        | 0.54%   |
| 6.8.4   | 20        | 0.49%   |
| 6.11.6  | 18        | 0.44%   |
| 6.11.10 | 15        | 0.37%   |
| 6.8.12  | 11        | 0.27%   |
| 6.8.1   | 7         | 0.17%   |
| 6.12.5  | 7         | 0.17%   |
| 6.11.8  | 7         | 0.17%   |
| 6.11.7  | 7         | 0.17%   |
| 6.8.6   | 6         | 0.15%   |
| 6.5.0   | 6         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8     | 1622      | 40.87%  |
| 6.10    | 1129      | 28.45%  |
| 6.9     | 870       | 21.92%  |
| 6.11    | 301       | 7.58%   |
| 6.12    | 18        | 0.45%   |
| 6.5     | 10        | 0.25%   |
| 6.7     | 7         | 0.18%   |
| 6.6     | 7         | 0.18%   |
| 6.4     | 1         | 0.03%   |
| 6.1     | 1         | 0.03%   |
| 5.4     | 1         | 0.03%   |
| 5.15    | 1         | 0.03%   |
| 5.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3731      | 99.81%  |
| aarch64 | 7         | 0.19%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 2650      | 70.16%  |
| KDE6          | 722       | 19.12%  |
| KDE4          | 103       | 2.73%   |
| Unknown       | 60        | 1.59%   |
| X-Cinnamon    | 47        | 1.24%   |
| XFCE          | 43        | 1.14%   |
| GNOME Classic | 36        | 0.95%   |
| Cinnamon      | 31        | 0.82%   |
| MATE          | 21        | 0.56%   |
| Budgie        | 14        | 0.37%   |
| Hyprland      | 12        | 0.32%   |
| sway          | 11        | 0.29%   |
| i3            | 6         | 0.16%   |
| KDE5          | 5         | 0.13%   |
| Deepin        | 5         | 0.13%   |
| LXQt          | 4         | 0.11%   |
| LXDE          | 2         | 0.05%   |
| bspwm         | 2         | 0.05%   |
| wlroots       | 1         | 0.03%   |
| KDE           | 1         | 0.03%   |
| awesome       | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 3278      | 86.86%  |
| X11     | 403       | 10.68%  |
| Tty     | 52        | 1.38%   |
| Unknown | 40        | 1.06%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2535      | 67.28%  |
| GDM     | 705       | 18.71%  |
| SDDM    | 390       | 10.35%  |
| LightDM | 135       | 3.58%   |
| LXDM    | 3         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1984      | 52.85%  |
| en_GB   | 279       | 7.43%   |
| de_DE   | 204       | 5.43%   |
| pt_BR   | 183       | 4.87%   |
| ru_RU   | 154       | 4.1%    |
| fr_FR   | 110       | 2.93%   |
| it_IT   | 98        | 2.61%   |
| en_AU   | 95        | 2.53%   |
| es_ES   | 62        | 1.65%   |
| en_CA   | 54        | 1.44%   |
| pl_PL   | 51        | 1.36%   |
| en_IN   | 42        | 1.12%   |
| es_MX   | 40        | 1.07%   |
| tr_TR   | 25        | 0.67%   |
| es_CL   | 23        | 0.61%   |
| es_AR   | 23        | 0.61%   |
| zh_CN   | 21        | 0.56%   |
| es_CO   | 19        | 0.51%   |
| nl_NL   | 17        | 0.45%   |
| da_DK   | 16        | 0.43%   |
| hu_HU   | 15        | 0.4%    |
| en_IE   | 15        | 0.4%    |
| en_DK   | 15        | 0.4%    |
| de_AT   | 13        | 0.35%   |
| fr_CA   | 12        | 0.32%   |
| Unknown | 12        | 0.32%   |
| es_PE   | 11        | 0.29%   |
| cs_CZ   | 11        | 0.29%   |
| en_NZ   | 10        | 0.27%   |
| sv_SE   | 9         | 0.24%   |
| pt_PT   | 9         | 0.24%   |
| de_CH   | 8         | 0.21%   |
| fi_FI   | 7         | 0.19%   |
| en_ZA   | 7         | 0.19%   |
| uk_UA   | 6         | 0.16%   |
| ro_RO   | 6         | 0.16%   |
| nl_BE   | 6         | 0.16%   |
| ko_KR   | 6         | 0.16%   |
| en_SG   | 6         | 0.16%   |
| en_PH   | 6         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2641      | 70.2%   |
| EFI  | 1121      | 29.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 3233      | 86.19%  |
| Ext4    | 408       | 10.88%  |
| Xfs     | 52        | 1.39%   |
| Tmpfs   | 46        | 1.23%   |
| Overlay | 7         | 0.19%   |
| Unknown | 3         | 0.08%   |
| F2fs    | 2         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2477      | 65.77%  |
| GPT     | 1246      | 33.09%  |
| MBR     | 43        | 1.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3475      | 92.54%  |
| Yes       | 280       | 7.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3260      | 86.84%  |
| Yes       | 494       | 13.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 668       | 17.87%  |
| ASUSTek Computer                     | 656       | 17.55%  |
| Hewlett-Packard                      | 426       | 11.4%   |
| Dell                                 | 385       | 10.3%   |
| Gigabyte Technology                  | 264       | 7.06%   |
| MSI                                  | 260       | 6.96%   |
| Apple                                | 178       | 4.76%   |
| Acer                                 | 158       | 4.23%   |
| ASRock                               | 127       | 3.4%    |
| Intel                                | 62        | 1.66%   |
| HUAWEI                               | 45        | 1.2%    |
| Samsung Electronics                  | 31        | 0.83%   |
| Google                               | 30        | 0.8%    |
| Framework                            | 28        | 0.75%   |
| Toshiba                              | 24        | 0.64%   |
| Unknown                              | 24        | 0.64%   |
| Microsoft                            | 18        | 0.48%   |
| Fujitsu                              | 17        | 0.45%   |
| Timi                                 | 16        | 0.43%   |
| Alienware                            | 16        | 0.43%   |
| AZW                                  | 13        | 0.35%   |
| Micro Computer (HK) Tech Limited     | 12        | 0.32%   |
| Shenzhen Meigao Electronic Equipment | 11        | 0.29%   |
| Sony                                 | 10        | 0.27%   |
| LG Electronics                       | 10        | 0.27%   |
| HONOR                                | 10        | 0.27%   |
| Chuwi                                | 9         | 0.24%   |
| AMI                                  | 9         | 0.24%   |
| Xiaomi                               | 8         | 0.21%   |
| TUXEDO                               | 8         | 0.21%   |
| Huanan                               | 8         | 0.21%   |
| SLIMBOOK                             | 7         | 0.19%   |
| Medion                               | 7         | 0.19%   |
| System76                             | 6         | 0.16%   |
| Supermicro                           | 6         | 0.16%   |
| Positivo                             | 6         | 0.16%   |
| MACHINIST                            | 6         | 0.16%   |
| Pegatron                             | 5         | 0.13%   |
| Itautec                              | 5         | 0.13%   |
| Schenker                             | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 31        | 0.83%   |
| ASUS All Series                                   | 19        | 0.51%   |
| Apple MacBookPro9,2                               | 14        | 0.37%   |
| MSI MS-7C56                                       | 13        | 0.35%   |
| MSI MS-7C91                                       | 12        | 0.32%   |
| Apple MacBookPro14,1                              | 12        | 0.32%   |
| MSI MS-7C02                                       | 11        | 0.29%   |
| Micro (HK) Tech Limited V3                        | 11        | 0.29%   |
| HP Notebook                                       | 11        | 0.29%   |
| HP EliteBook 840 G5                               | 10        | 0.27%   |
| Framework Laptop 16 (AMD Ryzen 7040 Series)       | 10        | 0.27%   |
| ASUS TUF Gaming X570-PLUS                         | 10        | 0.27%   |
| MSI MS-7B89                                       | 9         | 0.24%   |
| HUAWEI BOM-WXX9                                   | 9         | 0.24%   |
| Framework Laptop 13 (AMD Ryzen 7040Series)        | 9         | 0.24%   |
| AZW SER                                           | 9         | 0.24%   |
| ASUS TUF Gaming B550-PLUS                         | 9         | 0.24%   |
| Apple MacBookPro12,1                              | 9         | 0.24%   |
| Apple MacBookPro11,2                              | 9         | 0.24%   |
| MSI MS-7C52                                       | 8         | 0.21%   |
| Lenovo Yoga Pro 9 16IMH9 83DN                     | 8         | 0.21%   |
| HP EliteBook 840 G6                               | 8         | 0.21%   |
| Apple MacBookPro8,1                               | 8         | 0.21%   |
| Apple MacBookPro11,1                              | 8         | 0.21%   |
| Lenovo Legion Go 8APU1 83E1                       | 7         | 0.19%   |
| Intel X99                                         | 7         | 0.19%   |
| Dell OptiPlex 7050                                | 7         | 0.19%   |
| Dell OptiPlex 7010                                | 7         | 0.19%   |
| ASUS TUF Gaming B550M-PLUS WIFI II                | 7         | 0.19%   |
| ASUS PRIME A320M-K                                | 7         | 0.19%   |
| Apple Macmini7,1                                  | 7         | 0.19%   |
| Acer Nitro ANV15-51                               | 7         | 0.19%   |
| Shenzhen Meigao Electronic Equipment Venus series | 6         | 0.16%   |
| MSI MS-7D25                                       | 6         | 0.16%   |
| MSI MS-7C95                                       | 6         | 0.16%   |
| Lenovo Legion 5 15ACH6H 82JU                      | 6         | 0.16%   |
| Lenovo IdeaPad 3 15ITL6 82H8                      | 6         | 0.16%   |
| HP Pavilion Notebook                              | 6         | 0.16%   |
| Dell XPS 15 9500                                  | 6         | 0.16%   |
| Dell OptiPlex 9020                                | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 311       | 8.32%   |
| ASUS ROG           | 143       | 3.83%   |
| Lenovo IdeaPad     | 109       | 2.92%   |
| Dell Latitude      | 108       | 2.89%   |
| ASUS PRIME         | 91        | 2.43%   |
| Acer Aspire        | 85        | 2.27%   |
| ASUS VivoBook      | 83        | 2.22%   |
| ASUS TUF           | 80        | 2.14%   |
| Dell Inspiron      | 74        | 1.98%   |
| HP EliteBook       | 66        | 1.77%   |
| ASUS ASUS          | 64        | 1.71%   |
| HP Pavilion        | 58        | 1.55%   |
| Dell OptiPlex      | 57        | 1.52%   |
| Lenovo Legion      | 55        | 1.47%   |
| Dell Precision     | 55        | 1.47%   |
| Lenovo Yoga        | 53        | 1.42%   |
| Dell XPS           | 53        | 1.42%   |
| HP Laptop          | 50        | 1.34%   |
| HP ProBook         | 42        | 1.12%   |
| Acer Nitro         | 33        | 0.88%   |
| Unknown            | 31        | 0.83%   |
| Framework Laptop   | 28        | 0.75%   |
| Apple MacBookPro11 | 28        | 0.75%   |
| Lenovo ThinkBook   | 26        | 0.7%    |
| HP ENVY            | 26        | 0.7%    |
| Lenovo ThinkCentre | 23        | 0.62%   |
| HP Victus          | 23        | 0.62%   |
| HP OMEN            | 21        | 0.56%   |
| HP ZBook           | 20        | 0.54%   |
| HP EliteDesk       | 20        | 0.54%   |
| ASUS Zenbook       | 20        | 0.54%   |
| ASUS All           | 19        | 0.51%   |
| Microsoft Surface  | 18        | 0.48%   |
| Toshiba Satellite  | 16        | 0.43%   |
| Lenovo IdeaPadFlex | 15        | 0.4%    |
| Dell Vostro        | 15        | 0.4%    |
| Apple MacBookPro9  | 15        | 0.4%    |
| Gigabyte B550M     | 14        | 0.37%   |
| Gigabyte B550      | 14        | 0.37%   |
| Apple MacBookPro14 | 14        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 491       | 13.14%  |
| 2020    | 416       | 11.13%  |
| 2021    | 400       | 10.7%   |
| 2022    | 374       | 10.01%  |
| 2018    | 310       | 8.29%   |
| 2019    | 297       | 7.95%   |
| 2017    | 240       | 6.42%   |
| 2024    | 210       | 5.62%   |
| 2012    | 182       | 4.87%   |
| 2013    | 149       | 3.99%   |
| 2016    | 147       | 3.93%   |
| 2015    | 133       | 3.56%   |
| 2014    | 133       | 3.56%   |
| 2011    | 92        | 2.46%   |
| 2010    | 58        | 1.55%   |
| 2009    | 47        | 1.26%   |
| 2008    | 40        | 1.07%   |
| 2007    | 14        | 0.37%   |
| Unknown | 3         | 0.08%   |
| 2006    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2097      | 56.1%   |
| Desktop        | 1261      | 33.73%  |
| Convertible    | 150       | 4.01%   |
| Tablet         | 94        | 2.51%   |
| Mini pc        | 69        | 1.85%   |
| All in one     | 52        | 1.39%   |
| Server         | 13        | 0.35%   |
| System on chip | 2         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3423      | 91.26%  |
| Enabled  | 328       | 8.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3704      | 99.09%  |
| Yes  | 34        | 0.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 900       | 23.96%  |
| 32.01-64.0      | 762       | 20.29%  |
| 4.01-8.0        | 732       | 19.49%  |
| 8.01-16.0       | 682       | 18.16%  |
| 64.01-256.0     | 225       | 5.99%   |
| 3.01-4.0        | 203       | 5.4%    |
| 24.01-32.0      | 201       | 5.35%   |
| 1.01-2.0        | 37        | 0.99%   |
| 2.01-3.0        | 10        | 0.27%   |
| More than 256.0 | 4         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1451      | 36.79%  |
| 3.01-4.0    | 916       | 23.23%  |
| 2.01-3.0    | 828       | 20.99%  |
| 8.01-16.0   | 343       | 8.7%    |
| 1.01-2.0    | 312       | 7.91%   |
| 16.01-24.0  | 40        | 1.01%   |
| 0.51-1.0    | 37        | 0.94%   |
| 24.01-32.0  | 11        | 0.28%   |
| 32.01-64.0  | 3         | 0.08%   |
| 64.01-256.0 | 2         | 0.05%   |
| 0.01-0.5    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2207      | 58.39%  |
| 2      | 984       | 26.03%  |
| 3      | 333       | 8.81%   |
| 4      | 127       | 3.36%   |
| 5      | 64        | 1.69%   |
| 6      | 25        | 0.66%   |
| 7      | 19        | 0.5%    |
| 0      | 7         | 0.19%   |
| 8      | 5         | 0.13%   |
| 9      | 4         | 0.11%   |
| 12     | 2         | 0.05%   |
| 11     | 2         | 0.05%   |
| 10     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3094      | 82.62%  |
| Yes       | 651       | 17.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2946      | 78.62%  |
| No        | 801       | 21.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3052      | 81.36%  |
| No        | 699       | 18.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2892      | 77.1%   |
| No        | 859       | 22.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 825       | 21.93%  |
| Germany     | 302       | 8.03%   |
| Brazil      | 242       | 6.43%   |
| Russia      | 201       | 5.34%   |
| UK          | 184       | 4.89%   |
| Italy       | 150       | 3.99%   |
| France      | 132       | 3.51%   |
| India       | 130       | 3.46%   |
| Australia   | 107       | 2.84%   |
| Canada      | 103       | 2.74%   |
| Poland      | 87        | 2.31%   |
| Spain       | 86        | 2.29%   |
| Mexico      | 72        | 1.91%   |
| Netherlands | 71        | 1.89%   |
| Turkey      | 50        | 1.33%   |
| Sweden      | 42        | 1.12%   |
| Austria     | 41        | 1.09%   |
| Switzerland | 39        | 1.04%   |
| Chile       | 38        | 1.01%   |
| Denmark     | 35        | 0.93%   |
| Argentina   | 33        | 0.88%   |
| Norway      | 32        | 0.85%   |
| Czechia     | 31        | 0.82%   |
| Romania     | 30        | 0.8%    |
| Belgium     | 29        | 0.77%   |
| Hungary     | 28        | 0.74%   |
| Colombia    | 28        | 0.74%   |
| Portugal    | 26        | 0.69%   |
| Indonesia   | 25        | 0.66%   |
| Philippines | 24        | 0.64%   |
| Egypt       | 21        | 0.56%   |
| Serbia      | 20        | 0.53%   |
| Israel      | 20        | 0.53%   |
| Bulgaria    | 20        | 0.53%   |
| Greece      | 19        | 0.51%   |
| China       | 19        | 0.51%   |
| Finland     | 18        | 0.48%   |
| Ireland     | 17        | 0.45%   |
| Japan       | 16        | 0.43%   |
| Belarus     | 16        | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Sydney           | 47        | 1.22%   |
| Moscow           | 47        | 1.22%   |
| Berlin           | 37        | 0.96%   |
| St Petersburg    | 27        | 0.7%    |
| Milan            | 27        | 0.7%    |
| Sao Paulo        | 23        | 0.6%    |
| Paris            | 23        | 0.6%    |
| Santiago         | 22        | 0.57%   |
| Munich           | 21        | 0.55%   |
| Melbourne        | 21        | 0.55%   |
| Istanbul         | 21        | 0.55%   |
| Mexico City      | 20        | 0.52%   |
| Warsaw           | 19        | 0.5%    |
| Delhi            | 19        | 0.5%    |
| Vienna           | 18        | 0.47%   |
| Chicago          | 18        | 0.47%   |
| Amsterdam        | 16        | 0.42%   |
| Rio de Janeiro   | 15        | 0.39%   |
| Madrid           | 15        | 0.39%   |
| Dublin           | 15        | 0.39%   |
| Bogotá          | 15        | 0.39%   |
| Bengaluru        | 14        | 0.36%   |
| Belgrade         | 14        | 0.36%   |
| Montreal         | 13        | 0.34%   |
| Lima             | 13        | 0.34%   |
| Brisbane         | 13        | 0.34%   |
| Rome             | 12        | 0.31%   |
| Oslo             | 12        | 0.31%   |
| Hyderabad        | 12        | 0.31%   |
| Hamburg          | 12        | 0.31%   |
| Athens           | 12        | 0.31%   |
| Zurich           | 11        | 0.29%   |
| Sofia            | 11        | 0.29%   |
| New York         | 11        | 0.29%   |
| Los Angeles      | 11        | 0.29%   |
| Lisbon           | 11        | 0.29%   |
| Ho Chi Minh City | 11        | 0.29%   |
| Helsinki         | 11        | 0.29%   |
| Stockholm        | 10        | 0.26%   |
| Seattle          | 10        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 1014      | 1434   | 17.96%  |
| SanDisk                      | 597       | 709    | 10.57%  |
| Seagate                      | 474       | 661    | 8.4%    |
| WDC                          | 424       | 631    | 7.51%   |
| Kingston                     | 304       | 365    | 5.38%   |
| SK hynix                     | 257       | 289    | 4.55%   |
| Toshiba                      | 224       | 271    | 3.97%   |
| Unknown                      | 210       | 248    | 3.72%   |
| Micron Technology            | 204       | 219    | 3.61%   |
| Crucial                      | 176       | 227    | 3.12%   |
| Intel                        | 142       | 178    | 2.52%   |
| Phison Electronics           | 130       | 156    | 2.3%    |
| Micron/Crucial Technology    | 122       | 140    | 2.16%   |
| Apple                        | 98        | 133    | 1.74%   |
| Kingston Technology Company  | 94        | 96     | 1.66%   |
| KIOXIA                       | 88        | 107    | 1.56%   |
| China                        | 71        | 78     | 1.26%   |
| ADATA Technology             | 69        | 79     | 1.22%   |
| HGST                         | 65        | 71     | 1.15%   |
| Hitachi                      | 60        | 73     | 1.06%   |
| Silicon Motion               | 57        | 65     | 1.01%   |
| A-DATA Technology            | 56        | 66     | 0.99%   |
| MAXIO Technology (Hangzhou)  | 48        | 51     | 0.85%   |
| Shenzhen Longsys Electronics | 44        | 50     | 0.78%   |
| Realtek Semiconductor        | 39        | 42     | 0.69%   |
| SPCC                         | 30        | 33     | 0.53%   |
| Unknown                      | 29        | 34     | 0.51%   |
| Patriot                      | 22        | 38     | 0.39%   |
| PNY                          | 21        | 22     | 0.37%   |
| JMicron Technology           | 18        | 21     | 0.32%   |
| KingSpec                     | 17        | 21     | 0.3%    |
| Union Memory (Shenzhen)      | 14        | 16     | 0.25%   |
| LITEON                       | 14        | 16     | 0.25%   |
| Transcend                    | 13        | 16     | 0.23%   |
| OCZ                          | 13        | 16     | 0.23%   |
| Lexar                        | 12        | 15     | 0.21%   |
| Intenso                      | 12        | 14     | 0.21%   |
| Corsair                      | 12        | 14     | 0.21%   |
| Team                         | 11        | 12     | 0.19%   |
| Apacer                       | 11        | 12     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 250       | 4.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 181       | 2.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 74        | 1.21%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 73        | 1.19%   |
| Kingston SA400S37240G 240GB SSD                       | 61        | 1%      |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 58        | 0.95%   |
| Kingston SA400S37480G 480GB SSD                       | 55        | 0.9%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 52        | 0.85%   |
| Unknown MMC Card  128GB                               | 45        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 43        | 0.7%    |
| Phison E12 NVMe Controller 480GB                      | 42        | 0.69%   |
| Unknown MMC Card  32GB                                | 40        | 0.65%   |
| Samsung SSD 860 EVO 500GB                             | 40        | 0.65%   |
| Intel SSD 660P Series 1024GB                          | 37        | 0.6%    |
| Unknown MMC Card  64GB                                | 36        | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB                        | 36        | 0.59%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 35        | 0.57%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 33        | 0.54%   |
| Samsung SSD 850 EVO 250GB                             | 32        | 0.52%   |
| Samsung SSD 860 EVO 1TB                               | 31        | 0.51%   |
| Kingston Company SNV2S1000G 1TB                       | 31        | 0.51%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 29        | 0.47%   |
| Samsung SSD 870 EVO 1TB                               | 29        | 0.47%   |
| Unknown                                               | 29        | 0.47%   |
| Sandisk WD Black SN850 2TB                            | 28        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                           | 26        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                        | 25        | 0.41%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB       | 25        | 0.41%   |
| Samsung SSD 990 PRO 2TB                               | 25        | 0.41%   |
| Samsung SSD 980 1TB                                   | 25        | 0.41%   |
| Intel SSDPEKNU512GZ 512GB                             | 24        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                          | 24        | 0.39%   |
| Samsung SSD 850 EVO 500GB                             | 23        | 0.38%   |
| Seagate ST500DM002-1BD142 500GB                       | 22        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB                        | 22        | 0.36%   |
| Sandisk WD_BLACK SN850X 1000GB                        | 22        | 0.36%   |
| Crucial CT500MX500SSD1 500GB                          | 22        | 0.36%   |
| Samsung SSD 870 EVO 500GB                             | 21        | 0.34%   |
| Kingston Company A2000 NVMe SSD 500GB                 | 21        | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 20        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 461       | 637    | 39.13%  |
| WDC                 | 351       | 525    | 29.8%   |
| Toshiba             | 149       | 177    | 12.65%  |
| HGST                | 65        | 71     | 5.52%   |
| Hitachi             | 60        | 73     | 5.09%   |
| Samsung Electronics | 25        | 65     | 2.12%   |
| Apple               | 18        | 18     | 1.53%   |
| JMicron Technology  | 13        | 16     | 1.1%    |
| Unknown             | 11        | 11     | 0.93%   |
| SABRENT             | 5         | 5      | 0.42%   |
| ASMT                | 5         | 17     | 0.42%   |
| TO Exter            | 2         | 2      | 0.17%   |
| External            | 2         | 3      | 0.17%   |
| USB3.0              | 1         | 2      | 0.08%   |
| USB                 | 1         | 1      | 0.08%   |
| SAGE                | 1         | 1      | 0.08%   |
| RSH-319             | 1         | 2      | 0.08%   |
| Maxtor              | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| Initio              | 1         | 1      | 0.08%   |
| Inateck             | 1         | 2      | 0.08%   |
| HCG8e               | 1         | 1      | 0.08%   |
| Fujitsu             | 1         | 1      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 378       | 519    | 23.39%  |
| Kingston            | 215       | 250    | 13.3%   |
| Crucial             | 176       | 227    | 10.89%  |
| SanDisk             | 123       | 145    | 7.61%   |
| WDC                 | 90        | 104    | 5.57%   |
| China               | 71        | 78     | 4.39%   |
| Apple               | 59        | 62     | 3.65%   |
| A-DATA Technology   | 50        | 56     | 3.09%   |
| Intel               | 38        | 52     | 2.35%   |
| SK hynix            | 36        | 44     | 2.23%   |
| SPCC                | 30        | 33     | 1.86%   |
| Micron Technology   | 27        | 28     | 1.67%   |
| PNY                 | 21        | 22     | 1.3%    |
| Patriot             | 21        | 37     | 1.3%    |
| KingSpec            | 17        | 21     | 1.05%   |
| LITEON              | 14        | 16     | 0.87%   |
| Transcend           | 13        | 16     | 0.8%    |
| Toshiba             | 13        | 21     | 0.8%    |
| OCZ                 | 13        | 16     | 0.8%    |
| Corsair             | 12        | 14     | 0.74%   |
| Intenso             | 11        | 13     | 0.68%   |
| Apacer              | 11        | 12     | 0.68%   |
| Team                | 10        | 10     | 0.62%   |
| Lexar               | 10        | 13     | 0.62%   |
| GOODRAM             | 10        | 10     | 0.62%   |
| Fanxiang            | 8         | 8      | 0.5%    |
| Hewlett-Packard     | 7         | 10     | 0.43%   |
| Unknown             | 7         | 7      | 0.43%   |
| Verbatim            | 6         | 7      | 0.37%   |
| Netac               | 6         | 7      | 0.37%   |
| XrayDisk            | 5         | 5      | 0.31%   |
| Gigabyte Technology | 5         | 5      | 0.31%   |
| LITEONIT            | 4         | 7      | 0.25%   |
| FORESEE             | 4         | 4      | 0.25%   |
| Emtec               | 4         | 4      | 0.25%   |
| USB3.0              | 3         | 3      | 0.19%   |
| Plextor             | 3         | 5      | 0.19%   |
| Mushkin             | 3         | 3      | 0.19%   |
| HUSKY               | 3         | 3      | 0.19%   |
| Dogfish             | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2384      | 3191   | 47.14%  |
| SSD     | 1395      | 1984   | 27.59%  |
| HDD     | 1008      | 1634   | 19.93%  |
| MMC     | 166       | 191    | 3.28%   |
| Unknown | 104       | 125    | 2.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2381      | 3165   | 51.13%  |
| SATA | 1888      | 3464   | 40.54%  |
| SAS  | 222       | 305    | 4.77%   |
| MMC  | 166       | 191    | 3.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1250      | 1835   | 49.43%  |
| 0.51-1.0   | 793       | 1062   | 31.36%  |
| 1.01-2.0   | 270       | 375    | 10.68%  |
| 3.01-4.0   | 89        | 145    | 3.52%   |
| 4.01-10.0  | 60        | 111    | 2.37%   |
| 2.01-3.0   | 45        | 55     | 1.78%   |
| 10.01-20.0 | 22        | 35     | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 855       | 22.44%  |
| 1001-2000      | 673       | 17.66%  |
| 251-500        | 647       | 16.98%  |
| 101-250        | 449       | 11.78%  |
| More than 3000 | 371       | 9.74%   |
| 1-20           | 264       | 6.93%   |
| Unknown        | 253       | 6.64%   |
| 2001-3000      | 154       | 4.04%   |
| 51-100         | 105       | 2.76%   |
| 21-50          | 39        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1242      | 31.86%  |
| 21-50          | 611       | 15.67%  |
| 101-250        | 476       | 12.21%  |
| 51-100         | 428       | 10.98%  |
| 251-500        | 326       | 8.36%   |
| 501-1000       | 266       | 6.82%   |
| Unknown        | 253       | 6.49%   |
| 1001-2000      | 156       | 4%      |
| More than 3000 | 83        | 2.13%   |
| 2001-3000      | 56        | 1.44%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                            | Computers | Drives  | Percent |
|------------------------------------------------------------------|-----------|---------|---------|
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB  | 5         | 6       | 3.73%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4         | 4       | 2.99%   |
| Samsung Electronics SSD 870 EVO 1TB                              | 3         | 3       | 2.24%   |
| Intel SSDSC2CT120A3 120GB                                        | 3         | 9       | 2.24%   |
| WDC WD40EFRX-68N32N0 4TB                                         | 2         | 6       | 1.49%   |
| Toshiba MQ01ABD100 1TB                                           | 2         | 2       | 1.49%   |
| Toshiba DT01ACA100 1TB                                           | 2         | 2       | 1.49%   |
| Seagate ST3500418AS 500GB                                        | 2         | 5       | 1.49%   |
| Seagate ST31000524AS 1TB                                         | 2         | 6       | 1.49%   |
| Seagate ST1000LM049-2GH172 1TB                                   | 2         | 2       | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB                                   | 2         | 2       | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                               | 2         | 2       | 1.49%   |
| Seagate ST1000DM003-1ER162 1TB                                   | 2         | 2       | 1.49%   |
| Samsung Electronics HD501LJ 500GB                                | 2         | 12      | 1.49%   |
| Samsung Electronics HD103UJ 1TB                                  | 2         | 11      | 1.49%   |
| Kingston SUV500240G 240GB SSD                                    | 2         | 2       | 1.49%   |
| Kingston SA400S37480G 480GB SSD                                  | 2         | 3       | 1.49%   |
| HGST HTS725050A7E630 500GB                                       | 2         | 2       | 1.49%   |
| HGST HTS721010A9E630 1TB                                         | 2         | 2       | 1.49%   |
| Crucial CT120M500SSD1 120GB                                      | 2         | 2       | 1.49%   |
| XrayDisk SSD 256GB                                               | 1         | 1       | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                 | 1         | 2       | 0.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                 | 1         | 1       | 0.75%   |
| WDC WD6004FZWX-00BKVA0 6TB                                       | 1         | 1       | 0.75%   |
| WDC WD5000AVCS-632DY1 500GB                                      | 1         | 6       | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB                                     | 1         | 1       | 0.75%   |
| WDC WD5000AAKX-603CA0 500GB                                      | 1         | 1       | 0.75%   |
| WDC WD5000AAKX-08U6AA0 500GB                                     | 1         | 1       | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB                                      | 1         | 1       | 0.75%   |
| WDC WD5000AADS-00S9B0 500GB                                      | 1         | 1       | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB                                         | 1         | 1       | 0.75%   |
| WDC WD3200BEKT-60KA9T0 320GB                                     | 1         | 1       | 0.75%   |
| WDC WD20EZRX-00D 2TB                                             | 1         | Unknown | 0.75%   |
| WDC WD10SPZX-60Z10T1 1TB                                         | 1         | 1       | 0.75%   |
| WDC WD10SPZX-24Z10T0 1TB                                         | 1         | 1       | 0.75%   |
| WDC WD10JPCX-24UE4T0 1TB                                         | 1         | 1       | 0.75%   |
| WDC WD10EZEX-60ZF5A0 1TB                                         | 1         | 1       | 0.75%   |
| WDC WD10EZEX-60WN4A2 1TB                                         | 1         | 1       | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB                                         | 1         | 1       | 0.75%   |
| WDC WD10EZEX-08RKKA0 1TB                                         | 1         | 1       | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 28        | 45     | 21.05%  |
| WDC                         | 23        | 32     | 17.29%  |
| Samsung Electronics         | 20        | 41     | 15.04%  |
| Hitachi                     | 9         | 9      | 6.77%   |
| Toshiba                     | 8         | 8      | 6.02%   |
| Kingston                    | 8         | 9      | 6.02%   |
| HGST                        | 6         | 6      | 4.51%   |
| Intel                       | 5         | 13     | 3.76%   |
| Crucial                     | 5         | 5      | 3.76%   |
| Transcend                   | 3         | 3      | 2.26%   |
| China                       | 3         | 3      | 2.26%   |
| SK hynix                    | 2         | 2      | 1.5%    |
| SanDisk                     | 2         | 2      | 1.5%    |
| XrayDisk                    | 1         | 1      | 0.75%   |
| Silicon Motion              | 1         | 1      | 0.75%   |
| Neo                         | 1         | 1      | 0.75%   |
| Micron Technology           | 1         | 1      | 0.75%   |
| Maxtor                      | 1         | 1      | 0.75%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.75%   |
| Lite-On Technology          | 1         | 1      | 0.75%   |
| Intenso                     | 1         | 1      | 0.75%   |
| Hewlett-Packard             | 1         | 1      | 0.75%   |
| Corsair                     | 1         | 1      | 0.75%   |
| ADATA Technology            | 1         | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 45     | 35.9%   |
| WDC                 | 21        | 29     | 26.92%  |
| Hitachi             | 9         | 9      | 11.54%  |
| Toshiba             | 8         | 8      | 10.26%  |
| HGST                | 6         | 6      | 7.69%   |
| Samsung Electronics | 5         | 25     | 6.41%   |
| Maxtor              | 1         | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 75        | 123    | 58.59%  |
| SSD  | 37        | 49     | 28.91%  |
| NVMe | 16        | 17     | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Hitachi HDS721010DLE630 1TB      | 1         | 2      | 25%     |
| HGST HTS541010A9E680 1TB         | 1         | 1      | 25%     |
| Apple SSD SM0256F 256GB          | 1         | 1      | 25%     |
| ADATA Technology SX6000LNP 256GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor           | Computers | Drives | Percent |
|------------------|-----------|--------|---------|
| Hitachi          | 1         | 2      | 25%     |
| HGST             | 1         | 1      | 25%     |
| Apple            | 1         | 1      | 25%     |
| ADATA Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2651      | 4921   | 67.47%  |
| Works    | 1152      | 2010   | 29.32%  |
| Malfunc  | 122       | 189    | 3.11%   |
| Failed   | 4         | 5      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1868      | 34.59%  |
| AMD                                     | 738       | 13.66%  |
| Samsung Electronics                     | 732       | 13.55%  |
| SanDisk                                 | 486       | 9%      |
| SK hynix                                | 222       | 4.11%   |
| Kingston Technology Company             | 185       | 3.43%   |
| Micron Technology                       | 177       | 3.28%   |
| Phison Electronics                      | 138       | 2.56%   |
| Micron/Crucial Technology               | 121       | 2.24%   |
| KIOXIA                                  | 88        | 1.63%   |
| ASMedia Technology                      | 85        | 1.57%   |
| ADATA Technology                        | 75        | 1.39%   |
| Toshiba America Info Systems            | 64        | 1.18%   |
| Silicon Motion                          | 57        | 1.06%   |
| MAXIO Technology (Hangzhou)             | 47        | 0.87%   |
| Shenzhen Longsys Electronics            | 45        | 0.83%   |
| Realtek Semiconductor                   | 39        | 0.72%   |
| Marvell Technology Group                | 25        | 0.46%   |
| Apple                                   | 24        | 0.44%   |
| Nvidia                                  | 19        | 0.35%   |
| JMicron Technology                      | 19        | 0.35%   |
| Solid State Storage Technology          | 18        | 0.33%   |
| Solidigm                                | 17        | 0.31%   |
| Union Memory (Shenzhen)                 | 14        | 0.26%   |
| Seagate Technology                      | 12        | 0.22%   |
| Shenzhen Unionmemory Information System | 10        | 0.19%   |
| INNOGRIT                                | 10        | 0.19%   |
| Biwin Storage Technology                | 8         | 0.15%   |
| Yangtze Memory Technologies             | 7         | 0.13%   |
| LSI Logic / Symbios Logic               | 7         | 0.13%   |
| Lite-On Technology                      | 6         | 0.11%   |
| VIA Technologies                        | 5         | 0.09%   |
| Broadcom / LSI                          | 5         | 0.09%   |
| Unknown                                 | 5         | 0.09%   |
| Lenovo                                  | 4         | 0.07%   |
| Shenzhen Shichuangyi Electronics        | 3         | 0.06%   |
| Netac Technology                        | 3         | 0.06%   |
| Hosin Global Electronics                | 3         | 0.06%   |
| Adaptec                                 | 3         | 0.06%   |
| Transcend                               | 2         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 362       | 6.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 255       | 4.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 182       | 3.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 168       | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 164       | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 152       | 2.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 117       | 1.99%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 110       | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 110       | 1.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 108       | 1.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 99        | 1.69%   |
| AMD 600 Series Chipset SATA Controller                                         | 99        | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 92        | 1.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 83        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 74        | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 74        | 1.26%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 73        | 1.24%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 72        | 1.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 72        | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 67        | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 64        | 1.09%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 60        | 1.02%   |
| Intel SATA Controller [RAID mode]                                              | 58        | 0.99%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 57        | 0.97%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 56        | 0.95%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 55        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 55        | 0.94%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 54        | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 53        | 0.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 52        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 52        | 0.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 48        | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 47        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 46        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 44        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 43        | 0.73%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 43        | 0.73%   |
| Phison E12 NVMe Controller                                                     | 42        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 41        | 0.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 41        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 2373      | 45.78%  |
| SATA | 2264      | 43.67%  |
| RAID | 418       | 8.06%   |
| IDE  | 118       | 2.28%   |
| SAS  | 8         | 0.15%   |
| SCSI | 3         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2572      | 68.81%  |
| AMD      | 1159      | 31.01%  |
| ARM      | 4         | 0.11%   |
| Unknown  | 2         | 0.05%   |
| Qualcomm | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 52        | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 39        | 1.04%   |
| AMD Ryzen 5 3600 6-Core Processor          | 38        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 35        | 0.93%   |
| Intel Core Ultra 7 155H                    | 32        | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 32        | 0.85%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 32        | 0.85%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 30        | 0.8%    |
| Intel 12th Gen Core i7-12700H              | 29        | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 29        | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 28        | 0.75%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 28        | 0.75%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 27        | 0.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics     | 27        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 26        | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 26        | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 26        | 0.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 25        | 0.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 24        | 0.64%   |
| Intel 12th Gen Core i5-1235U               | 24        | 0.64%   |
| AMD Ryzen 7 5700G with Radeon Graphics     | 24        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 23        | 0.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 23        | 0.61%   |
| AMD Ryzen 5 5600H with Radeon Graphics     | 23        | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 22        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 22        | 0.59%   |
| Intel Core Ultra 9 185H                    | 21        | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 21        | 0.56%   |
| Intel 13th Gen Core i7-13700H              | 21        | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 21        | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 20        | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 20        | 0.53%   |
| Intel 12th Gen Core i7-1255U               | 20        | 0.53%   |
| Intel 12th Gen Core i5-12450H              | 20        | 0.53%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 20        | 0.53%   |
| Intel Core i5-8365U CPU @ 1.60GHz          | 19        | 0.51%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 19        | 0.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 18        | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 18        | 0.48%   |
| AMD Ryzen 7 5700X 8-Core Processor         | 18        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 709       | 18.95%  |
| Intel Core i5           | 706       | 18.87%  |
| Intel Core i7           | 617       | 16.49%  |
| AMD Ryzen 7             | 394       | 10.53%  |
| AMD Ryzen 5             | 350       | 9.35%   |
| AMD Ryzen 9             | 164       | 4.38%   |
| Intel Core i3           | 134       | 3.58%   |
| Intel Xeon              | 78        | 2.08%   |
| Intel Core              | 69        | 1.84%   |
| Intel Celeron           | 66        | 1.76%   |
| Intel Core 2 Duo        | 54        | 1.44%   |
| AMD Ryzen 3             | 53        | 1.42%   |
| Intel Atom              | 45        | 1.2%    |
| Intel Pentium           | 44        | 1.18%   |
| Intel Core i9           | 44        | 1.18%   |
| AMD Ryzen 7 PRO         | 31        | 0.83%   |
| AMD Ryzen 5 PRO         | 28        | 0.75%   |
| AMD FX                  | 19        | 0.51%   |
| AMD A8                  | 11        | 0.29%   |
| AMD A6                  | 11        | 0.29%   |
| AMD Phenom II X4        | 10        | 0.27%   |
| AMD A4                  | 10        | 0.27%   |
| AMD A10                 | 10        | 0.27%   |
| Intel Pentium Silver    | 9         | 0.24%   |
| Intel Pentium Dual-Core | 8         | 0.21%   |
| Intel Core 2 Quad       | 7         | 0.19%   |
| Intel Core m3           | 4         | 0.11%   |
| AMD Ryzen Threadripper  | 4         | 0.11%   |
| AMD Athlon              | 4         | 0.11%   |
| Intel Pentium Gold      | 3         | 0.08%   |
| Intel Core m5           | 3         | 0.08%   |
| AMD Phenom II X2        | 3         | 0.08%   |
| AMD Opteron             | 3         | 0.08%   |
| AMD GX                  | 3         | 0.08%   |
| AMD Athlon II X2        | 3         | 0.08%   |
| Intel Xeon Gold         | 2         | 0.05%   |
| Intel Genuine           | 2         | 0.05%   |
| Intel Core M            | 2         | 0.05%   |
| AMD PRO A10             | 2         | 0.05%   |
| AMD Phenom II X6        | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1179      | 31.52%  |
| 2       | 723       | 19.33%  |
| 8       | 616       | 16.47%  |
| 6       | 582       | 15.56%  |
| 12      | 172       | 4.6%    |
| 16      | 140       | 3.74%   |
| 10      | 137       | 3.66%   |
| 14      | 120       | 3.21%   |
| 24      | 45        | 1.2%    |
| 20      | 8         | 0.21%   |
| 1       | 5         | 0.13%   |
| 28      | 3         | 0.08%   |
| 5       | 3         | 0.08%   |
| 3       | 3         | 0.08%   |
| 32      | 2         | 0.05%   |
| 44      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3715      | 99.36%  |
| 2       | 22        | 0.59%   |
| 4       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3102      | 82.96%  |
| 1       | 635       | 16.98%  |
| 3       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3733      | 99.87%  |
| 64-bit         | 5         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3733      | 99.76%  |
| 0x206a7    | 2         | 0.05%   |
| 0x0a50000c | 2         | 0.05%   |
| 0x0a601206 | 1         | 0.03%   |
| 0x0a601203 | 1         | 0.03%   |
| 0x08701033 | 1         | 0.03%   |
| 0x08001138 | 1         | 0.03%   |
| 0x010000c8 | 1         | 0.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 798       | 21.33%  |
| KabyLake          | 599       | 16.01%  |
| Zen 3             | 344       | 9.2%    |
| Haswell           | 228       | 6.09%   |
| IvyBridge         | 190       | 5.08%   |
| Alderlake Hybrid  | 181       | 4.84%   |
| Skylake           | 180       | 4.81%   |
| Zen 2             | 168       | 4.49%   |
| TigerLake         | 160       | 4.28%   |
| SandyBridge       | 112       | 2.99%   |
| CometLake         | 112       | 2.99%   |
| Zen+              | 94        | 2.51%   |
| Broadwell         | 72        | 1.92%   |
| Silvermont        | 65        | 1.74%   |
| Penryn            | 60        | 1.6%    |
| Icelake           | 56        | 1.5%    |
| Zen               | 49        | 1.31%   |
| Meteorlake Hybrid | 37        | 0.99%   |
| Westmere          | 36        | 0.96%   |
| Goldmont plus     | 31        | 0.83%   |
| Piledriver        | 27        | 0.72%   |
| Excavator         | 25        | 0.67%   |
| K10               | 22        | 0.59%   |
| Nehalem           | 18        | 0.48%   |
| Core              | 15        | 0.4%    |
| Gracemont         | 12        | 0.32%   |
| Puma              | 9         | 0.24%   |
| Tremont           | 6         | 0.16%   |
| Jaguar            | 6         | 0.16%   |
| Bonnell           | 6         | 0.16%   |
| Steamroller       | 5         | 0.13%   |
| Goldmont          | 5         | 0.13%   |
| K10 Llano         | 4         | 0.11%   |
| K8 Hammer         | 3         | 0.08%   |
| Bulldozer         | 2         | 0.05%   |
| Bobcat            | 2         | 0.05%   |
| Sapphire Rapids   | 1         | 0.03%   |
| NetBurst          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2060      | 44.73%  |
| Nvidia                     | 1364      | 29.62%  |
| AMD                        | 1172      | 25.45%  |
| Matrox Electronics Systems | 6         | 0.13%   |
| ASPEED Technology          | 3         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 140       | 2.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 129       | 2.72%   |
| Intel UHD Graphics 620                                                                   | 111       | 2.34%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 103       | 2.18%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 94        | 1.99%   |
| AMD Phoenix1                                                                             | 85        | 1.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 78        | 1.65%   |
| AMD Rembrandt [Radeon 680M]                                                              | 75        | 1.58%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 72        | 1.52%   |
| Intel HD Graphics 620                                                                    | 71        | 1.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 70        | 1.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 69        | 1.46%   |
| AMD Raphael                                                                              | 69        | 1.46%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 67        | 1.42%   |
| AMD Lucienne                                                                             | 67        | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 63        | 1.33%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 60        | 1.27%   |
| Intel HD Graphics 530                                                                    | 60        | 1.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 60        | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 57        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 55        | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 54        | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 52        | 1.1%    |
| Intel HD Graphics 630                                                                    | 50        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 49        | 1.04%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 45        | 0.95%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 44        | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 42        | 0.89%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 42        | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 41        | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 41        | 0.87%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 39        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 37        | 0.78%   |
| AMD Phoenix3                                                                             | 37        | 0.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 36        | 0.76%   |
| Intel HD Graphics 5500                                                                   | 36        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 36        | 0.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 0.72%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 34        | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 32        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1356      | 36.21%  |
| 1 x AMD                  | 837       | 22.35%  |
| 1 x Nvidia               | 612       | 16.34%  |
| Intel + Nvidia           | 568       | 15.17%  |
| AMD + Nvidia             | 164       | 4.38%   |
| 2 x AMD                  | 100       | 2.67%   |
| Intel + AMD              | 65        | 1.74%   |
| Other                    | 10        | 0.27%   |
| 2 x Nvidia               | 10        | 0.27%   |
| 2 x Intel                | 9         | 0.24%   |
| 1 x Matrox               | 3         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.08%   |
| 1 x ASPEED               | 3         | 0.08%   |
| AMD + Matrox             | 2         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.03%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| AMD + 2 x Nvidia         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2900      | 77.03%  |
| Proprietary | 521       | 13.84%  |
| Unknown     | 344       | 9.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3092      | 82.12%  |
| 0.01-0.5   | 149       | 3.96%   |
| 7.01-8.0   | 110       | 2.92%   |
| 1.01-2.0   | 107       | 2.84%   |
| 3.01-4.0   | 102       | 2.71%   |
| 8.01-16.0  | 77        | 2.05%   |
| 0.51-1.0   | 57        | 1.51%   |
| 5.01-6.0   | 53        | 1.41%   |
| 16.01-24.0 | 14        | 0.37%   |
| 2.01-3.0   | 3         | 0.08%   |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 503       | 11.84%  |
| BOE                     | 478       | 11.25%  |
| AU Optronics            | 446       | 10.5%   |
| Chimei Innolux          | 361       | 8.5%    |
| Goldstar                | 269       | 6.33%   |
| LG Display              | 266       | 6.26%   |
| Dell                    | 265       | 6.24%   |
| Apple                   | 157       | 3.7%    |
| Hewlett-Packard         | 122       | 2.87%   |
| Acer                    | 109       | 2.57%   |
| AOC                     | 102       | 2.4%    |
| Philips                 | 90        | 2.12%   |
| Sharp                   | 89        | 2.1%    |
| Lenovo                  | 75        | 1.77%   |
| ASUSTek Computer        | 70        | 1.65%   |
| BenQ                    | 65        | 1.53%   |
| CSO                     | 59        | 1.39%   |
| Ancor Communications    | 52        | 1.22%   |
| InfoVision              | 48        | 1.13%   |
| MSI                     | 45        | 1.06%   |
| PANDA                   | 41        | 0.97%   |
| Iiyama                  | 40        | 0.94%   |
| ViewSonic               | 38        | 0.89%   |
| Gigabyte Technology     | 30        | 0.71%   |
| Chi Mei Optoelectronics | 21        | 0.49%   |
| TMX                     | 20        | 0.47%   |
| Unknown                 | 17        | 0.4%    |
| Sony                    | 17        | 0.4%    |
| Sceptre Tech            | 16        | 0.38%   |
| CSW                     | 15        | 0.35%   |
| HKC                     | 12        | 0.28%   |
| Mi                      | 11        | 0.26%   |
| Eizo                    | 11        | 0.26%   |
| Vizio                   | 10        | 0.24%   |
| Pixio                   | 8         | 0.19%   |
| Unknown (XXX)           | 7         | 0.16%   |
| HUAWEI                  | 7         | 0.16%   |
| Fujitsu Siemens         | 7         | 0.16%   |
| Vestel Elektronik       | 6         | 0.14%   |
| Toshiba                 | 6         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 26        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 21        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 18        | 0.41%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 18        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 16        | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 15        | 0.34%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 15        | 0.34%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 14        | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 14        | 0.32%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                 | 14        | 0.32%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 14        | 0.32%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 12        | 0.27%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 11        | 0.25%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 11        | 0.25%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 10        | 0.23%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 10        | 0.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 10        | 0.23%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 10        | 0.23%   |
| BOE LCD Monitor BOE0B7B 2560x1600 302x188mm 14.0-inch                 | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 10        | 0.23%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                 | 10        | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 9         | 0.2%    |
| BOE LCD Monitor BOE0BC9 2560x1600 345x215mm 16.0-inch                 | 9         | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.2%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 9         | 0.2%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 9         | 0.2%    |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 8         | 0.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 8         | 0.18%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 8         | 0.18%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 8         | 0.18%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 8         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1817      | 44.52%  |
| 3840x2160 (4K)     | 384       | 9.41%   |
| 1366x768 (WXGA)    | 341       | 8.36%   |
| 2560x1440 (QHD)    | 340       | 8.33%   |
| 1920x1200 (WUXGA)  | 198       | 4.85%   |
| 2560x1600          | 144       | 3.53%   |
| 2880x1800          | 131       | 3.21%   |
| 3440x1440          | 109       | 2.67%   |
| 1600x900 (HD+)     | 80        | 1.96%   |
| 1440x900 (WXGA+)   | 56        | 1.37%   |
| 2560x1080          | 51        | 1.25%   |
| 1680x1050 (WSXGA+) | 46        | 1.13%   |
| 1280x800 (WXGA)    | 45        | 1.1%    |
| 1280x1024 (SXGA)   | 38        | 0.93%   |
| 3840x2400          | 31        | 0.76%   |
| 3200x2000          | 27        | 0.66%   |
| 3840x1080          | 19        | 0.47%   |
| 2256x1504          | 18        | 0.44%   |
| Unknown            | 17        | 0.42%   |
| 1920x1280          | 15        | 0.37%   |
| 2288x1287          | 14        | 0.34%   |
| 2160x1440          | 14        | 0.34%   |
| 1360x768           | 14        | 0.34%   |
| 2240x1400          | 11        | 0.27%   |
| 2880x1920          | 10        | 0.25%   |
| 3200x1800 (QHD+)   | 9         | 0.22%   |
| 3000x2000          | 8         | 0.2%    |
| 1920x540           | 8         | 0.2%    |
| 3456x2160          | 7         | 0.17%   |
| 3072x1920          | 7         | 0.17%   |
| 3840x1600          | 6         | 0.15%   |
| 2880x1620          | 6         | 0.15%   |
| 1024x768 (XGA)     | 5         | 0.12%   |
| 800x1280           | 4         | 0.1%    |
| 3840x1100          | 4         | 0.1%    |
| 2400x1600          | 4         | 0.1%    |
| 1800x1200          | 4         | 0.1%    |
| 1600x1200          | 4         | 0.1%    |
| 2560x2880          | 3         | 0.07%   |
| 2304x1440          | 3         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 952       | 22.34%  |
| 14      | 445       | 10.44%  |
| 27      | 415       | 9.74%   |
| 13      | 401       | 9.41%   |
| 24      | 357       | 8.38%   |
| 23      | 209       | 4.9%    |
| 16      | 206       | 4.83%   |
| 31      | 194       | 4.55%   |
| 21      | 160       | 3.75%   |
| 34      | 140       | 3.28%   |
| 17      | 131       | 3.07%   |
| 12      | 69        | 1.62%   |
| 19      | 58        | 1.36%   |
| Unknown | 54        | 1.27%   |
| 22      | 44        | 1.03%   |
| 18      | 43        | 1.01%   |
| 20      | 37        | 0.87%   |
| 32      | 33        | 0.77%   |
| 84      | 31        | 0.73%   |
| 11      | 30        | 0.7%    |
| 72      | 23        | 0.54%   |
| 40      | 20        | 0.47%   |
| 48      | 17        | 0.4%    |
| 28      | 17        | 0.4%    |
| 54      | 16        | 0.38%   |
| 26      | 16        | 0.38%   |
| 142     | 14        | 0.33%   |
| 10      | 9         | 0.21%   |
| 42      | 8         | 0.19%   |
| 39      | 8         | 0.19%   |
| 65      | 7         | 0.16%   |
| 52      | 7         | 0.16%   |
| 49      | 7         | 0.16%   |
| 37      | 7         | 0.16%   |
| 25      | 7         | 0.16%   |
| 43      | 6         | 0.14%   |
| 35      | 6         | 0.14%   |
| 47      | 5         | 0.12%   |
| 29      | 5         | 0.12%   |
| 7       | 5         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1703      | 40.86%  |
| 501-600        | 890       | 21.35%  |
| 201-300        | 378       | 9.07%   |
| 401-500        | 309       | 7.41%   |
| 601-700        | 252       | 6.05%   |
| 351-400        | 180       | 4.32%   |
| 701-800        | 179       | 4.29%   |
| 1001-1500      | 81        | 1.94%   |
| 1501-2000      | 60        | 1.44%   |
| Unknown        | 54        | 1.3%    |
| 801-900        | 42        | 1.01%   |
| 901-1000       | 18        | 0.43%   |
| More than 2000 | 14        | 0.34%   |
| 101-200        | 4         | 0.1%    |
| 1-100          | 4         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2720      | 70.87%  |
| 16/10   | 725       | 18.89%  |
| 21/9    | 163       | 4.25%   |
| 3/2     | 87        | 2.27%   |
| 5/4     | 33        | 0.86%   |
| 32/9    | 24        | 0.63%   |
| Unknown | 23        | 0.6%    |
| 4/3     | 21        | 0.55%   |
| 1.00    | 16        | 0.42%   |
| 6/5     | 6         | 0.16%   |
| 3.40    | 4         | 0.1%    |
| 0.89    | 3         | 0.08%   |
| 2.12    | 2         | 0.05%   |
| 0.67    | 2         | 0.05%   |
| 0.62    | 2         | 0.05%   |
| 0.56    | 2         | 0.05%   |
| 3.20    | 1         | 0.03%   |
| 2.69    | 1         | 0.03%   |
| 2.01    | 1         | 0.03%   |
| 2.00    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 970       | 22.96%  |
| 81-90          | 658       | 15.58%  |
| 201-250        | 566       | 13.4%   |
| 301-350        | 428       | 10.13%  |
| 351-500        | 385       | 9.11%   |
| 111-120        | 189       | 4.47%   |
| 71-80          | 163       | 3.86%   |
| 151-200        | 150       | 3.55%   |
| 251-300        | 146       | 3.46%   |
| More than 1000 | 121       | 2.86%   |
| 121-130        | 109       | 2.58%   |
| 501-1000       | 90        | 2.13%   |
| 61-70          | 62        | 1.47%   |
| Unknown        | 54        | 1.28%   |
| 141-150        | 44        | 1.04%   |
| 51-60          | 37        | 0.88%   |
| 91-100         | 24        | 0.57%   |
| 131-140        | 13        | 0.31%   |
| 1-40           | 8         | 0.19%   |
| 41-50          | 7         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1277      | 31.25%  |
| 51-100        | 1140      | 27.9%   |
| 101-120       | 763       | 18.67%  |
| 161-240       | 551       | 13.49%  |
| More than 240 | 220       | 5.38%   |
| 1-50          | 81        | 1.98%   |
| Unknown       | 54        | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2866      | 75.66%  |
| 2     | 663       | 17.5%   |
| 0     | 149       | 3.93%   |
| 3     | 95        | 2.51%   |
| 4     | 11        | 0.29%   |
| 5     | 3         | 0.08%   |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2026      | 36.16%  |
| Realtek Semiconductor             | 1971      | 35.18%  |
| MediaTek                          | 342       | 6.1%    |
| Broadcom                          | 308       | 5.5%    |
| Qualcomm Atheros                  | 284       | 5.07%   |
| TP-Link                           | 77        | 1.37%   |
| Broadcom Limited                  | 65        | 1.16%   |
| ASIX Electronics                  | 48        | 0.86%   |
| Qualcomm                          | 40        | 0.71%   |
| Samsung Electronics               | 34        | 0.61%   |
| Ralink Technology                 | 28        | 0.5%    |
| Microsoft                         | 28        | 0.5%    |
| Ralink                            | 25        | 0.45%   |
| DisplayLink                       | 24        | 0.43%   |
| Marvell Technology Group          | 22        | 0.39%   |
| Aquantia                          | 20        | 0.36%   |
| Xiaomi                            | 17        | 0.3%    |
| Sierra Wireless                   | 17        | 0.3%    |
| Lenovo                            | 17        | 0.3%    |
| NetGear                           | 15        | 0.27%   |
| Nvidia                            | 13        | 0.23%   |
| Qualcomm Technologies             | 12        | 0.21%   |
| Google                            | 12        | 0.21%   |
| Dell                              | 11        | 0.2%    |
| OPPO Electronics                  | 10        | 0.18%   |
| Apple                             | 9         | 0.16%   |
| Qualcomm Atheros Communications   | 8         | 0.14%   |
| ASUSTek Computer                  | 8         | 0.14%   |
| D-Link System                     | 7         | 0.12%   |
| D-Link                            | 7         | 0.12%   |
| Mellanox Technologies             | 6         | 0.11%   |
| U-Blox                            | 5         | 0.09%   |
| Motorola PCS                      | 5         | 0.09%   |
| Huawei Technologies               | 5         | 0.09%   |
| Hewlett-Packard                   | 5         | 0.09%   |
| Fibocom                           | 5         | 0.09%   |
| Edimax Technology                 | 5         | 0.09%   |
| QinHeng Electronics               | 4         | 0.07%   |
| ICS Advent                        | 4         | 0.07%   |
| Ericsson Business Mobile Networks | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1202      | 18.25%  |
| Realtek RTL8125 2.5GbE Controller                                      | 235       | 3.57%   |
| Intel Wi-Fi 6 AX200                                                    | 212       | 3.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 160       | 2.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 148       | 2.25%   |
| Intel Wireless 8265 / 8275                                             | 145       | 2.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 141       | 2.14%   |
| Intel Wi-Fi 6 AX201                                                    | 127       | 1.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 121       | 1.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 120       | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 115       | 1.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 92        | 1.4%    |
| Intel Ethernet Controller I225-V                                       | 88        | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 83        | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 80        | 1.21%   |
| Intel I211 Gigabit Network Connection                                  | 75        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 73        | 1.11%   |
| Intel Wireless 7265                                                    | 70        | 1.06%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 64        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 61        | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 60        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 59        | 0.9%    |
| Intel Wireless 8260                                                    | 59        | 0.9%    |
| Intel Meteor Lake PCH CNVi WiFi                                        | 59        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 54        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 53        | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                  | 51        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 51        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 50        | 0.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 48        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 46        | 0.7%    |
| Intel Ethernet Connection I217-LM                                      | 45        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                   | 43        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 39        | 0.59%   |
| Intel Wireless 7260                                                    | 37        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 37        | 0.56%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 35        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                  | 34        | 0.52%   |
| Realtek Killer E2600 GbE Controller                                    | 32        | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 32        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1652      | 51.37%  |
| Realtek Semiconductor                 | 452       | 14.05%  |
| MediaTek                              | 284       | 8.83%   |
| Broadcom                              | 241       | 7.49%   |
| Qualcomm Atheros                      | 234       | 7.28%   |
| TP-Link                               | 69        | 2.15%   |
| Broadcom Limited                      | 58        | 1.8%    |
| Qualcomm                              | 37        | 1.15%   |
| Ralink Technology                     | 28        | 0.87%   |
| Ralink                                | 25        | 0.78%   |
| Microsoft                             | 23        | 0.72%   |
| Sierra Wireless                       | 17        | 0.53%   |
| NetGear                               | 15        | 0.47%   |
| Qualcomm Technologies                 | 12        | 0.37%   |
| Qualcomm Atheros Communications       | 8         | 0.25%   |
| Dell                                  | 8         | 0.25%   |
| ASUSTek Computer                      | 8         | 0.25%   |
| Marvell Technology Group              | 7         | 0.22%   |
| D-Link System                         | 6         | 0.19%   |
| D-Link                                | 6         | 0.19%   |
| Fibocom                               | 5         | 0.16%   |
| Edimax Technology                     | 5         | 0.16%   |
| Wacom                                 | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| Belkin Components                     | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Realtek                               | 1         | 0.03%   |
| Linksys                               | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| Belkin                                | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |
| AirTies Wireless Networks             | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 212       | 6.57%   |
| Intel Wireless 8265 / 8275                                           | 145       | 4.49%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 141       | 4.37%   |
| Intel Wi-Fi 6 AX201                                                  | 127       | 3.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 120       | 3.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 120       | 3.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 99        | 3.07%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 92        | 2.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 83        | 2.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 80        | 2.48%   |
| Intel Wireless 7265                                                  | 70        | 2.17%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 61        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 61        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 59        | 1.83%   |
| Intel Wireless 8260                                                  | 59        | 1.83%   |
| Intel Meteor Lake PCH CNVi WiFi                                      | 59        | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 54        | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 53        | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 51        | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 50        | 1.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 49        | 1.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 48        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 39        | 1.21%   |
| Intel Wireless 7260                                                  | 37        | 1.15%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 35        | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 32        | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 31        | 0.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 30        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 29        | 0.9%    |
| Realtek 802.11ac NIC                                                 | 28        | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 27        | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 27        | 0.84%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 27        | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 27        | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 26        | 0.81%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 26        | 0.81%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 25        | 0.77%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 24        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                        | 24        | 0.74%   |
| Intel Wireless 3165                                                  | 20        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1773      | 55.46%  |
| Intel                                  | 903       | 28.25%  |
| Broadcom                               | 129       | 4.04%   |
| Qualcomm Atheros                       | 68        | 2.13%   |
| MediaTek                               | 55        | 1.72%   |
| ASIX Electronics                       | 48        | 1.5%    |
| DisplayLink                            | 24        | 0.75%   |
| Samsung Electronics                    | 23        | 0.72%   |
| Aquantia                               | 20        | 0.63%   |
| Xiaomi                                 | 17        | 0.53%   |
| Lenovo                                 | 17        | 0.53%   |
| Marvell Technology Group               | 15        | 0.47%   |
| Nvidia                                 | 13        | 0.41%   |
| Google                                 | 11        | 0.34%   |
| OPPO Electronics                       | 10        | 0.31%   |
| Apple                                  | 9         | 0.28%   |
| TP-Link                                | 8         | 0.25%   |
| Broadcom Limited                       | 8         | 0.25%   |
| Mellanox Technologies                  | 6         | 0.19%   |
| Motorola PCS                           | 5         | 0.16%   |
| Huawei Technologies                    | 5         | 0.16%   |
| ICS Advent                             | 4         | 0.13%   |
| Spreadtrum Communications              | 3         | 0.09%   |
| Qualcomm                               | 3         | 0.09%   |
| Microsoft                              | 3         | 0.09%   |
| JMicron Technology                     | 3         | 0.09%   |
| Hewlett-Packard                        | 2         | 0.06%   |
| Dell                                   | 2         | 0.06%   |
| Unknown                                | 2         | 0.06%   |
| VIA Technologies                       | 1         | 0.03%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.03%   |
| Netchip Technology                     | 1         | 0.03%   |
| Linksys                                | 1         | 0.03%   |
| D-Link System                          | 1         | 0.03%   |
| D-Link                                 | 1         | 0.03%   |
| AboCom Systems                         | 1         | 0.03%   |
| 3Com                                   | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1202      | 36.39%  |
| Realtek RTL8125 2.5GbE Controller                                      | 235       | 7.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 160       | 4.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 115       | 3.48%   |
| Intel Ethernet Controller I225-V                                       | 88        | 2.66%   |
| Intel I211 Gigabit Network Connection                                  | 75        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 73        | 2.21%   |
| Intel Ethernet Connection (4) I219-LM                                  | 51        | 1.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 49        | 1.48%   |
| ASIX AX88179 Gigabit Ethernet                                          | 46        | 1.39%   |
| Intel Ethernet Connection I217-LM                                      | 45        | 1.36%   |
| Intel Ethernet Connection (2) I219-V                                   | 43        | 1.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 37        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                  | 34        | 1.03%   |
| Realtek Killer E2600 GbE Controller                                    | 32        | 0.97%   |
| Intel Ethernet Controller I226-V                                       | 31        | 0.94%   |
| Intel Ethernet Connection I219-LM                                      | 30        | 0.91%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 29        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 27        | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                                  | 26        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                   | 25        | 0.76%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 24        | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 23        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                   | 22        | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                                  | 19        | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 17        | 0.51%   |
| Intel Ethernet Connection (13) I219-V                                  | 17        | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                  | 17        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                | 17        | 0.51%   |
| Intel I210 Gigabit Network Connection                                  | 15        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 14        | 0.42%   |
| Intel Ethernet Connection (16) I219-LM                                 | 14        | 0.42%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 13        | 0.39%   |
| Intel Ethernet Connection (16) I219-V                                  | 13        | 0.39%   |
| Intel Ethernet Connection (14) I219-V                                  | 13        | 0.39%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 11        | 0.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 11        | 0.33%   |
| Intel Ethernet Connection (17) I219-V                                  | 11        | 0.33%   |
| Intel Ethernet Connection (13) I219-LM                                 | 11        | 0.33%   |
| Intel 82574L Gigabit Network Connection                                | 11        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3052      | 50.5%   |
| Ethernet | 2937      | 48.59%  |
| Modem    | 44        | 0.73%   |
| Unknown  | 11        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2422      | 62.18%  |
| Ethernet | 1470      | 37.74%  |
| Modem    | 3         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1944      | 51.87%  |
| 1     | 1631      | 43.52%  |
| 3     | 105       | 2.8%    |
| 0     | 44        | 1.17%   |
| 4     | 13        | 0.35%   |
| 5     | 8         | 0.21%   |
| 6     | 2         | 0.05%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2504      | 66.31%  |
| Yes  | 1272      | 33.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1518      | 51.72%  |
| Realtek Semiconductor           | 303       | 10.32%  |
| IMC Networks                    | 183       | 6.24%   |
| Foxconn / Hon Hai               | 155       | 5.28%   |
| Apple                           | 148       | 5.04%   |
| Qualcomm Atheros Communications | 112       | 3.82%   |
| Cambridge Silicon Radio         | 112       | 3.82%   |
| MediaTek                        | 92        | 3.13%   |
| Broadcom                        | 63        | 2.15%   |
| Lite-On Technology              | 60        | 2.04%   |
| TP-Link                         | 37        | 1.26%   |
| ASUSTek Computer                | 37        | 1.26%   |
| USI                             | 23        | 0.78%   |
| Realtek                         | 22        | 0.75%   |
| Dell                            | 11        | 0.37%   |
| Toshiba                         | 8         | 0.27%   |
| Ralink                          | 7         | 0.24%   |
| Actions                         | 7         | 0.24%   |
| Marvell Semiconductor           | 6         | 0.2%    |
| Foxconn International           | 6         | 0.2%    |
| Hewlett-Packard                 | 4         | 0.14%   |
| Unknown                         | 4         | 0.14%   |
| Opticis                         | 3         | 0.1%    |
| Ralink Technology               | 2         | 0.07%   |
| HTC (High Tech Computer)        | 2         | 0.07%   |
| Edimax Technology               | 2         | 0.07%   |
| Dynex                           | 2         | 0.07%   |
| Creative Technology             | 2         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Primax Electronics              | 1         | 0.03%   |
| Alps Electric                   | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 326       | 11.1%   |
| Intel Bluetooth wireless interface                  | 322       | 10.96%  |
| Intel AX211 Bluetooth                               | 258       | 8.78%   |
| Realtek Bluetooth Radio                             | 209       | 7.12%   |
| Intel AX200 Bluetooth                               | 205       | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 169       | 5.75%   |
| Intel AX210 Bluetooth                               | 133       | 4.53%   |
| IMC Networks Wireless_Device                        | 118       | 4.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 112       | 3.81%   |
| MediaTek Wireless_Device                            | 91        | 3.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 85        | 2.89%   |
| Apple Bluetooth Host Controller                     | 85        | 2.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 67        | 2.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 43        | 1.46%   |
| IMC Networks Bluetooth Radio                        | 42        | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 38        | 1.29%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 37        | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 30        | 1.02%   |
| Realtek 802.11ac WLAN Adapter                       | 27        | 0.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 25        | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 0.82%   |
| USI Bluetooth Device                                | 23        | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 0.78%   |
| Realtek Bluetooth Radio                             | 22        | 0.75%   |
| Intel Bluetooth Device                              | 21        | 0.72%   |
| ASUS ASUS USB-BT500                                 | 20        | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 0.65%   |
| Lite-On Wireless_Device                             | 18        | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 18        | 0.61%   |
| Lite-On Bluetooth Device                            | 16        | 0.54%   |
| Realtek Bluetooth 5.3 Radio                         | 13        | 0.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.41%   |
| IMC Networks Bluetooth Device                       | 11        | 0.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.37%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.27%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2491      | 43.66%  |
| AMD                                          | 1318      | 23.1%   |
| Nvidia                                       | 1088      | 19.07%  |
| Logitech                                     | 84        | 1.47%   |
| C-Media Electronics                          | 72        | 1.26%   |
| Focusrite-Novation                           | 40        | 0.7%    |
| ASUSTek Computer                             | 36        | 0.63%   |
| GN Netcom                                    | 33        | 0.58%   |
| JMTek                                        | 27        | 0.47%   |
| Kingston Technology                          | 25        | 0.44%   |
| Realtek Semiconductor                        | 22        | 0.39%   |
| Razer USA                                    | 21        | 0.37%   |
| Creative Technology                          | 21        | 0.37%   |
| Micro Star International                     | 20        | 0.35%   |
| Lenovo                                       | 19        | 0.33%   |
| Creative Labs                                | 19        | 0.33%   |
| SteelSeries ApS                              | 18        | 0.32%   |
| Hewlett-Packard                              | 18        | 0.32%   |
| Generalplus Technology                       | 18        | 0.32%   |
| Texas Instruments                            | 16        | 0.28%   |
| Sony                                         | 15        | 0.26%   |
| Corsair                                      | 14        | 0.25%   |
| Plantronics                                  | 13        | 0.23%   |
| Apple                                        | 12        | 0.21%   |
| Unknown                                      | 11        | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 9         | 0.16%   |
| Samson Technologies                          | 8         | 0.14%   |
| Jieli Technology                             | 8         | 0.14%   |
| Thesycon Systemsoftware & Consulting         | 6         | 0.11%   |
| KTMicro                                      | 6         | 0.11%   |
| Blue Microphones                             | 6         | 0.11%   |
| BEHRINGER International                      | 6         | 0.11%   |
| Trust                                        | 5         | 0.09%   |
| M-Audio                                      | 5         | 0.09%   |
| Audio-Technica                               | 5         | 0.09%   |
| Astro Gaming                                 | 5         | 0.09%   |
| XMOS                                         | 4         | 0.07%   |
| Walmart                                      | 4         | 0.07%   |
| TC Electronic                                | 4         | 0.07%   |
| RODE Microphones                             | 4         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 689       | 9.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 298       | 4.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 295       | 4.28%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 294       | 4.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 247       | 3.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 172       | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 167       | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 159       | 2.31%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 155       | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 139       | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 134       | 1.94%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 122       | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 114       | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 95        | 1.38%   |
| Intel Raptor Lake High Definition Audio Controller                         | 94        | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 85        | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 83        | 1.2%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 80        | 1.16%   |
| Nvidia AD107 High Definition Audio Controller                              | 79        | 1.15%   |
| Intel Comet Lake PCH cAVS                                                  | 78        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 77        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 74        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 74        | 1.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 73        | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 72        | 1.04%   |
| Nvidia GA107 High Definition Audio Controller                              | 71        | 1.03%   |
| Intel Alder Lake-S HD Audio Controller                                     | 70        | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 70        | 1.02%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 69        | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 63        | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 63        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 61        | 0.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 60        | 0.87%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 0.87%   |
| Intel 8 Series HD Audio Controller                                         | 59        | 0.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 59        | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 58        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 53        | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 43        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 353       | 23.77%  |
| SK hynix            | 259       | 17.44%  |
| Micron Technology   | 214       | 14.41%  |
| Kingston            | 124       | 8.35%   |
| Crucial             | 90        | 6.06%   |
| Corsair             | 82        | 5.52%   |
| G.Skill             | 74        | 4.98%   |
| Unknown             | 59        | 3.97%   |
| Unknown             | 37        | 2.49%   |
| A-DATA Technology   | 36        | 2.42%   |
| Team                | 17        | 1.14%   |
| Ramaxel Technology  | 16        | 1.08%   |
| Elpida              | 12        | 0.81%   |
| Smart               | 9         | 0.61%   |
| Nanya Technology    | 9         | 0.61%   |
| Patriot             | 7         | 0.47%   |
| Apacer              | 7         | 0.47%   |
| Lexar               | 5         | 0.34%   |
| AMD                 | 5         | 0.34%   |
| Unknown (ABCD)      | 3         | 0.2%    |
| Transcend           | 3         | 0.2%    |
| Timetec             | 3         | 0.2%    |
| Kllisre             | 3         | 0.2%    |
| Hikvision           | 3         | 0.2%    |
| ChangXin Memory     | 3         | 0.2%    |
| Avant               | 3         | 0.2%    |
| Unknown (0x0B45)    | 2         | 0.13%   |
| Teikon              | 2         | 0.13%   |
| Smart Modular       | 2         | 0.13%   |
| Silicon Power       | 2         | 0.13%   |
| Shenzhen SCY        | 2         | 0.13%   |
| PNY                 | 2         | 0.13%   |
| GOODRAM             | 2         | 0.13%   |
| Goldkey             | 2         | 0.13%   |
| Wilk                | 1         | 0.07%   |
| Unknown (F785)      | 1         | 0.07%   |
| Unknown (89F7)      | 1         | 0.07%   |
| Unknown (0x9801)    | 1         | 0.07%   |
| Unknown (0x8000)    | 1         | 0.07%   |
| Unknown (0x1636)    | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 37        | 2.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 1.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 1.09%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 16        | 1.03%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 11        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.51%   |
| SK hynix RAM H58G66BK7BX067 4GB Row Of Chips LPDDR5 8533MT/s     | 8         | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.51%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 8         | 0.51%   |
| Samsung RAM K3KL8L80CM-MGCT 2GB Row Of Chips LPDDR5 7500MT/s     | 8         | 0.51%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 7         | 0.45%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 7         | 0.45%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 6         | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.38%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 6         | 0.38%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 6         | 0.38%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.38%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 6         | 0.38%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.38%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 6         | 0.38%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 0.38%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 6         | 0.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.38%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 5         | 0.32%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.32%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 5         | 0.32%   |
| Samsung RAM K3KL9L90CM-MGCT 8GB SODIMM LPDDR5 7500MT/s           | 5         | 0.32%   |
| Micron RAM MT62F4G32D8DV-026 WT 16GB SODIMM LPDDR5 7500MT/s      | 5         | 0.32%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 5         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 649       | 49.5%   |
| DDR3    | 218       | 16.63%  |
| DDR5    | 161       | 12.28%  |
| LPDDR5  | 139       | 10.6%   |
| LPDDR4  | 68        | 5.19%   |
| LPDDR3  | 36        | 2.75%   |
| DDR2    | 16        | 1.22%   |
| Unknown | 16        | 1.22%   |
| SDRAM   | 7         | 0.53%   |
| DDR     | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 720       | 54.79%  |
| DIMM            | 352       | 26.79%  |
| Row Of Chips    | 222       | 16.89%  |
| Unknown         | 11        | 0.84%   |
| Chip            | 7         | 0.53%   |
| Proprietary Car | 1         | 0.08%   |
| DIP             | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 582       | 41.57%  |
| 16384  | 332       | 23.71%  |
| 4096   | 257       | 18.36%  |
| 32768  | 115       | 8.21%   |
| 2048   | 89        | 6.36%   |
| 1024   | 13        | 0.93%   |
| 49152  | 5         | 0.36%   |
| 3072   | 4         | 0.29%   |
| 131072 | 1         | 0.07%   |
| 24576  | 1         | 0.07%   |
| 12288  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 312       | 22.43%  |
| 1600  | 164       | 11.79%  |
| 2667  | 155       | 11.14%  |
| 6400  | 72        | 5.18%   |
| 5600  | 69        | 4.96%   |
| 2400  | 69        | 4.96%   |
| 4800  | 58        | 4.17%   |
| 2133  | 56        | 4.03%   |
| 3600  | 48        | 3.45%   |
| 4267  | 38        | 2.73%   |
| 7500  | 37        | 2.66%   |
| 1333  | 37        | 2.66%   |
| 6000  | 25        | 1.8%    |
| 3733  | 24        | 1.73%   |
| 1867  | 23        | 1.65%   |
| 7467  | 16        | 1.15%   |
| 3800  | 12        | 0.86%   |
| 2933  | 11        | 0.79%   |
| 8533  | 10        | 0.72%   |
| 4000  | 10        | 0.72%   |
| 3266  | 10        | 0.72%   |
| 1334  | 10        | 0.72%   |
| 800   | 9         | 0.65%   |
| 667   | 9         | 0.65%   |
| 4266  | 8         | 0.58%   |
| 3000  | 7         | 0.5%    |
| 2666  | 7         | 0.5%    |
| 3400  | 6         | 0.43%   |
| 3534  | 5         | 0.36%   |
| 1067  | 5         | 0.36%   |
| 1066  | 5         | 0.36%   |
| 8400  | 4         | 0.29%   |
| 400   | 4         | 0.29%   |
| 8600  | 3         | 0.22%   |
| 5800  | 3         | 0.22%   |
| 5500  | 3         | 0.22%   |
| 3866  | 3         | 0.22%   |
| 3666  | 3         | 0.22%   |
| 3466  | 3         | 0.22%   |
| 3333  | 3         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 17        | 33.33%  |
| Brother Industries            | 11        | 21.57%  |
| Seiko Epson                   | 7         | 13.73%  |
| Samsung Electronics           | 3         | 5.88%   |
| Dymo-CoStar                   | 3         | 5.88%   |
| Zhuhai Poskey Technology      | 2         | 3.92%   |
| Canon                         | 2         | 3.92%   |
| Samsung Info. Systems America | 1         | 1.96%   |
| Prolific Technology           | 1         | 1.96%   |
| Printer                       | 1         | 1.96%   |
| Pantum                        | 1         | 1.96%   |
| Kyocera                       | 1         | 1.96%   |
| iDPRT                         | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Zhuhai Poskey DT426B                         | 2         | 3.85%   |
| HP Smart Tank 510 series                     | 2         | 3.85%   |
| HP Ink Tank Wireless 410 series              | 2         | 3.85%   |
| Dymo-CoStar LabelWriter 450                  | 2         | 3.85%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.92%   |
| Seiko Epson Printer                          | 1         | 1.92%   |
| Seiko Epson M1120 Series                     | 1         | 1.92%   |
| Seiko Epson L3150 Series                     | 1         | 1.92%   |
| Seiko Epson L3110 Series                     | 1         | 1.92%   |
| Seiko Epson ET-4800 Series                   | 1         | 1.92%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.92%   |
| Samsung Info. Systems America Docuprint P8ex | 1         | 1.92%   |
| Samsung SCX-4623 Series                      | 1         | 1.92%   |
| Samsung SCX-3400 Series                      | 1         | 1.92%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.92%   |
| Prolific PL2305 Parallel Port                | 1         | 1.92%   |
| Printer Printer                              | 1         | 1.92%   |
| Pantum M6500W-series                         | 1         | 1.92%   |
| Kyocera FS-1040                              | 1         | 1.92%   |
| iDPRT SP410                                  | 1         | 1.92%   |
| HP Smart Tank 7600 series                    | 1         | 1.92%   |
| HP OfficeJet Pro 6970                        | 1         | 1.92%   |
| HP LaserJet Professional P 1102w             | 1         | 1.92%   |
| HP LaserJet Pro M148-M149                    | 1         | 1.92%   |
| HP LaserJet P1006                            | 1         | 1.92%   |
| HP LaserJet 3050                             | 1         | 1.92%   |
| HP LaserJet 1020                             | 1         | 1.92%   |
| HP Deskjet F2280 series                      | 1         | 1.92%   |
| HP DeskJet 3630 series                       | 1         | 1.92%   |
| HP DeskJet 2620 All-in-One Printer           | 1         | 1.92%   |
| HP Deskjet 2050 J510                         | 1         | 1.92%   |
| HP Deskjet 1510                              | 1         | 1.92%   |
| HP Deskjet 1000 J110 series                  | 1         | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 1         | 1.92%   |
| Canon TS3300 series                          | 1         | 1.92%   |
| Canon TS300 series                           | 1         | 1.92%   |
| Brother MFC-L2740DW                          | 1         | 1.92%   |
| Brother MFC-L2710DW series                   | 1         | 1.92%   |
| Brother MFC-J5945DW                          | 1         | 1.92%   |
| Brother MFC-J1170DW                          | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 58.33%  |
| Seiko Epson     | 3         | 25%     |
| Hewlett-Packard | 2         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                       | 3         | 25%     |
| Canon CanoScan 4200F                          | 2         | 16.67%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 8.33%   |
| Seiko Epson GT-6600U [Perfection 610]         | 1         | 8.33%   |
| Seiko Epson GT-1500 [GT-D1000]                | 1         | 8.33%   |
| HP ScanJet 82x0C                              | 1         | 8.33%   |
| HP ScanJet 4070 PhotoSmart                    | 1         | 8.33%   |
| Canon CanoScan LiDE 60                        | 1         | 8.33%   |
| Canon CanoScan LiDE 120                       | 1         | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 440       | 18.05%  |
| IMC Networks                           | 229       | 9.39%   |
| Realtek Semiconductor                  | 169       | 6.93%   |
| Logitech                               | 163       | 6.69%   |
| Microdia                               | 160       | 6.56%   |
| Quanta                                 | 152       | 6.23%   |
| Bison Electronics                      | 148       | 6.07%   |
| Sunplus Innovation Technology          | 118       | 4.84%   |
| Luxvisions Innotech Limited            | 116       | 4.76%   |
| Apple                                  | 107       | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 78        | 3.2%    |
| Syntek                                 | 71        | 2.91%   |
| Sonix Technology                       | 63        | 2.58%   |
| Lite-On Technology                     | 52        | 2.13%   |
| ShineTech                              | 46        | 1.89%   |
| Samsung Electronics                    | 25        | 1.03%   |
| Acer                                   | 25        | 1.03%   |
| SunplusIT                              | 23        | 0.94%   |
| Suyin                                  | 22        | 0.9%    |
| Alcor Micro                            | 17        | 0.7%    |
| Microsoft                              | 16        | 0.66%   |
| kingcome                               | 13        | 0.53%   |
| Silicon Motion                         | 11        | 0.45%   |
| MacroSilicon                           | 8         | 0.33%   |
| 2M UVC CAMERA                          | 8         | 0.33%   |
| Razer USA                              | 6         | 0.25%   |
| icSpring                               | 6         | 0.25%   |
| Generalplus Technology                 | 6         | 0.25%   |
| eMeet                                  | 6         | 0.25%   |
| Anker PowerConf C200                   | 6         | 0.25%   |
| ARC International                      | 5         | 0.21%   |
| Trust                                  | 4         | 0.16%   |
| ShineOptics                            | 4         | 0.16%   |
| Lenovo                                 | 4         | 0.16%   |
| GEMBIRD                                | 4         | 0.16%   |
| AVerMedia Technologies                 | 4         | 0.16%   |
| Unknown                                | 4         | 0.16%   |
| Z-Star Microelectronics                | 3         | 0.12%   |
| webcamvendor                           | 3         | 0.12%   |
| Tripath Technology                     | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 142       | 5.74%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 92        | 3.72%   |
| Realtek Integrated_Webcam_HD                         | 72        | 2.91%   |
| Microdia Integrated_Webcam_HD                        | 72        | 2.91%   |
| IMC Networks Integrated Camera                       | 69        | 2.79%   |
| Syntek Integrated Camera                             | 61        | 2.46%   |
| Bison Integrated Camera                              | 57        | 2.3%    |
| Logitech HD Pro Webcam C920                          | 44        | 1.78%   |
| Apple FaceTime HD Camera (Built-in)                  | 40        | 1.62%   |
| Sonix USB2.0 HD UVC WebCam                           | 39        | 1.58%   |
| Sunplus Integrated_Webcam_HD                         | 32        | 1.29%   |
| Luxvisions Innotech Limited Integrated Camera        | 32        | 1.29%   |
| Chicony HP HD Camera                                 | 30        | 1.21%   |
| Shinetech USB2.0 FHD UVC WebCam                      | 28        | 1.13%   |
| Apple FaceTime HD Camera                             | 27        | 1.09%   |
| Lite-On Integrated Camera                            | 25        | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)              | 24        | 0.97%   |
| Quanta HP HD Camera                                  | 24        | 0.97%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 24        | 0.97%   |
| Chicony HD WebCam                                    | 24        | 0.97%   |
| Quanta ACER HD User Facing                           | 23        | 0.93%   |
| Logitech Webcam C270                                 | 22        | 0.89%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 22        | 0.89%   |
| Chicony Integrated Camera (1280x720@30)              | 20        | 0.81%   |
| Apple Built-in iSight                                | 20        | 0.81%   |
| Quanta HP Wide Vision HD Camera                      | 18        | 0.73%   |
| Chicony Integrated IR Camera                         | 18        | 0.73%   |
| Logitech C922 Pro Stream Webcam                      | 17        | 0.69%   |
| Bison HD Webcam                                      | 17        | 0.69%   |
| Sonix USB2.0 FHD UVC WebCam                          | 16        | 0.65%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 15        | 0.61%   |
| Chicony HD User Facing                               | 15        | 0.61%   |
| Chicony ACER HD User Facing                          | 15        | 0.61%   |
| Quanta HD User Facing                                | 14        | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 14        | 0.57%   |
| ShineTech USB2.0 HD UVC WebCam                       | 13        | 0.53%   |
| Microdia Webcam Vitade AF                            | 13        | 0.53%   |
| Luxvisions Innotech Limited HP HD Camera             | 13        | 0.53%   |
| Chicony HP Wide Vision HD Camera                     | 13        | 0.53%   |
| Sunplus DICOTA 4K                                    | 12        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 174       | 40.28%  |
| Validity Sensors                   | 106       | 24.54%  |
| Shenzhen Goodix Technology         | 76        | 17.59%  |
| Elan Microelectronics              | 29        | 6.71%   |
| Realtek USB2.0 Finger Print Bridge | 14        | 3.24%   |
| Upek                               | 13        | 3.01%   |
| LighTuning Technology              | 6         | 1.39%   |
| AuthenTec                          | 5         | 1.16%   |
| FocalTech                          | 2         | 0.46%   |
| Focal-systems.Corp                 | 2         | 0.46%   |
| DigitalPersona                     | 2         | 0.46%   |
| Samsung Electronics                | 1         | 0.23%   |
| Next Biometrics                    | 1         | 0.23%   |
| GDMicroelectronics                 | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 12.27%  |
| Shenzhen Goodix  Fingerprint Device                                        | 46        | 10.65%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 31        | 7.18%   |
| Synaptics UWP WBDI Device                                                  | 22        | 5.09%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 4.63%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4.17%   |
| Elan ELAN:ARM-M4                                                           | 17        | 3.94%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 14        | 3.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 3.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 3.01%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 3.01%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 2.78%   |
| Validity Sensors VFS491                                                    | 11        | 2.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.55%   |
| Synaptics Prometheus Fingerprint Reader                                    | 10        | 2.31%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 2.08%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 1.62%   |
| Synaptics WBDI                                                             | 7         | 1.62%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.16%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.16%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.16%   |
| Synaptics  WBDI                                                            | 5         | 1.16%   |
| Synaptics UWP WBDI                                                         | 4         | 0.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.46%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.46%   |
| Synaptics TouchPad                                                         | 2         | 0.46%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.46%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.46%   |
| FocalTech FocalTech Fingerprint Device                                     | 2         | 0.46%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 0.46%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.46%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.46%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 91        | 53.85%  |
| Alcor Micro               | 48        | 28.4%   |
| Upek                      | 10        | 5.92%   |
| O2 Micro                  | 3         | 1.78%   |
| Lenovo                    | 3         | 1.78%   |
| Advanced Card Systems     | 3         | 1.78%   |
| Yubico.com                | 2         | 1.18%   |
| SCM Microsystems          | 1         | 0.59%   |
| Reiner SCT Kartensysteme  | 1         | 0.59%   |
| Realtek Semiconductor     | 1         | 0.59%   |
| OmniKey                   | 1         | 0.59%   |
| Gemalto (was Gemplus)     | 1         | 0.59%   |
| Feitian Technologies      | 1         | 0.59%   |
| Clay Logic                | 1         | 0.59%   |
| Aladdin Knowledge Systems | 1         | 0.59%   |
| Aktiv                     | 1         | 0.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 48        | 28.4%   |
| Broadcom 58200                                                               | 45        | 26.63%  |
| Broadcom 5880                                                                | 23        | 13.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 8.28%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 5.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 1.78%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 1.78%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.18%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.59%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.59%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.59%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.59%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.59%   |
| Feitian Technologies ePass2003                                               | 1         | 0.59%   |
| Clay Logic CanoKey Pigeon                                                    | 1         | 0.59%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.59%   |
| Aktiv Rutoken lite                                                           | 1         | 0.59%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.59%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.59%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2496      | 65.94%  |
| 1     | 1068      | 28.22%  |
| 2     | 197       | 5.2%    |
| 3     | 21        | 0.55%   |
| 7     | 2         | 0.05%   |
| 4     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 499       | 33.6%   |
| Fingerprint reader       | 428       | 28.82%  |
| Multimedia controller    | 239       | 16.09%  |
| Net/wireless             | 142       | 9.56%   |
| Chipcard                 | 40        | 2.69%   |
| Unassigned class         | 25        | 1.68%   |
| Camera                   | 19        | 1.28%   |
| Sound                    | 17        | 1.14%   |
| Communication controller | 16        | 1.08%   |
| Net/ethernet             | 15        | 1.01%   |
| Bluetooth                | 14        | 0.94%   |
| Card reader              | 9         | 0.61%   |
| Storage                  | 8         | 0.54%   |
| Network                  | 5         | 0.34%   |
| Storage/raid             | 3         | 0.2%    |
| Modem                    | 3         | 0.2%    |
| Tv card                  | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

