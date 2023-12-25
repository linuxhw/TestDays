Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 5482

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| PC Special... | GK7NP5R                     | Notebook    | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8decde512f](https://linux-hardware.org/?probe=8decde512f) | Dec 23, 2023 |
| System76      | Serval WS                   | Notebook    | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | Notebook    | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [de502eec48](https://linux-hardware.org/?probe=de502eec48) | Dec 22, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [ec6847b7f2](https://linux-hardware.org/?probe=ec6847b7f2) | Dec 22, 2023 |
| Gigabyte      | H610M S2H                   | Desktop     | [6c554a9668](https://linux-hardware.org/?probe=6c554a9668) | Dec 22, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [bf0861748d](https://linux-hardware.org/?probe=bf0861748d) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1b8100314e](https://linux-hardware.org/?probe=1b8100314e) | Dec 21, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ecefa48588](https://linux-hardware.org/?probe=ecefa48588) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | Notebook    | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [67098aebca](https://linux-hardware.org/?probe=67098aebca) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [d2ed93003e](https://linux-hardware.org/?probe=d2ed93003e) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | Notebook    | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | Notebook    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [86b686b3cf](https://linux-hardware.org/?probe=86b686b3cf) | Dec 19, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [047feb8e76](https://linux-hardware.org/?probe=047feb8e76) | Dec 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [9ec714a02b](https://linux-hardware.org/?probe=9ec714a02b) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [29169b6700](https://linux-hardware.org/?probe=29169b6700) | Dec 19, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1375b869d1](https://linux-hardware.org/?probe=1375b869d1) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [0759f6c04f](https://linux-hardware.org/?probe=0759f6c04f) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [939c3a4be6](https://linux-hardware.org/?probe=939c3a4be6) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [8efe53adcb](https://linux-hardware.org/?probe=8efe53adcb) | Dec 18, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f051e1ba58](https://linux-hardware.org/?probe=f051e1ba58) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [85358f7505](https://linux-hardware.org/?probe=85358f7505) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [2d78f7257c](https://linux-hardware.org/?probe=2d78f7257c) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | ProBook 4535s               | Notebook    | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3a10e23529](https://linux-hardware.org/?probe=3a10e23529) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [801f62b573](https://linux-hardware.org/?probe=801f62b573) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d16bd87505](https://linux-hardware.org/?probe=d16bd87505) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [7f32922e8f](https://linux-hardware.org/?probe=7f32922e8f) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [b9029b0475](https://linux-hardware.org/?probe=b9029b0475) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0baa198f9f](https://linux-hardware.org/?probe=0baa198f9f) | Dec 17, 2023 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | Desktop     | [47bc0a39bf](https://linux-hardware.org/?probe=47bc0a39bf) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d227968843](https://linux-hardware.org/?probe=d227968843) | Dec 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95deb85c40](https://linux-hardware.org/?probe=95deb85c40) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [4f6031c3b2](https://linux-hardware.org/?probe=4f6031c3b2) | Dec 16, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [51a1a58859](https://linux-hardware.org/?probe=51a1a58859) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [976a5e3ec2](https://linux-hardware.org/?probe=976a5e3ec2) | Dec 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [7da400b028](https://linux-hardware.org/?probe=7da400b028) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [fb32a1a82e](https://linux-hardware.org/?probe=fb32a1a82e) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [17fcc16842](https://linux-hardware.org/?probe=17fcc16842) | Dec 14, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9d6455339e](https://linux-hardware.org/?probe=9d6455339e) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3280eaaea1](https://linux-hardware.org/?probe=3280eaaea1) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b7bef0ec08](https://linux-hardware.org/?probe=b7bef0ec08) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [c132a249e4](https://linux-hardware.org/?probe=c132a249e4) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [913708c3f0](https://linux-hardware.org/?probe=913708c3f0) | Dec 13, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3f2ed65cf0](https://linux-hardware.org/?probe=3f2ed65cf0) | Dec 13, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | Notebook    | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [25a03e3488](https://linux-hardware.org/?probe=25a03e3488) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e33caa2659](https://linux-hardware.org/?probe=e33caa2659) | Dec 12, 2023 |
| AZW           | SER                         | Mini pc     | [35001d9cec](https://linux-hardware.org/?probe=35001d9cec) | Dec 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ca9ceaf4a0](https://linux-hardware.org/?probe=ca9ceaf4a0) | Dec 11, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [076e19b0aa](https://linux-hardware.org/?probe=076e19b0aa) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [efba53721c](https://linux-hardware.org/?probe=efba53721c) | Dec 11, 2023 |
| MSI           | H610M BOMBER DDR4           | Desktop     | [7ea9e34c4c](https://linux-hardware.org/?probe=7ea9e34c4c) | Dec 11, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [7b2a48d751](https://linux-hardware.org/?probe=7b2a48d751) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [90fce6c777](https://linux-hardware.org/?probe=90fce6c777) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [6c83c2bec6](https://linux-hardware.org/?probe=6c83c2bec6) | Dec 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| System76      | Lemur Pro                   | Notebook    | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [0c0de57a07](https://linux-hardware.org/?probe=0c0de57a07) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [ad9ec5bc5b](https://linux-hardware.org/?probe=ad9ec5bc5b) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| HP            | 2AF7                        | Desktop     | [e7a6fd7a82](https://linux-hardware.org/?probe=e7a6fd7a82) | Dec 10, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [3e42bedcd3](https://linux-hardware.org/?probe=3e42bedcd3) | Dec 10, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [ef47cf6d30](https://linux-hardware.org/?probe=ef47cf6d30) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| Razer         | Blade                       | Notebook    | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| Gigabyte      | MU92-TU0-00 01010101        | Server      | [fa219aabb0](https://linux-hardware.org/?probe=fa219aabb0) | Dec 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [f499be5e26](https://linux-hardware.org/?probe=f499be5e26) | Dec 09, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [e7d15edec4](https://linux-hardware.org/?probe=e7d15edec4) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [981334c448](https://linux-hardware.org/?probe=981334c448) | Dec 08, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [944218c6ec](https://linux-hardware.org/?probe=944218c6ec) | Dec 08, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [8c7f7f9b91](https://linux-hardware.org/?probe=8c7f7f9b91) | Dec 08, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [2499101d89](https://linux-hardware.org/?probe=2499101d89) | Dec 08, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [182fbc1464](https://linux-hardware.org/?probe=182fbc1464) | Dec 08, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [68bd979ae6](https://linux-hardware.org/?probe=68bd979ae6) | Dec 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | Notebook    | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [895b027832](https://linux-hardware.org/?probe=895b027832) | Dec 07, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [18c7fcf897](https://linux-hardware.org/?probe=18c7fcf897) | Dec 06, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [49e317cfc8](https://linux-hardware.org/?probe=49e317cfc8) | Dec 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeb3db62db](https://linux-hardware.org/?probe=eeb3db62db) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5160cc41b9](https://linux-hardware.org/?probe=5160cc41b9) | Dec 06, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [4ae43e0af1](https://linux-hardware.org/?probe=4ae43e0af1) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [973530edc6](https://linux-hardware.org/?probe=973530edc6) | Dec 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [67d1badc93](https://linux-hardware.org/?probe=67d1badc93) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [1f66aaf874](https://linux-hardware.org/?probe=1f66aaf874) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [474cae9549](https://linux-hardware.org/?probe=474cae9549) | Dec 05, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [48a8d668d9](https://linux-hardware.org/?probe=48a8d668d9) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b55a2ed6be](https://linux-hardware.org/?probe=b55a2ed6be) | Dec 03, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [7e41d52591](https://linux-hardware.org/?probe=7e41d52591) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c5bdb91907](https://linux-hardware.org/?probe=c5bdb91907) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [98567fb8e0](https://linux-hardware.org/?probe=98567fb8e0) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [00da9d31bd](https://linux-hardware.org/?probe=00da9d31bd) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [0714d912db](https://linux-hardware.org/?probe=0714d912db) | Dec 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [7488b95d21](https://linux-hardware.org/?probe=7488b95d21) | Dec 02, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [31ac2917e3](https://linux-hardware.org/?probe=31ac2917e3) | Dec 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [eb3b0a6afb](https://linux-hardware.org/?probe=eb3b0a6afb) | Dec 01, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [53bc6eba90](https://linux-hardware.org/?probe=53bc6eba90) | Dec 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | Notebook    | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [11e0af1d39](https://linux-hardware.org/?probe=11e0af1d39) | Nov 30, 2023 |
| HP            | 8299                        | Desktop     | [7d01726c17](https://linux-hardware.org/?probe=7d01726c17) | Nov 30, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e43b293d0e](https://linux-hardware.org/?probe=e43b293d0e) | Nov 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [43e0c71549](https://linux-hardware.org/?probe=43e0c71549) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [707797695c](https://linux-hardware.org/?probe=707797695c) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a05b28f5b1](https://linux-hardware.org/?probe=a05b28f5b1) | Nov 29, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| HP            | 0B40h                       | Desktop     | [9875f70785](https://linux-hardware.org/?probe=9875f70785) | Nov 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [977a25b18b](https://linux-hardware.org/?probe=977a25b18b) | Nov 29, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [07dd4aaf53](https://linux-hardware.org/?probe=07dd4aaf53) | Nov 29, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [a193c9a207](https://linux-hardware.org/?probe=a193c9a207) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| Dell          | Precision 3550              | Notebook    | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f502294656](https://linux-hardware.org/?probe=f502294656) | Nov 28, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Dell          | Precision M4700             | Notebook    | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [d6f36dff1d](https://linux-hardware.org/?probe=d6f36dff1d) | Nov 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [4fd4ea2869](https://linux-hardware.org/?probe=4fd4ea2869) | Nov 26, 2023 |
| Dell          | 0RY206                      | Desktop     | [7115b05660](https://linux-hardware.org/?probe=7115b05660) | Nov 25, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| MSI           | Z87-S02                     | Desktop     | [2d40c55867](https://linux-hardware.org/?probe=2d40c55867) | Nov 25, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [c6955988fb](https://linux-hardware.org/?probe=c6955988fb) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ab26a80bc5](https://linux-hardware.org/?probe=ab26a80bc5) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [1065af244c](https://linux-hardware.org/?probe=1065af244c) | Nov 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [904f3a4c07](https://linux-hardware.org/?probe=904f3a4c07) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [98b666cd95](https://linux-hardware.org/?probe=98b666cd95) | Nov 24, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [9e25aa3d8f](https://linux-hardware.org/?probe=9e25aa3d8f) | Nov 24, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d12afced10](https://linux-hardware.org/?probe=d12afced10) | Nov 24, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3730101bfb](https://linux-hardware.org/?probe=3730101bfb) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [c3d0a3a34c](https://linux-hardware.org/?probe=c3d0a3a34c) | Nov 24, 2023 |
| HP            | 85A2                        | All in one  | [80b79f2bed](https://linux-hardware.org/?probe=80b79f2bed) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| HP            | 2AF7                        | Desktop     | [5594c88f44](https://linux-hardware.org/?probe=5594c88f44) | Nov 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [bc09939521](https://linux-hardware.org/?probe=bc09939521) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b6e4999e4f](https://linux-hardware.org/?probe=b6e4999e4f) | Nov 22, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [b8a0ad5987](https://linux-hardware.org/?probe=b8a0ad5987) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [21257dcbad](https://linux-hardware.org/?probe=21257dcbad) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [b69760e673](https://linux-hardware.org/?probe=b69760e673) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [00c164e154](https://linux-hardware.org/?probe=00c164e154) | Nov 21, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [be7c395cc7](https://linux-hardware.org/?probe=be7c395cc7) | Nov 21, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [96172d652b](https://linux-hardware.org/?probe=96172d652b) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [a166dbb3cf](https://linux-hardware.org/?probe=a166dbb3cf) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [ece8c390b1](https://linux-hardware.org/?probe=ece8c390b1) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [55dac497f4](https://linux-hardware.org/?probe=55dac497f4) | Nov 20, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | Notebook    | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f58ea2a820](https://linux-hardware.org/?probe=f58ea2a820) | Nov 20, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| HP            | 8054                        | Desktop     | [2ccc2c67f2](https://linux-hardware.org/?probe=2ccc2c67f2) | Nov 20, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [56cd0716d9](https://linux-hardware.org/?probe=56cd0716d9) | Nov 19, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [792754cbe2](https://linux-hardware.org/?probe=792754cbe2) | Nov 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [354af02ac9](https://linux-hardware.org/?probe=354af02ac9) | Nov 19, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [75065dda24](https://linux-hardware.org/?probe=75065dda24) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | Notebook    | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [fca337aea5](https://linux-hardware.org/?probe=fca337aea5) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [7c45a9b620](https://linux-hardware.org/?probe=7c45a9b620) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ae962a2552](https://linux-hardware.org/?probe=ae962a2552) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [0619c3b255](https://linux-hardware.org/?probe=0619c3b255) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d402c27e5c](https://linux-hardware.org/?probe=d402c27e5c) | Nov 17, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| HP            | 83E8                        | Desktop     | [393ca40cd9](https://linux-hardware.org/?probe=393ca40cd9) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [9b4ca9cc96](https://linux-hardware.org/?probe=9b4ca9cc96) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | Notebook    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [e4ac0f919f](https://linux-hardware.org/?probe=e4ac0f919f) | Nov 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ProBook 4540s               | Notebook    | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| Dell          | XPS 9320                    | Notebook    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6a6b0096bb](https://linux-hardware.org/?probe=6a6b0096bb) | Nov 15, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [c3c068a998](https://linux-hardware.org/?probe=c3c068a998) | Nov 14, 2023 |
| Acer          | Aspire V3-471G              | Notebook    | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [7b17ba0f7f](https://linux-hardware.org/?probe=7b17ba0f7f) | Nov 14, 2023 |
| HP            | 2AF7                        | Desktop     | [dd8d87a916](https://linux-hardware.org/?probe=dd8d87a916) | Nov 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [73ef67d393](https://linux-hardware.org/?probe=73ef67d393) | Nov 13, 2023 |
| System76      | Adder WS                    | Notebook    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| ASUSTek       | X55U                        | Notebook    | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | Notebook    | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| AMI           | Intel                       | Desktop     | [7c96434a18](https://linux-hardware.org/?probe=7c96434a18) | Nov 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cac951f39c](https://linux-hardware.org/?probe=cac951f39c) | Nov 13, 2023 |
| System76      | Lemur Pro                   | Notebook    | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [a6083e5df9](https://linux-hardware.org/?probe=a6083e5df9) | Nov 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [4162e8afa8](https://linux-hardware.org/?probe=4162e8afa8) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f3b49f17b1](https://linux-hardware.org/?probe=f3b49f17b1) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [61994e2e2e](https://linux-hardware.org/?probe=61994e2e2e) | Nov 12, 2023 |
| Google        | Edgar                       | Notebook    | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [0e6185c9db](https://linux-hardware.org/?probe=0e6185c9db) | Nov 11, 2023 |
| Google        | Edgar                       | Notebook    | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [1946d2a10c](https://linux-hardware.org/?probe=1946d2a10c) | Nov 11, 2023 |
| HP            | G42                         | Notebook    | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [75735f5b69](https://linux-hardware.org/?probe=75735f5b69) | Nov 11, 2023 |
| Dell          | Latitude E5420              | Notebook    | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [f22d74d5eb](https://linux-hardware.org/?probe=f22d74d5eb) | Nov 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [080772c4d8](https://linux-hardware.org/?probe=080772c4d8) | Nov 11, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [9c77400bbf](https://linux-hardware.org/?probe=9c77400bbf) | Nov 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ecc5d08bd8](https://linux-hardware.org/?probe=ecc5d08bd8) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [93d7b2bcdc](https://linux-hardware.org/?probe=93d7b2bcdc) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1473413ce2](https://linux-hardware.org/?probe=1473413ce2) | Nov 09, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [03b4295585](https://linux-hardware.org/?probe=03b4295585) | Nov 09, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| Dell          | 015YTG A02                  | All in one  | [d151271204](https://linux-hardware.org/?probe=d151271204) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [c048c3b791](https://linux-hardware.org/?probe=c048c3b791) | Nov 09, 2023 |
| HP            | G42                         | Notebook    | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Precision 5520              | Notebook    | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Dell          | Latitude E7270              | Notebook    | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [d2ce7f8ca6](https://linux-hardware.org/?probe=d2ce7f8ca6) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [e4f3bd771d](https://linux-hardware.org/?probe=e4f3bd771d) | Nov 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [8ca7abbf03](https://linux-hardware.org/?probe=8ca7abbf03) | Nov 08, 2023 |
| Acer          | Aspire A517-51              | Notebook    | [9b0700130f](https://linux-hardware.org/?probe=9b0700130f) | Nov 08, 2023 |
| System76      | Lemur Pro                   | Notebook    | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [a675ce6c08](https://linux-hardware.org/?probe=a675ce6c08) | Nov 07, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [4075eda03c](https://linux-hardware.org/?probe=4075eda03c) | Nov 07, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c2ae66ef2b](https://linux-hardware.org/?probe=c2ae66ef2b) | Nov 06, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [7f057ebed2](https://linux-hardware.org/?probe=7f057ebed2) | Nov 06, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [2716ef5f71](https://linux-hardware.org/?probe=2716ef5f71) | Nov 06, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [697278adb7](https://linux-hardware.org/?probe=697278adb7) | Nov 06, 2023 |
| HP            | 89E9 0100                   | All in one  | [5e98ad51b6](https://linux-hardware.org/?probe=5e98ad51b6) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | Notebook    | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [6f11758faa](https://linux-hardware.org/?probe=6f11758faa) | Nov 04, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | Notebook    | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [f27bded4c1](https://linux-hardware.org/?probe=f27bded4c1) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26aff1917e](https://linux-hardware.org/?probe=26aff1917e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Intel         | X79 V1.0                    | Desktop     | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | Notebook    | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [fc0052213d](https://linux-hardware.org/?probe=fc0052213d) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [7812f09d39](https://linux-hardware.org/?probe=7812f09d39) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [b45e25ec01](https://linux-hardware.org/?probe=b45e25ec01) | Nov 02, 2023 |
| HP            | 2AF7                        | Desktop     | [65ac8348d7](https://linux-hardware.org/?probe=65ac8348d7) | Nov 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [04f3946d05](https://linux-hardware.org/?probe=04f3946d05) | Nov 02, 2023 |
| Supermicro    | X9DRE-TF+/X9DR7-TF+         | Server      | [1274766930](https://linux-hardware.org/?probe=1274766930) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd018c7ab7](https://linux-hardware.org/?probe=cd018c7ab7) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [d85d5f59c2](https://linux-hardware.org/?probe=d85d5f59c2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | Notebook    | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [38d664802f](https://linux-hardware.org/?probe=38d664802f) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [0ec8ac4d00](https://linux-hardware.org/?probe=0ec8ac4d00) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ea7f00b4e](https://linux-hardware.org/?probe=0ea7f00b4e) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| HP            | 829A                        | Mini pc     | [d6ef1b58ed](https://linux-hardware.org/?probe=d6ef1b58ed) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [e9f8c192f1](https://linux-hardware.org/?probe=e9f8c192f1) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| ASRockRack    | X570D4U-2L2T/BCM            | Server      | [66607ff17c](https://linux-hardware.org/?probe=66607ff17c) | Oct 31, 2023 |
| eMachines     | EL1352G                     | Desktop     | [e133fecf3e](https://linux-hardware.org/?probe=e133fecf3e) | Oct 31, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [a63d934992](https://linux-hardware.org/?probe=a63d934992) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | 8299                        | Desktop     | [e45f46df9d](https://linux-hardware.org/?probe=e45f46df9d) | Oct 30, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e231035f6e](https://linux-hardware.org/?probe=e231035f6e) | Oct 30, 2023 |
| System76      | Adder WS                    | Notebook    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | Notebook    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b62cfa508b](https://linux-hardware.org/?probe=b62cfa508b) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [48040bae06](https://linux-hardware.org/?probe=48040bae06) | Oct 29, 2023 |
| HP            | 2AF7                        | Desktop     | [1960b3a243](https://linux-hardware.org/?probe=1960b3a243) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [c1785bec94](https://linux-hardware.org/?probe=c1785bec94) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Samsung       | DM700A4K-KN27 SGL8559A1A... | All in one  | [e6c0db51c1](https://linux-hardware.org/?probe=e6c0db51c1) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6b8560a943](https://linux-hardware.org/?probe=6b8560a943) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9a6fdf5543](https://linux-hardware.org/?probe=9a6fdf5543) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [85b2c39c93](https://linux-hardware.org/?probe=85b2c39c93) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | Desktop     | [fdb96441a0](https://linux-hardware.org/?probe=fdb96441a0) | Oct 27, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | Desktop     | [dde83d5de1](https://linux-hardware.org/?probe=dde83d5de1) | Oct 27, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [880bf38f49](https://linux-hardware.org/?probe=880bf38f49) | Oct 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [fc29a80949](https://linux-hardware.org/?probe=fc29a80949) | Oct 27, 2023 |
| System76      | Darter Pro                  | Notebook    | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | Notebook    | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [4938c66cd8](https://linux-hardware.org/?probe=4938c66cd8) | Oct 27, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [815b0a4bc4](https://linux-hardware.org/?probe=815b0a4bc4) | Oct 27, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [61bdfadaa0](https://linux-hardware.org/?probe=61bdfadaa0) | Oct 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | Notebook    | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | Notebook    | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [13ad3bb316](https://linux-hardware.org/?probe=13ad3bb316) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8d850eef8](https://linux-hardware.org/?probe=a8d850eef8) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [023bd4d497](https://linux-hardware.org/?probe=023bd4d497) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [638386d33c](https://linux-hardware.org/?probe=638386d33c) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [dab53e45c9](https://linux-hardware.org/?probe=dab53e45c9) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [85fac54d6a](https://linux-hardware.org/?probe=85fac54d6a) | Oct 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | Desktop     | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Intel         | H61 V124                    | Desktop     | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b1f52f8dc1](https://linux-hardware.org/?probe=b1f52f8dc1) | Oct 23, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9af589ace](https://linux-hardware.org/?probe=a9af589ace) | Oct 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | Notebook    | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ce5ff412d1](https://linux-hardware.org/?probe=ce5ff412d1) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e0f48fec00](https://linux-hardware.org/?probe=e0f48fec00) | Oct 22, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | Notebook    | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [85894d27fe](https://linux-hardware.org/?probe=85894d27fe) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Dell          | 06FW8P A01                  | Desktop     | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | Notebook    | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [81f32f2ac2](https://linux-hardware.org/?probe=81f32f2ac2) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | Notebook    | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ed3ce7aaa6](https://linux-hardware.org/?probe=ed3ce7aaa6) | Oct 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Dell          | 0JYF1T A03                  | Server      | [93ada2329e](https://linux-hardware.org/?probe=93ada2329e) | Oct 18, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [b6b4b14ba1](https://linux-hardware.org/?probe=b6b4b14ba1) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| HP            | 85A2                        | All in one  | [67234a41ca](https://linux-hardware.org/?probe=67234a41ca) | Oct 18, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [e275cfc499](https://linux-hardware.org/?probe=e275cfc499) | Oct 18, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [d652b15856](https://linux-hardware.org/?probe=d652b15856) | Oct 17, 2023 |
| System76      | Gazelle                     | Notebook    | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [464e218144](https://linux-hardware.org/?probe=464e218144) | Oct 17, 2023 |
| Gigabyte      | Z590 VISION D               | Desktop     | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [0ebd0d4ce6](https://linux-hardware.org/?probe=0ebd0d4ce6) | Oct 16, 2023 |
| HP            | 250 G4                      | Notebook    | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | Notebook    | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | Notebook    | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [5631fc0230](https://linux-hardware.org/?probe=5631fc0230) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| HP            | ProBook 4730s               | Notebook    | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [98224c65b6](https://linux-hardware.org/?probe=98224c65b6) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [abc6dc18ab](https://linux-hardware.org/?probe=abc6dc18ab) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| HP            | 212B                        | Desktop     | [c0b9765d6e](https://linux-hardware.org/?probe=c0b9765d6e) | Oct 15, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5bbd5682e8](https://linux-hardware.org/?probe=5bbd5682e8) | Oct 15, 2023 |
| System76      | Lemur Pro                   | Notebook    | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [5a1df4c4df](https://linux-hardware.org/?probe=5a1df4c4df) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a8e7e9b968](https://linux-hardware.org/?probe=a8e7e9b968) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [7df48c5c5d](https://linux-hardware.org/?probe=7df48c5c5d) | Oct 14, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [0594aaa28b](https://linux-hardware.org/?probe=0594aaa28b) | Oct 13, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [596e3973bc](https://linux-hardware.org/?probe=596e3973bc) | Oct 13, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d6379353d](https://linux-hardware.org/?probe=4d6379353d) | Oct 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [52fdfb249e](https://linux-hardware.org/?probe=52fdfb249e) | Oct 12, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Biostar       | B550GTQ                     | Desktop     | [63f1b39dd4](https://linux-hardware.org/?probe=63f1b39dd4) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| HP            | Unknown                     | Convertible | [8fe4fae90f](https://linux-hardware.org/?probe=8fe4fae90f) | Oct 12, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [df15a4cce8](https://linux-hardware.org/?probe=df15a4cce8) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| System76      | Thelio Mega thelio-mega-... | Desktop     | [abb07364c1](https://linux-hardware.org/?probe=abb07364c1) | Oct 11, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | Notebook    | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4ce0d26e3c](https://linux-hardware.org/?probe=4ce0d26e3c) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| HP            | ProLiant SE1220             | Server      | [da67ae4335](https://linux-hardware.org/?probe=da67ae4335) | Oct 11, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [ee15914a37](https://linux-hardware.org/?probe=ee15914a37) | Oct 10, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | Notebook    | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3d02079672](https://linux-hardware.org/?probe=3d02079672) | Oct 10, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b09f4a3a8a](https://linux-hardware.org/?probe=b09f4a3a8a) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | Notebook    | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | Notebook    | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | Notebook    | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2d033cba6c](https://linux-hardware.org/?probe=2d033cba6c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d510e53b4](https://linux-hardware.org/?probe=3d510e53b4) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3ac34a911c](https://linux-hardware.org/?probe=3ac34a911c) | Oct 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a3190a6c6d](https://linux-hardware.org/?probe=a3190a6c6d) | Oct 07, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [e223a799bc](https://linux-hardware.org/?probe=e223a799bc) | Oct 07, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [36d48fe6f7](https://linux-hardware.org/?probe=36d48fe6f7) | Oct 07, 2023 |
| HP            | 8058                        | All in one  | [1e3047c572](https://linux-hardware.org/?probe=1e3047c572) | Oct 07, 2023 |
| System76      | Serval WS                   | Notebook    | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [17cdd65d6b](https://linux-hardware.org/?probe=17cdd65d6b) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [9477d90e51](https://linux-hardware.org/?probe=9477d90e51) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | Notebook    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5ec4f81683](https://linux-hardware.org/?probe=5ec4f81683) | Oct 06, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [95d81c3bb1](https://linux-hardware.org/?probe=95d81c3bb1) | Oct 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | Notebook    | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| HP            | Unknown                     | Convertible | [46bfa371c4](https://linux-hardware.org/?probe=46bfa371c4) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [ebbd23f352](https://linux-hardware.org/?probe=ebbd23f352) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | Notebook    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [3f779c87f6](https://linux-hardware.org/?probe=3f779c87f6) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [eb2aacccb0](https://linux-hardware.org/?probe=eb2aacccb0) | Oct 03, 2023 |
| HP            | 0AA4h                       | Desktop     | [8e4a645689](https://linux-hardware.org/?probe=8e4a645689) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5932daaa4e](https://linux-hardware.org/?probe=5932daaa4e) | Oct 03, 2023 |
| Dell          | Latitude 7400               | Notebook    | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| ASRock        | Z790 PG Riptide             | Desktop     | [82630a534f](https://linux-hardware.org/?probe=82630a534f) | Oct 03, 2023 |
| Kllisre       | X79 V1.2                    | Desktop     | [fb9b29c804](https://linux-hardware.org/?probe=fb9b29c804) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b5965220de](https://linux-hardware.org/?probe=b5965220de) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | Notebook    | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [57ddb0f758](https://linux-hardware.org/?probe=57ddb0f758) | Oct 01, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [d16a64a7e1](https://linux-hardware.org/?probe=d16a64a7e1) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | Notebook    | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| HP            | 8054                        | Desktop     | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | Notebook    | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| AZW           | SER V1                      | Desktop     | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | Notebook    | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [9d86e194aa](https://linux-hardware.org/?probe=9d86e194aa) | Sep 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f11867f0b7](https://linux-hardware.org/?probe=f11867f0b7) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5a73611f4d](https://linux-hardware.org/?probe=5a73611f4d) | Sep 26, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [0a5cc18946](https://linux-hardware.org/?probe=0a5cc18946) | Sep 26, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [4259a21921](https://linux-hardware.org/?probe=4259a21921) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [2fe436c443](https://linux-hardware.org/?probe=2fe436c443) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9de1c7395f](https://linux-hardware.org/?probe=9de1c7395f) | Sep 25, 2023 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [ac151127e1](https://linux-hardware.org/?probe=ac151127e1) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a7eb798aed](https://linux-hardware.org/?probe=a7eb798aed) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ac45698051](https://linux-hardware.org/?probe=ac45698051) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | Notebook    | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7119229a1b](https://linux-hardware.org/?probe=7119229a1b) | Sep 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a3e2e5f3c0](https://linux-hardware.org/?probe=a3e2e5f3c0) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f4a96c9156](https://linux-hardware.org/?probe=f4a96c9156) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | Notebook    | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9be7572b83](https://linux-hardware.org/?probe=9be7572b83) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [b063963175](https://linux-hardware.org/?probe=b063963175) | Sep 23, 2023 |
| HP            | 250 G4                      | Notebook    | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | Notebook    | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [1c755bb49f](https://linux-hardware.org/?probe=1c755bb49f) | Sep 23, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | Desktop     | [32b162a364](https://linux-hardware.org/?probe=32b162a364) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [6656c28ec7](https://linux-hardware.org/?probe=6656c28ec7) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [9867cb03bb](https://linux-hardware.org/?probe=9867cb03bb) | Sep 23, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d344d1e396](https://linux-hardware.org/?probe=d344d1e396) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [31fc587bda](https://linux-hardware.org/?probe=31fc587bda) | Sep 22, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | Notebook    | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [19d1333b4f](https://linux-hardware.org/?probe=19d1333b4f) | Sep 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [5e45e8b196](https://linux-hardware.org/?probe=5e45e8b196) | Sep 21, 2023 |
| System76      | Darter Pro                  | Notebook    | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | Notebook    | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| ASRockRack    | Z490D4U-2L2T                | Desktop     | [0d43dbb11d](https://linux-hardware.org/?probe=0d43dbb11d) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e0371fc03e](https://linux-hardware.org/?probe=e0371fc03e) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [43bf92a01b](https://linux-hardware.org/?probe=43bf92a01b) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [5c77a043ae](https://linux-hardware.org/?probe=5c77a043ae) | Sep 15, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | Notebook    | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | Notebook    | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [ebac37bdbd](https://linux-hardware.org/?probe=ebac37bdbd) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | Notebook    | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | Notebook    | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | Notebook    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [49aca37979](https://linux-hardware.org/?probe=49aca37979) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | Desktop     | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | Notebook    | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [6fdfbcc425](https://linux-hardware.org/?probe=6fdfbcc425) | Sep 10, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [56bef39b59](https://linux-hardware.org/?probe=56bef39b59) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a812c1659b](https://linux-hardware.org/?probe=a812c1659b) | Sep 09, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [375f82dc0c](https://linux-hardware.org/?probe=375f82dc0c) | Sep 09, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [de7d9282cd](https://linux-hardware.org/?probe=de7d9282cd) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | Notebook    | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| HP            | 1495                        | Desktop     | [b56f622d7a](https://linux-hardware.org/?probe=b56f622d7a) | Sep 09, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8442c861ed](https://linux-hardware.org/?probe=8442c861ed) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | Notebook    | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [bad7c8bf82](https://linux-hardware.org/?probe=bad7c8bf82) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Dell          | 0WN7Y6 A02                  | Desktop     | [aaf64e4624](https://linux-hardware.org/?probe=aaf64e4624) | Sep 07, 2023 |
| Biostar       | A58MD                       | Desktop     | [40f078fcfc](https://linux-hardware.org/?probe=40f078fcfc) | Sep 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [613e4acc75](https://linux-hardware.org/?probe=613e4acc75) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | Notebook    | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [1c82c8d8b5](https://linux-hardware.org/?probe=1c82c8d8b5) | Sep 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b4907a6220](https://linux-hardware.org/?probe=b4907a6220) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| MSI           | A320M-A PRO M2              | Desktop     | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [6ddc9b767d](https://linux-hardware.org/?probe=6ddc9b767d) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [d0cdea5d23](https://linux-hardware.org/?probe=d0cdea5d23) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| Google        | Kefka                       | Notebook    | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [45f86c066d](https://linux-hardware.org/?probe=45f86c066d) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | Notebook    | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ebebe5ddf7](https://linux-hardware.org/?probe=ebebe5ddf7) | Aug 29, 2023 |
| Dell          | Latitude 5330               | Notebook    | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6d2186fdd9](https://linux-hardware.org/?probe=6d2186fdd9) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | Notebook    | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | Notebook    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| HP            | ProBook 4730s               | Notebook    | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | Notebook    | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8d952e28e1](https://linux-hardware.org/?probe=8d952e28e1) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| System76      | Thelio Major thelio-majo... | Desktop     | [e5caa63b77](https://linux-hardware.org/?probe=e5caa63b77) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [254f8aee40](https://linux-hardware.org/?probe=254f8aee40) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6f72852248](https://linux-hardware.org/?probe=6f72852248) | Aug 25, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [acc5fdd0f3](https://linux-hardware.org/?probe=acc5fdd0f3) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [c0bf920a5b](https://linux-hardware.org/?probe=c0bf920a5b) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| HP            | 18E7                        | Desktop     | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| Samsung       | 750TDA                      | Notebook    | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [145d800029](https://linux-hardware.org/?probe=145d800029) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | Notebook    | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| Supermicro    | X12SPA-TF                   | Server      | [b0d65c559f](https://linux-hardware.org/?probe=b0d65c559f) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [d86049c586](https://linux-hardware.org/?probe=d86049c586) | Aug 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [be53b5931f](https://linux-hardware.org/?probe=be53b5931f) | Aug 21, 2023 |
| HP            | ProBook 4730s               | Notebook    | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [d699113f95](https://linux-hardware.org/?probe=d699113f95) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [83b6cab3cd](https://linux-hardware.org/?probe=83b6cab3cd) | Aug 20, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| NZXT          | N7 B550                     | Desktop     | [1f105eadd8](https://linux-hardware.org/?probe=1f105eadd8) | Aug 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [31861c8357](https://linux-hardware.org/?probe=31861c8357) | Aug 20, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [04df52e837](https://linux-hardware.org/?probe=04df52e837) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | Notebook    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | Notebook    | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [63d06430e4](https://linux-hardware.org/?probe=63d06430e4) | Aug 18, 2023 |
| HP            | 0266                        | Desktop     | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [70eda3a12d](https://linux-hardware.org/?probe=70eda3a12d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a77f908bb5](https://linux-hardware.org/?probe=a77f908bb5) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [53c4af621d](https://linux-hardware.org/?probe=53c4af621d) | Aug 18, 2023 |
| ASUSTek       | U38N                        | Notebook    | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| HP            | 2AF7                        | Desktop     | [4e55d08586](https://linux-hardware.org/?probe=4e55d08586) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| System76      | Lemur Pro                   | Notebook    | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| HP            | Elite Dragonfly             | Convertible | [7419fe990e](https://linux-hardware.org/?probe=7419fe990e) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | Desktop     | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0927025cfc](https://linux-hardware.org/?probe=0927025cfc) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Intel         | B75A                        | Desktop     | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| System76      | Galago Pro                  | Notebook    | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0b194349eb](https://linux-hardware.org/?probe=0b194349eb) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| HP            | ProBook 4540s               | Notebook    | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [2c2aca991d](https://linux-hardware.org/?probe=2c2aca991d) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [b87f112952](https://linux-hardware.org/?probe=b87f112952) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [edf714498f](https://linux-hardware.org/?probe=edf714498f) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [213d229837](https://linux-hardware.org/?probe=213d229837) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [eb83156c5f](https://linux-hardware.org/?probe=eb83156c5f) | Aug 12, 2023 |
| Intel         | B75A                        | Desktop     | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | Notebook    | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | Notebook    | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 832       | 19.54%  |
| 6.0.12-76060006-generic  | 476       | 11.18%  |
| 5.19.0-76051900-generic  | 449       | 10.54%  |
| 5.17.5-76051705-generic  | 419       | 9.84%   |
| 6.0.6-76060006-generic   | 302       | 7.09%   |
| 6.4.6-76060406-generic   | 293       | 6.88%   |
| 6.5.6-76060506-generic   | 286       | 6.72%   |
| 5.18.10-76051810-generic | 207       | 4.86%   |
| 5.17.15-76051715-generic | 186       | 4.37%   |
| 6.5.4-76060504-generic   | 127       | 2.98%   |
| 6.2.0-76060200-generic   | 122       | 2.87%   |
| 5.16.19-76051619-generic | 122       | 2.87%   |
| 6.0.2-76060002-generic   | 92        | 2.16%   |
| 6.1.11-76060111-generic  | 91        | 2.14%   |
| 6.6.6-76060606-generic   | 43        | 1.01%   |
| 5.19.16-76051916-generic | 43        | 1.01%   |
| 6.0.3-76060003-generic   | 40        | 0.94%   |
| 6.3.7-060307-generic     | 5         | 0.12%   |
| 6.5.7-060507-generic     | 3         | 0.07%   |
| 6.3.4-060304-generic     | 3         | 0.07%   |
| 6.1.0-1006-oem           | 3         | 0.07%   |
| 5.16.15-76051615-generic | 3         | 0.07%   |
| 6.5.5-x64v3-xanmod1      | 2         | 0.05%   |
| 6.5.12-x64v3-xanmod1     | 2         | 0.05%   |
| 6.4.0-060400-generic     | 2         | 0.05%   |
| 6.2.11-060211-generic    | 2         | 0.05%   |
| 6.1.8-060108-generic     | 2         | 0.05%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.05%   |
| 6.0.9-060009-generic     | 2         | 0.05%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.05%   |
| 5.19.12-xanmod1          | 2         | 0.05%   |
| 5.17.7-051707-generic    | 2         | 0.05%   |
| 5.17.5-051705-generic    | 2         | 0.05%   |
| 6.5.8-x64v1-xanmod1      | 1         | 0.02%   |
| 6.5.7-x64v3-xanmod1      | 1         | 0.02%   |
| 6.5.10-x64v3-xanmod1     | 1         | 0.02%   |
| 6.5.10-x64v2-xanmod1     | 1         | 0.02%   |
| 6.5.0-rc2                | 1         | 0.02%   |
| 6.4.8-x64v3-xanmod1      | 1         | 0.02%   |
| 6.4.7-surface            | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 833       | 19.57%  |
| 6.0.12  | 477       | 11.21%  |
| 5.19.0  | 453       | 10.64%  |
| 5.17.5  | 422       | 9.92%   |
| 6.0.6   | 303       | 7.12%   |
| 6.4.6   | 293       | 6.88%   |
| 6.5.6   | 286       | 6.72%   |
| 5.18.10 | 207       | 4.86%   |
| 5.17.15 | 186       | 4.37%   |
| 6.5.4   | 127       | 2.98%   |
| 6.2.0   | 122       | 2.87%   |
| 5.16.19 | 122       | 2.87%   |
| 6.0.2   | 95        | 2.23%   |
| 6.1.11  | 92        | 2.16%   |
| 6.6.6   | 43        | 1.01%   |
| 5.19.16 | 43        | 1.01%   |
| 6.0.3   | 40        | 0.94%   |
| 5.15.0  | 8         | 0.19%   |
| 6.1.0   | 6         | 0.14%   |
| 6.3.7   | 5         | 0.12%   |
| 6.5.7   | 4         | 0.09%   |
| 6.3.4   | 4         | 0.09%   |
| 6.1.8   | 3         | 0.07%   |
| 6.0.9   | 3         | 0.07%   |
| 5.16.15 | 3         | 0.07%   |
| 6.5.5   | 2         | 0.05%   |
| 6.5.12  | 2         | 0.05%   |
| 6.5.10  | 2         | 0.05%   |
| 6.4.0   | 2         | 0.05%   |
| 6.3.9   | 2         | 0.05%   |
| 6.3.8   | 2         | 0.05%   |
| 6.3.1   | 2         | 0.05%   |
| 6.2.9   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |
| 6.2.11  | 2         | 0.05%   |
| 6.1.9   | 2         | 0.05%   |
| 6.1.12  | 2         | 0.05%   |
| 6.0.0   | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.18.0  | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 954       | 22.78%  |
| 6.0     | 893       | 21.32%  |
| 5.17    | 604       | 14.42%  |
| 5.19    | 498       | 11.89%  |
| 6.5     | 419       | 10%     |
| 6.4     | 300       | 7.16%   |
| 5.18    | 213       | 5.09%   |
| 5.16    | 126       | 3.01%   |
| 6.1     | 109       | 2.6%    |
| 6.6     | 43        | 1.03%   |
| 6.3     | 17        | 0.41%   |
| 5.15    | 11        | 0.26%   |
| 5.4     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3807      | 99.84%  |
| aarch64 | 6         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 3705      | 96.89%  |
| KDE5            | 50        | 1.31%   |
| Unknown         | 25        | 0.65%   |
| X-Cinnamon      | 15        | 0.39%   |
| GNOME Flashback | 8         | 0.21%   |
| Unity           | 5         | 0.13%   |
| LXQt            | 4         | 0.1%    |
| i3              | 3         | 0.08%   |
| Cinnamon        | 3         | 0.08%   |
| XFCE            | 2         | 0.05%   |
| MATE            | 2         | 0.05%   |
| UKUI            | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3649      | 95.03%  |
| Wayland | 168       | 4.38%   |
| Unknown | 18        | 0.47%   |
| Tty     | 5         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2851      | 74.21%  |
| GDM3    | 971       | 25.27%  |
| SDDM    | 10        | 0.26%   |
| GDM     | 8         | 0.21%   |
| LightDM | 2         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2273      | 59.12%  |
| en_GB   | 249       | 6.48%   |
| pt_BR   | 204       | 5.31%   |
| de_DE   | 186       | 4.84%   |
| C       | 135       | 3.51%   |
| en_AU   | 89        | 2.31%   |
| it_IT   | 76        | 1.98%   |
| en_CA   | 74        | 1.92%   |
| fr_FR   | 71        | 1.85%   |
| es_ES   | 47        | 1.22%   |
| ru_RU   | 44        | 1.14%   |
| pl_PL   | 38        | 0.99%   |
| Unknown | 24        | 0.62%   |
| nb_NO   | 21        | 0.55%   |
| sv_SE   | 19        | 0.49%   |
| pt_PT   | 19        | 0.49%   |
| en_IN   | 19        | 0.49%   |
| fi_FI   | 17        | 0.44%   |
| nl_NL   | 16        | 0.42%   |
| en_NZ   | 15        | 0.39%   |
| es_CL   | 13        | 0.34%   |
| de_CH   | 13        | 0.34%   |
| tr_TR   | 12        | 0.31%   |
| es_MX   | 12        | 0.31%   |
| en_IE   | 12        | 0.31%   |
| da_DK   | 12        | 0.31%   |
| fr_CA   | 11        | 0.29%   |
| en_DK   | 11        | 0.29%   |
| ja_JP   | 10        | 0.26%   |
| es_AR   | 10        | 0.26%   |
| en_ZA   | 9         | 0.23%   |
| de_AT   | 9         | 0.23%   |
| cs_CZ   | 8         | 0.21%   |
| es_CO   | 5         | 0.13%   |
| zh_TW   | 4         | 0.1%    |
| fr_CH   | 4         | 0.1%    |
| fr_BE   | 4         | 0.1%    |
| zh_CN   | 3         | 0.08%   |
| ro_RO   | 3         | 0.08%   |
| hu_HU   | 3         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2896      | 75.38%  |
| EFI  | 946       | 24.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3622      | 94.62%  |
| Btrfs   | 109       | 2.85%   |
| Overlay | 79        | 2.06%   |
| Xfs     | 11        | 0.29%   |
| Zfs     | 5         | 0.13%   |
| Tmpfs   | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2829      | 73.63%  |
| GPT     | 957       | 24.91%  |
| MBR     | 56        | 1.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3696      | 96.63%  |
| Yes       | 129       | 3.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3426      | 89.5%   |
| Yes       | 402       | 10.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 687       | 18.02%  |
| Lenovo                  | 545       | 14.29%  |
| Dell                    | 469       | 12.3%   |
| Hewlett-Packard         | 437       | 11.46%  |
| MSI                     | 291       | 7.63%   |
| Gigabyte Technology     | 247       | 6.48%   |
| Apple                   | 208       | 5.46%   |
| Acer                    | 169       | 4.43%   |
| ASRock                  | 117       | 3.07%   |
| System76                | 90        | 2.36%   |
| Intel                   | 48        | 1.26%   |
| Samsung Electronics     | 41        | 1.08%   |
| Toshiba                 | 40        | 1.05%   |
| HUAWEI                  | 31        | 0.81%   |
| Alienware               | 25        | 0.66%   |
| Microsoft               | 21        | 0.55%   |
| Unknown                 | 21        | 0.55%   |
| Google                  | 20        | 0.52%   |
| Fujitsu                 | 19        | 0.5%    |
| Notebook                | 18        | 0.47%   |
| AZW                     | 13        | 0.34%   |
| Positivo                | 12        | 0.31%   |
| Sony                    | 11        | 0.29%   |
| Razer                   | 11        | 0.29%   |
| GPU Company             | 10        | 0.26%   |
| BESSTAR Tech            | 10        | 0.26%   |
| Timi                    | 8         | 0.21%   |
| Framework               | 8         | 0.21%   |
| HONOR                   | 7         | 0.18%   |
| Biostar                 | 7         | 0.18%   |
| Supermicro              | 6         | 0.16%   |
| Raspberry Pi Foundation | 6         | 0.16%   |
| MACHINIST               | 6         | 0.16%   |
| Avell High Performance  | 6         | 0.16%   |
| Pegatron                | 5         | 0.13%   |
| PC Specialist           | 5         | 0.13%   |
| Foxconn                 | 5         | 0.13%   |
| ZOTAC                   | 4         | 0.1%    |
| TUXEDO                  | 4         | 0.1%    |
| Schenker                | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 29        | 0.76%   |
| ASUS All Series                     | 26        | 0.68%   |
| System76 Oryx Pro                   | 19        | 0.5%    |
| ASUS ROG STRIX B550-F GAMING        | 18        | 0.47%   |
| System76 Lemur Pro                  | 16        | 0.42%   |
| Apple MacBookAir7,2                 | 15        | 0.39%   |
| System76 Gazelle                    | 13        | 0.34%   |
| HP Dev One Notebook PC              | 13        | 0.34%   |
| Apple MacBookPro12,1                | 12        | 0.31%   |
| Apple MacBookAir6,2                 | 12        | 0.31%   |
| Apple MacBookPro8,1                 | 11        | 0.29%   |
| ASUS TUF Gaming X570-PLUS           | 10        | 0.26%   |
| ASUS ROG STRIX B550-I GAMING        | 10        | 0.26%   |
| ASUS ROG STRIX B450-F GAMING        | 10        | 0.26%   |
| Apple MacBookPro9,2                 | 10        | 0.26%   |
| Gigabyte X570 AORUS ELITE           | 9         | 0.24%   |
| Apple MacBookPro11,3                | 9         | 0.24%   |
| System76 Darter Pro                 | 8         | 0.21%   |
| MSI MS-7B86                         | 8         | 0.21%   |
| Dell XPS 15 9520                    | 8         | 0.21%   |
| ASUS TUF Gaming B550-PLUS           | 8         | 0.21%   |
| System76 Galago Pro                 | 7         | 0.18%   |
| MSI MS-7C95                         | 7         | 0.18%   |
| MSI MS-7C91                         | 7         | 0.18%   |
| MSI MS-7C37                         | 7         | 0.18%   |
| MSI MS-7A38                         | 7         | 0.18%   |
| Lenovo Legion 5 15ACH6H 82JU        | 7         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7      | 7         | 0.18%   |
| Gigabyte B450 AORUS M               | 7         | 0.18%   |
| Gigabyte A320M-S2H                  | 7         | 0.18%   |
| Dell XPS 15 7590                    | 7         | 0.18%   |
| ASUS PRIME B450M-A                  | 7         | 0.18%   |
| Apple MacBookPro7,1                 | 7         | 0.18%   |
| System76 Thelio                     | 6         | 0.16%   |
| System76 Pangolin                   | 6         | 0.16%   |
| MSI MS-7D54                         | 6         | 0.16%   |
| MSI MS-7C02                         | 6         | 0.16%   |
| MSI MS-7A34                         | 6         | 0.16%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9 | 6         | 0.16%   |
| Lenovo IdeaPad 3 15ALC6 82MF        | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 209       | 5.48%   |
| ASUS ROG           | 180       | 4.72%   |
| Lenovo IdeaPad     | 126       | 3.3%    |
| Dell Inspiron      | 116       | 3.04%   |
| Acer Aspire        | 106       | 2.78%   |
| Dell Latitude      | 102       | 2.68%   |
| Dell XPS           | 85        | 2.23%   |
| ASUS PRIME         | 72        | 1.89%   |
| HP Pavilion        | 71        | 1.86%   |
| ASUS TUF           | 67        | 1.76%   |
| ASUS VivoBook      | 61        | 1.6%    |
| Dell Precision     | 60        | 1.57%   |
| HP EliteBook       | 55        | 1.44%   |
| Lenovo Legion      | 51        | 1.34%   |
| HP Laptop          | 49        | 1.29%   |
| Dell OptiPlex      | 42        | 1.1%    |
| Lenovo Yoga        | 38        | 1%      |
| HP ProBook         | 37        | 0.97%   |
| ASUS ASUS          | 34        | 0.89%   |
| Toshiba Satellite  | 33        | 0.87%   |
| HP ENVY            | 32        | 0.84%   |
| Unknown            | 29        | 0.76%   |
| ASUS ZenBook       | 28        | 0.73%   |
| Lenovo ThinkCentre | 27        | 0.71%   |
| ASUS All           | 26        | 0.68%   |
| Gigabyte X570      | 25        | 0.66%   |
| HP ZBook           | 24        | 0.63%   |
| Acer Swift         | 24        | 0.63%   |
| HP Compaq          | 23        | 0.6%    |
| Apple MacBookPro11 | 23        | 0.6%    |
| Microsoft Surface  | 21        | 0.55%   |
| HP OMEN            | 21        | 0.55%   |
| Dell Vostro        | 21        | 0.55%   |
| Acer Nitro         | 20        | 0.52%   |
| System76 Oryx      | 19        | 0.5%    |
| Gigabyte B450      | 19        | 0.5%    |
| HP EliteDesk       | 17        | 0.45%   |
| System76 Lemur     | 16        | 0.42%   |
| Lenovo ThinkBook   | 16        | 0.42%   |
| Apple MacBookAir7  | 15        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 513       | 13.45%  |
| 2020    | 477       | 12.51%  |
| 2022    | 423       | 11.09%  |
| 2019    | 359       | 9.42%   |
| 2018    | 352       | 9.23%   |
| 2013    | 216       | 5.66%   |
| 2017    | 207       | 5.43%   |
| 2012    | 203       | 5.32%   |
| 2014    | 179       | 4.69%   |
| 2011    | 172       | 4.51%   |
| 2015    | 170       | 4.46%   |
| 2016    | 166       | 4.35%   |
| 2023    | 112       | 2.94%   |
| 2010    | 98        | 2.57%   |
| 2009    | 85        | 2.23%   |
| 2008    | 38        | 1%      |
| 2007    | 32        | 0.84%   |
| Unknown | 8         | 0.21%   |
| 2006    | 2         | 0.05%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2185      | 57.3%   |
| Desktop        | 1319      | 34.59%  |
| Convertible    | 127       | 3.33%   |
| Mini pc        | 68        | 1.78%   |
| All in one     | 54        | 1.42%   |
| Tablet         | 36        | 0.94%   |
| Server         | 17        | 0.45%   |
| System on chip | 7         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3811      | 99.9%   |
| Enabled  | 4         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3733      | 97.9%   |
| Yes  | 80        | 2.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1006      | 26.11%  |
| 4.01-8.0        | 822       | 21.33%  |
| 8.01-16.0       | 684       | 17.75%  |
| 32.01-64.0      | 667       | 17.31%  |
| 3.01-4.0        | 325       | 8.43%   |
| 64.01-256.0     | 219       | 5.68%   |
| 24.01-32.0      | 106       | 2.75%   |
| 1.01-2.0        | 13        | 0.34%   |
| 2.01-3.0        | 8         | 0.21%   |
| More than 256.0 | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1407      | 33.99%  |
| 2.01-3.0    | 992       | 23.97%  |
| 3.01-4.0    | 891       | 21.53%  |
| 8.01-16.0   | 445       | 10.75%  |
| 1.01-2.0    | 312       | 7.54%   |
| 16.01-24.0  | 60        | 1.45%   |
| 24.01-32.0  | 16        | 0.39%   |
| 32.01-64.0  | 10        | 0.24%   |
| 0.51-1.0    | 4         | 0.1%    |
| 64.01-256.0 | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2228      | 57.38%  |
| 2      | 1015      | 26.14%  |
| 3      | 336       | 8.65%   |
| 4      | 151       | 3.89%   |
| 5      | 71        | 1.83%   |
| 6      | 33        | 0.85%   |
| 7      | 18        | 0.46%   |
| 0      | 16        | 0.41%   |
| 9      | 5         | 0.13%   |
| 8      | 4         | 0.1%    |
| 11     | 2         | 0.05%   |
| 10     | 2         | 0.05%   |
| 26     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2955      | 77.19%  |
| Yes       | 873       | 22.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3118      | 81.37%  |
| No        | 714       | 18.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3205      | 83.9%   |
| No        | 615       | 16.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2774      | 72.33%  |
| No        | 1061      | 27.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1190      | 31.05%  |
| Brazil       | 288       | 7.51%   |
| Germany      | 274       | 7.15%   |
| UK           | 172       | 4.49%   |
| Canada       | 171       | 4.46%   |
| Italy        | 141       | 3.68%   |
| Australia    | 121       | 3.16%   |
| India        | 101       | 2.64%   |
| France       | 101       | 2.64%   |
| Russia       | 74        | 1.93%   |
| Netherlands  | 73        | 1.9%    |
| Poland       | 63        | 1.64%   |
| Sweden       | 58        | 1.51%   |
| Spain        | 57        | 1.49%   |
| Norway       | 53        | 1.38%   |
| Mexico       | 46        | 1.2%    |
| Portugal     | 42        | 1.1%    |
| Finland      | 40        | 1.04%   |
| Switzerland  | 37        | 0.97%   |
| Turkey       | 32        | 0.83%   |
| Denmark      | 31        | 0.81%   |
| Austria      | 31        | 0.81%   |
| Czechia      | 29        | 0.76%   |
| New Zealand  | 28        | 0.73%   |
| Greece       | 28        | 0.73%   |
| Indonesia    | 27        | 0.7%    |
| Belgium      | 25        | 0.65%   |
| Romania      | 24        | 0.63%   |
| Chile        | 24        | 0.63%   |
| Argentina    | 24        | 0.63%   |
| Philippines  | 23        | 0.6%    |
| Japan        | 23        | 0.6%    |
| Serbia       | 20        | 0.52%   |
| Hungary      | 20        | 0.52%   |
| South Africa | 18        | 0.47%   |
| Ireland      | 18        | 0.47%   |
| Bulgaria     | 17        | 0.44%   |
| Thailand     | 14        | 0.37%   |
| Malaysia     | 14        | 0.37%   |
| Hong Kong    | 13        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 30        | 0.75%   |
| Sydney         | 29        | 0.73%   |
| Melbourne      | 27        | 0.68%   |
| Berlin         | 26        | 0.65%   |
| Helsinki       | 25        | 0.63%   |
| Milan          | 24        | 0.6%    |
| Rio de Janeiro | 23        | 0.58%   |
| Brisbane       | 23        | 0.58%   |
| Seattle        | 21        | 0.53%   |
| Oslo           | 20        | 0.5%    |
| Vienna         | 19        | 0.48%   |
| Moscow         | 18        | 0.45%   |
| Madrid         | 17        | 0.43%   |
| Istanbul       | 17        | 0.43%   |
| Chicago        | 17        | 0.43%   |
| Warsaw         | 16        | 0.4%    |
| Bengaluru      | 16        | 0.4%    |
| New York       | 15        | 0.38%   |
| Hamburg        | 15        | 0.38%   |
| Denver         | 15        | 0.38%   |
| Rome           | 14        | 0.35%   |
| London         | 14        | 0.35%   |
| Zurich         | 13        | 0.33%   |
| Toronto        | 13        | 0.33%   |
| Prague         | 13        | 0.33%   |
| Lisbon         | 13        | 0.33%   |
| Edmonton       | 13        | 0.33%   |
| Belgrade       | 13        | 0.33%   |
| Dallas         | 12        | 0.3%    |
| Calgary        | 12        | 0.3%    |
| Auckland       | 12        | 0.3%    |
| Amsterdam      | 12        | 0.3%    |
| Stockholm      | 11        | 0.28%   |
| Sofia          | 11        | 0.28%   |
| San Antonio    | 11        | 0.28%   |
| Portland       | 11        | 0.28%   |
| Paris          | 11        | 0.28%   |
| Munich         | 11        | 0.28%   |
| Dublin         | 11        | 0.28%   |
| Singapore      | 10        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1140      | 1668   | 19.49%  |
| WDC                            | 613       | 841    | 10.48%  |
| Seagate                        | 609       | 862    | 10.41%  |
| Sandisk                        | 442       | 575    | 7.56%   |
| Kingston                       | 299       | 361    | 5.11%   |
| Toshiba                        | 261       | 316    | 4.46%   |
| Crucial                        | 251       | 338    | 4.29%   |
| SK hynix                       | 210       | 247    | 3.59%   |
| Intel                          | 158       | 205    | 2.7%    |
| Micron Technology              | 150       | 177    | 2.56%   |
| Unknown                        | 146       | 191    | 2.5%    |
| Apple                          | 117       | 134    | 2%      |
| Phison Electronics             | 90        | 127    | 1.54%   |
| Hitachi                        | 87        | 129    | 1.49%   |
| HGST                           | 82        | 97     | 1.4%    |
| A-DATA Technology              | 81        | 91     | 1.38%   |
| Micron/Crucial Technology      | 79        | 106    | 1.35%   |
| KIOXIA                         | 65        | 71     | 1.11%   |
| China                          | 63        | 82     | 1.08%   |
| Phison                         | 56        | 67     | 0.96%   |
| PNY                            | 54        | 68     | 0.92%   |
| Silicon Motion                 | 52        | 64     | 0.89%   |
| Kingston Technology Company    | 50        | 59     | 0.85%   |
| SPCC                           | 32        | 45     | 0.55%   |
| Unknown                        | 27        | 31     | 0.46%   |
| Netac                          | 26        | 28     | 0.44%   |
| Team                           | 24        | 29     | 0.41%   |
| Intenso                        | 24        | 34     | 0.41%   |
| ADATA Technology               | 24        | 27     | 0.41%   |
| Realtek Semiconductor          | 20        | 21     | 0.34%   |
| JMicron Technology             | 20        | 32     | 0.34%   |
| Patriot                        | 19        | 24     | 0.32%   |
| KingSpec                       | 18        | 19     | 0.31%   |
| LITEON                         | 17        | 20     | 0.29%   |
| Transcend                      | 16        | 19     | 0.27%   |
| OCZ                            | 16        | 22     | 0.27%   |
| LITEONIT                       | 15        | 26     | 0.26%   |
| Lexar                          | 14        | 17     | 0.24%   |
| XPG                            | 12        | 14     | 0.21%   |
| Solid State Storage Technology | 11        | 11     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 153       | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 97        | 1.5%    |
| Kingston SA400S37240G 240GB SSD                       | 71        | 1.1%    |
| Samsung SSD 850 EVO 500GB                             | 45        | 0.7%    |
| Samsung SSD 850 EVO 250GB                             | 45        | 0.7%    |
| Samsung SSD 860 EVO 1TB                               | 44        | 0.68%   |
| SanDisk NVMe SSD Drive 1TB                            | 42        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                        | 41        | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB                        | 41        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 41        | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 41        | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 38        | 0.59%   |
| Samsung SSD 860 EVO 500GB                             | 38        | 0.59%   |
| Kingston SA400S37480G 480GB SSD                       | 37        | 0.57%   |
| Samsung NVMe SSD Drive 1TB                            | 36        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB                           | 36        | 0.56%   |
| Phison E12 NVMe Controller 512GB                      | 35        | 0.54%   |
| Kingston SA400S37120G 120GB SSD                       | 32        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                        | 31        | 0.48%   |
| Crucial CT240BX500SSD1 240GB                          | 30        | 0.46%   |
| Samsung SSD 980 1TB                                   | 29        | 0.45%   |
| Samsung NVMe SSD Drive 500GB                          | 29        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                          | 28        | 0.43%   |
| Unknown                                               | 27        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                          | 26        | 0.4%    |
| Intel SSD 660P Series 512GB                           | 26        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 25        | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 24        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                        | 24        | 0.37%   |
| Samsung SSD 870 QVO 1TB                               | 24        | 0.37%   |
| Toshiba MQ01ABD100 1TB                                | 23        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 23        | 0.36%   |
| Samsung SSD 980 PRO 1TB                               | 23        | 0.36%   |
| HGST HTS721010A9E630 1TB                              | 23        | 0.36%   |
| Unknown MMC Card  64GB                                | 22        | 0.34%   |
| Toshiba MQ04ABF100 1TB                                | 22        | 0.34%   |
| Seagate Expansion 1TB                                 | 22        | 0.34%   |
| Sandisk WD Black SN850 1024GB                         | 22        | 0.34%   |
| Samsung NVMe SSD Drive 512GB                          | 22        | 0.34%   |
| Unknown MMC Card  32GB                                | 21        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 588       | 821    | 39.44%  |
| WDC                 | 428       | 604    | 28.71%  |
| Toshiba             | 182       | 218    | 12.21%  |
| Hitachi             | 87        | 129    | 5.84%   |
| HGST                | 82        | 97     | 5.5%    |
| Samsung Electronics | 44        | 53     | 2.95%   |
| Apple               | 26        | 30     | 1.74%   |
| Unknown             | 19        | 23     | 1.27%   |
| Fujitsu             | 6         | 10     | 0.4%    |
| TO Exter            | 3         | 3      | 0.2%    |
| Maxtor              | 3         | 3      | 0.2%    |
| JMicron Technology  | 3         | 10     | 0.2%    |
| StoreJet            | 2         | 2      | 0.13%   |
| SABRENT             | 2         | 3      | 0.13%   |
| Intenso             | 2         | 6      | 0.13%   |
| External            | 2         | 2      | 0.13%   |
| ASMT                | 2         | 2      | 0.13%   |
| WD MediaMax         | 1         | 2      | 0.07%   |
| USB3.0              | 1         | 1      | 0.07%   |
| RSH-339             | 1         | 1      | 0.07%   |
| MaxDigital          | 1         | 1      | 0.07%   |
| LaCie               | 1         | 2      | 0.07%   |
| HGST HDN            | 1         | 1      | 0.07%   |
| DELLBOSS            | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |
| Asm                 | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 445       | 627    | 23.48%  |
| Kingston            | 225       | 263    | 11.87%  |
| Crucial             | 215       | 285    | 11.35%  |
| SanDisk             | 153       | 188    | 8.07%   |
| WDC                 | 111       | 132    | 5.86%   |
| Apple               | 78        | 86     | 4.12%   |
| China               | 62        | 81     | 3.27%   |
| A-DATA Technology   | 58        | 64     | 3.06%   |
| PNY                 | 52        | 66     | 2.74%   |
| Intel               | 36        | 47     | 1.9%    |
| SK hynix            | 33        | 38     | 1.74%   |
| Micron Technology   | 32        | 35     | 1.69%   |
| SPCC                | 26        | 32     | 1.37%   |
| Toshiba             | 23        | 23     | 1.21%   |
| Netac               | 21        | 23     | 1.11%   |
| Patriot             | 18        | 23     | 0.95%   |
| KingSpec            | 18        | 19     | 0.95%   |
| Team                | 17        | 21     | 0.9%    |
| OCZ                 | 16        | 22     | 0.84%   |
| Intenso             | 16        | 21     | 0.84%   |
| LITEONIT            | 15        | 26     | 0.79%   |
| Transcend           | 14        | 17     | 0.74%   |
| LITEON              | 14        | 17     | 0.74%   |
| JMicron Technology  | 12        | 14     | 0.63%   |
| Apacer              | 10        | 15     | 0.53%   |
| Hewlett-Packard     | 9         | 12     | 0.47%   |
| Lexar               | 8         | 10     | 0.42%   |
| Seagate             | 6         | 7      | 0.32%   |
| KingDian            | 6         | 11     | 0.32%   |
| GOODRAM             | 6         | 6      | 0.32%   |
| Gigabyte Technology | 6         | 6      | 0.32%   |
| Corsair             | 6         | 8      | 0.32%   |
| Mushkin             | 5         | 7      | 0.26%   |
| Fanxiang            | 5         | 5      | 0.26%   |
| Dogfish             | 5         | 6      | 0.26%   |
| Unknown             | 5         | 5      | 0.26%   |
| Verbatim            | 4         | 8      | 0.21%   |
| OWC                 | 3         | 3      | 0.16%   |
| MyDigitalSSD        | 3         | 3      | 0.16%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2044      | 3008   | 39.66%  |
| SSD     | 1627      | 2398   | 31.57%  |
| HDD     | 1256      | 2028   | 24.37%  |
| MMC     | 119       | 140    | 2.31%   |
| Unknown | 108       | 176    | 2.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2317      | 4212   | 49.06%  |
| NVMe | 2039      | 2985   | 43.17%  |
| SAS  | 248       | 413    | 5.25%   |
| MMC  | 119       | 140    | 2.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1583      | 2293   | 51.66%  |
| 0.51-1.0   | 964       | 1327   | 31.46%  |
| 1.01-2.0   | 301       | 433    | 9.82%   |
| 3.01-4.0   | 96        | 164    | 3.13%   |
| 4.01-10.0  | 72        | 128    | 2.35%   |
| 2.01-3.0   | 39        | 62     | 1.27%   |
| 10.01-20.0 | 9         | 19     | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1051      | 26.64%  |
| 251-500        | 992       | 25.15%  |
| 501-1000       | 845       | 21.42%  |
| 1001-2000      | 386       | 9.78%   |
| More than 3000 | 226       | 5.73%   |
| 2001-3000      | 145       | 3.68%   |
| 51-100         | 123       | 3.12%   |
| 1-20           | 97        | 2.46%   |
| 21-50          | 54        | 1.37%   |
| Unknown        | 26        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1165      | 28.35%  |
| 21-50          | 903       | 21.98%  |
| 101-250        | 617       | 15.02%  |
| 51-100         | 515       | 12.53%  |
| 251-500        | 388       | 9.44%   |
| 501-1000       | 236       | 5.74%   |
| 1001-2000      | 131       | 3.19%   |
| More than 3000 | 81        | 1.97%   |
| 2001-3000      | 47        | 1.14%   |
| Unknown        | 26        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 3         | 3      | 2.54%   |
| HGST HTS725050A7E630 500GB               | 3         | 4      | 2.54%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 2         | 2      | 1.69%   |
| Seagate ST3250310AS 250GB                | 2         | 4      | 1.69%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 2      | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 1.69%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 2         | 2      | 1.69%   |
| Samsung Electronics SSD 850 EVO 250GB    | 2         | 2      | 1.69%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD         | 1         | 1      | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.85%   |
| WDC WDS100T2B0B-00YS70 1TB SSD           | 1         | 1      | 0.85%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1         | 1      | 0.85%   |
| WDC WD5001AALS-00J7B1 500GB              | 1         | 1      | 0.85%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1      | 0.85%   |
| WDC WD5000AADS-00S9B0 500GB              | 1         | 1      | 0.85%   |
| WDC WD3200BEKX-75B7WT0 320GB             | 1         | 1      | 0.85%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.85%   |
| WDC WD20PURZ-85AKKY0 2TB                 | 1         | 1      | 0.85%   |
| WDC WD20PURX-64P6ZY0 2TB                 | 1         | 1      | 0.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 1      | 0.85%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1         | 1      | 0.85%   |
| WDC WD20EFRX-68AX9N0 2TB                 | 1         | 7      | 0.85%   |
| WDC WD15EADS-00P8B0 1TB                  | 1         | 1      | 0.85%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10SPZX-16Z10T0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EZEX-60ZF5A0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 1         | 1      | 0.85%   |
| WDC WD1001FALS-00E8B0 1TB                | 1         | 1      | 0.85%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.85%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.85%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.85%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.85%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.85%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.85%   |
| Toshiba MK3252GSX 320GB                  | 1         | 1      | 0.85%   |
| Toshiba MK1655GSX 160GB                  | 1         | 1      | 0.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 23.01%  |
| Seagate             | 22        | 26     | 19.47%  |
| Samsung Electronics | 15        | 17     | 13.27%  |
| Toshiba             | 7         | 7      | 6.19%   |
| SK hynix            | 7         | 7      | 6.19%   |
| HGST                | 7         | 8      | 6.19%   |
| Hitachi             | 4         | 6      | 3.54%   |
| Kingston            | 3         | 4      | 2.65%   |
| Intel               | 3         | 3      | 2.65%   |
| A-DATA Technology   | 3         | 3      | 2.65%   |
| Team                | 2         | 2      | 1.77%   |
| Micron Technology   | 2         | 4      | 1.77%   |
| Crucial             | 2         | 2      | 1.77%   |
| SanDisk             | 1         | 1      | 0.88%   |
| SABRENT             | 1         | 1      | 0.88%   |
| Plextor             | 1         | 1      | 0.88%   |
| LITEON              | 1         | 1      | 0.88%   |
| Lexar               | 1         | 1      | 0.88%   |
| Leven               | 1         | 1      | 0.88%   |
| Flashwar            | 1         | 1      | 0.88%   |
| China               | 1         | 1      | 0.88%   |
| BAITITON            | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 29     | 34.38%  |
| Seagate             | 22        | 26     | 34.38%  |
| HGST                | 7         | 8      | 10.94%  |
| Toshiba             | 5         | 5      | 7.81%   |
| Hitachi             | 4         | 6      | 6.25%   |
| Samsung Electronics | 3         | 3      | 4.69%   |
| Apple               | 1         | 1      | 1.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 78     | 55.36%  |
| SSD  | 31        | 33     | 27.68%  |
| NVMe | 19        | 21     | 16.96%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 25%     |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 25%     |
| KingDian S400 120GB               | 1         | 2      | 25%     |
| Intenso JAJP600M1TB               | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| KingDian            | 1         | 2      | 25%     |
| Intenso             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2937      | 5998   | 72.63%  |
| Works    | 996       | 1615   | 24.63%  |
| Malfunc  | 107       | 132    | 2.65%   |
| Failed   | 4         | 5      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2096      | 37.93%  |
| AMD                                     | 945       | 17.1%   |
| Samsung Electronics                     | 801       | 14.5%   |
| SanDisk                                 | 374       | 6.77%   |
| SK hynix                                | 178       | 3.22%   |
| Phison Electronics                      | 154       | 2.79%   |
| Kingston Technology Company             | 124       | 2.24%   |
| Micron Technology                       | 118       | 2.14%   |
| Micron/Crucial Technology               | 115       | 2.08%   |
| ASMedia Technology                      | 85        | 1.54%   |
| KIOXIA                                  | 64        | 1.16%   |
| Toshiba America Info Systems            | 63        | 1.14%   |
| Silicon Motion                          | 63        | 1.14%   |
| Nvidia                                  | 52        | 0.94%   |
| ADATA Technology                        | 48        | 0.87%   |
| Marvell Technology Group                | 46        | 0.83%   |
| Realtek Semiconductor                   | 30        | 0.54%   |
| Solid State Storage Technology          | 26        | 0.47%   |
| JMicron Technology                      | 19        | 0.34%   |
| Union Memory (Shenzhen)                 | 17        | 0.31%   |
| Apple                                   | 14        | 0.25%   |
| Seagate Technology                      | 13        | 0.24%   |
| MAXIO Technology (Hangzhou)             | 11        | 0.2%    |
| Broadcom / LSI                          | 11        | 0.2%    |
| Shenzhen Longsys Electronics            | 10        | 0.18%   |
| Solidigm                                | 7         | 0.13%   |
| LSI Logic / Symbios Logic               | 7         | 0.13%   |
| INNOGRIT                                | 7         | 0.13%   |
| Lite-On Technology                      | 6         | 0.11%   |
| Hewlett-Packard                         | 4         | 0.07%   |
| Yangtze Memory Technologies             | 3         | 0.05%   |
| VIA Technologies                        | 3         | 0.05%   |
| Netac Technology                        | 3         | 0.05%   |
| Transcend                               | 2         | 0.04%   |
| Silicon Image                           | 2         | 0.04%   |
| Western Digital                         | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |
| O2 Micro                                | 1         | 0.02%   |
| Biwin Storage Technology                | 1         | 0.02%   |
| Adaptec                                 | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 674       | 11.06%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 338       | 5.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 190       | 3.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 163       | 2.68%   |
| AMD 500 Series Chipset SATA Controller                                         | 162       | 2.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 155       | 2.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 151       | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 151       | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 136       | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 116       | 1.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 109       | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 104       | 1.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 86        | 1.41%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 82        | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 78        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 78        | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 72        | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 71        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 70        | 1.15%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 67        | 1.1%    |
| Phison E12 NVMe Controller                                                     | 65        | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 64        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 63        | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 58        | 0.95%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 56        | 0.92%   |
| Intel SSD 660P Series                                                          | 54        | 0.89%   |
| Intel SATA Controller [RAID mode]                                              | 54        | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 51        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 49        | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 47        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 45        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 44        | 0.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 43        | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 42        | 0.69%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 39        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 39        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 37        | 0.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 35        | 0.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 35        | 0.57%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 34        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2677      | 50.32%  |
| NVMe | 2034      | 38.23%  |
| RAID | 380       | 7.14%   |
| IDE  | 211       | 3.97%   |
| SAS  | 16        | 0.3%    |
| SCSI | 2         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2569      | 67.37%  |
| AMD    | 1238      | 32.47%  |
| ARM    | 6         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 52        | 1.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 51        | 1.34%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 46        | 1.2%    |
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 41        | 1.07%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 40        | 1.05%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 39        | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 1%      |
| Intel 12th Gen Core i7-12700H                 | 38        | 1%      |
| AMD Ryzen 5 5600X 6-Core Processor            | 36        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 35        | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 32        | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 32        | 0.84%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 31        | 0.81%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 31        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 31        | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 28        | 0.73%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.71%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 27        | 0.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 27        | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.63%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 24        | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.58%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 21        | 0.55%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 21        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 20        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 18        | 0.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 18        | 0.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 17        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 17        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 17        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 804       | 21.06%  |
| Intel Core i5           | 730       | 19.12%  |
| Other                   | 501       | 13.12%  |
| AMD Ryzen 5             | 399       | 10.45%  |
| AMD Ryzen 7             | 387       | 10.14%  |
| Intel Core i3           | 168       | 4.4%    |
| AMD Ryzen 9             | 155       | 4.06%   |
| Intel Celeron           | 91        | 2.38%   |
| Intel Core 2 Duo        | 81        | 2.12%   |
| Intel Xeon              | 78        | 2.04%   |
| AMD FX                  | 42        | 1.1%    |
| AMD Ryzen 3             | 38        | 1%      |
| AMD Ryzen 7 PRO         | 34        | 0.89%   |
| Intel Pentium           | 33        | 0.86%   |
| Intel Core i9           | 32        | 0.84%   |
| AMD A8                  | 22        | 0.58%   |
| AMD A10                 | 21        | 0.55%   |
| AMD A6                  | 16        | 0.42%   |
| AMD Ryzen Threadripper  | 13        | 0.34%   |
| AMD Ryzen 5 PRO         | 13        | 0.34%   |
| Intel Core 2 Quad       | 11        | 0.29%   |
| Intel Pentium Dual-Core | 10        | 0.26%   |
| AMD Athlon              | 10        | 0.26%   |
| AMD A4                  | 10        | 0.26%   |
| Intel Pentium Silver    | 9         | 0.24%   |
| AMD Athlon II X2        | 9         | 0.24%   |
| Intel Pentium Gold      | 8         | 0.21%   |
| AMD Athlon II X4        | 7         | 0.18%   |
| Intel Atom              | 6         | 0.16%   |
| AMD Phenom II X4        | 6         | 0.16%   |
| AMD E                   | 6         | 0.16%   |
| Intel Core m5           | 5         | 0.13%   |
| Intel Core 2            | 5         | 0.13%   |
| AMD E1                  | 5         | 0.13%   |
| AMD Ryzen 3 PRO         | 4         | 0.1%    |
| AMD Phenom II X6        | 4         | 0.1%    |
| AMD E2                  | 4         | 0.1%    |
| Intel Pentium Dual      | 3         | 0.08%   |
| Intel Pentium D         | 3         | 0.08%   |
| Intel Genuine           | 3         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1277      | 33.45%  |
| 2       | 948       | 24.83%  |
| 8       | 589       | 15.43%  |
| 6       | 567       | 14.85%  |
| 12      | 125       | 3.27%   |
| 16      | 95        | 2.49%   |
| 14      | 87        | 2.28%   |
| 10      | 66        | 1.73%   |
| 3       | 18        | 0.47%   |
| 24      | 15        | 0.39%   |
| 1       | 15        | 0.39%   |
| Unknown | 6         | 0.16%   |
| 40      | 2         | 0.05%   |
| 36      | 2         | 0.05%   |
| 32      | 2         | 0.05%   |
| 18      | 2         | 0.05%   |
| 64      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3786      | 99.29%  |
| 2       | 21        | 0.55%   |
| Unknown | 6         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3145      | 82.42%  |
| 1       | 665       | 17.43%  |
| Unknown | 6         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3809      | 99.9%   |
| 64-bit         | 4         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3118      | 80.63%  |
| 0x806c1    | 50        | 1.29%   |
| 0x0a50000c | 45        | 1.16%   |
| 0x806ec    | 26        | 0.67%   |
| 0x08701021 | 26        | 0.67%   |
| 0x08608103 | 25        | 0.65%   |
| 0x08600106 | 25        | 0.65%   |
| 0x906a3    | 24        | 0.62%   |
| 0x806ea    | 24        | 0.62%   |
| 0x806d1    | 24        | 0.62%   |
| 0x306a9    | 22        | 0.57%   |
| 0x906ea    | 21        | 0.54%   |
| 0x0a601203 | 21        | 0.54%   |
| 0xa0652    | 20        | 0.52%   |
| 0x0a50000d | 20        | 0.52%   |
| 0x0a404102 | 19        | 0.49%   |
| 0x08108109 | 17        | 0.44%   |
| 0x0a404101 | 16        | 0.41%   |
| 0x0800820d | 16        | 0.41%   |
| 0x806e9    | 14        | 0.36%   |
| 0x506e3    | 14        | 0.36%   |
| 0x406e3    | 14        | 0.36%   |
| 0x206a7    | 14        | 0.36%   |
| 0x0a201016 | 14        | 0.36%   |
| 0x906a4    | 13        | 0.34%   |
| 0x306c3    | 13        | 0.34%   |
| 0x40651    | 12        | 0.31%   |
| 0x0a20120a | 12        | 0.31%   |
| 0x906e9    | 11        | 0.28%   |
| 0x08600104 | 10        | 0.26%   |
| 0x306d4    | 9         | 0.23%   |
| 0x706e5    | 8         | 0.21%   |
| 0x1067a    | 8         | 0.21%   |
| 0x706a8    | 7         | 0.18%   |
| 0x08600103 | 7         | 0.18%   |
| 0x08108102 | 7         | 0.18%   |
| 0x906ec    | 5         | 0.13%   |
| 0x90672    | 5         | 0.13%   |
| 0x806eb    | 5         | 0.13%   |
| 0x0a704103 | 5         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 587       | 15.35%  |
| Unknown          | 427       | 11.16%  |
| Zen 3            | 367       | 9.59%   |
| Haswell          | 338       | 8.84%   |
| Zen 2            | 233       | 6.09%   |
| SandyBridge      | 199       | 5.2%    |
| Skylake          | 196       | 5.12%   |
| IvyBridge        | 190       | 4.97%   |
| Zen+             | 162       | 4.24%   |
| TigerLake        | 161       | 4.21%   |
| CometLake        | 125       | 3.27%   |
| Alderlake Hybrid | 106       | 2.77%   |
| Broadwell        | 103       | 2.69%   |
| Penryn           | 92        | 2.41%   |
| Zen              | 77        | 2.01%   |
| IceLake          | 70        | 1.83%   |
| Westmere         | 60        | 1.57%   |
| Piledriver       | 58        | 1.52%   |
| Goldmont plus    | 43        | 1.12%   |
| Silvermont       | 35        | 0.92%   |
| K10              | 35        | 0.92%   |
| Nehalem          | 31        | 0.81%   |
| Excavator        | 28        | 0.73%   |
| Core             | 22        | 0.58%   |
| Puma             | 17        | 0.44%   |
| Steamroller      | 15        | 0.39%   |
| K10 Llano        | 9         | 0.24%   |
| Goldmont         | 9         | 0.24%   |
| Bobcat           | 9         | 0.24%   |
| K8 Hammer        | 5         | 0.13%   |
| Jaguar           | 5         | 0.13%   |
| Tremont          | 4         | 0.1%    |
| NetBurst         | 3         | 0.08%   |
| Bulldozer        | 3         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1969      | 41.76%  |
| Nvidia                     | 1533      | 32.51%  |
| AMD                        | 1203      | 25.51%  |
| Matrox Electronics Systems | 5         | 0.11%   |
| ASPEED Technology          | 5         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 146       | 3.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 145       | 3%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 139       | 2.87%   |
| Intel UHD Graphics 620                                                      | 112       | 2.32%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 106       | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 99        | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 97        | 2%      |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 94        | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 92        | 1.9%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 85        | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 78        | 1.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 78        | 1.61%   |
| AMD Lucienne                                                                | 75        | 1.55%   |
| Intel HD Graphics 620                                                       | 70        | 1.45%   |
| AMD Rembrandt [Radeon 680M]                                                 | 67        | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 65        | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 64        | 1.32%   |
| Intel HD Graphics 5500                                                      | 61        | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 60        | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 60        | 1.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 59        | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 57        | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 57        | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 54        | 1.12%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 50        | 1.03%   |
| Intel HD Graphics 530                                                       | 49        | 1.01%   |
| AMD Raphael                                                                 | 46        | 0.95%   |
| Intel HD Graphics 630                                                       | 43        | 0.89%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 42        | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 39        | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                         | 39        | 0.81%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 37        | 0.76%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 35        | 0.72%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 35        | 0.72%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 35        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 33        | 0.68%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 31        | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30        | 0.62%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 27        | 0.56%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 26        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1277      | 33.19%  |
| 1 x AMD              | 859       | 22.32%  |
| 1 x Nvidia           | 771       | 20.04%  |
| Intel + Nvidia       | 558       | 14.5%   |
| AMD + Nvidia         | 181       | 4.7%    |
| 2 x AMD              | 83        | 2.16%   |
| Intel + AMD          | 79        | 2.05%   |
| 2 x Nvidia           | 14        | 0.36%   |
| Other                | 10        | 0.26%   |
| 1 x Matrox           | 4         | 0.1%    |
| Intel + 2 x Nvidia   | 3         | 0.08%   |
| AMD + ASPEED         | 3         | 0.08%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + Matrox      | 1         | 0.03%   |
| Nvidia + ASPEED      | 1         | 0.03%   |
| 1 x ASPEED           | 1         | 0.03%   |
| AMD + 2 x Nvidia     | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2519      | 65.33%  |
| Proprietary | 1242      | 32.21%  |
| Unknown     | 95        | 2.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3132      | 80.93%  |
| 7.01-8.0   | 141       | 3.64%   |
| 0.01-0.5   | 132       | 3.41%   |
| 1.01-2.0   | 130       | 3.36%   |
| 3.01-4.0   | 104       | 2.69%   |
| 8.01-16.0  | 89        | 2.3%    |
| 5.01-6.0   | 80        | 2.07%   |
| 0.51-1.0   | 32        | 0.83%   |
| 2.01-3.0   | 17        | 0.44%   |
| 16.01-24.0 | 12        | 0.31%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 504       | 11.38%  |
| Samsung Electronics     | 490       | 11.07%  |
| BOE                     | 428       | 9.67%   |
| Chimei Innolux          | 394       | 8.9%    |
| LG Display              | 340       | 7.68%   |
| Goldstar                | 289       | 6.53%   |
| Dell                    | 272       | 6.14%   |
| Apple                   | 160       | 3.61%   |
| Acer                    | 149       | 3.36%   |
| Hewlett-Packard         | 125       | 2.82%   |
| AOC                     | 118       | 2.66%   |
| Sharp                   | 113       | 2.55%   |
| ASUSTek Computer        | 88        | 1.99%   |
| Ancor Communications    | 82        | 1.85%   |
| BenQ                    | 81        | 1.83%   |
| Lenovo                  | 69        | 1.56%   |
| Philips                 | 63        | 1.42%   |
| PANDA                   | 58        | 1.31%   |
| InfoVision              | 42        | 0.95%   |
| Iiyama                  | 41        | 0.93%   |
| MSI                     | 36        | 0.81%   |
| ViewSonic               | 30        | 0.68%   |
| CSO                     | 28        | 0.63%   |
| Chi Mei Optoelectronics | 28        | 0.63%   |
| Gigabyte Technology     | 21        | 0.47%   |
| Sony                    | 20        | 0.45%   |
| Sceptre Tech            | 19        | 0.43%   |
| NEC Computers           | 18        | 0.41%   |
| Panasonic               | 16        | 0.36%   |
| Vizio                   | 13        | 0.29%   |
| TMX                     | 10        | 0.23%   |
| HKC                     | 10        | 0.23%   |
| Toshiba                 | 9         | 0.2%    |
| Eizo                    | 9         | 0.2%    |
| Vestel Elektronik       | 8         | 0.18%   |
| Unknown                 | 8         | 0.18%   |
| Hitachi                 | 7         | 0.16%   |
| Valve                   | 6         | 0.14%   |
| Unknown (XXX)           | 6         | 0.14%   |
| RTK                     | 6         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch   | 30        | 0.66%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch   | 25        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch   | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch     | 22        | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch            | 20        | 0.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch           | 20        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 19        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch   | 18        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch    | 15        | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch       | 13        | 0.28%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch       | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch     | 13        | 0.28%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch               | 13        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch       | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch   | 12        | 0.26%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch               | 12        | 0.26%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                   | 12        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch  | 11        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch   | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch      | 11        | 0.24%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch  | 10        | 0.22%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch         | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch    | 10        | 0.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch              | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch     | 10        | 0.22%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch  | 9         | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch            | 9         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                  | 9         | 0.2%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch     | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch     | 9         | 0.2%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch | 8         | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch        | 8         | 0.18%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch       | 8         | 0.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 8         | 0.18%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                  | 8         | 0.18%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                  | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch   | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch   | 8         | 0.18%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch              | 8         | 0.18%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch              | 8         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1980      | 47.19%  |
| 1366x768 (WXGA)    | 540       | 12.87%  |
| 3840x2160 (4K)     | 392       | 9.34%   |
| 2560x1440 (QHD)    | 300       | 7.15%   |
| 1920x1200 (WUXGA)  | 127       | 3.03%   |
| 1600x900 (HD+)     | 111       | 2.65%   |
| 3440x1440          | 98        | 2.34%   |
| 2560x1600          | 74        | 1.76%   |
| 2560x1080          | 74        | 1.76%   |
| 1440x900 (WXGA+)   | 67        | 1.6%    |
| 1680x1050 (WSXGA+) | 59        | 1.41%   |
| 2880x1800          | 53        | 1.26%   |
| 1280x800 (WXGA)    | 47        | 1.12%   |
| 1280x1024 (SXGA)   | 47        | 1.12%   |
| 3840x1080          | 27        | 0.64%   |
| 3840x2400          | 21        | 0.5%    |
| 1360x768           | 21        | 0.5%    |
| 1920x540           | 15        | 0.36%   |
| 2160x1440          | 14        | 0.33%   |
| 3072x1920          | 12        | 0.29%   |
| 1920x1280          | 10        | 0.24%   |
| Unknown            | 10        | 0.24%   |
| 3840x1600          | 9         | 0.21%   |
| 2736x1824          | 9         | 0.21%   |
| 2256x1504          | 9         | 0.21%   |
| 3200x1800 (QHD+)   | 7         | 0.17%   |
| 1024x768 (XGA)     | 6         | 0.14%   |
| 3456x2160          | 5         | 0.12%   |
| 3200x2000          | 5         | 0.12%   |
| 1600x1200          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 3000x2000          | 4         | 0.1%    |
| 2880x1620          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 3840x1100          | 3         | 0.07%   |
| 800x1280           | 2         | 0.05%   |
| 4480x1440          | 2         | 0.05%   |
| 2520x1680          | 2         | 0.05%   |
| 2304x1440          | 2         | 0.05%   |
| 5120x1440          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1082      | 24.42%  |
| 13      | 472       | 10.65%  |
| 27      | 434       | 9.8%    |
| 14      | 348       | 7.86%   |
| 24      | 335       | 7.56%   |
| 23      | 257       | 5.8%    |
| 17      | 198       | 4.47%   |
| 21      | 190       | 4.29%   |
| 31      | 182       | 4.11%   |
| 34      | 149       | 3.36%   |
| 16      | 94        | 2.12%   |
| 12      | 71        | 1.6%    |
| 19      | 62        | 1.4%    |
| Unknown | 62        | 1.4%    |
| 84      | 45        | 1.02%   |
| 32      | 44        | 0.99%   |
| 22      | 44        | 0.99%   |
| 18      | 43        | 0.97%   |
| 20      | 40        | 0.9%    |
| 11      | 29        | 0.65%   |
| 72      | 28        | 0.63%   |
| 48      | 27        | 0.61%   |
| 28      | 22        | 0.5%    |
| 40      | 20        | 0.45%   |
| 54      | 19        | 0.43%   |
| 25      | 14        | 0.32%   |
| 37      | 13        | 0.29%   |
| 26      | 12        | 0.27%   |
| 35      | 11        | 0.25%   |
| 29      | 9         | 0.2%    |
| 65      | 7         | 0.16%   |
| 52      | 7         | 0.16%   |
| 49      | 7         | 0.16%   |
| 33      | 7         | 0.16%   |
| 46      | 5         | 0.11%   |
| 42      | 5         | 0.11%   |
| 36      | 4         | 0.09%   |
| 74      | 3         | 0.07%   |
| 57      | 3         | 0.07%   |
| 44      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1730      | 39.99%  |
| 501-600     | 915       | 21.15%  |
| 201-300     | 358       | 8.28%   |
| 401-500     | 344       | 7.95%   |
| 601-700     | 267       | 6.17%   |
| 351-400     | 226       | 5.22%   |
| 701-800     | 197       | 4.55%   |
| 1001-1500   | 83        | 1.92%   |
| 1501-2000   | 81        | 1.87%   |
| Unknown     | 62        | 1.43%   |
| 801-900     | 51        | 1.18%   |
| 901-1000    | 8         | 0.18%   |
| 101-200     | 2         | 0.05%   |
| 1-100       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3047      | 77.75%  |
| 16/10   | 502       | 12.81%  |
| 21/9    | 182       | 4.64%   |
| 3/2     | 49        | 1.25%   |
| 5/4     | 48        | 1.22%   |
| 32/9    | 32        | 0.82%   |
| Unknown | 27        | 0.69%   |
| 4/3     | 21        | 0.54%   |
| 3.40    | 3         | 0.08%   |
| 6/5     | 2         | 0.05%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.89    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.63    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1085      | 24.77%  |
| 201-250        | 648       | 14.79%  |
| 81-90          | 625       | 14.27%  |
| 301-350        | 448       | 10.23%  |
| 351-500        | 402       | 9.18%   |
| 71-80          | 195       | 4.45%   |
| 121-130        | 162       | 3.7%    |
| 151-200        | 148       | 3.38%   |
| More than 1000 | 127       | 2.9%    |
| 251-300        | 123       | 2.81%   |
| 111-120        | 85        | 1.94%   |
| 501-1000       | 83        | 1.89%   |
| 141-150        | 67        | 1.53%   |
| Unknown        | 62        | 1.42%   |
| 61-70          | 56        | 1.28%   |
| 51-60          | 32        | 0.73%   |
| 131-140        | 14        | 0.32%   |
| 91-100         | 14        | 0.32%   |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1352      | 31.95%  |
| 51-100        | 1252      | 29.58%  |
| 101-120       | 949       | 22.42%  |
| 161-240       | 374       | 8.84%   |
| More than 240 | 149       | 3.52%   |
| 1-50          | 94        | 2.22%   |
| Unknown       | 62        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2932      | 75.51%  |
| 2     | 715       | 18.41%  |
| 0     | 121       | 3.12%   |
| 3     | 104       | 2.68%   |
| 4     | 10        | 0.26%   |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2054      | 35.35%  |
| Intel                             | 2004      | 34.49%  |
| Qualcomm Atheros                  | 515       | 8.86%   |
| Broadcom                          | 315       | 5.42%   |
| MediaTek                          | 202       | 3.48%   |
| Broadcom Limited                  | 93        | 1.6%    |
| TP-Link                           | 60        | 1.03%   |
| ASIX Electronics                  | 48        | 0.83%   |
| Marvell Technology Group          | 42        | 0.72%   |
| Ralink Technology                 | 37        | 0.64%   |
| Nvidia                            | 37        | 0.64%   |
| Samsung Electronics               | 34        | 0.59%   |
| Ralink                            | 32        | 0.55%   |
| NetGear                           | 25        | 0.43%   |
| Aquantia                          | 22        | 0.38%   |
| Xiaomi                            | 21        | 0.36%   |
| DisplayLink                       | 20        | 0.34%   |
| Microsoft                         | 19        | 0.33%   |
| Dell                              | 17        | 0.29%   |
| Qualcomm                          | 16        | 0.28%   |
| Google                            | 14        | 0.24%   |
| Sierra Wireless                   | 13        | 0.22%   |
| InterBiometrics                   | 13        | 0.22%   |
| ASUSTek Computer                  | 13        | 0.22%   |
| Lenovo                            | 12        | 0.21%   |
| Qualcomm Atheros Communications   | 10        | 0.17%   |
| Linksys                           | 10        | 0.17%   |
| OPPO Electronics                  | 9         | 0.15%   |
| D-Link                            | 9         | 0.15%   |
| JMicron Technology                | 8         | 0.14%   |
| Hewlett-Packard                   | 8         | 0.14%   |
| D-Link System                     | 7         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.1%    |
| Huawei Technologies               | 6         | 0.1%    |
| Ericsson Business Mobile Networks | 5         | 0.09%   |
| Motorola PCS                      | 4         | 0.07%   |
| Mellanox Technologies             | 4         | 0.07%   |
| Edimax Technology                 | 4         | 0.07%   |
| Fibocom                           | 3         | 0.05%   |
| Apple                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 1309      | 19.02%  |
| Intel Wi-Fi 6 AX200                                                  | 303       | 4.4%    |
| Realtek RTL8125 2.5GbE Controller                                    | 204       | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 152       | 2.21%   |
| Intel I211 Gigabit Network Connection                                | 148       | 2.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 136       | 1.98%   |
| Intel Wireless 8265 / 8275                                           | 133       | 1.93%   |
| Intel Ethernet Controller I225-V                                     | 130       | 1.89%   |
| Intel Wi-Fi 6 AX201                                                  | 128       | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 114       | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 91        | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 90        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 89        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 84        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 81        | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 79        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 74        | 1.08%   |
| Intel Wireless 7265                                                  | 70        | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 69        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                       | 69        | 1%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 68        | 0.99%   |
| Intel Wireless 8260                                                  | 65        | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 65        | 0.94%   |
| Intel Wireless 7260                                                  | 61        | 0.89%   |
| Intel Ethernet Connection I217-LM                                    | 61        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 60        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 58        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 57        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 53        | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 52        | 0.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 52        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                 | 49        | 0.71%   |
| Intel Wireless-AC 9260                                               | 45        | 0.65%   |
| Realtek 802.11ac NIC                                                 | 44        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 44        | 0.64%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 43        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 42        | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 41        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                        | 39        | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 38        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1629      | 48.11%  |
| Realtek Semiconductor                 | 526       | 15.53%  |
| Qualcomm Atheros                      | 409       | 12.08%  |
| Broadcom                              | 247       | 7.29%   |
| MediaTek                              | 201       | 5.94%   |
| Broadcom Limited                      | 80        | 2.36%   |
| TP-Link                               | 52        | 1.54%   |
| Ralink Technology                     | 37        | 1.09%   |
| Ralink                                | 32        | 0.95%   |
| NetGear                               | 25        | 0.74%   |
| Microsoft                             | 19        | 0.56%   |
| Dell                                  | 16        | 0.47%   |
| Marvell Technology Group              | 15        | 0.44%   |
| Qualcomm                              | 14        | 0.41%   |
| Sierra Wireless                       | 13        | 0.38%   |
| ASUSTek Computer                      | 11        | 0.32%   |
| Qualcomm Atheros Communications       | 10        | 0.3%    |
| Linksys                               | 10        | 0.3%    |
| D-Link                                | 8         | 0.24%   |
| D-Link System                         | 6         | 0.18%   |
| Hewlett-Packard                       | 4         | 0.12%   |
| Edimax Technology                     | 4         | 0.12%   |
| Fibocom                               | 3         | 0.09%   |
| Belkin Components                     | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| Accton Technology                     | 2         | 0.06%   |
| ZyDAS                                 | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| Ericsson Business Mobile Networks     | 1         | 0.03%   |
| Arduino SA                            | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 303       | 8.89%   |
| Intel Wireless 8265 / 8275                                           | 133       | 3.9%    |
| Intel Wi-Fi 6 AX201                                                  | 128       | 3.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 114       | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 90        | 2.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 89        | 2.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 84        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 81        | 2.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 79        | 2.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 74        | 2.17%   |
| Intel Wireless 7265                                                  | 70        | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 69        | 2.02%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 69        | 2.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 68        | 2%      |
| Intel Wireless 8260                                                  | 65        | 1.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 65        | 1.91%   |
| Intel Wireless 7260                                                  | 61        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 60        | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 58        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 57        | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 53        | 1.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 52        | 1.53%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 52        | 1.53%   |
| Intel Wireless-AC 9260                                               | 45        | 1.32%   |
| Realtek 802.11ac NIC                                                 | 44        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 44        | 1.29%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 43        | 1.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 42        | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 41        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 38        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 31        | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 29        | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 29        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                        | 29        | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 27        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 26        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 24        | 0.7%    |
| Intel Wireless 3165                                                  | 23        | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 22        | 0.65%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 21        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1818      | 54.51%  |
| Intel                         | 937       | 28.1%   |
| Qualcomm Atheros              | 148       | 4.44%   |
| Broadcom                      | 137       | 4.11%   |
| ASIX Electronics              | 48        | 1.44%   |
| Nvidia                        | 37        | 1.11%   |
| Marvell Technology Group      | 27        | 0.81%   |
| Aquantia                      | 22        | 0.66%   |
| Xiaomi                        | 21        | 0.63%   |
| Samsung Electronics           | 21        | 0.63%   |
| DisplayLink                   | 20        | 0.6%    |
| Google                        | 14        | 0.42%   |
| Broadcom Limited              | 13        | 0.39%   |
| Lenovo                        | 12        | 0.36%   |
| OPPO Electronics              | 9         | 0.27%   |
| TP-Link                       | 8         | 0.24%   |
| JMicron Technology            | 8         | 0.24%   |
| OnePlus Technology (Shenzhen) | 5         | 0.15%   |
| Huawei Technologies           | 5         | 0.15%   |
| Motorola PCS                  | 3         | 0.09%   |
| Mellanox Technologies         | 3         | 0.09%   |
| Hewlett-Packard               | 3         | 0.09%   |
| Qualcomm                      | 2         | 0.06%   |
| ICS Advent                    | 2         | 0.06%   |
| ASUSTek Computer              | 2         | 0.06%   |
| Apple                         | 2         | 0.06%   |
| American Megatrends           | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.03%   |
| VIA Technologies              | 1         | 0.03%   |
| T & A Mobile Phones           | 1         | 0.03%   |
| Insyde Software               | 1         | 0.03%   |
| D-Link System                 | 1         | 0.03%   |
| D-Link                        | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1309      | 38.31%  |
| Realtek RTL8125 2.5GbE Controller                                 | 204       | 5.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 152       | 4.45%   |
| Intel I211 Gigabit Network Connection                             | 148       | 4.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 136       | 3.98%   |
| Intel Ethernet Controller I225-V                                  | 130       | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 91        | 2.66%   |
| Intel Ethernet Connection I217-LM                                 | 61        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 49        | 1.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 39        | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 38        | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 33        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 30        | 0.88%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 28        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 25        | 0.73%   |
| Nvidia MCP79 Ethernet                                             | 24        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 22        | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 22        | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.59%   |
| Intel I210 Gigabit Network Connection                             | 20        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.47%   |
| Realtek Killer E3000 2.5GbE Controller                            | 15        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 14        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                             | 13        | 0.38%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.38%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.38%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.35%   |
| Intel Ethernet Connection (16) I219-V                             | 12        | 0.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 11        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3208      | 50.34%  |
| Ethernet | 3109      | 48.78%  |
| Modem    | 43        | 0.67%   |
| Unknown  | 13        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2490      | 61.42%  |
| Ethernet | 1563      | 38.55%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2133      | 55.87%  |
| 1     | 1522      | 39.86%  |
| 3     | 108       | 2.83%   |
| 0     | 41        | 1.07%   |
| 4     | 11        | 0.29%   |
| 5     | 3         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2669      | 68.9%   |
| Yes  | 1205      | 31.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1455      | 51.74%  |
| Realtek Semiconductor           | 274       | 9.74%   |
| Apple                           | 193       | 6.86%   |
| Qualcomm Atheros Communications | 184       | 6.54%   |
| IMC Networks                    | 133       | 4.73%   |
| Cambridge Silicon Radio         | 116       | 4.13%   |
| Foxconn / Hon Hai               | 107       | 3.81%   |
| Lite-On Technology              | 73        | 2.6%    |
| Broadcom                        | 59        | 2.1%    |
| MediaTek                        | 50        | 1.78%   |
| ASUSTek Computer                | 36        | 1.28%   |
| Dell                            | 19        | 0.68%   |
| TP-Link                         | 15        | 0.53%   |
| Realtek                         | 15        | 0.53%   |
| Marvell Semiconductor           | 15        | 0.53%   |
| Toshiba                         | 12        | 0.43%   |
| Hewlett-Packard                 | 9         | 0.32%   |
| Ralink                          | 8         | 0.28%   |
| Dynex                           | 6         | 0.21%   |
| Actions                         | 5         | 0.18%   |
| Opticis                         | 3         | 0.11%   |
| Micro Star International        | 3         | 0.11%   |
| Integrated System Solution      | 3         | 0.11%   |
| Foxconn International           | 3         | 0.11%   |
| USI                             | 2         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Fujitsu                         | 2         | 0.07%   |
| Edimax Technology               | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 346       | 12.3%   |
| Intel AX201 Bluetooth                               | 319       | 11.34%  |
| Intel AX200 Bluetooth                               | 286       | 10.16%  |
| Realtek Bluetooth Radio                             | 166       | 5.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 159       | 5.65%   |
| Intel Bluetooth Device                              | 131       | 4.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 116       | 4.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 101       | 3.59%   |
| Apple Bluetooth Host Controller                     | 99        | 3.52%   |
| Intel AX210 Bluetooth                               | 72        | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 62        | 2.2%    |
| IMC Networks Wireless_Device                        | 59        | 2.1%    |
| Apple Bluetooth USB Host Controller                 | 59        | 2.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 52        | 1.85%   |
| MediaTek Wireless_Device                            | 50        | 1.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 1.42%   |
| Realtek 802.11ac WLAN Adapter                       | 37        | 1.31%   |
| IMC Networks Bluetooth Radio                        | 33        | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 29        | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 0.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 23        | 0.82%   |
| IMC Networks Bluetooth Device                       | 22        | 0.78%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 0.68%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 16        | 0.57%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 16        | 0.57%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 15        | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 0.53%   |
| Lite-On Wireless_Device                             | 15        | 0.53%   |
| Lite-On Bluetooth Device                            | 15        | 0.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.53%   |
| ASUS ASUS USB-BT500                                 | 13        | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 12        | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 12        | 0.43%   |
| Apple Bluetooth HCI                                 | 12        | 0.43%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 0.39%   |
| Lite-On Bluetooth Radio                             | 10        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2492      | 41.67%  |
| AMD                                  | 1415      | 23.66%  |
| Nvidia                               | 1232      | 20.6%   |
| C-Media Electronics                  | 104       | 1.74%   |
| Logitech                             | 66        | 1.1%    |
| Kingston Technology                  | 45        | 0.75%   |
| Razer USA                            | 37        | 0.62%   |
| ASUSTek Computer                     | 33        | 0.55%   |
| JMTek                                | 31        | 0.52%   |
| Focusrite-Novation                   | 31        | 0.52%   |
| Generalplus Technology               | 29        | 0.48%   |
| Creative Labs                        | 29        | 0.48%   |
| Micro Star International             | 25        | 0.42%   |
| SteelSeries ApS                      | 24        | 0.4%    |
| GN Netcom                            | 23        | 0.38%   |
| Corsair                              | 21        | 0.35%   |
| Lenovo                               | 19        | 0.32%   |
| Texas Instruments                    | 18        | 0.3%    |
| Realtek Semiconductor                | 18        | 0.3%    |
| Creative Technology                  | 15        | 0.25%   |
| Sony                                 | 13        | 0.22%   |
| Blue Microphones                     | 13        | 0.22%   |
| Plantronics                          | 12        | 0.2%    |
| Apple                                | 12        | 0.2%    |
| DSEA A/S                             | 11        | 0.18%   |
| Hewlett-Packard                      | 10        | 0.17%   |
| Valve Software                       | 6         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 6         | 0.1%    |
| Giga-Byte Technology                 | 6         | 0.1%    |
| Dell                                 | 6         | 0.1%    |
| Astro Gaming                         | 6         | 0.1%    |
| Tenx Technology                      | 5         | 0.08%   |
| FiiO Electronics Technology          | 5         | 0.08%   |
| DCMT Technology                      | 5         | 0.08%   |
| BEHRINGER International              | 5         | 0.08%   |
| Yamaha                               | 4         | 0.07%   |
| Trust                                | 4         | 0.07%   |
| Samson Technologies                  | 4         | 0.07%   |
| Medeli Electronics                   | 4         | 0.07%   |
| Mackie Designs                       | 4         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 624       | 8.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 327       | 4.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 294       | 4.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 279       | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 193       | 2.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 188       | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 177       | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 161       | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 148       | 2.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 140       | 1.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 133       | 1.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 130       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 119       | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 119       | 1.64%   |
| Nvidia Audio device                                                        | 118       | 1.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 115       | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 100       | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 98        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 97        | 1.34%   |
| Nvidia GA106 High Definition Audio Controller                              | 96        | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 95        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 92        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 92        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 90        | 1.24%   |
| Nvidia TU116 High Definition Audio Controller                              | 84        | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 84        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 80        | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 79        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                               | 77        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 73        | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                              | 71        | 0.98%   |
| AMD FCH Azalia Controller                                                  | 71        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 70        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 70        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 68        | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 68        | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 67        | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 63        | 0.87%   |
| Nvidia GA102 High Definition Audio Controller                              | 55        | 0.76%   |
| Nvidia TU104 HD Audio Controller                                           | 51        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 300       | 24.08%  |
| SK hynix                                | 240       | 19.26%  |
| Micron Technology                       | 164       | 13.16%  |
| Kingston                                | 103       | 8.27%   |
| Corsair                                 | 93        | 7.46%   |
| Crucial                                 | 75        | 6.02%   |
| G.Skill                                 | 60        | 4.82%   |
| Unknown                                 | 29        | 2.33%   |
| Team                                    | 27        | 2.17%   |
| A-DATA Technology                       | 22        | 1.77%   |
| Unknown                                 | 22        | 1.77%   |
| Smart                                   | 14        | 1.12%   |
| Ramaxel Technology                      | 11        | 0.88%   |
| Unknown (ABCD)                          | 10        | 0.8%    |
| Neo Forza                               | 10        | 0.8%    |
| Goldkey                                 | 10        | 0.8%    |
| Elpida                                  | 10        | 0.8%    |
| PNY                                     | 4         | 0.32%   |
| Patriot                                 | 4         | 0.32%   |
| Nanya Technology                        | 4         | 0.32%   |
| Teikon                                  | 3         | 0.24%   |
| GSkill                                  | 3         | 0.24%   |
| Avant                                   | 3         | 0.24%   |
| Transcend                               | 2         | 0.16%   |
| Smart Brazil                            | 2         | 0.16%   |
| Gold Key                                | 2         | 0.16%   |
| ChangXin Memory                         | 2         | 0.16%   |
| Apacer                                  | 2         | 0.16%   |
| Wilk                                    | 1         | 0.08%   |
| Unknown (8A02)                          | 1         | 0.08%   |
| Unknown (0x0CAB)                        | 1         | 0.08%   |
| Unknown (09B6)                          | 1         | 0.08%   |
| Unknown (09A4)                          | 1         | 0.08%   |
| Timetec                                 | 1         | 0.08%   |
| Silicon Power Computer & Communications | 1         | 0.08%   |
| Patriot Memory (PDP Systems)            | 1         | 0.08%   |
| Patriot Memory                          | 1         | 0.08%   |
| Kllisre                                 | 1         | 0.08%   |
| Juhor                                   | 1         | 0.08%   |
| GeIL                                    | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 23        | 1.76%   |
| Unknown                                                           | 22        | 1.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 20        | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 15        | 1.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 15        | 1.15%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s              | 14        | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 12        | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 11        | 0.84%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 11        | 0.84%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 11        | 0.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 10        | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 10        | 0.76%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s            | 10        | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 9         | 0.69%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 9         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 8         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 8         | 0.61%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 8         | 0.61%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                | 8         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s               | 7         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 7         | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 7         | 0.53%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s             | 6         | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 6         | 0.46%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s            | 6         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 6         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 6         | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s          | 6         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.46%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s  | 6         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s              | 6         | 0.46%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s             | 6         | 0.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 6         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 6         | 0.46%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s            | 6         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 5         | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 5         | 0.38%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 698       | 64.1%   |
| DDR3    | 158       | 14.51%  |
| DDR5    | 84        | 7.71%   |
| LPDDR4  | 61        | 5.6%    |
| LPDDR5  | 44        | 4.04%   |
| LPDDR3  | 27        | 2.48%   |
| DDR2    | 9         | 0.83%   |
| SDRAM   | 5         | 0.46%   |
| Unknown | 3         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 676       | 61.12%  |
| DIMM         | 273       | 24.68%  |
| Row Of Chips | 149       | 13.47%  |
| Chip         | 5         | 0.45%   |
| Unknown      | 3         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 513       | 43.96%  |
| 16384 | 287       | 24.59%  |
| 4096  | 221       | 18.94%  |
| 32768 | 94        | 8.05%   |
| 2048  | 46        | 3.94%   |
| 1024  | 6         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 324       | 27.79%  |
| 2667  | 191       | 16.38%  |
| 1600  | 119       | 10.21%  |
| 2400  | 68        | 5.83%   |
| 4800  | 57        | 4.89%   |
| 3600  | 53        | 4.55%   |
| 6400  | 45        | 3.86%   |
| 2133  | 44        | 3.77%   |
| 4267  | 36        | 3.09%   |
| 3733  | 19        | 1.63%   |
| 3800  | 17        | 1.46%   |
| 1867  | 16        | 1.37%   |
| 1333  | 16        | 1.37%   |
| 3266  | 13        | 1.11%   |
| 5600  | 12        | 1.03%   |
| 1334  | 10        | 0.86%   |
| 3533  | 9         | 0.77%   |
| 8400  | 8         | 0.69%   |
| 2933  | 8         | 0.69%   |
| 1067  | 8         | 0.69%   |
| 800   | 8         | 0.69%   |
| 6000  | 7         | 0.6%    |
| 4266  | 6         | 0.51%   |
| 3534  | 6         | 0.51%   |
| 3400  | 6         | 0.51%   |
| 3000  | 6         | 0.51%   |
| 5200  | 5         | 0.43%   |
| 2666  | 5         | 0.43%   |
| 2800  | 4         | 0.34%   |
| 1866  | 4         | 0.34%   |
| 4000  | 3         | 0.26%   |
| 3866  | 3         | 0.26%   |
| 667   | 3         | 0.26%   |
| 4400  | 2         | 0.17%   |
| 4199  | 2         | 0.17%   |
| 3666  | 2         | 0.17%   |
| 3466  | 2         | 0.17%   |
| 3333  | 2         | 0.17%   |
| 3100  | 2         | 0.17%   |
| 2048  | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 32.81%  |
| Canon               | 10        | 15.63%  |
| Brother Industries  | 10        | 15.63%  |
| Samsung Electronics | 7         | 10.94%  |
| Seiko Epson         | 5         | 7.81%   |
| Dymo-CoStar         | 4         | 6.25%   |
| STMicroelectronics  | 2         | 3.13%   |
| Xerox               | 1         | 1.56%   |
| QinHeng Electronics | 1         | 1.56%   |
| Prolific Technology | 1         | 1.56%   |
| ICS Advent          | 1         | 1.56%   |
| Dell                | 1         | 1.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450                               | 3         | 4.62%   |
| Brother HL-2130 series                                    | 3         | 4.62%   |
| Seiko Epson WF-4830 Series                                | 2         | 3.08%   |
| HP ENVY Pro 6400 series                                   | 2         | 3.08%   |
| Canon PIXMA MX920 Series                                  | 2         | 3.08%   |
| Xerox B215                                                | 1         | 1.54%   |
| STMicroelectronics USB Printer P                          | 1         | 1.54%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.54%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 1.54%   |
| Seiko Epson L382 Series                                   | 1         | 1.54%   |
| Seiko Epson ET-2800 Series                                | 1         | 1.54%   |
| Samsung SCX-4500 Laser Printer                            | 1         | 1.54%   |
| Samsung SCX-3400 Series                                   | 1         | 1.54%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.54%   |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 1.54%   |
| Samsung M2070 Series                                      | 1         | 1.54%   |
| Samsung M2020 Series                                      | 1         | 1.54%   |
| Samsung C460 Series                                       | 1         | 1.54%   |
| QinHeng CH340S                                            | 1         | 1.54%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.54%   |
| ICS Advent Parallel Adapter                               | 1         | 1.54%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.54%   |
| HP OfficeJet Pro 9010 series                              | 1         | 1.54%   |
| HP OfficeJet 3830 series                                  | 1         | 1.54%   |
| HP LaserJet Professional P1102w                           | 1         | 1.54%   |
| HP LaserJet Professional P 1102w                          | 1         | 1.54%   |
| HP LaserJet Pro M201dw                                    | 1         | 1.54%   |
| HP LaserJet Pro M118-M119                                 | 1         | 1.54%   |
| HP LaserJet P2035                                         | 1         | 1.54%   |
| HP LaserJet M203-M206                                     | 1         | 1.54%   |
| HP LaserJet 3050                                          | 1         | 1.54%   |
| HP LaserJet 1018                                          | 1         | 1.54%   |
| HP LaserJet 1010                                          | 1         | 1.54%   |
| HP Ink Tank Wireless 410 series                           | 1         | 1.54%   |
| HP Ink Tank 110 series                                    | 1         | 1.54%   |
| HP ENVY 5000 series                                       | 1         | 1.54%   |
| HP Deskjet F2280 series                                   | 1         | 1.54%   |
| HP Deskjet 3520 series                                    | 1         | 1.54%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.54%   |
| HP Color LaserJet CP2025dn                                | 1         | 1.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 4         | 36.36%  |
| Canon           | 4         | 36.36%  |
| Hewlett-Packard | 2         | 18.18%  |
| Mustek Systems  | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 9.09%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 9.09%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 9.09%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 9.09%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 9.09%   |
| HP Scanjet G2710                                        | 1         | 9.09%   |
| HP ScanJet 82x0C                                        | 1         | 9.09%   |
| Canon CanoScan N650U/N656U                              | 1         | 9.09%   |
| Canon CanoScan LiDE 60                                  | 1         | 9.09%   |
| Canon CanoScan LiDE 200                                 | 1         | 9.09%   |
| Canon CanoScan 9000F Mark II                            | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 469       | 18.79%  |
| IMC Networks                           | 240       | 9.62%   |
| Microdia                               | 232       | 9.29%   |
| Realtek Semiconductor                  | 171       | 6.85%   |
| Bison Electronics                      | 169       | 6.77%   |
| Logitech                               | 151       | 6.05%   |
| Apple                                  | 143       | 5.73%   |
| Quanta                                 | 138       | 5.53%   |
| Sunplus Innovation Technology          | 123       | 4.93%   |
| Luxvisions Innotech Limited            | 73        | 2.92%   |
| Acer                                   | 67        | 2.68%   |
| Syntek                                 | 61        | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 61        | 2.44%   |
| Lite-On Technology                     | 43        | 1.72%   |
| Suyin                                  | 30        | 1.2%    |
| Sonix Technology                       | 29        | 1.16%   |
| Microsoft                              | 28        | 1.12%   |
| Samsung Electronics                    | 26        | 1.04%   |
| Silicon Motion                         | 23        | 0.92%   |
| SunplusIT                              | 18        | 0.72%   |
| Razer USA                              | 12        | 0.48%   |
| Alcor Micro                            | 12        | 0.48%   |
| Z-Star Microelectronics                | 10        | 0.4%    |
| Generalplus Technology                 | 10        | 0.4%    |
| Jieli Technology                       | 7         | 0.28%   |
| Creative Technology                    | 7         | 0.28%   |
| ARC International                      | 7         | 0.28%   |
| Ricoh                                  | 6         | 0.24%   |
| Primax Electronics                     | 6         | 0.24%   |
| Valve Software                         | 5         | 0.2%    |
| MacroSilicon                           | 5         | 0.2%    |
| Lenovo                                 | 5         | 0.2%    |
| icSpring                               | 5         | 0.2%    |
| AVerMedia Technologies                 | 5         | 0.2%    |
| Trust                                  | 4         | 0.16%   |
| Shinetech                              | 4         | 0.16%   |
| OmniVision Technologies                | 4         | 0.16%   |
| LG Electronics                         | 4         | 0.16%   |
| Hewlett-Packard                        | 4         | 0.16%   |
| Cubeternet                             | 4         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 110       | 4.36%   |
| Microdia Integrated_Webcam_HD                       | 107       | 4.24%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 89        | 3.53%   |
| Realtek Integrated_Webcam_HD                        | 72        | 2.85%   |
| IMC Networks Integrated Camera                      | 61        | 2.42%   |
| Chicony HD Webcam                                   | 54        | 2.14%   |
| Bison Integrated Camera                             | 49        | 1.94%   |
| Syntek Integrated Camera                            | 47        | 1.86%   |
| Apple Built-in iSight                               | 39        | 1.55%   |
| Acer BisonCam,NB Pro                                | 39        | 1.55%   |
| Apple FaceTime HD Camera (Built-in)                 | 37        | 1.47%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 36        | 1.43%   |
| Bison HD Webcam                                     | 34        | 1.35%   |
| Logitech Webcam C270                                | 32        | 1.27%   |
| Sunplus Integrated_Webcam_HD                        | 31        | 1.23%   |
| Quanta HD User Facing                               | 28        | 1.11%   |
| Logitech HD Pro Webcam C920                         | 27        | 1.07%   |
| Samsung Galaxy series, misc. (MTP mode)             | 26        | 1.03%   |
| Apple FaceTime HD Camera                            | 26        | 1.03%   |
| Quanta HP HD Camera                                 | 25        | 0.99%   |
| Chicony HP HD Camera                                | 25        | 0.99%   |
| Sonix USB2.0 HD UVC WebCam                          | 21        | 0.83%   |
| Chicony USB2.0 Camera                               | 20        | 0.79%   |
| Chicony HD User Facing                              | 20        | 0.79%   |
| Realtek USB Camera                                  | 19        | 0.75%   |
| Lite-On Integrated Camera                           | 18        | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 0.71%   |
| Quanta HP TrueVision HD Camera                      | 17        | 0.67%   |
| Microdia Webcam Vitade AF                           | 17        | 0.67%   |
| Chicony Chicony USB2.0 Camera                       | 17        | 0.67%   |
| Microdia Integrated Webcam                          | 16        | 0.63%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 15        | 0.59%   |
| Chicony HP Wide Vision HD Camera                    | 15        | 0.59%   |
| Luxvisions Innotech Limited HP HD Camera            | 14        | 0.55%   |
| Logitech C920 PRO HD Webcam                         | 14        | 0.55%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.55%   |
| Chicony Integrated Camera (1280x720@30)             | 14        | 0.55%   |
| Chicony HP Truevision HD camera                     | 14        | 0.55%   |
| Realtek Integrated Webcam                           | 13        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 161       | 36.26%  |
| Validity Sensors                   | 115       | 25.9%   |
| Shenzhen Goodix Technology         | 85        | 19.14%  |
| Elan Microelectronics              | 28        | 6.31%   |
| LighTuning Technology              | 17        | 3.83%   |
| Upek                               | 15        | 3.38%   |
| AuthenTec                          | 8         | 1.8%    |
| Realtek USB2.0 Finger Print Bridge | 5         | 1.13%   |
| Focal-systems.Corp                 | 5         | 1.13%   |
| HOLTEK                             | 3         | 0.68%   |
| Samsung Electronics                | 1         | 0.23%   |
| DigitalPersona                     | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 39        | 8.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 6.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 5.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 5.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.28%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 3.6%    |
| Elan ELAN:ARM-M4                                                           | 16        | 3.6%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 14        | 3.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 2.7%    |
| Synaptics WBDI Device                                                      | 11        | 2.48%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.48%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 10        | 2.25%   |
| Synaptics UWP WBDI                                                         | 10        | 2.25%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.03%   |
| Synaptics WBDI                                                             | 9         | 2.03%   |
| Synaptics  WBDI                                                            | 9         | 2.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 1.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1.58%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.58%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.58%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.35%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.35%   |
| Synaptics UWP WBDI Device                                                  | 6         | 1.35%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.35%   |
| Synaptics TouchPad                                                         | 5         | 1.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.13%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 1.13%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.13%   |
| Unknown                                                                    | 5         | 1.13%   |
| Validity Sensors VFS491                                                    | 4         | 0.9%    |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.68%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.68%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.68%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 76        | 52.78%  |
| Alcor Micro           | 43        | 29.86%  |
| O2 Micro              | 9         | 6.25%   |
| Lenovo                | 5         | 3.47%   |
| Upek                  | 4         | 2.78%   |
| OmniKey               | 2         | 1.39%   |
| SCM Microsystems      | 1         | 0.69%   |
| Realtek Semiconductor | 1         | 0.69%   |
| Gemalto (was Gemplus) | 1         | 0.69%   |
| Clay Logic            | 1         | 0.69%   |
| Advanced Card Systems | 1         | 0.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 42        | 29.17%  |
| Broadcom 58200                                                               | 27        | 18.75%  |
| Broadcom 5880                                                                | 21        | 14.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 6.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.47%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.78%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.69%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.69%   |
| OmniKey CardMan 4321                                                         | 1         | 0.69%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.69%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.69%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.69%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2592      | 66.74%  |
| 1     | 1054      | 27.14%  |
| 2     | 203       | 5.23%   |
| 3     | 27        | 0.7%    |
| 4     | 6         | 0.15%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 431       | 28.36%  |
| Net/wireless             | 224       | 14.74%  |
| Multimedia controller    | 218       | 14.34%  |
| Graphics card            | 212       | 13.95%  |
| Chipcard                 | 136       | 8.95%   |
| Bluetooth                | 84        | 5.53%   |
| Camera                   | 55        | 3.62%   |
| Sound                    | 30        | 1.97%   |
| Unassigned class         | 29        | 1.91%   |
| Communication controller | 23        | 1.51%   |
| Net/ethernet             | 21        | 1.38%   |
| Network                  | 13        | 0.86%   |
| Storage                  | 11        | 0.72%   |
| Card reader              | 10        | 0.66%   |
| Modem                    | 8         | 0.53%   |
| Storage/raid             | 6         | 0.39%   |
| Storage/ide              | 4         | 0.26%   |
| Storage/nvme             | 3         | 0.2%    |
| Wireless                 | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

